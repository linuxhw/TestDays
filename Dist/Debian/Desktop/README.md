Debian - Tested Hardware & Statistics (Desktops)
------------------------------------------------

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

Total: 3912

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | 2A9C                        | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [d3d117cf14](https://linux-hardware.org/?probe=d3d117cf14) | Oct 01, 2022 |
| MSI           | X470 GAMING PRO             | [53e99a8ce6](https://linux-hardware.org/?probe=53e99a8ce6) | Oct 01, 2022 |
| Dell          | 0KJCC5 A00                  | [7915b298b2](https://linux-hardware.org/?probe=7915b298b2) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Gigabyte      | H81M-D2V                    | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| HP            | 859C                        | [08161b9516](https://linux-hardware.org/?probe=08161b9516) | Sep 30, 2022 |
| ASRock        | X570 Steel Legend           | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| ECS           | G31T-M9                     | [45b25aaf8c](https://linux-hardware.org/?probe=45b25aaf8c) | Sep 29, 2022 |
| Biostar       | H55 HD                      | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| BESSTAR Te... | TH50                        | [2045e665b1](https://linux-hardware.org/?probe=2045e665b1) | Sep 28, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| HP            | 339A                        | [5c961ef93f](https://linux-hardware.org/?probe=5c961ef93f) | Sep 28, 2022 |
| HP            | 339A                        | [ac9538b489](https://linux-hardware.org/?probe=ac9538b489) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [82b108b3b8](https://linux-hardware.org/?probe=82b108b3b8) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0031772f40](https://linux-hardware.org/?probe=0031772f40) | Sep 27, 2022 |
| MSI           | B365M PRO-VDH               | [45e07c7119](https://linux-hardware.org/?probe=45e07c7119) | Sep 27, 2022 |
| Medion        | MS-7728                     | [0b9b2ca570](https://linux-hardware.org/?probe=0b9b2ca570) | Sep 27, 2022 |
| HP            | 339A                        | [25ef7556cc](https://linux-hardware.org/?probe=25ef7556cc) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [e3826dca71](https://linux-hardware.org/?probe=e3826dca71) | Sep 27, 2022 |
| Gigabyte      | H81M-S2PV                   | [76a7224818](https://linux-hardware.org/?probe=76a7224818) | Sep 26, 2022 |
| HP            | 339A                        | [07986ca95e](https://linux-hardware.org/?probe=07986ca95e) | Sep 26, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [2cc7eefe57](https://linux-hardware.org/?probe=2cc7eefe57) | Sep 26, 2022 |
| HP            | 0B40h                       | [d72bb749ff](https://linux-hardware.org/?probe=d72bb749ff) | Sep 26, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [508c873693](https://linux-hardware.org/?probe=508c873693) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6c9c3f13d0](https://linux-hardware.org/?probe=6c9c3f13d0) | Sep 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | [779faa3cfd](https://linux-hardware.org/?probe=779faa3cfd) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| Google        | Teemo                       | [5ddc8b97b8](https://linux-hardware.org/?probe=5ddc8b97b8) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| Foxconn       | 2ADA                        | [8a734f0799](https://linux-hardware.org/?probe=8a734f0799) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| MSI           | C236A WORKSTATION           | [67432a461e](https://linux-hardware.org/?probe=67432a461e) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| ECS           | H61H2-CM                    | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| ASUSTek       | P5QPL-VM EPU                | [8a4819f23d](https://linux-hardware.org/?probe=8a4819f23d) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | [6c884d4968](https://linux-hardware.org/?probe=6c884d4968) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | [39a94459dc](https://linux-hardware.org/?probe=39a94459dc) | Sep 23, 2022 |
| ASUSTek       | H110M-R                     | [c9f00bec8e](https://linux-hardware.org/?probe=c9f00bec8e) | Sep 23, 2022 |
| HP            | 876C SMVB                   | [c6fbf7c631](https://linux-hardware.org/?probe=c6fbf7c631) | Sep 23, 2022 |
| Pegatron      | 2ACD                        | [31c266d23c](https://linux-hardware.org/?probe=31c266d23c) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [c0cc0dc101](https://linux-hardware.org/?probe=c0cc0dc101) | Sep 21, 2022 |
| Lenovo        | ThinkCentre A70z 0401R6U    | [2a93ca040a](https://linux-hardware.org/?probe=2a93ca040a) | Sep 21, 2022 |
| Thecus        | N2810 0001                  | [f54df3994c](https://linux-hardware.org/?probe=f54df3994c) | Sep 21, 2022 |
| ECS           | G31T-M9                     | [6e67780df1](https://linux-hardware.org/?probe=6e67780df1) | Sep 21, 2022 |
| Gigabyte      | H61M-DS2                    | [a9e18191f7](https://linux-hardware.org/?probe=a9e18191f7) | Sep 21, 2022 |
| ASRock        | H470M-HVS                   | [e267d78b42](https://linux-hardware.org/?probe=e267d78b42) | Sep 21, 2022 |
| ECS           | G31T-M9                     | [46fd18ee44](https://linux-hardware.org/?probe=46fd18ee44) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | [03e6d4f5bc](https://linux-hardware.org/?probe=03e6d4f5bc) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | [658141844b](https://linux-hardware.org/?probe=658141844b) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| HP            | 158A                        | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Supermicro    | X9DR3-F                     | [da32f7dbfb](https://linux-hardware.org/?probe=da32f7dbfb) | Sep 21, 2022 |
| ASUSTek       | G20CB                       | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| Shuttle       | FS81                        | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | B85M-G                      | [f9fa37f0d2](https://linux-hardware.org/?probe=f9fa37f0d2) | Sep 20, 2022 |
| Gigabyte      | GA-M56S-S3                  | [ecd62e14f4](https://linux-hardware.org/?probe=ecd62e14f4) | Sep 20, 2022 |
| Unknown       | 1.0                         | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| Gigabyte      | EP45T-UD3R                  | [979765d106](https://linux-hardware.org/?probe=979765d106) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [a0a61b5d8c](https://linux-hardware.org/?probe=a0a61b5d8c) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb8e3ae62a](https://linux-hardware.org/?probe=bb8e3ae62a) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| Gigabyte      | B550 VISION D-P             | [b1f764b4ca](https://linux-hardware.org/?probe=b1f764b4ca) | Sep 19, 2022 |
| ASRock        | H470M-HVS                   | [ee235bf98c](https://linux-hardware.org/?probe=ee235bf98c) | Sep 19, 2022 |
| Gigabyte      | B550 VISION D-P             | [9457acbe13](https://linux-hardware.org/?probe=9457acbe13) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| AZW           | GK55                        | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| ASRock        | Z590M-ITX/ax                | [d202b0a504](https://linux-hardware.org/?probe=d202b0a504) | Sep 19, 2022 |
| Supermicro    | X10DRi-T4+                  | [1f507cde8c](https://linux-hardware.org/?probe=1f507cde8c) | Sep 19, 2022 |
| HP            | 1998                        | [14eeedb712](https://linux-hardware.org/?probe=14eeedb712) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [c639777548](https://linux-hardware.org/?probe=c639777548) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| MSI           | J1800I                      | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| Dell          | 0G785M A00                  | [c1045050d6](https://linux-hardware.org/?probe=c1045050d6) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| Dell          | 0T2HR0 A02                  | [46dd4dfa8f](https://linux-hardware.org/?probe=46dd4dfa8f) | Sep 17, 2022 |
| AZW           | Gemini T34-M                | [baafe96fc5](https://linux-hardware.org/?probe=baafe96fc5) | Sep 17, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | [968c24205d](https://linux-hardware.org/?probe=968c24205d) | Sep 17, 2022 |
| ASUSTek       | P8Z77-V                     | [3ace24ebfc](https://linux-hardware.org/?probe=3ace24ebfc) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| ASUSTek       | KCMA-D8                     | [dc8ecec94f](https://linux-hardware.org/?probe=dc8ecec94f) | Sep 16, 2022 |
| Gigabyte      | B150M-D3P-WG-CF             | [e37ff8fec3](https://linux-hardware.org/?probe=e37ff8fec3) | Sep 16, 2022 |
| Gigabyte      | EP45T-UD3R                  | [04a99c2508](https://linux-hardware.org/?probe=04a99c2508) | Sep 16, 2022 |
| ASRock        | H470M-HVS                   | [205e3937a8](https://linux-hardware.org/?probe=205e3937a8) | Sep 16, 2022 |
| MSI           | B450-A PRO MAX              | [c63f6d45b4](https://linux-hardware.org/?probe=c63f6d45b4) | Sep 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [00ca986a4c](https://linux-hardware.org/?probe=00ca986a4c) | Sep 16, 2022 |
| Unknown       | Unknown                     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d2a3eb186f](https://linux-hardware.org/?probe=d2a3eb186f) | Sep 15, 2022 |
| MSI           | H110M PRO-VD                | [23194305f6](https://linux-hardware.org/?probe=23194305f6) | Sep 15, 2022 |
| ASUSTek       | B85M-G                      | [9f2a08c261](https://linux-hardware.org/?probe=9f2a08c261) | Sep 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | [007e9d4205](https://linux-hardware.org/?probe=007e9d4205) | Sep 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [15d3d95ab2](https://linux-hardware.org/?probe=15d3d95ab2) | Sep 15, 2022 |
| HP            | 876C SMVB                   | [adc81b2fd5](https://linux-hardware.org/?probe=adc81b2fd5) | Sep 15, 2022 |
| Gigabyte      | B560M DS3H V2               | [af4b9d7add](https://linux-hardware.org/?probe=af4b9d7add) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [01d92ffc28](https://linux-hardware.org/?probe=01d92ffc28) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [c04d19fe27](https://linux-hardware.org/?probe=c04d19fe27) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [ad0ac85a1c](https://linux-hardware.org/?probe=ad0ac85a1c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [6cb46b9558](https://linux-hardware.org/?probe=6cb46b9558) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [bec6da09ae](https://linux-hardware.org/?probe=bec6da09ae) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [0366b6294c](https://linux-hardware.org/?probe=0366b6294c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [a914907c0f](https://linux-hardware.org/?probe=a914907c0f) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [662117584a](https://linux-hardware.org/?probe=662117584a) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [272b6ec971](https://linux-hardware.org/?probe=272b6ec971) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [2528bbb7ac](https://linux-hardware.org/?probe=2528bbb7ac) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [212a063241](https://linux-hardware.org/?probe=212a063241) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [2b6d3fc6f0](https://linux-hardware.org/?probe=2b6d3fc6f0) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [9bc2776801](https://linux-hardware.org/?probe=9bc2776801) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [4048396126](https://linux-hardware.org/?probe=4048396126) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [7036d4bc55](https://linux-hardware.org/?probe=7036d4bc55) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [e4147da882](https://linux-hardware.org/?probe=e4147da882) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [f85ab5e109](https://linux-hardware.org/?probe=f85ab5e109) | Sep 14, 2022 |
| HP            | 876C SMVB                   | [347ab44533](https://linux-hardware.org/?probe=347ab44533) | Sep 14, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | 876C SMVB                   | [61df16cfc9](https://linux-hardware.org/?probe=61df16cfc9) | Sep 13, 2022 |
| HP            | 876C SMVB                   | [15ec81ce9d](https://linux-hardware.org/?probe=15ec81ce9d) | Sep 13, 2022 |
| Biostar       | NF560-A2G                   | [96c296c2f3](https://linux-hardware.org/?probe=96c296c2f3) | Sep 13, 2022 |
| ASRock        | H470M-HDV                   | [41977548bc](https://linux-hardware.org/?probe=41977548bc) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| ASUSTek       | P5Q SE2                     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| HP            | 8464                        | [fcc16a5a56](https://linux-hardware.org/?probe=fcc16a5a56) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [31ca5d0add](https://linux-hardware.org/?probe=31ca5d0add) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [d76d427a61](https://linux-hardware.org/?probe=d76d427a61) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [c996d652d3](https://linux-hardware.org/?probe=c996d652d3) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [d08cb8e35b](https://linux-hardware.org/?probe=d08cb8e35b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [0c2d66313e](https://linux-hardware.org/?probe=0c2d66313e) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [5461cdbf3b](https://linux-hardware.org/?probe=5461cdbf3b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [c055d82971](https://linux-hardware.org/?probe=c055d82971) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [8c0d419ac8](https://linux-hardware.org/?probe=8c0d419ac8) | Sep 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [e8da6da2b0](https://linux-hardware.org/?probe=e8da6da2b0) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [e007728e0a](https://linux-hardware.org/?probe=e007728e0a) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Dell          | 01XK1W A00                  | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| HP            | 1998                        | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| Lenovo        | ThinkServer TS440           | [cf028f9b8c](https://linux-hardware.org/?probe=cf028f9b8c) | Sep 10, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [102cf248e9](https://linux-hardware.org/?probe=102cf248e9) | Sep 10, 2022 |
| Unknown       | Unknown                     | [a0c1db14a0](https://linux-hardware.org/?probe=a0c1db14a0) | Sep 09, 2022 |
| Biostar       | NF560-A2G                   | [68ffa42095](https://linux-hardware.org/?probe=68ffa42095) | Sep 09, 2022 |
| ASRock        | H310CM-HDV                  | [4f0ec780ee](https://linux-hardware.org/?probe=4f0ec780ee) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [e4d2c1c120](https://linux-hardware.org/?probe=e4d2c1c120) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d28677add3](https://linux-hardware.org/?probe=d28677add3) | Sep 09, 2022 |
| Gigabyte      | M61PME-S2                   | [2557dd83ce](https://linux-hardware.org/?probe=2557dd83ce) | Sep 09, 2022 |
| ASRock        | Q1900M                      | [aadbe54f8d](https://linux-hardware.org/?probe=aadbe54f8d) | Sep 08, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [17675b7bc8](https://linux-hardware.org/?probe=17675b7bc8) | Sep 08, 2022 |
| Gigabyte      | M61PME-S2                   | [1c48e52b18](https://linux-hardware.org/?probe=1c48e52b18) | Sep 08, 2022 |
| HP            | 2175                        | [97d08b25c7](https://linux-hardware.org/?probe=97d08b25c7) | Sep 08, 2022 |
| Gigabyte      | GA-M56S-S3                  | [b090ccb8fe](https://linux-hardware.org/?probe=b090ccb8fe) | Sep 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | [6949fd04b7](https://linux-hardware.org/?probe=6949fd04b7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS                    | [fcf815d38f](https://linux-hardware.org/?probe=fcf815d38f) | Sep 07, 2022 |
| MSI           | H110M PRO-VD                | [754b9daf74](https://linux-hardware.org/?probe=754b9daf74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
| Gigabyte      | GA-M56S-S3                  | [9012dd4a5d](https://linux-hardware.org/?probe=9012dd4a5d) | Sep 06, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [92af2339e3](https://linux-hardware.org/?probe=92af2339e3) | Sep 06, 2022 |
| ECS           | G31T-M9                     | [5005d8382e](https://linux-hardware.org/?probe=5005d8382e) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [f7b09fb3e3](https://linux-hardware.org/?probe=f7b09fb3e3) | Sep 06, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [dacafc4729](https://linux-hardware.org/?probe=dacafc4729) | Sep 06, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [2c5b0be3af](https://linux-hardware.org/?probe=2c5b0be3af) | Sep 06, 2022 |
| Gigabyte      | G41M-ES2L                   | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [26e63d2357](https://linux-hardware.org/?probe=26e63d2357) | Sep 05, 2022 |
| HP            | 805D                        | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Dell          | 06FW8P A00                  | [6023e5aa76](https://linux-hardware.org/?probe=6023e5aa76) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASRock        | Q1900M                      | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| ASUSTek       | PRIME A320M-K               | [878661705c](https://linux-hardware.org/?probe=878661705c) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [eb29524a90](https://linux-hardware.org/?probe=eb29524a90) | Sep 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| ASUSTek       | P8H61 PRO                   | [082520f2d8](https://linux-hardware.org/?probe=082520f2d8) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| ASRockRack    | X470D4U2/1N1                | [0be6c5963d](https://linux-hardware.org/?probe=0be6c5963d) | Sep 02, 2022 |
| ASRock        | J3455-ITX                   | [262c6222d1](https://linux-hardware.org/?probe=262c6222d1) | Sep 02, 2022 |
| Gigabyte      | B550M DS3H                  | [acdd27f635](https://linux-hardware.org/?probe=acdd27f635) | Sep 02, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3870423379](https://linux-hardware.org/?probe=3870423379) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Gigabyte      | H77-DS3H                    | [11f9e9fa68](https://linux-hardware.org/?probe=11f9e9fa68) | Sep 02, 2022 |
| HP            | 8767 A                      | [62e70ef3e8](https://linux-hardware.org/?probe=62e70ef3e8) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | [e9f6cafc6c](https://linux-hardware.org/?probe=e9f6cafc6c) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | [277340da8a](https://linux-hardware.org/?probe=277340da8a) | Sep 02, 2022 |
| Gigabyte      | Z590 UD AC                  | [6c7b47158f](https://linux-hardware.org/?probe=6c7b47158f) | Sep 02, 2022 |
| Dell          | 02YRK5 A02                  | [bc316a8d3f](https://linux-hardware.org/?probe=bc316a8d3f) | Sep 01, 2022 |
| MSI           | H81M-P33                    | [8d15799ff9](https://linux-hardware.org/?probe=8d15799ff9) | Sep 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b226dd8bc2](https://linux-hardware.org/?probe=b226dd8bc2) | Sep 01, 2022 |
| Gigabyte      | M68MT-S2                    | [29b9669488](https://linux-hardware.org/?probe=29b9669488) | Aug 31, 2022 |
| SZMZ          | X99M-G2                     | [eff1231310](https://linux-hardware.org/?probe=eff1231310) | Aug 31, 2022 |
| ASRock        | B450M-HDV R4.0              | [9c9e1d1ff1](https://linux-hardware.org/?probe=9c9e1d1ff1) | Aug 31, 2022 |
| ASRock        | N68-VS3 UCC                 | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| Dell          | 0WG864                      | [234e8953bc](https://linux-hardware.org/?probe=234e8953bc) | Aug 30, 2022 |
| Gigabyte      | M68MT-S2                    | [16b07a7497](https://linux-hardware.org/?probe=16b07a7497) | Aug 30, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [28f3abde34](https://linux-hardware.org/?probe=28f3abde34) | Aug 30, 2022 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
| Gigabyte      | M68MT-S2                    | [cfd6369e5a](https://linux-hardware.org/?probe=cfd6369e5a) | Aug 30, 2022 |
| Fujitsu       | D3348-B1 S26361-D3348-B1    | [9721d1f81d](https://linux-hardware.org/?probe=9721d1f81d) | Aug 30, 2022 |
| Unknown       | Unknown                     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Unknown       | Unknown                     | [4d1df25a9f](https://linux-hardware.org/?probe=4d1df25a9f) | Aug 29, 2022 |
| Dell          | 09KPNV A00                  | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| Unknown       | Unknown                     | [ef43339df1](https://linux-hardware.org/?probe=ef43339df1) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | [f17bcbfc4b](https://linux-hardware.org/?probe=f17bcbfc4b) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | [4960a57d91](https://linux-hardware.org/?probe=4960a57d91) | Aug 28, 2022 |
| MSI           | E350IA-E45                  | [d1d570a455](https://linux-hardware.org/?probe=d1d570a455) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [859b3cb78a](https://linux-hardware.org/?probe=859b3cb78a) | Aug 28, 2022 |
| ASRock        | 990FX Extreme9              | [1a472eb51c](https://linux-hardware.org/?probe=1a472eb51c) | Aug 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e0fedafd62](https://linux-hardware.org/?probe=e0fedafd62) | Aug 27, 2022 |
| ASRock        | Z68 Pro3 Gen3               | [186a63fa9e](https://linux-hardware.org/?probe=186a63fa9e) | Aug 27, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [fbfc58655a](https://linux-hardware.org/?probe=fbfc58655a) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [5d4e41a441](https://linux-hardware.org/?probe=5d4e41a441) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | [8418a8e83c](https://linux-hardware.org/?probe=8418a8e83c) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | [2a3114af33](https://linux-hardware.org/?probe=2a3114af33) | Aug 26, 2022 |
| ASUSTek       | IPN73-BA                    | [89f8b175e2](https://linux-hardware.org/?probe=89f8b175e2) | Aug 26, 2022 |
| Foxconn       | 2ABF                        | [46efca142c](https://linux-hardware.org/?probe=46efca142c) | Aug 26, 2022 |
| HP            | 18E5                        | [9196bf639b](https://linux-hardware.org/?probe=9196bf639b) | Aug 26, 2022 |
| Lenovo        | 7033EW4                     | [54417ae55f](https://linux-hardware.org/?probe=54417ae55f) | Aug 26, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [5769de3299](https://linux-hardware.org/?probe=5769de3299) | Aug 25, 2022 |
| Gigabyte      | M61SME-S2                   | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| Dell          | 0WG864                      | [7cbb2239ba](https://linux-hardware.org/?probe=7cbb2239ba) | Aug 25, 2022 |
| Dell          | 0D4MD1 A02                  | [7a06622253](https://linux-hardware.org/?probe=7a06622253) | Aug 25, 2022 |
| Dell          | 0WG864                      | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| ASUSTek       | PRIME H510M-E               | [c1c6b26e42](https://linux-hardware.org/?probe=c1c6b26e42) | Aug 25, 2022 |
| ASUSTek       | A7N8X2.0                    | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [0bcf6f0268](https://linux-hardware.org/?probe=0bcf6f0268) | Aug 25, 2022 |
| Gigabyte      | G41MT-S2                    | [42cd205688](https://linux-hardware.org/?probe=42cd205688) | Aug 25, 2022 |
| ASUSTek       | IPN73-BA                    | [da7e1db516](https://linux-hardware.org/?probe=da7e1db516) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| HP            | 339A                        | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| ASUSTek       | H97M-PLUS                   | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Dell          | 0D4MD1 A02                  | [b634bcdfa9](https://linux-hardware.org/?probe=b634bcdfa9) | Aug 24, 2022 |
| Huanan        | X99-F8D V2.4                | [11cfa7a502](https://linux-hardware.org/?probe=11cfa7a502) | Aug 24, 2022 |
| ASUSTek       | Pro B550M-C                 | [f0691dc9d8](https://linux-hardware.org/?probe=f0691dc9d8) | Aug 23, 2022 |
| Aquarius      | AQH310CM                    | [5e7e2820f4](https://linux-hardware.org/?probe=5e7e2820f4) | Aug 23, 2022 |
| ASUSTek       | A7N8X2.0                    | [56416fa002](https://linux-hardware.org/?probe=56416fa002) | Aug 23, 2022 |
| Dell          | 0MWYPT A02                  | [017af6f58d](https://linux-hardware.org/?probe=017af6f58d) | Aug 23, 2022 |
| retsamarre... | Unknown                     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| Dell          | 0WG864                      | [e199a1a176](https://linux-hardware.org/?probe=e199a1a176) | Aug 23, 2022 |
| MSI           | H110M PRO-VD                | [7652f87b3a](https://linux-hardware.org/?probe=7652f87b3a) | Aug 22, 2022 |
| HP            | 2187 A01                    | [ab44144f07](https://linux-hardware.org/?probe=ab44144f07) | Aug 22, 2022 |
| ASUSTek       | Z10PA-U8 Series             | [3e560a4018](https://linux-hardware.org/?probe=3e560a4018) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| ASUSTek       | Z170-A                      | [35270005d4](https://linux-hardware.org/?probe=35270005d4) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Foxconn       | 2ABF                        | [3eed86b908](https://linux-hardware.org/?probe=3eed86b908) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| MSI           | G31M3                       | [3bb7906f56](https://linux-hardware.org/?probe=3bb7906f56) | Aug 20, 2022 |
| Google        | Teemo                       | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| MSI           | Z370 PC PRO                 | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Intel         | DN2820FYK H24582-201        | [a67c5b1926](https://linux-hardware.org/?probe=a67c5b1926) | Aug 19, 2022 |
| ASRock        | B450M-HDV R4.0              | [2f99e182f6](https://linux-hardware.org/?probe=2f99e182f6) | Aug 19, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [38eed67854](https://linux-hardware.org/?probe=38eed67854) | Aug 18, 2022 |
| Gateway       | DS50                        | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Gigabyte      | B560M DS3H AC               | [84e861fd2c](https://linux-hardware.org/?probe=84e861fd2c) | Aug 18, 2022 |
| ECS           | H61H2-M13                   | [fb83ed3720](https://linux-hardware.org/?probe=fb83ed3720) | Aug 18, 2022 |
| ECS           | G31T-M9                     | [d5b3edd559](https://linux-hardware.org/?probe=d5b3edd559) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| Dell          | 0WG864                      | [c4aee967b4](https://linux-hardware.org/?probe=c4aee967b4) | Aug 18, 2022 |
| MSI           | B85M-E45                    | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | [b648d56b04](https://linux-hardware.org/?probe=b648d56b04) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | [d066e1bcdf](https://linux-hardware.org/?probe=d066e1bcdf) | Aug 17, 2022 |
| ECS           | G31T-M9                     | [6192258c32](https://linux-hardware.org/?probe=6192258c32) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | [47ecca331e](https://linux-hardware.org/?probe=47ecca331e) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [1999369ff0](https://linux-hardware.org/?probe=1999369ff0) | Aug 16, 2022 |
| Dell          | 02YRK5 A02                  | [959d35921a](https://linux-hardware.org/?probe=959d35921a) | Aug 15, 2022 |
| HP            | 3047h                       | [bba72086af](https://linux-hardware.org/?probe=bba72086af) | Aug 15, 2022 |
| ASUSTek       | P6T WS PRO                  | [155ba78790](https://linux-hardware.org/?probe=155ba78790) | Aug 15, 2022 |
| ASUSTek       | WS C422 DC                  | [92d816348a](https://linux-hardware.org/?probe=92d816348a) | Aug 15, 2022 |
| Gigabyte      | GA-970A-UD3                 | [9a1ff39910](https://linux-hardware.org/?probe=9a1ff39910) | Aug 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [265b666497](https://linux-hardware.org/?probe=265b666497) | Aug 14, 2022 |
| ASRock        | AB350 Gaming K4             | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Dell          | 0WWJRX A00                  | [c9a3a6e952](https://linux-hardware.org/?probe=c9a3a6e952) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8c792d555c](https://linux-hardware.org/?probe=8c792d555c) | Aug 12, 2022 |
| System76      | Thelio thelio-r1            | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| Dell          | 0WG864                      | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Unknown       | Unknown                     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| Gigabyte      | H270-Gaming 3               | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| ASUSTek       | PRIME Z370-P                | [7afaba2067](https://linux-hardware.org/?probe=7afaba2067) | Aug 12, 2022 |
| MSI           | H110M PRO-VD                | [57be8a8829](https://linux-hardware.org/?probe=57be8a8829) | Aug 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| ASRock        | H110M-DGS R3.0              | [934583e785](https://linux-hardware.org/?probe=934583e785) | Aug 11, 2022 |
| Aquarius      | AQH310CM                    | [4084737708](https://linux-hardware.org/?probe=4084737708) | Aug 11, 2022 |
| MSI           | H110M PRO-VD                | [830489f44c](https://linux-hardware.org/?probe=830489f44c) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | [d8432224a8](https://linux-hardware.org/?probe=d8432224a8) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | [1325d40c4e](https://linux-hardware.org/?probe=1325d40c4e) | Aug 11, 2022 |
| ASRock        | H61M/U3S3                   | [be0d853621](https://linux-hardware.org/?probe=be0d853621) | Aug 11, 2022 |
| Gigabyte      | B450M DS3H V2               | [33dc68fe04](https://linux-hardware.org/?probe=33dc68fe04) | Aug 11, 2022 |
| ASUSTek       | H81T                        | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [49098497d4](https://linux-hardware.org/?probe=49098497d4) | Aug 11, 2022 |
| ASRock        | G31M-S                      | [335a6f8616](https://linux-hardware.org/?probe=335a6f8616) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [fd910dc3ca](https://linux-hardware.org/?probe=fd910dc3ca) | Aug 10, 2022 |
| MSI           | G41M-P28                    | [c20d54489d](https://linux-hardware.org/?probe=c20d54489d) | Aug 10, 2022 |
| Intel         | DP35DP AAD81073-207         | [3f55eb1ae4](https://linux-hardware.org/?probe=3f55eb1ae4) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [a83fd820d4](https://linux-hardware.org/?probe=a83fd820d4) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [243392c01f](https://linux-hardware.org/?probe=243392c01f) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [8ea693190b](https://linux-hardware.org/?probe=8ea693190b) | Aug 09, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [346b22a42e](https://linux-hardware.org/?probe=346b22a42e) | Aug 09, 2022 |
| HP            | 1998                        | [d4dcaf27a2](https://linux-hardware.org/?probe=d4dcaf27a2) | Aug 09, 2022 |
| ASUSTek       | P8H61-M LX3                 | [19346d16de](https://linux-hardware.org/?probe=19346d16de) | Aug 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [1713317338](https://linux-hardware.org/?probe=1713317338) | Aug 09, 2022 |
| Gigabyte      | Z270-Gaming K3              | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [18b6026d87](https://linux-hardware.org/?probe=18b6026d87) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [fb01a8303f](https://linux-hardware.org/?probe=fb01a8303f) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| Unknown       | Unknown                     | [49c2378f28](https://linux-hardware.org/?probe=49c2378f28) | Aug 08, 2022 |
| Unknown       | Unknown                     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | [91fb10e9c6](https://linux-hardware.org/?probe=91fb10e9c6) | Aug 08, 2022 |
| ECS           | G31T-M9                     | [6d24097613](https://linux-hardware.org/?probe=6d24097613) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| ASUSTek       | P8Z77-V                     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| Gigabyte      | MZGLKAP-00                  | [5a349b05d2](https://linux-hardware.org/?probe=5a349b05d2) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [67934f8ed6](https://linux-hardware.org/?probe=67934f8ed6) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [d6d5cc239f](https://linux-hardware.org/?probe=d6d5cc239f) | Aug 07, 2022 |
| Unknown       | Unknown                     | [dbafe167dc](https://linux-hardware.org/?probe=dbafe167dc) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [468c10942e](https://linux-hardware.org/?probe=468c10942e) | Aug 06, 2022 |
| Biostar       | A780L3G                     | [a5ff2b3147](https://linux-hardware.org/?probe=a5ff2b3147) | Aug 05, 2022 |
| ECS           | G31T-M9                     | [8cdebd57de](https://linux-hardware.org/?probe=8cdebd57de) | Aug 05, 2022 |
| Gigabyte      | H81M-S2V                    | [696740d407](https://linux-hardware.org/?probe=696740d407) | Aug 05, 2022 |
| Lenovo        | 102F NO DPK                 | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Foxconn       | 2AB1                        | [a2ebd67b7b](https://linux-hardware.org/?probe=a2ebd67b7b) | Aug 04, 2022 |
| ASUSTek       | P8H61-M LX3                 | [3d945110f8](https://linux-hardware.org/?probe=3d945110f8) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| HP            | 8876 11                     | [150fcb8977](https://linux-hardware.org/?probe=150fcb8977) | Aug 03, 2022 |
| HP            | 8876 11                     | [029813dfc5](https://linux-hardware.org/?probe=029813dfc5) | Aug 03, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Foxconn       | 2AB1                        | [74cd42b826](https://linux-hardware.org/?probe=74cd42b826) | Aug 03, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| MSI           | Z97 GAMING 5                | [d2c534d06f](https://linux-hardware.org/?probe=d2c534d06f) | Aug 02, 2022 |
| ASUSTek       | P5G41T-M LE                 | [80c0577159](https://linux-hardware.org/?probe=80c0577159) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [0d7342cca0](https://linux-hardware.org/?probe=0d7342cca0) | Aug 01, 2022 |
| ASRock        | H470M-HVS                   | [5282e92d2c](https://linux-hardware.org/?probe=5282e92d2c) | Aug 01, 2022 |
| ASUSTek       | P9X79                       | [4a518ab792](https://linux-hardware.org/?probe=4a518ab792) | Jul 31, 2022 |
| Gigabyte      | Z590 UD AC                  | [12cf4f1c81](https://linux-hardware.org/?probe=12cf4f1c81) | Jul 31, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [cc1944f4a3](https://linux-hardware.org/?probe=cc1944f4a3) | Jul 31, 2022 |
| Gigabyte      | A320M-H-CF                  | [5facb7723f](https://linux-hardware.org/?probe=5facb7723f) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [c17e48cc2b](https://linux-hardware.org/?probe=c17e48cc2b) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [4644e4eaa8](https://linux-hardware.org/?probe=4644e4eaa8) | Jul 30, 2022 |
| ASUSTek       | P8B75-M                     | [ddf26da899](https://linux-hardware.org/?probe=ddf26da899) | Jul 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | [0cdabe4b69](https://linux-hardware.org/?probe=0cdabe4b69) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e3a44e4c5b](https://linux-hardware.org/?probe=e3a44e4c5b) | Jul 30, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [3b1f863612](https://linux-hardware.org/?probe=3b1f863612) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [8c57fbc9e8](https://linux-hardware.org/?probe=8c57fbc9e8) | Jul 29, 2022 |
| MSI           | H110M PRO-VD                | [675b1fa2ff](https://linux-hardware.org/?probe=675b1fa2ff) | Jul 29, 2022 |
| ASUSTek       | B85M-E/DASH                 | [2ebbaa4052](https://linux-hardware.org/?probe=2ebbaa4052) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [902ee3b350](https://linux-hardware.org/?probe=902ee3b350) | Jul 29, 2022 |
| AZW           | MINI S                      | [53ba28d9c3](https://linux-hardware.org/?probe=53ba28d9c3) | Jul 28, 2022 |
| AZW           | MINI S                      | [46216b2db1](https://linux-hardware.org/?probe=46216b2db1) | Jul 28, 2022 |
| MSI           | Z370 GAMING M5              | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| MSI           | PRO Z690-A DDR4             | [b5b5f049d0](https://linux-hardware.org/?probe=b5b5f049d0) | Jul 28, 2022 |
| HP            | ProLiant MicroServer        | [8104eee56e](https://linux-hardware.org/?probe=8104eee56e) | Jul 28, 2022 |
| Gigabyte      | A520M DS3H                  | [900a5b4f7f](https://linux-hardware.org/?probe=900a5b4f7f) | Jul 28, 2022 |
| ASUSTek       | P7P55D                      | [0c9828e226](https://linux-hardware.org/?probe=0c9828e226) | Jul 28, 2022 |
| Intel         | DH61AG AAG23736-505         | [7fd3a18899](https://linux-hardware.org/?probe=7fd3a18899) | Jul 28, 2022 |
| ASUSTek       | H97-PRO                     | [ca77f59b41](https://linux-hardware.org/?probe=ca77f59b41) | Jul 28, 2022 |
| MSI           | H110M PRO-VD                | [33961c087b](https://linux-hardware.org/?probe=33961c087b) | Jul 28, 2022 |
| HP            | 3048h                       | [01d1b1e99a](https://linux-hardware.org/?probe=01d1b1e99a) | Jul 28, 2022 |
| MSI           | H110I PRO                   | [1dcc4b694a](https://linux-hardware.org/?probe=1dcc4b694a) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [661a4a67d4](https://linux-hardware.org/?probe=661a4a67d4) | Jul 27, 2022 |
| ECS           | G31T-M9                     | [5537dcbed3](https://linux-hardware.org/?probe=5537dcbed3) | Jul 27, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [29780cf747](https://linux-hardware.org/?probe=29780cf747) | Jul 27, 2022 |
| Medion        | MS-7728                     | [662e3948f2](https://linux-hardware.org/?probe=662e3948f2) | Jul 27, 2022 |
| Gigabyte      | H470M DS3H                  | [5f90ec9763](https://linux-hardware.org/?probe=5f90ec9763) | Jul 27, 2022 |
| HP            | 0AACh                       | [d7df31df8c](https://linux-hardware.org/?probe=d7df31df8c) | Jul 26, 2022 |
| HP            | 0AACh                       | [357aa343ec](https://linux-hardware.org/?probe=357aa343ec) | Jul 26, 2022 |
| ASUSTek       | PRIME H310M-K               | [ba71ad5870](https://linux-hardware.org/?probe=ba71ad5870) | Jul 26, 2022 |
| ASRock        | H510M-HDV/M.2               | [e7672c215b](https://linux-hardware.org/?probe=e7672c215b) | Jul 26, 2022 |
| Gigabyte      | H61M-S1                     | [5e8e9fbd71](https://linux-hardware.org/?probe=5e8e9fbd71) | Jul 26, 2022 |
| ASUSTek       | P8B75-M                     | [46e85f96ca](https://linux-hardware.org/?probe=46e85f96ca) | Jul 26, 2022 |
| ASUSTek       | AT5NM10T-I                  | [9738c4bebc](https://linux-hardware.org/?probe=9738c4bebc) | Jul 26, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [9d3da43bea](https://linux-hardware.org/?probe=9d3da43bea) | Jul 25, 2022 |
| Dell          | 03NVJ6 A01                  | [3998c390f0](https://linux-hardware.org/?probe=3998c390f0) | Jul 25, 2022 |
| ASRock        | H470M Pro4                  | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| ASRockRack    | B565D4-V1L                  | [1301ad9bd0](https://linux-hardware.org/?probe=1301ad9bd0) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| AZW           | U59                         | [82e7dfdca5](https://linux-hardware.org/?probe=82e7dfdca5) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| ECS           | G31T-M9                     | [f7489c3b16](https://linux-hardware.org/?probe=f7489c3b16) | Jul 22, 2022 |
| MSI           | H110M PRO-VD                | [ffd65c627e](https://linux-hardware.org/?probe=ffd65c627e) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| MSI           | H110M PRO-VD                | [ffcc0670ba](https://linux-hardware.org/?probe=ffcc0670ba) | Jul 21, 2022 |
| Gigabyte      | M68MT-S2                    | [e505d3e2da](https://linux-hardware.org/?probe=e505d3e2da) | Jul 21, 2022 |
| MSI           | B150M BAZOOKA               | [41053f8c0e](https://linux-hardware.org/?probe=41053f8c0e) | Jul 21, 2022 |
| MSI           | G31TM-P21                   | [34b4e0a6ea](https://linux-hardware.org/?probe=34b4e0a6ea) | Jul 21, 2022 |
| Gigabyte      | M68MT-S2                    | [de41a6c75f](https://linux-hardware.org/?probe=de41a6c75f) | Jul 21, 2022 |
| Intel         | DH67BL AAG10189-209         | [8b924d9018](https://linux-hardware.org/?probe=8b924d9018) | Jul 21, 2022 |
| Dell          | 0HD5W2 A01                  | [e2eca7122c](https://linux-hardware.org/?probe=e2eca7122c) | Jul 21, 2022 |
| Intel         | DH67BL AAG10189-209         | [d9ce312767](https://linux-hardware.org/?probe=d9ce312767) | Jul 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8ad4c64b76](https://linux-hardware.org/?probe=8ad4c64b76) | Jul 20, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f7678fb134](https://linux-hardware.org/?probe=f7678fb134) | Jul 20, 2022 |
| Intel         | DH67BL AAG10189-209         | [7bb5f0bd56](https://linux-hardware.org/?probe=7bb5f0bd56) | Jul 20, 2022 |
| MSI           | MS-7236                     | [e824199021](https://linux-hardware.org/?probe=e824199021) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Dell          | 07T4MC A11                  | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| Gigabyte      | B365M DS3H                  | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| Gigabyte      | H61M-S2PV                   | [44b9b405c2](https://linux-hardware.org/?probe=44b9b405c2) | Jul 20, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fdc7518bfd](https://linux-hardware.org/?probe=fdc7518bfd) | Jul 19, 2022 |
| Intel         | DH67BL AAG10189-209         | [ff8bfdfce1](https://linux-hardware.org/?probe=ff8bfdfce1) | Jul 19, 2022 |
| ASUSTek       | PRIME H510M-A               | [6e29d1e7e1](https://linux-hardware.org/?probe=6e29d1e7e1) | Jul 19, 2022 |
| MSI           | H110M PRO-VD                | [ecf613ee2c](https://linux-hardware.org/?probe=ecf613ee2c) | Jul 19, 2022 |
| ASRock        | H470M-HVS                   | [2ccd5ab488](https://linux-hardware.org/?probe=2ccd5ab488) | Jul 19, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [44035117ae](https://linux-hardware.org/?probe=44035117ae) | Jul 19, 2022 |
| MSI           | H110M PRO-VD                | [069d79d670](https://linux-hardware.org/?probe=069d79d670) | Jul 19, 2022 |
| ASUSTek       | Z170M-PLUS                  | [85df5dd7a2](https://linux-hardware.org/?probe=85df5dd7a2) | Jul 19, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [4f256f41a7](https://linux-hardware.org/?probe=4f256f41a7) | Jul 19, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [a5082efd70](https://linux-hardware.org/?probe=a5082efd70) | Jul 19, 2022 |
| Compaq        | 07A8h                       | [329d1b25c3](https://linux-hardware.org/?probe=329d1b25c3) | Jul 18, 2022 |
| MSI           | H110M PRO-VD                | [b9799fcb96](https://linux-hardware.org/?probe=b9799fcb96) | Jul 18, 2022 |
| ASUSTek       | P5K SE/EPU                  | [b2b12a6837](https://linux-hardware.org/?probe=b2b12a6837) | Jul 18, 2022 |
| ASUSTek       | P5K                         | [f3c730853e](https://linux-hardware.org/?probe=f3c730853e) | Jul 18, 2022 |
| ASUSTek       | P5K                         | [581ed01922](https://linux-hardware.org/?probe=581ed01922) | Jul 18, 2022 |
| ASUSTek       | P8Z77-V                     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| ASRock        | X300M-STX                   | [150da602c4](https://linux-hardware.org/?probe=150da602c4) | Jul 17, 2022 |
| ASRock        | X300M-STX                   | [a46f6b3901](https://linux-hardware.org/?probe=a46f6b3901) | Jul 17, 2022 |
| Gigabyte      | F2A78M-DS2                  | [00a709911c](https://linux-hardware.org/?probe=00a709911c) | Jul 17, 2022 |
| Unknown       | Unknown                     | [e862207f95](https://linux-hardware.org/?probe=e862207f95) | Jul 15, 2022 |
| Gigabyte      | B450M S2H                   | [2fcccdc54a](https://linux-hardware.org/?probe=2fcccdc54a) | Jul 15, 2022 |
| HP            | 0B4Ch D                     | [a27d53815e](https://linux-hardware.org/?probe=a27d53815e) | Jul 15, 2022 |
| Gateway       | SX2803                      | [e92bbb285f](https://linux-hardware.org/?probe=e92bbb285f) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [e53d3eb407](https://linux-hardware.org/?probe=e53d3eb407) | Jul 15, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [85f6b3a720](https://linux-hardware.org/?probe=85f6b3a720) | Jul 14, 2022 |
| Intel         | DH67BL AAG10189-209         | [15c0aec8fc](https://linux-hardware.org/?probe=15c0aec8fc) | Jul 14, 2022 |
| Gigabyte      | H61M-DS2                    | [d0f1a65579](https://linux-hardware.org/?probe=d0f1a65579) | Jul 14, 2022 |
| Dell          | 09D2HH A00                  | [aadb1249e7](https://linux-hardware.org/?probe=aadb1249e7) | Jul 13, 2022 |
| Gigabyte      | H61M-DS2                    | [d581679f95](https://linux-hardware.org/?probe=d581679f95) | Jul 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [0c4f85c70e](https://linux-hardware.org/?probe=0c4f85c70e) | Jul 13, 2022 |
| ASUSTek       | H110M-R                     | [b1ec1ae2ba](https://linux-hardware.org/?probe=b1ec1ae2ba) | Jul 13, 2022 |
| ASRock        | H470M-HVS                   | [8f07cb2956](https://linux-hardware.org/?probe=8f07cb2956) | Jul 13, 2022 |
| Intel         | D946GZIS AAD66165-301       | [3d3076977a](https://linux-hardware.org/?probe=3d3076977a) | Jul 12, 2022 |
| Gigabyte      | B450M S2H                   | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [491e37bdfb](https://linux-hardware.org/?probe=491e37bdfb) | Jul 12, 2022 |
| Dell          | 0N4YC8 A00                  | [7bee96ebd2](https://linux-hardware.org/?probe=7bee96ebd2) | Jul 12, 2022 |
| ECS           | G31T-M9                     | [3465370e70](https://linux-hardware.org/?probe=3465370e70) | Jul 11, 2022 |
| MSI           | H110M PRO-VD                | [4fd6d22bdc](https://linux-hardware.org/?probe=4fd6d22bdc) | Jul 11, 2022 |
| ASRock        | H470M-HVS                   | [d670acc906](https://linux-hardware.org/?probe=d670acc906) | Jul 11, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [33c06e2d9c](https://linux-hardware.org/?probe=33c06e2d9c) | Jul 11, 2022 |
| MSI           | H110M PRO-VD                | [56a2a5762d](https://linux-hardware.org/?probe=56a2a5762d) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [abf6dfebe1](https://linux-hardware.org/?probe=abf6dfebe1) | Jul 11, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [6aeac582a4](https://linux-hardware.org/?probe=6aeac582a4) | Jul 11, 2022 |
| Dell          | 042P49 A00                  | [58ae3712ed](https://linux-hardware.org/?probe=58ae3712ed) | Jul 10, 2022 |
| ASUSTek       | PRIME H510M-A WIFI          | [7b4eeea730](https://linux-hardware.org/?probe=7b4eeea730) | Jul 10, 2022 |
| ASRock        | 990FX Killer                | [397d8bb63f](https://linux-hardware.org/?probe=397d8bb63f) | Jul 10, 2022 |
| ASRock        | Z77 Extreme6                | [fd8bd29c03](https://linux-hardware.org/?probe=fd8bd29c03) | Jul 09, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [8c3180c6f5](https://linux-hardware.org/?probe=8c3180c6f5) | Jul 09, 2022 |
| Dell          | 0N4YC8 A00                  | [f83cbbc674](https://linux-hardware.org/?probe=f83cbbc674) | Jul 08, 2022 |
| Dell          | 0N4YC8 A00                  | [dbda4f9266](https://linux-hardware.org/?probe=dbda4f9266) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [ec73826821](https://linux-hardware.org/?probe=ec73826821) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [ef38616f11](https://linux-hardware.org/?probe=ef38616f11) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [d6274d6dbb](https://linux-hardware.org/?probe=d6274d6dbb) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [d3f3acf23a](https://linux-hardware.org/?probe=d3f3acf23a) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [0d57ba971f](https://linux-hardware.org/?probe=0d57ba971f) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [1d775a2c62](https://linux-hardware.org/?probe=1d775a2c62) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [74b436de8d](https://linux-hardware.org/?probe=74b436de8d) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [8a7a7fc746](https://linux-hardware.org/?probe=8a7a7fc746) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [cfbc35dc7d](https://linux-hardware.org/?probe=cfbc35dc7d) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [6e1e9f1321](https://linux-hardware.org/?probe=6e1e9f1321) | Jul 08, 2022 |
| ASRock        | M3A UCC                     | [a7ffeac935](https://linux-hardware.org/?probe=a7ffeac935) | Jul 08, 2022 |
| Intel         | DH61CR AAG14064-204         | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [28a59cd061](https://linux-hardware.org/?probe=28a59cd061) | Jul 07, 2022 |
| Intel         | DQ35MP AAD82086-801         | [1f861ad92a](https://linux-hardware.org/?probe=1f861ad92a) | Jul 07, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [b806c8fc09](https://linux-hardware.org/?probe=b806c8fc09) | Jul 07, 2022 |
| Supermicro    | X10SRW-FB                   | [17c2ecc642](https://linux-hardware.org/?probe=17c2ecc642) | Jul 07, 2022 |
| ASRock        | B450M Pro4                  | [ff75212757](https://linux-hardware.org/?probe=ff75212757) | Jul 07, 2022 |
| Inventec      | D CLASS A02                 | [0fecc82851](https://linux-hardware.org/?probe=0fecc82851) | Jul 06, 2022 |
| congatec      | TS170 B.0                   | [b9469e26f8](https://linux-hardware.org/?probe=b9469e26f8) | Jul 06, 2022 |
| Gigabyte      | X99-UD4-CF                  | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| ECS           | G31T-M9                     | [f075057e96](https://linux-hardware.org/?probe=f075057e96) | Jul 06, 2022 |
| ASRockRack    | B565D4-V1L                  | [a363492ad6](https://linux-hardware.org/?probe=a363492ad6) | Jul 06, 2022 |
| Gigabyte      | B450M S2H V2                | [5da0f57567](https://linux-hardware.org/?probe=5da0f57567) | Jul 06, 2022 |
| MSI           | Creator TRX40               | [8d512a1405](https://linux-hardware.org/?probe=8d512a1405) | Jul 06, 2022 |
| Unknown       | Unknown                     | [7b1c72c3e7](https://linux-hardware.org/?probe=7b1c72c3e7) | Jul 06, 2022 |
| ASRock        | K10N78D                     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| HP            | 8433 11                     | [308e487f48](https://linux-hardware.org/?probe=308e487f48) | Jul 05, 2022 |
| MSI           | H61M-P31/W8                 | [ae5c00cbd0](https://linux-hardware.org/?probe=ae5c00cbd0) | Jul 05, 2022 |
| MSI           | H110M PRO-VD                | [cf4ef3e43e](https://linux-hardware.org/?probe=cf4ef3e43e) | Jul 05, 2022 |
| MSI           | H510M-A PRO                 | [f87b1f0fb5](https://linux-hardware.org/?probe=f87b1f0fb5) | Jul 05, 2022 |
| ASRock        | A300M-STX                   | [0e77b5637c](https://linux-hardware.org/?probe=0e77b5637c) | Jul 04, 2022 |
| ASUSTek       | H97-PLUS                    | [07a45bcfef](https://linux-hardware.org/?probe=07a45bcfef) | Jul 04, 2022 |
| Intel         | MAHOBAY                     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| MSI           | H510M-A PRO                 | [12a1f193b8](https://linux-hardware.org/?probe=12a1f193b8) | Jul 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9fd928b97f](https://linux-hardware.org/?probe=9fd928b97f) | Jul 03, 2022 |
| Gigabyte      | 945GCM-S2L                  | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| BESSTAR Te... | HM90                        | [064e176be8](https://linux-hardware.org/?probe=064e176be8) | Jul 02, 2022 |
| ASUSTek       | H97-PLUS                    | [85de5cfaff](https://linux-hardware.org/?probe=85de5cfaff) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| ASRock        | B450M Pro4                  | [64eae559ae](https://linux-hardware.org/?probe=64eae559ae) | Jul 02, 2022 |
| Gigabyte      | H81M-DS2V                   | [5f35ee7109](https://linux-hardware.org/?probe=5f35ee7109) | Jul 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d7d9387e6d](https://linux-hardware.org/?probe=d7d9387e6d) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [d0d9e7b5c7](https://linux-hardware.org/?probe=d0d9e7b5c7) | Jul 01, 2022 |
| MSI           | B75MA-E33                   | [482aec0a52](https://linux-hardware.org/?probe=482aec0a52) | Jun 30, 2022 |
| ASUSTek       | P5KPL-E                     | [c969c7cce8](https://linux-hardware.org/?probe=c969c7cce8) | Jun 30, 2022 |
| Dell          | 0D441T A01                  | [b205bc201e](https://linux-hardware.org/?probe=b205bc201e) | Jun 29, 2022 |
| Dell          | 0M858N A01                  | [6cc8dcd51e](https://linux-hardware.org/?probe=6cc8dcd51e) | Jun 29, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| ECS           | G41T-M16                    | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| Intel         | D945PLRN AAD32731-404       | [d9519690b8](https://linux-hardware.org/?probe=d9519690b8) | Jun 28, 2022 |
| ASUSTek       | B85M-G                      | [642e677d05](https://linux-hardware.org/?probe=642e677d05) | Jun 27, 2022 |
| ASUSTek       | H81M-P PLUS                 | [6c18625cb3](https://linux-hardware.org/?probe=6c18625cb3) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [60810eb934](https://linux-hardware.org/?probe=60810eb934) | Jun 27, 2022 |
| ASUSTek       | P5K                         | [e401eb71bc](https://linux-hardware.org/?probe=e401eb71bc) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [6ab12fa31e](https://linux-hardware.org/?probe=6ab12fa31e) | Jun 27, 2022 |
| EVGA          | 151-HE-E999                 | [2725b53d0c](https://linux-hardware.org/?probe=2725b53d0c) | Jun 27, 2022 |
| MSI           | Z170A GAMING PRO            | [70e3e75c86](https://linux-hardware.org/?probe=70e3e75c86) | Jun 27, 2022 |
| MSI           | 2A9C                        | [c4d999a9a5](https://linux-hardware.org/?probe=c4d999a9a5) | Jun 26, 2022 |
| Maxtang       | FP30 V1.0                   | [6d86a132d4](https://linux-hardware.org/?probe=6d86a132d4) | Jun 26, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [838a928e6a](https://linux-hardware.org/?probe=838a928e6a) | Jun 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c2e6e05eea](https://linux-hardware.org/?probe=c2e6e05eea) | Jun 25, 2022 |
| Unknown       | Unknown                     | [b3def4c8ad](https://linux-hardware.org/?probe=b3def4c8ad) | Jun 25, 2022 |
| Gigabyte      | M52LT-D3                    | [6c650dabf3](https://linux-hardware.org/?probe=6c650dabf3) | Jun 24, 2022 |
| Gigabyte      | B150-HD3P-CF                | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| Intel         | MAHOBAY                     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| Lenovo        | ThinkServer TS440           | [e68364c28e](https://linux-hardware.org/?probe=e68364c28e) | Jun 24, 2022 |
| Gigabyte      | H470M DS3H                  | [624ad307fc](https://linux-hardware.org/?probe=624ad307fc) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| HP            | 830C                        | [7e34e5c70d](https://linux-hardware.org/?probe=7e34e5c70d) | Jun 23, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [c44391986b](https://linux-hardware.org/?probe=c44391986b) | Jun 23, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [2c1f55aa8f](https://linux-hardware.org/?probe=2c1f55aa8f) | Jun 23, 2022 |
| ECS           | G31T-M9                     | [79e0e345f0](https://linux-hardware.org/?probe=79e0e345f0) | Jun 23, 2022 |
| Dell          | 0J8885                      | [06e5e2fe54](https://linux-hardware.org/?probe=06e5e2fe54) | Jun 23, 2022 |
| HP            | 3397                        | [3c7afd0ee2](https://linux-hardware.org/?probe=3c7afd0ee2) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [989b450d8b](https://linux-hardware.org/?probe=989b450d8b) | Jun 23, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [d5d735e981](https://linux-hardware.org/?probe=d5d735e981) | Jun 22, 2022 |
| ASUSTek       | H81M-P PLUS                 | [b91a1b0ded](https://linux-hardware.org/?probe=b91a1b0ded) | Jun 22, 2022 |
| Gigabyte      | B660M GAMING X DDR4         | [d2d5590419](https://linux-hardware.org/?probe=d2d5590419) | Jun 22, 2022 |
| MSI           | H110M PRO-VD                | [a46ae32016](https://linux-hardware.org/?probe=a46ae32016) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [1529cf29a5](https://linux-hardware.org/?probe=1529cf29a5) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [4a2493f02c](https://linux-hardware.org/?probe=4a2493f02c) | Jun 22, 2022 |
| Unknown       | Unknown                     | [6024015ecc](https://linux-hardware.org/?probe=6024015ecc) | Jun 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [273f19137a](https://linux-hardware.org/?probe=273f19137a) | Jun 21, 2022 |
| ASUSTek       | H110M-R                     | [49fca67e16](https://linux-hardware.org/?probe=49fca67e16) | Jun 21, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [fd01dae061](https://linux-hardware.org/?probe=fd01dae061) | Jun 21, 2022 |
| Gigabyte      | B360M H                     | [3b3898bab6](https://linux-hardware.org/?probe=3b3898bab6) | Jun 21, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| Gigabyte      | B360M H                     | [9302b49143](https://linux-hardware.org/?probe=9302b49143) | Jun 21, 2022 |
| ASUSTek       | P5G41T-M LE                 | [2ff86ed754](https://linux-hardware.org/?probe=2ff86ed754) | Jun 21, 2022 |
| Intel         | CD952                       | [da181703fa](https://linux-hardware.org/?probe=da181703fa) | Jun 21, 2022 |
| Unknown       | Unknown                     | [604913c4e4](https://linux-hardware.org/?probe=604913c4e4) | Jun 20, 2022 |
| ASUSTek       | P5GC-MX/1333                | [e7527331d5](https://linux-hardware.org/?probe=e7527331d5) | Jun 20, 2022 |
| Foxconn       | G33M03                      | [e66dc33431](https://linux-hardware.org/?probe=e66dc33431) | Jun 20, 2022 |
| HP            | ProLiant ML350 G5           | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e6bd544051](https://linux-hardware.org/?probe=e6bd544051) | Jun 20, 2022 |
| Gigabyte      | B450M S2H                   | [deae1c7af7](https://linux-hardware.org/?probe=deae1c7af7) | Jun 19, 2022 |
| Lenovo        | ThinkServer TS440           | [42bf4b080d](https://linux-hardware.org/?probe=42bf4b080d) | Jun 19, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [473e2262b2](https://linux-hardware.org/?probe=473e2262b2) | Jun 19, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [83858f351b](https://linux-hardware.org/?probe=83858f351b) | Jun 19, 2022 |
| Dell          | 00V62H A00                  | [b902ece510](https://linux-hardware.org/?probe=b902ece510) | Jun 19, 2022 |
| ASUSTek       | KGPE-D16                    | [8a0bcff648](https://linux-hardware.org/?probe=8a0bcff648) | Jun 19, 2022 |
| ASUSTek       | KGPE-D16                    | [2ce805f758](https://linux-hardware.org/?probe=2ce805f758) | Jun 19, 2022 |
| ASUSTek       | Z77-A                       | [b416c587af](https://linux-hardware.org/?probe=b416c587af) | Jun 18, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a6cb0e21fc](https://linux-hardware.org/?probe=a6cb0e21fc) | Jun 17, 2022 |
| Dell          | 0P9XHK A00                  | [e167c05dd2](https://linux-hardware.org/?probe=e167c05dd2) | Jun 17, 2022 |
| ASUSTek       | H110M-R                     | [575d907137](https://linux-hardware.org/?probe=575d907137) | Jun 17, 2022 |
| ASUSTek       | P5G41T-M LE                 | [9f392efe48](https://linux-hardware.org/?probe=9f392efe48) | Jun 17, 2022 |
| ASUSTek       | A7N8X2.0                    | [0078dfa592](https://linux-hardware.org/?probe=0078dfa592) | Jun 17, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [eb011c0886](https://linux-hardware.org/?probe=eb011c0886) | Jun 17, 2022 |
| MSI           | A68HM-E33 V2                | [244067b8a7](https://linux-hardware.org/?probe=244067b8a7) | Jun 17, 2022 |
| Dell          | 0NDYHG A01                  | [c4ed1ece70](https://linux-hardware.org/?probe=c4ed1ece70) | Jun 16, 2022 |
| Gigabyte      | B75-D3V                     | [3de9ecfb70](https://linux-hardware.org/?probe=3de9ecfb70) | Jun 16, 2022 |
| Gigabyte      | H81M-S2V                    | [de482da93c](https://linux-hardware.org/?probe=de482da93c) | Jun 15, 2022 |
| Gigabyte      | H81M-S2V                    | [2af43ca43d](https://linux-hardware.org/?probe=2af43ca43d) | Jun 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [16a9126560](https://linux-hardware.org/?probe=16a9126560) | Jun 15, 2022 |
| MSI           | H110M PRO-VD                | [9ac46f589f](https://linux-hardware.org/?probe=9ac46f589f) | Jun 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [0c8ec2807f](https://linux-hardware.org/?probe=0c8ec2807f) | Jun 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [54800ad012](https://linux-hardware.org/?probe=54800ad012) | Jun 14, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [863fc6a3bd](https://linux-hardware.org/?probe=863fc6a3bd) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cdbe0685be](https://linux-hardware.org/?probe=cdbe0685be) | Jun 13, 2022 |
| ASUSTek       | P8H77-M PRO                 | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Supermicro    | X8STi                       | [d99d775afe](https://linux-hardware.org/?probe=d99d775afe) | Jun 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3ddbde438b](https://linux-hardware.org/?probe=3ddbde438b) | Jun 12, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b15a9cd9ec](https://linux-hardware.org/?probe=b15a9cd9ec) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [530d14088b](https://linux-hardware.org/?probe=530d14088b) | Jun 11, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [55be0755f9](https://linux-hardware.org/?probe=55be0755f9) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [288ab3a8ad](https://linux-hardware.org/?probe=288ab3a8ad) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e7931e1d59](https://linux-hardware.org/?probe=e7931e1d59) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4624e51d0d](https://linux-hardware.org/?probe=4624e51d0d) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4d5e823219](https://linux-hardware.org/?probe=4d5e823219) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d185e26655](https://linux-hardware.org/?probe=d185e26655) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c184039865](https://linux-hardware.org/?probe=c184039865) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [96026aee3c](https://linux-hardware.org/?probe=96026aee3c) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a7feb8b173](https://linux-hardware.org/?probe=a7feb8b173) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8cf2ab21a1](https://linux-hardware.org/?probe=8cf2ab21a1) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [361ad1fd01](https://linux-hardware.org/?probe=361ad1fd01) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [2f0948a486](https://linux-hardware.org/?probe=2f0948a486) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [cbe79f811b](https://linux-hardware.org/?probe=cbe79f811b) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [128a4f95b3](https://linux-hardware.org/?probe=128a4f95b3) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [62c847aae6](https://linux-hardware.org/?probe=62c847aae6) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cdb0bc0ec](https://linux-hardware.org/?probe=0cdb0bc0ec) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c6ea351f57](https://linux-hardware.org/?probe=c6ea351f57) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a9a0fd0187](https://linux-hardware.org/?probe=a9a0fd0187) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e0610fc3ee](https://linux-hardware.org/?probe=e0610fc3ee) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [17e9ad5909](https://linux-hardware.org/?probe=17e9ad5909) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3ddd67d79c](https://linux-hardware.org/?probe=3ddd67d79c) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [52b1a2ddcc](https://linux-hardware.org/?probe=52b1a2ddcc) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [855eccf466](https://linux-hardware.org/?probe=855eccf466) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8e97ffd0ce](https://linux-hardware.org/?probe=8e97ffd0ce) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4c0f195f39](https://linux-hardware.org/?probe=4c0f195f39) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e525f8832b](https://linux-hardware.org/?probe=e525f8832b) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8511f3e652](https://linux-hardware.org/?probe=8511f3e652) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [44e4fe183c](https://linux-hardware.org/?probe=44e4fe183c) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [f8f771b95b](https://linux-hardware.org/?probe=f8f771b95b) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3c70a63df1](https://linux-hardware.org/?probe=3c70a63df1) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [ea7ec909e0](https://linux-hardware.org/?probe=ea7ec909e0) | Jun 11, 2022 |
| Dell          | 0TDG4V A01                  | [3da09dbe5d](https://linux-hardware.org/?probe=3da09dbe5d) | Jun 10, 2022 |
| ASRock        | G31M-VS2                    | [8da76dfd88](https://linux-hardware.org/?probe=8da76dfd88) | Jun 10, 2022 |
| Gigabyte      | H81M-DS2                    | [8f6316f63d](https://linux-hardware.org/?probe=8f6316f63d) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [25b0162512](https://linux-hardware.org/?probe=25b0162512) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [dec67b7ea7](https://linux-hardware.org/?probe=dec67b7ea7) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a1af74a271](https://linux-hardware.org/?probe=a1af74a271) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [5863863487](https://linux-hardware.org/?probe=5863863487) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4dd447cf4a](https://linux-hardware.org/?probe=4dd447cf4a) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b248c80824](https://linux-hardware.org/?probe=b248c80824) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [ec484ac5f1](https://linux-hardware.org/?probe=ec484ac5f1) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [fbfb5f5567](https://linux-hardware.org/?probe=fbfb5f5567) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [69177b9dd1](https://linux-hardware.org/?probe=69177b9dd1) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7b37f934d9](https://linux-hardware.org/?probe=7b37f934d9) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [f81bbaa809](https://linux-hardware.org/?probe=f81bbaa809) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [53cde78383](https://linux-hardware.org/?probe=53cde78383) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [958add1814](https://linux-hardware.org/?probe=958add1814) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [0045fbc083](https://linux-hardware.org/?probe=0045fbc083) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [4e319d922b](https://linux-hardware.org/?probe=4e319d922b) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [6d0ab85ca8](https://linux-hardware.org/?probe=6d0ab85ca8) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [057d965770](https://linux-hardware.org/?probe=057d965770) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [47adb91a17](https://linux-hardware.org/?probe=47adb91a17) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [e6c10e7c75](https://linux-hardware.org/?probe=e6c10e7c75) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [aa239405c6](https://linux-hardware.org/?probe=aa239405c6) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [c581adfc75](https://linux-hardware.org/?probe=c581adfc75) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [36a127b30b](https://linux-hardware.org/?probe=36a127b30b) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [c265928721](https://linux-hardware.org/?probe=c265928721) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [bc6f4accca](https://linux-hardware.org/?probe=bc6f4accca) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [495a331678](https://linux-hardware.org/?probe=495a331678) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [50d4873224](https://linux-hardware.org/?probe=50d4873224) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [e90c802b8a](https://linux-hardware.org/?probe=e90c802b8a) | Jun 10, 2022 |
| Dell          | 0X75JG A01                  | [04a5e20d9e](https://linux-hardware.org/?probe=04a5e20d9e) | Jun 10, 2022 |
| MSI           | X99S GAMING 7               | [d36fec156a](https://linux-hardware.org/?probe=d36fec156a) | Jun 10, 2022 |
| ASRock        | 970 Performance             | [d017602bb8](https://linux-hardware.org/?probe=d017602bb8) | Jun 10, 2022 |
| ASRock        | 970 Performance             | [a2afdf2651](https://linux-hardware.org/?probe=a2afdf2651) | Jun 10, 2022 |
| ASRockRack    | X470D4U                     | [bdf16fa487](https://linux-hardware.org/?probe=bdf16fa487) | Jun 09, 2022 |
| MSI           | B550-A PRO                  | [f549e0407f](https://linux-hardware.org/?probe=f549e0407f) | Jun 09, 2022 |
| Gigabyte      | B360M H                     | [94843ffed7](https://linux-hardware.org/?probe=94843ffed7) | Jun 09, 2022 |
| MSI           | H110M PRO-VD                | [d731f8ac03](https://linux-hardware.org/?probe=d731f8ac03) | Jun 09, 2022 |
| ASUSTek       | P5G41T-M LE                 | [6ae73c0b67](https://linux-hardware.org/?probe=6ae73c0b67) | Jun 09, 2022 |
| HP            | 085Ch                       | [357911a814](https://linux-hardware.org/?probe=357911a814) | Jun 08, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [6daae3f4db](https://linux-hardware.org/?probe=6daae3f4db) | Jun 08, 2022 |
| MSI           | H110M PRO-VD                | [aac1519759](https://linux-hardware.org/?probe=aac1519759) | Jun 08, 2022 |
| ASRock        | H470M-HVS                   | [0de4237fba](https://linux-hardware.org/?probe=0de4237fba) | Jun 08, 2022 |
| MSI           | H110M PRO-VD                | [0f1129c5f3](https://linux-hardware.org/?probe=0f1129c5f3) | Jun 08, 2022 |
| ASUSTek       | H110M-R                     | [75c023ebe1](https://linux-hardware.org/?probe=75c023ebe1) | Jun 08, 2022 |
| MSI           | H110M PRO-VH                | [ceae668577](https://linux-hardware.org/?probe=ceae668577) | Jun 07, 2022 |
| Gigabyte      | H81M-S2H                    | [4ca91078a2](https://linux-hardware.org/?probe=4ca91078a2) | Jun 07, 2022 |
| MSI           | B450M PRO-VDH MAX           | [11c7f60ef1](https://linux-hardware.org/?probe=11c7f60ef1) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [90b2505b78](https://linux-hardware.org/?probe=90b2505b78) | Jun 07, 2022 |
| MSI           | H110M PRO-VD                | [dbea5c81f2](https://linux-hardware.org/?probe=dbea5c81f2) | Jun 07, 2022 |
| ASUSTek       | B85M-G                      | [67662acc02](https://linux-hardware.org/?probe=67662acc02) | Jun 07, 2022 |
| MSI           | H81M-E33                    | [b2ce1d66a3](https://linux-hardware.org/?probe=b2ce1d66a3) | Jun 07, 2022 |
| ASRock        | B85M Pro3                   | [929408f1cd](https://linux-hardware.org/?probe=929408f1cd) | Jun 07, 2022 |
| Dell          | 040DDP A01                  | [94cce73a9d](https://linux-hardware.org/?probe=94cce73a9d) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [722cfa9375](https://linux-hardware.org/?probe=722cfa9375) | Jun 06, 2022 |
| PC Engines    | APU2                        | [269fa69513](https://linux-hardware.org/?probe=269fa69513) | Jun 06, 2022 |
| ASUSTek       | P8H61-MX                    | [a1b3220a4e](https://linux-hardware.org/?probe=a1b3220a4e) | Jun 06, 2022 |
| Foxconn       | 2ADA                        | [1242ad2894](https://linux-hardware.org/?probe=1242ad2894) | Jun 06, 2022 |
| ASRock        | H310CM-DVS                  | [2c46c3adb2](https://linux-hardware.org/?probe=2c46c3adb2) | Jun 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [9998592ce0](https://linux-hardware.org/?probe=9998592ce0) | Jun 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2aeb22bc4b](https://linux-hardware.org/?probe=2aeb22bc4b) | Jun 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [e3c84aefa8](https://linux-hardware.org/?probe=e3c84aefa8) | Jun 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [0948fcded8](https://linux-hardware.org/?probe=0948fcded8) | Jun 05, 2022 |
| MSI           | E350IA-E45                  | [048b860a2e](https://linux-hardware.org/?probe=048b860a2e) | Jun 05, 2022 |
| Unknown       | Unknown                     | [2a25ea86fc](https://linux-hardware.org/?probe=2a25ea86fc) | Jun 05, 2022 |
| Unknown       | Unknown                     | [e10faf271c](https://linux-hardware.org/?probe=e10faf271c) | Jun 05, 2022 |
| Dell          | 0WR7PY A01                  | [39c37e56ec](https://linux-hardware.org/?probe=39c37e56ec) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| BESSTAR Te... | HM90                        | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | [1f88a2c07c](https://linux-hardware.org/?probe=1f88a2c07c) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | [3cc513c431](https://linux-hardware.org/?probe=3cc513c431) | Jun 04, 2022 |
| MSI           | E350IA-E45                  | [cf188991af](https://linux-hardware.org/?probe=cf188991af) | Jun 04, 2022 |
| ASUSTek       | PRIME A320M-A               | [b610820278](https://linux-hardware.org/?probe=b610820278) | Jun 03, 2022 |
| Gigabyte      | B360M H                     | [8f5cd5eef5](https://linux-hardware.org/?probe=8f5cd5eef5) | Jun 03, 2022 |
| Gigabyte      | B360M H                     | [3cd0f35827](https://linux-hardware.org/?probe=3cd0f35827) | Jun 03, 2022 |
| Gigabyte      | M61PME-S2P                  | [a56a39a60e](https://linux-hardware.org/?probe=a56a39a60e) | Jun 03, 2022 |
| MSI           | H81M-P33                    | [c7974d4e6d](https://linux-hardware.org/?probe=c7974d4e6d) | Jun 03, 2022 |
| ASUSTek       | H81M-P PLUS                 | [8c60f1e8e0](https://linux-hardware.org/?probe=8c60f1e8e0) | Jun 03, 2022 |
| ASUSTek       | P5K                         | [2e621739e6](https://linux-hardware.org/?probe=2e621739e6) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b20f8a904c](https://linux-hardware.org/?probe=b20f8a904c) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [deaecc76bb](https://linux-hardware.org/?probe=deaecc76bb) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [65725a95b9](https://linux-hardware.org/?probe=65725a95b9) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a4622d1f55](https://linux-hardware.org/?probe=a4622d1f55) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e8019b4f83](https://linux-hardware.org/?probe=e8019b4f83) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [afba735e60](https://linux-hardware.org/?probe=afba735e60) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7f34664fe0](https://linux-hardware.org/?probe=7f34664fe0) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [feaafa4cfa](https://linux-hardware.org/?probe=feaafa4cfa) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [61260328d6](https://linux-hardware.org/?probe=61260328d6) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [5dcef6967d](https://linux-hardware.org/?probe=5dcef6967d) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3a2e3ed469](https://linux-hardware.org/?probe=3a2e3ed469) | Jun 03, 2022 |
| Gigabyte      | H57M-USB3                   | [ad3c50375c](https://linux-hardware.org/?probe=ad3c50375c) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7725e74369](https://linux-hardware.org/?probe=7725e74369) | Jun 02, 2022 |
| MSI           | H110M PRO-VD                | [cd124df84c](https://linux-hardware.org/?probe=cd124df84c) | Jun 02, 2022 |
| Gigabyte      | M68MT-S2                    | [c71933a046](https://linux-hardware.org/?probe=c71933a046) | Jun 02, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [459a6a7c75](https://linux-hardware.org/?probe=459a6a7c75) | Jun 02, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [b9eb4d507e](https://linux-hardware.org/?probe=b9eb4d507e) | Jun 02, 2022 |
| Dell          | 0J8885                      | [1b1eafbd15](https://linux-hardware.org/?probe=1b1eafbd15) | Jun 01, 2022 |
| Gigabyte      | 970A-DS3P                   | [272322b54a](https://linux-hardware.org/?probe=272322b54a) | Jun 01, 2022 |
| ASRock        | A320M-HDV R3.0              | [1b402ad8a4](https://linux-hardware.org/?probe=1b402ad8a4) | Jun 01, 2022 |
| Unknown       | Unknown                     | [bcb55ce8ce](https://linux-hardware.org/?probe=bcb55ce8ce) | Jun 01, 2022 |
| Gigabyte      | M68MT-S2                    | [24ef5903aa](https://linux-hardware.org/?probe=24ef5903aa) | Jun 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3a7e7b471a](https://linux-hardware.org/?probe=3a7e7b471a) | Jun 01, 2022 |
| Intel         | DH61BF AAG81311-101         | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| HP            | ProLiant ML110 Gen9         | [2940e1d0b2](https://linux-hardware.org/?probe=2940e1d0b2) | May 31, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4dad4a323a](https://linux-hardware.org/?probe=4dad4a323a) | May 31, 2022 |
| MSI           | A320M-HDV R4.0              | [c6f912a3cd](https://linux-hardware.org/?probe=c6f912a3cd) | May 31, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c60a969370](https://linux-hardware.org/?probe=c60a969370) | May 31, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [7bd2b1490a](https://linux-hardware.org/?probe=7bd2b1490a) | May 31, 2022 |
| ASUSTek       | P7H55-M SI                  | [bd7e895652](https://linux-hardware.org/?probe=bd7e895652) | May 31, 2022 |
| MSI           | G31TM-P21                   | [3ddbd38a08](https://linux-hardware.org/?probe=3ddbd38a08) | May 31, 2022 |
| Gigabyte      | M61PME-S2P                  | [6960eaa85b](https://linux-hardware.org/?probe=6960eaa85b) | May 31, 2022 |
| HP            | 158A                        | [7f7c6ae514](https://linux-hardware.org/?probe=7f7c6ae514) | May 31, 2022 |
| Gigabyte      | H61M-S2-B3                  | [3de5695c62](https://linux-hardware.org/?probe=3de5695c62) | May 30, 2022 |
| Gigabyte      | H61M-S2PV                   | [b002ab0fe8](https://linux-hardware.org/?probe=b002ab0fe8) | May 30, 2022 |
| Gigabyte      | M52L-S3                     | [1add8e904e](https://linux-hardware.org/?probe=1add8e904e) | May 30, 2022 |
| Gigabyte      | H61M-S2PV                   | [990a8757b8](https://linux-hardware.org/?probe=990a8757b8) | May 30, 2022 |
| Gigabyte      | M52L-S3                     | [e49b2962df](https://linux-hardware.org/?probe=e49b2962df) | May 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [33ac99c04e](https://linux-hardware.org/?probe=33ac99c04e) | May 30, 2022 |
| ASRock        | H470M-HVS                   | [b7404d28e0](https://linux-hardware.org/?probe=b7404d28e0) | May 30, 2022 |
| ASRock        | B450M-HDV R4.0              | [b6d663fde6](https://linux-hardware.org/?probe=b6d663fde6) | May 29, 2022 |
| Kllisre       | X99-B5 V1.1                 | [a4e80143d1](https://linux-hardware.org/?probe=a4e80143d1) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| Biostar       | X470GTQ                     | [44e1072418](https://linux-hardware.org/?probe=44e1072418) | May 28, 2022 |
| HP            | 213D A01                    | [1be94a04b6](https://linux-hardware.org/?probe=1be94a04b6) | May 28, 2022 |
| Unknown       | Unknown                     | [0ac7c4deee](https://linux-hardware.org/?probe=0ac7c4deee) | May 28, 2022 |
| BESSTAR Te... | HM80                        | [f507d65c2e](https://linux-hardware.org/?probe=f507d65c2e) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ed9c55ffc6](https://linux-hardware.org/?probe=ed9c55ffc6) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| ASUSTek       | P5K                         | [2b5230c5f8](https://linux-hardware.org/?probe=2b5230c5f8) | May 27, 2022 |
| ASUSTek       | P5K                         | [b816732403](https://linux-hardware.org/?probe=b816732403) | May 27, 2022 |
| ASRock        | AM2NF6G-VSTA                | [475179d795](https://linux-hardware.org/?probe=475179d795) | May 27, 2022 |
| MSI           | H110M PRO-VD                | [6c505927be](https://linux-hardware.org/?probe=6c505927be) | May 27, 2022 |
| Gigabyte      | B85M-D3H                    | [dc5f3161bd](https://linux-hardware.org/?probe=dc5f3161bd) | May 27, 2022 |
| ASRock        | 970M Pro3                   | [7c13c36e57](https://linux-hardware.org/?probe=7c13c36e57) | May 27, 2022 |
| ECS           | H61H2-M13                   | [6c5eea6e0a](https://linux-hardware.org/?probe=6c5eea6e0a) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e28ecda6a9](https://linux-hardware.org/?probe=e28ecda6a9) | May 27, 2022 |
| ASRock        | IMB-185                     | [f7b3b565a0](https://linux-hardware.org/?probe=f7b3b565a0) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [5b4a1a0b2d](https://linux-hardware.org/?probe=5b4a1a0b2d) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8a9debf1da](https://linux-hardware.org/?probe=8a9debf1da) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c34cf96051](https://linux-hardware.org/?probe=c34cf96051) | May 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | [305a4aa2be](https://linux-hardware.org/?probe=305a4aa2be) | May 26, 2022 |
| Gigabyte      | H410M S2H                   | [c7e011235c](https://linux-hardware.org/?probe=c7e011235c) | May 26, 2022 |
| MSI           | H110M PRO-VD                | [f50e4f5314](https://linux-hardware.org/?probe=f50e4f5314) | May 26, 2022 |
| American M... | K7S41GX                     | [b311270c22](https://linux-hardware.org/?probe=b311270c22) | May 26, 2022 |
| ASRock        | H470M-HVS                   | [134bd88895](https://linux-hardware.org/?probe=134bd88895) | May 26, 2022 |
| Gigabyte      | Z77-DS3H                    | [fe6eb0ff04](https://linux-hardware.org/?probe=fe6eb0ff04) | May 26, 2022 |
| ASUSTek       | H81M-K                      | [3fc005308d](https://linux-hardware.org/?probe=3fc005308d) | May 26, 2022 |
| Intel         | DZ77SL-50K AAG55115-300     | [a05a4109f7](https://linux-hardware.org/?probe=a05a4109f7) | May 26, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [544888143f](https://linux-hardware.org/?probe=544888143f) | May 25, 2022 |
| ECS           | G31T-M9                     | [cbc52e0724](https://linux-hardware.org/?probe=cbc52e0724) | May 25, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [c44b877046](https://linux-hardware.org/?probe=c44b877046) | May 25, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [29dd7760ba](https://linux-hardware.org/?probe=29dd7760ba) | May 25, 2022 |
| Packard Be... | IMEDIA S3840                | [d102437a6f](https://linux-hardware.org/?probe=d102437a6f) | May 25, 2022 |
| Foxconn       | G31MXP FAB:1.1              | [64552194de](https://linux-hardware.org/?probe=64552194de) | May 24, 2022 |
| Gigabyte      | H510M H                     | [4bf981574e](https://linux-hardware.org/?probe=4bf981574e) | May 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ca5eb0e4ff](https://linux-hardware.org/?probe=ca5eb0e4ff) | May 24, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [66b8c4e68c](https://linux-hardware.org/?probe=66b8c4e68c) | May 24, 2022 |
| MSI           | H110M PRO-VD                | [5f3d17f133](https://linux-hardware.org/?probe=5f3d17f133) | May 24, 2022 |
| Intel         | DX79SR AAG57199-200         | [0675f1755a](https://linux-hardware.org/?probe=0675f1755a) | May 24, 2022 |
| Gigabyte      | H61M-DS2                    | [1613ab8b42](https://linux-hardware.org/?probe=1613ab8b42) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [0e8f0ed773](https://linux-hardware.org/?probe=0e8f0ed773) | May 23, 2022 |
| Unknown       | Unknown                     | [98a5322922](https://linux-hardware.org/?probe=98a5322922) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [193d7daf36](https://linux-hardware.org/?probe=193d7daf36) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [0d1907cc6f](https://linux-hardware.org/?probe=0d1907cc6f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [ea8294c786](https://linux-hardware.org/?probe=ea8294c786) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [a888bc633f](https://linux-hardware.org/?probe=a888bc633f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [4277ebe7e7](https://linux-hardware.org/?probe=4277ebe7e7) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [6bfc4ef24f](https://linux-hardware.org/?probe=6bfc4ef24f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [3629d7c796](https://linux-hardware.org/?probe=3629d7c796) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [9938056162](https://linux-hardware.org/?probe=9938056162) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [02393f8ed7](https://linux-hardware.org/?probe=02393f8ed7) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [f8257427c6](https://linux-hardware.org/?probe=f8257427c6) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [3c545f2940](https://linux-hardware.org/?probe=3c545f2940) | May 23, 2022 |
| ECS           | H61H2-MV                    | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| MSI           | H81M-P33                    | [5694eb0d0e](https://linux-hardware.org/?probe=5694eb0d0e) | May 22, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [eaf9e6332b](https://linux-hardware.org/?probe=eaf9e6332b) | May 21, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [f697c39b33](https://linux-hardware.org/?probe=f697c39b33) | May 21, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [280302cc7b](https://linux-hardware.org/?probe=280302cc7b) | May 20, 2022 |
| Gigabyte      | G41MT-S2                    | [0245a34484](https://linux-hardware.org/?probe=0245a34484) | May 20, 2022 |
| ASUSTek       | H81M-R                      | [d29d7ee0ad](https://linux-hardware.org/?probe=d29d7ee0ad) | May 20, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [6e8eed720d](https://linux-hardware.org/?probe=6e8eed720d) | May 20, 2022 |
| Dell          | 0D6H9T A02                  | [3f87c84f7a](https://linux-hardware.org/?probe=3f87c84f7a) | May 20, 2022 |
| Intel         | CM-iAM/SBC-FITPC2i          | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [9330599ada](https://linux-hardware.org/?probe=9330599ada) | May 20, 2022 |
| MSI           | H110M PRO-VD                | [a9d54e08c9](https://linux-hardware.org/?probe=a9d54e08c9) | May 20, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [d26b453c29](https://linux-hardware.org/?probe=d26b453c29) | May 20, 2022 |
| MSI           | B550-A PRO                  | [373569ca56](https://linux-hardware.org/?probe=373569ca56) | May 20, 2022 |
| HP            | 8298                        | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| ASRock        | H470M-HVS                   | [b78055bf57](https://linux-hardware.org/?probe=b78055bf57) | May 19, 2022 |
| HP            | 158A                        | [befd0b5756](https://linux-hardware.org/?probe=befd0b5756) | May 18, 2022 |
| Gigabyte      | B75-D3V                     | [81bd72f465](https://linux-hardware.org/?probe=81bd72f465) | May 18, 2022 |
| MouseCompu... | B360M-ITX                   | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [05c3d14729](https://linux-hardware.org/?probe=05c3d14729) | May 18, 2022 |
| ASUSTek       | P8Z68-V                     | [4e8ebb2b51](https://linux-hardware.org/?probe=4e8ebb2b51) | May 17, 2022 |
| Gigabyte      | B75M-D2V                    | [6eba5e9bf2](https://linux-hardware.org/?probe=6eba5e9bf2) | May 17, 2022 |
| HP            | 1905                        | [eae1688df4](https://linux-hardware.org/?probe=eae1688df4) | May 17, 2022 |
| HP            | ProLiant MicroServer Gen... | [2a8a53c628](https://linux-hardware.org/?probe=2a8a53c628) | May 17, 2022 |
| ASRock        | H470M-HVS                   | [d71e59e4ef](https://linux-hardware.org/?probe=d71e59e4ef) | May 17, 2022 |
| Gigabyte      | G31M-ES2L                   | [1ab7586d5f](https://linux-hardware.org/?probe=1ab7586d5f) | May 17, 2022 |
| Dell          | 07N90W A01                  | [09d256b2ea](https://linux-hardware.org/?probe=09d256b2ea) | May 17, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| IP3 Tech      | TB20                        | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Gigabyte      | B75M-D2V                    | [86de85c736](https://linux-hardware.org/?probe=86de85c736) | May 16, 2022 |
| Gigabyte      | H81M-S2V                    | [f5817a11ec](https://linux-hardware.org/?probe=f5817a11ec) | May 16, 2022 |
| ASUSTek       | H97M-PLUS                   | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [e12a8b383f](https://linux-hardware.org/?probe=e12a8b383f) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [709552ce76](https://linux-hardware.org/?probe=709552ce76) | May 15, 2022 |
| Lenovo        | ThinkServer TS440           | [bde3f15809](https://linux-hardware.org/?probe=bde3f15809) | May 15, 2022 |
| Dell          | 0654JC A01                  | [ed0864a499](https://linux-hardware.org/?probe=ed0864a499) | May 14, 2022 |
| Dell          | 0654JC A01                  | [ed8e9e61b7](https://linux-hardware.org/?probe=ed8e9e61b7) | May 14, 2022 |
| Fujitsu       | D3813-A1 S26361-D3813-A1... | [f0e3c26d56](https://linux-hardware.org/?probe=f0e3c26d56) | May 14, 2022 |
| Dell          | 0JGM7F A00                  | [49bb61d936](https://linux-hardware.org/?probe=49bb61d936) | May 14, 2022 |
| Dell          | 0JGM7F A00                  | [1f5b1d9c0a](https://linux-hardware.org/?probe=1f5b1d9c0a) | May 14, 2022 |
| HP            | 2129                        | [d0babde387](https://linux-hardware.org/?probe=d0babde387) | May 14, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e39a3d8da2](https://linux-hardware.org/?probe=e39a3d8da2) | May 14, 2022 |
| Dell          | 0HY9JP A02                  | [5f98aaf42c](https://linux-hardware.org/?probe=5f98aaf42c) | May 14, 2022 |
| Gigabyte      | B450M S2H                   | [1185abcaaa](https://linux-hardware.org/?probe=1185abcaaa) | May 14, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| HP            | 158A                        | [a6bbb73cc3](https://linux-hardware.org/?probe=a6bbb73cc3) | May 13, 2022 |
| MSI           | 870S-C45                    | [eefd6f4979](https://linux-hardware.org/?probe=eefd6f4979) | May 12, 2022 |
| ASRock        | B365M Pro4-F                | [75587e5d3e](https://linux-hardware.org/?probe=75587e5d3e) | May 12, 2022 |
| ASRockRack    | X399D8A-2T                  | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| Medion        | Z370H4-EM                   | [2030abcd26](https://linux-hardware.org/?probe=2030abcd26) | May 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [41e7969ff2](https://linux-hardware.org/?probe=41e7969ff2) | May 12, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| ASRock        | H570M-ITX/ac                | [74f198b961](https://linux-hardware.org/?probe=74f198b961) | May 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f790f52fa7](https://linux-hardware.org/?probe=f790f52fa7) | May 11, 2022 |
| MSI           | H97M-E35                    | [fdd0f51b46](https://linux-hardware.org/?probe=fdd0f51b46) | May 10, 2022 |
| Gigabyte      | H370M D3H-CF                | [ffc3d3cf27](https://linux-hardware.org/?probe=ffc3d3cf27) | May 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [8575f58f88](https://linux-hardware.org/?probe=8575f58f88) | May 10, 2022 |
| MSI           | A68HM-E33 V2                | [dedc4ce0d5](https://linux-hardware.org/?probe=dedc4ce0d5) | May 10, 2022 |
| Dell          | 0KV3RP A00                  | [6ef8c2f171](https://linux-hardware.org/?probe=6ef8c2f171) | May 10, 2022 |
| ASUSTek       | PRIME H510M-E               | [0fed762686](https://linux-hardware.org/?probe=0fed762686) | May 10, 2022 |
| Dell          | 0T7D40 A01                  | [36b253f8bc](https://linux-hardware.org/?probe=36b253f8bc) | May 09, 2022 |
| Dell          | 0J37VM A01                  | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| AAEON         | MedPC-2000 V1.0             | [2375c6016b](https://linux-hardware.org/?probe=2375c6016b) | May 08, 2022 |
| Packard Be... | 1.XX                        | [d06b70fd87](https://linux-hardware.org/?probe=d06b70fd87) | May 08, 2022 |
| Packard Be... | 1.XX                        | [9f3bfe5333](https://linux-hardware.org/?probe=9f3bfe5333) | May 08, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c16ef97196](https://linux-hardware.org/?probe=c16ef97196) | May 08, 2022 |
| Alienware     | 0N43JM A00                  | [ec934dd53b](https://linux-hardware.org/?probe=ec934dd53b) | May 07, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [48cfd98488](https://linux-hardware.org/?probe=48cfd98488) | May 07, 2022 |
| Dell          | 0654JC A01                  | [ffd1f62dd4](https://linux-hardware.org/?probe=ffd1f62dd4) | May 07, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [4c2b573647](https://linux-hardware.org/?probe=4c2b573647) | May 07, 2022 |
| ASUSTek       | Z97M-PLUS                   | [d5210f6852](https://linux-hardware.org/?probe=d5210f6852) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | [d9c26e7eee](https://linux-hardware.org/?probe=d9c26e7eee) | May 07, 2022 |
| MSI           | C236A WORKSTATION           | [57d0654584](https://linux-hardware.org/?probe=57d0654584) | May 06, 2022 |
| HP            | 870C                        | [49c59843d3](https://linux-hardware.org/?probe=49c59843d3) | May 06, 2022 |
| HP            | 158A                        | [842aab71bd](https://linux-hardware.org/?probe=842aab71bd) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [033456f893](https://linux-hardware.org/?probe=033456f893) | May 06, 2022 |
| ASRock        | B450 Steel Legend           | [d2a6709c96](https://linux-hardware.org/?probe=d2a6709c96) | May 06, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [35aa84c6f4](https://linux-hardware.org/?probe=35aa84c6f4) | May 05, 2022 |
| Clientron     | Sunshine Valley             | [97a95fa1af](https://linux-hardware.org/?probe=97a95fa1af) | May 05, 2022 |
| ASUSTek       | VM42                        | [cb73da6c51](https://linux-hardware.org/?probe=cb73da6c51) | May 05, 2022 |
| ASUSTek       | VM42                        | [1fb131686b](https://linux-hardware.org/?probe=1fb131686b) | May 05, 2022 |
| Gigabyte      | H110M-DS2-CF                | [374070d210](https://linux-hardware.org/?probe=374070d210) | May 04, 2022 |
| Dell          | 0NDYHG A01                  | [2c2fd29320](https://linux-hardware.org/?probe=2c2fd29320) | May 03, 2022 |
| MSI           | MS-7053                     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| Gigabyte      | B560M D3H                   | [4a93a15de8](https://linux-hardware.org/?probe=4a93a15de8) | May 02, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [5e020f2247](https://linux-hardware.org/?probe=5e020f2247) | May 01, 2022 |
| Dell          | 0G919G A00                  | [f70b64d6b4](https://linux-hardware.org/?probe=f70b64d6b4) | May 01, 2022 |
| Positivo      | POS-EIH110EA                | [d0a20e98ac](https://linux-hardware.org/?probe=d0a20e98ac) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | [0132f4f349](https://linux-hardware.org/?probe=0132f4f349) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | [f2dccc8fb8](https://linux-hardware.org/?probe=f2dccc8fb8) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | [379c6be15c](https://linux-hardware.org/?probe=379c6be15c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | [620c550b04](https://linux-hardware.org/?probe=620c550b04) | May 01, 2022 |
| MSI           | B560M-A PRO                 | [21dbd84bbc](https://linux-hardware.org/?probe=21dbd84bbc) | Apr 30, 2022 |
| ASRock        | A300M-STX                   | [1c72c0839b](https://linux-hardware.org/?probe=1c72c0839b) | Apr 30, 2022 |
| MSI           | H87I                        | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| HP            | 18E7                        | [90a161bd80](https://linux-hardware.org/?probe=90a161bd80) | Apr 30, 2022 |
| ASUSTek       | P8Z68-V                     | [e6557824cb](https://linux-hardware.org/?probe=e6557824cb) | Apr 30, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| Supermicro    | X7DB8                       | [a2dd962374](https://linux-hardware.org/?probe=a2dd962374) | Apr 29, 2022 |
| Supermicro    | X11SSH-F                    | [0d475e91f3](https://linux-hardware.org/?probe=0d475e91f3) | Apr 29, 2022 |
| Hardkernel    | ODROID-H2                   | [c3303164ff](https://linux-hardware.org/?probe=c3303164ff) | Apr 29, 2022 |
| MSI           | H110M PRO-VD                | [e750916955](https://linux-hardware.org/?probe=e750916955) | Apr 29, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [6bb8f4af30](https://linux-hardware.org/?probe=6bb8f4af30) | Apr 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [94a47b7e85](https://linux-hardware.org/?probe=94a47b7e85) | Apr 28, 2022 |
| ASUSTek       | H110M-D D3                  | [e94f15dbb8](https://linux-hardware.org/?probe=e94f15dbb8) | Apr 27, 2022 |
| Dell          | 0M5DCD A00                  | [f420f53eca](https://linux-hardware.org/?probe=f420f53eca) | Apr 27, 2022 |
| Intel         | DH61BF AAG81311-101         | [f40f12b9be](https://linux-hardware.org/?probe=f40f12b9be) | Apr 27, 2022 |
| Dell          | 0M5DCD A00                  | [a8752656c1](https://linux-hardware.org/?probe=a8752656c1) | Apr 27, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [c82cd4f476](https://linux-hardware.org/?probe=c82cd4f476) | Apr 27, 2022 |
| ASRockRack    | B565D4-V1L                  | [bf0b5a06c9](https://linux-hardware.org/?probe=bf0b5a06c9) | Apr 27, 2022 |
| ASUSTek       | H110M-D D3                  | [abc1b924c9](https://linux-hardware.org/?probe=abc1b924c9) | Apr 27, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [8dafe7350b](https://linux-hardware.org/?probe=8dafe7350b) | Apr 27, 2022 |
| MSI           | Z370 SLI PLUS               | [75dbc4ddab](https://linux-hardware.org/?probe=75dbc4ddab) | Apr 27, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [f2fb45ef53](https://linux-hardware.org/?probe=f2fb45ef53) | Apr 26, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [d1e23f1023](https://linux-hardware.org/?probe=d1e23f1023) | Apr 26, 2022 |
| ASRock        | G31M-VS2                    | [912aa8341f](https://linux-hardware.org/?probe=912aa8341f) | Apr 25, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [71c83c7998](https://linux-hardware.org/?probe=71c83c7998) | Apr 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [0cbc3290f0](https://linux-hardware.org/?probe=0cbc3290f0) | Apr 25, 2022 |
| Pegatron      | Narra6                      | [0bfaba2999](https://linux-hardware.org/?probe=0bfaba2999) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | [d7d46c682c](https://linux-hardware.org/?probe=d7d46c682c) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | [4570a2caf7](https://linux-hardware.org/?probe=4570a2caf7) | Apr 25, 2022 |
| Foxconn       | 2ABF                        | [a7f5507dcd](https://linux-hardware.org/?probe=a7f5507dcd) | Apr 24, 2022 |
| Foxconn       | 2ABF                        | [e039df74b3](https://linux-hardware.org/?probe=e039df74b3) | Apr 24, 2022 |
| Gigabyte      | H110M-S2PV-CF               | [d076b5c763](https://linux-hardware.org/?probe=d076b5c763) | Apr 24, 2022 |
| MSI           | E350IA-E45                  | [8271a7f1d5](https://linux-hardware.org/?probe=8271a7f1d5) | Apr 23, 2022 |
| Intel         | X99                         | [1c9a508130](https://linux-hardware.org/?probe=1c9a508130) | Apr 23, 2022 |
| Unknown       | Unknown                     | [5d54074527](https://linux-hardware.org/?probe=5d54074527) | Apr 23, 2022 |
| Dell          | 0GY6Y8 A00                  | [cb93a4a05d](https://linux-hardware.org/?probe=cb93a4a05d) | Apr 23, 2022 |
| Supermicro    | X5DP8                       | [991180636d](https://linux-hardware.org/?probe=991180636d) | Apr 22, 2022 |
| Supermicro    | X5DP8                       | [3e50d9b6b4](https://linux-hardware.org/?probe=3e50d9b6b4) | Apr 22, 2022 |
| Dell          | 0HY9JP A00                  | [40d59bce4b](https://linux-hardware.org/?probe=40d59bce4b) | Apr 22, 2022 |
| Biostar       | TB250-BTC                   | [dd7f66f6dc](https://linux-hardware.org/?probe=dd7f66f6dc) | Apr 22, 2022 |
| Dell          | 073MMW A03                  | [f3ecf74145](https://linux-hardware.org/?probe=f3ecf74145) | Apr 22, 2022 |
| MSI           | 970A-G45                    | [35f8f0652d](https://linux-hardware.org/?probe=35f8f0652d) | Apr 21, 2022 |
| ASRock        | H61M-VG4                    | [a2452e4824](https://linux-hardware.org/?probe=a2452e4824) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [cb4bc274b3](https://linux-hardware.org/?probe=cb4bc274b3) | Apr 21, 2022 |
| Unknown       | RS780-SB700                 | [eb3aa5fa60](https://linux-hardware.org/?probe=eb3aa5fa60) | Apr 20, 2022 |
| ASUSTek       | M5A97                       | [8a262ac580](https://linux-hardware.org/?probe=8a262ac580) | Apr 19, 2022 |
| HP            | 18E7                        | [5f675779f1](https://linux-hardware.org/?probe=5f675779f1) | Apr 19, 2022 |
| ASUSTek       | M5A97                       | [3a20d298f9](https://linux-hardware.org/?probe=3a20d298f9) | Apr 19, 2022 |
| Intel         | X79G V2.x                   | [497807c732](https://linux-hardware.org/?probe=497807c732) | Apr 18, 2022 |
| Gigabyte      | B365M DS3H                  | [ed62d97841](https://linux-hardware.org/?probe=ed62d97841) | Apr 18, 2022 |
| ASUSTek       | PRIME H510M-A               | [59fb2af2c2](https://linux-hardware.org/?probe=59fb2af2c2) | Apr 18, 2022 |
| ASUSTek       | PRIME X399-A                | [e595903b64](https://linux-hardware.org/?probe=e595903b64) | Apr 18, 2022 |
| MSI           | G41M-P33 Combo              | [b3c127802c](https://linux-hardware.org/?probe=b3c127802c) | Apr 18, 2022 |
| ASUSTek       | H87-PLUS                    | [10e97d2168](https://linux-hardware.org/?probe=10e97d2168) | Apr 18, 2022 |
| Gigabyte      | A320M-H-CF                  | [6247b19a2f](https://linux-hardware.org/?probe=6247b19a2f) | Apr 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [dddd6b6edd](https://linux-hardware.org/?probe=dddd6b6edd) | Apr 18, 2022 |
| Gigabyte      | M61PME-S2P                  | [c354af5ec4](https://linux-hardware.org/?probe=c354af5ec4) | Apr 17, 2022 |
| J&W           | J1900T                      | [7c87f17ed7](https://linux-hardware.org/?probe=7c87f17ed7) | Apr 17, 2022 |
| ASUSTek       | PRIME X399-A                | [b2fe9a09fd](https://linux-hardware.org/?probe=b2fe9a09fd) | Apr 17, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [f0d5c82d74](https://linux-hardware.org/?probe=f0d5c82d74) | Apr 17, 2022 |
| Dell          | 0VHXCD A03                  | [290987223e](https://linux-hardware.org/?probe=290987223e) | Apr 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c8161370ea](https://linux-hardware.org/?probe=c8161370ea) | Apr 15, 2022 |
| HP            | 2129                        | [be64efcffd](https://linux-hardware.org/?probe=be64efcffd) | Apr 15, 2022 |
| ASRock        | G41M-VGS3                   | [62f424c896](https://linux-hardware.org/?probe=62f424c896) | Apr 15, 2022 |
| MSI           | B85I GAMING                 | [be865001b9](https://linux-hardware.org/?probe=be865001b9) | Apr 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [14f5389e9e](https://linux-hardware.org/?probe=14f5389e9e) | Apr 15, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [83dda83cdf](https://linux-hardware.org/?probe=83dda83cdf) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [92eaa72b3c](https://linux-hardware.org/?probe=92eaa72b3c) | Apr 14, 2022 |
| Gigabyte      | B85M-D3H                    | [a0c2314e31](https://linux-hardware.org/?probe=a0c2314e31) | Apr 14, 2022 |
| HP            | ProLiant ML330 G6           | [a62736690a](https://linux-hardware.org/?probe=a62736690a) | Apr 14, 2022 |
| Dell          | 0Y2MRG A00                  | [47f495eda5](https://linux-hardware.org/?probe=47f495eda5) | Apr 14, 2022 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [d00bde2a05](https://linux-hardware.org/?probe=d00bde2a05) | Apr 14, 2022 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [91a7810a37](https://linux-hardware.org/?probe=91a7810a37) | Apr 14, 2022 |
| ASUSTek       | Z97-A                       | [df33a057b6](https://linux-hardware.org/?probe=df33a057b6) | Apr 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [4c86ab8c47](https://linux-hardware.org/?probe=4c86ab8c47) | Apr 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3cc5e949a](https://linux-hardware.org/?probe=e3cc5e949a) | Apr 13, 2022 |
| ASUSTek       | Z97-A                       | [94783711b3](https://linux-hardware.org/?probe=94783711b3) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | [0ad016db29](https://linux-hardware.org/?probe=0ad016db29) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-A                | [cb3eb74403](https://linux-hardware.org/?probe=cb3eb74403) | Apr 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [58dab53fb1](https://linux-hardware.org/?probe=58dab53fb1) | Apr 13, 2022 |
| ASRockRack    | ROMED8-2T                   | [600b198520](https://linux-hardware.org/?probe=600b198520) | Apr 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [11ca71a8e4](https://linux-hardware.org/?probe=11ca71a8e4) | Apr 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Debian 11               | 1584     | 56.15%  |
| Debian 10               | 712      | 25.24%  |
| Debian Testing          | 222      | 7.87%   |
| Debian 9                | 144      | 5.1%    |
| Debian Unstable         | 114      | 4.04%   |
| Debian 8                | 21       | 0.74%   |
| Debian 11-updates       | 13       | 0.46%   |
| Debian 7                | 4        | 0.14%   |
| Debian Testing/unstable | 2        | 0.07%   |
| Debian 21               | 2        | 0.07%   |
| Debian Sid              | 1        | 0.04%   |
| Debian 16               | 1        | 0.04%   |
| Debian                  | 1        | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Debian | 2742     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.0-7-amd64       | 482      | 15.69%  |
| 5.10.0-8-amd64       | 238      | 7.75%   |
| 5.10.0-9-amd64       | 119      | 3.87%   |
| 5.10.0-13-amd64      | 82       | 2.67%   |
| 5.10.0-2-amd64       | 79       | 2.57%   |
| 5.10.0-11-amd64      | 72       | 2.34%   |
| 5.10.0-10-amd64      | 68       | 2.21%   |
| 5.10.0-16-amd64      | 64       | 2.08%   |
| 4.19.0-6-amd64       | 55       | 1.79%   |
| 4.19.0-16-amd64      | 52       | 1.69%   |
| 4.19.0-14-amd64      | 52       | 1.69%   |
| 4.19.0-13-amd64      | 49       | 1.6%    |
| 4.19.0-9-amd64       | 48       | 1.56%   |
| 4.19.0-17-amd64      | 48       | 1.56%   |
| 5.10.0-14-amd64      | 47       | 1.53%   |
| 4.19.0-8-amd64       | 47       | 1.53%   |
| 5.10.0-17-amd64      | 39       | 1.27%   |
| 4.19.0-12-amd64      | 38       | 1.24%   |
| 5.15.0-2-amd64       | 36       | 1.17%   |
| 4.9.0-8-amd64        | 31       | 1.01%   |
| 5.10.0-15-amd64      | 29       | 0.94%   |
| 4.19.0-10-amd64      | 29       | 0.94%   |
| 5.6.0-2-amd64        | 28       | 0.91%   |
| 5.10.0-18-amd64      | 28       | 0.91%   |
| 5.10.0-12-amd64      | 28       | 0.91%   |
| 5.18.0-2-amd64       | 20       | 0.65%   |
| 5.7.0-1-amd64        | 19       | 0.62%   |
| 5.10.0-6-amd64       | 19       | 0.62%   |
| 4.9.0-9-amd64        | 19       | 0.62%   |
| 5.4.0-4-amd64        | 18       | 0.59%   |
| 4.9.0-11-amd64       | 18       | 0.59%   |
| 4.19.0-5-amd64       | 18       | 0.59%   |
| 5.8.0-2-amd64        | 16       | 0.52%   |
| 4.19.0-11-amd64      | 16       | 0.52%   |
| 5.9.0-1-amd64        | 15       | 0.49%   |
| 5.18.0-0.bpo.1-amd64 | 15       | 0.49%   |
| 5.16.0-0.bpo.4-amd64 | 15       | 0.49%   |
| 5.10.0-4-amd64       | 15       | 0.49%   |
| 5.8.0-3-amd64        | 14       | 0.46%   |
| 5.7.0-2-amd64        | 14       | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 1447     | 49.39%  |
| 4.19.0  | 491      | 16.76%  |
| 4.9.0   | 108      | 3.69%   |
| 5.18.0  | 67       | 2.29%   |
| 5.9.0   | 59       | 2.01%   |
| 5.8.0   | 56       | 1.91%   |
| 5.16.0  | 54       | 1.84%   |
| 5.15.0  | 54       | 1.84%   |
| 5.7.0   | 53       | 1.81%   |
| 5.6.0   | 49       | 1.67%   |
| 5.4.0   | 44       | 1.5%    |
| 5.13.19 | 38       | 1.3%    |
| 5.14.0  | 31       | 1.06%   |
| 5.17.0  | 25       | 0.85%   |
| 5.11.22 | 19       | 0.65%   |
| 5.3.0   | 18       | 0.61%   |
| 5.5.0   | 14       | 0.48%   |
| 5.19.0  | 14       | 0.48%   |
| 5.15.39 | 13       | 0.44%   |
| 5.15.35 | 13       | 0.44%   |
| 3.16.0  | 10       | 0.34%   |
| 5.4.106 | 9        | 0.31%   |
| 4.18.0  | 9        | 0.31%   |
| 5.2.0   | 8        | 0.27%   |
| 5.4.44  | 7        | 0.24%   |
| 5.15.53 | 7        | 0.24%   |
| 4.15.18 | 7        | 0.24%   |
| 5.4.65  | 6        | 0.2%    |
| 5.15.30 | 6        | 0.2%    |
| 5.13.0  | 5        | 0.17%   |
| 4.17.0  | 5        | 0.17%   |
| 5.8.16  | 4        | 0.14%   |
| 5.4.78  | 4        | 0.14%   |
| 5.4.41  | 4        | 0.14%   |
| 5.4.119 | 4        | 0.14%   |
| 5.0.21  | 4        | 0.14%   |
| 5.4.28  | 3        | 0.1%    |
| 5.4.114 | 3        | 0.1%    |
| 5.3.6   | 3        | 0.1%    |
| 5.3.13  | 3        | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 1472     | 50.39%  |
| 4.19    | 495      | 16.95%  |
| 4.9     | 113      | 3.87%   |
| 5.15    | 99       | 3.39%   |
| 5.4     | 97       | 3.32%   |
| 5.18    | 71       | 2.43%   |
| 5.9     | 62       | 2.12%   |
| 5.8     | 62       | 2.12%   |
| 5.16    | 58       | 1.99%   |
| 5.7     | 57       | 1.95%   |
| 5.6     | 53       | 1.81%   |
| 5.13    | 49       | 1.68%   |
| 5.14    | 34       | 1.16%   |
| 5.11    | 30       | 1.03%   |
| 5.3     | 29       | 0.99%   |
| 5.17    | 29       | 0.99%   |
| 5.5     | 17       | 0.58%   |
| 5.19    | 16       | 0.55%   |
| 4.15    | 11       | 0.38%   |
| 4.18    | 10       | 0.34%   |
| 3.16    | 10       | 0.34%   |
| 5.2     | 8        | 0.27%   |
| 5.0     | 8        | 0.27%   |
| 4.17    | 5        | 0.17%   |
| 5.12    | 3        | 0.1%    |
| 5.1     | 3        | 0.1%    |
| 4.16    | 3        | 0.1%    |
| 4.1     | 3        | 0.1%    |
| 4.20    | 2        | 0.07%   |
| 4.14    | 2        | 0.07%   |
| 4.13    | 2        | 0.07%   |
| 6.0     | 1        | 0.03%   |
| 4.6     | 1        | 0.03%   |
| 4.5     | 1        | 0.03%   |
| 4.4     | 1        | 0.03%   |
| 4.3     | 1        | 0.03%   |
| 4.2     | 1        | 0.03%   |
| 3.4     | 1        | 0.03%   |
| 3.2     | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 2651     | 96.65%  |
| i686    | 75       | 2.73%   |
| riscv64 | 5        | 0.18%   |
| armv7l  | 4        | 0.15%   |
| ppc64   | 3        | 0.11%   |
| sh4a    | 1        | 0.04%   |
| ppc64le | 1        | 0.04%   |
| mips64  | 1        | 0.04%   |
| armv6l  | 1        | 0.04%   |
| aarch64 | 1        | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 1064     | 37.92%  |
| GNOME            | 480      | 17.11%  |
| XFCE             | 334      | 11.9%   |
| KDE5             | 310      | 11.05%  |
| MATE             | 134      | 4.78%   |
| X-Cinnamon       | 92       | 3.28%   |
| Cinnamon         | 80       | 2.85%   |
| KDE              | 76       | 2.71%   |
| LXDE             | 64       | 2.28%   |
| LXQt             | 42       | 1.5%    |
| i3               | 23       | 0.82%   |
| Openbox          | 22       | 0.78%   |
| GNOME Flashback  | 17       | 0.61%   |
| lightdm-xsession | 16       | 0.57%   |
| Trinity          | 10       | 0.36%   |
| Budgie           | 10       | 0.36%   |
| GNOME Classic    | 8        | 0.29%   |
| awesome          | 5        | 0.18%   |
| KDE4             | 4        | 0.14%   |
| fluxbox          | 4        | 0.14%   |
| sway             | 3        | 0.11%   |
| Enlightenment    | 2        | 0.07%   |
| xmonad           | 1        | 0.04%   |
| UKUI             | 1        | 0.04%   |
| i3-with-shmlog   | 1        | 0.04%   |
| GNUstep          | 1        | 0.04%   |
| DWM              | 1        | 0.04%   |
| default          | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1504     | 53.96%  |
| Unknown | 669      | 24%     |
| Tty     | 368      | 13.2%   |
| Wayland | 246      | 8.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1492     | 53.34%  |
| GDM     | 345      | 12.33%  |
| LightDM | 327      | 11.69%  |
| SDDM    | 294      | 10.51%  |
| TDM     | 249      | 8.9%    |
| GDM3    | 57       | 2.04%   |
| XDM     | 11       | 0.39%   |
| SLiM    | 10       | 0.36%   |
| NODM    | 6        | 0.21%   |
| KDM     | 4        | 0.14%   |
| WDM     | 1        | 0.04%   |
| Ly      | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 864      | 31.06%  |
| ru_RU   | 641      | 23.04%  |
| Unknown | 261      | 9.38%   |
| de_DE   | 142      | 5.1%    |
| en_GB   | 128      | 4.6%    |
| fr_FR   | 124      | 4.46%   |
| pt_BR   | 94       | 3.38%   |
| es_ES   | 70       | 2.52%   |
| it_IT   | 51       | 1.83%   |
| en_AU   | 45       | 1.62%   |
| en_CA   | 36       | 1.29%   |
| C       | 30       | 1.08%   |
| pl_PL   | 24       | 0.86%   |
| en_IN   | 16       | 0.58%   |
| en_IE   | 16       | 0.58%   |
| ja_JP   | 15       | 0.54%   |
| es_AR   | 15       | 0.54%   |
| hu_HU   | 13       | 0.47%   |
| es_VE   | 12       | 0.43%   |
| zh_CN   | 11       | 0.4%    |
| pt_PT   | 11       | 0.4%    |
| de_AT   | 10       | 0.36%   |
| nl_BE   | 9        | 0.32%   |
| cs_CZ   | 9        | 0.32%   |
| es_MX   | 8        | 0.29%   |
| nl_NL   | 7        | 0.25%   |
| de_CH   | 7        | 0.25%   |
| sv_SE   | 6        | 0.22%   |
| ru_UA   | 6        | 0.22%   |
| en_ZA   | 6        | 0.22%   |
| es_CL   | 5        | 0.18%   |
| uk_UA   | 4        | 0.14%   |
| hr_HR   | 4        | 0.14%   |
| fr_CH   | 4        | 0.14%   |
| fr_BE   | 4        | 0.14%   |
| eu_ES   | 4        | 0.14%   |
| es_CO   | 4        | 0.14%   |
| en_NZ   | 4        | 0.14%   |
| el_GR   | 4        | 0.14%   |
| ca_ES   | 4        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1870     | 67.05%  |
| EFI  | 919      | 32.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 1845     | 66.49%  |
| Overlay    | 585      | 21.08%  |
| Btrfs      | 111      | 4%      |
| Unknown    | 81       | 2.92%   |
| Zfs        | 58       | 2.09%   |
| Xfs        | 46       | 1.66%   |
| Ext3       | 20       | 0.72%   |
| Ext2       | 9        | 0.32%   |
| Tmpfs      | 5        | 0.18%   |
| Rootfs     | 5        | 0.18%   |
| Aufs       | 3        | 0.11%   |
| XXXXXXX    | 2        | 0.07%   |
| Jfs        | 2        | 0.07%   |
| F2fs       | 2        | 0.07%   |
| Fuse.sshfs | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1170     | 41.61%  |
| MBR     | 1032     | 36.7%   |
| Unknown | 610      | 21.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2233     | 80.53%  |
| Yes       | 540      | 19.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1678     | 60.45%  |
| Yes       | 1098     | 39.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 775      | 28.26%  |
| Gigabyte Technology | 472      | 17.21%  |
| ASRock              | 298      | 10.87%  |
| MSI                 | 284      | 10.36%  |
| Dell                | 174      | 6.35%   |
| Hewlett-Packard     | 158      | 5.76%   |
| Intel               | 86       | 3.14%   |
| Lenovo              | 76       | 2.77%   |
| ECS                 | 48       | 1.75%   |
| Unknown             | 42       | 1.53%   |
| Foxconn             | 33       | 1.2%    |
| Fujitsu             | 24       | 0.88%   |
| Supermicro          | 23       | 0.84%   |
| Acer                | 23       | 0.84%   |
| Biostar             | 18       | 0.66%   |
| ASRockRack          | 18       | 0.66%   |
| Pegatron            | 15       | 0.55%   |
| AZW                 | 13       | 0.47%   |
| Positivo            | 10       | 0.36%   |
| Shuttle             | 9        | 0.33%   |
| Huanan              | 9        | 0.33%   |
| Fujitsu Siemens     | 9        | 0.33%   |
| Apple               | 8        | 0.29%   |
| Medion              | 7        | 0.26%   |
| Google              | 5        | 0.18%   |
| Packard Bell        | 4        | 0.15%   |
| Inventec            | 4        | 0.15%   |
| Hardkernel          | 4        | 0.15%   |
| Gateway             | 4        | 0.15%   |
| BESSTAR Tech        | 4        | 0.15%   |
| Alienware           | 4        | 0.15%   |
| Wistron             | 3        | 0.11%   |
| PCWare              | 3        | 0.11%   |
| PC Engines          | 3        | 0.11%   |
| AOpen               | 3        | 0.11%   |
| YANYU               | 2        | 0.07%   |
| Thecus              | 2        | 0.07%   |
| Semp Toshiba        | 2        | 0.07%   |
| Qbex                | 2        | 0.07%   |
| Itautec             | 2        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 108      | 3.94%   |
| ASUS S20 K29               | 55       | 2.01%   |
| Unknown                    | 46       | 1.68%   |
| MSI MS-7996                | 35       | 1.28%   |
| ECS G31T-M9                | 20       | 0.73%   |
| ASRock H470M-HVS           | 20       | 0.73%   |
| MSI MS-7817                | 19       | 0.69%   |
| ASUS PRIME H510M-A         | 19       | 0.69%   |
| Gigabyte H81M-S2V          | 17       | 0.62%   |
| Gigabyte H410M S2H         | 16       | 0.58%   |
| ECS H61H2-M13              | 16       | 0.58%   |
| Dell OptiPlex 7010         | 14       | 0.51%   |
| ASUS P8H61-M LX3 R2.0      | 14       | 0.51%   |
| ASUS PRIME A320M-K         | 12       | 0.44%   |
| Gigabyte B450M DS3H        | 11       | 0.4%    |
| ASUS TUF Gaming X570-PLUS  | 11       | 0.4%    |
| MSI MS-7C56                | 10       | 0.36%   |
| Gigabyte B450M S2H         | 10       | 0.36%   |
| ASUS PRIME B450M-A         | 10       | 0.36%   |
| ASRock B450M Pro4          | 10       | 0.36%   |
| MSI MS-7B79                | 9        | 0.33%   |
| ASUS PRIME X370-PRO        | 9        | 0.33%   |
| ASRock H61M-VG4            | 9        | 0.33%   |
| MSI MS-7721                | 8        | 0.29%   |
| Gigabyte H61M-S2PV         | 8        | 0.29%   |
| ASUS P8H61-M LX3 PLUS R2.0 | 8        | 0.29%   |
| ASUS M5A78L-M/USB3         | 8        | 0.29%   |
| ASUS H110M-R               | 8        | 0.29%   |
| ASRock B450 Pro4           | 8        | 0.29%   |
| MSI MS-7C84                | 7        | 0.26%   |
| HP Z620 Workstation        | 7        | 0.26%   |
| HP ProLiant MicroServer    | 7        | 0.26%   |
| Gigabyte X570 AORUS ELITE  | 7        | 0.26%   |
| Gigabyte B360M H           | 7        | 0.26%   |
| Gigabyte 970A-DS3P         | 7        | 0.26%   |
| Fujitsu ESPRIMO P720       | 7        | 0.26%   |
| Dell OptiPlex 760          | 7        | 0.26%   |
| Dell OptiPlex 3020         | 7        | 0.26%   |
| ASUS PRIME X570-PRO        | 7        | 0.26%   |
| ASUS P8H67-M               | 7        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 144      | 5.25%   |
| ASUS All               | 108      | 3.94%   |
| Dell OptiPlex          | 95       | 3.46%   |
| ASUS S20               | 55       | 2.01%   |
| ASUS ROG               | 51       | 1.86%   |
| Unknown                | 46       | 1.68%   |
| HP Compaq              | 43       | 1.57%   |
| ASUS TUF               | 41       | 1.5%    |
| Lenovo ThinkCentre     | 39       | 1.42%   |
| MSI MS-7996            | 35       | 1.28%   |
| Dell Precision         | 33       | 1.2%    |
| ASUS P8H61-M           | 31       | 1.13%   |
| Gigabyte B450M         | 28       | 1.02%   |
| HP EliteDesk           | 21       | 0.77%   |
| Gigabyte X570          | 20       | 0.73%   |
| ECS G31T-M9            | 20       | 0.73%   |
| ASRock H470M-HVS       | 20       | 0.73%   |
| MSI MS-7817            | 19       | 0.69%   |
| HP ProLiant            | 19       | 0.69%   |
| ASRock B450M           | 18       | 0.66%   |
| Gigabyte H81M-S2V      | 17       | 0.62%   |
| Gigabyte H410M         | 17       | 0.62%   |
| ASUS PRO               | 17       | 0.62%   |
| ASUS M5A78L-M          | 17       | 0.62%   |
| Acer Aspire            | 17       | 0.62%   |
| ECS H61H2-M13          | 16       | 0.58%   |
| ASRock B450            | 16       | 0.58%   |
| Lenovo ThinkStation    | 12       | 0.44%   |
| Fujitsu ESPRIMO        | 12       | 0.44%   |
| ASUS P5G41T-M          | 12       | 0.44%   |
| ASRock X570            | 12       | 0.44%   |
| Lenovo IdeaCentre      | 11       | 0.4%    |
| HP ProDesk             | 11       | 0.4%    |
| Dell Inspiron          | 11       | 0.4%    |
| ASUS M5A97             | 11       | 0.4%    |
| MSI MS-7C56            | 10       | 0.36%   |
| Gigabyte GA-78LMT-USB3 | 10       | 0.36%   |
| Gigabyte B550          | 10       | 0.36%   |
| Dell XPS               | 10       | 0.36%   |
| ASUS P8H67-M           | 10       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 277      | 10.1%   |
| 2012    | 268      | 9.77%   |
| 2020    | 257      | 9.37%   |
| 2013    | 233      | 8.5%    |
| 2019    | 208      | 7.59%   |
| 2011    | 205      | 7.48%   |
| 2014    | 161      | 5.87%   |
| 2021    | 159      | 5.8%    |
| 2017    | 157      | 5.73%   |
| 2009    | 154      | 5.62%   |
| 2015    | 145      | 5.29%   |
| 2010    | 121      | 4.41%   |
| 2016    | 106      | 3.87%   |
| 2008    | 104      | 3.79%   |
| 2007    | 83       | 3.03%   |
| 2006    | 33       | 1.2%    |
| 2022    | 21       | 0.77%   |
| 2005    | 17       | 0.62%   |
| Unknown | 15       | 0.55%   |
| 2004    | 8        | 0.29%   |
| 2003    | 5        | 0.18%   |
| 2001    | 3        | 0.11%   |
| 2002    | 1        | 0.04%   |
| 2000    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2742     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2713     | 98.76%  |
| Enabled  | 34       | 1.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2729     | 99.53%  |
| Yes  | 13       | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 551      | 19.84%  |
| 8.01-16.0       | 463      | 16.67%  |
| 4.01-8.0        | 462      | 16.64%  |
| 3.01-4.0        | 457      | 16.46%  |
| 32.01-64.0      | 362      | 13.04%  |
| 64.01-256.0     | 199      | 7.17%   |
| 1.01-2.0        | 115      | 4.14%   |
| 24.01-32.0      | 68       | 2.45%   |
| 2.01-3.0        | 53       | 1.91%   |
| 0.51-1.0        | 20       | 0.72%   |
| More than 256.0 | 13       | 0.47%   |
| 0.01-0.5        | 8        | 0.29%   |
| Unknown         | 6        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 726      | 24.43%  |
| 1.01-2.0    | 602      | 20.26%  |
| 2.01-3.0    | 479      | 16.12%  |
| 4.01-8.0    | 423      | 14.23%  |
| 3.01-4.0    | 288      | 9.69%   |
| 8.01-16.0   | 195      | 6.56%   |
| 0.01-0.5    | 108      | 3.63%   |
| 16.01-24.0  | 78       | 2.62%   |
| 32.01-64.0  | 29       | 0.98%   |
| 24.01-32.0  | 25       | 0.84%   |
| 64.01-256.0 | 11       | 0.37%   |
| Unknown     | 8        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1247     | 44.2%   |
| 2       | 644      | 22.83%  |
| 3       | 384      | 13.61%  |
| 4       | 249      | 8.83%   |
| 5       | 117      | 4.15%   |
| 6       | 66       | 2.34%   |
| 7       | 34       | 1.21%   |
| 8       | 27       | 0.96%   |
| 0       | 12       | 0.43%   |
| 9       | 11       | 0.39%   |
| 10      | 9        | 0.32%   |
| 11      | 6        | 0.21%   |
| 12      | 4        | 0.14%   |
| 13      | 3        | 0.11%   |
| Unknown | 2        | 0.07%   |
| 46      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |
| 27      | 1        | 0.04%   |
| 17      | 1        | 0.04%   |
| 16      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1737     | 62.8%   |
| Yes       | 1029     | 37.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2722     | 99.27%  |
| No        | 20       | 0.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1968     | 71.2%   |
| Yes       | 796      | 28.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2156     | 77.78%  |
| Yes       | 616      | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 712      | 25.92%  |
| USA          | 389      | 14.16%  |
| Germany      | 250      | 9.1%    |
| France       | 162      | 5.9%    |
| Brazil       | 148      | 5.39%   |
| Spain        | 108      | 3.93%   |
| UK           | 92       | 3.35%   |
| Italy        | 80       | 2.91%   |
| Australia    | 58       | 2.11%   |
| Canada       | 56       | 2.04%   |
| Poland       | 43       | 1.57%   |
| Netherlands  | 37       | 1.35%   |
| Switzerland  | 35       | 1.27%   |
| Ukraine      | 34       | 1.24%   |
| Hungary      | 31       | 1.13%   |
| Austria      | 28       | 1.02%   |
| Belgium      | 27       | 0.98%   |
| Finland      | 24       | 0.87%   |
| Sweden       | 23       | 0.84%   |
| China        | 23       | 0.84%   |
| Portugal     | 21       | 0.76%   |
| Argentina    | 21       | 0.76%   |
| India        | 19       | 0.69%   |
| Czechia      | 19       | 0.69%   |
| Mexico       | 17       | 0.62%   |
| Japan        | 17       | 0.62%   |
| Venezuela    | 15       | 0.55%   |
| Norway       | 14       | 0.51%   |
| Bulgaria     | 14       | 0.51%   |
| Romania      | 12       | 0.44%   |
| Turkey       | 10       | 0.36%   |
| South Africa | 10       | 0.36%   |
| Belarus      | 10       | 0.36%   |
| Pakistan     | 9        | 0.33%   |
| Greece       | 9        | 0.33%   |
| Denmark      | 9        | 0.33%   |
| Croatia      | 8        | 0.29%   |
| Serbia       | 7        | 0.25%   |
| New Zealand  | 7        | 0.25%   |
| Israel       | 7        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 513      | 18.1%   |
| Moscow            | 46       | 1.62%   |
| St Petersburg     | 41       | 1.45%   |
| Sao Paulo         | 27       | 0.95%   |
| Vienna            | 21       | 0.74%   |
| Paris             | 21       | 0.74%   |
| Berlin            | 18       | 0.64%   |
| Barcelona         | 17       | 0.6%    |
| Seville           | 16       | 0.56%   |
| Falkenstein       | 16       | 0.56%   |
| Rio de Janeiro    | 15       | 0.53%   |
| Madrid            | 15       | 0.53%   |
| Brisbane          | 13       | 0.46%   |
| Milan             | 12       | 0.42%   |
| Budapest          | 12       | 0.42%   |
| Amsterdam         | 12       | 0.42%   |
| Perm              | 11       | 0.39%   |
| Munich            | 11       | 0.39%   |
| Melbourne         | 11       | 0.39%   |
| Yekaterinburg     | 10       | 0.35%   |
| Sydney            | 10       | 0.35%   |
| Dover-Foxcroft    | 10       | 0.35%   |
| Dallas            | 10       | 0.35%   |
| Bangor            | 10       | 0.35%   |
| Zurich            | 9        | 0.32%   |
| Warsaw            | 9        | 0.32%   |
| New York          | 9        | 0.32%   |
| Kyiv              | 9        | 0.32%   |
| Gladbeck          | 9        | 0.32%   |
| Frankfurt am Main | 9        | 0.32%   |
| Chicago           | 9        | 0.32%   |
| Stockholm         | 8        | 0.28%   |
| London            | 8        | 0.28%   |
| Hamburg           | 8        | 0.28%   |
| Cologne           | 8        | 0.28%   |
| Brasília         | 8        | 0.28%   |
| Valencia          | 7        | 0.25%   |
| Toronto           | 7        | 0.25%   |
| Sofia             | 7        | 0.25%   |
| Rome              | 7        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 934      | 1688   | 19.39%  |
| Seagate             | 910      | 1588   | 18.89%  |
| Samsung Electronics | 694      | 1102   | 14.4%   |
| Toshiba             | 331      | 594    | 6.87%   |
| Kingston            | 328      | 438    | 6.81%   |
| Crucial             | 283      | 381    | 5.87%   |
| Hitachi             | 178      | 253    | 3.69%   |
| SanDisk             | 145      | 198    | 3.01%   |
| Intel               | 87       | 121    | 1.81%   |
| A-DATA Technology   | 83       | 112    | 1.72%   |
| Unknown             | 63       | 92     | 1.31%   |
| HGST                | 61       | 116    | 1.27%   |
| China               | 50       | 57     | 1.04%   |
| SPCC                | 38       | 40     | 0.79%   |
| OCZ                 | 38       | 48     | 0.79%   |
| Maxtor              | 38       | 44     | 0.79%   |
| Phison              | 35       | 52     | 0.73%   |
| Corsair             | 29       | 44     | 0.6%    |
| Hewlett-Packard     | 28       | 51     | 0.58%   |
| Transcend           | 26       | 29     | 0.54%   |
| Patriot             | 25       | 32     | 0.52%   |
| PNY                 | 23       | 32     | 0.48%   |
| Netac               | 23       | 86     | 0.48%   |
| Intenso             | 21       | 29     | 0.44%   |
| Gigabyte Technology | 19       | 24     | 0.39%   |
| SK hynix            | 16       | 22     | 0.33%   |
| Micron Technology   | 14       | 19     | 0.29%   |
| Goodram             | 14       | 23     | 0.29%   |
| XPG                 | 12       | 18     | 0.25%   |
| Plextor             | 11       | 16     | 0.23%   |
| Unknown             | 11       | 12     | 0.23%   |
| Silicon Motion      | 10       | 14     | 0.21%   |
| KingDian            | 10       | 11     | 0.21%   |
| Team                | 8        | 9      | 0.17%   |
| LITEON              | 8        | 10     | 0.17%   |
| Apacer              | 8        | 8      | 0.17%   |
| Hajaan              | 7        | 11     | 0.15%   |
| SABRENT             | 6        | 7      | 0.12%   |
| Mushkin             | 6        | 7      | 0.12%   |
| LITEONIT            | 6        | 9      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 90       | 1.58%   |
| Kingston SA400S37240G 240GB SSD  | 79       | 1.39%   |
| Crucial CT480BX500SSD1 480GB     | 72       | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB   | 68       | 1.2%    |
| Toshiba DT01ACA050 500GB         | 58       | 1.02%   |
| Samsung SSD 860 EVO 1TB          | 44       | 0.77%   |
| Toshiba HDWD110 1TB              | 43       | 0.76%   |
| Samsung SSD 860 EVO 500GB        | 42       | 0.74%   |
| Kingston SV300S37A120G 120GB SSD | 42       | 0.74%   |
| Toshiba DT01ACA100 1TB           | 41       | 0.72%   |
| Samsung SSD 860 EVO 250GB        | 41       | 0.72%   |
| Samsung SSD 850 EVO 250GB        | 39       | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB         | 38       | 0.67%   |
| Kingston SA400S37480G 480GB SSD  | 37       | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB   | 36       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 36       | 0.63%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 35       | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB   | 34       | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB   | 34       | 0.6%    |
| Hitachi HDS721050CLA362 500GB    | 33       | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB   | 31       | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB     | 31       | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB   | 30       | 0.53%   |
| Crucial CT500MX500SSD1 500GB     | 29       | 0.51%   |
| Samsung SSD 850 EVO 500GB        | 28       | 0.49%   |
| Crucial CT240BX500SSD1 240GB     | 28       | 0.49%   |
| Crucial CT1000MX500SSD1 1TB      | 26       | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB   | 25       | 0.44%   |
| WDC WD20EFRX-68EUZN0 2TB         | 23       | 0.4%    |
| Toshiba DT01ACA200 2TB           | 23       | 0.4%    |
| Seagate ST3500418AS 500GB        | 23       | 0.4%    |
| Crucial CT250MX500SSD1 250GB     | 22       | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB         | 21       | 0.37%   |
| Toshiba DT01ACA300 3TB           | 21       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB   | 21       | 0.37%   |
| Netac SSD 240GB                  | 20       | 0.35%   |
| Seagate ST31000528AS 1TB         | 19       | 0.33%   |
| Kingston SUV400S37120G 120GB SSD | 19       | 0.33%   |
| Seagate ST3250318AS 250GB        | 18       | 0.32%   |
| Seagate ST31000524AS 1TB         | 18       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 892      | 1553   | 35.92%  |
| WDC                 | 828      | 1508   | 33.35%  |
| Toshiba             | 301      | 549    | 12.12%  |
| Hitachi             | 178      | 253    | 7.17%   |
| Samsung Electronics | 123      | 171    | 4.95%   |
| HGST                | 61       | 116    | 2.46%   |
| Maxtor              | 38       | 44     | 1.53%   |
| Unknown             | 13       | 20     | 0.52%   |
| Hewlett-Packard     | 8        | 22     | 0.32%   |
| Fujitsu             | 6        | 7      | 0.24%   |
| ASMT                | 5        | 8      | 0.2%    |
| Intenso             | 3        | 3      | 0.12%   |
| Apple               | 3        | 4      | 0.12%   |
| HPE                 | 2        | 4      | 0.08%   |
| USB 3.0             | 1        | 2      | 0.04%   |
| SABRENT             | 1        | 2      | 0.04%   |
| RSH-319             | 1        | 1      | 0.04%   |
| Quantum             | 1        | 1      | 0.04%   |
| pqi                 | 1        | 1      | 0.04%   |
| Pear 2TB            | 1        | 1      | 0.04%   |
| NAS                 | 1        | 10     | 0.04%   |
| MaxDigital          | 1        | 4      | 0.04%   |
| MARSHAL             | 1        | 1      | 0.04%   |
| Magnetic Data       | 1        | 1      | 0.04%   |
| LIO-ORG             | 1        | 8      | 0.04%   |
| LaCie               | 1        | 1      | 0.04%   |
| JMicron Technology  | 1        | 2      | 0.04%   |
| Innodisk            | 1        | 1      | 0.04%   |
| Inateck             | 1        | 1      | 0.04%   |
| IBM H0              | 1        | 1      | 0.04%   |
| Hajaan              | 1        | 1      | 0.04%   |
| ExcelStor           | 1        | 1      | 0.04%   |
| DAS                 | 1        | 1      | 0.04%   |
| AMP                 | 1        | 1      | 0.04%   |
| 3ware               | 1        | 4      | 0.04%   |
| 128MB               | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 393      | 566    | 22.48%  |
| Kingston            | 300      | 392    | 17.16%  |
| Crucial             | 263      | 349    | 15.05%  |
| SanDisk             | 116      | 159    | 6.64%   |
| WDC                 | 98       | 119    | 5.61%   |
| A-DATA Technology   | 65       | 87     | 3.72%   |
| China               | 49       | 56     | 2.8%    |
| Intel               | 44       | 56     | 2.52%   |
| OCZ                 | 38       | 48     | 2.17%   |
| SPCC                | 33       | 33     | 1.89%   |
| Transcend           | 24       | 27     | 1.37%   |
| Toshiba             | 24       | 31     | 1.37%   |
| Netac               | 23       | 86     | 1.32%   |
| Patriot             | 19       | 23     | 1.09%   |
| PNY                 | 18       | 26     | 1.03%   |
| Intenso             | 16       | 22     | 0.92%   |
| Corsair             | 14       | 18     | 0.8%    |
| Goodram             | 12       | 17     | 0.69%   |
| Plextor             | 10       | 15     | 0.57%   |
| Gigabyte Technology | 10       | 12     | 0.57%   |
| Micron Technology   | 9        | 13     | 0.51%   |
| KingDian            | 9        | 10     | 0.51%   |
| Unknown             | 8        | 9      | 0.46%   |
| Seagate             | 7        | 7      | 0.4%    |
| Hewlett-Packard     | 7        | 8      | 0.4%    |
| Hajaan              | 7        | 10     | 0.4%    |
| Unknown             | 6        | 9      | 0.34%   |
| Team                | 6        | 7      | 0.34%   |
| SK hynix            | 6        | 7      | 0.34%   |
| Mushkin             | 6        | 7      | 0.34%   |
| LITEONIT            | 6        | 9      | 0.34%   |
| Apacer              | 6        | 6      | 0.34%   |
| LITEON              | 5        | 7      | 0.29%   |
| Xinhaike            | 4        | 6      | 0.23%   |
| Foxline             | 4        | 4      | 0.23%   |
| TO Exter            | 3        | 3      | 0.17%   |
| Smartbuy            | 3        | 3      | 0.17%   |
| Lexar               | 3        | 5      | 0.17%   |
| LDLC                | 3        | 3      | 0.17%   |
| KingSpec            | 3        | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1914     | 4309   | 47.21%  |
| SSD     | 1470     | 2361   | 36.26%  |
| NVMe    | 590      | 901    | 14.55%  |
| Unknown | 49       | 91     | 1.21%   |
| MMC     | 31       | 37     | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2539     | 6446   | 76.66%  |
| NVMe | 582      | 889    | 17.57%  |
| SAS  | 160      | 327    | 4.83%   |
| MMC  | 31       | 37     | 0.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives  | Percent |
|------------|----------|---------|---------|
| 0.01-0.5   | 1985     | 3328    | 52.67%  |
| 0.51-1.0   | 910      | 1496    | 24.14%  |
| 1.01-2.0   | 391      | 685     | 10.37%  |
| 3.01-4.0   | 193      | 420     | 5.12%   |
| 4.01-10.0  | 143      | 402     | 3.79%   |
| 2.01-3.0   | 115      | 208     | 3.05%   |
| 10.01-20.0 | 31       | 131     | 0.82%   |
| 0          | 1        | Unknown | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 651      | 22.9%   |
| 101-250        | 430      | 15.12%  |
| 251-500        | 355      | 12.49%  |
| 501-1000       | 347      | 12.21%  |
| More than 3000 | 329      | 11.57%  |
| 1001-2000      | 261      | 9.18%   |
| 51-100         | 156      | 5.49%   |
| 2001-3000      | 135      | 4.75%   |
| 1-20           | 98       | 3.45%   |
| 21-50          | 81       | 2.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 651      | 22.4%   |
| 1-20           | 649      | 22.33%  |
| 101-250        | 285      | 9.81%   |
| 251-500        | 244      | 8.4%    |
| 21-50          | 239      | 8.22%   |
| 501-1000       | 219      | 7.54%   |
| 51-100         | 214      | 7.36%   |
| 1001-2000      | 166      | 5.71%   |
| More than 3000 | 154      | 5.3%    |
| 2001-3000      | 80       | 2.75%   |
| 0              | 5        | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 21       | 21     | 3.34%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 17       | 20     | 2.71%   |
| Kingston SV300S37A120G 120GB SSD  | 11       | 11     | 1.75%   |
| Hitachi HDS721050CLA362 500GB     | 10       | 10     | 1.59%   |
| Seagate ST3500418AS 500GB         | 7        | 10     | 1.11%   |
| Seagate ST1000DM003-9YN162 1TB    | 7        | 8      | 1.11%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 6        | 6      | 0.96%   |
| WDC WD5000AAKX-001CA0 500GB       | 6        | 8      | 0.96%   |
| Toshiba DT01ACA100 1TB            | 6        | 7      | 0.96%   |
| Seagate ST3250318AS 250GB         | 6        | 7      | 0.96%   |
| Seagate ST3160815AS 160GB         | 6        | 8      | 0.96%   |
| Seagate ST31500341AS 1TB          | 6        | 12     | 0.96%   |
| WDC WD10EADS-00M2B0 1TB           | 5        | 5      | 0.8%    |
| Toshiba DT01ACA050 500GB          | 5        | 6      | 0.8%    |
| Seagate ST31000528AS 1TB          | 5        | 5      | 0.8%    |
| Seagate ST31000524AS 1TB          | 5        | 5      | 0.8%    |
| Seagate ST250DM000-1BD141 250GB   | 5        | 5      | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB    | 5        | 5      | 0.8%    |
| Hitachi HDS721050DLE630 500GB     | 5        | 5      | 0.8%    |
| WDC WD20EFRX-68EUZN0 2TB          | 4        | 15     | 0.64%   |
| WDC WD20EARS-00MVWB0 2TB          | 4        | 4      | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 4      | 0.64%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 4      | 0.64%   |
| Seagate ST3320613AS 320GB         | 4        | 4      | 0.64%   |
| Samsung Electronics HD103UJ 1TB   | 4        | 5      | 0.64%   |
| Maxtor STM3250310AS 250GB         | 4        | 4      | 0.64%   |
| A-DATA Technology SU800 256GB SSD | 4        | 7      | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 3      | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 4      | 0.48%   |
| WDC WD3200AAJS-08L7A0 320GB       | 3        | 3      | 0.48%   |
| WDC WD2500AAJS-00B4A0 250GB       | 3        | 3      | 0.48%   |
| WDC WD2002FAEX-007BA0 2TB         | 3        | 4      | 0.48%   |
| WDC WD10EADS-65M2B1 1TB           | 3        | 4      | 0.48%   |
| Seagate ST9500325AS 500GB         | 3        | 5      | 0.48%   |
| Seagate ST380815AS 80GB           | 3        | 4      | 0.48%   |
| Seagate ST3250410AS 250GB         | 3        | 4      | 0.48%   |
| Seagate ST3250312AS 250GB         | 3        | 5      | 0.48%   |
| Seagate ST3250310AS 250GB         | 3        | 4      | 0.48%   |
| Seagate ST3160813AS 160GB         | 3        | 3      | 0.48%   |
| Seagate ST3120827AS 120GB         | 3        | 5      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 179      | 240    | 30.03%  |
| WDC                 | 172      | 235    | 28.86%  |
| Samsung Electronics | 55       | 62     | 9.23%   |
| Hitachi             | 47       | 59     | 7.89%   |
| Toshiba             | 25       | 34     | 4.19%   |
| Kingston            | 24       | 27     | 4.03%   |
| Intel               | 14       | 17     | 2.35%   |
| Crucial             | 14       | 17     | 2.35%   |
| A-DATA Technology   | 13       | 19     | 2.18%   |
| Maxtor              | 12       | 13     | 2.01%   |
| HGST                | 6        | 7      | 1.01%   |
| SanDisk             | 5        | 8      | 0.84%   |
| OCZ                 | 5        | 6      | 0.84%   |
| KingDian            | 4        | 4      | 0.67%   |
| China               | 3        | 3      | 0.5%    |
| SK hynix            | 2        | 6      | 0.34%   |
| Micron Technology   | 2        | 2      | 0.34%   |
| LITEONIT            | 2        | 2      | 0.34%   |
| Hewlett-Packard     | 2        | 3      | 0.34%   |
| Corsair             | 2        | 2      | 0.34%   |
| Unknown             | 1        | 1      | 0.17%   |
| PNY                 | 1        | 1      | 0.17%   |
| Plextor             | 1        | 2      | 0.17%   |
| LITEON              | 1        | 1      | 0.17%   |
| Hypertec            | 1        | 1      | 0.17%   |
| HP Phison           | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 2      | 0.17%   |
| ASMT                | 1        | 2      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 179      | 240    | 37.53%  |
| WDC                 | 167      | 229    | 35.01%  |
| Hitachi             | 47       | 59     | 9.85%   |
| Samsung Electronics | 36       | 41     | 7.55%   |
| Toshiba             | 25       | 34     | 5.24%   |
| Maxtor              | 12       | 13     | 2.52%   |
| HGST                | 6        | 7      | 1.26%   |
| Hewlett-Packard     | 2        | 3      | 0.42%   |
| Unknown             | 1        | 1      | 0.21%   |
| Fujitsu             | 1        | 2      | 0.21%   |
| ASMT                | 1        | 2      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 434      | 631    | 78.34%  |
| SSD  | 106      | 127    | 19.13%  |
| NVMe | 14       | 19     | 2.53%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB                       | 1        | 1      | 11.11%  |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 11.11%  |
| Seagate ST500DM005 HD502HJ 500GB                 | 1        | 1      | 11.11%  |
| Seagate ST500DM002-1BD142 500GB                  | 1        | 1      | 11.11%  |
| Seagate ST3500830AS 500GB                        | 1        | 1      | 11.11%  |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 11.11%  |
| Samsung Electronics HD103SJ 1TB                  | 1        | 1      | 11.11%  |
| HGST HDN724040ALE640 4TB                         | 1        | 1      | 11.11%  |
| Crucial CT1000P1SSD8 1TB                         | 1        | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 33.33%  |
| WDC                 | 2        | 2      | 22.22%  |
| Samsung Electronics | 2        | 3      | 22.22%  |
| HGST                | 1        | 1      | 11.11%  |
| Crucial             | 1        | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1940     | 4860   | 60.36%  |
| Detected | 734      | 2051   | 22.84%  |
| Malfunc  | 530      | 777    | 16.49%  |
| Failed   | 9        | 10     | 0.28%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1854     | 49.43%  |
| AMD                              | 776      | 20.69%  |
| Samsung Electronics              | 263      | 7.01%   |
| ASMedia Technology               | 132      | 3.52%   |
| Marvell Technology Group         | 114      | 3.04%   |
| Phison Electronics               | 77       | 2.05%   |
| JMicron Technology               | 76       | 2.03%   |
| SanDisk                          | 73       | 1.95%   |
| Nvidia                           | 73       | 1.95%   |
| Kingston Technology Company      | 37       | 0.99%   |
| VIA Technologies                 | 33       | 0.88%   |
| Silicon Motion                   | 33       | 0.88%   |
| LSI Logic / Symbios Logic        | 31       | 0.83%   |
| Micron/Crucial Technology        | 30       | 0.8%    |
| ADATA Technology                 | 28       | 0.75%   |
| Broadcom / LSI                   | 21       | 0.56%   |
| Silicon Image                    | 15       | 0.4%    |
| Toshiba America Info Systems     | 10       | 0.27%   |
| Adaptec                          | 10       | 0.27%   |
| SK hynix                         | 9        | 0.24%   |
| Seagate Technology               | 9        | 0.24%   |
| Realtek Semiconductor            | 7        | 0.19%   |
| Micron Technology                | 6        | 0.16%   |
| Lite-On Technology               | 6        | 0.16%   |
| KIOXIA                           | 3        | 0.08%   |
| Integrated Technology Express    | 3        | 0.08%   |
| Hewlett-Packard                  | 3        | 0.08%   |
| Silicon Integrated Systems [SiS] | 2        | 0.05%   |
| Mylex                            | 2        | 0.05%   |
| HighPoint Technologies           | 2        | 0.05%   |
| 3ware                            | 2        | 0.05%   |
| Unknown                          | 1        | 0.03%   |
| Tekram Technology                | 1        | 0.03%   |
| Shenzhen Longsys Electronics     | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.03%   |
| Loongson Technology              | 1        | 0.03%   |
| IBM                              | 1        | 0.03%   |
| Chelsio Communications           | 1        | 0.03%   |
| Broadcom                         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 474      | 9.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 239      | 5.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 173      | 3.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 170      | 3.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 155      | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 154      | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 151      | 3.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 144      | 3.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 121      | 2.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 120      | 2.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 115      | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 107      | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 95       | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 82       | 1.72%   |
| Intel SATA Controller [RAID mode]                                                       | 75       | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 71       | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 70       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 66       | 1.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 64       | 1.34%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 57       | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 53       | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 45       | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 45       | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 43       | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 42       | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 41       | 0.86%   |
| AMD FCH SATA Controller D                                                               | 39       | 0.82%   |
| Phison E12 NVMe Controller                                                              | 38       | 0.8%    |
| Nvidia MCP61 IDE                                                                        | 37       | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 36       | 0.75%   |
| AMD 300 Series Chipset SATA Controller                                                  | 36       | 0.75%   |
| AMD X370 Series Chipset SATA Controller                                                 | 34       | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 32       | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 31       | 0.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 30       | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 28       | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 28       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 27       | 0.57%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 26       | 0.54%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 24       | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2186     | 58.62%  |
| IDE  | 728      | 19.52%  |
| NVMe | 587      | 15.74%  |
| RAID | 152      | 4.08%   |
| SAS  | 53       | 1.42%   |
| SCSI | 23       | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 1867     | 68.09%  |
| AMD               | 852      | 31.07%  |
| CentaurHauls      | 6        | 0.22%   |
| ARM               | 5        | 0.18%   |
| Unknown           | 4        | 0.15%   |
| sifive,bullet0    | 3        | 0.11%   |
| CHRP IBM,9131-52A | 2        | 0.07%   |
| sifive,u74-mc     | 1        | 0.04%   |
| PowerNV FP5466G2  | 1        | 0.04%   |
| CHRP IBM,8233-E8B | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 62       | 2.26%   |
| AMD Ryzen 5 3600 6-Core Processor           | 51       | 1.86%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 1.28%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 31       | 1.13%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 31       | 1.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 27       | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 27       | 0.98%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 27       | 0.98%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 26       | 0.95%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 26       | 0.95%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 26       | 0.95%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 26       | 0.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 25       | 0.91%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 25       | 0.91%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 25       | 0.91%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 24       | 0.87%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 24       | 0.87%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 22       | 0.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 22       | 0.8%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 21       | 0.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 21       | 0.77%   |
| AMD FX-8350 Eight-Core Processor            | 21       | 0.77%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 20       | 0.73%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 20       | 0.73%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 19       | 0.69%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 19       | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 18       | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 18       | 0.66%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 18       | 0.66%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 18       | 0.66%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 17       | 0.62%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 17       | 0.62%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 16       | 0.58%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 16       | 0.58%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 16       | 0.58%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 16       | 0.58%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 16       | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 15       | 0.55%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 0.55%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 15       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 453      | 16.51%  |
| Intel Core i7           | 287      | 10.46%  |
| Intel Core i3           | 255      | 9.3%    |
| AMD Ryzen 5             | 183      | 6.67%   |
| Intel Xeon              | 175      | 6.38%   |
| Intel Pentium           | 166      | 6.05%   |
| AMD Ryzen 7             | 138      | 5.03%   |
| Intel Celeron           | 125      | 4.56%   |
| Intel Core 2 Duo        | 112      | 4.08%   |
| AMD FX                  | 92       | 3.35%   |
| AMD Ryzen 9             | 74       | 2.7%    |
| Other                   | 65       | 2.37%   |
| Intel Pentium Dual-Core | 58       | 2.11%   |
| Intel Core 2 Quad       | 49       | 1.79%   |
| AMD Ryzen 3             | 49       | 1.79%   |
| AMD Athlon 64 X2        | 28       | 1.02%   |
| AMD Ryzen Threadripper  | 27       | 0.98%   |
| Intel Core i9           | 26       | 0.95%   |
| Intel Atom              | 26       | 0.95%   |
| AMD Athlon II X2        | 26       | 0.95%   |
| AMD Phenom II X4        | 25       | 0.91%   |
| Intel Core 2            | 24       | 0.87%   |
| AMD A8                  | 23       | 0.84%   |
| AMD Athlon              | 22       | 0.8%    |
| AMD A10                 | 21       | 0.77%   |
| Intel Pentium Gold      | 20       | 0.73%   |
| Intel Pentium 4         | 20       | 0.73%   |
| Intel Pentium Dual      | 14       | 0.51%   |
| AMD Sempron             | 12       | 0.44%   |
| AMD Phenom II X6        | 12       | 0.44%   |
| AMD GX                  | 11       | 0.4%    |
| AMD Ryzen 5 PRO         | 9        | 0.33%   |
| AMD Phenom              | 9        | 0.33%   |
| AMD Athlon 64           | 9        | 0.33%   |
| AMD A6                  | 9        | 0.33%   |
| AMD Athlon X4           | 8        | 0.29%   |
| AMD Athlon II X4        | 8        | 0.29%   |
| Intel Pentium D         | 7        | 0.26%   |
| AMD A4                  | 7        | 0.26%   |
| AMD Turion II Neo       | 6        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 937      | 34.11%  |
| 2       | 878      | 31.96%  |
| 6       | 382      | 13.91%  |
| 8       | 253      | 9.21%   |
| 1       | 92       | 3.35%   |
| 16      | 63       | 2.29%   |
| 12      | 60       | 2.18%   |
| 3       | 32       | 1.16%   |
| 10      | 16       | 0.58%   |
| 32      | 9        | 0.33%   |
| 24      | 7        | 0.25%   |
| Unknown | 6        | 0.22%   |
| 44      | 3        | 0.11%   |
| 64      | 2        | 0.07%   |
| 20      | 2        | 0.07%   |
| 18      | 2        | 0.07%   |
| 28      | 1        | 0.04%   |
| 22      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2689     | 98%     |
| 2       | 49       | 1.79%   |
| Unknown | 6        | 0.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1439     | 52.44%  |
| 1       | 1297     | 47.27%  |
| Unknown | 6        | 0.22%   |
| 4       | 2        | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2645     | 96.25%  |
| Unknown        | 73       | 2.66%   |
| 32-bit         | 30       | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 651      | 23.11%  |
| 0x306c3    | 247      | 8.77%   |
| 0x206a7    | 157      | 5.57%   |
| 0x1067a    | 139      | 4.93%   |
| 0x306a9    | 130      | 4.61%   |
| 0x906ea    | 108      | 3.83%   |
| 0x506e3    | 106      | 3.76%   |
| 0x08701021 | 93       | 3.3%    |
| 0xa0653    | 67       | 2.38%   |
| 0x906e9    | 54       | 1.92%   |
| 0x0800820d | 50       | 1.77%   |
| 0xa0655    | 49       | 1.74%   |
| 0x08108109 | 44       | 1.56%   |
| 0x0a201016 | 39       | 1.38%   |
| 0x08701013 | 32       | 1.14%   |
| 0x010000c8 | 28       | 0.99%   |
| 0xa0671    | 26       | 0.92%   |
| 0x206d7    | 26       | 0.92%   |
| 0x6fd      | 24       | 0.85%   |
| 0x906ed    | 23       | 0.82%   |
| 0x306f2    | 23       | 0.82%   |
| 0x906eb    | 22       | 0.78%   |
| 0x06003106 | 22       | 0.78%   |
| 0x6fb      | 21       | 0.75%   |
| 0x08101016 | 21       | 0.75%   |
| 0x06000852 | 20       | 0.71%   |
| 0x306e4    | 18       | 0.64%   |
| 0x08001137 | 18       | 0.64%   |
| 0x206c2    | 16       | 0.57%   |
| 0x08001138 | 16       | 0.57%   |
| 0x06001119 | 15       | 0.53%   |
| 0x20655    | 14       | 0.5%    |
| 0x106a5    | 14       | 0.5%    |
| 0x10676    | 14       | 0.5%    |
| 0x0a201009 | 14       | 0.5%    |
| 0x706a1    | 13       | 0.46%   |
| 0x6f6      | 12       | 0.43%   |
| 0x106e5    | 12       | 0.43%   |
| 0x06000822 | 12       | 0.43%   |
| 0x406c3    | 11       | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 348      | 12.68%  |
| KabyLake         | 260      | 9.48%   |
| SandyBridge      | 222      | 8.09%   |
| Penryn           | 195      | 7.11%   |
| IvyBridge        | 179      | 6.52%   |
| Zen 2            | 177      | 6.45%   |
| Skylake          | 147      | 5.36%   |
| Zen+             | 143      | 5.21%   |
| CometLake        | 124      | 4.52%   |
| K10              | 100      | 3.64%   |
| Core             | 96       | 3.5%    |
| Zen              | 95       | 3.46%   |
| Zen 3            | 92       | 3.35%   |
| Piledriver       | 88       | 3.21%   |
| Unknown          | 51       | 1.86%   |
| Westmere         | 49       | 1.79%   |
| K8 Hammer        | 48       | 1.75%   |
| Silvermont       | 47       | 1.71%   |
| Nehalem          | 41       | 1.49%   |
| NetBurst         | 34       | 1.24%   |
| Steamroller      | 30       | 1.09%   |
| Bulldozer        | 25       | 0.91%   |
| Goldmont plus    | 24       | 0.87%   |
| Broadwell        | 18       | 0.66%   |
| Bonnell          | 18       | 0.66%   |
| Goldmont         | 16       | 0.58%   |
| Jaguar           | 15       | 0.55%   |
| Excavator        | 15       | 0.55%   |
| Icelake          | 8        | 0.29%   |
| Bobcat           | 8        | 0.29%   |
| Alderlake Hybrid | 7        | 0.26%   |
| K6               | 6        | 0.22%   |
| Puma             | 5        | 0.18%   |
| K10 Llano        | 5        | 0.18%   |
| Tremont          | 3        | 0.11%   |
| P6               | 3        | 0.11%   |
| TigerLake        | 2        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1105     | 38.37%  |
| Nvidia                           | 983      | 34.13%  |
| AMD                              | 712      | 24.72%  |
| ASPEED Technology                | 40       | 1.39%   |
| Matrox Electronics Systems       | 27       | 0.94%   |
| VIA Technologies                 | 9        | 0.31%   |
| Silicon Motion                   | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Loongson Technology              | 1        | 0.03%   |
| ATI Technologies                 | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 166      | 5.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 119      | 4.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 114      | 3.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 99       | 3.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 74       | 2.51%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 71       | 2.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 69       | 2.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 58       | 1.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 57       | 1.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 57       | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 53       | 1.8%    |
| Intel HD Graphics 530                                                                    | 51       | 1.73%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 49       | 1.66%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 40       | 1.36%   |
| Nvidia GT218 [GeForce 210]                                                               | 38       | 1.29%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 38       | 1.29%   |
| Intel HD Graphics 630                                                                    | 38       | 1.29%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 36       | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 34       | 1.15%   |
| Intel HD Graphics 510                                                                    | 33       | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 32       | 1.08%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 28       | 0.95%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 27       | 0.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 26       | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 25       | 0.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 24       | 0.81%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 23       | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 22       | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22       | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22       | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 22       | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21       | 0.71%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 21       | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 20       | 0.68%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 20       | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 17       | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 17       | 0.58%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 16       | 0.54%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 16       | 0.54%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 16       | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 995      | 35.91%  |
| 1 x Nvidia                        | 915      | 33.02%  |
| 1 x AMD                           | 649      | 23.42%  |
| Intel + Nvidia                    | 40       | 1.44%   |
| 2 x AMD                           | 32       | 1.15%   |
| 1 x ASPEED                        | 30       | 1.08%   |
| Other                             | 26       | 0.94%   |
| 1 x Matrox                        | 25       | 0.9%    |
| Intel + AMD                       | 11       | 0.4%    |
| AMD + Nvidia                      | 10       | 0.36%   |
| 2 x Nvidia                        | 9        | 0.32%   |
| 1 x VIA                           | 9        | 0.32%   |
| Nvidia + ASPEED                   | 5        | 0.18%   |
| AMD + ASPEED                      | 4        | 0.14%   |
| Intel + 2 x Nvidia                | 3        | 0.11%   |
| AMD + Matrox                      | 2        | 0.07%   |
| 3 x AMD                           | 1        | 0.04%   |
| 2 x Loongson Technology           | 1        | 0.04%   |
| 2 x Intel                         | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.04%   |
| 1 x SiS                           | 1        | 0.04%   |
| 1 x Silicon Motion                | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1538     | 55.42%  |
| Unknown     | 729      | 26.27%  |
| Proprietary | 508      | 18.31%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1671     | 59.68%  |
| 1.01-2.0   | 275      | 9.82%   |
| 0.51-1.0   | 215      | 7.68%   |
| 3.01-4.0   | 174      | 6.21%   |
| 0.01-0.5   | 168      | 6%      |
| 7.01-8.0   | 153      | 5.46%   |
| 5.01-6.0   | 78       | 2.79%   |
| 8.01-16.0  | 32       | 1.14%   |
| 2.01-3.0   | 29       | 1.04%   |
| 16.01-24.0 | 4        | 0.14%   |
| 24.01-32.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 358      | 16.21%  |
| Dell                 | 267      | 12.09%  |
| Goldstar             | 218      | 9.87%   |
| BenQ                 | 142      | 6.43%   |
| Acer                 | 137      | 6.2%    |
| Hewlett-Packard      | 135      | 6.11%   |
| AOC                  | 113      | 5.12%   |
| Philips              | 112      | 5.07%   |
| Ancor Communications | 98       | 4.44%   |
| Iiyama               | 55       | 2.49%   |
| ViewSonic            | 51       | 2.31%   |
| Unknown              | 48       | 2.17%   |
| Lenovo               | 34       | 1.54%   |
| LG Electronics       | 30       | 1.36%   |
| Eizo                 | 29       | 1.31%   |
| ASUSTek Computer     | 28       | 1.27%   |
| Sony                 | 19       | 0.86%   |
| NEC Computers        | 16       | 0.72%   |
| Fujitsu Siemens      | 14       | 0.63%   |
| Medion               | 13       | 0.59%   |
| Vizio                | 9        | 0.41%   |
| Vestel Elektronik    | 8        | 0.36%   |
| HannStar             | 8        | 0.36%   |
| Idek Iiyama          | 7        | 0.32%   |
| Hitachi              | 7        | 0.32%   |
| Belinea              | 7        | 0.32%   |
| Apple                | 7        | 0.32%   |
| Unknown              | 7        | 0.32%   |
| Toshiba              | 6        | 0.27%   |
| Sceptre Tech         | 6        | 0.27%   |
| ONN                  | 6        | 0.27%   |
| Panasonic            | 5        | 0.23%   |
| MSI                  | 5        | 0.23%   |
| CHR                  | 5        | 0.23%   |
| Targa Visionary      | 4        | 0.18%   |
| SGT                  | 4        | 0.18%   |
| OEM                  | 4        | 0.18%   |
| MStar                | 4        | 0.18%   |
| HPN                  | 4        | 0.18%   |
| Grundig              | 4        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 21       | 0.89%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 17       | 0.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10       | 0.42%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 9        | 0.38%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 8        | 0.34%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 8        | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7        | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 7        | 0.3%    |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                    | 7        | 0.3%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 7        | 0.3%    |
| Unknown                                                               | 7        | 0.3%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 6        | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 6        | 0.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 6        | 0.25%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6        | 0.25%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 6        | 0.25%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 6        | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6        | 0.25%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 6        | 0.25%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 6        | 0.25%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 6        | 0.25%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 5        | 0.21%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 5        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 0.21%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 5        | 0.21%   |
| Fujitsu Siemens LL 3190T FUS07A3 1366x768 430x255mm 19.7-inch         | 5        | 0.21%   |
| Dell E178FP DELA027 1280x1024 340x270mm 17.1-inch                     | 5        | 0.21%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 5        | 0.21%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 5        | 0.21%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 5        | 0.21%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 5        | 0.21%   |
| AOC 2350 AOC2350 1920x1080 509x286mm 23.0-inch                        | 5        | 0.21%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 5        | 0.21%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 5        | 0.21%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 5        | 0.21%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 4        | 0.17%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 4        | 0.17%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 380x300mm 19.1-inch  | 4        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 890      | 40.64%  |
| 1280x1024 (SXGA)   | 201      | 9.18%   |
| 3840x2160 (4K)     | 192      | 8.77%   |
| 2560x1440 (QHD)    | 149      | 6.8%    |
| 1680x1050 (WSXGA+) | 125      | 5.71%   |
| 1920x1200 (WUXGA)  | 96       | 4.38%   |
| 1366x768 (WXGA)    | 81       | 3.7%    |
| Unknown            | 76       | 3.47%   |
| 1440x900 (WXGA+)   | 66       | 3.01%   |
| 1600x900 (HD+)     | 51       | 2.33%   |
| 2560x1080          | 37       | 1.69%   |
| 3440x1440          | 30       | 1.37%   |
| 3840x1080          | 23       | 1.05%   |
| 1600x1200          | 23       | 1.05%   |
| 1360x768           | 23       | 1.05%   |
| 1024x768 (XGA)     | 22       | 1%      |
| 2288x1287          | 18       | 0.82%   |
| 1920x540           | 13       | 0.59%   |
| 4480x1440          | 7        | 0.32%   |
| 2560x1600          | 7        | 0.32%   |
| 3200x1080          | 6        | 0.27%   |
| 1280x720 (HD)      | 5        | 0.23%   |
| 5760x2160          | 4        | 0.18%   |
| 5760x1080          | 4        | 0.18%   |
| 7680x2160          | 3        | 0.14%   |
| 3840x1600          | 3        | 0.14%   |
| 3360x1050          | 3        | 0.14%   |
| 5760x1200          | 2        | 0.09%   |
| 5360x1440          | 2        | 0.09%   |
| 2560x1024          | 2        | 0.09%   |
| 2048x1536          | 2        | 0.09%   |
| 1400x1050          | 2        | 0.09%   |
| 7680x4320          | 1        | 0.05%   |
| 7680x1440          | 1        | 0.05%   |
| 6400x2160          | 1        | 0.05%   |
| 5120x2160          | 1        | 0.05%   |
| 5120x1440          | 1        | 0.05%   |
| 5120x1200          | 1        | 0.05%   |
| 5120x1080          | 1        | 0.05%   |
| 4880x1080          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 318      | 14.55%  |
| 27      | 288      | 13.17%  |
| 23      | 265      | 12.12%  |
| Unknown | 226      | 10.34%  |
| 21      | 202      | 9.24%   |
| 19      | 152      | 6.95%   |
| 17      | 96       | 4.39%   |
| 18      | 89       | 4.07%   |
| 22      | 86       | 3.93%   |
| 31      | 73       | 3.34%   |
| 20      | 60       | 2.74%   |
| 34      | 51       | 2.33%   |
| 15      | 50       | 2.29%   |
| 84      | 29       | 1.33%   |
| 25      | 26       | 1.19%   |
| 72      | 21       | 0.96%   |
| 142     | 17       | 0.78%   |
| 32      | 13       | 0.59%   |
| 54      | 12       | 0.55%   |
| 26      | 12       | 0.55%   |
| 52      | 9        | 0.41%   |
| 29      | 9        | 0.41%   |
| 40      | 8        | 0.37%   |
| 28      | 8        | 0.37%   |
| 48      | 7        | 0.32%   |
| 39      | 6        | 0.27%   |
| 65      | 5        | 0.23%   |
| 16      | 5        | 0.23%   |
| 13      | 5        | 0.23%   |
| 42      | 4        | 0.18%   |
| 35      | 4        | 0.18%   |
| 49      | 3        | 0.14%   |
| 43      | 3        | 0.14%   |
| 38      | 3        | 0.14%   |
| 37      | 3        | 0.14%   |
| 55      | 2        | 0.09%   |
| 50      | 2        | 0.09%   |
| 47      | 2        | 0.09%   |
| 46      | 2        | 0.09%   |
| 33      | 2        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 802      | 37.9%   |
| 401-500        | 488      | 23.06%  |
| Unknown        | 226      | 10.68%  |
| 301-350        | 141      | 6.66%   |
| 601-700        | 132      | 6.24%   |
| 351-400        | 109      | 5.15%   |
| 701-800        | 65       | 3.07%   |
| 1501-2000      | 52       | 2.46%   |
| 1001-1500      | 44       | 2.08%   |
| 801-900        | 23       | 1.09%   |
| More than 2000 | 17       | 0.8%    |
| 201-300        | 9        | 0.43%   |
| 901-1000       | 8        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1192     | 58.46%  |
| 16/10   | 292      | 14.32%  |
| Unknown | 198      | 9.71%   |
| 5/4     | 182      | 8.93%   |
| 21/9    | 63       | 3.09%   |
| 4/3     | 59       | 2.89%   |
| 1.00    | 19       | 0.93%   |
| 3/2     | 16       | 0.78%   |
| 6/5     | 8        | 0.39%   |
| 32/9    | 7        | 0.34%   |
| 1.96    | 2        | 0.1%    |
| 2.00    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 693      | 32.38%  |
| 301-350        | 294      | 13.74%  |
| 151-200        | 275      | 12.85%  |
| Unknown        | 226      | 10.56%  |
| 351-500        | 154      | 7.2%    |
| 141-150        | 149      | 6.96%   |
| 251-300        | 138      | 6.45%   |
| More than 1000 | 103      | 4.81%   |
| 101-110        | 43       | 2.01%   |
| 501-1000       | 37       | 1.73%   |
| 131-140        | 9        | 0.42%   |
| 111-120        | 8        | 0.37%   |
| 71-80          | 5        | 0.23%   |
| 121-130        | 3        | 0.14%   |
| 81-90          | 2        | 0.09%   |
| 41-50          | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1260     | 61.61%  |
| 101-120       | 336      | 16.43%  |
| Unknown       | 227      | 11.1%   |
| 121-160       | 90       | 4.4%    |
| 1-50          | 82       | 4.01%   |
| 161-240       | 49       | 2.4%    |
| More than 240 | 1        | 0.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1517     | 54.49%  |
| 0     | 851      | 30.57%  |
| 2     | 373      | 13.4%   |
| 3     | 39       | 1.4%    |
| 4     | 4        | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1691     | 46.66%  |
| Intel                                  | 1056     | 29.14%  |
| Qualcomm Atheros                       | 222      | 6.13%   |
| Broadcom                               | 104      | 2.87%   |
| Ralink Technology                      | 67       | 1.85%   |
| Nvidia                                 | 61       | 1.68%   |
| TP-Link                                | 35       | 0.97%   |
| Ralink                                 | 31       | 0.86%   |
| Broadcom Limited                       | 27       | 0.75%   |
| Marvell Technology Group               | 26       | 0.72%   |
| Aquantia                               | 19       | 0.52%   |
| D-Link System                          | 18       | 0.5%    |
| Microsoft                              | 15       | 0.41%   |
| Qualcomm Atheros Communications        | 14       | 0.39%   |
| VIA Technologies                       | 13       | 0.36%   |
| Mellanox Technologies                  | 12       | 0.33%   |
| MediaTek                               | 12       | 0.33%   |
| D-Link                                 | 12       | 0.33%   |
| ASUSTek Computer                       | 12       | 0.33%   |
| ASIX Electronics                       | 12       | 0.33%   |
| Samsung Electronics                    | 11       | 0.3%    |
| Huawei Technologies                    | 9        | 0.25%   |
| NetGear                                | 8        | 0.22%   |
| Gemtek                                 | 6        | 0.17%   |
| Edimax Technology                      | 6        | 0.17%   |
| American Megatrends                    | 6        | 0.17%   |
| 3Com                                   | 6        | 0.17%   |
| Sundance Technology Inc / IC Plus      | 5        | 0.14%   |
| IMC Networks                           | 5        | 0.14%   |
| Texas Instruments                      | 4        | 0.11%   |
| Belkin Components                      | 4        | 0.11%   |
| Xiaomi                                 | 3        | 0.08%   |
| Silicon Integrated Systems [SiS]       | 3        | 0.08%   |
| QLogic                                 | 3        | 0.08%   |
| Linksys                                | 3        | 0.08%   |
| InterBiometrics                        | 3        | 0.08%   |
| Dresden Elektronik                     | 3        | 0.08%   |
| Wilocity                               | 2        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.06%   |
| Sigma Designs                          | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1400     | 34.83%  |
| Intel I211 Gigabit Network Connection                             | 154      | 3.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 90       | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 89       | 2.21%   |
| Intel Wi-Fi 6 AX200                                               | 85       | 2.11%   |
| Intel Ethernet Connection (2) I219-V                              | 83       | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82       | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 58       | 1.44%   |
| Intel I210 Gigabit Network Connection                             | 52       | 1.29%   |
| Intel 82574L Gigabit Network Connection                           | 50       | 1.24%   |
| Intel Ethernet Connection I217-LM                                 | 46       | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 39       | 0.97%   |
| Nvidia MCP61 Ethernet                                             | 38       | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 38       | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 37       | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 35       | 0.87%   |
| Intel Ethernet Connection (14) I219-V                             | 34       | 0.85%   |
| Realtek 802.11ac NIC                                              | 33       | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 33       | 0.82%   |
| Intel Wireless-AC 9260                                            | 29       | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28       | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 28       | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 27       | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27       | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24       | 0.6%    |
| Intel Wireless 3165                                               | 22       | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 19       | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18       | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 17       | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17       | 0.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 17       | 0.42%   |
| Ralink RT5370 Wireless Adapter                                    | 16       | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 16       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 16       | 0.4%    |
| Intel I350 Gigabit Network Connection                             | 16       | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 16       | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 0.37%   |
| Intel Wireless 7260                                               | 15       | 0.37%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 15       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 287      | 34.13%  |
| Realtek Semiconductor                 | 171      | 20.33%  |
| Qualcomm Atheros                      | 106      | 12.6%   |
| Ralink Technology                     | 67       | 7.97%   |
| Broadcom                              | 34       | 4.04%   |
| TP-Link                               | 31       | 3.69%   |
| Ralink                                | 31       | 3.69%   |
| Qualcomm Atheros Communications       | 14       | 1.66%   |
| Microsoft                             | 12       | 1.43%   |
| D-Link                                | 12       | 1.43%   |
| ASUSTek Computer                      | 12       | 1.43%   |
| D-Link System                         | 10       | 1.19%   |
| MediaTek                              | 9        | 1.07%   |
| NetGear                               | 8        | 0.95%   |
| Edimax Technology                     | 6        | 0.71%   |
| IMC Networks                          | 5        | 0.59%   |
| Gemtek                                | 4        | 0.48%   |
| Belkin Components                     | 4        | 0.48%   |
| Linksys                               | 3        | 0.36%   |
| Broadcom Limited                      | 3        | 0.36%   |
| Wilocity                              | 2        | 0.24%   |
| AVM                                   | 2        | 0.24%   |
| TRENDnet                              | 1        | 0.12%   |
| Sitecom Europe                        | 1        | 0.12%   |
| PLANEX                                | 1        | 0.12%   |
| Micro Star International              | 1        | 0.12%   |
| Marvell Technology Group              | 1        | 0.12%   |
| Fiberline                             | 1        | 0.12%   |
| BUFFALO                               | 1        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 85       | 10.01%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39       | 4.59%   |
| Realtek 802.11ac NIC                                           | 33       | 3.89%   |
| Intel Wireless-AC 9260                                         | 29       | 3.42%   |
| Ralink MT7601U Wireless Adapter                                | 27       | 3.18%   |
| Intel Wireless 3165                                            | 22       | 2.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 19       | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18       | 2.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 17       | 2%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 17       | 2%      |
| Ralink RT5370 Wireless Adapter                                 | 16       | 1.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.77%   |
| Intel Wireless 7260                                            | 15       | 1.77%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 14       | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13       | 1.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 12       | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12       | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12       | 1.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 11       | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10       | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 1.18%   |
| Intel Wireless 8260                                            | 10       | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8        | 0.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 8        | 0.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 7        | 0.82%   |
| Microsoft Xbox 360 Wireless Adapter                            | 7        | 0.82%   |
| Intel Wireless 7265                                            | 7        | 0.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 6        | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 6        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 6        | 0.71%   |
| Ralink RT5372 Wireless Adapter                                 | 6        | 0.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6        | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6        | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 6        | 0.71%   |
| Intel Wireless 8265 / 8275                                     | 6        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1624     | 54.33%  |
| Intel                                  | 904      | 30.24%  |
| Qualcomm Atheros                       | 126      | 4.22%   |
| Broadcom                               | 74       | 2.48%   |
| Nvidia                                 | 61       | 2.04%   |
| Marvell Technology Group               | 25       | 0.84%   |
| Broadcom Limited                       | 24       | 0.8%    |
| Aquantia                               | 19       | 0.64%   |
| VIA Technologies                       | 13       | 0.43%   |
| ASIX Electronics                       | 12       | 0.4%    |
| Samsung Electronics                    | 11       | 0.37%   |
| Mellanox Technologies                  | 11       | 0.37%   |
| D-Link System                          | 8        | 0.27%   |
| Huawei Technologies                    | 6        | 0.2%    |
| American Megatrends                    | 6        | 0.2%    |
| 3Com                                   | 6        | 0.2%    |
| Sundance Technology Inc / IC Plus      | 5        | 0.17%   |
| TP-Link                                | 4        | 0.13%   |
| Xiaomi                                 | 3        | 0.1%    |
| Silicon Integrated Systems [SiS]       | 3        | 0.1%    |
| QLogic                                 | 3        | 0.1%    |
| Microsoft                              | 3        | 0.1%    |
| Sony Ericsson Mobile Communications AB | 2        | 0.07%   |
| Qualcomm                               | 2        | 0.07%   |
| Motorola PCS                           | 2        | 0.07%   |
| MediaTek                               | 2        | 0.07%   |
| JMicron Technology                     | 2        | 0.07%   |
| ICS Advent                             | 2        | 0.07%   |
| Google                                 | 2        | 0.07%   |
| Gemtek                                 | 2        | 0.07%   |
| DisplayLink                            | 2        | 0.07%   |
| ADMtek                                 | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| SysKonnect                             | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |
| Solarflare Communications              | 1        | 0.03%   |
| OPPO Electronics                       | 1        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.03%   |
| Microchip Technology                   | 1        | 0.03%   |
| Linux 3.4.39 with sunxi_usb_udc        | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1400     | 44.87%  |
| Intel I211 Gigabit Network Connection                             | 154      | 4.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 90       | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 89       | 2.85%   |
| Intel Ethernet Connection (2) I219-V                              | 83       | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82       | 2.63%   |
| Intel 82579V Gigabit Network Connection                           | 58       | 1.86%   |
| Intel I210 Gigabit Network Connection                             | 52       | 1.67%   |
| Intel 82574L Gigabit Network Connection                           | 50       | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 46       | 1.47%   |
| Nvidia MCP61 Ethernet                                             | 38       | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 38       | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 37       | 1.19%   |
| Intel Ethernet Connection I217-V                                  | 35       | 1.12%   |
| Intel Ethernet Connection (14) I219-V                             | 34       | 1.09%   |
| Intel Ethernet Controller I225-V                                  | 33       | 1.06%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28       | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 28       | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 27       | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24       | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17       | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 16       | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 16       | 0.51%   |
| Intel I350 Gigabit Network Connection                             | 16       | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 16       | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 15       | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 14       | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12       | 0.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 12       | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12       | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 10       | 0.32%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9        | 0.29%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 9        | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                             | 9        | 0.29%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 9        | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8        | 0.26%   |
| Intel Ethernet Controller X550                                    | 8        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2722     | 76.4%   |
| WiFi     | 793      | 22.26%  |
| Modem    | 43       | 1.21%   |
| Unknown  | 5        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2395     | 86.96%  |
| WiFi     | 359      | 13.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1857     | 67.43%  |
| 2     | 686      | 24.91%  |
| 3     | 134      | 4.87%   |
| 4     | 28       | 1.02%   |
| 0     | 20       | 0.73%   |
| 6     | 12       | 0.44%   |
| 5     | 8        | 0.29%   |
| 8     | 4        | 0.15%   |
| 21    | 1        | 0.04%   |
| 13    | 1        | 0.04%   |
| 12    | 1        | 0.04%   |
| 9     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 2401     | 86.71%  |
| Yes     | 367      | 13.25%  |
| Unknown | 1        | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 273      | 42.92%  |
| Cambridge Silicon Radio         | 145      | 22.8%   |
| ASUSTek Computer                | 53       | 8.33%   |
| Broadcom                        | 48       | 7.55%   |
| Realtek Semiconductor           | 40       | 6.29%   |
| Qualcomm Atheros Communications | 30       | 4.72%   |
| IMC Networks                    | 12       | 1.89%   |
| MediaTek                        | 7        | 1.1%    |
| Apple                           | 6        | 0.94%   |
| Belkin Components               | 4        | 0.63%   |
| Micro Star International        | 2        | 0.31%   |
| Integrated System Solution      | 2        | 0.31%   |
| Foxconn / Hon Hai               | 2        | 0.31%   |
| Edimax Technology               | 2        | 0.31%   |
| TP-Link                         | 1        | 0.16%   |
| Toshiba                         | 1        | 0.16%   |
| Sitecom Europe                  | 1        | 0.16%   |
| Realtek                         | 1        | 0.16%   |
| Qcom                            | 1        | 0.16%   |
| Lite-On Technology              | 1        | 0.16%   |
| Kensington                      | 1        | 0.16%   |
| Dynex                           | 1        | 0.16%   |
| Com One                         | 1        | 0.16%   |
| Unknown                         | 1        | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 145      | 22.76%  |
| Intel AX200 Bluetooth                                 | 84       | 13.19%  |
| Intel Bluetooth wireless interface                    | 62       | 9.73%   |
| Intel Wireless-AC 3168 Bluetooth                      | 38       | 5.97%   |
| Realtek Bluetooth Radio                               | 34       | 5.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 31       | 4.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 31       | 4.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 20       | 3.14%   |
| Intel AX210 Bluetooth                                 | 17       | 2.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 16       | 2.51%   |
| Intel AX201 Bluetooth                                 | 15       | 2.35%   |
| Qualcomm Atheros  Bluetooth Device                    | 12       | 1.88%   |
| ASUS Bluetooth Adapter                                | 11       | 1.73%   |
| MediaTek Wireless_Device                              | 7        | 1.1%    |
| ASUS Bluetooth Radio                                  | 7        | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 6        | 0.94%   |
| IMC Networks Bluetooth Radio                          | 6        | 0.94%   |
| Realtek  Bluetooth 4.2 Adapter                        | 5        | 0.78%   |
| IMC Networks Bluetooth Device                         | 5        | 0.78%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 5        | 0.78%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 4        | 0.63%   |
| ASUS BCM20702A0                                       | 4        | 0.63%   |
| ASUS ASUS USB-BT500                                   | 4        | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3        | 0.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 3        | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 3        | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3        | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)       | 3        | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.47%   |
| Broadcom Bluetooth 3.0 Dongle                         | 3        | 0.47%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.47%   |
| ASUS Bluetooth Device                                 | 3        | 0.47%   |
| Apple Bluetooth USB Host Controller                   | 3        | 0.47%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 0.31%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 2        | 0.31%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 2        | 0.31%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 2        | 0.31%   |
| Apple Bluetooth HCI                                   | 2        | 0.31%   |
| TP-Link UB500 Adapter                                 | 1        | 0.16%   |
| Toshiba Atheros AR3012 Bluetooth                      | 1        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1708     | 41.93%  |
| AMD                                          | 953      | 23.4%   |
| Nvidia                                       | 918      | 22.54%  |
| C-Media Electronics                          | 83       | 2.04%   |
| Logitech                                     | 43       | 1.06%   |
| Creative Labs                                | 42       | 1.03%   |
| Texas Instruments                            | 21       | 0.52%   |
| Generalplus Technology                       | 18       | 0.44%   |
| ASUSTek Computer                             | 16       | 0.39%   |
| GN Netcom                                    | 15       | 0.37%   |
| Creative Technology                          | 15       | 0.37%   |
| Plantronics                                  | 14       | 0.34%   |
| JMTek                                        | 14       | 0.34%   |
| VIA Technologies                             | 13       | 0.32%   |
| Kingston Technology                          | 13       | 0.32%   |
| Focusrite-Novation                           | 11       | 0.27%   |
| Micro Star International                     | 9        | 0.22%   |
| GYROCOM C&C                                  | 8        | 0.2%    |
| RODE Microphones                             | 7        | 0.17%   |
| Dell                                         | 7        | 0.17%   |
| BEHRINGER International                      | 7        | 0.17%   |
| SteelSeries ApS                              | 6        | 0.15%   |
| Corsair                                      | 6        | 0.15%   |
| Blue Microphones                             | 6        | 0.15%   |
| Yamaha                                       | 5        | 0.12%   |
| Razer USA                                    | 5        | 0.12%   |
| Cambridge Silicon Radio                      | 5        | 0.12%   |
| Unknown                                      | 4        | 0.1%    |
| Tenx Technology                              | 4        | 0.1%    |
| Sennheiser Communications                    | 4        | 0.1%    |
| Samson Technologies                          | 4        | 0.1%    |
| Microsoft                                    | 4        | 0.1%    |
| M-Audio                                      | 4        | 0.1%    |
| XMOS                                         | 3        | 0.07%   |
| Samsung Electronics                          | 3        | 0.07%   |
| ROCCAT                                       | 3        | 0.07%   |
| Musical Fidelity                             | 3        | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.05%   |
| Valve Software                               | 2        | 0.05%   |
| TEAC                                         | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 249      | 5.25%   |
| AMD Starship/Matisse HD Audio Controller                                          | 216      | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 214      | 4.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 193      | 4.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 166      | 3.5%    |
| Intel 200 Series PCH HD Audio                                                     | 160      | 3.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 153      | 3.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 141      | 2.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 135      | 2.84%   |
| AMD Family 17h/19h HD Audio Controller                                            | 121      | 2.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 118      | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 110      | 2.32%   |
| Nvidia GF108 High Definition Audio Controller                                     | 87       | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 84       | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 81       | 1.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 80       | 1.69%   |
| AMD FCH Azalia Controller                                                         | 78       | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                        | 67       | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 63       | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 63       | 1.33%   |
| Nvidia High Definition Audio Controller                                           | 59       | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                                     | 57       | 1.2%    |
| Intel Comet Lake PCH cAVS                                                         | 56       | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 50       | 1.05%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 47       | 0.99%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 46       | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                                     | 45       | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 45       | 0.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 43       | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                                     | 42       | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                                     | 42       | 0.88%   |
| Nvidia MCP61 High Definition Audio                                                | 40       | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                                     | 36       | 0.76%   |
| Intel Audio device                                                                | 36       | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 35       | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                                     | 34       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 33       | 0.7%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 33       | 0.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 32       | 0.67%   |
| AMD Navi 10 HDMI Audio                                                            | 32       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 484      | 19.34%  |
| Unknown                      | 414      | 16.55%  |
| Crucial                      | 325      | 12.99%  |
| Samsung Electronics          | 238      | 9.51%   |
| Corsair                      | 214      | 8.55%   |
| SK hynix                     | 202      | 8.07%   |
| G.Skill                      | 163      | 6.51%   |
| Micron Technology            | 86       | 3.44%   |
| Patriot                      | 66       | 2.64%   |
| A-DATA Technology            | 33       | 1.32%   |
| Hikvision                    | 20       | 0.8%    |
| Team                         | 19       | 0.76%   |
| Unknown                      | 19       | 0.76%   |
| Nanya Technology             | 18       | 0.72%   |
| AMD                          | 18       | 0.72%   |
| Ramaxel Technology           | 17       | 0.68%   |
| Transcend                    | 15       | 0.6%    |
| Elpida                       | 15       | 0.6%    |
| Unknown (ABCD)               | 14       | 0.56%   |
| Smart                        | 10       | 0.4%    |
| GeIL                         | 7        | 0.28%   |
| Qimonda                      | 6        | 0.24%   |
| Hewlett-Packard              | 6        | 0.24%   |
| GOODRAM                      | 6        | 0.24%   |
| Apacer                       | 5        | 0.2%    |
| Timetec                      | 4        | 0.16%   |
| Toshiba                      | 3        | 0.12%   |
| Silicon Power                | 3        | 0.12%   |
| Kimtigo                      | 3        | 0.12%   |
| 48spaces                     | 3        | 0.12%   |
| Wilk Elektronik              | 2        | 0.08%   |
| V-Color                      | 2        | 0.08%   |
| Unifosa                      | 2        | 0.08%   |
| Teikon                       | 2        | 0.08%   |
| PNY                          | 2        | 0.08%   |
| Patriot Memory (PDP Systems) | 2        | 0.08%   |
| Kllisre                      | 2        | 0.08%   |
| KLEVV                        | 2        | 0.08%   |
| Kingmax                      | 2        | 0.08%   |
| KETECH                       | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                               | 36       | 1.29%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s           | 31       | 1.12%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s           | 31       | 1.12%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s          | 26       | 0.94%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s            | 24       | 0.86%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s         | 20       | 0.72%   |
| Unknown                                                         | 19       | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                        | 18       | 0.65%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s           | 18       | 0.65%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 17       | 0.61%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 17       | 0.61%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 16       | 0.58%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                 | 16       | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 15       | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 15       | 0.54%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 14       | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 14       | 0.5%    |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                  | 14       | 0.5%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s          | 14       | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                         | 13       | 0.47%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s          | 13       | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 13       | 0.47%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 13       | 0.47%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s           | 13       | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s           | 13       | 0.47%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s            | 12       | 0.43%   |
| Unknown RAM Module 1GB DIMM 800MT/s                             | 11       | 0.4%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 11       | 0.4%    |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s        | 11       | 0.4%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s             | 10       | 0.36%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s           | 10       | 0.36%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s            | 10       | 0.36%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 9        | 0.32%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s             | 9        | 0.32%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s             | 9        | 0.32%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s               | 9        | 0.32%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s             | 9        | 0.32%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 9        | 0.32%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s             | 9        | 0.32%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s         | 9        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 971      | 43.23%  |
| DDR3         | 805      | 35.84%  |
| Unknown      | 164      | 7.3%    |
| DDR2         | 134      | 5.97%   |
| SDRAM        | 123      | 5.48%   |
| DDR          | 26       | 1.16%   |
| LPDDR4       | 15       | 0.67%   |
| DRAM         | 4        | 0.18%   |
| DDR5         | 3        | 0.13%   |
| DDR2 FB-DIMM | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2081     | 93.99%  |
| SODIMM       | 116      | 5.24%   |
| FB-DIMM      | 8        | 0.36%   |
| RIMM         | 4        | 0.18%   |
| Unknown      | 3        | 0.14%   |
| Row Of Chips | 1        | 0.05%   |
| Chip         | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 792      | 32.39%  |
| 4096  | 587      | 24.01%  |
| 2048  | 416      | 17.01%  |
| 16384 | 376      | 15.38%  |
| 1024  | 128      | 5.24%   |
| 32768 | 108      | 4.42%   |
| 512   | 28       | 1.15%   |
| 256   | 5        | 0.2%    |
| 65536 | 2        | 0.08%   |
| 128   | 2        | 0.08%   |
| 1536  | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 482      | 19.84%  |
| 1333    | 282      | 11.61%  |
| 3200    | 182      | 7.49%   |
| 2667    | 173      | 7.12%   |
| 2400    | 153      | 6.3%    |
| 2133    | 141      | 5.8%    |
| 3600    | 119      | 4.9%    |
| 800     | 114      | 4.69%   |
| Unknown | 87       | 3.58%   |
| 667     | 79       | 3.25%   |
| 1866    | 69       | 2.84%   |
| 2666    | 68       | 2.8%    |
| 3466    | 36       | 1.48%   |
| 3000    | 36       | 1.48%   |
| 2933    | 35       | 1.44%   |
| 3400    | 33       | 1.36%   |
| 1867    | 32       | 1.32%   |
| 1066    | 32       | 1.32%   |
| 2866    | 26       | 1.07%   |
| 1067    | 23       | 0.95%   |
| 1800    | 18       | 0.74%   |
| 400     | 17       | 0.7%    |
| 3733    | 16       | 0.66%   |
| 533     | 15       | 0.62%   |
| 1334    | 14       | 0.58%   |
| 3800    | 11       | 0.45%   |
| 3100    | 9        | 0.37%   |
| 3333    | 8        | 0.33%   |
| 4333    | 7        | 0.29%   |
| 3334    | 7        | 0.29%   |
| 3066    | 7        | 0.29%   |
| 2048    | 7        | 0.29%   |
| 333     | 7        | 0.29%   |
| 3666    | 6        | 0.25%   |
| 3500    | 5        | 0.21%   |
| 1639    | 5        | 0.21%   |
| 3866    | 4        | 0.16%   |
| 2800    | 4        | 0.16%   |
| 2200    | 4        | 0.16%   |
| 1400    | 4        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 41       | 35.96%  |
| Brother Industries    | 22       | 19.3%   |
| Canon                 | 12       | 10.53%  |
| Samsung Electronics   | 9        | 7.89%   |
| Seiko Epson           | 4        | 3.51%   |
| Prolific Technology   | 4        | 3.51%   |
| Dymo-CoStar           | 4        | 3.51%   |
| Zebra                 | 3        | 2.63%   |
| Xerox                 | 3        | 2.63%   |
| Kyocera               | 2        | 1.75%   |
| STMicroelectronics    | 1        | 0.88%   |
| Ricoh                 | 1        | 0.88%   |
| QinHeng Electronics   | 1        | 0.88%   |
| Pantum                | 1        | 0.88%   |
| Oki Data              | 1        | 0.88%   |
| Lexmark International | 1        | 0.88%   |
| Konica Minolta        | 1        | 0.88%   |
| GODEX INTERNATIONAL   | 1        | 0.88%   |
| Dell                  | 1        | 0.88%   |
| Datamax-O'Neil        | 1        | 0.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                          | 6        | 5.22%   |
| Prolific PL2305 Parallel Port                             | 4        | 3.48%   |
| Xerox B205                                                | 3        | 2.61%   |
| HP LaserJet M101-M106                                     | 3        | 2.61%   |
| HP LaserJet 1200                                          | 3        | 2.61%   |
| Brother HL-52x0 series                                    | 3        | 2.61%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.74%   |
| Samsung ML-1660 Series                                    | 2        | 1.74%   |
| HP LaserJet Pro M404-M405                                 | 2        | 1.74%   |
| HP LaserJet P1005                                         | 2        | 1.74%   |
| HP LaserJet M14-M17                                       | 2        | 1.74%   |
| HP LaserJet 400 M401dne                                   | 2        | 1.74%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.74%   |
| HP ENVY 4520 series                                       | 2        | 1.74%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.74%   |
| Brother Printer                                           | 2        | 1.74%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.87%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.87%   |
| Zebra ZTC S4M-200dpi ZPL                                  | 1        | 0.87%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.87%   |
| Seiko Epson XP-15000 Series                               | 1        | 0.87%   |
| Seiko Epson Printer                                       | 1        | 0.87%   |
| Seiko Epson L4150 Series                                  | 1        | 0.87%   |
| Seiko Epson L395 Series                                   | 1        | 0.87%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 0.87%   |
| Samsung SCX-4600 Series                                   | 1        | 0.87%   |
| Samsung SCX-4200 series                                   | 1        | 0.87%   |
| Samsung SCX-3400 Series                                   | 1        | 0.87%   |
| Samsung SCX-3200 Series                                   | 1        | 0.87%   |
| Ricoh Aficio SP 100SU                                     | 1        | 0.87%   |
| QinHeng CH340S                                            | 1        | 0.87%   |
| Pantum P2500W series                                      | 1        | 0.87%   |
| Oki Data USB Device                                       | 1        | 0.87%   |
| Lexmark International CS417dn                             | 1        | 0.87%   |
| Kyocera FS-1120D                                          | 1        | 0.87%   |
| Kyocera ECOSYS M5521cdn                                   | 1        | 0.87%   |
| Konica Minolta bizhub 4402P                               | 1        | 0.87%   |
| HP PhotoSmart P1000                                       | 1        | 0.87%   |
| HP Officejet J4500 series                                 | 1        | 0.87%   |
| HP Officejet 7110 series                                  | 1        | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 21       | 60%     |
| Seiko Epson        | 6        | 17.14%  |
| Hewlett-Packard    | 4        | 11.43%  |
| AGFA-Gevaert NV    | 2        | 5.71%   |
| Ultima Electronics | 1        | 2.86%   |
| Mustek Systems     | 1        | 2.86%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4        | 11.43%  |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 5.71%   |
| Canon CanoScan LiDE 220                                                               | 2        | 5.71%   |
| Canon CanoScan LiDE 210                                                               | 2        | 5.71%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2        | 5.71%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 2.86%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 2.86%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 2.86%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 2.86%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 2.86%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 2.86%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 2.86%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 2.86%   |
| HP ScanJet Pro 2500 f1                                                                | 1        | 2.86%   |
| HP ScanJet 82x0C                                                                      | 1        | 2.86%   |
| HP ScanJet 3970c                                                                      | 1        | 2.86%   |
| HP Scanjet 300                                                                        | 1        | 2.86%   |
| Canon CanoScan LIDE 25                                                                | 1        | 2.86%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 2.86%   |
| Canon CanoScan 8800F                                                                  | 1        | 2.86%   |
| Canon CanoScan 5600F                                                                  | 1        | 2.86%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 183      | 44.1%   |
| Microdia                               | 36       | 8.67%   |
| Microsoft                              | 23       | 5.54%   |
| Samsung Electronics                    | 19       | 4.58%   |
| Generalplus Technology                 | 18       | 4.34%   |
| Sunplus Innovation Technology          | 15       | 3.61%   |
| Z-Star Microelectronics                | 11       | 2.65%   |
| Creative Technology                    | 11       | 2.65%   |
| Apple                                  | 10       | 2.41%   |
| KYE Systems (Mouse Systems)            | 8        | 1.93%   |
| Jieli Technology                       | 8        | 1.93%   |
| ARC International                      | 8        | 1.93%   |
| GEMBIRD                                | 6        | 1.45%   |
| Hewlett-Packard                        | 4        | 0.96%   |
| Genesys Logic                          | 4        | 0.96%   |
| Chicony Electronics                    | 4        | 0.96%   |
| Realtek Semiconductor                  | 3        | 0.72%   |
| MacroSilicon                           | 3        | 0.72%   |
| Huawei Technologies                    | 3        | 0.72%   |
| Xiongmai                               | 2        | 0.48%   |
| Trust                                  | 2        | 0.48%   |
| Novatek Microelectronics               | 2        | 0.48%   |
| Nintendo                               | 2        | 0.48%   |
| Cubeternet                             | 2        | 0.48%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.48%   |
| AVerMedia Technologies                 | 2        | 0.48%   |
| Xiaomi                                 | 1        | 0.24%   |
| Valve Software                         | 1        | 0.24%   |
| Unknown                                | 1        | 0.24%   |
| Syntek                                 | 1        | 0.24%   |
| SiGma Micro                            | 1        | 0.24%   |
| Ruision                                | 1        | 0.24%   |
| Razer USA                              | 1        | 0.24%   |
| Quanta                                 | 1        | 0.24%   |
| Pixart Imaging                         | 1        | 0.24%   |
| Philips (or NXP)                       | 1        | 0.24%   |
| OmniVision Technologies                | 1        | 0.24%   |
| Mimaki Engineering                     | 1        | 0.24%   |
| Linux Foundation                       | 1        | 0.24%   |
| Lenovo                                 | 1        | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 51       | 12.23%  |
| Logitech HD Pro Webcam C920                       | 26       | 6.24%   |
| Samsung Galaxy A5 (MTP)                           | 18       | 4.32%   |
| Logitech C922 Pro Stream Webcam                   | 18       | 4.32%   |
| Microsoft LifeCam HD-3000                         | 13       | 3.12%   |
| Generalplus GENERAL WEBCAM                        | 12       | 2.88%   |
| Logitech Webcam C170                              | 11       | 2.64%   |
| Apple iPhone5/5C/5S/6                             | 10       | 2.4%    |
| Microdia Webcam Vitade AF                         | 9        | 2.16%   |
| Logitech HD Webcam C910                           | 8        | 1.92%   |
| Logitech HD Webcam C525                           | 8        | 1.92%   |
| Jieli USB PHY 2.0                                 | 8        | 1.92%   |
| Microdia CameraA                                  | 7        | 1.68%   |
| Logitech Webcam C310                              | 7        | 1.68%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 1.44%   |
| Logitech HD Webcam C615                           | 6        | 1.44%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 6        | 1.44%   |
| Sunplus PAPALOOK_229AF                            | 5        | 1.2%    |
| Microdia USB 2.0 Camera                           | 5        | 1.2%    |
| Logitech BRIO Ultra HD Webcam                     | 5        | 1.2%    |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam   | 5        | 1.2%    |
| Creative Live! Cam Chat HD [VF0700]               | 5        | 1.2%    |
| ARC International Camera                          | 5        | 1.2%    |
| Microdia Integrated Camera                        | 4        | 0.96%   |
| Microdia Camera                                   | 4        | 0.96%   |
| Logitech C920 PRO HD Webcam                       | 4        | 0.96%   |
| Microsoft LifeCam VX-500 [1357]                   | 3        | 0.72%   |
| Microdia Sonix USB 2.0 Camera                     | 3        | 0.72%   |
| Logitech Webcam Pro 9000                          | 3        | 0.72%   |
| Logitech Webcam C925e                             | 3        | 0.72%   |
| Logitech Webcam C210                              | 3        | 0.72%   |
| Logitech HD Webcam C510                           | 3        | 0.72%   |
| Huawei HiCamera                                   | 3        | 0.72%   |
| GEMBIRD USB2.0 PC CAMERA                          | 3        | 0.72%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 0.72%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 2        | 0.48%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 2        | 0.48%   |
| Xiongmai web camera                               | 2        | 0.48%   |
| Sunplus HK 1080P K20Pro                           | 2        | 0.48%   |
| Novatek HP High Definition 2MP Webcam             | 2        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 50%     |
| Elan Microelectronics | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 50%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Gemalto (was Gemplus)      | 4        | 14.81%  |
| Alcor Micro                | 4        | 14.81%  |
| SCM Microsystems           | 3        | 11.11%  |
| Clay Logic                 | 3        | 11.11%  |
| Cherry                     | 3        | 11.11%  |
| Yubico.com                 | 2        | 7.41%   |
| Chicony Electronics        | 2        | 7.41%   |
| Aladdin Knowledge Systems  | 2        | 7.41%   |
| Reiner SCT Kartensysteme   | 1        | 3.7%    |
| Realtek Semiconductor      | 1        | 3.7%    |
| Athena Smartcard Solutions | 1        | 3.7%    |
| Advanced Card Systems      | 1        | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 11.11%  |
| Clay Logic Nitrokey Pro                                                    | 2        | 7.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 7.41%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 7.41%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 3.7%    |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 3.7%    |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 3.7%    |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 3.7%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 3.7%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 3.7%    |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 3.7%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 3.7%    |
| Clay Logic Nitrokey Start                                                  | 1        | 3.7%    |
| Cherry SmartTerminal XX1X                                                  | 1        | 3.7%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 3.7%    |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                 | 1        | 3.7%    |
| Athena Smartcard Solutions ASEDrive CCID                                   | 1        | 3.7%    |
| Alcor Micro Watchdata W 1981                                               | 1        | 3.7%    |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1818     | 65.44%  |
| 1     | 836      | 30.09%  |
| 2     | 106      | 3.82%   |
| 3     | 11       | 0.4%    |
| 6     | 2        | 0.07%   |
| 5     | 2        | 0.07%   |
| 4     | 2        | 0.07%   |
| 7     | 1        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 755      | 72.11%  |
| Net/wireless             | 72       | 6.88%   |
| Communication controller | 50       | 4.78%   |
| Unassigned class         | 48       | 4.58%   |
| Multimedia controller    | 24       | 2.29%   |
| Sound                    | 22       | 2.1%    |
| Net/ethernet             | 13       | 1.24%   |
| Chipcard                 | 12       | 1.15%   |
| Card reader              | 10       | 0.96%   |
| Bluetooth                | 10       | 0.96%   |
| Camera                   | 6        | 0.57%   |
| Network                  | 5        | 0.48%   |
| Storage/raid             | 4        | 0.38%   |
| Storage/ide              | 4        | 0.38%   |
| Dvb card                 | 3        | 0.29%   |
| Tv card                  | 2        | 0.19%   |
| Storage                  | 2        | 0.19%   |
| Modem                    | 2        | 0.19%   |
| Fingerprint reader       | 2        | 0.19%   |
| Storage/ata              | 1        | 0.1%    |


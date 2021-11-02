Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X399 Taichi                 | [70d528a8fc](https://linux-hardware.org/?probe=70d528a8fc) | Oct 31, 2021 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [5adc857043](https://linux-hardware.org/?probe=5adc857043) | Oct 31, 2021 |
| Gigabyte      | B460M DS3H V2               | [83857e3215](https://linux-hardware.org/?probe=83857e3215) | Oct 29, 2021 |
| Gigabyte      | P55M-UD2                    | [b14c0e8dd2](https://linux-hardware.org/?probe=b14c0e8dd2) | Oct 29, 2021 |
| HP            | 1998                        | [b9e492678d](https://linux-hardware.org/?probe=b9e492678d) | Oct 29, 2021 |
| ASUSTek       | P5Q-EM                      | [ce2c332b33](https://linux-hardware.org/?probe=ce2c332b33) | Oct 29, 2021 |
| Acer          | Aspire XC600 v1.0           | [58dfae44e0](https://linux-hardware.org/?probe=58dfae44e0) | Oct 29, 2021 |
| ASUSTek       | M5A97                       | [83a2d81e1c](https://linux-hardware.org/?probe=83a2d81e1c) | Oct 29, 2021 |
| HP            | 0AECh D                     | [15a01d5e13](https://linux-hardware.org/?probe=15a01d5e13) | Oct 28, 2021 |
| HP            | 3047h                       | [eedab3769c](https://linux-hardware.org/?probe=eedab3769c) | Oct 28, 2021 |
| Gigabyte      | Q270M-D3H                   | [6ad4929a33](https://linux-hardware.org/?probe=6ad4929a33) | Oct 28, 2021 |
| Intel         | D945GCCR AAD78647-300       | [d41d75c998](https://linux-hardware.org/?probe=d41d75c998) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [369b39d1be](https://linux-hardware.org/?probe=369b39d1be) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [5b7faf1cc6](https://linux-hardware.org/?probe=5b7faf1cc6) | Oct 28, 2021 |
| MSI           | MEG X570 UNIFY              | [7c73c4e6f0](https://linux-hardware.org/?probe=7c73c4e6f0) | Oct 27, 2021 |
| ASUSTek       | M4A77T                      | [07942589ae](https://linux-hardware.org/?probe=07942589ae) | Oct 27, 2021 |
| Intel         | H55                         | [b32e64a698](https://linux-hardware.org/?probe=b32e64a698) | Oct 27, 2021 |
| Dell          | 06FW8P A02                  | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [b47e0921b6](https://linux-hardware.org/?probe=b47e0921b6) | Oct 25, 2021 |
| Dell          | 06FW8P A02                  | [3e6b56c5f9](https://linux-hardware.org/?probe=3e6b56c5f9) | Oct 25, 2021 |
| ASRock        | X399 Taichi                 | [88030b7fcb](https://linux-hardware.org/?probe=88030b7fcb) | Oct 25, 2021 |
| ASRock        | X399 Taichi                 | [ae0cd83502](https://linux-hardware.org/?probe=ae0cd83502) | Oct 25, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [487d0f0e12](https://linux-hardware.org/?probe=487d0f0e12) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K               | [fd2f79c5fc](https://linux-hardware.org/?probe=fd2f79c5fc) | Oct 24, 2021 |
| Dell          | 0KRC95 A00                  | [117223995c](https://linux-hardware.org/?probe=117223995c) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | [e97646cc2e](https://linux-hardware.org/?probe=e97646cc2e) | Oct 23, 2021 |
| MSI           | FM2-A55M-E33                | [08a5e38790](https://linux-hardware.org/?probe=08a5e38790) | Oct 22, 2021 |
| ASUSTek       | H81M-A                      | [c7a2305704](https://linux-hardware.org/?probe=c7a2305704) | Oct 21, 2021 |
| ASRock        | G31M-VS2                    | [c36147b6a6](https://linux-hardware.org/?probe=c36147b6a6) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | [8d1ec3a3b6](https://linux-hardware.org/?probe=8d1ec3a3b6) | Oct 21, 2021 |
| ASRock        | G31M-VS2                    | [0c016119e3](https://linux-hardware.org/?probe=0c016119e3) | Oct 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [3cdf9d520e](https://linux-hardware.org/?probe=3cdf9d520e) | Oct 21, 2021 |
| Dell          | 02YRK5 A01                  | [d7c89a5f6a](https://linux-hardware.org/?probe=d7c89a5f6a) | Oct 21, 2021 |
| ASRock        | B365M Pro4                  | [ec939fb289](https://linux-hardware.org/?probe=ec939fb289) | Oct 20, 2021 |
| American M... | K7S41GX                     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | [4899fa0cab](https://linux-hardware.org/?probe=4899fa0cab) | Oct 19, 2021 |
| Digiboard     | MPxx                        | [138c2ef6fb](https://linux-hardware.org/?probe=138c2ef6fb) | Oct 19, 2021 |
| ASRock        | B450 Pro4                   | [b5f275b4c4](https://linux-hardware.org/?probe=b5f275b4c4) | Oct 17, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [5c4edf2e8d](https://linux-hardware.org/?probe=5c4edf2e8d) | Oct 17, 2021 |
| Dell          | 0D6H9T A01                  | [795b03a6f8](https://linux-hardware.org/?probe=795b03a6f8) | Oct 16, 2021 |
| Pegatron      | 2AC2A                       | [b59ab42003](https://linux-hardware.org/?probe=b59ab42003) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [d54d095b0d](https://linux-hardware.org/?probe=d54d095b0d) | Oct 15, 2021 |
| HP            | 84FD 10                     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| ASRock        | H510M-HDV/M.2               | [3d41f5d139](https://linux-hardware.org/?probe=3d41f5d139) | Oct 14, 2021 |
| Intel         | DP43BF AAE78171-301         | [42df25414b](https://linux-hardware.org/?probe=42df25414b) | Oct 14, 2021 |
| Intel         | DP43BF AAE78171-301         | [b08c85ef1a](https://linux-hardware.org/?probe=b08c85ef1a) | Oct 14, 2021 |
| ASUSTek       | B85M-G                      | [7facc39e0e](https://linux-hardware.org/?probe=7facc39e0e) | Oct 14, 2021 |
| ASUSTek       | B85M-G                      | [65477965f4](https://linux-hardware.org/?probe=65477965f4) | Oct 14, 2021 |
| ASRock        | B550M Pro4                  | [6847e8306e](https://linux-hardware.org/?probe=6847e8306e) | Oct 14, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [6bd5cc2d9b](https://linux-hardware.org/?probe=6bd5cc2d9b) | Oct 14, 2021 |
| Dell          | 0773VG A02                  | [ecd9b7c720](https://linux-hardware.org/?probe=ecd9b7c720) | Oct 14, 2021 |
| Dell          | 0C2KJT A00                  | [0175c5181a](https://linux-hardware.org/?probe=0175c5181a) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [82de48bc60](https://linux-hardware.org/?probe=82de48bc60) | Oct 13, 2021 |
| Pegatron      | IPXCR-VN1                   | [695f542c6c](https://linux-hardware.org/?probe=695f542c6c) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [e3a92a65f5](https://linux-hardware.org/?probe=e3a92a65f5) | Oct 13, 2021 |
| Unknown       | LakePort                    | [24159c8d9e](https://linux-hardware.org/?probe=24159c8d9e) | Oct 13, 2021 |
| Lenovo        | SHARKBAY 0B98405 STD        | [6d09c42ade](https://linux-hardware.org/?probe=6d09c42ade) | Oct 12, 2021 |
| Gigabyte      | Z590 UD AC                  | [ec7ba8e11a](https://linux-hardware.org/?probe=ec7ba8e11a) | Oct 12, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [34774c0428](https://linux-hardware.org/?probe=34774c0428) | Oct 12, 2021 |
| ASUSTek       | B85M-G                      | [34fe4b38c7](https://linux-hardware.org/?probe=34fe4b38c7) | Oct 12, 2021 |
| MSI           | P43 Neo-F                   | [d79f0f85c1](https://linux-hardware.org/?probe=d79f0f85c1) | Oct 12, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [59f755658e](https://linux-hardware.org/?probe=59f755658e) | Oct 12, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [3638982195](https://linux-hardware.org/?probe=3638982195) | Oct 12, 2021 |
| ASUSTek       | H81M-E                      | [8ab9e5cc4b](https://linux-hardware.org/?probe=8ab9e5cc4b) | Oct 11, 2021 |
| Sun Micros... | Ultra 27 52                 | [144b473603](https://linux-hardware.org/?probe=144b473603) | Oct 11, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e776648230](https://linux-hardware.org/?probe=e776648230) | Oct 11, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [46f9cbae92](https://linux-hardware.org/?probe=46f9cbae92) | Oct 11, 2021 |
| HP            | 1589                        | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| MSI           | B150M Night Elf             | [ed3f4e9937](https://linux-hardware.org/?probe=ed3f4e9937) | Oct 09, 2021 |
| ASRock        | H110M-ITX/ac                | [261f3477ea](https://linux-hardware.org/?probe=261f3477ea) | Oct 09, 2021 |
| ASRock        | B75 Pro3-M                  | [62522e187a](https://linux-hardware.org/?probe=62522e187a) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | [e709e42b6e](https://linux-hardware.org/?probe=e709e42b6e) | Oct 09, 2021 |
| Dell          | 0RW199                      | [265977f345](https://linux-hardware.org/?probe=265977f345) | Oct 08, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | [d6391c098d](https://linux-hardware.org/?probe=d6391c098d) | Oct 08, 2021 |
| MSI           | B550-A PRO                  | [3c5d005ffb](https://linux-hardware.org/?probe=3c5d005ffb) | Oct 08, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [f180e5db7d](https://linux-hardware.org/?probe=f180e5db7d) | Oct 07, 2021 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [b8531e8039](https://linux-hardware.org/?probe=b8531e8039) | Oct 07, 2021 |
| HP            | 1998                        | [1a06c2831b](https://linux-hardware.org/?probe=1a06c2831b) | Oct 07, 2021 |
| HP            | 1998                        | [152a505ffd](https://linux-hardware.org/?probe=152a505ffd) | Oct 07, 2021 |
| HP            | 1998                        | [639a06485d](https://linux-hardware.org/?probe=639a06485d) | Oct 07, 2021 |
| Dell          | 06FW8P A02                  | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Pegatron      | 2A99                        | [10f364b4ef](https://linux-hardware.org/?probe=10f364b4ef) | Oct 07, 2021 |
| ASUSTek       | P5G41T-M LE                 | [9578e01f5b](https://linux-hardware.org/?probe=9578e01f5b) | Oct 06, 2021 |
| ASRock        | AM1B-ITX                    | [417050a11e](https://linux-hardware.org/?probe=417050a11e) | Oct 06, 2021 |
| Gigabyte      | B75M-D2V                    | [dca9b0f592](https://linux-hardware.org/?probe=dca9b0f592) | Oct 05, 2021 |
| ASUSTek       | H110M-R                     | [95f6633ea0](https://linux-hardware.org/?probe=95f6633ea0) | Oct 04, 2021 |
| MSI           | H81M-P33                    | [a0fffdb381](https://linux-hardware.org/?probe=a0fffdb381) | Oct 04, 2021 |
| ASUSTek       | P8H61-M LX2                 | [69ac6e6156](https://linux-hardware.org/?probe=69ac6e6156) | Oct 04, 2021 |
| Gigabyte      | MZBAYAB-00                  | [3040e45974](https://linux-hardware.org/?probe=3040e45974) | Oct 02, 2021 |
| ASUSTek       | PRIME B450M-K               | [666c41eb03](https://linux-hardware.org/?probe=666c41eb03) | Oct 01, 2021 |
| ASUSTek       | B85M-G                      | [0228744a56](https://linux-hardware.org/?probe=0228744a56) | Oct 01, 2021 |
| ASRock        | FM2A88X+ Killer             | [689bc2e25f](https://linux-hardware.org/?probe=689bc2e25f) | Oct 01, 2021 |
| ASUSTek       | B85M-E/BR                   | [29ae8992b5](https://linux-hardware.org/?probe=29ae8992b5) | Sep 30, 2021 |
| Foxconn       | 2ABF                        | [de498adb08](https://linux-hardware.org/?probe=de498adb08) | Sep 30, 2021 |
| HP            | 3047h                       | [89b3f0a1ad](https://linux-hardware.org/?probe=89b3f0a1ad) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [201d45c8e0](https://linux-hardware.org/?probe=201d45c8e0) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [508593e110](https://linux-hardware.org/?probe=508593e110) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [0a0b3ced3f](https://linux-hardware.org/?probe=0a0b3ced3f) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [b083b87cc1](https://linux-hardware.org/?probe=b083b87cc1) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [6bf4c617bf](https://linux-hardware.org/?probe=6bf4c617bf) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [2891a2fc4e](https://linux-hardware.org/?probe=2891a2fc4e) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1969de09f1](https://linux-hardware.org/?probe=1969de09f1) | Sep 30, 2021 |
| Intel         | DN2820FYK H24582-201        | [75eb93bbe0](https://linux-hardware.org/?probe=75eb93bbe0) | Sep 29, 2021 |
| MSI           | H81M-P33                    | [c7540ecd61](https://linux-hardware.org/?probe=c7540ecd61) | Sep 29, 2021 |
| Digiboard     | MPxx                        | [bad4baa7aa](https://linux-hardware.org/?probe=bad4baa7aa) | Sep 28, 2021 |
| ASRock        | B450M Pro4-F                | [997cfe39d2](https://linux-hardware.org/?probe=997cfe39d2) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | Pro WS 565-ACE              | [55315b68ec](https://linux-hardware.org/?probe=55315b68ec) | Sep 28, 2021 |
| ASUSTek       | Pro WS 565-ACE              | [5849e72724](https://linux-hardware.org/?probe=5849e72724) | Sep 28, 2021 |
| MSI           | B350 PC MATE                | [b8427dd0a9](https://linux-hardware.org/?probe=b8427dd0a9) | Sep 27, 2021 |
| Dell          | 06FW8P A02                  | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| ASRockRack    | ROMED8-2T                   | [c0104aa33d](https://linux-hardware.org/?probe=c0104aa33d) | Sep 27, 2021 |
| Dell          | 0X8DXD A00                  | [9870240430](https://linux-hardware.org/?probe=9870240430) | Sep 27, 2021 |
| ASUSTek       | PRIME X470-PRO              | [85925128ef](https://linux-hardware.org/?probe=85925128ef) | Sep 27, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [ee4f0f6f02](https://linux-hardware.org/?probe=ee4f0f6f02) | Sep 27, 2021 |
| MSI           | B350 PC MATE                | [6500bed04d](https://linux-hardware.org/?probe=6500bed04d) | Sep 26, 2021 |
| ASUSTek       | TUF GAMING H570-PRO         | [97c090583f](https://linux-hardware.org/?probe=97c090583f) | Sep 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [26897714a0](https://linux-hardware.org/?probe=26897714a0) | Sep 26, 2021 |
| Dell          | 018D1Y A00                  | [7ffbeea841](https://linux-hardware.org/?probe=7ffbeea841) | Sep 26, 2021 |
| ECS           | G31T-M9                     | [e0cdbe10a3](https://linux-hardware.org/?probe=e0cdbe10a3) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| ASUSTek       | P8H77-V LE                  | [76445d703b](https://linux-hardware.org/?probe=76445d703b) | Sep 24, 2021 |
| Dell          | 0DFRFW A01                  | [22132026c3](https://linux-hardware.org/?probe=22132026c3) | Sep 24, 2021 |
| Intel         | DH67CL AAG10212-205         | [652a4e63cd](https://linux-hardware.org/?probe=652a4e63cd) | Sep 24, 2021 |
| Acer          | Revo 70                     | [beb207e679](https://linux-hardware.org/?probe=beb207e679) | Sep 24, 2021 |
| Intel         | DH67CL AAG10212-210         | [5e1a7fc6bc](https://linux-hardware.org/?probe=5e1a7fc6bc) | Sep 24, 2021 |
| ASRock        | AM1B-ITX                    | [5ffe158a0b](https://linux-hardware.org/?probe=5ffe158a0b) | Sep 24, 2021 |
| Dell          | 0DFRFW A01                  | [166930508c](https://linux-hardware.org/?probe=166930508c) | Sep 24, 2021 |
| Lenovo        | ThinkStation S20 4105L1U    | [593eda37d7](https://linux-hardware.org/?probe=593eda37d7) | Sep 23, 2021 |
| Acer          | Revo 70                     | [138db946a6](https://linux-hardware.org/?probe=138db946a6) | Sep 23, 2021 |
| ASUSTek       | P8H67-M                     | [b77c25619c](https://linux-hardware.org/?probe=b77c25619c) | Sep 23, 2021 |
| ASUSTek       | P8H67-M                     | [8d162e55d8](https://linux-hardware.org/?probe=8d162e55d8) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | [3e95020892](https://linux-hardware.org/?probe=3e95020892) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | [f43227bf66](https://linux-hardware.org/?probe=f43227bf66) | Sep 23, 2021 |
| ASRock        | AM1B-ITX                    | [5896638049](https://linux-hardware.org/?probe=5896638049) | Sep 22, 2021 |
| Gigabyte      | H81M-H                      | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | [259707c0a4](https://linux-hardware.org/?probe=259707c0a4) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | [50f1e050a8](https://linux-hardware.org/?probe=50f1e050a8) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | [37c5e8334c](https://linux-hardware.org/?probe=37c5e8334c) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | [581dba008c](https://linux-hardware.org/?probe=581dba008c) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | [635bf47b02](https://linux-hardware.org/?probe=635bf47b02) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | [8a38fba20f](https://linux-hardware.org/?probe=8a38fba20f) | Sep 22, 2021 |
| ASUSTek       | P8B75-V                     | [84fc3eb5f2](https://linux-hardware.org/?probe=84fc3eb5f2) | Sep 22, 2021 |
| HP            | 8298                        | [5517c4780d](https://linux-hardware.org/?probe=5517c4780d) | Sep 22, 2021 |
| ASUSTek       | H110M-R                     | [09083b7dad](https://linux-hardware.org/?probe=09083b7dad) | Sep 22, 2021 |
| ASUSTek       | P8B75-V                     | [cf5436e8a1](https://linux-hardware.org/?probe=cf5436e8a1) | Sep 22, 2021 |
| ECS           | G31T-M9                     | [92ecc52d2f](https://linux-hardware.org/?probe=92ecc52d2f) | Sep 22, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [0dcd3691cd](https://linux-hardware.org/?probe=0dcd3691cd) | Sep 21, 2021 |
| ASRock        | FM2A68M-HD+                 | [c2a3074723](https://linux-hardware.org/?probe=c2a3074723) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [8d112d9531](https://linux-hardware.org/?probe=8d112d9531) | Sep 21, 2021 |
| Dell          | 040DDP A01                  | [f2e1fbb30c](https://linux-hardware.org/?probe=f2e1fbb30c) | Sep 21, 2021 |
| ASRock        | B550M Pro4                  | [d6e37b9488](https://linux-hardware.org/?probe=d6e37b9488) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [b767020eb6](https://linux-hardware.org/?probe=b767020eb6) | Sep 21, 2021 |
| Intel         | DQ35JO AAD82085-800         | [3751d2399e](https://linux-hardware.org/?probe=3751d2399e) | Sep 21, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [7e46c0bea0](https://linux-hardware.org/?probe=7e46c0bea0) | Sep 20, 2021 |
| ASUSTek       | PRIME H410M-E               | [d5776c4fd0](https://linux-hardware.org/?probe=d5776c4fd0) | Sep 20, 2021 |
| ASUSTek       | PRIME H410M-E               | [7be63eda40](https://linux-hardware.org/?probe=7be63eda40) | Sep 20, 2021 |
| HP            | 8433 11                     | [5c7a7c98e8](https://linux-hardware.org/?probe=5c7a7c98e8) | Sep 19, 2021 |
| HP            | 225E                        | [eadad0eb90](https://linux-hardware.org/?probe=eadad0eb90) | Sep 19, 2021 |
| Gigabyte      | GB-BLCE-4105R               | [3a1284b530](https://linux-hardware.org/?probe=3a1284b530) | Sep 19, 2021 |
| ASUSTek       | H81M-PLUS                   | [7a0ce4b17e](https://linux-hardware.org/?probe=7a0ce4b17e) | Sep 19, 2021 |
| Gigabyte      | P35-DS3                     | [32413546ce](https://linux-hardware.org/?probe=32413546ce) | Sep 18, 2021 |
| ECS           | H61H2-M13                   | [ebc7aac8d2](https://linux-hardware.org/?probe=ebc7aac8d2) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [cc91d3d293](https://linux-hardware.org/?probe=cc91d3d293) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [cf7b743325](https://linux-hardware.org/?probe=cf7b743325) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [58efd773fc](https://linux-hardware.org/?probe=58efd773fc) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [6f61a4bed1](https://linux-hardware.org/?probe=6f61a4bed1) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [2847b27014](https://linux-hardware.org/?probe=2847b27014) | Sep 17, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | [f6cde497b4](https://linux-hardware.org/?probe=f6cde497b4) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [ca5062256b](https://linux-hardware.org/?probe=ca5062256b) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [8b0908956f](https://linux-hardware.org/?probe=8b0908956f) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [35b84b3b23](https://linux-hardware.org/?probe=35b84b3b23) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [fd3abf36d9](https://linux-hardware.org/?probe=fd3abf36d9) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | [49001d8064](https://linux-hardware.org/?probe=49001d8064) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | [3fde672bb3](https://linux-hardware.org/?probe=3fde672bb3) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | [77f32a8e42](https://linux-hardware.org/?probe=77f32a8e42) | Sep 17, 2021 |
| MSI           | Z370 PC PRO                 | [c79178e6db](https://linux-hardware.org/?probe=c79178e6db) | Sep 17, 2021 |
| Dell          | 0X8DXD A00                  | [1fe7a4c597](https://linux-hardware.org/?probe=1fe7a4c597) | Sep 17, 2021 |
| Dell          | 0X8DXD A00                  | [cbe5d18ac2](https://linux-hardware.org/?probe=cbe5d18ac2) | Sep 17, 2021 |
| Libretrend    | LT1000                      | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| ECS           | G31T-M9                     | [ba4a294b69](https://linux-hardware.org/?probe=ba4a294b69) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | [d1a7e38fc8](https://linux-hardware.org/?probe=d1a7e38fc8) | Sep 16, 2021 |
| ASUSTek       | PRIME X570-P                | [3ef71721e0](https://linux-hardware.org/?probe=3ef71721e0) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| ASUSTek       | B75M-PLUS                   | [6056c96428](https://linux-hardware.org/?probe=6056c96428) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-A               | [4bb2af8998](https://linux-hardware.org/?probe=4bb2af8998) | Sep 16, 2021 |
| ASRock        | H470M-HVS                   | [233ad54ef9](https://linux-hardware.org/?probe=233ad54ef9) | Sep 16, 2021 |
| ASRock        | H470M-HVS                   | [d4e804931a](https://linux-hardware.org/?probe=d4e804931a) | Sep 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [f6f26d4c8e](https://linux-hardware.org/?probe=f6f26d4c8e) | Sep 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [54e89a0f5a](https://linux-hardware.org/?probe=54e89a0f5a) | Sep 14, 2021 |
| Positivo      | POS-PIQ77CL                 | [87ec217aed](https://linux-hardware.org/?probe=87ec217aed) | Sep 14, 2021 |
| ASUSTek       | P5Q-EM                      | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| MSI           | H81M-P33                    | [b5b64471de](https://linux-hardware.org/?probe=b5b64471de) | Sep 13, 2021 |
| Dell          | 0KC9NP A01                  | [3be45aba31](https://linux-hardware.org/?probe=3be45aba31) | Sep 13, 2021 |
| ASRock        | AM1B-ITX                    | [b15ebc1577](https://linux-hardware.org/?probe=b15ebc1577) | Sep 13, 2021 |
| MSI           | Z170-A PRO                  | [5b702a6c05](https://linux-hardware.org/?probe=5b702a6c05) | Sep 12, 2021 |
| Gigabyte      | H81M-S                      | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [cf7cbe9ec0](https://linux-hardware.org/?probe=cf7cbe9ec0) | Sep 12, 2021 |
| MSI           | A68HM-E33 V2                | [1fc1622a64](https://linux-hardware.org/?probe=1fc1622a64) | Sep 12, 2021 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [f81450ac96](https://linux-hardware.org/?probe=f81450ac96) | Sep 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | [c9bcb0db96](https://linux-hardware.org/?probe=c9bcb0db96) | Sep 11, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | [0e9729a88b](https://linux-hardware.org/?probe=0e9729a88b) | Sep 11, 2021 |
| Acer          | Aspire M3420                | [dfd381db06](https://linux-hardware.org/?probe=dfd381db06) | Sep 10, 2021 |
| Acer          | Aspire M3420                | [7a4ab56f68](https://linux-hardware.org/?probe=7a4ab56f68) | Sep 10, 2021 |
| Gigabyte      | H61M-DS2                    | [c2b2ebce62](https://linux-hardware.org/?probe=c2b2ebce62) | Sep 09, 2021 |
| ASUSTek       | P6T DELUXE V2               | [3fa68fe391](https://linux-hardware.org/?probe=3fa68fe391) | Sep 09, 2021 |
| Gigabyte      | H61M-DS2                    | [8bc230f7dc](https://linux-hardware.org/?probe=8bc230f7dc) | Sep 09, 2021 |
| Dell          | 0WMJ54 A01                  | [fb3d977ed2](https://linux-hardware.org/?probe=fb3d977ed2) | Sep 09, 2021 |
| ASUSTek       | P6T DELUXE V2               | [488fd18d85](https://linux-hardware.org/?probe=488fd18d85) | Sep 09, 2021 |
| Dell          | 040DDP A01                  | [19d6905d9a](https://linux-hardware.org/?probe=19d6905d9a) | Sep 09, 2021 |
| Gigabyte      | M61PME-S2P                  | [0baa540bf5](https://linux-hardware.org/?probe=0baa540bf5) | Sep 08, 2021 |
| Foxconn       | nT-A3000 series FAB         | [9e22d6dc70](https://linux-hardware.org/?probe=9e22d6dc70) | Sep 08, 2021 |
| ASUSTek       | P6T DELUXE V2               | [f8aae7ade2](https://linux-hardware.org/?probe=f8aae7ade2) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [a826f2f4c9](https://linux-hardware.org/?probe=a826f2f4c9) | Sep 08, 2021 |
| Gigabyte      | H61M-DS2                    | [5aa6e46608](https://linux-hardware.org/?probe=5aa6e46608) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | [2626e29c5f](https://linux-hardware.org/?probe=2626e29c5f) | Sep 08, 2021 |
| ASUSTek       | Z87-A                       | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [b521805956](https://linux-hardware.org/?probe=b521805956) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [c4f6c7da11](https://linux-hardware.org/?probe=c4f6c7da11) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [a4acb4b4d7](https://linux-hardware.org/?probe=a4acb4b4d7) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | [33ae3adcc6](https://linux-hardware.org/?probe=33ae3adcc6) | Sep 08, 2021 |
| Gigabyte      | H81M-S2V                    | [cb2158566c](https://linux-hardware.org/?probe=cb2158566c) | Sep 08, 2021 |
| Dell          | 0X8DXD A00                  | [65e545345d](https://linux-hardware.org/?probe=65e545345d) | Sep 07, 2021 |
| Gigabyte      | M61PME-S2P                  | [41ab6b2f21](https://linux-hardware.org/?probe=41ab6b2f21) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [5acaf42867](https://linux-hardware.org/?probe=5acaf42867) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [4d6ad821df](https://linux-hardware.org/?probe=4d6ad821df) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [511d2e120b](https://linux-hardware.org/?probe=511d2e120b) | Sep 07, 2021 |
| Gigabyte      | H81M-S2V                    | [13256468d1](https://linux-hardware.org/?probe=13256468d1) | Sep 07, 2021 |
| ASUSTek       | P5Q3                        | [3f08e7bf37](https://linux-hardware.org/?probe=3f08e7bf37) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [bcd1f7553d](https://linux-hardware.org/?probe=bcd1f7553d) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [0c0ccb21d8](https://linux-hardware.org/?probe=0c0ccb21d8) | Sep 07, 2021 |
| ASUSTek       | H81M-C                      | [cf59508b79](https://linux-hardware.org/?probe=cf59508b79) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [1c85c31f57](https://linux-hardware.org/?probe=1c85c31f57) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [6cf8ebc24c](https://linux-hardware.org/?probe=6cf8ebc24c) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [bf328adcb8](https://linux-hardware.org/?probe=bf328adcb8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | [09e28c958c](https://linux-hardware.org/?probe=09e28c958c) | Sep 07, 2021 |
| HP            | 212A                        | [7f51e384f7](https://linux-hardware.org/?probe=7f51e384f7) | Sep 07, 2021 |
| HP            | 212A                        | [c89a2196ab](https://linux-hardware.org/?probe=c89a2196ab) | Sep 07, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [265822ee2e](https://linux-hardware.org/?probe=265822ee2e) | Sep 06, 2021 |
| ASUSTek       | P5Q-PRO                     | [a0d1d9b2e6](https://linux-hardware.org/?probe=a0d1d9b2e6) | Sep 06, 2021 |
| ECS           | H61H2-M13                   | [4aec08beef](https://linux-hardware.org/?probe=4aec08beef) | Sep 06, 2021 |
| Dell          | 0X8DXD A00                  | [28c59930e4](https://linux-hardware.org/?probe=28c59930e4) | Sep 05, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [20f947223f](https://linux-hardware.org/?probe=20f947223f) | Sep 05, 2021 |
| ASUSTek       | PRIME H410M-E               | [af5a140c2e](https://linux-hardware.org/?probe=af5a140c2e) | Sep 04, 2021 |
| ASRock        | TRX40 Creator               | [0734c9bbd0](https://linux-hardware.org/?probe=0734c9bbd0) | Sep 03, 2021 |
| ASRock        | 960GM/U3S3 FX               | [ced0e47579](https://linux-hardware.org/?probe=ced0e47579) | Sep 02, 2021 |
| ECS           | G31T-M9                     | [0757de543d](https://linux-hardware.org/?probe=0757de543d) | Sep 02, 2021 |
| Gigabyte      | 8I945P-G                    | [a1eb33a5f1](https://linux-hardware.org/?probe=a1eb33a5f1) | Sep 02, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d4c78cc3c4](https://linux-hardware.org/?probe=d4c78cc3c4) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ECS           | H61H2-M13                   | [e96ab5fb39](https://linux-hardware.org/?probe=e96ab5fb39) | Sep 01, 2021 |
| MSI           | H110M PRO-VD                | [78fafc3314](https://linux-hardware.org/?probe=78fafc3314) | Sep 01, 2021 |
| Dell          | 0M863N A00                  | [d8083308fc](https://linux-hardware.org/?probe=d8083308fc) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| Intel         | DH77KC AAG39641-400         | [dadb397ef1](https://linux-hardware.org/?probe=dadb397ef1) | Sep 01, 2021 |
| Pegatron      | TRUCKEE                     | [68f16e9542](https://linux-hardware.org/?probe=68f16e9542) | Sep 01, 2021 |
| ASRock        | H61M-VG4                    | [6521e0d6be](https://linux-hardware.org/?probe=6521e0d6be) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [9c31643811](https://linux-hardware.org/?probe=9c31643811) | Aug 31, 2021 |
| ASUSTek       | P7P55D-E                    | [4c05b36e94](https://linux-hardware.org/?probe=4c05b36e94) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [37c3e457bc](https://linux-hardware.org/?probe=37c3e457bc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [0d38048f46](https://linux-hardware.org/?probe=0d38048f46) | Aug 31, 2021 |
| Intel         | DH77KC AAG39641-400         | [d7eaf975a0](https://linux-hardware.org/?probe=d7eaf975a0) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [df9b303eec](https://linux-hardware.org/?probe=df9b303eec) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [d9af23fb86](https://linux-hardware.org/?probe=d9af23fb86) | Aug 31, 2021 |
| AOpen         | D1001 C26361-D1001          | [e27239d870](https://linux-hardware.org/?probe=e27239d870) | Aug 31, 2021 |
| ASUSTek       | B85M-G                      | [1470c8cc7f](https://linux-hardware.org/?probe=1470c8cc7f) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [ba7144c0dc](https://linux-hardware.org/?probe=ba7144c0dc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [7204a77b38](https://linux-hardware.org/?probe=7204a77b38) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [c6a754129a](https://linux-hardware.org/?probe=c6a754129a) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | [a251dca266](https://linux-hardware.org/?probe=a251dca266) | Aug 30, 2021 |
| Intel         | DH67BL AAG10189-206         | [b7b3f489f2](https://linux-hardware.org/?probe=b7b3f489f2) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | [d255f48a39](https://linux-hardware.org/?probe=d255f48a39) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | [dc0abe4fcd](https://linux-hardware.org/?probe=dc0abe4fcd) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | [fc61c24624](https://linux-hardware.org/?probe=fc61c24624) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | [9d1b86643e](https://linux-hardware.org/?probe=9d1b86643e) | Aug 30, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [b9595196ea](https://linux-hardware.org/?probe=b9595196ea) | Aug 28, 2021 |
| Jetway        | 1.0                         | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| MSI           | B150A GAMING PRO            | [06de6cd826](https://linux-hardware.org/?probe=06de6cd826) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [46eacf8d5c](https://linux-hardware.org/?probe=46eacf8d5c) | Aug 27, 2021 |
| Intel         | DN2820FYK H24582-201        | [06f4334a82](https://linux-hardware.org/?probe=06f4334a82) | Aug 27, 2021 |
| ASUSTek       | WS X299 SAGE                | [7f3a68dd2a](https://linux-hardware.org/?probe=7f3a68dd2a) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [2737cfb67d](https://linux-hardware.org/?probe=2737cfb67d) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [dc9428d8b4](https://linux-hardware.org/?probe=dc9428d8b4) | Aug 27, 2021 |
| HP            | 0B0Ch                       | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Dell          | 0WR7PY A00                  | [cb25b1811b](https://linux-hardware.org/?probe=cb25b1811b) | Aug 26, 2021 |
| Dell          | 0X8DXD A00                  | [8dd8862b4b](https://linux-hardware.org/?probe=8dd8862b4b) | Aug 26, 2021 |
| ASRock        | H470M-HVS                   | [d37f13917f](https://linux-hardware.org/?probe=d37f13917f) | Aug 25, 2021 |
| ASRock        | C2750D4I                    | [6daa3c26bf](https://linux-hardware.org/?probe=6daa3c26bf) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0a79171c9e](https://linux-hardware.org/?probe=0a79171c9e) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | [feed9e2921](https://linux-hardware.org/?probe=feed9e2921) | Aug 25, 2021 |
| Biostar       | Hi-Fi A85W                  | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| AAEON         | MF-001 V1.0                 | [b06c4079a7](https://linux-hardware.org/?probe=b06c4079a7) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| ASRock        | H470M-HVS                   | [e5c92fe4ad](https://linux-hardware.org/?probe=e5c92fe4ad) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | [441b8b892e](https://linux-hardware.org/?probe=441b8b892e) | Aug 24, 2021 |
| ASRock        | P4i65G                      | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| ASRock        | H77 Pro4/MVP                | [c2179206a9](https://linux-hardware.org/?probe=c2179206a9) | Aug 24, 2021 |
| Unknown       | 1.0                         | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | [e92004f46a](https://linux-hardware.org/?probe=e92004f46a) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | [06c9a1ed3a](https://linux-hardware.org/?probe=06c9a1ed3a) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | [06234ebe05](https://linux-hardware.org/?probe=06234ebe05) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| HP            | 085Ch                       | [2e649d07a0](https://linux-hardware.org/?probe=2e649d07a0) | Aug 21, 2021 |
| HP            | 085Ch                       | [c5b36c5187](https://linux-hardware.org/?probe=c5b36c5187) | Aug 21, 2021 |
| ASRock        | Z97 Pro3                    | [0f9abf9c63](https://linux-hardware.org/?probe=0f9abf9c63) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| ASUSTek       | P5B SE                      | [81634fcb22](https://linux-hardware.org/?probe=81634fcb22) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| ASRock        | H470M-HVS                   | [cba7d82942](https://linux-hardware.org/?probe=cba7d82942) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | [62068f391f](https://linux-hardware.org/?probe=62068f391f) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | [c980f2d201](https://linux-hardware.org/?probe=c980f2d201) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| Intel         | DG33BU AAD79951-407         | [17c70c7886](https://linux-hardware.org/?probe=17c70c7886) | Aug 19, 2021 |
| HP            | 339A                        | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | [2151b5cdae](https://linux-hardware.org/?probe=2151b5cdae) | Aug 19, 2021 |
| HP            | 1587h                       | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | [0489699bc4](https://linux-hardware.org/?probe=0489699bc4) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | [757e261c56](https://linux-hardware.org/?probe=757e261c56) | Aug 19, 2021 |
| Lenovo        | MAHOBAY                     | [df15656fce](https://linux-hardware.org/?probe=df15656fce) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [1fce0ab0e8](https://linux-hardware.org/?probe=1fce0ab0e8) | Aug 18, 2021 |
| Lenovo        | Board                       | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| ASUSTek       | H81M-R                      | [8598ad2248](https://linux-hardware.org/?probe=8598ad2248) | Aug 18, 2021 |
| ASUSTek       | B150M-K                     | [3f706a2a69](https://linux-hardware.org/?probe=3f706a2a69) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | [9f3381d34c](https://linux-hardware.org/?probe=9f3381d34c) | Aug 18, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [85cfabd795](https://linux-hardware.org/?probe=85cfabd795) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | [765f5d340e](https://linux-hardware.org/?probe=765f5d340e) | Aug 18, 2021 |
| ASRock        | J4205-ITX                   | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| ASUSTek       | A68HM-PLUS                  | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Gigabyte      | Z97N-WIFI                   | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| ECS           | KBN-I                       | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [62faddbfaa](https://linux-hardware.org/?probe=62faddbfaa) | Aug 13, 2021 |
| ASUSTek       | X99-DELUXE                  | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| HP            | 3048h                       | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| HP            | 2AF7                        | [649ed7df8e](https://linux-hardware.org/?probe=649ed7df8e) | Aug 10, 2021 |
| Intel         | DQ45CB AAE30148-207         | [56a573eeed](https://linux-hardware.org/?probe=56a573eeed) | Aug 10, 2021 |
| ASUSTek       | P7H55-M/USB3                | [6f4ad31000](https://linux-hardware.org/?probe=6f4ad31000) | Aug 10, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| ASUSTek       | P7H55-M/USB3                | [7ca1257064](https://linux-hardware.org/?probe=7ca1257064) | Aug 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [fffaf4c700](https://linux-hardware.org/?probe=fffaf4c700) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| ASRock        | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Toshiba       | STI 910090 STIJ             | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Gigabyte      | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| ASRock        | H470M-HVS                   | [545f7195ab](https://linux-hardware.org/?probe=545f7195ab) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | [9ec5eaeaf9](https://linux-hardware.org/?probe=9ec5eaeaf9) | Aug 06, 2021 |
| HP            | 2AF7                        | [1737071720](https://linux-hardware.org/?probe=1737071720) | Aug 06, 2021 |
| HP            | 2AF7                        | [c504247f44](https://linux-hardware.org/?probe=c504247f44) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Lenovo        | Board                       | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Unknown       | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| Gigabyte      | H81M-S2V                    | [10e9ef3d45](https://linux-hardware.org/?probe=10e9ef3d45) | Aug 05, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a70054744](https://linux-hardware.org/?probe=8a70054744) | Aug 04, 2021 |
| Gigabyte      | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | 3047h                       | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte      | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI           | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell          | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS           | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte      | H61M-DS2                    | [21c6bb9dde](https://linux-hardware.org/?probe=21c6bb9dde) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle       | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASRock        | B450M-HDV R4.0              | [72032bc046](https://linux-hardware.org/?probe=72032bc046) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell          | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP            | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP            | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli     | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d3a887bf62](https://linux-hardware.org/?probe=d3a887bf62) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [c3aac7e847](https://linux-hardware.org/?probe=c3aac7e847) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [eeb04ca8d9](https://linux-hardware.org/?probe=eeb04ca8d9) | Jul 22, 2021 |
| Gigabyte      | B450M S2H V2                | [650e0a4954](https://linux-hardware.org/?probe=650e0a4954) | Jul 21, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| Gigabyte      | H61M-DS2                    | [be4679a65b](https://linux-hardware.org/?probe=be4679a65b) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| ASUSTek       | PRIME B450M-K               | [8691cb3cb9](https://linux-hardware.org/?probe=8691cb3cb9) | Jul 12, 2021 |
| Huanan        | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| ASRock        | H470M-HVS                   | [145ca872cf](https://linux-hardware.org/?probe=145ca872cf) | Jul 09, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| ASRock        | H470M-HVS                   | [5ab6c73674](https://linux-hardware.org/?probe=5ab6c73674) | Jul 08, 2021 |
| HP            | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Gigabyte      | H61M-DS2                    | [c80bd2ff96](https://linux-hardware.org/?probe=c80bd2ff96) | Jul 05, 2021 |
| Gigabyte      | B85M-D3H                    | [e8da9b3b84](https://linux-hardware.org/?probe=e8da9b3b84) | Jul 05, 2021 |
| MSI           | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock        | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| ASUSTek       | H81M-PLUS                   | [4ff716ad3a](https://linux-hardware.org/?probe=4ff716ad3a) | Jul 02, 2021 |
| Gigabyte      | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Intel         | DG41RQ AAE54511-205         | [51edb744b9](https://linux-hardware.org/?probe=51edb744b9) | Jun 29, 2021 |
| MSI           | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan        | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte      | H61M-DS2                    | [25956c35fb](https://linux-hardware.org/?probe=25956c35fb) | Jun 24, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | H110M-R                     | [f952173995](https://linux-hardware.org/?probe=f952173995) | Jun 23, 2021 |
| Gigabyte      | B85M-D2V                    | [25f911e59c](https://linux-hardware.org/?probe=25f911e59c) | Jun 23, 2021 |
| Gigabyte      | B360M H                     | [fcddb198ec](https://linux-hardware.org/?probe=fcddb198ec) | Jun 22, 2021 |
| Gigabyte      | B85M-D2V                    | [a719f039de](https://linux-hardware.org/?probe=a719f039de) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [16cf7bfb30](https://linux-hardware.org/?probe=16cf7bfb30) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI           | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Acer          | H11H4-AI V:1.0              | [19fb8aa218](https://linux-hardware.org/?probe=19fb8aa218) | Jun 18, 2021 |
| Acer          | H11H4-AI V:1.0              | [a1f50d7038](https://linux-hardware.org/?probe=a1f50d7038) | Jun 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [1dc449cb66](https://linux-hardware.org/?probe=1dc449cb66) | Jun 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [6511e56d8f](https://linux-hardware.org/?probe=6511e56d8f) | Jun 16, 2021 |
| Gigabyte      | B360M H                     | [44fd3744da](https://linux-hardware.org/?probe=44fd3744da) | Jun 16, 2021 |
| ASUSTek       | P7H55                       | [c8abc22ac7](https://linux-hardware.org/?probe=c8abc22ac7) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | P9X79                       | [dc6ae81a40](https://linux-hardware.org/?probe=dc6ae81a40) | Jun 11, 2021 |
| ASUSTek       | P9X79                       | [359862901e](https://linux-hardware.org/?probe=359862901e) | Jun 11, 2021 |
| QIYIDA        | X99-H9 V2.0                 | [b081ed3973](https://linux-hardware.org/?probe=b081ed3973) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Gigabyte      | H61M-S2PV                   | [50a33d0c01](https://linux-hardware.org/?probe=50a33d0c01) | Jun 09, 2021 |
| ASUSTek       | P5QL-CM                     | [2eb12a165a](https://linux-hardware.org/?probe=2eb12a165a) | Jun 09, 2021 |
| ASRock        | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Gigabyte      | P43-ES3G                    | [86c3abf0e6](https://linux-hardware.org/?probe=86c3abf0e6) | Jun 07, 2021 |
| ASUSTek       | B85M-G                      | [15fdd98402](https://linux-hardware.org/?probe=15fdd98402) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock        | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek       | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Gigabyte      | H61M-DS2                    | [f543bd7919](https://linux-hardware.org/?probe=f543bd7919) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| Intel         | DP965LT AAD41694-209        | [64b76f3b3d](https://linux-hardware.org/?probe=64b76f3b3d) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | [446457dc79](https://linux-hardware.org/?probe=446457dc79) | Jun 01, 2021 |
| ASUSTek       | P5QL-CM                     | [53e36afc53](https://linux-hardware.org/?probe=53e36afc53) | Jun 01, 2021 |
| Intel         | DG965RY AAD41691-206        | [1b04d7a76f](https://linux-hardware.org/?probe=1b04d7a76f) | Jun 01, 2021 |
| Medion        | MS-7616                     | [c3730db7dd](https://linux-hardware.org/?probe=c3730db7dd) | May 31, 2021 |
| ASUSTek       | P7H55                       | [ac572ef424](https://linux-hardware.org/?probe=ac572ef424) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| Gigabyte      | H81M-S2V                    | [e00920532d](https://linux-hardware.org/?probe=e00920532d) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Gigabyte      | H81M-S1                     | [07fcf530f1](https://linux-hardware.org/?probe=07fcf530f1) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| ASRock        | A320M-HDV R3.0              | [8947349c20](https://linux-hardware.org/?probe=8947349c20) | May 21, 2021 |
| Gigabyte      | H81M-S2V                    | [95f4bad7b5](https://linux-hardware.org/?probe=95f4bad7b5) | May 20, 2021 |
| Gigabyte      | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| ASRock        | H61M-VG4                    | [f2d7c64e1c](https://linux-hardware.org/?probe=f2d7c64e1c) | May 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [b471b7cf95](https://linux-hardware.org/?probe=b471b7cf95) | May 18, 2021 |
| ASRock        | H61M-VG4                    | [1699c8eab5](https://linux-hardware.org/?probe=1699c8eab5) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [bd2a3417a0](https://linux-hardware.org/?probe=bd2a3417a0) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [3a27d20178](https://linux-hardware.org/?probe=3a27d20178) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [17ff2add7a](https://linux-hardware.org/?probe=17ff2add7a) | May 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | [07ea2a4b8e](https://linux-hardware.org/?probe=07ea2a4b8e) | May 14, 2021 |
| ASRock        | H61M-VG4                    | [823bbbb4ed](https://linux-hardware.org/?probe=823bbbb4ed) | May 12, 2021 |
| ASRock        | G31M-VS2                    | [af6e17ac8c](https://linux-hardware.org/?probe=af6e17ac8c) | May 12, 2021 |
| ASRock        | B450M Pro4-F                | [f6d2299c81](https://linux-hardware.org/?probe=f6d2299c81) | May 12, 2021 |
| Gigabyte      | H61M-DS2                    | [380bf2eacc](https://linux-hardware.org/?probe=380bf2eacc) | May 11, 2021 |
| Gigabyte      | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Gigabyte      | H81M-DS2                    | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | [0c87980ed4](https://linux-hardware.org/?probe=0c87980ed4) | Apr 29, 2021 |
| Pegatron      | C15B                        | [54d1d5cde0](https://linux-hardware.org/?probe=54d1d5cde0) | Apr 27, 2021 |
| Biostar       | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASRock        | 970M Pro3                   | [89d9898d88](https://linux-hardware.org/?probe=89d9898d88) | Apr 26, 2021 |
| HP            | 3399                        | [4085344b20](https://linux-hardware.org/?probe=4085344b20) | Apr 26, 2021 |
| ASUSTek       | P8Z77-M                     | [8495ecf36e](https://linux-hardware.org/?probe=8495ecf36e) | Apr 26, 2021 |
| ASUSTek       | PRIME A320M-K               | [1c397e42c6](https://linux-hardware.org/?probe=1c397e42c6) | Apr 23, 2021 |
| ASUSTek       | PRIME B450M-K               | [fc24c1c56f](https://linux-hardware.org/?probe=fc24c1c56f) | Apr 23, 2021 |
| HP            | 3399                        | [a265b73c37](https://linux-hardware.org/?probe=a265b73c37) | Apr 22, 2021 |
| Gigabyte      | H410M S2H                   | [88f270d1d0](https://linux-hardware.org/?probe=88f270d1d0) | Apr 22, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6cdd8afad1](https://linux-hardware.org/?probe=6cdd8afad1) | Apr 19, 2021 |
| ECS           | G31T-M7                     | [4e1e8d1c1a](https://linux-hardware.org/?probe=4e1e8d1c1a) | Apr 19, 2021 |
| ECS           | G31T-M7                     | [2ffcd0d78d](https://linux-hardware.org/?probe=2ffcd0d78d) | Apr 19, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| HP            | 3399                        | [ae0ed46819](https://linux-hardware.org/?probe=ae0ed46819) | Apr 16, 2021 |
| MSI           | G41M-P28                    | [0b714b1814](https://linux-hardware.org/?probe=0b714b1814) | Apr 16, 2021 |
| Intel         | DQ45CB AAE30148-206         | [6a9f891230](https://linux-hardware.org/?probe=6a9f891230) | Apr 15, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [7a1d829bbb](https://linux-hardware.org/?probe=7a1d829bbb) | Apr 14, 2021 |
| Gigabyte      | H81M-S2V                    | [97a320e9df](https://linux-hardware.org/?probe=97a320e9df) | Apr 14, 2021 |
| MSI           | H110M PRO-D                 | [9f79d5f548](https://linux-hardware.org/?probe=9f79d5f548) | Apr 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [2f2f027581](https://linux-hardware.org/?probe=2f2f027581) | Apr 07, 2021 |
| ASUSTek       | P5B                         | [e6f18312ca](https://linux-hardware.org/?probe=e6f18312ca) | Apr 07, 2021 |
| Gigabyte      | G41M-ES2L                   | [1ae4d948e8](https://linux-hardware.org/?probe=1ae4d948e8) | Apr 06, 2021 |
| ECS           | G31T-M9                     | [769cb653f7](https://linux-hardware.org/?probe=769cb653f7) | Apr 02, 2021 |
| MSI           | H110M PRO-VD                | [6ba14141a6](https://linux-hardware.org/?probe=6ba14141a6) | Apr 01, 2021 |
| MSI           | H110M PRO-VD                | [f2e276c03d](https://linux-hardware.org/?probe=f2e276c03d) | Apr 01, 2021 |
| Intel         | DG33FB AAD81072-303         | [df4527f66c](https://linux-hardware.org/?probe=df4527f66c) | Mar 31, 2021 |
| ASUSTek       | P5K-VM                      | [4c297474dc](https://linux-hardware.org/?probe=4c297474dc) | Mar 30, 2021 |
| ASUSTek       | Z87I-DELUXE                 | [34a8087893](https://linux-hardware.org/?probe=34a8087893) | Mar 22, 2021 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [3876e9ed84](https://linux-hardware.org/?probe=3876e9ed84) | Mar 21, 2021 |
| ASUSTek       | H81M-K                      | [be20eafb4f](https://linux-hardware.org/?probe=be20eafb4f) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | [0dd442a763](https://linux-hardware.org/?probe=0dd442a763) | Mar 19, 2021 |
| HPE           | ProLiant MicroServer Gen... | [2f3f591fd0](https://linux-hardware.org/?probe=2f3f591fd0) | Mar 10, 2021 |
| Intel         | DG31PR AAD97573-301         | [09e15a8c00](https://linux-hardware.org/?probe=09e15a8c00) | Mar 04, 2021 |
| MSI           | MS-7329                     | [d67a4df7d0](https://linux-hardware.org/?probe=d67a4df7d0) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| Dell          | 0KWVT8 A02                  | [4bff426962](https://linux-hardware.org/?probe=4bff426962) | Jan 31, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [5d23694899](https://linux-hardware.org/?probe=5d23694899) | Jan 24, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [04b6596686](https://linux-hardware.org/?probe=04b6596686) | Jan 13, 2021 |
| Dell          | 0K83V0 A00                  | [54858a0cb0](https://linux-hardware.org/?probe=54858a0cb0) | Jan 06, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [8d9dbecbba](https://linux-hardware.org/?probe=8d9dbecbba) | Aug 11, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 225      | 40.69%  |
| 5.10.0-7-amd64                 | 155      | 28.03%  |
| 5.10.0-2-amd64                 | 77       | 13.92%  |
| 5.10.0-9-amd64                 | 27       | 4.88%   |
| 5.10.0-6-amd64                 | 13       | 2.35%   |
| 5.11.22-4-pve                  | 6        | 1.08%   |
| 5.10.0-8-686-pae               | 4        | 0.72%   |
| 5.10.0-4-amd64                 | 4        | 0.72%   |
| 5.11.22-1-pve                  | 3        | 0.54%   |
| 5.11.22-5-pve                  | 2        | 0.36%   |
| 5.11.22-2-pve                  | 2        | 0.36%   |
| 5.10.0-9-686                   | 2        | 0.36%   |
| 5.10.0-8-rt-amd64              | 2        | 0.36%   |
| 5.10.0-8-686                   | 2        | 0.36%   |
| 5.10.0-5-amd64                 | 2        | 0.36%   |
| 5.10.0-3-amd64                 | 2        | 0.36%   |
| 5.8.0-3-amd64                  | 1        | 0.18%   |
| 5.4.148                        | 1        | 0.18%   |
| 5.15.0-rc5-recomp              | 1        | 0.18%   |
| 5.14.0-trunk-amd64             | 1        | 0.18%   |
| 5.14.0-2-amd64                 | 1        | 0.18%   |
| 5.13.8-gnu                     | 1        | 0.18%   |
| 5.13.4                         | 1        | 0.18%   |
| 5.13.1a                        | 1        | 0.18%   |
| 5.13.13-arch1-1                | 1        | 0.18%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.18%   |
| 5.13.0-13.1-liquorix-amd64     | 1        | 0.18%   |
| 5.13.0-12.1-liquorix-amd64     | 1        | 0.18%   |
| 5.12.18-amd64-desktop          | 1        | 0.18%   |
| 5.11.22-3-pve                  | 1        | 0.18%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.18%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.18%   |
| 5.10.65-gnu1                   | 1        | 0.18%   |
| 5.10.46custom                  | 1        | 0.18%   |
| 5.10.42+truenas                | 1        | 0.18%   |
| 5.10.38-falcot                 | 1        | 0.18%   |
| 5.10.10                        | 1        | 0.18%   |
| 5.10.0-7-686-pae               | 1        | 0.18%   |
| 5.10.0-1-amd64                 | 1        | 0.18%   |
| 5.1.0-20.1-liquorix-amd64      | 1        | 0.18%   |
| 4.19.0-9-686-pae               | 1        | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 503      | 93.32%  |
| 5.11.22 | 14       | 2.6%    |
| 5.13.0  | 3        | 0.56%   |
| 5.14.0  | 2        | 0.37%   |
| 5.11.0  | 2        | 0.37%   |
| 5.8.0   | 1        | 0.19%   |
| 5.4.148 | 1        | 0.19%   |
| 5.15.0  | 1        | 0.19%   |
| 5.13.8  | 1        | 0.19%   |
| 5.13.4  | 1        | 0.19%   |
| 5.13.13 | 1        | 0.19%   |
| 5.13.1  | 1        | 0.19%   |
| 5.12.18 | 1        | 0.19%   |
| 5.10.65 | 1        | 0.19%   |
| 5.10.46 | 1        | 0.19%   |
| 5.10.42 | 1        | 0.19%   |
| 5.10.38 | 1        | 0.19%   |
| 5.10.10 | 1        | 0.19%   |
| 5.1.0   | 1        | 0.19%   |
| 4.19.0  | 1        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 508      | 94.25%  |
| 5.11    | 16       | 2.97%   |
| 5.13    | 7        | 1.3%    |
| 5.14    | 2        | 0.37%   |
| 5.8     | 1        | 0.19%   |
| 5.4     | 1        | 0.19%   |
| 5.15    | 1        | 0.19%   |
| 5.12    | 1        | 0.19%   |
| 5.1     | 1        | 0.19%   |
| 4.19    | 1        | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 528      | 97.96%  |
| i686   | 11       | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 233      | 42.83%  |
| GNOME            | 96       | 17.65%  |
| KDE5             | 56       | 10.29%  |
| XFCE             | 50       | 9.19%   |
| MATE             | 24       | 4.41%   |
| Cinnamon         | 14       | 2.57%   |
| X-Cinnamon       | 13       | 2.39%   |
| LXDE             | 12       | 2.21%   |
| KDE              | 9        | 1.65%   |
| i3               | 9        | 1.65%   |
| Trinity          | 7        | 1.29%   |
| LXQt             | 7        | 1.29%   |
| lightdm-xsession | 3        | 0.55%   |
| Budgie           | 3        | 0.55%   |
| openbox          | 2        | 0.37%   |
| GNOME Flashback  | 2        | 0.37%   |
| awesome          | 2        | 0.37%   |
| sway             | 1        | 0.18%   |
| GNUstep          | 1        | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 250      | 46.21%  |
| Unknown | 194      | 35.86%  |
| Wayland | 51       | 9.43%   |
| Tty     | 46       | 8.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 287      | 53.15%  |
| TDM     | 71       | 13.15%  |
| GDM     | 71       | 13.15%  |
| SDDM    | 54       | 10%     |
| LightDM | 49       | 9.07%   |
| SLiM    | 3        | 0.56%   |
| NODM    | 2        | 0.37%   |
| GDM3    | 2        | 0.37%   |
| XDM     | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 201      | 37.29%  |
| en_US   | 161      | 29.87%  |
| fr_FR   | 21       | 3.9%    |
| en_GB   | 21       | 3.9%    |
| es_ES   | 18       | 3.34%   |
| pt_BR   | 16       | 2.97%   |
| Unknown | 15       | 2.78%   |
| de_DE   | 13       | 2.41%   |
| en_AU   | 9        | 1.67%   |
| pl_PL   | 5        | 0.93%   |
| nl_BE   | 5        | 0.93%   |
| en_CA   | 5        | 0.93%   |
| C       | 5        | 0.93%   |
| it_IT   | 4        | 0.74%   |
| ja_JP   | 3        | 0.56%   |
| hu_HU   | 3        | 0.56%   |
| es_AR   | 3        | 0.56%   |
| uk_UA   | 2        | 0.37%   |
| sv_SE   | 2        | 0.37%   |
| pt_PT   | 2        | 0.37%   |
| es_MX   | 2        | 0.37%   |
| en_IE   | 2        | 0.37%   |
| de_CH   | 2        | 0.37%   |
| de_AT   | 2        | 0.37%   |
| tr_TR   | 1        | 0.19%   |
| sr_RS   | 1        | 0.19%   |
| ru_UA   | 1        | 0.19%   |
| ro_RO   | 1        | 0.19%   |
| nl_NL   | 1        | 0.19%   |
| hr_HR   | 1        | 0.19%   |
| fr_CH   | 1        | 0.19%   |
| es_VE   | 1        | 0.19%   |
| es_US   | 1        | 0.19%   |
| es_CO   | 1        | 0.19%   |
| en_PH   | 1        | 0.19%   |
| en_NZ   | 1        | 0.19%   |
| en_IN   | 1        | 0.19%   |
| en_HK   | 1        | 0.19%   |
| cs_CZ   | 1        | 0.19%   |
| ca_ES   | 1        | 0.19%   |
| bg_BG   | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 361      | 66.36%  |
| EFI  | 183      | 33.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 278      | 51.58%  |
| Overlay | 207      | 38.4%   |
| Btrfs   | 28       | 5.19%   |
| Zfs     | 10       | 1.86%   |
| Xfs     | 7        | 1.3%    |
| Ext3    | 6        | 1.11%   |
| Rootfs  | 1        | 0.19%   |
| Ext2    | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 254      | 46.69%  |
| GPT     | 228      | 41.91%  |
| Unknown | 62       | 11.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 457      | 84.63%  |
| Yes       | 83       | 15.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 274      | 50.65%  |
| No        | 267      | 49.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 163      | 30.24%  |
| Gigabyte Technology | 87       | 16.14%  |
| ASRock              | 79       | 14.66%  |
| MSI                 | 45       | 8.35%   |
| Dell                | 34       | 6.31%   |
| Hewlett-Packard     | 30       | 5.57%   |
| Intel               | 21       | 3.9%    |
| ECS                 | 20       | 3.71%   |
| Lenovo              | 10       | 1.86%   |
| Foxconn             | 7        | 1.3%    |
| Pegatron            | 5        | 0.93%   |
| Fujitsu             | 5        | 0.93%   |
| Acer                | 4        | 0.74%   |
| Unknown             | 3        | 0.56%   |
| Supermicro          | 2        | 0.37%   |
| Semp Toshiba        | 2        | 0.37%   |
| Huanan              | 2        | 0.37%   |
| Fujitsu Siemens     | 2        | 0.37%   |
| Biostar             | 2        | 0.37%   |
| ASRockRack          | 2        | 0.37%   |
| Sun Microsystems    | 1        | 0.19%   |
| Shuttle             | 1        | 0.19%   |
| QIYIDA              | 1        | 0.19%   |
| Protectli           | 1        | 0.19%   |
| Positivo            | 1        | 0.19%   |
| Medion              | 1        | 0.19%   |
| Libretrend          | 1        | 0.19%   |
| Jetway              | 1        | 0.19%   |
| HPE                 | 1        | 0.19%   |
| HARDKERNEL          | 1        | 0.19%   |
| Digiboard           | 1        | 0.19%   |
| AOpen               | 1        | 0.19%   |
| American Megatrends | 1        | 0.19%   |
| AAEON               | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 34       | 6.31%   |
| ASRock H470M-HVS                 | 20       | 3.71%   |
| ECS H61H2-M13                    | 13       | 2.41%   |
| ASUS P8H67-M                     | 7        | 1.3%    |
| ASUS P8H61-M LX3 PLUS R2.0       | 7        | 1.3%    |
| Gigabyte H81M-S2V                | 6        | 1.11%   |
| ASRock H61M-VG4                  | 6        | 1.11%   |
| ASUS PRIME A320M-K               | 5        | 0.93%   |
| MSI MS-7721                      | 4        | 0.74%   |
| Gigabyte H61M-DS2 REV 1.2        | 4        | 0.74%   |
| ECS G31T-M9                      | 4        | 0.74%   |
| Dell OptiPlex 7010               | 4        | 0.74%   |
| ASUS P8H61-M LX3 R2.0            | 4        | 0.74%   |
| MSI MS-7996                      | 3        | 0.56%   |
| MSI MS-7817                      | 3        | 0.56%   |
| Intel Pro, Std, Elt Series       | 3        | 0.56%   |
| Intel DN2820FYK H24582-201       | 3        | 0.56%   |
| Gigabyte Z77-D3H                 | 3        | 0.56%   |
| Gigabyte B550I AORUS PRO AX      | 3        | 0.56%   |
| Gigabyte A320M-S2H               | 3        | 0.56%   |
| Fujitsu ESPRIMO P720             | 3        | 0.56%   |
| Foxconn H61MXL/H61MXL-K          | 3        | 0.56%   |
| Dell OptiPlex 3020               | 3        | 0.56%   |
| ASUS PRIME B450M-K               | 3        | 0.56%   |
| ASUS PRIME B450M-A               | 3        | 0.56%   |
| ASUS H110M-R                     | 3        | 0.56%   |
| ASRock G31M-VS2                  | 3        | 0.56%   |
| ASRock B450M Pro4                | 3        | 0.56%   |
| Unknown                          | 3        | 0.56%   |
| Semp Toshiba STI                 | 2        | 0.37%   |
| MSI MS-7C75                      | 2        | 0.37%   |
| MSI MS-7C56                      | 2        | 0.37%   |
| MSI MS-7C35                      | 2        | 0.37%   |
| MSI MS-7A71                      | 2        | 0.37%   |
| MSI MS-7A70                      | 2        | 0.37%   |
| HP Z620 Workstation              | 2        | 0.37%   |
| HP EliteDesk 700 G1 SFF          | 2        | 0.37%   |
| HP Compaq 6005 Pro MT PC         | 2        | 0.37%   |
| Gigabyte Z370 AORUS Gaming 5     | 2        | 0.37%   |
| Gigabyte X570 I AORUS PRO WIFI   | 2        | 0.37%   |
| Gigabyte H61M-S2PV               | 2        | 0.37%   |
| Gigabyte H61M-DS2                | 2        | 0.37%   |
| Gigabyte B450M DS3H              | 2        | 0.37%   |
| Gigabyte B360M H                 | 2        | 0.37%   |
| Gigabyte AB350M-DS3H V2          | 2        | 0.37%   |
| Gigabyte 970A-DS3P               | 2        | 0.37%   |
| Dell Precision WorkStation T7500 | 2        | 0.37%   |
| Dell OptiPlex 760                | 2        | 0.37%   |
| Dell Inspiron 560                | 2        | 0.37%   |
| ASUS TUF GAMING X570-PRO         | 2        | 0.37%   |
| ASUS ROG STRIX B450-F GAMING     | 2        | 0.37%   |
| ASUS Pro WS X570-ACE             | 2        | 0.37%   |
| ASUS PRIME X470-PRO              | 2        | 0.37%   |
| ASUS PRIME B550-PLUS             | 2        | 0.37%   |
| ASUS P6T DELUXE V2               | 2        | 0.37%   |
| ASUS P5QL-CM                     | 2        | 0.37%   |
| ASUS P5Q-EM                      | 2        | 0.37%   |
| ASUS P5KPL-CM                    | 2        | 0.37%   |
| ASRock X399 Taichi               | 2        | 0.37%   |
| ASRock B550M Pro4                | 2        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS All             | 34       | 6.31%   |
| ASUS PRIME           | 31       | 5.75%   |
| ASRock H470M-HVS     | 20       | 3.71%   |
| Dell OptiPlex        | 19       | 3.53%   |
| ECS H61H2-M13        | 13       | 2.41%   |
| ASUS P8H61-M         | 13       | 2.41%   |
| ASUS ROG             | 12       | 2.23%   |
| Dell Precision       | 9        | 1.67%   |
| HP Compaq            | 8        | 1.48%   |
| ASUS TUF             | 8        | 1.48%   |
| ASUS P8H67-M         | 7        | 1.3%    |
| Lenovo ThinkCentre   | 6        | 1.11%   |
| HP EliteDesk         | 6        | 1.11%   |
| Gigabyte H81M-S2V    | 6        | 1.11%   |
| Gigabyte H61M-DS2    | 6        | 1.11%   |
| ASRock H61M-VG4      | 6        | 1.11%   |
| Dell Inspiron        | 5        | 0.93%   |
| MSI MS-7721          | 4        | 0.74%   |
| Gigabyte A320M-S2H   | 4        | 0.74%   |
| Fujitsu ESPRIMO      | 4        | 0.74%   |
| ECS G31T-M9          | 4        | 0.74%   |
| ASUS Pro             | 4        | 0.74%   |
| ASRock B450M         | 4        | 0.74%   |
| MSI MS-7996          | 3        | 0.56%   |
| MSI MS-7817          | 3        | 0.56%   |
| Intel Pro            | 3        | 0.56%   |
| Intel DN2820FYK      | 3        | 0.56%   |
| Gigabyte Z77-D3H     | 3        | 0.56%   |
| Gigabyte B550I       | 3        | 0.56%   |
| Gigabyte B450M       | 3        | 0.56%   |
| Gigabyte B450        | 3        | 0.56%   |
| Foxconn H61MXL       | 3        | 0.56%   |
| ASUS H110M-R         | 3        | 0.56%   |
| ASRock Z97           | 3        | 0.56%   |
| ASRock G31M-VS2      | 3        | 0.56%   |
| Unknown              | 3        | 0.56%   |
| Semp Toshiba STI     | 2        | 0.37%   |
| MSI MS-7C75          | 2        | 0.37%   |
| MSI MS-7C56          | 2        | 0.37%   |
| MSI MS-7C35          | 2        | 0.37%   |
| MSI MS-7A71          | 2        | 0.37%   |
| MSI MS-7A70          | 2        | 0.37%   |
| Intel DH67CL         | 2        | 0.37%   |
| HP Z620              | 2        | 0.37%   |
| HP ProLiant          | 2        | 0.37%   |
| Gigabyte Z370        | 2        | 0.37%   |
| Gigabyte X570        | 2        | 0.37%   |
| Gigabyte H61M-S2PV   | 2        | 0.37%   |
| Gigabyte B360M       | 2        | 0.37%   |
| Gigabyte AB350M-DS3H | 2        | 0.37%   |
| Gigabyte 970A-DS3P   | 2        | 0.37%   |
| ASUS P7H55-M         | 2        | 0.37%   |
| ASUS P6T             | 2        | 0.37%   |
| ASUS P5QL-CM         | 2        | 0.37%   |
| ASUS P5Q-EM          | 2        | 0.37%   |
| ASUS P5KPL-CM        | 2        | 0.37%   |
| ASUS P5B             | 2        | 0.37%   |
| ASUS M5A78L-M        | 2        | 0.37%   |
| ASRock X570          | 2        | 0.37%   |
| ASRock X399          | 2        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 61       | 11.32%  |
| 2020 | 59       | 10.95%  |
| 2014 | 54       | 10.02%  |
| 2018 | 52       | 9.65%   |
| 2019 | 50       | 9.28%   |
| 2011 | 41       | 7.61%   |
| 2012 | 38       | 7.05%   |
| 2015 | 33       | 6.12%   |
| 2010 | 33       | 6.12%   |
| 2013 | 31       | 5.75%   |
| 2009 | 28       | 5.19%   |
| 2016 | 23       | 4.27%   |
| 2008 | 12       | 2.23%   |
| 2017 | 11       | 2.04%   |
| 2007 | 6        | 1.11%   |
| 2006 | 4        | 0.74%   |
| 2005 | 1        | 0.19%   |
| 2004 | 1        | 0.19%   |
| 2001 | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 539      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 532      | 98.7%   |
| Enabled  | 7        | 1.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 537      | 99.63%  |
| Yes  | 2        | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 107      | 19.81%  |
| 8.01-16.0       | 97       | 17.96%  |
| 3.01-4.0        | 91       | 16.85%  |
| 4.01-8.0        | 83       | 15.37%  |
| 32.01-64.0      | 76       | 14.07%  |
| 64.01-256.0     | 34       | 6.3%    |
| 1.01-2.0        | 31       | 5.74%   |
| 2.01-3.0        | 9        | 1.67%   |
| 24.01-32.0      | 6        | 1.11%   |
| More than 256.0 | 3        | 0.56%   |
| 0.51-1.0        | 2        | 0.37%   |
| 0.01-0.5        | 1        | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 208      | 38.1%   |
| 1.01-2.0    | 81       | 14.84%  |
| 2.01-3.0    | 66       | 12.09%  |
| 4.01-8.0    | 62       | 11.36%  |
| 3.01-4.0    | 58       | 10.62%  |
| 8.01-16.0   | 25       | 4.58%   |
| 0.01-0.5    | 21       | 3.85%   |
| 16.01-24.0  | 12       | 2.2%    |
| 24.01-32.0  | 7        | 1.28%   |
| 32.01-64.0  | 4        | 0.73%   |
| 64.01-256.0 | 2        | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 273      | 50.56%  |
| 2      | 123      | 22.78%  |
| 3      | 56       | 10.37%  |
| 4      | 39       | 7.22%   |
| 5      | 19       | 3.52%   |
| 8      | 7        | 1.3%    |
| 6      | 7        | 1.3%    |
| 7      | 5        | 0.93%   |
| 9      | 3        | 0.56%   |
| 0      | 3        | 0.56%   |
| 13     | 2        | 0.37%   |
| 10     | 2        | 0.37%   |
| 12     | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 344      | 63.7%   |
| Yes       | 196      | 36.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 535      | 99.26%  |
| No        | 4        | 0.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 412      | 76.44%  |
| Yes       | 127      | 23.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 430      | 79.78%  |
| Yes       | 109      | 20.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| Russia                 | 204      | 37.78%  |
| USA                    | 83       | 15.37%  |
| France                 | 26       | 4.81%   |
| Germany                | 24       | 4.44%   |
| Spain                  | 23       | 4.26%   |
| UK                     | 19       | 3.52%   |
| Brazil                 | 17       | 3.15%   |
| Ukraine                | 14       | 2.59%   |
| Australia              | 11       | 2.04%   |
| Poland                 | 9        | 1.67%   |
| Belgium                | 9        | 1.67%   |
| Italy                  | 7        | 1.3%    |
| Sweden                 | 6        | 1.11%   |
| Canada                 | 6        | 1.11%   |
| Portugal               | 5        | 0.93%   |
| Mexico                 | 5        | 0.93%   |
| Hungary                | 5        | 0.93%   |
| Austria                | 5        | 0.93%   |
| Argentina              | 5        | 0.93%   |
| Switzerland            | 4        | 0.74%   |
| Netherlands            | 4        | 0.74%   |
| Bulgaria               | 4        | 0.74%   |
| Norway                 | 3        | 0.56%   |
| Japan                  | 3        | 0.56%   |
| Czechia                | 3        | 0.56%   |
| Venezuela              | 2        | 0.37%   |
| Turkey                 | 2        | 0.37%   |
| Singapore              | 2        | 0.37%   |
| Romania                | 2        | 0.37%   |
| Pakistan               | 2        | 0.37%   |
| Morocco                | 2        | 0.37%   |
| Finland                | 2        | 0.37%   |
| Taiwan                 | 1        | 0.19%   |
| Syria                  | 1        | 0.19%   |
| Serbia                 | 1        | 0.19%   |
| New Zealand            | 1        | 0.19%   |
| New Caledonia          | 1        | 0.19%   |
| Madagascar             | 1        | 0.19%   |
| Latvia                 | 1        | 0.19%   |
| Kazakhstan             | 1        | 0.19%   |
| Jamaica                | 1        | 0.19%   |
| Ireland                | 1        | 0.19%   |
| Iran                   | 1        | 0.19%   |
| India                  | 1        | 0.19%   |
| Hong Kong              | 1        | 0.19%   |
| Greece                 | 1        | 0.19%   |
| Ecuador                | 1        | 0.19%   |
| Croatia                | 1        | 0.19%   |
| Costa Rica             | 1        | 0.19%   |
| Colombia               | 1        | 0.19%   |
| China                  | 1        | 0.19%   |
| Bosnia and Herzegovina | 1        | 0.19%   |
| Bolivia                | 1        | 0.19%   |
| Bangladesh             | 1        | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Voronezh      | 175      | 32.11%  |
| Portland      | 9        | 1.65%   |
| Ocala         | 6        | 1.1%    |
| M??laga       | 6        | 1.1%    |
| Lyon          | 6        | 1.1%    |
| London        | 6        | 1.1%    |
| Kyiv          | 6        | 1.1%    |
| St Petersburg | 5        | 0.92%   |
| Vienna        | 4        | 0.73%   |
| Sofia         | 4        | 0.73%   |
| S??o Paulo    | 4        | 0.73%   |
| Moscow        | 4        | 0.73%   |
| Stockholm     | 3        | 0.55%   |
| Paris         | 3        | 0.55%   |
| Melbourne     | 3        | 0.55%   |
| Las Vegas     | 3        | 0.55%   |
| Kalamazoo     | 3        | 0.55%   |
| Frankfort     | 3        | 0.55%   |
| Ensenada      | 3        | 0.55%   |
| Berlin        | 3        | 0.55%   |
| Yarraville    | 2        | 0.37%   |
| Warsaw        | 2        | 0.37%   |
| Valencia      | 2        | 0.37%   |
| Seville       | 2        | 0.37%   |
| Saint-Denis   | 2        | 0.37%   |
| Perm          | 2        | 0.37%   |
| New York      | 2        | 0.37%   |
| New Orleans   | 2        | 0.37%   |
| Lisbon        | 2        | 0.37%   |
| Kharkiv       | 2        | 0.37%   |
| Kamoke        | 2        | 0.37%   |
| Iasi          | 2        | 0.37%   |
| Herndon       | 2        | 0.37%   |
| Dallas        | 2        | 0.37%   |
| Clitheroe     | 2        | 0.37%   |
| Canc??n       | 2        | 0.37%   |
| Barueri       | 2        | 0.37%   |
| Barcelona     | 2        | 0.37%   |
| Athens        | 2        | 0.37%   |
| Antwerp       | 2        | 0.37%   |
| Amsterdam     | 2        | 0.37%   |
| Érd          | 1        | 0.18%   |
| Zibo          | 1        | 0.18%   |
| Zastavka      | 1        | 0.18%   |
| Zaporizhzhya  | 1        | 0.18%   |
| Zagreb        | 1        | 0.18%   |
| Yuncos        | 1        | 0.18%   |
| Yssingeaux    | 1        | 0.18%   |
| Ypres         | 1        | 0.18%   |
| York          | 1        | 0.18%   |
| Yekaterinburg | 1        | 0.18%   |
| Wroclaw       | 1        | 0.18%   |
| Woolloongabba | 1        | 0.18%   |
| Woodstock     | 1        | 0.18%   |
| Williston     | 1        | 0.18%   |
| West Islip    | 1        | 0.18%   |
| Wenatchee     | 1        | 0.18%   |
| Warminster    | 1        | 0.18%   |
| Waregem       | 1        | 0.18%   |
| Vologda       | 1        | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 179      | 265    | 20.27%  |
| WDC                 | 160      | 236    | 18.12%  |
| Samsung Electronics | 129      | 184    | 14.61%  |
| Toshiba             | 70       | 109    | 7.93%   |
| Kingston            | 59       | 70     | 6.68%   |
| Crucial             | 47       | 53     | 5.32%   |
| Hitachi             | 39       | 42     | 4.42%   |
| SanDisk             | 24       | 29     | 2.72%   |
| Netac               | 20       | 24     | 2.27%   |
| Intel               | 19       | 26     | 2.15%   |
| HGST                | 14       | 19     | 1.59%   |
| A-DATA Technology   | 10       | 13     | 1.13%   |
| PNY                 | 8        | 8      | 0.91%   |
| China               | 8        | 8      | 0.91%   |
| SPCC                | 7        | 7      | 0.79%   |
| MAXTOR              | 6        | 6      | 0.68%   |
| Unknown             | 5        | 5      | 0.57%   |
| OCZ                 | 5        | 5      | 0.57%   |
| Hewlett-Packard     | 5        | 9      | 0.57%   |
| Phison              | 4        | 4      | 0.45%   |
| Patriot             | 4        | 4      | 0.45%   |
| Gigabyte Technology | 4        | 5      | 0.45%   |
| Corsair             | 4        | 5      | 0.45%   |
| XPG                 | 3        | 4      | 0.34%   |
| Transcend           | 3        | 4      | 0.34%   |
| Mushkin             | 3        | 3      | 0.34%   |
| Team                | 2        | 2      | 0.23%   |
| Silicon Motion      | 2        | 2      | 0.23%   |
| SABRENT             | 2        | 2      | 0.23%   |
| PLEXTOR             | 2        | 4      | 0.23%   |
| Phison Electronics  | 2        | 2      | 0.23%   |
| Micron Technology   | 2        | 2      | 0.23%   |
| LITEON              | 2        | 2      | 0.23%   |
| Intenso             | 2        | 4      | 0.23%   |
| Hajaan              | 2        | 2      | 0.23%   |
| Xinhaike            | 1        | 1      | 0.11%   |
| T-FORCE             | 1        | 1      | 0.11%   |
| SK Hynix            | 1        | 6      | 0.11%   |
| QGeeM               | 1        | 1      | 0.11%   |
| PNY USB             | 1        | 1      | 0.11%   |
| Pioneer             | 1        | 1      | 0.11%   |
| NAS                 | 1        | 5      | 0.11%   |
| MaxDigital          | 1        | 2      | 0.11%   |
| MARSHAL             | 1        | 1      | 0.11%   |
| Lexar               | 1        | 1      | 0.11%   |
| Lenovo              | 1        | 1      | 0.11%   |
| LaCie               | 1        | 1      | 0.11%   |
| KLEVV               | 1        | 1      | 0.11%   |
| KingDian            | 1        | 1      | 0.11%   |
| KING                | 1        | 1      | 0.11%   |
| JMicron             | 1        | 1      | 0.11%   |
| JAMESDONKEY         | 1        | 1      | 0.11%   |
| GOODRAM             | 1        | 2      | 0.11%   |
| Elite               | 1        | 2      | 0.11%   |
| DREVO               | 1        | 1      | 0.11%   |
| DOGFISH             | 1        | 1      | 0.11%   |
| Apple               | 1        | 1      | 0.11%   |
| Apacer              | 1        | 1      | 0.11%   |
| 2-Power             | 1        | 1      | 0.11%   |
| 128MB               | 1        | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB   | 26       | 2.55%   |
| Toshiba HDWD110 1TB               | 23       | 2.26%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 22       | 2.16%   |
| Netac SSD 240GB                   | 20       | 1.96%   |
| Kingston SA400S37240G 240GB SSD   | 15       | 1.47%   |
| Samsung SSD 860 EVO 250GB         | 13       | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB    | 12       | 1.18%   |
| Toshiba DT01ACA050 500GB          | 10       | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB      | 10       | 0.98%   |
| Samsung SSD 860 EVO 1TB           | 10       | 0.98%   |
| Kingston SV300S37A120G 120GB SSD  | 10       | 0.98%   |
| Hitachi HDS721050DLE630 500GB     | 10       | 0.98%   |
| Toshiba DT01ACA100 1TB            | 9        | 0.88%   |
| Seagate ST1000DM003-9YN162 1TB    | 9        | 0.88%   |
| Seagate ST1000DM003-1ER162 1TB    | 9        | 0.88%   |
| Samsung SSD 850 EVO 500GB         | 9        | 0.88%   |
| WDC WD2500AAKX-00ERMA0 250GB      | 8        | 0.79%   |
| Samsung SSD 970 EVO Plus 500GB    | 8        | 0.79%   |
| Samsung SSD 870 EVO 500GB         | 8        | 0.79%   |
| Kingston SA400S37120G 120GB SSD   | 8        | 0.79%   |
| Hitachi HDS721050CLA362 500GB     | 8        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB          | 7        | 0.69%   |
| Toshiba DT01ACA200 2TB            | 7        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB    | 7        | 0.69%   |
| Samsung SSD 850 EVO 250GB         | 7        | 0.69%   |
| Crucial CT500MX500SSD1 500GB      | 7        | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB    | 6        | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB    | 6        | 0.59%   |
| Samsung SSD 970 EVO 500GB         | 6        | 0.59%   |
| Samsung SSD 860 EVO 500GB         | 6        | 0.59%   |
| Crucial CT240BX500SSD1 240GB      | 6        | 0.59%   |
| Toshiba DT01ACA300 3TB            | 5        | 0.49%   |
| Samsung SSD 980 PRO 1TB           | 5        | 0.49%   |
| Crucial CT250MX500SSD1 250GB      | 5        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB       | 5        | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 4        | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB          | 4        | 0.39%   |
| Seagate ST4000DM000-1F2168 4TB    | 4        | 0.39%   |
| Seagate ST3500418AS 500GB         | 4        | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 0.39%   |
| SanDisk SD8SBAT128G1122 128GB SSD | 4        | 0.39%   |
| Samsung SSD 840 PRO Series 256GB  | 4        | 0.39%   |
| Kingston SV300S37A240G 240GB SSD  | 4        | 0.39%   |
| Kingston SUV400S37120G 120GB SSD  | 4        | 0.39%   |
| Crucial CT480BX500SSD1 480GB      | 4        | 0.39%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3        | 0.29%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 0.29%   |
| WDC WD5000AADS-00S9B0 500GB       | 3        | 0.29%   |
| WDC WD40EFRX-68N32N0 4TB          | 3        | 0.29%   |
| WDC WD20EFRX-68EUZN0 2TB          | 3        | 0.29%   |
| WDC WD20EARX-00PASB0 2TB          | 3        | 0.29%   |
| WDC WD20EARS-00MVWB0 2TB          | 3        | 0.29%   |
| Toshiba HDWD120 2TB               | 3        | 0.29%   |
| Seagate ST8000DM004-2CX188 8TB    | 3        | 0.29%   |
| Seagate ST3320613AS 320GB         | 3        | 0.29%   |
| Seagate ST3250310AS 250GB         | 3        | 0.29%   |
| Seagate ST3000DM001-1CH166 3TB    | 3        | 0.29%   |
| Seagate ST2000DM006-2DM164 2TB    | 3        | 0.29%   |
| Seagate Backup+ Hub BK 8TB        | 3        | 0.29%   |
| SanDisk SSD PLUS 240GB            | 3        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 174      | 247    | 37.66%  |
| WDC                 | 139      | 203    | 30.09%  |
| Toshiba             | 66       | 103    | 14.29%  |
| Hitachi             | 39       | 42     | 8.44%   |
| Samsung Electronics | 15       | 17     | 3.25%   |
| HGST                | 14       | 19     | 3.03%   |
| MAXTOR              | 6        | 6      | 1.3%    |
| SABRENT             | 2        | 2      | 0.43%   |
| Hewlett-Packard     | 2        | 4      | 0.43%   |
| NAS                 | 1        | 5      | 0.22%   |
| MaxDigital          | 1        | 2      | 0.22%   |
| MARSHAL             | 1        | 1      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |
| 128MB               | 1        | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 84       | 108    | 26.09%  |
| Kingston            | 58       | 68     | 18.01%  |
| Crucial             | 41       | 44     | 12.73%  |
| SanDisk             | 20       | 24     | 6.21%   |
| Netac               | 20       | 24     | 6.21%   |
| WDC                 | 17       | 18     | 5.28%   |
| A-DATA Technology   | 10       | 12     | 3.11%   |
| China               | 7        | 7      | 2.17%   |
| SPCC                | 6        | 6      | 1.86%   |
| PNY                 | 6        | 6      | 1.86%   |
| OCZ                 | 5        | 5      | 1.55%   |
| Intel               | 5        | 5      | 1.55%   |
| Toshiba             | 4        | 6      | 1.24%   |
| Patriot             | 4        | 4      | 1.24%   |
| Transcend           | 3        | 4      | 0.93%   |
| Mushkin             | 3        | 3      | 0.93%   |
| Unknown             | 2        | 2      | 0.62%   |
| Team                | 2        | 2      | 0.62%   |
| Seagate             | 2        | 2      | 0.62%   |
| PLEXTOR             | 2        | 4      | 0.62%   |
| Hajaan              | 2        | 2      | 0.62%   |
| Xinhaike            | 1        | 1      | 0.31%   |
| T-FORCE             | 1        | 1      | 0.31%   |
| PNY USB             | 1        | 1      | 0.31%   |
| Pioneer             | 1        | 1      | 0.31%   |
| Micron Technology   | 1        | 1      | 0.31%   |
| LITEON              | 1        | 1      | 0.31%   |
| Lexar               | 1        | 1      | 0.31%   |
| Lenovo              | 1        | 1      | 0.31%   |
| KingDian            | 1        | 1      | 0.31%   |
| KING                | 1        | 1      | 0.31%   |
| JAMESDONKEY         | 1        | 1      | 0.31%   |
| Intenso             | 1        | 1      | 0.31%   |
| GOODRAM             | 1        | 2      | 0.31%   |
| Gigabyte Technology | 1        | 1      | 0.31%   |
| DREVO               | 1        | 1      | 0.31%   |
| DOGFISH             | 1        | 1      | 0.31%   |
| Apacer              | 1        | 1      | 0.31%   |
| 2-Power             | 1        | 1      | 0.31%   |
| Unknown             | 1        | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 387      | 653    | 49.11%  |
| SSD     | 283      | 376    | 35.91%  |
| NVMe    | 102      | 151    | 12.94%  |
| Unknown | 13       | 24     | 1.65%   |
| MMC     | 3        | 3      | 0.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 504      | 1016   | 79.5%   |
| NVMe | 102      | 151    | 16.09%  |
| SAS  | 25       | 37     | 3.94%   |
| MMC  | 3        | 3      | 0.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 394      | 542    | 55.34%  |
| 0.51-1.0   | 175      | 225    | 24.58%  |
| 1.01-2.0   | 72       | 105    | 10.11%  |
| 3.01-4.0   | 31       | 66     | 4.35%   |
| 4.01-10.0  | 18       | 39     | 2.53%   |
| 2.01-3.0   | 16       | 24     | 2.25%   |
| 10.01-20.0 | 6        | 28     | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 192      | 35.49%  |
| 101-250        | 67       | 12.38%  |
| More than 3000 | 61       | 11.28%  |
| 251-500        | 56       | 10.35%  |
| 501-1000       | 49       | 9.06%   |
| 1001-2000      | 37       | 6.84%   |
| 1-20           | 32       | 5.91%   |
| 2001-3000      | 21       | 3.88%   |
| 51-100         | 18       | 3.33%   |
| 21-50          | 8        | 1.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 192      | 35.42%  |
| 1-20           | 101      | 18.63%  |
| 101-250        | 51       | 9.41%   |
| 21-50          | 33       | 6.09%   |
| 501-1000       | 33       | 6.09%   |
| 51-100         | 33       | 6.09%   |
| 251-500        | 29       | 5.35%   |
| More than 3000 | 28       | 5.17%   |
| 1001-2000      | 24       | 4.43%   |
| 2001-3000      | 15       | 2.77%   |
| 0              | 3        | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB       | 14       | 14     | 10.61%  |
| Seagate ST500DM002-1BD142 500GB    | 7        | 7      | 5.3%    |
| Hitachi HDS721050DLE630 500GB      | 5        | 5      | 3.79%   |
| Seagate ST1000DM003-9YN162 1TB     | 4        | 4      | 3.03%   |
| WDC WD20EARS-00MVWB0 2TB           | 3        | 3      | 2.27%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 3      | 2.27%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 2      | 1.52%   |
| Seagate ST3500418AS 500GB          | 2        | 2      | 1.52%   |
| Seagate ST3320613AS 320GB          | 2        | 2      | 1.52%   |
| Seagate ST3250310AS 250GB          | 2        | 2      | 1.52%   |
| Seagate ST3160813AS 160GB          | 2        | 2      | 1.52%   |
| Seagate ST31000528AS 1TB           | 2        | 2      | 1.52%   |
| Hitachi HDS721050CLA362 500GB      | 2        | 2      | 1.52%   |
| WDC WD6400BPVT-22HXZT3 640GB       | 1        | 1      | 0.76%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 1      | 0.76%   |
| WDC WD5003ABYX-18WERA0 500GB       | 1        | 2      | 0.76%   |
| WDC WD5002AALX-00J37A0 500GB       | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-00U6AA0 500GB       | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 0.76%   |
| WDC WD5000AAKS-22V1A0 500GB        | 1        | 1      | 0.76%   |
| WDC WD5000AAJS-22A8B0 500GB        | 1        | 1      | 0.76%   |
| WDC WD40EFZX-68AWUN0 4TB           | 1        | 6      | 0.76%   |
| WDC WD400BB-00DEA0 40GB            | 1        | 1      | 0.76%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1        | 1      | 0.76%   |
| WDC WD3200AAJS-22B4A0 320GB        | 1        | 1      | 0.76%   |
| WDC WD3200AAJS-08L7A0 320GB        | 1        | 1      | 0.76%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1        | 1      | 0.76%   |
| WDC WD30EZRX-00AZ6B0 3TB           | 1        | 1      | 0.76%   |
| WDC WD2500AAKX-00ERMA0 250GB       | 1        | 1      | 0.76%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 2      | 0.76%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 1      | 0.76%   |
| WDC WD1600AAJS-00L7A0 160GB        | 1        | 1      | 0.76%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 0.76%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 1        | 1      | 0.76%   |
| WDC WD1001FALS-75J7B0 1TB          | 1        | 1      | 0.76%   |
| Toshiba MK2565GSX 250GB            | 1        | 1      | 0.76%   |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 0.76%   |
| Toshiba DT01ACA050 500GB           | 1        | 1      | 0.76%   |
| SK Hynix PC401 NVMe 512GB          | 1        | 6      | 0.76%   |
| Seagate ST9500325AS 500GB          | 1        | 2      | 0.76%   |
| Seagate ST380215A 80GB             | 1        | 1      | 0.76%   |
| Seagate ST340016A 40GB             | 1        | 1      | 0.76%   |
| Seagate ST340014A 40GB             | 1        | 1      | 0.76%   |
| Seagate ST3320620AS 320GB          | 1        | 1      | 0.76%   |
| Seagate ST3320620A 320GB           | 1        | 1      | 0.76%   |
| Seagate ST3200827AS 200GB          | 1        | 2      | 0.76%   |
| Seagate ST32000542AS 2TB           | 1        | 1      | 0.76%   |
| Seagate ST31500341AS 1TB           | 1        | 1      | 0.76%   |
| Seagate ST3120827AS 120GB          | 1        | 2      | 0.76%   |
| Seagate ST3120811AS 120GB          | 1        | 1      | 0.76%   |
| Seagate ST3120022A 120GB           | 1        | 1      | 0.76%   |
| Seagate ST31000333AS 1TB           | 1        | 1      | 0.76%   |
| Seagate ST3000DM001-9YN166 3TB     | 1        | 1      | 0.76%   |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 0.76%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1      | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1      | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 51     | 34.11%  |
| Seagate             | 39       | 46     | 30.23%  |
| Hitachi             | 13       | 13     | 10.08%  |
| Samsung Electronics | 7        | 7      | 5.43%   |
| A-DATA Technology   | 5        | 6      | 3.88%   |
| Kingston            | 4        | 4      | 3.1%    |
| Intel               | 4        | 5      | 3.1%    |
| Toshiba             | 3        | 3      | 2.33%   |
| SanDisk             | 2        | 2      | 1.55%   |
| MAXTOR              | 2        | 2      | 1.55%   |
| SK Hynix            | 1        | 6      | 0.78%   |
| PNY                 | 1        | 1      | 0.78%   |
| KingDian            | 1        | 1      | 0.78%   |
| HGST                | 1        | 1      | 0.78%   |
| Crucial             | 1        | 1      | 0.78%   |
| China               | 1        | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 51     | 41.12%  |
| Seagate             | 39       | 46     | 36.45%  |
| Hitachi             | 13       | 13     | 12.15%  |
| Samsung Electronics | 5        | 5      | 4.67%   |
| Toshiba             | 3        | 3      | 2.8%    |
| MAXTOR              | 2        | 2      | 1.87%   |
| HGST                | 1        | 1      | 0.93%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 99       | 121    | 81.82%  |
| SSD  | 18       | 19     | 14.88%  |
| NVMe | 4        | 10     | 3.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 33.33%  |
| Seagate ST3500830AS 500GB        | 1        | 1      | 33.33%  |
| HGST HDN724040ALE640 4TB         | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| HGST    | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 415      | 856    | 68.03%  |
| Malfunc  | 115      | 150    | 18.85%  |
| Detected | 77       | 198    | 12.62%  |
| Failed   | 3        | 3      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 383      | 53.49%  |
| AMD                              | 148      | 20.67%  |
| Samsung Electronics              | 50       | 6.98%   |
| Marvell Technology Group         | 23       | 3.21%   |
| JMicron Technology               | 16       | 2.23%   |
| ASMedia Technology               | 16       | 2.23%   |
| Sandisk                          | 14       | 1.96%   |
| Phison Electronics               | 13       | 1.82%   |
| VIA Technologies                 | 12       | 1.68%   |
| Micron/Crucial Technology        | 7        | 0.98%   |
| Nvidia                           | 6        | 0.84%   |
| LSI Logic / Symbios Logic        | 5        | 0.7%    |
| Silicon Motion                   | 4        | 0.56%   |
| Broadcom / LSI                   | 3        | 0.42%   |
| ADATA Technology                 | 3        | 0.42%   |
| Seagate Technology               | 2        | 0.28%   |
| Kingston Technology Company      | 2        | 0.28%   |
| SK Hynix                         | 1        | 0.14%   |
| Silicon Integrated Systems [SiS] | 1        | 0.14%   |
| Silicon Image                    | 1        | 0.14%   |
| Realtek Semiconductor            | 1        | 0.14%   |
| Micron Technology                | 1        | 0.14%   |
| Lite-On Technology               | 1        | 0.14%   |
| Integrated Technology Express    | 1        | 0.14%   |
| Biwin Storage Technology         | 1        | 0.14%   |
| Adaptec                          | 1        | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 96       | 10.62%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 68       | 7.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 43       | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 35       | 3.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 35       | 3.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 26       | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 2.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25       | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21       | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21       | 2.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 19       | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19       | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18       | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17       | 1.88%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 1.77%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 15       | 1.66%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 14       | 1.55%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 1.55%   |
| AMD FCH SATA Controller D                                                               | 10       | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1%      |
| VIA VT6415 PATA IDE Host Controller                                                     | 8        | 0.88%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 0.77%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.66%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 6        | 0.66%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6        | 0.66%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6        | 0.66%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.66%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 0.66%   |
| AMD X399 Series Chipset SATA Controller                                                 | 6        | 0.66%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.55%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 0.55%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 5        | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 0.55%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 5        | 0.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.44%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.44%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.44%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4        | 0.44%   |
| Intel SSD 660P Series                                                                   | 4        | 0.44%   |
| Intel SSD 600P Series                                                                   | 4        | 0.44%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.44%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.44%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.44%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.33%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.33%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 3        | 0.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 435      | 60.92%  |
| IDE  | 138      | 19.33%  |
| NVMe | 102      | 14.29%  |
| RAID | 27       | 3.78%   |
| SAS  | 9        | 1.26%   |
| SCSI | 3        | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 382      | 70.87%  |
| AMD          | 156      | 28.94%  |
| CentaurHauls | 1        | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 22       | 4.08%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 21       | 3.9%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 14       | 2.6%    |
| AMD Ryzen 5 3600 6-Core Processor           | 12       | 2.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 9        | 1.67%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 8        | 1.48%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 8        | 1.48%   |
| Intel Core i3-3210 CPU @ 3.20GHz            | 7        | 1.3%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 7        | 1.3%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 6        | 1.11%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 6        | 1.11%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6        | 1.11%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 6        | 1.11%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 1.11%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 5        | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 0.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 5        | 0.93%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 5        | 0.93%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 5        | 0.93%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 0.93%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 0.93%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.74%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 4        | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.74%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 0.74%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 0.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.74%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.74%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 0.74%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 3        | 0.56%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 3        | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 0.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 0.56%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.56%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 0.56%   |
| Intel Celeron CPU N2820 @ 2.13GHz           | 3        | 0.56%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 0.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 0.56%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 0.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 0.56%   |
| AMD Phenom II X4 965 Processor              | 3        | 0.56%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 3        | 0.56%   |
| AMD A10-5700 APU with Radeon HD Graphics    | 3        | 0.56%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 0.37%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 0.37%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2        | 0.37%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 0.37%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.37%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.37%   |
| Intel Core i7-8086K CPU @ 4.00GHz           | 2        | 0.37%   |
| Intel Core i7 CPU 930 @ 2.80GHz             | 2        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 85       | 15.77%  |
| Intel Core i7           | 67       | 12.43%  |
| Intel Pentium           | 56       | 10.39%  |
| Intel Core i3           | 56       | 10.39%  |
| AMD Ryzen 5             | 37       | 6.86%   |
| Intel Core 2 Duo        | 28       | 5.19%   |
| AMD Ryzen 7             | 24       | 4.45%   |
| Intel Xeon              | 22       | 4.08%   |
| Intel Celeron           | 19       | 3.53%   |
| AMD FX                  | 14       | 2.6%    |
| AMD Ryzen 9             | 13       | 2.41%   |
| Intel Pentium Dual-Core | 12       | 2.23%   |
| Intel Core 2 Quad       | 10       | 1.86%   |
| AMD Ryzen 3             | 10       | 1.86%   |
| AMD Ryzen Threadripper  | 9        | 1.67%   |
| AMD A10                 | 7        | 1.3%    |
| AMD Phenom II X4        | 6        | 1.11%   |
| Intel Pentium 4         | 5        | 0.93%   |
| Intel Core 2            | 5        | 0.93%   |
| AMD Athlon              | 5        | 0.93%   |
| Other                   | 4        | 0.74%   |
| Intel Pentium Gold      | 4        | 0.74%   |
| Intel Core i9           | 4        | 0.74%   |
| Intel Atom              | 4        | 0.74%   |
| AMD Athlon X4           | 3        | 0.56%   |
| AMD Athlon II X2        | 3        | 0.56%   |
| AMD A8                  | 3        | 0.56%   |
| AMD Phenom II X3        | 2        | 0.37%   |
| AMD E                   | 2        | 0.37%   |
| AMD Athlon XP           | 2        | 0.37%   |
| AMD Athlon 64 X2        | 2        | 0.37%   |
| AMD A6                  | 2        | 0.37%   |
| Intel Pentium Dual      | 1        | 0.19%   |
| CentaurHauls VIA Eden   | 1        | 0.19%   |
| AMD Sempron             | 1        | 0.19%   |
| AMD Ryzen 7 PRO         | 1        | 0.19%   |
| AMD PRO A8              | 1        | 0.19%   |
| AMD Phenom II X6        | 1        | 0.19%   |
| AMD Opteron             | 1        | 0.19%   |
| AMD GX                  | 1        | 0.19%   |
| AMD EPYC                | 1        | 0.19%   |
| AMD E1                  | 1        | 0.19%   |
| AMD Athlon II X4        | 1        | 0.19%   |
| AMD Athlon II Neo       | 1        | 0.19%   |
| AMD Athlon Dual Core    | 1        | 0.19%   |
| AMD A4                  | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 212      | 39.33%  |
| 4      | 167      | 30.98%  |
| 8      | 61       | 11.32%  |
| 6      | 52       | 9.65%   |
| 1      | 13       | 2.41%   |
| 12     | 12       | 2.23%   |
| 16     | 11       | 2.04%   |
| 3      | 4        | 0.74%   |
| 32     | 2        | 0.37%   |
| 24     | 2        | 0.37%   |
| 44     | 1        | 0.19%   |
| 28     | 1        | 0.19%   |
| 14     | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 533      | 98.89%  |
| 2      | 6        | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 285      | 52.88%  |
| 1      | 254      | 47.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 532      | 98.7%   |
| 32-bit         | 6        | 1.11%   |
| Unknown        | 1        | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 79       | 14.6%   |
| 0x306c3    | 70       | 12.94%  |
| 0x206a7    | 48       | 8.87%   |
| 0x306a9    | 36       | 6.65%   |
| 0x1067a    | 31       | 5.73%   |
| 0x08701021 | 25       | 4.62%   |
| 0xa0655    | 23       | 4.25%   |
| 0x506e3    | 19       | 3.51%   |
| 0x906e9    | 12       | 2.22%   |
| 0x0800820d | 10       | 1.85%   |
| 0x906ea    | 9        | 1.66%   |
| 0x08108109 | 9        | 1.66%   |
| 0x06003106 | 8        | 1.48%   |
| 0x0a201009 | 7        | 1.29%   |
| 0xa0653    | 6        | 1.11%   |
| 0x206d7    | 6        | 1.11%   |
| 0x0a201016 | 6        | 1.11%   |
| 0x010000c8 | 6        | 1.11%   |
| 0x906ed    | 5        | 0.92%   |
| 0x6fd      | 5        | 0.92%   |
| 0x6fb      | 5        | 0.92%   |
| 0x306f2    | 5        | 0.92%   |
| 0x20655    | 5        | 0.92%   |
| 0x010000b6 | 5        | 0.92%   |
| 0xa0671    | 4        | 0.74%   |
| 0x08101016 | 4        | 0.74%   |
| 0x08001138 | 4        | 0.74%   |
| 0x08001137 | 4        | 0.74%   |
| 0x06000852 | 4        | 0.74%   |
| 0xf29      | 3        | 0.55%   |
| 0x6f2      | 3        | 0.55%   |
| 0x30673    | 3        | 0.55%   |
| 0x206c2    | 3        | 0.55%   |
| 0x106a5    | 3        | 0.55%   |
| 0x10677    | 3        | 0.55%   |
| 0x10676    | 3        | 0.55%   |
| 0x06001119 | 3        | 0.55%   |
| 0x0600063e | 3        | 0.55%   |
| 0x906ec    | 2        | 0.37%   |
| 0x906eb    | 2        | 0.37%   |
| 0x706a1    | 2        | 0.37%   |
| 0x6f6      | 2        | 0.37%   |
| 0x50654    | 2        | 0.37%   |
| 0x30678    | 2        | 0.37%   |
| 0x106e5    | 2        | 0.37%   |
| 0x08701013 | 2        | 0.37%   |
| 0x08301039 | 2        | 0.37%   |
| 0x0700010f | 2        | 0.37%   |
| 0x0600611a | 2        | 0.37%   |
| 0x06000822 | 2        | 0.37%   |
| 0xf49      | 1        | 0.18%   |
| 0xf43      | 1        | 0.18%   |
| 0xf41      | 1        | 0.18%   |
| 0xa0660    | 1        | 0.18%   |
| 0x806e9    | 1        | 0.18%   |
| 0x6f7      | 1        | 0.18%   |
| 0x506c9    | 1        | 0.18%   |
| 0x406f1    | 1        | 0.18%   |
| 0x406e3    | 1        | 0.18%   |
| 0x406d8    | 1        | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 85       | 15.77%  |
| SandyBridge   | 56       | 10.39%  |
| IvyBridge     | 43       | 7.98%   |
| Penryn        | 42       | 7.79%   |
| Zen 2         | 38       | 7.05%   |
| KabyLake      | 37       | 6.86%   |
| CometLake     | 31       | 5.75%   |
| Zen+          | 27       | 5.01%   |
| Skylake       | 25       | 4.64%   |
| Zen           | 18       | 3.34%   |
| Core          | 18       | 3.34%   |
| Zen 3         | 16       | 2.97%   |
| K10           | 15       | 2.78%   |
| Piledriver    | 13       | 2.41%   |
| Westmere      | 11       | 2.04%   |
| Steamroller   | 11       | 2.04%   |
| Silvermont    | 10       | 1.86%   |
| Nehalem       | 9        | 1.67%   |
| NetBurst      | 6        | 1.11%   |
| Bulldozer     | 5        | 0.93%   |
| Unknown       | 5        | 0.93%   |
| K8 Hammer     | 3        | 0.56%   |
| Jaguar        | 3        | 0.56%   |
| Excavator     | 3        | 0.56%   |
| K6            | 2        | 0.37%   |
| Goldmont plus | 2        | 0.37%   |
| Bobcat        | 2        | 0.37%   |
| Goldmont      | 1        | 0.19%   |
| Broadwell     | 1        | 0.19%   |
| Bonnell       | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 230      | 40%     |
| Intel                            | 201      | 34.96%  |
| AMD                              | 133      | 23.13%  |
| ASPEED Technology                | 7        | 1.22%   |
| VIA Technologies                 | 2        | 0.35%   |
| Silicon Integrated Systems [SiS] | 1        | 0.17%   |
| Matrox Electronics Systems       | 1        | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 42       | 7.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 24       | 4.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 24       | 4.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 24       | 4.12%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 20       | 3.44%   |
| Nvidia GF108 [GeForce GT 730]                                               | 20       | 3.44%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 2.58%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 15       | 2.58%   |
| Nvidia GF108 [GeForce GT 630]                                               | 14       | 2.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13       | 2.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 2.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 2.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 11       | 1.89%   |
| Nvidia GF108 [GeForce GT 430]                                               | 10       | 1.72%   |
| AMD Picasso                                                                 | 10       | 1.72%   |
| Intel HD Graphics 530                                                       | 9        | 1.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 1.55%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.2%    |
| Intel HD Graphics 630                                                       | 7        | 1.2%    |
| ASPEED Technology ASPEED Graphics Family                                    | 7        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 6        | 1.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 1.03%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 6        | 1.03%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 0.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 0.86%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.69%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 0.69%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 4        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.52%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 3        | 0.52%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 0.52%   |
| Nvidia G92 [GeForce GTS 250]                                                | 3        | 0.52%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 0.52%   |
| Intel 82865G Integrated Graphics Controller                                 | 3        | 0.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 0.52%   |
| AMD Trinity [Radeon HD 7660D]                                               | 3        | 0.52%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3        | 0.52%   |
| AMD RS880 [Radeon HD 4200]                                                  | 3        | 0.52%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.52%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 0.52%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.34%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.34%   |
| Nvidia GM206GL [Quadro M2000]                                               | 2        | 0.34%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.34%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.34%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 2        | 0.34%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.34%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 0.34%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 0.34%   |
| Nvidia GF119 [NVS 310]                                                      | 2        | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 213      | 39.37%  |
| 1 x Intel          | 171      | 31.61%  |
| 1 x AMD            | 126      | 23.29%  |
| Intel + Nvidia     | 12       | 2.22%   |
| 1 x ASPEED         | 6        | 1.11%   |
| 2 x AMD            | 3        | 0.55%   |
| 1 x VIA            | 2        | 0.37%   |
| Intel + 2 x Nvidia | 2        | 0.37%   |
| AMD + Nvidia       | 2        | 0.37%   |
| Other              | 1        | 0.18%   |
| 1 x SiS            | 1        | 0.18%   |
| 1 x Matrox         | 1        | 0.18%   |
| AMD + ASPEED       | 1        | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 254      | 46.95%  |
| Unknown     | 194      | 35.86%  |
| Proprietary | 93       | 17.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 349      | 64.39%  |
| 1.01-2.0   | 39       | 7.2%    |
| 7.01-8.0   | 34       | 6.27%   |
| 3.01-4.0   | 33       | 6.09%   |
| 0.51-1.0   | 30       | 5.54%   |
| 0.01-0.5   | 29       | 5.35%   |
| 5.01-6.0   | 15       | 2.77%   |
| 2.01-3.0   | 5        | 0.92%   |
| 8.01-16.0  | 5        | 0.92%   |
| 16.01-24.0 | 2        | 0.37%   |
| 24.01-32.0 | 1        | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 57       | 14.65%  |
| Dell                    | 47       | 12.08%  |
| Goldstar                | 38       | 9.77%   |
| Acer                    | 28       | 7.2%    |
| Ancor Communications    | 27       | 6.94%   |
| BenQ                    | 25       | 6.43%   |
| Hewlett-Packard         | 23       | 5.91%   |
| AOC                     | 18       | 4.63%   |
| Philips                 | 15       | 3.86%   |
| Unknown                 | 12       | 3.08%   |
| ViewSonic               | 9        | 2.31%   |
| Lenovo                  | 9        | 2.31%   |
| Eizo                    | 7        | 1.8%    |
| ASUSTek Computer        | 7        | 1.8%    |
| Iiyama                  | 6        | 1.54%   |
| Sony                    | 5        | 1.29%   |
| NEC Computers           | 4        | 1.03%   |
| LG Electronics          | 4        | 1.03%   |
| Fujitsu Siemens         | 3        | 0.77%   |
| Vizio                   | 2        | 0.51%   |
| Vestel Elektronik       | 2        | 0.51%   |
| ONN                     | 2        | 0.51%   |
| MStar                   | 2        | 0.51%   |
| MSI                     | 2        | 0.51%   |
| Hitachi                 | 2        | 0.51%   |
| Chi Mei Optoelectronics | 2        | 0.51%   |
| Unknown                 | 2        | 0.51%   |
| WTC                     | 1        | 0.26%   |
| VMO                     | 1        | 0.26%   |
| TXD                     | 1        | 0.26%   |
| TPU                     | 1        | 0.26%   |
| SGT                     | 1        | 0.26%   |
| Sceptre Tech            | 1        | 0.26%   |
| Sangyo                  | 1        | 0.26%   |
| RIC                     | 1        | 0.26%   |
| Prestigio               | 1        | 0.26%   |
| Onkyo                   | 1        | 0.26%   |
| ODH                     | 1        | 0.26%   |
| Mitsubishi              | 1        | 0.26%   |
| MiTAC                   | 1        | 0.26%   |
| MIT                     | 1        | 0.26%   |
| Mi                      | 1        | 0.26%   |
| Medion                  | 1        | 0.26%   |
| Lenovo Group Limited    | 1        | 0.26%   |
| JVC                     | 1        | 0.26%   |
| INFOTRONIC              | 1        | 0.26%   |
| Idek Iiyama             | 1        | 0.26%   |
| Hyundai ImageQuest      | 1        | 0.26%   |
| HXF                     | 1        | 0.26%   |
| HKC                     | 1        | 0.26%   |
| HannStar Display        | 1        | 0.26%   |
| HannStar                | 1        | 0.26%   |
| COBY                    | 1        | 0.26%   |
| Belinea                 | 1        | 0.26%   |
| AUS                     | 1        | 0.26%   |
| AU Optronics            | 1        | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 9        | 2.2%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 4        | 0.98%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 4        | 0.98%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 4        | 0.98%   |
| Philips 220WS PHL0851 1680x1050 474x296mm 22.0-inch                    | 3        | 0.73%   |
| Dell P2415Q DELA0BE 2048x1280 530x300mm 24.0-inch                      | 3        | 0.73%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 0.73%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 0.73%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 3        | 0.73%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2        | 0.49%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                     | 2        | 0.49%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 2        | 0.49%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 2        | 0.49%   |
| Samsung Electronics SyncMaster SAM00C8 1280x1024 338x270mm 17.0-inch   | 2        | 0.49%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 2        | 0.49%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 2        | 0.49%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.49%   |
| MStar TV_MONITOR MST0030 1440x900 1150x650mm 52.0-inch                 | 2        | 0.49%   |
| Lenovo LEN LI2364d LEN65C8 1920x1080 509x286mm 23.0-inch               | 2        | 0.49%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 0.49%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 0.49%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.49%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 0.49%   |
| Dell U2713HM DEL407E 2560x1440 597x336mm 27.0-inch                     | 2        | 0.49%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 0.49%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 0.49%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                         | 2        | 0.49%   |
| Ancor Communications PB328 ACI32A5 2560x1440 708x399mm 32.0-inch       | 2        | 0.49%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 2        | 0.49%   |
| Acer K272HUL ACR0524 2560x1440 598x336mm 27.0-inch                     | 2        | 0.49%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 0.49%   |
| Unknown                                                                | 2        | 0.49%   |
| WTC FW1420S WTC1400 1024x768 304x228mm 15.0-inch                       | 1        | 0.24%   |
| VMO WQX DP VMO1507 2560x1600 1600x1000mm 74.3-inch                     | 1        | 0.24%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.24%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1        | 0.24%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 1        | 0.24%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch              | 1        | 0.24%   |
| ViewSonic VG2860 SERIES VSC1F30 3840x2160 621x341mm 27.9-inch          | 1        | 0.24%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.24%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch              | 1        | 0.24%   |
| Unknown LCD Monitor TCT DP1080P60 1920x1080                            | 1        | 0.24%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                  | 1        | 0.24%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1        | 0.24%   |
| TXD HDMI TXD7825 1600x900 410x260mm 19.1-inch                          | 1        | 0.24%   |
| TPU HDMI TPU2150 1920x1080 376x301mm 19.0-inch                         | 1        | 0.24%   |
| Sony TV SNYE903 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.24%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.24%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.24%   |
| SGT LCD Monitor SGT1900 1440x900 400x270mm 19.0-inch                   | 1        | 0.24%   |
| Sceptre Tech X240BV-FHD SPT2411 1920x1080 531x299mm 24.0-inch          | 1        | 0.24%   |
| Sangyo LCD Monitor MT23L 1360x768                                      | 1        | 0.24%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1        | 0.24%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.24%   |
| Samsung Electronics U24E850 SAM0CCF 3840x2160 521x293mm 23.5-inch      | 1        | 0.24%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.24%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.24%   |
| Samsung Electronics SyncMaster SAM0572 1280x1024 376x301mm 19.0-inch   | 1        | 0.24%   |
| Samsung Electronics SyncMaster SAM0564 1024x768 410x230mm 18.5-inch    | 1        | 0.24%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch   | 1        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 157      | 40.89%  |
| 1280x1024 (SXGA)   | 34       | 8.85%   |
| 3840x2160 (4K)     | 31       | 8.07%   |
| 2560x1440 (QHD)    | 29       | 7.55%   |
| 1680x1050 (WSXGA+) | 24       | 6.25%   |
| Unknown            | 14       | 3.65%   |
| 1366x768 (WXGA)    | 13       | 3.39%   |
| 1920x1200 (WUXGA)  | 12       | 3.13%   |
| 1600x900 (HD+)     | 11       | 2.86%   |
| 2288x1287          | 9        | 2.34%   |
| 2560x1080          | 8        | 2.08%   |
| 1440x900 (WXGA+)   | 7        | 1.82%   |
| 1024x768 (XGA)     | 6        | 1.56%   |
| 3440x1440          | 5        | 1.3%    |
| 3840x1080          | 4        | 1.04%   |
| 2560x1600          | 3        | 0.78%   |
| 1600x1200          | 3        | 0.78%   |
| 4480x1440          | 2        | 0.52%   |
| 1360x768           | 2        | 0.52%   |
| 7680x4320          | 1        | 0.26%   |
| 6400x2160          | 1        | 0.26%   |
| 5760x1080          | 1        | 0.26%   |
| 5360x1440          | 1        | 0.26%   |
| 5120x1080          | 1        | 0.26%   |
| 3360x1080          | 1        | 0.26%   |
| 3360x1050          | 1        | 0.26%   |
| 2560x1024          | 1        | 0.26%   |
| 1920x540           | 1        | 0.26%   |
| 1024x600           | 1        | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 54       | 14.32%  |
| 27      | 49       | 13%     |
| 23      | 48       | 12.73%  |
| Unknown | 34       | 9.02%   |
| 21      | 31       | 8.22%   |
| 22      | 21       | 5.57%   |
| 19      | 20       | 5.31%   |
| 17      | 18       | 4.77%   |
| 18      | 15       | 3.98%   |
| 31      | 12       | 3.18%   |
| 15      | 12       | 3.18%   |
| 20      | 11       | 2.92%   |
| 34      | 10       | 2.65%   |
| 142     | 9        | 2.39%   |
| 72      | 4        | 1.06%   |
| 32      | 4        | 1.06%   |
| 84      | 3        | 0.8%    |
| 52      | 3        | 0.8%    |
| 28      | 3        | 0.8%    |
| 65      | 2        | 0.53%   |
| 48      | 2        | 0.53%   |
| 29      | 2        | 0.53%   |
| 25      | 2        | 0.53%   |
| 74      | 1        | 0.27%   |
| 55      | 1        | 0.27%   |
| 49      | 1        | 0.27%   |
| 38      | 1        | 0.27%   |
| 35      | 1        | 0.27%   |
| 26      | 1        | 0.27%   |
| 16      | 1        | 0.27%   |
| 10      | 1        | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 140      | 38.25%  |
| 401-500        | 80       | 21.86%  |
| Unknown        | 34       | 9.29%   |
| 301-350        | 30       | 8.2%    |
| 601-700        | 23       | 6.28%   |
| 351-400        | 17       | 4.64%   |
| 701-800        | 13       | 3.55%   |
| More than 2000 | 9        | 2.46%   |
| 1001-1500      | 9        | 2.46%   |
| 1501-2000      | 8        | 2.19%   |
| 801-900        | 2        | 0.55%   |
| 201-300        | 1        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 210      | 58.33%  |
| 16/10   | 46       | 12.78%  |
| Unknown | 32       | 8.89%   |
| 5/4     | 30       | 8.33%   |
| 4/3     | 13       | 3.61%   |
| 21/9    | 13       | 3.61%   |
| 1.00    | 10       | 2.78%   |
| 3/2     | 3        | 0.83%   |
| 6/5     | 2        | 0.56%   |
| 1.96    | 1        | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 126      | 34.05%  |
| 301-350        | 49       | 13.24%  |
| 151-200        | 42       | 11.35%  |
| Unknown        | 34       | 9.19%   |
| 351-500        | 30       | 8.11%   |
| 141-150        | 27       | 7.3%    |
| More than 1000 | 24       | 6.49%   |
| 251-300        | 20       | 5.41%   |
| 101-110        | 10       | 2.7%    |
| 131-140        | 3        | 0.81%   |
| 111-120        | 2        | 0.54%   |
| 501-1000       | 2        | 0.54%   |
| 41-50          | 1        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 223      | 62.12%  |
| 101-120 | 57       | 15.88%  |
| Unknown | 34       | 9.47%   |
| 1-50    | 20       | 5.57%   |
| 121-160 | 15       | 4.18%   |
| 161-240 | 10       | 2.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 263      | 48.61%  |
| 0     | 205      | 37.89%  |
| 2     | 66       | 12.2%   |
| 3     | 5        | 0.92%   |
| 4     | 2        | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 347      | 52.34%  |
| Intel                            | 180      | 27.15%  |
| Qualcomm Atheros                 | 46       | 6.94%   |
| Broadcom                         | 22       | 3.32%   |
| Ralink Technology                | 7        | 1.06%   |
| Nvidia                           | 6        | 0.9%    |
| Microsoft                        | 5        | 0.75%   |
| Ralink                           | 4        | 0.6%    |
| Marvell Technology Group         | 4        | 0.6%    |
| D-Link                           | 4        | 0.6%    |
| Broadcom Limited                 | 4        | 0.6%    |
| TP-Link                          | 3        | 0.45%   |
| NetGear                          | 3        | 0.45%   |
| Mellanox Technologies            | 3        | 0.45%   |
| VIA Technologies                 | 2        | 0.3%    |
| Qualcomm Atheros Communications  | 2        | 0.3%    |
| Belkin Components                | 2        | 0.3%    |
| Aquantia                         | 2        | 0.3%    |
| ZTE WCDMA Technologies MSM       | 1        | 0.15%   |
| Xiaomi                           | 1        | 0.15%   |
| Wilocity                         | 1        | 0.15%   |
| STMicroelectronics               | 1        | 0.15%   |
| Silicon Integrated Systems [SiS] | 1        | 0.15%   |
| QLogic                           | 1        | 0.15%   |
| OPPO Electronics                 | 1        | 0.15%   |
| Micro Star International         | 1        | 0.15%   |
| IMC Networks                     | 1        | 0.15%   |
| Google                           | 1        | 0.15%   |
| Edimax Technology                | 1        | 0.15%   |
| DisplayLink                      | 1        | 0.15%   |
| D-Link System                    | 1        | 0.15%   |
| ASUSTek Computer                 | 1        | 0.15%   |
| ASIX Electronics                 | 1        | 0.15%   |
| American Megatrends              | 1        | 0.15%   |
| ADMtek                           | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 285      | 39.47%  |
| Intel I211 Gigabit Network Connection                             | 28       | 3.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25       | 3.46%   |
| Intel Wi-Fi 6 AX200                                               | 19       | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 18       | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18       | 2.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 2.22%   |
| Intel I210 Gigabit Network Connection                             | 11       | 1.52%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8        | 1.11%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 7        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7        | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 0.97%   |
| Intel Wireless 7260                                               | 6        | 0.83%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 6        | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.69%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.55%   |
| Microsoft Xbox 360 Wireless Adapter                               | 4        | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.42%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3        | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.42%   |
| Intel Ethernet Controller 10G X550T                               | 3        | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.28%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.28%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.28%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.28%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.28%   |
| NetGear A6210                                                     | 2        | 0.28%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.28%   |
| Intel Wireless-AC 9260                                            | 2        | 0.28%   |
| Intel Wireless 8260                                               | 2        | 0.28%   |
| Intel Wireless 3165                                               | 2        | 0.28%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.28%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.28%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.28%   |
| Intel 82599 10 Gigabit Dual Port Network Connection               | 2        | 0.28%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 0.28%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 46       | 34.07%  |
| Realtek Semiconductor           | 25       | 18.52%  |
| Qualcomm Atheros                | 21       | 15.56%  |
| Ralink Technology               | 7        | 5.19%   |
| Broadcom                        | 7        | 5.19%   |
| Microsoft                       | 5        | 3.7%    |
| Ralink                          | 4        | 2.96%   |
| D-Link                          | 4        | 2.96%   |
| TP-Link                         | 3        | 2.22%   |
| NetGear                         | 3        | 2.22%   |
| Qualcomm Atheros Communications | 2        | 1.48%   |
| Belkin Components               | 2        | 1.48%   |
| Wilocity                        | 1        | 0.74%   |
| Micro Star International        | 1        | 0.74%   |
| IMC Networks                    | 1        | 0.74%   |
| Edimax Technology               | 1        | 0.74%   |
| D-Link System                   | 1        | 0.74%   |
| ASUSTek Computer                | 1        | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 19       | 14.07%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8        | 5.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 7        | 5.19%   |
| Intel Wireless 7260                                                     | 6        | 4.44%   |
| Ralink MT7601U Wireless Adapter                                         | 4        | 2.96%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 4        | 2.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3        | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3        | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2        | 1.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2        | 1.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 1.48%   |
| NetGear A6210                                                           | 2        | 1.48%   |
| Intel Wireless-AC 9260                                                  | 2        | 1.48%   |
| Intel Wireless 8260                                                     | 2        | 1.48%   |
| Intel Wireless 3165                                                     | 2        | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 1.48%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 2        | 1.48%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                      | 1        | 0.74%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1        | 0.74%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                             | 1        | 0.74%   |
| TP-Link Archer T4U ver.3                                                | 1        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1        | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1        | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1        | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 0.74%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1        | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1        | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 0.74%   |
| Realtek 802.11ac NIC                                                    | 1        | 0.74%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 0.74%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 0.74%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 0.74%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1        | 0.74%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1        | 0.74%   |
| Ralink RT2800 802.11n PCI                                               | 1        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 0.74%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1        | 0.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 0.74%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 0.74%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                 | 1        | 0.74%   |
| Microsoft Wireless XBox Controller Dongle                               | 1        | 0.74%   |
| Micro Star International RT2573                                         | 1        | 0.74%   |
| Intel Wireless 8265 / 8275                                              | 1        | 0.74%   |
| Intel Wireless 3160                                                     | 1        | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 0.74%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                    | 1        | 0.74%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 336      | 59.26%  |
| Intel                            | 158      | 27.87%  |
| Qualcomm Atheros                 | 27       | 4.76%   |
| Broadcom                         | 16       | 2.82%   |
| Nvidia                           | 6        | 1.06%   |
| Marvell Technology Group         | 4        | 0.71%   |
| Broadcom Limited                 | 4        | 0.71%   |
| Mellanox Technologies            | 3        | 0.53%   |
| VIA Technologies                 | 2        | 0.35%   |
| Aquantia                         | 2        | 0.35%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.18%   |
| Xiaomi                           | 1        | 0.18%   |
| Silicon Integrated Systems [SiS] | 1        | 0.18%   |
| QLogic                           | 1        | 0.18%   |
| OPPO Electronics                 | 1        | 0.18%   |
| DisplayLink                      | 1        | 0.18%   |
| ASIX Electronics                 | 1        | 0.18%   |
| American Megatrends              | 1        | 0.18%   |
| ADMtek                           | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 285      | 48.72%  |
| Intel I211 Gigabit Network Connection                             | 28       | 4.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25       | 4.27%   |
| Intel Ethernet Connection (2) I219-V                              | 18       | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18       | 3.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 2.74%   |
| Intel I210 Gigabit Network Connection                             | 11       | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7        | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 6        | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 6        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.51%   |
| Intel Ethernet Controller 10G X550T                               | 3        | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.51%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.34%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.34%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.34%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.34%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.34%   |
| Intel 82599 10 Gigabit Dual Port Network Connection               | 2        | 0.34%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.34%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.34%   |
| Intel 82566DC Gigabit Network Connection                          | 2        | 0.34%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 0.34%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.34%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.34%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1        | 0.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.17%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.17%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.17%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.17%   |
| QLogic cLOM8214 1/10GbE Controller                                | 1        | 0.17%   |
| OPPO SDM712-MTP _SN:E0B69F21                                      | 1        | 0.17%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.17%   |
| Mellanox MT27700 Family [ConnectX-4]                              | 1        | 0.17%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.17%   |
| Intel PRO/100 VE Network Connection                               | 1        | 0.17%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 535      | 80.57%  |
| WiFi     | 127      | 19.13%  |
| Modem    | 1        | 0.15%   |
| Unknown  | 1        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 508      | 85.38%  |
| WiFi     | 86       | 14.45%  |
| Unknown  | 1        | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 403      | 74.77%  |
| 2     | 112      | 20.78%  |
| 3     | 17       | 3.15%   |
| 5     | 2        | 0.37%   |
| 4     | 2        | 0.37%   |
| 13    | 1        | 0.19%   |
| 6     | 1        | 0.19%   |
| 0     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 470      | 87.2%   |
| Yes  | 69       | 12.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 39.82%  |
| Cambridge Silicon Radio         | 26       | 23.01%  |
| Broadcom                        | 11       | 9.73%   |
| ASUSTek Computer                | 9        | 7.96%   |
| Realtek Semiconductor           | 7        | 6.19%   |
| Qualcomm Atheros Communications | 4        | 3.54%   |
| IMC Networks                    | 4        | 3.54%   |
| Belkin Components               | 2        | 1.77%   |
| Toshiba                         | 1        | 0.88%   |
| Sitecom Europe                  | 1        | 0.88%   |
| Realtek                         | 1        | 0.88%   |
| Micro Star International        | 1        | 0.88%   |
| Edimax Technology               | 1        | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 26       | 23.01%  |
| Intel AX200 Bluetooth                                     | 20       | 17.7%   |
| Intel Bluetooth wireless interface                        | 8        | 7.08%   |
| Intel Wireless-AC 3168 Bluetooth                          | 7        | 6.19%   |
| Realtek Bluetooth Radio                                   | 5        | 4.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 5        | 4.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 4        | 3.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 4        | 3.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 3        | 2.65%   |
| Realtek  Bluetooth 4.2 Adapter                            | 2        | 1.77%   |
| Intel Bluetooth Device                                    | 2        | 1.77%   |
| IMC Networks Bluetooth Radio                              | 2        | 1.77%   |
| ASUS Bluetooth Device                                     | 2        | 1.77%   |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.88%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.88%   |
| Realtek Bluetooth Radio                                   | 1        | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 0.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 1        | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 1        | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 0.88%   |
| Micro Star International Bluetooth EDR Device             | 1        | 0.88%   |
| Intel AX210 Bluetooth                                     | 1        | 0.88%   |
| IMC Networks Bluetooth Device                             | 1        | 0.88%   |
| IMC Networks Bluetooth                                    | 1        | 0.88%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter   | 1        | 0.88%   |
| Broadcom HP Portable Bumble Bee                           | 1        | 0.88%   |
| Broadcom Bluetooth 3.0 Device                             | 1        | 0.88%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 1        | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 1        | 0.88%   |
| Broadcom BCM2045 Bluetooth                                | 1        | 0.88%   |
| Broadcom BCM2035 Bluetooth dongle                         | 1        | 0.88%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter     | 1        | 0.88%   |
| Belkin Components F8T012 Bluetooth Adapter                | 1        | 0.88%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 1        | 0.88%   |
| ASUS Bluetooth Radio                                      | 1        | 0.88%   |
| ASUS BCM20702A0                                           | 1        | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 364      | 42.77%  |
| Nvidia                           | 209      | 24.56%  |
| AMD                              | 183      | 21.5%   |
| C-Media Electronics              | 13       | 1.53%   |
| Logitech                         | 8        | 0.94%   |
| Creative Labs                    | 8        | 0.94%   |
| RODE Microphones                 | 5        | 0.59%   |
| Generalplus Technology           | 5        | 0.59%   |
| VIA Technologies                 | 4        | 0.47%   |
| GYROCOM C&C                      | 4        | 0.47%   |
| Unknown                          | 3        | 0.35%   |
| Texas Instruments                | 3        | 0.35%   |
| Cambridge Silicon Radio          | 3        | 0.35%   |
| Yamaha                           | 2        | 0.24%   |
| XMOS                             | 2        | 0.24%   |
| SteelSeries ApS                  | 2        | 0.24%   |
| Samson Technologies              | 2        | 0.24%   |
| Plantronics                      | 2        | 0.24%   |
| JMTek                            | 2        | 0.24%   |
| GN Netcom                        | 2        | 0.24%   |
| BEHRINGER International          | 2        | 0.24%   |
| ASUSTek Computer                 | 2        | 0.24%   |
| TerraTec Electronic              | 1        | 0.12%   |
| TEAC                             | 1        | 0.12%   |
| Silicon Integrated Systems [SiS] | 1        | 0.12%   |
| ROCCAT                           | 1        | 0.12%   |
| Razer USA                        | 1        | 0.12%   |
| PreSonus Audio Electronics       | 1        | 0.12%   |
| Musical Fidelity                 | 1        | 0.12%   |
| Micronas                         | 1        | 0.12%   |
| M-Audio                          | 1        | 0.12%   |
| Kingston Technology              | 1        | 0.12%   |
| Hangzhou Worlde                  | 1        | 0.12%   |
| Focusrite-Novation               | 1        | 0.12%   |
| DisplayLink                      | 1        | 0.12%   |
| Dell                             | 1        | 0.12%   |
| Creative Technology              | 1        | 0.12%   |
| Blue Microphones                 | 1        | 0.12%   |
| B & W Group                      | 1        | 0.12%   |
| AXELVOX                          | 1        | 0.12%   |
| AVID Technology                  | 1        | 0.12%   |
| Audioengine                      | 1        | 0.12%   |
| Alesis                           | 1        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 68       | 6.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 66       | 6.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 49       | 4.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 49       | 4.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 47       | 4.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 27       | 2.75%   |
| Intel Comet Lake PCH cAVS                                                  | 26       | 2.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 26       | 2.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25       | 2.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 25       | 2.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24       | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24       | 2.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 21       | 2.14%   |
| Intel 200 Series PCH HD Audio                                              | 21       | 2.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 20       | 2.04%   |
| AMD FCH Azalia Controller                                                  | 19       | 1.94%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 18       | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17       | 1.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 16       | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14       | 1.43%   |
| AMD Navi 10 HDMI Audio                                                     | 12       | 1.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11       | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 9        | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8        | 0.82%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 8        | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 7        | 0.71%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 7        | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6        | 0.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6        | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                   | 6        | 0.61%   |
| Nvidia MCP61 High Definition Audio                                         | 5        | 0.51%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.51%   |
| Nvidia GF116 High Definition Audio Controller                              | 5        | 0.51%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 0.51%   |
| Generalplus Technology Usb Audio Device                                    | 5        | 0.51%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 5        | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.41%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.41%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 0.41%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 4        | 0.41%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 4        | 0.41%   |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 0.41%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 4        | 0.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4        | 0.41%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.31%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.31%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 115      | 20.91%  |
| Unknown             | 85       | 15.45%  |
| Crucial             | 58       | 10.55%  |
| SK Hynix            | 48       | 8.73%   |
| Corsair             | 48       | 8.73%   |
| Samsung Electronics | 47       | 8.55%   |
| Patriot             | 31       | 5.64%   |
| G.Skill             | 30       | 5.45%   |
| Hikvision           | 20       | 3.64%   |
| Micron Technology   | 15       | 2.73%   |
| A-DATA Technology   | 6        | 1.09%   |
| Team                | 5        | 0.91%   |
| Ramaxel Technology  | 5        | 0.91%   |
| Smart               | 4        | 0.73%   |
| Elpida              | 4        | 0.73%   |
| Nanya Technology    | 3        | 0.55%   |
| AMD                 | 3        | 0.55%   |
| Qimonda             | 2        | 0.36%   |
| Kllisre             | 2        | 0.36%   |
| Kingmax             | 2        | 0.36%   |
| Apacer              | 2        | 0.36%   |
| V-Color             | 1        | 0.18%   |
| Unknown (ABCD)      | 1        | 0.18%   |
| Unifosa             | 1        | 0.18%   |
| TwinMOS             | 1        | 0.18%   |
| Transcend           | 1        | 0.18%   |
| Toshiba             | 1        | 0.18%   |
| TIMETEC             | 1        | 0.18%   |
| SemsoTai            | 1        | 0.18%   |
| OCZ                 | 1        | 0.18%   |
| KETECH              | 1        | 0.18%   |
| Infineon            | 1        | 0.18%   |
| GOODRAM             | 1        | 0.18%   |
| Goldkey             | 1        | 0.18%   |
| GeIL                | 1        | 0.18%   |
| 48spaces            | 1        | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1600MT/s      | 22       | 3.55%   |
| Hikvision RAM HKED4161DAA1D0MA1 16384MB DIMM DDR4 2667MT/s | 20       | 3.23%   |
| Patriot RAM PSD32G13332 2048MB DIMM DDR3 1333MT/s          | 10       | 1.61%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s            | 7        | 1.13%   |
| Kingston RAM 99U5474-025.A00LF 2GB DIMM DDR3 1333MT/s      | 7        | 1.13%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s   | 7        | 1.13%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 6        | 0.97%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 6        | 0.97%   |
| Patriot RAM PSD32G133381 2GB DIMM DDR3 1333MT/s            | 6        | 0.97%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s     | 6        | 0.97%   |
| Crucial RAM CT25664BA160B.D8FE 2GB DIMM DDR3 1600MT/s      | 6        | 0.97%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s      | 6        | 0.97%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 5        | 0.81%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 4        | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 4        | 0.65%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 4        | 0.65%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 4        | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 4        | 0.65%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                    | 4        | 0.65%   |
| Unknown RAM Module 1GB DIMM SDRAM                          | 4        | 0.65%   |
| Kingston RAM 99U5584-017.A00LF 4GB DIMM DDR3 1600MT/s      | 4        | 0.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 4        | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                  | 3        | 0.48%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 3        | 0.48%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 3        | 0.48%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                 | 3        | 0.48%   |
| SK Hynix RAM 4GBPC1600PB N0 4096MB DIMM DDR3 1067MT/s      | 3        | 0.48%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s     | 3        | 0.48%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s        | 3        | 0.48%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 2933MT/s       | 3        | 0.48%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s        | 3        | 0.48%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM 1867MT/s          | 3        | 0.48%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s     | 3        | 0.48%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s   | 3        | 0.48%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s      | 3        | 0.48%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 3        | 0.48%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s     | 3        | 0.48%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s      | 3        | 0.48%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s      | 3        | 0.48%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s      | 3        | 0.48%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s     | 3        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 2        | 0.32%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                 | 2        | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                    | 2        | 0.32%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                   | 2        | 0.32%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 0.32%   |
| Unknown RAM Module 1GB DIMM                                | 2        | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                | 2        | 0.32%   |
| Unknown RAM Module 1024MB DIMM 1066MT/s                    | 2        | 0.32%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s       | 2        | 0.32%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 2        | 0.32%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s    | 2        | 0.32%   |
| SK Hynix RAM HMAA2GU6AJR8N-XN 16GB DIMM DDR4 3200MT/s      | 2        | 0.32%   |
| SK Hynix RAM HMA82GU6JJR8N-VK 16384MB DIMM DDR4 2666MT/s   | 2        | 0.32%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s       | 2        | 0.32%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s       | 2        | 0.32%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s       | 2        | 0.32%   |
| Samsung RAM M378B5773QB0-CK0 2048MB DIMM DDR3 1600MT/s     | 2        | 0.32%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s        | 2        | 0.32%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 2        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 207      | 43.13%  |
| DDR4    | 185      | 38.54%  |
| DDR2    | 29       | 6.04%   |
| Unknown | 29       | 6.04%   |
| SDRAM   | 23       | 4.79%   |
| DDR     | 6        | 1.25%   |
| LPDDR4  | 1        | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 462      | 96.65%  |
| SODIMM  | 14       | 2.93%   |
| RIMM    | 1        | 0.21%   |
| FB-DIMM | 1        | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 153      | 28.65%  |
| 4096  | 135      | 25.28%  |
| 2048  | 104      | 19.48%  |
| 16384 | 79       | 14.79%  |
| 1024  | 31       | 5.81%   |
| 32768 | 20       | 3.75%   |
| 512   | 8        | 1.5%    |
| 256   | 3        | 0.56%   |
| 65536 | 1        | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 129      | 24.57%  |
| 1333    | 83       | 15.81%  |
| 2667    | 47       | 8.95%   |
| 3200    | 35       | 6.67%   |
| 800     | 27       | 5.14%   |
| 2400    | 24       | 4.57%   |
| 2133    | 20       | 3.81%   |
| 3600    | 17       | 3.24%   |
| Unknown | 17       | 3.24%   |
| 2666    | 13       | 2.48%   |
| 667     | 11       | 2.1%    |
| 3000    | 9        | 1.71%   |
| 1067    | 9        | 1.71%   |
| 2933    | 8        | 1.52%   |
| 1866    | 8        | 1.52%   |
| 1066    | 8        | 1.52%   |
| 1867    | 7        | 1.33%   |
| 3466    | 6        | 1.14%   |
| 3400    | 6        | 1.14%   |
| 1800    | 4        | 0.76%   |
| 4333    | 3        | 0.57%   |
| 3733    | 3        | 0.57%   |
| 3100    | 3        | 0.57%   |
| 1400    | 3        | 0.57%   |
| 400     | 3        | 0.57%   |
| 3533    | 2        | 0.38%   |
| 3500    | 2        | 0.38%   |
| 3066    | 2        | 0.38%   |
| 2465    | 2        | 0.38%   |
| 2000    | 2        | 0.38%   |
| 3866    | 1        | 0.19%   |
| 3800    | 1        | 0.19%   |
| 3333    | 1        | 0.19%   |
| 2866    | 1        | 0.19%   |
| 2187    | 1        | 0.19%   |
| 2134    | 1        | 0.19%   |
| 2048    | 1        | 0.19%   |
| 1367    | 1        | 0.19%   |
| 1334    | 1        | 0.19%   |
| 533     | 1        | 0.19%   |
| 333     | 1        | 0.19%   |
| 66      | 1        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 57.14%  |
| Brother Industries  | 3        | 14.29%  |
| Samsung Electronics | 2        | 9.52%   |
| Prolific Technology | 1        | 4.76%   |
| Konica Minolta      | 1        | 4.76%   |
| Dymo-CoStar         | 1        | 4.76%   |
| Canon               | 1        | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP LaserJet M101-M106         | 2        | 9.52%   |
| HP LaserJet 1200              | 2        | 9.52%   |
| HP ENVY 4520 series           | 2        | 9.52%   |
| Samsung SCX-4650 4x21S Series | 1        | 4.76%   |
| Samsung ML-1660 Series        | 1        | 4.76%   |
| Prolific PL2305 Parallel Port | 1        | 4.76%   |
| Konica Minolta bizhub 4402P   | 1        | 4.76%   |
| HP Officejet J4500 series     | 1        | 4.76%   |
| HP LaserJet P1006             | 1        | 4.76%   |
| HP LaserJet 400 M401n         | 1        | 4.76%   |
| HP LaserJet 1150              | 1        | 4.76%   |
| HP LaserJet 1020              | 1        | 4.76%   |
| HP ENVY 5000 series           | 1        | 4.76%   |
| Dymo-CoStar LabelWriter 450   | 1        | 4.76%   |
| Canon iP2700 series           | 1        | 4.76%   |
| Brother MFC-L2710DW series    | 1        | 4.76%   |
| Brother HL-2240 series        | 1        | 4.76%   |
| Brother FAX-2940              | 1        | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 50%     |
| Hewlett-Packard | 1        | 25%     |
| Canon           | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 25%     |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 25%     |
| HP ScanJet 3970c                                         | 1        | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 35       | 42.17%  |
| Microdia                      | 12       | 14.46%  |
| Samsung Electronics           | 5        | 6.02%   |
| Generalplus Technology        | 4        | 4.82%   |
| Z-Star Microelectronics       | 3        | 3.61%   |
| Sunplus Innovation Technology | 2        | 2.41%   |
| Microsoft                     | 2        | 2.41%   |
| Genesys Logic                 | 2        | 2.41%   |
| Creative Technology           | 2        | 2.41%   |
| Apple                         | 2        | 2.41%   |
| Xiongmai                      | 1        | 1.2%    |
| Unknown                       | 1        | 1.2%    |
| SiGma Micro                   | 1        | 1.2%    |
| Razer USA                     | 1        | 1.2%    |
| Novatek Microelectronics      | 1        | 1.2%    |
| Nintendo                      | 1        | 1.2%    |
| Lenovo                        | 1        | 1.2%    |
| Jieli Technology              | 1        | 1.2%    |
| Huawei Technologies           | 1        | 1.2%    |
| Hewlett-Packard               | 1        | 1.2%    |
| eMPIA Technology              | 1        | 1.2%    |
| Chicony Electronics           | 1        | 1.2%    |
| AVerMedia Technologies        | 1        | 1.2%    |
| ARC International             | 1        | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 10       | 12.05%  |
| Samsung Galaxy A5 (MTP)               | 5        | 6.02%   |
| Logitech HD Pro Webcam C920           | 5        | 6.02%   |
| Logitech C922 Pro Stream Webcam       | 5        | 6.02%   |
| Microdia Webcam Vitade AF             | 4        | 4.82%   |
| Microdia USB 2.0 Camera               | 4        | 4.82%   |
| Z-Star Venus USB2.0 Camera            | 3        | 3.61%   |
| Logitech HD Webcam C615               | 3        | 3.61%   |
| Microsoft LifeCam HD-3000             | 2        | 2.41%   |
| Logitech Webcam C170                  | 2        | 2.41%   |
| Logitech HD Webcam C910               | 2        | 2.41%   |
| Generalplus GENERAL WEBCAM            | 2        | 2.41%   |
| Generalplus 808 Camera                | 2        | 2.41%   |
| Apple iPhone 5/5C/5S/6/SE             | 2        | 2.41%   |
| Xiongmai web camera                   | 1        | 1.2%    |
| Unknown Konftel Cam20                 | 1        | 1.2%    |
| Sunplus HD USB Camaer 4K              | 1        | 1.2%    |
| Sunplus HD 720P webcam                | 1        | 1.2%    |
| SiGma Micro WebCam SiGma Micro        | 1        | 1.2%    |
| Razer USA Gaming Webcam [Kiyo]        | 1        | 1.2%    |
| Novatek HP High Definition 2MP Webcam | 1        | 1.2%    |
| Nintendo USB Camera                   | 1        | 1.2%    |
| Microdia Sonix USB 2.0 Camera         | 1        | 1.2%    |
| Microdia Integrated Camera            | 1        | 1.2%    |
| Microdia CyberTrack H6                | 1        | 1.2%    |
| Microdia Camera                       | 1        | 1.2%    |
| Logitech Webcam C925e                 | 1        | 1.2%    |
| Logitech Webcam C600                  | 1        | 1.2%    |
| Logitech Webcam C260                  | 1        | 1.2%    |
| Logitech QuickCam Orbit/Sphere AF     | 1        | 1.2%    |
| Logitech Quickcam 3000 For Business   | 1        | 1.2%    |
| Logitech HD Webcam B910               | 1        | 1.2%    |
| Logitech BRIO                         | 1        | 1.2%    |
| Logitech BCC950 ConferenceCam         | 1        | 1.2%    |
| Lenovo FHD Webcam                     | 1        | 1.2%    |
| Jieli USB PHY 2.0                     | 1        | 1.2%    |
| Huawei UVC Camera                     | 1        | 1.2%    |
| HP Webcam 3110                        | 1        | 1.2%    |
| Genesys Logic USB2.0 UVC PC Camera    | 1        | 1.2%    |
| Genesys Logic Camera                  | 1        | 1.2%    |
| eMPIA M035 Compact Web Cam            | 1        | 1.2%    |
| Creative Live! Cam Sync HD [VF0770]   | 1        | 1.2%    |
| Creative Live! Cam Chat HD [VF0700]   | 1        | 1.2%    |
| Chicony USB2.0 HD UVC WebCam          | 1        | 1.2%    |
| AVerMedia Live Gamer Ultra-Video      | 1        | 1.2%    |
| ARC International Camera              | 1        | 1.2%    |

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
| Yubico.com            | 1        | 33.33%  |
| Gemalto (was Gemplus) | 1        | 33.33%  |
| Chicony Electronics   | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4 CCID                            | 1        | 33.33%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 1        | 33.33%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 313      | 58.07%  |
| 1     | 201      | 37.29%  |
| 2     | 21       | 3.9%    |
| 3     | 3        | 0.56%   |
| 5     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 199      | 86.15%  |
| Unassigned class         | 6        | 2.6%    |
| Net/wireless             | 6        | 2.6%    |
| Sound                    | 5        | 2.16%   |
| Communication controller | 4        | 1.73%   |
| Bluetooth                | 4        | 1.73%   |
| Multimedia controller    | 3        | 1.3%    |
| Network                  | 1        | 0.43%   |
| Dvb card                 | 1        | 0.43%   |
| Card reader              | 1        | 0.43%   |
| Camera                   | 1        | 0.43%   |


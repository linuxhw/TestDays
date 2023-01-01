Linux in Russia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 17376

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MS-B0A41                    | [c69ab6fbe8](https://linux-hardware.org/?probe=c69ab6fbe8) | Jan 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e18f6635d3](https://linux-hardware.org/?probe=e18f6635d3) | Dec 31, 2022 |
| Phoenix       | 945GM                       | [d391eaf6e2](https://linux-hardware.org/?probe=d391eaf6e2) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | [dff8a56537](https://linux-hardware.org/?probe=dff8a56537) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [8fdced7ae8](https://linux-hardware.org/?probe=8fdced7ae8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b0a607e8d8](https://linux-hardware.org/?probe=b0a607e8d8) | Dec 30, 2022 |
| ASRock        | J3455-ITX                   | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | [4ea88219d8](https://linux-hardware.org/?probe=4ea88219d8) | Dec 30, 2022 |
| AZW           | U59                         | [290e34b89a](https://linux-hardware.org/?probe=290e34b89a) | Dec 30, 2022 |
| ASRock        | N68-GS4 FX                  | [379552e4d2](https://linux-hardware.org/?probe=379552e4d2) | Dec 30, 2022 |
| ASUSTek       | PRIME B560M-A               | [ee7c086eb6](https://linux-hardware.org/?probe=ee7c086eb6) | Dec 30, 2022 |
| ASUSTek       | UN65U                       | [b7f1365865](https://linux-hardware.org/?probe=b7f1365865) | Dec 30, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [aa6b264eb4](https://linux-hardware.org/?probe=aa6b264eb4) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [6621ba66ac](https://linux-hardware.org/?probe=6621ba66ac) | Dec 30, 2022 |
| Gigabyte      | B550 GAMING X               | [6e92b3e37b](https://linux-hardware.org/?probe=6e92b3e37b) | Dec 29, 2022 |
| ASUSTek       | H97-PRO                     | [b96b861fd7](https://linux-hardware.org/?probe=b96b861fd7) | Dec 29, 2022 |
| ASRock        | B550 Taichi                 | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| ASUSTek       | PRIME A320M-A               | [2cdb821b42](https://linux-hardware.org/?probe=2cdb821b42) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2L                  | [660194090d](https://linux-hardware.org/?probe=660194090d) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2L                  | [7ba365cac3](https://linux-hardware.org/?probe=7ba365cac3) | Dec 29, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [b3970a8e5a](https://linux-hardware.org/?probe=b3970a8e5a) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [556bc61c51](https://linux-hardware.org/?probe=556bc61c51) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [f0ab6f0649](https://linux-hardware.org/?probe=f0ab6f0649) | Dec 29, 2022 |
| ASRock        | B450 Gaming K4              | [1afc5015f1](https://linux-hardware.org/?probe=1afc5015f1) | Dec 28, 2022 |
| ASUSTek       | PRIME B450M-A               | [422238387a](https://linux-hardware.org/?probe=422238387a) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [519607ec55](https://linux-hardware.org/?probe=519607ec55) | Dec 28, 2022 |
| ASUSTek       | M4A79XTD EVO                | [91c217e497](https://linux-hardware.org/?probe=91c217e497) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| ASUSTek       | M4A785-M                    | [7fb63e4360](https://linux-hardware.org/?probe=7fb63e4360) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| MSI           | B350 PC MATE                | [3b9dbdb180](https://linux-hardware.org/?probe=3b9dbdb180) | Dec 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [1aac1f7eca](https://linux-hardware.org/?probe=1aac1f7eca) | Dec 27, 2022 |
| Gigabyte      | H97-HD3                     | [1707593d6d](https://linux-hardware.org/?probe=1707593d6d) | Dec 27, 2022 |
| ASRock        | H510M-HVS                   | [3733446191](https://linux-hardware.org/?probe=3733446191) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| Pegatron      | APX85-GS                    | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [731f916db1](https://linux-hardware.org/?probe=731f916db1) | Dec 27, 2022 |
| Gigabyte      | GA-890XA-UD3                | [492719506f](https://linux-hardware.org/?probe=492719506f) | Dec 27, 2022 |
| Gigabyte      | H510M S2H V2                | [a47cb3fa7c](https://linux-hardware.org/?probe=a47cb3fa7c) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Gigabyte      | H510M S2H V2                | [7ddc3d0292](https://linux-hardware.org/?probe=7ddc3d0292) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| Gigabyte      | B365M DS3H                  | [f9d83535bd](https://linux-hardware.org/?probe=f9d83535bd) | Dec 26, 2022 |
| Gigabyte      | F2A55M-DS2                  | [735d3cfda2](https://linux-hardware.org/?probe=735d3cfda2) | Dec 26, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | [0fa5809533](https://linux-hardware.org/?probe=0fa5809533) | Dec 26, 2022 |
| Gigabyte      | H61M-S1                     | [384000d018](https://linux-hardware.org/?probe=384000d018) | Dec 25, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [5174af9fdd](https://linux-hardware.org/?probe=5174af9fdd) | Dec 25, 2022 |
| ASRock        | H110 Pro BTC+               | [29311fe64c](https://linux-hardware.org/?probe=29311fe64c) | Dec 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| ASUSTek       | H81M-K                      | [c702bed39d](https://linux-hardware.org/?probe=c702bed39d) | Dec 25, 2022 |
| ASUSTek       | P7H55-M/USB3                | [85b55a267a](https://linux-hardware.org/?probe=85b55a267a) | Dec 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8994b9a877](https://linux-hardware.org/?probe=8994b9a877) | Dec 25, 2022 |
| ASUSTek       | F1A55-M LX R2.0             | [177c5ee2a6](https://linux-hardware.org/?probe=177c5ee2a6) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c545cf1f08](https://linux-hardware.org/?probe=c545cf1f08) | Dec 25, 2022 |
| ASRock        | H110 Pro BTC+               | [90f3fd2f80](https://linux-hardware.org/?probe=90f3fd2f80) | Dec 25, 2022 |
| Huanan        | B660-D4 V1.0                | [2a3d5dc01f](https://linux-hardware.org/?probe=2a3d5dc01f) | Dec 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [f48ac4aa81](https://linux-hardware.org/?probe=f48ac4aa81) | Dec 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b98be1b1e7](https://linux-hardware.org/?probe=b98be1b1e7) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [5368526dc0](https://linux-hardware.org/?probe=5368526dc0) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [fab270a7bf](https://linux-hardware.org/?probe=fab270a7bf) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | [84ea64b29c](https://linux-hardware.org/?probe=84ea64b29c) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | [407f76f02f](https://linux-hardware.org/?probe=407f76f02f) | Dec 24, 2022 |
| ASRock        | B450 Gaming K4              | [bb8b44cf69](https://linux-hardware.org/?probe=bb8b44cf69) | Dec 24, 2022 |
| ASUSTek       | P8H67-M LE                  | [892d40f349](https://linux-hardware.org/?probe=892d40f349) | Dec 24, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [7edfc4df26](https://linux-hardware.org/?probe=7edfc4df26) | Dec 24, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [7f19b0ef63](https://linux-hardware.org/?probe=7f19b0ef63) | Dec 24, 2022 |
| ASUSTek       | P8H67-M LE                  | [7517437358](https://linux-hardware.org/?probe=7517437358) | Dec 24, 2022 |
| Gigabyte      | B660M D2H DDR4              | [c34803fb1e](https://linux-hardware.org/?probe=c34803fb1e) | Dec 24, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [6f60f1b6da](https://linux-hardware.org/?probe=6f60f1b6da) | Dec 24, 2022 |
| Dell          | 0Y5DDC A00                  | [c107bb3a14](https://linux-hardware.org/?probe=c107bb3a14) | Dec 24, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [83203eef25](https://linux-hardware.org/?probe=83203eef25) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| ASUSTek       | P8B75-V                     | [cf3882b3f7](https://linux-hardware.org/?probe=cf3882b3f7) | Dec 24, 2022 |
| Gigabyte      | H55M-S2H                    | [7cecfa756a](https://linux-hardware.org/?probe=7cecfa756a) | Dec 24, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [40c2593694](https://linux-hardware.org/?probe=40c2593694) | Dec 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [81febc2905](https://linux-hardware.org/?probe=81febc2905) | Dec 23, 2022 |
| ASUSTek       | H97-PLUS                    | [0d45265efc](https://linux-hardware.org/?probe=0d45265efc) | Dec 23, 2022 |
| Unknown       | 865GV-ICH5                  | [fe2ef2ef31](https://linux-hardware.org/?probe=fe2ef2ef31) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| ASUSTek       | H81M-C                      | [73dc1109eb](https://linux-hardware.org/?probe=73dc1109eb) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| Gigabyte      | H310M A-CF x.x              | [daf1310bfa](https://linux-hardware.org/?probe=daf1310bfa) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASUSTek       | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| ASUSTek       | P5K                         | [406d3a2d92](https://linux-hardware.org/?probe=406d3a2d92) | Dec 22, 2022 |
| Intel         | X99                         | [24e1c625cb](https://linux-hardware.org/?probe=24e1c625cb) | Dec 22, 2022 |
| Gigabyte      | EP43-DS3                    | [d0f0cd82f9](https://linux-hardware.org/?probe=d0f0cd82f9) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ae98ccd9c2](https://linux-hardware.org/?probe=ae98ccd9c2) | Dec 22, 2022 |
| Unknown       | 865GV-ICH5                  | [f42b7383f4](https://linux-hardware.org/?probe=f42b7383f4) | Dec 22, 2022 |
| ASRock        | A320M Pro4-F                | [4f2abe0c64](https://linux-hardware.org/?probe=4f2abe0c64) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [2683bf55bf](https://linux-hardware.org/?probe=2683bf55bf) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c485d688ad](https://linux-hardware.org/?probe=c485d688ad) | Dec 22, 2022 |
| DEPO Compu... | DPH410S                     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| ASUSTek       | P5K PRO                     | [4088ff40e3](https://linux-hardware.org/?probe=4088ff40e3) | Dec 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10a98289bb](https://linux-hardware.org/?probe=10a98289bb) | Dec 21, 2022 |
| ASUSTek       | VANGUARD B85                | [73560a1b6a](https://linux-hardware.org/?probe=73560a1b6a) | Dec 21, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [b7311f5a21](https://linux-hardware.org/?probe=b7311f5a21) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | [768834619c](https://linux-hardware.org/?probe=768834619c) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [c39538e70e](https://linux-hardware.org/?probe=c39538e70e) | Dec 21, 2022 |
| MSI           | A320M-A PRO                 | [88eb56085f](https://linux-hardware.org/?probe=88eb56085f) | Dec 21, 2022 |
| ASRock        | ALiveXFire-eSATA2           | [e7383e309b](https://linux-hardware.org/?probe=e7383e309b) | Dec 21, 2022 |
| MSI           | B450-A PRO MAX              | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Gigabyte      | EP41-UD3L                   | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Gigabyte      | EP43-S3L                    | [8a24afa21d](https://linux-hardware.org/?probe=8a24afa21d) | Dec 20, 2022 |
| Intel         | X99                         | [ce9b83b781](https://linux-hardware.org/?probe=ce9b83b781) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [e7cfce65f6](https://linux-hardware.org/?probe=e7cfce65f6) | Dec 20, 2022 |
| ASUSTek       | P5QL PRO                    | [44d3238797](https://linux-hardware.org/?probe=44d3238797) | Dec 20, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [65d1b97540](https://linux-hardware.org/?probe=65d1b97540) | Dec 20, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [18ad099caf](https://linux-hardware.org/?probe=18ad099caf) | Dec 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| ASUSTek       | H81M-C                      | [9ae92c3b1e](https://linux-hardware.org/?probe=9ae92c3b1e) | Dec 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [a39b8f54af](https://linux-hardware.org/?probe=a39b8f54af) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [7c854ad5e0](https://linux-hardware.org/?probe=7c854ad5e0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [f82010222c](https://linux-hardware.org/?probe=f82010222c) | Dec 20, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dd024e0315](https://linux-hardware.org/?probe=dd024e0315) | Dec 20, 2022 |
| ASRock        | Z77M                        | [33c2afa3e0](https://linux-hardware.org/?probe=33c2afa3e0) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| Unknown       | Unknown                     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Gigabyte      | B85-HD3                     | [a8d78baa67](https://linux-hardware.org/?probe=a8d78baa67) | Dec 19, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [70b20b876e](https://linux-hardware.org/?probe=70b20b876e) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | [de20614d06](https://linux-hardware.org/?probe=de20614d06) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [66e45d9a82](https://linux-hardware.org/?probe=66e45d9a82) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | [90ea21bd4a](https://linux-hardware.org/?probe=90ea21bd4a) | Dec 19, 2022 |
| ASUSTek       | P7P55D EVO                  | [c8f2df83aa](https://linux-hardware.org/?probe=c8f2df83aa) | Dec 19, 2022 |
| ASRock        | P67 Pro3 SE                 | [5a59282fea](https://linux-hardware.org/?probe=5a59282fea) | Dec 19, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| Dell          | 0Y5DDC A00                  | [aa5228e9b8](https://linux-hardware.org/?probe=aa5228e9b8) | Dec 19, 2022 |
| ASRock        | H110 Pro BTC+               | [b44ba7da8e](https://linux-hardware.org/?probe=b44ba7da8e) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| Intel         | MAHOBAY                     | [7f8c2370d4](https://linux-hardware.org/?probe=7f8c2370d4) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [afcae667f0](https://linux-hardware.org/?probe=afcae667f0) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [8d21cb0063](https://linux-hardware.org/?probe=8d21cb0063) | Dec 18, 2022 |
| Gigabyte      | GA-K8NE                     | [64adeb3e60](https://linux-hardware.org/?probe=64adeb3e60) | Dec 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [626b750c51](https://linux-hardware.org/?probe=626b750c51) | Dec 18, 2022 |
| Biostar       | TB250-BTC                   | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [4760b50d21](https://linux-hardware.org/?probe=4760b50d21) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7964862f29](https://linux-hardware.org/?probe=7964862f29) | Dec 18, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [320ef20ffa](https://linux-hardware.org/?probe=320ef20ffa) | Dec 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | [7e864dc271](https://linux-hardware.org/?probe=7e864dc271) | Dec 18, 2022 |
| Gigabyte      | P41T-D3P                    | [20f90ee21e](https://linux-hardware.org/?probe=20f90ee21e) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| MSI           | MS-B0A41                    | [3eff37d029](https://linux-hardware.org/?probe=3eff37d029) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1212530d94](https://linux-hardware.org/?probe=1212530d94) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [19e8973a92](https://linux-hardware.org/?probe=19e8973a92) | Dec 18, 2022 |
| Gigabyte      | H110N-CF                    | [239dcc2a5c](https://linux-hardware.org/?probe=239dcc2a5c) | Dec 18, 2022 |
| ASUSTek       | A88XM-A                     | [e889711ed9](https://linux-hardware.org/?probe=e889711ed9) | Dec 17, 2022 |
| ASUSTek       | M2N-XE                      | [5cf5b3eb1b](https://linux-hardware.org/?probe=5cf5b3eb1b) | Dec 17, 2022 |
| Gigabyte      | X570S AERO G                | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [43d229d12e](https://linux-hardware.org/?probe=43d229d12e) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a8936bc5e3](https://linux-hardware.org/?probe=a8936bc5e3) | Dec 17, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [74133cd0bd](https://linux-hardware.org/?probe=74133cd0bd) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [f9f06d0bcb](https://linux-hardware.org/?probe=f9f06d0bcb) | Dec 17, 2022 |
| Gigabyte      | M61SME-S2                   | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5f8287cae9](https://linux-hardware.org/?probe=5f8287cae9) | Dec 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0eb4a7c919](https://linux-hardware.org/?probe=0eb4a7c919) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | [d34f278afd](https://linux-hardware.org/?probe=d34f278afd) | Dec 17, 2022 |
| Gigabyte      | 970A-DS3P                   | [f0303dc0a9](https://linux-hardware.org/?probe=f0303dc0a9) | Dec 17, 2022 |
| Gigabyte      | H81-D3                      | [547126e9e7](https://linux-hardware.org/?probe=547126e9e7) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| HP            | 18E6                        | [62ae9ced0f](https://linux-hardware.org/?probe=62ae9ced0f) | Dec 16, 2022 |
| Biostar       | A10N-8800E                  | [bc96dc9caf](https://linux-hardware.org/?probe=bc96dc9caf) | Dec 16, 2022 |
| Gigabyte      | H110M-M2-CF                 | [11c0643905](https://linux-hardware.org/?probe=11c0643905) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Graviton      | DMB-H510-MCA01              | [702f634fc4](https://linux-hardware.org/?probe=702f634fc4) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| Gigabyte      | P75-D3                      | [32b4b4d664](https://linux-hardware.org/?probe=32b4b4d664) | Dec 16, 2022 |
| MSI           | B450I GAMING PLUS AC        | [59a22369a1](https://linux-hardware.org/?probe=59a22369a1) | Dec 16, 2022 |
| Huanan        | X99-QD4 V1.0                | [a959e56dc8](https://linux-hardware.org/?probe=a959e56dc8) | Dec 15, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [62395615bf](https://linux-hardware.org/?probe=62395615bf) | Dec 15, 2022 |
| ASRock        | X570 Pro4                   | [713a2bcaf4](https://linux-hardware.org/?probe=713a2bcaf4) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3807037a5c](https://linux-hardware.org/?probe=3807037a5c) | Dec 15, 2022 |
| MSI           | K9N6PGM2-V2                 | [c25f374572](https://linux-hardware.org/?probe=c25f374572) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [6367cb9215](https://linux-hardware.org/?probe=6367cb9215) | Dec 15, 2022 |
| ASRock        | H110 Pro BTC+               | [9821ed300c](https://linux-hardware.org/?probe=9821ed300c) | Dec 15, 2022 |
| ASRock        | A520M Pro4                  | [9a6fcc5f1b](https://linux-hardware.org/?probe=9a6fcc5f1b) | Dec 15, 2022 |
| MSI           | B450-A PRO MAX              | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [766e33e4fb](https://linux-hardware.org/?probe=766e33e4fb) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H410M H V3                  | [cf668e53f4](https://linux-hardware.org/?probe=cf668e53f4) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [db904895cc](https://linux-hardware.org/?probe=db904895cc) | Dec 15, 2022 |
| Gigabyte      | B360M D3H-CF                | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ASUSTek       | F2A55-M LE                  | [f4c6e3c225](https://linux-hardware.org/?probe=f4c6e3c225) | Dec 14, 2022 |
| Gigabyte      | H110M-S2-CF                 | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Gigabyte      | H77N-WIFI                   | [5093772c0f](https://linux-hardware.org/?probe=5093772c0f) | Dec 14, 2022 |
| Intel         | X79v2.72 KD V2.0            | [0e58af2a59](https://linux-hardware.org/?probe=0e58af2a59) | Dec 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c337db1381](https://linux-hardware.org/?probe=c337db1381) | Dec 14, 2022 |
| ASRock        | M3A770DE                    | [2e6b1f9c2d](https://linux-hardware.org/?probe=2e6b1f9c2d) | Dec 13, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [22431e9b10](https://linux-hardware.org/?probe=22431e9b10) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [0e9eba0773](https://linux-hardware.org/?probe=0e9eba0773) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [af674c6b1b](https://linux-hardware.org/?probe=af674c6b1b) | Dec 13, 2022 |
| AZW           | U59                         | [fd5ccbfbd2](https://linux-hardware.org/?probe=fd5ccbfbd2) | Dec 13, 2022 |
| Gigabyte      | Z590 UD AC                  | [895bd1b0b2](https://linux-hardware.org/?probe=895bd1b0b2) | Dec 13, 2022 |
| ASUSTek       | PRIME H270-PRO              | [dc7d6ae170](https://linux-hardware.org/?probe=dc7d6ae170) | Dec 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Intel         | X79v2.72 KD V2.0            | [476f1e7cad](https://linux-hardware.org/?probe=476f1e7cad) | Dec 12, 2022 |
| MSI           | MEG B550 UNIFY              | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| Gigabyte      | B450 GAMING X               | [8918608744](https://linux-hardware.org/?probe=8918608744) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [2e0158ba73](https://linux-hardware.org/?probe=2e0158ba73) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [c6e03bcd07](https://linux-hardware.org/?probe=c6e03bcd07) | Dec 12, 2022 |
| Gigabyte      | B450M S2H                   | [c5220a0b87](https://linux-hardware.org/?probe=c5220a0b87) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| MSI           | Z97-G43 GAMING              | [982bf94727](https://linux-hardware.org/?probe=982bf94727) | Dec 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [7d4b5e1c20](https://linux-hardware.org/?probe=7d4b5e1c20) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f0fa1101ce](https://linux-hardware.org/?probe=f0fa1101ce) | Dec 11, 2022 |
| Gigabyte      | Z77-DS3H                    | [dbd992f05e](https://linux-hardware.org/?probe=dbd992f05e) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [f883834ef1](https://linux-hardware.org/?probe=f883834ef1) | Dec 11, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [9f72d262ef](https://linux-hardware.org/?probe=9f72d262ef) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [8bd005fd95](https://linux-hardware.org/?probe=8bd005fd95) | Dec 11, 2022 |
| ASUSTek       | PRIME B360M-K               | [aac6da2dfb](https://linux-hardware.org/?probe=aac6da2dfb) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| Gigabyte      | H77-DS3H                    | [4c52e333dd](https://linux-hardware.org/?probe=4c52e333dd) | Dec 10, 2022 |
| ASRock        | H81M-HDS R2.0               | [e3c2a2bc54](https://linux-hardware.org/?probe=e3c2a2bc54) | Dec 10, 2022 |
| ASRock        | Z270 Pro4                   | [9810ecf266](https://linux-hardware.org/?probe=9810ecf266) | Dec 10, 2022 |
| Intel         | D2500HN AAG81480-500        | [0963fa0173](https://linux-hardware.org/?probe=0963fa0173) | Dec 10, 2022 |
| ASUSTek       | PRIME B350M-A               | [619a4c2f87](https://linux-hardware.org/?probe=619a4c2f87) | Dec 10, 2022 |
| ASRock        | 760GM-HDV                   | [bbd75ce275](https://linux-hardware.org/?probe=bbd75ce275) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [941668ad89](https://linux-hardware.org/?probe=941668ad89) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [fc07cad186](https://linux-hardware.org/?probe=fc07cad186) | Dec 10, 2022 |
| ASUSTek       | Z170-P                      | [5180b907e3](https://linux-hardware.org/?probe=5180b907e3) | Dec 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [d11e502254](https://linux-hardware.org/?probe=d11e502254) | Dec 10, 2022 |
| HP            | 158A                        | [ebcf08f784](https://linux-hardware.org/?probe=ebcf08f784) | Dec 10, 2022 |
| ASRock        | H97 Anniversary             | [3f7aa1b6de](https://linux-hardware.org/?probe=3f7aa1b6de) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [f064a744ba](https://linux-hardware.org/?probe=f064a744ba) | Dec 10, 2022 |
| ASUSTek       | Z170-A                      | [c9df3386c5](https://linux-hardware.org/?probe=c9df3386c5) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Gigabyte      | H61N-USB3                   | [9a8885a88d](https://linux-hardware.org/?probe=9a8885a88d) | Dec 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | [75f1600dba](https://linux-hardware.org/?probe=75f1600dba) | Dec 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ed30003f61](https://linux-hardware.org/?probe=ed30003f61) | Dec 09, 2022 |
| Gigabyte      | B365M DS3H                  | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| Gigabyte      | D425TUD                     | [4d8c330a78](https://linux-hardware.org/?probe=4d8c330a78) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [b4bd04a5a0](https://linux-hardware.org/?probe=b4bd04a5a0) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [56a6a749bb](https://linux-hardware.org/?probe=56a6a749bb) | Dec 09, 2022 |
| ASRock        | H110M-DGS                   | [2311fd9c2f](https://linux-hardware.org/?probe=2311fd9c2f) | Dec 09, 2022 |
| ASUSTek       | M2N-X                       | [63a0188273](https://linux-hardware.org/?probe=63a0188273) | Dec 09, 2022 |
| Gigabyte      | G31M-S2L                    | [05707c88e0](https://linux-hardware.org/?probe=05707c88e0) | Dec 08, 2022 |
| Gigabyte      | H81M-S1                     | [c2ba58af35](https://linux-hardware.org/?probe=c2ba58af35) | Dec 08, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [4462cb3156](https://linux-hardware.org/?probe=4462cb3156) | Dec 08, 2022 |
| MSI           | PH61-SP35                   | [c3f5b1ddd3](https://linux-hardware.org/?probe=c3f5b1ddd3) | Dec 08, 2022 |
| Gigabyte      | P31-ES3G                    | [21c291e1e2](https://linux-hardware.org/?probe=21c291e1e2) | Dec 08, 2022 |
| Huanan        | X99 F8D V2.2                | [d960add854](https://linux-hardware.org/?probe=d960add854) | Dec 08, 2022 |
| ASRock        | H470M-HVS                   | [2f4b3b1185](https://linux-hardware.org/?probe=2f4b3b1185) | Dec 08, 2022 |
| ASUSTek       | P5W DH Deluxe               | [bedb81f629](https://linux-hardware.org/?probe=bedb81f629) | Dec 08, 2022 |
| ASUSTek       | H110-PLUS                   | [57e0d3651c](https://linux-hardware.org/?probe=57e0d3651c) | Dec 08, 2022 |
| ASUSTek       | H81M-R                      | [0858714315](https://linux-hardware.org/?probe=0858714315) | Dec 08, 2022 |
| Aquarius      | AQB560M                     | [3ac41202cf](https://linux-hardware.org/?probe=3ac41202cf) | Dec 08, 2022 |
| Gigabyte      | Z370M D3H-CF                | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| eMachines     | ET1350                      | [2d05a7a068](https://linux-hardware.org/?probe=2d05a7a068) | Dec 07, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [038581b13f](https://linux-hardware.org/?probe=038581b13f) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | [c4f63ee5a1](https://linux-hardware.org/?probe=c4f63ee5a1) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | [ae67b039af](https://linux-hardware.org/?probe=ae67b039af) | Dec 06, 2022 |
| HC Technol... | HCAR4000-MI                 | [596c3680f3](https://linux-hardware.org/?probe=596c3680f3) | Dec 06, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [0327ae6d81](https://linux-hardware.org/?probe=0327ae6d81) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K               | [7e82777792](https://linux-hardware.org/?probe=7e82777792) | Dec 06, 2022 |
| Gigabyte      | GA-MA770-ES3                | [70c1a43352](https://linux-hardware.org/?probe=70c1a43352) | Dec 06, 2022 |
| ASUSTek       | H170-PRO                    | [37cf939cbd](https://linux-hardware.org/?probe=37cf939cbd) | Dec 06, 2022 |
| ASUSTek       | M2N-XE                      | [663b3c7870](https://linux-hardware.org/?probe=663b3c7870) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K               | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | 0XHGV1 A00                  | [9b9778c525](https://linux-hardware.org/?probe=9b9778c525) | Dec 06, 2022 |
| ASUSTek       | P7H55-M                     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| ASRock        | P67 Pro                     | [74b28c3c76](https://linux-hardware.org/?probe=74b28c3c76) | Dec 06, 2022 |
| ASRock        | B450M-HDV                   | [afeed5f423](https://linux-hardware.org/?probe=afeed5f423) | Dec 05, 2022 |
| Gigabyte      | 970A-DS3P                   | [517e06781a](https://linux-hardware.org/?probe=517e06781a) | Dec 05, 2022 |
| MSI           | H110M PRO-VD                | [64c80c03cf](https://linux-hardware.org/?probe=64c80c03cf) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [76ce7610ea](https://linux-hardware.org/?probe=76ce7610ea) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| Gigabyte      | B450 GAMING X               | [c8b886d9bf](https://linux-hardware.org/?probe=c8b886d9bf) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [0301ad14ee](https://linux-hardware.org/?probe=0301ad14ee) | Dec 05, 2022 |
| ASUSTek       | A55BM-K                     | [e78b25a518](https://linux-hardware.org/?probe=e78b25a518) | Dec 05, 2022 |
| MSI           | H97 PC Mate                 | [b8081159ab](https://linux-hardware.org/?probe=b8081159ab) | Dec 05, 2022 |
| ASRock        | J4205-ITX                   | [f5eb647cc9](https://linux-hardware.org/?probe=f5eb647cc9) | Dec 04, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [930b8d0ff2](https://linux-hardware.org/?probe=930b8d0ff2) | Dec 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [10dd0b119a](https://linux-hardware.org/?probe=10dd0b119a) | Dec 04, 2022 |
| Unknown       | Unknown                     | [bdf0020add](https://linux-hardware.org/?probe=bdf0020add) | Dec 04, 2022 |
| HP            | 2AAC                        | [a6fb7751ed](https://linux-hardware.org/?probe=a6fb7751ed) | Dec 04, 2022 |
| Intel         | DG41CN AAE82429-102         | [8d5cd3253c](https://linux-hardware.org/?probe=8d5cd3253c) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [d3c99c8d63](https://linux-hardware.org/?probe=d3c99c8d63) | Dec 04, 2022 |
| Intel         | D2500HN AAG34776-404        | [b1ccefe421](https://linux-hardware.org/?probe=b1ccefe421) | Dec 04, 2022 |
| ASUSTek       | H81M-C                      | [0218d4ec25](https://linux-hardware.org/?probe=0218d4ec25) | Dec 03, 2022 |
| ASUSTek       | P5K                         | [c05392b19e](https://linux-hardware.org/?probe=c05392b19e) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-A               | [91d50f0379](https://linux-hardware.org/?probe=91d50f0379) | Dec 03, 2022 |
| Gigabyte      | P35-DS3                     | [f4be331a61](https://linux-hardware.org/?probe=f4be331a61) | Dec 03, 2022 |
| ASUSTek       | H81M-C                      | [ea7168ab4c](https://linux-hardware.org/?probe=ea7168ab4c) | Dec 03, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [1d881e7756](https://linux-hardware.org/?probe=1d881e7756) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [78746e7632](https://linux-hardware.org/?probe=78746e7632) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [ead86b243b](https://linux-hardware.org/?probe=ead86b243b) | Dec 03, 2022 |
| ASRock        | K10N78D                     | [7d0d581c7a](https://linux-hardware.org/?probe=7d0d581c7a) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [f1e82e8a2a](https://linux-hardware.org/?probe=f1e82e8a2a) | Dec 03, 2022 |
| ASRock        | H110 Pro BTC+               | [d485a9f321](https://linux-hardware.org/?probe=d485a9f321) | Dec 03, 2022 |
| Gigabyte      | 970A-UD3P                   | [7bb879efed](https://linux-hardware.org/?probe=7bb879efed) | Dec 03, 2022 |
| Gigabyte      | MZBSWMP-00                  | [76ba1ef6f2](https://linux-hardware.org/?probe=76ba1ef6f2) | Dec 03, 2022 |
| MSI           | P67S-C43                    | [9674663124](https://linux-hardware.org/?probe=9674663124) | Dec 03, 2022 |
| ASUSTek       | Z170M-PLUS                  | [a39dbe7189](https://linux-hardware.org/?probe=a39dbe7189) | Dec 03, 2022 |
| Gigabyte      | H61M-D2-B3                  | [0cc7f26d32](https://linux-hardware.org/?probe=0cc7f26d32) | Dec 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| Intel         | JSL MRD                     | [1a63097a67](https://linux-hardware.org/?probe=1a63097a67) | Dec 02, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5c0129ab3f](https://linux-hardware.org/?probe=5c0129ab3f) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [eaaeeb57fe](https://linux-hardware.org/?probe=eaaeeb57fe) | Dec 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| 3Q            | TD2500G-P-Q3 A01            | [46626558f6](https://linux-hardware.org/?probe=46626558f6) | Dec 01, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [16680c5211](https://linux-hardware.org/?probe=16680c5211) | Dec 01, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9866b7f07f](https://linux-hardware.org/?probe=9866b7f07f) | Dec 01, 2022 |
| Gigabyte      | B450 GAMING X               | [ff5aef2f59](https://linux-hardware.org/?probe=ff5aef2f59) | Dec 01, 2022 |
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| MSI           | H81M-E33                    | [aa874580d3](https://linux-hardware.org/?probe=aa874580d3) | Dec 01, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [010349b87b](https://linux-hardware.org/?probe=010349b87b) | Dec 01, 2022 |
| Gigabyte      | GA-990FXA-UD7               | [e300be2b5e](https://linux-hardware.org/?probe=e300be2b5e) | Dec 01, 2022 |
| ASUSTek       | P5B                         | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | P8H77-V LE                  | [d82ed03dd9](https://linux-hardware.org/?probe=d82ed03dd9) | Dec 01, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4ae619c728](https://linux-hardware.org/?probe=4ae619c728) | Dec 01, 2022 |
| Graviton      | DMB-H510-MCA01              | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| ASUSTek       | H81M-C                      | [458ea4bd06](https://linux-hardware.org/?probe=458ea4bd06) | Nov 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [99c33f6741](https://linux-hardware.org/?probe=99c33f6741) | Nov 29, 2022 |
| HP            | 8437                        | [c5bbfc32f6](https://linux-hardware.org/?probe=c5bbfc32f6) | Nov 29, 2022 |
| Lenovo        | 3162 SDK0J40697 WIN 3305... | [296ceaab80](https://linux-hardware.org/?probe=296ceaab80) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| ASRock        | N68C-S UCC                  | [c7bff3d908](https://linux-hardware.org/?probe=c7bff3d908) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| Dell          | 0Y5DDC A00                  | [5d4811b390](https://linux-hardware.org/?probe=5d4811b390) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [66fe0c3ddf](https://linux-hardware.org/?probe=66fe0c3ddf) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| ECS           | BSWI-D2                     | [b7e4fbdd31](https://linux-hardware.org/?probe=b7e4fbdd31) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [262228b1fb](https://linux-hardware.org/?probe=262228b1fb) | Nov 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | [be98ffe55b](https://linux-hardware.org/?probe=be98ffe55b) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Intel         | X79G V2.x                   | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Gigabyte      | B365M DS3H                  | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [245ea45167](https://linux-hardware.org/?probe=245ea45167) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Gigabyte      | B550 GAMING X               | [f8979201eb](https://linux-hardware.org/?probe=f8979201eb) | Nov 27, 2022 |
| ASUSTek       | P7H55-M                     | [e5ac492508](https://linux-hardware.org/?probe=e5ac492508) | Nov 27, 2022 |
| Unknown       | Unknown                     | [1a24753132](https://linux-hardware.org/?probe=1a24753132) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [3fda27c7b6](https://linux-hardware.org/?probe=3fda27c7b6) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e6a6d0affd](https://linux-hardware.org/?probe=e6a6d0affd) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [2a77cd8415](https://linux-hardware.org/?probe=2a77cd8415) | Nov 27, 2022 |
| ASUSTek       | PRIME B250M-K               | [73b4c53383](https://linux-hardware.org/?probe=73b4c53383) | Nov 27, 2022 |
| Koloe         | X58                         | [8b80e1a74c](https://linux-hardware.org/?probe=8b80e1a74c) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | [ff31791cfb](https://linux-hardware.org/?probe=ff31791cfb) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | [e09f910876](https://linux-hardware.org/?probe=e09f910876) | Nov 27, 2022 |
| ASRock        | H110M-DGS                   | [6667ba2bc2](https://linux-hardware.org/?probe=6667ba2bc2) | Nov 27, 2022 |
| MACHINIST     | X99-RS9 V3.1                | [86cead0335](https://linux-hardware.org/?probe=86cead0335) | Nov 27, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [4fa4184bfd](https://linux-hardware.org/?probe=4fa4184bfd) | Nov 26, 2022 |
| MSI           | J1800I                      | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | [0f4c0786c2](https://linux-hardware.org/?probe=0f4c0786c2) | Nov 26, 2022 |
| ASUSTek       | H110M-R                     | [f35782a773](https://linux-hardware.org/?probe=f35782a773) | Nov 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [f368bfcbe2](https://linux-hardware.org/?probe=f368bfcbe2) | Nov 26, 2022 |
| Gigabyte      | B560 HD3                    | [f7915b54fb](https://linux-hardware.org/?probe=f7915b54fb) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| ASUSTek       | P8H77-V LE                  | [c17b2fcd65](https://linux-hardware.org/?probe=c17b2fcd65) | Nov 26, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| MSI           | K9AG Neo2                   | [a57a6f079b](https://linux-hardware.org/?probe=a57a6f079b) | Nov 25, 2022 |
| ASRock        | H55M-LE                     | [75b9a8fb03](https://linux-hardware.org/?probe=75b9a8fb03) | Nov 25, 2022 |
| Gigabyte      | X570S UD                    | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| JGINYUE       | B660M-VDH                   | [bd879c87f8](https://linux-hardware.org/?probe=bd879c87f8) | Nov 25, 2022 |
| ASUSTek       | P5K                         | [87e7a3c0d0](https://linux-hardware.org/?probe=87e7a3c0d0) | Nov 25, 2022 |
| ASUSTek       | P8H61-MX                    | [d2e3977693](https://linux-hardware.org/?probe=d2e3977693) | Nov 25, 2022 |
| ASRock        | H110 Pro BTC+               | [db556f793b](https://linux-hardware.org/?probe=db556f793b) | Nov 25, 2022 |
| Gigabyte      | B250-FinTech-CF             | [fcc81ea02b](https://linux-hardware.org/?probe=fcc81ea02b) | Nov 24, 2022 |
| ASUSTek       | PRIME Z590-P                | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| MSI           | TRX40 PRO WIFI              | [3617f324a2](https://linux-hardware.org/?probe=3617f324a2) | Nov 24, 2022 |
| ASUSTek       | P5Q3                        | [655065ee03](https://linux-hardware.org/?probe=655065ee03) | Nov 24, 2022 |
| ASUSTek       | P5P43TD                     | [324669845a](https://linux-hardware.org/?probe=324669845a) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [8a5a155a45](https://linux-hardware.org/?probe=8a5a155a45) | Nov 24, 2022 |
| ASRock        | B560M-ITX/ac                | [3e1bbe410c](https://linux-hardware.org/?probe=3e1bbe410c) | Nov 24, 2022 |
| ASUSTek       | P5KPL-VM                    | [4e15e21f75](https://linux-hardware.org/?probe=4e15e21f75) | Nov 24, 2022 |
| ASUSTek       | H81M-C                      | [e892605084](https://linux-hardware.org/?probe=e892605084) | Nov 24, 2022 |
| ASUSTek       | P5K Premium                 | [5ff50a49ba](https://linux-hardware.org/?probe=5ff50a49ba) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [a17992aaa3](https://linux-hardware.org/?probe=a17992aaa3) | Nov 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [4617b6803a](https://linux-hardware.org/?probe=4617b6803a) | Nov 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e83d79d385](https://linux-hardware.org/?probe=e83d79d385) | Nov 23, 2022 |
| ASUSTek       | P8Z68-V LX                  | [7153762b68](https://linux-hardware.org/?probe=7153762b68) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [64728372e9](https://linux-hardware.org/?probe=64728372e9) | Nov 23, 2022 |
| Gigabyte      | G31M-ES2L                   | [e8ab5ad410](https://linux-hardware.org/?probe=e8ab5ad410) | Nov 23, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [3a36391d83](https://linux-hardware.org/?probe=3a36391d83) | Nov 22, 2022 |
| Gigabyte      | B450 GAMING X               | [c427f12dca](https://linux-hardware.org/?probe=c427f12dca) | Nov 22, 2022 |
| Gigabyte      | 970A-UD3P                   | [2cd736b247](https://linux-hardware.org/?probe=2cd736b247) | Nov 22, 2022 |
| ASUSTek       | PRIME B450M-A               | [49cb3f2e52](https://linux-hardware.org/?probe=49cb3f2e52) | Nov 22, 2022 |
| Biostar       | G41D3+                      | [6ce48937fe](https://linux-hardware.org/?probe=6ce48937fe) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [6d50058ef8](https://linux-hardware.org/?probe=6d50058ef8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [f6a783a27a](https://linux-hardware.org/?probe=f6a783a27a) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [423fbc1fa0](https://linux-hardware.org/?probe=423fbc1fa0) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [debc5b7ab9](https://linux-hardware.org/?probe=debc5b7ab9) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [dc53077baa](https://linux-hardware.org/?probe=dc53077baa) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [856bb3def2](https://linux-hardware.org/?probe=856bb3def2) | Nov 22, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [d140a0f503](https://linux-hardware.org/?probe=d140a0f503) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ee55108218](https://linux-hardware.org/?probe=ee55108218) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ec03d1b050](https://linux-hardware.org/?probe=ec03d1b050) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [1f2a4089cc](https://linux-hardware.org/?probe=1f2a4089cc) | Nov 22, 2022 |
| Intel         | JSL MRD                     | [31ffd9d911](https://linux-hardware.org/?probe=31ffd9d911) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [4190bbb2d8](https://linux-hardware.org/?probe=4190bbb2d8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [570a11d74b](https://linux-hardware.org/?probe=570a11d74b) | Nov 22, 2022 |
| Gigabyte      | G41M-ES2L                   | [404927f4cc](https://linux-hardware.org/?probe=404927f4cc) | Nov 22, 2022 |
| Dell          | 0Y5DDC A00                  | [37808c6686](https://linux-hardware.org/?probe=37808c6686) | Nov 22, 2022 |
| ASRock        | H55M-LE                     | [206082ac3f](https://linux-hardware.org/?probe=206082ac3f) | Nov 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [2575d2aab2](https://linux-hardware.org/?probe=2575d2aab2) | Nov 22, 2022 |
| Gigabyte      | B75M-D3V                    | [06396e3088](https://linux-hardware.org/?probe=06396e3088) | Nov 21, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| Gigabyte      | B365M DS3H                  | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | [a81c612515](https://linux-hardware.org/?probe=a81c612515) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | [ebc5b13d4e](https://linux-hardware.org/?probe=ebc5b13d4e) | Nov 21, 2022 |
| Biostar       | G41D3+                      | [d1d42fec13](https://linux-hardware.org/?probe=d1d42fec13) | Nov 21, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| Intel         | DG45ID AAE27729-310         | [81ecca3cd1](https://linux-hardware.org/?probe=81ecca3cd1) | Nov 20, 2022 |
| ASUSTek       | M4A785T-M                   | [451b8a6b52](https://linux-hardware.org/?probe=451b8a6b52) | Nov 20, 2022 |
| Gigabyte      | Z77X-D3H                    | [1702f14317](https://linux-hardware.org/?probe=1702f14317) | Nov 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [122a37af55](https://linux-hardware.org/?probe=122a37af55) | Nov 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [910d921a9d](https://linux-hardware.org/?probe=910d921a9d) | Nov 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | [b133dcd886](https://linux-hardware.org/?probe=b133dcd886) | Nov 20, 2022 |
| ASUSTek       | P7H55                       | [aaaefec31e](https://linux-hardware.org/?probe=aaaefec31e) | Nov 20, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [64953143a6](https://linux-hardware.org/?probe=64953143a6) | Nov 20, 2022 |
| ASRock        | P43ME                       | [3b90870750](https://linux-hardware.org/?probe=3b90870750) | Nov 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [5cf9d6d04e](https://linux-hardware.org/?probe=5cf9d6d04e) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [e8171566d3](https://linux-hardware.org/?probe=e8171566d3) | Nov 19, 2022 |
| ASUSTek       | P5K                         | [44b338a17d](https://linux-hardware.org/?probe=44b338a17d) | Nov 19, 2022 |
| Gigabyte      | G31M-ES2L                   | [3e3d8f727c](https://linux-hardware.org/?probe=3e3d8f727c) | Nov 19, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| ASUSTek       | P5KPL/1600                  | [b2e20d7f28](https://linux-hardware.org/?probe=b2e20d7f28) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Dell          | 0RY007                      | [d11a712f82](https://linux-hardware.org/?probe=d11a712f82) | Nov 18, 2022 |
| ASUSTek       | PRIME Z370-P                | [65abbfb38e](https://linux-hardware.org/?probe=65abbfb38e) | Nov 18, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Unknown       | Unknown                     | [53f563177d](https://linux-hardware.org/?probe=53f563177d) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c695addaa3](https://linux-hardware.org/?probe=c695addaa3) | Nov 18, 2022 |
| HP            | 8906 SMVB                   | [f644eba622](https://linux-hardware.org/?probe=f644eba622) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | [ceafbe876d](https://linux-hardware.org/?probe=ceafbe876d) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | [f6f8ae996d](https://linux-hardware.org/?probe=f6f8ae996d) | Nov 18, 2022 |
| Unknown       | P43Twins1600                | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASUSTek       | P8B75-V                     | [6f3b172132](https://linux-hardware.org/?probe=6f3b172132) | Nov 18, 2022 |
| MSI           | H110M PRO-VH PLUS           | [54f40f8c4b](https://linux-hardware.org/?probe=54f40f8c4b) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Dell          | 0Y5DDC A00                  | [99aed6e6d2](https://linux-hardware.org/?probe=99aed6e6d2) | Nov 17, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| Gigabyte      | A520M H                     | [d353571eef](https://linux-hardware.org/?probe=d353571eef) | Nov 17, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [814b71a20c](https://linux-hardware.org/?probe=814b71a20c) | Nov 17, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [f9da339cc7](https://linux-hardware.org/?probe=f9da339cc7) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| ASUSTek       | Z170-P                      | [735035876a](https://linux-hardware.org/?probe=735035876a) | Nov 17, 2022 |
| MSI           | B450M MORTAR MAX            | [2ea755455d](https://linux-hardware.org/?probe=2ea755455d) | Nov 16, 2022 |
| Biostar       | TH67XE                      | [47da767a5a](https://linux-hardware.org/?probe=47da767a5a) | Nov 16, 2022 |
| MSI           | H61M-P32/W8                 | [82cba9e87c](https://linux-hardware.org/?probe=82cba9e87c) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2                    | [757a1066ff](https://linux-hardware.org/?probe=757a1066ff) | Nov 16, 2022 |
| ASRock        | H310CM-DVS                  | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| Gigabyte      | P75-D3                      | [02bdf99508](https://linux-hardware.org/?probe=02bdf99508) | Nov 16, 2022 |
| ASRock        | J3455-ITX                   | [71c99edeb1](https://linux-hardware.org/?probe=71c99edeb1) | Nov 16, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [b0c0ad46de](https://linux-hardware.org/?probe=b0c0ad46de) | Nov 16, 2022 |
| ASUSTek       | B75M-A                      | [087a904af2](https://linux-hardware.org/?probe=087a904af2) | Nov 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ccf8236d38](https://linux-hardware.org/?probe=ccf8236d38) | Nov 16, 2022 |
| ASUSTek       | Z87-K                       | [39078e426c](https://linux-hardware.org/?probe=39078e426c) | Nov 16, 2022 |
| Gigabyte      | H110M-S2V-CF                | [74cdb80f42](https://linux-hardware.org/?probe=74cdb80f42) | Nov 16, 2022 |
| ASRock        | N68C-GS FX                  | [e7d93e8540](https://linux-hardware.org/?probe=e7d93e8540) | Nov 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| ASRock        | N68C-GS FX                  | [c67fea651e](https://linux-hardware.org/?probe=c67fea651e) | Nov 15, 2022 |
| ASRock        | N68-GS4 FX                  | [c651e62593](https://linux-hardware.org/?probe=c651e62593) | Nov 15, 2022 |
| ASRock        | H470M-HVS                   | [e69c2f0da4](https://linux-hardware.org/?probe=e69c2f0da4) | Nov 15, 2022 |
| ASRock        | B150M-HDS                   | [032d8f7c3c](https://linux-hardware.org/?probe=032d8f7c3c) | Nov 15, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| Unknown       | Intel X79                   | [61483ea15b](https://linux-hardware.org/?probe=61483ea15b) | Nov 14, 2022 |
| Graviton      | DMB-A520-MCA01              | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| Gigabyte      | B450M DS3H V2               | [dc808c4131](https://linux-hardware.org/?probe=dc808c4131) | Nov 14, 2022 |
| Gigabyte      | P75-D3                      | [37f9da1b7f](https://linux-hardware.org/?probe=37f9da1b7f) | Nov 14, 2022 |
| HP            | 2179                        | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | [191fa275ad](https://linux-hardware.org/?probe=191fa275ad) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | [0f8a90fef7](https://linux-hardware.org/?probe=0f8a90fef7) | Nov 14, 2022 |
| Gigabyte      | H77-DS3H                    | [f28540c049](https://linux-hardware.org/?probe=f28540c049) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [53a532435e](https://linux-hardware.org/?probe=53a532435e) | Nov 14, 2022 |
| Pegatron      | 2A94h                       | [5ebd2a4bf4](https://linux-hardware.org/?probe=5ebd2a4bf4) | Nov 13, 2022 |
| Gigabyte      | H110M-M2-CF                 | [aedb84820e](https://linux-hardware.org/?probe=aedb84820e) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASUSTek       | F2A85-V PRO                 | [0127d7b1cd](https://linux-hardware.org/?probe=0127d7b1cd) | Nov 12, 2022 |
| MSI           | A320M-A PRO                 | [6b77cc7062](https://linux-hardware.org/?probe=6b77cc7062) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [2677116eee](https://linux-hardware.org/?probe=2677116eee) | Nov 12, 2022 |
| ASUSTek       | P5K-VM                      | [8d1ad25443](https://linux-hardware.org/?probe=8d1ad25443) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [7fe6789365](https://linux-hardware.org/?probe=7fe6789365) | Nov 12, 2022 |
| MSI           | Z97-G43                     | [f5946a94b0](https://linux-hardware.org/?probe=f5946a94b0) | Nov 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8d2d850a5](https://linux-hardware.org/?probe=a8d2d850a5) | Nov 12, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [c1103d767e](https://linux-hardware.org/?probe=c1103d767e) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [0d1333128b](https://linux-hardware.org/?probe=0d1333128b) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | [ff49e5ddb5](https://linux-hardware.org/?probe=ff49e5ddb5) | Nov 11, 2022 |
| Sapphire      | IPC-E350M1                  | [58a5544fb4](https://linux-hardware.org/?probe=58a5544fb4) | Nov 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [af490e0878](https://linux-hardware.org/?probe=af490e0878) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | [b152665a17](https://linux-hardware.org/?probe=b152665a17) | Nov 11, 2022 |
| ASUSTek       | H81M-PLUS                   | [12d6552ded](https://linux-hardware.org/?probe=12d6552ded) | Nov 11, 2022 |
| ASRock        | B550M-HDV                   | [277c219cef](https://linux-hardware.org/?probe=277c219cef) | Nov 11, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [a37ca89eae](https://linux-hardware.org/?probe=a37ca89eae) | Nov 11, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| ASUSTek       | PRIME B450M-K               | [ccd759a684](https://linux-hardware.org/?probe=ccd759a684) | Nov 11, 2022 |
| Intel         | DP965LT AAD41694-206        | [72773d35e0](https://linux-hardware.org/?probe=72773d35e0) | Nov 11, 2022 |
| ASRock        | H470M-HVS                   | [b81b19a472](https://linux-hardware.org/?probe=b81b19a472) | Nov 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| MSI           | B150 GAMING M3              | [13f42af580](https://linux-hardware.org/?probe=13f42af580) | Nov 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | [46ee069dd8](https://linux-hardware.org/?probe=46ee069dd8) | Nov 11, 2022 |
| MSI           | B450M GAMING PLUS           | [dd56553c17](https://linux-hardware.org/?probe=dd56553c17) | Nov 11, 2022 |
| Unknown       | NF-CK804                    | [6bda1f2345](https://linux-hardware.org/?probe=6bda1f2345) | Nov 10, 2022 |
| ASRock        | H410M-HDV                   | [985b9b55e2](https://linux-hardware.org/?probe=985b9b55e2) | Nov 10, 2022 |
| Acer          | H11H4-AI V:1.0              | [0873e8bf70](https://linux-hardware.org/?probe=0873e8bf70) | Nov 10, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [45dc316bea](https://linux-hardware.org/?probe=45dc316bea) | Nov 10, 2022 |
| ASUSTek       | P5K/EPU                     | [4bd9a2de61](https://linux-hardware.org/?probe=4bd9a2de61) | Nov 10, 2022 |
| Gigabyte      | H55M-S2H                    | [8af42c3646](https://linux-hardware.org/?probe=8af42c3646) | Nov 10, 2022 |
| ASUSTek       | P5K/EPU                     | [cd3706107a](https://linux-hardware.org/?probe=cd3706107a) | Nov 10, 2022 |
| ASUSTek       | H110M-K                     | [4d6af313f5](https://linux-hardware.org/?probe=4d6af313f5) | Nov 10, 2022 |
| Gigabyte      | H55M-S2H                    | [18d013bbc8](https://linux-hardware.org/?probe=18d013bbc8) | Nov 10, 2022 |
| ASUSTek       | P7H55-M/USB3                | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [b5ce55106f](https://linux-hardware.org/?probe=b5ce55106f) | Nov 10, 2022 |
| Gigabyte      | A320M-H-CF                  | [4cf7d8ea41](https://linux-hardware.org/?probe=4cf7d8ea41) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [a885b61478](https://linux-hardware.org/?probe=a885b61478) | Nov 10, 2022 |
| Intel         | X79                         | [f806dcc4da](https://linux-hardware.org/?probe=f806dcc4da) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [475ad820cd](https://linux-hardware.org/?probe=475ad820cd) | Nov 10, 2022 |
| Pegatron      | 2A73h                       | [dc035c362e](https://linux-hardware.org/?probe=dc035c362e) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | [640d78b1e4](https://linux-hardware.org/?probe=640d78b1e4) | Nov 10, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | [d9d004077a](https://linux-hardware.org/?probe=d9d004077a) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| MSI           | MS-B1711                    | [a80911f521](https://linux-hardware.org/?probe=a80911f521) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | [50b86d41a2](https://linux-hardware.org/?probe=50b86d41a2) | Nov 09, 2022 |
| MSI           | Z370 TOMAHAWK               | [0763a922c8](https://linux-hardware.org/?probe=0763a922c8) | Nov 09, 2022 |
| ASRock        | H97 Pro4                    | [bdd79e7a9e](https://linux-hardware.org/?probe=bdd79e7a9e) | Nov 09, 2022 |
| Gigabyte      | 990XA-UD3                   | [c92f8d8b22](https://linux-hardware.org/?probe=c92f8d8b22) | Nov 09, 2022 |
| HP            | 806A                        | [e8bee1d38a](https://linux-hardware.org/?probe=e8bee1d38a) | Nov 08, 2022 |
| MSI           | X370 GAMING PLUS            | [ae91098674](https://linux-hardware.org/?probe=ae91098674) | Nov 08, 2022 |
| Huanan        | X99-BD4 V1.3                | [e50441190a](https://linux-hardware.org/?probe=e50441190a) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [c8383aa811](https://linux-hardware.org/?probe=c8383aa811) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [7f6cff35d7](https://linux-hardware.org/?probe=7f6cff35d7) | Nov 08, 2022 |
| Gigabyte      | Z77X-D3H                    | [09e3734a06](https://linux-hardware.org/?probe=09e3734a06) | Nov 08, 2022 |
| Gigabyte      | A320M-H-CF                  | [137958160c](https://linux-hardware.org/?probe=137958160c) | Nov 08, 2022 |
| ASUSTek       | P8H67-M LX                  | [277212bfc3](https://linux-hardware.org/?probe=277212bfc3) | Nov 08, 2022 |
| Gigabyte      | EP45-UD3L                   | [2b3eb32895](https://linux-hardware.org/?probe=2b3eb32895) | Nov 07, 2022 |
| Unknown       | Unknown                     | [37226d7d92](https://linux-hardware.org/?probe=37226d7d92) | Nov 07, 2022 |
| MSI           | X370 GAMING PLUS            | [cda3bef0bc](https://linux-hardware.org/?probe=cda3bef0bc) | Nov 07, 2022 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [731ce5b944](https://linux-hardware.org/?probe=731ce5b944) | Nov 07, 2022 |
| ASRock        | D1800M                      | [4935d67430](https://linux-hardware.org/?probe=4935d67430) | Nov 07, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dd30cc2e63](https://linux-hardware.org/?probe=dd30cc2e63) | Nov 07, 2022 |
| ASRock        | N68C-GS FX                  | [c7b8fac7e2](https://linux-hardware.org/?probe=c7b8fac7e2) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [16b37f0b80](https://linux-hardware.org/?probe=16b37f0b80) | Nov 07, 2022 |
| ASUSTek       | F2A55-M LK                  | [0c888d2b1f](https://linux-hardware.org/?probe=0c888d2b1f) | Nov 07, 2022 |
| MSI           | B450M MORTAR MAX            | [eae2553adf](https://linux-hardware.org/?probe=eae2553adf) | Nov 06, 2022 |
| MSI           | H81M-P33                    | [00cb3af126](https://linux-hardware.org/?probe=00cb3af126) | Nov 06, 2022 |
| ASRock        | H370M-ITX/ac                | [fe29240874](https://linux-hardware.org/?probe=fe29240874) | Nov 06, 2022 |
| Acer          | EG31M R01-C2                | [1c541d28e0](https://linux-hardware.org/?probe=1c541d28e0) | Nov 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | [a60e7d1961](https://linux-hardware.org/?probe=a60e7d1961) | Nov 06, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [905a8c9fee](https://linux-hardware.org/?probe=905a8c9fee) | Nov 06, 2022 |
| ASRock        | B550 Extreme4               | [16154018bb](https://linux-hardware.org/?probe=16154018bb) | Nov 06, 2022 |
| MSI           | B150 GAMING M3              | [38a85b01ad](https://linux-hardware.org/?probe=38a85b01ad) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [b6a4d355bc](https://linux-hardware.org/?probe=b6a4d355bc) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | [4d260267d7](https://linux-hardware.org/?probe=4d260267d7) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | [789df18cfb](https://linux-hardware.org/?probe=789df18cfb) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [ba495c1631](https://linux-hardware.org/?probe=ba495c1631) | Nov 06, 2022 |
| Gigabyte      | F2A55M-DS2                  | [4cadf85e6e](https://linux-hardware.org/?probe=4cadf85e6e) | Nov 06, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [4a3eefaf16](https://linux-hardware.org/?probe=4a3eefaf16) | Nov 06, 2022 |
| ASUSTek       | Z97-C                       | [ce7c45a3d9](https://linux-hardware.org/?probe=ce7c45a3d9) | Nov 06, 2022 |
| Biostar       | A78LR-M3S                   | [8e8da94ddb](https://linux-hardware.org/?probe=8e8da94ddb) | Nov 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [5db0a08b25](https://linux-hardware.org/?probe=5db0a08b25) | Nov 06, 2022 |
| ASRock        | B660M PG Riptide            | [2fb2a2e140](https://linux-hardware.org/?probe=2fb2a2e140) | Nov 05, 2022 |
| Gigabyte      | B365M D3H-CF                | [53d09fc292](https://linux-hardware.org/?probe=53d09fc292) | Nov 05, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5d6951212b](https://linux-hardware.org/?probe=5d6951212b) | Nov 05, 2022 |
| ASUSTek       | PRIME H510M-R               | [922e24a1a0](https://linux-hardware.org/?probe=922e24a1a0) | Nov 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | [40ef04163d](https://linux-hardware.org/?probe=40ef04163d) | Nov 05, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d7512f31a3](https://linux-hardware.org/?probe=d7512f31a3) | Nov 05, 2022 |
| Gigabyte      | H61M-S2PV                   | [1c2a17391f](https://linux-hardware.org/?probe=1c2a17391f) | Nov 05, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [a8926fce15](https://linux-hardware.org/?probe=a8926fce15) | Nov 05, 2022 |
| MSI           | P67A-C43                    | [a5e86512d1](https://linux-hardware.org/?probe=a5e86512d1) | Nov 05, 2022 |
| Gigabyte      | H110M-S2HP-CF               | [94004d5828](https://linux-hardware.org/?probe=94004d5828) | Nov 05, 2022 |
| Gigabyte      | B75-D3V                     | [a562aef0c3](https://linux-hardware.org/?probe=a562aef0c3) | Nov 05, 2022 |
| Dell          | 0MN1TX A01                  | [a788e75812](https://linux-hardware.org/?probe=a788e75812) | Nov 05, 2022 |
| ASUSTek       | M4A77TD PRO                 | [b5fa37b726](https://linux-hardware.org/?probe=b5fa37b726) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | [edf9105fc5](https://linux-hardware.org/?probe=edf9105fc5) | Nov 04, 2022 |
| Unknown       | X79-P3                      | [f069ed7bd9](https://linux-hardware.org/?probe=f069ed7bd9) | Nov 04, 2022 |
| Gigabyte      | Z87-HD3                     | [f67d642096](https://linux-hardware.org/?probe=f67d642096) | Nov 04, 2022 |
| MSI           | B360M PRO-VDH               | [2a801a9792](https://linux-hardware.org/?probe=2a801a9792) | Nov 04, 2022 |
| ASUSTek       | H170I-PLUS D3               | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | P5K                         | [ebc4a23dcc](https://linux-hardware.org/?probe=ebc4a23dcc) | Nov 04, 2022 |
| MSI           | X370 GAMING PLUS            | [db81c87a42](https://linux-hardware.org/?probe=db81c87a42) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | [95729b1578](https://linux-hardware.org/?probe=95729b1578) | Nov 04, 2022 |
| ASRock        | H61M-VG4                    | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Dell          | 0GY6Y8 A03                  | [7ff8f0aecd](https://linux-hardware.org/?probe=7ff8f0aecd) | Nov 03, 2022 |
| Huanan        | X99-BD4 V1.3                | [3eccdb8ba1](https://linux-hardware.org/?probe=3eccdb8ba1) | Nov 03, 2022 |
| Gigabyte      | Z87-HD3                     | [ef71fa8dd6](https://linux-hardware.org/?probe=ef71fa8dd6) | Nov 03, 2022 |
| Gigabyte      | Z490 UD                     | [c560dfaab4](https://linux-hardware.org/?probe=c560dfaab4) | Nov 03, 2022 |
| ASUSTek       | P8H77-V LE                  | [d5c39748e3](https://linux-hardware.org/?probe=d5c39748e3) | Nov 03, 2022 |
| MSI           | X370 GAMING PLUS            | [749d91dfd4](https://linux-hardware.org/?probe=749d91dfd4) | Nov 03, 2022 |
| ASUSTek       | H61M-K                      | [4b580ecb2b](https://linux-hardware.org/?probe=4b580ecb2b) | Nov 03, 2022 |
| ASUSTek       | H61M-K                      | [c47ee488a5](https://linux-hardware.org/?probe=c47ee488a5) | Nov 03, 2022 |
| Gigabyte      | Z490 UD                     | [eb3812d5ce](https://linux-hardware.org/?probe=eb3812d5ce) | Nov 03, 2022 |
| Gigabyte      | H310M S2H                   | [521297d21c](https://linux-hardware.org/?probe=521297d21c) | Nov 03, 2022 |
| ECS           | MCP61M-M3                   | [fe5e87a9ef](https://linux-hardware.org/?probe=fe5e87a9ef) | Nov 03, 2022 |
| MSI           | B85M PRO-VD                 | [46a3742fd3](https://linux-hardware.org/?probe=46a3742fd3) | Nov 03, 2022 |
| ASUSTek       | Z97-C                       | [be4968a790](https://linux-hardware.org/?probe=be4968a790) | Nov 03, 2022 |
| ASRock        | A320D4-P1                   | [8e453f4158](https://linux-hardware.org/?probe=8e453f4158) | Nov 03, 2022 |
| MSI           | H510M PRO-E                 | [23fa7a2cf8](https://linux-hardware.org/?probe=23fa7a2cf8) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [80dbb62739](https://linux-hardware.org/?probe=80dbb62739) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [f942b801f7](https://linux-hardware.org/?probe=f942b801f7) | Nov 03, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2c9714bc6b](https://linux-hardware.org/?probe=2c9714bc6b) | Nov 02, 2022 |
| ASRock        | N68-GS4 FX                  | [da7a70afe1](https://linux-hardware.org/?probe=da7a70afe1) | Nov 02, 2022 |
| Shenzhen a... | AC1-DP                      | [754335ffe9](https://linux-hardware.org/?probe=754335ffe9) | Nov 02, 2022 |
| MSI           | MS-7392                     | [d453f89064](https://linux-hardware.org/?probe=d453f89064) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [23a62c3509](https://linux-hardware.org/?probe=23a62c3509) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [d34ccf5e7a](https://linux-hardware.org/?probe=d34ccf5e7a) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [eb06593b9e](https://linux-hardware.org/?probe=eb06593b9e) | Nov 02, 2022 |
| Gigabyte      | H77N-WIFI                   | [d8b066edcd](https://linux-hardware.org/?probe=d8b066edcd) | Nov 02, 2022 |
| MSI           | H110M PRO-VD                | [1fb0a79791](https://linux-hardware.org/?probe=1fb0a79791) | Nov 02, 2022 |
| ASUSTek       | H61M-K                      | [3773260366](https://linux-hardware.org/?probe=3773260366) | Nov 02, 2022 |
| Gigabyte      | A520M DS3H                  | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Lenovo        | H420                        | [3e3f04d875](https://linux-hardware.org/?probe=3e3f04d875) | Nov 02, 2022 |
| Gigabyte      | EP45-DS4                    | [fa96a26c5a](https://linux-hardware.org/?probe=fa96a26c5a) | Nov 02, 2022 |
| ECS           | H61H2-M2                    | [b70c0aa20d](https://linux-hardware.org/?probe=b70c0aa20d) | Nov 01, 2022 |
| Gigabyte      | H610M H DDR4                | [b726668f90](https://linux-hardware.org/?probe=b726668f90) | Nov 01, 2022 |
| Gigabyte      | EP45-DS4                    | [2eb78b1c3d](https://linux-hardware.org/?probe=2eb78b1c3d) | Nov 01, 2022 |
| ASUSTek       | CROSSBLADE RANGER           | [5f92247b16](https://linux-hardware.org/?probe=5f92247b16) | Nov 01, 2022 |
| Gigabyte      | B450M H                     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| ASUSTek       | PRIME H310M-K               | [9efd2724b2](https://linux-hardware.org/?probe=9efd2724b2) | Nov 01, 2022 |
| ASRock        | B365M-HDV                   | [29a6bce4c0](https://linux-hardware.org/?probe=29a6bce4c0) | Nov 01, 2022 |
| ASUSTek       | H81M-C                      | [76052b7756](https://linux-hardware.org/?probe=76052b7756) | Nov 01, 2022 |
| Gigabyte      | X570S AERO G                | [92fccb6716](https://linux-hardware.org/?probe=92fccb6716) | Nov 01, 2022 |
| MSI           | H61M-P32/W8                 | [14df9c3c14](https://linux-hardware.org/?probe=14df9c3c14) | Nov 01, 2022 |
| MSI           | 0A90                        | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| MSI           | Z390-A PRO                  | [3eea020596](https://linux-hardware.org/?probe=3eea020596) | Nov 01, 2022 |
| ASRock        | N68C-GS FX                  | [f7a9c5f382](https://linux-hardware.org/?probe=f7a9c5f382) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | [1a88842782](https://linux-hardware.org/?probe=1a88842782) | Nov 01, 2022 |
| MSI           | H81M-P33                    | [29e4a4ec52](https://linux-hardware.org/?probe=29e4a4ec52) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [96d61ed3e1](https://linux-hardware.org/?probe=96d61ed3e1) | Oct 31, 2022 |
| MSI           | B450-A PRO MAX              | [8e480ded02](https://linux-hardware.org/?probe=8e480ded02) | Oct 31, 2022 |
| ASRock        | 960GM-VGS3 FX               | [f31f613901](https://linux-hardware.org/?probe=f31f613901) | Oct 31, 2022 |
| ASUSTek       | H81M-C                      | [2fdcf19b6d](https://linux-hardware.org/?probe=2fdcf19b6d) | Oct 31, 2022 |
| Foxconn       | RS690M2MA 0A                | [29605bcad9](https://linux-hardware.org/?probe=29605bcad9) | Oct 31, 2022 |
| Gigabyte      | B660M GAMING X AX           | [d48fe55211](https://linux-hardware.org/?probe=d48fe55211) | Oct 31, 2022 |
| ASRock        | H470M-HDV                   | [a4e522270c](https://linux-hardware.org/?probe=a4e522270c) | Oct 31, 2022 |
| Biostar       | H310MHC2                    | [5ad5ba772f](https://linux-hardware.org/?probe=5ad5ba772f) | Oct 31, 2022 |
| Intel         | DG41AN AAE92991-401         | [cd670cef3d](https://linux-hardware.org/?probe=cd670cef3d) | Oct 31, 2022 |
| Gigabyte      | A520M H                     | [0a8043d206](https://linux-hardware.org/?probe=0a8043d206) | Oct 31, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [5e87d391a3](https://linux-hardware.org/?probe=5e87d391a3) | Oct 31, 2022 |
| Intel         | D946GZAB AAD66610-300       | [33c41323a3](https://linux-hardware.org/?probe=33c41323a3) | Oct 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | [b5098e9fe5](https://linux-hardware.org/?probe=b5098e9fe5) | Oct 31, 2022 |
| ASRock        | N68C-GS FX                  | [e24bf2e31f](https://linux-hardware.org/?probe=e24bf2e31f) | Oct 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [d4340d8d66](https://linux-hardware.org/?probe=d4340d8d66) | Oct 31, 2022 |
| ASUSTek       | Leonite2                    | [955ce84cf2](https://linux-hardware.org/?probe=955ce84cf2) | Oct 30, 2022 |
| ASRock        | N68C-GS FX                  | [bf96e5a0a1](https://linux-hardware.org/?probe=bf96e5a0a1) | Oct 30, 2022 |
| ASRock        | H410M-HVS                   | [2d540e06b9](https://linux-hardware.org/?probe=2d540e06b9) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [6bbea41ce5](https://linux-hardware.org/?probe=6bbea41ce5) | Oct 30, 2022 |
| Gigabyte      | G41M-Combo                  | [180622c3be](https://linux-hardware.org/?probe=180622c3be) | Oct 30, 2022 |
| ASRock        | B450M Pro4-F R2.0           | [5fb37123e0](https://linux-hardware.org/?probe=5fb37123e0) | Oct 30, 2022 |
| ASUSTek       | P7H55-M/USB3                | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7f78f3451e](https://linux-hardware.org/?probe=7f78f3451e) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [47b5907eec](https://linux-hardware.org/?probe=47b5907eec) | Oct 29, 2022 |
| MSI           | B450M MORTAR MAX            | [d8321f617e](https://linux-hardware.org/?probe=d8321f617e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| MSI           | B450M MORTAR MAX            | [7f67023fa9](https://linux-hardware.org/?probe=7f67023fa9) | Oct 29, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [a750edc641](https://linux-hardware.org/?probe=a750edc641) | Oct 29, 2022 |
| ASRock        | H410M-HVS                   | [9371d71f6d](https://linux-hardware.org/?probe=9371d71f6d) | Oct 29, 2022 |
| Gigabyte      | H110M-M2-CF                 | [34c4f594c4](https://linux-hardware.org/?probe=34c4f594c4) | Oct 29, 2022 |
| Dell          | 0Y5DDC A00                  | [e3421b1908](https://linux-hardware.org/?probe=e3421b1908) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX                  | [04334f2930](https://linux-hardware.org/?probe=04334f2930) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | [7b3b808198](https://linux-hardware.org/?probe=7b3b808198) | Oct 29, 2022 |
| Techvision    | TVI7309X B0                 | [65b5280dd1](https://linux-hardware.org/?probe=65b5280dd1) | Oct 29, 2022 |
| ASUSTek       | P5K                         | [6d87562df6](https://linux-hardware.org/?probe=6d87562df6) | Oct 28, 2022 |
| ASRock        | Z370 Pro4                   | [04e898b2f6](https://linux-hardware.org/?probe=04e898b2f6) | Oct 28, 2022 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [429fd34d64](https://linux-hardware.org/?probe=429fd34d64) | Oct 28, 2022 |
| ASUSTek       | H81M-C                      | [c96189c44c](https://linux-hardware.org/?probe=c96189c44c) | Oct 28, 2022 |
| Gigabyte      | B560M H                     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Gigabyte      | PH67-UD3-B3                 | [c66fb514ab](https://linux-hardware.org/?probe=c66fb514ab) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | [4783ed1083](https://linux-hardware.org/?probe=4783ed1083) | Oct 28, 2022 |
| MSI           | 0A90                        | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| MSI           | Z97 GAMING 3                | [4488ff5b26](https://linux-hardware.org/?probe=4488ff5b26) | Oct 28, 2022 |
| Gigabyte      | A320M-S2H-CF                | [594b16e254](https://linux-hardware.org/?probe=594b16e254) | Oct 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [327ee3d5b0](https://linux-hardware.org/?probe=327ee3d5b0) | Oct 28, 2022 |
| Gigabyte      | F2A88X-D3H                  | [dc1e16bba1](https://linux-hardware.org/?probe=dc1e16bba1) | Oct 27, 2022 |
| ASUSTek       | P8B75-V                     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASUSTek       | M5A97 PRO                   | [de99c600e5](https://linux-hardware.org/?probe=de99c600e5) | Oct 27, 2022 |
| Gigabyte      | H110M-S2V-CF                | [1d4dfc3e06](https://linux-hardware.org/?probe=1d4dfc3e06) | Oct 27, 2022 |
| ASRock        | Z77 Pro4-M                  | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [6de2b1229f](https://linux-hardware.org/?probe=6de2b1229f) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| MSI           | H110M PRO-VD                | [175f39979c](https://linux-hardware.org/?probe=175f39979c) | Oct 27, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| MSI           | H81M-P33                    | [e4f38c5519](https://linux-hardware.org/?probe=e4f38c5519) | Oct 26, 2022 |
| AMI           | Cherry Trail CR             | [8cf0d29214](https://linux-hardware.org/?probe=8cf0d29214) | Oct 26, 2022 |
| HP            | 8717                        | [c2fcc7119a](https://linux-hardware.org/?probe=c2fcc7119a) | Oct 26, 2022 |
| AMI           | Cherry Trail CR             | [e8f64c2c8c](https://linux-hardware.org/?probe=e8f64c2c8c) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | [0d3545c6aa](https://linux-hardware.org/?probe=0d3545c6aa) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | [0b8dc998a9](https://linux-hardware.org/?probe=0b8dc998a9) | Oct 26, 2022 |
| ASRock        | 970 Pro3 R2.0               | [c2b4882963](https://linux-hardware.org/?probe=c2b4882963) | Oct 26, 2022 |
| MiTAC         | E220 E220AQ-601             | [1ee0c036f8](https://linux-hardware.org/?probe=1ee0c036f8) | Oct 26, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c1067e423b](https://linux-hardware.org/?probe=c1067e423b) | Oct 26, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [926be6d85b](https://linux-hardware.org/?probe=926be6d85b) | Oct 25, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [94a393835b](https://linux-hardware.org/?probe=94a393835b) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| Gigabyte      | P41T-D3                     | [fa69e3fada](https://linux-hardware.org/?probe=fa69e3fada) | Oct 25, 2022 |
| Gigabyte      | P41T-D3                     | [c96d8030a6](https://linux-hardware.org/?probe=c96d8030a6) | Oct 25, 2022 |
| MSI           | H110M PRO-VD                | [f8466185a4](https://linux-hardware.org/?probe=f8466185a4) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| MSI           | B450M-A PRO MAX             | [9f404fe6b4](https://linux-hardware.org/?probe=9f404fe6b4) | Oct 25, 2022 |
| Dell          | 0Y5DDC A00                  | [bc39e0cfd6](https://linux-hardware.org/?probe=bc39e0cfd6) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b8b23daad5](https://linux-hardware.org/?probe=b8b23daad5) | Oct 25, 2022 |
| ASUSTek       | PRIME H510M-A               | [83f5d2034b](https://linux-hardware.org/?probe=83f5d2034b) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| Gigabyte      | H410M H V3                  | [b4c5ed92b7](https://linux-hardware.org/?probe=b4c5ed92b7) | Oct 24, 2022 |
| MSI           | B450M GAMING PLUS           | [e3041ae2eb](https://linux-hardware.org/?probe=e3041ae2eb) | Oct 24, 2022 |
| Gigabyte      | H61M-S2PV                   | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| Gigabyte      | B450 AORUS M                | [08c2a2abf9](https://linux-hardware.org/?probe=08c2a2abf9) | Oct 24, 2022 |
| Gigabyte      | X58A-UD7                    | [8b0cff9259](https://linux-hardware.org/?probe=8b0cff9259) | Oct 24, 2022 |
| ASUSTek       | P8H77-V                     | [fdb1bce84a](https://linux-hardware.org/?probe=fdb1bce84a) | Oct 24, 2022 |
| ECS           | H310CH5-M2                  | [e9d2a5becb](https://linux-hardware.org/?probe=e9d2a5becb) | Oct 24, 2022 |
| Gigabyte      | G41M-ES2L                   | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Gigabyte      | Z690 UD DDR4                | [8cc3ca1253](https://linux-hardware.org/?probe=8cc3ca1253) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H V2               | [a159a5720e](https://linux-hardware.org/?probe=a159a5720e) | Oct 23, 2022 |
| Biostar       | TH67XE                      | [b523b997f6](https://linux-hardware.org/?probe=b523b997f6) | Oct 23, 2022 |
| ASUSTek       | Z97I-PLUS                   | [d7c07287bd](https://linux-hardware.org/?probe=d7c07287bd) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| ASUSTek       | M4A77T/USB3                 | [2df43ccc5d](https://linux-hardware.org/?probe=2df43ccc5d) | Oct 22, 2022 |
| Unknown       | NF-CK804                    | [4df3f7c7e6](https://linux-hardware.org/?probe=4df3f7c7e6) | Oct 22, 2022 |
| ASUSTek       | P7H55-M PRO                 | [0b306aaddf](https://linux-hardware.org/?probe=0b306aaddf) | Oct 22, 2022 |
| MSI           | A320M GRENADE               | [30bcc61268](https://linux-hardware.org/?probe=30bcc61268) | Oct 21, 2022 |
| Gigabyte      | H81M-S1                     | [8168ea4028](https://linux-hardware.org/?probe=8168ea4028) | Oct 21, 2022 |
| Lenovo        | 3708 NOK                    | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Gigabyte      | H310M H x.x                 | [a0a8fc6cb0](https://linux-hardware.org/?probe=a0a8fc6cb0) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| MSI           | A320M GRENADE               | [73112f41f7](https://linux-hardware.org/?probe=73112f41f7) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [a59f545a7b](https://linux-hardware.org/?probe=a59f545a7b) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| ASUSTek       | B85-PLUS                    | [a057e410d0](https://linux-hardware.org/?probe=a057e410d0) | Oct 21, 2022 |
| ASUSTek       | B85-PLUS                    | [72c61d8c50](https://linux-hardware.org/?probe=72c61d8c50) | Oct 21, 2022 |
| ASUSTek       | M5A78L LE                   | [88b0f5d5c3](https://linux-hardware.org/?probe=88b0f5d5c3) | Oct 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [f60716afd0](https://linux-hardware.org/?probe=f60716afd0) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASRock        | H81M-HDS R2.0               | [6161a12f13](https://linux-hardware.org/?probe=6161a12f13) | Oct 20, 2022 |
| ASUSTek       | P5Q SE                      | [c223e518c9](https://linux-hardware.org/?probe=c223e518c9) | Oct 20, 2022 |
| Dell          | 0D4MD1 A02                  | [becbded076](https://linux-hardware.org/?probe=becbded076) | Oct 20, 2022 |
| ASUSTek       | PRIME B360M-A               | [444b923209](https://linux-hardware.org/?probe=444b923209) | Oct 20, 2022 |
| Gigabyte      | EP41-UD3L                   | [d82763649b](https://linux-hardware.org/?probe=d82763649b) | Oct 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [fffc0ab985](https://linux-hardware.org/?probe=fffc0ab985) | Oct 20, 2022 |
| ASRock        | H110M-DVS R3.0              | [86b7c01699](https://linux-hardware.org/?probe=86b7c01699) | Oct 19, 2022 |
| ASRock        | H81M-HDS R2.0               | [b27f916880](https://linux-hardware.org/?probe=b27f916880) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Acer          | FMCP7A-ION                  | [e7646c8fe4](https://linux-hardware.org/?probe=e7646c8fe4) | Oct 19, 2022 |
| Gigabyte      | EP41-UD3L                   | [31867fb669](https://linux-hardware.org/?probe=31867fb669) | Oct 19, 2022 |
| ECS           | H61H2-M12                   | [7c4ae7b4ab](https://linux-hardware.org/?probe=7c4ae7b4ab) | Oct 19, 2022 |
| ASUSTek       | Leonite2                    | [717cc412e5](https://linux-hardware.org/?probe=717cc412e5) | Oct 19, 2022 |
| MSI           | PRO H410M-B                 | [549eeb915c](https://linux-hardware.org/?probe=549eeb915c) | Oct 19, 2022 |
| MSI           | H81M-P33                    | [784b068521](https://linux-hardware.org/?probe=784b068521) | Oct 19, 2022 |
| ASUSTek       | B85M-G                      | [42a1bedb35](https://linux-hardware.org/?probe=42a1bedb35) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| ASUSTek       | H81M-K                      | [a4a1d563b5](https://linux-hardware.org/?probe=a4a1d563b5) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| ASRock        | H61M-GE                     | [6149e0c478](https://linux-hardware.org/?probe=6149e0c478) | Oct 18, 2022 |
| Intel         | X99                         | [4217ddeb6b](https://linux-hardware.org/?probe=4217ddeb6b) | Oct 18, 2022 |
| MSI           | Z490-A PRO                  | [db93de2ab4](https://linux-hardware.org/?probe=db93de2ab4) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3b1ce3ab08](https://linux-hardware.org/?probe=3b1ce3ab08) | Oct 18, 2022 |
| MSI           | B360M GAMING PLUS           | [df2e89c571](https://linux-hardware.org/?probe=df2e89c571) | Oct 18, 2022 |
| Gigabyte      | H77N-WIFI                   | [1e8b0c8279](https://linux-hardware.org/?probe=1e8b0c8279) | Oct 18, 2022 |
| Giga-Byte ... | i440BX-W977                 | [018daa60e1](https://linux-hardware.org/?probe=018daa60e1) | Oct 18, 2022 |
| Biostar       | A320MD PRO                  | [0497b12091](https://linux-hardware.org/?probe=0497b12091) | Oct 18, 2022 |
| ASUSTek       | B85M-G                      | [86b92cdc50](https://linux-hardware.org/?probe=86b92cdc50) | Oct 18, 2022 |
| Gigabyte      | H510M S2H                   | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| ASRock        | H310CM-HDV/M.2              | [f2112b8b74](https://linux-hardware.org/?probe=f2112b8b74) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [e4769fb9e0](https://linux-hardware.org/?probe=e4769fb9e0) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [76bb60e5ee](https://linux-hardware.org/?probe=76bb60e5ee) | Oct 17, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [9d4d455bb2](https://linux-hardware.org/?probe=9d4d455bb2) | Oct 17, 2022 |
| ASRock        | H61M-GE                     | [873932f557](https://linux-hardware.org/?probe=873932f557) | Oct 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b85a76dd7f](https://linux-hardware.org/?probe=b85a76dd7f) | Oct 17, 2022 |
| Biostar       | H61MLV                      | [c2fb8ebaac](https://linux-hardware.org/?probe=c2fb8ebaac) | Oct 17, 2022 |
| Dell          | 0HY553                      | [08f05b94e6](https://linux-hardware.org/?probe=08f05b94e6) | Oct 17, 2022 |
| Gigabyte      | C246N-WU2-CF                | [cb7ca4eb5a](https://linux-hardware.org/?probe=cb7ca4eb5a) | Oct 16, 2022 |
| HP            | 81B3                        | [e303e50785](https://linux-hardware.org/?probe=e303e50785) | Oct 16, 2022 |
| Gigabyte      | B75M-D2V                    | [20ac585859](https://linux-hardware.org/?probe=20ac585859) | Oct 16, 2022 |
| ASUSTek       | P8H61-M LE                  | [cf76898812](https://linux-hardware.org/?probe=cf76898812) | Oct 16, 2022 |
| ASUSTek       | PRIME B450M-K II            | [d1d815635a](https://linux-hardware.org/?probe=d1d815635a) | Oct 16, 2022 |
| Gigabyte      | GA-770TA-UD3                | [82f436a99c](https://linux-hardware.org/?probe=82f436a99c) | Oct 16, 2022 |
| ASUSTek       | P5E                         | [747e4c7a68](https://linux-hardware.org/?probe=747e4c7a68) | Oct 16, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [59a0225889](https://linux-hardware.org/?probe=59a0225889) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [f26592e956](https://linux-hardware.org/?probe=f26592e956) | Oct 16, 2022 |
| ASRock        | A55 Pro3                    | [0b3e7a1cd2](https://linux-hardware.org/?probe=0b3e7a1cd2) | Oct 16, 2022 |
| ASUSTek       | PRIME B450M-K               | [288b9fadfe](https://linux-hardware.org/?probe=288b9fadfe) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [f9568da63c](https://linux-hardware.org/?probe=f9568da63c) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [b226135430](https://linux-hardware.org/?probe=b226135430) | Oct 15, 2022 |
| Gigabyte      | B250M-D3H-CF                | [c351e0fae6](https://linux-hardware.org/?probe=c351e0fae6) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| ASUSTek       | P7H55-M/USB3                | [8a98e44bee](https://linux-hardware.org/?probe=8a98e44bee) | Oct 15, 2022 |
| Huanan        | H97-ZD3 V2.0                | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| ASUSTek       | P5P43TD PRO                 | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI           | G31TM-P21                   | [ea0fc2d497](https://linux-hardware.org/?probe=ea0fc2d497) | Oct 14, 2022 |
| MSI           | B85M-P33                    | [83d476e3d7](https://linux-hardware.org/?probe=83d476e3d7) | Oct 14, 2022 |
| Gigabyte      | H77N-WIFI                   | [d1f08d0589](https://linux-hardware.org/?probe=d1f08d0589) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| Gigabyte      | Z77-D3H                     | [06edc1eef1](https://linux-hardware.org/?probe=06edc1eef1) | Oct 14, 2022 |
| ASUSTek       | P5QL-CM                     | [34c01c8045](https://linux-hardware.org/?probe=34c01c8045) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| HP            | 339A                        | [f7dd678058](https://linux-hardware.org/?probe=f7dd678058) | Oct 14, 2022 |
| ASUSTek       | P8H77-V                     | [9c98c411c5](https://linux-hardware.org/?probe=9c98c411c5) | Oct 14, 2022 |
| Kraftway      | KWQ67                       | [8346fc15e3](https://linux-hardware.org/?probe=8346fc15e3) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | [d57d34be64](https://linux-hardware.org/?probe=d57d34be64) | Oct 13, 2022 |
| ASRock        | G41M-VS3                    | [7fa0f82664](https://linux-hardware.org/?probe=7fa0f82664) | Oct 13, 2022 |
| Gigabyte      | H77N-WIFI                   | [6597eea759](https://linux-hardware.org/?probe=6597eea759) | Oct 13, 2022 |
| HP            | 1495                        | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| Founder       | H61H2-AM V1.1               | [4d558904f5](https://linux-hardware.org/?probe=4d558904f5) | Oct 13, 2022 |
| Lenovo        | ThinkCentre M71z 1782RP4    | [bee14a3740](https://linux-hardware.org/?probe=bee14a3740) | Oct 13, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| Graviton      | DMB-H510-MCA01              | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| ASUSTek       | P8B75-M                     | [98ea718793](https://linux-hardware.org/?probe=98ea718793) | Oct 12, 2022 |
| ASUSTek       | P8H61-M LX3                 | [be3020e232](https://linux-hardware.org/?probe=be3020e232) | Oct 12, 2022 |
| ASUSTek       | P8H77-M PRO                 | [16bee4f203](https://linux-hardware.org/?probe=16bee4f203) | Oct 12, 2022 |
| Gigabyte      | Z170-HD3-CF                 | [3e93bb51b9](https://linux-hardware.org/?probe=3e93bb51b9) | Oct 11, 2022 |
| ASUSTek       | PRIME B560M-A               | [15cc45253b](https://linux-hardware.org/?probe=15cc45253b) | Oct 11, 2022 |
| ASRock        | H570M-ITX/ac                | [eac6add22e](https://linux-hardware.org/?probe=eac6add22e) | Oct 11, 2022 |
| ASRock        | D1800B-ITX                  | [a44ef4b82f](https://linux-hardware.org/?probe=a44ef4b82f) | Oct 11, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [8ec5da3fb1](https://linux-hardware.org/?probe=8ec5da3fb1) | Oct 10, 2022 |
| ASRock        | D1800B-ITX                  | [7b33424235](https://linux-hardware.org/?probe=7b33424235) | Oct 10, 2022 |
| Gigabyte      | GA-880GM-D2H                | [6a9fe776d8](https://linux-hardware.org/?probe=6a9fe776d8) | Oct 10, 2022 |
| ECS           | H61H2-M6                    | [c3c43a35d0](https://linux-hardware.org/?probe=c3c43a35d0) | Oct 10, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [899c4a1231](https://linux-hardware.org/?probe=899c4a1231) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | MS-7430 0A                  | [ac3040f9c3](https://linux-hardware.org/?probe=ac3040f9c3) | Oct 10, 2022 |
| ASUSTek       | B150M-C                     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| ECS           | G31T-M9                     | [6f9e74945f](https://linux-hardware.org/?probe=6f9e74945f) | Oct 10, 2022 |
| MSI           | B450M-A PRO MAX             | [cac41cb816](https://linux-hardware.org/?probe=cac41cb816) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| ASUSTek       | P5K-V                       | [62de8ffd0e](https://linux-hardware.org/?probe=62de8ffd0e) | Oct 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b4dd4f4043](https://linux-hardware.org/?probe=b4dd4f4043) | Oct 09, 2022 |
| ASUSTek       | M4A78T-E                    | [0d574bf35b](https://linux-hardware.org/?probe=0d574bf35b) | Oct 09, 2022 |
| Gigabyte      | H110M-S2-CF                 | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| ASUSTek       | P5QL PRO                    | [93af7ecaf6](https://linux-hardware.org/?probe=93af7ecaf6) | Oct 09, 2022 |
| Gigabyte      | B550M DS3H                  | [1f344c3f2f](https://linux-hardware.org/?probe=1f344c3f2f) | Oct 09, 2022 |
| AZW           | MINI S                      | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| Pegatron      | 2A73h                       | [a5b4cd2cda](https://linux-hardware.org/?probe=a5b4cd2cda) | Oct 09, 2022 |
| Huanan        | H97-ZD3 V2.0                | [c6106f322e](https://linux-hardware.org/?probe=c6106f322e) | Oct 09, 2022 |
| ECS           | BSWI-D2                     | [97c824abf6](https://linux-hardware.org/?probe=97c824abf6) | Oct 09, 2022 |
| ASUSTek       | PRIME Z370-P                | [9f88a01ecd](https://linux-hardware.org/?probe=9f88a01ecd) | Oct 08, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [c21c4e0c90](https://linux-hardware.org/?probe=c21c4e0c90) | Oct 08, 2022 |
| ASRock        | A320M-HDV R4.0              | [5793d73ce0](https://linux-hardware.org/?probe=5793d73ce0) | Oct 08, 2022 |
| ECS           | BSWI-D2                     | [d717be733f](https://linux-hardware.org/?probe=d717be733f) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Colorful T... | B85M-G PRO V21              | [b41a5ff649](https://linux-hardware.org/?probe=b41a5ff649) | Oct 07, 2022 |
| MSI           | H55M-E33                    | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| HP            | 0A60h                       | [8d9a2bf124](https://linux-hardware.org/?probe=8d9a2bf124) | Oct 07, 2022 |
| Gigabyte      | P35-S3                      | [bfd38fc1aa](https://linux-hardware.org/?probe=bfd38fc1aa) | Oct 07, 2022 |
| Gigabyte      | P35-S3                      | [45acd19412](https://linux-hardware.org/?probe=45acd19412) | Oct 07, 2022 |
| Graviton      | DMB-H510-MCA01              | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| eMachines     | ER1401                      | [ee4504d60f](https://linux-hardware.org/?probe=ee4504d60f) | Oct 07, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [ec9fd4936c](https://linux-hardware.org/?probe=ec9fd4936c) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [b8f7c25d91](https://linux-hardware.org/?probe=b8f7c25d91) | Oct 07, 2022 |
| ASRock        | Z68 Extreme4                | [6b96459f0a](https://linux-hardware.org/?probe=6b96459f0a) | Oct 07, 2022 |
| MSI           | H55M-E33                    | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Kllisre       | X79 V1.2                    | [30966c572c](https://linux-hardware.org/?probe=30966c572c) | Oct 06, 2022 |
| Gigabyte      | H410M S2 V2                 | [ab20fa33ac](https://linux-hardware.org/?probe=ab20fa33ac) | Oct 06, 2022 |
| ASUSTek       | P5GDC Pro                   | [25ac480f76](https://linux-hardware.org/?probe=25ac480f76) | Oct 06, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | [ba05383ec5](https://linux-hardware.org/?probe=ba05383ec5) | Oct 06, 2022 |
| ASUSTek       | PRIME H510M-R               | [1b770a47f7](https://linux-hardware.org/?probe=1b770a47f7) | Oct 06, 2022 |
| Biostar       | TF570 SLI A2+               | [f7cacc2b3d](https://linux-hardware.org/?probe=f7cacc2b3d) | Oct 06, 2022 |
| Gigabyte      | H110M-S2V-CF                | [a2dd3b08ba](https://linux-hardware.org/?probe=a2dd3b08ba) | Oct 06, 2022 |
| Unknown       | X79                         | [be112e773d](https://linux-hardware.org/?probe=be112e773d) | Oct 06, 2022 |
| Lenovo        | 0B98401 PRO                 | [6d338f36ef](https://linux-hardware.org/?probe=6d338f36ef) | Oct 06, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [ebe4e45d60](https://linux-hardware.org/?probe=ebe4e45d60) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f92b06fc20](https://linux-hardware.org/?probe=f92b06fc20) | Oct 05, 2022 |
| ASUSTek       | P8H77-V                     | [0b3b1d97f8](https://linux-hardware.org/?probe=0b3b1d97f8) | Oct 05, 2022 |
| Gigabyte      | H110M-S2-CF                 | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| Gigabyte      | B450M S2H                   | [9d214ef1da](https://linux-hardware.org/?probe=9d214ef1da) | Oct 05, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7bf87b89f8](https://linux-hardware.org/?probe=7bf87b89f8) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| Gigabyte      | H110M-S2V-CF                | [20673d8f1e](https://linux-hardware.org/?probe=20673d8f1e) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a3e1169060](https://linux-hardware.org/?probe=a3e1169060) | Oct 05, 2022 |
| MSI           | PRO H410M-B                 | [e85d76f196](https://linux-hardware.org/?probe=e85d76f196) | Oct 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bbea875fdc](https://linux-hardware.org/?probe=bbea875fdc) | Oct 05, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| ASRock        | D1800M                      | [f8f6e6c8f2](https://linux-hardware.org/?probe=f8f6e6c8f2) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| MSI           | B350 TOMAHAWK ARCTIC        | [afcf9c151f](https://linux-hardware.org/?probe=afcf9c151f) | Oct 05, 2022 |
| Gigabyte      | AX370-Gaming K3             | [5ae0d33f23](https://linux-hardware.org/?probe=5ae0d33f23) | Oct 05, 2022 |
| Biostar       | B550T-SILVER                | [8e11b54005](https://linux-hardware.org/?probe=8e11b54005) | Oct 04, 2022 |
| ASUSTek       | Maximus IX CODE             | [da694ad588](https://linux-hardware.org/?probe=da694ad588) | Oct 04, 2022 |
| OEM           | Unknown                     | [ab6e21774c](https://linux-hardware.org/?probe=ab6e21774c) | Oct 04, 2022 |
| ASUSTek       | P6T WS PRO                  | [fb442877c5](https://linux-hardware.org/?probe=fb442877c5) | Oct 04, 2022 |
| ASUSTek       | Z87-DELUXE                  | [59bc735625](https://linux-hardware.org/?probe=59bc735625) | Oct 04, 2022 |
| Sapphire      | IPC-E350M1                  | [e9a9db8e30](https://linux-hardware.org/?probe=e9a9db8e30) | Oct 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c8e379037f](https://linux-hardware.org/?probe=c8e379037f) | Oct 03, 2022 |
| ASUSTek       | D300TA                      | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
| ASUSTek       | A68HM-K                     | [80f73c9aa8](https://linux-hardware.org/?probe=80f73c9aa8) | Oct 03, 2022 |
| ASUSTek       | Leonite2                    | [45ac930d40](https://linux-hardware.org/?probe=45ac930d40) | Oct 03, 2022 |
| Gigabyte      | Z97-HD3                     | [eccf4c45f5](https://linux-hardware.org/?probe=eccf4c45f5) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | P67X-UD3-B3                 | [a63ce26ce2](https://linux-hardware.org/?probe=a63ce26ce2) | Oct 02, 2022 |
| Gigabyte      | EP41-UD3L                   | [30464f2c62](https://linux-hardware.org/?probe=30464f2c62) | Oct 02, 2022 |
| Gigabyte      | B460M DS3H                  | [1f51daf0c8](https://linux-hardware.org/?probe=1f51daf0c8) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [77a9b37139](https://linux-hardware.org/?probe=77a9b37139) | Oct 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [00b0117f9a](https://linux-hardware.org/?probe=00b0117f9a) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| MSI           | H61M-P21                    | [f2f4c990bb](https://linux-hardware.org/?probe=f2f4c990bb) | Oct 02, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [391941d8b5](https://linux-hardware.org/?probe=391941d8b5) | Oct 02, 2022 |
| ASRock        | B550 Pro4                   | [6b42ddfd47](https://linux-hardware.org/?probe=6b42ddfd47) | Oct 02, 2022 |
| Gigabyte      | Z97-HD3                     | [0085eb8249](https://linux-hardware.org/?probe=0085eb8249) | Oct 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ade6e8d765](https://linux-hardware.org/?probe=ade6e8d765) | Oct 02, 2022 |
| Huanan        | H97-ZD3 V2.0                | [283a2e4ee5](https://linux-hardware.org/?probe=283a2e4ee5) | Oct 02, 2022 |
| ASRock        | J5005-ITX                   | [783c72d32e](https://linux-hardware.org/?probe=783c72d32e) | Oct 01, 2022 |
| MSI           | MS-7235                     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| MSI           | B450M-A PRO MAX             | [649f4ec8c6](https://linux-hardware.org/?probe=649f4ec8c6) | Oct 01, 2022 |
| Unknown       | Unknown                     | [0c82fc9806](https://linux-hardware.org/?probe=0c82fc9806) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| ASUSTek       | H81-PLUS                    | [e251d6b8f7](https://linux-hardware.org/?probe=e251d6b8f7) | Sep 30, 2022 |
| ASRock        | B450M Pro4-F                | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| ASUSTek       | PRIME B660M-K D4            | [7efad28576](https://linux-hardware.org/?probe=7efad28576) | Sep 30, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8d8e54ed69](https://linux-hardware.org/?probe=8d8e54ed69) | Sep 30, 2022 |
| ASRock        | B360M-HDV                   | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| HP            | 859C                        | [08161b9516](https://linux-hardware.org/?probe=08161b9516) | Sep 30, 2022 |
| MSI           | B450M MORTAR MAX            | [21028f343b](https://linux-hardware.org/?probe=21028f343b) | Sep 30, 2022 |
| ASRock        | N68C-S UCC                  | [90d8579454](https://linux-hardware.org/?probe=90d8579454) | Sep 30, 2022 |
| ASUSTek       | Maximus V GENE              | [7998f02578](https://linux-hardware.org/?probe=7998f02578) | Sep 29, 2022 |
| ASUSTek       | B85M-G                      | [a9983b2858](https://linux-hardware.org/?probe=a9983b2858) | Sep 29, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| ASUSTek       | B85M-G                      | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| HP            | 805D                        | [84d451ab19](https://linux-hardware.org/?probe=84d451ab19) | Sep 29, 2022 |
| ASUSTek       | H81M-D                      | [a1580941c3](https://linux-hardware.org/?probe=a1580941c3) | Sep 29, 2022 |
| ECS           | G31T-M9                     | [45b25aaf8c](https://linux-hardware.org/?probe=45b25aaf8c) | Sep 29, 2022 |
| Biostar       | IH61MF-Q5                   | [7a63314188](https://linux-hardware.org/?probe=7a63314188) | Sep 29, 2022 |
| ASUSTek       | M4A785T-M                   | [03277d55bc](https://linux-hardware.org/?probe=03277d55bc) | Sep 28, 2022 |
| MSI           | G41M-P26                    | [45f0101515](https://linux-hardware.org/?probe=45f0101515) | Sep 28, 2022 |
| HP            | 339A                        | [5c961ef93f](https://linux-hardware.org/?probe=5c961ef93f) | Sep 28, 2022 |
| Gigabyte      | B560M H                     | [80e3cd655a](https://linux-hardware.org/?probe=80e3cd655a) | Sep 28, 2022 |
| Gigabyte      | B560M H                     | [0192951511](https://linux-hardware.org/?probe=0192951511) | Sep 28, 2022 |
| HP            | 339A                        | [ac9538b489](https://linux-hardware.org/?probe=ac9538b489) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [2c82f3311d](https://linux-hardware.org/?probe=2c82f3311d) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [82b108b3b8](https://linux-hardware.org/?probe=82b108b3b8) | Sep 28, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [3def6cd1c2](https://linux-hardware.org/?probe=3def6cd1c2) | Sep 28, 2022 |
| ASUSTek       | H87-PLUS                    | [ccb24cd91e](https://linux-hardware.org/?probe=ccb24cd91e) | Sep 28, 2022 |
| Gigabyte      | 970A-DS3P                   | [ada186ce05](https://linux-hardware.org/?probe=ada186ce05) | Sep 27, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [03fff6add6](https://linux-hardware.org/?probe=03fff6add6) | Sep 27, 2022 |
| MSI           | B365M PRO-VDH               | [45e07c7119](https://linux-hardware.org/?probe=45e07c7119) | Sep 27, 2022 |
| ASUSTek       | P8H61-M LE                  | [0d9fdddd8a](https://linux-hardware.org/?probe=0d9fdddd8a) | Sep 27, 2022 |
| HP            | 339A                        | [25ef7556cc](https://linux-hardware.org/?probe=25ef7556cc) | Sep 27, 2022 |
| Gigabyte      | B360M HD3                   | [1107ba42b7](https://linux-hardware.org/?probe=1107ba42b7) | Sep 27, 2022 |
| Dell          | 0Y5DDC A00                  | [a135b97045](https://linux-hardware.org/?probe=a135b97045) | Sep 27, 2022 |
| Unknown       | Unknown                     | [128a8b6e2f](https://linux-hardware.org/?probe=128a8b6e2f) | Sep 27, 2022 |
| Gigabyte      | B450M S2H                   | [b5cc268970](https://linux-hardware.org/?probe=b5cc268970) | Sep 27, 2022 |
| ASUSTek       | Maximus V GENE              | [fc7a783877](https://linux-hardware.org/?probe=fc7a783877) | Sep 26, 2022 |
| Huanan        | X99-F8                      | [24c118fb0c](https://linux-hardware.org/?probe=24c118fb0c) | Sep 26, 2022 |
| Biostar       | TH67XE                      | [24df0079b5](https://linux-hardware.org/?probe=24df0079b5) | Sep 26, 2022 |
| Huanan        | X99 F8D V2.2                | [7663168534](https://linux-hardware.org/?probe=7663168534) | Sep 26, 2022 |
| ASRock        | 960GM-VGS3 FX               | [45bf4d54bf](https://linux-hardware.org/?probe=45bf4d54bf) | Sep 26, 2022 |
| ASUSTek       | H81M-K                      | [c449af2ab6](https://linux-hardware.org/?probe=c449af2ab6) | Sep 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| ROSA R11          | 1603     | 12.46%  |
| ROSA R10          | 1538     | 11.96%  |
| ROSA R8.1         | 1139     | 8.85%   |
| ROSA R8           | 1050     | 8.16%   |
| ROSA R9           | 928      | 7.21%   |
| ROSA 12.2         | 904      | 7.03%   |
| ROSA R11.1        | 859      | 6.68%   |
| Debian 11         | 630      | 4.9%    |
| Ubuntu 20.04      | 331      | 2.57%   |
| OpenMandriva 4.2  | 227      | 1.76%   |
| ROSA 12.3         | 212      | 1.65%   |
| Ubuntu 18.04      | 198      | 1.54%   |
| OpenMandriva 4.3  | 153      | 1.19%   |
| ROSA 12.1         | 143      | 1.11%   |
| Arch Rolling      | 93       | 0.72%   |
| Ubuntu 22.04      | 92       | 0.72%   |
| ROSA 12           | 91       | 0.71%   |
| KDE neon 20.04    | 87       | 0.68%   |
| Kometa P10        | 81       | 0.63%   |
| Debian 10         | 81       | 0.63%   |
| Arch              | 68       | 0.53%   |
| Xubuntu 20.04     | 62       | 0.48%   |
| RED X3            | 56       | 0.44%   |
| Linux Mint 20.3   | 54       | 0.42%   |
| Manjaro           | 52       | 0.4%    |
| RED X4            | 51       | 0.4%    |
| Linux Mint 18.3   | 51       | 0.4%    |
| Kubuntu 20.04     | 51       | 0.4%    |
| Fedora 36         | 47       | 0.37%   |
| Linux Mint 19.3   | 43       | 0.33%   |
| Linux Mint 19.1   | 43       | 0.33%   |
| Red OS 7.3.1      | 41       | 0.32%   |
| ROSA R12          | 38       | 0.3%    |
| Linux Mint 20     | 38       | 0.3%    |
| OpenMandriva 4.50 | 37       | 0.29%   |
| Linux Mint 20.2   | 33       | 0.26%   |
| Linux Mint 20.1   | 33       | 0.26%   |
| Fedora 35         | 33       | 0.26%   |
| ROSA R7           | 32       | 0.25%   |
| Red OS 7.3        | 32       | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 7333     | 64.31%  |
| Debian       | 764      | 6.7%    |
| Ubuntu       | 741      | 6.5%    |
| OpenMandriva | 436      | 3.82%   |
| Linux Mint   | 370      | 3.24%   |
| Manjaro      | 215      | 1.89%   |
| Fedora       | 198      | 1.74%   |
| ALT Linux    | 187      | 1.64%   |
| Arch         | 156      | 1.37%   |
| RED          | 113      | 0.99%   |
| KDE neon     | 106      | 0.93%   |
| Xubuntu      | 101      | 0.89%   |
| Kubuntu      | 89       | 0.78%   |
| Red OS       | 85       | 0.75%   |
| Gentoo       | 56       | 0.49%   |
| Endless      | 53       | 0.46%   |
| Pop!_OS      | 44       | 0.39%   |
| openSUSE     | 34       | 0.3%    |
| Ubuntu MATE  | 27       | 0.24%   |
| Clear Linux  | 24       | 0.21%   |
| RELS         | 22       | 0.19%   |
| Elementary   | 21       | 0.18%   |
| CentOS       | 21       | 0.18%   |
| Zorin        | 18       | 0.16%   |
| Ubuntu Unity | 18       | 0.16%   |
| Lubuntu      | 17       | 0.15%   |
| ArcoLinux    | 16       | 0.14%   |
| LMDE         | 15       | 0.13%   |
| Kali         | 8        | 0.07%   |
| Astra Linux  | 7        | 0.06%   |
| EndeavourOS  | 6        | 0.05%   |
| Artix        | 6        | 0.05%   |
| Solus        | 5        | 0.04%   |
| Void Linux   | 4        | 0.04%   |
| Virtuozzo    | 4        | 0.04%   |
| Slackware    | 4        | 0.04%   |
| Parrot       | 4        | 0.04%   |
| MX           | 4        | 0.04%   |
| Devuan       | 4        | 0.04%   |
| Calculate    | 4        | 0.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 771      | 5.56%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 700      | 5.05%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 697      | 5.03%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 667      | 4.81%   |
| 5.10.0-7-amd64                      | 472      | 3.4%    |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 401      | 2.89%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 332      | 2.39%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 318      | 2.29%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 255      | 1.84%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 250      | 1.8%    |
| 5.10.14-desktop-1omv4002            | 216      | 1.56%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 205      | 1.48%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 196      | 1.41%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 196      | 1.41%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 195      | 1.41%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 189      | 1.36%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 183      | 1.32%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 178      | 1.28%   |
| 4.15.0-desktop-45.1rosa-i586        | 168      | 1.21%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 165      | 1.19%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 165      | 1.19%   |
| 5.4.32-generic-2rosa-x86_64         | 156      | 1.13%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 151      | 1.09%   |
| 5.16.7-desktop-1omv4003             | 149      | 1.07%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 148      | 1.07%   |
| 5.4.83-generic-2rosa-x86_64         | 145      | 1.05%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 137      | 0.99%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 112      | 0.81%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 112      | 0.81%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 92       | 0.66%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 91       | 0.66%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 89       | 0.64%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 83       | 0.6%    |
| 5.10.0-2-amd64                      | 71       | 0.51%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 70       | 0.5%    |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 65       | 0.47%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 64       | 0.46%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 64       | 0.46%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 64       | 0.46%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 56       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 2000     | 14.91%  |
| 4.9.60   | 884      | 6.59%   |
| 4.9.20   | 846      | 6.31%   |
| 5.10.74  | 784      | 5.84%   |
| 5.10.0   | 629      | 4.69%   |
| 4.1.34   | 546      | 4.07%   |
| 5.4.0    | 526      | 3.92%   |
| 4.1.38   | 434      | 3.23%   |
| 4.1.25   | 430      | 3.21%   |
| 4.9.9    | 402      | 3%      |
| 4.9.124  | 395      | 2.94%   |
| 4.9.155  | 260      | 1.94%   |
| 4.9.76   | 251      | 1.87%   |
| 4.9.41   | 250      | 1.86%   |
| 5.10.14  | 216      | 1.61%   |
| 5.4.32   | 208      | 1.55%   |
| 5.15.0   | 196      | 1.46%   |
| 5.4.83   | 184      | 1.37%   |
| 5.10.118 | 168      | 1.25%   |
| 5.16.7   | 150      | 1.12%   |
| 5.8.0    | 139      | 1.04%   |
| 5.3.0    | 137      | 1.02%   |
| 5.11.0   | 128      | 0.95%   |
| 4.9.95   | 120      | 0.89%   |
| 5.0.0    | 110      | 0.82%   |
| 4.9.111  | 104      | 0.78%   |
| 5.13.0   | 90       | 0.67%   |
| 5.10.71  | 90       | 0.67%   |
| 4.9.87   | 82       | 0.61%   |
| 4.18.0   | 81       | 0.6%    |
| 5.15.75  | 75       | 0.56%   |
| 4.19.0   | 71       | 0.53%   |
| 5.10.109 | 51       | 0.38%   |
| 4.9.14   | 48       | 0.36%   |
| 5.15.79  | 46       | 0.34%   |
| 5.4.40   | 39       | 0.29%   |
| 4.13.0   | 38       | 0.28%   |
| 4.9.34   | 37       | 0.28%   |
| 3.10.0   | 37       | 0.28%   |
| 5.17.11  | 36       | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 3194     | 25.5%   |
| 5.10    | 2072     | 16.54%  |
| 4.15    | 2012     | 16.06%  |
| 4.1     | 1369     | 10.93%  |
| 5.4     | 1090     | 8.7%    |
| 5.15    | 557      | 4.45%   |
| 5.16    | 209      | 1.67%   |
| 5.11    | 206      | 1.64%   |
| 5.8     | 196      | 1.56%   |
| 5.3     | 186      | 1.49%   |
| 5.0     | 129      | 1.03%   |
| 5.13    | 126      | 1.01%   |
| 5.18    | 120      | 0.96%   |
| 4.19    | 106      | 0.85%   |
| 4.18    | 91       | 0.73%   |
| 6.0     | 72       | 0.57%   |
| 5.17    | 71       | 0.57%   |
| 5.6     | 60       | 0.48%   |
| 5.19    | 60       | 0.48%   |
| 5.9     | 57       | 0.46%   |
| 5.14    | 55       | 0.44%   |
| 4.4     | 52       | 0.42%   |
| 4.13    | 51       | 0.41%   |
| 5.12    | 47       | 0.38%   |
| 5.7     | 38       | 0.3%    |
| 3.10    | 37       | 0.3%    |
| 4.8     | 36       | 0.29%   |
| 5.5     | 26       | 0.21%   |
| 4.14    | 26       | 0.21%   |
| 4.16    | 25       | 0.2%    |
| 3.14    | 23       | 0.18%   |
| 5.2     | 21       | 0.17%   |
| 4.10    | 20       | 0.16%   |
| 4.20    | 13       | 0.1%    |
| 4.17    | 13       | 0.1%    |
| 4.12    | 13       | 0.1%    |
| 4.11    | 11       | 0.09%   |
| 4.7     | 8        | 0.06%   |
| 6.1     | 7        | 0.06%   |
| 5.1     | 4        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 9606     | 85.62%  |
| i686   | 1607     | 14.32%  |
| e2k    | 4        | 0.04%   |
| ppc64  | 1        | 0.01%   |
| armv6l | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KDE4             | 4709     | 39.66%  |
| KDE5             | 3101     | 26.12%  |
| GNOME            | 1467     | 12.36%  |
| Unknown          | 1040     | 8.76%   |
| XFCE             | 341      | 2.87%   |
| MATE             | 299      | 2.52%   |
| LXQt             | 296      | 2.49%   |
| Cinnamon         | 184      | 1.55%   |
| X-Cinnamon       | 162      | 1.36%   |
| KDE              | 137      | 1.15%   |
| LXDE             | 23       | 0.19%   |
| Pantheon         | 20       | 0.17%   |
| Unity            | 18       | 0.15%   |
| Budgie           | 11       | 0.09%   |
| i3               | 10       | 0.08%   |
| GNOME Flashback  | 8        | 0.07%   |
| Deepin           | 8        | 0.07%   |
| GNOME Classic    | 7        | 0.06%   |
| openbox          | 6        | 0.05%   |
| awesome          | 5        | 0.04%   |
| fly              | 4        | 0.03%   |
| bspwm            | 3        | 0.03%   |
| xmonad           | 2        | 0.02%   |
| sway             | 2        | 0.02%   |
| lightdm-xsession | 2        | 0.02%   |
| ICEWM            | 2        | 0.02%   |
| Hyprland         | 2        | 0.02%   |
| X-Generic        | 1        | 0.01%   |
| Trinity          | 1        | 0.01%   |
| i3-with-shmlog   | 1        | 0.01%   |
| DWM              | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 9237     | 81.07%  |
| Wayland | 1322     | 11.6%   |
| Unknown | 727      | 6.38%   |
| Tty     | 108      | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 4751     | 40.18%  |
| SDDM    | 3185     | 26.94%  |
| Unknown | 1842     | 15.58%  |
| GDM     | 1166     | 9.86%   |
| LightDM | 326      | 2.76%   |
| TDM     | 320      | 2.71%   |
| GDM3    | 180      | 1.52%   |
| MDM     | 22       | 0.19%   |
| XDM     | 10       | 0.08%   |
| SLiM    | 7        | 0.06%   |
| LXDM    | 5        | 0.04%   |
| FLY-DM  | 5        | 0.04%   |
| Ly      | 2        | 0.02%   |
| WDM     | 1        | 0.01%   |
| LDM     | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 6219     | 53.77%  |
| ru_RU       | 4519     | 39.07%  |
| en_US       | 727      | 6.29%   |
| C           | 38       | 0.33%   |
| en_GB       | 16       | 0.14%   |
| ru_RU.UTF_8 | 9        | 0.08%   |
| C.UTF8      | 7        | 0.06%   |
| ru_UA       | 6        | 0.05%   |
| ru_RU.UTF8  | 6        | 0.05%   |
| POSIX       | 3        | 0.03%   |
| cv_RU       | 3        | 0.03%   |
| tt_RU       | 2        | 0.02%   |
| en_DK       | 2        | 0.02%   |
| ba_RU       | 2        | 0.02%   |
| zh_CN       | 1        | 0.01%   |
| uk_UA       | 1        | 0.01%   |
| myv_RU      | 1        | 0.01%   |
| fr_FR       | 1        | 0.01%   |
| en_RU       | 1        | 0.01%   |
| en_CA       | 1        | 0.01%   |
| en_AG       | 1        | 0.01%   |
| de_DE       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 8333     | 73.33%  |
| EFI  | 3031     | 26.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 6303     | 53.51%  |
| Unknown  | 3833     | 32.54%  |
| Overlay  | 981      | 8.33%   |
| Btrfs    | 437      | 3.71%   |
| Xfs      | 90       | 0.76%   |
| Ext3     | 41       | 0.35%   |
| Zfs      | 33       | 0.28%   |
| F2fs     | 20       | 0.17%   |
| Ext2     | 19       | 0.16%   |
| Aufs     | 5        | 0.04%   |
| XXXXXXX  | 3        | 0.03%   |
| SAMSUNG  | 3        | 0.03%   |
| Reiserfs | 3        | 0.03%   |
| Jfs      | 3        | 0.03%   |
| Tmpfs    | 2        | 0.02%   |
| Rootfs   | 2        | 0.02%   |
| XXXXX    | 1        | 0.01%   |
| Exfat    | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 5622     | 47.55%  |
| GPT     | 3288     | 27.81%  |
| Unknown | 2914     | 24.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9682     | 84.1%   |
| Yes       | 1831     | 15.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7434     | 63.81%  |
| Yes       | 4216     | 36.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 3998     | 36.07%  |
| Gigabyte Technology | 2722     | 24.56%  |
| ASRock              | 1219     | 11%     |
| MSI                 | 1166     | 10.52%  |
| Intel               | 333      | 3%      |
| ECS                 | 254      | 2.29%   |
| Hewlett-Packard     | 169      | 1.52%   |
| Unknown             | 166      | 1.5%    |
| Acer                | 142      | 1.28%   |
| Biostar             | 118      | 1.06%   |
| Foxconn             | 115      | 1.04%   |
| Lenovo              | 95       | 0.86%   |
| Dell                | 93       | 0.84%   |
| Pegatron            | 81       | 0.73%   |
| Huanan              | 70       | 0.63%   |
| EPoX Computer       | 21       | 0.19%   |
| WinFast             | 20       | 0.18%   |
| DEPO Computers      | 20       | 0.18%   |
| Fujitsu             | 18       | 0.16%   |
| Supermicro          | 17       | 0.15%   |
| Fujitsu Siemens     | 12       | 0.11%   |
| Nvidia              | 10       | 0.09%   |
| Aquarius            | 10       | 0.09%   |
| AMD                 | 10       | 0.09%   |
| MACHINIST           | 9        | 0.08%   |
| AZW                 | 9        | 0.08%   |
| Kraftway            | 8        | 0.07%   |
| JW Technology       | 8        | 0.07%   |
| SiS Technology      | 7        | 0.06%   |
| Shuttle             | 7        | 0.06%   |
| OEM                 | 6        | 0.05%   |
| Kllisre             | 6        | 0.05%   |
| ABIT                | 6        | 0.05%   |
| Packard Bell        | 5        | 0.05%   |
| Lite-On             | 5        | 0.05%   |
| IBM                 | 5        | 0.05%   |
| eMachines           | 5        | 0.05%   |
| Colorful Technology | 5        | 0.05%   |
| AMI                 | 5        | 0.05%   |
| Koloe               | 4        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 352      | 3.18%   |
| Unknown                    | 182      | 1.64%   |
| Gigabyte 970A-DS3P         | 70       | 0.63%   |
| MSI MS-7996                | 69       | 0.62%   |
| ASUS M5A78L-M LX3          | 67       | 0.6%    |
| MSI MS-7817                | 65       | 0.59%   |
| ASUS P8H61-M LX3 R2.0      | 58       | 0.52%   |
| ASUS H110M-R               | 56       | 0.51%   |
| ASUS S20 K29               | 55       | 0.5%    |
| Intel SKYBAY               | 46       | 0.42%   |
| ASRock G31M-S              | 46       | 0.42%   |
| ASUS P5K                   | 45       | 0.41%   |
| ASUS M5A97 R2.0            | 45       | 0.41%   |
| MSI MS-7529                | 43       | 0.39%   |
| Gigabyte H61M-S1           | 43       | 0.39%   |
| Gigabyte G31M-ES2L         | 43       | 0.39%   |
| ASUS P5KPL-AM              | 40       | 0.36%   |
| ASUS P5G41T-M LX2/GB       | 40       | 0.36%   |
| ASUS M5A78L-M/USB3         | 39       | 0.35%   |
| ASRock N68C-S UCC          | 39       | 0.35%   |
| Gigabyte H61M-S2PV         | 38       | 0.34%   |
| MSI MS-7592                | 37       | 0.33%   |
| ASUS M5A97 LE R2.0         | 37       | 0.33%   |
| Gigabyte Z77-DS3H          | 33       | 0.3%    |
| ASUS PRIME A320M-K         | 33       | 0.3%    |
| ASUS P5B                   | 33       | 0.3%    |
| ASUS A68HM-K               | 33       | 0.3%    |
| ASUS P5KPL-AM IN/ROEM/SI   | 32       | 0.29%   |
| ECS G31T-M9                | 31       | 0.28%   |
| ASRock G41M-VS3            | 31       | 0.28%   |
| MSI MS-7721                | 30       | 0.27%   |
| Gigabyte GA-78LMT-S2       | 30       | 0.27%   |
| ASUS P8Z77-V LX            | 30       | 0.27%   |
| ASUS P5Q SE2               | 30       | 0.27%   |
| MSI MS-7693                | 29       | 0.26%   |
| Gigabyte GA-78LMT-S2P      | 29       | 0.26%   |
| ASUS PRIME H310M-R R2.0    | 28       | 0.25%   |
| ASUS H110M-K               | 28       | 0.25%   |
| MSI MS-7309                | 27       | 0.24%   |
| ASUS SABERTOOTH 990FX R2.0 | 27       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 362      | 3.27%   |
| ASUS All           | 352      | 3.18%   |
| Unknown            | 182      | 1.64%   |
| ASUS P8H61-M       | 181      | 1.63%   |
| ASUS M5A78L-M      | 175      | 1.58%   |
| ASUS P5KPL-AM      | 123      | 1.11%   |
| ASUS M5A97         | 111      | 1%      |
| ASUS P5G41T-M      | 101      | 0.91%   |
| ASUS P5K           | 94       | 0.85%   |
| Acer Aspire        | 89       | 0.8%    |
| ASUS P8Z77-V       | 84       | 0.76%   |
| Gigabyte 970A-DS3P | 71       | 0.64%   |
| ASUS P5Q           | 71       | 0.64%   |
| MSI MS-7996        | 69       | 0.62%   |
| ASUS TUF           | 66       | 0.6%    |
| MSI MS-7817        | 65       | 0.59%   |
| ASUS ROG           | 65       | 0.59%   |
| HP Compaq          | 64       | 0.58%   |
| Dell OptiPlex      | 64       | 0.58%   |
| Gigabyte B450M     | 61       | 0.55%   |
| ASUS H110M-R       | 56       | 0.51%   |
| ASUS S20           | 55       | 0.5%    |
| Gigabyte B450      | 53       | 0.48%   |
| ASUS P8H67-M       | 52       | 0.47%   |
| ASUS P8H77-V       | 48       | 0.43%   |
| ASUS SABERTOOTH    | 47       | 0.42%   |
| Intel SKYBAY       | 46       | 0.42%   |
| ASRock G31M-S      | 46       | 0.42%   |
| ASUS P8H61-MX      | 44       | 0.4%    |
| MSI MS-7529        | 43       | 0.39%   |
| Lenovo ThinkCentre | 43       | 0.39%   |
| Gigabyte H61M-S1   | 43       | 0.39%   |
| Gigabyte G31M-ES2L | 43       | 0.39%   |
| ASUS P8B75-M       | 41       | 0.37%   |
| ASUS P7H55-M       | 41       | 0.37%   |
| Gigabyte A320M-S2H | 40       | 0.36%   |
| ASRock N68C-S      | 40       | 0.36%   |
| Acer Veriton       | 40       | 0.36%   |
| Gigabyte H310M     | 39       | 0.35%   |
| ASUS P5B           | 39       | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 1562     | 14.09%  |
| 2009    | 982      | 8.86%   |
| 2011    | 977      | 8.82%   |
| 2010    | 885      | 7.99%   |
| 2013    | 814      | 7.34%   |
| 2018    | 784      | 7.07%   |
| 2008    | 748      | 6.75%   |
| 2007    | 714      | 6.44%   |
| 2016    | 490      | 4.42%   |
| 2006    | 460      | 4.15%   |
| 2014    | 435      | 3.92%   |
| 2017    | 420      | 3.79%   |
| 2019    | 393      | 3.55%   |
| 2015    | 373      | 3.37%   |
| 2020    | 365      | 3.29%   |
| 2021    | 287      | 2.59%   |
| 2005    | 194      | 1.75%   |
| 2004    | 69       | 0.62%   |
| 2022    | 61       | 0.55%   |
| 2003    | 40       | 0.36%   |
| Unknown | 18       | 0.16%   |
| 2002    | 7        | 0.06%   |
| 2001    | 4        | 0.04%   |
| 2000    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 11083    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11025    | 99.44%  |
| Enabled  | 62       | 0.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11081    | 99.98%  |
| Yes  | 2        | 0.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 2960     | 25.62%  |
| 8.01-16.0       | 2588     | 22.4%   |
| 4.01-8.0        | 1810     | 15.67%  |
| 16.01-24.0      | 1594     | 13.8%   |
| 1.01-2.0        | 994      | 8.6%    |
| 2.01-3.0        | 639      | 5.53%   |
| 32.01-64.0      | 544      | 4.71%   |
| 0.51-1.0        | 155      | 1.34%   |
| 64.01-256.0     | 132      | 1.14%   |
| 24.01-32.0      | 118      | 1.02%   |
| 0.01-0.5        | 13       | 0.11%   |
| More than 256.0 | 3        | 0.03%   |
| Unknown         | 3        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 4801     | 38.27%  |
| 0.51-1.0    | 4447     | 35.45%  |
| 2.01-3.0    | 1458     | 11.62%  |
| 4.01-8.0    | 693      | 5.52%   |
| 3.01-4.0    | 586      | 4.67%   |
| 0.01-0.5    | 281      | 2.24%   |
| 8.01-16.0   | 194      | 1.55%   |
| 16.01-24.0  | 48       | 0.38%   |
| 32.01-64.0  | 14       | 0.11%   |
| 24.01-32.0  | 11       | 0.09%   |
| Unknown     | 9        | 0.07%   |
| 64.01-256.0 | 2        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 5853     | 49.91%  |
| 2       | 3175     | 27.07%  |
| 3       | 1544     | 13.17%  |
| 4       | 654      | 5.58%   |
| 5       | 272      | 2.32%   |
| 6       | 88       | 0.75%   |
| 0       | 74       | 0.63%   |
| 7       | 33       | 0.28%   |
| 8       | 17       | 0.14%   |
| 9       | 8        | 0.07%   |
| 10      | 2        | 0.02%   |
| Unknown | 2        | 0.02%   |
| 18      | 1        | 0.01%   |
| 17      | 1        | 0.01%   |
| 13      | 1        | 0.01%   |
| 12      | 1        | 0.01%   |
| 11      | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5741     | 50.59%  |
| Yes       | 5607     | 49.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10979    | 99.05%  |
| No        | 105      | 0.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8657     | 76.85%  |
| Yes       | 2608     | 23.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9786     | 87.17%  |
| Yes       | 1440     | 12.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 11083    | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 1879     | 15.92%  |
| St Petersburg    | 765      | 6.48%   |
| Voronezh         | 713      | 6.04%   |
| Pecherskoye      | 421      | 3.57%   |
| Novosibirsk      | 361      | 3.06%   |
| Yekaterinburg    | 300      | 2.54%   |
| Krasnodar        | 258      | 2.19%   |
| Samara           | 232      | 1.97%   |
| Nizhniy Novgorod | 231      | 1.96%   |
| Rostov-on-Don    | 216      | 1.83%   |
| Chelyabinsk      | 190      | 1.61%   |
| Perm             | 189      | 1.6%    |
| Krasnoyarsk      | 147      | 1.25%   |
| Saratov          | 134      | 1.14%   |
| Omsk             | 132      | 1.12%   |
| Volgograd        | 111      | 0.94%   |
| Kazan’         | 111      | 0.94%   |
| Ufa              | 109      | 0.92%   |
| Vladivostok      | 101      | 0.86%   |
| Barnaul          | 101      | 0.86%   |
| Stavropol        | 98       | 0.83%   |
| Tyumen           | 95       | 0.8%    |
| Khabarovsk       | 92       | 0.78%   |
| Irkutsk          | 92       | 0.78%   |
| Ulyanovsk        | 78       | 0.66%   |
| Orenburg         | 76       | 0.64%   |
| Tomsk            | 74       | 0.63%   |
| Bryansk          | 72       | 0.61%   |
| Belgorod         | 71       | 0.6%    |
| Kemerovo         | 69       | 0.58%   |
| Novokuznetsk     | 68       | 0.58%   |
| Tula             | 66       | 0.56%   |
| Tolyatti         | 66       | 0.56%   |
| Cheboksary       | 66       | 0.56%   |
| Yaroslavl        | 65       | 0.55%   |
| Kaliningrad      | 61       | 0.52%   |
| Lipetsk          | 60       | 0.51%   |
| Izhevsk          | 59       | 0.5%    |
| Ryazan           | 58       | 0.49%   |
| Murmansk         | 57       | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4575     | 7423   | 25.22%  |
| WDC                 | 4450     | 7611   | 24.53%  |
| Samsung Electronics | 1611     | 2429   | 8.88%   |
| Toshiba             | 1232     | 1832   | 6.79%   |
| Hitachi             | 1003     | 1372   | 5.53%   |
| Kingston            | 931      | 1270   | 5.13%   |
| A-DATA Technology   | 304      | 419    | 1.68%   |
| SPCC                | 282      | 358    | 1.55%   |
| China               | 281      | 399    | 1.55%   |
| Maxtor              | 271      | 344    | 1.49%   |
| Crucial             | 271      | 362    | 1.49%   |
| OCZ                 | 223      | 293    | 1.23%   |
| SanDisk             | 200      | 287    | 1.1%    |
| Intel               | 200      | 342    | 1.1%    |
| Plextor             | 184      | 285    | 1.01%   |
| HGST                | 176      | 268    | 0.97%   |
| Apacer              | 158      | 216    | 0.87%   |
| Smartbuy            | 110      | 148    | 0.61%   |
| AMD                 | 102      | 127    | 0.56%   |
| Patriot             | 96       | 128    | 0.53%   |
| HUAWEI              | 88       | 103    | 0.49%   |
| Corsair             | 79       | 117    | 0.44%   |
| GOODRAM             | 77       | 106    | 0.42%   |
| Transcend           | 74       | 93     | 0.41%   |
| Silicon Motion      | 69       | 86     | 0.38%   |
| KingSpec            | 67       | 85     | 0.37%   |
| Unknown             | 60       | 94     | 0.33%   |
| Netac               | 58       | 128    | 0.32%   |
| Phison              | 48       | 55     | 0.26%   |
| Gigabyte Technology | 48       | 58     | 0.26%   |
| KingDian            | 43       | 69     | 0.24%   |
| XPG                 | 41       | 50     | 0.23%   |
| Fujitsu             | 37       | 43     | 0.2%    |
| Kingmax             | 35       | 61     | 0.19%   |
| JMicron Technology  | 31       | 32     | 0.17%   |
| Foxline             | 30       | 35     | 0.17%   |
| AXIOMTEK            | 26       | 26     | 0.14%   |
| XrayDisk            | 23       | 31     | 0.13%   |
| ZTE                 | 22       | 26     | 0.12%   |
| Hewlett-Packard     | 21       | 31     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 367      | 1.76%   |
| Toshiba DT01ACA050 500GB         | 257      | 1.23%   |
| Seagate ST3500418AS 500GB        | 241      | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB   | 237      | 1.14%   |
| Toshiba HDWD110 1TB              | 227      | 1.09%   |
| WDC WD10EZEX-08WN4A0 1TB         | 209      | 1%      |
| Seagate ST1000DM003-1CH162 1TB   | 192      | 0.92%   |
| Toshiba DT01ACA100 1TB           | 189      | 0.91%   |
| Kingston SA400S37120G 120GB SSD  | 147      | 0.7%    |
| Kingston SV300S37A120G 120GB SSD | 144      | 0.69%   |
| Samsung SSD 860 EVO 250GB        | 137      | 0.66%   |
| Kingston SA400S37240G 240GB SSD  | 137      | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB      | 136      | 0.65%   |
| Seagate ST3250410AS 250GB        | 130      | 0.62%   |
| Seagate ST380011A 80GB           | 128      | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 122      | 0.58%   |
| Seagate ST380815AS 80GB          | 121      | 0.58%   |
| Seagate ST31000524AS 1TB         | 119      | 0.57%   |
| Seagate ST3160815AS 160GB        | 116      | 0.56%   |
| Seagate ST31000528AS 1TB         | 112      | 0.54%   |
| Hitachi HDS721050CLA362 500GB    | 112      | 0.54%   |
| Seagate ST3250310AS 250GB        | 110      | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB   | 110      | 0.53%   |
| Seagate ST1000DM003-9YN162 1TB   | 102      | 0.49%   |
| Toshiba HDWD105 500GB            | 96       | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 95       | 0.46%   |
| Seagate ST3250318AS 250GB        | 88       | 0.42%   |
| Seagate ST250DM000-1BD141 250GB  | 87       | 0.42%   |
| Crucial CT480BX500SSD1 480GB     | 85       | 0.41%   |
| Seagate ST3500413AS 500GB        | 84       | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 80       | 0.38%   |
| SPCC Solid State Disk 120GB      | 80       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB         | 78       | 0.37%   |
| Seagate ST3320613AS 320GB        | 78       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB   | 78       | 0.37%   |
| Seagate ST3320620AS 320GB        | 74       | 0.35%   |
| WDC WD5000AADS-00S9B0 500GB      | 71       | 0.34%   |
| Samsung SSD 860 EVO 500GB        | 70       | 0.34%   |
| Hitachi HDS721616PLA380 160GB    | 69       | 0.33%   |
| SPCC Solid State Disk 64GB       | 66       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4557     | 7382   | 37.31%  |
| WDC                 | 4173     | 6996   | 34.17%  |
| Toshiba             | 1178     | 1723   | 9.65%   |
| Hitachi             | 1003     | 1372   | 8.21%   |
| Samsung Electronics | 739      | 1063   | 6.05%   |
| Maxtor              | 270      | 343    | 2.21%   |
| HGST                | 176      | 268    | 1.44%   |
| Fujitsu             | 36       | 42     | 0.29%   |
| Unknown             | 19       | 25     | 0.16%   |
| IBM/Hitachi         | 12       | 15     | 0.1%    |
| Hewlett-Packard     | 8        | 11     | 0.07%   |
| IBM                 | 4        | 4      | 0.03%   |
| USB3.0              | 3        | 3      | 0.02%   |
| Quantum             | 3        | 3      | 0.02%   |
| WD MediaMax         | 2        | 2      | 0.02%   |
| Synology            | 2        | 3      | 0.02%   |
| PHD 3.0             | 2        | 2      | 0.02%   |
| ExcelStor           | 2        | 2      | 0.02%   |
| CLOVER              | 2        | 2      | 0.02%   |
| ASMT106x            | 2        | 3      | 0.02%   |
| ASMT                | 2        | 10     | 0.02%   |
| Apple               | 2        | 2      | 0.02%   |
| Unknown             | 2        | 2      | 0.02%   |
| USB 3.0             | 1        | 1      | 0.01%   |
| USB                 | 1        | 1      | 0.01%   |
| Silicon             | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| Pioneer             | 1        | 1      | 0.01%   |
| MR2020              | 1        | 1      | 0.01%   |
| MARVELL             | 1        | 1      | 0.01%   |
| LIO-ORG             | 1        | 1      | 0.01%   |
| KESU                | 1        | 1      | 0.01%   |
| JMicron Technology  | 1        | 1      | 0.01%   |
| IET                 | 1        | 2      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |
| ASMedia             | 1        | 2      | 0.01%   |
| AFAYA               | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 844      | 1150   | 16.92%  |
| Samsung Electronics | 603      | 872    | 12.09%  |
| WDC                 | 424      | 564    | 8.5%    |
| China               | 279      | 397    | 5.59%   |
| SPCC                | 266      | 338    | 5.33%   |
| Crucial             | 264      | 350    | 5.29%   |
| A-DATA Technology   | 252      | 328    | 5.05%   |
| OCZ                 | 222      | 292    | 4.45%   |
| SanDisk             | 169      | 245    | 3.39%   |
| Plextor             | 169      | 249    | 3.39%   |
| Intel               | 146      | 256    | 2.93%   |
| Apacer              | 140      | 195    | 2.81%   |
| Smartbuy            | 104      | 140    | 2.08%   |
| Patriot             | 91       | 122    | 1.82%   |
| AMD                 | 91       | 111    | 1.82%   |
| Toshiba             | 76       | 105    | 1.52%   |
| Corsair             | 74       | 108    | 1.48%   |
| GOODRAM             | 72       | 101    | 1.44%   |
| Transcend           | 67       | 84     | 1.34%   |
| KingSpec            | 66       | 84     | 1.32%   |
| Netac               | 50       | 118    | 1%      |
| KingDian            | 43       | 69     | 0.86%   |
| Gigabyte Technology | 37       | 41     | 0.74%   |
| Kingmax             | 35       | 61     | 0.7%    |
| Foxline             | 29       | 34     | 0.58%   |
| AXIOMTEK            | 26       | 26     | 0.52%   |
| JMicron Technology  | 20       | 20     | 0.4%    |
| XrayDisk            | 17       | 24     | 0.34%   |
| Qumo                | 13       | 17     | 0.26%   |
| Unknown             | 13       | 13     | 0.26%   |
| Seagate             | 12       | 22     | 0.24%   |
| Londisk             | 12       | 13     | 0.24%   |
| Zheino              | 10       | 12     | 0.2%    |
| Team                | 10       | 11     | 0.2%    |
| OCZ-VERTEX3         | 10       | 15     | 0.2%    |
| KingFast            | 10       | 14     | 0.2%    |
| Hewlett-Packard     | 10       | 16     | 0.2%    |
| Unknown             | 9        | 13     | 0.18%   |
| Palit               | 9        | 13     | 0.18%   |
| Micron Technology   | 9        | 13     | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 9447     | 19294  | 63.75%  |
| SSD     | 4206     | 6909   | 28.38%  |
| NVMe    | 934      | 1388   | 6.3%    |
| Unknown | 218      | 252    | 1.47%   |
| MMC     | 13       | 19     | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 10750    | 26005  | 89.12%  |
| NVMe | 929      | 1380   | 7.7%    |
| SAS  | 371      | 458    | 3.08%   |
| MMC  | 13       | 19     | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 9178     | 17401  | 63.72%  |
| 0.51-1.0        | 3738     | 6335   | 25.95%  |
| 1.01-2.0        | 958      | 1578   | 6.65%   |
| 2.01-3.0        | 219      | 356    | 1.52%   |
| 3.01-4.0        | 201      | 307    | 1.4%    |
| 4.01-10.0       | 89       | 194    | 0.62%   |
| 10.01-20.0      | 17       | 29     | 0.12%   |
| More than 100.0 | 1        | 1      | 0.01%   |
| 20.01-50.0      | 1        | 1      | 0.01%   |
| 0               | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 3143     | 25.24%  |
| 251-500        | 2140     | 17.19%  |
| 501-1000       | 1568     | 12.59%  |
| 1-20           | 1302     | 10.46%  |
| 51-100         | 1273     | 10.22%  |
| 1001-2000      | 954      | 7.66%   |
| 21-50          | 742      | 5.96%   |
| Unknown        | 669      | 5.37%   |
| 2001-3000      | 336      | 2.7%    |
| More than 3000 | 324      | 2.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 6635     | 53.12%  |
| 21-50          | 1239     | 9.92%   |
| 101-250        | 988      | 7.91%   |
| 251-500        | 825      | 6.61%   |
| 51-100         | 823      | 6.59%   |
| 501-1000       | 672      | 5.38%   |
| Unknown        | 669      | 5.36%   |
| 1001-2000      | 388      | 3.11%   |
| More than 3000 | 135      | 1.08%   |
| 2001-3000      | 115      | 0.92%   |
| 0              | 1        | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 137      | 174    | 2.58%   |
| Seagate ST3500418AS 500GB          | 105      | 134    | 1.98%   |
| Seagate ST3250410AS 250GB          | 86       | 108    | 1.62%   |
| WDC WD5000AAKX-001CA0 500GB        | 66       | 84     | 1.24%   |
| Seagate ST3250310AS 250GB          | 63       | 104    | 1.19%   |
| Seagate ST3320613AS 320GB          | 60       | 78     | 1.13%   |
| Seagate ST31000528AS 1TB           | 53       | 60     | 1%      |
| Seagate ST1000DM003-9YN162 1TB     | 53       | 63     | 1%      |
| Seagate ST1000DM003-1CH162 1TB     | 50       | 78     | 0.94%   |
| Hitachi HDS721050CLA362 500GB      | 46       | 53     | 0.87%   |
| WDC WD5000AADS-00S9B0 500GB        | 45       | 52     | 0.85%   |
| Seagate ST380011A 80GB             | 45       | 48     | 0.85%   |
| Seagate ST3160815AS 160GB          | 42       | 53     | 0.79%   |
| Seagate ST250DM000-1BD141 250GB    | 42       | 56     | 0.79%   |
| Seagate ST31000524AS 1TB           | 40       | 53     | 0.75%   |
| Seagate ST3250318AS 250GB          | 38       | 45     | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB        | 37       | 42     | 0.7%    |
| Hitachi HDS721010CLA332 1TB        | 37       | 44     | 0.7%    |
| WDC WD10EARS-00Y5B1 1TB            | 36       | 60     | 0.68%   |
| Hitachi HDS721616PLA380 160GB      | 36       | 49     | 0.68%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 35       | 43     | 0.66%   |
| Seagate ST380815AS 80GB            | 34       | 46     | 0.64%   |
| Seagate ST3160811AS 160GB          | 34       | 49     | 0.64%   |
| Samsung Electronics HD160JJ/ 160GB | 33       | 53     | 0.62%   |
| Samsung Electronics HD080HJ/ 80GB  | 32       | 42     | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 32       | 33     | 0.6%    |
| Maxtor STM3250310AS 250GB          | 30       | 39     | 0.56%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 28       | 37     | 0.53%   |
| Seagate ST3500413AS 500GB          | 28       | 30     | 0.53%   |
| Seagate ST31500341AS 1TB           | 28       | 36     | 0.53%   |
| Hitachi HDP725050GLA360 500GB      | 27       | 39     | 0.51%   |
| WDC WD5000AAKS-00V1A0 500GB        | 26       | 30     | 0.49%   |
| Seagate ST3320620AS 320GB          | 25       | 33     | 0.47%   |
| Samsung Electronics HD161HJ 160GB  | 25       | 31     | 0.47%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 21       | 26     | 0.4%    |
| Toshiba DT01ACA100 1TB             | 21       | 31     | 0.4%    |
| Toshiba DT01ACA050 500GB           | 21       | 32     | 0.4%    |
| Seagate ST3500320AS 500GB          | 21       | 25     | 0.4%    |
| Seagate ST3320418AS 320GB          | 21       | 24     | 0.4%    |
| Seagate ST1000DL002-9TT153 1TB     | 21       | 22     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1837     | 2639   | 37.12%  |
| WDC                 | 1486     | 2085   | 30.03%  |
| Hitachi             | 457      | 608    | 9.23%   |
| Samsung Electronics | 386      | 545    | 7.8%    |
| Maxtor              | 159      | 190    | 3.21%   |
| Toshiba             | 157      | 211    | 3.17%   |
| Kingston            | 92       | 103    | 1.86%   |
| OCZ                 | 47       | 63     | 0.95%   |
| SPCC                | 37       | 44     | 0.75%   |
| HGST                | 30       | 37     | 0.61%   |
| A-DATA Technology   | 30       | 44     | 0.61%   |
| Corsair             | 28       | 42     | 0.57%   |
| Intel               | 25       | 30     | 0.51%   |
| Kingmax             | 24       | 44     | 0.48%   |
| SanDisk             | 13       | 18     | 0.26%   |
| Plextor             | 12       | 23     | 0.24%   |
| KingSpec            | 11       | 12     | 0.22%   |
| IBM/Hitachi         | 11       | 14     | 0.22%   |
| Crucial             | 10       | 20     | 0.2%    |
| Fujitsu             | 9        | 10     | 0.18%   |
| China               | 9        | 11     | 0.18%   |
| AMD                 | 9        | 11     | 0.18%   |
| OCZ-VERTEX3         | 6        | 11     | 0.12%   |
| Neo                 | 4        | 6      | 0.08%   |
| Qumo                | 3        | 4      | 0.06%   |
| Netac               | 3        | 3      | 0.06%   |
| KingDian            | 3        | 4      | 0.06%   |
| IBM                 | 3        | 3      | 0.06%   |
| Unknown             | 3        | 3      | 0.06%   |
| XPG                 | 2        | 2      | 0.04%   |
| Verbatim            | 2        | 2      | 0.04%   |
| Smartbuy            | 2        | 2      | 0.04%   |
| Silicon Motion      | 2        | 3      | 0.04%   |
| Quantum             | 2        | 2      | 0.04%   |
| Patriot             | 2        | 2      | 0.04%   |
| LITEONIT            | 2        | 2      | 0.04%   |
| Intenso             | 2        | 7      | 0.04%   |
| Hewlett-Packard     | 2        | 3      | 0.04%   |
| Espada              | 2        | 3      | 0.04%   |
| Apacer              | 2        | 2      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1836     | 2636   | 40.87%  |
| WDC                 | 1461     | 2038   | 32.52%  |
| Hitachi             | 457      | 608    | 10.17%  |
| Samsung Electronics | 364      | 518    | 8.1%    |
| Maxtor              | 159      | 190    | 3.54%   |
| Toshiba             | 154      | 208    | 3.43%   |
| HGST                | 30       | 37     | 0.67%   |
| IBM/Hitachi         | 11       | 14     | 0.24%   |
| Fujitsu             | 9        | 10     | 0.2%    |
| IBM                 | 3        | 3      | 0.07%   |
| Quantum             | 2        | 2      | 0.04%   |
| Hewlett-Packard     | 2        | 3      | 0.04%   |
| WD MediaMax         | 1        | 1      | 0.02%   |
| ExcelStor           | 1        | 1      | 0.02%   |
| ASMT                | 1        | 2      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3947     | 6272   | 89.64%  |
| SSD  | 437      | 590    | 9.93%   |
| NVMe | 19       | 31     | 0.43%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB          | 7        | 9      | 3.91%   |
| Seagate ST31000524AS 1TB          | 7        | 9      | 3.91%   |
| Seagate ST3500418AS 500GB         | 5        | 6      | 2.79%   |
| Seagate ST3500412AS 500GB         | 5        | 6      | 2.79%   |
| Hitachi HDS721010DLE630 1TB       | 5        | 6      | 2.79%   |
| Seagate ST31000333AS 1TB          | 3        | 3      | 1.68%   |
| Samsung Electronics SP0411N 40GB  | 3        | 4      | 1.68%   |
| Maxtor 6Y080L0 81GB               | 3        | 3      | 1.68%   |
| Hitachi HDS721010CLA332 1TB       | 3        | 3      | 1.68%   |
| HGST HTS545050A7E380 500GB        | 3        | 3      | 1.68%   |
| WDC WD5000AAKS-00V1A0 500GB       | 2        | 2      | 1.12%   |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 1.12%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 2      | 1.12%   |
| WDC WD15EARS-00MVWB0 1TB          | 2        | 4      | 1.12%   |
| Seagate STM3500418AS 500GB        | 2        | 2      | 1.12%   |
| Seagate ST500DM005 HD502HJ 500GB  | 2        | 3      | 1.12%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 1.12%   |
| Seagate ST500DM002-1BC142 500GB   | 2        | 2      | 1.12%   |
| Seagate ST3750528AS 752GB         | 2        | 2      | 1.12%   |
| Seagate ST3320613AS 320GB         | 2        | 3      | 1.12%   |
| Seagate ST3250318AS 250GB         | 2        | 2      | 1.12%   |
| Seagate ST32000542AS 2TB          | 2        | 4      | 1.12%   |
| Seagate ST3160318AS 160GB         | 2        | 2      | 1.12%   |
| Samsung Electronics HD503HI 500GB | 2        | 2      | 1.12%   |
| Samsung Electronics HD204UI 2TB   | 2        | 2      | 1.12%   |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 1.12%   |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 1.12%   |
| Hitachi HDS721050DLE630 500GB     | 2        | 2      | 1.12%   |
| Hitachi HDS721025CLA382 250GB     | 2        | 2      | 1.12%   |
| WDC WD800JD-22LSA0 80GB           | 1        | 1      | 0.56%   |
| WDC WD800JB-00FMA0 80GB           | 1        | 1      | 0.56%   |
| WDC WD800BB-55JKC0 80GB           | 1        | 2      | 0.56%   |
| WDC WD800BB-22JHA0 80GB           | 1        | 1      | 0.56%   |
| WDC WD800BB-00JKC0 80GB           | 1        | 2      | 0.56%   |
| WDC WD800BB-00JHC0 80GB           | 1        | 1      | 0.56%   |
| WDC WD7501AALS-00J7B0 752GB       | 1        | 1      | 0.56%   |
| WDC WD6400AACS-00G8B0 640GB       | 1        | 1      | 0.56%   |
| WDC WD5001AALS-00E3A0 500GB       | 1        | 1      | 0.56%   |
| WDC WD5000BPVT-00HXZT1 500GB      | 1        | 1      | 0.56%   |
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 0.56%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 66       | 78     | 37.08%  |
| WDC                 | 48       | 61     | 26.97%  |
| Samsung Electronics | 22       | 24     | 12.36%  |
| Hitachi             | 17       | 18     | 9.55%   |
| Maxtor              | 7        | 7      | 3.93%   |
| Toshiba             | 6        | 6      | 3.37%   |
| HGST                | 5        | 5      | 2.81%   |
| Transcend           | 1        | 1      | 0.56%   |
| OCZ                 | 1        | 1      | 0.56%   |
| Hewlett-Packard     | 1        | 1      | 0.56%   |
| GOODRAM             | 1        | 1      | 0.56%   |
| Crucial             | 1        | 1      | 0.56%   |
| Corsair             | 1        | 1      | 0.56%   |
| A-DATA Technology   | 1        | 1      | 0.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 7742     | 16866  | 55.66%  |
| Malfunc  | 4246     | 6893   | 30.53%  |
| Detected | 1747     | 3897   | 12.56%  |
| Failed   | 174      | 206    | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 7325     | 53.11%  |
| AMD                              | 2882     | 20.9%   |
| Nvidia                           | 750      | 5.44%   |
| JMicron Technology               | 749      | 5.43%   |
| Marvell Technology Group         | 418      | 3.03%   |
| ASMedia Technology               | 353      | 2.56%   |
| Samsung Electronics              | 349      | 2.53%   |
| VIA Technologies                 | 203      | 1.47%   |
| Silicon Motion                   | 123      | 0.89%   |
| Phison Electronics               | 105      | 0.76%   |
| Kingston Technology Company      | 101      | 0.73%   |
| SanDisk                          | 69       | 0.5%    |
| ADATA Technology                 | 59       | 0.43%   |
| Realtek Semiconductor            | 50       | 0.36%   |
| Silicon Integrated Systems [SiS] | 39       | 0.28%   |
| Silicon Image                    | 35       | 0.25%   |
| Integrated Technology Express    | 30       | 0.22%   |
| Lite-On Technology               | 28       | 0.2%    |
| SK hynix                         | 14       | 0.1%    |
| Micron/Crucial Technology        | 10       | 0.07%   |
| MAXIO Technology (Hangzhou)      | 10       | 0.07%   |
| Broadcom / LSI                   | 9        | 0.07%   |
| Adaptec                          | 9        | 0.07%   |
| Netac Technology                 | 6        | 0.04%   |
| LSI Logic / Symbios Logic        | 6        | 0.04%   |
| Micron Technology                | 5        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 5        | 0.04%   |
| ULi Electronics                  | 4        | 0.03%   |
| Toshiba America Info Systems     | 4        | 0.03%   |
| Promise Technology               | 4        | 0.03%   |
| MCST                             | 4        | 0.03%   |
| KIOXIA                           | 4        | 0.03%   |
| Hewlett-Packard                  | 4        | 0.03%   |
| Shenzhen Longsys Electronics     | 3        | 0.02%   |
| Seagate Technology               | 3        | 0.02%   |
| OCZ Technology Group             | 3        | 0.02%   |
| Union Memory (Shenzhen)          | 2        | 0.01%   |
| Solid State Storage Technology   | 2        | 0.01%   |
| INNOGRIT                         | 2        | 0.01%   |
| Broadcom                         | 2        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1369     | 6.98%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1126     | 5.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1032     | 5.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1028     | 5.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 740      | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 652      | 3.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 595      | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 581      | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 580      | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 579      | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 546      | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 453      | 2.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 402      | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 401      | 2.04%   |
| Nvidia MCP61 SATA Controller                                                            | 390      | 1.99%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 370      | 1.89%   |
| Nvidia MCP61 IDE                                                                        | 366      | 1.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 338      | 1.72%   |
| JMicron JMB368 IDE controller                                                           | 287      | 1.46%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 270      | 1.38%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 269      | 1.37%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 254      | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 222      | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 179      | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 179      | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 177      | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 176      | 0.9%    |
| AMD FCH SATA Controller D                                                               | 175      | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 170      | 0.87%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 162      | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 159      | 0.81%   |
| AMD FCH IDE Controller                                                                  | 139      | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 132      | 0.67%   |
| AMD 500 Series Chipset SATA Controller                                                  | 130      | 0.66%   |
| AMD 300 Series Chipset SATA Controller                                                  | 128      | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 118      | 0.6%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 118      | 0.6%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 117      | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 114      | 0.58%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 112      | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7030     | 50.46%  |
| IDE  | 5662     | 40.64%  |
| NVMe | 938      | 6.73%   |
| RAID | 277      | 1.99%   |
| SAS  | 19       | 0.14%   |
| SCSI | 6        | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 7467     | 67.37%  |
| AMD          | 3608     | 32.55%  |
| CentaurHauls | 2        | 0.02%   |
| PowerMac7,2  | 1        | 0.01%   |
| MBE8C-PC     | 1        | 0.01%   |
| Elbrus-MCST  | 1        | 0.01%   |
| E8C/EATX     | 1        | 0.01%   |
| E8C-SWTX     | 1        | 0.01%   |
| Unknown      | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 165      | 1.47%   |
| Intel Pentium 4 CPU 3.00GHz                 | 112      | 1%      |
| Intel Core i3-2120 CPU @ 3.30GHz            | 109      | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 107      | 0.96%   |
| AMD FX-6300 Six-Core Processor              | 104      | 0.93%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 103      | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 100      | 0.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 100      | 0.89%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 95       | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor           | 93       | 0.83%   |
| AMD Athlon II X2 250 Processor              | 90       | 0.8%    |
| AMD FX-8350 Eight-Core Processor            | 89       | 0.79%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 83       | 0.74%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 82       | 0.73%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 80       | 0.71%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 74       | 0.66%   |
| AMD FX-4300 Quad-Core Processor             | 74       | 0.66%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 70       | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 70       | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 69       | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 68       | 0.61%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 65       | 0.58%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 65       | 0.58%   |
| AMD FX-8320 Eight-Core Processor            | 65       | 0.58%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 61       | 0.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 58       | 0.52%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 57       | 0.51%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 56       | 0.5%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 56       | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 55       | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 55       | 0.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 55       | 0.49%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 55       | 0.49%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 53       | 0.47%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 53       | 0.47%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 53       | 0.47%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 52       | 0.46%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 52       | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 52       | 0.46%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 51       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1531     | 13.7%   |
| Intel Core i3           | 1131     | 10.12%  |
| Intel Core 2 Duo        | 727      | 6.5%    |
| Intel Celeron           | 659      | 5.9%    |
| Intel Pentium           | 658      | 5.89%   |
| Intel Core i7           | 620      | 5.55%   |
| AMD FX                  | 612      | 5.48%   |
| AMD Ryzen 5             | 476      | 4.26%   |
| Intel Xeon              | 474      | 4.24%   |
| AMD Athlon 64 X2        | 398      | 3.56%   |
| Intel Pentium Dual-Core | 372      | 3.33%   |
| Intel Core 2 Quad       | 334      | 2.99%   |
| AMD Athlon II X2        | 318      | 2.85%   |
| Intel Pentium 4         | 253      | 2.26%   |
| AMD Phenom II X4        | 197      | 1.76%   |
| AMD Ryzen 7             | 173      | 1.55%   |
| AMD Ryzen 3             | 153      | 1.37%   |
| AMD Athlon II X4        | 144      | 1.29%   |
| Intel Pentium Dual      | 138      | 1.23%   |
| Intel Core 2            | 130      | 1.16%   |
| Other                   | 127      | 1.14%   |
| AMD Athlon II X3        | 115      | 1.03%   |
| Intel Atom              | 114      | 1.02%   |
| Intel Pentium D         | 105      | 0.94%   |
| AMD A8                  | 102      | 0.91%   |
| AMD Phenom              | 99       | 0.89%   |
| AMD A10                 | 97       | 0.87%   |
| AMD A4                  | 94       | 0.84%   |
| AMD Athlon 64           | 87       | 0.78%   |
| AMD Phenom II X6        | 74       | 0.66%   |
| AMD A6                  | 74       | 0.66%   |
| AMD Athlon X4           | 72       | 0.64%   |
| AMD Athlon              | 69       | 0.62%   |
| Intel Pentium Gold      | 67       | 0.6%    |
| AMD Ryzen 9             | 45       | 0.4%    |
| AMD Sempron             | 42       | 0.38%   |
| Intel Genuine           | 35       | 0.31%   |
| AMD Phenom II X2        | 32       | 0.29%   |
| Intel Core i9           | 29       | 0.26%   |
| AMD Ryzen 5 PRO         | 20       | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 4710     | 41.34%  |
| 4       | 3413     | 29.96%  |
| 6       | 992      | 8.71%   |
| Unknown | 794      | 6.97%   |
| 1       | 616      | 5.41%   |
| 8       | 402      | 3.53%   |
| 3       | 297      | 2.61%   |
| 12      | 73       | 0.64%   |
| 16      | 37       | 0.32%   |
| 10      | 33       | 0.29%   |
| 24      | 12       | 0.11%   |
| 18      | 5        | 0.04%   |
| 32      | 2        | 0.02%   |
| 20      | 2        | 0.02%   |
| 14      | 2        | 0.02%   |
| 22      | 1        | 0.01%   |
| 15      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 11022    | 99.42%  |
| 2       | 55       | 0.5%    |
| Unknown | 7        | 0.06%   |
| 4       | 1        | 0.01%   |
| 0       | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 6451     | 56.76%  |
| 2       | 4118     | 36.23%  |
| Unknown | 794      | 6.99%   |
| 6       | 2        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 10841    | 97.7%   |
| 32-bit         | 181      | 1.63%   |
| Unknown        | 69       | 0.62%   |
| 64-bit         | 5        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1102     | 9.68%   |
| 0x1067a    | 982      | 8.63%   |
| 0x206a7    | 891      | 7.83%   |
| 0x306a9    | 800      | 7.03%   |
| 0x306c3    | 772      | 6.78%   |
| 0x010000c8 | 493      | 4.33%   |
| 0x506e3    | 401      | 3.52%   |
| 0x906e9    | 286      | 2.51%   |
| 0x906ea    | 277      | 2.43%   |
| 0x6fd      | 265      | 2.33%   |
| 0x10676    | 260      | 2.28%   |
| 0x06000852 | 231      | 2.03%   |
| 0x6fb      | 226      | 1.99%   |
| 0x06001119 | 214      | 1.88%   |
| 0x0600084f | 171      | 1.5%    |
| 0xa0653    | 156      | 1.37%   |
| 0x0800820d | 153      | 1.34%   |
| 0x08701021 | 149      | 1.31%   |
| 0x010000db | 145      | 1.27%   |
| 0x106e5    | 117      | 1.03%   |
| 0x20655    | 102      | 0.9%    |
| 0x06003106 | 98       | 0.86%   |
| 0x08108109 | 92       | 0.81%   |
| 0x08001138 | 89       | 0.78%   |
| 0x906eb    | 83       | 0.73%   |
| 0xf49      | 82       | 0.72%   |
| 0x6f6      | 81       | 0.71%   |
| 0x206d7    | 79       | 0.69%   |
| 0x6f2      | 78       | 0.69%   |
| 0x306f2    | 76       | 0.67%   |
| 0x010000c7 | 75       | 0.66%   |
| 0xf41      | 74       | 0.65%   |
| 0x03000027 | 69       | 0.61%   |
| 0x010000dc | 69       | 0.61%   |
| 0x0600063d | 68       | 0.6%    |
| 0x20652    | 67       | 0.59%   |
| 0x08101016 | 65       | 0.57%   |
| 0x0600063e | 65       | 0.57%   |
| 0x10677    | 61       | 0.54%   |
| 0xa0671    | 59       | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 1269     | 11.35%  |
| SandyBridge      | 1001     | 8.95%   |
| K10              | 999      | 8.94%   |
| Haswell          | 892      | 7.98%   |
| IvyBridge        | 891      | 7.97%   |
| KabyLake         | 778      | 6.96%   |
| Core             | 772      | 6.91%   |
| Piledriver       | 694      | 6.21%   |
| K8 Hammer        | 496      | 4.44%   |
| NetBurst         | 468      | 4.19%   |
| Skylake          | 443      | 3.96%   |
| Zen              | 295      | 2.64%   |
| Zen+             | 292      | 2.61%   |
| Zen 2            | 261      | 2.33%   |
| CometLake        | 220      | 1.97%   |
| Westmere         | 199      | 1.78%   |
| Nehalem          | 164      | 1.47%   |
| Unknown          | 160      | 1.43%   |
| Bulldozer        | 140      | 1.25%   |
| Steamroller      | 109      | 0.98%   |
| Zen 3            | 104      | 0.93%   |
| Bonnell          | 92       | 0.82%   |
| Silvermont       | 90       | 0.81%   |
| K10 Llano        | 75       | 0.67%   |
| Excavator        | 53       | 0.47%   |
| Goldmont plus    | 46       | 0.41%   |
| Icelake          | 31       | 0.28%   |
| Jaguar           | 24       | 0.21%   |
| Goldmont         | 24       | 0.21%   |
| Alderlake Hybrid | 23       | 0.21%   |
| Bobcat           | 21       | 0.19%   |
| Broadwell        | 20       | 0.18%   |
| K6               | 11       | 0.1%    |
| Tremont          | 8        | 0.07%   |
| Puma             | 6        | 0.05%   |
| P6               | 5        | 0.04%   |
| TigerLake        | 2        | 0.02%   |
| K8 & K10 hybrid  | 1        | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 5613     | 47.92%  |
| AMD                                          | 3088     | 26.36%  |
| Intel                                        | 2953     | 25.21%  |
| VIA Technologies                             | 15       | 0.13%   |
| ASPEED Technology                            | 15       | 0.13%   |
| Matrox Electronics Systems                   | 12       | 0.1%    |
| ATI Technologies                             | 7        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.03%   |
| S3 Graphics                                  | 3        | 0.03%   |
| Silicon Motion                               | 2        | 0.02%   |
| Zhaoxin                                      | 1        | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 363      | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 355      | 2.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 288      | 2.36%   |
| Nvidia GK208B [GeForce GT 710]                                              | 258      | 2.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 248      | 2.03%   |
| Nvidia GT218 [GeForce 210]                                                  | 243      | 1.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 239      | 1.96%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 208      | 1.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 205      | 1.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 200      | 1.64%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 170      | 1.39%   |
| Nvidia GF108 [GeForce GT 630]                                               | 170      | 1.39%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 165      | 1.35%   |
| Intel HD Graphics 530                                                       | 163      | 1.34%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 146      | 1.2%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 145      | 1.19%   |
| Nvidia GF119 [GeForce GT 610]                                               | 143      | 1.17%   |
| Intel HD Graphics 630                                                       | 132      | 1.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 122      | 1%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 119      | 0.98%   |
| Nvidia GF108 [GeForce GT 430]                                               | 119      | 0.98%   |
| Nvidia GK208B [GeForce GT 730]                                              | 118      | 0.97%   |
| AMD RS780L [Radeon 3000]                                                    | 116      | 0.95%   |
| Nvidia G92 [GeForce GTS 250]                                                | 115      | 0.94%   |
| Nvidia GF108 [GeForce GT 440]                                               | 114      | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 113      | 0.93%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 107      | 0.88%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 106      | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 104      | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 103      | 0.84%   |
| Nvidia GT215 [GeForce GT 240]                                               | 97       | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                               | 94       | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 94       | 0.77%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 92       | 0.75%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 92       | 0.75%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 90       | 0.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 90       | 0.74%   |
| Intel HD Graphics 510                                                       | 88       | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 87       | 0.71%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 86       | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| 1 x Nvidia                    | 5390     | 47.56%  |
| 1 x AMD                       | 2773     | 24.47%  |
| 1 x Intel                     | 2597     | 22.91%  |
| 2 x AMD                       | 254      | 2.24%   |
| Intel + Nvidia                | 148      | 1.31%   |
| AMD + Nvidia                  | 44       | 0.39%   |
| 2 x Nvidia                    | 30       | 0.26%   |
| Intel + AMD                   | 30       | 0.26%   |
| 1 x VIA                       | 15       | 0.13%   |
| 1 x ASPEED                    | 13       | 0.11%   |
| 1 x Matrox                    | 10       | 0.09%   |
| Other                         | 7        | 0.06%   |
| 3 x Nvidia                    | 3        | 0.03%   |
| 1 x SiS                       | 3        | 0.03%   |
| 3 x AMD                       | 2        | 0.02%   |
| 1 x Silicon Motion            | 2        | 0.02%   |
| 1 x S3 Graphics               | 2        | 0.02%   |
| Nvidia + Matrox               | 2        | 0.02%   |
| Nvidia + ASPEED               | 2        | 0.02%   |
| 2 x AMD + 1 x Nvidia          | 1        | 0.01%   |
| 1 x XGI                       | 1        | 0.01%   |
| Nvidia + Zhaoxin              | 1        | 0.01%   |
| Intel + 2 x AMD               | 1        | 0.01%   |
| Intel + SiS + 1 x S3 Graphics | 1        | 0.01%   |
| Intel + AMD + 4 x Nvidia      | 1        | 0.01%   |
| AMD + 2 x Nvidia              | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 8109     | 69.46%  |
| Proprietary | 2295     | 19.66%  |
| Unknown     | 1270     | 10.88%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3091     | 26.33%  |
| 1.01-2.0   | 2389     | 20.35%  |
| 0.51-1.0   | 2322     | 19.78%  |
| 0.01-0.5   | 2262     | 19.27%  |
| 3.01-4.0   | 887      | 7.55%   |
| 7.01-8.0   | 365      | 3.11%   |
| 5.01-6.0   | 197      | 1.68%   |
| 2.01-3.0   | 150      | 1.28%   |
| 8.01-16.0  | 67       | 0.57%   |
| 16.01-24.0 | 6        | 0.05%   |
| 4.01-5.0   | 5        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2595     | 24.5%   |
| Goldstar             | 1506     | 14.22%  |
| Acer                 | 1157     | 10.93%  |
| BenQ                 | 931      | 8.79%   |
| Philips              | 699      | 6.6%    |
| ViewSonic            | 530      | 5%      |
| AOC                  | 495      | 4.67%   |
| Dell                 | 457      | 4.32%   |
| Ancor Communications | 350      | 3.31%   |
| Hewlett-Packard      | 277      | 2.62%   |
| NEC Computers        | 238      | 2.25%   |
| Iiyama               | 143      | 1.35%   |
| Sony                 | 96       | 0.91%   |
| Unknown              | 73       | 0.69%   |
| Envision Peripherals | 61       | 0.58%   |
| Plain Tree Systems   | 56       | 0.53%   |
| LG Electronics       | 55       | 0.52%   |
| ASUSTek Computer     | 55       | 0.52%   |
| Lenovo               | 44       | 0.42%   |
| HHT                  | 44       | 0.42%   |
| Packard Bell         | 39       | 0.37%   |
| ___                  | 32       | 0.3%    |
| Toshiba              | 24       | 0.23%   |
| Fujitsu Siemens      | 23       | 0.22%   |
| CHR                  | 20       | 0.19%   |
| VIE                  | 19       | 0.18%   |
| MiTAC                | 19       | 0.18%   |
| KTC                  | 19       | 0.18%   |
| Mi                   | 18       | 0.17%   |
| HannStar             | 17       | 0.16%   |
| JRY                  | 15       | 0.14%   |
| HKC                  | 15       | 0.14%   |
| Panasonic            | 14       | 0.13%   |
| MStar                | 14       | 0.13%   |
| Haier                | 14       | 0.13%   |
| AGO                  | 14       | 0.13%   |
| MSI                  | 12       | 0.11%   |
| Hitachi              | 12       | 0.11%   |
| HUAWEI               | 11       | 0.1%    |
| BBK                  | 11       | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 77       | 0.7%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 71       | 0.64%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                   | 68       | 0.62%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 61       | 0.55%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 60       | 0.54%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 53       | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 53       | 0.48%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 45       | 0.41%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 43       | 0.39%   |
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 43       | 0.39%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 43       | 0.39%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch  | 42       | 0.38%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 39       | 0.35%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 38       | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 36       | 0.33%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 35       | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 33       | 0.3%    |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                    | 32       | 0.29%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 31       | 0.28%   |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                 | 28       | 0.25%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 27       | 0.25%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 27       | 0.25%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 27       | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 26       | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 26       | 0.24%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch | 25       | 0.23%   |
| Plain Tree Systems LCD Monitor PTS06A5 1280x1024 337x270mm 17.0-inch | 25       | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 25       | 0.23%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 25       | 0.23%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 25       | 0.23%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 24       | 0.22%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                     | 24       | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 23       | 0.21%   |
| Goldstar L1952S GSM4AE0 1280x1024 376x301mm 19.0-inch                | 23       | 0.21%   |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                | 23       | 0.21%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                | 23       | 0.21%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch | 22       | 0.2%    |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 22       | 0.2%    |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                | 21       | 0.19%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 21       | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 4511     | 43.27%  |
| 1280x1024 (SXGA)   | 2177     | 20.88%  |
| 1680x1050 (WSXGA+) | 604      | 5.79%   |
| 1440x900 (WXGA+)   | 536      | 5.14%   |
| 1366x768 (WXGA)    | 428      | 4.11%   |
| 1600x900 (HD+)     | 374      | 3.59%   |
| 3840x2160 (4K)     | 360      | 3.45%   |
| 2560x1440 (QHD)    | 340      | 3.26%   |
| 1920x1200 (WUXGA)  | 196      | 1.88%   |
| 1360x768           | 186      | 1.78%   |
| 1024x768 (XGA)     | 154      | 1.48%   |
| 1600x1200          | 86       | 0.82%   |
| 2560x1080          | 84       | 0.81%   |
| Unknown            | 82       | 0.79%   |
| 3440x1440          | 46       | 0.44%   |
| 1280x720 (HD)      | 37       | 0.35%   |
| 1920x540           | 31       | 0.3%    |
| 1400x1050          | 24       | 0.23%   |
| 3840x1080          | 22       | 0.21%   |
| 2288x1287          | 14       | 0.13%   |
| 2048x1536          | 13       | 0.12%   |
| 1152x864           | 13       | 0.12%   |
| 1280x960           | 12       | 0.12%   |
| 4480x1440          | 8        | 0.08%   |
| 2048x1152          | 8        | 0.08%   |
| 1920x1440          | 8        | 0.08%   |
| 3200x1080          | 5        | 0.05%   |
| 2560x1600          | 5        | 0.05%   |
| 5760x1080          | 4        | 0.04%   |
| 3600x1080          | 4        | 0.04%   |
| 2160x1200          | 4        | 0.04%   |
| 7680x2160          | 3        | 0.03%   |
| 5760x2160          | 3        | 0.03%   |
| 1280x768           | 3        | 0.03%   |
| 5120x1440          | 2        | 0.02%   |
| 5120x1080          | 2        | 0.02%   |
| 4093x4093          | 2        | 0.02%   |
| 4000x1440          | 2        | 0.02%   |
| 3840x2560          | 2        | 0.02%   |
| 3840x1600          | 2        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 1720     | 16.17%  |
| 19      | 1530     | 14.38%  |
| 23      | 1356     | 12.75%  |
| 17      | 1080     | 10.15%  |
| 24      | 1067     | 10.03%  |
| 27      | 703      | 6.61%   |
| 18      | 598      | 5.62%   |
| 20      | 501      | 4.71%   |
| Unknown | 418      | 3.93%   |
| 22      | 373      | 3.51%   |
| 15      | 278      | 2.61%   |
| 31      | 163      | 1.53%   |
| 34      | 117      | 1.1%    |
| 40      | 90       | 0.85%   |
| 72      | 85       | 0.8%    |
| 54      | 83       | 0.78%   |
| 32      | 70       | 0.66%   |
| 52      | 41       | 0.39%   |
| 16      | 39       | 0.37%   |
| 25      | 35       | 0.33%   |
| 84      | 31       | 0.29%   |
| 48      | 26       | 0.24%   |
| 46      | 23       | 0.22%   |
| 43      | 19       | 0.18%   |
| 26      | 18       | 0.17%   |
| 12      | 18       | 0.17%   |
| 42      | 17       | 0.16%   |
| 14      | 15       | 0.14%   |
| 28      | 13       | 0.12%   |
| 142     | 12       | 0.11%   |
| 13      | 12       | 0.11%   |
| 33      | 11       | 0.1%    |
| 29      | 9        | 0.08%   |
| 58      | 7        | 0.07%   |
| 50      | 7        | 0.07%   |
| 37      | 7        | 0.07%   |
| 60      | 6        | 0.06%   |
| 47      | 6        | 0.06%   |
| 39      | 6        | 0.06%   |
| 99      | 4        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 3653     | 34.89%  |
| 501-600        | 2993     | 28.59%  |
| 301-350        | 1372     | 13.11%  |
| 351-400        | 1081     | 10.33%  |
| Unknown        | 418      | 3.99%   |
| 601-700        | 220      | 2.1%    |
| 1001-1500      | 210      | 2.01%   |
| 701-800        | 199      | 1.9%    |
| 1501-2000      | 120      | 1.15%   |
| 901-1000       | 81       | 0.77%   |
| 801-900        | 62       | 0.59%   |
| 201-300        | 43       | 0.41%   |
| More than 2000 | 16       | 0.15%   |
| 1-100          | 1        | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 5790     | 56.82%  |
| 5/4     | 2066     | 20.27%  |
| 16/10   | 1260     | 12.37%  |
| 4/3     | 438      | 4.3%    |
| Unknown | 309      | 3.03%   |
| 21/9    | 168      | 1.65%   |
| 3/2     | 100      | 0.98%   |
| 6/5     | 37       | 0.36%   |
| 1.00    | 12       | 0.12%   |
| 32/9    | 9        | 0.09%   |
| 2.00    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3864     | 36.78%  |
| 151-200        | 2479     | 23.59%  |
| 141-150        | 1519     | 14.46%  |
| 301-350        | 719      | 6.84%   |
| Unknown        | 418      | 3.98%   |
| 351-500        | 365      | 3.47%   |
| More than 1000 | 309      | 2.94%   |
| 251-300        | 283      | 2.69%   |
| 501-1000       | 184      | 1.75%   |
| 101-110        | 175      | 1.67%   |
| 111-120        | 117      | 1.11%   |
| 121-130        | 24       | 0.23%   |
| 71-80          | 20       | 0.19%   |
| 131-140        | 14       | 0.13%   |
| 81-90          | 9        | 0.09%   |
| 91-100         | 5        | 0.05%   |
| 61-70          | 1        | 0.01%   |
| 51-60          | 1        | 0.01%   |
| 1-40           | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 7073     | 69.65%  |
| 101-120       | 2042     | 20.11%  |
| Unknown       | 418      | 4.12%   |
| 1-50          | 372      | 3.66%   |
| 121-160       | 167      | 1.64%   |
| 161-240       | 81       | 0.8%    |
| More than 240 | 2        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9379     | 82.8%   |
| 0     | 1003     | 8.85%   |
| 2     | 881      | 7.78%   |
| 3     | 61       | 0.54%   |
| 4     | 3        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 7927     | 55.61%  |
| Intel                                  | 1579     | 11.08%  |
| Qualcomm Atheros                       | 1398     | 9.81%   |
| Nvidia                                 | 650      | 4.56%   |
| Ralink Technology                      | 366      | 2.57%   |
| Huawei Technologies                    | 255      | 1.79%   |
| Marvell Technology Group               | 216      | 1.52%   |
| Ralink                                 | 187      | 1.31%   |
| TP-Link                                | 180      | 1.26%   |
| VIA Technologies                       | 179      | 1.26%   |
| D-Link System                          | 141      | 0.99%   |
| D-Link                                 | 126      | 0.88%   |
| Broadcom                               | 123      | 0.86%   |
| ASUSTek Computer                       | 102      | 0.72%   |
| Qualcomm Atheros Communications        | 94       | 0.66%   |
| ZTE WCDMA Technologies MSM             | 67       | 0.47%   |
| Xiaomi                                 | 66       | 0.46%   |
| Broadcom Limited                       | 65       | 0.46%   |
| MediaTek                               | 52       | 0.36%   |
| Samsung Electronics                    | 41       | 0.29%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.26%   |
| 3Com                                   | 30       | 0.21%   |
| Silicon Integrated Systems [SiS]       | 29       | 0.2%    |
| Microsoft                              | 23       | 0.16%   |
| NetGear                                | 18       | 0.13%   |
| ZyXEL Communications                   | 15       | 0.11%   |
| IMC Networks                           | 15       | 0.11%   |
| HTC (High Tech Computer)               | 15       | 0.11%   |
| Gemtek                                 | 15       | 0.11%   |
| Mercucys                               | 14       | 0.1%    |
| ASIX Electronics                       | 14       | 0.1%    |
| Spreadtrum Communications              | 12       | 0.08%   |
| Aquantia                               | 12       | 0.08%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.07%   |
| Qualcomm                               | 9        | 0.06%   |
| LSI                                    | 9        | 0.06%   |
| GCT Semiconductor                      | 8        | 0.06%   |
| Xilinx                                 | 7        | 0.05%   |
| T & A Mobile Phones                    | 7        | 0.05%   |
| Vimtron Electronics                    | 6        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6683     | 43.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 452      | 2.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 398      | 2.61%   |
| Nvidia MCP61 Ethernet                                             | 348      | 2.29%   |
| Ralink MT7601U Wireless Adapter                                   | 222      | 1.46%   |
| Intel Ethernet Connection (2) I219-V                              | 207      | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 199      | 1.31%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 174      | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 174      | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 157      | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 154      | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 149      | 0.98%   |
| Huawei Modem/Networkcard                                          | 134      | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 133      | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 122      | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 112      | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 111      | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 105      | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 101      | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 90       | 0.59%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 82       | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                   | 77       | 0.51%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 77       | 0.51%   |
| Intel Wi-Fi 6 AX200                                               | 76       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 74       | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 72       | 0.47%   |
| Intel Ethernet Connection (14) I219-V                             | 68       | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 67       | 0.44%   |
| Nvidia MCP77 Ethernet                                             | 65       | 0.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 64       | 0.42%   |
| Nvidia CK804 Ethernet Controller                                  | 64       | 0.42%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 63       | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 63       | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 62       | 0.41%   |
| Ralink RT5370 Wireless Adapter                                    | 60       | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 58       | 0.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58       | 0.38%   |
| Intel Ethernet Connection (2) I218-V                              | 57       | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 56       | 0.37%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 52       | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 683      | 24.93%  |
| Qualcomm Atheros                | 380      | 13.87%  |
| Ralink Technology               | 366      | 13.36%  |
| Intel                           | 356      | 12.99%  |
| Ralink                          | 187      | 6.82%   |
| TP-Link                         | 176      | 6.42%   |
| D-Link                          | 122      | 4.45%   |
| ASUSTek Computer                | 96       | 3.5%    |
| Qualcomm Atheros Communications | 94       | 3.43%   |
| Broadcom                        | 73       | 2.66%   |
| D-Link System                   | 60       | 2.19%   |
| Microsoft                       | 23       | 0.84%   |
| NetGear                         | 17       | 0.62%   |
| IMC Networks                    | 15       | 0.55%   |
| Mercucys                        | 14       | 0.51%   |
| ZyXEL Communications            | 13       | 0.47%   |
| MediaTek                        | 11       | 0.4%    |
| Broadcom Limited                | 10       | 0.36%   |
| Xiaomi                          | 7        | 0.26%   |
| Tenda                           | 6        | 0.22%   |
| ZyDAS                           | 3        | 0.11%   |
| VIA Technologies                | 3        | 0.11%   |
| Texas Instruments               | 3        | 0.11%   |
| Micro Star International        | 3        | 0.11%   |
| Marvell Technology Group        | 3        | 0.11%   |
| TRENDnet                        | 2        | 0.07%   |
| Edimax Technology               | 2        | 0.07%   |
| Z-Com                           | 1        | 0.04%   |
| Wilocity                        | 1        | 0.04%   |
| Sierra Wireless                 | 1        | 0.04%   |
| Linksys                         | 1        | 0.04%   |
| Gemtek                          | 1        | 0.04%   |
| Chu Yuen Enterprise             | 1        | 0.04%   |
| BUFFALO                         | 1        | 0.04%   |
| Belkin Components               | 1        | 0.04%   |
| ASUSTek Computer (wrong ID)     | 1        | 0.04%   |
| AirTies Wireless Networks       | 1        | 0.04%   |
| Accton Technology               | 1        | 0.04%   |
| AboCom Systems                  | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                    | 222      | 8.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 154      | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 105      | 3.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 90       | 3.25%   |
| Qualcomm Atheros AR9271 802.11n                                    | 77       | 2.78%   |
| Intel Wi-Fi 6 AX200                                                | 76       | 2.74%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                   | 64       | 2.31%   |
| Ralink RT5370 Wireless Adapter                                     | 60       | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 56       | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 50       | 1.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 47       | 1.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                              | 46       | 1.66%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 45       | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 43       | 1.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 41       | 1.48%   |
| Realtek 802.11ac NIC                                               | 38       | 1.37%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 38       | 1.37%   |
| Ralink RT2561/RT61 rev B 802.11g                                   | 37       | 1.34%   |
| Intel Wireless-AC 9260                                             | 35       | 1.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 33       | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 32       | 1.16%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 31       | 1.12%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                         | 30       | 1.08%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                               | 30       | 1.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 29       | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 29       | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 27       | 0.98%   |
| Intel Wireless 3165                                                | 27       | 0.98%   |
| D-Link 802.11 n WLAN                                               | 27       | 0.98%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]          | 26       | 0.94%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                | 25       | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 25       | 0.9%    |
| Intel Wireless 7265                                                | 24       | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 24       | 0.87%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 23       | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                          | 21       | 0.76%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 20       | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 19       | 0.69%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller          | 18       | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 17       | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 7703     | 64.53%  |
| Intel                                  | 1385     | 11.6%   |
| Qualcomm Atheros                       | 1059     | 8.87%   |
| Nvidia                                 | 650      | 5.44%   |
| Marvell Technology Group               | 213      | 1.78%   |
| VIA Technologies                       | 174      | 1.46%   |
| D-Link System                          | 82       | 0.69%   |
| Huawei Technologies                    | 76       | 0.64%   |
| ZTE WCDMA Technologies MSM             | 62       | 0.52%   |
| Xiaomi                                 | 59       | 0.49%   |
| Broadcom Limited                       | 55       | 0.46%   |
| Broadcom                               | 50       | 0.42%   |
| Samsung Electronics                    | 41       | 0.34%   |
| MediaTek                               | 40       | 0.34%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.31%   |
| 3Com                                   | 30       | 0.25%   |
| Silicon Integrated Systems [SiS]       | 29       | 0.24%   |
| HTC (High Tech Computer)               | 15       | 0.13%   |
| Gemtek                                 | 14       | 0.12%   |
| ASIX Electronics                       | 14       | 0.12%   |
| Spreadtrum Communications              | 12       | 0.1%    |
| Aquantia                               | 12       | 0.1%    |
| Sony Ericsson Mobile Communications AB | 10       | 0.08%   |
| Qualcomm                               | 9        | 0.08%   |
| GCT Semiconductor                      | 8        | 0.07%   |
| T & A Mobile Phones                    | 7        | 0.06%   |
| Vimtron Electronics                    | 6        | 0.05%   |
| OPPO Electronics                       | 6        | 0.05%   |
| JMicron Technology                     | 6        | 0.05%   |
| HMD Global                             | 6        | 0.05%   |
| ASUSTek Computer                       | 6        | 0.05%   |
| TP-Link                                | 5        | 0.04%   |
| Lenovo                                 | 5        | 0.04%   |
| ULi Electronics                        | 4        | 0.03%   |
| MCST                                   | 4        | 0.03%   |
| D-Link                                 | 4        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.03%   |
| ICS Advent                             | 3        | 0.03%   |
| Davicom Semiconductor                  | 3        | 0.03%   |
| ZyXEL Communications                   | 2        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6683     | 54.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 452      | 3.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 398      | 3.26%   |
| Nvidia MCP61 Ethernet                                             | 348      | 2.85%   |
| Intel Ethernet Connection (2) I219-V                              | 207      | 1.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 199      | 1.63%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 174      | 1.42%   |
| Intel I211 Gigabit Network Connection                             | 174      | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 157      | 1.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 149      | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 133      | 1.09%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 122      | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 112      | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 111      | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 101      | 0.83%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 82       | 0.67%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 77       | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 74       | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 72       | 0.59%   |
| Intel Ethernet Connection (14) I219-V                             | 68       | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 67       | 0.55%   |
| Nvidia MCP77 Ethernet                                             | 65       | 0.53%   |
| Nvidia CK804 Ethernet Controller                                  | 64       | 0.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 63       | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 63       | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 62       | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 58       | 0.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58       | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 57       | 0.47%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 52       | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 51       | 0.42%   |
| Nvidia MCP55 Ethernet                                             | 51       | 0.42%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 51       | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 49       | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 48       | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 44       | 0.36%   |
| Huawei STK-L21                                                    | 42       | 0.34%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 39       | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38       | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10973    | 79.34%  |
| WiFi     | 2609     | 18.86%  |
| Modem    | 228      | 1.65%   |
| Unknown  | 20       | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 9302     | 84.66%  |
| WiFi     | 1685     | 15.33%  |
| Modem    | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8998     | 80.63%  |
| 2     | 1879     | 16.84%  |
| 3     | 153      | 1.37%   |
| 0     | 95       | 0.85%   |
| 4     | 25       | 0.22%   |
| 5     | 3        | 0.03%   |
| 8     | 2        | 0.02%   |
| 6     | 2        | 0.02%   |
| 33    | 1        | 0.01%   |
| 13    | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10966    | 98.69%  |
| Yes  | 146      | 1.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 656      | 44.63%  |
| Intel                           | 319      | 21.7%   |
| ASUSTek Computer                | 138      | 9.39%   |
| Realtek Semiconductor           | 104      | 7.07%   |
| Broadcom                        | 88       | 5.99%   |
| Qualcomm Atheros Communications | 46       | 3.13%   |
| Integrated System Solution      | 27       | 1.84%   |
| IMC Networks                    | 17       | 1.16%   |
| Lite-On Technology              | 12       | 0.82%   |
| TP-Link                         | 10       | 0.68%   |
| Conwise Technology              | 9        | 0.61%   |
| Ralink                          | 6        | 0.41%   |
| Apple                           | 6        | 0.41%   |
| Roper                           | 5        | 0.34%   |
| MediaTek                        | 5        | 0.34%   |
| Logitech                        | 4        | 0.27%   |
| HTC (High Tech Computer)        | 4        | 0.27%   |
| Foxconn / Hon Hai               | 4        | 0.27%   |
| Hewlett-Packard                 | 3        | 0.2%    |
| D-Link System                   | 3        | 0.2%    |
| Micro Star International        | 2        | 0.14%   |
| TRENDnet                        | 1        | 0.07%   |
| Edimax Technology               | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 656      | 44.57%  |
| Realtek Bluetooth Radio                                              | 88       | 5.98%   |
| Intel Bluetooth wireless interface                                   | 88       | 5.98%   |
| Intel AX200 Bluetooth                                                | 73       | 4.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 60       | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 48       | 3.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 30       | 2.04%   |
| Intel AX210 Bluetooth                                                | 29       | 1.97%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 28       | 1.9%    |
| ASUS Bluetooth Adapter                                               | 23       | 1.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 22       | 1.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 20       | 1.36%   |
| Broadcom BCM2045 Bluetooth                                           | 17       | 1.15%   |
| Intel AX201 Bluetooth                                                | 15       | 1.02%   |
| Integrated System Solution Bluetooth Device                          | 15       | 1.02%   |
| ASUS BCM20702A0                                                      | 15       | 1.02%   |
| ASUS Bluetooth Device                                                | 14       | 0.95%   |
| Broadcom Bluetooth 3.0 Dongle                                        | 13       | 0.88%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 12       | 0.82%   |
| ASUS Bluetooth Radio                                                 | 12       | 0.82%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 11       | 0.75%   |
| TP-Link UB500 Adapter                                                | 10       | 0.68%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 0.68%   |
| Lite-On Bluetooth Device                                             | 10       | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 9        | 0.61%   |
| Conwise CW6622                                                       | 9        | 0.61%   |
| Broadcom BCM92045B3 ROM                                              | 9        | 0.61%   |
| Ralink RT3290 Bluetooth                                              | 6        | 0.41%   |
| Roper Class 1 Bluetooth Dongle                                       | 5        | 0.34%   |
| Qualcomm Atheros  Bluetooth Device                                   | 5        | 0.34%   |
| Qualcomm Atheros Bluetooth (AR3011)                                  | 5        | 0.34%   |
| MediaTek Wireless_Device                                             | 5        | 0.34%   |
| Intel Bluetooth Device                                               | 5        | 0.34%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 4        | 0.27%   |
| IMC Networks Bluetooth Radio                                         | 4        | 0.27%   |
| IMC Networks Bluetooth Module                                        | 4        | 0.27%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.27%   |
| Broadcom Bluetooth dongle                                            | 4        | 0.27%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 4        | 0.27%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 4        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 7090     | 40.17%  |
| Nvidia                               | 4831     | 27.37%  |
| AMD                                  | 4092     | 23.19%  |
| C-Media Electronics                  | 458      | 2.6%    |
| Creative Labs                        | 293      | 1.66%   |
| VIA Technologies                     | 114      | 0.65%   |
| Creative Technology                  | 72       | 0.41%   |
| Logitech                             | 63       | 0.36%   |
| JMTek                                | 63       | 0.36%   |
| Texas Instruments                    | 41       | 0.23%   |
| Silicon Integrated Systems [SiS]     | 37       | 0.21%   |
| Generalplus Technology               | 36       | 0.2%    |
| ASUSTek Computer                     | 22       | 0.12%   |
| Kingston Technology                  | 20       | 0.11%   |
| Plantronics                          | 18       | 0.1%    |
| Yamaha                               | 13       | 0.07%   |
| Sony                                 | 13       | 0.07%   |
| Razer USA                            | 12       | 0.07%   |
| Pixart Imaging                       | 11       | 0.06%   |
| A4Tech                               | 11       | 0.06%   |
| Focusrite-Novation                   | 10       | 0.06%   |
| Ensoniq                              | 10       | 0.06%   |
| SteelSeries ApS                      | 9        | 0.05%   |
| GN Netcom                            | 9        | 0.05%   |
| Samson Technologies                  | 8        | 0.05%   |
| M-Audio                              | 8        | 0.05%   |
| Microsoft                            | 7        | 0.04%   |
| KTMicro                              | 7        | 0.04%   |
| ESS Technology                       | 7        | 0.04%   |
| Conexant Systems                     | 7        | 0.04%   |
| BEHRINGER International              | 7        | 0.04%   |
| ATI Technologies                     | 7        | 0.04%   |
| XMOS                                 | 6        | 0.03%   |
| Tenx Technology                      | 6        | 0.03%   |
| Shenzhen Rapoo Technology            | 6        | 0.03%   |
| Aureal Semiconductor                 | 6        | 0.03%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.03%   |
| SAVITECH                             | 5        | 0.03%   |
| Realtek Semiconductor                | 5        | 0.03%   |
| Nordic Semiconductor ASA             | 5        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1376     | 6.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1361     | 6.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1088     | 5.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 684      | 3.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 646      | 3.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 572      | 2.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 530      | 2.68%   |
| AMD FCH Azalia Controller                                                  | 436      | 2.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 426      | 2.16%   |
| Nvidia High Definition Audio Controller                                    | 418      | 2.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 413      | 2.09%   |
| Intel 200 Series PCH HD Audio                                              | 413      | 2.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 396      | 2.01%   |
| Nvidia MCP61 High Definition Audio                                         | 377      | 1.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 376      | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 352      | 1.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 342      | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 305      | 1.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 303      | 1.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 296      | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 276      | 1.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 270      | 1.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 252      | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 229      | 1.16%   |
| Nvidia GK106 HDMI Audio Controller                                         | 217      | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                         | 211      | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 209      | 1.06%   |
| Nvidia GF116 High Definition Audio Controller                              | 201      | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 189      | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 183      | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 177      | 0.9%    |
| Nvidia GK104 HDMI Audio Controller                                         | 161      | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 139      | 0.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 137      | 0.69%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 132      | 0.67%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 132      | 0.67%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 127      | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                              | 123      | 0.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 116      | 0.59%   |
| Nvidia GP108 High Definition Audio Controller                              | 113      | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 4491     | 41.4%   |
| Kingston                     | 2069     | 19.07%  |
| Crucial                      | 866      | 7.98%   |
| Samsung Electronics          | 673      | 6.2%    |
| Corsair                      | 453      | 4.18%   |
| SK hynix                     | 447      | 4.12%   |
| Patriot                      | 276      | 2.54%   |
| AMD                          | 259      | 2.39%   |
| Micron Technology            | 153      | 1.41%   |
| A-DATA Technology            | 89       | 0.82%   |
| Goodram                      | 84       | 0.77%   |
| Nanya Technology             | 79       | 0.73%   |
| G.Skill                      | 72       | 0.66%   |
| Kingmax                      | 63       | 0.58%   |
| Qumo                         | 59       | 0.54%   |
| Apacer                       | 56       | 0.52%   |
| Foxline                      | 49       | 0.45%   |
| Silicon Power                | 46       | 0.42%   |
| Goldkey                      | 46       | 0.42%   |
| Unknown                      | 43       | 0.4%    |
| Elpida                       | 40       | 0.37%   |
| Kllisre                      | 38       | 0.35%   |
| Transcend                    | 37       | 0.34%   |
| KETECH                       | 29       | 0.27%   |
| GeIL                         | 27       | 0.25%   |
| Ramaxel Technology           | 24       | 0.22%   |
| Hikvision                    | 24       | 0.22%   |
| Unifosa                      | 21       | 0.19%   |
| Team                         | 19       | 0.18%   |
| Atermiter                    | 18       | 0.17%   |
| Ramos Technology             | 14       | 0.13%   |
| Unknown (ABCD)               | 11       | 0.1%    |
| Neo Forza                    | 10       | 0.09%   |
| Qimonda                      | 9        | 0.08%   |
| TakeMS                       | 8        | 0.07%   |
| Hexon                        | 7        | 0.06%   |
| Wilk Elektronik              | 6        | 0.06%   |
| Patriot Memory (PDP Systems) | 6        | 0.06%   |
| PLEXHD                       | 5        | 0.05%   |
| Patriot Memory               | 5        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 289      | 2.28%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 268      | 2.11%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 263      | 2.07%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 222      | 1.75%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 212      | 1.67%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 205      | 1.62%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s            | 186      | 1.47%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 142      | 1.12%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 137      | 1.08%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 122      | 0.96%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 97       | 0.76%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 89       | 0.7%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s    | 89       | 0.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                      | 86       | 0.68%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 86       | 0.68%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 85       | 0.67%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 83       | 0.65%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 79       | 0.62%   |
| Unknown RAM Module 1024MB DIMM                         | 71       | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 69       | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s            | 64       | 0.5%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 63       | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 61       | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s            | 60       | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 58       | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 57       | 0.45%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 57       | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 56       | 0.44%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 56       | 0.44%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s | 52       | 0.41%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 48       | 0.38%   |
| Unknown RAM Module 2048MB DIMM                         | 47       | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 47       | 0.37%   |
| Unknown RAM Module 512MB DIMM                          | 46       | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 46       | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR2                    | 46       | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2                    | 45       | 0.35%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                | 44       | 0.35%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s  | 44       | 0.35%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                 | 43       | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3401     | 34.38%  |
| DDR4    | 2152     | 21.75%  |
| Unknown | 1878     | 18.99%  |
| DDR2    | 1213     | 12.26%  |
| SDRAM   | 931      | 9.41%   |
| DDR     | 279      | 2.82%   |
| LPDDR4  | 17       | 0.17%   |
| DRAM    | 14       | 0.14%   |
| DDR5    | 7        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 9536     | 97.27%  |
| SODIMM       | 260      | 2.65%   |
| FB-DIMM      | 5        | 0.05%   |
| Row Of Chips | 2        | 0.02%   |
| RIMM         | 1        | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 3297     | 29.03%  |
| 2048  | 3065     | 26.99%  |
| 8192  | 2337     | 20.58%  |
| 1024  | 1620     | 14.26%  |
| 16384 | 451      | 3.97%   |
| 512   | 394      | 3.47%   |
| 32768 | 96       | 0.85%   |
| 256   | 88       | 0.77%   |
| 32    | 5        | 0.04%   |
| 128   | 2        | 0.02%   |
| 16    | 2        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1939     | 18.06%  |
| 1333    | 1722     | 16.04%  |
| 800     | 1206     | 11.24%  |
| Unknown | 950      | 8.85%   |
| 667     | 673      | 6.27%   |
| 2400    | 533      | 4.97%   |
| 2133    | 412      | 3.84%   |
| 2667    | 372      | 3.47%   |
| 3200    | 357      | 3.33%   |
| 400     | 268      | 2.5%    |
| 1867    | 212      | 1.98%   |
| 1866    | 193      | 1.8%    |
| 1066    | 168      | 1.57%   |
| 3600    | 158      | 1.47%   |
| 333     | 132      | 1.23%   |
| 533     | 126      | 1.17%   |
| 2666    | 109      | 1.02%   |
| 3400    | 108      | 1.01%   |
| 2933    | 106      | 0.99%   |
| 3466    | 72       | 0.67%   |
| 1800    | 70       | 0.65%   |
| 3000    | 61       | 0.57%   |
| 1067    | 58       | 0.54%   |
| 266     | 57       | 0.53%   |
| 2866    | 52       | 0.48%   |
| 1334    | 45       | 0.42%   |
| 2800    | 40       | 0.37%   |
| 3066    | 34       | 0.32%   |
| 66      | 33       | 0.31%   |
| 1648    | 31       | 0.29%   |
| 2134    | 30       | 0.28%   |
| 2000    | 28       | 0.26%   |
| 1400    | 25       | 0.23%   |
| 3334    | 23       | 0.21%   |
| 200     | 19       | 0.18%   |
| 3733    | 18       | 0.17%   |
| 3333    | 17       | 0.16%   |
| 2048    | 16       | 0.15%   |
| 2934    | 15       | 0.14%   |
| 2733    | 15       | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 266      | 28.98%  |
| Canon                           | 196      | 21.35%  |
| Samsung Electronics             | 163      | 17.76%  |
| Seiko Epson                     | 83       | 9.04%   |
| Brother Industries              | 63       | 6.86%   |
| Xerox                           | 33       | 3.59%   |
| Pantum                          | 28       | 3.05%   |
| Panasonic (Matsushita)          | 25       | 2.72%   |
| Kyocera                         | 17       | 1.85%   |
| QinHeng Electronics             | 11       | 1.2%    |
| Ricoh                           | 9        | 0.98%   |
| Prolific Technology             | 6        | 0.65%   |
| TSC Auto ID Technology          | 2        | 0.22%   |
| NXP Semiconductors              | 2        | 0.22%   |
| Lexmark International           | 2        | 0.22%   |
| Konica Minolta                  | 2        | 0.22%   |
| cab Produkttechnik GmbH & Co KG | 2        | 0.22%   |
| STMicroelectronics              | 1        | 0.11%   |
| Sharp                           | 1        | 0.11%   |
| Samsung Info. Systems America   | 1        | 0.11%   |
| KODAK                           | 1        | 0.11%   |
| GODEX INTERNATIONAL             | 1        | 0.11%   |
| Fuji Xerox                      | 1        | 0.11%   |
| Datamax-O'Neil                  | 1        | 0.11%   |
| Apple                           | 1        | 0.11%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| HP LaserJet 1020                      | 29       | 3.14%   |
| Canon LBP2900                         | 29       | 3.14%   |
| Samsung SCX-4200 series               | 28       | 3.03%   |
| HP LaserJet P1102                     | 24       | 2.59%   |
| HP LaserJet 1018                      | 24       | 2.59%   |
| Panasonic (Matsushita) KX-MB1500RU    | 18       | 1.95%   |
| HP LaserJet 1010                      | 16       | 1.73%   |
| Samsung SCX-3400 Series               | 15       | 1.62%   |
| HP LaserJet P1005                     | 15       | 1.62%   |
| Seiko Epson Printer                   | 14       | 1.51%   |
| Canon MF4410                          | 13       | 1.41%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 12       | 1.3%    |
| Samsung SCX-3200 Series               | 12       | 1.3%    |
| HP LaserJet 1320                      | 12       | 1.3%    |
| QinHeng CH340S                        | 11       | 1.19%   |
| Canon MF3010                          | 11       | 1.19%   |
| Pantum P2200 series                   | 10       | 1.08%   |
| HP LaserJet 1300                      | 10       | 1.08%   |
| HP LaserJet 1200                      | 10       | 1.08%   |
| Canon MF4010 series                   | 10       | 1.08%   |
| Samsung SCX-4100 Scanner              | 9        | 0.97%   |
| Samsung ML-2010P Mono Laser Printer   | 9        | 0.97%   |
| Samsung M2070 Series                  | 9        | 0.97%   |
| HP DeskJet 2130 series                | 9        | 0.97%   |
| Canon LBP3010/LBP3018/LBP3050         | 9        | 0.97%   |
| Xerox Phaser 3140 and 3155            | 8        | 0.86%   |
| Samsung ML-216x Series Laser Printer  | 8        | 0.86%   |
| Samsung ML-1640 Series Laser Printer  | 8        | 0.86%   |
| Samsung ML-1210 Printer               | 8        | 0.86%   |
| Pantum M6500 series                   | 8        | 0.86%   |
| HP LaserJet 1022                      | 8        | 0.86%   |
| Canon PIXMA MG2500 Series             | 8        | 0.86%   |
| Canon LBP810                          | 8        | 0.86%   |
| Brother DCP-7057 scanner/printer      | 8        | 0.86%   |
| Xerox WorkCentre 3119 Series          | 7        | 0.76%   |
| Seiko Epson L210 Series               | 7        | 0.76%   |
| HP LaserJet 1000                      | 7        | 0.76%   |
| Canon MG2400 series                   | 7        | 0.76%   |
| Canon LBP6000                         | 7        | 0.76%   |
| Brother HL-2030 Laser Printer         | 7        | 0.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 100      | 37.59%  |
| Seiko Epson                 | 66       | 24.81%  |
| Hewlett-Packard             | 45       | 16.92%  |
| Mustek Systems              | 28       | 10.53%  |
| Acer Peripherals (now BenQ) | 11       | 4.14%   |
| Ultima Electronics          | 10       | 3.76%   |
| KYE Systems (Mouse Systems) | 3        | 1.13%   |
| Avision                     | 2        | 0.75%   |
| Canon Electronics           | 1        | 0.38%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                                                      | 17       | 6.37%   |
| Canon CanoScan LIDE 25                                                                | 17       | 6.37%   |
| Canon CanoScan LiDE 120                                                               | 16       | 5.99%   |
| Canon CanoScan LiDE 110                                                               | 16       | 5.99%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11       | 4.12%   |
| Canon CanoScan LiDE 210                                                               | 11       | 4.12%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 9        | 3.37%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 9        | 3.37%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 8        | 3%      |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 8        | 3%      |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8        | 3%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 7        | 2.62%   |
| Mustek Systems SNAPSCAN e22                                                           | 6        | 2.25%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6        | 2.25%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 5        | 1.87%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 5        | 1.87%   |
| Canon CanoScan LiDE 60                                                                | 5        | 1.87%   |
| Canon CanoScan LiDE 220                                                               | 5        | 1.87%   |
| Canon CanoScan LiDE 100                                                               | 5        | 1.87%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4        | 1.5%    |
| HP ScanJet 3800c                                                                      | 4        | 1.5%    |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4        | 1.5%    |
| Seiko Epson Perfection 660                                                            | 3        | 1.12%   |
| HP ScanJet 3970c                                                                      | 3        | 1.12%   |
| Canon CanoScan LiDE 70                                                                | 3        | 1.12%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3        | 1.12%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 0.75%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2        | 0.75%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2        | 0.75%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2        | 0.75%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 2        | 0.75%   |
| HP ScanJet G4050                                                                      | 2        | 0.75%   |
| HP ScanJet 4300c                                                                      | 2        | 0.75%   |
| HP ScanJet 2300c                                                                      | 2        | 0.75%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 0.75%   |
| Canon CanoScan LiDE 700F                                                              | 2        | 0.75%   |
| Canon CanoScan                                                                        | 2        | 0.75%   |
| Avision iVina FB1600/UMAX Astra 4500                                                  | 2        | 0.75%   |
| Acer Peripherals (now BenQ) Color FlatbedScanner39                                    | 2        | 0.75%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 2        | 0.75%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 736      | 33.42%  |
| Z-Star Microelectronics                | 371      | 16.85%  |
| Microdia                               | 169      | 7.67%   |
| Microsoft                              | 113      | 5.13%   |
| KYE Systems (Mouse Systems)            | 88       | 4%      |
| Arkmicro Technologies                  | 72       | 3.27%   |
| GEMBIRD                                | 62       | 2.82%   |
| Aveo Technology                        | 60       | 2.72%   |
| Pixart Imaging                         | 50       | 2.27%   |
| Cubeternet                             | 48       | 2.18%   |
| Chicony Electronics                    | 45       | 2.04%   |
| Creative Technology                    | 42       | 1.91%   |
| Alcor Micro                            | 39       | 1.77%   |
| Realtek Semiconductor                  | 37       | 1.68%   |
| Apple                                  | 29       | 1.32%   |
| Samsung Electronics                    | 22       | 1%      |
| Genesys Logic                          | 18       | 0.82%   |
| Sunplus Innovation Technology          | 17       | 0.77%   |
| A4Tech                                 | 16       | 0.73%   |
| Guillemot                              | 13       | 0.59%   |
| Philips (or NXP)                       | 10       | 0.45%   |
| Hewlett-Packard                        | 10       | 0.45%   |
| SiGma Micro                            | 8        | 0.36%   |
| lihappe8                               | 8        | 0.36%   |
| IMC Networks                           | 8        | 0.36%   |
| Generalplus Technology                 | 8        | 0.36%   |
| AVerMedia Technologies                 | 8        | 0.36%   |
| Trust                                  | 6        | 0.27%   |
| SunplusIT                              | 6        | 0.27%   |
| Unknown                                | 4        | 0.18%   |
| Silicon Motion                         | 4        | 0.18%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.18%   |
| Suyin                                  | 3        | 0.14%   |
| Sony                                   | 3        | 0.14%   |
| Sonix Technology                       | 3        | 0.14%   |
| Nokia Mobile Phones                    | 3        | 0.14%   |
| MacroSilicon                           | 3        | 0.14%   |
| Jieli Technology                       | 3        | 0.14%   |
| Canon                                  | 3        | 0.14%   |
| ANYKA                                  | 3        | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 268      | 12.15%  |
| Z-Star Venus USB2.0 Camera                        | 157      | 7.12%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 107      | 4.85%   |
| Microdia Camera                                   | 105      | 4.76%   |
| Z-Star Vimicro USB Camera (Altair)                | 77       | 3.49%   |
| Arkmicro USB2.0 PC CAMERA                         | 66       | 2.99%   |
| Logitech Webcam C170                              | 60       | 2.72%   |
| Logitech Webcam C310                              | 56       | 2.54%   |
| Logitech HD Webcam C525                           | 54       | 2.45%   |
| Logitech Webcam C210                              | 47       | 2.13%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 37       | 1.68%   |
| Microsoft LifeCam HD-3000                         | 34       | 1.54%   |
| GEMBIRD USB2.0 PC CAMERA                          | 31       | 1.41%   |
| Logitech HD Pro Webcam C920                       | 30       | 1.36%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 30       | 1.36%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 26       | 1.18%   |
| Alcor Micro USB 2.0 PC Camera                     | 26       | 1.18%   |
| Logitech Webcam C110                              | 24       | 1.09%   |
| Logitech HD Webcam C510                           | 24       | 1.09%   |
| Apple iPhone5/5C/5S/6                             | 24       | 1.09%   |
| Microsoft LifeCam VX-800                          | 22       | 1%      |
| Aveo Camera                                       | 22       | 1%      |
| Samsung Galaxy A5 (MTP)                           | 21       | 0.95%   |
| Logitech Logitech Webcam C160                     | 19       | 0.86%   |
| Aveo USB2.0 Camera                                | 19       | 0.86%   |
| Logitech HD Webcam C615                           | 18       | 0.82%   |
| Microdia USB 2.0 Camera                           | 17       | 0.77%   |
| Realtek Full HD webcam                            | 16       | 0.73%   |
| Z-Star A4 TECH HD PC Camera                       | 15       | 0.68%   |
| Microdia Sonix USB 2.0 Camera                     | 15       | 0.68%   |
| Logitech HD Webcam C910                           | 15       | 0.68%   |
| Cubeternet USB2.0 Camera                          | 15       | 0.68%   |
| Aveo UVC camera (Bresser microscope)              | 15       | 0.68%   |
| Microsoft LifeCam VX-2000                         | 13       | 0.59%   |
| Microsoft LifeCam HD-5000                         | 13       | 0.59%   |
| Microsoft LifeCam Cinema                          | 13       | 0.59%   |
| Logitech Logitech Webcam C100                     | 13       | 0.59%   |
| Genesys Logic Camera                              | 12       | 0.54%   |
| Microdia MSI Starcam Racer                        | 11       | 0.5%    |
| Logitech Webcam C250                              | 10       | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 2        | 33.33%  |
| LighTuning Technology | 2        | 33.33%  |
| Microsoft             | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader       | 2        | 33.33%  |
| Microsoft Fingerprint Reader                | 1        | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor   | 1        | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Aktiv                      | 11       | 25.58%  |
| Aladdin Knowledge Systems  | 9        | 20.93%  |
| Aladdin R.D.               | 6        | 13.95%  |
| Athena Smartcard Solutions | 4        | 9.3%    |
| Alcor Micro                | 4        | 9.3%    |
| Advanced Card Systems      | 4        | 9.3%    |
| Yubico.com                 | 2        | 4.65%   |
| OmniKey                    | 1        | 2.33%   |
| Gemalto (was Gemplus)      | 1        | 2.33%   |
| Castles Technology         | 1        | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Aktiv Rutoken lite                               | 11       | 25.58%  |
| Aladdin Knowledge Systems Token JC               | 9        | 20.93%  |
| Aladdin R.D. JaCarta                             | 6        | 13.95%  |
| Athena Smartcard Solutions ASEDrive CCID         | 4        | 9.3%    |
| Alcor Micro Watchdata W 1981                     | 3        | 6.98%   |
| Yubico.com Yubikey 4/5 U2F+CCID                  | 2        | 4.65%   |
| OmniKey Smart Card Reader USB                    | 1        | 2.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1        | 2.33%   |
| Castles Technology EZCCID Smart Card Reader      | 1        | 2.33%   |
| Alcor Micro AU9540 Smartcard Reader              | 1        | 2.33%   |
| Advanced Card Systems ACR39U                     | 1        | 2.33%   |
| Advanced Card Systems ACR3901U                   | 1        | 2.33%   |
| Advanced Card Systems ACR38 SmartCard Reader     | 1        | 2.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader     | 1        | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 9347     | 82.22%  |
| 1     | 1833     | 16.12%  |
| 2     | 151      | 1.33%   |
| 3     | 21       | 0.18%   |
| 4     | 9        | 0.08%   |
| 6     | 3        | 0.03%   |
| 5     | 2        | 0.02%   |
| 9     | 1        | 0.01%   |
| 7     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1433     | 66.1%   |
| Net/wireless             | 212      | 9.78%   |
| Communication controller | 136      | 6.27%   |
| Unassigned class         | 84       | 3.87%   |
| Multimedia controller    | 66       | 3.04%   |
| Sound                    | 53       | 2.44%   |
| Chipcard                 | 34       | 1.57%   |
| Camera                   | 31       | 1.43%   |
| Net/ethernet             | 21       | 0.97%   |
| Network                  | 19       | 0.88%   |
| Bluetooth                | 17       | 0.78%   |
| Modem                    | 15       | 0.69%   |
| Storage/raid             | 10       | 0.46%   |
| Dvb card                 | 7        | 0.32%   |
| Firewire controller      | 6        | 0.28%   |
| Fingerprint reader       | 6        | 0.28%   |
| Storage/ide              | 5        | 0.23%   |
| Storage/ata              | 5        | 0.23%   |
| Tv card                  | 3        | 0.14%   |
| Storage                  | 2        | 0.09%   |
| Video                    | 1        | 0.05%   |
| Unclassified device      | 1        | 0.05%   |
| Card reader              | 1        | 0.05%   |


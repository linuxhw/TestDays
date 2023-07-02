Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 7825

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [4b57a18d9b](https://linux-hardware.org/?probe=4b57a18d9b) | Jun 30, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [1abd7f9f95](https://linux-hardware.org/?probe=1abd7f9f95) | Jun 30, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9f8e4c6a70](https://linux-hardware.org/?probe=9f8e4c6a70) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [5b7bc3205d](https://linux-hardware.org/?probe=5b7bc3205d) | Jun 29, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Dell          | 0WK833                      | Desktop     | [fd4a07e088](https://linux-hardware.org/?probe=fd4a07e088) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [d73388baab](https://linux-hardware.org/?probe=d73388baab) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| Dell          | 0WK833                      | Desktop     | [39a5ca93a7](https://linux-hardware.org/?probe=39a5ca93a7) | Jun 27, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [09f4e0e86a](https://linux-hardware.org/?probe=09f4e0e86a) | Jun 27, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [8aaaef4a62](https://linux-hardware.org/?probe=8aaaef4a62) | Jun 27, 2023 |
| MW            | NVR-N5105                   | Desktop     | [36ee490ef2](https://linux-hardware.org/?probe=36ee490ef2) | Jun 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | Notebook    | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [f58c462a34](https://linux-hardware.org/?probe=f58c462a34) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8c0f33ffe](https://linux-hardware.org/?probe=a8c0f33ffe) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9a30b63c87](https://linux-hardware.org/?probe=9a30b63c87) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [2eeb463035](https://linux-hardware.org/?probe=2eeb463035) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [ef129b5a6c](https://linux-hardware.org/?probe=ef129b5a6c) | Jun 25, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [785d3130e7](https://linux-hardware.org/?probe=785d3130e7) | Jun 24, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [68b591e6d8](https://linux-hardware.org/?probe=68b591e6d8) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | Compaq 610                  | Notebook    | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [39d5409264](https://linux-hardware.org/?probe=39d5409264) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [3708ae400f](https://linux-hardware.org/?probe=3708ae400f) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [d447bb1029](https://linux-hardware.org/?probe=d447bb1029) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6e68a59ffb](https://linux-hardware.org/?probe=6e68a59ffb) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [41a5a93ebb](https://linux-hardware.org/?probe=41a5a93ebb) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Foxconn       | ETON                        | Desktop     | [ae0d87abfb](https://linux-hardware.org/?probe=ae0d87abfb) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5fbfa89321](https://linux-hardware.org/?probe=5fbfa89321) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2bd22135e0](https://linux-hardware.org/?probe=2bd22135e0) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5cbbd51d7f](https://linux-hardware.org/?probe=5cbbd51d7f) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [39ed83a165](https://linux-hardware.org/?probe=39ed83a165) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| Dell          | Latitude 7430               | Notebook    | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [6131e6746c](https://linux-hardware.org/?probe=6131e6746c) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2b32ca2d11](https://linux-hardware.org/?probe=2b32ca2d11) | Jun 18, 2023 |
| Toshiba       | NB510                       | Notebook    | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e33558044f](https://linux-hardware.org/?probe=e33558044f) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [b17c80df83](https://linux-hardware.org/?probe=b17c80df83) | Jun 17, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [eebb6ba229](https://linux-hardware.org/?probe=eebb6ba229) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Notebook    | [3ea85763dc](https://linux-hardware.org/?probe=3ea85763dc) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Beelink       | Gemini X                    | Notebook    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | Notebook    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [851020a59f](https://linux-hardware.org/?probe=851020a59f) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [b9eac1e0b6](https://linux-hardware.org/?probe=b9eac1e0b6) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [7ee7ee0f67](https://linux-hardware.org/?probe=7ee7ee0f67) | Jun 14, 2023 |
| HP            | 3397                        | Desktop     | [e67824996f](https://linux-hardware.org/?probe=e67824996f) | Jun 14, 2023 |
| AMI           | Intel                       | Desktop     | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| MW            | NVR-N5105                   | Desktop     | [7481711a2f](https://linux-hardware.org/?probe=7481711a2f) | Jun 13, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [1364983b69](https://linux-hardware.org/?probe=1364983b69) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [7b48584062](https://linux-hardware.org/?probe=7b48584062) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [eac7ae2f7a](https://linux-hardware.org/?probe=eac7ae2f7a) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | Notebook    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [c8e822d0d7](https://linux-hardware.org/?probe=c8e822d0d7) | Jun 10, 2023 |
| MSI           | MS-B0621 100                | All in one  | [aa67f8201a](https://linux-hardware.org/?probe=aa67f8201a) | Jun 10, 2023 |
| Beelink       | Gemini X                    | Notebook    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude E5500              | Notebook    | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [264c056bf2](https://linux-hardware.org/?probe=264c056bf2) | Jun 10, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [1b3630b25a](https://linux-hardware.org/?probe=1b3630b25a) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| MSI           | Boston                      | Desktop     | [cc58f8cdf3](https://linux-hardware.org/?probe=cc58f8cdf3) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 3397                        | Desktop     | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| MSI           | GE66 Raider 10UE            | Notebook    | [38a5122d9c](https://linux-hardware.org/?probe=38a5122d9c) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| Beelink       | Gemini X                    | Notebook    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| HP            | 3397                        | Desktop     | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| HP            | 3396                        | Desktop     | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | Notebook    | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| Intel         | X99 V102                    | Desktop     | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [64c321d474](https://linux-hardware.org/?probe=64c321d474) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [9a0f40789b](https://linux-hardware.org/?probe=9a0f40789b) | Jun 02, 2023 |
| MSI           | Prestige 16 A12UD           | Notebook    | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Notebook      | N141CU                      | Notebook    | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | Notebook    | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| Teclast       | X4                          | Tablet      | [2392aa748a](https://linux-hardware.org/?probe=2392aa748a) | Jun 01, 2023 |
| MSI           | H81M-E33                    | Desktop     | [50f664d550](https://linux-hardware.org/?probe=50f664d550) | Jun 01, 2023 |
| MSI           | H81M-E33                    | Desktop     | [eb2a33204c](https://linux-hardware.org/?probe=eb2a33204c) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [ecc39bf44b](https://linux-hardware.org/?probe=ecc39bf44b) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4fbe93ecc5](https://linux-hardware.org/?probe=4fbe93ecc5) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [15c734c665](https://linux-hardware.org/?probe=15c734c665) | May 29, 2023 |
| HP            | 2820h                       | Desktop     | [d326b49f48](https://linux-hardware.org/?probe=d326b49f48) | May 29, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [b5e36f87e6](https://linux-hardware.org/?probe=b5e36f87e6) | May 28, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [bf9c082ee0](https://linux-hardware.org/?probe=bf9c082ee0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3e43db6ab5](https://linux-hardware.org/?probe=3e43db6ab5) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [d44b92320b](https://linux-hardware.org/?probe=d44b92320b) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [701c6c3410](https://linux-hardware.org/?probe=701c6c3410) | May 24, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [21ee588e1c](https://linux-hardware.org/?probe=21ee588e1c) | May 24, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [5d462a687d](https://linux-hardware.org/?probe=5d462a687d) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [21f52b0bc9](https://linux-hardware.org/?probe=21f52b0bc9) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [4c16a00ef6](https://linux-hardware.org/?probe=4c16a00ef6) | May 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Teclast       | X4                          | Tablet      | [9dc0b8fa7b](https://linux-hardware.org/?probe=9dc0b8fa7b) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [8e7dbefb51](https://linux-hardware.org/?probe=8e7dbefb51) | May 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [89e6088290](https://linux-hardware.org/?probe=89e6088290) | May 20, 2023 |
| HP            | 350 G1                      | Notebook    | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [a8553d6ad6](https://linux-hardware.org/?probe=a8553d6ad6) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| ASUSTek       | TP300LA                     | Notebook    | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| AZW           | GT-R                        | Notebook    | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| HP            | 630                         | Notebook    | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | Notebook    | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| Medion        | MS-7675                     | Desktop     | [4890b5bbf9](https://linux-hardware.org/?probe=4890b5bbf9) | May 16, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [923f447e90](https://linux-hardware.org/?probe=923f447e90) | May 15, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [9cb65eaaf2](https://linux-hardware.org/?probe=9cb65eaaf2) | May 15, 2023 |
| MSI           | H170A PC MATE               | Desktop     | [389ab53539](https://linux-hardware.org/?probe=389ab53539) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [8f36de95ee](https://linux-hardware.org/?probe=8f36de95ee) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [975de0cf0d](https://linux-hardware.org/?probe=975de0cf0d) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| HP            | Presario CQ61               | Notebook    | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [8e867c3cce](https://linux-hardware.org/?probe=8e867c3cce) | May 14, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [dc1d9d7e15](https://linux-hardware.org/?probe=dc1d9d7e15) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| HP            | 630                         | Notebook    | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [bbb7537d59](https://linux-hardware.org/?probe=bbb7537d59) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dc1c717240](https://linux-hardware.org/?probe=dc1c717240) | May 13, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [df0583682c](https://linux-hardware.org/?probe=df0583682c) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [f9ccb88980](https://linux-hardware.org/?probe=f9ccb88980) | May 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d43aab6fd](https://linux-hardware.org/?probe=3d43aab6fd) | May 12, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [db2c740451](https://linux-hardware.org/?probe=db2c740451) | May 12, 2023 |
| Gigabyte      | MW51-HP0-00                 | Desktop     | [ed263fdd1b](https://linux-hardware.org/?probe=ed263fdd1b) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [730cce9495](https://linux-hardware.org/?probe=730cce9495) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Acer          | Aspire 5253G                | Notebook    | [c5cae82cf1](https://linux-hardware.org/?probe=c5cae82cf1) | May 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [62abfc3d83](https://linux-hardware.org/?probe=62abfc3d83) | May 11, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [4c714fc6ea](https://linux-hardware.org/?probe=4c714fc6ea) | May 11, 2023 |
| Medion        | MS-7848                     | Desktop     | [e5e1e75529](https://linux-hardware.org/?probe=e5e1e75529) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [30036be67b](https://linux-hardware.org/?probe=30036be67b) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [b93ef808c5](https://linux-hardware.org/?probe=b93ef808c5) | May 10, 2023 |
| Samsung       | X420/X520                   | Notebook    | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [d4846b3b14](https://linux-hardware.org/?probe=d4846b3b14) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 304Ah                       | Desktop     | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [83741a7884](https://linux-hardware.org/?probe=83741a7884) | May 09, 2023 |
| ASRock        | A55M-DGS                    | Desktop     | [528232ffb1](https://linux-hardware.org/?probe=528232ffb1) | May 09, 2023 |
| HP            | 630                         | Notebook    | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | Notebook    | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b76481d6a9](https://linux-hardware.org/?probe=b76481d6a9) | May 09, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [228e778389](https://linux-hardware.org/?probe=228e778389) | May 09, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Intel         | NUC11TNBi5 M61235-402       | Mini pc     | [b85a510a03](https://linux-hardware.org/?probe=b85a510a03) | May 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9e3f14cf8d](https://linux-hardware.org/?probe=9e3f14cf8d) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [9369acb33c](https://linux-hardware.org/?probe=9369acb33c) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| eMachines     | eME728                      | Notebook    | [031e24359e](https://linux-hardware.org/?probe=031e24359e) | May 06, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [421f2de1c3](https://linux-hardware.org/?probe=421f2de1c3) | May 05, 2023 |
| HP            | 630                         | Notebook    | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | Notebook    | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7dabc9fc5c](https://linux-hardware.org/?probe=7dabc9fc5c) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [18895a52d4](https://linux-hardware.org/?probe=18895a52d4) | May 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [1f8f3c96a5](https://linux-hardware.org/?probe=1f8f3c96a5) | May 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [43f32e7ed8](https://linux-hardware.org/?probe=43f32e7ed8) | May 05, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e3dbb15ed](https://linux-hardware.org/?probe=9e3dbb15ed) | May 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [e146c82a49](https://linux-hardware.org/?probe=e146c82a49) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [caf5cbc634](https://linux-hardware.org/?probe=caf5cbc634) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [ad56dc6f51](https://linux-hardware.org/?probe=ad56dc6f51) | May 03, 2023 |
| Unknown       | Intel X79                   | Desktop     | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [f2c18c96df](https://linux-hardware.org/?probe=f2c18c96df) | May 02, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [2f16b0a530](https://linux-hardware.org/?probe=2f16b0a530) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [fb815bb11c](https://linux-hardware.org/?probe=fb815bb11c) | May 02, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c2dcdb892d](https://linux-hardware.org/?probe=c2dcdb892d) | May 01, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [3ca97c367a](https://linux-hardware.org/?probe=3ca97c367a) | May 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| HP            | 1495                        | Desktop     | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [88d774df0d](https://linux-hardware.org/?probe=88d774df0d) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [81cff8a578](https://linux-hardware.org/?probe=81cff8a578) | Apr 29, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [87d4b56fee](https://linux-hardware.org/?probe=87d4b56fee) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [a418b302b9](https://linux-hardware.org/?probe=a418b302b9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [00fe705be0](https://linux-hardware.org/?probe=00fe705be0) | Apr 27, 2023 |
| Lenovo        | 318D                        | All in one  | [8cf49b59a5](https://linux-hardware.org/?probe=8cf49b59a5) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| HP            | Compaq 15                   | Notebook    | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [6d981e0d7c](https://linux-hardware.org/?probe=6d981e0d7c) | Apr 25, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [2e4cd9799b](https://linux-hardware.org/?probe=2e4cd9799b) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| INSYS         | PT1-140C                    | Notebook    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [f4a215fc46](https://linux-hardware.org/?probe=f4a215fc46) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [7609d632a4](https://linux-hardware.org/?probe=7609d632a4) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| Intel         | NUC7i7DNB J83500-206        | Mini pc     | [b00fa62f7c](https://linux-hardware.org/?probe=b00fa62f7c) | Apr 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| HP            | Notebook                    | Notebook    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [694966dbd7](https://linux-hardware.org/?probe=694966dbd7) | Apr 22, 2023 |
| Shuttle       | FG45 V10                    | Desktop     | [b5a9d7b1e4](https://linux-hardware.org/?probe=b5a9d7b1e4) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [11f0485b1a](https://linux-hardware.org/?probe=11f0485b1a) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [969bbe5df0](https://linux-hardware.org/?probe=969bbe5df0) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [e76fb532be](https://linux-hardware.org/?probe=e76fb532be) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | Notebook    | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [3193403ef5](https://linux-hardware.org/?probe=3193403ef5) | Apr 19, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [80ee2192b6](https://linux-hardware.org/?probe=80ee2192b6) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [178dbe3693](https://linux-hardware.org/?probe=178dbe3693) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [973070ca0e](https://linux-hardware.org/?probe=973070ca0e) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [8858427eed](https://linux-hardware.org/?probe=8858427eed) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d076bcd8a5](https://linux-hardware.org/?probe=d076bcd8a5) | Apr 19, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [e9278fb49b](https://linux-hardware.org/?probe=e9278fb49b) | Apr 18, 2023 |
| MSI           | PS42 Modern 8RC             | Notebook    | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| HP            | 212A                        | Desktop     | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [8b6a2af9ce](https://linux-hardware.org/?probe=8b6a2af9ce) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| Medion        | E15415                      | Notebook    | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [5b446c43f3](https://linux-hardware.org/?probe=5b446c43f3) | Apr 15, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [8c450d2469](https://linux-hardware.org/?probe=8c450d2469) | Apr 15, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [f3bbb04052](https://linux-hardware.org/?probe=f3bbb04052) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [d5212d6298](https://linux-hardware.org/?probe=d5212d6298) | Apr 13, 2023 |
| Lenovo        | ThinkPad T410 2537NY6       | Notebook    | [977014ae11](https://linux-hardware.org/?probe=977014ae11) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | Notebook    | [a9b7cf3c18](https://linux-hardware.org/?probe=a9b7cf3c18) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | Notebook    | [b2259951b5](https://linux-hardware.org/?probe=b2259951b5) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [8fdb71aed1](https://linux-hardware.org/?probe=8fdb71aed1) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [0ba5f3a06e](https://linux-hardware.org/?probe=0ba5f3a06e) | Apr 12, 2023 |
| HP            | 3396                        | Desktop     | [25eac72561](https://linux-hardware.org/?probe=25eac72561) | Apr 12, 2023 |
| HP            | 1589                        | Desktop     | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [27688332ee](https://linux-hardware.org/?probe=27688332ee) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | Notebook    | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Gigabyte      | B75-D3V                     | Desktop     | [fe025c9491](https://linux-hardware.org/?probe=fe025c9491) | Apr 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a2dcc97485](https://linux-hardware.org/?probe=a2dcc97485) | Apr 09, 2023 |
| HP            | 1998                        | Desktop     | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7033d674d8](https://linux-hardware.org/?probe=7033d674d8) | Apr 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [05fc2725cf](https://linux-hardware.org/?probe=05fc2725cf) | Apr 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [10eeff8916](https://linux-hardware.org/?probe=10eeff8916) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [05aaab32ca](https://linux-hardware.org/?probe=05aaab32ca) | Apr 08, 2023 |
| AMI           | Intel                       | Desktop     | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [98bc626360](https://linux-hardware.org/?probe=98bc626360) | Apr 07, 2023 |
| Dell          | Latitude E5550              | Notebook    | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| HP            | 1998                        | Desktop     | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d492c2eca8](https://linux-hardware.org/?probe=d492c2eca8) | Apr 06, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Packard Be... | IMEDIA S2870 V1.0           | Desktop     | [61e1ab6733](https://linux-hardware.org/?probe=61e1ab6733) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [705d5f2396](https://linux-hardware.org/?probe=705d5f2396) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| Dell          | Latitude E4200              | Notebook    | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| HP            | 1998                        | Desktop     | [4830678f31](https://linux-hardware.org/?probe=4830678f31) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| ASUSTek       | VM42                        | Desktop     | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d006e94e8f](https://linux-hardware.org/?probe=d006e94e8f) | Apr 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [0a39d6faec](https://linux-hardware.org/?probe=0a39d6faec) | Apr 04, 2023 |
| Medion        | E2221T MD61083              | Convertible | [daa63988bd](https://linux-hardware.org/?probe=daa63988bd) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [151ffca106](https://linux-hardware.org/?probe=151ffca106) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [fb78fdb60c](https://linux-hardware.org/?probe=fb78fdb60c) | Apr 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [70eb6c0ec1](https://linux-hardware.org/?probe=70eb6c0ec1) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Google        | Snappy                      | Notebook    | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [61b490cae8](https://linux-hardware.org/?probe=61b490cae8) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | Notebook    | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c767575f27](https://linux-hardware.org/?probe=c767575f27) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [bb72de54b6](https://linux-hardware.org/?probe=bb72de54b6) | Mar 31, 2023 |
| HP            | 1998                        | Desktop     | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [ed35fbea6c](https://linux-hardware.org/?probe=ed35fbea6c) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Primux Tec... | A173                        | All in one  | [f31f5f63b9](https://linux-hardware.org/?probe=f31f5f63b9) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| Primux Tec... | A173                        | All in one  | [95e3fd6b4b](https://linux-hardware.org/?probe=95e3fd6b4b) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [307a8bce3e](https://linux-hardware.org/?probe=307a8bce3e) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [b924b0ff06](https://linux-hardware.org/?probe=b924b0ff06) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | Notebook    | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | Notebook    | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | Notebook    | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | Notebook    | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [7fba52ef43](https://linux-hardware.org/?probe=7fba52ef43) | Mar 27, 2023 |
| IP3 Tech      | GB3B                        | Mini pc     | [58b3789af3](https://linux-hardware.org/?probe=58b3789af3) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | Notebook    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [6a3fedcc68](https://linux-hardware.org/?probe=6a3fedcc68) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | Notebook    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | Notebook    | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [8a0cc5a4cb](https://linux-hardware.org/?probe=8a0cc5a4cb) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | Notebook    | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| HP            | 1790                        | Desktop     | [1a468c1b1c](https://linux-hardware.org/?probe=1a468c1b1c) | Mar 24, 2023 |
| Dell          | G15 5515                    | Notebook    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [81273bd2b0](https://linux-hardware.org/?probe=81273bd2b0) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2db2fb4a5a](https://linux-hardware.org/?probe=2db2fb4a5a) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [79cbdbc9c1](https://linux-hardware.org/?probe=79cbdbc9c1) | Mar 24, 2023 |
| HP            | 2000                        | Notebook    | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | Notebook    | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fc5894dcb4](https://linux-hardware.org/?probe=fc5894dcb4) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| ASUSTek       | PB60                        | Desktop     | [ec438486aa](https://linux-hardware.org/?probe=ec438486aa) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [c2bab115eb](https://linux-hardware.org/?probe=c2bab115eb) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [aab84f14ed](https://linux-hardware.org/?probe=aab84f14ed) | Mar 21, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [deaf7b9049](https://linux-hardware.org/?probe=deaf7b9049) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| HP            | 250 G4                      | Notebook    | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Supermicro    | X10SRL-F                    | Server      | [96e896465a](https://linux-hardware.org/?probe=96e896465a) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | Notebook    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [09fac43b8e](https://linux-hardware.org/?probe=09fac43b8e) | Mar 17, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [c94efea21b](https://linux-hardware.org/?probe=c94efea21b) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [afd7547cd1](https://linux-hardware.org/?probe=afd7547cd1) | Mar 16, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| Acer          | FIH57                       | Desktop     | [ee8c95f841](https://linux-hardware.org/?probe=ee8c95f841) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| Intel         | Unknown                     | Desktop     | [b4b73aafa0](https://linux-hardware.org/?probe=b4b73aafa0) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | Notebook    | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [c436834b30](https://linux-hardware.org/?probe=c436834b30) | Mar 14, 2023 |
| ZOTAC         | ZBOX-ID41                   | Mini pc     | [620812fe84](https://linux-hardware.org/?probe=620812fe84) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [cf5cbabe11](https://linux-hardware.org/?probe=cf5cbabe11) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| MSI           | MS-B1831                    | Desktop     | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [86a3944105](https://linux-hardware.org/?probe=86a3944105) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [96c3aadd1e](https://linux-hardware.org/?probe=96c3aadd1e) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Intel         | S2600WT2R H21573-372        | Server      | [18134c0dc1](https://linux-hardware.org/?probe=18134c0dc1) | Mar 10, 2023 |
| Intel         | S2600WT2R H21573-372        | Server      | [572cded7f3](https://linux-hardware.org/?probe=572cded7f3) | Mar 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [5df81d1297](https://linux-hardware.org/?probe=5df81d1297) | Mar 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a40a70a964](https://linux-hardware.org/?probe=a40a70a964) | Mar 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [946f48cdf6](https://linux-hardware.org/?probe=946f48cdf6) | Mar 09, 2023 |
| FriendlyEl... | NanoPC-T4                   | Soc         | [901194d1e1](https://linux-hardware.org/?probe=901194d1e1) | Mar 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | Notebook    | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | Desktop     | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7c17068a98](https://linux-hardware.org/?probe=7c17068a98) | Mar 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [6552e8b371](https://linux-hardware.org/?probe=6552e8b371) | Mar 07, 2023 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [4e2cd40175](https://linux-hardware.org/?probe=4e2cd40175) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| HP            | 2B0A                        | All in one  | [35f88e8f33](https://linux-hardware.org/?probe=35f88e8f33) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | Notebook    | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | Notebook    | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| HP            | 87A4 10100                  | All in one  | [6b92aede76](https://linux-hardware.org/?probe=6b92aede76) | Mar 05, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c6bb0ba4a6](https://linux-hardware.org/?probe=c6bb0ba4a6) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [f4cf2185ea](https://linux-hardware.org/?probe=f4cf2185ea) | Mar 04, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Intel         | powered classmate PC        | Notebook    | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49462bd855](https://linux-hardware.org/?probe=49462bd855) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c7cee84058](https://linux-hardware.org/?probe=c7cee84058) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [5033b7233d](https://linux-hardware.org/?probe=5033b7233d) | Mar 03, 2023 |
| Chuwi         | UBook                       | Tablet      | [6cbfc99f43](https://linux-hardware.org/?probe=6cbfc99f43) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | Notebook    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [0a38248462](https://linux-hardware.org/?probe=0a38248462) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| ASRock        | Q1900M Pro3                 | Desktop     | [ef9e90045e](https://linux-hardware.org/?probe=ef9e90045e) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [84a1a2c71e](https://linux-hardware.org/?probe=84a1a2c71e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | Notebook    | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [72d16085b5](https://linux-hardware.org/?probe=72d16085b5) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f03ce01ac3](https://linux-hardware.org/?probe=f03ce01ac3) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [24952b3b19](https://linux-hardware.org/?probe=24952b3b19) | Feb 27, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [319e003280](https://linux-hardware.org/?probe=319e003280) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [d3e84076c7](https://linux-hardware.org/?probe=d3e84076c7) | Feb 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32453b16fb](https://linux-hardware.org/?probe=32453b16fb) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cbadc857a2](https://linux-hardware.org/?probe=cbadc857a2) | Feb 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c7477f1aca](https://linux-hardware.org/?probe=c7477f1aca) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc7b5cb76e](https://linux-hardware.org/?probe=dc7b5cb76e) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | Notebook    | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | Notebook    | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | Notebook    | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9d39d13682](https://linux-hardware.org/?probe=9d39d13682) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3c27f298a3](https://linux-hardware.org/?probe=3c27f298a3) | Feb 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [8bb60bdebb](https://linux-hardware.org/?probe=8bb60bdebb) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d8bafec2da](https://linux-hardware.org/?probe=d8bafec2da) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e7175cb8fe](https://linux-hardware.org/?probe=e7175cb8fe) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | Notebook    | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f75f800bd4](https://linux-hardware.org/?probe=f75f800bd4) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [804306660e](https://linux-hardware.org/?probe=804306660e) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | Notebook    | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| Acer          | H57M01                      | Desktop     | [5e5e9d03a4](https://linux-hardware.org/?probe=5e5e9d03a4) | Feb 19, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [3f26c5e55c](https://linux-hardware.org/?probe=3f26c5e55c) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [e87ff10942](https://linux-hardware.org/?probe=e87ff10942) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [eff21e4d65](https://linux-hardware.org/?probe=eff21e4d65) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [2c3eb25bc4](https://linux-hardware.org/?probe=2c3eb25bc4) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [0f6c993491](https://linux-hardware.org/?probe=0f6c993491) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [f44579d8b4](https://linux-hardware.org/?probe=f44579d8b4) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [db4fef5830](https://linux-hardware.org/?probe=db4fef5830) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | Notebook    | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | 371C No DPK                 | All in one  | [02248f5982](https://linux-hardware.org/?probe=02248f5982) | Feb 16, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [5d03d010f4](https://linux-hardware.org/?probe=5d03d010f4) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | Notebook    | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Intel         | X79M-S                      | Desktop     | [2d3579e9b7](https://linux-hardware.org/?probe=2d3579e9b7) | Feb 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [8a7ce6b005](https://linux-hardware.org/?probe=8a7ce6b005) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e5b971a4b0](https://linux-hardware.org/?probe=e5b971a4b0) | Feb 14, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [3f40aab3d2](https://linux-hardware.org/?probe=3f40aab3d2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4211a6a7f4](https://linux-hardware.org/?probe=4211a6a7f4) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f3e396ccc3](https://linux-hardware.org/?probe=f3e396ccc3) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | Notebook    | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7458415afe](https://linux-hardware.org/?probe=7458415afe) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [39b7eef9e8](https://linux-hardware.org/?probe=39b7eef9e8) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | Notebook    | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [7b2f03d111](https://linux-hardware.org/?probe=7b2f03d111) | Feb 10, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [0bd59541f9](https://linux-hardware.org/?probe=0bd59541f9) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [f7df102318](https://linux-hardware.org/?probe=f7df102318) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | Notebook    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Lenovo        | 3741 NOK                    | Desktop     | [eeb2a331be](https://linux-hardware.org/?probe=eeb2a331be) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [e6f4812d50](https://linux-hardware.org/?probe=e6f4812d50) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a255954f75](https://linux-hardware.org/?probe=a255954f75) | Feb 06, 2023 |
| Unknown       | Intel X79                   | Desktop     | [2ad659fd7a](https://linux-hardware.org/?probe=2ad659fd7a) | Feb 06, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2e5b18f7c5](https://linux-hardware.org/?probe=2e5b18f7c5) | Feb 05, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | Desktop     | [9e8c261333](https://linux-hardware.org/?probe=9e8c261333) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [bede5aa93c](https://linux-hardware.org/?probe=bede5aa93c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | Notebook    | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | Notebook    | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X8DTL                       | Server      | [a3be5cdf41](https://linux-hardware.org/?probe=a3be5cdf41) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [0bd8186d9e](https://linux-hardware.org/?probe=0bd8186d9e) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | Notebook    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | 805D                        | Desktop     | [109d9e2356](https://linux-hardware.org/?probe=109d9e2356) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [dafdc36e54](https://linux-hardware.org/?probe=dafdc36e54) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [ed417f3a04](https://linux-hardware.org/?probe=ed417f3a04) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [7a8522045b](https://linux-hardware.org/?probe=7a8522045b) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | Notebook    | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [838de293f2](https://linux-hardware.org/?probe=838de293f2) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | Notebook    | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | Desktop     | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | Notebook    | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| HP            | G62                         | Notebook    | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | Notebook    | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | Notebook    | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | Notebook    | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [854a69817d](https://linux-hardware.org/?probe=854a69817d) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Medion        | MS-7675                     | Desktop     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| MSI           | MS-7383                     | Desktop     | [d47659fcf8](https://linux-hardware.org/?probe=d47659fcf8) | Jan 25, 2023 |
| MSI           | MS-7383                     | Desktop     | [b848100b0e](https://linux-hardware.org/?probe=b848100b0e) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | Notebook    | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 732       | 12.88%  |
| Ubuntu 18.04                 | 511       | 8.99%   |
| Ubuntu 22.04                 | 264       | 4.65%   |
| Debian 11                    | 245       | 4.31%   |
| OpenMandriva 4.2             | 182       | 3.2%    |
| OpenMandriva 4.3             | 122       | 2.15%   |
| KDE neon 20.04               | 112       | 1.97%   |
| Zorin 16                     | 104       | 1.83%   |
| Manjaro                      | 85        | 1.5%    |
| OpenMandriva 23.01           | 84        | 1.48%   |
| Debian 10                    | 83        | 1.46%   |
| Linux Mint 20.3              | 81        | 1.43%   |
| Arch Rolling                 | 80        | 1.41%   |
| Ubuntu 20.10                 | 72        | 1.27%   |
| Linux Mint 19.3              | 71        | 1.25%   |
| Linux Mint 21.1              | 68        | 1.2%    |
| Arch                         | 65        | 1.14%   |
| Xubuntu 20.04                | 62        | 1.09%   |
| Ubuntu 19.04                 | 61        | 1.07%   |
| Ubuntu 19.10                 | 58        | 1.02%   |
| Linux Mint 20.1              | 58        | 1.02%   |
| Fedora 36                    | 55        | 0.97%   |
| Ubuntu 21.04                 | 53        | 0.93%   |
| Linux Mint 20                | 52        | 0.92%   |
| Fedora 37                    | 51        | 0.9%    |
| Ubuntu 21.10                 | 50        | 0.88%   |
| Linux Mint 20.2              | 48        | 0.84%   |
| Xubuntu 18.04                | 47        | 0.83%   |
| Fedora 35                    | 47        | 0.83%   |
| OpenMandriva 23.03           | 46        | 0.81%   |
| Kubuntu 20.04                | 45        | 0.79%   |
| ROSA R10                     | 43        | 0.76%   |
| Pop!_OS 22.04                | 42        | 0.74%   |
| Ubuntu 22.10                 | 41        | 0.72%   |
| Linux Mint 21                | 41        | 0.72%   |
| Zorin 15                     | 40        | 0.7%    |
| Fedora 34                    | 40        | 0.7%    |
| Fedora 33                    | 38        | 0.67%   |
| Pop!_OS 20.04                | 37        | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 36        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1838      | 34.28%  |
| Linux Mint    | 454       | 8.47%   |
| OpenMandriva  | 438       | 8.17%   |
| Debian        | 397       | 7.41%   |
| Fedora        | 269       | 5.02%   |
| Manjaro       | 198       | 3.69%   |
| KDE neon      | 152       | 2.84%   |
| Zorin         | 149       | 2.78%   |
| Arch          | 143       | 2.67%   |
| Xubuntu       | 129       | 2.41%   |
| Pop!_OS       | 126       | 2.35%   |
| Endless       | 123       | 2.29%   |
| Kubuntu       | 113       | 2.11%   |
| ROSA          | 111       | 2.07%   |
| Ubuntu MATE   | 59        | 1.1%    |
| openSUSE      | 56        | 1.04%   |
| Elementary    | 55        | 1.03%   |
| Gentoo        | 48        | 0.9%    |
| ArcoLinux     | 46        | 0.86%   |
| Ubuntu Unity  | 40        | 0.75%   |
| Kali          | 40        | 0.75%   |
| Lubuntu       | 32        | 0.6%    |
| SteamOS       | 30        | 0.56%   |
| BlackPanther  | 29        | 0.54%   |
| LMDE          | 23        | 0.43%   |
| EndeavourOS   | 21        | 0.39%   |
| Parrot        | 20        | 0.37%   |
| MX            | 20        | 0.37%   |
| Nobara        | 17        | 0.32%   |
| Clear Linux   | 16        | 0.3%    |
| Ubuntu Budgie | 13        | 0.24%   |
| Garuda Linux  | 10        | 0.19%   |
| CentOS        | 10        | 0.19%   |
| Reborn OS     | 8         | 0.15%   |
| RHEL          | 6         | 0.11%   |
| Deepin        | 6         | 0.11%   |
| Ubuntu Studio | 5         | 0.09%   |
| Solus         | 5         | 0.09%   |
| Peppermint    | 5         | 0.09%   |
| Slackware     | 4         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 178       | 2.87%   |
| 5.16.7-desktop-1omv4003         | 119       | 1.92%   |
| 5.4.0-42-generic                | 96        | 1.55%   |
| 6.1.1-desktop-1omv2290          | 79        | 1.27%   |
| 5.15.0-56-generic               | 65        | 1.05%   |
| 5.4.0-58-generic                | 60        | 0.97%   |
| 5.10.0-8-amd64                  | 56        | 0.9%    |
| 5.4.0-52-generic                | 49        | 0.79%   |
| 5.4.0-54-generic                | 48        | 0.77%   |
| 5.4.0-26-generic                | 47        | 0.76%   |
| 6.2.6-desktop-1omv2390          | 44        | 0.71%   |
| 5.15.0-52-generic               | 44        | 0.71%   |
| 5.3.0-28-generic                | 42        | 0.68%   |
| 5.15.0-58-generic               | 42        | 0.68%   |
| 5.4.0-48-generic                | 39        | 0.63%   |
| 5.11.0-27-generic               | 38        | 0.61%   |
| 5.3.0-40-generic                | 37        | 0.6%    |
| 5.0.0-37-generic                | 36        | 0.58%   |
| 5.4.0-29-generic                | 34        | 0.55%   |
| 5.4.0-65-generic                | 32        | 0.52%   |
| 5.3.0-46-generic                | 32        | 0.52%   |
| 5.19.0-35-generic               | 32        | 0.52%   |
| 5.13.0-30-generic               | 32        | 0.52%   |
| 5.11.0-43-generic               | 32        | 0.52%   |
| 5.15.0-60-generic               | 31        | 0.5%    |
| 5.10.0-18-amd64                 | 31        | 0.5%    |
| 5.10.0-21-amd64                 | 30        | 0.48%   |
| 5.0.0-32-generic                | 30        | 0.48%   |
| 5.4.0-72-generic                | 29        | 0.47%   |
| 5.4.0-40-generic                | 29        | 0.47%   |
| 5.15.0-48-generic               | 29        | 0.47%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.47%   |
| 5.4.0-47-generic                | 27        | 0.44%   |
| 5.4.0-37-generic                | 27        | 0.44%   |
| 5.3.0-51-generic                | 27        | 0.44%   |
| 5.19.0-38-generic               | 26        | 0.42%   |
| 5.15.0-53-generic               | 26        | 0.42%   |
| 5.13.0-39-generic               | 26        | 0.42%   |
| 5.13.0-28-generic               | 26        | 0.42%   |
| 5.11.0-41-generic               | 26        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 957       | 16.42%  |
| 5.15.0  | 477       | 8.18%   |
| 4.15.0  | 419       | 7.19%   |
| 5.10.0  | 285       | 4.89%   |
| 5.11.0  | 277       | 4.75%   |
| 5.8.0   | 266       | 4.56%   |
| 5.3.0   | 254       | 4.36%   |
| 5.13.0  | 248       | 4.25%   |
| 5.0.0   | 198       | 3.4%    |
| 5.10.14 | 180       | 3.09%   |
| 5.19.0  | 178       | 3.05%   |
| 5.16.7  | 123       | 2.11%   |
| 4.18.0  | 114       | 1.96%   |
| 6.1.1   | 89        | 1.53%   |
| 4.19.0  | 85        | 1.46%   |
| 6.2.6   | 57        | 0.98%   |
| 6.1.0   | 40        | 0.69%   |
| 4.9.60  | 33        | 0.57%   |
| 6.0.0   | 27        | 0.46%   |
| 4.18.16 | 23        | 0.39%   |
| 5.14.0  | 22        | 0.38%   |
| 4.4.0   | 22        | 0.38%   |
| 6.2.0   | 21        | 0.36%   |
| 5.18.0  | 21        | 0.36%   |
| 5.17.5  | 16        | 0.27%   |
| 6.0.12  | 15        | 0.26%   |
| 5.9.16  | 15        | 0.26%   |
| 5.9.0   | 13        | 0.22%   |
| 5.16.0  | 13        | 0.22%   |
| 6.1.11  | 12        | 0.21%   |
| 5.7.0   | 12        | 0.21%   |
| 5.3.18  | 12        | 0.21%   |
| 5.16.11 | 12        | 0.21%   |
| 5.12.4  | 12        | 0.21%   |
| 4.9.20  | 12        | 0.21%   |
| 6.1.12  | 11        | 0.19%   |
| 5.15.6  | 11        | 0.19%   |
| 6.3.5   | 10        | 0.17%   |
| 6.2.12  | 10        | 0.17%   |
| 6.0.8   | 10        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1021      | 17.74%  |
| 5.15    | 601       | 10.44%  |
| 5.10    | 545       | 9.47%   |
| 4.15    | 419       | 7.28%   |
| 5.11    | 334       | 5.8%    |
| 5.8     | 326       | 5.66%   |
| 5.13    | 286       | 4.97%   |
| 5.3     | 282       | 4.9%    |
| 5.19    | 239       | 4.15%   |
| 6.1     | 212       | 3.68%   |
| 5.0     | 202       | 3.51%   |
| 5.16    | 188       | 3.27%   |
| 4.18    | 138       | 2.4%    |
| 6.2     | 132       | 2.29%   |
| 6.0     | 107       | 1.86%   |
| 4.19    | 100       | 1.74%   |
| 4.9     | 80        | 1.39%   |
| 5.14    | 79        | 1.37%   |
| 5.18    | 67        | 1.16%   |
| 5.9     | 52        | 0.9%    |
| 5.6     | 51        | 0.89%   |
| 5.17    | 50        | 0.87%   |
| 5.7     | 45        | 0.78%   |
| 5.12    | 44        | 0.76%   |
| 6.3     | 41        | 0.71%   |
| 5.5     | 26        | 0.45%   |
| 4.4     | 26        | 0.45%   |
| 4.1     | 9         | 0.16%   |
| 5.2     | 8         | 0.14%   |
| 3.10    | 8         | 0.14%   |
| 5.1     | 7         | 0.12%   |
| 4.16    | 6         | 0.1%    |
| 4.20    | 4         | 0.07%   |
| 4.17    | 4         | 0.07%   |
| 4.13    | 4         | 0.07%   |
| 4.8     | 3         | 0.05%   |
| 4.14    | 3         | 0.05%   |
| 3.16    | 3         | 0.05%   |
| 4.12    | 2         | 0.03%   |
| 3.18    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4959      | 95.88%  |
| i686    | 180       | 3.48%   |
| aarch64 | 25        | 0.48%   |
| armv7l  | 7         | 0.14%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2296      | 42.22%  |
| KDE5             | 979       | 18%     |
| Unknown          | 654       | 12.03%  |
| XFCE             | 409       | 7.52%   |
| X-Cinnamon       | 357       | 6.56%   |
| MATE             | 163       | 3%      |
| KDE              | 158       | 2.91%   |
| LXQt             | 54        | 0.99%   |
| Cinnamon         | 53        | 0.97%   |
| Pantheon         | 51        | 0.94%   |
| KDE4             | 48        | 0.88%   |
| Unity            | 39        | 0.72%   |
| i3               | 34        | 0.63%   |
| Budgie           | 26        | 0.48%   |
| LXDE             | 21        | 0.39%   |
| Deepin           | 19        | 0.35%   |
| GNOME Flashback  | 16        | 0.29%   |
| openbox          | 10        | 0.18%   |
| GNOME Classic    | 7         | 0.13%   |
| bspwm            | 7         | 0.13%   |
| Dwm              | 5         | 0.09%   |
| qtile            | 4         | 0.07%   |
| xmonad           | 3         | 0.06%   |
| LeftWM           | 3         | 0.06%   |
| ICEWM            | 3         | 0.06%   |
| Enlightenment    | 3         | 0.06%   |
| trinity          | 2         | 0.04%   |
| sway             | 2         | 0.04%   |
| i3-with-shmlog   | 2         | 0.04%   |
| Hyprland         | 2         | 0.04%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| chadwm           | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4163      | 78.11%  |
| Wayland | 735       | 13.79%  |
| Unknown | 349       | 6.55%   |
| Tty     | 83        | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2765      | 51.43%  |
| SDDM    | 844       | 15.7%   |
| GDM     | 593       | 11.03%  |
| GDM3    | 505       | 9.39%   |
| LightDM | 439       | 8.17%   |
| TDM     | 150       | 2.79%   |
| KDM     | 48        | 0.89%   |
| XDM     | 13        | 0.24%   |
| LXDM    | 8         | 0.15%   |
| SLiM    | 5         | 0.09%   |
| Ly      | 5         | 0.09%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 3124      | 58.55%  |
| en_US          | 926       | 17.35%  |
| Unknown        | 650       | 12.18%  |
| ca_ES          | 193       | 3.62%   |
| en_GB          | 113       | 2.12%   |
| C              | 52        | 0.97%   |
| gl_ES          | 33        | 0.62%   |
| de_DE          | 33        | 0.62%   |
| eu_ES          | 26        | 0.49%   |
| fr_FR          | 20        | 0.37%   |
| ru_RU          | 19        | 0.36%   |
| it_IT          | 16        | 0.3%    |
| an_ES          | 13        | 0.24%   |
| es_MX          | 10        | 0.19%   |
| es_AR          | 10        | 0.19%   |
| pt_BR          | 7         | 0.13%   |
| ca_AD          | 7         | 0.13%   |
| en_IE          | 6         | 0.11%   |
| ro_RO          | 5         | 0.09%   |
| pl_PL          | 5         | 0.09%   |
| en_AG          | 5         | 0.09%   |
| ca_ES@valencia | 5         | 0.09%   |
| C.UTF8         | 5         | 0.09%   |
| POSIX          | 4         | 0.07%   |
| es_ES.UTF8     | 4         | 0.07%   |
| pt_PT          | 3         | 0.06%   |
| nl_NL          | 3         | 0.06%   |
| fr_BE          | 3         | 0.06%   |
| de_AT          | 3         | 0.06%   |
| fr_CH          | 2         | 0.04%   |
| es_US          | 2         | 0.04%   |
| es_BO          | 2         | 0.04%   |
| en_DK          | 2         | 0.04%   |
| en_AU          | 2         | 0.04%   |
| de_CH          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2704      | 51.12%  |
| EFI  | 2586      | 48.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4046      | 76.12%  |
| Overlay  | 460       | 8.65%   |
| Btrfs    | 380       | 7.15%   |
| Unknown  | 212       | 3.99%   |
| Xfs      | 75        | 1.41%   |
| Tmpfs    | 52        | 0.98%   |
| Ext3     | 34        | 0.64%   |
| Zfs      | 27        | 0.51%   |
| Ext2     | 16        | 0.3%    |
| Reiserfs | 4         | 0.08%   |
| Jfs      | 3         | 0.06%   |
| F2fs     | 3         | 0.06%   |
| Aufs     | 3         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2928      | 55.14%  |
| GPT     | 1809      | 34.07%  |
| MBR     | 573       | 10.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4418      | 83.48%  |
| Yes       | 874       | 16.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3509      | 66.56%  |
| Yes       | 1763      | 33.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 984       | 19.03%  |
| Hewlett-Packard         | 732       | 14.16%  |
| Lenovo                  | 611       | 11.82%  |
| MSI                     | 461       | 8.92%   |
| Gigabyte Technology     | 429       | 8.3%    |
| Acer                    | 341       | 6.6%    |
| Dell                    | 321       | 6.21%   |
| Apple                   | 127       | 2.46%   |
| ASRock                  | 125       | 2.42%   |
| Toshiba                 | 113       | 2.19%   |
| Intel                   | 83        | 1.61%   |
| Unknown                 | 68        | 1.32%   |
| HUAWEI                  | 49        | 0.95%   |
| Packard Bell            | 45        | 0.87%   |
| Sony                    | 42        | 0.81%   |
| Chuwi                   | 41        | 0.79%   |
| Medion                  | 40        | 0.77%   |
| Samsung Electronics     | 34        | 0.66%   |
| Notebook                | 32        | 0.62%   |
| SLIMBOOK                | 27        | 0.52%   |
| Valve                   | 26        | 0.5%    |
| Raspberry Pi Foundation | 21        | 0.41%   |
| LG Electronics          | 21        | 0.41%   |
| Fujitsu                 | 21        | 0.41%   |
| Pegatron                | 20        | 0.39%   |
| eMachines               | 19        | 0.37%   |
| ECS                     | 17        | 0.33%   |
| BESSTAR Tech            | 17        | 0.33%   |
| Teclast                 | 15        | 0.29%   |
| AMI                     | 15        | 0.29%   |
| Fujitsu Siemens         | 13        | 0.25%   |
| Timi                    | 12        | 0.23%   |
| Foxconn                 | 12        | 0.23%   |
| Supermicro              | 11        | 0.21%   |
| AZW                     | 11        | 0.21%   |
| Huanan                  | 10        | 0.19%   |
| Microsoft               | 8         | 0.15%   |
| Dynabook                | 8         | 0.15%   |
| Clevo                   | 8         | 0.15%   |
| Shuttle                 | 7         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 94        | 1.82%   |
| ASUS All Series                            | 54        | 1.04%   |
| Valve Jupiter                              | 26        | 0.5%    |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.43%   |
| HP Pavilion g6                             | 22        | 0.43%   |
| HP Pavilion dv6                            | 20        | 0.39%   |
| HP Notebook                                | 20        | 0.39%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.35%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.29%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.29%   |
| Gigabyte B450M DS3H                        | 14        | 0.27%   |
| HP G62                                     | 12        | 0.23%   |
| MSI MS-7C37                                | 11        | 0.21%   |
| MSI MS-7817                                | 11        | 0.21%   |
| ASUS P5G41T-M LX                           | 11        | 0.21%   |
| RPi Raspberry Pi                           | 10        | 0.19%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 10        | 0.19%   |
| HUAWEI BOHK-WAX9X                          | 10        | 0.19%   |
| HP Pavilion 15                             | 10        | 0.19%   |
| HP Laptop 15-da0xxx                        | 10        | 0.19%   |
| Gigabyte 970A-DS3P                         | 10        | 0.19%   |
| Dell XPS 13 7390                           | 10        | 0.19%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.17%   |
| HP Compaq Elite 8300 SFF                   | 9         | 0.17%   |
| Gigabyte H61M-DS2                          | 9         | 0.17%   |
| Gigabyte H110M-S2H                         | 9         | 0.17%   |
| Chuwi GemiBook Pro                         | 9         | 0.17%   |
| ASUS PRIME A320M-K                         | 9         | 0.17%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.15%   |
| MSI MS-7C91                                | 8         | 0.15%   |
| MSI MS-7C02                                | 8         | 0.15%   |
| MSI MS-7B86                                | 8         | 0.15%   |
| MSI MS-7B79                                | 8         | 0.15%   |
| HP Laptop 15-bw0xx                         | 8         | 0.15%   |
| HP EliteDesk 800 G1 SFF                    | 8         | 0.15%   |
| Gigabyte H81M-S2H                          | 8         | 0.15%   |
| Gigabyte B450 AORUS M                      | 8         | 0.15%   |
| ASUS X555LAB                               | 8         | 0.15%   |
| ASUS X550VX                                | 8         | 0.15%   |
| ASUS X540NA                                | 8         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 243       | 4.7%    |
| Lenovo ThinkPad       | 200       | 3.87%   |
| HP Pavilion           | 150       | 2.9%    |
| Lenovo IdeaPad        | 141       | 2.73%   |
| HP Compaq             | 100       | 1.93%   |
| Dell Latitude         | 94        | 1.82%   |
| Unknown               | 94        | 1.82%   |
| ASUS PRIME            | 90        | 1.74%   |
| Toshiba Satellite     | 87        | 1.68%   |
| ASUS VivoBook         | 84        | 1.62%   |
| HP Laptop             | 75        | 1.45%   |
| ASUS ROG              | 72        | 1.39%   |
| ASUS TUF              | 69        | 1.33%   |
| HP EliteBook          | 66        | 1.28%   |
| Dell XPS              | 61        | 1.18%   |
| Lenovo ThinkCentre    | 59        | 1.14%   |
| ASUS All              | 54        | 1.04%   |
| Dell OptiPlex         | 53        | 1.03%   |
| Dell Inspiron         | 45        | 0.87%   |
| HP ProBook            | 42        | 0.81%   |
| ASUS ZenBook          | 39        | 0.75%   |
| Packard Bell EasyNote | 32        | 0.62%   |
| HP 250                | 32        | 0.62%   |
| MSI Prestige          | 29        | 0.56%   |
| Lenovo Yoga           | 28        | 0.54%   |
| MSI Modern            | 27        | 0.52%   |
| HP OMEN               | 27        | 0.52%   |
| Valve Jupiter         | 26        | 0.5%    |
| Lenovo Legion         | 26        | 0.5%    |
| Dell Precision        | 25        | 0.48%   |
| Acer TravelMate       | 24        | 0.46%   |
| Gigabyte B450M        | 23        | 0.44%   |
| RPi Raspberry         | 21        | 0.41%   |
| Gigabyte X570         | 21        | 0.41%   |
| Acer Extensa          | 21        | 0.41%   |
| HP Notebook           | 20        | 0.39%   |
| HP ENVY               | 20        | 0.39%   |
| ASUS ASUS             | 20        | 0.39%   |
| HP EliteDesk          | 19        | 0.37%   |
| Lenovo ThinkBook      | 18        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 524       | 10.14%  |
| 2019    | 483       | 9.34%   |
| 2020    | 437       | 8.45%   |
| 2014    | 354       | 6.85%   |
| 2021    | 352       | 6.81%   |
| 2013    | 318       | 6.15%   |
| 2012    | 316       | 6.11%   |
| 2017    | 314       | 6.07%   |
| 2015    | 297       | 5.74%   |
| 2011    | 295       | 5.71%   |
| 2010    | 264       | 5.11%   |
| 2009    | 249       | 4.82%   |
| 2016    | 240       | 4.64%   |
| 2008    | 236       | 4.56%   |
| 2007    | 170       | 3.29%   |
| 2022    | 160       | 3.09%   |
| 2006    | 86        | 1.66%   |
| Unknown | 32        | 0.62%   |
| 2005    | 22        | 0.43%   |
| 2023    | 7         | 0.14%   |
| 2004    | 7         | 0.14%   |
| 2003    | 3         | 0.06%   |
| 2002    | 2         | 0.04%   |
| 2001    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2866      | 55.44%  |
| Desktop        | 1944      | 37.6%   |
| All in one     | 94        | 1.82%   |
| Convertible    | 82        | 1.59%   |
| Mini pc        | 79        | 1.53%   |
| Tablet         | 44        | 0.85%   |
| System on chip | 29        | 0.56%   |
| Server         | 28        | 0.54%   |
| Phone          | 3         | 0.06%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4860      | 93.48%  |
| Enabled  | 339       | 6.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5162      | 99.85%  |
| Yes  | 8         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1165      | 22.14%  |
| 3.01-4.0        | 1071      | 20.36%  |
| 16.01-24.0      | 1070      | 20.34%  |
| 8.01-16.0       | 968       | 18.4%   |
| 32.01-64.0      | 461       | 8.76%   |
| 1.01-2.0        | 233       | 4.43%   |
| 2.01-3.0        | 85        | 1.62%   |
| 64.01-256.0     | 78        | 1.48%   |
| 24.01-32.0      | 61        | 1.16%   |
| 0.51-1.0        | 60        | 1.14%   |
| More than 256.0 | 6         | 0.11%   |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2190      | 38.11%  |
| 2.01-3.0   | 1440      | 25.06%  |
| 4.01-8.0   | 741       | 12.9%   |
| 3.01-4.0   | 655       | 11.4%   |
| 0.51-1.0   | 440       | 7.66%   |
| 8.01-16.0  | 189       | 3.29%   |
| 0.01-0.5   | 64        | 1.11%   |
| 16.01-24.0 | 14        | 0.24%   |
| 24.01-32.0 | 10        | 0.17%   |
| 32.01-64.0 | 2         | 0.03%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3182      | 59.43%  |
| 2       | 1349      | 25.2%   |
| 3       | 429       | 8.01%   |
| 4       | 190       | 3.55%   |
| 5       | 76        | 1.42%   |
| 0       | 44        | 0.82%   |
| 6       | 40        | 0.75%   |
| 7       | 16        | 0.3%    |
| 9       | 8         | 0.15%   |
| 8       | 8         | 0.15%   |
| 10      | 4         | 0.07%   |
| 12      | 2         | 0.04%   |
| 11      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 13      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3155      | 60.41%  |
| Yes       | 2068      | 39.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4465      | 86.05%  |
| No        | 724       | 13.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3915      | 75.14%  |
| No        | 1295      | 24.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2992      | 57.18%  |
| No        | 2241      | 42.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 5170      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 858       | 15.19%  |
| Barcelona                  | 578       | 10.23%  |
| Valencia                   | 199       | 3.52%   |
| Seville                    | 192       | 3.4%    |
| Zaragoza                   | 86        | 1.52%   |
| Málaga                    | 84        | 1.49%   |
| Granada                    | 77        | 1.36%   |
| Valladolid                 | 57        | 1.01%   |
| Palma                      | 55        | 0.97%   |
| Bilbao                     | 55        | 0.97%   |
| Alcobendas                 | 55        | 0.97%   |
| Vigo                       | 53        | 0.94%   |
| Sabadell                   | 53        | 0.94%   |
| Córdoba                   | 51        | 0.9%    |
| Las Palmas de Gran Canaria | 49        | 0.87%   |
| Ourense                    | 40        | 0.71%   |
| Murcia                     | 39        | 0.69%   |
| Pamplona                   | 38        | 0.67%   |
| Donostia / San Sebastian   | 36        | 0.64%   |
| Oviedo                     | 35        | 0.62%   |
| Alicante                   | 35        | 0.62%   |
| A Coruña                  | 35        | 0.62%   |
| Alcalá de Henares         | 33        | 0.58%   |
| Santiago de Compostela     | 31        | 0.55%   |
| Santa Cruz de Tenerife     | 31        | 0.55%   |
| Gijón                     | 30        | 0.53%   |
| Almería                   | 29        | 0.51%   |
| León                      | 27        | 0.48%   |
| Burgos                     | 27        | 0.48%   |
| Salamanca                  | 25        | 0.44%   |
| Mostoles                   | 25        | 0.44%   |
| Barakaldo                  | 24        | 0.42%   |
| Vitoria-Gasteiz            | 23        | 0.41%   |
| Badalona                   | 23        | 0.41%   |
| Terrassa                   | 22        | 0.39%   |
| Santander                  | 22        | 0.39%   |
| Albacete                   | 22        | 0.39%   |
| Girona                     | 21        | 0.37%   |
| Getxo                      | 20        | 0.35%   |
| Reus                       | 19        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1282      | 1977   | 16.88%  |
| WDC                         | 1044      | 1539   | 13.75%  |
| Samsung Electronics         | 995       | 1447   | 13.1%   |
| Kingston                    | 855       | 1173   | 11.26%  |
| Toshiba                     | 539       | 826    | 7.1%    |
| SanDisk                     | 417       | 561    | 5.49%   |
| Crucial                     | 290       | 410    | 3.82%   |
| Unknown                     | 289       | 370    | 3.81%   |
| Hitachi                     | 232       | 275    | 3.06%   |
| SK hynix                    | 178       | 227    | 2.34%   |
| Intel                       | 163       | 214    | 2.15%   |
| HGST                        | 129       | 161    | 1.7%    |
| Micron Technology           | 125       | 156    | 1.65%   |
| China                       | 76        | 103    | 1%      |
| Phison                      | 55        | 61     | 0.72%   |
| Apple                       | 45        | 59     | 0.59%   |
| Micron/Crucial Technology   | 44        | 58     | 0.58%   |
| KIOXIA                      | 44        | 55     | 0.58%   |
| Fujitsu                     | 44        | 50     | 0.58%   |
| Maxtor                      | 40        | 55     | 0.53%   |
| Silicon Motion              | 33        | 39     | 0.43%   |
| OCZ                         | 33        | 45     | 0.43%   |
| Phison Electronics          | 32        | 38     | 0.42%   |
| Kingston Technology Company | 26        | 33     | 0.34%   |
| JMicron Technology          | 26        | 28     | 0.34%   |
| Transcend                   | 24        | 48     | 0.32%   |
| Netac                       | 24        | 37     | 0.32%   |
| A-DATA Technology           | 24        | 33     | 0.32%   |
| KIOXIA-EXCERIA              | 23        | 31     | 0.3%    |
| Unknown                     | 22        | 24     | 0.29%   |
| KingSpec                    | 21        | 28     | 0.28%   |
| Corsair                     | 20        | 25     | 0.26%   |
| LITEON                      | 19        | 20     | 0.25%   |
| PNY                         | 17        | 27     | 0.22%   |
| KingDian                    | 17        | 21     | 0.22%   |
| USB30                       | 16        | 34     | 0.21%   |
| Emtec                       | 16        | 20     | 0.21%   |
| Intenso                     | 14        | 21     | 0.18%   |
| Patriot                     | 13        | 20     | 0.17%   |
| Teclast                     | 11        | 12     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 276       | 3.31%   |
| Kingston SA400S37480G 480GB SSD                     | 126       | 1.51%   |
| Seagate ST1000DM010-2EP102 1TB                      | 99        | 1.19%   |
| Kingston SA400S37120G 120GB SSD                     | 88        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB                     | 86        | 1.03%   |
| Kingston SV300S37A120G 120GB SSD                    | 75        | 0.9%    |
| Seagate ST3500418AS 500GB                           | 64        | 0.77%   |
| Samsung SSD 860 EVO 500GB                           | 60        | 0.72%   |
| Unknown MMC Card  64GB                              | 55        | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB                      | 52        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 52        | 0.62%   |
| Unknown MMC Card  32GB                              | 50        | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB                      | 50        | 0.6%    |
| Samsung SSD 850 EVO 250GB                           | 50        | 0.6%    |
| Samsung SSD 850 EVO 500GB                           | 47        | 0.56%   |
| Seagate ST500LT012-1DG142 500GB                     | 46        | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB                      | 46        | 0.55%   |
| Toshiba DT01ACA100 1TB                              | 45        | 0.54%   |
| Toshiba MQ01ABD100 1TB                              | 44        | 0.53%   |
| Kingston SUV400S37240G 240GB SSD                    | 44        | 0.53%   |
| Seagate ST9500325AS 500GB                           | 43        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 41        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 0.48%   |
| SanDisk SSD PLUS 480GB                              | 40        | 0.48%   |
| HGST HTS721010A9E630 1TB                            | 39        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 37        | 0.44%   |
| Samsung NVMe SSD Drive 512GB                        | 36        | 0.43%   |
| Samsung NVMe SSD Drive 500GB                        | 36        | 0.43%   |
| Toshiba MQ01ABF050 500GB                            | 35        | 0.42%   |
| Seagate ST31000528AS 1TB                            | 35        | 0.42%   |
| SK hynix NVMe SSD Drive 512GB                       | 34        | 0.41%   |
| Kingston SV300S37A240G 240GB SSD                    | 34        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                        | 32        | 0.38%   |
| Unknown SD/MMC/MS PRO 250GB                         | 31        | 0.37%   |
| Unknown MMC Card  128GB                             | 31        | 0.37%   |
| Toshiba TR200 240GB SSD                             | 31        | 0.37%   |
| Toshiba MQ01ABD050 500GB                            | 31        | 0.37%   |
| Crucial CT480BX500SSD1 480GB                        | 31        | 0.37%   |
| WDC WD20EARX-00PASB0 2TB                            | 30        | 0.36%   |
| Seagate Expansion 1TB                               | 30        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1271      | 1961   | 40.74%  |
| WDC                 | 814       | 1189   | 26.09%  |
| Toshiba             | 384       | 556    | 12.31%  |
| Hitachi             | 232       | 275    | 7.44%   |
| HGST                | 129       | 161    | 4.13%   |
| Samsung Electronics | 127       | 157    | 4.07%   |
| Fujitsu             | 43        | 49     | 1.38%   |
| Maxtor              | 35        | 48     | 1.12%   |
| Unknown             | 31        | 37     | 0.99%   |
| Apple               | 19        | 23     | 0.61%   |
| USB3.0              | 6         | 6      | 0.19%   |
| ASMT                | 5         | 9      | 0.16%   |
| Hewlett-Packard     | 3         | 4      | 0.1%    |
| SSK                 | 2         | 2      | 0.06%   |
| Intenso             | 2         | 3      | 0.06%   |
| Inateck             | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| OEM                 | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| JMicron Technology  | 1         | 1      | 0.03%   |
| IBM-207x            | 1         | 8      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| HPE                 | 1         | 2      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 776       | 1065   | 30.19%  |
| Samsung Electronics | 448       | 628    | 17.43%  |
| Crucial             | 261       | 368    | 10.16%  |
| SanDisk             | 237       | 300    | 9.22%   |
| WDC                 | 132       | 191    | 5.14%   |
| Toshiba             | 101       | 185    | 3.93%   |
| China               | 74        | 101    | 2.88%   |
| SK hynix            | 42        | 46     | 1.63%   |
| Intel               | 38        | 55     | 1.48%   |
| Micron Technology   | 34        | 44     | 1.32%   |
| OCZ                 | 33        | 45     | 1.28%   |
| Netac               | 24        | 37     | 0.93%   |
| Transcend           | 23        | 47     | 0.89%   |
| KingSpec            | 21        | 28     | 0.82%   |
| A-DATA Technology   | 21        | 30     | 0.82%   |
| LITEON              | 18        | 18     | 0.7%    |
| Apple               | 18        | 21     | 0.7%    |
| USB30               | 16        | 34     | 0.62%   |
| KIOXIA-EXCERIA      | 16        | 20     | 0.62%   |
| KingDian            | 16        | 20     | 0.62%   |
| Emtec               | 14        | 17     | 0.54%   |
| Patriot             | 12        | 19     | 0.47%   |
| Intenso             | 12        | 16     | 0.47%   |
| Teclast             | 11        | 12     | 0.43%   |
| PNY                 | 11        | 21     | 0.43%   |
| FORESEE             | 10        | 14     | 0.39%   |
| Unknown             | 10        | 10     | 0.39%   |
| Corsair             | 8         | 11     | 0.31%   |
| BAITITON            | 8         | 10     | 0.31%   |
| Drevo               | 7         | 9      | 0.27%   |
| LITEONIT            | 6         | 7      | 0.23%   |
| GOODRAM             | 6         | 8      | 0.23%   |
| Maxtor              | 5         | 7      | 0.19%   |
| Dogfish             | 5         | 6      | 0.19%   |
| TCSUNBOW            | 4         | 4      | 0.16%   |
| SPCC                | 4         | 4      | 0.16%   |
| Hoodisk             | 4         | 5      | 0.16%   |
| Unknown             | 3         | 3      | 0.12%   |
| Plextor             | 3         | 4      | 0.12%   |
| KingFast            | 3         | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2656      | 4505   | 39.33%  |
| SSD     | 2211      | 3566   | 32.74%  |
| NVMe    | 1537      | 2176   | 22.76%  |
| MMC     | 265       | 348    | 3.92%   |
| Unknown | 84        | 102    | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3881      | 7866   | 65.56%  |
| NVMe | 1521      | 2149   | 25.69%  |
| MMC  | 265       | 348    | 4.48%   |
| SAS  | 253       | 334    | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3099      | 5111   | 61.77%  |
| 0.51-1.0        | 1343      | 1990   | 26.77%  |
| 1.01-2.0        | 359       | 587    | 7.16%   |
| 3.01-4.0        | 85        | 142    | 1.69%   |
| 2.01-3.0        | 82        | 130    | 1.63%   |
| 4.01-10.0       | 47        | 108    | 0.94%   |
| More than 100.0 | 1         | 2      | 0.02%   |
| 10.01-20.0      | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1519      | 27.54%  |
| 251-500        | 1285      | 23.3%   |
| 501-1000       | 749       | 13.58%  |
| 1-20           | 428       | 7.76%   |
| 1001-2000      | 378       | 6.85%   |
| 51-100         | 374       | 6.78%   |
| 21-50          | 232       | 4.21%   |
| More than 3000 | 223       | 4.04%   |
| 2001-3000      | 189       | 3.43%   |
| Unknown        | 138       | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2214      | 38.73%  |
| 21-50          | 970       | 16.97%  |
| 101-250        | 733       | 12.82%  |
| 51-100         | 612       | 10.7%   |
| 251-500        | 431       | 7.54%   |
| 501-1000       | 299       | 5.23%   |
| 1001-2000      | 172       | 3.01%   |
| Unknown        | 138       | 2.41%   |
| More than 3000 | 86        | 1.5%    |
| 2001-3000      | 60        | 1.05%   |
| 0              | 2         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 15        | 15     | 2.96%   |
| Seagate ST3500418AS 500GB           | 14        | 20     | 2.77%   |
| Kingston SV300S37A120G 120GB SSD    | 14        | 20     | 2.77%   |
| Seagate ST9500325AS 500GB           | 10        | 12     | 1.98%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 1.38%   |
| SanDisk SSD PLUS 480GB              | 7         | 9      | 1.38%   |
| Seagate ST3500320AS 500GB           | 6         | 9      | 1.19%   |
| Seagate ST31000528AS 1TB            | 6         | 7      | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB      | 6         | 7      | 1.19%   |
| Seagate ST1000DM003-1CH162 1TB      | 6         | 7      | 1.19%   |
| HGST HTS545050A7E680 500GB          | 5         | 7      | 0.99%   |
| WDC WD5000AAKX-001CA0 500GB         | 4         | 6      | 0.79%   |
| WDC WD20EARX-00PASB0 2TB            | 4         | 6      | 0.79%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 0.79%   |
| Seagate ST9250827AS 250GB           | 4         | 4      | 0.79%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 0.79%   |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 0.79%   |
| Seagate ST1000DM003-1ER162 1TB      | 4         | 7      | 0.79%   |
| Kingston SUV400S37240G 240GB SSD    | 4         | 6      | 0.79%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 7      | 0.79%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.79%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.79%   |
| Drevo X1 SSD 120GB                  | 4         | 6      | 0.79%   |
| China G521N256GB SSD                | 4         | 5      | 0.79%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 3         | 3      | 0.59%   |
| WDC WD20PURZ-85GU6Y0 2TB            | 3         | 4      | 0.59%   |
| WDC WD20EZRX-00DC0B0 2TB            | 3         | 3      | 0.59%   |
| Toshiba DT01ACA100 1TB              | 3         | 5      | 0.59%   |
| Seagate ST3250310AS 250GB           | 3         | 3      | 0.59%   |
| Seagate ST3200822A 200GB            | 3         | 3      | 0.59%   |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 4      | 0.59%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 4      | 0.59%   |
| Samsung Electronics HD501LJ 500GB   | 3         | 3      | 0.59%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.59%   |
| Fujitsu MHZ2250BH G2 250GB          | 3         | 4      | 0.59%   |
| WDC WD6400AAKS-22A7B0 640GB         | 2         | 2      | 0.4%    |
| WDC WD5000BPVT-60HXZT3 500GB        | 2         | 2      | 0.4%    |
| WDC WD5000AAKS-402AA0 500GB         | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 167       | 210    | 33.87%  |
| WDC                 | 90        | 110    | 18.26%  |
| Toshiba             | 34        | 39     | 6.9%    |
| Hitachi             | 34        | 37     | 6.9%    |
| Samsung Electronics | 32        | 35     | 6.49%   |
| Kingston            | 29        | 41     | 5.88%   |
| HGST                | 18        | 21     | 3.65%   |
| SanDisk             | 13        | 15     | 2.64%   |
| Crucial             | 11        | 13     | 2.23%   |
| Intel               | 10        | 12     | 2.03%   |
| Maxtor              | 9         | 11     | 1.83%   |
| China               | 9         | 11     | 1.83%   |
| Fujitsu             | 7         | 8      | 1.42%   |
| Drevo               | 5         | 7      | 1.01%   |
| SK hynix            | 3         | 3      | 0.61%   |
| OCZ                 | 3         | 3      | 0.61%   |
| Micron Technology   | 3         | 4      | 0.61%   |
| KingDian            | 2         | 2      | 0.41%   |
| Transcend           | 1         | 7      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| Intenso             | 1         | 1      | 0.2%    |
| IBM                 | 1         | 1      | 0.2%    |
| Hypertec            | 1         | 1      | 0.2%    |
| HPE                 | 1         | 2      | 0.2%    |
| Dogfish             | 1         | 1      | 0.2%    |
| Corsair             | 1         | 1      | 0.2%    |
| ASMT                | 1         | 2      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |
| A-DATA Technology   | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 167       | 210    | 44.41%  |
| WDC                 | 88        | 108    | 23.4%   |
| Hitachi             | 34        | 37     | 9.04%   |
| Toshiba             | 29        | 34     | 7.71%   |
| Samsung Electronics | 19        | 21     | 5.05%   |
| HGST                | 18        | 21     | 4.79%   |
| Maxtor              | 9         | 11     | 2.39%   |
| Fujitsu             | 7         | 8      | 1.86%   |
| IBM                 | 1         | 1      | 0.27%   |
| HPE                 | 1         | 2      | 0.27%   |
| China               | 1         | 1      | 0.27%   |
| ASMT                | 1         | 2      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 350       | 457    | 75.92%  |
| SSD  | 101       | 136    | 21.91%  |
| NVMe | 10        | 11     | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2         | 2      | 14.29%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 7.14%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 7.14%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 7.14%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.14%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 7.14%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.14%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 7.14%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 7.14%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 50%     |
| Samsung Electronics | 3         | 4      | 21.43%  |
| Toshiba             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3251      | 6528   | 57.59%  |
| Works    | 1938      | 3550   | 34.33%  |
| Malfunc  | 442       | 604    | 7.83%   |
| Failed   | 14        | 15     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3495      | 55.07%  |
| AMD                              | 891       | 14.04%  |
| Samsung Electronics              | 493       | 7.77%   |
| SanDisk                          | 295       | 4.65%   |
| SK hynix                         | 127       | 2%      |
| Kingston Technology Company      | 115       | 1.81%   |
| Phison Electronics               | 107       | 1.69%   |
| Nvidia                           | 107       | 1.69%   |
| Micron Technology                | 93        | 1.47%   |
| JMicron Technology               | 88        | 1.39%   |
| ASMedia Technology               | 85        | 1.34%   |
| Micron/Crucial Technology        | 71        | 1.12%   |
| Marvell Technology Group         | 67        | 1.06%   |
| Toshiba America Info Systems     | 61        | 0.96%   |
| KIOXIA                           | 57        | 0.9%    |
| Silicon Motion                   | 42        | 0.66%   |
| VIA Technologies                 | 34        | 0.54%   |
| Silicon Integrated Systems [SiS] | 22        | 0.35%   |
| LSI Logic / Symbios Logic        | 14        | 0.22%   |
| Union Memory (Shenzhen)          | 11        | 0.17%   |
| Apple                            | 7         | 0.11%   |
| Hewlett-Packard                  | 6         | 0.09%   |
| Silicon Image                    | 5         | 0.08%   |
| Realtek Semiconductor            | 5         | 0.08%   |
| O2 Micro                         | 5         | 0.08%   |
| Solid State Storage Technology   | 4         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.06%   |
| Broadcom / LSI                   | 4         | 0.06%   |
| ADATA Technology                 | 4         | 0.06%   |
| Shenzhen Longsys Electronics     | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Adaptec                          | 3         | 0.05%   |
| 3ware                            | 3         | 0.05%   |
| Seagate Technology               | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| Swissbit                         | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 628       | 8.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 271       | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 263       | 3.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 253       | 3.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 157       | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 150       | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 135       | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 134       | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 132       | 1.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 124       | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 122       | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 121       | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 112       | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 104       | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 103       | 1.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 100       | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 97        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 95        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                | 94        | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 92        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 91        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 91        | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 83        | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 82        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 81        | 1.09%   |
| Intel SATA Controller [RAID mode]                                              | 79        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 76        | 1.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 74        | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 73        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 71        | 0.96%   |
| Intel SSD 660P Series                                                          | 68        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 66        | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 66        | 0.89%   |
| Micron NVMe Storage Controller                                                 | 61        | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 60        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 56        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 55        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 55        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 53        | 0.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 53        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3680      | 56.83%  |
| NVMe | 1535      | 23.71%  |
| IDE  | 846       | 13.07%  |
| RAID | 394       | 6.08%   |
| SAS  | 11        | 0.17%   |
| SCSI | 9         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3994      | 77.25%  |
| AMD          | 1142      | 22.09%  |
| ARM          | 31        | 0.6%    |
| QUALCOMM     | 2         | 0.04%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 63        | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 56        | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 55        | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 47        | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 43        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 43        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 39        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 38        | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 37        | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 36        | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 35        | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 33        | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 32        | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 32        | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 31        | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.58%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 29        | 0.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 28        | 0.54%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 27        | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.52%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.5%    |
| AMD Custom APU 0405                           | 26        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 25        | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 24        | 0.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 23        | 0.44%   |
| ARM Processor                                 | 23        | 0.44%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 22        | 0.42%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 21        | 0.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.39%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 20        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 978       | 18.88%  |
| Intel Core i7           | 962       | 18.57%  |
| Intel Core i3           | 413       | 7.97%   |
| Other                   | 368       | 7.1%    |
| Intel Celeron           | 325       | 6.27%   |
| AMD Ryzen 5             | 283       | 5.46%   |
| Intel Core 2 Duo        | 256       | 4.94%   |
| AMD Ryzen 7             | 248       | 4.79%   |
| Intel Atom              | 147       | 2.84%   |
| Intel Xeon              | 113       | 2.18%   |
| Intel Pentium           | 96        | 1.85%   |
| Intel Pentium Dual-Core | 86        | 1.66%   |
| Intel Core 2 Quad       | 75        | 1.45%   |
| AMD FX                  | 60        | 1.16%   |
| Intel Core 2            | 54        | 1.04%   |
| Intel Pentium Dual      | 53        | 1.02%   |
| AMD Ryzen 9             | 53        | 1.02%   |
| AMD A4                  | 49        | 0.95%   |
| AMD Ryzen 3             | 44        | 0.85%   |
| AMD A6                  | 37        | 0.71%   |
| AMD A10                 | 35        | 0.68%   |
| Intel Genuine           | 34        | 0.66%   |
| AMD A8                  | 33        | 0.64%   |
| Intel Core i9           | 30        | 0.58%   |
| Intel Pentium 4         | 25        | 0.48%   |
| AMD Athlon 64 X2        | 24        | 0.46%   |
| AMD E1                  | 22        | 0.42%   |
| AMD Athlon II X2        | 22        | 0.42%   |
| AMD Athlon              | 20        | 0.39%   |
| AMD Phenom II X4        | 15        | 0.29%   |
| AMD E                   | 15        | 0.29%   |
| AMD Ryzen 7 PRO         | 13        | 0.25%   |
| AMD Phenom              | 11        | 0.21%   |
| Intel Pentium D         | 10        | 0.19%   |
| Intel Pentium Silver    | 9         | 0.17%   |
| Intel Pentium M         | 9         | 0.17%   |
| Intel Pentium Gold      | 8         | 0.15%   |
| Intel Celeron M         | 8         | 0.15%   |
| AMD Sempron             | 8         | 0.15%   |
| AMD Ryzen Threadripper  | 8         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2105      | 40.58%  |
| 4       | 1821      | 35.11%  |
| 6       | 499       | 9.62%   |
| 8       | 376       | 7.25%   |
| 1       | 188       | 3.62%   |
| 12      | 65        | 1.25%   |
| 14      | 31        | 0.6%    |
| 10      | 29        | 0.56%   |
| 16      | 25        | 0.48%   |
| 3       | 22        | 0.42%   |
| Unknown | 14        | 0.27%   |
| 20      | 3         | 0.06%   |
| 64      | 2         | 0.04%   |
| 32      | 2         | 0.04%   |
| 24      | 2         | 0.04%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5126      | 99.13%  |
| 2       | 41        | 0.79%   |
| Unknown | 4         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3254      | 62.76%  |
| 1       | 1916      | 36.95%  |
| Unknown | 14        | 0.27%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4986      | 95.88%  |
| Unknown        | 114       | 2.19%   |
| 32-bit         | 66        | 1.27%   |
| 64-bit         | 34        | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1166      | 21.69%  |
| 0x306c3    | 262       | 4.87%   |
| 0x206a7    | 241       | 4.48%   |
| 0x306a9    | 224       | 4.17%   |
| 0x1067a    | 186       | 3.46%   |
| 0x906ea    | 148       | 2.75%   |
| 0x806ea    | 125       | 2.33%   |
| 0x806c1    | 118       | 2.2%    |
| 0x506e3    | 115       | 2.14%   |
| 0x6fd      | 108       | 2.01%   |
| 0x806ec    | 104       | 1.93%   |
| 0x40651    | 104       | 1.93%   |
| 0x20655    | 98        | 1.82%   |
| 0x806e9    | 97        | 1.8%    |
| 0x406e3    | 93        | 1.73%   |
| 0x306d4    | 79        | 1.47%   |
| 0x08108109 | 78        | 1.45%   |
| 0x906e9    | 77        | 1.43%   |
| 0x30678    | 60        | 1.12%   |
| 0x10676    | 58        | 1.08%   |
| 0x08701021 | 54        | 1%      |
| 0x6fb      | 53        | 0.99%   |
| 0x0a50000c | 53        | 0.99%   |
| 0x20652    | 52        | 0.97%   |
| 0x706a1    | 47        | 0.87%   |
| 0x0800820d | 45        | 0.84%   |
| 0x506c9    | 44        | 0.82%   |
| 0x406c4    | 44        | 0.82%   |
| 0xa0652    | 42        | 0.78%   |
| 0x706e5    | 42        | 0.78%   |
| 0x06006705 | 41        | 0.76%   |
| 0x08600106 | 38        | 0.71%   |
| 0x706a8    | 37        | 0.69%   |
| 0x6f6      | 37        | 0.69%   |
| 0x106ca    | 35        | 0.65%   |
| 0x08108102 | 35        | 0.65%   |
| 0x906ed    | 33        | 0.61%   |
| 0x06000852 | 33        | 0.61%   |
| 0x010000c8 | 33        | 0.61%   |
| 0x806eb    | 32        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 798       | 15.4%   |
| Haswell          | 497       | 9.59%   |
| Penryn           | 316       | 6.1%    |
| SandyBridge      | 308       | 5.94%   |
| IvyBridge        | 273       | 5.27%   |
| Core             | 270       | 5.21%   |
| Skylake          | 258       | 4.98%   |
| Zen+             | 204       | 3.94%   |
| Zen 2            | 197       | 3.8%    |
| Westmere         | 183       | 3.53%   |
| Silvermont       | 173       | 3.34%   |
| TigerLake        | 164       | 3.16%   |
| Unknown          | 160       | 3.09%   |
| Zen 3            | 131       | 2.53%   |
| CometLake        | 118       | 2.28%   |
| Broadwell        | 112       | 2.16%   |
| Goldmont plus    | 105       | 2.03%   |
| K10              | 93        | 1.79%   |
| Zen              | 90        | 1.74%   |
| Piledriver       | 90        | 1.74%   |
| Icelake          | 79        | 1.52%   |
| Bonnell          | 74        | 1.43%   |
| Excavator        | 70        | 1.35%   |
| K8 Hammer        | 53        | 1.02%   |
| Alderlake Hybrid | 52        | 1%      |
| Goldmont         | 51        | 0.98%   |
| Nehalem          | 48        | 0.93%   |
| NetBurst         | 38        | 0.73%   |
| Puma             | 33        | 0.64%   |
| P6               | 30        | 0.58%   |
| Jaguar           | 27        | 0.52%   |
| Steamroller      | 26        | 0.5%    |
| Bobcat           | 24        | 0.46%   |
| Tremont          | 14        | 0.27%   |
| K10 Llano        | 11        | 0.21%   |
| Bulldozer        | 8         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.06%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2967      | 48.51%  |
| Nvidia                                       | 1782      | 29.14%  |
| AMD                                          | 1307      | 21.37%  |
| Matrox Electronics Systems                   | 22        | 0.36%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.23%   |
| VIA Technologies                             | 11        | 0.18%   |
| ASPEED Technology                            | 10        | 0.16%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 209       | 3.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 158       | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 141       | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 136       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 131       | 2.07%   |
| Intel UHD Graphics 620                                                                   | 127       | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 121       | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 108       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 107       | 1.69%   |
| Intel HD Graphics 620                                                                    | 102       | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 98        | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 97        | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 96        | 1.52%   |
| AMD Renoir                                                                               | 93        | 1.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 91        | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 90        | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 83        | 1.31%   |
| Intel HD Graphics 530                                                                    | 82        | 1.3%    |
| Intel HD Graphics 5500                                                                   | 79        | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 76        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 72        | 1.14%   |
| Intel HD Graphics 630                                                                    | 72        | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 70        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 67        | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 64        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 63        | 1%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 56        | 0.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 52        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 51        | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 0.79%   |
| Intel HD Graphics 500                                                                    | 49        | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 45        | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 41        | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 40        | 0.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 40        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2116      | 40.59%  |
| 1 x AMD                | 1027      | 19.7%   |
| 1 x Nvidia             | 989       | 18.97%  |
| Intel + Nvidia         | 676       | 12.97%  |
| Intel + AMD            | 104       | 2%      |
| AMD + Nvidia           | 102       | 1.96%   |
| 2 x AMD                | 75        | 1.44%   |
| Other                  | 37        | 0.71%   |
| 1 x Matrox             | 19        | 0.36%   |
| 2 x Nvidia             | 15        | 0.29%   |
| 1 x SiS                | 14        | 0.27%   |
| 1 x VIA                | 11        | 0.21%   |
| 2 x Intel              | 10        | 0.19%   |
| 1 x ASPEED             | 6         | 0.12%   |
| Nvidia + ASPEED        | 4         | 0.08%   |
| Nvidia + Matrox        | 3         | 0.06%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4161      | 79.2%   |
| Proprietary | 872       | 16.6%   |
| Unknown     | 221       | 4.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2861      | 53.64%  |
| 1.01-2.0   | 703       | 13.18%  |
| 0.01-0.5   | 633       | 11.87%  |
| 3.01-4.0   | 393       | 7.37%   |
| 0.51-1.0   | 378       | 7.09%   |
| 7.01-8.0   | 199       | 3.73%   |
| 5.01-6.0   | 97        | 1.82%   |
| 8.01-16.0  | 32        | 0.6%    |
| 2.01-3.0   | 30        | 0.56%   |
| 16.01-24.0 | 8         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 651       | 11.74%  |
| AU Optronics            | 571       | 10.3%   |
| Chimei Innolux          | 528       | 9.52%   |
| LG Display              | 454       | 8.19%   |
| BOE                     | 403       | 7.27%   |
| Goldstar                | 383       | 6.91%   |
| Hewlett-Packard         | 277       | 4.99%   |
| Dell                    | 227       | 4.09%   |
| BenQ                    | 220       | 3.97%   |
| Acer                    | 191       | 3.44%   |
| Ancor Communications    | 159       | 2.87%   |
| Philips                 | 151       | 2.72%   |
| AOC                     | 121       | 2.18%   |
| Apple                   | 112       | 2.02%   |
| Chi Mei Optoelectronics | 99        | 1.79%   |
| Sharp                   | 95        | 1.71%   |
| Lenovo                  | 85        | 1.53%   |
| PANDA                   | 66        | 1.19%   |
| LG Electronics          | 56        | 1.01%   |
| Sony                    | 54        | 0.97%   |
| Unknown                 | 47        | 0.85%   |
| LG Philips              | 44        | 0.79%   |
| HannStar                | 43        | 0.78%   |
| ASUSTek Computer        | 40        | 0.72%   |
| ViewSonic               | 30        | 0.54%   |
| InfoVision              | 24        | 0.43%   |
| MSI                     | 22        | 0.4%    |
| Valve                   | 17        | 0.31%   |
| CPT                     | 14        | 0.25%   |
| Eizo                    | 13        | 0.23%   |
| Toshiba                 | 11        | 0.2%    |
| OEM                     | 11        | 0.2%    |
| CSO                     | 11        | 0.2%    |
| Vestel Elektronik       | 10        | 0.18%   |
| Panasonic               | 10        | 0.18%   |
| NEC Computers           | 10        | 0.18%   |
| Fujitsu Siemens         | 10        | 0.18%   |
| ___                     | 9         | 0.16%   |
| Packard Bell            | 9         | 0.16%   |
| Mi                      | 9         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 1.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 38        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 31        | 0.54%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 31        | 0.54%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 31        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 25        | 0.44%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 21        | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 18        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 17        | 0.3%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 17        | 0.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                  | 16        | 0.28%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.28%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 15        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 14        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 14        | 0.24%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 14        | 0.24%   |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch         | 14        | 0.24%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.21%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 12        | 0.21%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 12        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2285      | 43.26%  |
| 1366x768 (WXGA)    | 1081      | 20.47%  |
| 3840x2160 (4K)     | 246       | 4.66%   |
| 1280x1024 (SXGA)   | 224       | 4.24%   |
| 2560x1440 (QHD)    | 205       | 3.88%   |
| 1280x800 (WXGA)    | 171       | 3.24%   |
| 1680x1050 (WSXGA+) | 156       | 2.95%   |
| 1440x900 (WXGA+)   | 149       | 2.82%   |
| 1600x900 (HD+)     | 121       | 2.29%   |
| 1920x1200 (WUXGA)  | 93        | 1.76%   |
| Unknown            | 63        | 1.19%   |
| 2560x1080          | 61        | 1.15%   |
| 1360x768           | 48        | 0.91%   |
| 1024x600           | 43        | 0.81%   |
| 3440x1440          | 37        | 0.7%    |
| 2560x1600          | 31        | 0.59%   |
| 2160x1440          | 29        | 0.55%   |
| 1024x768 (XGA)     | 27        | 0.51%   |
| 800x1280           | 23        | 0.44%   |
| 3840x1080          | 20        | 0.38%   |
| 2880x1800          | 16        | 0.3%    |
| 1600x1200          | 14        | 0.27%   |
| 1920x540           | 13        | 0.25%   |
| 3200x1800 (QHD+)   | 8         | 0.15%   |
| 2288x1287          | 7         | 0.13%   |
| 3840x2400          | 6         | 0.11%   |
| 3200x1080          | 6         | 0.11%   |
| 3840x1600          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 4480x1080          | 4         | 0.08%   |
| 2736x1824          | 4         | 0.08%   |
| 1280x768           | 4         | 0.08%   |
| 3840x1200          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3360x1080          | 3         | 0.06%   |
| 2960x1050          | 3         | 0.06%   |
| 2944x1080          | 3         | 0.06%   |
| 2520x1680          | 3         | 0.06%   |
| 2256x1504          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1593      | 28.76%  |
| 13      | 419       | 7.57%   |
| 24      | 400       | 7.22%   |
| 21      | 391       | 7.06%   |
| 27      | 358       | 6.46%   |
| 23      | 315       | 5.69%   |
| Unknown | 302       | 5.45%   |
| 14      | 290       | 5.24%   |
| 17      | 285       | 5.15%   |
| 19      | 172       | 3.11%   |
| 18      | 130       | 2.35%   |
| 22      | 89        | 1.61%   |
| 34      | 85        | 1.53%   |
| 31      | 82        | 1.48%   |
| 20      | 82        | 1.48%   |
| 12      | 72        | 1.3%    |
| 11      | 56        | 1.01%   |
| 10      | 54        | 0.98%   |
| 16      | 48        | 0.87%   |
| 84      | 45        | 0.81%   |
| 25      | 27        | 0.49%   |
| 54      | 26        | 0.47%   |
| 32      | 26        | 0.47%   |
| 72      | 24        | 0.43%   |
| 26      | 24        | 0.43%   |
| 40      | 20        | 0.36%   |
| 7       | 17        | 0.31%   |
| 65      | 10        | 0.18%   |
| 48      | 8         | 0.14%   |
| 46      | 8         | 0.14%   |
| 28      | 8         | 0.14%   |
| 3       | 8         | 0.14%   |
| 52      | 7         | 0.13%   |
| 142     | 6         | 0.11%   |
| 33      | 6         | 0.11%   |
| 60      | 4         | 0.07%   |
| 37      | 4         | 0.07%   |
| 36      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |
| 8       | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2163      | 39.78%  |
| 501-600        | 1003      | 18.45%  |
| 401-500        | 775       | 14.25%  |
| 201-300        | 431       | 7.93%   |
| 351-400        | 302       | 5.55%   |
| Unknown        | 302       | 5.55%   |
| 601-700        | 131       | 2.41%   |
| 701-800        | 116       | 2.13%   |
| 1501-2000      | 71        | 1.31%   |
| 1001-1500      | 70        | 1.29%   |
| 801-900        | 32        | 0.59%   |
| 1-100          | 25        | 0.46%   |
| More than 2000 | 6         | 0.11%   |
| 901-1000       | 6         | 0.11%   |
| 101-200        | 4         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3667      | 73.22%  |
| 16/10   | 621       | 12.4%   |
| Unknown | 256       | 5.11%   |
| 5/4     | 205       | 4.09%   |
| 21/9    | 92        | 1.84%   |
| 3/2     | 63        | 1.26%   |
| 4/3     | 59        | 1.18%   |
| 0.67    | 17        | 0.34%   |
| 6/5     | 10        | 0.2%    |
| 32/9    | 6         | 0.12%   |
| 1.00    | 6         | 0.12%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1597      | 29.08%  |
| 201-250        | 978       | 17.81%  |
| 81-90          | 513       | 9.34%   |
| 151-200        | 371       | 6.76%   |
| 301-350        | 370       | 6.74%   |
| Unknown        | 302       | 5.5%    |
| 141-150        | 229       | 4.17%   |
| 351-500        | 203       | 3.7%    |
| 71-80          | 198       | 3.61%   |
| More than 1000 | 133       | 2.42%   |
| 121-130        | 131       | 2.39%   |
| 251-300        | 124       | 2.26%   |
| 61-70          | 61        | 1.11%   |
| 51-60          | 56        | 1.02%   |
| 41-50          | 54        | 0.98%   |
| 501-1000       | 54        | 0.98%   |
| 131-140        | 35        | 0.64%   |
| 111-120        | 34        | 0.62%   |
| 1-40           | 29        | 0.53%   |
| 91-100         | 19        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1864      | 34.93%  |
| 101-120       | 1456      | 27.29%  |
| 121-160       | 1246      | 23.35%  |
| Unknown       | 302       | 5.66%   |
| 161-240       | 280       | 5.25%   |
| 1-50          | 108       | 2.02%   |
| More than 240 | 80        | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4184      | 78.97%  |
| 2     | 777       | 14.67%  |
| 0     | 239       | 4.51%   |
| 3     | 91        | 1.72%   |
| 4     | 6         | 0.11%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2958      | 37.77%  |
| Intel                             | 2224      | 28.4%   |
| Qualcomm Atheros                  | 960       | 12.26%  |
| Broadcom                          | 482       | 6.15%   |
| TP-Link                           | 133       | 1.7%    |
| Ralink Technology                 | 121       | 1.54%   |
| Marvell Technology Group          | 118       | 1.51%   |
| Broadcom Limited                  | 100       | 1.28%   |
| Nvidia                            | 90        | 1.15%   |
| Ralink                            | 82        | 1.05%   |
| MediaTek                          | 77        | 0.98%   |
| Qualcomm Atheros Communications   | 42        | 0.54%   |
| Xiaomi                            | 33        | 0.42%   |
| ASIX Electronics                  | 33        | 0.42%   |
| Samsung Electronics               | 29        | 0.37%   |
| D-Link                            | 24        | 0.31%   |
| Silicon Integrated Systems [SiS]  | 20        | 0.26%   |
| VIA Technologies                  | 18        | 0.23%   |
| DisplayLink                       | 17        | 0.22%   |
| D-Link System                     | 17        | 0.22%   |
| ASUSTek Computer                  | 17        | 0.22%   |
| Qualcomm                          | 16        | 0.2%    |
| Lenovo                            | 15        | 0.19%   |
| JMicron Technology                | 14        | 0.18%   |
| Ericsson Business Mobile Networks | 14        | 0.18%   |
| Dell                              | 14        | 0.18%   |
| Sierra Wireless                   | 12        | 0.15%   |
| Hewlett-Packard                   | 12        | 0.15%   |
| Belkin Components                 | 12        | 0.15%   |
| Microsoft                         | 10        | 0.13%   |
| Huawei Technologies               | 10        | 0.13%   |
| Edimax Technology                 | 8         | 0.1%    |
| ZyDAS                             | 6         | 0.08%   |
| NetGear                           | 5         | 0.06%   |
| Microchip Technology              | 5         | 0.06%   |
| LSI                               | 4         | 0.05%   |
| Gemtek                            | 4         | 0.05%   |
| Attansic Technology               | 4         | 0.05%   |
| Arduino SA                        | 4         | 0.05%   |
| Aquantia                          | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2001      | 22.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 320       | 3.54%   |
| Intel Wi-Fi 6 AX200                                                     | 204       | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 156       | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 140       | 1.55%   |
| Intel Wireless 8265 / 8275                                              | 126       | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 125       | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 116       | 1.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 116       | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 115       | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 110       | 1.22%   |
| Intel Wireless 7265                                                     | 110       | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 108       | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 106       | 1.17%   |
| Intel Wireless 3165                                                     | 97        | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 96        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                    | 90        | 1%      |
| Realtek RTL8125 2.5GbE Controller                                       | 89        | 0.98%   |
| Intel I211 Gigabit Network Connection                                   | 85        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 78        | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 0.8%    |
| Intel Wireless 7260                                                     | 68        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 49        | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 48        | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 46        | 0.51%   |
| Intel WiFi Link 5100                                                    | 46        | 0.51%   |
| Intel Ethernet Connection I217-LM                                       | 46        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 45        | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 45        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 45        | 0.5%    |
| Intel Ethernet Controller I225-V                                        | 45        | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 44        | 0.49%   |
| Intel Wireless 8260                                                     | 44        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1671      | 40.08%  |
| Realtek Semiconductor                 | 803       | 19.26%  |
| Qualcomm Atheros                      | 741       | 17.77%  |
| Broadcom                              | 301       | 7.22%   |
| Ralink Technology                     | 121       | 2.9%    |
| TP-Link                               | 113       | 2.71%   |
| Ralink                                | 82        | 1.97%   |
| MediaTek                              | 74        | 1.78%   |
| Broadcom Limited                      | 68        | 1.63%   |
| Qualcomm Atheros Communications       | 42        | 1.01%   |
| D-Link                                | 24        | 0.58%   |
| ASUSTek Computer                      | 17        | 0.41%   |
| Sierra Wireless                       | 12        | 0.29%   |
| Belkin Components                     | 12        | 0.29%   |
| D-Link System                         | 11        | 0.26%   |
| Microsoft                             | 9         | 0.22%   |
| Edimax Technology                     | 8         | 0.19%   |
| Dell                                  | 8         | 0.19%   |
| ZyDAS                                 | 6         | 0.14%   |
| Marvell Technology Group              | 6         | 0.14%   |
| NetGear                               | 5         | 0.12%   |
| Qualcomm                              | 4         | 0.1%    |
| Hewlett-Packard                       | 4         | 0.1%    |
| Gemtek                                | 4         | 0.1%    |
| Texas Instruments                     | 3         | 0.07%   |
| Sitecom Europe                        | 2         | 0.05%   |
| Realtek                               | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| Fibocom                               | 2         | 0.05%   |
| Accton Technology                     | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Standard Microsystems                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| AirTies Wireless Networks             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |
| 3Com                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 204       | 4.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 140       | 3.34%   |
| Intel Wireless 8265 / 8275                                              | 126       | 3%      |
| Intel Wi-Fi 6 AX201                                                     | 125       | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 116       | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 115       | 2.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 110       | 2.62%   |
| Intel Wireless 7265                                                     | 110       | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 108       | 2.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 106       | 2.53%   |
| Intel Wireless 3165                                                     | 97        | 2.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 96        | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 78        | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 1.72%   |
| Intel Wireless 7260                                                     | 68        | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 49        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 48        | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 46        | 1.1%    |
| Intel WiFi Link 5100                                                    | 46        | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 45        | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 45        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 1.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 44        | 1.05%   |
| Intel Wireless 8260                                                     | 44        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 40        | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 40        | 0.95%   |
| Intel Wireless 3160                                                     | 40        | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 39        | 0.93%   |
| Realtek 802.11ac NIC                                                    | 38        | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                         | 38        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 38        | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 34        | 0.81%   |
| Intel Wireless-AC 9260                                                  | 34        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2617      | 56.03%  |
| Intel                                  | 1010      | 21.62%  |
| Qualcomm Atheros                       | 306       | 6.55%   |
| Broadcom                               | 237       | 5.07%   |
| Marvell Technology Group               | 113       | 2.42%   |
| Nvidia                                 | 90        | 1.93%   |
| Broadcom Limited                       | 34        | 0.73%   |
| ASIX Electronics                       | 33        | 0.71%   |
| Xiaomi                                 | 32        | 0.69%   |
| TP-Link                                | 21        | 0.45%   |
| Silicon Integrated Systems [SiS]       | 20        | 0.43%   |
| Samsung Electronics                    | 19        | 0.41%   |
| VIA Technologies                       | 18        | 0.39%   |
| DisplayLink                            | 17        | 0.36%   |
| Lenovo                                 | 15        | 0.32%   |
| JMicron Technology                     | 14        | 0.3%    |
| Qualcomm                               | 12        | 0.26%   |
| D-Link System                          | 6         | 0.13%   |
| Huawei Technologies                    | 5         | 0.11%   |
| LSI                                    | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Attansic Technology                    | 4         | 0.09%   |
| Aquantia                               | 4         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.06%   |
| Microchip Technology                   | 3         | 0.06%   |
| MediaTek                               | 3         | 0.06%   |
| IBM                                    | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| Google                                 | 2         | 0.04%   |
| Davicom Semiconductor                  | 2         | 0.04%   |
| ADMtek                                 | 2         | 0.04%   |
| Accton Technology                      | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| MosChip Semiconductor                  | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2001      | 41.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 320       | 6.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 156       | 3.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 116       | 2.43%   |
| Intel Ethernet Connection (2) I219-V                              | 90        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 1.87%   |
| Intel I211 Gigabit Network Connection                             | 85        | 1.78%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 45        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.88%   |
| Intel 82579V Gigabit Network Connection                           | 40        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 37        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 32        | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 30        | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 27        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 26        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 26        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                              | 26        | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 25        | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 23        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 23        | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 21        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 20        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4460      | 52.81%  |
| WiFi     | 3912      | 46.32%  |
| Modem    | 67        | 0.79%   |
| Unknown  | 7         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2960      | 54.79%  |
| Ethernet | 2441      | 45.19%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2786      | 53.64%  |
| 1     | 2186      | 42.09%  |
| 0     | 120       | 2.31%   |
| 3     | 76        | 1.46%   |
| 4     | 17        | 0.33%   |
| 5     | 5         | 0.1%    |
| 6     | 4         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4992      | 96.09%  |
| Yes  | 203       | 3.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1335      | 43.97%  |
| Realtek Semiconductor           | 356       | 11.73%  |
| Cambridge Silicon Radio         | 257       | 8.47%   |
| IMC Networks                    | 195       | 6.42%   |
| Qualcomm Atheros Communications | 162       | 5.34%   |
| Broadcom                        | 125       | 4.12%   |
| Apple                           | 124       | 4.08%   |
| Lite-On Technology              | 102       | 3.36%   |
| Foxconn / Hon Hai               | 95        | 3.13%   |
| ASUSTek Computer                | 53        | 1.75%   |
| Realtek                         | 41        | 1.35%   |
| Toshiba                         | 38        | 1.25%   |
| Dell                            | 29        | 0.96%   |
| Hewlett-Packard                 | 24        | 0.79%   |
| Ralink                          | 19        | 0.63%   |
| Alps Electric                   | 14        | 0.46%   |
| MediaTek                        | 12        | 0.4%    |
| Belkin Components               | 9         | 0.3%    |
| Integrated System Solution      | 8         | 0.26%   |
| Foxconn International           | 8         | 0.26%   |
| TP-Link                         | 7         | 0.23%   |
| Ralink Technology               | 4         | 0.13%   |
| Marvell Semiconductor           | 4         | 0.13%   |
| Edimax Technology               | 3         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.07%   |
| Roper                           | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Actions                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 487       | 16.04%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 257       | 8.46%   |
| Realtek Bluetooth Radio                             | 256       | 8.43%   |
| Intel AX201 Bluetooth                               | 246       | 8.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 220       | 7.24%   |
| Intel AX200 Bluetooth                               | 197       | 6.49%   |
| IMC Networks Bluetooth Radio                        | 94        | 3.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 65        | 2.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 65        | 2.14%   |
| IMC Networks Bluetooth Device                       | 52        | 1.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 47        | 1.55%   |
| Apple Bluetooth Host Controller                     | 46        | 1.51%   |
| Realtek Bluetooth Radio                             | 41        | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 40        | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 39        | 1.28%   |
| Apple Bluetooth USB Host Controller                 | 39        | 1.28%   |
| Intel AX210 Bluetooth                               | 38        | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.09%   |
| Intel Bluetooth Device                              | 33        | 1.09%   |
| IMC Networks Wireless_Device                        | 30        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 0.89%   |
| Lite-On Bluetooth Device                            | 27        | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 0.69%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 0.59%   |
| Apple Bluetooth HCI                                 | 16        | 0.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 0.46%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.46%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.43%   |
| Realtek RTL8821A Bluetooth                          | 12        | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 12        | 0.4%    |
| MediaTek Wireless_Device                            | 12        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 12        | 0.4%    |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3774      | 53.81%  |
| AMD                                  | 1378      | 19.65%  |
| Nvidia                               | 1230      | 17.54%  |
| C-Media Electronics                  | 109       | 1.55%   |
| Logitech                             | 40        | 0.57%   |
| Creative Labs                        | 38        | 0.54%   |
| Texas Instruments                    | 28        | 0.4%    |
| JMTek                                | 26        | 0.37%   |
| Silicon Integrated Systems [SiS]     | 22        | 0.31%   |
| Plantronics                          | 22        | 0.31%   |
| VIA Technologies                     | 20        | 0.29%   |
| GN Netcom                            | 20        | 0.29%   |
| Kingston Technology                  | 18        | 0.26%   |
| ASUSTek Computer                     | 18        | 0.26%   |
| Corsair                              | 17        | 0.24%   |
| Lenovo                               | 16        | 0.23%   |
| Creative Technology                  | 14        | 0.2%    |
| Realtek Semiconductor                | 13        | 0.19%   |
| SteelSeries ApS                      | 12        | 0.17%   |
| Generalplus Technology               | 12        | 0.17%   |
| Dell                                 | 9         | 0.13%   |
| Focusrite-Novation                   | 8         | 0.11%   |
| Sennheiser Communications            | 7         | 0.1%    |
| BEHRINGER International              | 7         | 0.1%    |
| Micro Star International             | 6         | 0.09%   |
| M-Audio                              | 6         | 0.09%   |
| Ensoniq                              | 6         | 0.09%   |
| Apple                                | 6         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.07%   |
| Scarlett                             | 5         | 0.07%   |
| Hewlett-Packard                      | 5         | 0.07%   |
| Yamaha                               | 4         | 0.06%   |
| Tenx Technology                      | 4         | 0.06%   |
| Sony                                 | 4         | 0.06%   |
| Razer USA                            | 4         | 0.06%   |
| Blue Microphones                     | 4         | 0.06%   |
| XMOS                                 | 3         | 0.04%   |
| SAVITECH                             | 3         | 0.04%   |
| QinHeng Electronics                  | 3         | 0.04%   |
| PreSonus Audio Electronics           | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 408       | 4.92%   |
| Intel Sunrise Point-LP HD Audio                                            | 350       | 4.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 294       | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 281       | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 269       | 3.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 230       | 2.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 219       | 2.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 203       | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 198       | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 198       | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 175       | 2.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 164       | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 164       | 1.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 156       | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 154       | 1.86%   |
| AMD FCH Azalia Controller                                                  | 144       | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 141       | 1.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 141       | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 137       | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 136       | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 122       | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 113       | 1.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 112       | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 111       | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 109       | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 109       | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 105       | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 103       | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 95        | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 92        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 84        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 76        | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 73        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 69        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 68        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 63        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 63        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 63        | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 62        | 0.75%   |
| AMD High Definition Audio Controller                                       | 56        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 669       | 22.37%  |
| SK hynix                                         | 475       | 15.88%  |
| Kingston                                         | 464       | 15.51%  |
| Unknown                                          | 311       | 10.4%   |
| Micron Technology                                | 284       | 9.5%    |
| Crucial                                          | 210       | 7.02%   |
| Corsair                                          | 137       | 4.58%   |
| G.Skill                                          | 89        | 2.98%   |
| Ramaxel Technology                               | 72        | 2.41%   |
| Unknown (ABCD)                                   | 44        | 1.47%   |
| Elpida                                           | 41        | 1.37%   |
| Nanya Technology                                 | 27        | 0.9%    |
| A-DATA Technology                                | 26        | 0.87%   |
| Silicon Power                                    | 15        | 0.5%    |
| Unknown                                          | 15        | 0.5%    |
| Goodram                                          | 12        | 0.4%    |
| Team                                             | 9         | 0.3%    |
| Transcend                                        | 8         | 0.27%   |
| Apacer                                           | 8         | 0.27%   |
| Unifosa                                          | 6         | 0.2%    |
| Wilk                                             | 4         | 0.13%   |
| Patriot                                          | 4         | 0.13%   |
| Kllisre                                          | 4         | 0.13%   |
| ASint Technology                                 | 4         | 0.13%   |
| Timetec                                          | 3         | 0.1%    |
| Avant                                            | 3         | 0.1%    |
| Atermiter                                        | 3         | 0.1%    |
| Unknown (AB)                                     | 2         | 0.07%   |
| Toshiba                                          | 2         | 0.07%   |
| SHARETRONIC                                      | 2         | 0.07%   |
| Qimonda                                          | 2         | 0.07%   |
| PNY                                              | 2         | 0.07%   |
| Neo Forza                                        | 2         | 0.07%   |
| Micron/Elpida                                    | 2         | 0.07%   |
| KomputerBay                                      | 2         | 0.07%   |
| Innodisk                                         | 2         | 0.07%   |
| Exceleram                                        | 2         | 0.07%   |
| ChangXin Memory                                  | 2         | 0.07%   |
| Unknown (0x5846)                                 | 1         | 0.03%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 34        | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 28        | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 28        | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 20        | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 16        | 0.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.5%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 16        | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 15        | 0.47%   |
| Unknown                                                          | 15        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 14        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 14        | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.4%    |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 12        | 0.37%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 12        | 0.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.34%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.34%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 11        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.34%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 11        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1248      | 47.78%  |
| DDR3    | 815       | 31.2%   |
| DDR2    | 150       | 5.74%   |
| LPDDR4  | 112       | 4.29%   |
| SDRAM   | 79        | 3.02%   |
| Unknown | 77        | 2.95%   |
| LPDDR3  | 62        | 2.37%   |
| DDR5    | 34        | 1.3%    |
| DDR     | 18        | 0.69%   |
| LPDDR5  | 10        | 0.38%   |
| DRAM    | 7         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1530      | 58.67%  |
| DIMM         | 879       | 33.7%   |
| Row Of Chips | 183       | 7.02%   |
| Chip         | 9         | 0.35%   |
| FB-DIMM      | 3         | 0.12%   |
| RIMM         | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1091      | 38.47%  |
| 4096  | 753       | 26.55%  |
| 16384 | 419       | 14.77%  |
| 2048  | 374       | 13.19%  |
| 1024  | 122       | 4.3%    |
| 32768 | 62        | 2.19%   |
| 512   | 8         | 0.28%   |
| 65536 | 4         | 0.14%   |
| 256   | 2         | 0.07%   |
| 3072  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 514       | 18.18%  |
| 3200    | 420       | 14.86%  |
| 2667    | 415       | 14.68%  |
| 2400    | 230       | 8.14%   |
| 1333    | 182       | 6.44%   |
| 2133    | 137       | 4.85%   |
| 667     | 98        | 3.47%   |
| 1334    | 84        | 2.97%   |
| 800     | 78        | 2.76%   |
| 3600    | 70        | 2.48%   |
| 1867    | 60        | 2.12%   |
| Unknown | 59        | 2.09%   |
| 4267    | 38        | 1.34%   |
| 8400    | 35        | 1.24%   |
| 1067    | 31        | 1.1%    |
| 4800    | 28        | 0.99%   |
| 3266    | 22        | 0.78%   |
| 3533    | 21        | 0.74%   |
| 2933    | 21        | 0.74%   |
| 1866    | 21        | 0.74%   |
| 3400    | 20        | 0.71%   |
| 1066    | 20        | 0.71%   |
| 2048    | 18        | 0.64%   |
| 533     | 17        | 0.6%    |
| 3733    | 16        | 0.57%   |
| 3000    | 15        | 0.53%   |
| 4199    | 13        | 0.46%   |
| 2733    | 13        | 0.46%   |
| 6400    | 12        | 0.42%   |
| 2666    | 11        | 0.39%   |
| 2800    | 9         | 0.32%   |
| 4266    | 7         | 0.25%   |
| 3800    | 7         | 0.25%   |
| 3466    | 7         | 0.25%   |
| 1639    | 7         | 0.25%   |
| 975     | 6         | 0.21%   |
| 400     | 6         | 0.21%   |
| 3933    | 5         | 0.18%   |
| 1800    | 5         | 0.18%   |
| 5200    | 4         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 68        | 50.75%  |
| Brother Industries       | 24        | 17.91%  |
| Canon                    | 13        | 9.7%    |
| Samsung Electronics      | 9         | 6.72%   |
| Seiko Epson              | 8         | 5.97%   |
| Oki Data                 | 3         | 2.24%   |
| Dymo-CoStar              | 2         | 1.49%   |
| Ricoh                    | 1         | 0.75%   |
| Prolific Technology      | 1         | 0.75%   |
| Magic Control Technology | 1         | 0.75%   |
| Lexmark International    | 1         | 0.75%   |
| Kyocera                  | 1         | 0.75%   |
| Konica Minolta           | 1         | 0.75%   |
| Apple                    | 1         | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 3.7%    |
| Brother HL-2030 Laser Printer                   | 5         | 3.7%    |
| HP DeskJet 2620 All-in-One Printer              | 4         | 2.96%   |
| Canon PIXMA MG2500 Series                       | 4         | 2.96%   |
| Oki Data USB Device                             | 3         | 2.22%   |
| HP LaserJet 1020                                | 3         | 2.22%   |
| HP ENVY 5540 series                             | 3         | 2.22%   |
| HP DeskJet F2492 All-in-One                     | 3         | 2.22%   |
| HP DeskJet 2700 series                          | 3         | 2.22%   |
| HP Deskjet 1050 J410                            | 3         | 2.22%   |
| Canon LiDE 400                                  | 3         | 2.22%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.48%   |
| Samsung M2070 Series                            | 2         | 1.48%   |
| HP LaserJet M14-M17                             | 2         | 1.48%   |
| HP LaserJet 1010                                | 2         | 1.48%   |
| HP ENVY 5000 series                             | 2         | 1.48%   |
| HP ENVY 4520 series                             | 2         | 1.48%   |
| HP ENVY 4500 series                             | 2         | 1.48%   |
| HP DeskJet 5550                                 | 2         | 1.48%   |
| HP DeskJet 3630 series                          | 2         | 1.48%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.48%   |
| Brother Printer                                 | 2         | 1.48%   |
| Brother MFC-J5330DW                             | 2         | 1.48%   |
| Brother DCP-1510                                | 2         | 1.48%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.74%   |
| Seiko Epson XP-230 Series                       | 1         | 0.74%   |
| Seiko Epson XP-225 Series                       | 1         | 0.74%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.74%   |
| Seiko Epson Printer                             | 1         | 0.74%   |
| Seiko Epson L555 Series                         | 1         | 0.74%   |
| Seiko Epson L1300 Series                        | 1         | 0.74%   |
| Seiko Epson ET-2700 Series                      | 1         | 0.74%   |
| Samsung SCX-4300 Series                         | 1         | 0.74%   |
| Samsung SCX-3400 Series                         | 1         | 0.74%   |
| Samsung SCX-3200 Series                         | 1         | 0.74%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.74%   |
| Samsung M267x 287x Series                       | 1         | 0.74%   |
| Ricoh SP 112                                    | 1         | 0.74%   |
| Prolific PL2305 Parallel Port                   | 1         | 0.74%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.74%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 43.75%  |
| Hewlett-Packard             | 8         | 25%     |
| Seiko Epson                 | 6         | 18.75%  |
| Acer Peripherals (now BenQ) | 2         | 6.25%   |
| Mustek Systems              | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.5%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.25%   |
| HP Scanjet 300                                           | 2         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 3.13%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.13%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.13%   |
| HP Scanjet N6010                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                         | 1         | 3.13%   |
| HP ScanJet 4570c                                         | 1         | 3.13%   |
| HP ScanJet 4300c                                         | 1         | 3.13%   |
| HP ScanJet 3570c                                         | 1         | 3.13%   |
| HP ScanJet 3300c                                         | 1         | 3.13%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 675       | 22.58%  |
| IMC Networks                           | 326       | 10.91%  |
| Microdia                               | 193       | 6.46%   |
| Realtek Semiconductor                  | 188       | 6.29%   |
| Acer                                   | 144       | 4.82%   |
| Logitech                               | 140       | 4.68%   |
| Quanta                                 | 138       | 4.62%   |
| Bison Electronics                      | 138       | 4.62%   |
| Sunplus Innovation Technology          | 130       | 4.35%   |
| Suyin                                  | 124       | 4.15%   |
| Cheng Uei Precision Industry (Foxlink) | 102       | 3.41%   |
| Apple                                  | 86        | 2.88%   |
| Syntek                                 | 85        | 2.84%   |
| Alcor Micro                            | 52        | 1.74%   |
| Lite-On Technology                     | 46        | 1.54%   |
| Luxvisions Innotech Limited            | 42        | 1.41%   |
| Ricoh                                  | 32        | 1.07%   |
| Silicon Motion                         | 23        | 0.77%   |
| Samsung Electronics                    | 22        | 0.74%   |
| Creative Technology                    | 19        | 0.64%   |
| Z-Star Microelectronics                | 17        | 0.57%   |
| Microsoft                              | 17        | 0.57%   |
| Sonix Technology                       | 16        | 0.54%   |
| Generalplus Technology                 | 14        | 0.47%   |
| GEMBIRD                                | 14        | 0.47%   |
| USB Camera                             | 11        | 0.37%   |
| Lenovo                                 | 11        | 0.37%   |
| Importek                               | 10        | 0.33%   |
| KYE Systems (Mouse Systems)            | 9         | 0.3%    |
| ARC International                      | 9         | 0.3%    |
| ALi                                    | 9         | 0.3%    |
| Sunplus Technology                     | 8         | 0.27%   |
| Cubeternet                             | 8         | 0.27%   |
| Jieli Technology                       | 7         | 0.23%   |
| Intel                                  | 7         | 0.23%   |
| Genesys Logic                          | 7         | 0.23%   |
| 2M UVC CAMERA                          | 7         | 0.23%   |
| SunplusIT                              | 6         | 0.2%    |
| Primax Electronics                     | 6         | 0.2%    |
| Trust                                  | 5         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 87        | 2.89%   |
| Chicony Integrated Camera                               | 73        | 2.43%   |
| Chicony HD WebCam                                       | 70        | 2.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 68        | 2.26%   |
| Microdia Integrated_Webcam_HD                           | 65        | 2.16%   |
| Acer HD Webcam                                          | 57        | 1.89%   |
| IMC Networks Integrated Camera                          | 55        | 1.83%   |
| Chicony USB2.0 VGA UVC WebCam                           | 43        | 1.43%   |
| Apple Built-in iSight                                   | 38        | 1.26%   |
| Realtek Integrated_Webcam_HD                            | 35        | 1.16%   |
| Acer Integrated Camera                                  | 35        | 1.16%   |
| Syntek Integrated Camera                                | 34        | 1.13%   |
| Logitech Webcam C270                                    | 34        | 1.13%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 33        | 1.1%    |
| Quanta HP TrueVision HD Camera                          | 33        | 1.1%    |
| Bison Integrated Camera                                 | 32        | 1.06%   |
| Realtek USB Camera                                      | 30        | 1%      |
| Chicony EasyCamera                                      | 30        | 1%      |
| Sunplus HD WebCam                                       | 29        | 0.96%   |
| Microdia Webcam Vitade AF                               | 29        | 0.96%   |
| Chicony USB 2.0 Camera                                  | 28        | 0.93%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 0.86%   |
| Samsung Galaxy A5 (MTP)                                 | 22        | 0.73%   |
| Chicony USB2.0 Camera                                   | 22        | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                            | 21        | 0.7%    |
| Chicony HP TrueVision HD Camera                         | 21        | 0.7%    |
| Apple FaceTime HD Camera (Built-in)                     | 21        | 0.7%    |
| Syntek EasyCamera                                       | 20        | 0.66%   |
| Logitech HD Pro Webcam C920                             | 20        | 0.66%   |
| Lite-On Integrated Camera                               | 19        | 0.63%   |
| IMC Networks ov9734_azurewave_camera                    | 19        | 0.63%   |
| Chicony HP Truevision HD                                | 19        | 0.63%   |
| Bison HD Camera                                         | 19        | 0.63%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.6%    |
| Chicony VGA Webcam                                      | 18        | 0.6%    |
| Chicony Integrated Camera (1280x720@30)                 | 18        | 0.6%    |
| Chicony HP HD Camera                                    | 18        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 18        | 0.6%    |
| Realtek Lenovo EasyCamera                               | 17        | 0.57%   |
| Quanta HP Wide Vision HD Camera                         | 17        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 131       | 30.54%  |
| Validity Sensors                   | 97        | 22.61%  |
| Shenzhen Goodix Technology         | 76        | 17.72%  |
| Elan Microelectronics              | 39        | 9.09%   |
| AuthenTec                          | 37        | 8.62%   |
| Upek                               | 27        | 6.29%   |
| LighTuning Technology              | 14        | 3.26%   |
| STMicroelectronics                 | 7         | 1.63%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 56        | 13.05%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 37        | 8.62%   |
| Elan ELAN:Fingerprint                                                      | 35        | 8.16%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 7.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 3.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 3.03%   |
| Synaptics  WBDI                                                            | 12        | 2.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 1.86%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.63%   |
| AuthenTec AES1600                                                          | 7         | 1.63%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.4%    |
| Validity Sensors VFS491                                                    | 5         | 1.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.17%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.17%   |
| Synaptics WBDI                                                             | 5         | 1.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.17%   |
| AuthenTec AES2810                                                          | 5         | 1.17%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 1.17%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.93%   |
| Synaptics UWP WBDI                                                         | 4         | 0.93%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.93%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.93%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.7%    |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.7%    |
| LighTuning Fingerprint Sensor                                              | 3         | 0.7%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.47%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 74        | 34.91%  |
| Broadcom                  | 56        | 26.42%  |
| O2 Micro                  | 24        | 11.32%  |
| Lenovo                    | 10        | 4.72%   |
| Advanced Card Systems     | 8         | 3.77%   |
| Realtek Semiconductor     | 6         | 2.83%   |
| Chicony Electronics       | 6         | 2.83%   |
| C3PO                      | 6         | 2.83%   |
| Cherry                    | 5         | 2.36%   |
| Upek                      | 4         | 1.89%   |
| SCM Microsystems          | 3         | 1.42%   |
| Gemalto (was Gemplus)     | 3         | 1.42%   |
| OmniKey                   | 2         | 0.94%   |
| Hewlett-Packard           | 2         | 0.94%   |
| In Focus Systems          | 1         | 0.47%   |
| Fujitsu Siemens Computers | 1         | 0.47%   |
| Bit4id                    | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 33.02%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 10.85%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 9.43%   |
| Broadcom 5880                                                                | 16        | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 4.72%   |
| Broadcom 58200                                                               | 9         | 4.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 2.83%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 2.83%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 2.83%   |
| C3PO LTC31v2                                                                 | 5         | 2.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 1.89%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 1.89%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.89%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.94%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.94%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 0.94%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.94%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.47%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.47%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.47%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.47%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.47%   |
| Bit4id miniLector-s                                                          | 1         | 0.47%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.47%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3858      | 72.76%  |
| 1     | 1147      | 21.63%  |
| 2     | 244       | 4.6%    |
| 3     | 34        | 0.64%   |
| 4     | 8         | 0.15%   |
| 5     | 7         | 0.13%   |
| 6     | 2         | 0.04%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 443       | 25.34%  |
| Fingerprint reader       | 420       | 24.03%  |
| Net/wireless             | 262       | 14.99%  |
| Chipcard                 | 173       | 9.9%    |
| Multimedia controller    | 109       | 6.24%   |
| Camera                   | 60        | 3.43%   |
| Communication controller | 53        | 3.03%   |
| Bluetooth                | 47        | 2.69%   |
| Unassigned class         | 37        | 2.12%   |
| Storage                  | 28        | 1.6%    |
| Sound                    | 26        | 1.49%   |
| Card reader              | 23        | 1.32%   |
| Net/ethernet             | 17        | 0.97%   |
| Network                  | 15        | 0.86%   |
| Flash memory             | 10        | 0.57%   |
| Modem                    | 9         | 0.51%   |
| Dvb card                 | 7         | 0.4%    |
| Firewire controller      | 4         | 0.23%   |
| Storage/raid             | 2         | 0.11%   |
| Tv card                  | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |


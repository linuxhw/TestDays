Linux in Brazil - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 9798

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Positivo B... | VJFE53F11X-B0511H           | [24b1be97d6](https://linux-hardware.org/?probe=24b1be97d6) | Dec 01, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | [a2e91cba31](https://linux-hardware.org/?probe=a2e91cba31) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Samsung       | 300E5K/300E5Q               | [f6bb652f5a](https://linux-hardware.org/?probe=f6bb652f5a) | Nov 30, 2022 |
| Samsung       | 550XDA                      | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Philco        | 14H                         | [8d29065667](https://linux-hardware.org/?probe=8d29065667) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Positivo B... | S14SL03                     | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| Dell          | Vostro 5470                 | [15c504a6ef](https://linux-hardware.org/?probe=15c504a6ef) | Nov 29, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [adb0404576](https://linux-hardware.org/?probe=adb0404576) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Acer          | TravelMate B113             | [567c2d2e20](https://linux-hardware.org/?probe=567c2d2e20) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Dell          | G15 5520                    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [ab9e6cc193](https://linux-hardware.org/?probe=ab9e6cc193) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [a4d6ce5fa1](https://linux-hardware.org/?probe=a4d6ce5fa1) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | [99e1d10484](https://linux-hardware.org/?probe=99e1d10484) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | [7d3bf460f7](https://linux-hardware.org/?probe=7d3bf460f7) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [c41d8da6ac](https://linux-hardware.org/?probe=c41d8da6ac) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [47d9a5f1ca](https://linux-hardware.org/?probe=47d9a5f1ca) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [5d324af4d0](https://linux-hardware.org/?probe=5d324af4d0) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c3e10b2149](https://linux-hardware.org/?probe=c3e10b2149) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [cd5eb0566d](https://linux-hardware.org/?probe=cd5eb0566d) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [3e969e8aa0](https://linux-hardware.org/?probe=3e969e8aa0) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2965050f1a](https://linux-hardware.org/?probe=2965050f1a) | Nov 25, 2022 |
| ASUSTek       | Z450LA                      | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| Avell High... | STORM TWO                   | [d8a406b26c](https://linux-hardware.org/?probe=d8a406b26c) | Nov 24, 2022 |
| Sony          | VPCEA23FB                   | [187f57793d](https://linux-hardware.org/?probe=187f57793d) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47116ddd3e](https://linux-hardware.org/?probe=47116ddd3e) | Nov 24, 2022 |
| Toshiba       | IS 1442                     | [8a2d7b5a48](https://linux-hardware.org/?probe=8a2d7b5a48) | Nov 23, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | System Vostro 3460          | [4f9fb6602d](https://linux-hardware.org/?probe=4f9fb6602d) | Nov 23, 2022 |
| Samsung       | 270E5K                      | [871e23c67c](https://linux-hardware.org/?probe=871e23c67c) | Nov 23, 2022 |
| Samsung       | 270E5K                      | [398893bbd1](https://linux-hardware.org/?probe=398893bbd1) | Nov 23, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [0fd3b230e0](https://linux-hardware.org/?probe=0fd3b230e0) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Acer          | Aspire E5-574G              | [703b6ee54d](https://linux-hardware.org/?probe=703b6ee54d) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| Dell          | Latitude 5480               | [5b9f1e717c](https://linux-hardware.org/?probe=5b9f1e717c) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Dell          | Inspiron 5548               | [8d8a193e7b](https://linux-hardware.org/?probe=8d8a193e7b) | Nov 21, 2022 |
| Dell          | Inspiron 3442               | [d9678fb5a7](https://linux-hardware.org/?probe=d9678fb5a7) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| Toshiba       | IS 1422                     | [aa59e6576d](https://linux-hardware.org/?probe=aa59e6576d) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Acer          | Nitro AN515-44              | [c6b85f956a](https://linux-hardware.org/?probe=c6b85f956a) | Nov 20, 2022 |
| Acer          | Aspire E1-571               | [35fc3411ec](https://linux-hardware.org/?probe=35fc3411ec) | Nov 20, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [1253590f60](https://linux-hardware.org/?probe=1253590f60) | Nov 20, 2022 |
| Samsung       | 767XCL                      | [729f4f303e](https://linux-hardware.org/?probe=729f4f303e) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e777561ba5](https://linux-hardware.org/?probe=e777561ba5) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [496647cddb](https://linux-hardware.org/?probe=496647cddb) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [1d527a6849](https://linux-hardware.org/?probe=1d527a6849) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| HP            | Presario CQ43               | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [f796cfccaa](https://linux-hardware.org/?probe=f796cfccaa) | Nov 17, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [873552cfae](https://linux-hardware.org/?probe=873552cfae) | Nov 17, 2022 |
| Compaq        | 420                         | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | [7d7f4061fa](https://linux-hardware.org/?probe=7d7f4061fa) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | [d36317c3be](https://linux-hardware.org/?probe=d36317c3be) | Nov 17, 2022 |
| Dell          | G15 5510                    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [7aa6773734](https://linux-hardware.org/?probe=7aa6773734) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [d5c4a2f02e](https://linux-hardware.org/?probe=d5c4a2f02e) | Nov 16, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Dell          | Inspiron 3583               | [1dc59dc45d](https://linux-hardware.org/?probe=1dc59dc45d) | Nov 16, 2022 |
| Sony          | SVE14A15FBB                 | [1b368520d1](https://linux-hardware.org/?probe=1b368520d1) | Nov 16, 2022 |
| Positivo B... | VJFE44F11X-B2111H           | [070af1bd42](https://linux-hardware.org/?probe=070af1bd42) | Nov 16, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Acer          | Aspire E5-571               | [3e04c315ee](https://linux-hardware.org/?probe=3e04c315ee) | Nov 15, 2022 |
| Daten Tecn... | DT02-M4                     | [783a9a5607](https://linux-hardware.org/?probe=783a9a5607) | Nov 15, 2022 |
| Gateway       | NV55C                       | [64d8e467d4](https://linux-hardware.org/?probe=64d8e467d4) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [a21cf96dd6](https://linux-hardware.org/?probe=a21cf96dd6) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [14e272fe11](https://linux-hardware.org/?probe=14e272fe11) | Nov 15, 2022 |
| Samsung       | RV411                       | [ded212573f](https://linux-hardware.org/?probe=ded212573f) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | [c6b6ee8cc8](https://linux-hardware.org/?probe=c6b6ee8cc8) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | [e751f32d49](https://linux-hardware.org/?probe=e751f32d49) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Lenovo        | G50-80 80R0                 | [35193d2431](https://linux-hardware.org/?probe=35193d2431) | Nov 14, 2022 |
| Dell          | Vostro 5470                 | [5b542891b7](https://linux-hardware.org/?probe=5b542891b7) | Nov 14, 2022 |
| Multilaser    | PC121                       | [5870f0d565](https://linux-hardware.org/?probe=5870f0d565) | Nov 14, 2022 |
| Acer          | Nitro AN517-54              | [b5c1404ef7](https://linux-hardware.org/?probe=b5c1404ef7) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Standard      | MB40II                      | [c95529c90a](https://linux-hardware.org/?probe=c95529c90a) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | [d3b618e418](https://linux-hardware.org/?probe=d3b618e418) | Nov 12, 2022 |
| Apple         | MacBookPro6,2               | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| LG Electro... | 15Z970-E.BH91P1             | [347940efc3](https://linux-hardware.org/?probe=347940efc3) | Nov 11, 2022 |
| Toshiba       | IS 1422+                    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [fb2b32db6a](https://linux-hardware.org/?probe=fb2b32db6a) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Acer          | Aspire 5742                 | [9c688c611e](https://linux-hardware.org/?probe=9c688c611e) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| HP            | Pavilion dv2700             | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a4bce0a93a](https://linux-hardware.org/?probe=a4bce0a93a) | Nov 07, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [589354a449](https://linux-hardware.org/?probe=589354a449) | Nov 07, 2022 |
| Dell          | Latitude 3410               | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [c2f8bf4caf](https://linux-hardware.org/?probe=c2f8bf4caf) | Nov 07, 2022 |
| ASUSTek       | K52Jr                       | [7be3408f46](https://linux-hardware.org/?probe=7be3408f46) | Nov 07, 2022 |
| Lenovo        | G475 20080                  | [f0f78f8e7e](https://linux-hardware.org/?probe=f0f78f8e7e) | Nov 07, 2022 |
| Acer          | Aspire 5742                 | [028e3c3f64](https://linux-hardware.org/?probe=028e3c3f64) | Nov 06, 2022 |
| Samsung       | 550XDA                      | [a57a40964e](https://linux-hardware.org/?probe=a57a40964e) | Nov 06, 2022 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [5afc3788fc](https://linux-hardware.org/?probe=5afc3788fc) | Nov 06, 2022 |
| Quanta        | TWS                         | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Positivo      | W940TU                      | [ad13b613fa](https://linux-hardware.org/?probe=ad13b613fa) | Nov 06, 2022 |
| Quanta        | TWS                         | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| Positivo      | W940TU                      | [ee23486fc7](https://linux-hardware.org/?probe=ee23486fc7) | Nov 06, 2022 |
| Acer          | Nitro AN515-44              | [91851e068d](https://linux-hardware.org/?probe=91851e068d) | Nov 06, 2022 |
| Dell          | Inspiron 15-3552            | [f72391a03b](https://linux-hardware.org/?probe=f72391a03b) | Nov 05, 2022 |
| Dell          | Inspiron 5402               | [109f44c580](https://linux-hardware.org/?probe=109f44c580) | Nov 05, 2022 |
| Samsung       | 270E5J/2570EJ               | [1466580b6e](https://linux-hardware.org/?probe=1466580b6e) | Nov 05, 2022 |
| Dell          | Vostro 13 5310              | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| Dell          | Inspiron 11-3168            | [71fac7ca47](https://linux-hardware.org/?probe=71fac7ca47) | Nov 05, 2022 |
| Toshiba       | IS 1422                     | [2ea67b9fac](https://linux-hardware.org/?probe=2ea67b9fac) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| Acer          | Nitro AN515-44              | [03176fa010](https://linux-hardware.org/?probe=03176fa010) | Nov 04, 2022 |
| Dell          | G15 5511                    | [68f1e6d4f0](https://linux-hardware.org/?probe=68f1e6d4f0) | Nov 04, 2022 |
| Sony          | VPCEA23FB                   | [ff50b0dd2a](https://linux-hardware.org/?probe=ff50b0dd2a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| Sony          | VPCEB4L1E                   | [5448ca63bc](https://linux-hardware.org/?probe=5448ca63bc) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Avell High... | B.ON                        | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| Intel         | powered classmate PC        | [5e9392864a](https://linux-hardware.org/?probe=5e9392864a) | Nov 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [43609f5bd5](https://linux-hardware.org/?probe=43609f5bd5) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| Positivo      | Mobile                      | [f35235fdfa](https://linux-hardware.org/?probe=f35235fdfa) | Nov 03, 2022 |
| Positivo      | Mobile                      | [581c79bdee](https://linux-hardware.org/?probe=581c79bdee) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | [cdd5c3cca0](https://linux-hardware.org/?probe=cdd5c3cca0) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | [7d43f3c00b](https://linux-hardware.org/?probe=7d43f3c00b) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| Samsung       | 550P5C/550P7C               | [39cb4cb083](https://linux-hardware.org/?probe=39cb4cb083) | Nov 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | [09c2704bb0](https://linux-hardware.org/?probe=09c2704bb0) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Samsung       | 800G5M/800G5W               | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [973fc77891](https://linux-hardware.org/?probe=973fc77891) | Oct 31, 2022 |
| LG Electro... | A560-T.BG77P1               | [cad4120a42](https://linux-hardware.org/?probe=cad4120a42) | Oct 31, 2022 |
| Avell High... | B.ON                        | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c8970ae94a](https://linux-hardware.org/?probe=c8970ae94a) | Oct 31, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| Dell          | Precision 5750              | [9b9addd3b7](https://linux-hardware.org/?probe=9b9addd3b7) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| Samsung       | 670Z5E                      | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| Avell High... | B.ON                        | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| Lenovo        | Unknown                     | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [fe1166a134](https://linux-hardware.org/?probe=fe1166a134) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [b35b1298a8](https://linux-hardware.org/?probe=b35b1298a8) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| Acer          | Nitro AN515-44              | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Dell          | Inspiron 5402               | [a7a8cc4cff](https://linux-hardware.org/?probe=a7a8cc4cff) | Oct 27, 2022 |
| Avell High... | A60 MUV                     | [ccdf105523](https://linux-hardware.org/?probe=ccdf105523) | Oct 26, 2022 |
| Sony          | VPCEA23FB                   | [1b9688e23f](https://linux-hardware.org/?probe=1b9688e23f) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | [a0adbfd7fe](https://linux-hardware.org/?probe=a0adbfd7fe) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | [519384ee8a](https://linux-hardware.org/?probe=519384ee8a) | Oct 26, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [562c9438d1](https://linux-hardware.org/?probe=562c9438d1) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Acer          | Nitro AN515-43              | [9a9880cc6a](https://linux-hardware.org/?probe=9a9880cc6a) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | S500CA                      | [bc57450141](https://linux-hardware.org/?probe=bc57450141) | Oct 24, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Avell High... | C62 MOB                     | [3baeb7ee26](https://linux-hardware.org/?probe=3baeb7ee26) | Oct 22, 2022 |
| Acer          | Aspire A315-53              | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Avell High... | B.ON                        | [17ce0979b3](https://linux-hardware.org/?probe=17ce0979b3) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Dell          | Latitude E5410              | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| Positivo      | C4120F                      | [92338290da](https://linux-hardware.org/?probe=92338290da) | Oct 20, 2022 |
| Acer          | Aspire E5-574               | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Samsung       | 550XDA                      | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| Samsung       | 270E5J/2570EJ               | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| Lenovo        | G480                        | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| Avell High... | B.ON                        | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Teclast       | F7 Plus                     | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| Dell          | Inspiron 5447               | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Multilaser    | PC024                       | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [81cec7c137](https://linux-hardware.org/?probe=81cec7c137) | Oct 16, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [2d843ba905](https://linux-hardware.org/?probe=2d843ba905) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| Acer          | Nitro AN515-44              | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Alienware     | m15 R6                      | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| Acer          | Nitro AN515-44              | [8e16d67f02](https://linux-hardware.org/?probe=8e16d67f02) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Compaq        | 420                         | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [19d249aa9c](https://linux-hardware.org/?probe=19d249aa9c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b5cfcb5d6c](https://linux-hardware.org/?probe=b5cfcb5d6c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a65b043bb7](https://linux-hardware.org/?probe=a65b043bb7) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | [491ba5984a](https://linux-hardware.org/?probe=491ba5984a) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | [d22d4118a7](https://linux-hardware.org/?probe=d22d4118a7) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| Acer          | Aspire A315-34              | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| Samsung       | 300E5M/300E5L               | [f8eae084ac](https://linux-hardware.org/?probe=f8eae084ac) | Oct 13, 2022 |
| Lenovo        | G50-80 80R0                 | [990bec11d7](https://linux-hardware.org/?probe=990bec11d7) | Oct 13, 2022 |
| Dell          | Inspiron 5567               | [754608b701](https://linux-hardware.org/?probe=754608b701) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Acer          | Aspire A315-53              | [3c99de982b](https://linux-hardware.org/?probe=3c99de982b) | Oct 13, 2022 |
| HP            | G42                         | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| Lenovo        | ThinkPad T480 20L6S1U700    | [df4489e9fb](https://linux-hardware.org/?probe=df4489e9fb) | Oct 12, 2022 |
| Acer          | Aspire ES1-572              | [7741ed43d0](https://linux-hardware.org/?probe=7741ed43d0) | Oct 12, 2022 |
| Acer          | Aspire A514-54              | [b566c0179a](https://linux-hardware.org/?probe=b566c0179a) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Acer          | Nitro AN515-52              | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Dell          | Latitude 5410               | [c69cc79a8e](https://linux-hardware.org/?probe=c69cc79a8e) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Samsung       | 550XBE/350XBE               | [bfce31736f](https://linux-hardware.org/?probe=bfce31736f) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Acer          | Nitro AN515-44              | [be45a704e2](https://linux-hardware.org/?probe=be45a704e2) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| Acer          | Aspire A315-53              | [cdd4dd4637](https://linux-hardware.org/?probe=cdd4dd4637) | Oct 08, 2022 |
| Positivo      | Q232A                       | [658da8785e](https://linux-hardware.org/?probe=658da8785e) | Oct 08, 2022 |
| Standard      | MB40II                      | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [dd91590e9f](https://linux-hardware.org/?probe=dd91590e9f) | Oct 07, 2022 |
| Acer          | Aspire E1-571               | [fe1e7b060c](https://linux-hardware.org/?probe=fe1e7b060c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [6f08bf3d68](https://linux-hardware.org/?probe=6f08bf3d68) | Oct 07, 2022 |
| Positivo      | Mobile                      | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| Positivo      | W940SU2                     | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Dell          | Inspiron 5537               | [75f96017fd](https://linux-hardware.org/?probe=75f96017fd) | Oct 05, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| Positivo      | C14CR01                     | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| Avell High... | B.ON                        | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Dell          | Inspiron 3442               | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Unknown       | Unknown                     | [23c45d949c](https://linux-hardware.org/?probe=23c45d949c) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [10fec0d039](https://linux-hardware.org/?probe=10fec0d039) | Oct 04, 2022 |
| Intel         | W7645                       | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [f30bf7e978](https://linux-hardware.org/?probe=f30bf7e978) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [a9281e38d4](https://linux-hardware.org/?probe=a9281e38d4) | Oct 04, 2022 |
| Dell          | G3 3500                     | [9a574c1075](https://linux-hardware.org/?probe=9a574c1075) | Oct 04, 2022 |
| Dell          | Latitude E6420              | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c277d88bb6](https://linux-hardware.org/?probe=c277d88bb6) | Oct 03, 2022 |
| Sony          | VPCCA15FX                   | [c6c2a651b9](https://linux-hardware.org/?probe=c6c2a651b9) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | Inspiron 5590               | [bdb7d444f0](https://linux-hardware.org/?probe=bdb7d444f0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Dell          | XPS 13 9300                 | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| Unknown       | Unknown                     | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| Dell          | XPS L421X                   | [dc90cf9dbf](https://linux-hardware.org/?probe=dc90cf9dbf) | Oct 02, 2022 |
| Samsung       | 275E4E/275E5E               | [ba82d9366c](https://linux-hardware.org/?probe=ba82d9366c) | Oct 02, 2022 |
| Avell High... | B.ON                        | [240b350525](https://linux-hardware.org/?probe=240b350525) | Oct 02, 2022 |
| Positivo      | Mobile                      | [640bc1a962](https://linux-hardware.org/?probe=640bc1a962) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Sony          | VPCCA15FX                   | [96eb3d8cf7](https://linux-hardware.org/?probe=96eb3d8cf7) | Oct 01, 2022 |
| Lenovo        | G400s VILG1                 | [e666344187](https://linux-hardware.org/?probe=e666344187) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [b62ddbdab0](https://linux-hardware.org/?probe=b62ddbdab0) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | [9a047ee214](https://linux-hardware.org/?probe=9a047ee214) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | [4c0a153a12](https://linux-hardware.org/?probe=4c0a153a12) | Oct 01, 2022 |
| Chuwi         | HeroBook Air                | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| Positivo      | Mobile                      | [dcf8b09bec](https://linux-hardware.org/?probe=dcf8b09bec) | Sep 30, 2022 |
| Positivo      | Mobile                      | [6d2584bcb8](https://linux-hardware.org/?probe=6d2584bcb8) | Sep 30, 2022 |
| Acer          | Nitro AN515-44              | [149337514c](https://linux-hardware.org/?probe=149337514c) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fa00f3d0ca](https://linux-hardware.org/?probe=fa00f3d0ca) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| Dell          | Inspiron 5447               | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| Dell          | Vostro 15 3515              | [7e4413a053](https://linux-hardware.org/?probe=7e4413a053) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bbd715eb5a](https://linux-hardware.org/?probe=bbd715eb5a) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire E5-573               | [f7e628a5a1](https://linux-hardware.org/?probe=f7e628a5a1) | Sep 28, 2022 |
| Positivo      | S14CT01                     | [66e0c53646](https://linux-hardware.org/?probe=66e0c53646) | Sep 28, 2022 |
| Unknown       | Unknown                     | [3e450900da](https://linux-hardware.org/?probe=3e450900da) | Sep 28, 2022 |
| LG Electro... | C400-G.BC22P1               | [a325f5eb86](https://linux-hardware.org/?probe=a325f5eb86) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Philco        | PNB14.1AC14S128W10          | [ee4bc98535](https://linux-hardware.org/?probe=ee4bc98535) | Sep 27, 2022 |
| Lenovo        | ThinkPad T410 2537AT9       | [553490bb4c](https://linux-hardware.org/?probe=553490bb4c) | Sep 27, 2022 |
| Standard      | AHV                         | [a80b2d344d](https://linux-hardware.org/?probe=a80b2d344d) | Sep 27, 2022 |
| Acer          | Nitro AN515-45              | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| Dell          | Latitude 5420               | [bd81c07917](https://linux-hardware.org/?probe=bd81c07917) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | [60933ed48b](https://linux-hardware.org/?probe=60933ed48b) | Sep 26, 2022 |
| Acer          | Aspire A514-54              | [bab009e0b7](https://linux-hardware.org/?probe=bab009e0b7) | Sep 26, 2022 |
| Positivo      | S14CT01                     | [2191cd2dd1](https://linux-hardware.org/?probe=2191cd2dd1) | Sep 26, 2022 |
| HP            | G42                         | [39a4836398](https://linux-hardware.org/?probe=39a4836398) | Sep 26, 2022 |
| Samsung       | 670Z5E                      | [6bce247e38](https://linux-hardware.org/?probe=6bce247e38) | Sep 26, 2022 |
| Positivo      | S14SL01                     | [a6b3c260f4](https://linux-hardware.org/?probe=a6b3c260f4) | Sep 25, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| Positivo      | S14SL01                     | [e09fcd6e38](https://linux-hardware.org/?probe=e09fcd6e38) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [939bba43d1](https://linux-hardware.org/?probe=939bba43d1) | Sep 25, 2022 |
| Avell High... | A70 MOB                     | [b867406b76](https://linux-hardware.org/?probe=b867406b76) | Sep 25, 2022 |
| Acer          | AO532h                      | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | [7fb024bb5d](https://linux-hardware.org/?probe=7fb024bb5d) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | [1190ad2886](https://linux-hardware.org/?probe=1190ad2886) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [118cf21173](https://linux-hardware.org/?probe=118cf21173) | Sep 24, 2022 |
| Dell          | Latitude E5400              | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| Dell          | Latitude 3410               | [ba10ea9fc5](https://linux-hardware.org/?probe=ba10ea9fc5) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2322475867](https://linux-hardware.org/?probe=2322475867) | Sep 24, 2022 |
| Dell          | Latitude 5420               | [170a3248f6](https://linux-hardware.org/?probe=170a3248f6) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| Dell          | Inspiron 5566               | [4ed9eae431](https://linux-hardware.org/?probe=4ed9eae431) | Sep 23, 2022 |
| Acer          | Nitro AN515-44              | [b02d161acb](https://linux-hardware.org/?probe=b02d161acb) | Sep 23, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Sony          | SVE15125CBW                 | [50b65906b1](https://linux-hardware.org/?probe=50b65906b1) | Sep 22, 2022 |
| Dell          | Inspiron 5566               | [183f486a54](https://linux-hardware.org/?probe=183f486a54) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [74d69dbd69](https://linux-hardware.org/?probe=74d69dbd69) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| ASUSTek       | X451CA                      | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| LG Electro... | C400-G.BC22P1               | [b5aad7f903](https://linux-hardware.org/?probe=b5aad7f903) | Sep 20, 2022 |
| ASUSTek       | K46CB                       | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| LG Electro... | C400-G.BC31P1               | [66c8977810](https://linux-hardware.org/?probe=66c8977810) | Sep 19, 2022 |
| Samsung       | 300E5K/300E5Q               | [aaedf90f31](https://linux-hardware.org/?probe=aaedf90f31) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [40629d6fbc](https://linux-hardware.org/?probe=40629d6fbc) | Sep 19, 2022 |
| Acer          | Aspire E1-571               | [b98206a5fb](https://linux-hardware.org/?probe=b98206a5fb) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| Positivo      | C14CR21                     | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Samsung       | 370E4K                      | [1a297b75f9](https://linux-hardware.org/?probe=1a297b75f9) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Gateway       | NV55C                       | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Samsung       | 670Z5E                      | [50758a53dd](https://linux-hardware.org/?probe=50758a53dd) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| HP            | ProBook 6470b               | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [edc0c871cb](https://linux-hardware.org/?probe=edc0c871cb) | Sep 17, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| Samsung       | 275E4E/275E5E               | [89706d3dac](https://linux-hardware.org/?probe=89706d3dac) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| Dell          | Vostro 15 3510              | [d70dc7ab47](https://linux-hardware.org/?probe=d70dc7ab47) | Sep 16, 2022 |
| Dell          | Vostro 15 3510              | [0bcb975501](https://linux-hardware.org/?probe=0bcb975501) | Sep 16, 2022 |
| Lenovo        | G480 20149                  | [8fed7863dd](https://linux-hardware.org/?probe=8fed7863dd) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Acer          | Aspire A515-51              | [59811273b4](https://linux-hardware.org/?probe=59811273b4) | Sep 16, 2022 |
| Unknown       | Unknown                     | [d391ace7f8](https://linux-hardware.org/?probe=d391ace7f8) | Sep 16, 2022 |
| Dell          | G7 7588                     | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| HP            | ProBook 4530s               | [821a6eda47](https://linux-hardware.org/?probe=821a6eda47) | Sep 16, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Acer          | Aspire E5-571G              | [0a02b8ef94](https://linux-hardware.org/?probe=0a02b8ef94) | Sep 15, 2022 |
| Positivo      | Mobile                      | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| Dell          | Latitude 3420               | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| HP            | 1000                        | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [16cf967fc8](https://linux-hardware.org/?probe=16cf967fc8) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Compal        | NCL60/61                    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Dell          | Inspiron 5458               | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | RV415/RV515                 | [bc83707f72](https://linux-hardware.org/?probe=bc83707f72) | Sep 12, 2022 |
| HP            | EliteBook 2530p             | [4bae06f3d0](https://linux-hardware.org/?probe=4bae06f3d0) | Sep 12, 2022 |
| Dell          | Inspiron 5548               | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Avell High... | B.ON                        | [f30bca74ab](https://linux-hardware.org/?probe=f30bca74ab) | Sep 12, 2022 |
| Acer          | Aspire ES1-411              | [064b2bd5f2](https://linux-hardware.org/?probe=064b2bd5f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| Toshiba       | IS 1413G                    | [fab48b6c15](https://linux-hardware.org/?probe=fab48b6c15) | Sep 10, 2022 |
| Acer          | Aspire ES1-411              | [6bbebcbcb1](https://linux-hardware.org/?probe=6bbebcbcb1) | Sep 10, 2022 |
| ASUSTek       | K53E                        | [d39f35f5d9](https://linux-hardware.org/?probe=d39f35f5d9) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Acer          | Nitro AN515-44              | [9f5bc258b6](https://linux-hardware.org/?probe=9f5bc258b6) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| Acer          | Aspire E1-572               | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| HP            | ProBook 640 G1              | [e6c0d3de61](https://linux-hardware.org/?probe=e6c0d3de61) | Sep 09, 2022 |
| Avell High... | A70 MOB                     | [1cc84e9a0d](https://linux-hardware.org/?probe=1cc84e9a0d) | Sep 09, 2022 |
| Acer          | Aspire A515-54              | [745c098d8a](https://linux-hardware.org/?probe=745c098d8a) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc0a825c8e](https://linux-hardware.org/?probe=cc0a825c8e) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| Positivo      | H14BT58                     | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| Dell          | Inspiron 5457               | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| Dell          | Vostro 3550                 | [f04353bb0e](https://linux-hardware.org/?probe=f04353bb0e) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | [1d73ebcfb8](https://linux-hardware.org/?probe=1d73ebcfb8) | Sep 08, 2022 |
| Acer          | Aspire ES1-411              | [d3df9a2592](https://linux-hardware.org/?probe=d3df9a2592) | Sep 08, 2022 |
| Digibras      | US41II1                     | [890a4894cf](https://linux-hardware.org/?probe=890a4894cf) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | [de1ddd77dd](https://linux-hardware.org/?probe=de1ddd77dd) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| Positivo      | Mobile                      | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [104331cf4c](https://linux-hardware.org/?probe=104331cf4c) | Sep 07, 2022 |
| Positivo      | Smash                       | [0051f458c6](https://linux-hardware.org/?probe=0051f458c6) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| LG Electro... | A530-T.BE76P1               | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | [b12a6d2146](https://linux-hardware.org/?probe=b12a6d2146) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | [48a1236943](https://linux-hardware.org/?probe=48a1236943) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [93d596fc4f](https://linux-hardware.org/?probe=93d596fc4f) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Alienware     | m15 R7                      | [c9d5bcb40f](https://linux-hardware.org/?probe=c9d5bcb40f) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| ASUSTek       | X45C                        | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [0e3fd8d374](https://linux-hardware.org/?probe=0e3fd8d374) | Sep 05, 2022 |
| Lenovo        | G40-80 80JE                 | [c876beae17](https://linux-hardware.org/?probe=c876beae17) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | [e6fa43e12e](https://linux-hardware.org/?probe=e6fa43e12e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [920bfdae34](https://linux-hardware.org/?probe=920bfdae34) | Sep 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| Timi          | TM1701                      | [740d59830a](https://linux-hardware.org/?probe=740d59830a) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Itautec       | Infoway                     | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| Daten Tecn... | DT02-M4                     | [b697980a15](https://linux-hardware.org/?probe=b697980a15) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Samsung       | 670Z5E                      | [0e65ce891e](https://linux-hardware.org/?probe=0e65ce891e) | Sep 02, 2022 |
| Samsung       | 670Z5E                      | [595f13e0b9](https://linux-hardware.org/?probe=595f13e0b9) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | G15 5510                    | [78f2f5c95a](https://linux-hardware.org/?probe=78f2f5c95a) | Sep 01, 2022 |
| Dell          | G3 3590                     | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Avell High... | C62 MOB                     | [ab93c1f314](https://linux-hardware.org/?probe=ab93c1f314) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | [6e337cb132](https://linux-hardware.org/?probe=6e337cb132) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | [cdac9cafaf](https://linux-hardware.org/?probe=cdac9cafaf) | Sep 01, 2022 |
| Acer          | Aspire E5-571               | [7759e41b1d](https://linux-hardware.org/?probe=7759e41b1d) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [c1d60c7b0b](https://linux-hardware.org/?probe=c1d60c7b0b) | Aug 31, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [dafd789095](https://linux-hardware.org/?probe=dafd789095) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Dell          | Vostro 3550                 | [c26bf23cdd](https://linux-hardware.org/?probe=c26bf23cdd) | Aug 31, 2022 |
| Samsung       | 670Z5E                      | [c72797ddaa](https://linux-hardware.org/?probe=c72797ddaa) | Aug 31, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [454c7382bd](https://linux-hardware.org/?probe=454c7382bd) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| Dell          | Inspiron N5110              | [9fe8c04ec6](https://linux-hardware.org/?probe=9fe8c04ec6) | Aug 30, 2022 |
| Avell High... | B.ON                        | [dbc18dad43](https://linux-hardware.org/?probe=dbc18dad43) | Aug 30, 2022 |
| Samsung       | 300E5M/300E5L               | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [eedd8fa1eb](https://linux-hardware.org/?probe=eedd8fa1eb) | Aug 29, 2022 |
| Samsung       | 670Z5E                      | [59959102e0](https://linux-hardware.org/?probe=59959102e0) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| Sony          | VPCEB36GM                   | [4495872308](https://linux-hardware.org/?probe=4495872308) | Aug 29, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [ee3156dfc5](https://linux-hardware.org/?probe=ee3156dfc5) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Acer          | Nitro AN515-54              | [211edd7b18](https://linux-hardware.org/?probe=211edd7b18) | Aug 28, 2022 |
| Acer          | Aspire A315-53              | [6ba36ee616](https://linux-hardware.org/?probe=6ba36ee616) | Aug 28, 2022 |
| Samsung       | 670Z5E                      | [8d86f689b4](https://linux-hardware.org/?probe=8d86f689b4) | Aug 28, 2022 |
| Dell          | Inspiron 5567               | [09d8066f44](https://linux-hardware.org/?probe=09d8066f44) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| HP            | ENVY dv7                    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Acer          | Nitro AN515-44              | [7d3e13cfa9](https://linux-hardware.org/?probe=7d3e13cfa9) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Acer          | Nitro AN515-54              | [975f6a801d](https://linux-hardware.org/?probe=975f6a801d) | Aug 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [85e0bc5d57](https://linux-hardware.org/?probe=85e0bc5d57) | Aug 27, 2022 |
| Positivo      | C14CR01                     | [bb9a4c427a](https://linux-hardware.org/?probe=bb9a4c427a) | Aug 27, 2022 |
| Alienware     | m15 R6                      | [d39642f1ce](https://linux-hardware.org/?probe=d39642f1ce) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Dell          | Vostro 1520                 | [b51f7dfba6](https://linux-hardware.org/?probe=b51f7dfba6) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [c8d0dcb323](https://linux-hardware.org/?probe=c8d0dcb323) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [f2de49c59b](https://linux-hardware.org/?probe=f2de49c59b) | Aug 26, 2022 |
| Acer          | Aspire A315-34              | [d71a1ce240](https://linux-hardware.org/?probe=d71a1ce240) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [21e69486fd](https://linux-hardware.org/?probe=21e69486fd) | Aug 26, 2022 |
| Dell          | Inspiron 1525               | [46512c691b](https://linux-hardware.org/?probe=46512c691b) | Aug 26, 2022 |
| Dell          | Inspiron 1525               | [47efe2482f](https://linux-hardware.org/?probe=47efe2482f) | Aug 25, 2022 |
| Dell          | Inspiron 5537               | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Samsung       | 550XDA                      | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [635925265e](https://linux-hardware.org/?probe=635925265e) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Dell          | Inspiron 3583               | [37c79f953b](https://linux-hardware.org/?probe=37c79f953b) | Aug 24, 2022 |
| Dell          | Latitude 5400               | [fce2c90c7e](https://linux-hardware.org/?probe=fce2c90c7e) | Aug 24, 2022 |
| Acer          | Nitro AN515-44              | [b456a14fe0](https://linux-hardware.org/?probe=b456a14fe0) | Aug 24, 2022 |
| ASUSTek       | X202E                       | [b814b9f427](https://linux-hardware.org/?probe=b814b9f427) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Acer          | Aspire A315-42G             | [d5b057d1c9](https://linux-hardware.org/?probe=d5b057d1c9) | Aug 23, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3507cf3eab](https://linux-hardware.org/?probe=3507cf3eab) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [d394d086d9](https://linux-hardware.org/?probe=d394d086d9) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| Dell          | Inspiron 3501               | [514172ddcc](https://linux-hardware.org/?probe=514172ddcc) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [dd86526296](https://linux-hardware.org/?probe=dd86526296) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| Acer          | Nitro AN515-44              | [092dcdf5b7](https://linux-hardware.org/?probe=092dcdf5b7) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c41ecc4e0](https://linux-hardware.org/?probe=3c41ecc4e0) | Aug 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [323faca611](https://linux-hardware.org/?probe=323faca611) | Aug 22, 2022 |
| AMI           | Unknown                     | [b6004987ab](https://linux-hardware.org/?probe=b6004987ab) | Aug 22, 2022 |
| ASUSTek       | X45U                        | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| ASUSTek       | K53E                        | [65ddd1bb6f](https://linux-hardware.org/?probe=65ddd1bb6f) | Aug 22, 2022 |
| Dell          | Inspiron 13-5368            | [9d0f972a5f](https://linux-hardware.org/?probe=9d0f972a5f) | Aug 22, 2022 |
| Dell          | Inspiron 3501               | [2f3937854b](https://linux-hardware.org/?probe=2f3937854b) | Aug 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [64b9832653](https://linux-hardware.org/?probe=64b9832653) | Aug 22, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| HP            | Mini 110-3100               | [1e27123078](https://linux-hardware.org/?probe=1e27123078) | Aug 22, 2022 |
| Acer          | Unknown                     | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | [d9ab8accea](https://linux-hardware.org/?probe=d9ab8accea) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | [6ff066abac](https://linux-hardware.org/?probe=6ff066abac) | Aug 21, 2022 |
| Positivo      | C14RV01                     | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| Samsung       | 550XCJ/550XCR               | [cae0d518ee](https://linux-hardware.org/?probe=cae0d518ee) | Aug 21, 2022 |
| Positivo      | C14CU51                     | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| Positivo      | Mobile                      | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| Positivo      | Q4128C-S                    | [abe16f9b0c](https://linux-hardware.org/?probe=abe16f9b0c) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| Gateway       | NV55C                       | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| ASUSTek       | K45A                        | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Acer          | Aspire A515-52G             | [00a40c053e](https://linux-hardware.org/?probe=00a40c053e) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| Acer          | Nitro AN515-44              | [aa18fee893](https://linux-hardware.org/?probe=aa18fee893) | Aug 18, 2022 |
| Samsung       | 670Z5E                      | [039ab9ead1](https://linux-hardware.org/?probe=039ab9ead1) | Aug 17, 2022 |
| HP            | 14                          | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| Positivo      | S14CT01                     | [22d8d4f3a2](https://linux-hardware.org/?probe=22d8d4f3a2) | Aug 17, 2022 |
| Positivo      | S14CT01                     | [2b561def97](https://linux-hardware.org/?probe=2b561def97) | Aug 17, 2022 |
| ASUSTek       | K45A                        | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| AMI           | Unknown                     | [a1a8c0b2c5](https://linux-hardware.org/?probe=a1a8c0b2c5) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Sony          | VGN-NR230AE                 | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [3a6b82f27f](https://linux-hardware.org/?probe=3a6b82f27f) | Aug 15, 2022 |
| ASUSTek       | K84C                        | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Itautec       | Infoway W7425               | [64b3153e8a](https://linux-hardware.org/?probe=64b3153e8a) | Aug 15, 2022 |
| Dell          | Vostro 5490                 | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Lenovo        | G470 20078                  | [cafdc06a51](https://linux-hardware.org/?probe=cafdc06a51) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | Inspiron 5420               | [83b14f40e6](https://linux-hardware.org/?probe=83b14f40e6) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | [42223a802a](https://linux-hardware.org/?probe=42223a802a) | Aug 14, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| HP            | ProBook 640 G1              | [7f8289a8f3](https://linux-hardware.org/?probe=7f8289a8f3) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| Samsung       | 300E5M/300E5L               | [e39c1b59a6](https://linux-hardware.org/?probe=e39c1b59a6) | Aug 13, 2022 |
| HP            | EliteBook 8460p             | [b7418c601b](https://linux-hardware.org/?probe=b7418c601b) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [837e6e891d](https://linux-hardware.org/?probe=837e6e891d) | Aug 13, 2022 |
| Positivo      | Mobile                      | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| Samsung       | 550XDA                      | [4964cf32aa](https://linux-hardware.org/?probe=4964cf32aa) | Aug 12, 2022 |
| Acer          | Aspire A514-54              | [be52876050](https://linux-hardware.org/?probe=be52876050) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| Samsung       | R430/R480/R440              | [39323c99dc](https://linux-hardware.org/?probe=39323c99dc) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Positivo      | Q4128C-S                    | [4f8b07c958](https://linux-hardware.org/?probe=4f8b07c958) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [074b25e3a3](https://linux-hardware.org/?probe=074b25e3a3) | Aug 12, 2022 |
| Positivo      | C14CR21                     | [6e7b0da365](https://linux-hardware.org/?probe=6e7b0da365) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| Avell High... | B.ON                        | [b057c64850](https://linux-hardware.org/?probe=b057c64850) | Aug 11, 2022 |
| Dell          | Vostro 15 3515              | [087818a904](https://linux-hardware.org/?probe=087818a904) | Aug 11, 2022 |
| Dell          | Vostro 3460                 | [fbaf8208cb](https://linux-hardware.org/?probe=fbaf8208cb) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| ASUSTek       | X510UR                      | [3faeed2cc1](https://linux-hardware.org/?probe=3faeed2cc1) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Dell          | G3 3590                     | [6284e4a400](https://linux-hardware.org/?probe=6284e4a400) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19c10fbafb](https://linux-hardware.org/?probe=19c10fbafb) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3151f7847e](https://linux-hardware.org/?probe=3151f7847e) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Compaq        | Presario CQ-31              | [d22794a255](https://linux-hardware.org/?probe=d22794a255) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d34fcfc4f7](https://linux-hardware.org/?probe=d34fcfc4f7) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [350a6d8583](https://linux-hardware.org/?probe=350a6d8583) | Aug 09, 2022 |
| Alienware     | x15 R1                      | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Acer          | Aspire A315-56              | [95de2fe5b3](https://linux-hardware.org/?probe=95de2fe5b3) | Aug 08, 2022 |
| Acer          | Aspire A315-56              | [742452483f](https://linux-hardware.org/?probe=742452483f) | Aug 08, 2022 |
| Lenovo        | ThinkPad L450 20DSS0DH1N    | [1aa79c3fef](https://linux-hardware.org/?probe=1aa79c3fef) | Aug 08, 2022 |
| Dell          | Inspiron 5447               | [65b4e485ad](https://linux-hardware.org/?probe=65b4e485ad) | Aug 08, 2022 |
| Acer          | Nitro AN515-54              | [221d7636db](https://linux-hardware.org/?probe=221d7636db) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| HP            | Mini 110-3100               | [f91eefcb06](https://linux-hardware.org/?probe=f91eefcb06) | Aug 07, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| Avell High... | B.ON                        | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| Dell          | XPS 13 9310                 | [7e9a6b9e85](https://linux-hardware.org/?probe=7e9a6b9e85) | Aug 06, 2022 |
| Positivo      | Mobile                      | [017b8eeb6b](https://linux-hardware.org/?probe=017b8eeb6b) | Aug 06, 2022 |
| Positivo      | Mobile                      | [fe169d2119](https://linux-hardware.org/?probe=fe169d2119) | Aug 06, 2022 |
| Sony          | VPCSB35FB                   | [edbd7a9cb8](https://linux-hardware.org/?probe=edbd7a9cb8) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Acer          | Swift SF314-511             | [39b2c17704](https://linux-hardware.org/?probe=39b2c17704) | Aug 06, 2022 |
| Toshiba       | PORTEGE Z930                | [6cec3fa330](https://linux-hardware.org/?probe=6cec3fa330) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Dell          | Inspiron 5402               | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Compaq        | 430                         | [581a8bbf00](https://linux-hardware.org/?probe=581a8bbf00) | Aug 05, 2022 |
| HP            | ProBook 4440s               | [cb7b9336ac](https://linux-hardware.org/?probe=cb7b9336ac) | Aug 04, 2022 |
| MSI           | Katana GF66 11UC            | [8d210c5007](https://linux-hardware.org/?probe=8d210c5007) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| Dell          | Latitude E5470              | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0ef9fef16d](https://linux-hardware.org/?probe=0ef9fef16d) | Aug 04, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [8bd9c2f957](https://linux-hardware.org/?probe=8bd9c2f957) | Aug 04, 2022 |
| Positivo      | S14BW01                     | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| Sony          | VPCCW13FB                   | [34db85d2d4](https://linux-hardware.org/?probe=34db85d2d4) | Aug 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Dell          | Inspiron 5566               | [91ecf4a05f](https://linux-hardware.org/?probe=91ecf4a05f) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Dell          | Inspiron 5502               | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Acer          | Aspire A315-56              | [aed4690a47](https://linux-hardware.org/?probe=aed4690a47) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | [a1eb69af2d](https://linux-hardware.org/?probe=a1eb69af2d) | Aug 03, 2022 |
| Clevo         | W240BU                      | [df5302b1c3](https://linux-hardware.org/?probe=df5302b1c3) | Aug 03, 2022 |
| Positivo      | Smash                       | [fd44d353d3](https://linux-hardware.org/?probe=fd44d353d3) | Aug 03, 2022 |
| Daten Tecn... | DT02-M4                     | [1dfd4fe5ba](https://linux-hardware.org/?probe=1dfd4fe5ba) | Aug 03, 2022 |
| Sony          | VPCCW13FB                   | [2d36ec46e0](https://linux-hardware.org/?probe=2d36ec46e0) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03770f280e](https://linux-hardware.org/?probe=03770f280e) | Aug 02, 2022 |
| Dell          | Inspiron 5547               | [cd42712c4c](https://linux-hardware.org/?probe=cd42712c4c) | Aug 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8a4208caa8](https://linux-hardware.org/?probe=8a4208caa8) | Aug 02, 2022 |
| Dell          | Inspiron 5547               | [be6e34d630](https://linux-hardware.org/?probe=be6e34d630) | Aug 02, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | G15 5510                    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| HP            | Laptop 15-db0xxx            | [ec7e5864c2](https://linux-hardware.org/?probe=ec7e5864c2) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Positivo      | Q232A                       | [da99b8ab1e](https://linux-hardware.org/?probe=da99b8ab1e) | Aug 01, 2022 |
| Positivo      | Q232A                       | [7d860e8f5d](https://linux-hardware.org/?probe=7d860e8f5d) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Sony          | VPCCW13FB                   | [453d0f75cc](https://linux-hardware.org/?probe=453d0f75cc) | Jul 31, 2022 |
| Dell          | Inspiron 5590               | [4d91f51698](https://linux-hardware.org/?probe=4d91f51698) | Jul 31, 2022 |
| Clevo         | W240BU                      | [7f4a0b1995](https://linux-hardware.org/?probe=7f4a0b1995) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| Compaq        | Presario CQ-23              | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| Acer          | Nitro AN515-44              | [1c907403d4](https://linux-hardware.org/?probe=1c907403d4) | Jul 30, 2022 |
| Positivo      | C4128E-S                    | [03150bf5fa](https://linux-hardware.org/?probe=03150bf5fa) | Jul 29, 2022 |
| Acer          | Aspire A514-54              | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [c8609ab506](https://linux-hardware.org/?probe=c8609ab506) | Jul 29, 2022 |
| Acer          | Aspire E1-531               | [e9161d7c33](https://linux-hardware.org/?probe=e9161d7c33) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| Dell          | Inspiron 5402               | [90df51f92b](https://linux-hardware.org/?probe=90df51f92b) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| Dell          | Inspiron 3501               | [be3c46490f](https://linux-hardware.org/?probe=be3c46490f) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [fdb481a551](https://linux-hardware.org/?probe=fdb481a551) | Jul 28, 2022 |
| Acer          | Aspire A514-54              | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [adb71c8acc](https://linux-hardware.org/?probe=adb71c8acc) | Jul 28, 2022 |
| A14CR         | Unknown                     | [6315deeec1](https://linux-hardware.org/?probe=6315deeec1) | Jul 28, 2022 |
| Dell          | Latitude 5420               | [3e0d6fec55](https://linux-hardware.org/?probe=3e0d6fec55) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| Acer          | Aspire 5742                 | [4e2290847d](https://linux-hardware.org/?probe=4e2290847d) | Jul 28, 2022 |
| Positivo      | Mobile                      | [a8719171ea](https://linux-hardware.org/?probe=a8719171ea) | Jul 28, 2022 |
| Dell          | Vostro 3550                 | [db7097f5f3](https://linux-hardware.org/?probe=db7097f5f3) | Jul 28, 2022 |
| Digibras      | NH4CU03                     | [bf8a8c589a](https://linux-hardware.org/?probe=bf8a8c589a) | Jul 28, 2022 |
| Positivo      | Mobile                      | [422b663a21](https://linux-hardware.org/?probe=422b663a21) | Jul 28, 2022 |
| Unknown       | Unknown                     | [f14e834c32](https://linux-hardware.org/?probe=f14e834c32) | Jul 28, 2022 |
| Dell          | Inspiron 3421               | [67e0e7d1ba](https://linux-hardware.org/?probe=67e0e7d1ba) | Jul 28, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [0439161423](https://linux-hardware.org/?probe=0439161423) | Jul 28, 2022 |
| Positivo      | H14BT58                     | [7f271e5d68](https://linux-hardware.org/?probe=7f271e5d68) | Jul 28, 2022 |
| Samsung       | 550XBE/350XBE               | [b7fabad758](https://linux-hardware.org/?probe=b7fabad758) | Jul 27, 2022 |
| Dell          | Latitude 7480               | [86fd278e6d](https://linux-hardware.org/?probe=86fd278e6d) | Jul 27, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c872c322dc](https://linux-hardware.org/?probe=c872c322dc) | Jul 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [87f0eb95eb](https://linux-hardware.org/?probe=87f0eb95eb) | Jul 27, 2022 |
| Dell          | G5 5590                     | [ae478a8f82](https://linux-hardware.org/?probe=ae478a8f82) | Jul 27, 2022 |
| Dell          | Inspiron 5402               | [6735eaf093](https://linux-hardware.org/?probe=6735eaf093) | Jul 27, 2022 |
| HP            | Pavilion g4                 | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| Avell High... | B.ON                        | [182df5e0c6](https://linux-hardware.org/?probe=182df5e0c6) | Jul 26, 2022 |
| Intel         | powered classmate PC        | [5ef3ce99dc](https://linux-hardware.org/?probe=5ef3ce99dc) | Jul 26, 2022 |
| Intel         | powered classmate PC        | [53e2fcbd36](https://linux-hardware.org/?probe=53e2fcbd36) | Jul 26, 2022 |
| Dell          | Latitude 131L               | [ec8717bc3f](https://linux-hardware.org/?probe=ec8717bc3f) | Jul 26, 2022 |
| Toshiba       | IS 1413G                    | [adfacec492](https://linux-hardware.org/?probe=adfacec492) | Jul 26, 2022 |
| Dell          | Inspiron 14-3467            | [1c2babaa0a](https://linux-hardware.org/?probe=1c2babaa0a) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2a9595e780](https://linux-hardware.org/?probe=2a9595e780) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| Daten Tecn... | DT02-M4                     | [8719e60f77](https://linux-hardware.org/?probe=8719e60f77) | Jul 25, 2022 |
| Positivo      | C14CU51                     | [1bc38897f0](https://linux-hardware.org/?probe=1bc38897f0) | Jul 25, 2022 |
| Acer          | Aspire A315-23G             | [df57effbc5](https://linux-hardware.org/?probe=df57effbc5) | Jul 25, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ff4dba6b3e](https://linux-hardware.org/?probe=ff4dba6b3e) | Jul 24, 2022 |
| Dell          | G15 5515                    | [2d7ddd400c](https://linux-hardware.org/?probe=2d7ddd400c) | Jul 24, 2022 |
| Acer          | Aspire F5-573               | [922044b473](https://linux-hardware.org/?probe=922044b473) | Jul 24, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [252eb862c0](https://linux-hardware.org/?probe=252eb862c0) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Toshiba       | IS-1253                     | [d7bfcb65bf](https://linux-hardware.org/?probe=d7bfcb65bf) | Jul 23, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [2f8b49e4f8](https://linux-hardware.org/?probe=2f8b49e4f8) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [51d002e1b7](https://linux-hardware.org/?probe=51d002e1b7) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [41d0e95039](https://linux-hardware.org/?probe=41d0e95039) | Jul 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [6b6a156202](https://linux-hardware.org/?probe=6b6a156202) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| ASUSTek       | X450LCP                     | [0617861116](https://linux-hardware.org/?probe=0617861116) | Jul 22, 2022 |
| Unknown       | Unknown                     | [a93e6b77ec](https://linux-hardware.org/?probe=a93e6b77ec) | Jul 22, 2022 |
| Positivo      | J14AL11                     | [7510e905d8](https://linux-hardware.org/?probe=7510e905d8) | Jul 22, 2022 |
| Acer          | Aspire A315-54              | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b8ce5a0377](https://linux-hardware.org/?probe=b8ce5a0377) | Jul 22, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [2c8cd53533](https://linux-hardware.org/?probe=2c8cd53533) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| Dell          | Latitude 3420               | [07c70a9430](https://linux-hardware.org/?probe=07c70a9430) | Jul 20, 2022 |
| Avell High... | A40 LIV                     | [7a685eedd0](https://linux-hardware.org/?probe=7a685eedd0) | Jul 20, 2022 |
| Dell          | Vostro 15 3510              | [8327d57f7b](https://linux-hardware.org/?probe=8327d57f7b) | Jul 20, 2022 |
| Dell          | Inspiron 5447               | [e5b80a7f5e](https://linux-hardware.org/?probe=e5b80a7f5e) | Jul 19, 2022 |
| Dell          | Latitude 3450               | [970985b513](https://linux-hardware.org/?probe=970985b513) | Jul 19, 2022 |
| Avell High... | B.ON                        | [6bd67d621f](https://linux-hardware.org/?probe=6bd67d621f) | Jul 19, 2022 |
| HP            | EliteBook 2530p             | [8dd11387c6](https://linux-hardware.org/?probe=8dd11387c6) | Jul 19, 2022 |
| Samsung       | 270E5G/270E5U               | [c26ed846e9](https://linux-hardware.org/?probe=c26ed846e9) | Jul 19, 2022 |
| Dell          | Inspiron 5566               | [f653a494f3](https://linux-hardware.org/?probe=f653a494f3) | Jul 18, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| Dell          | Vostro 15 3510              | [bcb8dbf459](https://linux-hardware.org/?probe=bcb8dbf459) | Jul 18, 2022 |
| Dell          | Inspiron 3583               | [6f281be47b](https://linux-hardware.org/?probe=6f281be47b) | Jul 18, 2022 |
| Acer          | Aspire ES1-411              | [5d551a94bd](https://linux-hardware.org/?probe=5d551a94bd) | Jul 18, 2022 |
| Acer          | Aspire A315-23G             | [268d2145ff](https://linux-hardware.org/?probe=268d2145ff) | Jul 17, 2022 |
| Acer          | Aspire E5-575G              | [78023056af](https://linux-hardware.org/?probe=78023056af) | Jul 17, 2022 |
| ASUSTek       | X510UAR                     | [56298c2c32](https://linux-hardware.org/?probe=56298c2c32) | Jul 17, 2022 |
| Digibras      | NH4CU03                     | [803b7d3211](https://linux-hardware.org/?probe=803b7d3211) | Jul 16, 2022 |
| Digibras      | NH4CU53                     | [f6b402afe8](https://linux-hardware.org/?probe=f6b402afe8) | Jul 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [79b4ccf8b3](https://linux-hardware.org/?probe=79b4ccf8b3) | Jul 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [99f294736d](https://linux-hardware.org/?probe=99f294736d) | Jul 16, 2022 |
| Positivo      | S14CT01                     | [eac9cd386b](https://linux-hardware.org/?probe=eac9cd386b) | Jul 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [2ee086df64](https://linux-hardware.org/?probe=2ee086df64) | Jul 15, 2022 |
| AMI           | Unknown                     | [2d15648f33](https://linux-hardware.org/?probe=2d15648f33) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| ASUSTek       | UX301LA                     | [3d4655e7cf](https://linux-hardware.org/?probe=3d4655e7cf) | Jul 14, 2022 |
| Acer          | Aspire A315-23G             | [09f86c23ae](https://linux-hardware.org/?probe=09f86c23ae) | Jul 14, 2022 |
| Dell          | Inspiron 5437               | [1f59d159c7](https://linux-hardware.org/?probe=1f59d159c7) | Jul 14, 2022 |
| Lenovo        | G400s VILG1                 | [fbaf6e2d8f](https://linux-hardware.org/?probe=fbaf6e2d8f) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | [33853365fd](https://linux-hardware.org/?probe=33853365fd) | Jul 13, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [399639e6a0](https://linux-hardware.org/?probe=399639e6a0) | Jul 12, 2022 |
| Acer          | Nitro AN517-52              | [5379fd7508](https://linux-hardware.org/?probe=5379fd7508) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1b31625c12](https://linux-hardware.org/?probe=1b31625c12) | Jul 12, 2022 |
| Dell          | Latitude E7440              | [4b1c881401](https://linux-hardware.org/?probe=4b1c881401) | Jul 12, 2022 |
| ASUSTek       | X202E                       | [102f50d1a3](https://linux-hardware.org/?probe=102f50d1a3) | Jul 12, 2022 |
| Dell          | Vostro 5470                 | [aedb7a18da](https://linux-hardware.org/?probe=aedb7a18da) | Jul 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Precision 5750              | [213817ad67](https://linux-hardware.org/?probe=213817ad67) | Jul 11, 2022 |
| Positivo      | C14CU51                     | [5888159062](https://linux-hardware.org/?probe=5888159062) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3ac0019f4e](https://linux-hardware.org/?probe=3ac0019f4e) | Jul 11, 2022 |
| Dell          | Inspiron 14-3467            | [6f6ccba766](https://linux-hardware.org/?probe=6f6ccba766) | Jul 10, 2022 |
| Sony          | VGN-NW270F                  | [81c369f3c6](https://linux-hardware.org/?probe=81c369f3c6) | Jul 10, 2022 |
| Dell          | Inspiron 5421               | [8fda6f0cbc](https://linux-hardware.org/?probe=8fda6f0cbc) | Jul 10, 2022 |
| TPVAOC        | AA183M                      | [a2dcc0c977](https://linux-hardware.org/?probe=a2dcc0c977) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec2174a329](https://linux-hardware.org/?probe=ec2174a329) | Jul 10, 2022 |
| Acer          | Aspire A315-23G             | [a2ef844aef](https://linux-hardware.org/?probe=a2ef844aef) | Jul 10, 2022 |
| Acer          | Aspire A515-52              | [9dc5c32b9f](https://linux-hardware.org/?probe=9dc5c32b9f) | Jul 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d8d42d690f](https://linux-hardware.org/?probe=d8d42d690f) | Jul 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2d5d0efe6d](https://linux-hardware.org/?probe=2d5d0efe6d) | Jul 09, 2022 |
| Acer          | Aspire E5-574               | [6565916b6f](https://linux-hardware.org/?probe=6565916b6f) | Jul 09, 2022 |
| Acer          | Predator PH315-53           | [b6c6516360](https://linux-hardware.org/?probe=b6c6516360) | Jul 09, 2022 |
| Dell          | Latitude 3400               | [6a36fb9dd9](https://linux-hardware.org/?probe=6a36fb9dd9) | Jul 09, 2022 |
| Coradir       | Coradir/ES10IS5             | [f6e9e6fb39](https://linux-hardware.org/?probe=f6e9e6fb39) | Jul 09, 2022 |
| Acer          | Aspire A315-23              | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
| Dell          | Inspiron 3583               | [f413588311](https://linux-hardware.org/?probe=f413588311) | Jul 07, 2022 |
| Dell          | Inspiron 1440               | [cb9b1dda1f](https://linux-hardware.org/?probe=cb9b1dda1f) | Jul 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e850b43a12](https://linux-hardware.org/?probe=e850b43a12) | Jul 07, 2022 |
| Acer          | Aspire 5750Z                | [28c94adfea](https://linux-hardware.org/?probe=28c94adfea) | Jul 07, 2022 |
| Dell          | Vostro 15 3510              | [bb44d4f6ba](https://linux-hardware.org/?probe=bb44d4f6ba) | Jul 07, 2022 |
| Dell          | Latitude 5420               | [9601fde79c](https://linux-hardware.org/?probe=9601fde79c) | Jul 07, 2022 |
| Dell          | Inspiron 7572               | [e249d01b2b](https://linux-hardware.org/?probe=e249d01b2b) | Jul 06, 2022 |
| Samsung       | 550XDA                      | [74bcded10f](https://linux-hardware.org/?probe=74bcded10f) | Jul 06, 2022 |
| Acer          | Aspire E5-571               | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Samsung       | R430/R480/R440              | [70260c78a2](https://linux-hardware.org/?probe=70260c78a2) | Jul 06, 2022 |
| Gateway       | NE56R                       | [69f2805432](https://linux-hardware.org/?probe=69f2805432) | Jul 06, 2022 |
| Samsung       | R430/R480/R440              | [347519269f](https://linux-hardware.org/?probe=347519269f) | Jul 06, 2022 |
| Acer          | Nitro AN515-44              | [d52a3dc4ed](https://linux-hardware.org/?probe=d52a3dc4ed) | Jul 06, 2022 |
| Dell          | Inspiron 7560               | [d9e6fd6bc2](https://linux-hardware.org/?probe=d9e6fd6bc2) | Jul 06, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [17607e5f03](https://linux-hardware.org/?probe=17607e5f03) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5afb466a35](https://linux-hardware.org/?probe=5afb466a35) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [162080ffcf](https://linux-hardware.org/?probe=162080ffcf) | Jul 06, 2022 |
| Megaware      | Mega netbook IP-M10.6F.2... | [286852aacb](https://linux-hardware.org/?probe=286852aacb) | Jul 06, 2022 |
| HP            | G42                         | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| Dell          | Vostro 3460                 | [b8795fc256](https://linux-hardware.org/?probe=b8795fc256) | Jul 06, 2022 |
| HP            | Compaq Presario CQ40        | [ca07c0428a](https://linux-hardware.org/?probe=ca07c0428a) | Jul 05, 2022 |
| HP            | Notebook                    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Acer          | Nitro AN515-54              | [2292096a08](https://linux-hardware.org/?probe=2292096a08) | Jul 05, 2022 |
| Sony          | VJF153                      | [a1efa9107c](https://linux-hardware.org/?probe=a1efa9107c) | Jul 05, 2022 |
| Samsung       | 300E5M/300E5L               | [03926dc548](https://linux-hardware.org/?probe=03926dc548) | Jul 05, 2022 |
| Dell          | Inspiron 14-3467            | [b9a61ec06d](https://linux-hardware.org/?probe=b9a61ec06d) | Jul 05, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bc1f4a78a2](https://linux-hardware.org/?probe=bc1f4a78a2) | Jul 04, 2022 |
| HP            | Unknown                     | [4c05aaaab8](https://linux-hardware.org/?probe=4c05aaaab8) | Jul 04, 2022 |
| HP            | Unknown                     | [ed13c5f0f5](https://linux-hardware.org/?probe=ed13c5f0f5) | Jul 04, 2022 |
| Multilaser    | PC150                       | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| Dell          | Vostro 15 3515              | [129ffffad2](https://linux-hardware.org/?probe=129ffffad2) | Jul 03, 2022 |
| Notebook      | P65xHP                      | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| Unknown       | Unknown                     | [78e8133c88](https://linux-hardware.org/?probe=78e8133c88) | Jul 03, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c02e6b91bf](https://linux-hardware.org/?probe=c02e6b91bf) | Jul 03, 2022 |
| Dell          | Inspiron 3501               | [6b6b2abba6](https://linux-hardware.org/?probe=6b6b2abba6) | Jul 03, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [a8c5e48dc8](https://linux-hardware.org/?probe=a8c5e48dc8) | Jul 03, 2022 |
| Intel         | HuronRiver Platform         | [c0d79569d8](https://linux-hardware.org/?probe=c0d79569d8) | Jul 03, 2022 |
| Lenovo        | IdeaPad Z460 0913           | [90ea533adb](https://linux-hardware.org/?probe=90ea533adb) | Jul 02, 2022 |
| Lenovo        | IdeaPad Z460 0913           | [2d50c0ffab](https://linux-hardware.org/?probe=2d50c0ffab) | Jul 02, 2022 |
| Acer          | Aspire VX5-591G             | [5393a13046](https://linux-hardware.org/?probe=5393a13046) | Jul 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [75f07cbe46](https://linux-hardware.org/?probe=75f07cbe46) | Jul 02, 2022 |
| eMachines     | E725                        | [531d170b09](https://linux-hardware.org/?probe=531d170b09) | Jul 02, 2022 |
| Samsung       | 300E5M/300E5L               | [497939c649](https://linux-hardware.org/?probe=497939c649) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Acer          | Aspire A315-23G             | [6fc80d8654](https://linux-hardware.org/?probe=6fc80d8654) | Jul 02, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [affc21d7de](https://linux-hardware.org/?probe=affc21d7de) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [81fff806a4](https://linux-hardware.org/?probe=81fff806a4) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [294f501cdd](https://linux-hardware.org/?probe=294f501cdd) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [af946ca10b](https://linux-hardware.org/?probe=af946ca10b) | Jul 01, 2022 |
| OEM           | S20II1                      | [bcaac39dde](https://linux-hardware.org/?probe=bcaac39dde) | Jul 01, 2022 |
| Chuwi         | HeroBook Air                | [217dcb770c](https://linux-hardware.org/?probe=217dcb770c) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d68cd17ca2](https://linux-hardware.org/?probe=d68cd17ca2) | Jun 30, 2022 |
| LG Electro... | A410-G.BC48P1               | [41e6b25be5](https://linux-hardware.org/?probe=41e6b25be5) | Jun 30, 2022 |
| Acer          | Nitro AN515-44              | [2112b8aff3](https://linux-hardware.org/?probe=2112b8aff3) | Jun 30, 2022 |
| Acer          | Nitro AN515-44              | [09659e3083](https://linux-hardware.org/?probe=09659e3083) | Jun 30, 2022 |
| Dell          | Inspiron 7572               | [a6c34895e2](https://linux-hardware.org/?probe=a6c34895e2) | Jun 30, 2022 |
| Positivo      | CHT14B                      | [7aaac075a6](https://linux-hardware.org/?probe=7aaac075a6) | Jun 30, 2022 |
| Acer          | Aspire A315-23G             | [f5ca75e65b](https://linux-hardware.org/?probe=f5ca75e65b) | Jun 30, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Dell          | Inspiron 1525               | [8f507b2e8c](https://linux-hardware.org/?probe=8f507b2e8c) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| Acer          | Aspire M5-582PT             | [e159de9f3e](https://linux-hardware.org/?probe=e159de9f3e) | Jun 28, 2022 |
| Acer          | Predator G3-572             | [505efe3b72](https://linux-hardware.org/?probe=505efe3b72) | Jun 28, 2022 |
| Login Info... | LOG-MB47II7                 | [332f799fe9](https://linux-hardware.org/?probe=332f799fe9) | Jun 28, 2022 |
| BenQ          | Joybook Lite U102           | [49bbad20bd](https://linux-hardware.org/?probe=49bbad20bd) | Jun 27, 2022 |
| Positivo      | Q232A                       | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Acer          | Aspire A515-41G             | [cbb6f48321](https://linux-hardware.org/?probe=cbb6f48321) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| Apple         | MacBook5,2                  | [11aefd7938](https://linux-hardware.org/?probe=11aefd7938) | Jun 26, 2022 |
| Acer          | Nitro AN515-44              | [694f0baf86](https://linux-hardware.org/?probe=694f0baf86) | Jun 26, 2022 |
| Positivo      | S14CT01                     | [b973795a61](https://linux-hardware.org/?probe=b973795a61) | Jun 26, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Samsung       | 300E5K/300E5Q               | [6fdcfe2be7](https://linux-hardware.org/?probe=6fdcfe2be7) | Jun 26, 2022 |
| Dell          | Inspiron 3442               | [72286bac00](https://linux-hardware.org/?probe=72286bac00) | Jun 26, 2022 |
| Samsung       | 300E5K/300E5Q               | [1b7010c05b](https://linux-hardware.org/?probe=1b7010c05b) | Jun 26, 2022 |
| Acer          | Aspire E5-571G              | [f8c41984c9](https://linux-hardware.org/?probe=f8c41984c9) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [87f6da99c4](https://linux-hardware.org/?probe=87f6da99c4) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [f3c9818cba](https://linux-hardware.org/?probe=f3c9818cba) | Jun 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3b84529124](https://linux-hardware.org/?probe=3b84529124) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [7559b1f8fa](https://linux-hardware.org/?probe=7559b1f8fa) | Jun 24, 2022 |
| ASUSTek       | X551MA                      | [e5780aff8c](https://linux-hardware.org/?probe=e5780aff8c) | Jun 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| Samsung       | 370E4K                      | [d930d75576](https://linux-hardware.org/?probe=d930d75576) | Jun 24, 2022 |
| Acer          | Aspire E5-571G              | [6eb35edbfd](https://linux-hardware.org/?probe=6eb35edbfd) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [eb8dbfaa92](https://linux-hardware.org/?probe=eb8dbfaa92) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Acer          | Aspire ES1-572              | [584216bcad](https://linux-hardware.org/?probe=584216bcad) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| Teclast       | F7S                         | [dba66e9d34](https://linux-hardware.org/?probe=dba66e9d34) | Jun 22, 2022 |
| Acer          | Aspire E1-531               | [415b93724e](https://linux-hardware.org/?probe=415b93724e) | Jun 22, 2022 |
| Dell          | Vostro 5470                 | [9a5e42fa6f](https://linux-hardware.org/?probe=9a5e42fa6f) | Jun 22, 2022 |
| Acer          | Aspire E1-571               | [d863d34426](https://linux-hardware.org/?probe=d863d34426) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5eaea4e568](https://linux-hardware.org/?probe=5eaea4e568) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [d98d060a72](https://linux-hardware.org/?probe=d98d060a72) | Jun 21, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [8c6cc60dc6](https://linux-hardware.org/?probe=8c6cc60dc6) | Jun 21, 2022 |
| Acer          | Nitro AN515-55              | [b3b8a4d0c8](https://linux-hardware.org/?probe=b3b8a4d0c8) | Jun 21, 2022 |
| Philco        | OEM                         | [bee7961704](https://linux-hardware.org/?probe=bee7961704) | Jun 20, 2022 |
| Acer          | Predator G3-572             | [10466efc20](https://linux-hardware.org/?probe=10466efc20) | Jun 20, 2022 |
| A14CR         | Unknown                     | [8ecee0a59e](https://linux-hardware.org/?probe=8ecee0a59e) | Jun 19, 2022 |
| Samsung       | 300E5M/300E5L               | [9191469ae0](https://linux-hardware.org/?probe=9191469ae0) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | ProBook 4440s               | [14d2048e71](https://linux-hardware.org/?probe=14d2048e71) | Jun 19, 2022 |
| Acer          | Aspire E1-571               | [7e2a57a9a2](https://linux-hardware.org/?probe=7e2a57a9a2) | Jun 19, 2022 |
| Acer          | Aspire A315-53              | [cdaacd4b95](https://linux-hardware.org/?probe=cdaacd4b95) | Jun 18, 2022 |
| Acer          | Aspire A315-23G             | [2ec41b35a4](https://linux-hardware.org/?probe=2ec41b35a4) | Jun 18, 2022 |
| HP            | Pavilion dv7                | [7b7e3113e0](https://linux-hardware.org/?probe=7b7e3113e0) | Jun 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu 20.04     | 904       | 12.85%  |
| Ubuntu 18.04     | 590       | 8.39%   |
| Pop!_OS 20.04    | 192       | 2.73%   |
| Linux Mint 20    | 189       | 2.69%   |
| Ubuntu 22.04     | 165       | 2.35%   |
| Linux Mint 19.3  | 165       | 2.35%   |
| OpenMandriva 4.2 | 155       | 2.2%    |
| OpenMandriva 4.3 | 133       | 1.89%   |
| Linux Mint 20.3  | 130       | 1.85%   |
| Linux Mint 19.1  | 122       | 1.73%   |
| Ubuntu 19.04     | 117       | 1.66%   |
| Linux Mint 20.1  | 116       | 1.65%   |
| Arch             | 114       | 1.62%   |
| KDE neon 20.04   | 112       | 1.59%   |
| Linux Mint 20.2  | 111       | 1.58%   |
| Ubuntu 19.10     | 106       | 1.51%   |
| Manjaro          | 102       | 1.45%   |
| Zorin 15         | 90        | 1.28%   |
| Pop!_OS 22.04    | 87        | 1.24%   |
| Zorin 16         | 85        | 1.21%   |
| Debian 10        | 83        | 1.18%   |
| Fedora 35        | 78        | 1.11%   |
| Debian 11        | 76        | 1.08%   |
| Fedora 34        | 72        | 1.02%   |
| Pop!_OS 21.10    | 71        | 1.01%   |
| Fedora 32        | 69        | 0.98%   |
| Endless 3.7.8    | 68        | 0.97%   |
| Xubuntu 20.04    | 67        | 0.95%   |
| Pop!_OS 21.04    | 67        | 0.95%   |
| Endless 3.9.5    | 67        | 0.95%   |
| Fedora 36        | 63        | 0.9%    |
| Kubuntu 20.04    | 62        | 0.88%   |
| Pop!_OS 20.10    | 60        | 0.85%   |
| Fedora 33        | 60        | 0.85%   |
| Ubuntu 20.10     | 56        | 0.8%    |
| Linux Mint 19.2  | 55        | 0.78%   |
| Endless 3.9.1    | 53        | 0.75%   |
| Arch Rolling     | 51        | 0.73%   |
| Ubuntu 18.10     | 47        | 0.67%   |
| Endless 3.8.6    | 46        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2044      | 30.37%  |
| Linux Mint    | 907       | 13.47%  |
| Endless       | 819       | 12.17%  |
| Pop!_OS       | 458       | 6.8%    |
| Fedora        | 382       | 5.68%   |
| OpenMandriva  | 317       | 4.71%   |
| Debian        | 203       | 3.02%   |
| Manjaro       | 196       | 2.91%   |
| Zorin         | 179       | 2.66%   |
| Arch          | 155       | 2.3%    |
| KDE neon      | 133       | 1.98%   |
| Xubuntu       | 118       | 1.75%   |
| Kubuntu       | 114       | 1.69%   |
| Lubuntu       | 67        | 1%      |
| Ubuntu MATE   | 60        | 0.89%   |
| Elementary    | 60        | 0.89%   |
| openSUSE      | 52        | 0.77%   |
| ROSA          | 50        | 0.74%   |
| Ubuntu Unity  | 49        | 0.73%   |
| Kali          | 35        | 0.52%   |
| LMDE          | 33        | 0.49%   |
| Deepin        | 30        | 0.45%   |
| Ubuntu Budgie | 27        | 0.4%    |
| Clear Linux   | 26        | 0.39%   |
| LinuxFX       | 21        | 0.31%   |
| ArcoLinux     | 19        | 0.28%   |
| EndeavourOS   | 12        | 0.18%   |
| BigLinux      | 12        | 0.18%   |
| BlackPanther  | 11        | 0.16%   |
| CentOS        | 10        | 0.15%   |
| Reborn OS     | 9         | 0.13%   |
| UbuntuDDE     | 8         | 0.12%   |
| Peppermint    | 8         | 0.12%   |
| Parrot        | 8         | 0.12%   |
| MX            | 8         | 0.12%   |
| Gentoo        | 7         | 0.1%    |
| Garuda Linux  | 7         | 0.1%    |
| Solus         | 6         | 0.09%   |
| Linux Lite    | 5         | 0.07%   |
| Devuan        | 5         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 470       | 6.23%   |
| 5.8.0-14-generic         | 271       | 3.59%   |
| 5.10.14-desktop-1omv4002 | 149       | 1.97%   |
| 5.16.7-desktop-1omv4003  | 128       | 1.7%    |
| 5.4.0-19-generic         | 114       | 1.51%   |
| 5.3.0-28-generic         | 107       | 1.42%   |
| 5.11.0-35-generic        | 79        | 1.05%   |
| 5.4.0-7634-generic       | 74        | 0.98%   |
| 5.4.0-48-generic         | 72        | 0.95%   |
| 5.4.0-40-generic         | 70        | 0.93%   |
| 4.15.0-46-generic        | 70        | 0.93%   |
| 5.4.0-26-generic         | 63        | 0.83%   |
| 5.4.0-58-generic         | 59        | 0.78%   |
| 5.4.0-52-generic         | 57        | 0.76%   |
| 5.4.0-47-generic         | 54        | 0.72%   |
| 5.3.0-19-generic         | 50        | 0.66%   |
| 5.3.0-23-generic         | 47        | 0.62%   |
| 5.3.0-46-generic         | 46        | 0.61%   |
| 5.0.0-32-generic         | 46        | 0.61%   |
| 5.4.0-29-generic         | 44        | 0.58%   |
| 4.18.0-15-generic        | 44        | 0.58%   |
| 5.3.0-40-generic         | 43        | 0.57%   |
| 5.4.0-65-generic         | 42        | 0.56%   |
| 5.4.0-39-generic         | 41        | 0.54%   |
| 5.0.0-37-generic         | 41        | 0.54%   |
| 5.4.0-80-generic         | 40        | 0.53%   |
| 5.4.0-70-generic         | 39        | 0.52%   |
| 5.15.0-46-generic        | 39        | 0.52%   |
| 5.0.0-25-generic         | 39        | 0.52%   |
| 5.13.0-30-generic        | 38        | 0.5%    |
| 5.11.0-7620-generic      | 38        | 0.5%    |
| 4.18.0-16-generic        | 38        | 0.5%    |
| 5.4.0-91-generic         | 37        | 0.49%   |
| 5.4.0-37-generic         | 37        | 0.49%   |
| 4.15.0-20-generic        | 37        | 0.49%   |
| 5.15.0-52-generic        | 36        | 0.48%   |
| 5.4.0-74-generic         | 35        | 0.46%   |
| 5.3.0-51-generic         | 35        | 0.46%   |
| 5.11.0-27-generic        | 35        | 0.46%   |
| 5.4.0-72-generic         | 34        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1821      | 25.46%  |
| 5.8.0   | 603       | 8.43%   |
| 5.3.0   | 534       | 7.47%   |
| 4.15.0  | 514       | 7.19%   |
| 5.11.0  | 416       | 5.82%   |
| 5.0.0   | 320       | 4.47%   |
| 5.15.0  | 298       | 4.17%   |
| 5.13.0  | 265       | 3.71%   |
| 4.18.0  | 231       | 3.23%   |
| 5.10.14 | 151       | 2.11%   |
| 5.16.7  | 128       | 1.79%   |
| 5.10.0  | 106       | 1.48%   |
| 4.19.0  | 101       | 1.41%   |
| 5.19.0  | 41        | 0.57%   |
| 5.17.5  | 34        | 0.48%   |
| 5.16.11 | 29        | 0.41%   |
| 5.7.9   | 26        | 0.36%   |
| 4.4.0   | 26        | 0.36%   |
| 5.14.0  | 23        | 0.32%   |
| 5.15.15 | 20        | 0.28%   |
| 5.15.5  | 19        | 0.27%   |
| 4.9.0   | 19        | 0.27%   |
| 5.9.16  | 17        | 0.24%   |
| 5.7.0   | 17        | 0.24%   |
| 5.6.19  | 16        | 0.22%   |
| 5.3.18  | 15        | 0.21%   |
| 5.16.19 | 15        | 0.21%   |
| 5.16.15 | 15        | 0.21%   |
| 5.11.12 | 15        | 0.21%   |
| 5.18.10 | 14        | 0.2%    |
| 5.9.11  | 13        | 0.18%   |
| 5.6.0   | 13        | 0.18%   |
| 5.15.8  | 13        | 0.18%   |
| 5.7.10  | 12        | 0.17%   |
| 5.13.13 | 12        | 0.17%   |
| 4.18.16 | 12        | 0.17%   |
| 5.8.18  | 11        | 0.15%   |
| 5.17.0  | 11        | 0.15%   |
| 5.15.23 | 11        | 0.15%   |
| 4.9.60  | 11        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1892      | 26.76%  |
| 5.8     | 672       | 9.5%    |
| 5.3     | 578       | 8.17%   |
| 4.15    | 514       | 7.27%   |
| 5.11    | 482       | 6.82%   |
| 5.15    | 446       | 6.31%   |
| 5.10    | 360       | 5.09%   |
| 5.0     | 345       | 4.88%   |
| 5.13    | 319       | 4.51%   |
| 5.16    | 251       | 3.55%   |
| 4.18    | 247       | 3.49%   |
| 4.19    | 118       | 1.67%   |
| 5.7     | 101       | 1.43%   |
| 5.17    | 93        | 1.32%   |
| 5.19    | 86        | 1.22%   |
| 5.14    | 79        | 1.12%   |
| 5.18    | 75        | 1.06%   |
| 5.6     | 68        | 0.96%   |
| 5.9     | 66        | 0.93%   |
| 5.12    | 61        | 0.86%   |
| 4.9     | 43        | 0.61%   |
| 6.0     | 37        | 0.52%   |
| 5.5     | 32        | 0.45%   |
| 4.4     | 29        | 0.41%   |
| 5.1     | 28        | 0.4%    |
| 5.2     | 15        | 0.21%   |
| 4.13    | 7         | 0.1%    |
| 4.20    | 5         | 0.07%   |
| 4.14    | 4         | 0.06%   |
| 4.10    | 4         | 0.06%   |
| 4.1     | 4         | 0.06%   |
| 3.10    | 3         | 0.04%   |
| 4.17    | 2         | 0.03%   |
| 6.1     | 1         | 0.01%   |
| 6       | 1         | 0.01%   |
| 4.8     | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 6279      | 97.33%  |
| i686   | 170       | 2.64%   |
| armv7l | 2         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3348      | 49.86%  |
| Unknown         | 968       | 14.42%  |
| KDE5            | 655       | 9.75%   |
| X-Cinnamon      | 519       | 7.73%   |
| XFCE            | 425       | 6.33%   |
| MATE            | 178       | 2.65%   |
| KDE             | 159       | 2.37%   |
| Cinnamon        | 126       | 1.88%   |
| LXQt            | 64        | 0.95%   |
| Pantheon        | 53        | 0.79%   |
| Unity           | 50        | 0.74%   |
| Deepin          | 38        | 0.57%   |
| Budgie          | 35        | 0.52%   |
| LXDE            | 29        | 0.43%   |
| KDE4            | 25        | 0.37%   |
| i3              | 18        | 0.27%   |
| GNOME Classic   | 8         | 0.12%   |
| awesome         | 5         | 0.07%   |
| GNOME Flashback | 3         | 0.04%   |
| sway            | 2         | 0.03%   |
| Enlightenment   | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Openbox         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5477      | 82.87%  |
| Wayland | 619       | 9.37%   |
| Unknown | 486       | 7.35%   |
| Tty     | 27        | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4422      | 66.21%  |
| GDM     | 714       | 10.69%  |
| SDDM    | 597       | 8.94%   |
| GDM3    | 319       | 4.78%   |
| LightDM | 300       | 4.49%   |
| TDM     | 292       | 4.37%   |
| KDM     | 26        | 0.39%   |
| XDM     | 4         | 0.06%   |
| SLiM    | 3         | 0.04%   |
| MDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_BR   | 4394      | 66.74%  |
| en_US   | 1109      | 16.84%  |
| Unknown | 910       | 13.82%  |
| C       | 87        | 1.32%   |
| en_GB   | 28        | 0.43%   |
| pt_PT   | 25        | 0.38%   |
| es_ES   | 9         | 0.14%   |
| POSIX   | 3         | 0.05%   |
| fr_FR   | 3         | 0.05%   |
| en_CA   | 3         | 0.05%   |
| de_DE   | 3         | 0.05%   |
| ja_JP   | 2         | 0.03%   |
| it_IT   | 2         | 0.03%   |
| ru_RU   | 1         | 0.02%   |
| es_MX   | 1         | 0.02%   |
| es_CL   | 1         | 0.02%   |
| es_AR   | 1         | 0.02%   |
| em_US   | 1         | 0.02%   |
| ar_EG   | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3332      | 50.46%  |
| EFI  | 3271      | 49.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5296      | 80.38%  |
| Overlay | 406       | 6.16%   |
| Btrfs   | 398       | 6.04%   |
| Unknown | 386       | 5.86%   |
| Xfs     | 40        | 0.61%   |
| Zfs     | 22        | 0.33%   |
| Tmpfs   | 15        | 0.23%   |
| Ext3    | 10        | 0.15%   |
| Ext2    | 10        | 0.15%   |
| F2fs    | 4         | 0.06%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4645      | 70.36%  |
| GPT     | 1383      | 20.95%  |
| MBR     | 574       | 8.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5929      | 91.06%  |
| Yes       | 582       | 8.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5104      | 78.08%  |
| Yes       | 1433      | 21.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1474      | 22.85%  |
| Acer                   | 1289      | 19.98%  |
| Lenovo                 | 795       | 12.33%  |
| Samsung Electronics    | 550       | 8.53%   |
| Hewlett-Packard        | 443       | 6.87%   |
| Positivo               | 431       | 6.68%   |
| ASUSTek Computer       | 347       | 5.38%   |
| Sony                   | 144       | 2.23%   |
| LG Electronics         | 89        | 1.38%   |
| Apple                  | 77        | 1.19%   |
| Avell High Performance | 66        | 1.02%   |
| Itautec                | 62        | 0.96%   |
| Digibras               | 62        | 0.96%   |
| Semp Toshiba           | 61        | 0.95%   |
| Unknown                | 58        | 0.9%    |
| Intel                  | 47        | 0.73%   |
| Philco                 | 36        | 0.56%   |
| Multilaser             | 34        | 0.53%   |
| Toshiba                | 33        | 0.51%   |
| Compaq                 | 33        | 0.51%   |
| Positivo Bahia - VAIO  | 32        | 0.5%    |
| OEM                    | 31        | 0.48%   |
| Notebook               | 24        | 0.37%   |
| Clevo                  | 21        | 0.33%   |
| Gateway                | 19        | 0.29%   |
| Compal                 | 18        | 0.28%   |
| MSI                    | 15        | 0.23%   |
| Google                 | 15        | 0.23%   |
| Alienware              | 11        | 0.17%   |
| Standard               | 10        | 0.16%   |
| Quanta                 | 10        | 0.16%   |
| eMachines              | 10        | 0.16%   |
| Timi                   | 7         | 0.11%   |
| Daten Tecnologia       | 7         | 0.11%   |
| CCE                    | 7         | 0.11%   |
| Chuwi                  | 6         | 0.09%   |
| Login Informatica      | 5         | 0.08%   |
| LNV                    | 5         | 0.08%   |
| TPVAOC                 | 4         | 0.06%   |
| IDEALMAX               | 4         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 132       | 2.05%   |
| Positivo Mobile                             | 115       | 1.78%   |
| Unknown                                     | 99        | 1.53%   |
| Acer Nitro AN515-44                         | 76        | 1.18%   |
| Acer Aspire A315-53                         | 67        | 1.04%   |
| Samsung 340XAA/350XAA/550XAA                | 65        | 1.01%   |
| Dell Inspiron 5566                          | 56        | 0.87%   |
| Lenovo IdeaPad S145-15API 81V7              | 55        | 0.85%   |
| Dell Inspiron 3583                          | 54        | 0.84%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 52        | 0.81%   |
| Acer Aspire A315-34                         | 52        | 0.81%   |
| Acer Nitro AN517-51                         | 50        | 0.78%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 49        | 0.76%   |
| Dell Inspiron 15-3567                       | 48        | 0.74%   |
| Acer Nitro AN515-43                         | 45        | 0.7%    |
| Acer Aspire A515-51                         | 44        | 0.68%   |
| HP G42                                      | 39        | 0.6%    |
| Samsung 300E5M/300E5L                       | 37        | 0.57%   |
| Positivo S14CT01                            | 37        | 0.57%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 36        | 0.56%   |
| Dell Inspiron 3442                          | 36        | 0.56%   |
| Acer Nitro AN515-52                         | 36        | 0.56%   |
| Dell Inspiron 3421                          | 35        | 0.54%   |
| Dell Inspiron 7520                          | 33        | 0.51%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 32        | 0.5%    |
| Dell Inspiron N4050                         | 32        | 0.5%    |
| Dell Inspiron 1545                          | 31        | 0.48%   |
| Acer Aspire E1-571                          | 31        | 0.48%   |
| HP Pavilion g4                              | 30        | 0.47%   |
| Samsung 550XDA                              | 28        | 0.43%   |
| Itautec Infoway                             | 28        | 0.43%   |
| Digibras NH4CU03                            | 28        | 0.43%   |
| Dell Inspiron 5458                          | 28        | 0.43%   |
| Dell Inspiron 5437                          | 28        | 0.43%   |
| Acer Aspire E5-571                          | 28        | 0.43%   |
| Digibras NH4CU53                            | 26        | 0.4%    |
| Dell Inspiron 1525                          | 26        | 0.4%    |
| Dell G3 3590                                | 26        | 0.4%    |
| Acer Aspire A515-51G                        | 26        | 0.4%    |
| Dell Inspiron 5423                          | 25        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 976       | 15.13%  |
| Acer Aspire       | 835       | 12.95%  |
| Lenovo IdeaPad    | 425       | 6.59%   |
| Acer Nitro        | 371       | 5.75%   |
| Dell Vostro       | 197       | 3.05%   |
| Lenovo ThinkPad   | 181       | 2.81%   |
| HP Pavilion       | 179       | 2.78%   |
| Dell Latitude     | 155       | 2.4%    |
| Positivo Mobile   | 115       | 1.78%   |
| Unknown           | 99        | 1.53%   |
| ASUS VivoBook     | 82        | 1.27%   |
| Samsung 340XAA    | 65        | 1.01%   |
| Itautec Infoway   | 62        | 0.96%   |
| Dell G3           | 49        | 0.76%   |
| Samsung RV411     | 45        | 0.7%    |
| HP ProBook        | 45        | 0.7%    |
| HP G42            | 39        | 0.6%    |
| Samsung 300E5M    | 37        | 0.57%   |
| Positivo S14CT01  | 37        | 0.57%   |
| Dell System       | 36        | 0.56%   |
| HP EliteBook      | 34        | 0.53%   |
| Semp Toshiba IS   | 30        | 0.47%   |
| Acer Predator     | 29        | 0.45%   |
| Samsung 550XDA    | 28        | 0.43%   |
| Digibras NH4CU03  | 28        | 0.43%   |
| Toshiba Satellite | 27        | 0.42%   |
| Compaq Presario   | 27        | 0.42%   |
| Digibras NH4CU53  | 26        | 0.4%    |
| Samsung RV415     | 23        | 0.36%   |
| Samsung 370E4K    | 23        | 0.36%   |
| Samsung 270E5J    | 23        | 0.36%   |
| Lenovo G400s      | 23        | 0.36%   |
| Samsung 550XBE    | 22        | 0.34%   |
| Positivo Q232A    | 22        | 0.34%   |
| Samsung 300E5EV   | 21        | 0.33%   |
| Samsung 300E4C    | 21        | 0.33%   |
| Positivo H14BT58  | 21        | 0.33%   |
| HP Compaq         | 21        | 0.33%   |
| Dell XPS          | 21        | 0.33%   |
| Positivo CHT14B   | 20        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 863       | 13.38%  |
| 2012    | 685       | 10.62%  |
| 2011    | 605       | 9.38%   |
| 2018    | 553       | 8.57%   |
| 2013    | 521       | 8.08%   |
| 2017    | 488       | 7.57%   |
| 2016    | 483       | 7.49%   |
| 2010    | 410       | 6.36%   |
| 2014    | 356       | 5.52%   |
| 2020    | 341       | 5.29%   |
| 2015    | 300       | 4.65%   |
| 2008    | 241       | 3.74%   |
| 2021    | 221       | 3.43%   |
| 2009    | 211       | 3.27%   |
| 2007    | 84        | 1.3%    |
| 2006    | 34        | 0.53%   |
| Unknown | 23        | 0.36%   |
| 2022    | 18        | 0.28%   |
| 2005    | 9         | 0.14%   |
| 2004    | 4         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6450      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5493      | 84.48%  |
| Enabled  | 1009      | 15.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6433      | 99.74%  |
| Yes  | 17        | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2141      | 32.77%  |
| 3.01-4.0    | 1829      | 27.99%  |
| 8.01-16.0   | 909       | 13.91%  |
| 16.01-24.0  | 808       | 12.37%  |
| 1.01-2.0    | 505       | 7.73%   |
| 2.01-3.0    | 165       | 2.53%   |
| 32.01-64.0  | 96        | 1.47%   |
| 0.51-1.0    | 32        | 0.49%   |
| 24.01-32.0  | 27        | 0.41%   |
| 64.01-256.0 | 21        | 0.32%   |
| 0.01-0.5    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2657      | 37.43%  |
| 2.01-3.0   | 1984      | 27.95%  |
| 3.01-4.0   | 939       | 13.23%  |
| 4.01-8.0   | 817       | 11.51%  |
| 0.51-1.0   | 505       | 7.11%   |
| 8.01-16.0  | 145       | 2.04%   |
| 0.01-0.5   | 40        | 0.56%   |
| 16.01-24.0 | 7         | 0.1%    |
| 32.01-64.0 | 2         | 0.03%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4598      | 70.11%  |
| 2      | 1772      | 27.02%  |
| 3      | 129       | 1.97%   |
| 0      | 48        | 0.73%   |
| 4      | 11        | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3897      | 60.13%  |
| Yes       | 2584      | 39.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5774      | 89.34%  |
| No        | 689       | 10.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6253      | 96.75%  |
| No        | 210       | 3.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4586      | 70.43%  |
| No        | 1925      | 29.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 6450      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 806       | 11.94%  |
| Rio de Janeiro        | 357       | 5.29%   |
| Brasília             | 216       | 3.2%    |
| Curitiba              | 200       | 2.96%   |
| Belo Horizonte        | 192       | 2.84%   |
| Fortaleza             | 156       | 2.31%   |
| Porto Alegre          | 135       | 2%      |
| Salvador              | 110       | 1.63%   |
| Recife                | 95        | 1.41%   |
| Campinas              | 95        | 1.41%   |
| Goiânia              | 78        | 1.16%   |
| Florianópolis        | 74        | 1.1%    |
| Santo André          | 73        | 1.08%   |
| Natal                 | 68        | 1.01%   |
| Sao Luís             | 56        | 0.83%   |
| Campo Grande          | 56        | 0.83%   |
| Manaus                | 54        | 0.8%    |
| Osasco                | 53        | 0.78%   |
| Sao José dos Campos  | 49        | 0.73%   |
| Teresina              | 47        | 0.7%    |
| Niterói              | 47        | 0.7%    |
| Belém                | 47        | 0.7%    |
| Maringá              | 46        | 0.68%   |
| Guarulhos             | 44        | 0.65%   |
| Sorocaba              | 43        | 0.64%   |
| Joao Pessoa           | 43        | 0.64%   |
| Joinville             | 41        | 0.61%   |
| Aracaju               | 41        | 0.61%   |
| Uberlândia           | 39        | 0.58%   |
| Ribeirao Preto        | 38        | 0.56%   |
| Maceió               | 36        | 0.53%   |
| Londrina              | 36        | 0.53%   |
| Sao Jose              | 35        | 0.52%   |
| Sao Carlos            | 30        | 0.44%   |
| Cuiabá               | 30        | 0.44%   |
| Canoas                | 30        | 0.44%   |
| Vitória              | 29        | 0.43%   |
| Juiz de Fora          | 29        | 0.43%   |
| Americana             | 27        | 0.4%    |
| Sao Bernardo do Campo | 25        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 1825      | 2214   | 22.9%   |
| Seagate                        | 1259      | 1497   | 15.8%   |
| Kingston                       | 744       | 894    | 9.34%   |
| Toshiba                        | 576       | 666    | 7.23%   |
| Samsung Electronics            | 574       | 732    | 7.2%    |
| SanDisk                        | 459       | 595    | 5.76%   |
| Unknown                        | 353       | 471    | 4.43%   |
| A-DATA Technology              | 302       | 380    | 3.79%   |
| Intel                          | 255       | 304    | 3.2%    |
| Hitachi                        | 185       | 225    | 2.32%   |
| Crucial                        | 136       | 184    | 1.71%   |
| China                          | 125       | 152    | 1.57%   |
| ADATA Technology               | 121       | 145    | 1.52%   |
| LITEON                         | 100       | 118    | 1.25%   |
| SK hynix                       | 97        | 124    | 1.22%   |
| HGST                           | 95        | 114    | 1.19%   |
| Silicon Motion                 | 57        | 67     | 0.72%   |
| KingSpec                       | 49        | 55     | 0.61%   |
| Fujitsu                        | 41        | 48     | 0.51%   |
| JMicron Technology             | 35        | 41     | 0.44%   |
| Lexar                          | 31        | 40     | 0.39%   |
| Apple                          | 31        | 38     | 0.39%   |
| Solid State Storage Technology | 30        | 39     | 0.38%   |
| Phison                         | 29        | 31     | 0.36%   |
| SSSTC                          | 27        | 28     | 0.34%   |
| KIOXIA                         | 25        | 29     | 0.31%   |
| Corsair                        | 24        | 24     | 0.3%    |
| Netac                          | 20        | 21     | 0.25%   |
| Realtek Semiconductor          | 19        | 25     | 0.24%   |
| PNY                            | 19        | 26     | 0.24%   |
| Unknown                        | 19        | 19     | 0.24%   |
| Solid State Storage            | 18        | 19     | 0.23%   |
| Smart                          | 17        | 19     | 0.21%   |
| Patriot                        | 15        | 18     | 0.19%   |
| Micron Technology              | 15        | 16     | 0.19%   |
| Hewlett-Packard                | 15        | 18     | 0.19%   |
| XPG                            | 14        | 17     | 0.18%   |
| LITEONIT                       | 13        | 19     | 0.16%   |
| KingDian                       | 13        | 19     | 0.16%   |
| Gigabyte Technology            | 13        | 17     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 454       | 5.54%   |
| Kingston SA400S37240G 240GB SSD     | 262       | 3.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 247       | 3.02%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 208       | 2.54%   |
| Kingston SA400S37480G 480GB SSD     | 132       | 1.61%   |
| Toshiba MQ01ABD100 1TB              | 130       | 1.59%   |
| Kingston SA400S37120G 120GB SSD     | 120       | 1.47%   |
| WDC WD10SPZX-24Z10 1TB              | 118       | 1.44%   |
| Unknown MMC Card  32GB              | 111       | 1.36%   |
| Intel NVMe SSD Drive 512GB          | 98        | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB      | 92        | 1.12%   |
| WDC WD10JPVX-22JC3T0 1TB            | 91        | 1.11%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 87        | 1.06%   |
| WDC WD10SPZX-75Z10T2 1TB            | 75        | 0.92%   |
| Samsung HM321HI 320GB               | 75        | 0.92%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.85%   |
| Seagate ST9500325AS 500GB           | 69        | 0.84%   |
| SanDisk NVMe SSD Drive 512GB        | 69        | 0.84%   |
| ADATA NVMe SSD Drive 256GB          | 67        | 0.82%   |
| Toshiba MQ04ABF100 1TB              | 65        | 0.79%   |
| SanDisk SSD PLUS 240GB              | 64        | 0.78%   |
| Kingston SV300S37A120G 120GB SSD    | 58        | 0.71%   |
| SanDisk SSD PLUS 120GB              | 56        | 0.68%   |
| WDC WD10JPVX-75JC3T0 1TB            | 55        | 0.67%   |
| Seagate Expansion 1TB               | 54        | 0.66%   |
| Toshiba MQ01ABF050 500GB            | 53        | 0.65%   |
| Seagate ST2000LM007-1R8174 2TB      | 51        | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 49        | 0.6%    |
| Seagate ST500LT012-9WS142 500GB     | 49        | 0.6%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 48        | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 47        | 0.57%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 42        | 0.51%   |
| WDC WD10JPCX-24UE4T0 1TB            | 42        | 0.51%   |
| Intel NVMe SSD Drive 256GB          | 40        | 0.49%   |
| WDC WD10SPZX-75Z10T1 1TB            | 39        | 0.48%   |
| Seagate ST1000LM014-1EJ164 1TB      | 39        | 0.48%   |
| Toshiba MQ01ABD050 500GB            | 38        | 0.46%   |
| SanDisk SDSSDA240G 240GB            | 36        | 0.44%   |
| Crucial CT240BX500SSD1 240GB        | 36        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB     | 35        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1641      | 1923   | 40.37%  |
| Seagate             | 1252      | 1487   | 30.8%   |
| Toshiba             | 545       | 630    | 13.41%  |
| Samsung Electronics | 266       | 306    | 6.54%   |
| Hitachi             | 185       | 225    | 4.55%   |
| HGST                | 95        | 114    | 2.34%   |
| Fujitsu             | 40        | 46     | 0.98%   |
| Unknown             | 17        | 20     | 0.42%   |
| Apple               | 11        | 14     | 0.27%   |
| SAGE                | 4         | 6      | 0.1%    |
| JMicron Technology  | 3         | 3      | 0.07%   |
| Maxtor 6            | 1         | 1      | 0.02%   |
| Maxtor              | 1         | 1      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 2      | 0.02%   |
| CLOVER              | 1         | 1      | 0.02%   |
| ASMT                | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 716       | 852    | 30.08%  |
| SanDisk             | 312       | 427    | 13.11%  |
| Samsung Electronics | 210       | 286    | 8.82%   |
| WDC                 | 181       | 220    | 7.61%   |
| A-DATA Technology   | 179       | 217    | 7.52%   |
| Crucial             | 129       | 174    | 5.42%   |
| China               | 125       | 152    | 5.25%   |
| LITEON              | 91        | 109    | 3.82%   |
| KingSpec            | 48        | 54     | 2.02%   |
| Lexar               | 30        | 39     | 1.26%   |
| JMicron Technology  | 27        | 33     | 1.13%   |
| Intel               | 22        | 26     | 0.92%   |
| PNY                 | 19        | 26     | 0.8%    |
| Netac               | 19        | 20     | 0.8%    |
| Corsair             | 19        | 19     | 0.8%    |
| Apple               | 19        | 22     | 0.8%    |
| Smart               | 17        | 19     | 0.71%   |
| Patriot             | 14        | 17     | 0.59%   |
| Unknown             | 13        | 14     | 0.55%   |
| SK hynix            | 13        | 16     | 0.55%   |
| LITEONIT            | 13        | 19     | 0.55%   |
| KingDian            | 12        | 18     | 0.5%    |
| Gigabyte Technology | 12        | 16     | 0.5%    |
| Unknown             | 12        | 12     | 0.5%    |
| Hewlett-Packard     | 11        | 13     | 0.46%   |
| Toshiba             | 8         | 9      | 0.34%   |
| Micron Technology   | 8         | 9      | 0.34%   |
| Seagate             | 7         | 7      | 0.29%   |
| BHT                 | 6         | 6      | 0.25%   |
| BIWIN               | 5         | 5      | 0.21%   |
| XrayDisk            | 4         | 5      | 0.17%   |
| Win Memory          | 4         | 5      | 0.17%   |
| S3+                 | 4         | 4      | 0.17%   |
| Maxtor              | 4         | 4      | 0.17%   |
| WALRAM              | 3         | 3      | 0.13%   |
| Vaseky              | 3         | 3      | 0.13%   |
| Transcend           | 3         | 3      | 0.13%   |
| RZX                 | 3         | 4      | 0.13%   |
| Plextor             | 3         | 3      | 0.13%   |
| OCZ                 | 3         | 3      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3997      | 4781   | 51.69%  |
| SSD     | 2220      | 2948   | 28.71%  |
| NVMe    | 1172      | 1508   | 15.16%  |
| MMC     | 284       | 400    | 3.67%   |
| Unknown | 59        | 70     | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5503      | 7601   | 77.37%  |
| NVMe | 1171      | 1507   | 16.46%  |
| MMC  | 284       | 400    | 3.99%   |
| SAS  | 155       | 199    | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3865      | 5054   | 63.77%  |
| 0.51-1.0   | 2083      | 2538   | 34.37%  |
| 1.01-2.0   | 105       | 128    | 1.73%   |
| 4.01-10.0  | 5         | 6      | 0.08%   |
| 3.01-4.0   | 2         | 2      | 0.03%   |
| 2.01-3.0   | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2016      | 29.84%  |
| 251-500        | 1739      | 25.74%  |
| 501-1000       | 1237      | 18.31%  |
| 1-20           | 462       | 6.84%   |
| 51-100         | 413       | 6.11%   |
| 1001-2000      | 354       | 5.24%   |
| 21-50          | 337       | 4.99%   |
| Unknown        | 92        | 1.36%   |
| 2001-3000      | 60        | 0.89%   |
| More than 3000 | 47        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2680      | 38.21%  |
| 21-50          | 1670      | 23.81%  |
| 51-100         | 928       | 13.23%  |
| 101-250        | 907       | 12.93%  |
| 251-500        | 442       | 6.3%    |
| 501-1000       | 207       | 2.95%   |
| Unknown        | 92        | 1.31%   |
| 1001-2000      | 71        | 1.01%   |
| 2001-3000      | 9         | 0.13%   |
| More than 3000 | 7         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 29        | 31     | 6.92%   |
| Seagate ST9500325AS 500GB           | 19        | 21     | 4.53%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 16        | 18     | 3.82%   |
| Toshiba MQ01ABD100 1TB              | 11        | 11     | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 11        | 11     | 2.63%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 11     | 2.15%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.67%   |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.43%   |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 1.43%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 1.43%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 7      | 1.43%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 5      | 1.19%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 1.19%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 1.19%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 1.19%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 1.19%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 5      | 1.19%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 1.19%   |
| WDC WD10JPCX-24UE4T0 1TB            | 4         | 4      | 0.95%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 4      | 0.95%   |
| Seagate ST1000LM014-1EJ164 1TB      | 4         | 4      | 0.95%   |
| SanDisk SSD PLUS 480GB              | 4         | 4      | 0.95%   |
| Samsung Electronics HM160HI 160GB   | 4         | 4      | 0.95%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.72%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 3         | 3      | 0.72%   |
| WDC WD3200BPVT-00JJ5T0 320GB        | 3         | 5      | 0.72%   |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 4      | 0.72%   |
| WDC WD10SPZX-24Z10 1TB              | 3         | 3      | 0.72%   |
| Toshiba MQ01ACF050 500GB            | 3         | 3      | 0.72%   |
| Toshiba MQ01ABD032 320GB            | 3         | 3      | 0.72%   |
| Toshiba MK5061GSYN 500GB            | 3         | 3      | 0.72%   |
| Toshiba MK3259GSXP 320GB            | 3         | 3      | 0.72%   |
| Seagate ST9500423AS 500GB           | 3         | 3      | 0.72%   |
| Seagate ST9320423AS 320GB           | 3         | 3      | 0.72%   |
| Seagate ST9250410AS 250GB           | 3         | 3      | 0.72%   |
| Seagate ST9160314AS 160GB           | 3         | 4      | 0.72%   |
| Seagate ST500LM030-2E717D 500GB     | 3         | 3      | 0.72%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 3         | 3      | 0.72%   |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.72%   |
| Samsung Electronics HM250HI 250GB   | 3         | 3      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 157    | 34.94%  |
| WDC                 | 75        | 84     | 18.07%  |
| Toshiba             | 67        | 73     | 16.14%  |
| Hitachi             | 27        | 29     | 6.51%   |
| Samsung Electronics | 25        | 33     | 6.02%   |
| Kingston            | 21        | 25     | 5.06%   |
| SanDisk             | 11        | 11     | 2.65%   |
| China               | 8         | 9      | 1.93%   |
| HGST                | 6         | 6      | 1.45%   |
| A-DATA Technology   | 6         | 6      | 1.45%   |
| Fujitsu             | 4         | 5      | 0.96%   |
| PNY                 | 3         | 5      | 0.72%   |
| Intel               | 3         | 3      | 0.72%   |
| WALRAM              | 2         | 2      | 0.48%   |
| LITEON              | 2         | 2      | 0.48%   |
| Crucial             | 2         | 2      | 0.48%   |
| Apple               | 2         | 2      | 0.48%   |
| XPG                 | 1         | 1      | 0.24%   |
| SK hynix            | 1         | 1      | 0.24%   |
| ShiJi               | 1         | 1      | 0.24%   |
| OCZ                 | 1         | 1      | 0.24%   |
| Micron Technology   | 1         | 1      | 0.24%   |
| LITEONIT            | 1         | 2      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 157    | 42.65%  |
| WDC                 | 70        | 79     | 20.59%  |
| Toshiba             | 66        | 72     | 19.41%  |
| Hitachi             | 27        | 29     | 7.94%   |
| Samsung Electronics | 21        | 29     | 6.18%   |
| HGST                | 6         | 6      | 1.76%   |
| Fujitsu             | 4         | 5      | 1.18%   |
| Apple               | 1         | 1      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 339       | 378    | 81.88%  |
| SSD  | 66        | 74     | 15.94%  |
| NVMe | 9         | 9      | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 18.18%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 9.09%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 9.09%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 9.09%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 9.09%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 36.36%  |
| WDC                 | 2         | 2      | 18.18%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Maxtor              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4774      | 7120   | 71.03%  |
| Works    | 1528      | 2115   | 22.73%  |
| Malfunc  | 408       | 461    | 6.07%   |
| Failed   | 11        | 11     | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5402      | 75.82%  |
| AMD                              | 584       | 8.2%    |
| ADATA Technology                 | 256       | 3.59%   |
| SanDisk                          | 175       | 2.46%   |
| Samsung Electronics              | 119       | 1.67%   |
| Silicon Integrated Systems [SiS] | 94        | 1.32%   |
| Solid State Storage Technology   | 87        | 1.22%   |
| SK hynix                         | 79        | 1.11%   |
| Silicon Motion                   | 65        | 0.91%   |
| Phison Electronics               | 36        | 0.51%   |
| Kingston Technology Company      | 32        | 0.45%   |
| Realtek Semiconductor            | 31        | 0.44%   |
| Nvidia                           | 31        | 0.44%   |
| VIA Technologies                 | 24        | 0.34%   |
| KIOXIA                           | 24        | 0.34%   |
| Toshiba America Info Systems     | 22        | 0.31%   |
| Micron/Crucial Technology        | 18        | 0.25%   |
| Lite-On Technology               | 18        | 0.25%   |
| Micron Technology                | 7         | 0.1%    |
| Union Memory (Shenzhen)          | 5         | 0.07%   |
| Marvell Technology Group         | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.04%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Apple                            | 2         | 0.03%   |
| Seagate Technology               | 1         | 0.01%   |
| Netac Technology                 | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 898       | 11.42%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 748       | 9.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 582       | 7.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 417       | 5.3%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 412       | 5.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 355       | 4.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 291       | 3.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 287       | 3.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 224       | 2.85%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 199       | 2.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 185       | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 135       | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 130       | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 125       | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 114       | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 114       | 1.45%   |
| ADATA Non-Volatile memory controller                                             | 114       | 1.45%   |
| Intel Comet Lake SATA AHCI Controller                                            | 112       | 1.42%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                      | 109       | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 107       | 1.36%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 93        | 1.18%   |
| Solid State Storage Non-Volatile memory controller                               | 87        | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                              | 86        | 1.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 86        | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 84        | 1.07%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 77        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 70        | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 69        | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                              | 69        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 67        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 62        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 62        | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 59        | 0.75%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 55        | 0.7%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 55        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 44        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 42        | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 42        | 0.53%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 41        | 0.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 33        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5248      | 69.38%  |
| NVMe | 1176      | 15.55%  |
| RAID | 607       | 8.02%   |
| IDE  | 533       | 7.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 5823      | 90.28%  |
| AMD    | 625       | 9.69%   |
| ARM    | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 226       | 3.5%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 158       | 2.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 138       | 2.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 122       | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 121       | 1.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 118       | 1.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 118       | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 112       | 1.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 111       | 1.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 106       | 1.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 89        | 1.38%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 88        | 1.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 85        | 1.32%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 85        | 1.32%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 82        | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 80        | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 78        | 1.21%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 78        | 1.21%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 75        | 1.16%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 72        | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 71        | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 71        | 1.1%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 70        | 1.09%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 70        | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 69        | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 67        | 1.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 62        | 0.96%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 61        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 60        | 0.93%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 60        | 0.93%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 58        | 0.9%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 56        | 0.87%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 55        | 0.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 55        | 0.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 53        | 0.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 53        | 0.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 51        | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 50        | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 48        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 46        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 1929      | 29.9%   |
| Intel Core i7                  | 1335      | 20.69%  |
| Intel Core i3                  | 1013      | 15.7%   |
| Intel Celeron                  | 483       | 7.49%   |
| Intel Core 2 Duo               | 249       | 3.86%   |
| Intel Atom                     | 230       | 3.57%   |
| Other                          | 174       | 2.7%    |
| AMD Ryzen 5                    | 147       | 2.28%   |
| AMD Ryzen 7                    | 138       | 2.14%   |
| Intel Pentium Dual-Core        | 132       | 2.05%   |
| Intel Pentium                  | 126       | 1.95%   |
| Intel Pentium Dual             | 70        | 1.09%   |
| AMD E                          | 46        | 0.71%   |
| AMD C-60                       | 37        | 0.57%   |
| AMD E1                         | 31        | 0.48%   |
| AMD A4                         | 27        | 0.42%   |
| Intel Genuine                  | 26        | 0.4%    |
| AMD A6                         | 23        | 0.36%   |
| AMD C-70                       | 21        | 0.33%   |
| AMD A10                        | 20        | 0.31%   |
| Intel Core 2                   | 18        | 0.28%   |
| Intel Celeron Dual-Core        | 15        | 0.23%   |
| AMD C-50                       | 15        | 0.23%   |
| AMD Ryzen 3                    | 12        | 0.19%   |
| AMD Mobile Sempron             | 12        | 0.19%   |
| Intel Celeron M                | 11        | 0.17%   |
| AMD A12                        | 11        | 0.17%   |
| AMD Athlon II                  | 9         | 0.14%   |
| AMD Ryzen 9                    | 7         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.09%   |
| AMD Turion 64 Mobile           | 6         | 0.09%   |
| AMD Turion II                  | 5         | 0.08%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.08%   |
| AMD Phenom II                  | 5         | 0.08%   |
| Intel Pentium M                | 4         | 0.06%   |
| Intel Pentium Gold             | 4         | 0.06%   |
| AMD Ryzen 7 PRO                | 4         | 0.06%   |
| AMD Athlon 64 X2               | 4         | 0.06%   |
| AMD A8                         | 4         | 0.06%   |
| AMD V120                       | 3         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4158      | 64.45%  |
| 4       | 1784      | 27.65%  |
| 6       | 244       | 3.78%   |
| 1       | 142       | 2.2%    |
| 8       | 110       | 1.7%    |
| 14      | 4         | 0.06%   |
| Unknown | 3         | 0.05%   |
| 10      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 3       | 2         | 0.03%   |
| 12      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6450      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4838      | 74.97%  |
| 1       | 1611      | 24.97%  |
| Unknown | 3         | 0.05%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6133      | 94.54%  |
| Unknown        | 295       | 4.55%   |
| 32-bit         | 44        | 0.68%   |
| 64-bit         | 15        | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1184      | 17.76%  |
| 0x306a9    | 571       | 8.56%   |
| 0x206a7    | 553       | 8.29%   |
| 0x806e9    | 356       | 5.34%   |
| 0x40651    | 321       | 4.81%   |
| 0x806ec    | 297       | 4.45%   |
| 0x906ea    | 285       | 4.27%   |
| 0x20655    | 282       | 4.23%   |
| 0x306d4    | 261       | 3.91%   |
| 0x406e3    | 258       | 3.87%   |
| 0x1067a    | 246       | 3.69%   |
| 0x806ea    | 240       | 3.6%    |
| 0x406c4    | 140       | 2.1%    |
| 0x6fd      | 138       | 2.07%   |
| 0x806c1    | 123       | 1.84%   |
| 0x05000119 | 84        | 1.26%   |
| 0x906e9    | 81        | 1.21%   |
| 0x30678    | 79        | 1.18%   |
| 0x08600103 | 76        | 1.14%   |
| 0x08108109 | 64        | 0.96%   |
| 0x706e5    | 58        | 0.87%   |
| 0x08108102 | 57        | 0.85%   |
| 0x906ed    | 56        | 0.84%   |
| 0x706a1    | 56        | 0.84%   |
| 0x306c3    | 53        | 0.79%   |
| 0x406c3    | 47        | 0.7%    |
| 0x20652    | 47        | 0.7%    |
| 0x806eb    | 45        | 0.67%   |
| 0x106ca    | 44        | 0.66%   |
| 0xa0652    | 42        | 0.63%   |
| 0x706a8    | 41        | 0.61%   |
| 0x10676    | 32        | 0.48%   |
| 0x30661    | 31        | 0.46%   |
| 0x506c9    | 27        | 0.4%    |
| 0x05000029 | 27        | 0.4%    |
| 0x03000027 | 26        | 0.39%   |
| 0x506e3    | 24        | 0.36%   |
| 0x10661    | 24        | 0.36%   |
| 0x0810100b | 21        | 0.31%   |
| 0x0700010f | 19        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1610      | 24.96%  |
| IvyBridge        | 675       | 10.46%  |
| SandyBridge      | 639       | 9.91%   |
| Haswell          | 439       | 6.81%   |
| Westmere         | 386       | 5.98%   |
| Skylake          | 327       | 5.07%   |
| Penryn           | 325       | 5.04%   |
| Silvermont       | 318       | 4.93%   |
| Broadwell        | 301       | 4.67%   |
| Core             | 213       | 3.3%    |
| Zen+             | 155       | 2.4%    |
| TigerLake        | 154       | 2.39%   |
| Bobcat           | 139       | 2.15%   |
| Goldmont plus    | 108       | 1.67%   |
| Bonnell          | 92        | 1.43%   |
| Zen 2            | 84        | 1.3%    |
| IceLake          | 80        | 1.24%   |
| CometLake        | 69        | 1.07%   |
| Unknown          | 43        | 0.67%   |
| K8 Hammer        | 39        | 0.6%    |
| Excavator        | 36        | 0.56%   |
| Goldmont         | 33        | 0.51%   |
| K10 Llano        | 30        | 0.47%   |
| Zen              | 29        | 0.45%   |
| K10              | 27        | 0.42%   |
| P6               | 24        | 0.37%   |
| Jaguar           | 21        | 0.33%   |
| Zen 3            | 14        | 0.22%   |
| Nehalem          | 12        | 0.19%   |
| K8 & K10 hybrid  | 10        | 0.16%   |
| Piledriver       | 8         | 0.12%   |
| Puma             | 4         | 0.06%   |
| Alderlake Hybrid | 4         | 0.06%   |
| Steamroller      | 2         | 0.03%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5573      | 66.42%  |
| Nvidia                           | 1695      | 20.2%   |
| AMD                              | 1004      | 11.97%  |
| Silicon Integrated Systems [SiS] | 94        | 1.12%   |
| VIA Technologies                 | 24        | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 667       | 7.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 628       | 7.29%   |
| Intel HD Graphics 620                                                                    | 444       | 5.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 372       | 4.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 362       | 4.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 357       | 4.14%   |
| Intel HD Graphics 5500                                                                   | 283       | 3.28%   |
| Intel UHD Graphics 620                                                                   | 272       | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 268       | 3.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 257       | 2.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 249       | 2.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 237       | 2.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 223       | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 154       | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 150       | 1.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 137       | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 132       | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 127       | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 127       | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 108       | 1.25%   |
| Intel HD Graphics 630                                                                    | 96        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 95        | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 92        | 1.07%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 91        | 1.06%   |
| Nvidia TU117M                                                                            | 89        | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 86        | 1%      |
| AMD Renoir                                                                               | 83        | 0.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 82        | 0.95%   |
| Nvidia GM108M [GeForce MX110]                                                            | 81        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 65        | 0.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 64        | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 61        | 0.71%   |
| Nvidia GP108M [GeForce MX250]                                                            | 51        | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 50        | 0.58%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 48        | 0.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 42        | 0.49%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 42        | 0.49%   |
| Nvidia GP108M [GeForce MX230]                                                            | 40        | 0.46%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 39        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3771      | 58.37%  |
| Intel + Nvidia | 1444      | 22.35%  |
| 1 x AMD        | 441       | 6.83%   |
| Intel + AMD    | 362       | 5.6%    |
| AMD + Nvidia   | 133       | 2.06%   |
| 1 x Nvidia     | 117       | 1.81%   |
| 1 x SiS        | 94        | 1.46%   |
| 2 x AMD        | 67        | 1.04%   |
| 1 x VIA        | 24        | 0.37%   |
| Other          | 4         | 0.06%   |
| 2 x Intel      | 3         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5247      | 80.64%  |
| Proprietary | 1063      | 16.34%  |
| Unknown     | 197       | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4535      | 68.94%  |
| 1.01-2.0   | 958       | 14.56%  |
| 0.01-0.5   | 479       | 7.28%   |
| 3.01-4.0   | 353       | 5.37%   |
| 0.51-1.0   | 165       | 2.51%   |
| 5.01-6.0   | 62        | 0.94%   |
| 2.01-3.0   | 15        | 0.23%   |
| 7.01-8.0   | 10        | 0.15%   |
| 8.01-16.0  | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1420      | 19.23%  |
| BOE                     | 1338      | 18.12%  |
| Chimei Innolux          | 1054      | 14.27%  |
| LG Display              | 1039      | 14.07%  |
| Samsung Electronics     | 764       | 10.35%  |
| Goldstar                | 388       | 5.25%   |
| AOC                     | 150       | 2.03%   |
| Dell                    | 144       | 1.95%   |
| Chi Mei Optoelectronics | 142       | 1.92%   |
| InfoVision              | 113       | 1.53%   |
| PANDA                   | 103       | 1.39%   |
| Philips                 | 86        | 1.16%   |
| Apple                   | 75        | 1.02%   |
| Lenovo                  | 56        | 0.76%   |
| HannStar                | 47        | 0.64%   |
| CPT                     | 46        | 0.62%   |
| Acer                    | 43        | 0.58%   |
| LG Philips              | 33        | 0.45%   |
| Sony                    | 31        | 0.42%   |
| InnoLux Display         | 28        | 0.38%   |
| Hewlett-Packard         | 28        | 0.38%   |
| Sharp                   | 21        | 0.28%   |
| SLD                     | 20        | 0.27%   |
| MTD                     | 17        | 0.23%   |
| Panasonic               | 13        | 0.18%   |
| KDC                     | 11        | 0.15%   |
| BenQ                    | 10        | 0.14%   |
| Toshiba                 | 9         | 0.12%   |
| SKY                     | 9         | 0.12%   |
| Unknown                 | 8         | 0.11%   |
| ASUSTek Computer        | 8         | 0.11%   |
| STA                     | 7         | 0.09%   |
| GDH                     | 7         | 0.09%   |
| RTK                     | 6         | 0.08%   |
| NCS                     | 6         | 0.08%   |
| MStar                   | 6         | 0.08%   |
| HB@                     | 6         | 0.08%   |
| AGO                     | 6         | 0.08%   |
| Unknown (XXX)           | 5         | 0.07%   |
| Quanta Display          | 5         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 111       | 1.49%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 103       | 1.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 100       | 1.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 98        | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 96        | 1.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 95        | 1.28%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 95        | 1.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 91        | 1.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 78        | 1.05%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 73        | 0.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 71        | 0.96%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 64        | 0.86%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 64        | 0.86%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.83%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 61        | 0.82%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 56        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 55        | 0.74%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.73%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 54        | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 54        | 0.73%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 53        | 0.71%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 53        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 50        | 0.67%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 49        | 0.66%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 49        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 47        | 0.63%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.59%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 43        | 0.58%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 41        | 0.55%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 40        | 0.54%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 39        | 0.53%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 39        | 0.53%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 38        | 0.51%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 38        | 0.51%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 37        | 0.5%    |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 36        | 0.48%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch         | 35        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 35        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 35        | 0.47%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 33        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3926      | 55.69%  |
| 1920x1080 (FHD)    | 2035      | 28.87%  |
| 1280x800 (WXGA)    | 274       | 3.89%   |
| 1600x900 (HD+)     | 157       | 2.23%   |
| 2560x1080          | 140       | 1.99%   |
| 3840x2160 (4K)     | 91        | 1.29%   |
| 1440x900 (WXGA+)   | 86        | 1.22%   |
| 1360x768           | 65        | 0.92%   |
| 1920x1200 (WUXGA)  | 43        | 0.61%   |
| 1024x600           | 39        | 0.55%   |
| 2560x1440 (QHD)    | 38        | 0.54%   |
| 1680x1050 (WSXGA+) | 28        | 0.4%    |
| 1280x1024 (SXGA)   | 28        | 0.4%    |
| 1024x768 (XGA)     | 21        | 0.3%    |
| 1920x540           | 14        | 0.2%    |
| 1280x720 (HD)      | 10        | 0.14%   |
| 2560x1600          | 8         | 0.11%   |
| 2288x1287          | 8         | 0.11%   |
| Unknown            | 7         | 0.1%    |
| 3840x2400          | 3         | 0.04%   |
| 3840x1080          | 3         | 0.04%   |
| 3200x1800 (QHD+)   | 3         | 0.04%   |
| 2880x1800          | 3         | 0.04%   |
| 1280x960           | 3         | 0.04%   |
| 4240x1080          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3440x1440          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |
| 2256x1504          | 1         | 0.01%   |
| 2160x1440          | 1         | 0.01%   |
| 1792x768           | 1         | 0.01%   |
| 1680x945           | 1         | 0.01%   |
| 1600x1200          | 1         | 0.01%   |
| 1360x765           | 1         | 0.01%   |
| 1280x768           | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3187      | 43.23%  |
| 14      | 1394      | 18.91%  |
| 13      | 1193      | 16.18%  |
| 21      | 216       | 2.93%   |
| 23      | 196       | 2.66%   |
| 17      | 162       | 2.2%    |
| 18      | 152       | 2.06%   |
| 34      | 131       | 1.78%   |
| 11      | 105       | 1.42%   |
| 24      | 95        | 1.29%   |
| 27      | 83        | 1.13%   |
| 31      | 52        | 0.71%   |
| 12      | 50        | 0.68%   |
| Unknown | 45        | 0.61%   |
| 10      | 44        | 0.6%    |
| 20      | 43        | 0.58%   |
| 19      | 41        | 0.56%   |
| 40      | 24        | 0.33%   |
| 72      | 18        | 0.24%   |
| 32      | 18        | 0.24%   |
| 22      | 16        | 0.22%   |
| 54      | 14        | 0.19%   |
| 52      | 14        | 0.19%   |
| 28      | 14        | 0.19%   |
| 84      | 13        | 0.18%   |
| 16      | 13        | 0.18%   |
| 47      | 8         | 0.11%   |
| 46      | 6         | 0.08%   |
| 37      | 5         | 0.07%   |
| 26      | 4         | 0.05%   |
| 58      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 65      | 2         | 0.03%   |
| 142     | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 55      | 1         | 0.01%   |
| 49      | 1         | 0.01%   |
| 42      | 1         | 0.01%   |
| 41      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5483      | 74.97%  |
| 401-500        | 461       | 6.3%    |
| 201-300        | 369       | 5.05%   |
| 501-600        | 360       | 4.92%   |
| 351-400        | 256       | 3.5%    |
| 701-800        | 149       | 2.04%   |
| 601-700        | 73        | 1%      |
| 1001-1500      | 54        | 0.74%   |
| Unknown        | 45        | 0.62%   |
| 1501-2000      | 31        | 0.42%   |
| 801-900        | 30        | 0.41%   |
| 901-1000       | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5775      | 89.11%  |
| 16/10   | 460       | 7.1%    |
| 21/9    | 142       | 2.19%   |
| 4/3     | 38        | 0.59%   |
| 5/4     | 29        | 0.45%   |
| Unknown | 21        | 0.32%   |
| 3/2     | 13        | 0.2%    |
| 32/9    | 2         | 0.03%   |
| 1.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3169      | 43.04%  |
| 81-90          | 2455      | 33.34%  |
| 201-250        | 448       | 6.08%   |
| 351-500        | 204       | 2.77%   |
| 151-200        | 160       | 2.17%   |
| 141-150        | 153       | 2.08%   |
| 71-80          | 127       | 1.72%   |
| 121-130        | 117       | 1.59%   |
| 51-60          | 105       | 1.43%   |
| 301-350        | 84        | 1.14%   |
| More than 1000 | 70        | 0.95%   |
| 501-1000       | 48        | 0.65%   |
| Unknown        | 45        | 0.61%   |
| 41-50          | 44        | 0.6%    |
| 61-70          | 38        | 0.52%   |
| 91-100         | 33        | 0.45%   |
| 251-300        | 29        | 0.39%   |
| 131-140        | 24        | 0.33%   |
| 111-120        | 10        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4033      | 56.08%  |
| 121-160       | 1803      | 25.07%  |
| 51-100        | 1090      | 15.16%  |
| 1-50          | 107       | 1.49%   |
| 161-240       | 96        | 1.33%   |
| Unknown       | 45        | 0.63%   |
| More than 240 | 18        | 0.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5210      | 78.8%   |
| 2     | 1155      | 17.47%  |
| 0     | 188       | 2.84%   |
| 3     | 57        | 0.86%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4700      | 41.43%  |
| Qualcomm Atheros                  | 2908      | 25.63%  |
| Intel                             | 1992      | 17.56%  |
| Broadcom                          | 630       | 5.55%   |
| JMicron Technology                | 177       | 1.56%   |
| Marvell Technology Group          | 174       | 1.53%   |
| Broadcom Limited                  | 138       | 1.22%   |
| Ralink                            | 121       | 1.07%   |
| Silicon Integrated Systems [SiS]  | 94        | 0.83%   |
| Ralink Technology                 | 79        | 0.7%    |
| TP-Link                           | 51        | 0.45%   |
| Samsung Electronics               | 42        | 0.37%   |
| Motorola PCS                      | 30        | 0.26%   |
| VIA Technologies                  | 24        | 0.21%   |
| ASIX Electronics                  | 24        | 0.21%   |
| Qualcomm Atheros Communications   | 22        | 0.19%   |
| Nvidia                            | 22        | 0.19%   |
| Xiaomi                            | 20        | 0.18%   |
| D-Link                            | 14        | 0.12%   |
| MediaTek                          | 10        | 0.09%   |
| ICS Advent                        | 10        | 0.09%   |
| D-Link System                     | 7         | 0.06%   |
| DisplayLink                       | 6         | 0.05%   |
| Lenovo                            | 4         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |
| LG Electronics                    | 3         | 0.03%   |
| Huawei Technologies               | 3         | 0.03%   |
| Ericsson Business Mobile Networks | 3         | 0.03%   |
| Dell                              | 3         | 0.03%   |
| AMD                               | 3         | 0.03%   |
| OPPO Electronics                  | 2         | 0.02%   |
| NetGear                           | 2         | 0.02%   |
| Microsoft                         | 2         | 0.02%   |
| Micro Star International          | 2         | 0.02%   |
| Edimax Technology                 | 2         | 0.02%   |
| ASUSTek Computer                  | 2         | 0.02%   |
| Arduino SA                        | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| Sierra Wireless                   | 1         | 0.01%   |
| Qualcomm                          | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2767      | 22.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1297      | 10.43%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 771       | 6.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 691       | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 546       | 4.39%   |
| Intel Wi-Fi 6 AX200                                               | 294       | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 279       | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 276       | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 272       | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 200       | 1.61%   |
| Intel Wireless 7265                                               | 151       | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 148       | 1.19%   |
| Intel Wi-Fi 6 AX201                                               | 144       | 1.16%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 130       | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 122       | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 104       | 0.84%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 98        | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 94        | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 92        | 0.74%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 91        | 0.73%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 89        | 0.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80        | 0.64%   |
| Intel Wireless 3165                                               | 79        | 0.64%   |
| Intel Wireless 7260                                               | 78        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 75        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 74        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 74        | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 74        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 70        | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 66        | 0.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 61        | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 60        | 0.48%   |
| Intel Centrino Advanced-N 6235                                    | 59        | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 56        | 0.45%   |
| Intel Wireless 3160                                               | 55        | 0.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 54        | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 54        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 54        | 0.43%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 54        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 53        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2737      | 42.3%   |
| Intel                                 | 1944      | 30.04%  |
| Realtek Semiconductor                 | 940       | 14.53%  |
| Broadcom                              | 452       | 6.99%   |
| Ralink                                | 121       | 1.87%   |
| Broadcom Limited                      | 89        | 1.38%   |
| Ralink Technology                     | 79        | 1.22%   |
| TP-Link                               | 41        | 0.63%   |
| Qualcomm Atheros Communications       | 22        | 0.34%   |
| D-Link                                | 14        | 0.22%   |
| MediaTek                              | 8         | 0.12%   |
| D-Link System                         | 7         | 0.11%   |
| NetGear                               | 2         | 0.03%   |
| Microsoft                             | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Edimax Technology                     | 2         | 0.03%   |
| Dell                                  | 2         | 0.03%   |
| Sierra Wireless                       | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Pegatron                              | 1         | 0.02%   |
| Mercucys                              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 771       | 11.86%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 691       | 10.63%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 546       | 8.4%    |
| Intel Wi-Fi 6 AX200                                                     | 294       | 4.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 279       | 4.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 276       | 4.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 272       | 4.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 200       | 3.08%   |
| Intel Wireless 7265                                                     | 151       | 2.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 148       | 2.28%   |
| Intel Wi-Fi 6 AX201                                                     | 144       | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 122       | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 104       | 1.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 98        | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 92        | 1.41%   |
| Intel Wireless 3165                                                     | 79        | 1.21%   |
| Intel Wireless 7260                                                     | 78        | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 75        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 74        | 1.14%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 74        | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 61        | 0.94%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 60        | 0.92%   |
| Intel Centrino Advanced-N 6235                                          | 59        | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 56        | 0.86%   |
| Intel Wireless 3160                                                     | 55        | 0.85%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 54        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 54        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 54        | 0.83%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 49        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                         | 48        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 48        | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 46        | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.71%   |
| Intel Wireless 8265 / 8275                                              | 45        | 0.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 44        | 0.68%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 43        | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 40        | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 0.58%   |
| Intel WiFi Link 5100                                                    | 37        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                           | 35        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4249      | 72.4%   |
| Qualcomm Atheros                 | 387       | 6.59%   |
| Intel                            | 292       | 4.98%   |
| Broadcom                         | 244       | 4.16%   |
| JMicron Technology               | 177       | 3.02%   |
| Marvell Technology Group         | 174       | 2.96%   |
| Silicon Integrated Systems [SiS] | 94        | 1.6%    |
| Broadcom Limited                 | 55        | 0.94%   |
| Samsung Electronics              | 42        | 0.72%   |
| VIA Technologies                 | 24        | 0.41%   |
| ASIX Electronics                 | 24        | 0.41%   |
| Motorola PCS                     | 23        | 0.39%   |
| Nvidia                           | 21        | 0.36%   |
| Xiaomi                           | 20        | 0.34%   |
| TP-Link                          | 10        | 0.17%   |
| ICS Advent                       | 10        | 0.17%   |
| DisplayLink                      | 6         | 0.1%    |
| Lenovo                           | 4         | 0.07%   |
| Attansic Technology              | 4         | 0.07%   |
| OPPO Electronics                 | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| Qualcomm                         | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| MediaTek                         | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2767      | 46.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1297      | 21.99%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 130       | 2.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 94        | 1.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 91        | 1.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 89        | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 80        | 1.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 74        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 70        | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 66        | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 54        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 53        | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 50        | 0.85%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 47        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 42        | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 36        | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 30        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 29        | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 28        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 27        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 27        | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                                          | 27        | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 24        | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 24        | 0.41%   |
| Motorola PCS motorola one                                                      | 23        | 0.39%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 23        | 0.39%   |
| Intel 82577LM Gigabit Network Connection                                       | 22        | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 20        | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 20        | 0.34%   |
| Intel Ethernet Connection I219-LM                                              | 20        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 19        | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                              | 19        | 0.32%   |
| Intel Ethernet Connection I218-LM                                              | 19        | 0.32%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 19        | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 16        | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 16        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 15        | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 15        | 0.25%   |
| Intel Ethernet Connection I217-LM                                              | 15        | 0.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 14        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6252      | 51.87%  |
| Ethernet | 5767      | 47.85%  |
| Modem    | 24        | 0.2%    |
| Unknown  | 10        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5403      | 79.66%  |
| Ethernet | 1379      | 20.33%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5439      | 84.18%  |
| 1     | 812       | 12.57%  |
| 0     | 203       | 3.14%   |
| 3     | 7         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5226      | 79.15%  |
| Yes  | 1377      | 20.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1629      | 35.31%  |
| Qualcomm Atheros Communications | 1372      | 29.74%  |
| Lite-On Technology              | 606       | 13.13%  |
| Broadcom                        | 193       | 4.18%   |
| Realtek Semiconductor           | 145       | 3.14%   |
| Foxconn / Hon Hai               | 111       | 2.41%   |
| IMC Networks                    | 103       | 2.23%   |
| Cambridge Silicon Radio         | 86        | 1.86%   |
| Apple                           | 76        | 1.65%   |
| Dell                            | 71        | 1.54%   |
| Hewlett-Packard                 | 49        | 1.06%   |
| Ralink                          | 46        | 1%      |
| Unknown                         | 38        | 0.82%   |
| Qcom                            | 25        | 0.54%   |
| Ralink Technology               | 16        | 0.35%   |
| Alps Electric                   | 13        | 0.28%   |
| Foxconn International           | 12        | 0.26%   |
| Askey Computer                  | 8         | 0.17%   |
| Toshiba                         | 4         | 0.09%   |
| ASUSTek Computer                | 4         | 0.09%   |
| Micro Star International        | 3         | 0.07%   |
| Opticis                         | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 776       | 16.82%  |
| Intel Bluetooth wireless interface                                                  | 561       | 12.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 433       | 9.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 351       | 7.61%   |
| Intel AX200 Bluetooth                                                               | 291       | 6.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 224       | 4.85%   |
| Intel AX201 Bluetooth                                                               | 140       | 3.03%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 127       | 2.75%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 125       | 2.71%   |
| Realtek Bluetooth Radio                                                             | 110       | 2.38%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 107       | 2.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 86        | 1.86%   |
| Lite-On Bluetooth Device                                                            | 82        | 1.78%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 82        | 1.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 82        | 1.78%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 60        | 1.3%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 57        | 1.24%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 54        | 1.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 52        | 1.13%   |
| Ralink RT3290 Bluetooth                                                             | 46        | 1%      |
| Intel Wireless-AC 3168 Bluetooth                                                    | 46        | 1%      |
| IMC Networks Bluetooth Radio                                                        | 39        | 0.85%   |
| Unknown Bluetooth Device                                                            | 38        | 0.82%   |
| Apple Bluetooth Host Controller                                                     | 32        | 0.69%   |
| Dell Wireless 365 Bluetooth                                                         | 31        | 0.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 29        | 0.63%   |
| IMC Networks Bluetooth Device                                                       | 28        | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 27        | 0.59%   |
| Apple Bluetooth USB Host Controller                                                 | 27        | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 26        | 0.56%   |
| Lite-On Atheros Bluetooth                                                           | 22        | 0.48%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 22        | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 18        | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 17        | 0.37%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 16        | 0.35%   |
| Realtek RTL8723A Bluetooth                                                          | 15        | 0.33%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.33%   |
| Dell DW375 Bluetooth Module                                                         | 15        | 0.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 15        | 0.33%   |
| Qcom Broadcom Bluetooth USB                                                         | 14        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5552      | 74.87%  |
| Nvidia                                          | 799       | 10.77%  |
| AMD                                             | 656       | 8.85%   |
| Silicon Integrated Systems [SiS]                | 94        | 1.27%   |
| C-Media Electronics                             | 61        | 0.82%   |
| Generalplus Technology                          | 37        | 0.5%    |
| Logitech                                        | 36        | 0.49%   |
| VIA Technologies                                | 24        | 0.32%   |
| Kingston Technology                             | 18        | 0.24%   |
| JMTek                                           | 17        | 0.23%   |
| Corsair                                         | 10        | 0.13%   |
| Texas Instruments                               | 9         | 0.12%   |
| Plantronics                                     | 9         | 0.12%   |
| Realtek Semiconductor                           | 8         | 0.11%   |
| GN Netcom                                       | 8         | 0.11%   |
| Microsoft                                       | 7         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.08%   |
| Sony                                            | 5         | 0.07%   |
| Samsung Electronics                             | 5         | 0.07%   |
| SteelSeries ApS                                 | 3         | 0.04%   |
| Samson Technologies                             | 3         | 0.04%   |
| Razer USA                                       | 3         | 0.04%   |
| Meizu                                           | 3         | 0.04%   |
| Lenovo                                          | 3         | 0.04%   |
| JBL                                             | 3         | 0.04%   |
| WL80                                            | 2         | 0.03%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Tdlasunnic                                      | 2         | 0.03%   |
| M-Audio                                         | 2         | 0.03%   |
| Goldvish                                        | 2         | 0.03%   |
| Focusrite-Novation                              | 2         | 0.03%   |
| Dell                                            | 2         | 0.03%   |
| BY EDIFIER                                      | 2         | 0.03%   |
| BEHRINGER International                         | 2         | 0.03%   |
| Astro Gaming                                    | 2         | 0.03%   |
| Winbond Electronics                             | 1         | 0.01%   |
| Tenx Technology                                 | 1         | 0.01%   |
| Syntek                                          | 1         | 0.01%   |
| SOMIC Industrial                                | 1         | 0.01%   |
| Sennheiser Communications                       | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1022      | 11.81%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 871       | 10.07%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 443       | 5.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 397       | 4.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 373       | 4.31%   |
| Intel 8 Series HD Audio Controller                                                                | 372       | 4.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 368       | 4.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 305       | 3.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 305       | 3.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 300       | 3.47%   |
| Intel Broadwell-U Audio Controller                                                                | 300       | 3.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 265       | 3.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 255       | 2.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 179       | 2.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 165       | 1.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 153       | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 148       | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 142       | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 137       | 1.58%   |
| AMD Wrestler HDMI Audio                                                                           | 131       | 1.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 115       | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 111       | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 108       | 1.25%   |
| Intel CM238 HD Audio Controller                                                                   | 97        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 93        | 1.07%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 91        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 88        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 76        | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 68        | 0.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 68        | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 63        | 0.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 54        | 0.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 52        | 0.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 43        | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 38        | 0.44%   |
| Generalplus Technology USB Audio Device                                                           | 37        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 36        | 0.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 36        | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 0.38%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 30        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 462       | 19.17%  |
| Samsung Electronics | 332       | 13.78%  |
| Unknown             | 233       | 9.67%   |
| Kingston            | 232       | 9.63%   |
| SK hynix            | 222       | 9.21%   |
| A-DATA Technology   | 180       | 7.47%   |
| Teikon              | 132       | 5.48%   |
| Micron Technology   | 103       | 4.27%   |
| Smart Brazil        | 94        | 3.9%    |
| Crucial             | 59        | 2.45%   |
| High Bridge         | 57        | 2.37%   |
| Corsair             | 57        | 2.37%   |
| Elpida              | 39        | 1.62%   |
| Multilaser          | 21        | 0.87%   |
| Unknown (ABCD)      | 20        | 0.83%   |
| Apacer              | 18        | 0.75%   |
| Nanya Technology    | 16        | 0.66%   |
| Ramaxel Technology  | 11        | 0.46%   |
| Patriot             | 11        | 0.46%   |
| HT Micron           | 11        | 0.46%   |
| Unknown             | 11        | 0.46%   |
| Kllisre             | 10        | 0.41%   |
| Smart Modular       | 5         | 0.21%   |
| Avant               | 5         | 0.21%   |
| RZX                 | 4         | 0.17%   |
| Carry               | 4         | 0.17%   |
| Team                | 3         | 0.12%   |
| PUSKILL             | 3         | 0.12%   |
| Kreton              | 3         | 0.12%   |
| Kingmax             | 3         | 0.12%   |
| HBS                 | 3         | 0.12%   |
| G.Skill             | 3         | 0.12%   |
| Atermiter           | 3         | 0.12%   |
| Walton Chaintech    | 2         | 0.08%   |
| Unknown (8A02)      | 2         | 0.08%   |
| Unknown (898F)      | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| Positivo            | 2         | 0.08%   |
| Lexar               | 2         | 0.08%   |
| CSX                 | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 71        | 2.71%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 46        | 1.76%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 42        | 1.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 40        | 1.53%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 39        | 1.49%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 36        | 1.37%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s         | 33        | 1.26%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 30        | 1.15%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 29        | 1.11%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 28        | 1.07%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.92%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 22        | 0.84%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 21        | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 20        | 0.76%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 20        | 0.76%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 20        | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.73%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 19        | 0.73%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s        | 17        | 0.65%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 16        | 0.61%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 16        | 0.61%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 15        | 0.57%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 14        | 0.53%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 14        | 0.53%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 14        | 0.53%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 14        | 0.53%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s          | 14        | 0.53%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 14        | 0.53%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 14        | 0.53%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 14        | 0.53%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 12        | 0.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.46%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s             | 12        | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 11        | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 11        | 0.42%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 11        | 0.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.42%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 943       | 47.1%   |
| DDR4    | 754       | 37.66%  |
| DDR2    | 127       | 6.34%   |
| SDRAM   | 60        | 3%      |
| LPDDR4  | 51        | 2.55%   |
| LPDDR3  | 26        | 1.3%    |
| DRAM    | 18        | 0.9%    |
| DDR     | 12        | 0.6%    |
| Unknown | 7         | 0.35%   |
| DDR5    | 2         | 0.1%    |
| RAM     | 1         | 0.05%   |
| LPDDR5  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1901      | 95.96%  |
| Row Of Chips | 63        | 3.18%   |
| Unknown      | 9         | 0.45%   |
| DIMM         | 6         | 0.3%    |
| Chip         | 2         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 927       | 40.6%   |
| 8192  | 578       | 25.32%  |
| 2048  | 483       | 21.16%  |
| 16384 | 193       | 8.45%   |
| 1024  | 77        | 3.37%   |
| 32768 | 20        | 0.88%   |
| 512   | 5         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 592       | 26.04%  |
| 2667    | 431       | 18.96%  |
| 2400    | 266       | 11.7%   |
| 1334    | 201       | 8.84%   |
| 1333    | 176       | 7.74%   |
| 3200    | 105       | 4.62%   |
| Unknown | 85        | 3.74%   |
| 2133    | 77        | 3.39%   |
| 800     | 50        | 2.2%    |
| 667     | 48        | 2.11%   |
| 4199    | 37        | 1.63%   |
| 1067    | 36        | 1.58%   |
| 1066    | 32        | 1.41%   |
| 4267    | 23        | 1.01%   |
| 975     | 20        | 0.88%   |
| 533     | 20        | 0.88%   |
| 2048    | 19        | 0.84%   |
| 3266    | 9         | 0.4%    |
| 2933    | 9         | 0.4%    |
| 1867    | 9         | 0.4%    |
| 8400    | 6         | 0.26%   |
| 1200    | 4         | 0.18%   |
| 4800    | 2         | 0.09%   |
| 3733    | 2         | 0.09%   |
| 400     | 2         | 0.09%   |
| 6400    | 1         | 0.04%   |
| 3466    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1400    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 2       | 1         | 0.04%   |
| 1       | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 40.38%  |
| Seiko Epson         | 18        | 34.62%  |
| Canon               | 5         | 9.62%   |
| Samsung Electronics | 4         | 7.69%   |
| Brother Industries  | 2         | 3.85%   |
| Xerox               | 1         | 1.92%   |
| MIIIW               | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                     | 7         | 13.46%  |
| HP DeskJet 2700 series                       | 3         | 5.77%   |
| Seiko Epson ET-3750 Series                   | 2         | 3.85%   |
| Seiko Epson ET-2600 Series                   | 2         | 3.85%   |
| HP LaserJet Professional P1102w              | 2         | 3.85%   |
| HP LaserJet 1020                             | 2         | 3.85%   |
| HP Ink Tank Wireless 410 series              | 2         | 3.85%   |
| HP Deskjet 3050 J610 series                  | 2         | 3.85%   |
| HP Deskjet 2540 series                       | 2         | 3.85%   |
| Canon G3000 series                           | 2         | 3.85%   |
| Xerox Phaser 3040                            | 1         | 1.92%   |
| Seiko Epson XP-230 Series                    | 1         | 1.92%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.92%   |
| Seiko Epson L805 Series                      | 1         | 1.92%   |
| Seiko Epson L4150 Series                     | 1         | 1.92%   |
| Seiko Epson L380 Series                      | 1         | 1.92%   |
| Seiko Epson L355 Series                      | 1         | 1.92%   |
| Seiko Epson L222 Series                      | 1         | 1.92%   |
| Samsung SCX-4623 Series                      | 1         | 1.92%   |
| Samsung SCX-4200 series                      | 1         | 1.92%   |
| Samsung M332x 382x 402x Series               | 1         | 1.92%   |
| Samsung M2020 Series                         | 1         | 1.92%   |
| MIIIW MW Keyboard Air Mini                   | 1         | 1.92%   |
| HP LaserJet 1018                             | 1         | 1.92%   |
| HP DeskJet F4200 series                      | 1         | 1.92%   |
| HP DeskJet F4100 Printer series              | 1         | 1.92%   |
| HP DeskJet D1360                             | 1         | 1.92%   |
| HP DeskJet 3630 series                       | 1         | 1.92%   |
| HP DeskJet 2300 series                       | 1         | 1.92%   |
| HP DeskJet 2130 series                       | 1         | 1.92%   |
| HP Deskjet 1510                              | 1         | 1.92%   |
| Canon G4010 series                           | 1         | 1.92%   |
| Canon G4000 series                           | 1         | 1.92%   |
| Canon G3010 series                           | 1         | 1.92%   |
| Brother HL-5250DN Printer                    | 1         | 1.92%   |
| Brother DCP-7040                             | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Hewlett-Packard | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 2400c                   | 1         | 20%     |
| HP Scanjet 200                     | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1273      | 21.59%  |
| Microdia                               | 703       | 11.92%  |
| Realtek Semiconductor                  | 592       | 10.04%  |
| Quanta                                 | 560       | 9.5%    |
| Silicon Motion                         | 492       | 8.34%   |
| Sunplus Innovation Technology          | 452       | 7.67%   |
| Acer                                   | 405       | 6.87%   |
| IMC Networks                           | 266       | 4.51%   |
| Suyin                                  | 259       | 4.39%   |
| Syntek                                 | 186       | 3.15%   |
| Alcor Micro                            | 112       | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) | 76        | 1.29%   |
| Apple                                  | 75        | 1.27%   |
| Samsung Electronics                    | 51        | 0.86%   |
| Ricoh                                  | 45        | 0.76%   |
| Logitech                               | 45        | 0.76%   |
| ALi                                    | 41        | 0.7%    |
| Unknown                                | 24        | 0.41%   |
| Lite-On Technology                     | 22        | 0.37%   |
| Importek                               | 21        | 0.36%   |
| OmniVision Technologies                | 20        | 0.34%   |
| Z-Star Microelectronics                | 19        | 0.32%   |
| Lenovo                                 | 12        | 0.2%    |
| USB Camera                             | 11        | 0.19%   |
| LG Electronics                         | 10        | 0.17%   |
| Generalplus Technology                 | 10        | 0.17%   |
| Sonix Technology                       | 9         | 0.15%   |
| Intel                                  | 9         | 0.15%   |
| Y Media                                | 7         | 0.12%   |
| SunplusIT                              | 7         | 0.12%   |
| Pixart Imaging                         | 7         | 0.12%   |
| Microsoft                              | 6         | 0.1%    |
| Camera                                 | 6         | 0.1%    |
| Sunplus Technology                     | 5         | 0.08%   |
| Primax Electronics                     | 5         | 0.08%   |
| Jieli Technology                       | 5         | 0.08%   |
| Image Processor                        | 5         | 0.08%   |
| Foxconn / Hon Hai                      | 5         | 0.08%   |
| DigiTech                               | 5         | 0.08%   |
| JMicron Technology                     | 4         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD              | 254       | 4.3%    |
| Microdia Integrated_Webcam_HD             | 250       | 4.24%   |
| Quanta HD User Facing                     | 236       | 4%      |
| Chicony HD User Facing                    | 194       | 3.29%   |
| Chicony HD WebCam                         | 187       | 3.17%   |
| Silicon Motion Web Camera                 | 182       | 3.08%   |
| Sunplus Integrated_Webcam_HD              | 180       | 3.05%   |
| Quanta VGA WebCam                         | 172       | 2.91%   |
| Chicony USB 2.0 Camera                    | 136       | 2.3%    |
| Chicony VGA WebCam                        | 132       | 2.24%   |
| Chicony Integrated Camera                 | 130       | 2.2%    |
| Syntek Integrated Camera                  | 101       | 1.71%   |
| Sunplus HD WebCam                         | 101       | 1.71%   |
| Realtek Integrated Webcam                 | 97        | 1.64%   |
| Quanta HD Webcam                          | 95        | 1.61%   |
| Microdia Laptop_Integrated_Webcam_HD      | 92        | 1.56%   |
| Alcor Micro USB 2.0 Camera                | 70        | 1.19%   |
| Acer BisonCam, NB Pro                     | 63        | 1.07%   |
| Acer Lenovo EasyCamera                    | 62        | 1.05%   |
| Acer EasyCamera                           | 60        | 1.02%   |
| Realtek USB Camera                        | 59        | 1%      |
| Microdia Dell Laptop Integrated Webcam HD | 53        | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)   | 51        | 0.86%   |
| Silicon Motion WebCam SC-10HDD12636N      | 48        | 0.81%   |
| Microdia Integrated Webcam HD             | 44        | 0.75%   |
| IMC Networks Integrated Camera            | 43        | 0.73%   |
| Acer VGA WebCam                           | 43        | 0.73%   |
| Suyin Integrated_Webcam_HD                | 42        | 0.71%   |
| Silicon Motion WebCam SCB-1100N           | 39        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 39        | 0.66%   |
| Realtek HD WebCam                         | 38        | 0.64%   |
| Silicon Motion WebCam SC-13HDL11939N      | 37        | 0.63%   |
| Silicon Motion WebCam SC-0311139N         | 36        | 0.61%   |
| Syntek EasyCamera                         | 35        | 0.59%   |
| Chicony EasyCamera                        | 34        | 0.58%   |
| Acer USB Camera                           | 34        | 0.58%   |
| Acer HD Webcam                            | 34        | 0.58%   |
| IMC Networks USB2.0 HD UVC WebCam         | 33        | 0.56%   |
| Silicon Motion WebCam SCB-0385N           | 32        | 0.54%   |
| Chicony Lenovo EasyCamera                 | 32        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 264       | 50.19%  |
| AuthenTec                  | 55        | 10.46%  |
| Upek                       | 52        | 9.89%   |
| Synaptics                  | 51        | 9.7%    |
| Shenzhen Goodix Technology | 46        | 8.75%   |
| LighTuning Technology      | 29        | 5.51%   |
| Samsung Electronics        | 15        | 2.85%   |
| Elan Microelectronics      | 8         | 1.52%   |
| STMicroelectronics         | 3         | 0.57%   |
| Focal-systems.Corp         | 1         | 0.19%   |
| DigitalPersona             | 1         | 0.19%   |
| Dell                       | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 101       | 19.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 44        | 8.37%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 4.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 4.94%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 24        | 4.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 22        | 4.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.99%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.99%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 15        | 2.85%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 2.85%   |
| Samsung Fingerprint Device                                                 | 15        | 2.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.66%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.28%   |
| AuthenTec AES2810                                                          | 12        | 2.28%   |
| Validity Sensors VFS491                                                    | 11        | 2.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 2.09%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.71%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.52%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.52%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.33%   |
| Synaptics  WBDI                                                            | 7         | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.14%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.95%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.95%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.95%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.38%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.38%   |
| AuthenTec AES1600                                                          | 2         | 0.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.19%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.19%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.19%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.19%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 73        | 52.52%  |
| Alcor Micro               | 23        | 16.55%  |
| Lenovo                    | 13        | 9.35%   |
| Upek                      | 8         | 5.76%   |
| Giesecke & Devrient       | 7         | 5.04%   |
| Aladdin Knowledge Systems | 5         | 3.6%    |
| Watchdata                 | 4         | 2.88%   |
| O2 Micro                  | 3         | 2.16%   |
| SCM Microsystems          | 1         | 0.72%   |
| Gemalto (was Gemplus)     | 1         | 0.72%   |
| Advanced Card Systems     | 1         | 0.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 16.55%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 14.39%  |
| Broadcom 58200                                                               | 19        | 13.67%  |
| Broadcom 5880                                                                | 18        | 12.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 11.51%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 9.35%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 5.76%   |
| Giesecke & Devrient StarSign CUT                                             | 5         | 3.6%    |
| Aladdin Knowledge Systems Token JC                                           | 5         | 3.6%    |
| Watchdata USB Key                                                            | 4         | 2.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.44%   |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 1.44%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.72%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.72%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.72%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5027      | 76.76%  |
| 1     | 1330      | 20.31%  |
| 2     | 161       | 2.46%   |
| 3     | 16        | 0.24%   |
| 4     | 7         | 0.11%   |
| 7     | 4         | 0.06%   |
| 8     | 2         | 0.03%   |
| 5     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 524       | 30.34%  |
| Graphics card            | 477       | 27.62%  |
| Multimedia controller    | 170       | 9.84%   |
| Net/wireless             | 137       | 7.93%   |
| Chipcard                 | 125       | 7.24%   |
| Bluetooth                | 76        | 4.4%    |
| Camera                   | 53        | 3.07%   |
| Communication controller | 38        | 2.2%    |
| Storage                  | 36        | 2.08%   |
| Sound                    | 28        | 1.62%   |
| Flash memory             | 20        | 1.16%   |
| Net/ethernet             | 18        | 1.04%   |
| Card reader              | 8         | 0.46%   |
| Modem                    | 7         | 0.41%   |
| Firewire controller      | 4         | 0.23%   |
| Network                  | 3         | 0.17%   |
| Unassigned class         | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |


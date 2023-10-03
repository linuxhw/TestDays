Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 5461

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Victus by Laptop 16-d0xx... | [5ee355215f](https://linux-hardware.org/?probe=5ee355215f) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef74c51c65](https://linux-hardware.org/?probe=ef74c51c65) | Oct 01, 2023 |
| Dell          | Inspiron 5567               | [493a83e70a](https://linux-hardware.org/?probe=493a83e70a) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| HP            | ProBook 6560b               | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| eMachines     | eME732Z                     | [ba03824830](https://linux-hardware.org/?probe=ba03824830) | Sep 29, 2023 |
| Dell          | Precision 5480              | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [eef8975f1e](https://linux-hardware.org/?probe=eef8975f1e) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| Google        | Lindar                      | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| Google        | Lindar                      | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | G3 3590                     | [3523165978](https://linux-hardware.org/?probe=3523165978) | Sep 27, 2023 |
| Dell          | Latitude 3540               | [eb8bf9b174](https://linux-hardware.org/?probe=eb8bf9b174) | Sep 26, 2023 |
| Dell          | G5 5590                     | [c7e7205fff](https://linux-hardware.org/?probe=c7e7205fff) | Sep 26, 2023 |
| Dell          | G5 5590                     | [0e80b66cb6](https://linux-hardware.org/?probe=0e80b66cb6) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [742cfeafb0](https://linux-hardware.org/?probe=742cfeafb0) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a7d0f8e075](https://linux-hardware.org/?probe=a7d0f8e075) | Sep 26, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [1ce8f959f1](https://linux-hardware.org/?probe=1ce8f959f1) | Sep 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [549941d843](https://linux-hardware.org/?probe=549941d843) | Sep 25, 2023 |
| Samsung       | 750XDA                      | [dd03d00004](https://linux-hardware.org/?probe=dd03d00004) | Sep 25, 2023 |
| MSI           | Bravo 15 C7VF               | [ab0a5a435f](https://linux-hardware.org/?probe=ab0a5a435f) | Sep 25, 2023 |
| Dell          | Latitude E5440              | [f4accb1cb0](https://linux-hardware.org/?probe=f4accb1cb0) | Sep 25, 2023 |
| Dell          | Latitude E6330              | [1375d355a5](https://linux-hardware.org/?probe=1375d355a5) | Sep 24, 2023 |
| Dell          | Latitude E5470              | [efb0e356d6](https://linux-hardware.org/?probe=efb0e356d6) | Sep 24, 2023 |
| Lenovo        | IdeaPad N581 7505           | [ed2e5eed86](https://linux-hardware.org/?probe=ed2e5eed86) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| Dell          | Inspiron 3543               | [2075d98d66](https://linux-hardware.org/?probe=2075d98d66) | Sep 24, 2023 |
| Dell          | Inspiron 7577               | [685f51111f](https://linux-hardware.org/?probe=685f51111f) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E431 62778... | [31b0e8e9ce](https://linux-hardware.org/?probe=31b0e8e9ce) | Sep 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [234fc6a6fb](https://linux-hardware.org/?probe=234fc6a6fb) | Sep 24, 2023 |
| Dell          | Latitude 5580               | [6353ffcdf5](https://linux-hardware.org/?probe=6353ffcdf5) | Sep 23, 2023 |
| MSI           | Katana GF76 11UE            | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| Fujitsu       | LIFEBOOK A357               | [d18e2d8811](https://linux-hardware.org/?probe=d18e2d8811) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [04141bd71c](https://linux-hardware.org/?probe=04141bd71c) | Sep 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [900334906e](https://linux-hardware.org/?probe=900334906e) | Sep 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [0f097b1b88](https://linux-hardware.org/?probe=0f097b1b88) | Sep 22, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [8c65f7a68a](https://linux-hardware.org/?probe=8c65f7a68a) | Sep 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | [0f189d3c2a](https://linux-hardware.org/?probe=0f189d3c2a) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | [5dae6d6eda](https://linux-hardware.org/?probe=5dae6d6eda) | Sep 21, 2023 |
| Lenovo        | ThinkPad L540 20AU006CRI    | [e8885911a0](https://linux-hardware.org/?probe=e8885911a0) | Sep 21, 2023 |
| Apple         | MacBookPro12,1              | [bb796b1e6e](https://linux-hardware.org/?probe=bb796b1e6e) | Sep 21, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [2310ddb9a7](https://linux-hardware.org/?probe=2310ddb9a7) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | [ae062bd5ca](https://linux-hardware.org/?probe=ae062bd5ca) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1850488dd1](https://linux-hardware.org/?probe=1850488dd1) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c122be4331](https://linux-hardware.org/?probe=c122be4331) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | [49ed4b61ff](https://linux-hardware.org/?probe=49ed4b61ff) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [91c2eeef2f](https://linux-hardware.org/?probe=91c2eeef2f) | Sep 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [052438c7dd](https://linux-hardware.org/?probe=052438c7dd) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a87ec029ab](https://linux-hardware.org/?probe=a87ec029ab) | Sep 19, 2023 |
| Dell          | Vostro 15 3515              | [1929f30e86](https://linux-hardware.org/?probe=1929f30e86) | Sep 18, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| Dell          | Latitude 5501               | [66b2685ca5](https://linux-hardware.org/?probe=66b2685ca5) | Sep 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| Lenovo        | ThinkPad X220 4290LT8       | [56d2386012](https://linux-hardware.org/?probe=56d2386012) | Sep 17, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [959cef0f9e](https://linux-hardware.org/?probe=959cef0f9e) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [506d025e1e](https://linux-hardware.org/?probe=506d025e1e) | Sep 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [282def5c2a](https://linux-hardware.org/?probe=282def5c2a) | Sep 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Acer          | Predator PH315-54           | [bb4b6fe52f](https://linux-hardware.org/?probe=bb4b6fe52f) | Sep 15, 2023 |
| Acer          | Nitro AN515-45              | [51c7125a22](https://linux-hardware.org/?probe=51c7125a22) | Sep 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [fca517e53f](https://linux-hardware.org/?probe=fca517e53f) | Sep 15, 2023 |
| Timi          | A35S                        | [b229627e35](https://linux-hardware.org/?probe=b229627e35) | Sep 14, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Acer          | Predator PH315-54           | [e1a54edbdc](https://linux-hardware.org/?probe=e1a54edbdc) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [b06966adc5](https://linux-hardware.org/?probe=b06966adc5) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [9f459c45cc](https://linux-hardware.org/?probe=9f459c45cc) | Sep 14, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [c4b64b54dd](https://linux-hardware.org/?probe=c4b64b54dd) | Sep 14, 2023 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [040dc9433a](https://linux-hardware.org/?probe=040dc9433a) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | [b8b03de96a](https://linux-hardware.org/?probe=b8b03de96a) | Sep 13, 2023 |
| HP            | Victus by Gaming Laptop ... | [ac50c36768](https://linux-hardware.org/?probe=ac50c36768) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0XL0... | [31e98e457c](https://linux-hardware.org/?probe=31e98e457c) | Sep 13, 2023 |
| Lenovo        | ThinkPad T450s 20BWS03F0... | [772c104a64](https://linux-hardware.org/?probe=772c104a64) | Sep 13, 2023 |
| Acer          | Aspire A515-45              | [1df9430f46](https://linux-hardware.org/?probe=1df9430f46) | Sep 13, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [deb3ba5bf7](https://linux-hardware.org/?probe=deb3ba5bf7) | Sep 13, 2023 |
| ASUSTek       | GL753VD                     | [c122d5178e](https://linux-hardware.org/?probe=c122d5178e) | Sep 12, 2023 |
| Apple         | MacBookPro15,1              | [3d297f7444](https://linux-hardware.org/?probe=3d297f7444) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | [c549b7a562](https://linux-hardware.org/?probe=c549b7a562) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | [26fe63f6ba](https://linux-hardware.org/?probe=26fe63f6ba) | Sep 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [471faa50e0](https://linux-hardware.org/?probe=471faa50e0) | Sep 12, 2023 |
| ASUSTek       | X555LN                      | [d5d9b73baa](https://linux-hardware.org/?probe=d5d9b73baa) | Sep 11, 2023 |
| ASUSTek       | X555LN                      | [3aef7779ec](https://linux-hardware.org/?probe=3aef7779ec) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | [afa0844d9f](https://linux-hardware.org/?probe=afa0844d9f) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| HP            | Elite x2 1012 G1            | [f7546a9d25](https://linux-hardware.org/?probe=f7546a9d25) | Sep 11, 2023 |
| Dell          | Latitude 5420               | [d561f541f6](https://linux-hardware.org/?probe=d561f541f6) | Sep 10, 2023 |
| Dell          | Latitude 5420               | [982a0e5ce2](https://linux-hardware.org/?probe=982a0e5ce2) | Sep 10, 2023 |
| Acer          | Swift SF314-71              | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Dell          | Inspiron 5515               | [a6c468e52d](https://linux-hardware.org/?probe=a6c468e52d) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | [320bbb4e83](https://linux-hardware.org/?probe=320bbb4e83) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | [534003f1ab](https://linux-hardware.org/?probe=534003f1ab) | Sep 10, 2023 |
| ASUSTek       | X550CC                      | [838e1d8f4a](https://linux-hardware.org/?probe=838e1d8f4a) | Sep 10, 2023 |
| HUAWEI        | HKD-WXX                     | [3b97b2d662](https://linux-hardware.org/?probe=3b97b2d662) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [57e235e93d](https://linux-hardware.org/?probe=57e235e93d) | Sep 09, 2023 |
| ASUSTek       | X555LAB                     | [dd0683372d](https://linux-hardware.org/?probe=dd0683372d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [0ede91c6cd](https://linux-hardware.org/?probe=0ede91c6cd) | Sep 08, 2023 |
| HP            | Laptop 15s-fr1xxx           | [a6e3c47b2d](https://linux-hardware.org/?probe=a6e3c47b2d) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [727b5526f9](https://linux-hardware.org/?probe=727b5526f9) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905f93bc0a](https://linux-hardware.org/?probe=905f93bc0a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e87517b925](https://linux-hardware.org/?probe=e87517b925) | Sep 08, 2023 |
| HP            | Pavilion 15                 | [b6de5d8503](https://linux-hardware.org/?probe=b6de5d8503) | Sep 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b6686658dc](https://linux-hardware.org/?probe=b6686658dc) | Sep 07, 2023 |
| HP            | Pavilion 15                 | [6ab4c7f2d8](https://linux-hardware.org/?probe=6ab4c7f2d8) | Sep 07, 2023 |
| HP            | Pavilion 15                 | [c251475f43](https://linux-hardware.org/?probe=c251475f43) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f33c62ab06](https://linux-hardware.org/?probe=f33c62ab06) | Sep 07, 2023 |
| HP            | ProBook 445 G7              | [373ba724e4](https://linux-hardware.org/?probe=373ba724e4) | Sep 06, 2023 |
| HP            | Pavilion dv6                | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| HUAWEI        | BOM-WXX9                    | [8e0ee8ad83](https://linux-hardware.org/?probe=8e0ee8ad83) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Samsung       | 750XDA                      | [efe919fb13](https://linux-hardware.org/?probe=efe919fb13) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Dell          | XPS 15 9500                 | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| Dell          | XPS 13 9310                 | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| HP            | EliteBook Folio 9470m       | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| ASUSTek       | X555LAB                     | [b8aba55b59](https://linux-hardware.org/?probe=b8aba55b59) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| MSI           | Modern 14 B11MOU            | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| Dell          | Latitude 3410               | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6736962dbe](https://linux-hardware.org/?probe=6736962dbe) | Sep 01, 2023 |
| ASUSTek       | X555LAB                     | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [3c434cdeda](https://linux-hardware.org/?probe=3c434cdeda) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| MSI           | MS-7E06                     | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| HP            | Pavilion Notebook           | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| ASUSTek       | X555LAB                     | [ce793ccb8d](https://linux-hardware.org/?probe=ce793ccb8d) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [aa23e296ad](https://linux-hardware.org/?probe=aa23e296ad) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7d74c2bc61](https://linux-hardware.org/?probe=7d74c2bc61) | Aug 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [dcceb74a56](https://linux-hardware.org/?probe=dcceb74a56) | Aug 29, 2023 |
| Acer          | One Z1402                   | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| Dell          | Precision 3520              | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Dell          | Latitude 5580               | [e16786f57e](https://linux-hardware.org/?probe=e16786f57e) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f30251883f](https://linux-hardware.org/?probe=f30251883f) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Chuwi         | GemiBook Pro                | [95b9733408](https://linux-hardware.org/?probe=95b9733408) | Aug 23, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [34532a7998](https://linux-hardware.org/?probe=34532a7998) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [3a3b362bd0](https://linux-hardware.org/?probe=3a3b362bd0) | Aug 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8e478e15da](https://linux-hardware.org/?probe=8e478e15da) | Aug 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cdb0c49b6a](https://linux-hardware.org/?probe=cdb0c49b6a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2e4f8c0f7c](https://linux-hardware.org/?probe=2e4f8c0f7c) | Aug 21, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Acer          | Aspire E5-573G              | [005b310c55](https://linux-hardware.org/?probe=005b310c55) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| Dell          | XPS 15 9500                 | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [1289521063](https://linux-hardware.org/?probe=1289521063) | Aug 18, 2023 |
| ASUSTek       | GL552VX                     | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| Notebook      | NS50MU                      | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| Acer          | Swift SFX14-41G             | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| HUAWEI        | WRT-WX9                     | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| Timi          | A35S                        | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Dell          | Latitude 5300               | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Valve         | Jupiter                     | [acf70a31a9](https://linux-hardware.org/?probe=acf70a31a9) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [bbe00bbe48](https://linux-hardware.org/?probe=bbe00bbe48) | Aug 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [10f2a6448d](https://linux-hardware.org/?probe=10f2a6448d) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Acer          | Aspire 7750G                | [494c725472](https://linux-hardware.org/?probe=494c725472) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| Alienware     | 15                          | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| HP            | EliteBook 840 G1            | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Dell          | Inspiron 5570               | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | [fdfeffb5f3](https://linux-hardware.org/?probe=fdfeffb5f3) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | [71424c4380](https://linux-hardware.org/?probe=71424c4380) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| HP            | Pavilion 17                 | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | [0b797c9368](https://linux-hardware.org/?probe=0b797c9368) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | [90fbc716ed](https://linux-hardware.org/?probe=90fbc716ed) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| ASUSTek       | K73SV                       | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [21eaf09dc9](https://linux-hardware.org/?probe=21eaf09dc9) | Aug 05, 2023 |
| Dell          | Latitude E5440              | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| HP            | OMEN by Laptop              | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| Acer          | Nitro AN515-54              | [c4d1667ffe](https://linux-hardware.org/?probe=c4d1667ffe) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| HP            | EliteBook 840 G2            | [64810e5a10](https://linux-hardware.org/?probe=64810e5a10) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Chuwi         | GemiBook Pro                | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| HP            | Notebook                    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| PC Special... | Lafite Pro III 17           | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [a251ad988c](https://linux-hardware.org/?probe=a251ad988c) | Aug 03, 2023 |
| Acer          | Predator PHN16-71           | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Timi          | A7S                         | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| HUAWEI        | KPR-WX9                     | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| Dell          | Latitude 5590               | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| Apple         | MacBookPro14,1              | [cb322d77a4](https://linux-hardware.org/?probe=cb322d77a4) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| Dell          | G15 5511                    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Dell          | G15 5511                    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| Dell          | Latitude E6400              | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| Acer          | Aspire A315-53              | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Latitude 5421               | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [5e1021c76b](https://linux-hardware.org/?probe=5e1021c76b) | Jul 30, 2023 |
| Razer         | Blade                       | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| HP            | EliteBook 745 G3            | [30e5e63466](https://linux-hardware.org/?probe=30e5e63466) | Jul 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [6426edf740](https://linux-hardware.org/?probe=6426edf740) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| MSI           | Raider GE78HX 13VI          | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Google        | Atlas                       | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [407859fa58](https://linux-hardware.org/?probe=407859fa58) | Jul 27, 2023 |
| HP            | ProBook 4530s               | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HUAWEI        | KPR-WX9                     | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| Acer          | Aspire A514-54              | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7910b0c067](https://linux-hardware.org/?probe=7910b0c067) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Acer          | Nitro AN515-54              | [f1db825d10](https://linux-hardware.org/?probe=f1db825d10) | Jul 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3bd5c9d59c](https://linux-hardware.org/?probe=3bd5c9d59c) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [0e123e6d85](https://linux-hardware.org/?probe=0e123e6d85) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| Acer          | Aspire V5-551               | [8a13138f82](https://linux-hardware.org/?probe=8a13138f82) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| HP            | ProBook 4530s               | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| Dell          | Latitude 5580               | [f115a04168](https://linux-hardware.org/?probe=f115a04168) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9a2d353d76](https://linux-hardware.org/?probe=9a2d353d76) | Jul 20, 2023 |
| Panasonic     | CFSZ5-3                     | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| ASUSTek       | N501VW                      | [08cd5a81b2](https://linux-hardware.org/?probe=08cd5a81b2) | Jul 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Dell          | Inspiron 7400               | [f145687601](https://linux-hardware.org/?probe=f145687601) | Jul 19, 2023 |
| Avell High... | B.ON                        | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| Apple         | MacBookPro11,2              | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| Lenovo        | B50-45 20388                | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [53c97d91d4](https://linux-hardware.org/?probe=53c97d91d4) | Jul 18, 2023 |
| HP            | EliteBook 830 G5            | [42eb1edbb6](https://linux-hardware.org/?probe=42eb1edbb6) | Jul 17, 2023 |
| Apple         | MacBookPro11,2              | [6bebb2e751](https://linux-hardware.org/?probe=6bebb2e751) | Jul 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b53aa427b9](https://linux-hardware.org/?probe=b53aa427b9) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [5be1306636](https://linux-hardware.org/?probe=5be1306636) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [2b81f8a707](https://linux-hardware.org/?probe=2b81f8a707) | Jul 17, 2023 |
| HP            | Pavilion 17                 | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| Lenovo        | M490s 20215                 | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e204dc6cf1](https://linux-hardware.org/?probe=e204dc6cf1) | Jul 15, 2023 |
| HUAWEI        | HN-WX9X                     | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [793289bc48](https://linux-hardware.org/?probe=793289bc48) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| Acer          | TravelMate P246-MG          | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Dell          | Latitude 7480               | [a375f7685c](https://linux-hardware.org/?probe=a375f7685c) | Jul 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS0P300    | [2c96c19647](https://linux-hardware.org/?probe=2c96c19647) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [23e018569e](https://linux-hardware.org/?probe=23e018569e) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [222924f1c2](https://linux-hardware.org/?probe=222924f1c2) | Jul 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e2792f841d](https://linux-hardware.org/?probe=e2792f841d) | Jul 12, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| Dell          | Precision M4700             | [69a672ec44](https://linux-hardware.org/?probe=69a672ec44) | Jul 11, 2023 |
| Acer          | SF714-52T                   | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [214dd1ad57](https://linux-hardware.org/?probe=214dd1ad57) | Jul 09, 2023 |
| HP            | ProBook 6460b               | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| HP            | OMEN by Laptop              | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [6f3284cac3](https://linux-hardware.org/?probe=6f3284cac3) | Jul 07, 2023 |
| Purism        | Librem 14                   | [18db47d3f6](https://linux-hardware.org/?probe=18db47d3f6) | Jul 07, 2023 |
| HP            | Laptop 14s-dk0xxx           | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| Lenovo        | B50-70 20384                | [8a0a97b362](https://linux-hardware.org/?probe=8a0a97b362) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| HP            | ENVY 15                     | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf134cbdd9](https://linux-hardware.org/?probe=cf134cbdd9) | Jul 06, 2023 |
| Dell          | G3 3590                     | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Dell          | G3 3590                     | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| Dell          | Latitude 7350               | [bc00420bfc](https://linux-hardware.org/?probe=bc00420bfc) | Jul 05, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c387c4fbf1](https://linux-hardware.org/?probe=c387c4fbf1) | Jul 04, 2023 |
| Dell          | Latitude 7350               | [14d41ff667](https://linux-hardware.org/?probe=14d41ff667) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [90b6b19a97](https://linux-hardware.org/?probe=90b6b19a97) | Jul 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [25d3329df1](https://linux-hardware.org/?probe=25d3329df1) | Jul 03, 2023 |
| ASUSTek       | 1015BX                      | [c4bc43a932](https://linux-hardware.org/?probe=c4bc43a932) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| Lenovo        | ThinkPad T520 4243B65       | [07584ce70c](https://linux-hardware.org/?probe=07584ce70c) | Jul 02, 2023 |
| Lenovo        | ThinkPad T410 2537PW4       | [10079a3e26](https://linux-hardware.org/?probe=10079a3e26) | Jul 02, 2023 |
| Lenovo        | ThinkPad T530 2429AA9       | [708fe309bc](https://linux-hardware.org/?probe=708fe309bc) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [d69c578d83](https://linux-hardware.org/?probe=d69c578d83) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [2e20df184f](https://linux-hardware.org/?probe=2e20df184f) | Jul 02, 2023 |
| Dell          | Inspiron 7460               | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| Apple         | MacBookPro11,1              | [998267633e](https://linux-hardware.org/?probe=998267633e) | Jul 01, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [2ba1cce30e](https://linux-hardware.org/?probe=2ba1cce30e) | Jul 01, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [85c3968edc](https://linux-hardware.org/?probe=85c3968edc) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | Precision 5570              | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| HP            | EliteBook 840 G3            | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| Dell          | XPS 9315                    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| MSI           | GS63 7RD                    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Precision 3581              | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26a3b9b3e9](https://linux-hardware.org/?probe=26a3b9b3e9) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| Acer          | Nitro AN517-51              | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| Dell          | Inspiron 3558               | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S14V00    | [6f81cc6d57](https://linux-hardware.org/?probe=6f81cc6d57) | Jun 19, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| Dell          | Latitude E7440              | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| HP            | Pavilion dv7                | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| Samsung       | 750XDA                      | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| Dell          | XPS 13 9350                 | [1150629ceb](https://linux-hardware.org/?probe=1150629ceb) | Jun 16, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| HP            | ProBook 650 G2              | [535950bae5](https://linux-hardware.org/?probe=535950bae5) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Acer          | Aspire A715-41G             | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | [41526d21bc](https://linux-hardware.org/?probe=41526d21bc) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | [6154060edd](https://linux-hardware.org/?probe=6154060edd) | Jun 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Dell          | Latitude E5470              | [cc81f6c74c](https://linux-hardware.org/?probe=cc81f6c74c) | Jun 11, 2023 |
| HP            | EliteBook 840 G2            | [80bc2607fb](https://linux-hardware.org/?probe=80bc2607fb) | Jun 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| Dell          | Latitude E5470              | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| HP            | 14                          | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Dell          | XPS 17 9730                 | [bb7335618d](https://linux-hardware.org/?probe=bb7335618d) | Jun 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Dell          | G15 5520                    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Google        | Edgar                       | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1f4ef72dbd](https://linux-hardware.org/?probe=1f4ef72dbd) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire A515-47              | [db7f17cbe1](https://linux-hardware.org/?probe=db7f17cbe1) | Jun 07, 2023 |
| Acer          | Swift SF314-43              | [9636ea4dc5](https://linux-hardware.org/?probe=9636ea4dc5) | Jun 07, 2023 |
| Dell          | Latitude 5480               | [dd2fef35ee](https://linux-hardware.org/?probe=dd2fef35ee) | Jun 06, 2023 |
| Dell          | Latitude 5480               | [7917512387](https://linux-hardware.org/?probe=7917512387) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| MSI           | Crosshair 15 C12VF          | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| Apple         | MacBookPro7,1               | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| MSI           | Katana GF66 11UG            | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Cube          | i16-L                       | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| Acer          | Swift SF314-511             | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [e0f06316db](https://linux-hardware.org/?probe=e0f06316db) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| Gigabyte      | AERO 15WV8                  | [a8700141be](https://linux-hardware.org/?probe=a8700141be) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Acer          | Nitro AN515-55              | [947c70d6b6](https://linux-hardware.org/?probe=947c70d6b6) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Inspiron 5515               | [f383c5193d](https://linux-hardware.org/?probe=f383c5193d) | Jun 01, 2023 |
| Dell          | Latitude E6400              | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Dell          | Latitude E6400              | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| Dell          | Inspiron 5593               | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| Dell          | Latitude E6420              | [102e4634b1](https://linux-hardware.org/?probe=102e4634b1) | May 31, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| ASUSTek       | N61Jv                       | [7184d6add6](https://linux-hardware.org/?probe=7184d6add6) | May 30, 2023 |
| HP            | Laptop 15-ef1xxx            | [55b500a1a9](https://linux-hardware.org/?probe=55b500a1a9) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| Dell          | Inspiron 1525               | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | 14                          | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Dell          | Inspiron 1525               | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Acer          | Aspire A515-41G             | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Dell          | Inspiron 5447               | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [12838b3e3b](https://linux-hardware.org/?probe=12838b3e3b) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Apple         | MacBookPro7,1               | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| HP            | EliteBook 840 G5            | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Dell          | Latitude E6440              | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| Acer          | Swift SF514-54GT            | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | EliteBook 8440p             | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| Dell          | Precision 3581              | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Dell          | Latitude 5430               | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Nitro AN515-45              | [a9e0505d3f](https://linux-hardware.org/?probe=a9e0505d3f) | May 26, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Z580                | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| ASUSTek       | S551LB                      | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Acer          | Swift SF314-71              | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| Acer          | Swift SF314-71              | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e6c958dd68](https://linux-hardware.org/?probe=e6c958dd68) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| Acer          | Aspire A315-58              | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Toshiba       | Satellite C645D             | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| HP            | Pavilion 17                 | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Acer          | Nitro AN515-45              | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Apple         | MacBookPro7,1               | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Dell          | G3 3500                     | [490bdc1f92](https://linux-hardware.org/?probe=490bdc1f92) | May 21, 2023 |
| HP            | Laptop 15-dy4xxx            | [d739b1ab41](https://linux-hardware.org/?probe=d739b1ab41) | May 21, 2023 |
| HASEE Comp... | V1x0PNPx                    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [d82bf9332f](https://linux-hardware.org/?probe=d82bf9332f) | May 20, 2023 |
| Dell          | Latitude D630               | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| Apple         | MacBookPro15,2              | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| HP            | Unknown                     | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| ASUSTek       | X555LPB                     | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| Dell          | Latitude 5500               | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| Dell          | Latitude 5420               | [bd0c08b7b8](https://linux-hardware.org/?probe=bd0c08b7b8) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Apple         | MacBookPro11,1              | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Acer          | Swift SF315-51G             | [4361a75669](https://linux-hardware.org/?probe=4361a75669) | May 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [42f598550a](https://linux-hardware.org/?probe=42f598550a) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| Emdoor        | AG958                       | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Google        | Cyan                        | [41811cace9](https://linux-hardware.org/?probe=41811cace9) | May 17, 2023 |
| Dell          | Latitude 5330               | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| GPD           | MicroPC                     | [0da3fc7738](https://linux-hardware.org/?probe=0da3fc7738) | May 16, 2023 |
| Google        | Cyan                        | [65c63caab7](https://linux-hardware.org/?probe=65c63caab7) | May 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [dc5dd8c32a](https://linux-hardware.org/?probe=dc5dd8c32a) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [85c2869727](https://linux-hardware.org/?probe=85c2869727) | May 15, 2023 |
| Acer          | Swift SF114-34              | [360db31139](https://linux-hardware.org/?probe=360db31139) | May 14, 2023 |
| Acer          | Swift SF114-34              | [c3bbc544d3](https://linux-hardware.org/?probe=c3bbc544d3) | May 14, 2023 |
| Lenovo        | ThinkPad T570 20H90002GE    | [e6ff63678e](https://linux-hardware.org/?probe=e6ff63678e) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| HP            | EliteBook 8470p             | [b9f9ed1b25](https://linux-hardware.org/?probe=b9f9ed1b25) | May 14, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [4b296f5c40](https://linux-hardware.org/?probe=4b296f5c40) | May 12, 2023 |
| Razer         | Blade 15 Studio Edition ... | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| realme        | RMNBXXXX                    | [16782746d8](https://linux-hardware.org/?probe=16782746d8) | May 12, 2023 |
| Dell          | Latitude 7390               | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Medion        | Crawler E40                 | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| Medion        | Crawler E40                 | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| Dell          | Latitude 7400               | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Dell          | Latitude 5480               | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [39dd8fc09a](https://linux-hardware.org/?probe=39dd8fc09a) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [0a1c43b710](https://linux-hardware.org/?probe=0a1c43b710) | May 09, 2023 |
| MSI           | PS42 Modern 8RA             | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire A315-22              | [8849d7a1c9](https://linux-hardware.org/?probe=8849d7a1c9) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Acer          | Aspire V3-772G              | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| MSI           | GV63 8SE                    | [55bfa86f43](https://linux-hardware.org/?probe=55bfa86f43) | May 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [af9591cedc](https://linux-hardware.org/?probe=af9591cedc) | May 07, 2023 |
| Dell          | Precision 7720              | [9e0a1bd8ef](https://linux-hardware.org/?probe=9e0a1bd8ef) | May 06, 2023 |
| Toshiba       | Satellite C855              | [775c7346eb](https://linux-hardware.org/?probe=775c7346eb) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Dell          | Precision 7550              | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| HP            | Laptop 15s-eq0xxx           | [a5252d48f3](https://linux-hardware.org/?probe=a5252d48f3) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| Lenovo        | ThinkPad X131e 33712MU      | [6957336ed7](https://linux-hardware.org/?probe=6957336ed7) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5f4447aa45](https://linux-hardware.org/?probe=5f4447aa45) | May 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [907a94ae07](https://linux-hardware.org/?probe=907a94ae07) | May 05, 2023 |
| MSI           | GV63 8SE                    | [1c78e3feb9](https://linux-hardware.org/?probe=1c78e3feb9) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Apple         | MacBookPro14,2              | [4124bb2dde](https://linux-hardware.org/?probe=4124bb2dde) | May 04, 2023 |
| ASUSTek       | N550JK                      | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | G505s 20255                 | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Quanta        | UW3 TBD                     | [0c951d032e](https://linux-hardware.org/?probe=0c951d032e) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | [abc1819fc1](https://linux-hardware.org/?probe=abc1819fc1) | May 04, 2023 |
| Lenovo        | B490 37722XP                | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Quanta        | UW3 TBD                     | [c138f57a47](https://linux-hardware.org/?probe=c138f57a47) | May 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| Acer          | Predator G9-793             | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Samsung       | 750XDA                      | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [abd1474dfc](https://linux-hardware.org/?probe=abd1474dfc) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| HP            | ProBook 430 G1              | [56542de280](https://linux-hardware.org/?probe=56542de280) | May 01, 2023 |
| Dell          | Inspiron 5458               | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [6b61472a4a](https://linux-hardware.org/?probe=6b61472a4a) | May 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| HP            | Laptop 15s-eq3xxx           | [3c321c476a](https://linux-hardware.org/?probe=3c321c476a) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| Dell          | XPS 13 9310                 | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [34420e9478](https://linux-hardware.org/?probe=34420e9478) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [96194bc912](https://linux-hardware.org/?probe=96194bc912) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| Dell          | Latitude 7420               | [7ceeb888fd](https://linux-hardware.org/?probe=7ceeb888fd) | Apr 27, 2023 |
| Dell          | Latitude E5440              | [0217386dbe](https://linux-hardware.org/?probe=0217386dbe) | Apr 27, 2023 |
| Sony          | SVE11113FXW                 | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| MSI           | Prestige 14 A12UC           | [137a3623dc](https://linux-hardware.org/?probe=137a3623dc) | Apr 25, 2023 |
| Notebook      | N85_N87HCHNHZ               | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Notebook      | N15_N17RD1                  | [8bba7a7447](https://linux-hardware.org/?probe=8bba7a7447) | Apr 23, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| HP            | 240 G4                      | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| HP            | 15                          | [4f563db114](https://linux-hardware.org/?probe=4f563db114) | Apr 21, 2023 |
| Valve         | Jupiter                     | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| Acer          | Aspire A715-71G             | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [be217cbc1e](https://linux-hardware.org/?probe=be217cbc1e) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d5e90c4b14](https://linux-hardware.org/?probe=d5e90c4b14) | Apr 19, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [146c678131](https://linux-hardware.org/?probe=146c678131) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [65a5b3f43d](https://linux-hardware.org/?probe=65a5b3f43d) | Apr 17, 2023 |
| MSI           | GF75 Thin 9SC               | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2fcbae14f2](https://linux-hardware.org/?probe=2fcbae14f2) | Apr 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [fff7f3dd1f](https://linux-hardware.org/?probe=fff7f3dd1f) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [e0ad93045c](https://linux-hardware.org/?probe=e0ad93045c) | Apr 14, 2023 |
| Lenovo        | V15-ADA 82C7                | [f604f6e212](https://linux-hardware.org/?probe=f604f6e212) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Avell High... | B.ON                        | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| HP            | ProBook 430 G6              | [9a4bce918e](https://linux-hardware.org/?probe=9a4bce918e) | Apr 14, 2023 |
| System76      | Pangolin                    | [b5dd9f13b9](https://linux-hardware.org/?probe=b5dd9f13b9) | Apr 14, 2023 |
| System76      | Pangolin                    | [a1a17fa4c4](https://linux-hardware.org/?probe=a1a17fa4c4) | Apr 14, 2023 |
| Lenovo        | ThinkPad T460 20FMS0E22C    | [ee911053e5](https://linux-hardware.org/?probe=ee911053e5) | Apr 13, 2023 |
| MSI           | Prestige 14 A12UC           | [43e044c37a](https://linux-hardware.org/?probe=43e044c37a) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| MSI           | Stealth 14Studio A13VF      | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Dell          | Latitude E7440              | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Toshiba       | Satellite S50-B             | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| HP            | Laptop 14s-cr0xxx           | [f95d67a702](https://linux-hardware.org/?probe=f95d67a702) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| Google        | Phaser360                   | [64953bc26c](https://linux-hardware.org/?probe=64953bc26c) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [772414cda4](https://linux-hardware.org/?probe=772414cda4) | Apr 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK S935               | [e7ba943509](https://linux-hardware.org/?probe=e7ba943509) | Apr 07, 2023 |
| HP            | ZBook 15 G5                 | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Dell          | Vostro 5620                 | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a02839d653](https://linux-hardware.org/?probe=a02839d653) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| Timi          | RedmiBook Pro 15            | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Alienware     | M17xR3                      | [514f79bd8e](https://linux-hardware.org/?probe=514f79bd8e) | Apr 05, 2023 |
| Acer          | AO756                       | [4e33479949](https://linux-hardware.org/?probe=4e33479949) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Prestigio     | PSB133S01ZFH                | [ba6746febf](https://linux-hardware.org/?probe=ba6746febf) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Google        | Snappy                      | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Schenker      | S405                        | [6d89f7e662](https://linux-hardware.org/?probe=6d89f7e662) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| Dell          | Inspiron 13 5310            | [32bdbfa581](https://linux-hardware.org/?probe=32bdbfa581) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440p              | [4057e0c5e9](https://linux-hardware.org/?probe=4057e0c5e9) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Dell          | XPS 17 9700                 | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440p              | [1063ba3fb9](https://linux-hardware.org/?probe=1063ba3fb9) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [0ab4f4cd55](https://linux-hardware.org/?probe=0ab4f4cd55) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [2e8eab25be](https://linux-hardware.org/?probe=2e8eab25be) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [d96583e702](https://linux-hardware.org/?probe=d96583e702) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| Acer          | Aspire ES1-512              | [f6357798c5](https://linux-hardware.org/?probe=f6357798c5) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| HP            | ElitePad 1000 G2            | [4b16a78f3e](https://linux-hardware.org/?probe=4b16a78f3e) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| Dell          | XPS 15 9500                 | [cebc7c547a](https://linux-hardware.org/?probe=cebc7c547a) | Mar 26, 2023 |
| Dell          | XPS 15 9500                 | [4391dcbdd2](https://linux-hardware.org/?probe=4391dcbdd2) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [0933beb0f7](https://linux-hardware.org/?probe=0933beb0f7) | Mar 26, 2023 |
| Dell          | G3 3590                     | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| HP            | ENVY Laptop 17-ce1xxx       | [f9ff96064b](https://linux-hardware.org/?probe=f9ff96064b) | Mar 24, 2023 |
| Toshiba       | Satellite C850-140          | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| Toshiba       | Satellite C55D-B            | [ae6069d9bb](https://linux-hardware.org/?probe=ae6069d9bb) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Acer          | Aspire A515-57              | [748d918a61](https://linux-hardware.org/?probe=748d918a61) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [38b0e00744](https://linux-hardware.org/?probe=38b0e00744) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [ad1134944b](https://linux-hardware.org/?probe=ad1134944b) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| ASUSTek       | T100HAN                     | [5f0061dd7b](https://linux-hardware.org/?probe=5f0061dd7b) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [0880214933](https://linux-hardware.org/?probe=0880214933) | Mar 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [e7b50c8f22](https://linux-hardware.org/?probe=e7b50c8f22) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [1da76d59b2](https://linux-hardware.org/?probe=1da76d59b2) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| MSI           | Modern 14 B10MW             | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| HP            | ProBook 440 G3              | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | [8d13f6eef9](https://linux-hardware.org/?probe=8d13f6eef9) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | [5b4e0532f8](https://linux-hardware.org/?probe=5b4e0532f8) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Dell          | G15 5511                    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0500018bce](https://linux-hardware.org/?probe=0500018bce) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [aa4184ac0c](https://linux-hardware.org/?probe=aa4184ac0c) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [00de843c75](https://linux-hardware.org/?probe=00de843c75) | Mar 19, 2023 |
| MSI           | GP66 Leopard 11UG           | [7210f8c423](https://linux-hardware.org/?probe=7210f8c423) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Unknown       | Unknown                     | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [434b76d9cd](https://linux-hardware.org/?probe=434b76d9cd) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [2ffc3ebd28](https://linux-hardware.org/?probe=2ffc3ebd28) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [304f8b71db](https://linux-hardware.org/?probe=304f8b71db) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [4bfe066835](https://linux-hardware.org/?probe=4bfe066835) | Mar 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [590a3ca248](https://linux-hardware.org/?probe=590a3ca248) | Mar 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [e4254565ed](https://linux-hardware.org/?probe=e4254565ed) | Mar 15, 2023 |
| Star Labs     | StarBook                    | [13efc22826](https://linux-hardware.org/?probe=13efc22826) | Mar 15, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [29ebc422fe](https://linux-hardware.org/?probe=29ebc422fe) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Acer          | Aspire E5-571               | [6c7886396a](https://linux-hardware.org/?probe=6c7886396a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| Dell          | Vostro 2420                 | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Star Labs     | StarBook                    | [3e534c533a](https://linux-hardware.org/?probe=3e534c533a) | Mar 14, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [2906d8ad11](https://linux-hardware.org/?probe=2906d8ad11) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Panasonic     | FZ40-1                      | [1dfcc0c545](https://linux-hardware.org/?probe=1dfcc0c545) | Mar 13, 2023 |
| HP            | ProBook 6460b               | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [87331b21e8](https://linux-hardware.org/?probe=87331b21e8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [5522717dc5](https://linux-hardware.org/?probe=5522717dc5) | Mar 12, 2023 |
| MSI           | Pulse GL66 11UGKV           | [1abb09da1a](https://linux-hardware.org/?probe=1abb09da1a) | Mar 12, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [a081c489c9](https://linux-hardware.org/?probe=a081c489c9) | Mar 12, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Dell          | Latitude E6530              | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | [5d082aaf0e](https://linux-hardware.org/?probe=5d082aaf0e) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | [9eac1dc6f5](https://linux-hardware.org/?probe=9eac1dc6f5) | Mar 10, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [06971429a7](https://linux-hardware.org/?probe=06971429a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| HP            | Laptop 14-fq0xxx            | [8574146364](https://linux-hardware.org/?probe=8574146364) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | [c397e2fa8b](https://linux-hardware.org/?probe=c397e2fa8b) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [79fc708bbd](https://linux-hardware.org/?probe=79fc708bbd) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [c768e8ff8f](https://linux-hardware.org/?probe=c768e8ff8f) | Mar 08, 2023 |
| Dell          | Precision 3520              | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude 5590               | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| GPD           | P2 MAX                      | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Arch Rolling           | 2133      | 54.83%  |
| Arch                   | 1745      | 44.86%  |
| Arch V20.5.7           | 2         | 0.05%   |
| Arch V19.04.4          | 2         | 0.05%   |
| Arch V6.9.2            | 1         | 0.03%   |
| Arch V20.3.4           | 1         | 0.03%   |
| Arch V19.07.9          | 1         | 0.03%   |
| Arch V19.06.1          | 1         | 0.03%   |
| Arch V19.01.4          | 1         | 0.03%   |
| Arch 23.0.0            | 1         | 0.03%   |
| Arch 20230723.0.166908 | 1         | 0.03%   |
| Arch 2.7               | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 3778      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 52        | 1.16%   |
| 6.0.2-arch1-1   | 51        | 1.14%   |
| 6.4.12-arch1-1  | 38        | 0.85%   |
| 5.9.14-arch1-1  | 31        | 0.69%   |
| 5.9.1-arch1-1   | 31        | 0.69%   |
| 6.0.9-arch1-1   | 28        | 0.63%   |
| 5.8.5-arch1-1   | 28        | 0.63%   |
| 5.17.5-arch1-1  | 28        | 0.63%   |
| 6.1.1-arch1-1   | 26        | 0.58%   |
| 5.8.10-arch1-1  | 26        | 0.58%   |
| 6.2.8-arch1-1   | 25        | 0.56%   |
| 5.17.9-arch1-1  | 25        | 0.56%   |
| 6.3.9-arch1-1   | 24        | 0.54%   |
| 6.0.12-arch1-1  | 24        | 0.54%   |
| 5.11.16-arch1-1 | 24        | 0.54%   |
| 6.3.2-arch1-1   | 23        | 0.51%   |
| 6.2.10-arch1-1  | 23        | 0.51%   |
| 5.8.14-arch1-1  | 23        | 0.51%   |
| 5.8.1-arch1-1   | 23        | 0.51%   |
| 5.7.12-arch1-1  | 23        | 0.51%   |
| 5.18.1-arch1-1  | 22        | 0.49%   |
| 5.13.13-arch1-1 | 22        | 0.49%   |
| 5.13.12-arch1-1 | 22        | 0.49%   |
| 5.18.16-arch1-1 | 21        | 0.47%   |
| 6.4.10-arch1-1  | 20        | 0.45%   |
| 6.3.5-arch1-1   | 20        | 0.45%   |
| 5.9.10-arch1-1  | 20        | 0.45%   |
| 5.8.12-arch1-1  | 20        | 0.45%   |
| 6.0.7-arch1-1   | 19        | 0.42%   |
| 5.8.3-arch1-1   | 19        | 0.42%   |
| 5.16.16-arch1-1 | 19        | 0.42%   |
| 5.11.11-arch1-1 | 19        | 0.42%   |
| 6.5.4-arch2-1   | 18        | 0.4%    |
| 6.5.3-arch1-1   | 18        | 0.4%    |
| 6.3.6-arch1-1   | 18        | 0.4%    |
| 6.0.10-arch2-1  | 18        | 0.4%    |
| 5.9.11-arch2-1  | 18        | 0.4%    |
| 5.19.13-arch1-1 | 18        | 0.4%    |
| 5.16.2-arch1-1  | 18        | 0.4%    |
| 5.12.15-arch1-1 | 18        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 1.45%   |
| 6.0.2   | 60        | 1.34%   |
| 6.4.12  | 45        | 1.01%   |
| 5.9.1   | 40        | 0.89%   |
| 5.9.14  | 38        | 0.85%   |
| 5.8.5   | 38        | 0.85%   |
| 5.17.5  | 38        | 0.85%   |
| 6.3.1   | 36        | 0.8%    |
| 6.0.9   | 34        | 0.76%   |
| 6.3.2   | 31        | 0.69%   |
| 6.1.9   | 31        | 0.69%   |
| 6.1.1   | 31        | 0.69%   |
| 5.13.13 | 31        | 0.69%   |
| 6.3.5   | 30        | 0.67%   |
| 6.2.8   | 30        | 0.67%   |
| 5.8.14  | 30        | 0.67%   |
| 5.17.9  | 30        | 0.67%   |
| 6.0.12  | 29        | 0.65%   |
| 5.8.10  | 29        | 0.65%   |
| 6.3.9   | 28        | 0.63%   |
| 6.2.10  | 28        | 0.63%   |
| 5.18.16 | 27        | 0.6%    |
| 6.4.3   | 26        | 0.58%   |
| 6.2.2   | 26        | 0.58%   |
| 5.8.12  | 26        | 0.58%   |
| 5.8.1   | 26        | 0.58%   |
| 5.18.1  | 26        | 0.58%   |
| 5.16.2  | 26        | 0.58%   |
| 5.13.12 | 26        | 0.58%   |
| 5.11.16 | 26        | 0.58%   |
| 6.4.10  | 25        | 0.56%   |
| 6.1.12  | 25        | 0.56%   |
| 6.0.11  | 25        | 0.56%   |
| 5.7.12  | 25        | 0.56%   |
| 6.4.7   | 24        | 0.54%   |
| 5.19.13 | 24        | 0.54%   |
| 5.16.16 | 24        | 0.54%   |
| 5.14.8  | 24        | 0.54%   |
| 5.11.2  | 24        | 0.54%   |
| 5.10.16 | 24        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 266       | 6.18%   |
| 5.15    | 266       | 6.18%   |
| 6.0     | 245       | 5.7%    |
| 5.8     | 232       | 5.39%   |
| 6.4     | 229       | 5.32%   |
| 6.2     | 224       | 5.21%   |
| 5.18    | 219       | 5.09%   |
| 6.3     | 213       | 4.95%   |
| 5.9     | 208       | 4.84%   |
| 5.17    | 198       | 4.6%    |
| 5.4     | 193       | 4.49%   |
| 5.16    | 188       | 4.37%   |
| 5.10    | 182       | 4.23%   |
| 5.19    | 177       | 4.12%   |
| 5.11    | 168       | 3.91%   |
| 5.12    | 153       | 3.56%   |
| 5.13    | 142       | 3.3%    |
| 5.7     | 138       | 3.21%   |
| 5.6     | 135       | 3.14%   |
| 5.14    | 129       | 3%      |
| 5.5     | 93        | 2.16%   |
| 6.5     | 68        | 1.58%   |
| 5.3     | 64        | 1.49%   |
| 5.2     | 33        | 0.77%   |
| 4.19    | 26        | 0.6%    |
| 5.0     | 19        | 0.44%   |
| 5.1     | 16        | 0.37%   |
| 4.18    | 16        | 0.37%   |
| 4.17    | 12        | 0.28%   |
| 4.20    | 9         | 0.21%   |
| 4.14    | 9         | 0.21%   |
| 4.15    | 5         | 0.12%   |
| 4.9     | 4         | 0.09%   |
| 4.7     | 4         | 0.09%   |
| 4.16    | 4         | 0.09%   |
| 4.6     | 3         | 0.07%   |
| 4.4     | 3         | 0.07%   |
| 4.8     | 2         | 0.05%   |
| 4.13    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3774      | 99.89%  |
| i686   | 4         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1300      | 33.04%  |
| KDE5                     | 1033      | 26.25%  |
| Unknown                  | 470       | 11.94%  |
| XFCE                     | 294       | 7.47%   |
| i3                       | 213       | 5.41%   |
| KDE                      | 146       | 3.71%   |
| sway                     | 61        | 1.55%   |
| X-Cinnamon               | 49        | 1.25%   |
| MATE                     | 45        | 1.14%   |
| Budgie                   | 42        | 1.07%   |
| Cinnamon                 | 41        | 1.04%   |
| Hyprland                 | 37        | 0.94%   |
| LXQt                     | 35        | 0.89%   |
| awesome                  | 26        | 0.66%   |
| Deepin                   | 24        | 0.61%   |
| bspwm                    | 23        | 0.58%   |
| LXDE                     | 18        | 0.46%   |
| xmonad                   | 9         | 0.23%   |
| Unity                    | 9         | 0.23%   |
| qtile                    | 9         | 0.23%   |
| GNOME Flashback          | 9         | 0.23%   |
| DWM                      | 9         | 0.23%   |
| openbox                  | 6         | 0.15%   |
| GNOME Classic            | 5         | 0.13%   |
| Enlightenment            | 5         | 0.13%   |
| i3-with-shmlog           | 3         | 0.08%   |
| LeftWM                   | 2         | 0.05%   |
| X-Generic                | 1         | 0.03%   |
| river                    | 1         | 0.03%   |
| Pantheon                 | 1         | 0.03%   |
| jwm                      | 1         | 0.03%   |
| instantwm                | 1         | 0.03%   |
| ICEWM                    | 1         | 0.03%   |
| herbstluftwm             | 1         | 0.03%   |
| GNOME-Classic            | 1         | 0.03%   |
| dusk                     | 1         | 0.03%   |
| default                  | 1         | 0.03%   |
| chadwm                   | 1         | 0.03%   |
| /usr/bin/openbox-session | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2199      | 56.21%  |
| Wayland | 1124      | 28.73%  |
| Tty     | 316       | 8.08%   |
| Unknown | 273       | 6.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1595      | 40.92%  |
| SDDM    | 941       | 24.14%  |
| GDM     | 579       | 14.85%  |
| LightDM | 459       | 11.78%  |
| TDM     | 188       | 4.82%   |
| Ly      | 40        | 1.03%   |
| XDM     | 29        | 0.74%   |
| LXDM    | 26        | 0.67%   |
| SLiM    | 17        | 0.44%   |
| GREETD  | 10        | 0.26%   |
| LY-DM   | 5         | 0.13%   |
| EMPTTY  | 5         | 0.13%   |
| NODM    | 3         | 0.08%   |
| MDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1874      | 48.56%  |
| Unknown | 371       | 9.61%   |
| en_GB   | 221       | 5.73%   |
| C       | 213       | 5.52%   |
| it_IT   | 130       | 3.37%   |
| de_DE   | 124       | 3.21%   |
| ru_RU   | 109       | 2.82%   |
| pt_BR   | 109       | 2.82%   |
| fr_FR   | 100       | 2.59%   |
| zh_CN   | 57        | 1.48%   |
| en_IN   | 48        | 1.24%   |
| pl_PL   | 46        | 1.19%   |
| en_CA   | 43        | 1.11%   |
| es_ES   | 40        | 1.04%   |
| en_AU   | 31        | 0.8%    |
| es_MX   | 20        | 0.52%   |
| es_AR   | 15        | 0.39%   |
| en_IE   | 14        | 0.36%   |
| tr_TR   | 13        | 0.34%   |
| pt_PT   | 13        | 0.34%   |
| en_DK   | 13        | 0.34%   |
| de_AT   | 13        | 0.34%   |
| ja_JP   | 9         | 0.23%   |
| hu_HU   | 9         | 0.23%   |
| es_CO   | 9         | 0.23%   |
| es_CL   | 9         | 0.23%   |
| nl_NL   | 8         | 0.21%   |
| en_NZ   | 8         | 0.21%   |
| zh_TW   | 7         | 0.18%   |
| ru_UA   | 7         | 0.18%   |
| en_ZA   | 7         | 0.18%   |
| en_SG   | 7         | 0.18%   |
| en_AG   | 7         | 0.18%   |
| cs_CZ   | 7         | 0.18%   |
| fr_CA   | 6         | 0.16%   |
| es_PE   | 6         | 0.16%   |
| lv_LV   | 5         | 0.13%   |
| en_DE   | 5         | 0.13%   |
| en-US   | 5         | 0.13%   |
| ca_ES   | 5         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2414      | 62.62%  |
| BIOS | 1441      | 37.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 2721      | 71.12%  |
| Btrfs               | 798       | 20.86%  |
| Unknown             | 112       | 2.93%   |
| Xfs                 | 86        | 2.25%   |
| F2fs                | 45        | 1.18%   |
| Overlay             | 25        | 0.65%   |
| Zfs                 | 20        | 0.52%   |
| Tmpfs               | 8         | 0.21%   |
| XXXXX               | 3         | 0.08%   |
| Ext2                | 3         | 0.08%   |
| XXX4                | 2         | 0.05%   |
| Jfs                 | 1         | 0.03%   |
| Fuse.fuse-overlayfs | 1         | 0.03%   |
| Aufs                | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2421      | 63.23%  |
| Unknown | 1096      | 28.62%  |
| MBR     | 312       | 8.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3437      | 90.07%  |
| Yes       | 379       | 9.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2826      | 73.75%  |
| Yes       | 1006      | 26.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1094      | 28.96%  |
| Dell                   | 603       | 15.96%  |
| Hewlett-Packard        | 514       | 13.61%  |
| ASUSTek Computer       | 461       | 12.2%   |
| Acer                   | 299       | 7.91%   |
| MSI                    | 113       | 2.99%   |
| HUAWEI                 | 73        | 1.93%   |
| Apple                  | 73        | 1.93%   |
| Samsung Electronics    | 52        | 1.38%   |
| Toshiba                | 47        | 1.24%   |
| Notebook               | 34        | 0.9%    |
| Timi                   | 32        | 0.85%   |
| Google                 | 28        | 0.74%   |
| Sony                   | 23        | 0.61%   |
| TUXEDO                 | 22        | 0.58%   |
| Framework              | 20        | 0.53%   |
| Alienware              | 19        | 0.5%    |
| Fujitsu                | 17        | 0.45%   |
| Razer                  | 15        | 0.4%    |
| Unknown                | 13        | 0.34%   |
| LG Electronics         | 11        | 0.29%   |
| Gigabyte Technology    | 11        | 0.29%   |
| Avell High Performance | 11        | 0.29%   |
| System76               | 10        | 0.26%   |
| Schenker               | 10        | 0.26%   |
| Packard Bell           | 8         | 0.21%   |
| MECHREVO               | 8         | 0.21%   |
| Chuwi                  | 8         | 0.21%   |
| Medion                 | 7         | 0.19%   |
| Intel                  | 7         | 0.19%   |
| HONOR                  | 6         | 0.16%   |
| GPD                    | 6         | 0.16%   |
| Positivo               | 5         | 0.13%   |
| Monster                | 5         | 0.13%   |
| Intel Client Systems   | 5         | 0.13%   |
| Valve                  | 4         | 0.11%   |
| Teclast                | 4         | 0.11%   |
| Star Labs              | 4         | 0.11%   |
| SLIMBOOK               | 4         | 0.11%   |
| PC Specialist          | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 34        | 0.9%    |
| Dell XPS 15 9570                | 18        | 0.48%   |
| Dell XPS 15 9500                | 18        | 0.48%   |
| HP Notebook                     | 16        | 0.42%   |
| Framework Laptop                | 16        | 0.42%   |
| Dell XPS 13 9360                | 14        | 0.37%   |
| Dell XPS 13 9380                | 11        | 0.29%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 10        | 0.26%   |
| HUAWEI NBLK-WAX9X               | 10        | 0.26%   |
| Dell XPS 15 7590                | 10        | 0.26%   |
| Dell XPS 13 9310                | 10        | 0.26%   |
| Dell Latitude E6430             | 10        | 0.26%   |
| Dell Inspiron 15 7000 Gaming    | 10        | 0.26%   |
| ASUS ROG Strix G513QY_G513QY    | 10        | 0.26%   |
| HP Pavilion dv6                 | 9         | 0.24%   |
| HP EliteBook 840 G6             | 9         | 0.24%   |
| Dell XPS 13 9370                | 9         | 0.24%   |
| Dell XPS 13 9350                | 9         | 0.24%   |
| Dell Inspiron 5570              | 9         | 0.24%   |
| Lenovo IdeaPad 5 14ARE05 81YM   | 8         | 0.21%   |
| HUAWEI BOHK-WAX9X               | 8         | 0.21%   |
| HP Pavilion Notebook            | 8         | 0.21%   |
| HP EliteBook 840 G5             | 8         | 0.21%   |
| Dell Latitude E7450             | 8         | 0.21%   |
| Dell Latitude 5480              | 8         | 0.21%   |
| ASUS TUF Gaming FX505DT_FX505DT | 8         | 0.21%   |
| Acer Nitro AN515-45             | 8         | 0.21%   |
| Acer Aspire E5-571              | 8         | 0.21%   |
| Lenovo Legion Y530-15ICH 81FV   | 7         | 0.19%   |
| Lenovo Legion 5 15ARH05 82B5    | 7         | 0.19%   |
| HP Pavilion g6                  | 7         | 0.19%   |
| HP Laptop 15-da0xxx             | 7         | 0.19%   |
| HP 250 G6 Notebook PC           | 7         | 0.19%   |
| Dell XPS 15 9560                | 7         | 0.19%   |
| Dell XPS 13 7390                | 7         | 0.19%   |
| Dell Precision 7540             | 7         | 0.19%   |
| Dell Latitude E5470             | 7         | 0.19%   |
| Dell G3 3579                    | 7         | 0.19%   |
| Dell G3 3500                    | 7         | 0.19%   |
| Acer Swift SF314-43             | 7         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 645       | 17.07%  |
| Lenovo IdeaPad     | 216       | 5.72%   |
| Acer Aspire        | 170       | 4.5%    |
| Dell Latitude      | 163       | 4.31%   |
| Dell Inspiron      | 162       | 4.29%   |
| Dell XPS           | 151       | 4%      |
| HP Pavilion        | 112       | 2.96%   |
| HP EliteBook       | 105       | 2.78%   |
| Lenovo Legion      | 77        | 2.04%   |
| HP Laptop          | 77        | 2.04%   |
| ASUS VivoBook      | 76        | 2.01%   |
| ASUS ROG           | 72        | 1.91%   |
| HP ProBook         | 62        | 1.64%   |
| Dell Precision     | 51        | 1.35%   |
| Acer Nitro         | 49        | 1.3%    |
| ASUS ASUS          | 46        | 1.22%   |
| Acer Swift         | 40        | 1.06%   |
| Toshiba Satellite  | 38        | 1.01%   |
| ASUS ZenBook       | 38        | 1.01%   |
| Lenovo ThinkBook   | 35        | 0.93%   |
| Unknown            | 34        | 0.9%    |
| ASUS TUF           | 33        | 0.87%   |
| Dell Vostro        | 31        | 0.82%   |
| HP OMEN            | 26        | 0.69%   |
| HP ENVY            | 24        | 0.64%   |
| Lenovo Yoga        | 21        | 0.56%   |
| Framework Laptop   | 20        | 0.53%   |
| Dell G3            | 18        | 0.48%   |
| MSI Modern         | 16        | 0.42%   |
| HP Notebook        | 16        | 0.42%   |
| Fujitsu LIFEBOOK   | 16        | 0.42%   |
| Razer Blade        | 15        | 0.4%    |
| HP 250             | 15        | 0.4%    |
| HP ZBook           | 13        | 0.34%   |
| Apple MacBookPro11 | 12        | 0.32%   |
| Acer Predator      | 12        | 0.32%   |
| HUAWEI NBLK-WAX9X  | 10        | 0.26%   |
| Timi RedmiBook     | 9         | 0.24%   |
| HP 255             | 9         | 0.24%   |
| ASUS Strix         | 9         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 493       | 13.05%  |
| 2020    | 491       | 13%     |
| 2021    | 463       | 12.26%  |
| 2018    | 424       | 11.22%  |
| 2017    | 279       | 7.38%   |
| 2022    | 213       | 5.64%   |
| 2012    | 206       | 5.45%   |
| 2015    | 204       | 5.4%    |
| 2016    | 202       | 5.35%   |
| 2013    | 190       | 5.03%   |
| 2014    | 180       | 4.76%   |
| 2011    | 164       | 4.34%   |
| 2010    | 99        | 2.62%   |
| 2008    | 64        | 1.69%   |
| 2009    | 45        | 1.19%   |
| 2023    | 44        | 1.16%   |
| 2007    | 12        | 0.32%   |
| 2006    | 4         | 0.11%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3778      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3733      | 98.57%  |
| Enabled  | 54        | 1.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3728      | 98.68%  |
| Yes  | 50        | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1003      | 26.24%  |
| 16.01-24.0  | 912       | 23.86%  |
| 8.01-16.0   | 866       | 22.66%  |
| 3.01-4.0    | 400       | 10.47%  |
| 32.01-64.0  | 391       | 10.23%  |
| 24.01-32.0  | 81        | 2.12%   |
| 64.01-256.0 | 78        | 2.04%   |
| 1.01-2.0    | 57        | 1.49%   |
| 2.01-3.0    | 28        | 0.73%   |
| 0.51-1.0    | 6         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1046      | 25.04%  |
| 1.01-2.0   | 968       | 23.17%  |
| 4.01-8.0   | 917       | 21.95%  |
| 3.01-4.0   | 725       | 17.35%  |
| 8.01-16.0  | 281       | 6.73%   |
| 0.51-1.0   | 159       | 3.81%   |
| 0.01-0.5   | 36        | 0.86%   |
| 16.01-24.0 | 29        | 0.69%   |
| 24.01-32.0 | 14        | 0.34%   |
| 32.01-64.0 | 3         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2639      | 68.71%  |
| 2      | 1032      | 26.87%  |
| 3      | 138       | 3.59%   |
| 4      | 14        | 0.36%   |
| 0      | 14        | 0.36%   |
| 5      | 3         | 0.08%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3073      | 81.06%  |
| Yes       | 718       | 18.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2893      | 76.23%  |
| No        | 902       | 23.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3740      | 98.89%  |
| No        | 42        | 1.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3281      | 86.03%  |
| No        | 533       | 13.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 628       | 16.51%  |
| Germany     | 326       | 8.57%   |
| Russia      | 242       | 6.36%   |
| Italy       | 224       | 5.89%   |
| Brazil      | 207       | 5.44%   |
| France      | 183       | 4.81%   |
| India       | 158       | 4.15%   |
| UK          | 130       | 3.42%   |
| Poland      | 106       | 2.79%   |
| Canada      | 99        | 2.6%    |
| Spain       | 84        | 2.21%   |
| China       | 80        | 2.1%    |
| Netherlands | 72        | 1.89%   |
| Turkey      | 60        | 1.58%   |
| Australia   | 55        | 1.45%   |
| Austria     | 49        | 1.29%   |
| Ukraine     | 44        | 1.16%   |
| Sweden      | 43        | 1.13%   |
| Indonesia   | 42        | 1.1%    |
| Mexico      | 36        | 0.95%   |
| Portugal    | 35        | 0.92%   |
| Romania     | 34        | 0.89%   |
| Belgium     | 34        | 0.89%   |
| Czechia     | 33        | 0.87%   |
| Argentina   | 32        | 0.84%   |
| Switzerland | 29        | 0.76%   |
| Vietnam     | 28        | 0.74%   |
| Denmark     | 27        | 0.71%   |
| Japan       | 25        | 0.66%   |
| Iran        | 25        | 0.66%   |
| Hungary     | 25        | 0.66%   |
| Finland     | 24        | 0.63%   |
| New Zealand | 23        | 0.6%    |
| Colombia    | 23        | 0.6%    |
| Chile       | 22        | 0.58%   |
| Hong Kong   | 20        | 0.53%   |
| Greece      | 20        | 0.53%   |
| Peru        | 19        | 0.5%    |
| Taiwan      | 18        | 0.47%   |
| Belarus     | 18        | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 69        | 1.7%    |
| Milan             | 39        | 0.96%   |
| Paris             | 38        | 0.94%   |
| Berlin            | 38        | 0.94%   |
| Sao Paulo         | 37        | 0.91%   |
| St Petersburg     | 35        | 0.86%   |
| Warsaw            | 30        | 0.74%   |
| Munich            | 26        | 0.64%   |
| Vienna            | 25        | 0.62%   |
| Melbourne         | 23        | 0.57%   |
| Los Angeles       | 23        | 0.57%   |
| Bengaluru         | 23        | 0.57%   |
| Valencia          | 21        | 0.52%   |
| Istanbul          | 21        | 0.52%   |
| Amsterdam         | 19        | 0.47%   |
| Sydney            | 17        | 0.42%   |
| Kyiv              | 17        | 0.42%   |
| Prague            | 16        | 0.4%    |
| Montreal          | 16        | 0.4%    |
| Frankfurt am Main | 16        | 0.4%    |
| Tehran            | 15        | 0.37%   |
| Rome              | 14        | 0.35%   |
| Phoenix           | 14        | 0.35%   |
| Mexico City       | 14        | 0.35%   |
| Madrid            | 14        | 0.35%   |
| Lima              | 14        | 0.35%   |
| Jakarta           | 14        | 0.35%   |
| Helsinki          | 14        | 0.35%   |
| Budapest          | 14        | 0.35%   |
| New York          | 13        | 0.32%   |
| Hamburg           | 13        | 0.32%   |
| Curitiba          | 13        | 0.32%   |
| Bogotá           | 13        | 0.32%   |
| Beijing           | 13        | 0.32%   |
| Turin             | 12        | 0.3%    |
| Singapore         | 12        | 0.3%    |
| Cologne           | 12        | 0.3%    |
| Central           | 12        | 0.3%    |
| Buenos Aires      | 12        | 0.3%    |
| Seattle           | 11        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1052      | 1404   | 21.24%  |
| WDC                            | 477       | 584    | 9.63%   |
| Sandisk                        | 423       | 508    | 8.54%   |
| Seagate                        | 402       | 485    | 8.11%   |
| Toshiba                        | 324       | 374    | 6.54%   |
| SK hynix                       | 285       | 347    | 5.75%   |
| Kingston                       | 234       | 295    | 4.72%   |
| Unknown                        | 197       | 234    | 3.98%   |
| Intel                          | 187       | 244    | 3.77%   |
| Micron Technology              | 178       | 216    | 3.59%   |
| Crucial                        | 136       | 196    | 2.75%   |
| HGST                           | 124       | 135    | 2.5%    |
| A-DATA Technology              | 67        | 93     | 1.35%   |
| Hitachi                        | 65        | 66     | 1.31%   |
| KIOXIA                         | 54        | 61     | 1.09%   |
| Apple                          | 46        | 59     | 0.93%   |
| Phison Electronics             | 40        | 46     | 0.81%   |
| Phison                         | 32        | 37     | 0.65%   |
| LITEON                         | 30        | 31     | 0.61%   |
| Kingston Technology Company    | 30        | 30     | 0.61%   |
| Silicon Motion                 | 29        | 30     | 0.59%   |
| Micron/Crucial Technology      | 27        | 29     | 0.55%   |
| China                          | 27        | 33     | 0.55%   |
| Transcend                      | 26        | 28     | 0.52%   |
| SPCC                           | 20        | 22     | 0.4%    |
| Lenovo                         | 17        | 22     | 0.34%   |
| PNY                            | 16        | 20     | 0.32%   |
| JMicron Technology             | 16        | 17     | 0.32%   |
| ADATA Technology               | 14        | 16     | 0.28%   |
| Yangtze Memory Technologies    | 12        | 12     | 0.24%   |
| LITEONIT                       | 12        | 12     | 0.24%   |
| GOODRAM                        | 12        | 12     | 0.24%   |
| KingSpec                       | 11        | 12     | 0.22%   |
| Intenso                        | 11        | 13     | 0.22%   |
| OCZ                            | 10        | 10     | 0.2%    |
| Union Memory                   | 9         | 9      | 0.18%   |
| Solid State Storage Technology | 9         | 9      | 0.18%   |
| Patriot                        | 9         | 10     | 0.18%   |
| MAXIO Technology (Hangzhou)    | 9         | 10     | 0.18%   |
| Union Memory (Shenzhen)        | 8         | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 129       | 2.49%   |
| Seagate ST1000LM035-1RK172 1TB                      | 91        | 1.75%   |
| Samsung NVMe SSD Drive 512GB                        | 63        | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 62        | 1.2%    |
| HGST HTS721010A9E630 1TB                            | 49        | 0.94%   |
| SanDisk NVMe SSD Drive 512GB                        | 46        | 0.89%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 43        | 0.83%   |
| Toshiba MQ04ABF100 1TB                              | 42        | 0.81%   |
| Toshiba MQ01ABD100 1TB                              | 40        | 0.77%   |
| SK hynix NVMe SSD Drive 512GB                       | 39        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 38        | 0.73%   |
| Unknown MMC Card  32GB                              | 36        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 36        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 36        | 0.69%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 35        | 0.67%   |
| Samsung SSD 850 EVO 500GB                           | 30        | 0.58%   |
| Unknown MMC Card  64GB                              | 29        | 0.56%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 29        | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB                      | 26        | 0.5%    |
| Intel SSDPEKNU512GZ 512GB                           | 26        | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 24        | 0.46%   |
| SanDisk NVMe SSD Drive 256GB                        | 24        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 24        | 0.46%   |
| Unknown MMC Card  128GB                             | 23        | 0.44%   |
| Seagate ST2000LM007-1R8174 2TB                      | 23        | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                          | 22        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 22        | 0.42%   |
| Kingston SA400S37480G 480GB SSD                     | 22        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                         | 22        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.4%    |
| Intel SSD 660P Series 1024GB                        | 21        | 0.4%    |
| Toshiba NVMe SSD Drive 512GB                        | 20        | 0.39%   |
| Toshiba MQ01ABF050 500GB                            | 20        | 0.39%   |
| Seagate ST500LT012-1DG142 500GB                     | 20        | 0.39%   |
| Seagate ST1000LX015-1U7172 1TB                      | 20        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB                      | 20        | 0.39%   |
| Samsung SSD 850 EVO 250GB                           | 20        | 0.39%   |
| Samsung NVMe SSD Drive 1TB                          | 20        | 0.39%   |
| HGST HTS541010A9E680 1TB                            | 20        | 0.39%   |
| Samsung SSD 980 1TB                                 | 18        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 394       | 475    | 36.08%  |
| WDC                 | 277       | 316    | 25.37%  |
| Toshiba             | 177       | 199    | 16.21%  |
| HGST                | 124       | 135    | 11.36%  |
| Hitachi             | 65        | 66     | 5.95%   |
| Samsung Electronics | 11        | 11     | 1.01%   |
| Unknown             | 10        | 13     | 0.92%   |
| External            | 5         | 6      | 0.46%   |
| Fujitsu             | 4         | 4      | 0.37%   |
| SABRENT             | 3         | 3      | 0.27%   |
| HGST HTS            | 3         | 3      | 0.27%   |
| Apple               | 3         | 3      | 0.27%   |
| USB3.0              | 2         | 2      | 0.18%   |
| SSK                 | 2         | 2      | 0.18%   |
| SAGE                | 2         | 3      | 0.18%   |
| Generic-            | 2         | 3      | 0.18%   |
| ASMT                | 2         | 3      | 0.18%   |
| ACASIS              | 2         | 2      | 0.18%   |
| USB                 | 1         | 1      | 0.09%   |
| Pioneer             | 1         | 1      | 0.09%   |
| NeoTech             | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 361       | 446    | 25.33%  |
| SanDisk             | 157       | 179    | 11.02%  |
| Kingston            | 155       | 191    | 10.88%  |
| Crucial             | 122       | 172    | 8.56%   |
| WDC                 | 87        | 114    | 6.11%   |
| A-DATA Technology   | 42        | 61     | 2.95%   |
| Toshiba             | 36        | 44     | 2.53%   |
| SK hynix            | 36        | 44     | 2.53%   |
| Micron Technology   | 36        | 43     | 2.53%   |
| Intel               | 36        | 40     | 2.53%   |
| LITEON              | 27        | 28     | 1.89%   |
| China               | 27        | 33     | 1.89%   |
| Apple               | 27        | 28     | 1.89%   |
| Transcend           | 25        | 27     | 1.75%   |
| SPCC                | 16        | 17     | 1.12%   |
| PNY                 | 15        | 19     | 1.05%   |
| LITEONIT            | 12        | 12     | 0.84%   |
| KingSpec            | 11        | 12     | 0.77%   |
| JMicron Technology  | 11        | 13     | 0.77%   |
| Intenso             | 11        | 13     | 0.77%   |
| GOODRAM             | 11        | 11     | 0.77%   |
| OCZ                 | 10        | 10     | 0.7%    |
| Patriot             | 9         | 10     | 0.63%   |
| Plextor             | 8         | 8      | 0.56%   |
| FORESEE             | 6         | 9      | 0.42%   |
| TO Exter            | 5         | 10     | 0.35%   |
| Lexar               | 5         | 11     | 0.35%   |
| Gigabyte Technology | 5         | 5      | 0.35%   |
| ASMT                | 5         | 5      | 0.35%   |
| Team                | 4         | 4      | 0.28%   |
| Mushkin             | 4         | 4      | 0.28%   |
| Hewlett-Packard     | 4         | 5      | 0.28%   |
| BHT                 | 4         | 6      | 0.28%   |
| Unknown             | 4         | 4      | 0.28%   |
| Unknown             | 3         | 3      | 0.21%   |
| Phison              | 3         | 3      | 0.21%   |
| Netac               | 3         | 3      | 0.21%   |
| HS-SSD-E100         | 3         | 4      | 0.21%   |
| BIWIN               | 3         | 3      | 0.21%   |
| Apacer              | 3         | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2039      | 2837   | 43.86%  |
| SSD     | 1317      | 1739   | 28.33%  |
| HDD     | 1061      | 1253   | 22.82%  |
| MMC     | 186       | 219    | 4%      |
| Unknown | 46        | 49     | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2037      | 2828   | 46.32%  |
| SATA | 2011      | 2845   | 45.73%  |
| MMC  | 186       | 219    | 4.23%   |
| SAS  | 164       | 205    | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1418      | 1878   | 60.57%  |
| 0.51-1.0   | 827       | 992    | 35.33%  |
| 1.01-2.0   | 84        | 109    | 3.59%   |
| 3.01-4.0   | 6         | 7      | 0.26%   |
| 4.01-10.0  | 3         | 3      | 0.13%   |
| 10.01-20.0 | 2         | 2      | 0.09%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1055      | 26.82%  |
| 101-250        | 1016      | 25.83%  |
| 501-1000       | 738       | 18.76%  |
| 1001-2000      | 447       | 11.37%  |
| 51-100         | 168       | 4.27%   |
| More than 3000 | 160       | 4.07%   |
| 2001-3000      | 127       | 3.23%   |
| Unknown        | 96        | 2.44%   |
| 21-50          | 65        | 1.65%   |
| 1-20           | 61        | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 905       | 22%     |
| 101-250        | 789       | 19.18%  |
| 21-50          | 683       | 16.6%   |
| 51-100         | 598       | 14.54%  |
| 251-500        | 524       | 12.74%  |
| 501-1000       | 325       | 7.9%    |
| 1001-2000      | 118       | 2.87%   |
| Unknown        | 96        | 2.33%   |
| More than 3000 | 39        | 0.95%   |
| 2001-3000      | 36        | 0.88%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                        | 12        | 12     | 5.02%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 11        | 11     | 4.6%    |
| HGST HTS541010A9E680 1TB                                        | 6         | 6      | 2.51%   |
| Seagate ST9500325AS 500GB                                       | 5         | 5      | 2.09%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 5         | 5      | 2.09%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 2.09%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 1.67%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 4         | 5      | 1.67%   |
| HGST HTS725050A7E630 500GB                                      | 4         | 4      | 1.67%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 3         | 3      | 1.26%   |
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 1.26%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 3         | 3      | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 3      | 1.26%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 3         | 3      | 1.26%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 4      | 1.26%   |
| Hitachi HTS545025B9A300 250GB                                   | 3         | 3      | 1.26%   |
| Toshiba MQ01ABD100 1TB                                          | 2         | 2      | 0.84%   |
| Toshiba MK3276GSX 320GB                                         | 2         | 2      | 0.84%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 2         | 2      | 0.84%   |
| Seagate ST9320325AS 320GB                                       | 2         | 2      | 0.84%   |
| Seagate ST9250315AS 250GB                                       | 2         | 2      | 0.84%   |
| Seagate ST500LT012-9WS142 500GB                                 | 2         | 2      | 0.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB                             | 2         | 2      | 0.84%   |
| Seagate ST500LM000-SSHD-8GB                                     | 2         | 2      | 0.84%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 2         | 2      | 0.84%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 2         | 2      | 0.84%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 2         | 2      | 0.84%   |
| Seagate ST1000LM014-1EJ164 1TB                                  | 2         | 2      | 0.84%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                               | 2         | 2      | 0.84%   |
| Samsung Electronics SSD 970 EVO 2TB                             | 2         | 2      | 0.84%   |
| LITEON CV8-8E128-HP 128GB SSD                                   | 2         | 2      | 0.84%   |
| Intel SSDSC2BF240A4L 240GB                                      | 2         | 2      | 0.84%   |
| Hitachi HTS723232A7A364 320GB                                   | 2         | 2      | 0.84%   |
| Hitachi HTS545050A7E380 500GB                                   | 2         | 3      | 0.84%   |
| Hitachi HTS541680J9SA00 80GB                                    | 2         | 2      | 0.84%   |
| Hitachi HTS541616J9SA00 160GB                                   | 2         | 2      | 0.84%   |
| HGST HTS545050A7E380 500GB                                      | 2         | 2      | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 0.42%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                  | 1         | 1      | 0.42%   |
| WDC WD7500BPKT-00PK4T0 752GB                                    | 1         | 1      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 67        | 71     | 28.03%  |
| HGST                  | 32        | 33     | 13.39%  |
| WDC                   | 28        | 30     | 11.72%  |
| Toshiba               | 23        | 26     | 9.62%   |
| Hitachi               | 20        | 21     | 8.37%   |
| Samsung Electronics   | 13        | 18     | 5.44%   |
| SK hynix              | 12        | 13     | 5.02%   |
| Intel                 | 8         | 9      | 3.35%   |
| SanDisk               | 6         | 7      | 2.51%   |
| Kingston              | 5         | 5      | 2.09%   |
| Crucial               | 5         | 5      | 2.09%   |
| Micron Technology     | 4         | 5      | 1.67%   |
| LITEON                | 3         | 3      | 1.26%   |
| A-DATA Technology     | 3         | 3      | 1.26%   |
| China                 | 2         | 2      | 0.84%   |
| ASMT                  | 2         | 2      | 0.84%   |
| VNYEZ                 | 1         | 1      | 0.42%   |
| SSSTC                 | 1         | 1      | 0.42%   |
| Realtek Semiconductor | 1         | 1      | 0.42%   |
| OCZ                   | 1         | 1      | 0.42%   |
| KingSpec              | 1         | 1      | 0.42%   |
| Apple                 | 1         | 1      | 0.42%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 67        | 71     | 40.61%  |
| HGST    | 32        | 33     | 19.39%  |
| WDC     | 26        | 28     | 15.76%  |
| Hitachi | 20        | 21     | 12.12%  |
| Toshiba | 18        | 21     | 10.91%  |
| ASMT    | 1         | 1      | 0.61%   |
| Apple   | 1         | 1      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 164       | 176    | 68.91%  |
| SSD  | 57        | 62     | 23.95%  |
| NVMe | 17        | 21     | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 16.67%  |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB    | 1         | 1      | 16.67%  |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 16.67%  |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 16.67%  |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 2         | 3      | 33.33%  |
| WDC                     | 1         | 1      | 16.67%  |
| Union Memory (Shenzhen) | 1         | 1      | 16.67%  |
| Phison                  | 1         | 1      | 16.67%  |
| Kingston                | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1948      | 2952   | 47.36%  |
| Detected | 1925      | 2879   | 46.8%   |
| Malfunc  | 234       | 259    | 5.69%   |
| Failed   | 6         | 7      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2267      | 47.04%  |
| Samsung Electronics              | 721       | 14.96%  |
| AMD                              | 464       | 9.63%   |
| SanDisk                          | 362       | 7.51%   |
| SK hynix                         | 246       | 5.1%    |
| Micron Technology                | 143       | 2.97%   |
| Toshiba America Info Systems     | 111       | 2.3%    |
| Kingston Technology Company      | 108       | 2.24%   |
| Phison Electronics               | 79        | 1.64%   |
| KIOXIA                           | 55        | 1.14%   |
| Micron/Crucial Technology        | 42        | 0.87%   |
| Silicon Motion                   | 36        | 0.75%   |
| ADATA Technology                 | 35        | 0.73%   |
| Union Memory (Shenzhen)          | 22        | 0.46%   |
| Solid State Storage Technology   | 20        | 0.42%   |
| Apple                            | 16        | 0.33%   |
| Lenovo                           | 15        | 0.31%   |
| Yangtze Memory Technologies      | 14        | 0.29%   |
| Realtek Semiconductor            | 13        | 0.27%   |
| Lite-On Technology               | 12        | 0.25%   |
| MAXIO Technology (Hangzhou)      | 9         | 0.19%   |
| Shenzhen Longsys Electronics     | 6         | 0.12%   |
| Nvidia                           | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| Marvell Technology Group         | 3         | 0.06%   |
| Biwin Storage Technology         | 3         | 0.06%   |
| Netac Technology                 | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Transcend                        | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| ASMedia Technology               | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 441       | 8.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 388       | 7.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 317       | 6.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 210       | 4.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 207       | 4.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 175       | 3.5%    |
| Samsung NVMe SSD Controller 980                                                | 163       | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 133       | 2.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 129       | 2.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 122       | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 121       | 2.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 119       | 2.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 109       | 2.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 100       | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 96        | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 90        | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 71        | 1.42%   |
| Intel SSD 660P Series                                                          | 69        | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 63        | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 62        | 1.24%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 60        | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 53        | 1.06%   |
| Intel Tiger Lake-LP SATA Controller                                            | 45        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 43        | 0.86%   |
| Phison E12 NVMe Controller                                                     | 41        | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 40        | 0.8%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 40        | 0.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 38        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 36        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 36        | 0.72%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 35        | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 35        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 35        | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 35        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 34        | 0.68%   |
| SK hynix BC511 NVMe SSD                                                        | 32        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 31        | 0.62%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 31        | 0.62%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 28        | 0.56%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 27        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2345      | 49.07%  |
| NVMe | 2040      | 42.69%  |
| RAID | 343       | 7.18%   |
| IDE  | 51        | 1.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2907      | 76.95%  |
| AMD    | 871       | 23.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 82        | 2.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 80        | 2.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 78        | 2.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 77        | 2.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 76        | 2.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 76        | 2.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 74        | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 69        | 1.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 64        | 1.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 55        | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 52        | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 1.32%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 49        | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 47        | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 45        | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 44        | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 44        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 43        | 1.14%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 43        | 1.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 41        | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 1.01%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 37        | 0.98%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 35        | 0.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 33        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 30        | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 29        | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 27        | 0.71%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 27        | 0.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 27        | 0.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 27        | 0.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 26        | 0.69%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 25        | 0.66%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 25        | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 25        | 0.66%   |
| Intel 12th Gen Core i7-12700H                 | 25        | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1029      | 27.22%  |
| Intel Core i5           | 917       | 24.25%  |
| Other                   | 397       | 10.5%   |
| AMD Ryzen 7             | 279       | 7.38%   |
| AMD Ryzen 5             | 274       | 7.25%   |
| Intel Core i3           | 204       | 5.4%    |
| Intel Celeron           | 109       | 2.88%   |
| Intel Core 2 Duo        | 84        | 2.22%   |
| AMD Ryzen 7 PRO         | 74        | 1.96%   |
| AMD Ryzen 9             | 64        | 1.69%   |
| Intel Pentium           | 51        | 1.35%   |
| Intel Atom              | 37        | 0.98%   |
| AMD Ryzen 3             | 36        | 0.95%   |
| Intel Core i9           | 31        | 0.82%   |
| AMD Ryzen 5 PRO         | 25        | 0.66%   |
| AMD A6                  | 17        | 0.45%   |
| Intel Pentium Silver    | 15        | 0.4%    |
| AMD A4                  | 15        | 0.4%    |
| AMD A10                 | 14        | 0.37%   |
| Intel Xeon              | 12        | 0.32%   |
| AMD A8                  | 12        | 0.32%   |
| AMD E2                  | 10        | 0.26%   |
| Intel Pentium Dual-Core | 7         | 0.19%   |
| Intel Genuine           | 6         | 0.16%   |
| Intel Core m3           | 6         | 0.16%   |
| AMD E1                  | 6         | 0.16%   |
| AMD E                   | 6         | 0.16%   |
| Intel Core 2            | 4         | 0.11%   |
| AMD Athlon              | 4         | 0.11%   |
| AMD A12                 | 4         | 0.11%   |
| Intel Celeron Dual-Core | 3         | 0.08%   |
| Intel Pentium Dual      | 2         | 0.05%   |
| Intel Core m7           | 2         | 0.05%   |
| Intel Core m5           | 2         | 0.05%   |
| Intel Core M            | 2         | 0.05%   |
| AMD Turion Neo X2       | 2         | 0.05%   |
| AMD Phenom II           | 2         | 0.05%   |
| AMD C-60                | 2         | 0.05%   |
| AMD Athlon X2           | 2         | 0.05%   |
| Intel Pentium Gold      | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1413      | 37.37%  |
| 2      | 1342      | 35.49%  |
| 8      | 465       | 12.3%   |
| 6      | 432       | 11.43%  |
| 12     | 39        | 1.03%   |
| 14     | 36        | 0.95%   |
| 10     | 22        | 0.58%   |
| 1      | 22        | 0.58%   |
| 16     | 6         | 0.16%   |
| 24     | 2         | 0.05%   |
| 5      | 1         | 0.03%   |
| 3      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3778      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3257      | 86.12%  |
| 1      | 525       | 13.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3717      | 98.33%  |
| Unknown        | 60        | 1.59%   |
| 32-bit         | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1504      | 38.29%  |
| 0x906ea    | 139       | 3.54%   |
| 0x806ea    | 138       | 3.51%   |
| 0x306a9    | 121       | 3.08%   |
| 0x806ec    | 117       | 2.98%   |
| 0x806c1    | 111       | 2.83%   |
| 0x0a50000c | 109       | 2.77%   |
| 0x206a7    | 105       | 2.67%   |
| 0x406e3    | 100       | 2.55%   |
| 0x306d4    | 90        | 2.29%   |
| 0x40651    | 86        | 2.19%   |
| 0x906e9    | 84        | 2.14%   |
| 0x806e9    | 80        | 2.04%   |
| 0x08108102 | 76        | 1.93%   |
| 0x08600106 | 75        | 1.91%   |
| 0x306c3    | 67        | 1.71%   |
| 0xa0652    | 62        | 1.58%   |
| 0x08108109 | 55        | 1.4%    |
| 0x20655    | 46        | 1.17%   |
| 0x506e3    | 44        | 1.12%   |
| 0x08600104 | 43        | 1.09%   |
| 0x08608103 | 42        | 1.07%   |
| 0x806eb    | 40        | 1.02%   |
| 0x08600103 | 40        | 1.02%   |
| 0x0a404102 | 37        | 0.94%   |
| 0x1067a    | 34        | 0.87%   |
| 0x0810100b | 25        | 0.64%   |
| 0x906a3    | 24        | 0.61%   |
| 0x706e5    | 24        | 0.61%   |
| 0x08608102 | 23        | 0.59%   |
| 0x806d1    | 21        | 0.53%   |
| 0x406c4    | 21        | 0.53%   |
| 0x30678    | 20        | 0.51%   |
| 0x10676    | 19        | 0.48%   |
| 0x906ed    | 18        | 0.46%   |
| 0x706a1    | 16        | 0.41%   |
| 0x506c9    | 16        | 0.41%   |
| 0x20652    | 15        | 0.38%   |
| 0x06006705 | 15        | 0.38%   |
| 0x0a50000d | 13        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 990       | 26.18%  |
| Haswell          | 247       | 6.53%   |
| Skylake          | 240       | 6.35%   |
| Unknown          | 232       | 6.13%   |
| TigerLake        | 218       | 5.76%   |
| Zen 2            | 205       | 5.42%   |
| IvyBridge        | 205       | 5.42%   |
| Zen 3            | 173       | 4.57%   |
| Zen+             | 168       | 4.44%   |
| SandyBridge      | 167       | 4.42%   |
| Broadwell        | 144       | 3.81%   |
| CometLake        | 127       | 3.36%   |
| Penryn           | 83        | 2.19%   |
| Westmere         | 78        | 2.06%   |
| Silvermont       | 78        | 2.06%   |
| IceLake          | 77        | 2.04%   |
| Alderlake Hybrid | 75        | 1.98%   |
| Zen              | 47        | 1.24%   |
| Goldmont plus    | 41        | 1.08%   |
| Excavator        | 39        | 1.03%   |
| Core             | 25        | 0.66%   |
| Goldmont         | 22        | 0.58%   |
| Bobcat           | 17        | 0.45%   |
| Puma             | 14        | 0.37%   |
| Bonnell          | 14        | 0.37%   |
| Nehalem          | 9         | 0.24%   |
| Piledriver       | 8         | 0.21%   |
| Jaguar           | 8         | 0.21%   |
| Tremont          | 7         | 0.19%   |
| K10 Llano        | 7         | 0.19%   |
| K10              | 7         | 0.19%   |
| Steamroller      | 3         | 0.08%   |
| K8 Hammer        | 3         | 0.08%   |
| P6               | 2         | 0.05%   |
| K8 & K10 hybrid  | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2731      | 53.25%  |
| Nvidia                           | 1344      | 26.2%   |
| AMD                              | 1050      | 20.47%  |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 229       | 4.39%   |
| Intel UHD Graphics 620                                                                   | 215       | 4.12%   |
| AMD Renoir                                                                               | 195       | 3.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 194       | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 193       | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 171       | 3.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 160       | 3.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 150       | 2.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 146       | 2.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 139       | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 136       | 2.6%    |
| Intel HD Graphics 620                                                                    | 130       | 2.49%   |
| Intel HD Graphics 5500                                                                   | 123       | 2.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 112       | 2.15%   |
| Intel HD Graphics 630                                                                    | 102       | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 99        | 1.9%    |
| AMD Lucienne                                                                             | 88        | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 86        | 1.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 80        | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 75        | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 75        | 1.44%   |
| AMD Rembrandt [Radeon 680M]                                                              | 65        | 1.24%   |
| Intel HD Graphics 530                                                                    | 63        | 1.21%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 58        | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 57        | 1.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 57        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 54        | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 54        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 52        | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 48        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 42        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 42        | 0.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 41        | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 37        | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 36        | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 35        | 0.67%   |
| Nvidia TU117M                                                                            | 34        | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 34        | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 32        | 0.61%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 31        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1565      | 41.28%  |
| Intel + Nvidia           | 1010      | 26.64%  |
| 1 x AMD                  | 647       | 17.07%  |
| AMD + Nvidia             | 185       | 4.88%   |
| 1 x Nvidia               | 148       | 3.9%    |
| Intel + AMD              | 143       | 3.77%   |
| 2 x AMD                  | 74        | 1.95%   |
| 2 x Intel                | 8         | 0.21%   |
| Other                    | 3         | 0.08%   |
| 1 x SiS                  | 3         | 0.08%   |
| Intel + 2 x Nvidia       | 2         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.05%   |
| 2 x Nvidia               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2965      | 77.78%  |
| Proprietary | 834       | 21.88%  |
| Unknown     | 13        | 0.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2633      | 67.86%  |
| 0.01-0.5   | 403       | 10.39%  |
| 1.01-2.0   | 326       | 8.4%    |
| 3.01-4.0   | 203       | 5.23%   |
| 0.51-1.0   | 146       | 3.76%   |
| 7.01-8.0   | 73        | 1.88%   |
| 5.01-6.0   | 72        | 1.86%   |
| 2.01-3.0   | 12        | 0.31%   |
| 8.01-16.0  | 12        | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 866       | 18.9%   |
| BOE                     | 684       | 14.93%  |
| Chimei Innolux          | 629       | 13.73%  |
| LG Display              | 587       | 12.81%  |
| Samsung Electronics     | 375       | 8.18%   |
| Sharp                   | 194       | 4.23%   |
| Dell                    | 157       | 3.43%   |
| PANDA                   | 116       | 2.53%   |
| Goldstar                | 107       | 2.34%   |
| Lenovo                  | 91        | 1.99%   |
| Apple                   | 75        | 1.64%   |
| Hewlett-Packard         | 66        | 1.44%   |
| AOC                     | 54        | 1.18%   |
| Acer                    | 50        | 1.09%   |
| CSO                     | 46        | 1%      |
| BenQ                    | 46        | 1%      |
| InfoVision              | 45        | 0.98%   |
| Philips                 | 38        | 0.83%   |
| Chi Mei Optoelectronics | 33        | 0.72%   |
| Ancor Communications    | 28        | 0.61%   |
| Iiyama                  | 22        | 0.48%   |
| TMX                     | 21        | 0.46%   |
| ASUSTek Computer        | 17        | 0.37%   |
| Sony                    | 15        | 0.33%   |
| ViewSonic               | 13        | 0.28%   |
| JDI                     | 10        | 0.22%   |
| CPT                     | 10        | 0.22%   |
| MSI                     | 9         | 0.2%    |
| Panasonic               | 8         | 0.17%   |
| NEC Computers           | 8         | 0.17%   |
| LG Philips              | 8         | 0.17%   |
| Eizo                    | 8         | 0.17%   |
| Toshiba                 | 7         | 0.15%   |
| BOE Technology Group    | 7         | 0.15%   |
| Pixio                   | 5         | 0.11%   |
| LGD                     | 5         | 0.11%   |
| InnoLux Display         | 5         | 0.11%   |
| HannStar                | 5         | 0.11%   |
| RTK                     | 4         | 0.09%   |
| Mi                      | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 45        | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 44        | 0.95%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 38        | 0.82%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 34        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 33        | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 27        | 0.58%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 23        | 0.5%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 21        | 0.45%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 20        | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 20        | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 18        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 18        | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 17        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 17        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 15        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 14        | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch     | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 14        | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 13        | 0.28%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 12        | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 12        | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 12        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 12        | 0.26%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 11        | 0.24%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 11        | 0.24%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 11        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2210      | 52%     |
| 1366x768 (WXGA)    | 816       | 19.2%   |
| 3840x2160 (4K)     | 214       | 5.04%   |
| 2560x1440 (QHD)    | 173       | 4.07%   |
| 1600x900 (HD+)     | 142       | 3.34%   |
| 1920x1200 (WUXGA)  | 107       | 2.52%   |
| 2560x1600          | 84        | 1.98%   |
| 1280x800 (WXGA)    | 58        | 1.36%   |
| 2880x1800          | 52        | 1.22%   |
| 1440x900 (WXGA+)   | 43        | 1.01%   |
| 3840x2400          | 36        | 0.85%   |
| 1680x1050 (WSXGA+) | 34        | 0.8%    |
| 3440x1440          | 33        | 0.78%   |
| 2560x1080          | 22        | 0.52%   |
| 3200x1800 (QHD+)   | 21        | 0.49%   |
| 2256x1504          | 21        | 0.49%   |
| 2160x1440          | 20        | 0.47%   |
| 1280x1024 (SXGA)   | 20        | 0.47%   |
| 1360x768           | 15        | 0.35%   |
| 3200x2000          | 10        | 0.24%   |
| 3072x1920          | 10        | 0.24%   |
| 3000x2000          | 10        | 0.24%   |
| 3840x1600          | 9         | 0.21%   |
| Unknown            | 9         | 0.21%   |
| 2240x1400          | 8         | 0.19%   |
| 1024x600           | 8         | 0.19%   |
| 2520x1680          | 6         | 0.14%   |
| 1920x540           | 6         | 0.14%   |
| 3456x2160          | 5         | 0.12%   |
| 1600x1200          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 800x1280           | 4         | 0.09%   |
| 3840x1100          | 3         | 0.07%   |
| 3840x1080          | 3         | 0.07%   |
| 1680x945           | 3         | 0.07%   |
| 2944x1840          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 1920x550           | 2         | 0.05%   |
| 1920x1280          | 2         | 0.05%   |
| 1400x1050          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1765      | 38.53%  |
| 13      | 710       | 15.5%   |
| 14      | 655       | 14.3%   |
| 17      | 224       | 4.89%   |
| 27      | 206       | 4.5%    |
| 24      | 194       | 4.23%   |
| 23      | 136       | 2.97%   |
| 12      | 110       | 2.4%    |
| 21      | 93        | 2.03%   |
| 16      | 87        | 1.9%    |
| 11      | 54        | 1.18%   |
| Unknown | 52        | 1.14%   |
| 34      | 50        | 1.09%   |
| 18      | 37        | 0.81%   |
| 31      | 29        | 0.63%   |
| 19      | 24        | 0.52%   |
| 22      | 19        | 0.41%   |
| 20      | 16        | 0.35%   |
| 10      | 14        | 0.31%   |
| 84      | 10        | 0.22%   |
| 72      | 8         | 0.17%   |
| 54      | 8         | 0.17%   |
| 40      | 8         | 0.17%   |
| 37      | 8         | 0.17%   |
| 28      | 8         | 0.17%   |
| 25      | 8         | 0.17%   |
| 29      | 7         | 0.15%   |
| 32      | 5         | 0.11%   |
| 26      | 5         | 0.11%   |
| 52      | 4         | 0.09%   |
| 48      | 4         | 0.09%   |
| 74      | 2         | 0.04%   |
| 65      | 2         | 0.04%   |
| 42      | 2         | 0.04%   |
| 38      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |
| 3       | 2         | 0.04%   |
| 142     | 1         | 0.02%   |
| 57      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2802      | 61.83%  |
| 201-300        | 532       | 11.74%  |
| 501-600        | 498       | 10.99%  |
| 351-400        | 279       | 6.16%   |
| 401-500        | 174       | 3.84%   |
| 601-700        | 67        | 1.48%   |
| 701-800        | 56        | 1.24%   |
| Unknown        | 52        | 1.15%   |
| 1001-1500      | 22        | 0.49%   |
| 801-900        | 20        | 0.44%   |
| 1501-2000      | 20        | 0.44%   |
| 1-100          | 4         | 0.09%   |
| 901-1000       | 3         | 0.07%   |
| 101-200        | 2         | 0.04%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3296      | 82.92%  |
| 16/10   | 457       | 11.5%   |
| 3/2     | 70        | 1.76%   |
| 21/9    | 64        | 1.61%   |
| Unknown | 34        | 0.86%   |
| 5/4     | 20        | 0.5%    |
| 4/3     | 12        | 0.3%    |
| 32/9    | 8         | 0.2%    |
| 2.65    | 4         | 0.1%    |
| 6/5     | 3         | 0.08%   |
| 3.40    | 3         | 0.08%   |
| 0.67    | 2         | 0.05%   |
| 1.03    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1757      | 38.47%  |
| 81-90          | 1084      | 23.74%  |
| 201-250        | 368       | 8.06%   |
| 71-80          | 266       | 5.82%   |
| 301-350        | 210       | 4.6%    |
| 121-130        | 192       | 4.2%    |
| 61-70          | 107       | 2.34%   |
| 351-500        | 92        | 2.01%   |
| 111-120        | 83        | 1.82%   |
| 251-300        | 65        | 1.42%   |
| 151-200        | 62        | 1.36%   |
| 51-60          | 57        | 1.25%   |
| Unknown        | 52        | 1.14%   |
| More than 1000 | 39        | 0.85%   |
| 141-150        | 38        | 0.83%   |
| 91-100         | 27        | 0.59%   |
| 501-1000       | 25        | 0.55%   |
| 131-140        | 23        | 0.5%    |
| 41-50          | 15        | 0.33%   |
| 1-40           | 5         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2113      | 47.17%  |
| 101-120       | 926       | 20.67%  |
| 51-100        | 632       | 14.11%  |
| 161-240       | 490       | 10.94%  |
| More than 240 | 227       | 5.07%   |
| Unknown       | 52        | 1.16%   |
| 1-50          | 40        | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3003      | 77.74%  |
| 2     | 739       | 19.13%  |
| 3     | 96        | 2.49%   |
| 0     | 16        | 0.41%   |
| 4     | 9         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2291      | 38.72%  |
| Realtek Semiconductor             | 1986      | 33.56%  |
| Qualcomm Atheros                  | 683       | 11.54%  |
| Broadcom                          | 230       | 3.89%   |
| MediaTek                          | 169       | 2.86%   |
| Broadcom Limited                  | 57        | 0.96%   |
| Lenovo                            | 45        | 0.76%   |
| ASIX Electronics                  | 43        | 0.73%   |
| Qualcomm                          | 39        | 0.66%   |
| TP-Link                           | 36        | 0.61%   |
| Sierra Wireless                   | 32        | 0.54%   |
| Ericsson Business Mobile Networks | 27        | 0.46%   |
| Marvell Technology Group          | 24        | 0.41%   |
| Ralink                            | 23        | 0.39%   |
| DisplayLink                       | 21        | 0.35%   |
| Xiaomi                            | 20        | 0.34%   |
| Ralink Technology                 | 19        | 0.32%   |
| Samsung Electronics               | 18        | 0.3%    |
| Dell                              | 18        | 0.3%    |
| Hewlett-Packard                   | 15        | 0.25%   |
| Apple                             | 12        | 0.2%    |
| Google                            | 9         | 0.15%   |
| D-Link                            | 9         | 0.15%   |
| Huawei Technologies               | 8         | 0.14%   |
| Cypress Semiconductor             | 7         | 0.12%   |
| NetGear                           | 6         | 0.1%    |
| Fibocom                           | 6         | 0.1%    |
| Qualcomm Atheros Communications   | 5         | 0.08%   |
| Motorola PCS                      | 5         | 0.08%   |
| Linksys                           | 5         | 0.08%   |
| JMicron Technology                | 5         | 0.08%   |
| OPPO Electronics                  | 4         | 0.07%   |
| Nvidia                            | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |
| Microsoft                         | 3         | 0.05%   |
| ASUSTek Computer                  | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |
| U-Blox                            | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.03%   |
| Aquantia                          | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1319      | 18.64%  |
| Intel Wi-Fi 6 AX200                                               | 324       | 4.58%   |
| Intel Wireless 8265 / 8275                                        | 228       | 3.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 226       | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 176       | 2.49%   |
| Intel Wi-Fi 6 AX201                                               | 162       | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 161       | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 137       | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 137       | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 137       | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 136       | 1.92%   |
| Intel Wireless 7265                                               | 124       | 1.75%   |
| Intel Wireless 8260                                               | 112       | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 106       | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 103       | 1.46%   |
| Intel Wireless 7260                                               | 103       | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 93        | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 92        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 91        | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 87        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 87        | 1.23%   |
| Intel Wireless 3165                                               | 79        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 75        | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 75        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 72        | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 64        | 0.9%    |
| Intel Wireless-AC 9260                                            | 57        | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 54        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 54        | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 46        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 44        | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 43        | 0.61%   |
| Intel Wireless 3160                                               | 43        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 43        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 43        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 40        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 40        | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2201      | 56.45%  |
| Qualcomm Atheros                | 581       | 14.9%   |
| Realtek Semiconductor           | 521       | 13.36%  |
| Broadcom                        | 195       | 5%      |
| MediaTek                        | 166       | 4.26%   |
| Broadcom Limited                | 44        | 1.13%   |
| Qualcomm                        | 35        | 0.9%    |
| Sierra Wireless                 | 32        | 0.82%   |
| TP-Link                         | 28        | 0.72%   |
| Ralink                          | 23        | 0.59%   |
| Ralink Technology               | 19        | 0.49%   |
| Dell                            | 11        | 0.28%   |
| D-Link                          | 7         | 0.18%   |
| Hewlett-Packard                 | 6         | 0.15%   |
| Fibocom                         | 6         | 0.15%   |
| Qualcomm Atheros Communications | 5         | 0.13%   |
| NetGear                         | 5         | 0.13%   |
| Linksys                         | 5         | 0.13%   |
| ASUSTek Computer                | 3         | 0.08%   |
| Xiaomi                          | 2         | 0.05%   |
| Quectel Wireless Solutions      | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 324       | 8.28%   |
| Intel Wireless 8265 / 8275                                     | 228       | 5.83%   |
| Intel Wi-Fi 6 AX201                                            | 162       | 4.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 161       | 4.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 137       | 3.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 137       | 3.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 137       | 3.5%    |
| Intel Wireless 7265                                            | 124       | 3.17%   |
| Intel Wireless 8260                                            | 112       | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 106       | 2.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 103       | 2.63%   |
| Intel Wireless 7260                                            | 103       | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 93        | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 92        | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 91        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 87        | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 87        | 2.22%   |
| Intel Wireless 3165                                            | 79        | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 75        | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 73        | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 72        | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 64        | 1.64%   |
| Intel Wireless-AC 9260                                         | 57        | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 54        | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 44        | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 43        | 1.1%    |
| Intel Wireless 3160                                            | 43        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 40        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 37        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 35        | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 34        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                  | 33        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                 | 30        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.69%   |
| Intel Centrino Advanced-N 6235                                 | 25        | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 24        | 0.61%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 22        | 0.56%   |
| Intel Centrino Advanced-N 6200                                 | 20        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 19        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1776      | 58.29%  |
| Intel                            | 787       | 25.83%  |
| Qualcomm Atheros                 | 157       | 5.15%   |
| Broadcom                         | 61        | 2%      |
| ASIX Electronics                 | 43        | 1.41%   |
| Lenovo                           | 42        | 1.38%   |
| Marvell Technology Group         | 23        | 0.75%   |
| DisplayLink                      | 21        | 0.69%   |
| Xiaomi                           | 18        | 0.59%   |
| Samsung Electronics              | 18        | 0.59%   |
| Broadcom Limited                 | 13        | 0.43%   |
| Apple                            | 12        | 0.39%   |
| Google                           | 9         | 0.3%    |
| TP-Link                          | 8         | 0.26%   |
| Cypress Semiconductor            | 7         | 0.23%   |
| JMicron Technology               | 5         | 0.16%   |
| Qualcomm                         | 4         | 0.13%   |
| OPPO Electronics                 | 4         | 0.13%   |
| Nvidia                           | 4         | 0.13%   |
| Motorola PCS                     | 4         | 0.13%   |
| MediaTek                         | 4         | 0.13%   |
| Huawei Technologies              | 4         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Hewlett-Packard                  | 3         | 0.1%    |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| Microsoft                        | 2         | 0.07%   |
| D-Link                           | 2         | 0.07%   |
| Aquantia                         | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| QNAP System                      | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1319      | 42.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 226       | 7.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 176       | 5.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 136       | 4.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 2.26%   |
| Intel Ethernet Connection (4) I219-V                              | 54        | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 46        | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 43        | 1.39%   |
| Intel Ethernet Connection (6) I219-V                              | 40        | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 38        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 33        | 1.06%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 33        | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 1%      |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.9%    |
| Intel Ethernet Connection (6) I219-LM                             | 26        | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 25        | 0.81%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.77%   |
| Intel Ethernet Connection I219-V                                  | 20        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.58%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 15        | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.35%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10        | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.32%   |
| Lenovo USB-C Dock Ethernet                                        | 10        | 0.32%   |
| Intel Ethernet Connection (16) I219-V                             | 10        | 0.32%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3741      | 55.91%  |
| Ethernet | 2887      | 43.15%  |
| Modem    | 56        | 0.84%   |
| Unknown  | 7         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3197      | 79.35%  |
| Ethernet | 831       | 20.63%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2606      | 68.87%  |
| 1     | 1100      | 29.07%  |
| 3     | 45        | 1.19%   |
| 0     | 31        | 0.82%   |
| 4     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3129      | 81.38%  |
| Yes  | 716       | 18.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1871      | 56.53%  |
| Realtek Semiconductor           | 318       | 9.61%   |
| Qualcomm Atheros Communications | 261       | 7.89%   |
| IMC Networks                    | 172       | 5.2%    |
| Lite-On Technology              | 143       | 4.32%   |
| Broadcom                        | 136       | 4.11%   |
| Foxconn / Hon Hai               | 134       | 4.05%   |
| Apple                           | 54        | 1.63%   |
| Realtek                         | 44        | 1.33%   |
| Dell                            | 34        | 1.03%   |
| Cambridge Silicon Radio         | 26        | 0.79%   |
| Hewlett-Packard                 | 19        | 0.57%   |
| MediaTek                        | 17        | 0.51%   |
| USI                             | 14        | 0.42%   |
| Toshiba                         | 13        | 0.39%   |
| Ralink                          | 12        | 0.36%   |
| Foxconn International           | 8         | 0.24%   |
| ASUSTek Computer                | 6         | 0.18%   |
| Opticis                         | 5         | 0.15%   |
| TP-Link                         | 3         | 0.09%   |
| Chicony Electronics             | 3         | 0.09%   |
| Askey Computer                  | 3         | 0.09%   |
| Smart Modular Technologies      | 2         | 0.06%   |
| Ralink Technology               | 2         | 0.06%   |
| Dynex                           | 2         | 0.06%   |
| Alps Electric                   | 2         | 0.06%   |
| Syntek                          | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 662       | 19.97%  |
| Intel AX201 Bluetooth                               | 344       | 10.38%  |
| Intel AX200 Bluetooth                               | 306       | 9.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 280       | 8.45%   |
| Realtek Bluetooth Radio                             | 197       | 5.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 143       | 4.31%   |
| Intel AX210 Bluetooth                               | 87        | 2.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 70        | 2.11%   |
| IMC Networks Wireless_Device                        | 64        | 1.93%   |
| Intel Bluetooth Device                              | 63        | 1.9%    |
| IMC Networks Bluetooth Radio                        | 55        | 1.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 53        | 1.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 49        | 1.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 47        | 1.42%   |
| Foxconn / Hon Hai Bluetooth Device                  | 46        | 1.39%   |
| Realtek Bluetooth Radio                             | 44        | 1.33%   |
| Lite-On Bluetooth Device                            | 43        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 42        | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 1.12%   |
| Apple Bluetooth Host Controller                     | 35        | 1.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 1%      |
| IMC Networks Bluetooth Device                       | 33        | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 30        | 0.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 26        | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 0.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 26        | 0.78%   |
| Lite-On Wireless_Device                             | 24        | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 21        | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.54%   |
| MediaTek Wireless_Device                            | 16        | 0.48%   |
| USI Bluetooth Device                                | 14        | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.42%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.39%   |
| Realtek RTL8821A Bluetooth                          | 12        | 0.36%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.36%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.36%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.36%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2864      | 57.5%   |
| AMD                                  | 932       | 18.71%  |
| Nvidia                               | 753       | 15.12%  |
| C-Media Electronics                  | 47        | 0.94%   |
| Lenovo                               | 42        | 0.84%   |
| Realtek Semiconductor                | 38        | 0.76%   |
| Logitech                             | 24        | 0.48%   |
| JMTek                                | 22        | 0.44%   |
| Texas Instruments                    | 21        | 0.42%   |
| GN Netcom                            | 17        | 0.34%   |
| Apple                                | 16        | 0.32%   |
| Kingston Technology                  | 15        | 0.3%    |
| Focusrite-Novation                   | 15        | 0.3%    |
| Razer USA                            | 12        | 0.24%   |
| SteelSeries ApS                      | 10        | 0.2%    |
| Plantronics                          | 9         | 0.18%   |
| Creative Technology                  | 8         | 0.16%   |
| ASUSTek Computer                     | 8         | 0.16%   |
| Hewlett-Packard                      | 7         | 0.14%   |
| Generalplus Technology               | 5         | 0.1%    |
| Samson Technologies                  | 4         | 0.08%   |
| Corsair                              | 4         | 0.08%   |
| Unknown                              | 4         | 0.08%   |
| Yamaha                               | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.06%   |
| Sennheiser Communications            | 3         | 0.06%   |
| SAVITECH                             | 3         | 0.06%   |
| DSEA A/S                             | 3         | 0.06%   |
| Conexant Systems                     | 3         | 0.06%   |
| XMOS                                 | 2         | 0.04%   |
| Valve Software                       | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |
| Schiit Audio                         | 2         | 0.04%   |
| No brand                             | 2         | 0.04%   |
| Native Instruments                   | 2         | 0.04%   |
| Microsoft                            | 2         | 0.04%   |
| Medeli Electronics                   | 2         | 0.04%   |
| Mackie Designs                       | 2         | 0.04%   |
| JBL                                  | 2         | 0.04%   |
| GYROCOM C&C                          | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 736       | 12.01%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 521       | 8.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 371       | 6.05%   |
| Intel Cannon Lake PCH cAVS                                                                        | 245       | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 231       | 3.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 218       | 3.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 193       | 3.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 169       | 2.76%   |
| Intel Broadwell-U Audio Controller                                                                | 143       | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 140       | 2.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 139       | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 137       | 2.24%   |
| Intel 8 Series HD Audio Controller                                                                | 137       | 2.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 122       | 1.99%   |
| Intel CM238 HD Audio Controller                                                                   | 121       | 1.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 119       | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 113       | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 98        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 96        | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 94        | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 87        | 1.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 86        | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 76        | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 75        | 1.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 71        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 70        | 1.14%   |
| Nvidia Audio device                                                                               | 65        | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 59        | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 58        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 58        | 0.95%   |
| AMD FCH Azalia Controller                                                                         | 47        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 41        | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 41        | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 41        | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 39        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 36        | 0.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 36        | 0.59%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 31        | 0.51%   |
| Realtek Semiconductor USB Audio                                                                   | 30        | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 28        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1001      | 30.11%  |
| SK hynix            | 755       | 22.71%  |
| Micron Technology   | 444       | 13.36%  |
| Kingston            | 322       | 9.69%   |
| Crucial             | 205       | 6.17%   |
| Unknown             | 111       | 3.34%   |
| Ramaxel Technology  | 83        | 2.5%    |
| A-DATA Technology   | 68        | 2.05%   |
| Corsair             | 55        | 1.65%   |
| Elpida              | 44        | 1.32%   |
| G.Skill             | 24        | 0.72%   |
| Nanya Technology    | 20        | 0.6%    |
| Team                | 15        | 0.45%   |
| Patriot             | 15        | 0.45%   |
| GOODRAM             | 15        | 0.45%   |
| Transcend           | 14        | 0.42%   |
| Unknown             | 14        | 0.42%   |
| Smart               | 13        | 0.39%   |
| Unknown (ABCD)      | 12        | 0.36%   |
| Smart Brazil        | 7         | 0.21%   |
| AMD                 | 7         | 0.21%   |
| Teikon              | 6         | 0.18%   |
| PNY                 | 5         | 0.15%   |
| Goldkey             | 5         | 0.15%   |
| Apacer              | 5         | 0.15%   |
| Avant               | 4         | 0.12%   |
| V-GeN               | 3         | 0.09%   |
| GSkill              | 3         | 0.09%   |
| 48spaces            | 3         | 0.09%   |
| V-Color             | 2         | 0.06%   |
| Unknown (08AE)      | 2         | 0.06%   |
| Silicon Power       | 2         | 0.06%   |
| PKI/Kingston        | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| High Bridge         | 2         | 0.06%   |
| fef5                | 2         | 0.06%   |
| ASint Technology    | 2         | 0.06%   |
| 4ea5                | 2         | 0.06%   |
| ZIFEI               | 1         | 0.03%   |
| Wilk                | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 63        | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 60        | 1.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 60        | 1.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 1.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 33        | 0.94%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 31        | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 30        | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 26        | 0.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 26        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 25        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 24        | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 22        | 0.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.54%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.54%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 17        | 0.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 17        | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 16        | 0.46%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 16        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 15        | 0.43%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 15        | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 14        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1607      | 58.52%  |
| DDR3    | 679       | 24.73%  |
| LPDDR4  | 146       | 5.32%   |
| LPDDR3  | 106       | 3.86%   |
| DDR5    | 66        | 2.4%    |
| LPDDR5  | 63        | 2.29%   |
| DDR2    | 40        | 1.46%   |
| SDRAM   | 32        | 1.17%   |
| Unknown | 5         | 0.18%   |
| DRAM    | 1         | 0.04%   |
| DDR     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2380      | 86.2%   |
| Row Of Chips | 327       | 11.84%  |
| Chip         | 32        | 1.16%   |
| Unknown      | 14        | 0.51%   |
| DIMM         | 8         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1363      | 45.19%  |
| 4096  | 734       | 24.34%  |
| 16384 | 545       | 18.07%  |
| 2048  | 214       | 7.1%    |
| 32768 | 123       | 4.08%   |
| 1024  | 37        | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 723       | 24.24%  |
| 3200    | 659       | 22.09%  |
| 1600    | 489       | 16.39%  |
| 2400    | 266       | 8.92%   |
| 2133    | 167       | 5.6%    |
| 1334    | 99        | 3.32%   |
| 4267    | 71        | 2.38%   |
| 4800    | 65        | 2.18%   |
| 6400    | 61        | 2.04%   |
| 3266    | 60        | 2.01%   |
| 1333    | 59        | 1.98%   |
| 1867    | 49        | 1.64%   |
| 1067    | 33        | 1.11%   |
| 667     | 29        | 0.97%   |
| 4266    | 27        | 0.91%   |
| 4199    | 19        | 0.64%   |
| 8400    | 18        | 0.6%    |
| Unknown | 14        | 0.47%   |
| 1066    | 13        | 0.44%   |
| 2048    | 10        | 0.34%   |
| 975     | 9         | 0.3%    |
| 800     | 9         | 0.3%    |
| 2933    | 8         | 0.27%   |
| 3733    | 6         | 0.2%    |
| 5600    | 2         | 0.07%   |
| 1866    | 2         | 0.07%   |
| 1777    | 2         | 0.07%   |
| 1200    | 2         | 0.07%   |
| 533     | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 6000    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 3000    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 52.63%  |
| Samsung Electronics | 2         | 10.53%  |
| Prolific Technology | 2         | 10.53%  |
| Canon               | 2         | 10.53%  |
| Seiko Epson         | 1         | 5.26%   |
| Dymo-CoStar         | 1         | 5.26%   |
| Brother Industries  | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 10.53%  |
| HP DeskJet 2130 series        | 2         | 10.53%  |
| Seiko Epson WF-2530 Series    | 1         | 5.26%   |
| Samsung SCX-3200 Series       | 1         | 5.26%   |
| Samsung M2020 Series          | 1         | 5.26%   |
| HP OfficeJet 5600 (USBHUB)    | 1         | 5.26%   |
| HP LaserJet P1102             | 1         | 5.26%   |
| HP LaserJet 1320              | 1         | 5.26%   |
| HP LaserJet 1022              | 1         | 5.26%   |
| HP ENVY 5000 series           | 1         | 5.26%   |
| HP DeskJet 840c               | 1         | 5.26%   |
| HP DeskJet 4100 series        | 1         | 5.26%   |
| HP DeskJet 2600 series        | 1         | 5.26%   |
| Dymo-CoStar LabelWriter 400   | 1         | 5.26%   |
| Canon PIXMA MG2500 Series     | 1         | 5.26%   |
| Canon LiDE 400                | 1         | 5.26%   |
| Brother HL-1110 series        | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 822       | 23.72%  |
| IMC Networks                           | 448       | 12.93%  |
| Microdia                               | 314       | 9.06%   |
| Bison Electronics                      | 268       | 7.73%   |
| Realtek Semiconductor                  | 251       | 7.24%   |
| Quanta                                 | 217       | 6.26%   |
| Sunplus Innovation Technology          | 171       | 4.93%   |
| Cheng Uei Precision Industry (Foxlink) | 121       | 3.49%   |
| Syntek                                 | 108       | 3.12%   |
| Acer                                   | 98        | 2.83%   |
| Lite-On Technology                     | 97        | 2.8%    |
| Luxvisions Innotech Limited            | 73        | 2.11%   |
| Logitech                               | 63        | 1.82%   |
| Suyin                                  | 58        | 1.67%   |
| Apple                                  | 55        | 1.59%   |
| Silicon Motion                         | 40        | 1.15%   |
| Alcor Micro                            | 35        | 1.01%   |
| Sonix Technology                       | 28        | 0.81%   |
| Lenovo                                 | 24        | 0.69%   |
| Samsung Electronics                    | 18        | 0.52%   |
| SunplusIT                              | 16        | 0.46%   |
| Importek                               | 13        | 0.38%   |
| Ricoh                                  | 11        | 0.32%   |
| ALi                                    | 11        | 0.32%   |
| Microsoft                              | 7         | 0.2%    |
| Z-Star Microelectronics                | 6         | 0.17%   |
| Primax Electronics                     | 6         | 0.17%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.14%   |
| ARC International                      | 5         | 0.14%   |
| OmniVision Technologies                | 4         | 0.12%   |
| MacroSilicon                           | 4         | 0.12%   |
| Google                                 | 4         | 0.12%   |
| ShineTech                              | 3         | 0.09%   |
| LG Electronics                         | 3         | 0.09%   |
| Colorado                               | 3         | 0.09%   |
| 8SSC21D67422V1SR28902JL                | 3         | 0.09%   |
| Valve Software                         | 2         | 0.06%   |
| Razer USA                              | 2         | 0.06%   |
| Pixart Imaging                         | 2         | 0.06%   |
| kingcome                               | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 237       | 6.78%   |
| Microdia Integrated_Webcam_HD                                              | 180       | 5.15%   |
| IMC Networks Integrated Camera                                             | 146       | 4.18%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 136       | 3.89%   |
| Realtek Integrated_Webcam_HD                                               | 97        | 2.78%   |
| Bison Integrated Camera                                                    | 91        | 2.61%   |
| Sunplus Integrated_Webcam_HD                                               | 84        | 2.4%    |
| Chicony HD WebCam                                                          | 83        | 2.38%   |
| Syntek Integrated Camera                                                   | 72        | 2.06%   |
| Quanta HD User Facing                                                      | 52        | 1.49%   |
| Lite-On Integrated Camera                                                  | 52        | 1.49%   |
| Bison HD Webcam                                                            | 50        | 1.43%   |
| Bison SunplusIT Integrated Camera                                          | 45        | 1.29%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 37        | 1.06%   |
| Chicony USB2.0 Camera                                                      | 37        | 1.06%   |
| Chicony HD User Facing                                                     | 37        | 1.06%   |
| Chicony Integrated Camera (1280x720@30)                                    | 35        | 1%      |
| Microdia Integrated Webcam                                                 | 31        | 0.89%   |
| Chicony HP HD Camera                                                       | 31        | 0.89%   |
| Sunplus HD WebCam                                                          | 26        | 0.74%   |
| Chicony HP Wide Vision HD Camera                                           | 26        | 0.74%   |
| IMC Networks ov9734_azurewave_camera                                       | 25        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 25        | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 24        | 0.69%   |
| Chicony Integrated IR Camera                                               | 24        | 0.69%   |
| Chicony HP Truevision HD                                                   | 24        | 0.69%   |
| Acer Integrated Camera                                                     | 24        | 0.69%   |
| Realtek USB Camera                                                         | 23        | 0.66%   |
| Realtek Integrated Webcam                                                  | 23        | 0.66%   |
| Quanta HP Wide Vision HD Camera                                            | 23        | 0.66%   |
| Quanta HP TrueVision HD Camera                                             | 23        | 0.66%   |
| Quanta VGA WebCam                                                          | 22        | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 21        | 0.6%    |
| Chicony HP TrueVision HD Camera                                            | 21        | 0.6%    |
| IMC Networks HD Camera                                                     | 20        | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                                               | 20        | 0.57%   |
| Chicony EasyCamera                                                         | 20        | 0.57%   |
| Syntek Lenovo EasyCamera                                                   | 19        | 0.54%   |
| Quanta HP HD Camera                                                        | 19        | 0.54%   |
| Quanta HD Webcam                                                           | 19        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 277       | 34.2%   |
| Validity Sensors                   | 222       | 27.41%  |
| Shenzhen Goodix Technology         | 160       | 19.75%  |
| Elan Microelectronics              | 51        | 6.3%    |
| LighTuning Technology              | 31        | 3.83%   |
| Upek                               | 30        | 3.7%    |
| AuthenTec                          | 20        | 2.47%   |
| STMicroelectronics                 | 9         | 1.11%   |
| Samsung Electronics                | 3         | 0.37%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.37%   |
| HOLTEK                             | 3         | 0.37%   |
| Focal-systems.Corp                 | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 117       | 14.44%  |
| Shenzhen Goodix  Fingerprint Device                                        | 94        | 11.6%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 55        | 6.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 43        | 5.31%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 36        | 4.44%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 4.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 31        | 3.83%   |
| Validity Sensors Synaptics WBDI                                            | 29        | 3.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 3.46%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 27        | 3.33%   |
| Elan ELAN:Fingerprint                                                      | 25        | 3.09%   |
| Elan ELAN:ARM-M4                                                           | 20        | 2.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 19        | 2.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 18        | 2.22%   |
| Synaptics Fingerprint reader [HP G6]                                       | 17        | 2.1%    |
| Synaptics UWP WBDI Device                                                  | 15        | 1.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.85%   |
| Validity Sensors VFS491                                                    | 13        | 1.6%    |
| Validity Sensors Fingerprint scanner                                       | 13        | 1.6%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.36%   |
| AuthenTec AES2810                                                          | 11        | 1.36%   |
| Synaptics UWP WBDI                                                         | 10        | 1.23%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 1.11%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.74%   |
| Synaptics  WBDI                                                            | 6         | 0.74%   |
| Elan WBF Fingerprint Sensor                                                | 6         | 0.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.49%   |
| Synaptics WBDI Device                                                      | 4         | 0.49%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.37%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.37%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.37%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.37%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 139       | 43.3%   |
| Broadcom                  | 119       | 37.07%  |
| Upek                      | 24        | 7.48%   |
| Lenovo                    | 13        | 4.05%   |
| O2 Micro                  | 9         | 2.8%    |
| SCM Microsystems          | 4         | 1.25%   |
| Yubico.com                | 3         | 0.93%   |
| Gemalto (was Gemplus)     | 3         | 0.93%   |
| Clay Logic                | 2         | 0.62%   |
| Realtek Semiconductor     | 1         | 0.31%   |
| Hewlett-Packard           | 1         | 0.31%   |
| Chicony Electronics       | 1         | 0.31%   |
| Aladdin Knowledge Systems | 1         | 0.31%   |
| Aktiv                     | 1         | 0.31%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 139       | 43.3%   |
| Broadcom 5880                                                                | 33        | 10.28%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 9.35%   |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 8.41%   |
| Broadcom 58200                                                               | 27        | 8.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.48%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 4.05%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 2.49%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.93%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.93%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.93%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.62%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.62%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.31%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.31%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.31%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.31%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.31%   |
| Aktiv Rutoken lite                                                           | 1         | 0.31%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2309      | 59.68%  |
| 1     | 1218      | 31.48%  |
| 2     | 274       | 7.08%   |
| 3     | 58        | 1.5%    |
| 4     | 8         | 0.21%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 790       | 41%     |
| Graphics card            | 362       | 18.79%  |
| Chipcard                 | 281       | 14.58%  |
| Multimedia controller    | 139       | 7.21%   |
| Net/wireless             | 112       | 5.81%   |
| Camera                   | 101       | 5.24%   |
| Bluetooth                | 35        | 1.82%   |
| Net/ethernet             | 20        | 1.04%   |
| Storage                  | 17        | 0.88%   |
| Sound                    | 16        | 0.83%   |
| Communication controller | 14        | 0.73%   |
| Card reader              | 12        | 0.62%   |
| Network                  | 11        | 0.57%   |
| Modem                    | 7         | 0.36%   |
| Dvb card                 | 3         | 0.16%   |
| Wireless                 | 2         | 0.1%    |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |


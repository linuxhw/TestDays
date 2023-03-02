Kubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_22.04/Notebook/README.md).

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

Total: 902

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Dell          | Precision 7730              | Notebook    | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | Notebook    | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| MSI           | MS-AEC21                    | All in one  | [e541cd3043](https://linux-hardware.org/?probe=e541cd3043) | Jan 23, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d2b797f3de](https://linux-hardware.org/?probe=d2b797f3de) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bfaffed5d2](https://linux-hardware.org/?probe=bfaffed5d2) | Jan 21, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a9d66d6af6](https://linux-hardware.org/?probe=a9d66d6af6) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0bc976587f](https://linux-hardware.org/?probe=0bc976587f) | Jan 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | Desktop     | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [6286dbdb0b](https://linux-hardware.org/?probe=6286dbdb0b) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | Notebook    | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| HP            | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [774322328a](https://linux-hardware.org/?probe=774322328a) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d94fa63122](https://linux-hardware.org/?probe=d94fa63122) | Jan 08, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [391d13c7ba](https://linux-hardware.org/?probe=391d13c7ba) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a5b2453630](https://linux-hardware.org/?probe=a5b2453630) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | Desktop     | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | Notebook    | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| HP            | Beats 15                    | Notebook    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Acer          | Aspire A517-53              | Notebook    | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | Notebook    | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| SGIN          | laptop                      | Notebook    | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| HP            | Sona                        | Notebook    | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [3d563943d4](https://linux-hardware.org/?probe=3d563943d4) | Dec 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | Notebook    | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1cbc80c6fb](https://linux-hardware.org/?probe=1cbc80c6fb) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | NOK                         | Desktop     | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8745419f51](https://linux-hardware.org/?probe=8745419f51) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [55e56516e5](https://linux-hardware.org/?probe=55e56516e5) | Dec 06, 2022 |
| HP            | Beats 15                    | Notebook    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HP            | EliteBook x360 1040 G5      | Convertible | [02c80899f7](https://linux-hardware.org/?probe=02c80899f7) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | Notebook    | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| Haier         | A1420EM                     | Notebook    | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fc681f2f42](https://linux-hardware.org/?probe=fc681f2f42) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [d876db7f78](https://linux-hardware.org/?probe=d876db7f78) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | Notebook    | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | Desktop     | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [12fe5843d1](https://linux-hardware.org/?probe=12fe5843d1) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | Notebook    | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | Notebook    | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [317efeba98](https://linux-hardware.org/?probe=317efeba98) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | Notebook    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [abfee9c5f7](https://linux-hardware.org/?probe=abfee9c5f7) | Oct 18, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [b106ebaef6](https://linux-hardware.org/?probe=b106ebaef6) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [159150cc56](https://linux-hardware.org/?probe=159150cc56) | Oct 17, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| JWIPC         | A320I S1                    | Desktop     | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | Notebook    | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [eb5e8725ae](https://linux-hardware.org/?probe=eb5e8725ae) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Dell          | Latitude 7430               | Notebook    | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Acer          | Predator G3-571             | Notebook    | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| HP            | Notebook                    | Notebook    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [33784347f5](https://linux-hardware.org/?probe=33784347f5) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | Notebook    | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Dell          | Latitude 5590               | Notebook    | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Intel         | Unknown                     | Notebook    | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| Dell          | Latitude 5590               | Notebook    | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [8b027b07d9](https://linux-hardware.org/?probe=8b027b07d9) | Jul 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | Desktop     | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | Notebook    | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | 8459                        | Desktop     | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | Desktop     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| Haier         | A1420EM                     | Notebook    | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | Notebook    | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | Notebook    | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [91316a0904](https://linux-hardware.org/?probe=91316a0904) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | Notebook    | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | Notebook    | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | Notebook    | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3a58a9889b](https://linux-hardware.org/?probe=3a58a9889b) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [acf0372bdc](https://linux-hardware.org/?probe=acf0372bdc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | Notebook    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [c8e2700624](https://linux-hardware.org/?probe=c8e2700624) | Jun 02, 2022 |
| Dell          | Latitude 7420               | Notebook    | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | Notebook    | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | Notebook    | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [540416deba](https://linux-hardware.org/?probe=540416deba) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [63a10ce1e0](https://linux-hardware.org/?probe=63a10ce1e0) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| HP            | ProBook 6470b               | Notebook    | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | Desktop     | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | Notebook    | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | Notebook    | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ef1e814871](https://linux-hardware.org/?probe=ef1e814871) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3ea846ae2a](https://linux-hardware.org/?probe=3ea846ae2a) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | Notebook    | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2015948e6d](https://linux-hardware.org/?probe=2015948e6d) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2c7c189ffa](https://linux-hardware.org/?probe=2c7c189ffa) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-56-generic      | 67        | 9.27%   |
| 5.15.0-52-generic      | 66        | 9.13%   |
| 5.15.0-48-generic      | 41        | 5.67%   |
| 5.15.0-58-generic      | 39        | 5.39%   |
| 5.15.0-47-generic      | 36        | 4.98%   |
| 5.15.0-43-generic      | 36        | 4.98%   |
| 5.15.0-46-generic      | 33        | 4.56%   |
| 5.15.0-53-generic      | 32        | 4.43%   |
| 5.15.0-60-generic      | 31        | 4.29%   |
| 5.15.0-41-generic      | 29        | 4.01%   |
| 5.15.0-40-generic      | 26        | 3.6%    |
| 5.15.0-25-generic      | 25        | 3.46%   |
| 5.15.0-27-generic      | 24        | 3.32%   |
| 5.15.0-50-generic      | 22        | 3.04%   |
| 5.15.0-33-generic      | 18        | 2.49%   |
| 5.15.0-57-generic      | 14        | 1.94%   |
| 5.15.0-37-generic      | 10        | 1.38%   |
| 5.15.0-30-generic      | 10        | 1.38%   |
| 5.15.0-39-generic      | 9         | 1.24%   |
| 5.15.0-43-lowlatency   | 8         | 1.11%   |
| 5.15.0-48-lowlatency   | 7         | 0.97%   |
| 5.19.0-32-generic      | 6         | 0.83%   |
| 5.15.0-35-generic      | 6         | 0.83%   |
| 5.15.0-56-lowlatency   | 5         | 0.69%   |
| 5.15.0-52-lowlatency   | 5         | 0.69%   |
| 5.15.0-18-generic      | 5         | 0.69%   |
| 5.17.0-1020-oem        | 4         | 0.55%   |
| 5.15.0-58-lowlatency   | 4         | 0.55%   |
| 5.15.0-46-lowlatency   | 4         | 0.55%   |
| 5.17.0-1017-oem        | 3         | 0.41%   |
| 5.15.0-60-lowlatency   | 3         | 0.41%   |
| 5.15.0-47-lowlatency   | 3         | 0.41%   |
| 5.15.0-30-lowlatency   | 3         | 0.41%   |
| 5.15.0-27-lowlatency   | 3         | 0.41%   |
| 5.13.0-19-generic      | 3         | 0.41%   |
| 6.1.0-1006-oem         | 2         | 0.28%   |
| 6.0.7-060007-generic   | 2         | 0.28%   |
| 6.0.1-060001-generic   | 2         | 0.28%   |
| 5.19.5-051905-generic  | 2         | 0.28%   |
| 5.18.10-051810-generic | 2         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 612       | 89.34%  |
| 5.17.0   | 14        | 2.04%   |
| 5.19.0   | 7         | 1.02%   |
| 6.0.0    | 6         | 0.88%   |
| 5.13.0   | 6         | 0.88%   |
| 6.1.5    | 2         | 0.29%   |
| 6.1.0    | 2         | 0.29%   |
| 6.0.7    | 2         | 0.29%   |
| 6.0.1    | 2         | 0.29%   |
| 5.19.5   | 2         | 0.29%   |
| 5.18.4   | 2         | 0.29%   |
| 5.18.10  | 2         | 0.29%   |
| 6.1.9    | 1         | 0.15%   |
| 6.1.12   | 1         | 0.15%   |
| 6.0.9    | 1         | 0.15%   |
| 6.0.8    | 1         | 0.15%   |
| 6.0.6    | 1         | 0.15%   |
| 5.4.0    | 1         | 0.15%   |
| 5.19.2   | 1         | 0.15%   |
| 5.19.12  | 1         | 0.15%   |
| 5.19.11  | 1         | 0.15%   |
| 5.18.6   | 1         | 0.15%   |
| 5.18.19  | 1         | 0.15%   |
| 5.18.15  | 1         | 0.15%   |
| 5.18.12  | 1         | 0.15%   |
| 5.17.6   | 1         | 0.15%   |
| 5.17.5   | 1         | 0.15%   |
| 5.17.4   | 1         | 0.15%   |
| 5.17.2   | 1         | 0.15%   |
| 5.17.14  | 1         | 0.15%   |
| 5.16.2   | 1         | 0.15%   |
| 5.16.11  | 1         | 0.15%   |
| 5.16.0   | 1         | 0.15%   |
| 5.15.65  | 1         | 0.15%   |
| 5.15.34  | 1         | 0.15%   |
| 5.15.13  | 1         | 0.15%   |
| 5.11.0   | 1         | 0.15%   |
| 5.10.123 | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 614       | 89.9%   |
| 5.17    | 19        | 2.78%   |
| 6.0     | 12        | 1.76%   |
| 5.19    | 12        | 1.76%   |
| 5.18    | 8         | 1.17%   |
| 6.1     | 6         | 0.88%   |
| 5.13    | 6         | 0.88%   |
| 5.16    | 3         | 0.44%   |
| 5.4     | 1         | 0.15%   |
| 5.11    | 1         | 0.15%   |
| 5.10    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 673       | 99.85%  |
| aarch64 | 1         | 0.15%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 664       | 98.22%  |
| GNOME      | 5         | 0.74%   |
| KDE        | 2         | 0.3%    |
| X-Cinnamon | 1         | 0.15%   |
| MATE       | 1         | 0.15%   |
| i3         | 1         | 0.15%   |
| GNUstep    | 1         | 0.15%   |
| Budgie     | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 644       | 94.99%  |
| Wayland | 25        | 3.69%   |
| Tty     | 8         | 1.18%   |
| Web     | 1         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 501       | 73.89%  |
| Unknown | 123       | 18.14%  |
| GDM3    | 37        | 5.46%   |
| LightDM | 14        | 2.06%   |
| SLiM    | 1         | 0.15%   |
| LXDM    | 1         | 0.15%   |
| GDM     | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 332       | 49.04%  |
| de_DE   | 49        | 7.24%   |
| it_IT   | 42        | 6.2%    |
| fr_FR   | 37        | 5.47%   |
| ru_RU   | 33        | 4.87%   |
| en_GB   | 25        | 3.69%   |
| en_AU   | 18        | 2.66%   |
| pl_PL   | 16        | 2.36%   |
| pt_BR   | 14        | 2.07%   |
| es_ES   | 13        | 1.92%   |
| en_IN   | 12        | 1.77%   |
| en_CA   | 9         | 1.33%   |
| en_NZ   | 6         | 0.89%   |
| hu_HU   | 5         | 0.74%   |
| es_AR   | 5         | 0.74%   |
| en_SG   | 5         | 0.74%   |
| en_PH   | 5         | 0.74%   |
| tr_TR   | 4         | 0.59%   |
| en_ZA   | 4         | 0.59%   |
| cs_CZ   | 4         | 0.59%   |
| C       | 3         | 0.44%   |
| sl_SI   | 2         | 0.3%    |
| nl_NL   | 2         | 0.3%    |
| fr_BE   | 2         | 0.3%    |
| es_MX   | 2         | 0.3%    |
| es_CL   | 2         | 0.3%    |
| el_GR   | 2         | 0.3%    |
| de_CH   | 2         | 0.3%    |
| Default | 2         | 0.3%    |
| zh_TW   | 1         | 0.15%   |
| zh_CN   | 1         | 0.15%   |
| ru_UA   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| osa_US  | 1         | 0.15%   |
| nl_BE   | 1         | 0.15%   |
| lt_LT   | 1         | 0.15%   |
| ko_KR   | 1         | 0.15%   |
| fr_CH   | 1         | 0.15%   |
| fi_FI   | 1         | 0.15%   |
| et_EE   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 369       | 54.42%  |
| BIOS | 309       | 45.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 611       | 90.25%  |
| Overlay | 29        | 4.28%   |
| Btrfs   | 29        | 4.28%   |
| Xfs     | 5         | 0.74%   |
| Zfs     | 1         | 0.15%   |
| Ext3    | 1         | 0.15%   |
| Ext2    | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 441       | 64.85%  |
| Unknown | 196       | 28.82%  |
| MBR     | 43        | 6.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 613       | 90.55%  |
| Yes       | 64        | 9.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 409       | 60.5%   |
| Yes       | 267       | 39.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 111       | 16.47%  |
| ASUSTek Computer               | 102       | 15.13%  |
| Hewlett-Packard                | 94        | 13.95%  |
| Dell                           | 84        | 12.46%  |
| Gigabyte Technology            | 51        | 7.57%   |
| MSI                            | 49        | 7.27%   |
| Acer                           | 36        | 5.34%   |
| ASRock                         | 26        | 3.86%   |
| Apple                          | 14        | 2.08%   |
| Samsung Electronics            | 8         | 1.19%   |
| HUAWEI                         | 7         | 1.04%   |
| Toshiba                        | 6         | 0.89%   |
| Google                         | 6         | 0.89%   |
| TUXEDO                         | 4         | 0.59%   |
| Timi                           | 4         | 0.59%   |
| Supermicro                     | 4         | 0.59%   |
| Sony                           | 3         | 0.45%   |
| Fujitsu                        | 3         | 0.45%   |
| Framework                      | 3         | 0.45%   |
| AZW                            | 3         | 0.45%   |
| Unknown                        | 3         | 0.45%   |
| System76                       | 2         | 0.3%    |
| Shuttle                        | 2         | 0.3%    |
| Panasonic                      | 2         | 0.3%    |
| Notebook                       | 2         | 0.3%    |
| Microsoft                      | 2         | 0.3%    |
| Intel                          | 2         | 0.3%    |
| HONOR                          | 2         | 0.3%    |
| Haier                          | 2         | 0.3%    |
| GPU Company                    | 2         | 0.3%    |
| Biostar                        | 2         | 0.3%    |
| Alienware                      | 2         | 0.3%    |
| ZOTAC                          | 1         | 0.15%   |
| VALE                           | 1         | 0.15%   |
| TrekStor                       | 1         | 0.15%   |
| Tactus                         | 1         | 0.15%   |
| Standard                       | 1         | 0.15%   |
| SLIMBOOK                       | 1         | 0.15%   |
| SK hynix                       | 1         | 0.15%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 8         | 1.19%   |
| Unknown                                | 7         | 1.04%   |
| ASUS ROG STRIX B550-F GAMING           | 5         | 0.74%   |
| MSI MS-7B79                            | 4         | 0.59%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 3         | 0.45%   |
| HP ProBook 6470b                       | 3         | 0.45%   |
| HP Pavilion g6                         | 3         | 0.45%   |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.45%   |
| HP 255 G8 Notebook PC                  | 3         | 0.45%   |
| Gigabyte B450M DS3H                    | 3         | 0.45%   |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.45%   |
| Dell XPS 15 9560                       | 3         | 0.45%   |
| Dell OptiPlex 7010                     | 3         | 0.45%   |
| Dell Latitude 3420                     | 3         | 0.45%   |
| Timi TM1701                            | 2         | 0.3%    |
| Supermicro SKAGIT09                    | 2         | 0.3%    |
| MSI MS-7C95                            | 2         | 0.3%    |
| MSI MS-7C56                            | 2         | 0.3%    |
| MSI MS-7B86                            | 2         | 0.3%    |
| MSI MS-7B84                            | 2         | 0.3%    |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.3%    |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 2         | 0.3%    |
| Lenovo IdeaPad 3 15ADA05 81W1          | 2         | 0.3%    |
| HUAWEI CREM-WXX9                       | 2         | 0.3%    |
| HP x2 Detachable 10-p0XX               | 2         | 0.3%    |
| HP ProBook 6570b                       | 2         | 0.3%    |
| HP ProBook 440 G8 Notebook PC          | 2         | 0.3%    |
| HP Pavilion Laptop 15-eh1xxx           | 2         | 0.3%    |
| HP Pavilion dv6                        | 2         | 0.3%    |
| HP OMEN Laptop 15-en0xxx               | 2         | 0.3%    |
| HP Laptop 17-by3xxx                    | 2         | 0.3%    |
| HP Laptop 15-da0xxx                    | 2         | 0.3%    |
| HP ENVY x360 Convertible 13-ay0xxx     | 2         | 0.3%    |
| HP Compaq Elite 8300 SFF               | 2         | 0.3%    |
| Haier A1420EM                          | 2         | 0.3%    |
| Gigabyte X570 GAMING X                 | 2         | 0.3%    |
| Gigabyte B450 I AORUS PRO WIFI         | 2         | 0.3%    |
| Dell XPS 15 9520                       | 2         | 0.3%    |
| Dell Precision 7540                    | 2         | 0.3%    |
| Dell OptiPlex 7040                     | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 43        | 6.38%   |
| Lenovo IdeaPad     | 25        | 3.71%   |
| ASUS ROG           | 21        | 3.12%   |
| Dell Latitude      | 19        | 2.82%   |
| Acer Aspire        | 18        | 2.67%   |
| Dell Inspiron      | 17        | 2.52%   |
| HP Pavilion        | 16        | 2.37%   |
| HP ProBook         | 14        | 2.08%   |
| Dell XPS           | 14        | 2.08%   |
| HP Laptop          | 11        | 1.63%   |
| HP EliteBook       | 11        | 1.63%   |
| Dell Precision     | 11        | 1.63%   |
| Dell OptiPlex      | 11        | 1.63%   |
| ASUS PRIME         | 11        | 1.63%   |
| Lenovo ThinkCentre | 8         | 1.19%   |
| ASUS All           | 8         | 1.19%   |
| Lenovo ThinkBook   | 7         | 1.04%   |
| ASUS VivoBook      | 7         | 1.04%   |
| ASUS TUF           | 7         | 1.04%   |
| Acer Nitro         | 7         | 1.04%   |
| Unknown            | 7         | 1.04%   |
| Lenovo Legion      | 6         | 0.89%   |
| HP ENVY            | 6         | 0.89%   |
| Dell Vostro        | 6         | 0.89%   |
| Toshiba Satellite  | 5         | 0.74%   |
| Lenovo Yoga        | 5         | 0.74%   |
| MSI MS-7B79        | 4         | 0.59%   |
| HP Spectre         | 4         | 0.59%   |
| HP OMEN            | 4         | 0.59%   |
| Gigabyte X570      | 4         | 0.59%   |
| Acer Swift         | 4         | 0.59%   |
| Acer Predator      | 4         | 0.59%   |
| HP Compaq          | 3         | 0.45%   |
| HP 255             | 3         | 0.45%   |
| Gigabyte B450M     | 3         | 0.45%   |
| Gigabyte B450      | 3         | 0.45%   |
| Framework Laptop   | 3         | 0.45%   |
| ASUS ZenBook       | 3         | 0.45%   |
| ASUS STRIX         | 3         | 0.45%   |
| ASUS M5A78L-M      | 3         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 110       | 16.32%  |
| 2020    | 102       | 15.13%  |
| 2019    | 63        | 9.35%   |
| 2018    | 56        | 8.31%   |
| 2022    | 55        | 8.16%   |
| 2012    | 52        | 7.72%   |
| 2016    | 39        | 5.79%   |
| 2017    | 38        | 5.64%   |
| 2014    | 38        | 5.64%   |
| 2013    | 31        | 4.6%    |
| 2015    | 27        | 4.01%   |
| 2011    | 27        | 4.01%   |
| 2010    | 14        | 2.08%   |
| 2009    | 7         | 1.04%   |
| 2008    | 6         | 0.89%   |
| 2007    | 6         | 0.89%   |
| 2023    | 2         | 0.3%    |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 387       | 57.42%  |
| Desktop        | 232       | 34.42%  |
| Convertible    | 28        | 4.15%   |
| Mini pc        | 11        | 1.63%   |
| All in one     | 7         | 1.04%   |
| Tablet         | 5         | 0.74%   |
| Server         | 3         | 0.45%   |
| System on chip | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 611       | 90.38%  |
| Enabled  | 65        | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 667       | 98.96%  |
| Yes  | 7         | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 190       | 27.98%  |
| 4.01-8.0        | 145       | 21.35%  |
| 8.01-16.0       | 125       | 18.41%  |
| 32.01-64.0      | 103       | 15.17%  |
| 3.01-4.0        | 57        | 8.39%   |
| 64.01-256.0     | 35        | 5.15%   |
| 24.01-32.0      | 17        | 2.5%    |
| 2.01-3.0        | 3         | 0.44%   |
| 1.01-2.0        | 3         | 0.44%   |
| More than 256.0 | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 197       | 27.75%  |
| 4.01-8.0   | 171       | 24.08%  |
| 3.01-4.0   | 144       | 20.28%  |
| 1.01-2.0   | 139       | 19.58%  |
| 8.01-16.0  | 46        | 6.48%   |
| 16.01-24.0 | 6         | 0.85%   |
| 0.51-1.0   | 6         | 0.85%   |
| 32.01-64.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 351       | 51.62%  |
| 2      | 200       | 29.41%  |
| 3      | 66        | 9.71%   |
| 4      | 28        | 4.12%   |
| 5      | 15        | 2.21%   |
| 6      | 9         | 1.32%   |
| 7      | 6         | 0.88%   |
| 9      | 2         | 0.29%   |
| 11     | 1         | 0.15%   |
| 8      | 1         | 0.15%   |
| 0      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 502       | 74.26%  |
| Yes       | 174       | 25.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 544       | 80.71%  |
| No        | 130       | 19.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 552       | 81.78%  |
| No        | 123       | 18.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 485       | 71.53%  |
| No        | 193       | 28.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 139       | 20.62%  |
| Germany      | 61        | 9.05%   |
| Italy        | 56        | 8.31%   |
| France       | 46        | 6.82%   |
| Russia       | 43        | 6.38%   |
| Poland       | 26        | 3.86%   |
| UK           | 23        | 3.41%   |
| Brazil       | 21        | 3.12%   |
| Spain        | 17        | 2.52%   |
| Australia    | 16        | 2.37%   |
| India        | 13        | 1.93%   |
| Canada       | 13        | 1.93%   |
| Switzerland  | 12        | 1.78%   |
| Netherlands  | 11        | 1.63%   |
| Indonesia    | 9         | 1.34%   |
| Hungary      | 9         | 1.34%   |
| Argentina    | 9         | 1.34%   |
| New Zealand  | 7         | 1.04%   |
| Mexico       | 7         | 1.04%   |
| Turkey       | 6         | 0.89%   |
| Philippines  | 6         | 0.89%   |
| Czechia      | 6         | 0.89%   |
| Bulgaria     | 6         | 0.89%   |
| Belgium      | 6         | 0.89%   |
| Thailand     | 5         | 0.74%   |
| Slovenia     | 5         | 0.74%   |
| Singapore    | 5         | 0.74%   |
| Portugal     | 5         | 0.74%   |
| Finland      | 5         | 0.74%   |
| Sweden       | 4         | 0.59%   |
| South Africa | 4         | 0.59%   |
| Serbia       | 4         | 0.59%   |
| Estonia      | 4         | 0.59%   |
| Ukraine      | 3         | 0.45%   |
| South Korea  | 3         | 0.45%   |
| Romania      | 3         | 0.45%   |
| Lithuania    | 3         | 0.45%   |
| Greece       | 3         | 0.45%   |
| Ecuador      | 3         | 0.45%   |
| Denmark      | 3         | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 14        | 2.02%   |
| Milan          | 14        | 2.02%   |
| Berlin         | 9         | 1.3%    |
| Paris          | 6         | 0.87%   |
| Munich         | 6         | 0.87%   |
| Wroclaw        | 5         | 0.72%   |
| St Petersburg  | 5         | 0.72%   |
| Sofia          | 5         | 0.72%   |
| Singapore      | 5         | 0.72%   |
| Dallas         | 5         | 0.72%   |
| Auckland       | 5         | 0.72%   |
| Warsaw         | 4         | 0.58%   |
| Turin          | 4         | 0.58%   |
| Sydney         | 4         | 0.58%   |
| Rio de Janeiro | 4         | 0.58%   |
| Prague         | 4         | 0.58%   |
| New York       | 4         | 0.58%   |
| Montreal       | 4         | 0.58%   |
| Madrid         | 4         | 0.58%   |
| Jakarta        | 4         | 0.58%   |
| Jacksonville   | 4         | 0.58%   |
| Bengaluru      | 4         | 0.58%   |
| Zurich         | 3         | 0.43%   |
| Washington     | 3         | 0.43%   |
| Vladivostok    | 3         | 0.43%   |
| Vilnius        | 3         | 0.43%   |
| Tallinn        | 3         | 0.43%   |
| Sao Paulo      | 3         | 0.43%   |
| Porto          | 3         | 0.43%   |
| London         | 3         | 0.43%   |
| Katowice       | 3         | 0.43%   |
| Karlsruhe      | 3         | 0.43%   |
| Johannesburg   | 3         | 0.43%   |
| Houston        | 3         | 0.43%   |
| Castro Valley  | 3         | 0.43%   |
| Budapest       | 3         | 0.43%   |
| Bougival       | 3         | 0.43%   |
| Bologna        | 3         | 0.43%   |
| Belgrade       | 3         | 0.43%   |
| Amsterdam      | 3         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 178       | 244    | 16.75%  |
| WDC                         | 141       | 189    | 13.26%  |
| Seagate                     | 116       | 183    | 10.91%  |
| Kingston                    | 73        | 83     | 6.87%   |
| Toshiba                     | 65        | 83     | 6.11%   |
| SanDisk                     | 58        | 72     | 5.46%   |
| Crucial                     | 39        | 46     | 3.67%   |
| Unknown                     | 35        | 46     | 3.29%   |
| SK hynix                    | 35        | 41     | 3.29%   |
| Intel                       | 30        | 38     | 2.82%   |
| Micron Technology           | 26        | 28     | 2.45%   |
| Hitachi                     | 24        | 24     | 2.26%   |
| HGST                        | 19        | 23     | 1.79%   |
| KIOXIA                      | 16        | 16     | 1.51%   |
| China                       | 12        | 15     | 1.13%   |
| Phison                      | 11        | 11     | 1.03%   |
| A-DATA Technology           | 10        | 11     | 0.94%   |
| Patriot                     | 9         | 11     | 0.85%   |
| Apple                       | 9         | 10     | 0.85%   |
| PNY                         | 7         | 8      | 0.66%   |
| SPCC                        | 6         | 6      | 0.56%   |
| Phison Electronics          | 6         | 6      | 0.56%   |
| Unknown                     | 6         | 6      | 0.56%   |
| Micron/Crucial Technology   | 5         | 6      | 0.47%   |
| Lexar                       | 5         | 5      | 0.47%   |
| SSSTC                       | 4         | 4      | 0.38%   |
| Silicon Motion              | 4         | 4      | 0.38%   |
| SABRENT                     | 4         | 6      | 0.38%   |
| Maxtor                      | 4         | 4      | 0.38%   |
| LITEON                      | 4         | 4      | 0.38%   |
| JMicron Technology          | 4         | 4      | 0.38%   |
| Emtec                       | 4         | 4      | 0.38%   |
| Corsair                     | 4         | 5      | 0.38%   |
| Verbatim                    | 3         | 3      | 0.28%   |
| Transcend                   | 3         | 4      | 0.28%   |
| Team                        | 3         | 3      | 0.28%   |
| Realtek Semiconductor       | 3         | 3      | 0.28%   |
| OCZ                         | 3         | 3      | 0.28%   |
| LITEONIT                    | 3         | 3      | 0.28%   |
| Kingston Technology Company | 3         | 3      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 13        | 1.1%    |
| Samsung SSD 860 EVO 500GB                           | 11        | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 11        | 0.93%   |
| Kingston SA400S37480G 480GB SSD                     | 11        | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8         | 0.68%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.59%   |
| Samsung SSD 980 PRO 1TB                             | 7         | 0.59%   |
| Samsung SSD 970 EVO Plus 1TB                        | 7         | 0.59%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.59%   |
| Kingston SA2000M81000G 1TB                          | 7         | 0.59%   |
| Crucial CT500MX500SSD1 500GB                        | 6         | 0.51%   |
| Crucial CT240BX500SSD1 240GB                        | 6         | 0.51%   |
| Unknown                                             | 6         | 0.51%   |
| Toshiba DT01ACA100 1TB                              | 5         | 0.42%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.42%   |
| Seagate Expansion 1TB                               | 5         | 0.42%   |
| SanDisk NVMe SSD Drive 500GB                        | 5         | 0.42%   |
| SanDisk NVMe SSD Drive 1TB                          | 5         | 0.42%   |
| Samsung SSD 980 1TB                                 | 5         | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                      | 5         | 0.42%   |
| Samsung SSD 970 EVO Plus 2TB                        | 5         | 0.42%   |
| Samsung SSD 870 EVO 1TB                             | 5         | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4         | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4         | 0.34%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                | 4         | 0.34%   |
| Unknown MMC Card  64GB                              | 4         | 0.34%   |
| Unknown MMC Card  32GB                              | 4         | 0.34%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.34%   |
| Toshiba HDWD110 1TB                                 | 4         | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 4         | 0.34%   |
| Seagate ST2000LM015-2E8174 2TB                      | 4         | 0.34%   |
| Seagate ST2000LM007-1R8174 2TB                      | 4         | 0.34%   |
| Samsung SSD 980 500GB                               | 4         | 0.34%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 0.34%   |
| Samsung SSD 850 EVO 250GB                           | 4         | 0.34%   |
| Samsung NVMe SSD Drive 500GB                        | 4         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 169    | 34.16%  |
| WDC                 | 97        | 125    | 30.12%  |
| Toshiba             | 38        | 48     | 11.8%   |
| Hitachi             | 24        | 24     | 7.45%   |
| HGST                | 19        | 23     | 5.9%    |
| Samsung Electronics | 14        | 15     | 4.35%   |
| SABRENT             | 4         | 6      | 1.24%   |
| Maxtor              | 3         | 3      | 0.93%   |
| USB3.0              | 2         | 2      | 0.62%   |
| Unknown             | 2         | 2      | 0.62%   |
| JMicron Technology  | 2         | 2      | 0.62%   |
| Apple               | 2         | 2      | 0.62%   |
| SAGE                | 1         | 1      | 0.31%   |
| KESU                | 1         | 1      | 0.31%   |
| IET                 | 1         | 1      | 0.31%   |
| HPE                 | 1         | 6      | 0.31%   |
| HGST HTS            | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 88        | 118    | 25.07%  |
| Kingston            | 52        | 56     | 14.81%  |
| SanDisk             | 29        | 35     | 8.26%   |
| Crucial             | 28        | 33     | 7.98%   |
| WDC                 | 20        | 27     | 5.7%    |
| Intel               | 11        | 14     | 3.13%   |
| China               | 11        | 14     | 3.13%   |
| Patriot             | 9         | 11     | 2.56%   |
| Micron Technology   | 7         | 7      | 1.99%   |
| A-DATA Technology   | 7         | 8      | 1.99%   |
| Toshiba             | 5         | 8      | 1.42%   |
| PNY                 | 5         | 6      | 1.42%   |
| SPCC                | 4         | 4      | 1.14%   |
| LITEON              | 4         | 4      | 1.14%   |
| Lexar               | 4         | 4      | 1.14%   |
| Apple               | 4         | 4      | 1.14%   |
| Verbatim            | 3         | 3      | 0.85%   |
| Team                | 3         | 3      | 0.85%   |
| SK hynix            | 3         | 3      | 0.85%   |
| OCZ                 | 3         | 3      | 0.85%   |
| LITEONIT            | 3         | 3      | 0.85%   |
| GOODRAM             | 3         | 3      | 0.85%   |
| Transcend           | 2         | 2      | 0.57%   |
| Smart               | 2         | 2      | 0.57%   |
| Plextor             | 2         | 2      | 0.57%   |
| Netac               | 2         | 2      | 0.57%   |
| KODAK               | 2         | 2      | 0.57%   |
| Intenso             | 2         | 2      | 0.57%   |
| Emtec               | 2         | 2      | 0.57%   |
| Apacer              | 2         | 2      | 0.57%   |
| VISIPRO             | 1         | 1      | 0.28%   |
| ValueTech           | 1         | 1      | 0.28%   |
| tecmiyo             | 1         | 3      | 0.28%   |
| T-FORCE             | 1         | 1      | 0.28%   |
| Smartbuy            | 1         | 1      | 0.28%   |
| Seagate             | 1         | 1      | 0.28%   |
| Ramos Technology    | 1         | 1      | 0.28%   |
| R580                | 1         | 1      | 0.28%   |
| Pioneer             | 1         | 1      | 0.28%   |
| NGFF                | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 327       | 426    | 34.53%  |
| SSD     | 302       | 420    | 31.89%  |
| HDD     | 262       | 431    | 27.67%  |
| MMC     | 36        | 43     | 3.8%    |
| Unknown | 20        | 28     | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 420       | 797    | 50.36%  |
| NVMe | 327       | 424    | 39.21%  |
| SAS  | 51        | 84     | 6.12%   |
| MMC  | 36        | 43     | 4.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 302       | 445    | 50.67%  |
| 0.51-1.0   | 173       | 230    | 29.03%  |
| 1.01-2.0   | 61        | 74     | 10.23%  |
| 3.01-4.0   | 30        | 55     | 5.03%   |
| 4.01-10.0  | 18        | 33     | 3.02%   |
| 2.01-3.0   | 10        | 12     | 1.68%   |
| 10.01-20.0 | 2         | 2      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 159       | 23.14%  |
| 101-250        | 141       | 20.52%  |
| 501-1000       | 126       | 18.34%  |
| 1001-2000      | 96        | 13.97%  |
| More than 3000 | 56        | 8.15%   |
| 2001-3000      | 42        | 6.11%   |
| 51-100         | 31        | 4.51%   |
| 1-20           | 26        | 3.78%   |
| 21-50          | 9         | 1.31%   |
| Unknown        | 1         | 0.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 144       | 20.84%  |
| 101-250        | 129       | 18.67%  |
| 21-50          | 96        | 13.89%  |
| 251-500        | 94        | 13.6%   |
| 51-100         | 82        | 11.87%  |
| 501-1000       | 66        | 9.55%   |
| 1001-2000      | 40        | 5.79%   |
| More than 3000 | 27        | 3.91%   |
| 2001-3000      | 12        | 1.74%   |
| Unknown        | 1         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 2.78%   |
| Seagate ST500DM002-1BD142 500GB          | 2         | 2      | 2.78%   |
| Seagate ST2000LM007-1R8174 2TB           | 2         | 2      | 2.78%   |
| Samsung Electronics SSD 870 EVO 1TB      | 2         | 2      | 2.78%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 2.78%   |
| HGST HTS721010A9E630 1TB                 | 2         | 2      | 2.78%   |
| Crucial CT525MX300SSD1 528GB             | 2         | 2      | 2.78%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1      | 1.39%   |
| WDC WD5000AZRX-00A3KB0 500GB             | 1         | 1      | 1.39%   |
| WDC WD5000AVVS-63M8B0 500GB              | 1         | 1      | 1.39%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1         | 1      | 1.39%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1         | 1      | 1.39%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1         | 1      | 1.39%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1         | 1      | 1.39%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 1.39%   |
| WDC WD10EADS-00L5B1 1TB                  | 1         | 1      | 1.39%   |
| WDC WD10EACS-65D6B0 1TB                  | 1         | 1      | 1.39%   |
| VISIPRO SSD 256GB                        | 1         | 1      | 1.39%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 1.39%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.39%   |
| tecmiyo SATA SSD 128GB                   | 1         | 3      | 1.39%   |
| T-FORCE SSD 512GB                        | 1         | 1      | 1.39%   |
| SK hynix BC711 HFM256GD3JX013N 256GB     | 1         | 1      | 1.39%   |
| Seagate ST9750420AS 752GB                | 1         | 1      | 1.39%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 1.39%   |
| Seagate ST4000VN008-2DR166 4TB           | 1         | 2      | 1.39%   |
| Seagate ST3500630AS 500GB                | 1         | 1      | 1.39%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1      | 1.39%   |
| Seagate ST3160827AS 160GB                | 1         | 1      | 1.39%   |
| Seagate ST3160023A 160GB                 | 1         | 1      | 1.39%   |
| Seagate ST31500341AS 1TB                 | 1         | 1      | 1.39%   |
| Seagate ST31000524AS 1TB                 | 1         | 2      | 1.39%   |
| Seagate ST2000LM015-2E8174 2TB           | 1         | 1      | 1.39%   |
| Seagate ST1000DM003-1SB102 1TB           | 1         | 1      | 1.39%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 1      | 1.39%   |
| SanDisk SSD U100 128GB                   | 1         | 1      | 1.39%   |
| SanDisk SSD PLUS 240GB                   | 1         | 1      | 1.39%   |
| SanDisk SDSSDX240GG25 240GB              | 1         | 1      | 1.39%   |
| Samsung Electronics SSD 840 Series 250GB | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 19     | 21.74%  |
| WDC                 | 9         | 10     | 13.04%  |
| Hitachi             | 7         | 7      | 10.14%  |
| Samsung Electronics | 6         | 6      | 8.7%    |
| Crucial             | 5         | 5      | 7.25%   |
| HGST                | 4         | 4      | 5.8%    |
| SK hynix            | 3         | 3      | 4.35%   |
| SanDisk             | 3         | 3      | 4.35%   |
| Kingston            | 3         | 3      | 4.35%   |
| Toshiba             | 2         | 2      | 2.9%    |
| Micron Technology   | 2         | 2      | 2.9%    |
| Intel               | 2         | 5      | 2.9%    |
| VISIPRO             | 1         | 1      | 1.45%   |
| tecmiyo             | 1         | 3      | 1.45%   |
| T-FORCE             | 1         | 1      | 1.45%   |
| R580                | 1         | 1      | 1.45%   |
| Maxtor              | 1         | 1      | 1.45%   |
| LITEONIT            | 1         | 1      | 1.45%   |
| BAITITON            | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 19     | 38.46%  |
| WDC                 | 8         | 9      | 20.51%  |
| Hitachi             | 7         | 7      | 17.95%  |
| HGST                | 4         | 4      | 10.26%  |
| Toshiba             | 2         | 2      | 5.13%   |
| Samsung Electronics | 2         | 2      | 5.13%   |
| Maxtor              | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 44     | 55.38%  |
| SSD  | 25        | 31     | 38.46%  |
| NVMe | 4         | 4      | 6.15%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 379       | 660    | 49.87%  |
| Detected | 316       | 607    | 41.58%  |
| Malfunc  | 64        | 79     | 8.42%   |
| Failed   | 1         | 2      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 399       | 42.72%  |
| AMD                            | 155       | 16.6%   |
| Samsung Electronics            | 92        | 9.85%   |
| SanDisk                        | 62        | 6.64%   |
| SK hynix                       | 32        | 3.43%   |
| Kingston Technology Company    | 26        | 2.78%   |
| Phison Electronics             | 24        | 2.57%   |
| Toshiba America Info Systems   | 22        | 2.36%   |
| Micron Technology              | 19        | 2.03%   |
| Micron/Crucial Technology      | 17        | 1.82%   |
| KIOXIA                         | 16        | 1.71%   |
| ASMedia Technology             | 14        | 1.5%    |
| Solid State Storage Technology | 6         | 0.64%   |
| Silicon Motion                 | 6         | 0.64%   |
| JMicron Technology             | 6         | 0.64%   |
| ADATA Technology               | 6         | 0.64%   |
| Union Memory (Shenzhen)        | 4         | 0.43%   |
| Realtek Semiconductor          | 4         | 0.43%   |
| Marvell Technology Group       | 4         | 0.43%   |
| Seagate Technology             | 3         | 0.32%   |
| LSI Logic / Symbios Logic      | 3         | 0.32%   |
| Apple                          | 3         | 0.32%   |
| Nvidia                         | 2         | 0.21%   |
| Zhaoxin                        | 1         | 0.11%   |
| VIA Technologies               | 1         | 0.11%   |
| Silicon Image                  | 1         | 0.11%   |
| Shenzhen Longsys Electronics   | 1         | 0.11%   |
| OCZ Technology Group           | 1         | 0.11%   |
| O2 Micro                       | 1         | 0.11%   |
| INNOGRIT                       | 1         | 0.11%   |
| Hewlett-Packard                | 1         | 0.11%   |
| Broadcom / LSI                 | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 112       | 10.69%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 44        | 4.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 40        | 3.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 33        | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 29        | 2.77%   |
| AMD 400 Series Chipset SATA Controller                                         | 28        | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21        | 2%      |
| Samsung NVMe SSD Controller 980                                                | 20        | 1.91%   |
| Micron Non-Volatile memory controller                                          | 19        | 1.81%   |
| AMD 500 Series Chipset SATA Controller                                         | 18        | 1.72%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 16        | 1.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 16        | 1.53%   |
| SanDisk Non-Volatile memory controller                                         | 16        | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 1.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 16        | 1.53%   |
| Intel Tiger Lake-LP SATA Controller                                            | 14        | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14        | 1.34%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 13        | 1.24%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 12        | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 12        | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 12        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 1.05%   |
| Intel SATA Controller [RAID mode]                                              | 11        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 1.05%   |
| Phison E12 NVMe Controller                                                     | 10        | 0.95%   |
| Kingston Company Company Non-Volatile memory controller                        | 10        | 0.95%   |
| Intel SSD 660P Series                                                          | 10        | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 0.95%   |
| Kingston Company A2000 NVMe SSD                                                | 9         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 0.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 9         | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 0.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 7         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 480       | 51.84%  |
| NVMe | 326       | 35.21%  |
| RAID | 79        | 8.53%   |
| IDE  | 39        | 4.21%   |
| SAS  | 1         | 0.11%   |
| SCSI | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 474       | 70.33%  |
| AMD          | 198       | 29.38%  |
| CentaurHauls | 1         | 0.15%   |
| ARM          | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 15        | 2.23%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 15        | 2.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 14        | 2.08%   |
| Intel 12th Gen Core i7-12700H            | 12        | 1.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 11        | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 10        | 1.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 10        | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 9         | 1.34%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 8         | 1.19%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 8         | 1.19%   |
| AMD Ryzen 5 5600X 6-Core Processor       | 8         | 1.19%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 7         | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 6         | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 6         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 0.89%   |
| Intel 12th Gen Core i7-1260P             | 6         | 0.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 5         | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 5         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 5         | 0.74%   |
| Intel Core i5-10400F CPU @ 2.90GHz       | 5         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 5         | 0.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 5         | 0.74%   |
| AMD Ryzen 5 2600X Six-Core Processor     | 5         | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 4         | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 0.59%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 4         | 0.59%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 4         | 0.59%   |
| Intel Core i5-9600K CPU @ 3.70GHz        | 4         | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 4         | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 4         | 0.59%   |
| Intel Core i5-10300H CPU @ 2.50GHz       | 4         | 0.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 4         | 0.59%   |
| Intel 12th Gen Core i7-1255U             | 4         | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 4         | 0.59%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 4         | 0.59%   |
| AMD Ryzen 9 5900HX with Radeon Graphics  | 4         | 0.59%   |
| AMD Ryzen 7 5700G with Radeon Graphics   | 4         | 0.59%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 4         | 0.59%   |
| AMD Ryzen 5 3600 6-Core Processor        | 4         | 0.59%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 3         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 145       | 21.51%  |
| Intel Core i5           | 122       | 18.1%   |
| Other                   | 94        | 13.95%  |
| AMD Ryzen 7             | 62        | 9.2%    |
| AMD Ryzen 5             | 59        | 8.75%   |
| Intel Core i3           | 31        | 4.6%    |
| Intel Celeron           | 24        | 3.56%   |
| AMD Ryzen 9             | 21        | 3.12%   |
| Intel Xeon              | 16        | 2.37%   |
| Intel Pentium           | 14        | 2.08%   |
| Intel Core 2 Duo        | 10        | 1.48%   |
| AMD Ryzen 3             | 10        | 1.48%   |
| Intel Pentium Silver    | 6         | 0.89%   |
| Intel Core i9           | 6         | 0.89%   |
| AMD Ryzen 7 PRO         | 6         | 0.89%   |
| AMD FX                  | 6         | 0.89%   |
| AMD A6                  | 5         | 0.74%   |
| AMD A8                  | 4         | 0.59%   |
| AMD Ryzen Threadripper  | 3         | 0.45%   |
| AMD Ryzen 5 PRO         | 3         | 0.45%   |
| Intel Core m3           | 2         | 0.3%    |
| Intel Core 2 Quad       | 2         | 0.3%    |
| Intel Atom              | 2         | 0.3%    |
| AMD Phenom II X4        | 2         | 0.3%    |
| AMD Phenom II X2        | 2         | 0.3%    |
| AMD Opteron             | 2         | 0.3%    |
| AMD E                   | 2         | 0.3%    |
| AMD A4                  | 2         | 0.3%    |
| Intel Pentium Gold      | 1         | 0.15%   |
| Intel Core 2            | 1         | 0.15%   |
| Intel Celeron Dual-Core | 1         | 0.15%   |
| AMD Sempron             | 1         | 0.15%   |
| AMD PRO A10             | 1         | 0.15%   |
| AMD Phenom II X6        | 1         | 0.15%   |
| AMD Phenom              | 1         | 0.15%   |
| AMD E1                  | 1         | 0.15%   |
| AMD Athlon II X2        | 1         | 0.15%   |
| AMD Athlon 64 X2        | 1         | 0.15%   |
| AMD A10                 | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 247       | 36.65%  |
| 2       | 172       | 25.52%  |
| 6       | 107       | 15.88%  |
| 8       | 90        | 13.35%  |
| 12      | 18        | 2.67%   |
| 14      | 15        | 2.23%   |
| 16      | 9         | 1.34%   |
| 10      | 9         | 1.34%   |
| 1       | 3         | 0.45%   |
| 36      | 1         | 0.15%   |
| 5       | 1         | 0.15%   |
| 3       | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 670       | 99.41%  |
| 2       | 3         | 0.45%   |
| Unknown | 1         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 540       | 80%     |
| 1       | 134       | 19.85%  |
| Unknown | 1         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 674       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 37.48%  |
| 0x306a9    | 27        | 3.95%   |
| 0x806c1    | 25        | 3.66%   |
| 0x0a50000c | 25        | 3.66%   |
| 0x906a3    | 22        | 3.22%   |
| 0x306c3    | 20        | 2.93%   |
| 0x806ea    | 19        | 2.78%   |
| 0x906ea    | 14        | 2.05%   |
| 0x08608103 | 13        | 1.9%    |
| 0x806ec    | 12        | 1.76%   |
| 0x806e9    | 12        | 1.76%   |
| 0x206a7    | 12        | 1.76%   |
| 0x08600106 | 12        | 1.76%   |
| 0x906e9    | 10        | 1.46%   |
| 0x08701021 | 10        | 1.46%   |
| 0x506e3    | 9         | 1.32%   |
| 0x406e3    | 9         | 1.32%   |
| 0x0800820d | 7         | 1.02%   |
| 0xa0653    | 6         | 0.88%   |
| 0xa0652    | 6         | 0.88%   |
| 0x706a8    | 6         | 0.88%   |
| 0x40651    | 6         | 0.88%   |
| 0x0a50000d | 6         | 0.88%   |
| 0x906ed    | 5         | 0.73%   |
| 0x906a4    | 5         | 0.73%   |
| 0x806d1    | 5         | 0.73%   |
| 0x806c2    | 5         | 0.73%   |
| 0x706a1    | 5         | 0.73%   |
| 0x406f1    | 5         | 0.73%   |
| 0x40661    | 5         | 0.73%   |
| 0x08608102 | 5         | 0.73%   |
| 0x010000c8 | 5         | 0.73%   |
| 0xa0655    | 4         | 0.59%   |
| 0x1067a    | 4         | 0.59%   |
| 0x0a201205 | 4         | 0.59%   |
| 0x08108109 | 4         | 0.59%   |
| 0x90672    | 3         | 0.44%   |
| 0x506c9    | 3         | 0.44%   |
| 0x20652    | 3         | 0.44%   |
| 0x0a201016 | 3         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 112       | 16.57%  |
| Zen 3            | 64        | 9.47%   |
| IvyBridge        | 58        | 8.58%   |
| Haswell          | 58        | 8.58%   |
| TigerLake        | 45        | 6.66%   |
| Unknown          | 42        | 6.21%   |
| Zen 2            | 35        | 5.18%   |
| Skylake          | 31        | 4.59%   |
| Alderlake Hybrid | 29        | 4.29%   |
| Zen+             | 27        | 3.99%   |
| SandyBridge      | 26        | 3.85%   |
| CometLake        | 22        | 3.25%   |
| Goldmont plus    | 20        | 2.96%   |
| Zen              | 13        | 1.92%   |
| IceLake          | 11        | 1.63%   |
| Piledriver       | 10        | 1.48%   |
| Broadwell        | 10        | 1.48%   |
| Westmere         | 8         | 1.18%   |
| Penryn           | 8         | 1.18%   |
| K10              | 8         | 1.18%   |
| Silvermont       | 6         | 0.89%   |
| Nehalem          | 6         | 0.89%   |
| Core             | 6         | 0.89%   |
| Goldmont         | 5         | 0.74%   |
| Excavator        | 5         | 0.74%   |
| Puma             | 3         | 0.44%   |
| K10 Llano        | 3         | 0.44%   |
| Bobcat           | 2         | 0.3%    |
| Steamroller      | 1         | 0.15%   |
| K8 Hammer        | 1         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 367       | 43.9%   |
| Nvidia                     | 257       | 30.74%  |
| AMD                        | 206       | 24.64%  |
| Matrox Electronics Systems | 3         | 0.36%   |
| ASPEED Technology          | 2         | 0.24%   |
| Zhaoxin                    | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 39        | 4.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 38        | 4.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 32        | 3.77%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 23        | 2.71%   |
| Intel UHD Graphics 620                                                                | 20        | 2.36%   |
| AMD Renoir                                                                            | 20        | 2.36%   |
| Intel HD Graphics 620                                                                 | 19        | 2.24%   |
| AMD Lucienne                                                                          | 19        | 2.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 17        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 16        | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 15        | 1.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 14        | 1.65%   |
| Intel HD Graphics 630                                                                 | 13        | 1.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 13        | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 12        | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 12        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 11        | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 10        | 1.18%   |
| Intel HD Graphics 530                                                                 | 10        | 1.18%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 9         | 1.06%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 8         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 8         | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 8         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 7         | 0.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 6         | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                | 6         | 0.71%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 6         | 0.71%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 6         | 0.71%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 6         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 5         | 0.59%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 5         | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 5         | 0.59%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 5         | 0.59%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 5         | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 0.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 4         | 0.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 231       | 34.22%  |
| 1 x AMD                  | 143       | 21.19%  |
| 1 x Nvidia               | 133       | 19.7%   |
| Intel + Nvidia           | 96        | 14.22%  |
| Intel + AMD              | 28        | 4.15%   |
| AMD + Nvidia             | 23        | 3.41%   |
| 2 x AMD                  | 9         | 1.33%   |
| Other                    | 3         | 0.44%   |
| 2 x Nvidia               | 2         | 0.3%    |
| Nvidia + ASPEED          | 2         | 0.3%    |
| 1 x Zhaoxin              | 1         | 0.15%   |
| Nvidia + Matrox          | 1         | 0.15%   |
| 1 x Matrox               | 1         | 0.15%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.15%   |
| AMD + Matrox             | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 480       | 70.9%   |
| Proprietary | 182       | 26.88%  |
| Unknown     | 15        | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 428       | 62.76%  |
| 0.01-0.5   | 66        | 9.68%   |
| 1.01-2.0   | 56        | 8.21%   |
| 3.01-4.0   | 37        | 5.43%   |
| 7.01-8.0   | 33        | 4.84%   |
| 0.51-1.0   | 29        | 4.25%   |
| 5.01-6.0   | 20        | 2.93%   |
| 8.01-16.0  | 9         | 1.32%   |
| 16.01-24.0 | 2         | 0.29%   |
| 4.01-5.0   | 1         | 0.15%   |
| 2.01-3.0   | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 102       | 12.81%  |
| AU Optronics            | 83        | 10.43%  |
| BOE                     | 80        | 10.05%  |
| Chimei Innolux          | 76        | 9.55%   |
| LG Display              | 65        | 8.17%   |
| Dell                    | 52        | 6.53%   |
| Goldstar                | 47        | 5.9%    |
| Hewlett-Packard         | 32        | 4.02%   |
| Acer                    | 26        | 3.27%   |
| Philips                 | 22        | 2.76%   |
| BenQ                    | 21        | 2.64%   |
| Sharp                   | 16        | 2.01%   |
| AOC                     | 15        | 1.88%   |
| Ancor Communications    | 15        | 1.88%   |
| InfoVision              | 11        | 1.38%   |
| Apple                   | 11        | 1.38%   |
| Iiyama                  | 10        | 1.26%   |
| Lenovo                  | 9         | 1.13%   |
| ASUSTek Computer        | 8         | 1.01%   |
| Sony                    | 7         | 0.88%   |
| CSO                     | 7         | 0.88%   |
| Chi Mei Optoelectronics | 7         | 0.88%   |
| NEC Computers           | 5         | 0.63%   |
| ViewSonic               | 4         | 0.5%    |
| Vizio                   | 3         | 0.38%   |
| Sceptre Tech            | 3         | 0.38%   |
| PANDA                   | 3         | 0.38%   |
| Panasonic               | 3         | 0.38%   |
| MSI                     | 3         | 0.38%   |
| Idek Iiyama             | 3         | 0.38%   |
| HKC                     | 3         | 0.38%   |
| Gigabyte Technology     | 3         | 0.38%   |
| SLD                     | 2         | 0.25%   |
| RTK                     | 2         | 0.25%   |
| LG Electronics          | 2         | 0.25%   |
| IBM                     | 2         | 0.25%   |
| Fujitsu Siemens         | 2         | 0.25%   |
| Eizo                    | 2         | 0.25%   |
| Denver                  | 2         | 0.25%   |
| Xiaomi                  | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 0.85%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.36%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 3         | 0.36%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.36%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.36%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 3         | 0.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.36%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.36%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.36%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3         | 0.36%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 2         | 0.24%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2         | 0.24%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.24%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 2         | 0.24%   |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                     | 2         | 0.24%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 2         | 0.24%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 2         | 0.24%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 2         | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.24%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 2         | 0.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.24%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 2         | 0.24%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.24%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 387       | 52.09%  |
| 1366x768 (WXGA)    | 93        | 12.52%  |
| 3840x2160 (4K)     | 58        | 7.81%   |
| 2560x1440 (QHD)    | 41        | 5.52%   |
| 1920x1200 (WUXGA)  | 31        | 4.17%   |
| 1600x900 (HD+)     | 19        | 2.56%   |
| 1680x1050 (WSXGA+) | 18        | 2.42%   |
| 1280x1024 (SXGA)   | 13        | 1.75%   |
| 3440x1440          | 11        | 1.48%   |
| 2880x1800          | 11        | 1.48%   |
| 2560x1600          | 11        | 1.48%   |
| 2560x1080          | 10        | 1.35%   |
| 1440x900 (WXGA+)   | 5         | 0.67%   |
| 1280x800 (WXGA)    | 4         | 0.54%   |
| 3840x1080          | 3         | 0.4%    |
| 2256x1504          | 3         | 0.4%    |
| 2240x1400          | 3         | 0.4%    |
| 2520x1680          | 2         | 0.27%   |
| 1360x768           | 2         | 0.27%   |
| 1280x720 (HD)      | 2         | 0.27%   |
| 1024x768 (XGA)     | 2         | 0.27%   |
| Unknown            | 2         | 0.27%   |
| 5760x1080          | 1         | 0.13%   |
| 3840x1600          | 1         | 0.13%   |
| 3840x1200          | 1         | 0.13%   |
| 3600x1200          | 1         | 0.13%   |
| 3072x1920          | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2736x1824          | 1         | 0.13%   |
| 2288x1287          | 1         | 0.13%   |
| 2160x1440          | 1         | 0.13%   |
| 2160x1350          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 197       | 24.66%  |
| 24      | 74        | 9.26%   |
| 14      | 71        | 8.89%   |
| 27      | 69        | 8.64%   |
| 13      | 63        | 7.88%   |
| 23      | 56        | 7.01%   |
| 21      | 47        | 5.88%   |
| 17      | 43        | 5.38%   |
| 31      | 22        | 2.75%   |
| 34      | 20        | 2.5%    |
| 16      | 16        | 2%      |
| 22      | 12        | 1.5%    |
| 19      | 11        | 1.38%   |
| Unknown | 11        | 1.38%   |
| 18      | 8         | 1%      |
| 12      | 8         | 1%      |
| 11      | 8         | 1%      |
| 32      | 6         | 0.75%   |
| 25      | 6         | 0.75%   |
| 72      | 5         | 0.63%   |
| 54      | 5         | 0.63%   |
| 40      | 5         | 0.63%   |
| 20      | 5         | 0.63%   |
| 84      | 3         | 0.38%   |
| 49      | 3         | 0.38%   |
| 46      | 3         | 0.38%   |
| 69      | 2         | 0.25%   |
| 65      | 2         | 0.25%   |
| 60      | 2         | 0.25%   |
| 36      | 2         | 0.25%   |
| 28      | 2         | 0.25%   |
| 26      | 2         | 0.25%   |
| 10      | 2         | 0.25%   |
| 142     | 1         | 0.13%   |
| 78      | 1         | 0.13%   |
| 55      | 1         | 0.13%   |
| 48      | 1         | 0.13%   |
| 43      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 38      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 303       | 39%     |
| 501-600        | 176       | 22.65%  |
| 401-500        | 77        | 9.91%   |
| 351-400        | 55        | 7.08%   |
| 201-300        | 55        | 7.08%   |
| 601-700        | 35        | 4.5%    |
| 701-800        | 27        | 3.47%   |
| 1001-1500      | 17        | 2.19%   |
| 1501-2000      | 11        | 1.42%   |
| Unknown        | 11        | 1.42%   |
| 801-900        | 7         | 0.9%    |
| 901-1000       | 2         | 0.26%   |
| More than 2000 | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 546       | 79.13%  |
| 16/10   | 87        | 12.61%  |
| 21/9    | 22        | 3.19%   |
| 5/4     | 11        | 1.59%   |
| 3/2     | 10        | 1.45%   |
| Unknown | 8         | 1.16%   |
| 32/9    | 3         | 0.43%   |
| 4/3     | 2         | 0.29%   |
| 1.00    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 201       | 25.7%   |
| 201-250        | 140       | 17.9%   |
| 81-90          | 105       | 13.43%  |
| 301-350        | 71        | 9.08%   |
| 351-500        | 46        | 5.88%   |
| 121-130        | 37        | 4.73%   |
| 71-80          | 30        | 3.84%   |
| 151-200        | 30        | 3.84%   |
| 251-300        | 29        | 3.71%   |
| More than 1000 | 23        | 2.94%   |
| 501-1000       | 17        | 2.17%   |
| 141-150        | 12        | 1.53%   |
| 111-120        | 11        | 1.41%   |
| Unknown        | 11        | 1.41%   |
| 51-60          | 8         | 1.02%   |
| 61-70          | 7         | 0.9%    |
| 41-50          | 2         | 0.26%   |
| 131-140        | 1         | 0.13%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 251       | 33.38%  |
| 51-100        | 228       | 30.32%  |
| 101-120       | 146       | 19.41%  |
| 161-240       | 71        | 9.44%   |
| 1-50          | 24        | 3.19%   |
| More than 240 | 21        | 2.79%   |
| Unknown       | 11        | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 501       | 73.57%  |
| 2     | 142       | 20.85%  |
| 0     | 18        | 2.64%   |
| 3     | 15        | 2.2%    |
| 4     | 5         | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 389       | 37.58%  |
| Intel                             | 354       | 34.2%   |
| Qualcomm Atheros                  | 87        | 8.41%   |
| Broadcom                          | 47        | 4.54%   |
| MediaTek                          | 37        | 3.57%   |
| TP-Link                           | 14        | 1.35%   |
| Ralink Technology                 | 14        | 1.35%   |
| ASIX Electronics                  | 9         | 0.87%   |
| Samsung Electronics               | 8         | 0.77%   |
| Aquantia                          | 7         | 0.68%   |
| Ralink                            | 6         | 0.58%   |
| Huawei Technologies               | 6         | 0.58%   |
| Sierra Wireless                   | 5         | 0.48%   |
| Marvell Technology Group          | 4         | 0.39%   |
| Broadcom Limited                  | 4         | 0.39%   |
| Xiaomi                            | 3         | 0.29%   |
| Lenovo                            | 3         | 0.29%   |
| DisplayLink                       | 3         | 0.29%   |
| Qualcomm                          | 2         | 0.19%   |
| Nvidia                            | 2         | 0.19%   |
| NetGear                           | 2         | 0.19%   |
| Google                            | 2         | 0.19%   |
| Ericsson Business Mobile Networks | 2         | 0.19%   |
| D-Link System                     | 2         | 0.19%   |
| D-Link                            | 2         | 0.19%   |
| ASUSTek Computer                  | 2         | 0.19%   |
| Apple                             | 2         | 0.19%   |
| ZyXEL Communications              | 1         | 0.1%    |
| Wilocity                          | 1         | 0.1%    |
| VIA Technologies                  | 1         | 0.1%    |
| U-Blox                            | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| NIIMBOT                           | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Microsoft                         | 1         | 0.1%    |
| Mercucys                          | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| LG Electronics                    | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Hewlett-Packard                   | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 253       | 21%     |
| Intel Wi-Fi 6 AX200                                               | 40        | 3.32%   |
| Intel Wi-Fi 6 AX201                                               | 32        | 2.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 28        | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 2.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 25        | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 1.41%   |
| Intel Wireless 7260                                               | 17        | 1.41%   |
| Intel Wireless 8265 / 8275                                        | 16        | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 16        | 1.33%   |
| Intel Ethernet Controller I225-V                                  | 16        | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 1.16%   |
| Intel Wireless 7265                                               | 13        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 12        | 1%      |
| Intel Ethernet Connection I217-LM                                 | 12        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1%      |
| Realtek 802.11ac NIC                                              | 10        | 0.83%   |
| Intel Wireless 8260                                               | 10        | 0.83%   |
| Intel Wireless 3165                                               | 10        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 9         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.58%   |
| Realtek 802.11n WLAN Adapter                                      | 7         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 270       | 46.47%  |
| Realtek Semiconductor             | 118       | 20.31%  |
| Qualcomm Atheros                  | 63        | 10.84%  |
| Broadcom                          | 38        | 6.54%   |
| MediaTek                          | 27        | 4.65%   |
| Ralink Technology                 | 14        | 2.41%   |
| TP-Link                           | 12        | 2.07%   |
| Ralink                            | 6         | 1.03%   |
| Sierra Wireless                   | 5         | 0.86%   |
| Broadcom Limited                  | 4         | 0.69%   |
| Qualcomm                          | 2         | 0.34%   |
| NetGear                           | 2         | 0.34%   |
| Marvell Technology Group          | 2         | 0.34%   |
| Ericsson Business Mobile Networks | 2         | 0.34%   |
| D-Link System                     | 2         | 0.34%   |
| D-Link                            | 2         | 0.34%   |
| ASUSTek Computer                  | 2         | 0.34%   |
| ZyXEL Communications              | 1         | 0.17%   |
| Wilocity                          | 1         | 0.17%   |
| Qualcomm Atheros Communications   | 1         | 0.17%   |
| Microsoft                         | 1         | 0.17%   |
| Mercucys                          | 1         | 0.17%   |
| Linksys                           | 1         | 0.17%   |
| LG Electronics                    | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| Belkin Components                 | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 40        | 6.81%   |
| Intel Wi-Fi 6 AX201                                           | 32        | 5.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 26        | 4.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 25        | 4.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 22        | 3.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 19        | 3.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 17        | 2.9%    |
| Intel Wireless 7260                                           | 17        | 2.9%    |
| Intel Wireless 8265 / 8275                                    | 16        | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 15        | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 14        | 2.39%   |
| Intel Wireless 7265                                           | 13        | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 13        | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 12        | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 12        | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 12        | 2.04%   |
| Realtek 802.11ac NIC                                          | 10        | 1.7%    |
| Intel Wireless 8260                                           | 10        | 1.7%    |
| Intel Wireless 3165                                           | 10        | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                | 9         | 1.53%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 9         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 9         | 1.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 8         | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 7         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 7         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 7         | 1.19%   |
| Realtek 802.11n WLAN Adapter                                  | 7         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 7         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 6         | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 6         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 5         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 5         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                | 5         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 5         | 0.85%   |
| Intel Wireless-AC 9260                                        | 5         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 5         | 0.85%   |
| Intel Centrino Advanced-N 6235                                | 5         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 0.85%   |
| Ralink MT7601U Wireless Adapter                               | 4         | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 4         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 331       | 55.26%  |
| Intel                    | 164       | 27.38%  |
| Qualcomm Atheros         | 27        | 4.51%   |
| Broadcom                 | 16        | 2.67%   |
| MediaTek                 | 10        | 1.67%   |
| ASIX Electronics         | 9         | 1.5%    |
| Samsung Electronics      | 8         | 1.34%   |
| Aquantia                 | 7         | 1.17%   |
| Huawei Technologies      | 6         | 1%      |
| Xiaomi                   | 3         | 0.5%    |
| Lenovo                   | 3         | 0.5%    |
| DisplayLink              | 3         | 0.5%    |
| TP-Link                  | 2         | 0.33%   |
| Nvidia                   | 2         | 0.33%   |
| Marvell Technology Group | 2         | 0.33%   |
| Google                   | 2         | 0.33%   |
| Apple                    | 2         | 0.33%   |
| VIA Technologies         | 1         | 0.17%   |
| ICS Advent               | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 253       | 41.27%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 4.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 3.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 3.43%   |
| Intel I211 Gigabit Network Connection                             | 16        | 2.61%   |
| Intel Ethernet Controller I225-V                                  | 16        | 2.61%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 1.47%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 1.47%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 1.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.98%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.82%   |
| Intel Ethernet Connection (14) I219-V                             | 5         | 0.82%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.82%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 0.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.82%   |
| Huawei MLA-L11                                                    | 4         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.49%   |
| Intel Ethernet Connection (11) I219-V                             | 3         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.49%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.49%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 552       | 50.18%  |
| Ethernet | 543       | 49.36%  |
| Modem    | 4         | 0.36%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 430       | 60.56%  |
| Ethernet | 280       | 39.44%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 355       | 52.67%  |
| 1     | 288       | 42.73%  |
| 3     | 14        | 2.08%   |
| 0     | 13        | 1.93%   |
| 4     | 3         | 0.45%   |
| 6     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 483       | 71.24%  |
| Yes  | 195       | 28.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 233       | 47.07%  |
| Realtek Semiconductor           | 64        | 12.93%  |
| Cambridge Silicon Radio         | 35        | 7.07%   |
| Qualcomm Atheros Communications | 29        | 5.86%   |
| IMC Networks                    | 25        | 5.05%   |
| Foxconn / Hon Hai               | 21        | 4.24%   |
| Broadcom                        | 21        | 4.24%   |
| Lite-On Technology              | 16        | 3.23%   |
| ASUSTek Computer                | 11        | 2.22%   |
| Apple                           | 10        | 2.02%   |
| MediaTek                        | 5         | 1.01%   |
| Toshiba                         | 4         | 0.81%   |
| Realtek                         | 4         | 0.81%   |
| Edimax Technology               | 4         | 0.81%   |
| TP-Link                         | 3         | 0.61%   |
| Dell                            | 3         | 0.61%   |
| Marvell Semiconductor           | 2         | 0.4%    |
| Hewlett-Packard                 | 2         | 0.4%    |
| Foxconn International           | 1         | 0.2%    |
| Conwise Technology              | 1         | 0.2%    |
| Alps Electric                   | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 63        | 12.7%   |
| Intel AX201 Bluetooth                               | 53        | 10.69%  |
| Realtek Bluetooth Radio                             | 49        | 9.88%   |
| Intel AX200 Bluetooth                               | 38        | 7.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35        | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 6.05%   |
| Intel Bluetooth Device                              | 21        | 4.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 2.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 2.42%   |
| Intel AX210 Bluetooth                               | 11        | 2.22%   |
| IMC Networks Wireless_Device                        | 10        | 2.02%   |
| Lite-On Wireless_Device                             | 9         | 1.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.61%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.21%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.21%   |
| Apple Bluetooth Host Controller                     | 6         | 1.21%   |
| MediaTek Wireless_Device                            | 5         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.01%   |
| ASUS ASUS USB-BT500                                 | 5         | 1.01%   |
| IMC Networks Bluetooth Device                       | 4         | 0.81%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.81%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.81%   |
| TP-Link TPuLink UB500 Adapter                       | 3         | 0.6%    |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 2         | 0.4%    |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.4%    |
| Edimax Bluetooth Adapter                            | 2         | 0.4%    |
| Dell DW375 Bluetooth Module                         | 2         | 0.4%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.4%    |
| ASUS Qualcomm Bluetooth 4.1                         | 2         | 0.4%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.2%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.2%    |
| Toshiba Bluetooth Device                            | 1         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 463       | 45.62%  |
| AMD                      | 231       | 22.76%  |
| Nvidia                   | 195       | 19.21%  |
| C-Media Electronics      | 20        | 1.97%   |
| GN Netcom                | 8         | 0.79%   |
| JMTek                    | 7         | 0.69%   |
| Texas Instruments        | 4         | 0.39%   |
| Razer USA                | 4         | 0.39%   |
| Lenovo                   | 4         | 0.39%   |
| Generalplus Technology   | 4         | 0.39%   |
| Creative Labs            | 4         | 0.39%   |
| Blue Microphones         | 4         | 0.39%   |
| VIA Technologies         | 3         | 0.3%    |
| Tenx Technology          | 3         | 0.3%    |
| Kingston Technology      | 3         | 0.3%    |
| Focusrite-Novation       | 3         | 0.3%    |
| ZOOM                     | 2         | 0.2%    |
| TerraTec Electronic      | 2         | 0.2%    |
| SteelSeries ApS          | 2         | 0.2%    |
| Realtek Semiconductor    | 2         | 0.2%    |
| Micro Star International | 2         | 0.2%    |
| M-Audio                  | 2         | 0.2%    |
| Logitech                 | 2         | 0.2%    |
| KORG                     | 2         | 0.2%    |
| Corsair                  | 2         | 0.2%    |
| BY EDIFIER               | 2         | 0.2%    |
| ASUSTek Computer         | 2         | 0.2%    |
| Arturia                  | 2         | 0.2%    |
| Apple                    | 2         | 0.2%    |
| Zhaoxin                  | 1         | 0.1%    |
| Yamaha                   | 1         | 0.1%    |
| Veho                     | 1         | 0.1%    |
| Unknown (ABC)            | 1         | 0.1%    |
| Unknown                  | 1         | 0.1%    |
| Sony                     | 1         | 0.1%    |
| Silicon Motion           | 1         | 0.1%    |
| Samson Technologies      | 1         | 0.1%    |
| Roland                   | 1         | 0.1%    |
| QinHeng Electronics      | 1         | 0.1%    |
| Princeton Technology     | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 104       | 8.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71        | 5.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 57        | 4.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 55        | 4.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 45        | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35        | 2.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 35        | 2.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 31        | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 27        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22        | 1.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 15        | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                              | 15        | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 1.25%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 14        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 1%      |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 11        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.92%   |
| AMD FCH Azalia Controller                                                  | 11        | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11        | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 10        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.75%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 9         | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9         | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.67%   |
| Nvidia Audio device                                                        | 8         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 135       | 25.42%  |
| SK hynix            | 86        | 16.2%   |
| Kingston            | 59        | 11.11%  |
| Micron Technology   | 51        | 9.6%    |
| Crucial             | 46        | 8.66%   |
| Corsair             | 29        | 5.46%   |
| G.Skill             | 21        | 3.95%   |
| Unknown             | 19        | 3.58%   |
| Unknown (ABCD)      | 10        | 1.88%   |
| A-DATA Technology   | 9         | 1.69%   |
| Unknown             | 8         | 1.51%   |
| Team                | 6         | 1.13%   |
| Elpida              | 6         | 1.13%   |
| Ramaxel Technology  | 4         | 0.75%   |
| Patriot             | 4         | 0.75%   |
| AMD                 | 4         | 0.75%   |
| Wilk                | 3         | 0.56%   |
| Nanya Technology    | 3         | 0.56%   |
| Transcend           | 2         | 0.38%   |
| Silicon Power       | 2         | 0.38%   |
| PNY                 | 2         | 0.38%   |
| GOODRAM             | 2         | 0.38%   |
| Atermiter           | 2         | 0.38%   |
| Unknown (8A02)      | 1         | 0.19%   |
| Unifosa             | 1         | 0.19%   |
| Teikon              | 1         | 0.19%   |
| Super Talent        | 1         | 0.19%   |
| Smart               | 1         | 0.19%   |
| Shenzhen Zhongteng  | 1         | 0.19%   |
| Shenzhen WODPOSIT   | 1         | 0.19%   |
| SHARETRONIC         | 1         | 0.19%   |
| Qumo                | 1         | 0.19%   |
| Qimonda             | 1         | 0.19%   |
| Lexar               | 1         | 0.19%   |
| Kingmax             | 1         | 0.19%   |
| Imation             | 1         | 0.19%   |
| Hewlett-Packard     | 1         | 0.19%   |
| Goldkey             | 1         | 0.19%   |
| ff                  | 1         | 0.19%   |
| Essencore Limited   | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 1.43%   |
| Unknown                                                          | 8         | 1.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.72%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.54%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.54%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 0.54%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 3         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.54%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Crucial RAM CT16G4SFRA32A.C8FF 16GB SODIMM DDR4 3200MT/s         | 3         | 0.54%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.54%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s             | 2         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.36%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 2         | 0.36%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.36%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.36%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 283       | 62.06%  |
| DDR3    | 102       | 22.37%  |
| LPDDR4  | 28        | 6.14%   |
| DDR5    | 14        | 3.07%   |
| DDR2    | 7         | 1.54%   |
| LPDDR3  | 6         | 1.32%   |
| SDRAM   | 5         | 1.1%    |
| LPDDR5  | 5         | 1.1%    |
| Unknown | 5         | 1.1%    |
| DDR     | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 273       | 59.09%  |
| DIMM         | 139       | 30.09%  |
| Row Of Chips | 45        | 9.74%   |
| Chip         | 2         | 0.43%   |
| Unknown      | 2         | 0.43%   |
| RIMM         | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 225       | 45.92%  |
| 4096  | 107       | 21.84%  |
| 16384 | 96        | 19.59%  |
| 32768 | 29        | 5.92%   |
| 2048  | 28        | 5.71%   |
| 1024  | 5         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 127       | 26.35%  |
| 1600    | 77        | 15.98%  |
| 2667    | 70        | 14.52%  |
| 2400    | 42        | 8.71%   |
| 1333    | 22        | 4.56%   |
| 2133    | 19        | 3.94%   |
| 3600    | 15        | 3.11%   |
| 4800    | 11        | 2.28%   |
| 4267    | 11        | 2.28%   |
| 1867    | 8         | 1.66%   |
| 3266    | 7         | 1.45%   |
| 2666    | 6         | 1.24%   |
| 1334    | 6         | 1.24%   |
| 6400    | 5         | 1.04%   |
| 3800    | 5         | 1.04%   |
| 3000    | 5         | 1.04%   |
| 1066    | 4         | 0.83%   |
| 667     | 4         | 0.83%   |
| 4266    | 3         | 0.62%   |
| 3333    | 3         | 0.62%   |
| 3066    | 3         | 0.62%   |
| 2933    | 3         | 0.62%   |
| 6000    | 2         | 0.41%   |
| 3866    | 2         | 0.41%   |
| Unknown | 2         | 0.41%   |
| 52217   | 1         | 0.21%   |
| 8400    | 1         | 0.21%   |
| 5800    | 1         | 0.21%   |
| 4133    | 1         | 0.21%   |
| 4000    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 3666    | 1         | 0.21%   |
| 3467    | 1         | 0.21%   |
| 3466    | 1         | 0.21%   |
| 3400    | 1         | 0.21%   |
| 3334    | 1         | 0.21%   |
| 2800    | 1         | 0.21%   |
| 2448    | 1         | 0.21%   |
| 2176    | 1         | 0.21%   |
| 2134    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 34.62%  |
| Seiko Epson         | 5         | 19.23%  |
| Canon               | 3         | 11.54%  |
| Brother Industries  | 3         | 11.54%  |
| Samsung Electronics | 2         | 7.69%   |
| Xerox               | 1         | 3.85%   |
| Kyocera             | 1         | 3.85%   |
| Dymo-CoStar         | 1         | 3.85%   |
| Datamax-O'Neil      | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson L3110 Series              | 2         | 7.69%   |
| Samsung M2070 Series                  | 2         | 7.69%   |
| Xerox Phaser 3140 and 3155            | 1         | 3.85%   |
| Seiko Epson XP-3100 Series            | 1         | 3.85%   |
| Seiko Epson L220 Series               | 1         | 3.85%   |
| Seiko Epson ET-2700 Series            | 1         | 3.85%   |
| Kyocera Mita FS-820                   | 1         | 3.85%   |
| HP OfficeJet 5500 series              | 1         | 3.85%   |
| HP LaserJet Professional P 1102w      | 1         | 3.85%   |
| HP LaserJet P2015 series              | 1         | 3.85%   |
| HP LaserJet 1022                      | 1         | 3.85%   |
| HP ENVY 4500 series                   | 1         | 3.85%   |
| HP DeskJet D2300                      | 1         | 3.85%   |
| HP DeskJet 3700 series                | 1         | 3.85%   |
| HP DeskJet 3630 series                | 1         | 3.85%   |
| HP ColorLaserJet M253-M254            | 1         | 3.85%   |
| Dymo-CoStar LabelWriter 450           | 1         | 3.85%   |
| Datamax-O'Neil Datamax E-4304         | 1         | 3.85%   |
| Canon PIXMA MX470 Series              | 1         | 3.85%   |
| Canon LaserShot LBP-1120 Printer      | 1         | 3.85%   |
| Canon iP2600 series                   | 1         | 3.85%   |
| Brother PT-P700 P-touch Label Printer | 1         | 3.85%   |
| Brother MFC-J460DW                    | 1         | 3.85%   |
| Brother HL-2230 series                | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 5         | 71.43%  |
| Seiko Epson    | 1         | 14.29%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2         | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 14.29%  |
| Canon CanoScan LiDE 220                     | 1         | 14.29%  |
| Canon CanoScan LiDE 210                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 86        | 18.9%   |
| Microdia                               | 46        | 10.11%  |
| Acer                                   | 40        | 8.79%   |
| IMC Networks                           | 39        | 8.57%   |
| Quanta                                 | 38        | 8.35%   |
| Logitech                               | 34        | 7.47%   |
| Realtek Semiconductor                  | 31        | 6.81%   |
| Sunplus Innovation Technology          | 18        | 3.96%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.96%   |
| Luxvisions Innotech Limited            | 11        | 2.42%   |
| Syntek                                 | 8         | 1.76%   |
| Lite-On Technology                     | 8         | 1.76%   |
| Silicon Motion                         | 7         | 1.54%   |
| Apple                                  | 7         | 1.54%   |
| Samsung Electronics                    | 5         | 1.1%    |
| Alcor Micro                            | 5         | 1.1%    |
| Y Media                                | 4         | 0.88%   |
| Microsoft                              | 4         | 0.88%   |
| Suyin                                  | 3         | 0.66%   |
| Z-Star Microelectronics                | 2         | 0.44%   |
| Unknown                                | 2         | 0.44%   |
| SunplusIT                              | 2         | 0.44%   |
| KYE Systems (Mouse Systems)            | 2         | 0.44%   |
| Jieli Technology                       | 2         | 0.44%   |
| icSpring                               | 2         | 0.44%   |
| HD WEBCAM                              | 2         | 0.44%   |
| Generalplus Technology                 | 2         | 0.44%   |
| DLEQNA19IFK6G2                         | 2         | 0.44%   |
| ARC International                      | 2         | 0.44%   |
| Xiaomi                                 | 1         | 0.22%   |
| USB Camera CS                          | 1         | 0.22%   |
| STEREOLABS                             | 1         | 0.22%   |
| Sonix Technology                       | 1         | 0.22%   |
| SN0002                                 | 1         | 0.22%   |
| ShineTech                              | 1         | 0.22%   |
| Ricoh                                  | 1         | 0.22%   |
| Razer USA                              | 1         | 0.22%   |
| Pixart Imaging                         | 1         | 0.22%   |
| Novatek Microelectronics               | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 25        | 5.46%   |
| Microdia Integrated_Webcam_HD                                   | 20        | 4.37%   |
| Acer Integrated Camera                                          | 18        | 3.93%   |
| IMC Networks Integrated Camera                                  | 13        | 2.84%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 11        | 2.4%    |
| Chicony HD Webcam                                               | 9         | 1.97%   |
| Realtek Integrated_Webcam_HD                                    | 8         | 1.75%   |
| Quanta HP TrueVision HD Camera                                  | 8         | 1.75%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 1.53%   |
| Chicony HD User Facing                                          | 7         | 1.53%   |
| Syntek Integrated Camera                                        | 6         | 1.31%   |
| Quanta HD User Facing                                           | 6         | 1.31%   |
| Microdia Integrated_Webcam_FHD                                  | 6         | 1.31%   |
| Logitech Webcam C270                                            | 6         | 1.31%   |
| Logitech HD Pro Webcam C920                                     | 6         | 1.31%   |
| Samsung Galaxy A5 (MTP)                                         | 5         | 1.09%   |
| Quanta HP Wide Vision HD Camera                                 | 5         | 1.09%   |
| Microdia Webcam Vitade AF                                       | 5         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 1.09%   |
| Y Media USB Camera                                              | 4         | 0.87%   |
| Quanta ACER HD User Facing                                      | 4         | 0.87%   |
| Chicony USB2.0 Camera                                           | 4         | 0.87%   |
| Chicony Integrated Camera (1280x720@30)                         | 4         | 0.87%   |
| Chicony HP Wide Vision HD Camera                                | 4         | 0.87%   |
| Chicony HP HD Camera                                            | 4         | 0.87%   |
| Realtek USB Camera                                              | 3         | 0.66%   |
| Quanta HD Webcam                                                | 3         | 0.66%   |
| Microdia CameraA                                                | 3         | 0.66%   |
| Luxvisions Innotech Limited Integrated Camera                   | 3         | 0.66%   |
| Logitech Webcam C310                                            | 3         | 0.66%   |
| Logitech C922 Pro Stream Webcam                                 | 3         | 0.66%   |
| Logitech C920 PRO HD Webcam                                     | 3         | 0.66%   |
| Chicony HP Truevision HD                                        | 3         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 3         | 0.66%   |
| Apple FaceTime HD Camera (Built-in)                             | 3         | 0.66%   |
| Acer ThinkPad Integrated Camera                                 | 3         | 0.66%   |
| Acer HD Webcam                                                  | 3         | 0.66%   |
| Unknown HD camera                                               | 2         | 0.44%   |
| Silicon Motion WebCam SC-13HDL11939N                            | 2         | 0.44%   |
| Silicon Motion 300k Pixel Camera                                | 2         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 29        | 32.22%  |
| Shenzhen Goodix Technology | 23        | 25.56%  |
| Validity Sensors           | 20        | 22.22%  |
| Elan Microelectronics      | 10        | 11.11%  |
| Upek                       | 3         | 3.33%   |
| AuthenTec                  | 3         | 3.33%   |
| STMicroelectronics         | 1         | 1.11%   |
| Focal-systems.Corp         | 1         | 1.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 19        | 21.11%  |
| Unknown                                                                    | 13        | 14.44%  |
| Elan ELAN:ARM-M4                                                           | 6         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 4.44%   |
| Elan ELAN:Fingerprint                                                      | 4         | 4.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 3.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 3.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.22%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 2.22%   |
| Synaptics  WBDI                                                            | 2         | 2.22%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.22%   |
| Validity Sensors VFS491                                                    | 1         | 1.11%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.11%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.11%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.11%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.11%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.11%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.11%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.11%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.11%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 38.24%  |
| Alcor Micro           | 10        | 29.41%  |
| Upek                  | 3         | 8.82%   |
| BIT4ID                | 2         | 5.88%   |
| SCM Microsystems      | 1         | 2.94%   |
| OmniKey               | 1         | 2.94%   |
| O2 Micro              | 1         | 2.94%   |
| Lenovo                | 1         | 2.94%   |
| Gemalto (was Gemplus) | 1         | 2.94%   |
| Advanced Card Systems | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 29.41%  |
| Broadcom 58200                                                               | 6         | 17.65%  |
| Broadcom 5880                                                                | 4         | 11.76%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 8.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.88%   |
| BIT4ID miniLector EVO                                                        | 2         | 5.88%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 2.94%   |
| OmniKey CardMan 1021                                                         | 1         | 2.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.94%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.94%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.94%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 2.94%   |
| Advanced Card Systems ACR39U                                                 | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 472       | 69.11%  |
| 1     | 168       | 24.6%   |
| 2     | 38        | 5.56%   |
| 3     | 3         | 0.44%   |
| 9     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 89        | 35.46%  |
| Graphics card            | 35        | 13.94%  |
| Chipcard                 | 31        | 12.35%  |
| Net/wireless             | 28        | 11.16%  |
| Multimedia controller    | 15        | 5.98%   |
| Camera                   | 15        | 5.98%   |
| Unassigned class         | 11        | 4.38%   |
| Communication controller | 7         | 2.79%   |
| Bluetooth                | 7         | 2.79%   |
| Sound                    | 5         | 1.99%   |
| Net/ethernet             | 3         | 1.2%    |
| Network                  | 2         | 0.8%    |
| Modem                    | 1         | 0.4%    |
| Dvb card                 | 1         | 0.4%    |
| Card reader              | 1         | 0.4%    |


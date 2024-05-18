Linux in Pakistan - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Pakistan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Pakistan/Desktop/README.md) and [notebooks](/Location/Pakistan/Notebook/README.md).

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

Total: 612

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5547               | Notebook    | [b8dd9a912d](https://linux-hardware.org/?probe=b8dd9a912d) | May 07, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [c9bddc6d00](https://linux-hardware.org/?probe=c9bddc6d00) | May 06, 2024 |
| HP            | 1000                        | Notebook    | [c2783cbe1f](https://linux-hardware.org/?probe=c2783cbe1f) | May 04, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [91569d1ab1](https://linux-hardware.org/?probe=91569d1ab1) | Apr 30, 2024 |
| Gigabyte      | B250M-D2VX-SI-CF            | Desktop     | [5c277491cf](https://linux-hardware.org/?probe=5c277491cf) | Apr 27, 2024 |
| Dell          | Latitude E6410              | Notebook    | [e1b489ec79](https://linux-hardware.org/?probe=e1b489ec79) | Apr 25, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ae077e8935](https://linux-hardware.org/?probe=ae077e8935) | Apr 23, 2024 |
| Dell          | 0VRWRC A00                  | Desktop     | [19c02bd31c](https://linux-hardware.org/?probe=19c02bd31c) | Apr 23, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [ac69abc7f8](https://linux-hardware.org/?probe=ac69abc7f8) | Apr 08, 2024 |
| Haier         | Y11C                        | Notebook    | [412c266aec](https://linux-hardware.org/?probe=412c266aec) | Apr 05, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [f3587d854e](https://linux-hardware.org/?probe=f3587d854e) | Apr 05, 2024 |
| Dell          | Latitude 5410               | Notebook    | [6916b94a45](https://linux-hardware.org/?probe=6916b94a45) | Mar 31, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [1115e42390](https://linux-hardware.org/?probe=1115e42390) | Mar 30, 2024 |
| Lenovo        | V14 G3 IAP 82TS             | Notebook    | [fd2f12c510](https://linux-hardware.org/?probe=fd2f12c510) | Mar 28, 2024 |
| Dell          | Latitude 9420               | Convertible | [a125bb2e0b](https://linux-hardware.org/?probe=a125bb2e0b) | Mar 23, 2024 |
| Dell          | Latitude 5410               | Notebook    | [d93cd1f9c2](https://linux-hardware.org/?probe=d93cd1f9c2) | Mar 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [869127a088](https://linux-hardware.org/?probe=869127a088) | Mar 13, 2024 |
| Dell          | Latitude 5410               | Notebook    | [b5dc4f7d43](https://linux-hardware.org/?probe=b5dc4f7d43) | Mar 13, 2024 |
| Dell          | Latitude 7300               | Notebook    | [01e6414d07](https://linux-hardware.org/?probe=01e6414d07) | Mar 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [3c51a5f5ed](https://linux-hardware.org/?probe=3c51a5f5ed) | Mar 06, 2024 |
| HP            | 18E6                        | Desktop     | [e26531db78](https://linux-hardware.org/?probe=e26531db78) | Mar 01, 2024 |
| HP            | ProLiant DL380p Gen8        | Server      | [032e32e32d](https://linux-hardware.org/?probe=032e32e32d) | Feb 23, 2024 |
| Lenovo        | V14 G3 IAP 82TS             | Notebook    | [91aad182bd](https://linux-hardware.org/?probe=91aad182bd) | Feb 20, 2024 |
| Lenovo        | V14 G3 IAP 82TS             | Notebook    | [c4d2285111](https://linux-hardware.org/?probe=c4d2285111) | Feb 19, 2024 |
| Dell          | Inspiron 7391 2n1           | Convertible | [a385dd2c39](https://linux-hardware.org/?probe=a385dd2c39) | Feb 16, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [258dc80f87](https://linux-hardware.org/?probe=258dc80f87) | Feb 11, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [f3cb8642e0](https://linux-hardware.org/?probe=f3cb8642e0) | Feb 01, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [dda1c0dfa9](https://linux-hardware.org/?probe=dda1c0dfa9) | Jan 29, 2024 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [5b803efc86](https://linux-hardware.org/?probe=5b803efc86) | Jan 26, 2024 |
| Acer          | Predator PH317-53           | Notebook    | [4b8b265f8c](https://linux-hardware.org/?probe=4b8b265f8c) | Jan 23, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [3fb985c33d](https://linux-hardware.org/?probe=3fb985c33d) | Jan 21, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [a25a75e986](https://linux-hardware.org/?probe=a25a75e986) | Jan 11, 2024 |
| Acer          | TMP455-M                    | Notebook    | [559512a222](https://linux-hardware.org/?probe=559512a222) | Jan 09, 2024 |
| Dell          | Inspiron 3593               | Notebook    | [cb4c4f82a1](https://linux-hardware.org/?probe=cb4c4f82a1) | Jan 02, 2024 |
| Dell          | Inspiron 3593               | Notebook    | [a2424d3523](https://linux-hardware.org/?probe=a2424d3523) | Jan 01, 2024 |
| MSI           | Z590-A PRO                  | Desktop     | [f6eb92aa92](https://linux-hardware.org/?probe=f6eb92aa92) | Dec 30, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [dc67ac3e38](https://linux-hardware.org/?probe=dc67ac3e38) | Dec 29, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [7a857447b4](https://linux-hardware.org/?probe=7a857447b4) | Dec 28, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [27f6eb03d0](https://linux-hardware.org/?probe=27f6eb03d0) | Dec 28, 2023 |
| Lenovo        | ThinkPad T410 2537HN2       | Notebook    | [c268085f95](https://linux-hardware.org/?probe=c268085f95) | Dec 20, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [eac468f369](https://linux-hardware.org/?probe=eac468f369) | Dec 20, 2023 |
| Dell          | Latitude E7440              | Notebook    | [35982f622e](https://linux-hardware.org/?probe=35982f622e) | Dec 17, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [4cdde5e9dc](https://linux-hardware.org/?probe=4cdde5e9dc) | Dec 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [9eb3de84e4](https://linux-hardware.org/?probe=9eb3de84e4) | Dec 10, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [a41eb50b0e](https://linux-hardware.org/?probe=a41eb50b0e) | Dec 04, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [4298ef81a3](https://linux-hardware.org/?probe=4298ef81a3) | Dec 04, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [e0e8d08912](https://linux-hardware.org/?probe=e0e8d08912) | Dec 01, 2023 |
| Dell          | Precision 7740              | Notebook    | [50b0f0be08](https://linux-hardware.org/?probe=50b0f0be08) | Nov 25, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [84c3c8db78](https://linux-hardware.org/?probe=84c3c8db78) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1060eb5e48](https://linux-hardware.org/?probe=1060eb5e48) | Nov 23, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [a4927b394e](https://linux-hardware.org/?probe=a4927b394e) | Nov 23, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | Notebook    | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| HP            | ZBook 15                    | Notebook    | [7959bd4b85](https://linux-hardware.org/?probe=7959bd4b85) | Nov 18, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [f292f81323](https://linux-hardware.org/?probe=f292f81323) | Nov 13, 2023 |
| HP            | 3646h                       | Desktop     | [1cfad160f4](https://linux-hardware.org/?probe=1cfad160f4) | Nov 12, 2023 |
| HP            | 845A                        | Desktop     | [95fbc211ec](https://linux-hardware.org/?probe=95fbc211ec) | Nov 11, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [cb1c24030f](https://linux-hardware.org/?probe=cb1c24030f) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcd7a71a14](https://linux-hardware.org/?probe=bcd7a71a14) | Nov 06, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | Desktop     | [65b9bad459](https://linux-hardware.org/?probe=65b9bad459) | Nov 03, 2023 |
| Dell          | Precision 7740              | Notebook    | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [18398fe53c](https://linux-hardware.org/?probe=18398fe53c) | Oct 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [773814f03f](https://linux-hardware.org/?probe=773814f03f) | Oct 27, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [d76b3901c7](https://linux-hardware.org/?probe=d76b3901c7) | Oct 26, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [58d1baf31c](https://linux-hardware.org/?probe=58d1baf31c) | Oct 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6259de67f2](https://linux-hardware.org/?probe=6259de67f2) | Oct 23, 2023 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [33e4aebc37](https://linux-hardware.org/?probe=33e4aebc37) | Oct 21, 2023 |
| Dell          | Latitude 5491               | Notebook    | [c701f6e10d](https://linux-hardware.org/?probe=c701f6e10d) | Oct 21, 2023 |
| Dell          | Latitude 7300               | Notebook    | [e68476c5ee](https://linux-hardware.org/?probe=e68476c5ee) | Oct 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a8c11a4935](https://linux-hardware.org/?probe=a8c11a4935) | Oct 13, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [662889cd52](https://linux-hardware.org/?probe=662889cd52) | Oct 12, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [51c5671188](https://linux-hardware.org/?probe=51c5671188) | Oct 12, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [08444b33e9](https://linux-hardware.org/?probe=08444b33e9) | Oct 10, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [a58029a4f8](https://linux-hardware.org/?probe=a58029a4f8) | Oct 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS1A100    | Notebook    | [1b7097cf90](https://linux-hardware.org/?probe=1b7097cf90) | Oct 06, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [373685317f](https://linux-hardware.org/?probe=373685317f) | Oct 03, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [1959705750](https://linux-hardware.org/?probe=1959705750) | Oct 03, 2023 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [ae0c9bf33a](https://linux-hardware.org/?probe=ae0c9bf33a) | Oct 02, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS1A100    | Notebook    | [f4887bacc7](https://linux-hardware.org/?probe=f4887bacc7) | Sep 25, 2023 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [44784bdea7](https://linux-hardware.org/?probe=44784bdea7) | Sep 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f597ec9360](https://linux-hardware.org/?probe=f597ec9360) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [fd0da8d5ba](https://linux-hardware.org/?probe=fd0da8d5ba) | Sep 22, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [d85124e7d2](https://linux-hardware.org/?probe=d85124e7d2) | Sep 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [32cf98639a](https://linux-hardware.org/?probe=32cf98639a) | Sep 20, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [11d6fae345](https://linux-hardware.org/?probe=11d6fae345) | Sep 18, 2023 |
| Clevo         | P170HMx                     | Notebook    | [4abfcaf4ba](https://linux-hardware.org/?probe=4abfcaf4ba) | Sep 16, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [9720b79b9d](https://linux-hardware.org/?probe=9720b79b9d) | Sep 16, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [0f34501ff9](https://linux-hardware.org/?probe=0f34501ff9) | Sep 16, 2023 |
| Clevo         | P170HMx                     | Notebook    | [1a0ef2b235](https://linux-hardware.org/?probe=1a0ef2b235) | Sep 16, 2023 |
| HP            | Unknown                     | Notebook    | [defc1de0cf](https://linux-hardware.org/?probe=defc1de0cf) | Sep 11, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [08f7d373e7](https://linux-hardware.org/?probe=08f7d373e7) | Sep 07, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [cb4847f435](https://linux-hardware.org/?probe=cb4847f435) | Sep 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f01ca37e4c](https://linux-hardware.org/?probe=f01ca37e4c) | Aug 31, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [79855ccf9d](https://linux-hardware.org/?probe=79855ccf9d) | Aug 30, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | Desktop     | [187d930341](https://linux-hardware.org/?probe=187d930341) | Aug 29, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [c82147d598](https://linux-hardware.org/?probe=c82147d598) | Aug 29, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [4fe996e64f](https://linux-hardware.org/?probe=4fe996e64f) | Aug 29, 2023 |
| Unknown       | IPMSB-H61                   | Desktop     | [c104b6462e](https://linux-hardware.org/?probe=c104b6462e) | Aug 26, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| HP            | 18E7                        | Desktop     | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [7ef5fc5f0c](https://linux-hardware.org/?probe=7ef5fc5f0c) | Aug 23, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [5e8e8a6397](https://linux-hardware.org/?probe=5e8e8a6397) | Aug 22, 2023 |
| Toshiba       | Satellite L55-B             | Notebook    | [4b2bcc2231](https://linux-hardware.org/?probe=4b2bcc2231) | Aug 18, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | Notebook    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Dell          | Latitude E7450              | Notebook    | [9d787db93a](https://linux-hardware.org/?probe=9d787db93a) | Aug 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [ab45ffe407](https://linux-hardware.org/?probe=ab45ffe407) | Aug 07, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [e4d39c20bc](https://linux-hardware.org/?probe=e4d39c20bc) | Aug 05, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [aac7924f4e](https://linux-hardware.org/?probe=aac7924f4e) | Aug 05, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [ceca389ec4](https://linux-hardware.org/?probe=ceca389ec4) | Aug 03, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [814b3a8cf8](https://linux-hardware.org/?probe=814b3a8cf8) | Aug 02, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Gateway       | NV57H                       | Notebook    | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [30afe43d32](https://linux-hardware.org/?probe=30afe43d32) | Jul 28, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Dell          | Latitude 5480               | Notebook    | [2db18c20d1](https://linux-hardware.org/?probe=2db18c20d1) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dc3fd72332](https://linux-hardware.org/?probe=dc3fd72332) | Jul 18, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [2bd8f70433](https://linux-hardware.org/?probe=2bd8f70433) | Jul 17, 2023 |
| HP            | Unknown                     | Notebook    | [6100712075](https://linux-hardware.org/?probe=6100712075) | Jul 12, 2023 |
| Biostar       | H61MGV                      | Desktop     | [4fadeeb5bd](https://linux-hardware.org/?probe=4fadeeb5bd) | Jul 12, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [32f2a1756a](https://linux-hardware.org/?probe=32f2a1756a) | Jun 23, 2023 |
| Alienware     | x17 R2                      | Notebook    | [632fbfe682](https://linux-hardware.org/?probe=632fbfe682) | Jun 20, 2023 |
| Haier         | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1f5222a92f](https://linux-hardware.org/?probe=1f5222a92f) | Jun 15, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [4919ecc453](https://linux-hardware.org/?probe=4919ecc453) | Jun 14, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [911cc1f620](https://linux-hardware.org/?probe=911cc1f620) | Jun 14, 2023 |
| HP            | ProBook 6360b               | Notebook    | [cdef37cb2d](https://linux-hardware.org/?probe=cdef37cb2d) | Jun 09, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [2c98c872f8](https://linux-hardware.org/?probe=2c98c872f8) | Jun 08, 2023 |
| Clevo         | P170HMx                     | Notebook    | [6513e1e52e](https://linux-hardware.org/?probe=6513e1e52e) | Jun 08, 2023 |
| Clevo         | P170HMx                     | Notebook    | [7e2d7bfd0d](https://linux-hardware.org/?probe=7e2d7bfd0d) | Jun 06, 2023 |
| Dell          | Latitude E7450              | Notebook    | [fe7cb1e53f](https://linux-hardware.org/?probe=fe7cb1e53f) | Jun 03, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [b99041460e](https://linux-hardware.org/?probe=b99041460e) | May 27, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Dell          | Latitude E7450              | Notebook    | [4a88622321](https://linux-hardware.org/?probe=4a88622321) | May 26, 2023 |
| Dell          | Latitude 5480               | Notebook    | [adb6ba25f1](https://linux-hardware.org/?probe=adb6ba25f1) | May 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [45b63ce664](https://linux-hardware.org/?probe=45b63ce664) | May 25, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Precision 5520              | Notebook    | [a5e0cc8586](https://linux-hardware.org/?probe=a5e0cc8586) | May 24, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [b38d6399b4](https://linux-hardware.org/?probe=b38d6399b4) | May 22, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [f1d994fa47](https://linux-hardware.org/?probe=f1d994fa47) | May 22, 2023 |
| Dell          | Latitude E7450              | Notebook    | [51f34cd446](https://linux-hardware.org/?probe=51f34cd446) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e844aeb177](https://linux-hardware.org/?probe=e844aeb177) | May 19, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [68573d1b85](https://linux-hardware.org/?probe=68573d1b85) | May 13, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [9ba944eae5](https://linux-hardware.org/?probe=9ba944eae5) | May 09, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [3e9f94b26a](https://linux-hardware.org/?probe=3e9f94b26a) | May 09, 2023 |
| Dell          | Latitude E5440              | Notebook    | [6db42a9acc](https://linux-hardware.org/?probe=6db42a9acc) | May 08, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| Dell          | Latitude 5410               | Notebook    | [840aaee455](https://linux-hardware.org/?probe=840aaee455) | May 04, 2023 |
| Dell          | Latitude 5410               | Notebook    | [f95e1d32bf](https://linux-hardware.org/?probe=f95e1d32bf) | May 04, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| KEIAN         | KBM101K                     | Tablet      | [20982ffeb1](https://linux-hardware.org/?probe=20982ffeb1) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [f9228e78d3](https://linux-hardware.org/?probe=f9228e78d3) | Apr 25, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [44b6a5142e](https://linux-hardware.org/?probe=44b6a5142e) | Apr 25, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [5ac8ce1eb9](https://linux-hardware.org/?probe=5ac8ce1eb9) | Apr 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [7ec2b3ff95](https://linux-hardware.org/?probe=7ec2b3ff95) | Apr 14, 2023 |
| HP            | EliteBook 8470w             | Notebook    | [47e8a4441b](https://linux-hardware.org/?probe=47e8a4441b) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [e628a47ac6](https://linux-hardware.org/?probe=e628a47ac6) | Apr 01, 2023 |
| Dell          | G3 3500                     | Notebook    | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [3394687910](https://linux-hardware.org/?probe=3394687910) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| HP            | 1850                        | Desktop     | [5ae52efa64](https://linux-hardware.org/?probe=5ae52efa64) | Mar 25, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [f84f8c068b](https://linux-hardware.org/?probe=f84f8c068b) | Mar 15, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | Notebook    | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [7b5d4c040b](https://linux-hardware.org/?probe=7b5d4c040b) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [948a77b264](https://linux-hardware.org/?probe=948a77b264) | Mar 04, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f245db2b9a](https://linux-hardware.org/?probe=f245db2b9a) | Mar 04, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [009eefdc1d](https://linux-hardware.org/?probe=009eefdc1d) | Feb 28, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [17a7ee80ac](https://linux-hardware.org/?probe=17a7ee80ac) | Feb 28, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [329c0a65eb](https://linux-hardware.org/?probe=329c0a65eb) | Feb 25, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [6f65703034](https://linux-hardware.org/?probe=6f65703034) | Feb 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [876f755425](https://linux-hardware.org/?probe=876f755425) | Feb 19, 2023 |
| HP            | 339A                        | Desktop     | [07001c3589](https://linux-hardware.org/?probe=07001c3589) | Feb 19, 2023 |
| HP            | 339A                        | Desktop     | [0d7bb8b04a](https://linux-hardware.org/?probe=0d7bb8b04a) | Feb 19, 2023 |
| HP            | Notebook                    | Notebook    | [047fd0d69e](https://linux-hardware.org/?probe=047fd0d69e) | Feb 18, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| Unknown       | IPMSB-H61                   | Desktop     | [7e13c996bd](https://linux-hardware.org/?probe=7e13c996bd) | Feb 02, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [b7cec06bcb](https://linux-hardware.org/?probe=b7cec06bcb) | Jan 30, 2023 |
| Dell          | Latitude E7470              | Notebook    | [42ace80c0b](https://linux-hardware.org/?probe=42ace80c0b) | Jan 27, 2023 |
| HP            | ProBook 6565b               | Notebook    | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [bf9e573abf](https://linux-hardware.org/?probe=bf9e573abf) | Jan 25, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [dafb34058f](https://linux-hardware.org/?probe=dafb34058f) | Jan 17, 2023 |
| HP            | ENVY dv7                    | Notebook    | [4b7b0f98af](https://linux-hardware.org/?probe=4b7b0f98af) | Jan 15, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [43bee9503c](https://linux-hardware.org/?probe=43bee9503c) | Jan 11, 2023 |
| HP            | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [b55d0dfc1e](https://linux-hardware.org/?probe=b55d0dfc1e) | Jan 03, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [63adf72d53](https://linux-hardware.org/?probe=63adf72d53) | Jan 01, 2023 |
| HP            | 304Ah                       | Desktop     | [6106d55390](https://linux-hardware.org/?probe=6106d55390) | Dec 26, 2022 |
| Haier         | Y11C                        | Notebook    | [cc9a03834f](https://linux-hardware.org/?probe=cc9a03834f) | Dec 21, 2022 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [86f0e8ad5d](https://linux-hardware.org/?probe=86f0e8ad5d) | Dec 20, 2022 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [8122fe7426](https://linux-hardware.org/?probe=8122fe7426) | Dec 20, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [0b6bf86b5e](https://linux-hardware.org/?probe=0b6bf86b5e) | Dec 10, 2022 |
| Dell          | Latitude D620               | Notebook    | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| HP            | 198E                        | Desktop     | [9d22530b3c](https://linux-hardware.org/?probe=9d22530b3c) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | Notebook    | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| Dell          | Latitude D620               | Notebook    | [d45ad40496](https://linux-hardware.org/?probe=d45ad40496) | Nov 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [835a83d0ea](https://linux-hardware.org/?probe=835a83d0ea) | Nov 20, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [03426a19e5](https://linux-hardware.org/?probe=03426a19e5) | Nov 16, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [e7c7b6c8a7](https://linux-hardware.org/?probe=e7c7b6c8a7) | Nov 14, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8224e059c6](https://linux-hardware.org/?probe=8224e059c6) | Nov 14, 2022 |
| Timi          | TM1613                      | Notebook    | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [dcb6d439d4](https://linux-hardware.org/?probe=dcb6d439d4) | Nov 13, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [543c3778c3](https://linux-hardware.org/?probe=543c3778c3) | Nov 12, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f73ba4186b](https://linux-hardware.org/?probe=f73ba4186b) | Nov 11, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [143dc1e811](https://linux-hardware.org/?probe=143dc1e811) | Nov 05, 2022 |
| Lenovo        | ThinkPad E580 20KTA001GE    | Notebook    | [55dc6ac7ba](https://linux-hardware.org/?probe=55dc6ac7ba) | Oct 31, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| Dell          | Studio 1458                 | Notebook    | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [79f94ede46](https://linux-hardware.org/?probe=79f94ede46) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [cbacce92bd](https://linux-hardware.org/?probe=cbacce92bd) | Oct 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [2830144a8a](https://linux-hardware.org/?probe=2830144a8a) | Oct 04, 2022 |
| HP            | 18E7                        | Desktop     | [797aa81ce0](https://linux-hardware.org/?probe=797aa81ce0) | Oct 02, 2022 |
| HP            | 18E7                        | Desktop     | [69e4bb94f3](https://linux-hardware.org/?probe=69e4bb94f3) | Oct 02, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [b01a9ac97f](https://linux-hardware.org/?probe=b01a9ac97f) | Sep 24, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| HP            | ENVY 15                     | Notebook    | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [31e3939680](https://linux-hardware.org/?probe=31e3939680) | Sep 18, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [f207769c14](https://linux-hardware.org/?probe=f207769c14) | Sep 18, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ca96e9bf9b](https://linux-hardware.org/?probe=ca96e9bf9b) | Sep 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [be88e72feb](https://linux-hardware.org/?probe=be88e72feb) | Sep 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2b1c502b28](https://linux-hardware.org/?probe=2b1c502b28) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| HP            | ProBook 4540s               | Notebook    | [c1bf52b653](https://linux-hardware.org/?probe=c1bf52b653) | Sep 13, 2022 |
| HP            | ProBook 4540s               | Notebook    | [320e270f44](https://linux-hardware.org/?probe=320e270f44) | Sep 13, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [c03777782c](https://linux-hardware.org/?probe=c03777782c) | Sep 13, 2022 |
| HP            | Unknown                     | Notebook    | [5cf262a728](https://linux-hardware.org/?probe=5cf262a728) | Sep 10, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | Notebook    | [5beda28487](https://linux-hardware.org/?probe=5beda28487) | Sep 09, 2022 |
| Dell          | Latitude 3340               | Notebook    | [ec720c63b1](https://linux-hardware.org/?probe=ec720c63b1) | Sep 06, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | Notebook    | [3a466cef0a](https://linux-hardware.org/?probe=3a466cef0a) | Sep 05, 2022 |
| Dell          | Latitude E6420              | Notebook    | [98a628a92a](https://linux-hardware.org/?probe=98a628a92a) | Sep 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e9c43bd2ab](https://linux-hardware.org/?probe=e9c43bd2ab) | Sep 03, 2022 |
| Dell          | Latitude 3340               | Notebook    | [b9d472b965](https://linux-hardware.org/?probe=b9d472b965) | Sep 01, 2022 |
| Dell          | Latitude 7390               | Notebook    | [571b195a12](https://linux-hardware.org/?probe=571b195a12) | Aug 31, 2022 |
| Dell          | Latitude 7390               | Notebook    | [3c3f6114f6](https://linux-hardware.org/?probe=3c3f6114f6) | Aug 31, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5ba91d8167](https://linux-hardware.org/?probe=5ba91d8167) | Aug 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [23d73aa95c](https://linux-hardware.org/?probe=23d73aa95c) | Aug 30, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [bed3be5142](https://linux-hardware.org/?probe=bed3be5142) | Aug 30, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b588415d06](https://linux-hardware.org/?probe=b588415d06) | Aug 30, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | Notebook    | [3b1630e4bc](https://linux-hardware.org/?probe=3b1630e4bc) | Aug 30, 2022 |
| HP            | Unknown                     | Notebook    | [9b22ce41e3](https://linux-hardware.org/?probe=9b22ce41e3) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [1b2c235511](https://linux-hardware.org/?probe=1b2c235511) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [c563f4b965](https://linux-hardware.org/?probe=c563f4b965) | Aug 22, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| Dell          | Latitude 7400               | Notebook    | [7f870ac8c2](https://linux-hardware.org/?probe=7f870ac8c2) | Aug 17, 2022 |
| Acer          | Predator PH317-53           | Notebook    | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [072d897eda](https://linux-hardware.org/?probe=072d897eda) | Jul 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [07a671ae31](https://linux-hardware.org/?probe=07a671ae31) | Jul 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [3b30865387](https://linux-hardware.org/?probe=3b30865387) | Jul 20, 2022 |
| Quanta        | 2ABB 101                    | Desktop     | [3d241d58b9](https://linux-hardware.org/?probe=3d241d58b9) | Jul 13, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [52aab7f65b](https://linux-hardware.org/?probe=52aab7f65b) | Jul 12, 2022 |
| Sony          | VPCEA26FG                   | Notebook    | [c5432e157a](https://linux-hardware.org/?probe=c5432e157a) | Jul 11, 2022 |
| Dell          | Latitude E7450              | Notebook    | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| Sony          | VPCEA26FG                   | Notebook    | [2075c04c4c](https://linux-hardware.org/?probe=2075c04c4c) | Jul 03, 2022 |
| Sony          | VPCEA26FG                   | Notebook    | [b72a4de42b](https://linux-hardware.org/?probe=b72a4de42b) | Jul 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [18fbe5a2d0](https://linux-hardware.org/?probe=18fbe5a2d0) | Jun 28, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| HP            | 339A                        | Desktop     | [a20191b759](https://linux-hardware.org/?probe=a20191b759) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f9895656b6](https://linux-hardware.org/?probe=f9895656b6) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2e2bcb63d7](https://linux-hardware.org/?probe=2e2bcb63d7) | Jun 23, 2022 |
| HP            | 18E7                        | Desktop     | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [085f5c458d](https://linux-hardware.org/?probe=085f5c458d) | Jun 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [5bcb742cbe](https://linux-hardware.org/?probe=5bcb742cbe) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BV0005US    | Notebook    | [a795ed872f](https://linux-hardware.org/?probe=a795ed872f) | Jun 03, 2022 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [4508e41795](https://linux-hardware.org/?probe=4508e41795) | May 22, 2022 |
| HP            | Notebook                    | Notebook    | [dc587c572e](https://linux-hardware.org/?probe=dc587c572e) | May 22, 2022 |
| HP            | 1495                        | Desktop     | [9ec1730693](https://linux-hardware.org/?probe=9ec1730693) | May 11, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [07526b3b20](https://linux-hardware.org/?probe=07526b3b20) | May 10, 2022 |
| Dell          | Latitude 3330               | Notebook    | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| HP            | 3396                        | Desktop     | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [3e0d410668](https://linux-hardware.org/?probe=3e0d410668) | Apr 19, 2022 |
| HP            | 3396                        | Desktop     | [2c07ec89d4](https://linux-hardware.org/?probe=2c07ec89d4) | Apr 17, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1974bfe63a](https://linux-hardware.org/?probe=1974bfe63a) | Apr 15, 2022 |
| Dell          | Latitude 3520               | Notebook    | [ee204b07aa](https://linux-hardware.org/?probe=ee204b07aa) | Apr 11, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [9a817f6695](https://linux-hardware.org/?probe=9a817f6695) | Apr 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [57d44d9705](https://linux-hardware.org/?probe=57d44d9705) | Apr 03, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [e70c6e6d89](https://linux-hardware.org/?probe=e70c6e6d89) | Apr 03, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [1936ee53b3](https://linux-hardware.org/?probe=1936ee53b3) | Mar 22, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [a3aeef468a](https://linux-hardware.org/?probe=a3aeef468a) | Mar 12, 2022 |
| Dell          | 0HR330                      | Desktop     | [9e351420b6](https://linux-hardware.org/?probe=9e351420b6) | Mar 04, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [06db14c491](https://linux-hardware.org/?probe=06db14c491) | Mar 01, 2022 |
| Dell          | 0HR330                      | Desktop     | [7e4c13a9bd](https://linux-hardware.org/?probe=7e4c13a9bd) | Mar 01, 2022 |
| Dell          | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e0169c3e87](https://linux-hardware.org/?probe=e0169c3e87) | Feb 23, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1aa838368f](https://linux-hardware.org/?probe=1aa838368f) | Feb 20, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| HP            | 8717                        | Desktop     | [d5d2ee0ab5](https://linux-hardware.org/?probe=d5d2ee0ab5) | Feb 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [7fdd5b66fc](https://linux-hardware.org/?probe=7fdd5b66fc) | Feb 14, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [2d6ff07a82](https://linux-hardware.org/?probe=2d6ff07a82) | Feb 12, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [0dd77f2f7a](https://linux-hardware.org/?probe=0dd77f2f7a) | Feb 12, 2022 |
| HP            | 8061                        | Desktop     | [f721051d60](https://linux-hardware.org/?probe=f721051d60) | Feb 11, 2022 |
| HP            | 8717                        | Desktop     | [97d99714a1](https://linux-hardware.org/?probe=97d99714a1) | Feb 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5a9a256568](https://linux-hardware.org/?probe=5a9a256568) | Feb 01, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [4a0c4a62b7](https://linux-hardware.org/?probe=4a0c4a62b7) | Feb 01, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [c902cc42a6](https://linux-hardware.org/?probe=c902cc42a6) | Jan 18, 2022 |
| Dell          | 0DR845                      | Desktop     | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [ce839c3628](https://linux-hardware.org/?probe=ce839c3628) | Jan 08, 2022 |
| Lenovo        | ThinkPad T540p 20BFS5630... | Notebook    | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [70e6bfadc4](https://linux-hardware.org/?probe=70e6bfadc4) | Dec 26, 2021 |
| Acer          | Aspire ES1-411              | Notebook    | [9a5ebb6379](https://linux-hardware.org/?probe=9a5ebb6379) | Dec 19, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [0f7389c7d9](https://linux-hardware.org/?probe=0f7389c7d9) | Dec 14, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| HP            | 0B3Ch HP P/N                | Desktop     | [2805378159](https://linux-hardware.org/?probe=2805378159) | Dec 10, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [e662c8b956](https://linux-hardware.org/?probe=e662c8b956) | Dec 07, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [0784c5596b](https://linux-hardware.org/?probe=0784c5596b) | Dec 04, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [ebfaaee6ef](https://linux-hardware.org/?probe=ebfaaee6ef) | Dec 04, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [50a026d588](https://linux-hardware.org/?probe=50a026d588) | Dec 02, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [19fd4c2057](https://linux-hardware.org/?probe=19fd4c2057) | Nov 30, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [7493408721](https://linux-hardware.org/?probe=7493408721) | Nov 29, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [637bba1c58](https://linux-hardware.org/?probe=637bba1c58) | Nov 29, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [555032936f](https://linux-hardware.org/?probe=555032936f) | Nov 28, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [538c96bb62](https://linux-hardware.org/?probe=538c96bb62) | Nov 26, 2021 |
| Dell          | Latitude E6440              | Notebook    | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| HP            | Unknown                     | Notebook    | [ef28d45f68](https://linux-hardware.org/?probe=ef28d45f68) | Nov 23, 2021 |
| Dell          | G3 3579                     | Notebook    | [38e9f54ba1](https://linux-hardware.org/?probe=38e9f54ba1) | Nov 23, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| HP            | Unknown                     | Notebook    | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| Shuttle       | FS81                        | Desktop     | [ac6138c9d7](https://linux-hardware.org/?probe=ac6138c9d7) | Nov 19, 2021 |
| Shuttle       | FS81                        | Desktop     | [d889090212](https://linux-hardware.org/?probe=d889090212) | Nov 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cd386145b8](https://linux-hardware.org/?probe=cd386145b8) | Nov 18, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [f9ebb771b0](https://linux-hardware.org/?probe=f9ebb771b0) | Nov 14, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [67e5184b17](https://linux-hardware.org/?probe=67e5184b17) | Nov 13, 2021 |
| Dell          | Vostro 1500                 | Notebook    | [23aeb68ca2](https://linux-hardware.org/?probe=23aeb68ca2) | Nov 11, 2021 |
| HP            | 0AECh D                     | Desktop     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [72f1028535](https://linux-hardware.org/?probe=72f1028535) | Nov 09, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [e43d36b3cf](https://linux-hardware.org/?probe=e43d36b3cf) | Nov 09, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [98ddca21d9](https://linux-hardware.org/?probe=98ddca21d9) | Nov 06, 2021 |
| HP            | 0AECh D                     | Desktop     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| HP            | 650                         | Notebook    | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [bb1aa448fd](https://linux-hardware.org/?probe=bb1aa448fd) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [0e66d5fd62](https://linux-hardware.org/?probe=0e66d5fd62) | Oct 16, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [f2a84de135](https://linux-hardware.org/?probe=f2a84de135) | Oct 12, 2021 |
| Dell          | Latitude E5570              | Notebook    | [938d1a781d](https://linux-hardware.org/?probe=938d1a781d) | Oct 08, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| HP            | 0AECh D                     | Desktop     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [196fa579f8](https://linux-hardware.org/?probe=196fa579f8) | Oct 04, 2021 |
| Haier         | Y11C                        | Notebook    | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Dell          | Precision M6400             | Notebook    | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| Haier         | Y11C                        | Notebook    | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| HP            | 0AECh D                     | Desktop     | [202ada3fc3](https://linux-hardware.org/?probe=202ada3fc3) | Sep 23, 2021 |
| HP            | 3047h                       | Desktop     | [356ad972a7](https://linux-hardware.org/?probe=356ad972a7) | Sep 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| HP            | 1587h                       | Desktop     | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [321a93dff9](https://linux-hardware.org/?probe=321a93dff9) | Sep 07, 2021 |
| Shuttle       | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [c5c3b2d36c](https://linux-hardware.org/?probe=c5c3b2d36c) | Sep 02, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [ece6c14756](https://linux-hardware.org/?probe=ece6c14756) | Sep 02, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [262cc4f3e7](https://linux-hardware.org/?probe=262cc4f3e7) | Aug 29, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [7e939d9f5f](https://linux-hardware.org/?probe=7e939d9f5f) | Aug 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [966a09526a](https://linux-hardware.org/?probe=966a09526a) | Aug 14, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| Dell          | Latitude E5250              | Notebook    | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [7e8e35538a](https://linux-hardware.org/?probe=7e8e35538a) | Jul 26, 2021 |
| Dell          | Latitude E5250              | Notebook    | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell          | Latitude E5250              | Notebook    | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [4fc5079d7e](https://linux-hardware.org/?probe=4fc5079d7e) | Jul 20, 2021 |
| Dell          | Latitude E5250              | Notebook    | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [d89b69a6a3](https://linux-hardware.org/?probe=d89b69a6a3) | Jul 16, 2021 |
| Lenovo        | ThinkCentre M70e 0830F2U    | Desktop     | [8dad962f2f](https://linux-hardware.org/?probe=8dad962f2f) | Jul 09, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d320594f42](https://linux-hardware.org/?probe=d320594f42) | Jul 07, 2021 |
| Lenovo        | ThinkPad E14 20RA007SAD     | Notebook    | [eb51ce8f36](https://linux-hardware.org/?probe=eb51ce8f36) | Jul 07, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f4d326f499](https://linux-hardware.org/?probe=f4d326f499) | Jul 05, 2021 |
| Dell          | Precision 5530              | Notebook    | [7d267375f2](https://linux-hardware.org/?probe=7d267375f2) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [7236dc0c95](https://linux-hardware.org/?probe=7236dc0c95) | Jul 04, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [f5ac8e2aca](https://linux-hardware.org/?probe=f5ac8e2aca) | Jun 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [c3529dc2aa](https://linux-hardware.org/?probe=c3529dc2aa) | Jun 24, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| HP            | 158A                        | Desktop     | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| Dell          | Latitude 3510               | Notebook    | [79c73e5595](https://linux-hardware.org/?probe=79c73e5595) | Jun 09, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [2d9b300bd3](https://linux-hardware.org/?probe=2d9b300bd3) | May 13, 2021 |
| Dell          | Latitude E5250              | Notebook    | [8c3b8c27c8](https://linux-hardware.org/?probe=8c3b8c27c8) | May 10, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| Dell          | 06FW8P A01                  | Desktop     | [08f4c825cc](https://linux-hardware.org/?probe=08f4c825cc) | Apr 25, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [bc7c3f8c4d](https://linux-hardware.org/?probe=bc7c3f8c4d) | Apr 23, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [8d7a62ce1a](https://linux-hardware.org/?probe=8d7a62ce1a) | Apr 20, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [583acd1f2e](https://linux-hardware.org/?probe=583acd1f2e) | Apr 20, 2021 |
| Dell          | 06FW8P A01                  | Desktop     | [a0b4b692ff](https://linux-hardware.org/?probe=a0b4b692ff) | Apr 20, 2021 |
| Shuttle       | FS81                        | Desktop     | [14e78cfe43](https://linux-hardware.org/?probe=14e78cfe43) | Apr 20, 2021 |
| Dell          | Latitude E6420              | Notebook    | [6e3288ca3a](https://linux-hardware.org/?probe=6e3288ca3a) | Apr 11, 2021 |
| Dell          | Inspiron 17-7779            | Notebook    | [2cf1f86b67](https://linux-hardware.org/?probe=2cf1f86b67) | Apr 06, 2021 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Dell          | Latitude 3510               | Notebook    | [1ef27c1786](https://linux-hardware.org/?probe=1ef27c1786) | Mar 25, 2021 |
| ASUSTek       | PN61                        | Mini pc     | [45389ef622](https://linux-hardware.org/?probe=45389ef622) | Mar 24, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [eba311c4d7](https://linux-hardware.org/?probe=eba311c4d7) | Mar 22, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [e506fc315e](https://linux-hardware.org/?probe=e506fc315e) | Mar 21, 2021 |
| Dell          | 0GU083 A00                  | Desktop     | [03e87a4ada](https://linux-hardware.org/?probe=03e87a4ada) | Mar 20, 2021 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [eb713030d2](https://linux-hardware.org/?probe=eb713030d2) | Mar 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [a062baeb24](https://linux-hardware.org/?probe=a062baeb24) | Mar 12, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [2ab353f0c6](https://linux-hardware.org/?probe=2ab353f0c6) | Mar 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [6dbe550700](https://linux-hardware.org/?probe=6dbe550700) | Feb 28, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [67ea005277](https://linux-hardware.org/?probe=67ea005277) | Feb 24, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [b8a8ea9182](https://linux-hardware.org/?probe=b8a8ea9182) | Feb 24, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [ce415da689](https://linux-hardware.org/?probe=ce415da689) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [64c73f58bb](https://linux-hardware.org/?probe=64c73f58bb) | Feb 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [0426a1c07e](https://linux-hardware.org/?probe=0426a1c07e) | Feb 20, 2021 |
| Lenovo        | MAHOBAY 31900003 STD        | Desktop     | [845f5a30c2](https://linux-hardware.org/?probe=845f5a30c2) | Feb 13, 2021 |
| HP            | 14                          | Notebook    | [d5382b721f](https://linux-hardware.org/?probe=d5382b721f) | Feb 11, 2021 |
| Toshiba       | Satellite S50t-B            | Notebook    | [2fe86bc977](https://linux-hardware.org/?probe=2fe86bc977) | Feb 06, 2021 |
| Toshiba       | Satellite S50t-B            | Notebook    | [ec72426035](https://linux-hardware.org/?probe=ec72426035) | Feb 05, 2021 |
| Toshiba       | Satellite S50t-B            | Notebook    | [f7709c05cb](https://linux-hardware.org/?probe=f7709c05cb) | Feb 05, 2021 |
| HP            | 14                          | Notebook    | [f27a999e26](https://linux-hardware.org/?probe=f27a999e26) | Feb 03, 2021 |
| Sony          | SVE15126CXS                 | Notebook    | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [e3790fd911](https://linux-hardware.org/?probe=e3790fd911) | Jan 31, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [0ee13de953](https://linux-hardware.org/?probe=0ee13de953) | Jan 31, 2021 |
| Lenovo        | ThinkPad E15 20RD0088UE     | Notebook    | [d2bfe04a2b](https://linux-hardware.org/?probe=d2bfe04a2b) | Jan 28, 2021 |
| Lenovo        | ThinkCentre M58 7373C51     | Desktop     | [3e79476403](https://linux-hardware.org/?probe=3e79476403) | Jan 27, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [e4b829fff8](https://linux-hardware.org/?probe=e4b829fff8) | Jan 26, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [7db1cae3c0](https://linux-hardware.org/?probe=7db1cae3c0) | Jan 25, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [0421fbf0d1](https://linux-hardware.org/?probe=0421fbf0d1) | Jan 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS39800    | Notebook    | [7b4f78f648](https://linux-hardware.org/?probe=7b4f78f648) | Jan 10, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [c3c2bbd2bc](https://linux-hardware.org/?probe=c3c2bbd2bc) | Jan 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [01da85c434](https://linux-hardware.org/?probe=01da85c434) | Dec 25, 2020 |
| Dell          | Inspiron 7391 2n1           | Convertible | [597b76daa1](https://linux-hardware.org/?probe=597b76daa1) | Dec 25, 2020 |
| Dell          | Latitude E6510              | Notebook    | [2557f813e4](https://linux-hardware.org/?probe=2557f813e4) | Dec 15, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b04b3b207e](https://linux-hardware.org/?probe=b04b3b207e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [252afde67a](https://linux-hardware.org/?probe=252afde67a) | Dec 08, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [f84c7affac](https://linux-hardware.org/?probe=f84c7affac) | Dec 07, 2020 |
| Dell          | Latitude E7440              | Notebook    | [0d04075b3e](https://linux-hardware.org/?probe=0d04075b3e) | Dec 03, 2020 |
| Lenovo        | ThinkPad W500 40612HU       | Notebook    | [06465bf227](https://linux-hardware.org/?probe=06465bf227) | Dec 01, 2020 |
| Lenovo        | ThinkPad T60 1951WAT        | Notebook    | [4da418a597](https://linux-hardware.org/?probe=4da418a597) | Nov 28, 2020 |
| Dell          | Latitude E7450              | Notebook    | [20ee05f0fa](https://linux-hardware.org/?probe=20ee05f0fa) | Nov 27, 2020 |
| Dell          | Latitude E7440              | Notebook    | [9627b61c6f](https://linux-hardware.org/?probe=9627b61c6f) | Nov 25, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e9a83f5dc5](https://linux-hardware.org/?probe=e9a83f5dc5) | Nov 24, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [00a011fa83](https://linux-hardware.org/?probe=00a011fa83) | Nov 22, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [12f4630385](https://linux-hardware.org/?probe=12f4630385) | Nov 22, 2020 |
| Microsoft     | Surface Pro 3               | Tablet      | [eb17673652](https://linux-hardware.org/?probe=eb17673652) | Nov 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [a52f064714](https://linux-hardware.org/?probe=a52f064714) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| HP            | 650                         | Notebook    | [67e06d1514](https://linux-hardware.org/?probe=67e06d1514) | Nov 09, 2020 |
| HP            | Pavilion g6                 | Notebook    | [98124ff6a4](https://linux-hardware.org/?probe=98124ff6a4) | Nov 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [847807840d](https://linux-hardware.org/?probe=847807840d) | Nov 05, 2020 |
| HP            | ProBook 6560b               | Notebook    | [934ffc99e6](https://linux-hardware.org/?probe=934ffc99e6) | Oct 30, 2020 |
| Dell          | 07N90W A01                  | Desktop     | [127c1a4946](https://linux-hardware.org/?probe=127c1a4946) | Oct 29, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [2b138e461a](https://linux-hardware.org/?probe=2b138e461a) | Oct 26, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4460c27fd7](https://linux-hardware.org/?probe=4460c27fd7) | Oct 26, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [b647bae107](https://linux-hardware.org/?probe=b647bae107) | Oct 24, 2020 |
| Apple         | MacBookAir6,2               | Notebook    | [3509d2f6e3](https://linux-hardware.org/?probe=3509d2f6e3) | Oct 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [d7c9922a29](https://linux-hardware.org/?probe=d7c9922a29) | Oct 21, 2020 |
| HP            | ProBook 4340s               | Notebook    | [3db4ff09f4](https://linux-hardware.org/?probe=3db4ff09f4) | Oct 18, 2020 |
| Dell          | Latitude E6540              | Notebook    | [36688dde6e](https://linux-hardware.org/?probe=36688dde6e) | Oct 06, 2020 |
| HP            | 650                         | Notebook    | [1ea9bf783e](https://linux-hardware.org/?probe=1ea9bf783e) | Oct 03, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [94eb24ff74](https://linux-hardware.org/?probe=94eb24ff74) | Oct 02, 2020 |
| Dell          | Latitude E4300              | Notebook    | [12b944fb30](https://linux-hardware.org/?probe=12b944fb30) | Oct 02, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [cb2cef5fcf](https://linux-hardware.org/?probe=cb2cef5fcf) | Oct 01, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [caf12cb57f](https://linux-hardware.org/?probe=caf12cb57f) | Sep 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [d3cc62a7f5](https://linux-hardware.org/?probe=d3cc62a7f5) | Sep 30, 2020 |
| Dell          | Latitude E7450              | Notebook    | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell          | Latitude E7450              | Notebook    | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [974d6d3289](https://linux-hardware.org/?probe=974d6d3289) | Sep 29, 2020 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [b6f7494e44](https://linux-hardware.org/?probe=b6f7494e44) | Sep 21, 2020 |
| HP            | 650                         | Notebook    | [278a9afdeb](https://linux-hardware.org/?probe=278a9afdeb) | Sep 21, 2020 |
| Dell          | Vostro 14-3468              | Notebook    | [4ab76fd5c2](https://linux-hardware.org/?probe=4ab76fd5c2) | Sep 20, 2020 |
| HP            | 650                         | Notebook    | [8aaa8d7e4d](https://linux-hardware.org/?probe=8aaa8d7e4d) | Sep 19, 2020 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [1ec83fe97e](https://linux-hardware.org/?probe=1ec83fe97e) | Sep 17, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [d6204bd9e2](https://linux-hardware.org/?probe=d6204bd9e2) | Sep 16, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP            | ENVY 17                     | Notebook    | [08285409ad](https://linux-hardware.org/?probe=08285409ad) | Sep 13, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [dd76cd9006](https://linux-hardware.org/?probe=dd76cd9006) | Sep 12, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [85d0104e28](https://linux-hardware.org/?probe=85d0104e28) | Sep 10, 2020 |
| Dell          | Inspiron 15-3573            | Notebook    | [9be442a7dd](https://linux-hardware.org/?probe=9be442a7dd) | Sep 07, 2020 |
| HP            | 8433 11                     | Desktop     | [1d000792d8](https://linux-hardware.org/?probe=1d000792d8) | Sep 03, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [1c4d1f875b](https://linux-hardware.org/?probe=1c4d1f875b) | Sep 01, 2020 |
| HP            | ProBook 4340s               | Notebook    | [f7580ed51b](https://linux-hardware.org/?probe=f7580ed51b) | Aug 31, 2020 |
| Dell          | 0D6H9T A01                  | Desktop     | [1f914ddd57](https://linux-hardware.org/?probe=1f914ddd57) | Aug 31, 2020 |
| Dell          | Latitude E7250              | Notebook    | [ff13c002c8](https://linux-hardware.org/?probe=ff13c002c8) | Aug 27, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [f35b20067d](https://linux-hardware.org/?probe=f35b20067d) | Aug 25, 2020 |
| Dell          | 0HY9JP A02                  | Desktop     | [19795140c8](https://linux-hardware.org/?probe=19795140c8) | Aug 22, 2020 |
| Dell          | 0HY9JP A02                  | Desktop     | [b739a3410a](https://linux-hardware.org/?probe=b739a3410a) | Aug 22, 2020 |
| HP            | Laptop 15-da2xxx            | Notebook    | [031606a1a9](https://linux-hardware.org/?probe=031606a1a9) | Aug 21, 2020 |
| Dell          | 0PP150 A00                  | Desktop     | [a990cf0ce7](https://linux-hardware.org/?probe=a990cf0ce7) | Aug 21, 2020 |
| Dell          | Latitude E7250              | Notebook    | [63024e0df6](https://linux-hardware.org/?probe=63024e0df6) | Aug 19, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [8a5fc0bc23](https://linux-hardware.org/?probe=8a5fc0bc23) | Aug 13, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [fa604583d6](https://linux-hardware.org/?probe=fa604583d6) | Aug 10, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [255da50641](https://linux-hardware.org/?probe=255da50641) | Aug 10, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [4053256264](https://linux-hardware.org/?probe=4053256264) | Aug 10, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [930fbc43ed](https://linux-hardware.org/?probe=930fbc43ed) | Aug 09, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [f62759a869](https://linux-hardware.org/?probe=f62759a869) | Aug 05, 2020 |
| Dell          | 0DR845                      | Desktop     | [e4ff6acb83](https://linux-hardware.org/?probe=e4ff6acb83) | Aug 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [4b9fbd7a8f](https://linux-hardware.org/?probe=4b9fbd7a8f) | Aug 01, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4af4cdfef7](https://linux-hardware.org/?probe=4af4cdfef7) | Jul 30, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [4b38ecdae9](https://linux-hardware.org/?probe=4b38ecdae9) | Jul 28, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [9dbea8590b](https://linux-hardware.org/?probe=9dbea8590b) | Jul 19, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [45478d9106](https://linux-hardware.org/?probe=45478d9106) | Jul 18, 2020 |
| HP            | 1589                        | Desktop     | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ce6e9cb36](https://linux-hardware.org/?probe=8ce6e9cb36) | Jul 10, 2020 |
| HP            | ProBook 470 G2              | Notebook    | [c42c686ae8](https://linux-hardware.org/?probe=c42c686ae8) | Jul 09, 2020 |
| MOTION        | NVX00                       | Notebook    | [fd07831802](https://linux-hardware.org/?probe=fd07831802) | Jul 04, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [a12518d58c](https://linux-hardware.org/?probe=a12518d58c) | Jun 30, 2020 |
| Dell          | Latitude E6440              | Notebook    | [a7fe187945](https://linux-hardware.org/?probe=a7fe187945) | Jun 28, 2020 |
| Haier         | Y11C                        | Notebook    | [6b98c2c449](https://linux-hardware.org/?probe=6b98c2c449) | Jun 23, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [4e6a9e5117](https://linux-hardware.org/?probe=4e6a9e5117) | Jun 12, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [8c8ed3d489](https://linux-hardware.org/?probe=8c8ed3d489) | Jun 06, 2020 |
| Haier         | Y11C                        | Notebook    | [7f9f93809f](https://linux-hardware.org/?probe=7f9f93809f) | Jun 01, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [f74cf1545a](https://linux-hardware.org/?probe=f74cf1545a) | May 21, 2020 |
| Dell          | Latitude E6410              | Notebook    | [60757c8504](https://linux-hardware.org/?probe=60757c8504) | May 21, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [86a1d31e5c](https://linux-hardware.org/?probe=86a1d31e5c) | May 21, 2020 |
| Dell          | Latitude E7450              | Notebook    | [1031b89b4b](https://linux-hardware.org/?probe=1031b89b4b) | May 12, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [34b0697bf6](https://linux-hardware.org/?probe=34b0697bf6) | May 10, 2020 |
| Dell          | Latitude E6320              | Notebook    | [cedc2c5001](https://linux-hardware.org/?probe=cedc2c5001) | May 10, 2020 |
| Dell          | 0GU083 A00                  | Desktop     | [a31c9c5f4f](https://linux-hardware.org/?probe=a31c9c5f4f) | May 05, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e3400fb2b7](https://linux-hardware.org/?probe=e3400fb2b7) | May 04, 2020 |
| Dell          | 0PP150 A00                  | Desktop     | [51f69f1430](https://linux-hardware.org/?probe=51f69f1430) | May 02, 2020 |
| Lenovo        | ThinkCentre M57 6072W2A     | Desktop     | [d42ad893b6](https://linux-hardware.org/?probe=d42ad893b6) | May 01, 2020 |
| Lenovo        | ThinkCentre M57 6072W2A     | Desktop     | [366d3d0483](https://linux-hardware.org/?probe=366d3d0483) | May 01, 2020 |
| Dell          | 0PP150 A00                  | Desktop     | [f224ee60e5](https://linux-hardware.org/?probe=f224ee60e5) | Apr 30, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [581af37cda](https://linux-hardware.org/?probe=581af37cda) | Apr 19, 2020 |
| Dell          | Latitude E5420              | Notebook    | [6d2ddeb934](https://linux-hardware.org/?probe=6d2ddeb934) | Apr 18, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [ea52c08646](https://linux-hardware.org/?probe=ea52c08646) | Apr 09, 2020 |
| Dell          | Latitude E4300              | Notebook    | [5e38d54ea2](https://linux-hardware.org/?probe=5e38d54ea2) | Mar 18, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [9434f7214c](https://linux-hardware.org/?probe=9434f7214c) | Mar 16, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [4a53b5e634](https://linux-hardware.org/?probe=4a53b5e634) | Mar 11, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [3cd2a73254](https://linux-hardware.org/?probe=3cd2a73254) | Mar 09, 2020 |
| Dell          | 054KM3 A01                  | Desktop     | [857f976c7f](https://linux-hardware.org/?probe=857f976c7f) | Jan 29, 2020 |
| HP            | 1497                        | Desktop     | [fe24ec7591](https://linux-hardware.org/?probe=fe24ec7591) | Jan 28, 2020 |
| HP            | Pavilion dv7                | Notebook    | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| Dell          | 054KM3 A01                  | Desktop     | [f682ad8814](https://linux-hardware.org/?probe=f682ad8814) | Jan 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [e257c71d0b](https://linux-hardware.org/?probe=e257c71d0b) | Jan 14, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [f73167982a](https://linux-hardware.org/?probe=f73167982a) | Jan 01, 2020 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [e921d3af77](https://linux-hardware.org/?probe=e921d3af77) | Dec 13, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| Dell          | Latitude XT3                | Notebook    | [4ccaa2e0e2](https://linux-hardware.org/?probe=4ccaa2e0e2) | Oct 29, 2019 |
| Lenovo        | ThinkPad T440 20B7S1NK05    | Notebook    | [310405c604](https://linux-hardware.org/?probe=310405c604) | Oct 29, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [856fcded98](https://linux-hardware.org/?probe=856fcded98) | Oct 25, 2019 |
| HP            | Unknown                     | Notebook    | [25dd8af3ee](https://linux-hardware.org/?probe=25dd8af3ee) | Oct 22, 2019 |
| ASUSTek       | Q87M-E                      | Desktop     | [01f990ea56](https://linux-hardware.org/?probe=01f990ea56) | Oct 19, 2019 |
| Lenovo        | ThinkPad 10 20C3001QAU      | Tablet      | [b1cb7238da](https://linux-hardware.org/?probe=b1cb7238da) | Oct 04, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [43c8f2b72c](https://linux-hardware.org/?probe=43c8f2b72c) | Sep 13, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [964e933faf](https://linux-hardware.org/?probe=964e933faf) | Sep 13, 2019 |
| Samsung       | 940Z5L                      | Notebook    | [28c94787df](https://linux-hardware.org/?probe=28c94787df) | Sep 13, 2019 |
| AMI           | Unknown                     | Notebook    | [407590d103](https://linux-hardware.org/?probe=407590d103) | Sep 09, 2019 |
| HP            | ProBook 6470b               | Notebook    | [81e17acdb1](https://linux-hardware.org/?probe=81e17acdb1) | Aug 02, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [b419735d70](https://linux-hardware.org/?probe=b419735d70) | Jul 04, 2019 |
| Sony          | VPCCB490X                   | Notebook    | [ed39416136](https://linux-hardware.org/?probe=ed39416136) | Jun 22, 2019 |
| Haier         | Y11C                        | Notebook    | [ab6b2cf0e5](https://linux-hardware.org/?probe=ab6b2cf0e5) | Jun 20, 2019 |
| Haier         | Y11C                        | Notebook    | [74a3547ed6](https://linux-hardware.org/?probe=74a3547ed6) | Jun 20, 2019 |
| HP            | 304Ah                       | Desktop     | [4f72bfd1f5](https://linux-hardware.org/?probe=4f72bfd1f5) | May 13, 2019 |
| Dell          | Latitude E6420              | Notebook    | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell          | Latitude E6420              | Notebook    | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Haier         | Y11B                        | Notebook    | [d90f70d18f](https://linux-hardware.org/?probe=d90f70d18f) | May 11, 2019 |
| Dell          | 054KM3 A01                  | Desktop     | [144815a4e9](https://linux-hardware.org/?probe=144815a4e9) | Jan 15, 2019 |
| Dell          | 054KM3 A01                  | Desktop     | [f83bcddf2e](https://linux-hardware.org/?probe=f83bcddf2e) | Jan 08, 2019 |
| Dell          | 054KM3 A01                  | Desktop     | [404e699144](https://linux-hardware.org/?probe=404e699144) | Jan 08, 2019 |
| Haier         | Y11B                        | Notebook    | [e359a25a69](https://linux-hardware.org/?probe=e359a25a69) | Nov 18, 2018 |
| Haier         | Y11B                        | Notebook    | [13e5308d20](https://linux-hardware.org/?probe=13e5308d20) | Nov 18, 2018 |
| HP            | Pavilion Notebook           | Notebook    | [7e2949f7da](https://linux-hardware.org/?probe=7e2949f7da) | Nov 11, 2018 |
| Acer          | Aspire 5733                 | Notebook    | [970a40e3d0](https://linux-hardware.org/?probe=970a40e3d0) | Oct 23, 2018 |
| ASUSTek       | K53U                        | Notebook    | [f644624e98](https://linux-hardware.org/?probe=f644624e98) | Oct 01, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Pakistan/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 87        | 19.73%  |
| Ubuntu 22.04       | 55        | 12.47%  |
| Ubuntu 18.04       | 25        | 5.67%   |
| Debian 11          | 12        | 2.72%   |
| Ubuntu 23.04       | 10        | 2.27%   |
| Pop!_OS 22.04      | 9         | 2.04%   |
| Zorin 16           | 8         | 1.81%   |
| Arch               | 8         | 1.81%   |
| OpenMandriva 4.3   | 7         | 1.59%   |
| KDE neon 20.04     | 7         | 1.59%   |
| Ubuntu 22.10       | 6         | 1.36%   |
| Ubuntu 21.04       | 6         | 1.36%   |
| Kali 2023.3        | 6         | 1.36%   |
| Debian 10          | 6         | 1.36%   |
| ArcoLinux Rolling  | 6         | 1.36%   |
| Zorin 15           | 5         | 1.13%   |
| Ubuntu 23.10       | 5         | 1.13%   |
| Pop!_OS 20.04      | 5         | 1.13%   |
| Fedora 38          | 5         | 1.13%   |
| Xero Rolling       | 4         | 0.91%   |
| Ubuntu 19.04       | 4         | 0.91%   |
| Pop!_OS 21.04      | 4         | 0.91%   |
| OpenMandriva 4.2   | 4         | 0.91%   |
| Linux Mint 21.2    | 4         | 0.91%   |
| Linux Mint 21.1    | 4         | 0.91%   |
| Linux Mint 20      | 4         | 0.91%   |
| Kali 2023.2        | 4         | 0.91%   |
| Fedora 36          | 4         | 0.91%   |
| Elementary 6.1     | 4         | 0.91%   |
| Xubuntu 22.04      | 3         | 0.68%   |
| Ubuntu 21.10       | 3         | 0.68%   |
| Pop!_OS 20.10      | 3         | 0.68%   |
| OpenMandriva 23.01 | 3         | 0.68%   |
| Manjaro            | 3         | 0.68%   |
| Lubuntu 22.04      | 3         | 0.68%   |
| Linux Mint 20.3    | 3         | 0.68%   |
| Linux Mint 20.2    | 3         | 0.68%   |
| Kubuntu 22.04      | 3         | 0.68%   |
| Kubuntu 20.04      | 3         | 0.68%   |
| Fedora 39          | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 203       | 47.54%  |
| Fedora        | 23        | 5.39%   |
| Linux Mint    | 22        | 5.15%   |
| Pop!_OS       | 20        | 4.68%   |
| Kali          | 17        | 3.98%   |
| Zorin         | 16        | 3.75%   |
| Debian        | 16        | 3.75%   |
| OpenMandriva  | 15        | 3.51%   |
| Arch          | 11        | 2.58%   |
| Kubuntu       | 10        | 2.34%   |
| KDE neon      | 9         | 2.11%   |
| ArcoLinux     | 7         | 1.64%   |
| Manjaro       | 6         | 1.41%   |
| Elementary    | 5         | 1.17%   |
| Xero          | 4         | 0.94%   |
| Xubuntu       | 3         | 0.7%    |
| Ubuntu Unity  | 3         | 0.7%    |
| Parrot        | 3         | 0.7%    |
| Nobara        | 3         | 0.7%    |
| Lubuntu       | 3         | 0.7%    |
| Garuda Linux  | 3         | 0.7%    |
| Endless       | 3         | 0.7%    |
| ROSA          | 2         | 0.47%   |
| CentOS        | 2         | 0.47%   |
| Artix         | 2         | 0.47%   |
| Ubuntu MATE   | 1         | 0.23%   |
| Ubuntu Budgie | 1         | 0.23%   |
| Rocky Linux   | 1         | 0.23%   |
| RHEL          | 1         | 0.23%   |
| PureOS        | 1         | 0.23%   |
| Oracle Linux  | 1         | 0.23%   |
| openSUSE      | 1         | 0.23%   |
| LMDE          | 1         | 0.23%   |
| LinuxFX       | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| EndeavourOS   | 1         | 0.23%   |
| Deepin        | 1         | 0.23%   |
| Clear Linux   | 1         | 0.23%   |
| BlackPanther  | 1         | 0.23%   |
| Alpine        | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 10        | 2.1%    |
| 5.15.0-46-generic        | 8         | 1.68%   |
| 5.16.7-desktop-1omv4003  | 7         | 1.47%   |
| 5.19.0-42-generic        | 6         | 1.26%   |
| 5.11.0-37-generic        | 6         | 1.26%   |
| 5.4.106-1-pve            | 5         | 1.05%   |
| 5.15.0-47-generic        | 5         | 1.05%   |
| 6.3.0-kali1-amd64        | 4         | 0.84%   |
| 6.2.0-34-generic         | 4         | 0.84%   |
| 6.2.0-32-generic         | 4         | 0.84%   |
| 5.8.0-59-generic         | 4         | 0.84%   |
| 5.4.0-54-generic         | 4         | 0.84%   |
| 5.4.0-52-generic         | 4         | 0.84%   |
| 5.4.0-48-generic         | 4         | 0.84%   |
| 5.4.0-47-generic         | 4         | 0.84%   |
| 5.4.0-40-generic         | 4         | 0.84%   |
| 5.4.0-26-generic         | 4         | 0.84%   |
| 5.19.0-46-generic        | 4         | 0.84%   |
| 5.15.0-58-generic        | 4         | 0.84%   |
| 5.15.0-56-generic        | 4         | 0.84%   |
| 5.11.0-43-generic        | 4         | 0.84%   |
| 5.11.0-27-generic        | 4         | 0.84%   |
| 5.10.14-desktop-1omv4002 | 4         | 0.84%   |
| 6.5.0-28-generic         | 3         | 0.63%   |
| 6.5.0-14-generic         | 3         | 0.63%   |
| 6.2.0-39-generic         | 3         | 0.63%   |
| 6.2.0-35-generic         | 3         | 0.63%   |
| 6.2.0-31-generic         | 3         | 0.63%   |
| 6.2.0-26-generic         | 3         | 0.63%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.63%   |
| 5.8.0-7630-generic       | 3         | 0.63%   |
| 5.8.0-44-generic         | 3         | 0.63%   |
| 5.8.0-41-generic         | 3         | 0.63%   |
| 5.4.0-7642-generic       | 3         | 0.63%   |
| 5.4.0-58-generic         | 3         | 0.63%   |
| 5.3.0-28-generic         | 3         | 0.63%   |
| 5.19.0-43-generic        | 3         | 0.63%   |
| 5.19.0-41-generic        | 3         | 0.63%   |
| 5.15.0-79-generic        | 3         | 0.63%   |
| 5.15.0-76-generic        | 3         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 14.16%  |
| 5.15.0  | 56        | 12.39%  |
| 5.19.0  | 32        | 7.08%   |
| 5.11.0  | 31        | 6.86%   |
| 6.2.0   | 24        | 5.31%   |
| 5.8.0   | 23        | 5.09%   |
| 6.5.0   | 20        | 4.42%   |
| 5.13.0  | 19        | 4.2%    |
| 4.15.0  | 16        | 3.54%   |
| 5.0.0   | 11        | 2.43%   |
| 5.10.0  | 8         | 1.77%   |
| 5.3.0   | 7         | 1.55%   |
| 5.16.7  | 7         | 1.55%   |
| 5.4.106 | 5         | 1.11%   |
| 4.18.0  | 5         | 1.11%   |
| 6.3.0   | 4         | 0.88%   |
| 6.1.1   | 4         | 0.88%   |
| 5.11.22 | 4         | 0.88%   |
| 5.10.14 | 4         | 0.88%   |
| 6.2.6   | 3         | 0.66%   |
| 6.1.0   | 3         | 0.66%   |
| 6.0.8   | 3         | 0.66%   |
| 6.7.9   | 2         | 0.44%   |
| 6.5.5   | 2         | 0.44%   |
| 6.4.0   | 2         | 0.44%   |
| 6.0.12  | 2         | 0.44%   |
| 5.9.8   | 2         | 0.44%   |
| 5.7.0   | 2         | 0.44%   |
| 5.19.9  | 2         | 0.44%   |
| 5.19.13 | 2         | 0.44%   |
| 5.18.0  | 2         | 0.44%   |
| 5.16.15 | 2         | 0.44%   |
| 5.13.4  | 2         | 0.44%   |
| 5.13.19 | 2         | 0.44%   |
| 3.10.0  | 2         | 0.44%   |
| 6.8.1   | 1         | 0.22%   |
| 6.8.0   | 1         | 0.22%   |
| 6.7.6   | 1         | 0.22%   |
| 6.7.5   | 1         | 0.22%   |
| 6.6.7   | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 16.48%  |
| 5.15    | 59        | 13.14%  |
| 5.19    | 37        | 8.24%   |
| 5.11    | 35        | 7.8%    |
| 6.2     | 30        | 6.68%   |
| 6.5     | 27        | 6.01%   |
| 5.13    | 27        | 6.01%   |
| 5.8     | 24        | 5.35%   |
| 4.15    | 16        | 3.56%   |
| 5.10    | 15        | 3.34%   |
| 6.1     | 11        | 2.45%   |
| 5.0     | 11        | 2.45%   |
| 5.16    | 10        | 2.23%   |
| 6.0     | 8         | 1.78%   |
| 5.3     | 8         | 1.78%   |
| 6.6     | 6         | 1.34%   |
| 6.3     | 6         | 1.34%   |
| 4.18    | 6         | 1.34%   |
| 6.4     | 5         | 1.11%   |
| 5.7     | 5         | 1.11%   |
| 5.18    | 5         | 1.11%   |
| 6.7     | 4         | 0.89%   |
| 5.9     | 3         | 0.67%   |
| 5.17    | 3         | 0.67%   |
| 5.14    | 3         | 0.67%   |
| 3.10    | 3         | 0.67%   |
| 6.8     | 2         | 0.45%   |
| 5.12    | 2         | 0.45%   |
| 5.6     | 1         | 0.22%   |
| 5.2     | 1         | 0.22%   |
| 4.9     | 1         | 0.22%   |
| 4.19    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 409       | 98.79%  |
| i686   | 5         | 1.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 269       | 62.56%  |
| KDE5       | 43        | 10%     |
| Unknown    | 37        | 8.6%    |
| XFCE       | 22        | 5.12%   |
| X-Cinnamon | 19        | 4.42%   |
| KDE        | 8         | 1.86%   |
| MATE       | 7         | 1.63%   |
| Pantheon   | 5         | 1.16%   |
| i3         | 4         | 0.93%   |
| Unity      | 3         | 0.7%    |
| LXQt       | 3         | 0.7%    |
| KDE4       | 3         | 0.7%    |
| KDE6       | 2         | 0.47%   |
| Hyprland   | 2         | 0.47%   |
| LXDE       | 1         | 0.23%   |
| Deepin     | 1         | 0.23%   |
| Budgie     | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 288       | 67.76%  |
| Wayland | 102       | 24%     |
| Unknown | 26        | 6.12%   |
| Tty     | 9         | 2.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 44.76%  |
| GDM3    | 106       | 24.71%  |
| GDM     | 54        | 12.59%  |
| SDDM    | 45        | 10.49%  |
| LightDM | 24        | 5.59%   |
| TDM     | 5         | 1.17%   |
| XDM     | 1         | 0.23%   |
| LXDM    | 1         | 0.23%   |
| KDM     | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 360       | 85.71%  |
| Unknown | 23        | 5.48%   |
| en_GB   | 21        | 5%      |
| C       | 6         | 1.43%   |
| en_PK   | 3         | 0.71%   |
| ur_PK   | 2         | 0.48%   |
| en_IN   | 2         | 0.48%   |
| en_ZA   | 1         | 0.24%   |
| en_CA   | 1         | 0.24%   |
| en_AG   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 219       | 51.41%  |
| EFI  | 207       | 48.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 330       | 77.46%  |
| Tmpfs    | 29        | 6.81%   |
| Btrfs    | 29        | 6.81%   |
| Overlay  | 17        | 3.99%   |
| Xfs      | 8         | 1.88%   |
| Zfs      | 7         | 1.64%   |
| Unknown  | 5         | 1.17%   |
| Reiserfs | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 210       | 49.65%  |
| GPT     | 175       | 41.37%  |
| MBR     | 38        | 8.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 369       | 87.86%  |
| Yes       | 51        | 12.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 270       | 63.83%  |
| Yes       | 153       | 36.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 142       | 34.3%   |
| Dell                | 118       | 28.5%   |
| Lenovo              | 66        | 15.94%  |
| Gigabyte Technology | 15        | 3.62%   |
| ASUSTek Computer    | 15        | 3.62%   |
| Acer                | 9         | 2.17%   |
| Haier               | 8         | 1.93%   |
| Apple               | 7         | 1.69%   |
| Toshiba             | 5         | 1.21%   |
| Sony                | 3         | 0.72%   |
| Samsung Electronics | 3         | 0.72%   |
| Shuttle             | 2         | 0.48%   |
| Intel               | 2         | 0.48%   |
| Fujitsu             | 2         | 0.48%   |
| Unknown             | 2         | 0.48%   |
| Timi                | 1         | 0.24%   |
| Quanta              | 1         | 0.24%   |
| MSI                 | 1         | 0.24%   |
| MOTION              | 1         | 0.24%   |
| Microsoft           | 1         | 0.24%   |
| KEIAN               | 1         | 0.24%   |
| Inventec            | 1         | 0.24%   |
| Google              | 1         | 0.24%   |
| Gateway             | 1         | 0.24%   |
| Colorful Technology | 1         | 0.24%   |
| Clevo               | 1         | 0.24%   |
| Biostar             | 1         | 0.24%   |
| AMI                 | 1         | 0.24%   |
| Alienware           | 1         | 0.24%   |
| AAEON               | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 6         | 1.45%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 5         | 1.21%   |
| HP ProBook 450 G7                    | 5         | 1.21%   |
| HP EliteBook 8470p                   | 5         | 1.21%   |
| HP EliteBook 840 G3                  | 5         | 1.21%   |
| Haier Y11C                           | 5         | 1.21%   |
| Dell Latitude E7450                  | 5         | 1.21%   |
| Dell Precision WorkStation T7500     | 4         | 0.97%   |
| Dell Latitude E6420                  | 4         | 0.97%   |
| HP ProLiant DL380p Gen8              | 3         | 0.72%   |
| HP ProBook 450 G5                    | 3         | 0.72%   |
| HP Laptop 15s-fq5xxx                 | 3         | 0.72%   |
| HP EliteBook 840 G2                  | 3         | 0.72%   |
| Haier Y11B                           | 3         | 0.72%   |
| Dell Precision WorkStation T3500     | 3         | 0.72%   |
| Shuttle DS81D                        | 2         | 0.48%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GF00 | 2         | 0.48%   |
| Lenovo ThinkPad E15 Gen 2 20TD000EUE | 2         | 0.48%   |
| Lenovo ThinkBook 15-IML 20RW         | 2         | 0.48%   |
| Lenovo ThinkBook 15-IIL 20SM         | 2         | 0.48%   |
| HP ZBook 15 G3                       | 2         | 0.48%   |
| HP ProDesk 600 G1 SFF                | 2         | 0.48%   |
| HP ProDesk 400 G7 Microtower PC      | 2         | 0.48%   |
| HP ProBook 450 G8 Notebook PC        | 2         | 0.48%   |
| HP ProBook 450 G3                    | 2         | 0.48%   |
| HP ProBook 440 G7                    | 2         | 0.48%   |
| HP Pavilion Notebook                 | 2         | 0.48%   |
| HP Pavilion g6                       | 2         | 0.48%   |
| HP Pavilion dv6                      | 2         | 0.48%   |
| HP Notebook                          | 2         | 0.48%   |
| HP Laptop 15-da2xxx                  | 2         | 0.48%   |
| HP ENVY x360 m6 Convertible          | 2         | 0.48%   |
| HP EliteBook Folio 9470m             | 2         | 0.48%   |
| HP EliteBook 850 G6                  | 2         | 0.48%   |
| HP EliteBook 8440p                   | 2         | 0.48%   |
| HP EliteBook 840 G1                  | 2         | 0.48%   |
| HP EliteBook 6930p                   | 2         | 0.48%   |
| HP EliteBook 2540p                   | 2         | 0.48%   |
| HP Compaq 8100 Elite SFF PC          | 2         | 0.48%   |
| HP 650                               | 2         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 49        | 11.84%  |
| HP EliteBook       | 36        | 8.7%    |
| Lenovo ThinkPad    | 31        | 7.49%   |
| HP ProBook         | 28        | 6.76%   |
| Dell Inspiron      | 28        | 6.76%   |
| HP Pavilion        | 16        | 3.86%   |
| Dell Precision     | 14        | 3.38%   |
| HP Laptop          | 12        | 2.9%    |
| HP Compaq          | 12        | 2.9%    |
| Dell OptiPlex      | 12        | 2.9%    |
| Lenovo ThinkBook   | 9         | 2.17%   |
| Dell Vostro        | 8         | 1.93%   |
| Lenovo ThinkCentre | 7         | 1.69%   |
| Lenovo IdeaPad     | 7         | 1.69%   |
| HP ProDesk         | 7         | 1.69%   |
| HP ENVY            | 7         | 1.69%   |
| Unknown            | 6         | 1.45%   |
| Haier Y11C         | 5         | 1.21%   |
| HP ProLiant        | 4         | 0.97%   |
| Dell XPS           | 4         | 0.97%   |
| Acer Aspire        | 4         | 0.97%   |
| Toshiba Satellite  | 3         | 0.72%   |
| HP ZBook           | 3         | 0.72%   |
| Haier Y11B         | 3         | 0.72%   |
| ASUS VivoBook      | 3         | 0.72%   |
| Toshiba PORTEGE    | 2         | 0.48%   |
| Shuttle DS81D      | 2         | 0.48%   |
| Lenovo Yoga        | 2         | 0.48%   |
| Lenovo Legion      | 2         | 0.48%   |
| HP Notebook        | 2         | 0.48%   |
| HP 650             | 2         | 0.48%   |
| Gigabyte Z590      | 2         | 0.48%   |
| Gigabyte Q87M-D2H  | 2         | 0.48%   |
| Gigabyte B250M-D3H | 2         | 0.48%   |
| Gigabyte A520M     | 2         | 0.48%   |
| Fujitsu LIFEBOOK   | 2         | 0.48%   |
| Dell G3            | 2         | 0.48%   |
| ASUS TUF           | 2         | 0.48%   |
| Apple MacBookPro11 | 2         | 0.48%   |
| Acer Veriton       | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 40        | 9.66%   |
| 2011    | 40        | 9.66%   |
| 2019    | 38        | 9.18%   |
| 2014    | 37        | 8.94%   |
| 2013    | 34        | 8.21%   |
| 2012    | 34        | 8.21%   |
| 2016    | 27        | 6.52%   |
| 2017    | 26        | 6.28%   |
| 2010    | 25        | 6.04%   |
| 2018    | 24        | 5.8%    |
| 2021    | 23        | 5.56%   |
| 2015    | 20        | 4.83%   |
| 2009    | 14        | 3.38%   |
| 2008    | 12        | 2.9%    |
| 2022    | 7         | 1.69%   |
| 2007    | 5         | 1.21%   |
| 2006    | 4         | 0.97%   |
| 2023    | 3         | 0.72%   |
| Unknown | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 293       | 70.77%  |
| Desktop     | 98        | 23.67%  |
| Convertible | 14        | 3.38%   |
| Server      | 4         | 0.97%   |
| Tablet      | 3         | 0.72%   |
| Mini pc     | 2         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 384       | 92.31%  |
| Enabled  | 32        | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 413       | 99.76%  |
| Yes  | 1         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 123       | 29.43%  |
| 16.01-24.0      | 90        | 21.53%  |
| 8.01-16.0       | 84        | 20.1%   |
| 3.01-4.0        | 74        | 17.7%   |
| 32.01-64.0      | 27        | 6.46%   |
| 1.01-2.0        | 8         | 1.91%   |
| 64.01-256.0     | 7         | 1.67%   |
| 24.01-32.0      | 4         | 0.96%   |
| More than 256.0 | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 143       | 31.09%  |
| 1.01-2.0    | 134       | 29.13%  |
| 4.01-8.0    | 76        | 16.52%  |
| 3.01-4.0    | 69        | 15%     |
| 8.01-16.0   | 24        | 5.22%   |
| 0.51-1.0    | 8         | 1.74%   |
| 16.01-24.0  | 3         | 0.65%   |
| 32.01-64.0  | 1         | 0.22%   |
| 64.01-256.0 | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 275       | 64.4%   |
| 2      | 113       | 26.46%  |
| 3      | 19        | 4.45%   |
| 6      | 5         | 1.17%   |
| 5      | 4         | 0.94%   |
| 4      | 4         | 0.94%   |
| 0      | 2         | 0.47%   |
| 13     | 1         | 0.23%   |
| 11     | 1         | 0.23%   |
| 10     | 1         | 0.23%   |
| 9      | 1         | 0.23%   |
| 8      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 292       | 70.36%  |
| Yes       | 123       | 29.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 364       | 87.71%  |
| No        | 51        | 12.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 365       | 87.74%  |
| No        | 51        | 12.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 273       | 64.24%  |
| No        | 152       | 35.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Pakistan | 414       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Lahore         | 130       | 30.59%  |
| Karachi        | 100       | 23.53%  |
| Islamabad      | 61        | 14.35%  |
| Rawalpindi     | 32        | 7.53%   |
| Multan         | 13        | 3.06%   |
| Faisalabad     | 10        | 2.35%   |
| Peshawar       | 8         | 1.88%   |
| Mirpur         | 7         | 1.65%   |
| Sargodha       | 5         | 1.18%   |
| Gujranwala     | 4         | 0.94%   |
| Bahawalpur     | 4         | 0.94%   |
| Sialkot        | 3         | 0.71%   |
| Jhelum         | 3         | 0.71%   |
| Abbottabad     | 3         | 0.71%   |
| Quetta         | 2         | 0.47%   |
| Mardan         | 2         | 0.47%   |
| Kamoke         | 2         | 0.47%   |
| Hyderabad      | 2         | 0.47%   |
| Dina           | 2         | 0.47%   |
| Wah            | 1         | 0.24%   |
| Vehari         | 1         | 0.24%   |
| Topi           | 1         | 0.24%   |
| Toba Tek Singh | 1         | 0.24%   |
| Taunsa         | 1         | 0.24%   |
| Tando Allahyar | 1         | 0.24%   |
| Swabi          | 1         | 0.24%   |
| Sukkur         | 1         | 0.24%   |
| Sheikhupura    | 1         | 0.24%   |
| Sahiwal        | 1         | 0.24%   |
| Rahim Yar Khan | 1         | 0.24%   |
| Pindi Gheb     | 1         | 0.24%   |
| Okara          | 1         | 0.24%   |
| Muzaffarabad   | 1         | 0.24%   |
| Muridke        | 1         | 0.24%   |
| Layyah         | 1         | 0.24%   |
| Layari         | 1         | 0.24%   |
| Larkana        | 1         | 0.24%   |
| Kohat          | 1         | 0.24%   |
| Khanewal       | 1         | 0.24%   |
| Kaleke Mandi   | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 93        | 144    | 15.76%  |
| WDC                          | 80        | 114    | 13.56%  |
| Samsung Electronics          | 73        | 90     | 12.37%  |
| Toshiba                      | 45        | 48     | 7.63%   |
| Hitachi                      | 29        | 39     | 4.92%   |
| Kingston                     | 20        | 23     | 3.39%   |
| Intel                        | 20        | 27     | 3.39%   |
| Unknown                      | 19        | 25     | 3.22%   |
| SanDisk                      | 18        | 20     | 3.05%   |
| SK hynix                     | 16        | 21     | 2.71%   |
| Micron Technology            | 15        | 20     | 2.54%   |
| Hewlett-Packard              | 13        | 27     | 2.2%    |
| Transcend                    | 11        | 11     | 1.86%   |
| HGST                         | 11        | 13     | 1.86%   |
| Lexar                        | 10        | 14     | 1.69%   |
| HS-SSD-E100                  | 10        | 12     | 1.69%   |
| LITEON                       | 9         | 11     | 1.53%   |
| A-DATA Technology            | 9         | 10     | 1.53%   |
| KIOXIA                       | 8         | 8      | 1.36%   |
| Silicon Motion               | 7         | 7      | 1.19%   |
| LITEONIT                     | 7         | 10     | 1.19%   |
| Hajaan                       | 6         | 9      | 1.02%   |
| Crucial                      | 6         | 7      | 1.02%   |
| China                        | 6         | 8      | 1.02%   |
| Apple                        | 5         | 6      | 0.85%   |
| SPCC                         | 3         | 3      | 0.51%   |
| Maxtor                       | 3         | 3      | 0.51%   |
| LaCie                        | 3         | 3      | 0.51%   |
| Team                         | 2         | 2      | 0.34%   |
| Phison Electronics           | 2         | 2      | 0.34%   |
| Netac                        | 2         | 2      | 0.34%   |
| Gigabyte Technology          | 2         | 3      | 0.34%   |
| Fujitsu                      | 2         | 2      | 0.34%   |
| ZTE                          | 1         | 1      | 0.17%   |
| Vaseky                       | 1         | 1      | 0.17%   |
| Toshiba America Info Systems | 1         | 1      | 0.17%   |
| Supersonic                   | 1         | 1      | 0.17%   |
| SSSTC                        | 1         | 1      | 0.17%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.17%   |
| Realtek Semiconductor        | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 10        | 1.56%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 1.09%   |
| Seagate ST3000NXCLAR3000 3TB                      | 7         | 1.09%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 6         | 0.94%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 0.94%   |
| HP MB2000EBZQC 2TB                                | 6         | 0.94%   |
| Hajaan SSD 256G                                   | 6         | 0.94%   |
| Unknown MMC Card  32GB                            | 5         | 0.78%   |
| Seagate ST9250311CS 250GB                         | 5         | 0.78%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 0.78%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 5         | 0.78%   |
| Samsung MZALQ512HALU-000L1 512GB                  | 5         | 0.78%   |
| Lexar 256GB SSD                                   | 5         | 0.78%   |
| WDC WD10SPZX-75Z10T3 1TB                          | 4         | 0.62%   |
| Seagate ST500DM002-1BD142 500GB                   | 4         | 0.62%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD             | 4         | 0.62%   |
| HS-SSD-E100 128G                                  | 4         | 0.62%   |
| Hitachi HTS545050A7E380 500GB                     | 4         | 0.62%   |
| HP LOGICAL VOLUME 160GB                           | 4         | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 3         | 0.47%   |
| WDC WD5000LPVX-75V0TT0 500GB                      | 3         | 0.47%   |
| WDC PC SN530 NVMe 256GB                           | 3         | 0.47%   |
| Toshiba MQ01ACF050 500GB                          | 3         | 0.47%   |
| Silicon Motion NVMe SSD Drive 512GB               | 3         | 0.47%   |
| Seagate ST8000DM004-2CX188 8TB                    | 3         | 0.47%   |
| Seagate ST6000NM0024 6TB                          | 3         | 0.47%   |
| Seagate ST500LM000-1EJ162 500GB                   | 3         | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB | 3         | 0.47%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD              | 3         | 0.47%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB SSD             | 3         | 0.47%   |
| LITEON CS1-SP32 32GB SSD                          | 3         | 0.47%   |
| LaCie Rugged USB-C 5TB                            | 3         | 0.47%   |
| Intel SSDSA2M080G2GN 80GB                         | 3         | 0.47%   |
| Intel H10 HBRPEKNX0202AO NVMe 32GB                | 3         | 0.47%   |
| Intel H10 HBRPEKNX0202A NVMe 512GB                | 3         | 0.47%   |
| HS-SSD-E100 256G                                  | 3         | 0.47%   |
| Hitachi HTS545032B9A300 320GB                     | 3         | 0.47%   |
| Hitachi HTS543225A7A384 250GB                     | 3         | 0.47%   |
| WDC WD5002ABYS-02B1B0 500GB                       | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 144    | 35.23%  |
| WDC                 | 67        | 93     | 25.38%  |
| Toshiba             | 38        | 41     | 14.39%  |
| Hitachi             | 29        | 39     | 10.98%  |
| HGST                | 11        | 13     | 4.17%   |
| Hewlett-Packard     | 11        | 24     | 4.17%   |
| Samsung Electronics | 7         | 8      | 2.65%   |
| Maxtor              | 3         | 3      | 1.14%   |
| Fujitsu             | 2         | 2      | 0.76%   |
| Unknown             | 1         | 1      | 0.38%   |
| MARSHAL             | 1         | 1      | 0.38%   |
| KESU                | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 46     | 22.4%   |
| Kingston            | 15        | 18     | 8.2%    |
| SanDisk             | 12        | 12     | 6.56%   |
| WDC                 | 9         | 12     | 4.92%   |
| SK hynix            | 9         | 14     | 4.92%   |
| Micron Technology   | 9         | 11     | 4.92%   |
| LITEON              | 9         | 11     | 4.92%   |
| Lexar               | 8         | 11     | 4.37%   |
| LITEONIT            | 7         | 10     | 3.83%   |
| Intel               | 7         | 8      | 3.83%   |
| A-DATA Technology   | 7         | 8      | 3.83%   |
| Transcend           | 6         | 6      | 3.28%   |
| Hajaan              | 6         | 9      | 3.28%   |
| Crucial             | 6         | 7      | 3.28%   |
| China               | 6         | 8      | 3.28%   |
| Toshiba             | 4         | 4      | 2.19%   |
| SPCC                | 3         | 3      | 1.64%   |
| HS-SSD-E100         | 3         | 3      | 1.64%   |
| Team                | 2         | 2      | 1.09%   |
| Hewlett-Packard     | 2         | 3      | 1.09%   |
| Apple               | 2         | 2      | 1.09%   |
| Vaseky              | 1         | 1      | 0.55%   |
| Supersonic          | 1         | 1      | 0.55%   |
| PNY                 | 1         | 2      | 0.55%   |
| PHD 3.0             | 1         | 1      | 0.55%   |
| Netac               | 1         | 1      | 0.55%   |
| Gritronix           | 1         | 1      | 0.55%   |
| Gigabyte Technology | 1         | 2      | 0.55%   |
| Emtec               | 1         | 1      | 0.55%   |
| Biostar             | 1         | 1      | 0.55%   |
| Apacer              | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 221       | 370    | 42.34%  |
| SSD     | 156       | 220    | 29.89%  |
| NVMe    | 109       | 137    | 20.88%  |
| Unknown | 21        | 27     | 4.02%   |
| MMC     | 15        | 21     | 2.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 318       | 577    | 68.53%  |
| NVMe | 109       | 137    | 23.49%  |
| SAS  | 22        | 40     | 4.74%   |
| MMC  | 15        | 21     | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 247       | 386    | 65.34%  |
| 0.51-1.0   | 101       | 120    | 26.72%  |
| 1.01-2.0   | 15        | 40     | 3.97%   |
| 2.01-3.0   | 9         | 19     | 2.38%   |
| 4.01-10.0  | 4         | 23     | 1.06%   |
| 3.01-4.0   | 2         | 2      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 158       | 36.07%  |
| 251-500        | 100       | 22.83%  |
| 51-100         | 58        | 13.24%  |
| 501-1000       | 43        | 9.82%   |
| 1-20           | 24        | 5.48%   |
| 21-50          | 20        | 4.57%   |
| 1001-2000      | 18        | 4.11%   |
| Unknown        | 9         | 2.05%   |
| More than 3000 | 5         | 1.14%   |
| 2001-3000      | 3         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 167       | 36.62%  |
| 21-50          | 114       | 25%     |
| 51-100         | 65        | 14.25%  |
| 101-250        | 57        | 12.5%   |
| 251-500        | 24        | 5.26%   |
| 501-1000       | 13        | 2.85%   |
| Unknown        | 9         | 1.97%   |
| 1001-2000      | 4         | 0.88%   |
| 2001-3000      | 2         | 0.44%   |
| More than 3000 | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD              | 2         | 2      | 3.77%   |
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 3.77%   |
| Seagate ST2000DM008-2FR1 2TB                  | 2         | 2      | 3.77%   |
| Seagate ST1000LM035-1RK172 1TB                | 2         | 2      | 3.77%   |
| Hewlett-Packard MB2000EBZQC 2TB               | 2         | 3      | 3.77%   |
| Crucial CT525MX300SSD1 528GB                  | 2         | 2      | 3.77%   |
| WDC WD5000AAKX-75U6AA0 500GB                  | 1         | 1      | 1.89%   |
| WDC WD2500HHTZ-04N21V0 250GB                  | 1         | 1      | 1.89%   |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 1.89%   |
| WDC WD2500AAKS-00F0A0 250GB                   | 1         | 1      | 1.89%   |
| WDC WD20EZRZ-00Z5HB0 2TB                      | 1         | 1      | 1.89%   |
| WDC WD1600AAJS-22L7A0 160GB                   | 1         | 1      | 1.89%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 1.89%   |
| WDC WD10JPVT-60A1YT0 1TB                      | 1         | 1      | 1.89%   |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 1.89%   |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 1.89%   |
| Toshiba MQ01ABD050V 500GB                     | 1         | 1      | 1.89%   |
| Toshiba MK1633GSG 160GB                       | 1         | 2      | 1.89%   |
| Toshiba DT01ACA100 1TB                        | 1         | 1      | 1.89%   |
| Supersonic SSD 256 256GB                      | 1         | 1      | 1.89%   |
| SK hynix PC401 NVMe 256GB                     | 1         | 1      | 1.89%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 1.89%   |
| Seagate ST980411ASG 80GB                      | 1         | 2      | 1.89%   |
| Seagate ST9750420AS 752GB                     | 1         | 1      | 1.89%   |
| Seagate ST500LM021-1KJ152 500GB               | 1         | 1      | 1.89%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 1.89%   |
| Seagate ST3500418AS 500GB                     | 1         | 1      | 1.89%   |
| Seagate ST3160215AS 160GB                     | 1         | 1      | 1.89%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 2      | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 1.89%   |
| Seagate ST1000DM010-2EP102 1TB                | 1         | 1      | 1.89%   |
| Seagate ST1000DM003-1SB10C 1TB                | 1         | 1      | 1.89%   |
| Samsung Electronics SP2004C 200GB             | 1         | 1      | 1.89%   |
| Samsung Electronics HD080HJ 80GB              | 1         | 1      | 1.89%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 1.89%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD | 1         | 1      | 1.89%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 1.89%   |
| Intel SSDSC2BF180A4H 180GB                    | 1         | 1      | 1.89%   |
| Intel SSDSA2M080G2GN 80GB                     | 1         | 1      | 1.89%   |
| HS-SSD-E100 SSD 1024G                         | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 25.49%  |
| WDC                 | 11        | 13     | 21.57%  |
| Toshiba             | 5         | 6      | 9.8%    |
| Hitachi             | 5         | 6      | 9.8%    |
| Intel               | 3         | 3      | 5.88%   |
| SK hynix            | 2         | 2      | 3.92%   |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Micron Technology   | 2         | 2      | 3.92%   |
| Hewlett-Packard     | 2         | 3      | 3.92%   |
| Crucial             | 2         | 2      | 3.92%   |
| Supersonic          | 1         | 1      | 1.96%   |
| HS-SSD-E100         | 1         | 1      | 1.96%   |
| Gritronix           | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 35.14%  |
| WDC                 | 10        | 11     | 27.03%  |
| Toshiba             | 5         | 6      | 13.51%  |
| Hitachi             | 5         | 6      | 13.51%  |
| Samsung Electronics | 2         | 2      | 5.41%   |
| Hewlett-Packard     | 2         | 3      | 5.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 44     | 68.18%  |
| SSD  | 13        | 14     | 29.55%  |
| NVMe | 1         | 1      | 2.27%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 265       | 452    | 59.02%  |
| Works    | 142       | 264    | 31.63%  |
| Malfunc  | 42        | 59     | 9.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 346       | 69.62%  |
| Samsung Electronics            | 29        | 5.84%   |
| AMD                            | 29        | 5.84%   |
| SanDisk                        | 12        | 2.41%   |
| KIOXIA                         | 10        | 2.01%   |
| Silicon Motion                 | 8         | 1.61%   |
| LSI Logic / Symbios Logic      | 8         | 1.61%   |
| SK hynix                       | 7         | 1.41%   |
| Micron Technology              | 6         | 1.21%   |
| Kingston Technology Company    | 5         | 1.01%   |
| Transcend                      | 4         | 0.8%    |
| Phison Electronics             | 4         | 0.8%    |
| Hewlett-Packard                | 4         | 0.8%    |
| Toshiba America Info Systems   | 3         | 0.6%    |
| Nvidia                         | 3         | 0.6%    |
| Apple                          | 3         | 0.6%    |
| Shenzhen Longsys Electronics   | 2         | 0.4%    |
| Realtek Semiconductor          | 2         | 0.4%    |
| Marvell Technology Group       | 2         | 0.4%    |
| ASMedia Technology             | 2         | 0.4%    |
| ADATA Technology               | 2         | 0.4%    |
| Solid State Storage Technology | 1         | 0.2%    |
| Netac Technology               | 1         | 0.2%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.2%    |
| Lenovo                         | 1         | 0.2%    |
| Broadcom / LSI                 | 1         | 0.2%    |
| Adaptec                        | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 53        | 9.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 32        | 5.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 4.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 3.86%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 3.68%   |
| Intel Comet Lake SATA AHCI Controller                                          | 19        | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 3.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 17        | 2.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.46%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 2.28%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 2.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.4%    |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 8         | 1.4%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 1.4%    |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.23%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 6         | 1.05%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6         | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.88%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 5         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 0.88%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 4         | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.7%    |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.7%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 0.7%    |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 4         | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.7%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.53%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 3         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 299       | 55.99%  |
| NVMe | 109       | 20.41%  |
| RAID | 69        | 12.92%  |
| IDE  | 42        | 7.87%   |
| SCSI | 9         | 1.69%   |
| SAS  | 6         | 1.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 380       | 91.79%  |
| AMD    | 34        | 8.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 13        | 3.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 12        | 2.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 12        | 2.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 2.17%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 2.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 1.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 7         | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 1.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 1.45%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 5         | 1.2%    |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 5         | 1.2%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 1.2%    |
| Intel Core i5-4300U CPU @ 1.90GHz       | 5         | 1.2%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 5         | 1.2%    |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 4         | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 0.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 0.96%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 0.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 4         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 0.96%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 4         | 0.96%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 0.96%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4         | 0.96%   |
| Intel 12th Gen Core i5-1235U            | 4         | 0.96%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 3         | 0.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.72%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 3         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 0.72%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 3         | 0.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 3         | 0.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 0.72%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3         | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3         | 0.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 146       | 35.27%  |
| Intel Core i7        | 98        | 23.67%  |
| Other                | 41        | 9.9%    |
| Intel Core i3        | 22        | 5.31%   |
| Intel Xeon           | 21        | 5.07%   |
| Intel Core 2 Duo     | 18        | 4.35%   |
| AMD Ryzen 7          | 12        | 2.9%    |
| Intel Celeron        | 8         | 1.93%   |
| AMD Ryzen 5          | 7         | 1.69%   |
| Intel Pentium        | 5         | 1.21%   |
| Intel Core m3        | 5         | 1.21%   |
| Intel Atom           | 5         | 1.21%   |
| Intel Core M         | 3         | 0.72%   |
| Intel Pentium Dual   | 2         | 0.48%   |
| Intel Core 2 Quad    | 2         | 0.48%   |
| Intel Core 2         | 2         | 0.48%   |
| AMD Athlon II X2     | 2         | 0.48%   |
| AMD A6               | 2         | 0.48%   |
| AMD A4               | 2         | 0.48%   |
| Intel Genuine        | 1         | 0.24%   |
| Intel Core 2 Extreme | 1         | 0.24%   |
| AMD Ryzen 9          | 1         | 0.24%   |
| AMD Ryzen 3          | 1         | 0.24%   |
| AMD PRO A8           | 1         | 0.24%   |
| AMD G                | 1         | 0.24%   |
| AMD FX               | 1         | 0.24%   |
| AMD E                | 1         | 0.24%   |
| AMD Athlon X4        | 1         | 0.24%   |
| AMD A8               | 1         | 0.24%   |
| AMD A12              | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 197       | 47.36%  |
| 4      | 157       | 37.74%  |
| 8      | 22        | 5.29%   |
| 6      | 22        | 5.29%   |
| 10     | 7         | 1.68%   |
| 12     | 5         | 1.2%    |
| 1      | 3         | 0.72%   |
| 16     | 2         | 0.48%   |
| 14     | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 404       | 97.35%  |
| 2      | 11        | 2.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 324       | 77.88%  |
| 1      | 92        | 22.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 411       | 99.04%  |
| Unknown        | 3         | 0.72%   |
| 32-bit         | 1         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 36.03%  |
| 0x206a7    | 24        | 5.54%   |
| 0x306a9    | 20        | 4.62%   |
| 0x806c1    | 19        | 4.39%   |
| 0x806ec    | 18        | 4.16%   |
| 0x806e9    | 17        | 3.93%   |
| 0x406e3    | 17        | 3.93%   |
| 0x40651    | 14        | 3.23%   |
| 0x806ea    | 13        | 3%      |
| 0x306d4    | 13        | 3%      |
| 0x306c3    | 13        | 3%      |
| 0x20655    | 11        | 2.54%   |
| 0x1067a    | 11        | 2.54%   |
| 0x706e5    | 6         | 1.39%   |
| 0x206c2    | 6         | 1.39%   |
| 0x206d7    | 5         | 1.15%   |
| 0x906ea    | 4         | 0.92%   |
| 0x6f6      | 4         | 0.92%   |
| 0x506e3    | 4         | 0.92%   |
| 0x30678    | 4         | 0.92%   |
| 0x0a50000c | 4         | 0.92%   |
| 0xa0655    | 3         | 0.69%   |
| 0xa0652    | 3         | 0.69%   |
| 0x406c4    | 3         | 0.69%   |
| 0x106a5    | 3         | 0.69%   |
| 0x10676    | 3         | 0.69%   |
| 0x906e9    | 2         | 0.46%   |
| 0x906a4    | 2         | 0.46%   |
| 0x6fd      | 2         | 0.46%   |
| 0x20652    | 2         | 0.46%   |
| 0x08701021 | 2         | 0.46%   |
| 0x08608103 | 2         | 0.46%   |
| 0x08600106 | 2         | 0.46%   |
| 0x0600111f | 2         | 0.46%   |
| 0x05000119 | 2         | 0.46%   |
| 0xa0671    | 1         | 0.23%   |
| 0xa0660    | 1         | 0.23%   |
| 0x906a3    | 1         | 0.23%   |
| 0x806eb    | 1         | 0.23%   |
| 0x706a1    | 1         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 86        | 20.72%  |
| Haswell          | 46        | 11.08%  |
| SandyBridge      | 39        | 9.4%    |
| IvyBridge        | 34        | 8.19%   |
| TigerLake        | 30        | 7.23%   |
| Westmere         | 28        | 6.75%   |
| Skylake          | 27        | 6.51%   |
| Broadwell        | 20        | 4.82%   |
| Penryn           | 19        | 4.58%   |
| Silvermont       | 10        | 2.41%   |
| Icelake          | 8         | 1.93%   |
| Core             | 8         | 1.93%   |
| Zen 3            | 7         | 1.69%   |
| Zen 2            | 7         | 1.69%   |
| CometLake        | 7         | 1.69%   |
| Unknown          | 7         | 1.69%   |
| Nehalem          | 6         | 1.45%   |
| Alderlake Hybrid | 6         | 1.45%   |
| Zen+             | 4         | 0.96%   |
| Steamroller      | 3         | 0.72%   |
| Piledriver       | 3         | 0.72%   |
| K10              | 2         | 0.48%   |
| Bobcat           | 2         | 0.48%   |
| Zen              | 1         | 0.24%   |
| P6               | 1         | 0.24%   |
| K10 Llano        | 1         | 0.24%   |
| Jaguar           | 1         | 0.24%   |
| Goldmont plus    | 1         | 0.24%   |
| Excavator        | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 320       | 65.31%  |
| Nvidia                     | 92        | 18.78%  |
| AMD                        | 75        | 15.31%  |
| Matrox Electronics Systems | 3         | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 5.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 4.99%   |
| Intel UHD Graphics 620                                                                   | 21        | 4.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 4.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 4.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 3.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 3.79%   |
| Intel HD Graphics 620                                                                    | 17        | 3.39%   |
| Intel HD Graphics 5500                                                                   | 17        | 3.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 2.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.4%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.4%    |
| Nvidia GP108M [GeForce MX230]                                                            | 6         | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.2%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1%      |
| Intel HD Graphics 615                                                                    | 5         | 1%      |
| Intel HD Graphics 530                                                                    | 5         | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 0.8%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 0.8%    |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.6%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.6%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.6%    |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 0.6%    |
| Intel HD Graphics 5300                                                                   | 3         | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.4%    |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.4%    |
| Nvidia GT218 [GeForce 310]                                                               | 2         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 251       | 60.05%  |
| 1 x AMD        | 46        | 11%     |
| Intel + Nvidia | 45        | 10.77%  |
| 1 x Nvidia     | 39        | 9.33%   |
| Intel + AMD    | 22        | 5.26%   |
| AMD + Nvidia   | 6         | 1.44%   |
| 1 x Matrox     | 3         | 0.72%   |
| Other          | 2         | 0.48%   |
| 2 x Nvidia     | 2         | 0.48%   |
| 2 x AMD        | 2         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 363       | 85.61%  |
| Proprietary | 47        | 11.08%  |
| Unknown     | 14        | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 305       | 72.62%  |
| 1.01-2.0   | 51        | 12.14%  |
| 0.01-0.5   | 25        | 5.95%   |
| 0.51-1.0   | 16        | 3.81%   |
| 3.01-4.0   | 15        | 3.57%   |
| 7.01-8.0   | 3         | 0.71%   |
| 5.01-6.0   | 2         | 0.48%   |
| 8.01-16.0  | 2         | 0.48%   |
| 2.01-3.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 71        | 17.79%  |
| AU Optronics            | 60        | 15.04%  |
| Chimei Innolux          | 57        | 14.29%  |
| BOE                     | 44        | 11.03%  |
| Samsung Electronics     | 30        | 7.52%   |
| Dell                    | 29        | 7.27%   |
| Hewlett-Packard         | 26        | 6.52%   |
| Chi Mei Optoelectronics | 9         | 2.26%   |
| Lenovo                  | 8         | 2.01%   |
| Apple                   | 7         | 1.75%   |
| Acer                    | 6         | 1.5%    |
| Sharp                   | 5         | 1.25%   |
| InfoVision              | 5         | 1.25%   |
| Unknown                 | 4         | 1%      |
| KDC                     | 4         | 1%      |
| Goldstar                | 4         | 1%      |
| NEC Computers           | 3         | 0.75%   |
| ViewSonic               | 2         | 0.5%    |
| Sony                    | 2         | 0.5%    |
| PANDA                   | 2         | 0.5%    |
| MStar                   | 2         | 0.5%    |
| LGD                     | 2         | 0.5%    |
| LG Philips              | 2         | 0.5%    |
| Hitachi                 | 2         | 0.5%    |
| BenQ                    | 2         | 0.5%    |
| SDC                     | 1         | 0.25%   |
| Planar                  | 1         | 0.25%   |
| Philips                 | 1         | 0.25%   |
| LPL                     | 1         | 0.25%   |
| LED                     | 1         | 0.25%   |
| HKC                     | 1         | 0.25%   |
| HannStar                | 1         | 0.25%   |
| DENON                   | 1         | 0.25%   |
| CTO                     | 1         | 0.25%   |
| CSO                     | 1         | 0.25%   |
| AOC                     | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 10        | 2.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 1.24%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 0.99%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 4         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 4         | 0.99%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.99%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 0.74%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.74%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 3         | 0.74%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 3         | 0.74%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.5%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.5%    |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 2         | 0.5%    |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 0.5%    |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 0.5%    |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 2         | 0.5%    |
| LG Display LCD Monitor LGD052F 1920x1080 344x194mm 15.5-inch          | 2         | 0.5%    |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 2         | 0.5%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.5%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.5%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 2         | 0.5%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.5%    |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 0.5%    |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch              | 2         | 0.5%    |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.5%    |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 0.5%    |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                     | 2         | 0.5%    |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 0.5%    |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 179       | 46.74%  |
| 1366x768 (WXGA)    | 111       | 28.98%  |
| 1600x900 (HD+)     | 13        | 3.39%   |
| 3840x2160 (4K)     | 12        | 3.13%   |
| 1680x1050 (WSXGA+) | 11        | 2.87%   |
| 1280x800 (WXGA)    | 9         | 2.35%   |
| 1280x1024 (SXGA)   | 9         | 2.35%   |
| 1440x900 (WXGA+)   | 7         | 1.83%   |
| 1920x1200 (WUXGA)  | 6         | 1.57%   |
| 2880x1800          | 4         | 1.04%   |
| 1024x768 (XGA)     | 4         | 1.04%   |
| 3440x1440          | 3         | 0.78%   |
| 2560x1600          | 3         | 0.78%   |
| 2560x1440 (QHD)    | 3         | 0.78%   |
| 2288x1287          | 2         | 0.52%   |
| Unknown            | 2         | 0.52%   |
| 3640x1920          | 1         | 0.26%   |
| 3520x1080          | 1         | 0.26%   |
| 2160x1440          | 1         | 0.26%   |
| 1600x1200          | 1         | 0.26%   |
| 1360x768           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 145       | 36.52%  |
| 14      | 57        | 14.36%  |
| 13      | 55        | 13.85%  |
| 24      | 20        | 5.04%   |
| 17      | 19        | 4.79%   |
| 21      | 17        | 4.28%   |
| 23      | 14        | 3.53%   |
| Unknown | 14        | 3.53%   |
| 12      | 10        | 2.52%   |
| 11      | 8         | 2.02%   |
| 19      | 7         | 1.76%   |
| 22      | 6         | 1.51%   |
| 27      | 5         | 1.26%   |
| 40      | 3         | 0.76%   |
| 18      | 3         | 0.76%   |
| 142     | 2         | 0.5%    |
| 72      | 2         | 0.5%    |
| 52      | 2         | 0.5%    |
| 20      | 2         | 0.5%    |
| 16      | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 31      | 1         | 0.25%   |
| 26      | 1         | 0.25%   |
| 10      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 232       | 58.73%  |
| 201-300        | 47        | 11.9%   |
| 501-600        | 39        | 9.87%   |
| 401-500        | 31        | 7.85%   |
| 351-400        | 21        | 5.32%   |
| Unknown        | 14        | 3.54%   |
| 801-900        | 3         | 0.76%   |
| 1501-2000      | 3         | 0.76%   |
| More than 2000 | 2         | 0.51%   |
| 1001-1500      | 2         | 0.51%   |
| 601-700        | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 306       | 82.04%  |
| 16/10   | 36        | 9.65%   |
| Unknown | 14        | 3.75%   |
| 5/4     | 9         | 2.41%   |
| 4/3     | 5         | 1.34%   |
| 1.00    | 2         | 0.54%   |
| 3/2     | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 145       | 36.62%  |
| 81-90          | 86        | 21.72%  |
| 201-250        | 47        | 11.87%  |
| 71-80          | 24        | 6.06%   |
| 151-200        | 14        | 3.54%   |
| Unknown        | 14        | 3.54%   |
| 121-130        | 12        | 3.03%   |
| 61-70          | 10        | 2.53%   |
| 51-60          | 8         | 2.02%   |
| 141-150        | 8         | 2.02%   |
| More than 1000 | 7         | 1.77%   |
| 301-350        | 5         | 1.26%   |
| 251-300        | 5         | 1.26%   |
| 501-1000       | 3         | 0.76%   |
| 91-100         | 3         | 0.76%   |
| 131-140        | 2         | 0.51%   |
| 351-500        | 1         | 0.25%   |
| 41-50          | 1         | 0.25%   |
| 111-120        | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 156       | 39.69%  |
| 101-120       | 115       | 29.26%  |
| 51-100        | 75        | 19.08%  |
| 161-240       | 19        | 4.83%   |
| Unknown       | 14        | 3.56%   |
| More than 240 | 8         | 2.04%   |
| 1-50          | 6         | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 361       | 85.95%  |
| 2     | 34        | 8.1%    |
| 0     | 24        | 5.71%   |
| 3     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 271       | 40.45%  |
| Realtek Semiconductor             | 193       | 28.81%  |
| Broadcom                          | 56        | 8.36%   |
| Qualcomm Atheros                  | 36        | 5.37%   |
| Ralink Technology                 | 15        | 2.24%   |
| Broadcom Limited                  | 13        | 1.94%   |
| MediaTek                          | 11        | 1.64%   |
| TP-Link                           | 6         | 0.9%    |
| Samsung Electronics               | 6         | 0.9%    |
| Marvell Technology Group          | 6         | 0.9%    |
| Hewlett-Packard                   | 6         | 0.9%    |
| Ralink                            | 5         | 0.75%   |
| ASIX Electronics                  | 5         | 0.75%   |
| Sierra Wireless                   | 4         | 0.6%    |
| Qualcomm Atheros Communications   | 4         | 0.6%    |
| Huawei Technologies               | 4         | 0.6%    |
| D-Link                            | 4         | 0.6%    |
| ZTE WCDMA Technologies MSM        | 3         | 0.45%   |
| Xiaomi                            | 3         | 0.45%   |
| Nvidia                            | 3         | 0.45%   |
| Spreadtrum Communications         | 2         | 0.3%    |
| Qualcomm                          | 2         | 0.3%    |
| Dell                              | 2         | 0.3%    |
| ZTopInc                           | 1         | 0.15%   |
| Zoom Telephonics                  | 1         | 0.15%   |
| VIA Technologies                  | 1         | 0.15%   |
| QLogic                            | 1         | 0.15%   |
| OPPO Electronics                  | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| Google                            | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| Emulex                            | 1         | 0.15%   |
| 3Com                              | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 125       | 15.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 38        | 4.69%   |
| Intel Wi-Fi 6 AX201                                                    | 24        | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 2.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 18        | 2.22%   |
| Intel Wireless 8265 / 8275                                             | 17        | 2.1%    |
| Intel Wireless 7265                                                    | 17        | 2.1%    |
| Intel Wireless 7260                                                    | 17        | 2.1%    |
| Intel Ethernet Connection I217-LM                                      | 17        | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 15        | 1.85%   |
| Intel Wireless 3165                                                    | 14        | 1.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 14        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 1.6%    |
| Intel Wireless 8260                                                    | 12        | 1.48%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 1.36%   |
| Ralink MT7601U Wireless Adapter                                        | 10        | 1.23%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.11%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 9         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 0.99%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.99%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 7         | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 0.86%   |
| Intel Centrino Advanced-N 6200                                         | 7         | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.74%   |
| MediaTek RMX3085                                                       | 6         | 0.74%   |
| Intel Wireless 3160                                                    | 6         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                         | 6         | 0.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 6         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 0.62%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 0.62%   |
| Intel Ultimate N WiFi Link 5300                                        | 5         | 0.62%   |
| Intel Centrino Advanced-N 6235                                         | 5         | 0.62%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 211       | 54.24%  |
| Realtek Semiconductor           | 58        | 14.91%  |
| Qualcomm Atheros                | 33        | 8.48%   |
| Broadcom                        | 29        | 7.46%   |
| Ralink Technology               | 15        | 3.86%   |
| Broadcom Limited                | 8         | 2.06%   |
| TP-Link                         | 6         | 1.54%   |
| Ralink                          | 5         | 1.29%   |
| Sierra Wireless                 | 4         | 1.03%   |
| Qualcomm Atheros Communications | 4         | 1.03%   |
| MediaTek                        | 4         | 1.03%   |
| D-Link                          | 4         | 1.03%   |
| Hewlett-Packard                 | 3         | 0.77%   |
| Marvell Technology Group        | 2         | 0.51%   |
| Dell                            | 2         | 0.51%   |
| ZTopInc                         | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 24        | 6.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 18        | 4.59%   |
| Intel Wireless 8265 / 8275                                           | 17        | 4.34%   |
| Intel Wireless 7265                                                  | 17        | 4.34%   |
| Intel Wireless 7260                                                  | 17        | 4.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 15        | 3.83%   |
| Intel Wireless 3165                                                  | 14        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 13        | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 13        | 3.32%   |
| Intel Wireless 8260                                                  | 12        | 3.06%   |
| Ralink MT7601U Wireless Adapter                                      | 10        | 2.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 9         | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8         | 2.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 7         | 1.79%   |
| Intel Centrino Advanced-N 6200                                       | 7         | 1.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 7         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 6         | 1.53%   |
| Intel Wireless 3160                                                  | 6         | 1.53%   |
| Intel Centrino Ultimate-N 6300                                       | 6         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 1.28%   |
| Intel Wi-Fi 6 AX200                                                  | 5         | 1.28%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 1.28%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 1.28%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 5         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 1.02%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 1.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 3         | 0.77%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 3         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 0.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3         | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 0.77%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 162       | 39.9%   |
| Intel                      | 159       | 39.16%  |
| Broadcom                   | 28        | 6.9%    |
| MediaTek                   | 7         | 1.72%   |
| Samsung Electronics        | 6         | 1.48%   |
| Qualcomm Atheros           | 5         | 1.23%   |
| Broadcom Limited           | 5         | 1.23%   |
| ASIX Electronics           | 5         | 1.23%   |
| Marvell Technology Group   | 4         | 0.99%   |
| ZTE WCDMA Technologies MSM | 3         | 0.74%   |
| Xiaomi                     | 3         | 0.74%   |
| Nvidia                     | 3         | 0.74%   |
| Huawei Technologies        | 3         | 0.74%   |
| Spreadtrum Communications  | 2         | 0.49%   |
| Qualcomm                   | 2         | 0.49%   |
| Hewlett-Packard            | 2         | 0.49%   |
| VIA Technologies           | 1         | 0.25%   |
| QLogic                     | 1         | 0.25%   |
| OPPO Electronics           | 1         | 0.25%   |
| JMicron Technology         | 1         | 0.25%   |
| Google                     | 1         | 0.25%   |
| Emulex                     | 1         | 0.25%   |
| 3Com                       | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 125       | 30.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 38        | 9.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 5.54%   |
| Intel Ethernet Connection I217-LM                                      | 17        | 4.1%    |
| Intel Ethernet Connection (3) I218-LM                                  | 14        | 3.37%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 2.65%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 2.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 2.17%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 9         | 2.17%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.69%   |
| MediaTek RMX3085                                                       | 6         | 1.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 6         | 1.45%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                               | 5         | 1.2%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.96%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                    | 3         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.72%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 3         | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.72%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 3         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.48%   |
| Spreadtrum Unisoc Phone                                                | 2         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.48%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.48%   |
| Qualcomm Nokia G42 5G                                                  | 2         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.48%   |
| Nvidia MCP51 Ethernet Controller                                       | 2         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.48%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 366       | 49.8%   |
| Ethernet | 365       | 49.66%  |
| Modem    | 4         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 308       | 74.94%  |
| Ethernet | 103       | 25.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 276       | 66.03%  |
| 1     | 121       | 28.95%  |
| 3     | 7         | 1.67%   |
| 0     | 7         | 1.67%   |
| 4     | 5         | 1.2%    |
| 8     | 1         | 0.24%   |
| 6     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 381       | 90.28%  |
| Yes  | 41        | 9.72%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 154       | 55.8%   |
| Realtek Semiconductor           | 34        | 12.32%  |
| Qualcomm Atheros Communications | 23        | 8.33%   |
| Cambridge Silicon Radio         | 18        | 6.52%   |
| Broadcom                        | 18        | 6.52%   |
| Dell                            | 6         | 2.17%   |
| Foxconn / Hon Hai               | 5         | 1.81%   |
| Apple                           | 4         | 1.45%   |
| Ralink                          | 3         | 1.09%   |
| Hewlett-Packard                 | 3         | 1.09%   |
| IMC Networks                    | 2         | 0.72%   |
| Realtek                         | 1         | 0.36%   |
| Ralink Technology               | 1         | 0.36%   |
| Marvell Semiconductor           | 1         | 0.36%   |
| Lite-On Technology              | 1         | 0.36%   |
| Askey Computer                  | 1         | 0.36%   |
| AboCom Systems                  | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 50        | 18.12%  |
| Intel AX201 Bluetooth                                                               | 35        | 12.68%  |
| Intel Bluetooth Device                                                              | 26        | 9.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 26        | 9.42%   |
| Realtek Bluetooth Radio                                                             | 22        | 7.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 18        | 6.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.71%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 2.54%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.17%   |
| Intel AX200 Bluetooth                                                               | 5         | 1.81%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 1.81%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.09%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.09%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.09%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.72%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.72%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.72%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.72%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.72%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 2         | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.36%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.36%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.36%   |
| Ralink CSR BS8510                                                                   | 1         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.36%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.36%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.36%   |
| Intel AX211 Bluetooth                                                               | 1         | 0.36%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.36%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.36%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.36%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 367       | 73.11%  |
| Nvidia                 | 54        | 10.76%  |
| AMD                    | 54        | 10.76%  |
| Generalplus Technology | 7         | 1.39%   |
| C-Media Electronics    | 5         | 1%      |
| Logitech               | 4         | 0.8%    |
| JMTek                  | 2         | 0.4%    |
| Apple                  | 2         | 0.4%    |
| Texas Instruments      | 1         | 0.2%    |
| Samsung Electronics    | 1         | 0.2%    |
| Realtek Semiconductor  | 1         | 0.2%    |
| OPPO Electronics       | 1         | 0.2%    |
| FIFINE 683 Microphone  | 1         | 0.2%    |
| Dell                   | 1         | 0.2%    |
| Creative Labs          | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 64        | 10.81%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 36        | 6.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 30        | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30        | 5.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24        | 4.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 3.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 22        | 3.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 21        | 3.55%   |
| Intel 8 Series HD Audio Controller                                         | 21        | 3.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 3.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 3.38%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 3.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 2.53%   |
| Nvidia High Definition Audio Controller                                    | 11        | 1.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11        | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 1.52%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.18%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.18%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.01%   |
| Generalplus Technology USB Audio Device                                    | 6         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.68%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4         | 0.68%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.68%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 81        | 29.24%  |
| SK hynix            | 77        | 27.8%   |
| Micron Technology   | 35        | 12.64%  |
| A-DATA Technology   | 17        | 6.14%   |
| Kingston            | 11        | 3.97%   |
| Transcend           | 8         | 2.89%   |
| Crucial             | 8         | 2.89%   |
| Unknown             | 6         | 2.17%   |
| Team                | 6         | 2.17%   |
| Lexar               | 6         | 2.17%   |
| Elpida              | 4         | 1.44%   |
| Spectek             | 3         | 1.08%   |
| Unknown (2C0B)      | 2         | 0.72%   |
| Ramaxel Technology  | 2         | 0.72%   |
| Nanya Technology    | 2         | 0.72%   |
| Unknown (768A)      | 1         | 0.36%   |
| Unknown (0x0BF7)    | 1         | 0.36%   |
| TwinMOS             | 1         | 0.36%   |
| Toshiba-0098        | 1         | 0.36%   |
| S                   | 1         | 0.36%   |
| Patriot             | 1         | 0.36%   |
| Hikvision           | 1         | 0.36%   |
| H                   | 1         | 0.36%   |
| Axiom               | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 1.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 5         | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 1.64%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s               | 5         | 1.64%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 4         | 1.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.98%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 3         | 0.98%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 3         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.98%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 0.98%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.98%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 3         | 0.98%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s         | 3         | 0.98%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s              | 3         | 0.98%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 0.98%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 3         | 0.98%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 3         | 0.98%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                   | 3         | 0.98%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s            | 2         | 0.66%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s        | 2         | 0.66%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 2         | 0.66%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s     | 2         | 0.66%   |
| Spectek RAM Module 8GB Row Of Chips LPDDR3 1600MT/s          | 2         | 0.66%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 2         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.66%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s        | 2         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 2         | 0.66%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s       | 2         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.66%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 0.66%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 2         | 0.66%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s               | 2         | 0.66%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 2         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 106       | 50.96%  |
| DDR3   | 80        | 38.46%  |
| LPDDR3 | 9         | 4.33%   |
| LPDDR4 | 5         | 2.4%    |
| SDRAM  | 3         | 1.44%   |
| DDR5   | 2         | 0.96%   |
| DDR2   | 2         | 0.96%   |
| DDR    | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 151       | 71.56%  |
| DIMM         | 40        | 18.96%  |
| Row Of Chips | 20        | 9.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 93        | 39.74%  |
| 4096  | 64        | 27.35%  |
| 16384 | 42        | 17.95%  |
| 2048  | 24        | 10.26%  |
| 32768 | 11        | 4.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 63        | 26.58%  |
| 2667  | 47        | 19.83%  |
| 3200  | 40        | 16.88%  |
| 2133  | 22        | 9.28%   |
| 2400  | 13        | 5.49%   |
| 1333  | 13        | 5.49%   |
| 1334  | 10        | 4.22%   |
| 4267  | 3         | 1.27%   |
| 3266  | 3         | 1.27%   |
| 1866  | 3         | 1.27%   |
| 1067  | 3         | 1.27%   |
| 4800  | 2         | 0.84%   |
| 1066  | 2         | 0.84%   |
| 8400  | 1         | 0.42%   |
| 4266  | 1         | 0.42%   |
| 4199  | 1         | 0.42%   |
| 3800  | 1         | 0.42%   |
| 3733  | 1         | 0.42%   |
| 3000  | 1         | 0.42%   |
| 2666  | 1         | 0.42%   |
| 2267  | 1         | 0.42%   |
| 2200  | 1         | 0.42%   |
| 2000  | 1         | 0.42%   |
| 1867  | 1         | 0.42%   |
| 975   | 1         | 0.42%   |
| 800   | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 66.67%  |
| STMicroelectronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| STMicroelectronics USB Printer P | 1         | 33.33%  |
| HP LaserJet 1300                 | 1         | 33.33%  |
| HP DeskJet F2492 All-in-One      | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Plustek | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 74        | 25.17%  |
| Microdia                               | 33        | 11.22%  |
| Sunplus Innovation Technology          | 28        | 9.52%   |
| Realtek Semiconductor                  | 26        | 8.84%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 8.16%   |
| Lite-On Technology                     | 15        | 5.1%    |
| Quanta                                 | 14        | 4.76%   |
| IMC Networks                           | 12        | 4.08%   |
| Syntek                                 | 9         | 3.06%   |
| Suyin                                  | 7         | 2.38%   |
| Ricoh                                  | 6         | 2.04%   |
| Luxvisions Innotech Limited            | 6         | 2.04%   |
| Bison Electronics                      | 6         | 2.04%   |
| Apple                                  | 5         | 1.7%    |
| Acer                                   | 5         | 1.7%    |
| Silicon Motion                         | 4         | 1.36%   |
| Logitech                               | 3         | 1.02%   |
| Z-Star Microelectronics                | 2         | 0.68%   |
| Primax Electronics                     | 2         | 0.68%   |
| SunplusIT                              | 1         | 0.34%   |
| Sunplus Technology                     | 1         | 0.34%   |
| Samsung Electronics                    | 1         | 0.34%   |
| Pixart Imaging                         | 1         | 0.34%   |
| OmniVision Technologies                | 1         | 0.34%   |
| Microsoft                              | 1         | 0.34%   |
| MacroSilicon                           | 1         | 0.34%   |
| Lenovo                                 | 1         | 0.34%   |
| Generalplus Technology                 | 1         | 0.34%   |
| DigiTech                               | 1         | 0.34%   |
| Asuscom Network                        | 1         | 0.34%   |
| Arkmicro Technologies                  | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 17        | 5.72%   |
| Sunplus Integrated_Webcam_HD                                               | 16        | 5.39%   |
| Chicony Integrated Camera                                                  | 15        | 5.05%   |
| Realtek Integrated_Webcam_HD                                               | 11        | 3.7%    |
| Chicony HP HD Camera                                                       | 11        | 3.7%    |
| Lite-On HP HD Webcam                                                       | 9         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 9         | 3.03%   |
| IMC Networks Integrated Camera                                             | 7         | 2.36%   |
| Syntek Integrated Camera                                                   | 6         | 2.02%   |
| Microdia Integrated Webcam                                                 | 6         | 2.02%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 1.68%   |
| Quanta HP HD Camera                                                        | 5         | 1.68%   |
| Chicony USB 2.0Camera                                                      | 5         | 1.68%   |
| Chicony HP TrueVision HD Camera                                            | 5         | 1.68%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 4         | 1.35%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.35%   |
| Chicony HP TrueVision HD                                                   | 4         | 1.35%   |
| Chicony EasyCamera                                                         | 4         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 1.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 4         | 1.35%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.01%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.01%   |
| Realtek USB Camera                                                         | 3         | 1.01%   |
| Realtek Integrated Webcam                                                  | 3         | 1.01%   |
| Lite-On Integrated Camera                                                  | 3         | 1.01%   |
| Lite-On HP HD Camera                                                       | 3         | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                                            | 3         | 1.01%   |
| Chicony HP Webcam [2 MP Macro]                                             | 3         | 1.01%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 3         | 1.01%   |
| Bison Integrated Camera                                                    | 3         | 1.01%   |
| Z-Star Venus USB2.0 Camera                                                 | 2         | 0.67%   |
| Suyin HP Truevision HD                                                     | 2         | 0.67%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 0.67%   |
| Sunplus HP Universal Camera                                                | 2         | 0.67%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.67%   |
| Ricoh HD Webcam                                                            | 2         | 0.67%   |
| Realtek Laptop_Integrated_Webcam_HD                                        | 2         | 0.67%   |
| Realtek Integrated Webcam_HD                                               | 2         | 0.67%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 59.77%  |
| Synaptics                  | 15        | 17.24%  |
| Shenzhen Goodix Technology | 10        | 11.49%  |
| AuthenTec                  | 4         | 4.6%    |
| Upek                       | 3         | 3.45%   |
| Elan Microelectronics      | 2         | 2.3%    |
| LighTuning Technology      | 1         | 1.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 25.29%  |
| Validity Sensors VFS491                                                    | 10        | 11.49%  |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 11.49%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 8.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 6.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.45%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.45%   |
| AuthenTec AES2810                                                          | 3         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.3%    |
| Synaptics  WBDI                                                            | 2         | 2.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.3%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.3%    |
| Elan ELAN:ARM-M4                                                           | 2         | 2.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.15%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.15%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.15%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.15%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.15%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 30        | 85.71%  |
| O2 Micro         | 3         | 8.57%   |
| SCM Microsystems | 1         | 2.86%   |
| Alcor Micro      | 1         | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 31.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 25.71%  |
| Broadcom 58200                                                               | 6         | 17.14%  |
| Broadcom 5880                                                                | 4         | 11.43%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.71%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 2.86%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.86%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 248       | 57.94%  |
| 1     | 149       | 34.81%  |
| 2     | 24        | 5.61%   |
| 3     | 3         | 0.7%    |
| 4     | 2         | 0.47%   |
| 8     | 1         | 0.23%   |
| 7     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 86        | 39.09%  |
| Chipcard                 | 34        | 15.45%  |
| Graphics card            | 31        | 14.09%  |
| Net/wireless             | 22        | 10%     |
| Sound                    | 11        | 5%      |
| Communication controller | 7         | 3.18%   |
| Multimedia controller    | 6         | 2.73%   |
| Bluetooth                | 6         | 2.73%   |
| Storage                  | 5         | 2.27%   |
| Camera                   | 5         | 2.27%   |
| Net/ethernet             | 3         | 1.36%   |
| Network                  | 2         | 0.91%   |
| Storage/ata              | 1         | 0.45%   |
| Card reader              | 1         | 0.45%   |


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

Total: 553

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Colorful T... | CVN X570M GAMING PRO V14    | Desktop     | [65b9bad459](https://linux-hardware.org/?probe=65b9bad459) | Nov 03, 2023 |
| Dell          | Precision 7740              | Notebook    | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [18398fe53c](https://linux-hardware.org/?probe=18398fe53c) | Oct 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [773814f03f](https://linux-hardware.org/?probe=773814f03f) | Oct 27, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 87        | 21.8%   |
| Ubuntu 22.04       | 45        | 11.28%  |
| Ubuntu 18.04       | 25        | 6.27%   |
| Debian 11          | 11        | 2.76%   |
| Ubuntu 23.04       | 9         | 2.26%   |
| Zorin 16           | 8         | 2.01%   |
| Arch               | 8         | 2.01%   |
| Pop!_OS 22.04      | 7         | 1.75%   |
| OpenMandriva 4.3   | 7         | 1.75%   |
| KDE neon 20.04     | 7         | 1.75%   |
| Ubuntu 22.10       | 6         | 1.5%    |
| Ubuntu 21.04       | 6         | 1.5%    |
| Debian 10          | 6         | 1.5%    |
| Zorin 15           | 5         | 1.25%   |
| Pop!_OS 20.04      | 5         | 1.25%   |
| Kali 2023.3        | 5         | 1.25%   |
| Fedora 38          | 5         | 1.25%   |
| ArcoLinux Rolling  | 5         | 1.25%   |
| Ubuntu 19.04       | 4         | 1%      |
| Pop!_OS 21.04      | 4         | 1%      |
| OpenMandriva 4.2   | 4         | 1%      |
| Linux Mint 21.2    | 4         | 1%      |
| Linux Mint 21.1    | 4         | 1%      |
| Linux Mint 20      | 4         | 1%      |
| Kali 2023.2        | 4         | 1%      |
| Fedora 36          | 4         | 1%      |
| Elementary 6.1     | 4         | 1%      |
| Xero Rolling       | 3         | 0.75%   |
| Ubuntu 21.10       | 3         | 0.75%   |
| Pop!_OS 20.10      | 3         | 0.75%   |
| OpenMandriva 23.01 | 3         | 0.75%   |
| Manjaro            | 3         | 0.75%   |
| Linux Mint 20.3    | 3         | 0.75%   |
| Linux Mint 20.2    | 3         | 0.75%   |
| Kubuntu 22.04      | 3         | 0.75%   |
| Kubuntu 20.04      | 3         | 0.75%   |
| Fedora 37          | 3         | 0.75%   |
| Fedora 34          | 3         | 0.75%   |
| Fedora 33          | 3         | 0.75%   |
| Arch Rolling       | 3         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 187       | 48.45%  |
| Linux Mint    | 22        | 5.7%    |
| Fedora        | 20        | 5.18%   |
| Pop!_OS       | 18        | 4.66%   |
| OpenMandriva  | 15        | 3.89%   |
| Zorin         | 14        | 3.63%   |
| Kali          | 14        | 3.63%   |
| Debian        | 14        | 3.63%   |
| Arch          | 11        | 2.85%   |
| Kubuntu       | 10        | 2.59%   |
| KDE neon      | 8         | 2.07%   |
| Manjaro       | 6         | 1.55%   |
| ArcoLinux     | 6         | 1.55%   |
| Elementary    | 4         | 1.04%   |
| Xero          | 3         | 0.78%   |
| Ubuntu Unity  | 3         | 0.78%   |
| Parrot        | 3         | 0.78%   |
| Endless       | 3         | 0.78%   |
| Xubuntu       | 2         | 0.52%   |
| ROSA          | 2         | 0.52%   |
| Nobara        | 2         | 0.52%   |
| Lubuntu       | 2         | 0.52%   |
| CentOS        | 2         | 0.52%   |
| Artix         | 2         | 0.52%   |
| Ubuntu MATE   | 1         | 0.26%   |
| Ubuntu Budgie | 1         | 0.26%   |
| Rocky Linux   | 1         | 0.26%   |
| RHEL          | 1         | 0.26%   |
| Oracle Linux  | 1         | 0.26%   |
| LMDE          | 1         | 0.26%   |
| LinuxFX       | 1         | 0.26%   |
| EndeavourOS   | 1         | 0.26%   |
| Deepin        | 1         | 0.26%   |
| Clear Linux   | 1         | 0.26%   |
| BlackPanther  | 1         | 0.26%   |
| Alpine        | 1         | 0.26%   |
| AlmaLinux     | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 10        | 2.33%   |
| 5.15.0-46-generic        | 8         | 1.86%   |
| 5.16.7-desktop-1omv4003  | 7         | 1.63%   |
| 5.19.0-42-generic        | 6         | 1.4%    |
| 5.11.0-37-generic        | 6         | 1.4%    |
| 5.4.106-1-pve            | 5         | 1.17%   |
| 5.15.0-47-generic        | 5         | 1.17%   |
| 6.3.0-kali1-amd64        | 4         | 0.93%   |
| 6.2.0-34-generic         | 4         | 0.93%   |
| 6.2.0-32-generic         | 4         | 0.93%   |
| 5.8.0-59-generic         | 4         | 0.93%   |
| 5.4.0-54-generic         | 4         | 0.93%   |
| 5.4.0-52-generic         | 4         | 0.93%   |
| 5.4.0-48-generic         | 4         | 0.93%   |
| 5.4.0-47-generic         | 4         | 0.93%   |
| 5.4.0-40-generic         | 4         | 0.93%   |
| 5.4.0-26-generic         | 4         | 0.93%   |
| 5.19.0-46-generic        | 4         | 0.93%   |
| 5.15.0-58-generic        | 4         | 0.93%   |
| 5.15.0-56-generic        | 4         | 0.93%   |
| 5.11.0-43-generic        | 4         | 0.93%   |
| 5.11.0-27-generic        | 4         | 0.93%   |
| 5.10.14-desktop-1omv4002 | 4         | 0.93%   |
| 6.2.0-35-generic         | 3         | 0.7%    |
| 6.2.0-31-generic         | 3         | 0.7%    |
| 6.2.0-26-generic         | 3         | 0.7%    |
| 6.1.1-desktop-1omv2290   | 3         | 0.7%    |
| 5.8.0-7630-generic       | 3         | 0.7%    |
| 5.8.0-44-generic         | 3         | 0.7%    |
| 5.8.0-41-generic         | 3         | 0.7%    |
| 5.4.0-7642-generic       | 3         | 0.7%    |
| 5.4.0-58-generic         | 3         | 0.7%    |
| 5.3.0-28-generic         | 3         | 0.7%    |
| 5.19.0-43-generic        | 3         | 0.7%    |
| 5.19.0-41-generic        | 3         | 0.7%    |
| 5.15.0-79-generic        | 3         | 0.7%    |
| 5.15.0-76-generic        | 3         | 0.7%    |
| 5.15.0-53-generic        | 3         | 0.7%    |
| 5.15.0-48-generic        | 3         | 0.7%    |
| 5.15.0-41-generic        | 3         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 15.8%   |
| 5.15.0  | 53        | 13.09%  |
| 5.19.0  | 31        | 7.65%   |
| 5.11.0  | 31        | 7.65%   |
| 5.8.0   | 23        | 5.68%   |
| 6.2.0   | 20        | 4.94%   |
| 5.13.0  | 19        | 4.69%   |
| 4.15.0  | 16        | 3.95%   |
| 5.0.0   | 11        | 2.72%   |
| 5.3.0   | 7         | 1.73%   |
| 5.16.7  | 7         | 1.73%   |
| 5.10.0  | 6         | 1.48%   |
| 5.4.106 | 5         | 1.23%   |
| 4.18.0  | 5         | 1.23%   |
| 6.3.0   | 4         | 0.99%   |
| 6.1.1   | 4         | 0.99%   |
| 5.11.22 | 4         | 0.99%   |
| 5.10.14 | 4         | 0.99%   |
| 6.2.6   | 3         | 0.74%   |
| 6.0.8   | 3         | 0.74%   |
| 6.5.5   | 2         | 0.49%   |
| 6.4.0   | 2         | 0.49%   |
| 6.1.0   | 2         | 0.49%   |
| 6.0.12  | 2         | 0.49%   |
| 5.9.8   | 2         | 0.49%   |
| 5.7.0   | 2         | 0.49%   |
| 5.19.9  | 2         | 0.49%   |
| 5.19.13 | 2         | 0.49%   |
| 5.18.0  | 2         | 0.49%   |
| 5.16.15 | 2         | 0.49%   |
| 5.13.4  | 2         | 0.49%   |
| 5.13.19 | 2         | 0.49%   |
| 3.10.0  | 2         | 0.49%   |
| 6.5.9   | 1         | 0.25%   |
| 6.5.7   | 1         | 0.25%   |
| 6.5.4   | 1         | 0.25%   |
| 6.5.0   | 1         | 0.25%   |
| 6.4.6   | 1         | 0.25%   |
| 6.4.15  | 1         | 0.25%   |
| 6.4.12  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 18.32%  |
| 5.15    | 55        | 13.61%  |
| 5.19    | 36        | 8.91%   |
| 5.11    | 35        | 8.66%   |
| 5.13    | 27        | 6.68%   |
| 6.2     | 26        | 6.44%   |
| 5.8     | 24        | 5.94%   |
| 4.15    | 16        | 3.96%   |
| 5.10    | 13        | 3.22%   |
| 5.0     | 11        | 2.72%   |
| 5.16    | 10        | 2.48%   |
| 6.1     | 9         | 2.23%   |
| 6.0     | 8         | 1.98%   |
| 5.3     | 8         | 1.98%   |
| 6.5     | 6         | 1.49%   |
| 6.3     | 6         | 1.49%   |
| 4.18    | 6         | 1.49%   |
| 6.4     | 5         | 1.24%   |
| 5.7     | 5         | 1.24%   |
| 5.18    | 5         | 1.24%   |
| 5.14    | 4         | 0.99%   |
| 5.9     | 3         | 0.74%   |
| 5.17    | 3         | 0.74%   |
| 3.10    | 3         | 0.74%   |
| 5.12    | 2         | 0.5%    |
| 5.6     | 1         | 0.25%   |
| 5.2     | 1         | 0.25%   |
| 4.9     | 1         | 0.25%   |
| 4.19    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 371       | 98.67%  |
| i686   | 5         | 1.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 240       | 61.7%   |
| KDE5       | 41        | 10.54%  |
| Unknown    | 37        | 9.51%   |
| X-Cinnamon | 19        | 4.88%   |
| XFCE       | 18        | 4.63%   |
| KDE        | 8         | 2.06%   |
| MATE       | 7         | 1.8%    |
| Pantheon   | 4         | 1.03%   |
| i3         | 4         | 1.03%   |
| Unity      | 3         | 0.77%   |
| KDE4       | 3         | 0.77%   |
| LXQt       | 2         | 0.51%   |
| Hyprland   | 1         | 0.26%   |
| Deepin     | 1         | 0.26%   |
| Budgie     | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 273       | 71.09%  |
| Wayland | 78        | 20.31%  |
| Unknown | 24        | 6.25%   |
| Tty     | 9         | 2.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 180       | 46.88%  |
| GDM3    | 86        | 22.4%   |
| GDM     | 50        | 13.02%  |
| SDDM    | 40        | 10.42%  |
| LightDM | 20        | 5.21%   |
| TDM     | 5         | 1.3%    |
| XDM     | 1         | 0.26%   |
| LXDM    | 1         | 0.26%   |
| KDM     | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 327       | 85.6%   |
| Unknown | 23        | 6.02%   |
| en_GB   | 19        | 4.97%   |
| en_PK   | 3         | 0.79%   |
| C       | 3         | 0.79%   |
| ur_PK   | 2         | 0.52%   |
| en_IN   | 2         | 0.52%   |
| en_ZA   | 1         | 0.26%   |
| en_CA   | 1         | 0.26%   |
| en_AG   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 199       | 51.69%  |
| EFI  | 186       | 48.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 306       | 79.27%  |
| Btrfs    | 22        | 5.7%    |
| Tmpfs    | 20        | 5.18%   |
| Overlay  | 16        | 4.15%   |
| Xfs      | 8         | 2.07%   |
| Zfs      | 7         | 1.81%   |
| Unknown  | 6         | 1.55%   |
| Reiserfs | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 200       | 52.22%  |
| GPT     | 145       | 37.86%  |
| MBR     | 38        | 9.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 336       | 87.73%  |
| Yes       | 47        | 12.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 249       | 64.68%  |
| Yes       | 136       | 35.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 131       | 34.84%  |
| Dell                | 104       | 27.66%  |
| Lenovo              | 61        | 16.22%  |
| Gigabyte Technology | 13        | 3.46%   |
| ASUSTek Computer    | 13        | 3.46%   |
| Haier               | 7         | 1.86%   |
| Acer                | 7         | 1.86%   |
| Apple               | 6         | 1.6%    |
| Toshiba             | 5         | 1.33%   |
| Sony                | 3         | 0.8%    |
| Samsung Electronics | 3         | 0.8%    |
| Shuttle             | 2         | 0.53%   |
| Intel               | 2         | 0.53%   |
| Fujitsu             | 2         | 0.53%   |
| Unknown             | 2         | 0.53%   |
| Timi                | 1         | 0.27%   |
| Quanta              | 1         | 0.27%   |
| MSI                 | 1         | 0.27%   |
| MOTION              | 1         | 0.27%   |
| Microsoft           | 1         | 0.27%   |
| KEIAN               | 1         | 0.27%   |
| Inventec            | 1         | 0.27%   |
| Google              | 1         | 0.27%   |
| Gateway             | 1         | 0.27%   |
| Colorful Technology | 1         | 0.27%   |
| Clevo               | 1         | 0.27%   |
| Biostar             | 1         | 0.27%   |
| AMI                 | 1         | 0.27%   |
| Alienware           | 1         | 0.27%   |
| AAEON               | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 6         | 1.6%    |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 5         | 1.33%   |
| HP ProBook 450 G7                    | 5         | 1.33%   |
| HP EliteBook 8470p                   | 5         | 1.33%   |
| HP EliteBook 840 G3                  | 5         | 1.33%   |
| Dell Latitude E7450                  | 5         | 1.33%   |
| Haier Y11C                           | 4         | 1.06%   |
| Dell Precision WorkStation T7500     | 4         | 1.06%   |
| Dell Latitude E6420                  | 4         | 1.06%   |
| HP ProLiant DL380p Gen8              | 3         | 0.8%    |
| HP ProBook 450 G5                    | 3         | 0.8%    |
| HP EliteBook 840 G2                  | 3         | 0.8%    |
| Haier Y11B                           | 3         | 0.8%    |
| Dell Precision WorkStation T3500     | 3         | 0.8%    |
| Shuttle DS81D                        | 2         | 0.53%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GF00 | 2         | 0.53%   |
| Lenovo ThinkPad E15 Gen 2 20TD000EUE | 2         | 0.53%   |
| Lenovo ThinkBook 15-IML 20RW         | 2         | 0.53%   |
| Lenovo ThinkBook 15-IIL 20SM         | 2         | 0.53%   |
| HP ZBook 15 G3                       | 2         | 0.53%   |
| HP ProDesk 600 G1 SFF                | 2         | 0.53%   |
| HP ProDesk 400 G7 Microtower PC      | 2         | 0.53%   |
| HP ProBook 450 G8 Notebook PC        | 2         | 0.53%   |
| HP ProBook 450 G3                    | 2         | 0.53%   |
| HP ProBook 440 G7                    | 2         | 0.53%   |
| HP Pavilion Notebook                 | 2         | 0.53%   |
| HP Pavilion g6                       | 2         | 0.53%   |
| HP Pavilion dv6                      | 2         | 0.53%   |
| HP Notebook                          | 2         | 0.53%   |
| HP Laptop 15s-fq5xxx                 | 2         | 0.53%   |
| HP Laptop 15-da2xxx                  | 2         | 0.53%   |
| HP ENVY x360 m6 Convertible          | 2         | 0.53%   |
| HP EliteBook Folio 9470m             | 2         | 0.53%   |
| HP EliteBook 850 G6                  | 2         | 0.53%   |
| HP EliteBook 8440p                   | 2         | 0.53%   |
| HP EliteBook 840 G1                  | 2         | 0.53%   |
| HP EliteBook 6930p                   | 2         | 0.53%   |
| HP Compaq 8100 Elite SFF PC          | 2         | 0.53%   |
| HP 650                               | 2         | 0.53%   |
| Gigabyte Z590 UD AC                  | 2         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 44        | 11.7%   |
| HP EliteBook       | 34        | 9.04%   |
| Lenovo ThinkPad    | 28        | 7.45%   |
| HP ProBook         | 28        | 7.45%   |
| Dell Inspiron      | 23        | 6.12%   |
| HP Pavilion        | 14        | 3.72%   |
| Dell Precision     | 14        | 3.72%   |
| HP Laptop          | 11        | 2.93%   |
| HP Compaq          | 11        | 2.93%   |
| Lenovo ThinkBook   | 9         | 2.39%   |
| Dell OptiPlex      | 9         | 2.39%   |
| Dell Vostro        | 8         | 2.13%   |
| Lenovo IdeaPad     | 7         | 1.86%   |
| HP ProDesk         | 7         | 1.86%   |
| Lenovo ThinkCentre | 6         | 1.6%    |
| HP ENVY            | 6         | 1.6%    |
| Unknown            | 6         | 1.6%    |
| HP ProLiant        | 4         | 1.06%   |
| Haier Y11C         | 4         | 1.06%   |
| Acer Aspire        | 4         | 1.06%   |
| Toshiba Satellite  | 3         | 0.8%    |
| Haier Y11B         | 3         | 0.8%    |
| Dell XPS           | 3         | 0.8%    |
| Toshiba PORTEGE    | 2         | 0.53%   |
| Shuttle DS81D      | 2         | 0.53%   |
| Lenovo Yoga        | 2         | 0.53%   |
| Lenovo Legion      | 2         | 0.53%   |
| HP ZBook           | 2         | 0.53%   |
| HP Notebook        | 2         | 0.53%   |
| HP 650             | 2         | 0.53%   |
| Gigabyte Z590      | 2         | 0.53%   |
| Gigabyte Q87M-D2H  | 2         | 0.53%   |
| Gigabyte A520M     | 2         | 0.53%   |
| Fujitsu LIFEBOOK   | 2         | 0.53%   |
| Dell G3            | 2         | 0.53%   |
| ASUS VivoBook      | 2         | 0.53%   |
| ASUS TUF           | 2         | 0.53%   |
| Apple MacBookPro11 | 2         | 0.53%   |
| Acer Veriton       | 2         | 0.53%   |
| Timi TM1613        | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 40        | 10.64%  |
| 2020    | 37        | 9.84%   |
| 2019    | 35        | 9.31%   |
| 2014    | 32        | 8.51%   |
| 2012    | 32        | 8.51%   |
| 2013    | 30        | 7.98%   |
| 2016    | 26        | 6.91%   |
| 2017    | 24        | 6.38%   |
| 2018    | 23        | 6.12%   |
| 2010    | 23        | 6.12%   |
| 2021    | 18        | 4.79%   |
| 2015    | 18        | 4.79%   |
| 2009    | 11        | 2.93%   |
| 2008    | 11        | 2.93%   |
| 2022    | 5         | 1.33%   |
| 2007    | 5         | 1.33%   |
| 2006    | 4         | 1.06%   |
| 2023    | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 268       | 71.28%  |
| Desktop     | 89        | 23.67%  |
| Convertible | 10        | 2.66%   |
| Server      | 4         | 1.06%   |
| Tablet      | 3         | 0.8%    |
| Mini pc     | 2         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 351       | 93.1%   |
| Enabled  | 26        | 6.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 375       | 99.73%  |
| Yes  | 1         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 109       | 28.68%  |
| 16.01-24.0      | 81        | 21.32%  |
| 8.01-16.0       | 75        | 19.74%  |
| 3.01-4.0        | 69        | 18.16%  |
| 32.01-64.0      | 26        | 6.84%   |
| 1.01-2.0        | 8         | 2.11%   |
| 64.01-256.0     | 7         | 1.84%   |
| 24.01-32.0      | 4         | 1.05%   |
| More than 256.0 | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 130       | 31.4%   |
| 1.01-2.0    | 122       | 29.47%  |
| 4.01-8.0    | 68        | 16.43%  |
| 3.01-4.0    | 58        | 14.01%  |
| 8.01-16.0   | 23        | 5.56%   |
| 0.51-1.0    | 8         | 1.93%   |
| 16.01-24.0  | 2         | 0.48%   |
| 32.01-64.0  | 1         | 0.24%   |
| 64.01-256.0 | 1         | 0.24%   |
| Unknown     | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 253       | 65.21%  |
| 2      | 98        | 25.26%  |
| 3      | 17        | 4.38%   |
| 6      | 5         | 1.29%   |
| 5      | 4         | 1.03%   |
| 4      | 4         | 1.03%   |
| 0      | 2         | 0.52%   |
| 13     | 1         | 0.26%   |
| 11     | 1         | 0.26%   |
| 10     | 1         | 0.26%   |
| 9      | 1         | 0.26%   |
| 8      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 265       | 70.29%  |
| Yes       | 112       | 29.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 338       | 89.66%  |
| No        | 39        | 10.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 330       | 87.3%   |
| No        | 48        | 12.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 63.21%  |
| No        | 142       | 36.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Pakistan | 376       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Lahore         | 122       | 31.69%  |
| Karachi        | 88        | 22.86%  |
| Islamabad      | 60        | 15.58%  |
| Rawalpindi     | 26        | 6.75%   |
| Multan         | 10        | 2.6%    |
| Faisalabad     | 10        | 2.6%    |
| Peshawar       | 7         | 1.82%   |
| Mirpur         | 7         | 1.82%   |
| Sargodha       | 4         | 1.04%   |
| Jhelum         | 3         | 0.78%   |
| Gujranwala     | 3         | 0.78%   |
| Bahawalpur     | 3         | 0.78%   |
| Abbottabad     | 3         | 0.78%   |
| Sialkot        | 2         | 0.52%   |
| Quetta         | 2         | 0.52%   |
| Mardan         | 2         | 0.52%   |
| Kamoke         | 2         | 0.52%   |
| Hyderabad      | 2         | 0.52%   |
| Dina           | 2         | 0.52%   |
| Wah            | 1         | 0.26%   |
| Vehari         | 1         | 0.26%   |
| Topi           | 1         | 0.26%   |
| Toba Tek Singh | 1         | 0.26%   |
| Taunsa         | 1         | 0.26%   |
| Tando Allahyar | 1         | 0.26%   |
| Swabi          | 1         | 0.26%   |
| Sukkur         | 1         | 0.26%   |
| Sheikhupura    | 1         | 0.26%   |
| Sahiwal        | 1         | 0.26%   |
| Rahim Yar Khan | 1         | 0.26%   |
| Pindi Gheb     | 1         | 0.26%   |
| Okara          | 1         | 0.26%   |
| Layyah         | 1         | 0.26%   |
| Layari         | 1         | 0.26%   |
| Larkana        | 1         | 0.26%   |
| Kohat          | 1         | 0.26%   |
| Khanewal       | 1         | 0.26%   |
| Hazro City     | 1         | 0.26%   |
| Hassan Abdal   | 1         | 0.26%   |
| Hafizabad      | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 87        | 136    | 16.51%  |
| WDC                          | 76        | 107    | 14.42%  |
| Samsung Electronics          | 64        | 79     | 12.14%  |
| Toshiba                      | 40        | 41     | 7.59%   |
| Hitachi                      | 27        | 36     | 5.12%   |
| Kingston                     | 18        | 20     | 3.42%   |
| Unknown                      | 16        | 19     | 3.04%   |
| SanDisk                      | 16        | 17     | 3.04%   |
| Intel                        | 15        | 21     | 2.85%   |
| SK hynix                     | 14        | 19     | 2.66%   |
| Micron Technology            | 12        | 16     | 2.28%   |
| Transcend                    | 10        | 10     | 1.9%    |
| HGST                         | 10        | 12     | 1.9%    |
| Lexar                        | 9         | 12     | 1.71%   |
| HS-SSD-E100                  | 9         | 11     | 1.71%   |
| Hewlett-Packard              | 9         | 21     | 1.71%   |
| A-DATA Technology            | 9         | 10     | 1.71%   |
| LITEON                       | 8         | 9      | 1.52%   |
| Silicon Motion               | 7         | 7      | 1.33%   |
| LITEONIT                     | 7         | 10     | 1.33%   |
| KIOXIA                       | 6         | 6      | 1.14%   |
| Hajaan                       | 6         | 9      | 1.14%   |
| Crucial                      | 6         | 7      | 1.14%   |
| China                        | 5         | 7      | 0.95%   |
| Apple                        | 5         | 6      | 0.95%   |
| SPCC                         | 3         | 3      | 0.57%   |
| Maxtor                       | 3         | 3      | 0.57%   |
| LaCie                        | 3         | 3      | 0.57%   |
| Netac                        | 2         | 2      | 0.38%   |
| Fujitsu                      | 2         | 2      | 0.38%   |
| ZTE                          | 1         | 1      | 0.19%   |
| Vaseky                       | 1         | 1      | 0.19%   |
| Toshiba America Info Systems | 1         | 1      | 0.19%   |
| Team                         | 1         | 1      | 0.19%   |
| Supersonic                   | 1         | 1      | 0.19%   |
| PNY                          | 1         | 2      | 0.19%   |
| Phison Electronics           | 1         | 1      | 0.19%   |
| Phison                       | 1         | 2      | 0.19%   |
| PHD 3.0                      | 1         | 1      | 0.19%   |
| MARSHAL                      | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 8         | 1.39%   |
| Toshiba MQ04ABF100 1TB                | 7         | 1.22%   |
| Seagate ST3000NXCLAR3000 3TB          | 7         | 1.22%   |
| WDC WD10SPZX-60Z10T0 1TB              | 6         | 1.04%   |
| Toshiba MQ01ABF050 500GB              | 6         | 1.04%   |
| HP MB2000EBZQC 2TB                    | 6         | 1.04%   |
| Hajaan SSD 256G                       | 6         | 1.04%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 5         | 0.87%   |
| Samsung SSD PM830 2.5 7mm 256GB       | 5         | 0.87%   |
| Samsung MZALQ512HALU-000L1 512GB      | 5         | 0.87%   |
| Lexar 256GB SSD                       | 5         | 0.87%   |
| Unknown MMC Card  32GB                | 4         | 0.69%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 4         | 0.69%   |
| HS-SSD-E100 128G                      | 4         | 0.69%   |
| Hitachi HTS545050A7E380 500GB         | 4         | 0.69%   |
| WDC WD10SPZX-75Z10T3 1TB              | 3         | 0.52%   |
| WDC PC SN530 NVMe 256GB               | 3         | 0.52%   |
| Toshiba MQ01ACF050 500GB              | 3         | 0.52%   |
| Silicon Motion NVMe SSD Drive 512GB   | 3         | 0.52%   |
| Seagate ST9250311CS 250GB             | 3         | 0.52%   |
| Seagate ST8000DM004-2CX188 8TB        | 3         | 0.52%   |
| Seagate ST6000NM0024 6TB              | 3         | 0.52%   |
| Seagate ST500LM000-1EJ162 500GB       | 3         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 0.52%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD  | 3         | 0.52%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB SSD | 3         | 0.52%   |
| LITEON CS1-SP32 32GB SSD              | 3         | 0.52%   |
| LaCie Rugged USB-C 2TB                | 3         | 0.52%   |
| Intel SSDSA2M080G2GN 80GB             | 3         | 0.52%   |
| Hitachi HTS545032B9A300 320GB         | 3         | 0.52%   |
| Hitachi HTS543225A7A384 250GB         | 3         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 0.35%   |
| WDC WD5002ABYS-02B1B0 500GB           | 2         | 0.35%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 0.35%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 2         | 0.35%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2         | 0.35%   |
| WDC WD3200BEKX-75B7WT0 320GB          | 2         | 0.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2         | 0.35%   |
| WDC WD10SPZX-24Z10 1TB                | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 136    | 35.95%  |
| WDC                 | 64        | 87     | 26.45%  |
| Toshiba             | 33        | 34     | 13.64%  |
| Hitachi             | 27        | 36     | 11.16%  |
| HGST                | 10        | 12     | 4.13%   |
| Hewlett-Packard     | 7         | 18     | 2.89%   |
| Samsung Electronics | 6         | 7      | 2.48%   |
| Maxtor              | 3         | 3      | 1.24%   |
| Fujitsu             | 2         | 2      | 0.83%   |
| Unknown             | 1         | 1      | 0.41%   |
| MARSHAL             | 1         | 1      | 0.41%   |
| KESU                | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 41     | 22.02%  |
| Kingston            | 13        | 15     | 7.74%   |
| SanDisk             | 11        | 11     | 6.55%   |
| SK hynix            | 9         | 14     | 5.36%   |
| WDC                 | 8         | 11     | 4.76%   |
| LITEON              | 8         | 9      | 4.76%   |
| Micron Technology   | 7         | 9      | 4.17%   |
| LITEONIT            | 7         | 10     | 4.17%   |
| Lexar               | 7         | 9      | 4.17%   |
| Intel               | 7         | 8      | 4.17%   |
| A-DATA Technology   | 7         | 8      | 4.17%   |
| Hajaan              | 6         | 9      | 3.57%   |
| Crucial             | 6         | 7      | 3.57%   |
| Transcend           | 5         | 5      | 2.98%   |
| China               | 5         | 7      | 2.98%   |
| Toshiba             | 4         | 4      | 2.38%   |
| SPCC                | 3         | 3      | 1.79%   |
| HS-SSD-E100         | 3         | 3      | 1.79%   |
| Hewlett-Packard     | 2         | 3      | 1.19%   |
| Apple               | 2         | 2      | 1.19%   |
| Vaseky              | 1         | 1      | 0.6%    |
| Team                | 1         | 1      | 0.6%    |
| Supersonic          | 1         | 1      | 0.6%    |
| PNY                 | 1         | 2      | 0.6%    |
| PHD 3.0             | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| Gritronix           | 1         | 1      | 0.6%    |
| Gigabyte Technology | 1         | 2      | 0.6%    |
| Emtec               | 1         | 1      | 0.6%    |
| Biostar             | 1         | 1      | 0.6%    |
| Apacer              | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 202       | 338    | 43.53%  |
| SSD     | 142       | 201    | 30.6%   |
| NVMe    | 89        | 112    | 19.18%  |
| Unknown | 18        | 24     | 3.88%   |
| MMC     | 13        | 16     | 2.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 294       | 533    | 71.36%  |
| NVMe | 89        | 112    | 21.6%   |
| SAS  | 16        | 30     | 3.88%   |
| MMC  | 13        | 16     | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 223       | 348    | 64.08%  |
| 0.51-1.0   | 97        | 113    | 27.87%  |
| 1.01-2.0   | 14        | 39     | 4.02%   |
| 2.01-3.0   | 8         | 16     | 2.3%    |
| 4.01-10.0  | 4         | 21     | 1.15%   |
| 3.01-4.0   | 2         | 2      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 141       | 35.43%  |
| 251-500        | 92        | 23.12%  |
| 51-100         | 55        | 13.82%  |
| 501-1000       | 37        | 9.3%    |
| 1-20           | 22        | 5.53%   |
| 21-50          | 20        | 5.03%   |
| 1001-2000      | 17        | 4.27%   |
| Unknown        | 8         | 2.01%   |
| More than 3000 | 4         | 1.01%   |
| 2001-3000      | 2         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 156       | 38.05%  |
| 21-50          | 102       | 24.88%  |
| 101-250        | 53        | 12.93%  |
| 51-100         | 52        | 12.68%  |
| 251-500        | 22        | 5.37%   |
| 501-1000       | 11        | 2.68%   |
| Unknown        | 8         | 1.95%   |
| 1001-2000      | 4         | 0.98%   |
| More than 3000 | 1         | 0.24%   |
| 2001-3000      | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 4.17%   |
| Seagate ST2000DM008-2FR1 2TB                  | 2         | 2      | 4.17%   |
| Hewlett-Packard MB2000EBZQC 2TB               | 2         | 3      | 4.17%   |
| Crucial CT525MX300SSD1 528GB                  | 2         | 2      | 4.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD              | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-75U6AA0 500GB                  | 1         | 1      | 2.08%   |
| WDC WD2500HHTZ-04N21V0 250GB                  | 1         | 1      | 2.08%   |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 2.08%   |
| WDC WD2500AAKS-00F0A0 250GB                   | 1         | 1      | 2.08%   |
| WDC WD20EZRZ-00Z5HB0 2TB                      | 1         | 1      | 2.08%   |
| WDC WD1600AAJS-22L7A0 160GB                   | 1         | 1      | 2.08%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 2.08%   |
| WDC WD10JPVT-60A1YT0 1TB                      | 1         | 1      | 2.08%   |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 2.08%   |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 2.08%   |
| Supersonic SSD 256 256GB                      | 1         | 1      | 2.08%   |
| SK hynix PC401 NVMe 256GB                     | 1         | 1      | 2.08%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 2.08%   |
| Seagate ST980411ASG 80GB                      | 1         | 2      | 2.08%   |
| Seagate ST9750420AS 752GB                     | 1         | 1      | 2.08%   |
| Seagate ST500LM021-1KJ152 500GB               | 1         | 1      | 2.08%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 2.08%   |
| Seagate ST3500418AS 500GB                     | 1         | 1      | 2.08%   |
| Seagate ST3160215AS 160GB                     | 1         | 1      | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 2      | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 2.08%   |
| Seagate ST1000DM010-2EP102 1TB                | 1         | 1      | 2.08%   |
| Seagate ST1000DM003-1SB10C 1TB                | 1         | 1      | 2.08%   |
| Samsung Electronics SP2004C 200GB             | 1         | 1      | 2.08%   |
| Samsung Electronics HD080HJ 80GB              | 1         | 1      | 2.08%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 2.08%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD | 1         | 1      | 2.08%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 2.08%   |
| Intel SSDSC2BF180A4H 180GB                    | 1         | 1      | 2.08%   |
| Intel SSDSA2M080G2GN 80GB                     | 1         | 1      | 2.08%   |
| HS-SSD-E100 SSD 1024G                         | 1         | 1      | 2.08%   |
| Hitachi HUA723020ALA640 2TB                   | 1         | 2      | 2.08%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 2.08%   |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 15     | 26.09%  |
| WDC                 | 10        | 12     | 21.74%  |
| Hitachi             | 5         | 6      | 10.87%  |
| Intel               | 3         | 3      | 6.52%   |
| Toshiba             | 2         | 2      | 4.35%   |
| SK hynix            | 2         | 2      | 4.35%   |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| Hewlett-Packard     | 2         | 3      | 4.35%   |
| Crucial             | 2         | 2      | 4.35%   |
| Supersonic          | 1         | 1      | 2.17%   |
| HS-SSD-E100         | 1         | 1      | 2.17%   |
| Gritronix           | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 15     | 36.36%  |
| WDC                 | 10        | 11     | 30.3%   |
| Hitachi             | 5         | 6      | 15.15%  |
| Toshiba             | 2         | 2      | 6.06%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| Hewlett-Packard     | 2         | 3      | 6.06%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 39     | 66.67%  |
| SSD  | 12        | 13     | 30.77%  |
| NVMe | 1         | 1      | 2.56%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 239       | 399    | 59.31%  |
| Works    | 127       | 239    | 31.51%  |
| Malfunc  | 37        | 53     | 9.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 314       | 70.72%  |
| Samsung Electronics          | 25        | 5.63%   |
| AMD                          | 25        | 5.63%   |
| SanDisk                      | 11        | 2.48%   |
| Silicon Motion               | 8         | 1.8%    |
| LSI Logic / Symbios Logic    | 8         | 1.8%    |
| KIOXIA                       | 8         | 1.8%    |
| SK hynix                     | 5         | 1.13%   |
| Micron Technology            | 5         | 1.13%   |
| Kingston Technology Company  | 5         | 1.13%   |
| Transcend                    | 4         | 0.9%    |
| Hewlett-Packard              | 4         | 0.9%    |
| Toshiba America Info Systems | 3         | 0.68%   |
| Apple                        | 3         | 0.68%   |
| Phison Electronics           | 2         | 0.45%   |
| Nvidia                       | 2         | 0.45%   |
| Marvell Technology Group     | 2         | 0.45%   |
| ASMedia Technology           | 2         | 0.45%   |
| Shenzhen Longsys Electronics | 1         | 0.23%   |
| Realtek Semiconductor        | 1         | 0.23%   |
| Netac Technology             | 1         | 0.23%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.23%   |
| Lenovo                       | 1         | 0.23%   |
| Broadcom / LSI               | 1         | 0.23%   |
| ADATA Technology             | 1         | 0.23%   |
| Adaptec                      | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 52        | 10.18%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 27        | 5.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 4.11%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 3.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 3.52%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 15        | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 2.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11        | 2.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 10        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 1.57%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 8         | 1.57%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.37%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6         | 1.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.98%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 0.98%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 4         | 0.78%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.78%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 0.78%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 4         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 0.78%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 4         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.59%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.59%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 3         | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 273       | 57.35%  |
| NVMe | 89        | 18.7%   |
| RAID | 59        | 12.39%  |
| IDE  | 40        | 8.4%    |
| SCSI | 9         | 1.89%   |
| SAS  | 6         | 1.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 347       | 92.29%  |
| AMD    | 29        | 7.71%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 13        | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 12        | 3.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 2.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 2.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 2.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 2.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 7         | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 1.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 1.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 1.59%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 5         | 1.33%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 1.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 5         | 1.33%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 4         | 1.06%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 4         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 4         | 1.06%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 1.06%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 1.06%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4         | 1.06%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 3         | 0.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.8%    |
| Intel Core i7-8850H CPU @ 2.60GHz       | 3         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 0.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 3         | 0.8%    |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 3         | 0.8%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 0.8%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 0.8%    |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3         | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 0.8%    |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3         | 0.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3         | 0.8%    |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 136       | 36.17%  |
| Intel Core i7        | 91        | 24.2%   |
| Other                | 34        | 9.04%   |
| Intel Xeon           | 21        | 5.59%   |
| Intel Core i3        | 18        | 4.79%   |
| Intel Core 2 Duo     | 16        | 4.26%   |
| AMD Ryzen 7          | 10        | 2.66%   |
| Intel Celeron        | 8         | 2.13%   |
| Intel Atom           | 5         | 1.33%   |
| AMD Ryzen 5          | 5         | 1.33%   |
| Intel Pentium        | 4         | 1.06%   |
| Intel Core m3        | 4         | 1.06%   |
| Intel Core M         | 3         | 0.8%    |
| Intel Core 2 Quad    | 2         | 0.53%   |
| Intel Core 2         | 2         | 0.53%   |
| AMD Athlon II X2     | 2         | 0.53%   |
| AMD A6               | 2         | 0.53%   |
| Intel Pentium Dual   | 1         | 0.27%   |
| Intel Genuine        | 1         | 0.27%   |
| Intel Core 2 Extreme | 1         | 0.27%   |
| AMD Ryzen 9          | 1         | 0.27%   |
| AMD Ryzen 3          | 1         | 0.27%   |
| AMD PRO A8           | 1         | 0.27%   |
| AMD G                | 1         | 0.27%   |
| AMD FX               | 1         | 0.27%   |
| AMD E                | 1         | 0.27%   |
| AMD Athlon X4        | 1         | 0.27%   |
| AMD A8               | 1         | 0.27%   |
| AMD A4               | 1         | 0.27%   |
| AMD A12              | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 182       | 48.15%  |
| 4      | 144       | 38.1%   |
| 8      | 20        | 5.29%   |
| 6      | 20        | 5.29%   |
| 12     | 5         | 1.32%   |
| 16     | 2         | 0.53%   |
| 10     | 2         | 0.53%   |
| 1      | 2         | 0.53%   |
| 14     | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 366       | 97.08%  |
| 2      | 11        | 2.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 296       | 78.31%  |
| 1      | 82        | 21.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 373       | 98.94%  |
| Unknown        | 3         | 0.8%    |
| 32-bit         | 1         | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 30.87%  |
| 0x206a7    | 24        | 6.12%   |
| 0x306a9    | 20        | 5.1%    |
| 0x806c1    | 19        | 4.85%   |
| 0x806ec    | 18        | 4.59%   |
| 0x406e3    | 17        | 4.34%   |
| 0x806e9    | 16        | 4.08%   |
| 0x40651    | 14        | 3.57%   |
| 0x806ea    | 13        | 3.32%   |
| 0x306d4    | 13        | 3.32%   |
| 0x306c3    | 13        | 3.32%   |
| 0x1067a    | 11        | 2.81%   |
| 0x20655    | 10        | 2.55%   |
| 0x706e5    | 6         | 1.53%   |
| 0x206c2    | 6         | 1.53%   |
| 0x206d7    | 5         | 1.28%   |
| 0x906ea    | 4         | 1.02%   |
| 0x6f6      | 4         | 1.02%   |
| 0x506e3    | 4         | 1.02%   |
| 0x30678    | 4         | 1.02%   |
| 0xa0655    | 3         | 0.77%   |
| 0xa0652    | 3         | 0.77%   |
| 0x406c4    | 3         | 0.77%   |
| 0x106a5    | 3         | 0.77%   |
| 0x10676    | 3         | 0.77%   |
| 0x0a50000c | 3         | 0.77%   |
| 0x906e9    | 2         | 0.51%   |
| 0x6fd      | 2         | 0.51%   |
| 0x20652    | 2         | 0.51%   |
| 0x08701021 | 2         | 0.51%   |
| 0x08608103 | 2         | 0.51%   |
| 0x0600111f | 2         | 0.51%   |
| 0x05000119 | 2         | 0.51%   |
| 0xa0671    | 1         | 0.26%   |
| 0xa0660    | 1         | 0.26%   |
| 0x906a4    | 1         | 0.26%   |
| 0x906a3    | 1         | 0.26%   |
| 0x806eb    | 1         | 0.26%   |
| 0x706a1    | 1         | 0.26%   |
| 0x6fb      | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 20.69%  |
| Haswell          | 40        | 10.61%  |
| SandyBridge      | 38        | 10.08%  |
| IvyBridge        | 32        | 8.49%   |
| TigerLake        | 28        | 7.43%   |
| Skylake          | 26        | 6.9%    |
| Westmere         | 25        | 6.63%   |
| Broadwell        | 19        | 5.04%   |
| Penryn           | 17        | 4.51%   |
| Silvermont       | 10        | 2.65%   |
| IceLake          | 7         | 1.86%   |
| Core             | 7         | 1.86%   |
| CometLake        | 7         | 1.86%   |
| Zen 2            | 6         | 1.59%   |
| Nehalem          | 6         | 1.59%   |
| Unknown          | 6         | 1.59%   |
| Zen 3            | 5         | 1.33%   |
| Zen+             | 3         | 0.8%    |
| Steamroller      | 3         | 0.8%    |
| Piledriver       | 2         | 0.53%   |
| K10              | 2         | 0.53%   |
| Bobcat           | 2         | 0.53%   |
| Alderlake Hybrid | 2         | 0.53%   |
| Zen              | 1         | 0.27%   |
| P6               | 1         | 0.27%   |
| K10 Llano        | 1         | 0.27%   |
| Jaguar           | 1         | 0.27%   |
| Goldmont plus    | 1         | 0.27%   |
| Excavator        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 291       | 64.96%  |
| Nvidia                     | 85        | 18.97%  |
| AMD                        | 69        | 15.4%   |
| Matrox Electronics Systems | 3         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 5.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 5.24%   |
| Intel UHD Graphics 620                                                                   | 20        | 4.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 4.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 4.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 4.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 4.15%   |
| Intel HD Graphics 620                                                                    | 17        | 3.71%   |
| Intel HD Graphics 5500                                                                   | 16        | 3.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.31%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1.09%   |
| Nvidia GP108M [GeForce MX230]                                                            | 5         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.09%   |
| Intel HD Graphics 530                                                                    | 5         | 1.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.09%   |
| Intel HD Graphics 615                                                                    | 4         | 0.87%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.66%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 0.66%   |
| Intel HD Graphics 5300                                                                   | 3         | 0.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.66%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.66%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.44%   |
| Nvidia GT218 [GeForce 310]                                                               | 2         | 0.44%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.44%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 224       | 58.95%  |
| Intel + Nvidia | 43        | 11.32%  |
| 1 x AMD        | 42        | 11.05%  |
| 1 x Nvidia     | 36        | 9.47%   |
| Intel + AMD    | 22        | 5.79%   |
| AMD + Nvidia   | 4         | 1.05%   |
| 1 x Matrox     | 3         | 0.79%   |
| Other          | 2         | 0.53%   |
| 2 x Nvidia     | 2         | 0.53%   |
| 2 x AMD        | 2         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 329       | 85.68%  |
| Proprietary | 42        | 10.94%  |
| Unknown     | 13        | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 274       | 71.54%  |
| 1.01-2.0   | 48        | 12.53%  |
| 0.01-0.5   | 24        | 6.27%   |
| 0.51-1.0   | 16        | 4.18%   |
| 3.01-4.0   | 14        | 3.66%   |
| 7.01-8.0   | 2         | 0.52%   |
| 5.01-6.0   | 2         | 0.52%   |
| 8.01-16.0  | 2         | 0.52%   |
| 2.01-3.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 68        | 18.78%  |
| AU Optronics            | 53        | 14.64%  |
| Chimei Innolux          | 51        | 14.09%  |
| BOE                     | 41        | 11.33%  |
| Samsung Electronics     | 26        | 7.18%   |
| Hewlett-Packard         | 24        | 6.63%   |
| Dell                    | 24        | 6.63%   |
| Chi Mei Optoelectronics | 9         | 2.49%   |
| Lenovo                  | 7         | 1.93%   |
| Apple                   | 6         | 1.66%   |
| Acer                    | 6         | 1.66%   |
| InfoVision              | 5         | 1.38%   |
| Unknown                 | 4         | 1.1%    |
| Sharp                   | 4         | 1.1%    |
| Goldstar                | 4         | 1.1%    |
| NEC Computers           | 3         | 0.83%   |
| KDC                     | 3         | 0.83%   |
| ViewSonic               | 2         | 0.55%   |
| Sony                    | 2         | 0.55%   |
| PANDA                   | 2         | 0.55%   |
| MStar                   | 2         | 0.55%   |
| LGD                     | 2         | 0.55%   |
| LG Philips              | 2         | 0.55%   |
| Hitachi                 | 2         | 0.55%   |
| BenQ                    | 2         | 0.55%   |
| Planar                  | 1         | 0.28%   |
| Philips                 | 1         | 0.28%   |
| LPL                     | 1         | 0.28%   |
| LED                     | 1         | 0.28%   |
| HannStar                | 1         | 0.28%   |
| DENON                   | 1         | 0.28%   |
| CSO                     | 1         | 0.28%   |
| AOC                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 10        | 2.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 1.36%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 4         | 1.09%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 0.82%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.82%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 3         | 0.82%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 3         | 0.82%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 3         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 3         | 0.82%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.54%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch     | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 2         | 0.54%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 0.54%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD052F 1920x1080 344x194mm 15.5-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.54%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 2         | 0.54%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.54%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 0.54%   |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch              | 2         | 0.54%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.54%   |
| Dell P2217H DELA0D9 1920x1080 480x270mm 21.7-inch                     | 2         | 0.54%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 0.54%   |
| Dell P2212H DELA07E 1920x1080 477x268mm 21.5-inch                     | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch       | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 155       | 44.41%  |
| 1366x768 (WXGA)    | 108       | 30.95%  |
| 1600x900 (HD+)     | 13        | 3.72%   |
| 3840x2160 (4K)     | 11        | 3.15%   |
| 1680x1050 (WSXGA+) | 11        | 3.15%   |
| 1280x1024 (SXGA)   | 9         | 2.58%   |
| 1920x1200 (WUXGA)  | 6         | 1.72%   |
| 1280x800 (WXGA)    | 6         | 1.72%   |
| 1440x900 (WXGA+)   | 5         | 1.43%   |
| 2880x1800          | 4         | 1.15%   |
| 1024x768 (XGA)     | 4         | 1.15%   |
| 3440x1440          | 3         | 0.86%   |
| 2560x1440 (QHD)    | 3         | 0.86%   |
| 2560x1600          | 2         | 0.57%   |
| 2288x1287          | 2         | 0.57%   |
| Unknown            | 2         | 0.57%   |
| 3640x1920          | 1         | 0.29%   |
| 3520x1080          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 1600x1200          | 1         | 0.29%   |
| 1360x768           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 136       | 37.78%  |
| 14      | 50        | 13.89%  |
| 13      | 46        | 12.78%  |
| 17      | 19        | 5.28%   |
| 24      | 17        | 4.72%   |
| 21      | 17        | 4.72%   |
| Unknown | 12        | 3.33%   |
| 23      | 10        | 2.78%   |
| 12      | 9         | 2.5%    |
| 19      | 7         | 1.94%   |
| 22      | 6         | 1.67%   |
| 11      | 6         | 1.67%   |
| 27      | 5         | 1.39%   |
| 40      | 3         | 0.83%   |
| 18      | 3         | 0.83%   |
| 142     | 2         | 0.56%   |
| 72      | 2         | 0.56%   |
| 52      | 2         | 0.56%   |
| 20      | 2         | 0.56%   |
| 16      | 2         | 0.56%   |
| 84      | 1         | 0.28%   |
| 31      | 1         | 0.28%   |
| 26      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 213       | 59.5%   |
| 201-300        | 38        | 10.61%  |
| 501-600        | 32        | 8.94%   |
| 401-500        | 31        | 8.66%   |
| 351-400        | 21        | 5.87%   |
| Unknown        | 12        | 3.35%   |
| 801-900        | 3         | 0.84%   |
| 1501-2000      | 3         | 0.84%   |
| More than 2000 | 2         | 0.56%   |
| 1001-1500      | 2         | 0.56%   |
| 601-700        | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 280       | 82.6%   |
| 16/10   | 30        | 8.85%   |
| Unknown | 12        | 3.54%   |
| 5/4     | 9         | 2.65%   |
| 4/3     | 5         | 1.47%   |
| 1.00    | 2         | 0.59%   |
| 3/2     | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 136       | 37.88%  |
| 81-90          | 75        | 20.89%  |
| 201-250        | 40        | 11.14%  |
| 71-80          | 19        | 5.29%   |
| 151-200        | 14        | 3.9%    |
| 121-130        | 12        | 3.34%   |
| Unknown        | 12        | 3.34%   |
| 61-70          | 9         | 2.51%   |
| 141-150        | 8         | 2.23%   |
| More than 1000 | 7         | 1.95%   |
| 51-60          | 6         | 1.67%   |
| 301-350        | 5         | 1.39%   |
| 251-300        | 5         | 1.39%   |
| 501-1000       | 3         | 0.84%   |
| 91-100         | 3         | 0.84%   |
| 131-140        | 2         | 0.56%   |
| 351-500        | 1         | 0.28%   |
| 41-50          | 1         | 0.28%   |
| 111-120        | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 139       | 39.04%  |
| 101-120       | 112       | 31.46%  |
| 51-100        | 67        | 18.82%  |
| 161-240       | 13        | 3.65%   |
| Unknown       | 12        | 3.37%   |
| More than 240 | 7         | 1.97%   |
| 1-50          | 6         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 327       | 85.6%   |
| 2     | 31        | 8.12%   |
| 0     | 23        | 6.02%   |
| 3     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 243       | 40.1%   |
| Realtek Semiconductor           | 178       | 29.37%  |
| Broadcom                        | 52        | 8.58%   |
| Qualcomm Atheros                | 35        | 5.78%   |
| Ralink Technology               | 15        | 2.48%   |
| Broadcom Limited                | 12        | 1.98%   |
| MediaTek                        | 10        | 1.65%   |
| Ralink                          | 5         | 0.83%   |
| Marvell Technology Group        | 5         | 0.83%   |
| Hewlett-Packard                 | 5         | 0.83%   |
| ASIX Electronics                | 5         | 0.83%   |
| Sierra Wireless                 | 4         | 0.66%   |
| Samsung Electronics             | 4         | 0.66%   |
| Qualcomm Atheros Communications | 4         | 0.66%   |
| D-Link                          | 4         | 0.66%   |
| ZTE WCDMA Technologies MSM      | 3         | 0.5%    |
| TP-Link                         | 3         | 0.5%    |
| Huawei Technologies             | 3         | 0.5%    |
| Xiaomi                          | 2         | 0.33%   |
| Spreadtrum Communications       | 2         | 0.33%   |
| Nvidia                          | 2         | 0.33%   |
| Dell                            | 2         | 0.33%   |
| Zoom Telephonics                | 1         | 0.17%   |
| VIA Technologies                | 1         | 0.17%   |
| Qualcomm                        | 1         | 0.17%   |
| QLogic                          | 1         | 0.17%   |
| OPPO Electronics                | 1         | 0.17%   |
| JMicron Technology              | 1         | 0.17%   |
| Emulex                          | 1         | 0.17%   |
| 3Com                            | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 16.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 37        | 5.02%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 3.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 2.85%   |
| Intel Wireless 7265                                               | 17        | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 2.17%   |
| Intel Wireless 8265 / 8275                                        | 15        | 2.04%   |
| Intel Wireless 7260                                               | 14        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 1.9%    |
| Intel Wireless 3165                                               | 13        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.63%   |
| Intel Wireless 8260                                               | 12        | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.49%   |
| Ralink MT7601U Wireless Adapter                                   | 10        | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6         | 0.81%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.81%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.68%   |
| MediaTek Wiko U316AT                                              | 5         | 0.68%   |
| Intel Wireless 3160                                               | 5         | 0.68%   |
| Intel Ultimate N WiFi Link 5300                                   | 5         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.68%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 188       | 53.87%  |
| Realtek Semiconductor           | 51        | 14.61%  |
| Qualcomm Atheros                | 32        | 9.17%   |
| Broadcom                        | 26        | 7.45%   |
| Ralink Technology               | 15        | 4.3%    |
| Broadcom Limited                | 7         | 2.01%   |
| Ralink                          | 5         | 1.43%   |
| Sierra Wireless                 | 4         | 1.15%   |
| Qualcomm Atheros Communications | 4         | 1.15%   |
| MediaTek                        | 4         | 1.15%   |
| D-Link                          | 4         | 1.15%   |
| TP-Link                         | 3         | 0.86%   |
| Marvell Technology Group        | 2         | 0.57%   |
| Hewlett-Packard                 | 2         | 0.57%   |
| Dell                            | 2         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 23        | 6.53%   |
| Intel Wireless 7265                                                  | 17        | 4.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 16        | 4.55%   |
| Intel Wireless 8265 / 8275                                           | 15        | 4.26%   |
| Intel Wireless 7260                                                  | 14        | 3.98%   |
| Intel Wireless 3165                                                  | 13        | 3.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 13        | 3.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 12        | 3.41%   |
| Intel Wireless 8260                                                  | 12        | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 11        | 3.13%   |
| Ralink MT7601U Wireless Adapter                                      | 10        | 2.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8         | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7         | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 6         | 1.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 6         | 1.7%    |
| Intel Centrino Advanced-N 6200                                       | 6         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 1.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 1.42%   |
| Intel Wireless 3160                                                  | 5         | 1.42%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 1.42%   |
| Intel Centrino Ultimate-N 6300                                       | 5         | 1.42%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.42%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.14%   |
| Intel Wi-Fi 6 AX200                                                  | 4         | 1.14%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 1.14%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 4         | 1.14%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 3         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 0.85%   |
| Intel Wireless-AC 9260                                               | 3         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 0.85%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.85%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 3         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 152       | 40.64%  |
| Intel                      | 146       | 39.04%  |
| Broadcom                   | 27        | 7.22%   |
| MediaTek                   | 6         | 1.6%    |
| Qualcomm Atheros           | 5         | 1.34%   |
| Broadcom Limited           | 5         | 1.34%   |
| ASIX Electronics           | 5         | 1.34%   |
| Samsung Electronics        | 4         | 1.07%   |
| ZTE WCDMA Technologies MSM | 3         | 0.8%    |
| Marvell Technology Group   | 3         | 0.8%    |
| Huawei Technologies        | 3         | 0.8%    |
| Xiaomi                     | 2         | 0.53%   |
| Spreadtrum Communications  | 2         | 0.53%   |
| Nvidia                     | 2         | 0.53%   |
| Hewlett-Packard            | 2         | 0.53%   |
| VIA Technologies           | 1         | 0.27%   |
| Qualcomm                   | 1         | 0.27%   |
| QLogic                     | 1         | 0.27%   |
| OPPO Electronics           | 1         | 0.27%   |
| JMicron Technology         | 1         | 0.27%   |
| Emulex                     | 1         | 0.27%   |
| 3Com                       | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 31.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 37        | 9.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 5.48%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 3.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 3.66%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 2.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 2.35%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 2.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 2.09%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.83%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 1.57%   |
| MediaTek Wiko U316AT                                              | 5         | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.31%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.31%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.04%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 3         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.78%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 3         | 0.78%   |
| Spreadtrum meizu C9                                               | 2         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.52%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.52%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 2         | 0.52%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.52%   |
| Huawei E353/E3131                                                 | 2         | 0.52%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 2         | 0.52%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 2         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 339       | 50.45%  |
| WiFi     | 331       | 49.26%  |
| Modem    | 2         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 279       | 74.4%   |
| Ethernet | 96        | 25.6%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 258       | 68.07%  |
| 1     | 101       | 26.65%  |
| 0     | 7         | 1.85%   |
| 3     | 6         | 1.58%   |
| 4     | 5         | 1.32%   |
| 8     | 1         | 0.26%   |
| 6     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 350       | 91.62%  |
| Yes  | 32        | 8.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 55.69%  |
| Realtek Semiconductor           | 29        | 11.79%  |
| Qualcomm Atheros Communications | 22        | 8.94%   |
| Cambridge Silicon Radio         | 16        | 6.5%    |
| Broadcom                        | 15        | 6.1%    |
| Dell                            | 6         | 2.44%   |
| Foxconn / Hon Hai               | 5         | 2.03%   |
| Ralink                          | 3         | 1.22%   |
| Apple                           | 3         | 1.22%   |
| IMC Networks                    | 2         | 0.81%   |
| Hewlett-Packard                 | 2         | 0.81%   |
| Realtek                         | 1         | 0.41%   |
| Ralink Technology               | 1         | 0.41%   |
| Marvell Semiconductor           | 1         | 0.41%   |
| Lite-On Technology              | 1         | 0.41%   |
| Askey Computer                  | 1         | 0.41%   |
| AboCom Systems                  | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 70        | 28.46%  |
| Intel AX201 Bluetooth                                                               | 29        | 11.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 9.35%   |
| Realtek Bluetooth Radio                                                             | 19        | 7.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 6.5%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 4.88%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 3.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.44%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 2.03%   |
| Intel AX200 Bluetooth                                                               | 4         | 1.63%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.22%   |
| Intel Bluetooth Device                                                              | 3         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.81%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.81%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.81%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.81%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.81%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.41%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.41%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.41%   |
| Ralink CSR BS8510                                                                   | 1         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.41%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.41%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.41%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.41%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.41%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.41%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.41%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.41%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.41%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 335       | 73.79%  |
| Nvidia                 | 48        | 10.57%  |
| AMD                    | 48        | 10.57%  |
| Generalplus Technology | 6         | 1.32%   |
| Logitech               | 4         | 0.88%   |
| C-Media Electronics    | 3         | 0.66%   |
| JMTek                  | 2         | 0.44%   |
| Apple                  | 2         | 0.44%   |
| Texas Instruments      | 1         | 0.22%   |
| Realtek Semiconductor  | 1         | 0.22%   |
| OPPO Electronics       | 1         | 0.22%   |
| FIFINE 683 Microphone  | 1         | 0.22%   |
| Dell                   | 1         | 0.22%   |
| Creative Labs          | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 62        | 11.59%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33        | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30        | 5.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 5.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 3.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 3.55%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 3.55%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 3.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 3.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 3.18%   |
| Nvidia High Definition Audio Controller                                    | 11        | 2.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11        | 2.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 2.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 1.5%    |
| AMD FCH Azalia Controller                                                  | 7         | 1.31%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6         | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.93%   |
| Generalplus Technology USB Audio Device                                    | 5         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.75%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.56%   |
| Logitech Headset H340                                                      | 3         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 31.05%  |
| SK hynix            | 64        | 25.81%  |
| Micron Technology   | 29        | 11.69%  |
| A-DATA Technology   | 15        | 6.05%   |
| Kingston            | 11        | 4.44%   |
| Crucial             | 8         | 3.23%   |
| Transcend           | 7         | 2.82%   |
| Unknown             | 6         | 2.42%   |
| Team                | 5         | 2.02%   |
| Lexar               | 5         | 2.02%   |
| Elpida              | 4         | 1.61%   |
| Unknown (2C0B)      | 2         | 0.81%   |
| Spectek             | 2         | 0.81%   |
| Ramaxel Technology  | 2         | 0.81%   |
| Nanya Technology    | 2         | 0.81%   |
| Unknown (768A)      | 1         | 0.4%    |
| Unknown (0x0BF7)    | 1         | 0.4%    |
| TwinMOS             | 1         | 0.4%    |
| Toshiba-0098        | 1         | 0.4%    |
| S                   | 1         | 0.4%    |
| Patriot             | 1         | 0.4%    |
| Hikvision           | 1         | 0.4%    |
| H                   | 1         | 0.4%    |
| Axiom               | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 2.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 5         | 1.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 1.81%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s               | 5         | 1.81%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.09%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 1.09%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 1.09%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 3         | 1.09%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s         | 3         | 1.09%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s              | 3         | 1.09%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 3         | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s     | 3         | 1.09%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 3         | 1.09%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s            | 2         | 0.72%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s         | 2         | 0.72%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 2         | 0.72%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 2         | 0.72%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s        | 2         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 2         | 0.72%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.72%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 2         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.72%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.72%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 2         | 0.72%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.72%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 2         | 0.72%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s               | 2         | 0.72%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 2         | 0.72%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 0.72%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 2         | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 0.72%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.72%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1334MT/s       | 2         | 0.72%   |
| Lexar RAM LD4AS016G-H2666G 16GB SODIMM DDR4 2667MT/s         | 2         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 92        | 49.73%  |
| DDR3   | 76        | 41.08%  |
| LPDDR3 | 6         | 3.24%   |
| LPDDR4 | 4         | 2.16%   |
| SDRAM  | 3         | 1.62%   |
| DDR2   | 2         | 1.08%   |
| DDR5   | 1         | 0.54%   |
| DDR    | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 133       | 71.12%  |
| DIMM         | 38        | 20.32%  |
| Row Of Chips | 16        | 8.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 81        | 39.13%  |
| 4096  | 56        | 27.05%  |
| 16384 | 38        | 18.36%  |
| 2048  | 23        | 11.11%  |
| 32768 | 9         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 58        | 27.49%  |
| 2667  | 44        | 20.85%  |
| 3200  | 32        | 15.17%  |
| 2133  | 18        | 8.53%   |
| 2400  | 13        | 6.16%   |
| 1333  | 13        | 6.16%   |
| 1334  | 9         | 4.27%   |
| 4267  | 3         | 1.42%   |
| 1866  | 3         | 1.42%   |
| 1067  | 3         | 1.42%   |
| 1066  | 2         | 0.95%   |
| 8400  | 1         | 0.47%   |
| 4800  | 1         | 0.47%   |
| 4199  | 1         | 0.47%   |
| 3733  | 1         | 0.47%   |
| 3266  | 1         | 0.47%   |
| 3000  | 1         | 0.47%   |
| 2666  | 1         | 0.47%   |
| 2267  | 1         | 0.47%   |
| 2200  | 1         | 0.47%   |
| 2000  | 1         | 0.47%   |
| 1867  | 1         | 0.47%   |
| 975   | 1         | 0.47%   |
| 800   | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 66.67%  |
| STMicroelectronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| STMicroelectronics USB Printer P | 1         | 33.33%  |
| HP LaserJet 1300                 | 1         | 33.33%  |
| HP DeskJet F2492 All-in-One      | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Plustek | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 68        | 25.56%  |
| Microdia                               | 30        | 11.28%  |
| Sunplus Innovation Technology          | 26        | 9.77%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 8.65%   |
| Realtek Semiconductor                  | 21        | 7.89%   |
| Lite-On Technology                     | 14        | 5.26%   |
| Quanta                                 | 10        | 3.76%   |
| IMC Networks                           | 10        | 3.76%   |
| Syntek                                 | 8         | 3.01%   |
| Suyin                                  | 7         | 2.63%   |
| Bison Electronics                      | 7         | 2.63%   |
| Luxvisions Innotech Limited            | 6         | 2.26%   |
| Ricoh                                  | 5         | 1.88%   |
| Silicon Motion                         | 4         | 1.5%    |
| Apple                                  | 4         | 1.5%    |
| Acer                                   | 4         | 1.5%    |
| Logitech                               | 3         | 1.13%   |
| Z-Star Microelectronics                | 2         | 0.75%   |
| Primax Electronics                     | 2         | 0.75%   |
| SunplusIT                              | 1         | 0.38%   |
| Sunplus Technology                     | 1         | 0.38%   |
| Samsung Electronics                    | 1         | 0.38%   |
| Pixart Imaging                         | 1         | 0.38%   |
| OmniVision Technologies                | 1         | 0.38%   |
| Microsoft                              | 1         | 0.38%   |
| MacroSilicon                           | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| DigiTech                               | 1         | 0.38%   |
| Asuscom Network                        | 1         | 0.38%   |
| Arkmicro Technologies                  | 1         | 0.38%   |
| ALi                                    | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 15        | 5.6%    |
| Microdia Integrated_Webcam_HD                                              | 15        | 5.6%    |
| Chicony Integrated Camera                                                  | 15        | 5.6%    |
| Chicony HP HD Camera                                                       | 11        | 4.1%    |
| Realtek Integrated_Webcam_HD                                               | 9         | 3.36%   |
| Lite-On HP HD Webcam                                                       | 9         | 3.36%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 9         | 3.36%   |
| IMC Networks Integrated Camera                                             | 6         | 2.24%   |
| Syntek Integrated Camera                                                   | 5         | 1.87%   |
| Microdia Integrated Webcam                                                 | 5         | 1.87%   |
| Quanta HP HD Camera                                                        | 4         | 1.49%   |
| Chicony USB 2.0Camera                                                      | 4         | 1.49%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.49%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.49%   |
| Chicony HP TrueVision HD                                                   | 4         | 1.49%   |
| Chicony EasyCamera                                                         | 4         | 1.49%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 4         | 1.49%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.12%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.12%   |
| Realtek USB2.0 camera                                                      | 3         | 1.12%   |
| Realtek Integrated Webcam                                                  | 3         | 1.12%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 1.12%   |
| Lite-On HP HD Camera                                                       | 3         | 1.12%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.12%   |
| Chicony TOSHIBA Web Camera - HD                                            | 3         | 1.12%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 3         | 1.12%   |
| Z-Star Venus USB2.0 Camera                                                 | 2         | 0.75%   |
| Suyin HP Truevision HD                                                     | 2         | 0.75%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 0.75%   |
| Sunplus HP Universal Camera                                                | 2         | 0.75%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.75%   |
| Realtek Integrated Webcam_HD                                               | 2         | 0.75%   |
| Realtek HP Truevision HD                                                   | 2         | 0.75%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.75%   |
| Primax HP HD Webcam [Fixed]                                                | 2         | 0.75%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 0.75%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 50        | 59.52%  |
| Synaptics                  | 15        | 17.86%  |
| Shenzhen Goodix Technology | 10        | 11.9%   |
| AuthenTec                  | 4         | 4.76%   |
| Upek                       | 3         | 3.57%   |
| Elan Microelectronics      | 2         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 25%     |
| Validity Sensors VFS491                                                    | 10        | 11.9%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 11.9%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 8.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 5.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.57%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.57%   |
| AuthenTec AES2810                                                          | 3         | 3.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.38%   |
| Synaptics  WBDI                                                            | 2         | 2.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.38%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.38%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.19%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.19%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.19%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 27        | 84.38%  |
| O2 Micro         | 3         | 9.38%   |
| SCM Microsystems | 1         | 3.13%   |
| Alcor Micro      | 1         | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 31.25%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 28.13%  |
| Broadcom 5880                                                                | 4         | 12.5%   |
| Broadcom 58200                                                               | 4         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.25%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 3.13%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.13%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 221       | 57.11%  |
| 1     | 139       | 35.92%  |
| 2     | 21        | 5.43%   |
| 4     | 2         | 0.52%   |
| 3     | 2         | 0.52%   |
| 8     | 1         | 0.26%   |
| 7     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 83        | 41.09%  |
| Chipcard                 | 31        | 15.35%  |
| Graphics card            | 29        | 14.36%  |
| Net/wireless             | 18        | 8.91%   |
| Sound                    | 11        | 5.45%   |
| Bluetooth                | 6         | 2.97%   |
| Storage                  | 5         | 2.48%   |
| Communication controller | 5         | 2.48%   |
| Multimedia controller    | 4         | 1.98%   |
| Net/ethernet             | 3         | 1.49%   |
| Camera                   | 3         | 1.49%   |
| Network                  | 2         | 0.99%   |
| Storage/ata              | 1         | 0.5%    |
| Card reader              | 1         | 0.5%    |


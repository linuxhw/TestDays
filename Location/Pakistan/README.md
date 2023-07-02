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

Total: 489

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo    | Edge 15 80H1                | Notebook    | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| Lenovo    | IdeaPad 3 15ITL6 82H8       | Notebook    | [32f2a1756a](https://linux-hardware.org/?probe=32f2a1756a) | Jun 23, 2023 |
| Alienware | x17 R2                      | Notebook    | [632fbfe682](https://linux-hardware.org/?probe=632fbfe682) | Jun 20, 2023 |
| Haier     | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| Lenovo    | IdeaPad 310-15IKB 80TV      | Notebook    | [1f5222a92f](https://linux-hardware.org/?probe=1f5222a92f) | Jun 15, 2023 |
| HP        | ProLiant DL380p Gen8        | Server      | [4919ecc453](https://linux-hardware.org/?probe=4919ecc453) | Jun 14, 2023 |
| HP        | ProLiant DL380p Gen8        | Server      | [911cc1f620](https://linux-hardware.org/?probe=911cc1f620) | Jun 14, 2023 |
| HP        | ProBook 6360b               | Notebook    | [cdef37cb2d](https://linux-hardware.org/?probe=cdef37cb2d) | Jun 09, 2023 |
| ASUSTek   | T200TA                      | Notebook    | [2c98c872f8](https://linux-hardware.org/?probe=2c98c872f8) | Jun 08, 2023 |
| Clevo     | P170HMx                     | Notebook    | [6513e1e52e](https://linux-hardware.org/?probe=6513e1e52e) | Jun 08, 2023 |
| Clevo     | P170HMx                     | Notebook    | [7e2d7bfd0d](https://linux-hardware.org/?probe=7e2d7bfd0d) | Jun 06, 2023 |
| Dell      | Latitude E7450              | Notebook    | [fe7cb1e53f](https://linux-hardware.org/?probe=fe7cb1e53f) | Jun 03, 2023 |
| Lenovo    | Edge 15 80H1                | Notebook    | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Dell      | Inspiron 7391 2n1           | Convertible | [b99041460e](https://linux-hardware.org/?probe=b99041460e) | May 27, 2023 |
| Acer      | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Dell      | Latitude E7450              | Notebook    | [4a88622321](https://linux-hardware.org/?probe=4a88622321) | May 26, 2023 |
| Dell      | Latitude 5480               | Notebook    | [adb6ba25f1](https://linux-hardware.org/?probe=adb6ba25f1) | May 25, 2023 |
| Dell      | Latitude 5480               | Notebook    | [45b63ce664](https://linux-hardware.org/?probe=45b63ce664) | May 25, 2023 |
| Dell      | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell      | Precision 5520              | Notebook    | [a5e0cc8586](https://linux-hardware.org/?probe=a5e0cc8586) | May 24, 2023 |
| MSI       | Z590-A PRO                  | Desktop     | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| HP        | EliteBook 850 G6            | Notebook    | [b38d6399b4](https://linux-hardware.org/?probe=b38d6399b4) | May 22, 2023 |
| Apple     | MacBookPro15,1              | Notebook    | [f1d994fa47](https://linux-hardware.org/?probe=f1d994fa47) | May 22, 2023 |
| Dell      | Latitude E7450              | Notebook    | [51f34cd446](https://linux-hardware.org/?probe=51f34cd446) | May 20, 2023 |
| Dell      | Latitude E7450              | Notebook    | [e844aeb177](https://linux-hardware.org/?probe=e844aeb177) | May 19, 2023 |
| MSI       | Z590-A PRO                  | Desktop     | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| HP        | OMEN by Laptop 16-b0xxx     | Notebook    | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| Gigabyte  | B550 GAMING X V2            | Desktop     | [68573d1b85](https://linux-hardware.org/?probe=68573d1b85) | May 13, 2023 |
| HP        | EliteBook 820 G1            | Notebook    | [9ba944eae5](https://linux-hardware.org/?probe=9ba944eae5) | May 09, 2023 |
| HP        | EliteBook 820 G1            | Notebook    | [3e9f94b26a](https://linux-hardware.org/?probe=3e9f94b26a) | May 09, 2023 |
| Dell      | Latitude E5440              | Notebook    | [6db42a9acc](https://linux-hardware.org/?probe=6db42a9acc) | May 08, 2023 |
| Dell      | Inspiron 17-7779            | Notebook    | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| Dell      | Latitude 5410               | Notebook    | [840aaee455](https://linux-hardware.org/?probe=840aaee455) | May 04, 2023 |
| Dell      | Latitude 5410               | Notebook    | [f95e1d32bf](https://linux-hardware.org/?probe=f95e1d32bf) | May 04, 2023 |
| Google    | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google    | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| KEIAN     | KBM101K                     | Tablet      | [20982ffeb1](https://linux-hardware.org/?probe=20982ffeb1) | Apr 29, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop TP41... | Convertible | [f9228e78d3](https://linux-hardware.org/?probe=f9228e78d3) | Apr 25, 2023 |
| Inventec  | Z CLASS A02                 | Desktop     | [44b6a5142e](https://linux-hardware.org/?probe=44b6a5142e) | Apr 25, 2023 |
| HP        | Pavilion Laptop 15-cc1xx    | Notebook    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| Dell      | Inspiron 3593               | Notebook    | [5ac8ce1eb9](https://linux-hardware.org/?probe=5ac8ce1eb9) | Apr 19, 2023 |
| Lenovo    | ThinkPad E15 Gen 3 20YG0... | Notebook    | [7ec2b3ff95](https://linux-hardware.org/?probe=7ec2b3ff95) | Apr 14, 2023 |
| HP        | EliteBook 8470w             | Notebook    | [47e8a4441b](https://linux-hardware.org/?probe=47e8a4441b) | Apr 04, 2023 |
| HP        | EliteBook 850 G6            | Notebook    | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Intel     | DQ67OW AAG28716-309         | Desktop     | [e628a47ac6](https://linux-hardware.org/?probe=e628a47ac6) | Apr 01, 2023 |
| Dell      | G3 3500                     | Notebook    | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| Intel     | DQ67OW AAG28716-309         | Desktop     | [3394687910](https://linux-hardware.org/?probe=3394687910) | Mar 29, 2023 |
| Intel     | DQ67OW AAG28716-309         | Desktop     | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| HP        | 1850                        | Desktop     | [5ae52efa64](https://linux-hardware.org/?probe=5ae52efa64) | Mar 25, 2023 |
| HP        | Laptop 15s-fq5xxx           | Notebook    | [f84f8c068b](https://linux-hardware.org/?probe=f84f8c068b) | Mar 15, 2023 |
| Lenovo    | ThinkPad 11e 20DAS0T500     | Notebook    | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| Inventec  | Z CLASS A02                 | Desktop     | [7b5d4c040b](https://linux-hardware.org/?probe=7b5d4c040b) | Mar 05, 2023 |
| HP        | EliteBook 840 G5            | Notebook    | [948a77b264](https://linux-hardware.org/?probe=948a77b264) | Mar 04, 2023 |
| HP        | EliteBook 840 G5            | Notebook    | [f245db2b9a](https://linux-hardware.org/?probe=f245db2b9a) | Mar 04, 2023 |
| Samsung   | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
| HP        | ProBook 450 G8 Notebook ... | Notebook    | [009eefdc1d](https://linux-hardware.org/?probe=009eefdc1d) | Feb 28, 2023 |
| HP        | ProBook 450 G8 Notebook ... | Notebook    | [17a7ee80ac](https://linux-hardware.org/?probe=17a7ee80ac) | Feb 28, 2023 |
| HP        | ProBook 645 G1              | Notebook    | [329c0a65eb](https://linux-hardware.org/?probe=329c0a65eb) | Feb 25, 2023 |
| Lenovo    | Legion S7 15ACH6 82K8       | Notebook    | [6f65703034](https://linux-hardware.org/?probe=6f65703034) | Feb 19, 2023 |
| HP        | Pavilion g6                 | Notebook    | [876f755425](https://linux-hardware.org/?probe=876f755425) | Feb 19, 2023 |
| HP        | 339A                        | Desktop     | [07001c3589](https://linux-hardware.org/?probe=07001c3589) | Feb 19, 2023 |
| HP        | 339A                        | Desktop     | [0d7bb8b04a](https://linux-hardware.org/?probe=0d7bb8b04a) | Feb 19, 2023 |
| HP        | Notebook                    | Notebook    | [047fd0d69e](https://linux-hardware.org/?probe=047fd0d69e) | Feb 18, 2023 |
| ASUSTek   | A55BM-PLUS                  | Desktop     | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Apple     | MacBookPro11,3              | Notebook    | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| Unknown   | IPMSB-H61                   | Desktop     | [7e13c996bd](https://linux-hardware.org/?probe=7e13c996bd) | Feb 02, 2023 |
| Apple     | MacBookPro11,3              | Notebook    | [b7cec06bcb](https://linux-hardware.org/?probe=b7cec06bcb) | Jan 30, 2023 |
| Dell      | Latitude E7470              | Notebook    | [42ace80c0b](https://linux-hardware.org/?probe=42ace80c0b) | Jan 27, 2023 |
| HP        | ProBook 6565b               | Notebook    | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| Dell      | 0KRC95 A00                  | Desktop     | [bf9e573abf](https://linux-hardware.org/?probe=bf9e573abf) | Jan 25, 2023 |
| HP        | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Lenovo    | Yoga 920-13IKB 80Y7         | Convertible | [dafb34058f](https://linux-hardware.org/?probe=dafb34058f) | Jan 17, 2023 |
| HP        | ENVY dv7                    | Notebook    | [4b7b0f98af](https://linux-hardware.org/?probe=4b7b0f98af) | Jan 15, 2023 |
| Lenovo    | S20-30 20421                | Notebook    | [43bee9503c](https://linux-hardware.org/?probe=43bee9503c) | Jan 11, 2023 |
| HP        | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| HP        | ENVY dv6                    | Notebook    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| MSI       | Z590-A PRO                  | Desktop     | [b55d0dfc1e](https://linux-hardware.org/?probe=b55d0dfc1e) | Jan 03, 2023 |
| MSI       | Z590-A PRO                  | Desktop     | [63adf72d53](https://linux-hardware.org/?probe=63adf72d53) | Jan 01, 2023 |
| HP        | 304Ah                       | Desktop     | [6106d55390](https://linux-hardware.org/?probe=6106d55390) | Dec 26, 2022 |
| Haier     | Y11C                        | Notebook    | [cc9a03834f](https://linux-hardware.org/?probe=cc9a03834f) | Dec 21, 2022 |
| HP        | Laptop 15s-fq5xxx           | Notebook    | [86f0e8ad5d](https://linux-hardware.org/?probe=86f0e8ad5d) | Dec 20, 2022 |
| HP        | Laptop 15s-fq5xxx           | Notebook    | [8122fe7426](https://linux-hardware.org/?probe=8122fe7426) | Dec 20, 2022 |
| Gigabyte  | Q87M-D2H                    | Desktop     | [0b6bf86b5e](https://linux-hardware.org/?probe=0b6bf86b5e) | Dec 10, 2022 |
| Dell      | Latitude D620               | Notebook    | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| Toshiba   | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Dell      | Vostro 3500                 | Notebook    | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| HP        | 198E                        | Desktop     | [9d22530b3c](https://linux-hardware.org/?probe=9d22530b3c) | Nov 25, 2022 |
| Lenovo    | ThinkPad E14 20RAS04700     | Notebook    | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| Dell      | Latitude D620               | Notebook    | [d45ad40496](https://linux-hardware.org/?probe=d45ad40496) | Nov 21, 2022 |
| HP        | EliteBook 840 G3            | Notebook    | [835a83d0ea](https://linux-hardware.org/?probe=835a83d0ea) | Nov 20, 2022 |
| Dell      | 0HN7XN A00                  | Desktop     | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| HP        | Laptop 15-dw3xxx            | Notebook    | [03426a19e5](https://linux-hardware.org/?probe=03426a19e5) | Nov 16, 2022 |
| Gigabyte  | Q87M-D2H                    | Desktop     | [e7c7b6c8a7](https://linux-hardware.org/?probe=e7c7b6c8a7) | Nov 14, 2022 |
| Gigabyte  | Q87M-D2H                    | Desktop     | [8224e059c6](https://linux-hardware.org/?probe=8224e059c6) | Nov 14, 2022 |
| Timi      | TM1613                      | Notebook    | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| HP        | Laptop 14-dq2xxx            | Notebook    | [dcb6d439d4](https://linux-hardware.org/?probe=dcb6d439d4) | Nov 13, 2022 |
| Gigabyte  | Q87M-D2H                    | Desktop     | [543c3778c3](https://linux-hardware.org/?probe=543c3778c3) | Nov 12, 2022 |
| Gigabyte  | Q87M-D2H                    | Desktop     | [f73ba4186b](https://linux-hardware.org/?probe=f73ba4186b) | Nov 11, 2022 |
| Gigabyte  | Q87M-D2H                    | Desktop     | [143dc1e811](https://linux-hardware.org/?probe=143dc1e811) | Nov 05, 2022 |
| Lenovo    | ThinkPad E580 20KTA001GE    | Notebook    | [55dc6ac7ba](https://linux-hardware.org/?probe=55dc6ac7ba) | Oct 31, 2022 |
| Dell      | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| Dell      | Studio 1458                 | Notebook    | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| HP        | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | Notebook    | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | Notebook    | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| ASUSTek   | Q87M-E                      | Desktop     | [79f94ede46](https://linux-hardware.org/?probe=79f94ede46) | Oct 11, 2022 |
| Dell      | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell      | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP        | Laptop 15s-du3xxx           | Notebook    | [cbacce92bd](https://linux-hardware.org/?probe=cbacce92bd) | Oct 05, 2022 |
| HP        | Pavilion dv6                | Notebook    | [2830144a8a](https://linux-hardware.org/?probe=2830144a8a) | Oct 04, 2022 |
| HP        | 18E7                        | Desktop     | [797aa81ce0](https://linux-hardware.org/?probe=797aa81ce0) | Oct 02, 2022 |
| HP        | 18E7                        | Desktop     | [69e4bb94f3](https://linux-hardware.org/?probe=69e4bb94f3) | Oct 02, 2022 |
| HP        | EliteBook 850 G8 Noteboo... | Notebook    | [b01a9ac97f](https://linux-hardware.org/?probe=b01a9ac97f) | Sep 24, 2022 |
| HP        | Laptop 15-bs1xx             | Notebook    | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| HP        | ENVY 15                     | Notebook    | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Dell      | Inspiron 7791 2n1           | Convertible | [31e3939680](https://linux-hardware.org/?probe=31e3939680) | Sep 18, 2022 |
| Dell      | Inspiron 7791 2n1           | Convertible | [f207769c14](https://linux-hardware.org/?probe=f207769c14) | Sep 18, 2022 |
| HP        | EliteBook 840 G2            | Notebook    | [ca96e9bf9b](https://linux-hardware.org/?probe=ca96e9bf9b) | Sep 14, 2022 |
| HP        | EliteBook 840 G3            | Notebook    | [be88e72feb](https://linux-hardware.org/?probe=be88e72feb) | Sep 14, 2022 |
| HP        | EliteBook 840 G3            | Notebook    | [2b1c502b28](https://linux-hardware.org/?probe=2b1c502b28) | Sep 14, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| HP        | ProBook 4540s               | Notebook    | [c1bf52b653](https://linux-hardware.org/?probe=c1bf52b653) | Sep 13, 2022 |
| HP        | ProBook 4540s               | Notebook    | [320e270f44](https://linux-hardware.org/?probe=320e270f44) | Sep 13, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [c03777782c](https://linux-hardware.org/?probe=c03777782c) | Sep 13, 2022 |
| HP        | Unknown                     | Notebook    | [5cf262a728](https://linux-hardware.org/?probe=5cf262a728) | Sep 10, 2022 |
| Lenovo    | ThinkPad T470 20HES3370A    | Notebook    | [5beda28487](https://linux-hardware.org/?probe=5beda28487) | Sep 09, 2022 |
| Dell      | Latitude 3340               | Notebook    | [ec720c63b1](https://linux-hardware.org/?probe=ec720c63b1) | Sep 06, 2022 |
| Lenovo    | ThinkPad T470 20HES3370A    | Notebook    | [3a466cef0a](https://linux-hardware.org/?probe=3a466cef0a) | Sep 05, 2022 |
| Dell      | Latitude E6420              | Notebook    | [98a628a92a](https://linux-hardware.org/?probe=98a628a92a) | Sep 03, 2022 |
| Dell      | Latitude E6420              | Notebook    | [e9c43bd2ab](https://linux-hardware.org/?probe=e9c43bd2ab) | Sep 03, 2022 |
| Dell      | Latitude 3340               | Notebook    | [b9d472b965](https://linux-hardware.org/?probe=b9d472b965) | Sep 01, 2022 |
| Dell      | Latitude 7390               | Notebook    | [571b195a12](https://linux-hardware.org/?probe=571b195a12) | Aug 31, 2022 |
| Dell      | Latitude 7390               | Notebook    | [3c3f6114f6](https://linux-hardware.org/?probe=3c3f6114f6) | Aug 31, 2022 |
| HP        | EliteBook 840 G2            | Notebook    | [5ba91d8167](https://linux-hardware.org/?probe=5ba91d8167) | Aug 30, 2022 |
| HP        | EliteBook 840 G1            | Notebook    | [23d73aa95c](https://linux-hardware.org/?probe=23d73aa95c) | Aug 30, 2022 |
| HP        | EliteBook 840 G2            | Notebook    | [bed3be5142](https://linux-hardware.org/?probe=bed3be5142) | Aug 30, 2022 |
| HP        | EliteBook 840 G2            | Notebook    | [b588415d06](https://linux-hardware.org/?probe=b588415d06) | Aug 30, 2022 |
| Lenovo    | ThinkPad T470 20HES3370A    | Notebook    | [3b1630e4bc](https://linux-hardware.org/?probe=3b1630e4bc) | Aug 30, 2022 |
| HP        | Unknown                     | Notebook    | [9b22ce41e3](https://linux-hardware.org/?probe=9b22ce41e3) | Aug 27, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop TP41... | Convertible | [1b2c235511](https://linux-hardware.org/?probe=1b2c235511) | Aug 22, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop TP41... | Convertible | [c563f4b965](https://linux-hardware.org/?probe=c563f4b965) | Aug 22, 2022 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| Dell      | Latitude 7400               | Notebook    | [7f870ac8c2](https://linux-hardware.org/?probe=7f870ac8c2) | Aug 17, 2022 |
| Acer      | Predator PH317-53           | Notebook    | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo    | IdeaPad 330-15IKB 81DE      | Notebook    | [072d897eda](https://linux-hardware.org/?probe=072d897eda) | Jul 28, 2022 |
| Dell      | Latitude E6420              | Notebook    | [07a671ae31](https://linux-hardware.org/?probe=07a671ae31) | Jul 22, 2022 |
| Dell      | Latitude E5440              | Notebook    | [3b30865387](https://linux-hardware.org/?probe=3b30865387) | Jul 20, 2022 |
| Quanta    | 2ABB 101                    | Desktop     | [3d241d58b9](https://linux-hardware.org/?probe=3d241d58b9) | Jul 13, 2022 |
| Gigabyte  | A520M S2H                   | Desktop     | [52aab7f65b](https://linux-hardware.org/?probe=52aab7f65b) | Jul 12, 2022 |
| Sony      | VPCEA26FG                   | Notebook    | [c5432e157a](https://linux-hardware.org/?probe=c5432e157a) | Jul 11, 2022 |
| Dell      | Latitude E7450              | Notebook    | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| ASUSTek   | TUF Gaming B550-PLUS WIF... | Desktop     | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| Sony      | VPCEA26FG                   | Notebook    | [2075c04c4c](https://linux-hardware.org/?probe=2075c04c4c) | Jul 03, 2022 |
| Sony      | VPCEA26FG                   | Notebook    | [b72a4de42b](https://linux-hardware.org/?probe=b72a4de42b) | Jul 01, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | Notebook    | [18fbe5a2d0](https://linux-hardware.org/?probe=18fbe5a2d0) | Jun 28, 2022 |
| HP        | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Gigabyte  | A520M S2H                   | Desktop     | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| HP        | 339A                        | Desktop     | [a20191b759](https://linux-hardware.org/?probe=a20191b759) | Jun 23, 2022 |
| HP        | EliteBook 8470p             | Notebook    | [f9895656b6](https://linux-hardware.org/?probe=f9895656b6) | Jun 23, 2022 |
| HP        | EliteBook 8470p             | Notebook    | [2e2bcb63d7](https://linux-hardware.org/?probe=2e2bcb63d7) | Jun 23, 2022 |
| HP        | 18E7                        | Desktop     | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| HP        | EliteBook 850 G5            | Notebook    | [085f5c458d](https://linux-hardware.org/?probe=085f5c458d) | Jun 10, 2022 |
| HP        | Laptop 15s-fq2xxx           | Notebook    | [5bcb742cbe](https://linux-hardware.org/?probe=5bcb742cbe) | Jun 04, 2022 |
| Lenovo    | ThinkPad T450 20BV0005US    | Notebook    | [a795ed872f](https://linux-hardware.org/?probe=a795ed872f) | Jun 03, 2022 |
| ASUSTek   | STRIX B250H GAMING          | Desktop     | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| HP        | EliteBook 8460p             | Notebook    | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP        | EliteBook 8460p             | Notebook    | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell      | Inspiron 3543               | Notebook    | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| HP        | Notebook                    | Notebook    | [4508e41795](https://linux-hardware.org/?probe=4508e41795) | May 22, 2022 |
| HP        | Notebook                    | Notebook    | [dc587c572e](https://linux-hardware.org/?probe=dc587c572e) | May 22, 2022 |
| HP        | 1495                        | Desktop     | [9ec1730693](https://linux-hardware.org/?probe=9ec1730693) | May 11, 2022 |
| Lenovo    | SDK0E50510 WIN              | Desktop     | [07526b3b20](https://linux-hardware.org/?probe=07526b3b20) | May 10, 2022 |
| Dell      | Latitude 3330               | Notebook    | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Dell      | Latitude E6420              | Notebook    | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| HP        | 3396                        | Desktop     | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP        | 3396                        | Desktop     | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| HP        | EliteBook 840 G1            | Notebook    | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| HP        | EliteBook 840 G2            | Notebook    | [3e0d410668](https://linux-hardware.org/?probe=3e0d410668) | Apr 19, 2022 |
| HP        | 3396                        | Desktop     | [2c07ec89d4](https://linux-hardware.org/?probe=2c07ec89d4) | Apr 17, 2022 |
| HP        | ProBook 450 G8 Notebook ... | Notebook    | [1974bfe63a](https://linux-hardware.org/?probe=1974bfe63a) | Apr 15, 2022 |
| Dell      | Latitude 3520               | Notebook    | [ee204b07aa](https://linux-hardware.org/?probe=ee204b07aa) | Apr 11, 2022 |
| HP        | Pavilion TS 11              | Notebook    | [9a817f6695](https://linux-hardware.org/?probe=9a817f6695) | Apr 09, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| HP        | 87D6 SMVB                   | Desktop     | [57d44d9705](https://linux-hardware.org/?probe=57d44d9705) | Apr 03, 2022 |
| HP        | 87D6 SMVB                   | Desktop     | [e70c6e6d89](https://linux-hardware.org/?probe=e70c6e6d89) | Apr 03, 2022 |
| Dell      | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | Notebook    | [1936ee53b3](https://linux-hardware.org/?probe=1936ee53b3) | Mar 22, 2022 |
| Dell      | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Lenovo    | V110-15IKB 80TH             | Notebook    | [a3aeef468a](https://linux-hardware.org/?probe=a3aeef468a) | Mar 12, 2022 |
| Dell      | 0HR330                      | Desktop     | [9e351420b6](https://linux-hardware.org/?probe=9e351420b6) | Mar 04, 2022 |
| Gigabyte  | A520M S2H                   | Desktop     | [06db14c491](https://linux-hardware.org/?probe=06db14c491) | Mar 01, 2022 |
| Dell      | 0HR330                      | Desktop     | [7e4c13a9bd](https://linux-hardware.org/?probe=7e4c13a9bd) | Mar 01, 2022 |
| Dell      | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell      | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e0169c3e87](https://linux-hardware.org/?probe=e0169c3e87) | Feb 23, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [1aa838368f](https://linux-hardware.org/?probe=1aa838368f) | Feb 20, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| HP        | 8717                        | Desktop     | [d5d2ee0ab5](https://linux-hardware.org/?probe=d5d2ee0ab5) | Feb 18, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [7fdd5b66fc](https://linux-hardware.org/?probe=7fdd5b66fc) | Feb 14, 2022 |
| Lenovo    | IdeaPad 510-15ISK 80SR      | Notebook    | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Dell      | Inspiron 5547               | Notebook    | [2d6ff07a82](https://linux-hardware.org/?probe=2d6ff07a82) | Feb 12, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [0dd77f2f7a](https://linux-hardware.org/?probe=0dd77f2f7a) | Feb 12, 2022 |
| HP        | 8061                        | Desktop     | [f721051d60](https://linux-hardware.org/?probe=f721051d60) | Feb 11, 2022 |
| HP        | 8717                        | Desktop     | [97d99714a1](https://linux-hardware.org/?probe=97d99714a1) | Feb 10, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5a9a256568](https://linux-hardware.org/?probe=5a9a256568) | Feb 01, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [4a0c4a62b7](https://linux-hardware.org/?probe=4a0c4a62b7) | Feb 01, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [c902cc42a6](https://linux-hardware.org/?probe=c902cc42a6) | Jan 18, 2022 |
| Dell      | 0DR845                      | Desktop     | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [ce839c3628](https://linux-hardware.org/?probe=ce839c3628) | Jan 08, 2022 |
| Lenovo    | ThinkPad T540p 20BFS5630... | Notebook    | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| HP        | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP        | EliteBook Folio 9470m       | Notebook    | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP        | EliteBook Folio 9470m       | Notebook    | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| HP        | ProLiant DL360 G7           | Server      | [70e6bfadc4](https://linux-hardware.org/?probe=70e6bfadc4) | Dec 26, 2021 |
| Acer      | Aspire ES1-411              | Notebook    | [9a5ebb6379](https://linux-hardware.org/?probe=9a5ebb6379) | Dec 19, 2021 |
| HP        | EliteBook 8470p             | Notebook    | [0f7389c7d9](https://linux-hardware.org/?probe=0f7389c7d9) | Dec 14, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| HP        | 0B3Ch HP P/N                | Desktop     | [2805378159](https://linux-hardware.org/?probe=2805378159) | Dec 10, 2021 |
| HP        | ZBook 15 G3                 | Notebook    | [e662c8b956](https://linux-hardware.org/?probe=e662c8b956) | Dec 07, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [0784c5596b](https://linux-hardware.org/?probe=0784c5596b) | Dec 04, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [ebfaaee6ef](https://linux-hardware.org/?probe=ebfaaee6ef) | Dec 04, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [50a026d588](https://linux-hardware.org/?probe=50a026d588) | Dec 02, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [19fd4c2057](https://linux-hardware.org/?probe=19fd4c2057) | Nov 30, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [7493408721](https://linux-hardware.org/?probe=7493408721) | Nov 29, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [637bba1c58](https://linux-hardware.org/?probe=637bba1c58) | Nov 29, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [555032936f](https://linux-hardware.org/?probe=555032936f) | Nov 28, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [538c96bb62](https://linux-hardware.org/?probe=538c96bb62) | Nov 26, 2021 |
| Dell      | Latitude E6440              | Notebook    | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| HP        | Unknown                     | Notebook    | [ef28d45f68](https://linux-hardware.org/?probe=ef28d45f68) | Nov 23, 2021 |
| Dell      | G3 3579                     | Notebook    | [38e9f54ba1](https://linux-hardware.org/?probe=38e9f54ba1) | Nov 23, 2021 |
| Dell      | Inspiron 5520               | Notebook    | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| HP        | Unknown                     | Notebook    | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| Shuttle   | FS81                        | Desktop     | [ac6138c9d7](https://linux-hardware.org/?probe=ac6138c9d7) | Nov 19, 2021 |
| Shuttle   | FS81                        | Desktop     | [d889090212](https://linux-hardware.org/?probe=d889090212) | Nov 18, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [cd386145b8](https://linux-hardware.org/?probe=cd386145b8) | Nov 18, 2021 |
| HP        | Pavilion Laptop 14-ce2xx... | Notebook    | [f9ebb771b0](https://linux-hardware.org/?probe=f9ebb771b0) | Nov 14, 2021 |
| HP        | ZBook 15 G3                 | Notebook    | [67e5184b17](https://linux-hardware.org/?probe=67e5184b17) | Nov 13, 2021 |
| Dell      | Vostro 1500                 | Notebook    | [23aeb68ca2](https://linux-hardware.org/?probe=23aeb68ca2) | Nov 11, 2021 |
| HP        | 0AECh D                     | Desktop     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| HP        | ZBook 15 G3                 | Notebook    | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [72f1028535](https://linux-hardware.org/?probe=72f1028535) | Nov 09, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [e43d36b3cf](https://linux-hardware.org/?probe=e43d36b3cf) | Nov 09, 2021 |
| Dell      | Inspiron 3501               | Notebook    | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| Dell      | Inspiron 15-3567            | Notebook    | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| ASUSTek   | PRIME B550-PLUS             | Desktop     | [98ddca21d9](https://linux-hardware.org/?probe=98ddca21d9) | Nov 06, 2021 |
| HP        | 0AECh D                     | Desktop     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| HP        | 650                         | Notebook    | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| Apple     | MacBookPro14,1              | Notebook    | [bb1aa448fd](https://linux-hardware.org/?probe=bb1aa448fd) | Oct 20, 2021 |
| HP        | ProBook 450 G7              | Notebook    | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| Dell      | 0XPDFK A01                  | Desktop     | [0e66d5fd62](https://linux-hardware.org/?probe=0e66d5fd62) | Oct 16, 2021 |
| Lenovo    | ThinkBook 15-IIL 20SM       | Notebook    | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| HP        | ProBook 450 G7              | Notebook    | [f2a84de135](https://linux-hardware.org/?probe=f2a84de135) | Oct 12, 2021 |
| Dell      | Latitude E5570              | Notebook    | [938d1a781d](https://linux-hardware.org/?probe=938d1a781d) | Oct 08, 2021 |
| Lenovo    | ThinkPad X220 Tablet 429... | Notebook    | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| HP        | 0AECh D                     | Desktop     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | Notebook    | [196fa579f8](https://linux-hardware.org/?probe=196fa579f8) | Oct 04, 2021 |
| Haier     | Y11C                        | Notebook    | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Dell      | Precision M6400             | Notebook    | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| Haier     | Y11C                        | Notebook    | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| HP        | 0AECh D                     | Desktop     | [202ada3fc3](https://linux-hardware.org/?probe=202ada3fc3) | Sep 23, 2021 |
| HP        | 3047h                       | Desktop     | [356ad972a7](https://linux-hardware.org/?probe=356ad972a7) | Sep 22, 2021 |
| Lenovo    | ThinkPad X220 Tablet 429... | Notebook    | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| HP        | 1587h                       | Desktop     | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| Unknown   | Unknown                     | Desktop     | [321a93dff9](https://linux-hardware.org/?probe=321a93dff9) | Sep 07, 2021 |
| Shuttle   | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| HP        | ProLiant DL380p Gen8        | Server      | [c5c3b2d36c](https://linux-hardware.org/?probe=c5c3b2d36c) | Sep 02, 2021 |
| HP        | ProLiant DL380p Gen8        | Server      | [ece6c14756](https://linux-hardware.org/?probe=ece6c14756) | Sep 02, 2021 |
| HP        | ProLiant DL380p Gen8        | Server      | [262cc4f3e7](https://linux-hardware.org/?probe=262cc4f3e7) | Aug 29, 2021 |
| Dell      | 09KPNV A01                  | Desktop     | [7e939d9f5f](https://linux-hardware.org/?probe=7e939d9f5f) | Aug 20, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X571... | Notebook    | [966a09526a](https://linux-hardware.org/?probe=966a09526a) | Aug 14, 2021 |
| Dell      | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Dell      | Inspiron 5570               | Notebook    | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| Dell      | Inspiron 5593               | Notebook    | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| Dell      | Latitude E5250              | Notebook    | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Gigabyte  | Z590 UD AC                  | Desktop     | [7e8e35538a](https://linux-hardware.org/?probe=7e8e35538a) | Jul 26, 2021 |
| Dell      | Latitude E5250              | Notebook    | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell      | Latitude E5250              | Notebook    | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Gigabyte  | Z590 UD AC                  | Desktop     | [4fc5079d7e](https://linux-hardware.org/?probe=4fc5079d7e) | Jul 20, 2021 |
| Dell      | Latitude E5250              | Notebook    | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| HP        | EliteBook 8440p             | Notebook    | [d89b69a6a3](https://linux-hardware.org/?probe=d89b69a6a3) | Jul 16, 2021 |
| Lenovo    | ThinkCentre M70e 0830F2U    | Desktop     | [8dad962f2f](https://linux-hardware.org/?probe=8dad962f2f) | Jul 09, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [d320594f42](https://linux-hardware.org/?probe=d320594f42) | Jul 07, 2021 |
| Lenovo    | ThinkPad E14 20RA007SAD     | Notebook    | [eb51ce8f36](https://linux-hardware.org/?probe=eb51ce8f36) | Jul 07, 2021 |
| Dell      | Inspiron 7306 2n1           | Convertible | [f4d326f499](https://linux-hardware.org/?probe=f4d326f499) | Jul 05, 2021 |
| Dell      | Precision 5530              | Notebook    | [7d267375f2](https://linux-hardware.org/?probe=7d267375f2) | Jul 05, 2021 |
| Dell      | Inspiron 7306 2n1           | Convertible | [7236dc0c95](https://linux-hardware.org/?probe=7236dc0c95) | Jul 04, 2021 |
| Dell      | Inspiron 5593               | Notebook    | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| HP        | Pavilion Notebook           | Notebook    | [f5ac8e2aca](https://linux-hardware.org/?probe=f5ac8e2aca) | Jun 25, 2021 |
| HP        | Pavilion dv6                | Notebook    | [c3529dc2aa](https://linux-hardware.org/?probe=c3529dc2aa) | Jun 24, 2021 |
| Dell      | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| HP        | 158A                        | Desktop     | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| Dell      | Latitude 3510               | Notebook    | [79c73e5595](https://linux-hardware.org/?probe=79c73e5595) | Jun 09, 2021 |
| Toshiba   | Satellite L850              | Notebook    | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Dell      | Vostro 14-3468              | Notebook    | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| Dell      | 042P49 A00                  | Desktop     | [2d9b300bd3](https://linux-hardware.org/?probe=2d9b300bd3) | May 13, 2021 |
| Dell      | Latitude E5250              | Notebook    | [8c3b8c27c8](https://linux-hardware.org/?probe=8c3b8c27c8) | May 10, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| Dell      | 06FW8P A01                  | Desktop     | [08f4c825cc](https://linux-hardware.org/?probe=08f4c825cc) | Apr 25, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [bc7c3f8c4d](https://linux-hardware.org/?probe=bc7c3f8c4d) | Apr 23, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [8d7a62ce1a](https://linux-hardware.org/?probe=8d7a62ce1a) | Apr 20, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [583acd1f2e](https://linux-hardware.org/?probe=583acd1f2e) | Apr 20, 2021 |
| Dell      | 06FW8P A01                  | Desktop     | [a0b4b692ff](https://linux-hardware.org/?probe=a0b4b692ff) | Apr 20, 2021 |
| Shuttle   | FS81                        | Desktop     | [14e78cfe43](https://linux-hardware.org/?probe=14e78cfe43) | Apr 20, 2021 |
| Dell      | Latitude E6420              | Notebook    | [6e3288ca3a](https://linux-hardware.org/?probe=6e3288ca3a) | Apr 11, 2021 |
| Dell      | Inspiron 17-7779            | Notebook    | [2cf1f86b67](https://linux-hardware.org/?probe=2cf1f86b67) | Apr 06, 2021 |
| Gigabyte  | AERO 15-SA                  | Notebook    | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Gigabyte  | AERO 15-SA                  | Notebook    | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Dell      | Latitude 3510               | Notebook    | [1ef27c1786](https://linux-hardware.org/?probe=1ef27c1786) | Mar 25, 2021 |
| ASUSTek   | PN61                        | Mini pc     | [45389ef622](https://linux-hardware.org/?probe=45389ef622) | Mar 24, 2021 |
| HP        | EliteBook 2170p             | Notebook    | [eba311c4d7](https://linux-hardware.org/?probe=eba311c4d7) | Mar 22, 2021 |
| HP        | EliteBook 2170p             | Notebook    | [e506fc315e](https://linux-hardware.org/?probe=e506fc315e) | Mar 21, 2021 |
| Dell      | 0GU083 A00                  | Desktop     | [03e87a4ada](https://linux-hardware.org/?probe=03e87a4ada) | Mar 20, 2021 |
| Lenovo    | IdeaPad L340-15IWL 81LG     | Notebook    | [eb713030d2](https://linux-hardware.org/?probe=eb713030d2) | Mar 18, 2021 |
| Dell      | Latitude E6420              | Notebook    | [a062baeb24](https://linux-hardware.org/?probe=a062baeb24) | Mar 12, 2021 |
| Dell      | 0C27VV A01                  | Desktop     | [2ab353f0c6](https://linux-hardware.org/?probe=2ab353f0c6) | Mar 06, 2021 |
| HP        | EliteBook 850 G7 Noteboo... | Notebook    | [6dbe550700](https://linux-hardware.org/?probe=6dbe550700) | Feb 28, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [67ea005277](https://linux-hardware.org/?probe=67ea005277) | Feb 24, 2021 |
| HP        | EliteBook 840 G3            | Notebook    | [b8a8ea9182](https://linux-hardware.org/?probe=b8a8ea9182) | Feb 24, 2021 |
| HP        | EliteBook 840 G3            | Notebook    | [ce415da689](https://linux-hardware.org/?probe=ce415da689) | Feb 23, 2021 |
| ASUSTek   | TUF Gaming FA706IU_FA706... | Notebook    | [64c73f58bb](https://linux-hardware.org/?probe=64c73f58bb) | Feb 22, 2021 |
| Lenovo    | ThinkBook 15-IIL 20SM       | Notebook    | [0426a1c07e](https://linux-hardware.org/?probe=0426a1c07e) | Feb 20, 2021 |
| Lenovo    | MAHOBAY 31900003 STD        | Desktop     | [845f5a30c2](https://linux-hardware.org/?probe=845f5a30c2) | Feb 13, 2021 |
| HP        | 14                          | Notebook    | [d5382b721f](https://linux-hardware.org/?probe=d5382b721f) | Feb 11, 2021 |
| Toshiba   | Satellite S50t-B            | Notebook    | [2fe86bc977](https://linux-hardware.org/?probe=2fe86bc977) | Feb 06, 2021 |
| Toshiba   | Satellite S50t-B            | Notebook    | [ec72426035](https://linux-hardware.org/?probe=ec72426035) | Feb 05, 2021 |
| Toshiba   | Satellite S50t-B            | Notebook    | [f7709c05cb](https://linux-hardware.org/?probe=f7709c05cb) | Feb 05, 2021 |
| HP        | 14                          | Notebook    | [f27a999e26](https://linux-hardware.org/?probe=f27a999e26) | Feb 03, 2021 |
| Sony      | SVE15126CXS                 | Notebook    | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| Apple     | MacBookPro16,2              | Notebook    | [e3790fd911](https://linux-hardware.org/?probe=e3790fd911) | Jan 31, 2021 |
| Apple     | MacBookPro16,2              | Notebook    | [0ee13de953](https://linux-hardware.org/?probe=0ee13de953) | Jan 31, 2021 |
| Lenovo    | ThinkPad E15 20RD0088UE     | Notebook    | [d2bfe04a2b](https://linux-hardware.org/?probe=d2bfe04a2b) | Jan 28, 2021 |
| Lenovo    | ThinkCentre M58 7373C51     | Desktop     | [3e79476403](https://linux-hardware.org/?probe=3e79476403) | Jan 27, 2021 |
| HP        | ProBook 450 G5              | Notebook    | [e4b829fff8](https://linux-hardware.org/?probe=e4b829fff8) | Jan 26, 2021 |
| HP        | ProBook 450 G2              | Notebook    | [7db1cae3c0](https://linux-hardware.org/?probe=7db1cae3c0) | Jan 25, 2021 |
| HP        | ProBook 450 G5              | Notebook    | [0421fbf0d1](https://linux-hardware.org/?probe=0421fbf0d1) | Jan 25, 2021 |
| Lenovo    | ThinkPad T460 20FMS39800    | Notebook    | [7b4f78f648](https://linux-hardware.org/?probe=7b4f78f648) | Jan 10, 2021 |
| HP        | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| HP        | ENVY x360 m6 Convertible    | Convertible | [c3c2bbd2bc](https://linux-hardware.org/?probe=c3c2bbd2bc) | Jan 06, 2021 |
| Dell      | Inspiron 7391 2n1           | Convertible | [01da85c434](https://linux-hardware.org/?probe=01da85c434) | Dec 25, 2020 |
| Dell      | Inspiron 7391 2n1           | Convertible | [597b76daa1](https://linux-hardware.org/?probe=597b76daa1) | Dec 25, 2020 |
| Dell      | Latitude E6510              | Notebook    | [2557f813e4](https://linux-hardware.org/?probe=2557f813e4) | Dec 15, 2020 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [b04b3b207e](https://linux-hardware.org/?probe=b04b3b207e) | Dec 11, 2020 |
| Fujitsu   | LIFEBOOK E752               | Notebook    | [252afde67a](https://linux-hardware.org/?probe=252afde67a) | Dec 08, 2020 |
| Lenovo    | ThinkBook 15-IML 20RW       | Notebook    | [f84c7affac](https://linux-hardware.org/?probe=f84c7affac) | Dec 07, 2020 |
| Dell      | Latitude E7440              | Notebook    | [0d04075b3e](https://linux-hardware.org/?probe=0d04075b3e) | Dec 03, 2020 |
| Lenovo    | ThinkPad W500 40612HU       | Notebook    | [06465bf227](https://linux-hardware.org/?probe=06465bf227) | Dec 01, 2020 |
| Lenovo    | ThinkPad T60 1951WAT        | Notebook    | [4da418a597](https://linux-hardware.org/?probe=4da418a597) | Nov 28, 2020 |
| Dell      | Latitude E7450              | Notebook    | [20ee05f0fa](https://linux-hardware.org/?probe=20ee05f0fa) | Nov 27, 2020 |
| Dell      | Latitude E7440              | Notebook    | [9627b61c6f](https://linux-hardware.org/?probe=9627b61c6f) | Nov 25, 2020 |
| Dell      | Latitude E7450              | Notebook    | [e9a83f5dc5](https://linux-hardware.org/?probe=e9a83f5dc5) | Nov 24, 2020 |
| HP        | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| HP        | EliteBook 2540p             | Notebook    | [00a011fa83](https://linux-hardware.org/?probe=00a011fa83) | Nov 22, 2020 |
| HP        | EliteBook 2540p             | Notebook    | [12f4630385](https://linux-hardware.org/?probe=12f4630385) | Nov 22, 2020 |
| Microsoft | Surface Pro 3               | Tablet      | [eb17673652](https://linux-hardware.org/?probe=eb17673652) | Nov 21, 2020 |
| Lenovo    | ThinkPad E560 20EV0010UK    | Notebook    | [a52f064714](https://linux-hardware.org/?probe=a52f064714) | Nov 19, 2020 |
| Dell      | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| HP        | 650                         | Notebook    | [67e06d1514](https://linux-hardware.org/?probe=67e06d1514) | Nov 09, 2020 |
| HP        | Pavilion g6                 | Notebook    | [98124ff6a4](https://linux-hardware.org/?probe=98124ff6a4) | Nov 08, 2020 |
| HP        | EliteBook 8470p             | Notebook    | [847807840d](https://linux-hardware.org/?probe=847807840d) | Nov 05, 2020 |
| HP        | ProBook 6560b               | Notebook    | [934ffc99e6](https://linux-hardware.org/?probe=934ffc99e6) | Oct 30, 2020 |
| Dell      | 07N90W A01                  | Desktop     | [127c1a4946](https://linux-hardware.org/?probe=127c1a4946) | Oct 29, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [2b138e461a](https://linux-hardware.org/?probe=2b138e461a) | Oct 26, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [4460c27fd7](https://linux-hardware.org/?probe=4460c27fd7) | Oct 26, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [b647bae107](https://linux-hardware.org/?probe=b647bae107) | Oct 24, 2020 |
| Apple     | MacBookAir6,2               | Notebook    | [3509d2f6e3](https://linux-hardware.org/?probe=3509d2f6e3) | Oct 22, 2020 |
| Toshiba   | PORTEGE Z30-B               | Notebook    | [d7c9922a29](https://linux-hardware.org/?probe=d7c9922a29) | Oct 21, 2020 |
| HP        | ProBook 4340s               | Notebook    | [3db4ff09f4](https://linux-hardware.org/?probe=3db4ff09f4) | Oct 18, 2020 |
| Dell      | Latitude E6540              | Notebook    | [36688dde6e](https://linux-hardware.org/?probe=36688dde6e) | Oct 06, 2020 |
| HP        | 650                         | Notebook    | [1ea9bf783e](https://linux-hardware.org/?probe=1ea9bf783e) | Oct 03, 2020 |
| HP        | ProBook 450 G5              | Notebook    | [94eb24ff74](https://linux-hardware.org/?probe=94eb24ff74) | Oct 02, 2020 |
| Dell      | Latitude E4300              | Notebook    | [12b944fb30](https://linux-hardware.org/?probe=12b944fb30) | Oct 02, 2020 |
| HP        | ProBook 450 G5              | Notebook    | [cb2cef5fcf](https://linux-hardware.org/?probe=cb2cef5fcf) | Oct 01, 2020 |
| Lenovo    | ThinkPad T440p 20AWS0DU0... | Notebook    | [caf12cb57f](https://linux-hardware.org/?probe=caf12cb57f) | Sep 30, 2020 |
| Lenovo    | ThinkPad T440p 20AWS0DU0... | Notebook    | [d3cc62a7f5](https://linux-hardware.org/?probe=d3cc62a7f5) | Sep 30, 2020 |
| Dell      | Latitude E7450              | Notebook    | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell      | Latitude E7450              | Notebook    | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| HP        | ENVY x360 m6 Convertible    | Convertible | [974d6d3289](https://linux-hardware.org/?probe=974d6d3289) | Sep 29, 2020 |
| Samsung   | QX311/QX411/QX412/QX511     | Notebook    | [b6f7494e44](https://linux-hardware.org/?probe=b6f7494e44) | Sep 21, 2020 |
| HP        | 650                         | Notebook    | [278a9afdeb](https://linux-hardware.org/?probe=278a9afdeb) | Sep 21, 2020 |
| Dell      | Vostro 14-3468              | Notebook    | [4ab76fd5c2](https://linux-hardware.org/?probe=4ab76fd5c2) | Sep 20, 2020 |
| HP        | 650                         | Notebook    | [8aaa8d7e4d](https://linux-hardware.org/?probe=8aaa8d7e4d) | Sep 19, 2020 |
| Samsung   | QX311/QX411/QX412/QX511     | Notebook    | [1ec83fe97e](https://linux-hardware.org/?probe=1ec83fe97e) | Sep 17, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [d6204bd9e2](https://linux-hardware.org/?probe=d6204bd9e2) | Sep 16, 2020 |
| HP        | ProBook 455 G7              | Notebook    | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP        | ENVY 17                     | Notebook    | [08285409ad](https://linux-hardware.org/?probe=08285409ad) | Sep 13, 2020 |
| HP        | ProBook 455 G7              | Notebook    | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| HP        | ENVY x360 m6 Convertible    | Convertible | [dd76cd9006](https://linux-hardware.org/?probe=dd76cd9006) | Sep 12, 2020 |
| HP        | ProBook 450 G7              | Notebook    | [85d0104e28](https://linux-hardware.org/?probe=85d0104e28) | Sep 10, 2020 |
| Dell      | Inspiron 15-3573            | Notebook    | [9be442a7dd](https://linux-hardware.org/?probe=9be442a7dd) | Sep 07, 2020 |
| HP        | 8433 11                     | Desktop     | [1d000792d8](https://linux-hardware.org/?probe=1d000792d8) | Sep 03, 2020 |
| HP        | ProBook 440 G7              | Notebook    | [1c4d1f875b](https://linux-hardware.org/?probe=1c4d1f875b) | Sep 01, 2020 |
| HP        | ProBook 4340s               | Notebook    | [f7580ed51b](https://linux-hardware.org/?probe=f7580ed51b) | Aug 31, 2020 |
| Dell      | 0D6H9T A01                  | Desktop     | [1f914ddd57](https://linux-hardware.org/?probe=1f914ddd57) | Aug 31, 2020 |
| Dell      | Latitude E7250              | Notebook    | [ff13c002c8](https://linux-hardware.org/?probe=ff13c002c8) | Aug 27, 2020 |
| HP        | EliteBook 820 G2            | Notebook    | [f35b20067d](https://linux-hardware.org/?probe=f35b20067d) | Aug 25, 2020 |
| Dell      | 0HY9JP A02                  | Desktop     | [19795140c8](https://linux-hardware.org/?probe=19795140c8) | Aug 22, 2020 |
| Dell      | 0HY9JP A02                  | Desktop     | [b739a3410a](https://linux-hardware.org/?probe=b739a3410a) | Aug 22, 2020 |
| HP        | Laptop 15-da2xxx            | Notebook    | [031606a1a9](https://linux-hardware.org/?probe=031606a1a9) | Aug 21, 2020 |
| Dell      | 0PP150 A00                  | Desktop     | [a990cf0ce7](https://linux-hardware.org/?probe=a990cf0ce7) | Aug 21, 2020 |
| Dell      | Latitude E7250              | Notebook    | [63024e0df6](https://linux-hardware.org/?probe=63024e0df6) | Aug 19, 2020 |
| HP        | ProBook 450 G7              | Notebook    | [8a5fc0bc23](https://linux-hardware.org/?probe=8a5fc0bc23) | Aug 13, 2020 |
| HP        | ProBook 440 G5              | Notebook    | [fa604583d6](https://linux-hardware.org/?probe=fa604583d6) | Aug 10, 2020 |
| HP        | ProBook 440 G5              | Notebook    | [255da50641](https://linux-hardware.org/?probe=255da50641) | Aug 10, 2020 |
| HP        | 0B4Ch D                     | Desktop     | [4053256264](https://linux-hardware.org/?probe=4053256264) | Aug 10, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | Notebook    | [930fbc43ed](https://linux-hardware.org/?probe=930fbc43ed) | Aug 09, 2020 |
| HP        | Pavilion Notebook           | Notebook    | [f62759a869](https://linux-hardware.org/?probe=f62759a869) | Aug 05, 2020 |
| Dell      | 0DR845                      | Desktop     | [e4ff6acb83](https://linux-hardware.org/?probe=e4ff6acb83) | Aug 01, 2020 |
| Dell      | 0DR845                      | Desktop     | [4b9fbd7a8f](https://linux-hardware.org/?probe=4b9fbd7a8f) | Aug 01, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [4af4cdfef7](https://linux-hardware.org/?probe=4af4cdfef7) | Jul 30, 2020 |
| HP        | ProBook 440 G7              | Notebook    | [4b38ecdae9](https://linux-hardware.org/?probe=4b38ecdae9) | Jul 28, 2020 |
| HP        | EliteBook 840 G2            | Notebook    | [9dbea8590b](https://linux-hardware.org/?probe=9dbea8590b) | Jul 19, 2020 |
| HP        | ProBook 450 G7              | Notebook    | [45478d9106](https://linux-hardware.org/?probe=45478d9106) | Jul 18, 2020 |
| HP        | 1589                        | Desktop     | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| HP        | Pavilion x360 Convertibl... | Convertible | [8ce6e9cb36](https://linux-hardware.org/?probe=8ce6e9cb36) | Jul 10, 2020 |
| HP        | ProBook 470 G2              | Notebook    | [c42c686ae8](https://linux-hardware.org/?probe=c42c686ae8) | Jul 09, 2020 |
| MOTION    | NVX00                       | Notebook    | [fd07831802](https://linux-hardware.org/?probe=fd07831802) | Jul 04, 2020 |
| HP        | ProBook 450 G3              | Notebook    | [a12518d58c](https://linux-hardware.org/?probe=a12518d58c) | Jun 30, 2020 |
| Dell      | Latitude E6440              | Notebook    | [a7fe187945](https://linux-hardware.org/?probe=a7fe187945) | Jun 28, 2020 |
| Haier     | Y11C                        | Notebook    | [6b98c2c449](https://linux-hardware.org/?probe=6b98c2c449) | Jun 23, 2020 |
| Gigabyte  | B450M S2H                   | Desktop     | [4e6a9e5117](https://linux-hardware.org/?probe=4e6a9e5117) | Jun 12, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | Notebook    | [8c8ed3d489](https://linux-hardware.org/?probe=8c8ed3d489) | Jun 06, 2020 |
| Haier     | Y11C                        | Notebook    | [7f9f93809f](https://linux-hardware.org/?probe=7f9f93809f) | Jun 01, 2020 |
| Gigabyte  | B250M-D3H-CF                | Desktop     | [f74cf1545a](https://linux-hardware.org/?probe=f74cf1545a) | May 21, 2020 |
| Dell      | Latitude E6410              | Notebook    | [60757c8504](https://linux-hardware.org/?probe=60757c8504) | May 21, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | Notebook    | [86a1d31e5c](https://linux-hardware.org/?probe=86a1d31e5c) | May 21, 2020 |
| Dell      | Latitude E7450              | Notebook    | [1031b89b4b](https://linux-hardware.org/?probe=1031b89b4b) | May 12, 2020 |
| HP        | EliteBook Folio 1040 G1     | Notebook    | [34b0697bf6](https://linux-hardware.org/?probe=34b0697bf6) | May 10, 2020 |
| Dell      | Latitude E6320              | Notebook    | [cedc2c5001](https://linux-hardware.org/?probe=cedc2c5001) | May 10, 2020 |
| Dell      | 0GU083 A00                  | Desktop     | [a31c9c5f4f](https://linux-hardware.org/?probe=a31c9c5f4f) | May 05, 2020 |
| Gigabyte  | Z170X-Gaming 7              | Desktop     | [e3400fb2b7](https://linux-hardware.org/?probe=e3400fb2b7) | May 04, 2020 |
| Dell      | 0PP150 A00                  | Desktop     | [51f69f1430](https://linux-hardware.org/?probe=51f69f1430) | May 02, 2020 |
| Lenovo    | ThinkCentre M57 6072W2A     | Desktop     | [d42ad893b6](https://linux-hardware.org/?probe=d42ad893b6) | May 01, 2020 |
| Lenovo    | ThinkCentre M57 6072W2A     | Desktop     | [366d3d0483](https://linux-hardware.org/?probe=366d3d0483) | May 01, 2020 |
| Dell      | 0PP150 A00                  | Desktop     | [f224ee60e5](https://linux-hardware.org/?probe=f224ee60e5) | Apr 30, 2020 |
| Acer      | Aspire E5-576               | Notebook    | [581af37cda](https://linux-hardware.org/?probe=581af37cda) | Apr 19, 2020 |
| Dell      | Latitude E5420              | Notebook    | [6d2ddeb934](https://linux-hardware.org/?probe=6d2ddeb934) | Apr 18, 2020 |
| HP        | EliteBook 6930p             | Notebook    | [ea52c08646](https://linux-hardware.org/?probe=ea52c08646) | Apr 09, 2020 |
| Dell      | Latitude E4300              | Notebook    | [5e38d54ea2](https://linux-hardware.org/?probe=5e38d54ea2) | Mar 18, 2020 |
| Dell      | 0XPDFK A01                  | Desktop     | [9434f7214c](https://linux-hardware.org/?probe=9434f7214c) | Mar 16, 2020 |
| Dell      | 0XPDFK A01                  | Desktop     | [4a53b5e634](https://linux-hardware.org/?probe=4a53b5e634) | Mar 11, 2020 |
| HP        | EliteBook 8440p             | Notebook    | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Lenovo    | ThinkBook 15-IML 20RW       | Notebook    | [3cd2a73254](https://linux-hardware.org/?probe=3cd2a73254) | Mar 09, 2020 |
| Dell      | 054KM3 A01                  | Desktop     | [857f976c7f](https://linux-hardware.org/?probe=857f976c7f) | Jan 29, 2020 |
| HP        | 1497                        | Desktop     | [fe24ec7591](https://linux-hardware.org/?probe=fe24ec7591) | Jan 28, 2020 |
| HP        | Pavilion dv7                | Notebook    | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| Dell      | 054KM3 A01                  | Desktop     | [f682ad8814](https://linux-hardware.org/?probe=f682ad8814) | Jan 21, 2020 |
| HP        | EliteBook 8470p             | Notebook    | [e257c71d0b](https://linux-hardware.org/?probe=e257c71d0b) | Jan 14, 2020 |
| HP        | ProBook 450 G3              | Notebook    | [f73167982a](https://linux-hardware.org/?probe=f73167982a) | Jan 01, 2020 |
| Acer      | Veriton X6620G v1.0         | Desktop     | [e921d3af77](https://linux-hardware.org/?probe=e921d3af77) | Dec 13, 2019 |
| Dell      | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| Dell      | Latitude XT3                | Notebook    | [4ccaa2e0e2](https://linux-hardware.org/?probe=4ccaa2e0e2) | Oct 29, 2019 |
| Lenovo    | ThinkPad T440 20B7S1NK05    | Notebook    | [310405c604](https://linux-hardware.org/?probe=310405c604) | Oct 29, 2019 |
| HP        | EliteBook 6930p             | Notebook    | [856fcded98](https://linux-hardware.org/?probe=856fcded98) | Oct 25, 2019 |
| HP        | Unknown                     | Notebook    | [25dd8af3ee](https://linux-hardware.org/?probe=25dd8af3ee) | Oct 22, 2019 |
| ASUSTek   | Q87M-E                      | Desktop     | [01f990ea56](https://linux-hardware.org/?probe=01f990ea56) | Oct 19, 2019 |
| Lenovo    | ThinkPad 10 20C3001QAU      | Tablet      | [b1cb7238da](https://linux-hardware.org/?probe=b1cb7238da) | Oct 04, 2019 |
| HP        | EliteBook 6930p             | Notebook    | [43c8f2b72c](https://linux-hardware.org/?probe=43c8f2b72c) | Sep 13, 2019 |
| HP        | EliteBook 6930p             | Notebook    | [964e933faf](https://linux-hardware.org/?probe=964e933faf) | Sep 13, 2019 |
| Samsung   | 940Z5L                      | Notebook    | [28c94787df](https://linux-hardware.org/?probe=28c94787df) | Sep 13, 2019 |
| AMI       | Unknown                     | Notebook    | [407590d103](https://linux-hardware.org/?probe=407590d103) | Sep 09, 2019 |
| HP        | ProBook 6470b               | Notebook    | [81e17acdb1](https://linux-hardware.org/?probe=81e17acdb1) | Aug 02, 2019 |
| HP        | EliteBook 840 G3            | Notebook    | [b419735d70](https://linux-hardware.org/?probe=b419735d70) | Jul 04, 2019 |
| Sony      | VPCCB490X                   | Notebook    | [ed39416136](https://linux-hardware.org/?probe=ed39416136) | Jun 22, 2019 |
| Haier     | Y11C                        | Notebook    | [ab6b2cf0e5](https://linux-hardware.org/?probe=ab6b2cf0e5) | Jun 20, 2019 |
| Haier     | Y11C                        | Notebook    | [74a3547ed6](https://linux-hardware.org/?probe=74a3547ed6) | Jun 20, 2019 |
| HP        | 304Ah                       | Desktop     | [4f72bfd1f5](https://linux-hardware.org/?probe=4f72bfd1f5) | May 13, 2019 |
| Dell      | Latitude E6420              | Notebook    | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell      | Latitude E6420              | Notebook    | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Haier     | Y11B                        | Notebook    | [d90f70d18f](https://linux-hardware.org/?probe=d90f70d18f) | May 11, 2019 |
| Dell      | 054KM3 A01                  | Desktop     | [144815a4e9](https://linux-hardware.org/?probe=144815a4e9) | Jan 15, 2019 |
| Dell      | 054KM3 A01                  | Desktop     | [f83bcddf2e](https://linux-hardware.org/?probe=f83bcddf2e) | Jan 08, 2019 |
| Dell      | 054KM3 A01                  | Desktop     | [404e699144](https://linux-hardware.org/?probe=404e699144) | Jan 08, 2019 |
| Haier     | Y11B                        | Notebook    | [e359a25a69](https://linux-hardware.org/?probe=e359a25a69) | Nov 18, 2018 |
| Haier     | Y11B                        | Notebook    | [13e5308d20](https://linux-hardware.org/?probe=13e5308d20) | Nov 18, 2018 |
| HP        | Pavilion Notebook           | Notebook    | [7e2949f7da](https://linux-hardware.org/?probe=7e2949f7da) | Nov 11, 2018 |
| Acer      | Aspire 5733                 | Notebook    | [970a40e3d0](https://linux-hardware.org/?probe=970a40e3d0) | Oct 23, 2018 |
| ASUSTek   | K53U                        | Notebook    | [f644624e98](https://linux-hardware.org/?probe=f644624e98) | Oct 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 85        | 24.08%  |
| Ubuntu 22.04       | 37        | 10.48%  |
| Ubuntu 18.04       | 25        | 7.08%   |
| Debian 11          | 11        | 3.12%   |
| Arch               | 8         | 2.27%   |
| OpenMandriva 4.3   | 7         | 1.98%   |
| KDE neon 20.04     | 7         | 1.98%   |
| Zorin 16           | 6         | 1.7%    |
| Ubuntu 22.10       | 6         | 1.7%    |
| Ubuntu 21.04       | 6         | 1.7%    |
| Pop!_OS 22.04      | 6         | 1.7%    |
| Debian 10          | 6         | 1.7%    |
| Zorin 15           | 5         | 1.42%   |
| Pop!_OS 20.04      | 5         | 1.42%   |
| Ubuntu 19.04       | 4         | 1.13%   |
| Pop!_OS 21.04      | 4         | 1.13%   |
| OpenMandriva 4.2   | 4         | 1.13%   |
| Linux Mint 21.1    | 4         | 1.13%   |
| Linux Mint 20      | 4         | 1.13%   |
| Fedora 36          | 4         | 1.13%   |
| Elementary 6.1     | 4         | 1.13%   |
| ArcoLinux Rolling  | 4         | 1.13%   |
| Ubuntu 21.10       | 3         | 0.85%   |
| Pop!_OS 20.10      | 3         | 0.85%   |
| OpenMandriva 23.01 | 3         | 0.85%   |
| Manjaro            | 3         | 0.85%   |
| Linux Mint 20.3    | 3         | 0.85%   |
| Linux Mint 20.2    | 3         | 0.85%   |
| Kubuntu 20.04      | 3         | 0.85%   |
| Fedora 38          | 3         | 0.85%   |
| Fedora 37          | 3         | 0.85%   |
| Fedora 34          | 3         | 0.85%   |
| Fedora 33          | 3         | 0.85%   |
| Xero Rolling       | 2         | 0.57%   |
| Ubuntu 20.10       | 2         | 0.57%   |
| Parrot 4.10        | 2         | 0.57%   |
| OpenMandriva 23.03 | 2         | 0.57%   |
| Linux Mint 20.1    | 2         | 0.57%   |
| Linux Mint 19.3    | 2         | 0.57%   |
| Kubuntu 22.04      | 2         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 170       | 49.42%  |
| Linux Mint   | 18        | 5.23%   |
| Fedora       | 18        | 5.23%   |
| Pop!_OS      | 17        | 4.94%   |
| OpenMandriva | 15        | 4.36%   |
| Debian       | 14        | 4.07%   |
| Zorin        | 12        | 3.49%   |
| Kali         | 9         | 2.62%   |
| Arch         | 9         | 2.62%   |
| Kubuntu      | 8         | 2.33%   |
| KDE neon     | 7         | 2.03%   |
| Manjaro      | 6         | 1.74%   |
| ArcoLinux    | 5         | 1.45%   |
| Elementary   | 4         | 1.16%   |
| Ubuntu Unity | 3         | 0.87%   |
| Parrot       | 3         | 0.87%   |
| Endless      | 3         | 0.87%   |
| Xero         | 2         | 0.58%   |
| ROSA         | 2         | 0.58%   |
| CentOS       | 2         | 0.58%   |
| Artix        | 2         | 0.58%   |
| Xubuntu      | 1         | 0.29%   |
| Ubuntu MATE  | 1         | 0.29%   |
| Rocky Linux  | 1         | 0.29%   |
| RHEL         | 1         | 0.29%   |
| Oracle Linux | 1         | 0.29%   |
| Nobara       | 1         | 0.29%   |
| Lubuntu      | 1         | 0.29%   |
| LMDE         | 1         | 0.29%   |
| LinuxFX      | 1         | 0.29%   |
| EndeavourOS  | 1         | 0.29%   |
| Deepin       | 1         | 0.29%   |
| Clear Linux  | 1         | 0.29%   |
| BlackPanther | 1         | 0.29%   |
| Alpine       | 1         | 0.29%   |
| AlmaLinux    | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 10        | 2.67%   |
| 5.15.0-46-generic        | 8         | 2.13%   |
| 5.16.7-desktop-1omv4003  | 7         | 1.87%   |
| 5.19.0-42-generic        | 6         | 1.6%    |
| 5.11.0-37-generic        | 6         | 1.6%    |
| 5.4.106-1-pve            | 5         | 1.33%   |
| 5.15.0-47-generic        | 5         | 1.33%   |
| 5.8.0-59-generic         | 4         | 1.07%   |
| 5.4.0-54-generic         | 4         | 1.07%   |
| 5.4.0-52-generic         | 4         | 1.07%   |
| 5.4.0-48-generic         | 4         | 1.07%   |
| 5.4.0-47-generic         | 4         | 1.07%   |
| 5.4.0-40-generic         | 4         | 1.07%   |
| 5.4.0-26-generic         | 4         | 1.07%   |
| 5.15.0-58-generic        | 4         | 1.07%   |
| 5.15.0-56-generic        | 4         | 1.07%   |
| 5.11.0-43-generic        | 4         | 1.07%   |
| 5.11.0-27-generic        | 4         | 1.07%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.07%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.8%    |
| 5.8.0-7630-generic       | 3         | 0.8%    |
| 5.8.0-44-generic         | 3         | 0.8%    |
| 5.8.0-41-generic         | 3         | 0.8%    |
| 5.4.0-7642-generic       | 3         | 0.8%    |
| 5.4.0-58-generic         | 3         | 0.8%    |
| 5.3.0-28-generic         | 3         | 0.8%    |
| 5.19.0-43-generic        | 3         | 0.8%    |
| 5.19.0-41-generic        | 3         | 0.8%    |
| 5.15.0-53-generic        | 3         | 0.8%    |
| 5.15.0-48-generic        | 3         | 0.8%    |
| 5.15.0-41-generic        | 3         | 0.8%    |
| 5.13.0-39-generic        | 3         | 0.8%    |
| 5.13.0-30-generic        | 3         | 0.8%    |
| 5.11.0-7620-generic      | 3         | 0.8%    |
| 5.11.0-41-generic        | 3         | 0.8%    |
| 5.11.0-40-generic        | 3         | 0.8%    |
| 5.11.0-38-generic        | 3         | 0.8%    |
| 5.0.0-23-generic         | 3         | 0.8%    |
| 6.2.6-desktop-1omv2390   | 2         | 0.53%   |
| 6.1.0-kali9-amd64        | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 17.98%  |
| 5.15.0  | 44        | 12.36%  |
| 5.11.0  | 31        | 8.71%   |
| 5.19.0  | 25        | 7.02%   |
| 5.8.0   | 23        | 6.46%   |
| 5.13.0  | 19        | 5.34%   |
| 4.15.0  | 16        | 4.49%   |
| 5.0.0   | 11        | 3.09%   |
| 5.3.0   | 7         | 1.97%   |
| 5.16.7  | 7         | 1.97%   |
| 5.10.0  | 6         | 1.69%   |
| 5.4.106 | 5         | 1.4%    |
| 4.18.0  | 5         | 1.4%    |
| 6.1.1   | 4         | 1.12%   |
| 5.11.22 | 4         | 1.12%   |
| 5.10.14 | 4         | 1.12%   |
| 6.2.6   | 3         | 0.84%   |
| 6.0.8   | 3         | 0.84%   |
| 6.2.0   | 2         | 0.56%   |
| 6.1.0   | 2         | 0.56%   |
| 6.0.12  | 2         | 0.56%   |
| 5.9.8   | 2         | 0.56%   |
| 5.7.0   | 2         | 0.56%   |
| 5.19.9  | 2         | 0.56%   |
| 5.19.13 | 2         | 0.56%   |
| 5.18.0  | 2         | 0.56%   |
| 5.16.15 | 2         | 0.56%   |
| 5.13.4  | 2         | 0.56%   |
| 5.13.19 | 2         | 0.56%   |
| 3.10.0  | 2         | 0.56%   |
| 6.3.2   | 1         | 0.28%   |
| 6.2.14  | 1         | 0.28%   |
| 6.2.11  | 1         | 0.28%   |
| 6.2.10  | 1         | 0.28%   |
| 6.1.7   | 1         | 0.28%   |
| 6.1.20  | 1         | 0.28%   |
| 6.1.12  | 1         | 0.28%   |
| 6.0.6   | 1         | 0.28%   |
| 6.0.19  | 1         | 0.28%   |
| 6.0.0   | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 20.85%  |
| 5.15    | 46        | 12.96%  |
| 5.11    | 35        | 9.86%   |
| 5.19    | 30        | 8.45%   |
| 5.13    | 27        | 7.61%   |
| 5.8     | 24        | 6.76%   |
| 4.15    | 16        | 4.51%   |
| 5.10    | 13        | 3.66%   |
| 5.0     | 11        | 3.1%    |
| 5.16    | 10        | 2.82%   |
| 6.1     | 9         | 2.54%   |
| 6.2     | 8         | 2.25%   |
| 6.0     | 8         | 2.25%   |
| 5.3     | 8         | 2.25%   |
| 4.18    | 6         | 1.69%   |
| 5.7     | 5         | 1.41%   |
| 5.18    | 5         | 1.41%   |
| 5.14    | 4         | 1.13%   |
| 5.9     | 3         | 0.85%   |
| 5.17    | 3         | 0.85%   |
| 3.10    | 3         | 0.85%   |
| 5.12    | 2         | 0.56%   |
| 6.3     | 1         | 0.28%   |
| 5.6     | 1         | 0.28%   |
| 5.2     | 1         | 0.28%   |
| 4.9     | 1         | 0.28%   |
| 4.19    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 330       | 98.51%  |
| i686   | 5         | 1.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 213       | 61.92%  |
| Unknown    | 37        | 10.76%  |
| KDE5       | 36        | 10.47%  |
| X-Cinnamon | 16        | 4.65%   |
| XFCE       | 11        | 3.2%    |
| KDE        | 8         | 2.33%   |
| MATE       | 6         | 1.74%   |
| Pantheon   | 4         | 1.16%   |
| i3         | 4         | 1.16%   |
| Unity      | 3         | 0.87%   |
| KDE4       | 3         | 0.87%   |
| LXQt       | 1         | 0.29%   |
| Hyprland   | 1         | 0.29%   |
| Deepin     | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 246       | 71.93%  |
| Wayland | 64        | 18.71%  |
| Unknown | 24        | 7.02%   |
| Tty     | 8         | 2.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 166       | 48.68%  |
| GDM3    | 69        | 20.23%  |
| GDM     | 48        | 14.08%  |
| SDDM    | 35        | 10.26%  |
| LightDM | 15        | 4.4%    |
| TDM     | 5         | 1.47%   |
| XDM     | 1         | 0.29%   |
| LXDM    | 1         | 0.29%   |
| KDM     | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 291       | 85.84%  |
| Unknown | 23        | 6.78%   |
| en_GB   | 16        | 4.72%   |
| en_PK   | 3         | 0.88%   |
| en_IN   | 2         | 0.59%   |
| ur_PK   | 1         | 0.29%   |
| en_ZA   | 1         | 0.29%   |
| en_CA   | 1         | 0.29%   |
| C       | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 182       | 53.22%  |
| EFI  | 160       | 46.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 276       | 80.23%  |
| Btrfs    | 20        | 5.81%   |
| Overlay  | 16        | 4.65%   |
| Tmpfs    | 11        | 3.2%    |
| Zfs      | 7         | 2.03%   |
| Xfs      | 7         | 2.03%   |
| Unknown  | 6         | 1.74%   |
| Reiserfs | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 186       | 54.87%  |
| GPT     | 118       | 34.81%  |
| MBR     | 35        | 10.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 297       | 86.84%  |
| Yes       | 45        | 13.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 218       | 63.74%  |
| Yes       | 124       | 36.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 124       | 37.01%  |
| Dell                | 95        | 28.36%  |
| Lenovo              | 47        | 14.03%  |
| ASUSTek Computer    | 12        | 3.58%   |
| Gigabyte Technology | 11        | 3.28%   |
| Haier               | 7         | 2.09%   |
| Apple               | 6         | 1.79%   |
| Acer                | 6         | 1.79%   |
| Toshiba             | 4         | 1.19%   |
| Sony                | 3         | 0.9%    |
| Samsung Electronics | 3         | 0.9%    |
| Shuttle             | 2         | 0.6%    |
| Unknown             | 2         | 0.6%    |
| Timi                | 1         | 0.3%    |
| Quanta              | 1         | 0.3%    |
| MSI                 | 1         | 0.3%    |
| MOTION              | 1         | 0.3%    |
| Microsoft           | 1         | 0.3%    |
| KEIAN               | 1         | 0.3%    |
| Inventec            | 1         | 0.3%    |
| Intel               | 1         | 0.3%    |
| Google              | 1         | 0.3%    |
| Fujitsu             | 1         | 0.3%    |
| Clevo               | 1         | 0.3%    |
| AMI                 | 1         | 0.3%    |
| Alienware           | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| HP ProBook 450 G7                | 5         | 1.49%   |
| HP EliteBook 8470p               | 5         | 1.49%   |
| HP EliteBook 840 G3              | 5         | 1.49%   |
| Dell Latitude E7450              | 5         | 1.49%   |
| Unknown                          | 5         | 1.49%   |
| Haier Y11C                       | 4         | 1.19%   |
| Dell Precision WorkStation T7500 | 4         | 1.19%   |
| Dell Latitude E6420              | 4         | 1.19%   |
| HP ProLiant DL380p Gen8          | 3         | 0.9%    |
| HP ProBook 450 G5                | 3         | 0.9%    |
| HP EliteBook 840 G2              | 3         | 0.9%    |
| Haier Y11B                       | 3         | 0.9%    |
| Dell Precision WorkStation T3500 | 3         | 0.9%    |
| Shuttle DS81D                    | 2         | 0.6%    |
| Lenovo ThinkBook 15-IML 20RW     | 2         | 0.6%    |
| Lenovo ThinkBook 15-IIL 20SM     | 2         | 0.6%    |
| Lenovo ThinkBook 15 G2 ITL 20VE  | 2         | 0.6%    |
| HP ZBook 15 G3                   | 2         | 0.6%    |
| HP ProDesk 600 G1 SFF            | 2         | 0.6%    |
| HP ProDesk 400 G7 Microtower PC  | 2         | 0.6%    |
| HP ProBook 450 G8 Notebook PC    | 2         | 0.6%    |
| HP ProBook 450 G3                | 2         | 0.6%    |
| HP ProBook 440 G7                | 2         | 0.6%    |
| HP Pavilion Notebook             | 2         | 0.6%    |
| HP Pavilion g6                   | 2         | 0.6%    |
| HP Pavilion dv6                  | 2         | 0.6%    |
| HP Notebook                      | 2         | 0.6%    |
| HP Laptop 15s-fq5xxx             | 2         | 0.6%    |
| HP ENVY x360 m6 Convertible      | 2         | 0.6%    |
| HP EliteBook Folio 9470m         | 2         | 0.6%    |
| HP EliteBook 850 G6              | 2         | 0.6%    |
| HP EliteBook 8440p               | 2         | 0.6%    |
| HP EliteBook 840 G1              | 2         | 0.6%    |
| HP EliteBook 6930p               | 2         | 0.6%    |
| HP Compaq 8100 Elite SFF PC      | 2         | 0.6%    |
| HP 650                           | 2         | 0.6%    |
| Gigabyte Z590 UD AC              | 2         | 0.6%    |
| Gigabyte Q87M-D2H                | 2         | 0.6%    |
| Gigabyte A520M S2H               | 2         | 0.6%    |
| Dell XPS 630i                    | 2         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 39        | 11.64%  |
| HP EliteBook       | 34        | 10.15%  |
| HP ProBook         | 26        | 7.76%   |
| Lenovo ThinkPad    | 23        | 6.87%   |
| Dell Inspiron      | 21        | 6.27%   |
| HP Pavilion        | 14        | 4.18%   |
| Dell Precision     | 13        | 3.88%   |
| HP Compaq          | 11        | 3.28%   |
| Dell OptiPlex      | 9         | 2.69%   |
| HP Laptop          | 8         | 2.39%   |
| Dell Vostro        | 8         | 2.39%   |
| Lenovo ThinkBook   | 6         | 1.79%   |
| HP ProDesk         | 6         | 1.79%   |
| HP ENVY            | 6         | 1.79%   |
| Lenovo ThinkCentre | 5         | 1.49%   |
| Lenovo IdeaPad     | 5         | 1.49%   |
| Unknown            | 5         | 1.49%   |
| HP ProLiant        | 4         | 1.19%   |
| Haier Y11C         | 4         | 1.19%   |
| Haier Y11B         | 3         | 0.9%    |
| Acer Aspire        | 3         | 0.9%    |
| Toshiba Satellite  | 2         | 0.6%    |
| Toshiba PORTEGE    | 2         | 0.6%    |
| Shuttle DS81D      | 2         | 0.6%    |
| Lenovo Legion      | 2         | 0.6%    |
| HP ZBook           | 2         | 0.6%    |
| HP Notebook        | 2         | 0.6%    |
| HP 650             | 2         | 0.6%    |
| Gigabyte Z590      | 2         | 0.6%    |
| Gigabyte Q87M-D2H  | 2         | 0.6%    |
| Gigabyte A520M     | 2         | 0.6%    |
| Dell XPS           | 2         | 0.6%    |
| Dell G3            | 2         | 0.6%    |
| ASUS VivoBook      | 2         | 0.6%    |
| ASUS TUF           | 2         | 0.6%    |
| Apple MacBookPro11 | 2         | 0.6%    |
| Acer Veriton       | 2         | 0.6%    |
| Timi TM1613        | 1         | 0.3%    |
| Sony VPCEA26FG     | 1         | 0.3%    |
| Sony VPCCB490X     | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 39        | 11.64%  |
| 2020    | 30        | 8.96%   |
| 2012    | 30        | 8.96%   |
| 2019    | 29        | 8.66%   |
| 2014    | 28        | 8.36%   |
| 2013    | 27        | 8.06%   |
| 2016    | 26        | 7.76%   |
| 2017    | 22        | 6.57%   |
| 2018    | 19        | 5.67%   |
| 2010    | 19        | 5.67%   |
| 2021    | 16        | 4.78%   |
| 2015    | 16        | 4.78%   |
| 2009    | 10        | 2.99%   |
| 2008    | 10        | 2.99%   |
| 2007    | 5         | 1.49%   |
| 2006    | 4         | 1.19%   |
| 2022    | 3         | 0.9%    |
| 2023    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 238       | 71.04%  |
| Desktop     | 81        | 24.18%  |
| Convertible | 8         | 2.39%   |
| Server      | 4         | 1.19%   |
| Tablet      | 3         | 0.9%    |
| Mini pc     | 1         | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 317       | 94.35%  |
| Enabled  | 19        | 5.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 334       | 99.7%   |
| Yes  | 1         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 97        | 28.7%   |
| 16.01-24.0      | 71        | 21.01%  |
| 3.01-4.0        | 65        | 19.23%  |
| 8.01-16.0       | 65        | 19.23%  |
| 32.01-64.0      | 21        | 6.21%   |
| 64.01-256.0     | 7         | 2.07%   |
| 1.01-2.0        | 7         | 2.07%   |
| 24.01-32.0      | 4         | 1.18%   |
| More than 256.0 | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 113       | 31.04%  |
| 1.01-2.0    | 113       | 31.04%  |
| 4.01-8.0    | 55        | 15.11%  |
| 3.01-4.0    | 52        | 14.29%  |
| 8.01-16.0   | 19        | 5.22%   |
| 0.51-1.0    | 7         | 1.92%   |
| 16.01-24.0  | 2         | 0.55%   |
| 32.01-64.0  | 1         | 0.27%   |
| 64.01-256.0 | 1         | 0.27%   |
| Unknown     | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 223       | 64.83%  |
| 2      | 86        | 25%     |
| 3      | 16        | 4.65%   |
| 6      | 5         | 1.45%   |
| 5      | 4         | 1.16%   |
| 4      | 4         | 1.16%   |
| 13     | 1         | 0.29%   |
| 11     | 1         | 0.29%   |
| 10     | 1         | 0.29%   |
| 9      | 1         | 0.29%   |
| 8      | 1         | 0.29%   |
| 0      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 231       | 68.75%  |
| Yes       | 105       | 31.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 91.64%  |
| No        | 28        | 8.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 86.35%  |
| No        | 46        | 13.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 61.4%   |
| No        | 132       | 38.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Pakistan | 335       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Lahore         | 110       | 32.16%  |
| Karachi        | 75        | 21.93%  |
| Islamabad      | 57        | 16.67%  |
| Rawalpindi     | 24        | 7.02%   |
| Multan         | 8         | 2.34%   |
| Faisalabad     | 8         | 2.34%   |
| Peshawar       | 7         | 2.05%   |
| Mirpur         | 7         | 2.05%   |
| Sargodha       | 3         | 0.88%   |
| Jhelum         | 3         | 0.88%   |
| Bahawalpur     | 3         | 0.88%   |
| Abbottabad     | 3         | 0.88%   |
| Sialkot        | 2         | 0.58%   |
| Kamoke         | 2         | 0.58%   |
| Hyderabad      | 2         | 0.58%   |
| Dina           | 2         | 0.58%   |
| Wah            | 1         | 0.29%   |
| Vehari         | 1         | 0.29%   |
| Topi           | 1         | 0.29%   |
| Taunsa         | 1         | 0.29%   |
| Tando Allahyar | 1         | 0.29%   |
| Swabi          | 1         | 0.29%   |
| Sukkur         | 1         | 0.29%   |
| Sheikhupura    | 1         | 0.29%   |
| Sahiwal        | 1         | 0.29%   |
| Rahim Yar Khan | 1         | 0.29%   |
| Pindi Gheb     | 1         | 0.29%   |
| Mardan         | 1         | 0.29%   |
| Layyah         | 1         | 0.29%   |
| Layari         | 1         | 0.29%   |
| Larkana        | 1         | 0.29%   |
| Kohat          | 1         | 0.29%   |
| Khanewal       | 1         | 0.29%   |
| Hazro City     | 1         | 0.29%   |
| Hassan Abdal   | 1         | 0.29%   |
| Gujranwala     | 1         | 0.29%   |
| Ghotki         | 1         | 0.29%   |
| Daultala       | 1         | 0.29%   |
| Daska Kalan    | 1         | 0.29%   |
| Dadu           | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 81        | 127    | 17.09%  |
| WDC                          | 72        | 100    | 15.19%  |
| Samsung Electronics          | 59        | 72     | 12.45%  |
| Toshiba                      | 37        | 38     | 7.81%   |
| Hitachi                      | 23        | 31     | 4.85%   |
| Kingston                     | 18        | 20     | 3.8%    |
| SanDisk                      | 16        | 17     | 3.38%   |
| Intel                        | 13        | 19     | 2.74%   |
| Unknown                      | 12        | 15     | 2.53%   |
| SK hynix                     | 11        | 15     | 2.32%   |
| Transcend                    | 10        | 10     | 2.11%   |
| HGST                         | 10        | 11     | 2.11%   |
| Micron Technology            | 9         | 10     | 1.9%    |
| HS-SSD-E100                  | 9         | 11     | 1.9%    |
| LITEON                       | 8         | 9      | 1.69%   |
| Hewlett-Packard              | 8         | 19     | 1.69%   |
| A-DATA Technology            | 8         | 8      | 1.69%   |
| Lexar                        | 6         | 8      | 1.27%   |
| Hajaan                       | 6         | 9      | 1.27%   |
| Silicon Motion               | 5         | 5      | 1.05%   |
| LITEONIT                     | 5         | 8      | 1.05%   |
| Crucial                      | 5         | 5      | 1.05%   |
| Apple                        | 5         | 6      | 1.05%   |
| KIOXIA                       | 4         | 4      | 0.84%   |
| Maxtor                       | 3         | 3      | 0.63%   |
| LaCie                        | 3         | 3      | 0.63%   |
| China                        | 3         | 4      | 0.63%   |
| SPCC                         | 2         | 2      | 0.42%   |
| Netac                        | 2         | 2      | 0.42%   |
| Fujitsu                      | 2         | 2      | 0.42%   |
| ZTE                          | 1         | 1      | 0.21%   |
| Vaseky                       | 1         | 1      | 0.21%   |
| Toshiba America Info Systems | 1         | 1      | 0.21%   |
| Team                         | 1         | 1      | 0.21%   |
| PNY                          | 1         | 2      | 0.21%   |
| Phison                       | 1         | 2      | 0.21%   |
| PHD 3.0                      | 1         | 1      | 0.21%   |
| MARSHAL                      | 1         | 1      | 0.21%   |
| Kingsand                     | 1         | 1      | 0.21%   |
| KingFast                     | 1         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST3000NXCLAR3000 3TB          | 7         | 1.34%   |
| Seagate ST1000LM035-1RK172 1TB        | 7         | 1.34%   |
| WDC WD10SPZX-60Z10T0 1TB              | 6         | 1.15%   |
| Toshiba MQ04ABF100 1TB                | 6         | 1.15%   |
| Toshiba MQ01ABF050 500GB              | 6         | 1.15%   |
| HP MB2000EBZQC 2TB                    | 6         | 1.15%   |
| Hajaan SSD 256G                       | 6         | 1.15%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 0.96%   |
| Samsung SSD PM830 2.5 7mm 256GB       | 5         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 0.77%   |
| Samsung MZALQ512HALU-000L1 512GB      | 4         | 0.77%   |
| Lexar 256GB SSD                       | 4         | 0.77%   |
| HS-SSD-E100 128G                      | 4         | 0.77%   |
| WDC WD10SPZX-75Z10T3 1TB              | 3         | 0.58%   |
| WDC PC SN530 NVMe 256GB               | 3         | 0.58%   |
| Unknown MMC Card  32GB                | 3         | 0.58%   |
| Toshiba MQ01ACF050 500GB              | 3         | 0.58%   |
| Silicon Motion NVMe SSD Drive 512GB   | 3         | 0.58%   |
| Seagate ST9250311CS 250GB             | 3         | 0.58%   |
| Seagate ST8000DM004-2CX188 8TB        | 3         | 0.58%   |
| Seagate ST6000NM0024 6TB              | 3         | 0.58%   |
| Seagate ST500LM000-1EJ162 500GB       | 3         | 0.58%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 0.58%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD  | 3         | 0.58%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 3         | 0.58%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB SSD | 3         | 0.58%   |
| LITEON CS1-SP32 32GB SSD              | 3         | 0.58%   |
| LaCie Rugged USB-C 1TB                | 3         | 0.58%   |
| Intel SSDSA2M080G2GN 80GB             | 3         | 0.58%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 0.58%   |
| Hitachi HTS545032B9A300 320GB         | 3         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 0.38%   |
| WDC WD5002ABYS-02B1B0 500GB           | 2         | 0.38%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 0.38%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 2         | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2         | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2         | 0.38%   |
| WDC WD10SPZX-24Z10 1TB                | 2         | 0.38%   |
| WDC WD Elements 320GB                 | 2         | 0.38%   |
| Unknown MMC Card  64GB                | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 127    | 35.68%  |
| WDC                 | 61        | 81     | 26.87%  |
| Toshiba             | 30        | 31     | 13.22%  |
| Hitachi             | 23        | 31     | 10.13%  |
| HGST                | 10        | 11     | 4.41%   |
| Hewlett-Packard     | 7         | 18     | 3.08%   |
| Samsung Electronics | 6         | 7      | 2.64%   |
| Maxtor              | 3         | 3      | 1.32%   |
| Fujitsu             | 2         | 2      | 0.88%   |
| Unknown             | 1         | 1      | 0.44%   |
| PHD 3.0             | 1         | 1      | 0.44%   |
| MARSHAL             | 1         | 1      | 0.44%   |
| KESU                | 1         | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 39     | 23.03%  |
| Kingston            | 13        | 15     | 8.55%   |
| SanDisk             | 11        | 11     | 7.24%   |
| SK hynix            | 9         | 13     | 5.92%   |
| LITEON              | 8         | 9      | 5.26%   |
| WDC                 | 7         | 10     | 4.61%   |
| Intel               | 7         | 8      | 4.61%   |
| Micron Technology   | 6         | 7      | 3.95%   |
| Lexar               | 6         | 8      | 3.95%   |
| Hajaan              | 6         | 9      | 3.95%   |
| A-DATA Technology   | 6         | 6      | 3.95%   |
| Transcend           | 5         | 5      | 3.29%   |
| LITEONIT            | 5         | 8      | 3.29%   |
| Crucial             | 5         | 5      | 3.29%   |
| Toshiba             | 4         | 4      | 2.63%   |
| HS-SSD-E100         | 3         | 3      | 1.97%   |
| China               | 3         | 4      | 1.97%   |
| SPCC                | 2         | 2      | 1.32%   |
| Apple               | 2         | 2      | 1.32%   |
| Vaseky              | 1         | 1      | 0.66%   |
| Team                | 1         | 1      | 0.66%   |
| PNY                 | 1         | 2      | 0.66%   |
| Netac               | 1         | 1      | 0.66%   |
| Hewlett-Packard     | 1         | 1      | 0.66%   |
| Gritronix           | 1         | 1      | 0.66%   |
| Gigabyte Technology | 1         | 2      | 0.66%   |
| Biostar             | 1         | 1      | 0.66%   |
| Apacer              | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 188       | 315    | 45.52%  |
| SSD     | 127       | 179    | 30.75%  |
| NVMe    | 71        | 89     | 17.19%  |
| Unknown | 18        | 24     | 4.36%   |
| MMC     | 9         | 12     | 2.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 269       | 488    | 73.7%   |
| NVMe | 71        | 89     | 19.45%  |
| SAS  | 16        | 30     | 4.38%   |
| MMC  | 9         | 12     | 2.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 205       | 323    | 64.06%  |
| 0.51-1.0   | 86        | 95     | 26.88%  |
| 1.01-2.0   | 14        | 38     | 4.38%   |
| 2.01-3.0   | 8         | 16     | 2.5%    |
| 4.01-10.0  | 5         | 20     | 1.56%   |
| 3.01-4.0   | 2         | 2      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 120       | 34.09%  |
| 251-500        | 82        | 23.3%   |
| 51-100         | 51        | 14.49%  |
| 501-1000       | 35        | 9.94%   |
| 1-20           | 21        | 5.97%   |
| 21-50          | 17        | 4.83%   |
| 1001-2000      | 12        | 3.41%   |
| Unknown        | 8         | 2.27%   |
| More than 3000 | 4         | 1.14%   |
| 2001-3000      | 2         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 141       | 39.17%  |
| 21-50          | 89        | 24.72%  |
| 101-250        | 46        | 12.78%  |
| 51-100         | 43        | 11.94%  |
| 251-500        | 18        | 5%      |
| 501-1000       | 11        | 3.06%   |
| Unknown        | 8         | 2.22%   |
| 1001-2000      | 2         | 0.56%   |
| More than 3000 | 1         | 0.28%   |
| 2001-3000      | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 4.55%   |
| Seagate ST2000DM008-2FR1 2TB                  | 2         | 2      | 4.55%   |
| Hewlett-Packard MB2000EBZQC 2TB               | 2         | 3      | 4.55%   |
| Crucial CT525MX300SSD1 528GB                  | 2         | 2      | 4.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD              | 1         | 1      | 2.27%   |
| WDC WD5000AAKX-75U6AA0 500GB                  | 1         | 1      | 2.27%   |
| WDC WD2500HHTZ-04N21V0 250GB                  | 1         | 1      | 2.27%   |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 2.27%   |
| WDC WD2500AAKS-00F0A0 250GB                   | 1         | 1      | 2.27%   |
| WDC WD20EZRZ-00Z5HB0 2TB                      | 1         | 1      | 2.27%   |
| WDC WD1600AAJS-22L7A0 160GB                   | 1         | 1      | 2.27%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 2.27%   |
| WDC WD10JPVT-60A1YT0 1TB                      | 1         | 1      | 2.27%   |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 2.27%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 2.27%   |
| Seagate ST980411ASG 80GB                      | 1         | 2      | 2.27%   |
| Seagate ST500LM021-1KJ152 500GB               | 1         | 1      | 2.27%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 2.27%   |
| Seagate ST3500418AS 500GB                     | 1         | 1      | 2.27%   |
| Seagate ST3160215AS 160GB                     | 1         | 1      | 2.27%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 2      | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 2.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB                | 1         | 1      | 2.27%   |
| Samsung Electronics SP2004C 200GB             | 1         | 1      | 2.27%   |
| Samsung Electronics HD080HJ/ 80GB             | 1         | 1      | 2.27%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 2.27%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD | 1         | 1      | 2.27%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 2.27%   |
| Intel SSDSC2BF180A4H 180GB                    | 1         | 1      | 2.27%   |
| Intel SSDSA2M080G2GN 80GB                     | 1         | 1      | 2.27%   |
| HS-SSD-E100 SSD 1024G                         | 1         | 1      | 2.27%   |
| Hitachi HUA723020ALA640 2TB                   | 1         | 2      | 2.27%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 2.27%   |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 2.27%   |
| Hitachi HDS721680PLA380 80GB                  | 1         | 1      | 2.27%   |
| Hitachi HDS721050CLA660 500GB                 | 1         | 1      | 2.27%   |
| Gritronix M.2 2280 256GB SSD                  | 1         | 1      | 2.27%   |
| China SSD 240GB                               | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 23.81%  |
| Seagate             | 10        | 13     | 23.81%  |
| Hitachi             | 5         | 6      | 11.9%   |
| Intel               | 3         | 3      | 7.14%   |
| Toshiba             | 2         | 2      | 4.76%   |
| Samsung Electronics | 2         | 2      | 4.76%   |
| Micron Technology   | 2         | 2      | 4.76%   |
| Hewlett-Packard     | 2         | 3      | 4.76%   |
| Crucial             | 2         | 2      | 4.76%   |
| SK hynix            | 1         | 1      | 2.38%   |
| HS-SSD-E100         | 1         | 1      | 2.38%   |
| Gritronix           | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 32.26%  |
| Seagate             | 10        | 13     | 32.26%  |
| Hitachi             | 5         | 6      | 16.13%  |
| Toshiba             | 2         | 2      | 6.45%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Hewlett-Packard     | 2         | 3      | 6.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 37     | 68.57%  |
| SSD  | 11        | 12     | 31.43%  |

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
| Detected | 217       | 358    | 60.45%  |
| Works    | 109       | 212    | 30.36%  |
| Malfunc  | 33        | 49     | 9.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 285       | 72.34%  |
| Samsung Electronics          | 22        | 5.58%   |
| AMD                          | 21        | 5.33%   |
| SanDisk                      | 11        | 2.79%   |
| LSI Logic / Symbios Logic    | 8         | 2.03%   |
| Silicon Motion               | 6         | 1.52%   |
| KIOXIA                       | 6         | 1.52%   |
| Kingston Technology Company  | 5         | 1.27%   |
| Transcend                    | 4         | 1.02%   |
| Hewlett-Packard              | 4         | 1.02%   |
| Toshiba America Info Systems | 3         | 0.76%   |
| Micron Technology            | 3         | 0.76%   |
| Apple                        | 3         | 0.76%   |
| SK hynix                     | 2         | 0.51%   |
| Nvidia                       | 2         | 0.51%   |
| Marvell Technology Group     | 2         | 0.51%   |
| Realtek Semiconductor        | 1         | 0.25%   |
| Phison Electronics           | 1         | 0.25%   |
| Netac Technology             | 1         | 0.25%   |
| Broadcom / LSI               | 1         | 0.25%   |
| ASMedia Technology           | 1         | 0.25%   |
| ADATA Technology             | 1         | 0.25%   |
| Adaptec                      | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 46        | 10.07%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 5.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 20        | 4.38%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 3.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 3.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 2.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 2.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 2.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 2.19%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 1.97%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 1.97%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 8         | 1.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 1.31%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 6         | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.09%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.09%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 1.09%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5         | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.09%   |
| Transcend Non-Volatile memory controller                                       | 4         | 0.88%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 0.88%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 0.88%   |
| Intel NVMe Controller                                                          | 4         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.88%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 4         | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.88%   |
| Micron NVMe Storage Controller                                                 | 3         | 0.66%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.66%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 3         | 0.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.66%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 245       | 57.78%  |
| NVMe | 71        | 16.75%  |
| RAID | 53        | 12.5%   |
| IDE  | 40        | 9.43%   |
| SCSI | 9         | 2.12%   |
| SAS  | 6         | 1.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 312       | 93.13%  |
| AMD    | 23        | 6.87%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 3.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 3.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 8         | 2.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 8         | 2.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 2.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 2.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 1.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 1.79%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 5         | 1.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 5         | 1.49%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 4         | 1.19%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 4         | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.19%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 1.19%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4         | 1.19%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 3         | 0.89%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 0.89%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 0.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 3         | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 0.89%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 0.89%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3         | 0.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 0.89%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3         | 0.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 0.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3         | 0.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 0.89%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 0.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 3         | 0.89%   |
| Intel Xeon CPU X5660 @ 2.80GHz          | 2         | 0.6%    |
| Intel Xeon CPU 5160 @ 3.00GHz           | 2         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.6%    |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.6%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 119       | 35.52%  |
| Intel Core i7        | 83        | 24.78%  |
| Other                | 27        | 8.06%   |
| Intel Xeon           | 21        | 6.27%   |
| Intel Core i3        | 18        | 5.37%   |
| Intel Core 2 Duo     | 15        | 4.48%   |
| Intel Celeron        | 8         | 2.39%   |
| AMD Ryzen 7          | 7         | 2.09%   |
| Intel Core m3        | 4         | 1.19%   |
| Intel Atom           | 4         | 1.19%   |
| AMD Ryzen 5          | 4         | 1.19%   |
| Intel Pentium        | 3         | 0.9%    |
| Intel Core M         | 3         | 0.9%    |
| Intel Core 2 Quad    | 2         | 0.6%    |
| Intel Core 2         | 2         | 0.6%    |
| AMD Athlon II X2     | 2         | 0.6%    |
| AMD A6               | 2         | 0.6%    |
| Intel Pentium Dual   | 1         | 0.3%    |
| Intel Genuine        | 1         | 0.3%    |
| Intel Core 2 Extreme | 1         | 0.3%    |
| AMD Ryzen 9          | 1         | 0.3%    |
| AMD Ryzen 3          | 1         | 0.3%    |
| AMD PRO A8           | 1         | 0.3%    |
| AMD G                | 1         | 0.3%    |
| AMD E                | 1         | 0.3%    |
| AMD A8               | 1         | 0.3%    |
| AMD A4               | 1         | 0.3%    |
| AMD A12              | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 167       | 49.55%  |
| 4      | 123       | 36.5%   |
| 6      | 18        | 5.34%   |
| 8      | 17        | 5.04%   |
| 12     | 5         | 1.48%   |
| 16     | 2         | 0.59%   |
| 10     | 2         | 0.59%   |
| 1      | 2         | 0.59%   |
| 14     | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 325       | 96.73%  |
| 2      | 11        | 3.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 260       | 77.38%  |
| 1      | 76        | 22.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 332       | 98.81%  |
| Unknown        | 3         | 0.89%   |
| 32-bit         | 1         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 25.07%  |
| 0x206a7    | 24        | 6.92%   |
| 0x306a9    | 19        | 5.48%   |
| 0x806ec    | 18        | 5.19%   |
| 0x806c1    | 17        | 4.9%    |
| 0x806e9    | 16        | 4.61%   |
| 0x406e3    | 16        | 4.61%   |
| 0x40651    | 14        | 4.03%   |
| 0x306d4    | 13        | 3.75%   |
| 0x306c3    | 13        | 3.75%   |
| 0x806ea    | 11        | 3.17%   |
| 0x1067a    | 11        | 3.17%   |
| 0x20655    | 10        | 2.88%   |
| 0x706e5    | 6         | 1.73%   |
| 0x206c2    | 6         | 1.73%   |
| 0x206d7    | 5         | 1.44%   |
| 0x906ea    | 4         | 1.15%   |
| 0x6f6      | 4         | 1.15%   |
| 0x506e3    | 4         | 1.15%   |
| 0x30678    | 4         | 1.15%   |
| 0xa0655    | 3         | 0.86%   |
| 0xa0652    | 3         | 0.86%   |
| 0x10676    | 3         | 0.86%   |
| 0x906e9    | 2         | 0.58%   |
| 0x6fd      | 2         | 0.58%   |
| 0x406c4    | 2         | 0.58%   |
| 0x20652    | 2         | 0.58%   |
| 0x106a5    | 2         | 0.58%   |
| 0x08701021 | 2         | 0.58%   |
| 0x08608103 | 2         | 0.58%   |
| 0x0600111f | 2         | 0.58%   |
| 0x05000119 | 2         | 0.58%   |
| 0xa0671    | 1         | 0.29%   |
| 0xa0660    | 1         | 0.29%   |
| 0x906a4    | 1         | 0.29%   |
| 0x906a3    | 1         | 0.29%   |
| 0x806eb    | 1         | 0.29%   |
| 0x706a1    | 1         | 0.29%   |
| 0x6fb      | 1         | 0.29%   |
| 0x40661    | 1         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 66        | 19.7%   |
| SandyBridge      | 37        | 11.04%  |
| Haswell          | 37        | 11.04%  |
| IvyBridge        | 28        | 8.36%   |
| Skylake          | 25        | 7.46%   |
| Westmere         | 22        | 6.57%   |
| TigerLake        | 21        | 6.27%   |
| Broadwell        | 18        | 5.37%   |
| Penryn           | 16        | 4.78%   |
| Silvermont       | 9         | 2.69%   |
| Icelake          | 7         | 2.09%   |
| Core             | 7         | 2.09%   |
| CometLake        | 7         | 2.09%   |
| Zen 2            | 6         | 1.79%   |
| Nehalem          | 5         | 1.49%   |
| Unknown          | 5         | 1.49%   |
| Zen+             | 2         | 0.6%    |
| Zen 3            | 2         | 0.6%    |
| Piledriver       | 2         | 0.6%    |
| K10              | 2         | 0.6%    |
| Bobcat           | 2         | 0.6%    |
| Alderlake Hybrid | 2         | 0.6%    |
| Zen              | 1         | 0.3%    |
| Steamroller      | 1         | 0.3%    |
| P6               | 1         | 0.3%    |
| K10 Llano        | 1         | 0.3%    |
| Jaguar           | 1         | 0.3%    |
| Goldmont plus    | 1         | 0.3%    |
| Excavator        | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 258       | 64.5%   |
| Nvidia                     | 79        | 19.75%  |
| AMD                        | 60        | 15%     |
| Matrox Electronics Systems | 3         | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 23        | 5.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 20        | 4.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 18        | 4.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 18        | 4.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 18        | 4.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 18        | 4.39%   |
| Intel UHD Graphics 620                                                                | 15        | 3.66%   |
| Intel HD Graphics 5500                                                                | 15        | 3.66%   |
| Intel HD Graphics 620                                                                 | 13        | 3.17%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 2.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 7         | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 7         | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 6         | 1.46%   |
| Nvidia GT218 [GeForce 210]                                                            | 5         | 1.22%   |
| Nvidia GP108M [GeForce MX230]                                                         | 5         | 1.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 5         | 1.22%   |
| Intel HD Graphics 530                                                                 | 5         | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 5         | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 4         | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 0.98%   |
| Intel HD Graphics 615                                                                 | 4         | 0.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 0.98%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 3         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 0.73%   |
| Matrox Electronics Systems MGA G200EH                                                 | 3         | 0.73%   |
| Intel HD Graphics 5300                                                                | 3         | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 0.73%   |
| AMD Renoir                                                                            | 3         | 0.73%   |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 0.49%   |
| Nvidia GT218M [NVS 3100M]                                                             | 2         | 0.49%   |
| Nvidia GT218 [GeForce 310]                                                            | 2         | 0.49%   |
| Nvidia GP108M [GeForce MX250]                                                         | 2         | 0.49%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 2         | 0.49%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 197       | 58.28%  |
| Intel + Nvidia | 40        | 11.83%  |
| 1 x AMD        | 35        | 10.36%  |
| 1 x Nvidia     | 34        | 10.06%  |
| Intel + AMD    | 20        | 5.92%   |
| 1 x Matrox     | 3         | 0.89%   |
| AMD + Nvidia   | 3         | 0.89%   |
| Other          | 2         | 0.59%   |
| 2 x Nvidia     | 2         | 0.59%   |
| 2 x AMD        | 2         | 0.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 291       | 85.09%  |
| Proprietary | 39        | 11.4%   |
| Unknown     | 12        | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 240       | 70.38%  |
| 1.01-2.0   | 44        | 12.9%   |
| 0.01-0.5   | 22        | 6.45%   |
| 0.51-1.0   | 15        | 4.4%    |
| 3.01-4.0   | 14        | 4.11%   |
| 5.01-6.0   | 2         | 0.59%   |
| 8.01-16.0  | 2         | 0.59%   |
| 7.01-8.0   | 1         | 0.29%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 63        | 19.81%  |
| AU Optronics            | 46        | 14.47%  |
| Chimei Innolux          | 41        | 12.89%  |
| BOE                     | 35        | 11.01%  |
| Samsung Electronics     | 25        | 7.86%   |
| Hewlett-Packard         | 22        | 6.92%   |
| Dell                    | 21        | 6.6%    |
| Chi Mei Optoelectronics | 8         | 2.52%   |
| Lenovo                  | 6         | 1.89%   |
| Apple                   | 6         | 1.89%   |
| Acer                    | 5         | 1.57%   |
| Unknown                 | 4         | 1.26%   |
| Sharp                   | 4         | 1.26%   |
| InfoVision              | 4         | 1.26%   |
| NEC Computers           | 3         | 0.94%   |
| KDC                     | 3         | 0.94%   |
| Goldstar                | 3         | 0.94%   |
| Sony                    | 2         | 0.63%   |
| PANDA                   | 2         | 0.63%   |
| LGD                     | 2         | 0.63%   |
| LG Philips              | 2         | 0.63%   |
| Hitachi                 | 2         | 0.63%   |
| BenQ                    | 2         | 0.63%   |
| ViewSonic               | 1         | 0.31%   |
| Planar                  | 1         | 0.31%   |
| Philips                 | 1         | 0.31%   |
| LPL                     | 1         | 0.31%   |
| LED                     | 1         | 0.31%   |
| HannStar                | 1         | 0.31%   |
| DENON                   | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 2.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 1.55%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 1.24%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 1.24%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 0.93%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 0.93%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 3         | 0.93%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 3         | 0.93%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.93%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.62%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.62%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 2         | 0.62%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 0.62%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 2         | 0.62%   |
| LG Display LCD Monitor LGD052F 1920x1080 344x194mm 15.5-inch          | 2         | 0.62%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 2         | 0.62%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.62%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.62%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 2         | 0.62%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.62%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 0.62%   |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch              | 2         | 0.62%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.62%   |
| Dell P2217H DELA0D9 1920x1080 480x270mm 21.7-inch                     | 2         | 0.62%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch       | 2         | 0.62%   |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                 | 2         | 0.62%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 2         | 0.62%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch         | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 2         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 131       | 42.53%  |
| 1366x768 (WXGA)    | 97        | 31.49%  |
| 1600x900 (HD+)     | 13        | 4.22%   |
| 1680x1050 (WSXGA+) | 11        | 3.57%   |
| 3840x2160 (4K)     | 9         | 2.92%   |
| 1280x1024 (SXGA)   | 9         | 2.92%   |
| 1280x800 (WXGA)    | 6         | 1.95%   |
| 1920x1200 (WUXGA)  | 5         | 1.62%   |
| 2880x1800          | 4         | 1.3%    |
| 1440x900 (WXGA+)   | 4         | 1.3%    |
| 1024x768 (XGA)     | 4         | 1.3%    |
| 3440x1440          | 3         | 0.97%   |
| 2560x1440 (QHD)    | 3         | 0.97%   |
| 2288x1287          | 2         | 0.65%   |
| Unknown            | 2         | 0.65%   |
| 3640x1920          | 1         | 0.32%   |
| 3520x1080          | 1         | 0.32%   |
| 2560x1600          | 1         | 0.32%   |
| 2160x1440          | 1         | 0.32%   |
| 1360x768           | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 122       | 38.73%  |
| 14      | 45        | 14.29%  |
| 13      | 37        | 11.75%  |
| 17      | 17        | 5.4%    |
| 21      | 14        | 4.44%   |
| 24      | 13        | 4.13%   |
| Unknown | 11        | 3.49%   |
| 23      | 9         | 2.86%   |
| 12      | 9         | 2.86%   |
| 22      | 6         | 1.9%    |
| 19      | 6         | 1.9%    |
| 11      | 6         | 1.9%    |
| 27      | 5         | 1.59%   |
| 18      | 3         | 0.95%   |
| 142     | 2         | 0.63%   |
| 72      | 2         | 0.63%   |
| 40      | 2         | 0.63%   |
| 84      | 1         | 0.32%   |
| 31      | 1         | 0.32%   |
| 26      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |
| 10      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 186       | 59.42%  |
| 201-300        | 36        | 11.5%   |
| 501-600        | 27        | 8.63%   |
| 401-500        | 26        | 8.31%   |
| 351-400        | 19        | 6.07%   |
| Unknown        | 11        | 3.51%   |
| 1501-2000      | 3         | 0.96%   |
| More than 2000 | 2         | 0.64%   |
| 801-900        | 2         | 0.64%   |
| 601-700        | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 245       | 81.94%  |
| 16/10   | 27        | 9.03%   |
| Unknown | 11        | 3.68%   |
| 5/4     | 9         | 3.01%   |
| 4/3     | 4         | 1.34%   |
| 1.00    | 2         | 0.67%   |
| 3/2     | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 122       | 38.85%  |
| 81-90          | 63        | 20.06%  |
| 201-250        | 35        | 11.15%  |
| 71-80          | 17        | 5.41%   |
| Unknown        | 11        | 3.5%    |
| 151-200        | 10        | 3.18%   |
| 121-130        | 10        | 3.18%   |
| 61-70          | 9         | 2.87%   |
| 141-150        | 8         | 2.55%   |
| 51-60          | 6         | 1.91%   |
| More than 1000 | 5         | 1.59%   |
| 301-350        | 5         | 1.59%   |
| 251-300        | 4         | 1.27%   |
| 91-100         | 3         | 0.96%   |
| 131-140        | 2         | 0.64%   |
| 501-1000       | 2         | 0.64%   |
| 351-500        | 1         | 0.32%   |
| 41-50          | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 121       | 38.91%  |
| 101-120       | 98        | 31.51%  |
| 51-100        | 59        | 18.97%  |
| 161-240       | 11        | 3.54%   |
| Unknown       | 11        | 3.54%   |
| More than 240 | 7         | 2.25%   |
| 1-50          | 4         | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 292       | 85.88%  |
| 2     | 26        | 7.65%   |
| 0     | 21        | 6.18%   |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 218       | 39.93%  |
| Realtek Semiconductor           | 161       | 29.49%  |
| Broadcom                        | 51        | 9.34%   |
| Qualcomm Atheros                | 29        | 5.31%   |
| Ralink Technology               | 13        | 2.38%   |
| Broadcom Limited                | 11        | 2.01%   |
| MediaTek                        | 9         | 1.65%   |
| Hewlett-Packard                 | 5         | 0.92%   |
| Sierra Wireless                 | 4         | 0.73%   |
| Samsung Electronics             | 4         | 0.73%   |
| Ralink                          | 4         | 0.73%   |
| Qualcomm Atheros Communications | 4         | 0.73%   |
| Marvell Technology Group        | 4         | 0.73%   |
| D-Link                          | 4         | 0.73%   |
| ASIX Electronics                | 4         | 0.73%   |
| Huawei Technologies             | 3         | 0.55%   |
| ZTE WCDMA Technologies MSM      | 2         | 0.37%   |
| Xiaomi                          | 2         | 0.37%   |
| Spreadtrum Communications       | 2         | 0.37%   |
| Nvidia                          | 2         | 0.37%   |
| Dell                            | 2         | 0.37%   |
| Zoom Telephonics                | 1         | 0.18%   |
| VIA Technologies                | 1         | 0.18%   |
| Qualcomm                        | 1         | 0.18%   |
| QLogic                          | 1         | 0.18%   |
| OPPO Electronics                | 1         | 0.18%   |
| JMicron Technology              | 1         | 0.18%   |
| Emulex                          | 1         | 0.18%   |
| 3Com                            | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 105       | 15.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 5.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 3.18%   |
| Intel Wi-Fi 6 AX201                                               | 17        | 2.58%   |
| Intel Wireless 7265                                               | 16        | 2.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 2.42%   |
| Intel Wireless 7260                                               | 13        | 1.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 13        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.82%   |
| Intel Wireless 8260                                               | 12        | 1.82%   |
| Intel Wireless 3165                                               | 12        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 1.67%   |
| Ralink MT7601U Wireless Adapter                                   | 10        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.06%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.91%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.76%   |
| MediaTek Armor X10 Pro                                            | 5         | 0.76%   |
| Intel Wireless 3160                                               | 5         | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                   | 5         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.76%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.76%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4         | 0.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 166       | 54.25%  |
| Realtek Semiconductor           | 44        | 14.38%  |
| Qualcomm Atheros                | 26        | 8.5%    |
| Broadcom                        | 26        | 8.5%    |
| Ralink Technology               | 13        | 4.25%   |
| Broadcom Limited                | 6         | 1.96%   |
| Sierra Wireless                 | 4         | 1.31%   |
| Ralink                          | 4         | 1.31%   |
| Qualcomm Atheros Communications | 4         | 1.31%   |
| D-Link                          | 4         | 1.31%   |
| MediaTek                        | 3         | 0.98%   |
| Marvell Technology Group        | 2         | 0.65%   |
| Hewlett-Packard                 | 2         | 0.65%   |
| Dell                            | 2         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 17        | 5.5%    |
| Intel Wireless 7265                                                  | 16        | 5.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 16        | 5.18%   |
| Intel Wireless 7260                                                  | 13        | 4.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 12        | 3.88%   |
| Intel Wireless 8260                                                  | 12        | 3.88%   |
| Intel Wireless 3165                                                  | 12        | 3.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 3.56%   |
| Ralink MT7601U Wireless Adapter                                      | 10        | 3.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 9         | 2.91%   |
| Intel Wireless 8265 / 8275                                           | 8         | 2.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 6         | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 5         | 1.62%   |
| Intel Wireless 3160                                                  | 5         | 1.62%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 1.62%   |
| Intel Centrino Ultimate-N 6300                                       | 5         | 1.62%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 1.62%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 1.29%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 1.29%   |
| Intel Wi-Fi 6 AX200                                                  | 4         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 1.29%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 1.29%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 4         | 1.29%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 3         | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 0.97%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.97%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 3         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 0.97%   |
| Sierra Wireless EM7345 4G LTE                                        | 2         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 138       | 40.95%  |
| Intel                     | 132       | 39.17%  |
| Broadcom                  | 26        | 7.72%   |
| MediaTek                  | 6         | 1.78%   |
| Broadcom Limited          | 5         | 1.48%   |
| ASIX Electronics          | 4         | 1.19%   |
| Samsung Electronics       | 3         | 0.89%   |
| Qualcomm Atheros          | 3         | 0.89%   |
| Huawei Technologies       | 3         | 0.89%   |
| Xiaomi                    | 2         | 0.59%   |
| Spreadtrum Communications | 2         | 0.59%   |
| Nvidia                    | 2         | 0.59%   |
| Marvell Technology Group  | 2         | 0.59%   |
| Hewlett-Packard           | 2         | 0.59%   |
| VIA Technologies          | 1         | 0.3%    |
| Qualcomm                  | 1         | 0.3%    |
| QLogic                    | 1         | 0.3%    |
| OPPO Electronics          | 1         | 0.3%    |
| JMicron Technology        | 1         | 0.3%    |
| Emulex                    | 1         | 0.3%    |
| 3Com                      | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 105       | 30.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 10.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 6.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 13        | 3.76%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 3.47%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 2.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.02%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 2.02%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.73%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 1.73%   |
| MediaTek Armor X10 Pro                                            | 5         | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.45%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.87%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.87%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.87%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 3         | 0.87%   |
| Spreadtrum Spreadtrum Phone                                       | 2         | 0.58%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.58%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.58%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 2         | 0.58%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.58%   |
| Huawei E353/E3131                                                 | 2         | 0.58%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 2         | 0.58%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 2         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.29%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 307       | 50.91%  |
| WiFi     | 291       | 48.26%  |
| Modem    | 5         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 242       | 73.11%  |
| Ethernet | 89        | 26.89%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 233       | 68.93%  |
| 1     | 85        | 25.15%  |
| 0     | 7         | 2.07%   |
| 3     | 6         | 1.78%   |
| 4     | 5         | 1.48%   |
| 8     | 1         | 0.3%    |
| 6     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 313       | 92.33%  |
| Yes  | 26        | 7.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 121       | 57.08%  |
| Realtek Semiconductor           | 23        | 10.85%  |
| Qualcomm Atheros Communications | 19        | 8.96%   |
| Broadcom                        | 15        | 7.08%   |
| Cambridge Silicon Radio         | 12        | 5.66%   |
| Foxconn / Hon Hai               | 4         | 1.89%   |
| Dell                            | 4         | 1.89%   |
| Ralink                          | 3         | 1.42%   |
| Apple                           | 3         | 1.42%   |
| IMC Networks                    | 2         | 0.94%   |
| Hewlett-Packard                 | 2         | 0.94%   |
| Ralink Technology               | 1         | 0.47%   |
| Marvell Semiconductor           | 1         | 0.47%   |
| Lite-On Technology              | 1         | 0.47%   |
| AboCom Systems                  | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 61        | 28.77%  |
| Intel AX201 Bluetooth                                                               | 23        | 10.85%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 10.38%  |
| Realtek Bluetooth Radio                                                             | 15        | 7.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 5.66%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 5.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.83%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 2.36%   |
| Intel AX200 Bluetooth                                                               | 4         | 1.89%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.94%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.94%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.94%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.47%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.47%   |
| Ralink CSR BS8510                                                                   | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.47%   |
| Intel Bluetooth Device                                                              | 1         | 0.47%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.47%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.47%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.47%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.47%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.47%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.47%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.47%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.47%   |
| Broadcom HP Bluethunder                                                             | 1         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 300       | 74.44%  |
| Nvidia                 | 46        | 11.41%  |
| AMD                    | 39        | 9.68%   |
| Generalplus Technology | 5         | 1.24%   |
| Logitech               | 2         | 0.5%    |
| C-Media Electronics    | 2         | 0.5%    |
| Apple                  | 2         | 0.5%    |
| Texas Instruments      | 1         | 0.25%   |
| Realtek Semiconductor  | 1         | 0.25%   |
| OPPO Electronics       | 1         | 0.25%   |
| JMTek                  | 1         | 0.25%   |
| FIFINE 683 Microphone  | 1         | 0.25%   |
| Dell                   | 1         | 0.25%   |
| Creative Labs          | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 52        | 10.97%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 5.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 4.43%   |
| Intel Comet Lake PCH-LP cAVS                                               | 19        | 4.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 3.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 3.8%    |
| Intel Broadwell-U Audio Controller                                         | 18        | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 3.8%    |
| Intel 8 Series HD Audio Controller                                         | 18        | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 3.16%   |
| Nvidia High Definition Audio Controller                                    | 10        | 2.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 2.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.48%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 1.48%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 1.05%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.84%   |
| Generalplus Technology USB Audio Device                                    | 4         | 0.84%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 31.34%  |
| SK hynix            | 58        | 26.73%  |
| Micron Technology   | 22        | 10.14%  |
| A-DATA Technology   | 14        | 6.45%   |
| Kingston            | 10        | 4.61%   |
| Unknown             | 6         | 2.76%   |
| Transcend           | 6         | 2.76%   |
| Crucial             | 6         | 2.76%   |
| Team                | 4         | 1.84%   |
| Elpida              | 4         | 1.84%   |
| Lexar               | 3         | 1.38%   |
| Unknown (2C0B)      | 2         | 0.92%   |
| Spectek             | 2         | 0.92%   |
| Ramaxel Technology  | 2         | 0.92%   |
| Nanya Technology    | 2         | 0.92%   |
| Unknown (768A)      | 1         | 0.46%   |
| TwinMOS             | 1         | 0.46%   |
| Toshiba-0098        | 1         | 0.46%   |
| S                   | 1         | 0.46%   |
| Patriot             | 1         | 0.46%   |
| Hikvision           | 1         | 0.46%   |
| H                   | 1         | 0.46%   |
| Axiom               | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 2.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 5         | 2.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 5         | 2.05%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s           | 5         | 2.05%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s    | 3         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.23%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 3         | 1.23%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s | 3         | 1.23%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s     | 3         | 1.23%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s          | 3         | 1.23%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s     | 3         | 1.23%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s        | 2         | 0.82%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s          | 2         | 0.82%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s    | 2         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 2         | 0.82%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 2         | 0.82%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s   | 2         | 0.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s              | 2         | 0.82%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s           | 2         | 0.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s    | 2         | 0.82%   |
| Samsung RAM M471A5143DB0-CPB 4096MB SODIMM DDR4 2133MT/s | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s    | 2         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 0.82%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 2         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 2         | 0.82%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 2         | 0.82%   |
| Lexar RAM LD4AS016G-H2666G 16GB SODIMM DDR4 2667MT/s     | 2         | 0.82%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s               | 2         | 0.82%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s              | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s               | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.41%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s               | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s             | 1         | 0.41%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s        | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 78        | 48.75%  |
| DDR3   | 69        | 43.13%  |
| LPDDR3 | 4         | 2.5%    |
| SDRAM  | 3         | 1.88%   |
| LPDDR4 | 3         | 1.88%   |
| DDR5   | 1         | 0.63%   |
| DDR2   | 1         | 0.63%   |
| DDR    | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 73.13%  |
| DIMM         | 34        | 21.25%  |
| Row Of Chips | 9         | 5.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 36.72%  |
| 4096  | 50        | 28.25%  |
| 16384 | 36        | 20.34%  |
| 2048  | 21        | 11.86%  |
| 32768 | 5         | 2.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 53        | 28.65%  |
| 2667  | 39        | 21.08%  |
| 3200  | 24        | 12.97%  |
| 2133  | 15        | 8.11%   |
| 1333  | 13        | 7.03%   |
| 2400  | 11        | 5.95%   |
| 1334  | 8         | 4.32%   |
| 1866  | 3         | 1.62%   |
| 1067  | 3         | 1.62%   |
| 4267  | 2         | 1.08%   |
| 1066  | 2         | 1.08%   |
| 8400  | 1         | 0.54%   |
| 4800  | 1         | 0.54%   |
| 4199  | 1         | 0.54%   |
| 3733  | 1         | 0.54%   |
| 3266  | 1         | 0.54%   |
| 3000  | 1         | 0.54%   |
| 2666  | 1         | 0.54%   |
| 2267  | 1         | 0.54%   |
| 2200  | 1         | 0.54%   |
| 2000  | 1         | 0.54%   |
| 1867  | 1         | 0.54%   |
| 800   | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| HP LaserJet 1300            | 1         | 50%     |
| HP DeskJet F2492 All-in-One | 1         | 50%     |

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
| Chicony Electronics                    | 63        | 26.69%  |
| Microdia                               | 27        | 11.44%  |
| Sunplus Innovation Technology          | 22        | 9.32%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 9.32%   |
| Realtek Semiconductor                  | 18        | 7.63%   |
| Lite-On Technology                     | 13        | 5.51%   |
| Quanta                                 | 8         | 3.39%   |
| Suyin                                  | 7         | 2.97%   |
| IMC Networks                           | 7         | 2.97%   |
| Bison Electronics                      | 6         | 2.54%   |
| Syntek                                 | 5         | 2.12%   |
| Ricoh                                  | 5         | 2.12%   |
| Luxvisions Innotech Limited            | 5         | 2.12%   |
| Silicon Motion                         | 4         | 1.69%   |
| Apple                                  | 4         | 1.69%   |
| Acer                                   | 4         | 1.69%   |
| Z-Star Microelectronics                | 2         | 0.85%   |
| Primax Electronics                     | 2         | 0.85%   |
| Logitech                               | 2         | 0.85%   |
| Sunplus Technology                     | 1         | 0.42%   |
| Samsung Electronics                    | 1         | 0.42%   |
| Pixart Imaging                         | 1         | 0.42%   |
| OmniVision Technologies                | 1         | 0.42%   |
| Microsoft                              | 1         | 0.42%   |
| MacroSilicon                           | 1         | 0.42%   |
| Lenovo                                 | 1         | 0.42%   |
| DigiTech                               | 1         | 0.42%   |
| Asuscom Network                        | 1         | 0.42%   |
| Arkmicro Technologies                  | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 14        | 5.88%   |
| Sunplus Integrated_Webcam_HD                                               | 13        | 5.46%   |
| Chicony Integrated Camera                                                  | 12        | 5.04%   |
| Chicony HP HD Camera                                                       | 10        | 4.2%    |
| Lite-On HP HD Webcam                                                       | 9         | 3.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 9         | 3.78%   |
| Realtek Integrated_Webcam_HD                                               | 7         | 2.94%   |
| Microdia Integrated Webcam                                                 | 5         | 2.1%    |
| Quanta HP HD Camera                                                        | 4         | 1.68%   |
| Chicony USB 2.0Camera                                                      | 4         | 1.68%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.68%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.68%   |
| Chicony HP TrueVision HD                                                   | 4         | 1.68%   |
| Chicony EasyCamera                                                         | 4         | 1.68%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 4         | 1.68%   |
| Syntek Integrated Camera                                                   | 3         | 1.26%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.26%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.26%   |
| Realtek USB2.0 camera                                                      | 3         | 1.26%   |
| Realtek Integrated Webcam                                                  | 3         | 1.26%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.26%   |
| IMC Networks Integrated Camera                                             | 3         | 1.26%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 3         | 1.26%   |
| Acer Integrated Camera                                                     | 3         | 1.26%   |
| Z-Star Venus USB2.0 Camera                                                 | 2         | 0.84%   |
| Suyin HP Truevision HD                                                     | 2         | 0.84%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 0.84%   |
| Sunplus HP Universal Camera                                                | 2         | 0.84%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.84%   |
| Realtek Integrated Webcam_HD                                               | 2         | 0.84%   |
| Realtek HP Truevision HD                                                   | 2         | 0.84%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.84%   |
| Primax HP HD Webcam [Fixed]                                                | 2         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 0.84%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.84%   |
| Lite-On Integrated Camera                                                  | 2         | 0.84%   |
| Lite-On HP HD Camera                                                       | 2         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 47        | 63.51%  |
| Synaptics                  | 12        | 16.22%  |
| Shenzhen Goodix Technology | 6         | 8.11%   |
| AuthenTec                  | 4         | 5.41%   |
| Upek                       | 3         | 4.05%   |
| Elan Microelectronics      | 2         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 25.68%  |
| Validity Sensors VFS491                                                    | 10        | 13.51%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 9.46%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 8.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.05%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.05%   |
| AuthenTec AES2810                                                          | 3         | 4.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 2.7%    |
| Elan ELAN:ARM-M4                                                           | 2         | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.35%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.35%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.35%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.35%   |
| Synaptics  WBDI                                                            | 1         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.35%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 24        | 88.89%  |
| O2 Micro | 3         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 37.04%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 33.33%  |
| Broadcom 5880                                                                | 3         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 7.41%   |
| Broadcom 58200                                                               | 2         | 7.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 195       | 56.85%  |
| 1     | 123       | 35.86%  |
| 2     | 19        | 5.54%   |
| 4     | 2         | 0.58%   |
| 3     | 2         | 0.58%   |
| 8     | 1         | 0.29%   |
| 7     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 73        | 39.89%  |
| Chipcard                 | 27        | 14.75%  |
| Graphics card            | 26        | 14.21%  |
| Net/wireless             | 17        | 9.29%   |
| Sound                    | 11        | 6.01%   |
| Storage                  | 5         | 2.73%   |
| Communication controller | 5         | 2.73%   |
| Bluetooth                | 5         | 2.73%   |
| Multimedia controller    | 4         | 2.19%   |
| Net/ethernet             | 3         | 1.64%   |
| Camera                   | 3         | 1.64%   |
| Network                  | 2         | 1.09%   |
| Storage/ata              | 1         | 0.55%   |
| Card reader              | 1         | 0.55%   |


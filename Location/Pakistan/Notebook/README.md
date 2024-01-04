Linux in Pakistan - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Pakistan.

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

Total: 399

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Inspiron 3593               | [a2424d3523](https://linux-hardware.org/?probe=a2424d3523) | Jan 01, 2024 |
| Dell      | Inspiron 3593               | [dc67ac3e38](https://linux-hardware.org/?probe=dc67ac3e38) | Dec 29, 2023 |
| Dell      | Inspiron 3593               | [27f6eb03d0](https://linux-hardware.org/?probe=27f6eb03d0) | Dec 28, 2023 |
| Lenovo    | ThinkPad T410 2537HN2       | [c268085f95](https://linux-hardware.org/?probe=c268085f95) | Dec 20, 2023 |
| Dell      | Latitude E7440              | [35982f622e](https://linux-hardware.org/?probe=35982f622e) | Dec 17, 2023 |
| HP        | EliteBook 830 G8 Noteboo... | [4cdde5e9dc](https://linux-hardware.org/?probe=4cdde5e9dc) | Dec 14, 2023 |
| Dell      | Inspiron 1525               | [9eb3de84e4](https://linux-hardware.org/?probe=9eb3de84e4) | Dec 10, 2023 |
| HP        | ProBook 450 G4              | [a41eb50b0e](https://linux-hardware.org/?probe=a41eb50b0e) | Dec 04, 2023 |
| Dell      | XPS 13 9343                 | [e0e8d08912](https://linux-hardware.org/?probe=e0e8d08912) | Dec 01, 2023 |
| Dell      | Precision 7740              | [50b0f0be08](https://linux-hardware.org/?probe=50b0f0be08) | Nov 25, 2023 |
| Dell      | Inspiron 15 3515            | [84c3c8db78](https://linux-hardware.org/?probe=84c3c8db78) | Nov 23, 2023 |
| HP        | Pavilion Gaming Laptop 1... | [1060eb5e48](https://linux-hardware.org/?probe=1060eb5e48) | Nov 23, 2023 |
| Dell      | Inspiron 1525               | [a4927b394e](https://linux-hardware.org/?probe=a4927b394e) | Nov 23, 2023 |
| Lenovo    | ThinkPad Helix 3701CTO      | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| HP        | ZBook 15                    | [7959bd4b85](https://linux-hardware.org/?probe=7959bd4b85) | Nov 18, 2023 |
| Dell      | Inspiron 1525               | [f292f81323](https://linux-hardware.org/?probe=f292f81323) | Nov 13, 2023 |
| HP        | Pavilion Gaming Laptop 1... | [bcd7a71a14](https://linux-hardware.org/?probe=bcd7a71a14) | Nov 06, 2023 |
| Dell      | Precision 7740              | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| HP        | Laptop 15s-fq5xxx           | [18398fe53c](https://linux-hardware.org/?probe=18398fe53c) | Oct 31, 2023 |
| HP        | Laptop 15s-fq5xxx           | [773814f03f](https://linux-hardware.org/?probe=773814f03f) | Oct 27, 2023 |
| Chuwi     | HeroBook Pro                | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| HP        | ProBook 450 G4              | [d76b3901c7](https://linux-hardware.org/?probe=d76b3901c7) | Oct 26, 2023 |
| HP        | ProBook 450 G4              | [58d1baf31c](https://linux-hardware.org/?probe=58d1baf31c) | Oct 26, 2023 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [6259de67f2](https://linux-hardware.org/?probe=6259de67f2) | Oct 23, 2023 |
| HP        | Laptop 15-ef0xxx            | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Dell      | Latitude 7420               | [33e4aebc37](https://linux-hardware.org/?probe=33e4aebc37) | Oct 21, 2023 |
| Dell      | Latitude 5491               | [c701f6e10d](https://linux-hardware.org/?probe=c701f6e10d) | Oct 21, 2023 |
| Dell      | Latitude 7300               | [e68476c5ee](https://linux-hardware.org/?probe=e68476c5ee) | Oct 17, 2023 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [a8c11a4935](https://linux-hardware.org/?probe=a8c11a4935) | Oct 13, 2023 |
| Dell      | XPS 13 9370                 | [51c5671188](https://linux-hardware.org/?probe=51c5671188) | Oct 12, 2023 |
| Dell      | Inspiron 15-7579            | [08444b33e9](https://linux-hardware.org/?probe=08444b33e9) | Oct 10, 2023 |
| Dell      | Inspiron 15-7579            | [a58029a4f8](https://linux-hardware.org/?probe=a58029a4f8) | Oct 10, 2023 |
| Lenovo    | ThinkPad T450 20BUS1A100    | [1b7097cf90](https://linux-hardware.org/?probe=1b7097cf90) | Oct 06, 2023 |
| HP        | Laptop 15-da2xxx            | [1959705750](https://linux-hardware.org/?probe=1959705750) | Oct 03, 2023 |
| Lenovo    | IdeaPad L3 15ITL6 82HL      | [ae0c9bf33a](https://linux-hardware.org/?probe=ae0c9bf33a) | Oct 02, 2023 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| Lenovo    | ThinkPad T450 20BUS1A100    | [f4887bacc7](https://linux-hardware.org/?probe=f4887bacc7) | Sep 25, 2023 |
| Dell      | Inspiron 15-7579            | [d85124e7d2](https://linux-hardware.org/?probe=d85124e7d2) | Sep 20, 2023 |
| Dell      | Latitude E6430              | [32cf98639a](https://linux-hardware.org/?probe=32cf98639a) | Sep 20, 2023 |
| HP        | Laptop 15s-fq5xxx           | [11d6fae345](https://linux-hardware.org/?probe=11d6fae345) | Sep 18, 2023 |
| Clevo     | P170HMx                     | [4abfcaf4ba](https://linux-hardware.org/?probe=4abfcaf4ba) | Sep 16, 2023 |
| HP        | Laptop 15-fc0xxx            | [9720b79b9d](https://linux-hardware.org/?probe=9720b79b9d) | Sep 16, 2023 |
| HP        | Laptop 15-fc0xxx            | [0f34501ff9](https://linux-hardware.org/?probe=0f34501ff9) | Sep 16, 2023 |
| Clevo     | P170HMx                     | [1a0ef2b235](https://linux-hardware.org/?probe=1a0ef2b235) | Sep 16, 2023 |
| HP        | Unknown                     | [defc1de0cf](https://linux-hardware.org/?probe=defc1de0cf) | Sep 11, 2023 |
| Acer      | Aspire 3820                 | [08f7d373e7](https://linux-hardware.org/?probe=08f7d373e7) | Sep 07, 2023 |
| Dell      | Inspiron 1545               | [cb4847f435](https://linux-hardware.org/?probe=cb4847f435) | Sep 01, 2023 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [f01ca37e4c](https://linux-hardware.org/?probe=f01ca37e4c) | Aug 31, 2023 |
| HP        | EliteBook 820 G1            | [79855ccf9d](https://linux-hardware.org/?probe=79855ccf9d) | Aug 30, 2023 |
| HP        | EliteBook 820 G1            | [c82147d598](https://linux-hardware.org/?probe=c82147d598) | Aug 29, 2023 |
| HP        | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| ASUSTek   | G75VW                       | [7ef5fc5f0c](https://linux-hardware.org/?probe=7ef5fc5f0c) | Aug 23, 2023 |
| Fujitsu   | LIFEBOOK AH530              | [5e8e8a6397](https://linux-hardware.org/?probe=5e8e8a6397) | Aug 22, 2023 |
| Toshiba   | Satellite L55-B             | [4b2bcc2231](https://linux-hardware.org/?probe=4b2bcc2231) | Aug 18, 2023 |
| Lenovo    | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Dell      | Latitude E7450              | [9d787db93a](https://linux-hardware.org/?probe=9d787db93a) | Aug 13, 2023 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | [ab45ffe407](https://linux-hardware.org/?probe=ab45ffe407) | Aug 07, 2023 |
| Acer      | Aspire 3820                 | [e4d39c20bc](https://linux-hardware.org/?probe=e4d39c20bc) | Aug 05, 2023 |
| Acer      | Aspire 3820                 | [aac7924f4e](https://linux-hardware.org/?probe=aac7924f4e) | Aug 05, 2023 |
| Acer      | Aspire 3820                 | [ceca389ec4](https://linux-hardware.org/?probe=ceca389ec4) | Aug 03, 2023 |
| Acer      | Aspire 3820                 | [814b3a8cf8](https://linux-hardware.org/?probe=814b3a8cf8) | Aug 02, 2023 |
| Gateway   | NV57H                       | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| Lenovo    | Z50-75 80EC                 | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Dell      | Latitude 5480               | [2db18c20d1](https://linux-hardware.org/?probe=2db18c20d1) | Jul 18, 2023 |
| Lenovo    | IdeaPad 5 Pro 16ACH6 82L... | [dc3fd72332](https://linux-hardware.org/?probe=dc3fd72332) | Jul 18, 2023 |
| ASUSTek   | G75VW                       | [2bd8f70433](https://linux-hardware.org/?probe=2bd8f70433) | Jul 17, 2023 |
| HP        | Unknown                     | [6100712075](https://linux-hardware.org/?probe=6100712075) | Jul 12, 2023 |
| Lenovo    | Edge 15 80H1                | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| Lenovo    | IdeaPad 3 15ITL6 82H8       | [32f2a1756a](https://linux-hardware.org/?probe=32f2a1756a) | Jun 23, 2023 |
| Alienware | x17 R2                      | [632fbfe682](https://linux-hardware.org/?probe=632fbfe682) | Jun 20, 2023 |
| Haier     | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| Lenovo    | IdeaPad 310-15IKB 80TV      | [1f5222a92f](https://linux-hardware.org/?probe=1f5222a92f) | Jun 15, 2023 |
| HP        | ProBook 6360b               | [cdef37cb2d](https://linux-hardware.org/?probe=cdef37cb2d) | Jun 09, 2023 |
| ASUSTek   | T200TA                      | [2c98c872f8](https://linux-hardware.org/?probe=2c98c872f8) | Jun 08, 2023 |
| Clevo     | P170HMx                     | [6513e1e52e](https://linux-hardware.org/?probe=6513e1e52e) | Jun 08, 2023 |
| Clevo     | P170HMx                     | [7e2d7bfd0d](https://linux-hardware.org/?probe=7e2d7bfd0d) | Jun 06, 2023 |
| Dell      | Latitude E7450              | [fe7cb1e53f](https://linux-hardware.org/?probe=fe7cb1e53f) | Jun 03, 2023 |
| Lenovo    | Edge 15 80H1                | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Dell      | Latitude E7450              | [4a88622321](https://linux-hardware.org/?probe=4a88622321) | May 26, 2023 |
| Dell      | Latitude 5480               | [adb6ba25f1](https://linux-hardware.org/?probe=adb6ba25f1) | May 25, 2023 |
| Dell      | Latitude 5480               | [45b63ce664](https://linux-hardware.org/?probe=45b63ce664) | May 25, 2023 |
| Dell      | Latitude 7280               | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell      | Precision 5520              | [a5e0cc8586](https://linux-hardware.org/?probe=a5e0cc8586) | May 24, 2023 |
| HP        | EliteBook 850 G6            | [b38d6399b4](https://linux-hardware.org/?probe=b38d6399b4) | May 22, 2023 |
| Apple     | MacBookPro15,1              | [f1d994fa47](https://linux-hardware.org/?probe=f1d994fa47) | May 22, 2023 |
| Dell      | Latitude E7450              | [51f34cd446](https://linux-hardware.org/?probe=51f34cd446) | May 20, 2023 |
| Dell      | Latitude E7450              | [e844aeb177](https://linux-hardware.org/?probe=e844aeb177) | May 19, 2023 |
| HP        | OMEN by Laptop 16-b0xxx     | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| HP        | EliteBook 820 G1            | [9ba944eae5](https://linux-hardware.org/?probe=9ba944eae5) | May 09, 2023 |
| HP        | EliteBook 820 G1            | [3e9f94b26a](https://linux-hardware.org/?probe=3e9f94b26a) | May 09, 2023 |
| Dell      | Latitude E5440              | [6db42a9acc](https://linux-hardware.org/?probe=6db42a9acc) | May 08, 2023 |
| Dell      | Inspiron 17-7779            | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| Dell      | Latitude 5410               | [840aaee455](https://linux-hardware.org/?probe=840aaee455) | May 04, 2023 |
| Dell      | Latitude 5410               | [f95e1d32bf](https://linux-hardware.org/?probe=f95e1d32bf) | May 04, 2023 |
| Google    | Glimmer                     | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google    | Glimmer                     | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| HP        | Pavilion Laptop 15-cc1xx    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| Dell      | Inspiron 3593               | [5ac8ce1eb9](https://linux-hardware.org/?probe=5ac8ce1eb9) | Apr 19, 2023 |
| Lenovo    | ThinkPad E15 Gen 3 20YG0... | [7ec2b3ff95](https://linux-hardware.org/?probe=7ec2b3ff95) | Apr 14, 2023 |
| HP        | EliteBook 8470w             | [47e8a4441b](https://linux-hardware.org/?probe=47e8a4441b) | Apr 04, 2023 |
| HP        | EliteBook 850 G6            | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Dell      | G3 3500                     | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| HP        | Laptop 15s-fq5xxx           | [f84f8c068b](https://linux-hardware.org/?probe=f84f8c068b) | Mar 15, 2023 |
| Lenovo    | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HP        | EliteBook 840 G5            | [948a77b264](https://linux-hardware.org/?probe=948a77b264) | Mar 04, 2023 |
| HP        | EliteBook 840 G5            | [f245db2b9a](https://linux-hardware.org/?probe=f245db2b9a) | Mar 04, 2023 |
| Samsung   | 300E5EV/300E4EV/270E5EV/... | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
| HP        | ProBook 450 G8 Notebook ... | [009eefdc1d](https://linux-hardware.org/?probe=009eefdc1d) | Feb 28, 2023 |
| HP        | ProBook 450 G8 Notebook ... | [17a7ee80ac](https://linux-hardware.org/?probe=17a7ee80ac) | Feb 28, 2023 |
| HP        | ProBook 645 G1              | [329c0a65eb](https://linux-hardware.org/?probe=329c0a65eb) | Feb 25, 2023 |
| Lenovo    | Legion S7 15ACH6 82K8       | [6f65703034](https://linux-hardware.org/?probe=6f65703034) | Feb 19, 2023 |
| HP        | Pavilion g6                 | [876f755425](https://linux-hardware.org/?probe=876f755425) | Feb 19, 2023 |
| HP        | Notebook                    | [047fd0d69e](https://linux-hardware.org/?probe=047fd0d69e) | Feb 18, 2023 |
| Apple     | MacBookPro11,3              | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| Apple     | MacBookPro11,3              | [b7cec06bcb](https://linux-hardware.org/?probe=b7cec06bcb) | Jan 30, 2023 |
| Dell      | Latitude E7470              | [42ace80c0b](https://linux-hardware.org/?probe=42ace80c0b) | Jan 27, 2023 |
| HP        | ProBook 6565b               | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| HP        | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| HP        | ENVY dv7                    | [4b7b0f98af](https://linux-hardware.org/?probe=4b7b0f98af) | Jan 15, 2023 |
| Lenovo    | S20-30 20421                | [43bee9503c](https://linux-hardware.org/?probe=43bee9503c) | Jan 11, 2023 |
| HP        | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| HP        | ENVY dv6                    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| Haier     | Y11C                        | [cc9a03834f](https://linux-hardware.org/?probe=cc9a03834f) | Dec 21, 2022 |
| HP        | Laptop 15s-fq5xxx           | [86f0e8ad5d](https://linux-hardware.org/?probe=86f0e8ad5d) | Dec 20, 2022 |
| HP        | Laptop 15s-fq5xxx           | [8122fe7426](https://linux-hardware.org/?probe=8122fe7426) | Dec 20, 2022 |
| Dell      | Latitude D620               | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| Toshiba   | PORTEGE Z30t-A              | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Dell      | Vostro 3500                 | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| Lenovo    | ThinkPad E14 20RAS04700     | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| Dell      | Latitude D620               | [d45ad40496](https://linux-hardware.org/?probe=d45ad40496) | Nov 21, 2022 |
| HP        | EliteBook 840 G3            | [835a83d0ea](https://linux-hardware.org/?probe=835a83d0ea) | Nov 20, 2022 |
| HP        | Laptop 15-dw3xxx            | [03426a19e5](https://linux-hardware.org/?probe=03426a19e5) | Nov 16, 2022 |
| Timi      | TM1613                      | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| HP        | Laptop 14-dq2xxx            | [dcb6d439d4](https://linux-hardware.org/?probe=dcb6d439d4) | Nov 13, 2022 |
| Lenovo    | ThinkPad E580 20KTA001GE    | [55dc6ac7ba](https://linux-hardware.org/?probe=55dc6ac7ba) | Oct 31, 2022 |
| Dell      | Inspiron 13-7359            | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| Dell      | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| HP        | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| Dell      | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell      | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP        | Laptop 15s-du3xxx           | [cbacce92bd](https://linux-hardware.org/?probe=cbacce92bd) | Oct 05, 2022 |
| HP        | Pavilion dv6                | [2830144a8a](https://linux-hardware.org/?probe=2830144a8a) | Oct 04, 2022 |
| HP        | EliteBook 850 G8 Noteboo... | [b01a9ac97f](https://linux-hardware.org/?probe=b01a9ac97f) | Sep 24, 2022 |
| HP        | Laptop 15-bs1xx             | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| HP        | ENVY 15                     | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| HP        | EliteBook 840 G2            | [ca96e9bf9b](https://linux-hardware.org/?probe=ca96e9bf9b) | Sep 14, 2022 |
| HP        | EliteBook 840 G3            | [be88e72feb](https://linux-hardware.org/?probe=be88e72feb) | Sep 14, 2022 |
| HP        | EliteBook 840 G3            | [2b1c502b28](https://linux-hardware.org/?probe=2b1c502b28) | Sep 14, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| HP        | ProBook 4540s               | [c1bf52b653](https://linux-hardware.org/?probe=c1bf52b653) | Sep 13, 2022 |
| HP        | ProBook 4540s               | [320e270f44](https://linux-hardware.org/?probe=320e270f44) | Sep 13, 2022 |
| HP        | EliteBook Folio 9470m       | [c03777782c](https://linux-hardware.org/?probe=c03777782c) | Sep 13, 2022 |
| HP        | Unknown                     | [5cf262a728](https://linux-hardware.org/?probe=5cf262a728) | Sep 10, 2022 |
| Lenovo    | ThinkPad T470 20HES3370A    | [5beda28487](https://linux-hardware.org/?probe=5beda28487) | Sep 09, 2022 |
| Dell      | Latitude 3340               | [ec720c63b1](https://linux-hardware.org/?probe=ec720c63b1) | Sep 06, 2022 |
| Lenovo    | ThinkPad T470 20HES3370A    | [3a466cef0a](https://linux-hardware.org/?probe=3a466cef0a) | Sep 05, 2022 |
| Dell      | Latitude E6420              | [98a628a92a](https://linux-hardware.org/?probe=98a628a92a) | Sep 03, 2022 |
| Dell      | Latitude E6420              | [e9c43bd2ab](https://linux-hardware.org/?probe=e9c43bd2ab) | Sep 03, 2022 |
| Dell      | Latitude 3340               | [b9d472b965](https://linux-hardware.org/?probe=b9d472b965) | Sep 01, 2022 |
| Dell      | Latitude 7390               | [571b195a12](https://linux-hardware.org/?probe=571b195a12) | Aug 31, 2022 |
| Dell      | Latitude 7390               | [3c3f6114f6](https://linux-hardware.org/?probe=3c3f6114f6) | Aug 31, 2022 |
| HP        | EliteBook 840 G2            | [5ba91d8167](https://linux-hardware.org/?probe=5ba91d8167) | Aug 30, 2022 |
| HP        | EliteBook 840 G1            | [23d73aa95c](https://linux-hardware.org/?probe=23d73aa95c) | Aug 30, 2022 |
| HP        | EliteBook 840 G2            | [bed3be5142](https://linux-hardware.org/?probe=bed3be5142) | Aug 30, 2022 |
| HP        | EliteBook 840 G2            | [b588415d06](https://linux-hardware.org/?probe=b588415d06) | Aug 30, 2022 |
| Lenovo    | ThinkPad T470 20HES3370A    | [3b1630e4bc](https://linux-hardware.org/?probe=3b1630e4bc) | Aug 30, 2022 |
| HP        | Unknown                     | [9b22ce41e3](https://linux-hardware.org/?probe=9b22ce41e3) | Aug 27, 2022 |
| Dell      | Latitude 7400               | [7f870ac8c2](https://linux-hardware.org/?probe=7f870ac8c2) | Aug 17, 2022 |
| Acer      | Predator PH317-53           | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo    | IdeaPad 330-15IKB 81DE      | [072d897eda](https://linux-hardware.org/?probe=072d897eda) | Jul 28, 2022 |
| Dell      | Latitude E6420              | [07a671ae31](https://linux-hardware.org/?probe=07a671ae31) | Jul 22, 2022 |
| Dell      | Latitude E5440              | [3b30865387](https://linux-hardware.org/?probe=3b30865387) | Jul 20, 2022 |
| Sony      | VPCEA26FG                   | [c5432e157a](https://linux-hardware.org/?probe=c5432e157a) | Jul 11, 2022 |
| Dell      | Latitude E7450              | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| Sony      | VPCEA26FG                   | [2075c04c4c](https://linux-hardware.org/?probe=2075c04c4c) | Jul 03, 2022 |
| Sony      | VPCEA26FG                   | [b72a4de42b](https://linux-hardware.org/?probe=b72a4de42b) | Jul 01, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | [18fbe5a2d0](https://linux-hardware.org/?probe=18fbe5a2d0) | Jun 28, 2022 |
| HP        | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| HP        | EliteBook 8470p             | [f9895656b6](https://linux-hardware.org/?probe=f9895656b6) | Jun 23, 2022 |
| HP        | EliteBook 8470p             | [2e2bcb63d7](https://linux-hardware.org/?probe=2e2bcb63d7) | Jun 23, 2022 |
| HP        | EliteBook 850 G5            | [085f5c458d](https://linux-hardware.org/?probe=085f5c458d) | Jun 10, 2022 |
| HP        | Laptop 15s-fq2xxx           | [5bcb742cbe](https://linux-hardware.org/?probe=5bcb742cbe) | Jun 04, 2022 |
| Lenovo    | ThinkPad T450 20BV0005US    | [a795ed872f](https://linux-hardware.org/?probe=a795ed872f) | Jun 03, 2022 |
| HP        | EliteBook 8460p             | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP        | EliteBook 8460p             | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell      | Inspiron 3543               | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| HP        | Notebook                    | [4508e41795](https://linux-hardware.org/?probe=4508e41795) | May 22, 2022 |
| HP        | Notebook                    | [dc587c572e](https://linux-hardware.org/?probe=dc587c572e) | May 22, 2022 |
| Dell      | Latitude 3330               | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Dell      | Latitude E6420              | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| HP        | EliteBook 840 G1            | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| HP        | EliteBook 840 G2            | [3e0d410668](https://linux-hardware.org/?probe=3e0d410668) | Apr 19, 2022 |
| HP        | ProBook 450 G8 Notebook ... | [1974bfe63a](https://linux-hardware.org/?probe=1974bfe63a) | Apr 15, 2022 |
| Dell      | Latitude 3520               | [ee204b07aa](https://linux-hardware.org/?probe=ee204b07aa) | Apr 11, 2022 |
| HP        | Pavilion TS 11              | [9a817f6695](https://linux-hardware.org/?probe=9a817f6695) | Apr 09, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Dell      | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | [1936ee53b3](https://linux-hardware.org/?probe=1936ee53b3) | Mar 22, 2022 |
| Dell      | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Lenovo    | V110-15IKB 80TH             | [a3aeef468a](https://linux-hardware.org/?probe=a3aeef468a) | Mar 12, 2022 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [e0169c3e87](https://linux-hardware.org/?probe=e0169c3e87) | Feb 23, 2022 |
| HP        | EliteBook Folio 9470m       | [1aa838368f](https://linux-hardware.org/?probe=1aa838368f) | Feb 20, 2022 |
| HP        | EliteBook Folio 9470m       | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| Dell      | Inspiron 3501               | [7fdd5b66fc](https://linux-hardware.org/?probe=7fdd5b66fc) | Feb 14, 2022 |
| Lenovo    | IdeaPad 510-15ISK 80SR      | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Dell      | Inspiron 5547               | [2d6ff07a82](https://linux-hardware.org/?probe=2d6ff07a82) | Feb 12, 2022 |
| Dell      | Inspiron 3501               | [0dd77f2f7a](https://linux-hardware.org/?probe=0dd77f2f7a) | Feb 12, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [5a9a256568](https://linux-hardware.org/?probe=5a9a256568) | Feb 01, 2022 |
| Dell      | Inspiron 3501               | [4a0c4a62b7](https://linux-hardware.org/?probe=4a0c4a62b7) | Feb 01, 2022 |
| Dell      | Inspiron 3501               | [c902cc42a6](https://linux-hardware.org/?probe=c902cc42a6) | Jan 18, 2022 |
| Dell      | Inspiron 3501               | [ce839c3628](https://linux-hardware.org/?probe=ce839c3628) | Jan 08, 2022 |
| Lenovo    | ThinkPad T540p 20BFS5630... | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| HP        | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| HP        | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP        | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP        | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| Acer      | Aspire ES1-411              | [9a5ebb6379](https://linux-hardware.org/?probe=9a5ebb6379) | Dec 19, 2021 |
| HP        | EliteBook 8470p             | [0f7389c7d9](https://linux-hardware.org/?probe=0f7389c7d9) | Dec 14, 2021 |
| Dell      | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell      | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| HP        | ZBook 15 G3                 | [e662c8b956](https://linux-hardware.org/?probe=e662c8b956) | Dec 07, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | [538c96bb62](https://linux-hardware.org/?probe=538c96bb62) | Nov 26, 2021 |
| Dell      | Latitude E6440              | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| HP        | Unknown                     | [ef28d45f68](https://linux-hardware.org/?probe=ef28d45f68) | Nov 23, 2021 |
| Dell      | G3 3579                     | [38e9f54ba1](https://linux-hardware.org/?probe=38e9f54ba1) | Nov 23, 2021 |
| Dell      | Inspiron 5520               | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| HP        | Unknown                     | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | [cd386145b8](https://linux-hardware.org/?probe=cd386145b8) | Nov 18, 2021 |
| HP        | Pavilion Laptop 14-ce2xx... | [f9ebb771b0](https://linux-hardware.org/?probe=f9ebb771b0) | Nov 14, 2021 |
| HP        | ZBook 15 G3                 | [67e5184b17](https://linux-hardware.org/?probe=67e5184b17) | Nov 13, 2021 |
| Dell      | Vostro 1500                 | [23aeb68ca2](https://linux-hardware.org/?probe=23aeb68ca2) | Nov 11, 2021 |
| HP        | ZBook 15 G3                 | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Dell      | Inspiron 3501               | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| Dell      | Inspiron 15-3567            | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| HP        | 650                         | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| Apple     | MacBookPro14,1              | [bb1aa448fd](https://linux-hardware.org/?probe=bb1aa448fd) | Oct 20, 2021 |
| HP        | ProBook 450 G7              | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| Lenovo    | ThinkBook 15-IIL 20SM       | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| HP        | ProBook 450 G7              | [f2a84de135](https://linux-hardware.org/?probe=f2a84de135) | Oct 12, 2021 |
| Dell      | Latitude E5570              | [938d1a781d](https://linux-hardware.org/?probe=938d1a781d) | Oct 08, 2021 |
| Lenovo    | ThinkPad X220 Tablet 429... | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [196fa579f8](https://linux-hardware.org/?probe=196fa579f8) | Oct 04, 2021 |
| Haier     | Y11C                        | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Dell      | Precision M6400             | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| Haier     | Y11C                        | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| Dell      | Inspiron 5515               | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Lenovo    | ThinkPad X220 Tablet 429... | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X571... | [966a09526a](https://linux-hardware.org/?probe=966a09526a) | Aug 14, 2021 |
| Dell      | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Dell      | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| Dell      | Inspiron 5593               | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| Dell      | Latitude E5250              | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Dell      | Latitude E5250              | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell      | Latitude E5250              | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Dell      | Latitude E5250              | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| HP        | EliteBook 8440p             | [d89b69a6a3](https://linux-hardware.org/?probe=d89b69a6a3) | Jul 16, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | [d320594f42](https://linux-hardware.org/?probe=d320594f42) | Jul 07, 2021 |
| Lenovo    | ThinkPad E14 20RA007SAD     | [eb51ce8f36](https://linux-hardware.org/?probe=eb51ce8f36) | Jul 07, 2021 |
| Dell      | Precision 5530              | [7d267375f2](https://linux-hardware.org/?probe=7d267375f2) | Jul 05, 2021 |
| Dell      | Inspiron 5593               | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| HP        | Pavilion Notebook           | [f5ac8e2aca](https://linux-hardware.org/?probe=f5ac8e2aca) | Jun 25, 2021 |
| HP        | Pavilion dv6                | [c3529dc2aa](https://linux-hardware.org/?probe=c3529dc2aa) | Jun 24, 2021 |
| Dell      | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| Dell      | Latitude 3510               | [79c73e5595](https://linux-hardware.org/?probe=79c73e5595) | Jun 09, 2021 |
| Toshiba   | Satellite L850              | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Dell      | Vostro 14-3468              | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| Dell      | Latitude E5250              | [8c3b8c27c8](https://linux-hardware.org/?probe=8c3b8c27c8) | May 10, 2021 |
| Dell      | Latitude E6420              | [6e3288ca3a](https://linux-hardware.org/?probe=6e3288ca3a) | Apr 11, 2021 |
| Dell      | Inspiron 17-7779            | [2cf1f86b67](https://linux-hardware.org/?probe=2cf1f86b67) | Apr 06, 2021 |
| Gigabyte  | AERO 15-SA                  | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Gigabyte  | AERO 15-SA                  | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Dell      | Latitude 3510               | [1ef27c1786](https://linux-hardware.org/?probe=1ef27c1786) | Mar 25, 2021 |
| HP        | EliteBook 2170p             | [eba311c4d7](https://linux-hardware.org/?probe=eba311c4d7) | Mar 22, 2021 |
| HP        | EliteBook 2170p             | [e506fc315e](https://linux-hardware.org/?probe=e506fc315e) | Mar 21, 2021 |
| Lenovo    | IdeaPad L340-15IWL 81LG     | [eb713030d2](https://linux-hardware.org/?probe=eb713030d2) | Mar 18, 2021 |
| Dell      | Latitude E6420              | [a062baeb24](https://linux-hardware.org/?probe=a062baeb24) | Mar 12, 2021 |
| HP        | EliteBook 850 G7 Noteboo... | [6dbe550700](https://linux-hardware.org/?probe=6dbe550700) | Feb 28, 2021 |
| HP        | EliteBook 840 G3            | [b8a8ea9182](https://linux-hardware.org/?probe=b8a8ea9182) | Feb 24, 2021 |
| HP        | EliteBook 840 G3            | [ce415da689](https://linux-hardware.org/?probe=ce415da689) | Feb 23, 2021 |
| ASUSTek   | TUF Gaming FA706IU_FA706... | [64c73f58bb](https://linux-hardware.org/?probe=64c73f58bb) | Feb 22, 2021 |
| Lenovo    | ThinkBook 15-IIL 20SM       | [0426a1c07e](https://linux-hardware.org/?probe=0426a1c07e) | Feb 20, 2021 |
| HP        | 14                          | [d5382b721f](https://linux-hardware.org/?probe=d5382b721f) | Feb 11, 2021 |
| Toshiba   | Satellite S50t-B            | [2fe86bc977](https://linux-hardware.org/?probe=2fe86bc977) | Feb 06, 2021 |
| Toshiba   | Satellite S50t-B            | [ec72426035](https://linux-hardware.org/?probe=ec72426035) | Feb 05, 2021 |
| Toshiba   | Satellite S50t-B            | [f7709c05cb](https://linux-hardware.org/?probe=f7709c05cb) | Feb 05, 2021 |
| HP        | 14                          | [f27a999e26](https://linux-hardware.org/?probe=f27a999e26) | Feb 03, 2021 |
| Sony      | SVE15126CXS                 | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| Apple     | MacBookPro16,2              | [e3790fd911](https://linux-hardware.org/?probe=e3790fd911) | Jan 31, 2021 |
| Apple     | MacBookPro16,2              | [0ee13de953](https://linux-hardware.org/?probe=0ee13de953) | Jan 31, 2021 |
| Lenovo    | ThinkPad E15 20RD0088UE     | [d2bfe04a2b](https://linux-hardware.org/?probe=d2bfe04a2b) | Jan 28, 2021 |
| HP        | ProBook 450 G5              | [e4b829fff8](https://linux-hardware.org/?probe=e4b829fff8) | Jan 26, 2021 |
| HP        | ProBook 450 G2              | [7db1cae3c0](https://linux-hardware.org/?probe=7db1cae3c0) | Jan 25, 2021 |
| HP        | ProBook 450 G5              | [0421fbf0d1](https://linux-hardware.org/?probe=0421fbf0d1) | Jan 25, 2021 |
| Lenovo    | ThinkPad T460 20FMS39800    | [7b4f78f648](https://linux-hardware.org/?probe=7b4f78f648) | Jan 10, 2021 |
| Dell      | Latitude E6510              | [2557f813e4](https://linux-hardware.org/?probe=2557f813e4) | Dec 15, 2020 |
| Dell      | Inspiron 15 7000 Gaming     | [b04b3b207e](https://linux-hardware.org/?probe=b04b3b207e) | Dec 11, 2020 |
| Fujitsu   | LIFEBOOK E752               | [252afde67a](https://linux-hardware.org/?probe=252afde67a) | Dec 08, 2020 |
| Lenovo    | ThinkBook 15-IML 20RW       | [f84c7affac](https://linux-hardware.org/?probe=f84c7affac) | Dec 07, 2020 |
| Dell      | Latitude E7440              | [0d04075b3e](https://linux-hardware.org/?probe=0d04075b3e) | Dec 03, 2020 |
| Lenovo    | ThinkPad W500 40612HU       | [06465bf227](https://linux-hardware.org/?probe=06465bf227) | Dec 01, 2020 |
| Lenovo    | ThinkPad T60 1951WAT        | [4da418a597](https://linux-hardware.org/?probe=4da418a597) | Nov 28, 2020 |
| Dell      | Latitude E7450              | [20ee05f0fa](https://linux-hardware.org/?probe=20ee05f0fa) | Nov 27, 2020 |
| Dell      | Latitude E7440              | [9627b61c6f](https://linux-hardware.org/?probe=9627b61c6f) | Nov 25, 2020 |
| Dell      | Latitude E7450              | [e9a83f5dc5](https://linux-hardware.org/?probe=e9a83f5dc5) | Nov 24, 2020 |
| HP        | EliteBook 2540p             | [00a011fa83](https://linux-hardware.org/?probe=00a011fa83) | Nov 22, 2020 |
| HP        | EliteBook 2540p             | [12f4630385](https://linux-hardware.org/?probe=12f4630385) | Nov 22, 2020 |
| Lenovo    | ThinkPad E560 20EV0010UK    | [a52f064714](https://linux-hardware.org/?probe=a52f064714) | Nov 19, 2020 |
| Dell      | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| HP        | 650                         | [67e06d1514](https://linux-hardware.org/?probe=67e06d1514) | Nov 09, 2020 |
| HP        | Pavilion g6                 | [98124ff6a4](https://linux-hardware.org/?probe=98124ff6a4) | Nov 08, 2020 |
| HP        | EliteBook 8470p             | [847807840d](https://linux-hardware.org/?probe=847807840d) | Nov 05, 2020 |
| HP        | ProBook 6560b               | [934ffc99e6](https://linux-hardware.org/?probe=934ffc99e6) | Oct 30, 2020 |
| Dell      | Inspiron 15-3567            | [2b138e461a](https://linux-hardware.org/?probe=2b138e461a) | Oct 26, 2020 |
| Dell      | Inspiron 15-3567            | [4460c27fd7](https://linux-hardware.org/?probe=4460c27fd7) | Oct 26, 2020 |
| Dell      | Inspiron 15-3567            | [b647bae107](https://linux-hardware.org/?probe=b647bae107) | Oct 24, 2020 |
| Apple     | MacBookAir6,2               | [3509d2f6e3](https://linux-hardware.org/?probe=3509d2f6e3) | Oct 22, 2020 |
| Toshiba   | PORTEGE Z30-B               | [d7c9922a29](https://linux-hardware.org/?probe=d7c9922a29) | Oct 21, 2020 |
| HP        | ProBook 4340s               | [3db4ff09f4](https://linux-hardware.org/?probe=3db4ff09f4) | Oct 18, 2020 |
| Dell      | Latitude E6540              | [36688dde6e](https://linux-hardware.org/?probe=36688dde6e) | Oct 06, 2020 |
| HP        | 650                         | [1ea9bf783e](https://linux-hardware.org/?probe=1ea9bf783e) | Oct 03, 2020 |
| HP        | ProBook 450 G5              | [94eb24ff74](https://linux-hardware.org/?probe=94eb24ff74) | Oct 02, 2020 |
| Dell      | Latitude E4300              | [12b944fb30](https://linux-hardware.org/?probe=12b944fb30) | Oct 02, 2020 |
| HP        | ProBook 450 G5              | [cb2cef5fcf](https://linux-hardware.org/?probe=cb2cef5fcf) | Oct 01, 2020 |
| Lenovo    | ThinkPad T440p 20AWS0DU0... | [caf12cb57f](https://linux-hardware.org/?probe=caf12cb57f) | Sep 30, 2020 |
| Lenovo    | ThinkPad T440p 20AWS0DU0... | [d3cc62a7f5](https://linux-hardware.org/?probe=d3cc62a7f5) | Sep 30, 2020 |
| Dell      | Latitude E7450              | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell      | Latitude E7450              | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| Samsung   | QX311/QX411/QX412/QX511     | [b6f7494e44](https://linux-hardware.org/?probe=b6f7494e44) | Sep 21, 2020 |
| HP        | 650                         | [278a9afdeb](https://linux-hardware.org/?probe=278a9afdeb) | Sep 21, 2020 |
| Dell      | Vostro 14-3468              | [4ab76fd5c2](https://linux-hardware.org/?probe=4ab76fd5c2) | Sep 20, 2020 |
| HP        | 650                         | [8aaa8d7e4d](https://linux-hardware.org/?probe=8aaa8d7e4d) | Sep 19, 2020 |
| Samsung   | QX311/QX411/QX412/QX511     | [1ec83fe97e](https://linux-hardware.org/?probe=1ec83fe97e) | Sep 17, 2020 |
| HP        | EliteBook 840 G3            | [d6204bd9e2](https://linux-hardware.org/?probe=d6204bd9e2) | Sep 16, 2020 |
| HP        | ProBook 455 G7              | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP        | ENVY 17                     | [08285409ad](https://linux-hardware.org/?probe=08285409ad) | Sep 13, 2020 |
| HP        | ProBook 455 G7              | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| HP        | ProBook 450 G7              | [85d0104e28](https://linux-hardware.org/?probe=85d0104e28) | Sep 10, 2020 |
| Dell      | Inspiron 15-3573            | [9be442a7dd](https://linux-hardware.org/?probe=9be442a7dd) | Sep 07, 2020 |
| HP        | ProBook 440 G7              | [1c4d1f875b](https://linux-hardware.org/?probe=1c4d1f875b) | Sep 01, 2020 |
| HP        | ProBook 4340s               | [f7580ed51b](https://linux-hardware.org/?probe=f7580ed51b) | Aug 31, 2020 |
| Dell      | Latitude E7250              | [ff13c002c8](https://linux-hardware.org/?probe=ff13c002c8) | Aug 27, 2020 |
| HP        | EliteBook 820 G2            | [f35b20067d](https://linux-hardware.org/?probe=f35b20067d) | Aug 25, 2020 |
| HP        | Laptop 15-da2xxx            | [031606a1a9](https://linux-hardware.org/?probe=031606a1a9) | Aug 21, 2020 |
| Dell      | Latitude E7250              | [63024e0df6](https://linux-hardware.org/?probe=63024e0df6) | Aug 19, 2020 |
| HP        | ProBook 450 G7              | [8a5fc0bc23](https://linux-hardware.org/?probe=8a5fc0bc23) | Aug 13, 2020 |
| HP        | ProBook 440 G5              | [fa604583d6](https://linux-hardware.org/?probe=fa604583d6) | Aug 10, 2020 |
| HP        | ProBook 440 G5              | [255da50641](https://linux-hardware.org/?probe=255da50641) | Aug 10, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | [930fbc43ed](https://linux-hardware.org/?probe=930fbc43ed) | Aug 09, 2020 |
| HP        | Pavilion Notebook           | [f62759a869](https://linux-hardware.org/?probe=f62759a869) | Aug 05, 2020 |
| Dell      | Inspiron 15-3567            | [4af4cdfef7](https://linux-hardware.org/?probe=4af4cdfef7) | Jul 30, 2020 |
| HP        | ProBook 440 G7              | [4b38ecdae9](https://linux-hardware.org/?probe=4b38ecdae9) | Jul 28, 2020 |
| HP        | EliteBook 840 G2            | [9dbea8590b](https://linux-hardware.org/?probe=9dbea8590b) | Jul 19, 2020 |
| HP        | ProBook 450 G7              | [45478d9106](https://linux-hardware.org/?probe=45478d9106) | Jul 18, 2020 |
| HP        | ProBook 470 G2              | [c42c686ae8](https://linux-hardware.org/?probe=c42c686ae8) | Jul 09, 2020 |
| MOTION    | NVX00                       | [fd07831802](https://linux-hardware.org/?probe=fd07831802) | Jul 04, 2020 |
| HP        | ProBook 450 G3              | [a12518d58c](https://linux-hardware.org/?probe=a12518d58c) | Jun 30, 2020 |
| Dell      | Latitude E6440              | [a7fe187945](https://linux-hardware.org/?probe=a7fe187945) | Jun 28, 2020 |
| Haier     | Y11C                        | [6b98c2c449](https://linux-hardware.org/?probe=6b98c2c449) | Jun 23, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | [8c8ed3d489](https://linux-hardware.org/?probe=8c8ed3d489) | Jun 06, 2020 |
| Haier     | Y11C                        | [7f9f93809f](https://linux-hardware.org/?probe=7f9f93809f) | Jun 01, 2020 |
| Dell      | Latitude E6410              | [60757c8504](https://linux-hardware.org/?probe=60757c8504) | May 21, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | [86a1d31e5c](https://linux-hardware.org/?probe=86a1d31e5c) | May 21, 2020 |
| Dell      | Latitude E7450              | [1031b89b4b](https://linux-hardware.org/?probe=1031b89b4b) | May 12, 2020 |
| HP        | EliteBook Folio 1040 G1     | [34b0697bf6](https://linux-hardware.org/?probe=34b0697bf6) | May 10, 2020 |
| Dell      | Latitude E6320              | [cedc2c5001](https://linux-hardware.org/?probe=cedc2c5001) | May 10, 2020 |
| Acer      | Aspire E5-576               | [581af37cda](https://linux-hardware.org/?probe=581af37cda) | Apr 19, 2020 |
| Dell      | Latitude E5420              | [6d2ddeb934](https://linux-hardware.org/?probe=6d2ddeb934) | Apr 18, 2020 |
| HP        | EliteBook 6930p             | [ea52c08646](https://linux-hardware.org/?probe=ea52c08646) | Apr 09, 2020 |
| Dell      | Latitude E4300              | [5e38d54ea2](https://linux-hardware.org/?probe=5e38d54ea2) | Mar 18, 2020 |
| HP        | EliteBook 8440p             | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Lenovo    | ThinkBook 15-IML 20RW       | [3cd2a73254](https://linux-hardware.org/?probe=3cd2a73254) | Mar 09, 2020 |
| HP        | Pavilion dv7                | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| HP        | EliteBook 8470p             | [e257c71d0b](https://linux-hardware.org/?probe=e257c71d0b) | Jan 14, 2020 |
| HP        | ProBook 450 G3              | [f73167982a](https://linux-hardware.org/?probe=f73167982a) | Jan 01, 2020 |
| Dell      | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| Dell      | Latitude XT3                | [4ccaa2e0e2](https://linux-hardware.org/?probe=4ccaa2e0e2) | Oct 29, 2019 |
| Lenovo    | ThinkPad T440 20B7S1NK05    | [310405c604](https://linux-hardware.org/?probe=310405c604) | Oct 29, 2019 |
| HP        | EliteBook 6930p             | [856fcded98](https://linux-hardware.org/?probe=856fcded98) | Oct 25, 2019 |
| HP        | Unknown                     | [25dd8af3ee](https://linux-hardware.org/?probe=25dd8af3ee) | Oct 22, 2019 |
| HP        | EliteBook 6930p             | [43c8f2b72c](https://linux-hardware.org/?probe=43c8f2b72c) | Sep 13, 2019 |
| HP        | EliteBook 6930p             | [964e933faf](https://linux-hardware.org/?probe=964e933faf) | Sep 13, 2019 |
| Samsung   | 940Z5L                      | [28c94787df](https://linux-hardware.org/?probe=28c94787df) | Sep 13, 2019 |
| AMI       | Unknown                     | [407590d103](https://linux-hardware.org/?probe=407590d103) | Sep 09, 2019 |
| HP        | ProBook 6470b               | [81e17acdb1](https://linux-hardware.org/?probe=81e17acdb1) | Aug 02, 2019 |
| HP        | EliteBook 840 G3            | [b419735d70](https://linux-hardware.org/?probe=b419735d70) | Jul 04, 2019 |
| Sony      | VPCCB490X                   | [ed39416136](https://linux-hardware.org/?probe=ed39416136) | Jun 22, 2019 |
| Haier     | Y11C                        | [ab6b2cf0e5](https://linux-hardware.org/?probe=ab6b2cf0e5) | Jun 20, 2019 |
| Haier     | Y11C                        | [74a3547ed6](https://linux-hardware.org/?probe=74a3547ed6) | Jun 20, 2019 |
| Dell      | Latitude E6420              | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell      | Latitude E6420              | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Haier     | Y11B                        | [d90f70d18f](https://linux-hardware.org/?probe=d90f70d18f) | May 11, 2019 |
| Haier     | Y11B                        | [e359a25a69](https://linux-hardware.org/?probe=e359a25a69) | Nov 18, 2018 |
| Haier     | Y11B                        | [13e5308d20](https://linux-hardware.org/?probe=13e5308d20) | Nov 18, 2018 |
| HP        | Pavilion Notebook           | [7e2949f7da](https://linux-hardware.org/?probe=7e2949f7da) | Nov 11, 2018 |
| Acer      | Aspire 5733                 | [970a40e3d0](https://linux-hardware.org/?probe=970a40e3d0) | Oct 23, 2018 |
| ASUSTek   | K53U                        | [f644624e98](https://linux-hardware.org/?probe=f644624e98) | Oct 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 71        | 24.23%  |
| Ubuntu 22.04       | 35        | 11.95%  |
| Ubuntu 18.04       | 20        | 6.83%   |
| Ubuntu 23.04       | 9         | 3.07%   |
| Zorin 16           | 7         | 2.39%   |
| Kali 2023.3        | 6         | 2.05%   |
| Pop!_OS 22.04      | 5         | 1.71%   |
| KDE neon 20.04     | 5         | 1.71%   |
| Arch               | 5         | 1.71%   |
| Ubuntu 22.10       | 4         | 1.37%   |
| Kali 2023.2        | 4         | 1.37%   |
| Debian 11          | 4         | 1.37%   |
| Ubuntu 23.10       | 3         | 1.02%   |
| Ubuntu 21.10       | 3         | 1.02%   |
| Ubuntu 21.04       | 3         | 1.02%   |
| Ubuntu 19.04       | 3         | 1.02%   |
| Pop!_OS 21.04      | 3         | 1.02%   |
| Pop!_OS 20.10      | 3         | 1.02%   |
| Pop!_OS 20.04      | 3         | 1.02%   |
| OpenMandriva 4.3   | 3         | 1.02%   |
| Linux Mint 20      | 3         | 1.02%   |
| Kubuntu 22.04      | 3         | 1.02%   |
| Fedora 37          | 3         | 1.02%   |
| Fedora 33          | 3         | 1.02%   |
| Elementary 6.1     | 3         | 1.02%   |
| ArcoLinux Rolling  | 3         | 1.02%   |
| Arch Rolling       | 3         | 1.02%   |
| Zorin 15           | 2         | 0.68%   |
| Xero Rolling       | 2         | 0.68%   |
| OpenMandriva 4.2   | 2         | 0.68%   |
| OpenMandriva 23.03 | 2         | 0.68%   |
| OpenMandriva 23.01 | 2         | 0.68%   |
| Linux Mint 21.2    | 2         | 0.68%   |
| Linux Mint 21.1    | 2         | 0.68%   |
| Linux Mint 20.3    | 2         | 0.68%   |
| Linux Mint 20.2    | 2         | 0.68%   |
| Linux Mint 20.1    | 2         | 0.68%   |
| Kali 2022.3        | 2         | 0.68%   |
| Fedora 38          | 2         | 0.68%   |
| Fedora 36          | 2         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 152       | 53.33%  |
| Kali         | 14        | 4.91%   |
| Fedora       | 14        | 4.91%   |
| Pop!_OS      | 13        | 4.56%   |
| Linux Mint   | 12        | 4.21%   |
| Zorin        | 10        | 3.51%   |
| OpenMandriva | 8         | 2.81%   |
| Arch         | 8         | 2.81%   |
| Kubuntu      | 6         | 2.11%   |
| KDE neon     | 6         | 2.11%   |
| Manjaro      | 4         | 1.4%    |
| Debian       | 4         | 1.4%    |
| ArcoLinux    | 4         | 1.4%    |
| Ubuntu Unity | 3         | 1.05%   |
| Endless      | 3         | 1.05%   |
| Elementary   | 3         | 1.05%   |
| Xero         | 2         | 0.7%    |
| Parrot       | 2         | 0.7%    |
| Nobara       | 2         | 0.7%    |
| Garuda Linux | 2         | 0.7%    |
| Artix        | 2         | 0.7%    |
| Xubuntu      | 1         | 0.35%   |
| ROSA         | 1         | 0.35%   |
| Rocky Linux  | 1         | 0.35%   |
| RHEL         | 1         | 0.35%   |
| Oracle Linux | 1         | 0.35%   |
| Lubuntu      | 1         | 0.35%   |
| LinuxFX      | 1         | 0.35%   |
| EndeavourOS  | 1         | 0.35%   |
| Deepin       | 1         | 0.35%   |
| Clear Linux  | 1         | 0.35%   |
| AlmaLinux    | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 9         | 2.85%   |
| 5.15.0-46-generic       | 8         | 2.53%   |
| 5.19.0-42-generic       | 5         | 1.58%   |
| 5.15.0-47-generic       | 5         | 1.58%   |
| 5.11.0-37-generic       | 5         | 1.58%   |
| 6.3.0-kali1-amd64       | 4         | 1.27%   |
| 6.2.0-34-generic        | 4         | 1.27%   |
| 6.2.0-32-generic        | 4         | 1.27%   |
| 5.4.0-48-generic        | 4         | 1.27%   |
| 5.4.0-47-generic        | 4         | 1.27%   |
| 5.4.0-40-generic        | 4         | 1.27%   |
| 6.2.0-35-generic        | 3         | 0.95%   |
| 5.8.0-7630-generic      | 3         | 0.95%   |
| 5.8.0-41-generic        | 3         | 0.95%   |
| 5.4.0-54-generic        | 3         | 0.95%   |
| 5.4.0-52-generic        | 3         | 0.95%   |
| 5.4.0-26-generic        | 3         | 0.95%   |
| 5.3.0-28-generic        | 3         | 0.95%   |
| 5.19.0-46-generic       | 3         | 0.95%   |
| 5.19.0-41-generic       | 3         | 0.95%   |
| 5.16.7-desktop-1omv4003 | 3         | 0.95%   |
| 5.15.0-79-generic       | 3         | 0.95%   |
| 5.15.0-58-generic       | 3         | 0.95%   |
| 5.15.0-56-generic       | 3         | 0.95%   |
| 5.13.0-39-generic       | 3         | 0.95%   |
| 5.13.0-30-generic       | 3         | 0.95%   |
| 6.5.0-kali3-amd64       | 2         | 0.63%   |
| 6.4.0-kali3-amd64       | 2         | 0.63%   |
| 6.2.6-desktop-1omv2390  | 2         | 0.63%   |
| 6.2.0-39-generic        | 2         | 0.63%   |
| 6.2.0-31-generic        | 2         | 0.63%   |
| 6.2.0-26-generic        | 2         | 0.63%   |
| 6.1.1-desktop-1omv2290  | 2         | 0.63%   |
| 6.1.0-kali9-amd64       | 2         | 0.63%   |
| 6.0.8-300.fc37.x86_64   | 2         | 0.63%   |
| 5.9.8-200.fc33.x86_64   | 2         | 0.63%   |
| 5.8.0-59-generic        | 2         | 0.63%   |
| 5.8.0-48-generic        | 2         | 0.63%   |
| 5.4.0-91-generic        | 2         | 0.63%   |
| 5.4.0-58-generic        | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 16.95%  |
| 5.15.0  | 37        | 12.54%  |
| 5.19.0  | 23        | 7.8%    |
| 5.11.0  | 20        | 6.78%   |
| 6.2.0   | 19        | 6.44%   |
| 5.8.0   | 16        | 5.42%   |
| 5.13.0  | 16        | 5.42%   |
| 4.15.0  | 12        | 4.07%   |
| 5.3.0   | 7         | 2.37%   |
| 6.5.0   | 6         | 2.03%   |
| 5.0.0   | 6         | 2.03%   |
| 5.10.0  | 5         | 1.69%   |
| 6.3.0   | 4         | 1.36%   |
| 6.2.6   | 3         | 1.02%   |
| 6.0.8   | 3         | 1.02%   |
| 5.16.7  | 3         | 1.02%   |
| 4.18.0  | 3         | 1.02%   |
| 6.4.0   | 2         | 0.68%   |
| 6.1.1   | 2         | 0.68%   |
| 6.1.0   | 2         | 0.68%   |
| 5.9.8   | 2         | 0.68%   |
| 5.19.9  | 2         | 0.68%   |
| 5.10.14 | 2         | 0.68%   |
| 6.6.1   | 1         | 0.34%   |
| 6.5.9   | 1         | 0.34%   |
| 6.5.7   | 1         | 0.34%   |
| 6.5.6   | 1         | 0.34%   |
| 6.5.5   | 1         | 0.34%   |
| 6.5.4   | 1         | 0.34%   |
| 6.5.12  | 1         | 0.34%   |
| 6.5.11  | 1         | 0.34%   |
| 6.3.8   | 1         | 0.34%   |
| 6.2.10  | 1         | 0.34%   |
| 6.1.7   | 1         | 0.34%   |
| 6.1.64  | 1         | 0.34%   |
| 6.1.20  | 1         | 0.34%   |
| 6.1.12  | 1         | 0.34%   |
| 6.0.6   | 1         | 0.34%   |
| 6.0.19  | 1         | 0.34%   |
| 6.0.12  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 18.09%  |
| 5.15    | 38        | 12.97%  |
| 5.19    | 27        | 9.22%   |
| 6.2     | 23        | 7.85%   |
| 5.13    | 20        | 6.83%   |
| 5.11    | 20        | 6.83%   |
| 5.8     | 16        | 5.46%   |
| 6.5     | 12        | 4.1%    |
| 4.15    | 12        | 4.1%    |
| 6.1     | 8         | 2.73%   |
| 5.10    | 8         | 2.73%   |
| 6.0     | 7         | 2.39%   |
| 5.3     | 7         | 2.39%   |
| 5.0     | 6         | 2.05%   |
| 6.3     | 5         | 1.71%   |
| 5.16    | 5         | 1.71%   |
| 5.14    | 4         | 1.37%   |
| 5.9     | 3         | 1.02%   |
| 5.7     | 3         | 1.02%   |
| 5.17    | 3         | 1.02%   |
| 4.18    | 3         | 1.02%   |
| 6.4     | 2         | 0.68%   |
| 5.18    | 2         | 0.68%   |
| 5.12    | 2         | 0.68%   |
| 6.6     | 1         | 0.34%   |
| 5.6     | 1         | 0.34%   |
| 5.2     | 1         | 0.34%   |
| 4.9     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 275       | 98.57%  |
| i686   | 4         | 1.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 196       | 68.53%  |
| KDE5       | 25        | 8.74%   |
| Unknown    | 20        | 6.99%   |
| XFCE       | 15        | 5.24%   |
| X-Cinnamon | 11        | 3.85%   |
| KDE        | 5         | 1.75%   |
| Unity      | 3         | 1.05%   |
| Pantheon   | 3         | 1.05%   |
| MATE       | 2         | 0.7%    |
| i3         | 2         | 0.7%    |
| LXQt       | 1         | 0.35%   |
| KDE4       | 1         | 0.35%   |
| Hyprland   | 1         | 0.35%   |
| Deepin     | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 200       | 69.93%  |
| Wayland | 67        | 23.43%  |
| Unknown | 18        | 6.29%   |
| Tty     | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 128       | 45.07%  |
| GDM3    | 71        | 25%     |
| GDM     | 42        | 14.79%  |
| SDDM    | 22        | 7.75%   |
| LightDM | 15        | 5.28%   |
| TDM     | 4         | 1.41%   |
| XDM     | 1         | 0.35%   |
| KDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 241       | 85.16%  |
| Unknown | 17        | 6.01%   |
| en_GB   | 13        | 4.59%   |
| C       | 4         | 1.41%   |
| ur_PK   | 2         | 0.71%   |
| en_PK   | 2         | 0.71%   |
| en_IN   | 2         | 0.71%   |
| en_CA   | 1         | 0.35%   |
| en_AG   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 149       | 51.92%  |
| BIOS | 138       | 48.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 225       | 79.79%  |
| Tmpfs   | 18        | 6.38%   |
| Btrfs   | 18        | 6.38%   |
| Overlay | 9         | 3.19%   |
| Xfs     | 6         | 2.13%   |
| Unknown | 5         | 1.77%   |
| Zfs     | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 151       | 53.17%  |
| GPT     | 104       | 36.62%  |
| MBR     | 29        | 10.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 250       | 88.97%  |
| Yes       | 31        | 11.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 185       | 65.14%  |
| Yes       | 99        | 34.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 103       | 36.92%  |
| Dell                | 82        | 29.39%  |
| Lenovo              | 50        | 17.92%  |
| Haier               | 7         | 2.51%   |
| Apple               | 6         | 2.15%   |
| Toshiba             | 5         | 1.79%   |
| ASUSTek Computer    | 5         | 1.79%   |
| Acer                | 5         | 1.79%   |
| Sony                | 3         | 1.08%   |
| Samsung Electronics | 3         | 1.08%   |
| Fujitsu             | 2         | 0.72%   |
| Timi                | 1         | 0.36%   |
| MOTION              | 1         | 0.36%   |
| Google              | 1         | 0.36%   |
| Gigabyte Technology | 1         | 0.36%   |
| Gateway             | 1         | 0.36%   |
| Clevo               | 1         | 0.36%   |
| AMI                 | 1         | 0.36%   |
| Alienware           | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo ThinkBook 15 G2 ITL 20VE      | 5         | 1.79%   |
| HP ProBook 450 G7                    | 5         | 1.79%   |
| HP EliteBook 8470p                   | 5         | 1.79%   |
| HP EliteBook 840 G3                  | 5         | 1.79%   |
| Dell Latitude E7450                  | 5         | 1.79%   |
| Haier Y11C                           | 4         | 1.43%   |
| Dell Latitude E6420                  | 4         | 1.43%   |
| Unknown                              | 4         | 1.43%   |
| HP ProBook 450 G5                    | 3         | 1.08%   |
| HP EliteBook 840 G2                  | 3         | 1.08%   |
| Haier Y11B                           | 3         | 1.08%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GF00 | 2         | 0.72%   |
| Lenovo ThinkPad E15 Gen 2 20TD000EUE | 2         | 0.72%   |
| Lenovo ThinkBook 15-IML 20RW         | 2         | 0.72%   |
| Lenovo ThinkBook 15-IIL 20SM         | 2         | 0.72%   |
| HP ZBook 15 G3                       | 2         | 0.72%   |
| HP ProBook 450 G8 Notebook PC        | 2         | 0.72%   |
| HP ProBook 450 G3                    | 2         | 0.72%   |
| HP ProBook 440 G7                    | 2         | 0.72%   |
| HP Pavilion Notebook                 | 2         | 0.72%   |
| HP Pavilion g6                       | 2         | 0.72%   |
| HP Pavilion dv6                      | 2         | 0.72%   |
| HP Notebook                          | 2         | 0.72%   |
| HP Laptop 15s-fq5xxx                 | 2         | 0.72%   |
| HP Laptop 15-da2xxx                  | 2         | 0.72%   |
| HP EliteBook Folio 9470m             | 2         | 0.72%   |
| HP EliteBook 850 G6                  | 2         | 0.72%   |
| HP EliteBook 8440p                   | 2         | 0.72%   |
| HP EliteBook 840 G1                  | 2         | 0.72%   |
| HP EliteBook 6930p                   | 2         | 0.72%   |
| HP 650                               | 2         | 0.72%   |
| Dell Vostro 14-3468                  | 2         | 0.72%   |
| Dell Latitude E7440                  | 2         | 0.72%   |
| Dell Latitude E6440                  | 2         | 0.72%   |
| Dell Latitude E5440                  | 2         | 0.72%   |
| Dell Latitude E5250                  | 2         | 0.72%   |
| Dell Latitude E4300                  | 2         | 0.72%   |
| Dell Latitude 5480                   | 2         | 0.72%   |
| Dell Latitude 3510                   | 2         | 0.72%   |
| Dell Inspiron 5593                   | 2         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 45        | 16.13%  |
| HP EliteBook       | 35        | 12.54%  |
| Lenovo ThinkPad    | 28        | 10.04%  |
| HP ProBook         | 28        | 10.04%  |
| Dell Inspiron      | 23        | 8.24%   |
| HP Pavilion        | 13        | 4.66%   |
| HP Laptop          | 11        | 3.94%   |
| Lenovo ThinkBook   | 9         | 3.23%   |
| Lenovo IdeaPad     | 7         | 2.51%   |
| Dell Vostro        | 5         | 1.79%   |
| HP ENVY            | 4         | 1.43%   |
| Haier Y11C         | 4         | 1.43%   |
| Dell Precision     | 4         | 1.43%   |
| Acer Aspire        | 4         | 1.43%   |
| Unknown            | 4         | 1.43%   |
| Toshiba Satellite  | 3         | 1.08%   |
| HP ZBook           | 3         | 1.08%   |
| Haier Y11B         | 3         | 1.08%   |
| Toshiba PORTEGE    | 2         | 0.72%   |
| Lenovo Legion      | 2         | 0.72%   |
| HP Notebook        | 2         | 0.72%   |
| HP 650             | 2         | 0.72%   |
| Fujitsu LIFEBOOK   | 2         | 0.72%   |
| Dell XPS           | 2         | 0.72%   |
| Dell G3            | 2         | 0.72%   |
| Apple MacBookPro11 | 2         | 0.72%   |
| Timi TM1613        | 1         | 0.36%   |
| Sony VPCEA26FG     | 1         | 0.36%   |
| Sony VPCCB490X     | 1         | 0.36%   |
| Sony SVE15126CXS   | 1         | 0.36%   |
| Samsung QX311      | 1         | 0.36%   |
| Samsung 940Z5L     | 1         | 0.36%   |
| Samsung 300E5EV    | 1         | 0.36%   |
| MOTION J3500       | 1         | 0.36%   |
| Lenovo Z50-75      | 1         | 0.36%   |
| Lenovo V110-15IKB  | 1         | 0.36%   |
| Lenovo S20-30      | 1         | 0.36%   |
| Lenovo Edge        | 1         | 0.36%   |
| HP OMEN            | 1         | 0.36%   |
| HP 14              | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 31        | 11.11%  |
| 2020 | 30        | 10.75%  |
| 2014 | 29        | 10.39%  |
| 2011 | 26        | 9.32%   |
| 2016 | 23        | 8.24%   |
| 2013 | 20        | 7.17%   |
| 2017 | 19        | 6.81%   |
| 2012 | 19        | 6.81%   |
| 2018 | 18        | 6.45%   |
| 2021 | 15        | 5.38%   |
| 2010 | 15        | 5.38%   |
| 2015 | 14        | 5.02%   |
| 2008 | 9         | 3.23%   |
| 2022 | 4         | 1.43%   |
| 2009 | 3         | 1.08%   |
| 2006 | 2         | 0.72%   |
| 2023 | 1         | 0.36%   |
| 2007 | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 279       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 258       | 91.81%  |
| Enabled  | 23        | 8.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 278       | 99.64%  |
| Yes  | 1         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 92        | 32.74%  |
| 16.01-24.0 | 57        | 20.28%  |
| 8.01-16.0  | 57        | 20.28%  |
| 3.01-4.0   | 53        | 18.86%  |
| 32.01-64.0 | 14        | 4.98%   |
| 1.01-2.0   | 5         | 1.78%   |
| 24.01-32.0 | 3         | 1.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 96        | 31.68%  |
| 1.01-2.0  | 86        | 28.38%  |
| 4.01-8.0  | 56        | 18.48%  |
| 3.01-4.0  | 45        | 14.85%  |
| 8.01-16.0 | 14        | 4.62%   |
| 0.51-1.0  | 6         | 1.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 210       | 74.47%  |
| 2      | 66        | 23.4%   |
| 3      | 3         | 1.06%   |
| 0      | 2         | 0.71%   |
| 4      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 202       | 72.14%  |
| Yes       | 78        | 27.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 89.64%  |
| No        | 29        | 10.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 98.92%  |
| No        | 3         | 1.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 75%     |
| No        | 71        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Pakistan | 279       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lahore                         | 93        | 32.52%  |
| Karachi                        | 60        | 20.98%  |
| Islamabad                      | 45        | 15.73%  |
| Rawalpindi                     | 22        | 7.69%   |
| Faisalabad                     | 9         | 3.15%   |
| Multan                         | 7         | 2.45%   |
| Mirpur                         | 7         | 2.45%   |
| Sargodha                       | 4         | 1.4%    |
| Bahawalpur                     | 4         | 1.4%    |
| Peshawar                       | 2         | 0.7%    |
| Jhelum                         | 2         | 0.7%    |
| Gujranwala                     | 2         | 0.7%    |
| Abbottabad                     | 2         | 0.7%    |
| Wah                            | 1         | 0.35%   |
| Vehari                         | 1         | 0.35%   |
| Topi                           | 1         | 0.35%   |
| Taunsa                         | 1         | 0.35%   |
| Swabi                          | 1         | 0.35%   |
| Sukkur                         | 1         | 0.35%   |
| Sialkot                        | 1         | 0.35%   |
| Rahim Yar Khan                 | 1         | 0.35%   |
| Quetta                         | 1         | 0.35%   |
| Pindi Gheb                     | 1         | 0.35%   |
| Okara                          | 1         | 0.35%   |
| Muridke                        | 1         | 0.35%   |
| Mardan                         | 1         | 0.35%   |
| Layyah                         | 1         | 0.35%   |
| Layari                         | 1         | 0.35%   |
| Kohat                          | 1         | 0.35%   |
| Khanewal                       | 1         | 0.35%   |
| Hyderabad                      | 1         | 0.35%   |
| Hassan Abdal                   | 1         | 0.35%   |
| Ghotki                         | 1         | 0.35%   |
| Dina                           | 1         | 0.35%   |
| Dera Ismail Khan               | 1         | 0.35%   |
| Daultala                       | 1         | 0.35%   |
| Daska Kalan                    | 1         | 0.35%   |
| Dadu                           | 1         | 0.35%   |
| Chak Five Hundred Seventy-five | 1         | 0.35%   |
| Barkhan                        | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 58     | 13.54%  |
| Seagate             | 44        | 56     | 12.68%  |
| Samsung Electronics | 43        | 50     | 12.39%  |
| Toshiba             | 36        | 37     | 10.37%  |
| SanDisk             | 15        | 16     | 4.32%   |
| Kingston            | 15        | 17     | 4.32%   |
| Hitachi             | 15        | 18     | 4.32%   |
| Unknown             | 12        | 15     | 3.46%   |
| SK hynix            | 12        | 17     | 3.46%   |
| Micron Technology   | 12        | 15     | 3.46%   |
| Intel               | 12        | 14     | 3.46%   |
| Transcend           | 9         | 9      | 2.59%   |
| HGST                | 7         | 9      | 2.02%   |
| Silicon Motion      | 6         | 6      | 1.73%   |
| KIOXIA              | 6         | 6      | 1.73%   |
| A-DATA Technology   | 6         | 6      | 1.73%   |
| Apple               | 5         | 6      | 1.44%   |
| LITEON              | 4         | 4      | 1.15%   |
| Lexar               | 4         | 5      | 1.15%   |
| HS-SSD-E100         | 4         | 4      | 1.15%   |
| China               | 4         | 6      | 1.15%   |
| SPCC                | 3         | 3      | 0.86%   |
| Crucial             | 3         | 4      | 0.86%   |
| Team                | 2         | 2      | 0.58%   |
| Fujitsu             | 2         | 2      | 0.58%   |
| Vaseky              | 1         | 1      | 0.29%   |
| Supersonic          | 1         | 1      | 0.29%   |
| SSSTC               | 1         | 1      | 0.29%   |
| PNY                 | 1         | 2      | 0.29%   |
| Phison Electronics  | 1         | 1      | 0.29%   |
| Phison              | 1         | 2      | 0.29%   |
| PHD 3.0             | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| Lenovo              | 1         | 1      | 0.29%   |
| Kingsand            | 1         | 1      | 0.29%   |
| KESU                | 1         | 1      | 0.29%   |
| Integral            | 1         | 2      | 0.29%   |
| HS-SSD-E100N        | 1         | 1      | 0.29%   |
| Hewlett-Packard     | 1         | 2      | 0.29%   |
| Gritronix           | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 10        | 2.8%    |
| Toshiba MQ04ABF100 1TB                                | 7         | 1.96%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 6         | 1.68%   |
| Toshiba MQ01ABF050 500GB                              | 6         | 1.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 1.4%    |
| Samsung MZALQ512HALU-000L1 512GB                      | 5         | 1.4%    |
| Seagate ST500LT012-1DG142 500GB                       | 4         | 1.12%   |
| WDC WD5000LPVX-75V0TT0 500GB                          | 3         | 0.84%   |
| WDC WD10SPZX-75Z10T3 1TB                              | 3         | 0.84%   |
| WDC PC SN530 NVMe 256GB                               | 3         | 0.84%   |
| Unknown MMC Card  32GB                                | 3         | 0.84%   |
| Toshiba MQ01ACF050 500GB                              | 3         | 0.84%   |
| Silicon Motion NVMe SSD Drive 512GB                   | 3         | 0.84%   |
| Seagate ST9250311CS 250GB                             | 3         | 0.84%   |
| Seagate ST500LM000-1EJ162 500GB                       | 3         | 0.84%   |
| LITEON CS1-SP32 32GB SSD                              | 3         | 0.84%   |
| Hitachi HTS545032B9A300 320GB                         | 3         | 0.84%   |
| Hitachi HTS543225A7A384 250GB                         | 3         | 0.84%   |
| WDC WD3200LPVX-75V0TT0 320GB                          | 2         | 0.56%   |
| WDC WD3200BEKX-75B7WT0 320GB                          | 2         | 0.56%   |
| WDC WD10SPZX-24Z10 1TB                                | 2         | 0.56%   |
| WDC WD10JPVX-60JC3T1 1TB                              | 2         | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 2         | 0.56%   |
| WDC WD Elements 320GB                                 | 2         | 0.56%   |
| Transcend TS512GMTE110S 512GB                         | 2         | 0.56%   |
| Transcend TS256GMTS830S 256GB SSD                     | 2         | 0.56%   |
| Toshiba MQ01ACF032 320GB                              | 2         | 0.56%   |
| Toshiba MQ01ABD100 1TB                                | 2         | 0.56%   |
| Toshiba MQ01ABD075 752GB                              | 2         | 0.56%   |
| Toshiba MQ01ABD050 500GB                              | 2         | 0.56%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                | 2         | 0.56%   |
| SK hynix PC611 NVMe 512GB                             | 2         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 2         | 0.56%   |
| Seagate ST9320423AS 320GB                             | 2         | 0.56%   |
| Seagate ST9250315AS 250GB                             | 2         | 0.56%   |
| SanDisk X110 MSATA 128GB SSD                          | 2         | 0.56%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                   | 2         | 0.56%   |
| SanDisk SD7SN6S-256G-1006 256GB SSD                   | 2         | 0.56%   |
| Samsung SSD 870 EVO 500GB                             | 2         | 0.56%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB                  | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 56     | 31.65%  |
| WDC                 | 37        | 43     | 26.62%  |
| Toshiba             | 30        | 31     | 21.58%  |
| Hitachi             | 15        | 18     | 10.79%  |
| HGST                | 7         | 9      | 5.04%   |
| Samsung Electronics | 2         | 2      | 1.44%   |
| Fujitsu             | 2         | 2      | 1.44%   |
| Unknown             | 1         | 1      | 0.72%   |
| KESU                | 1         | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 29     | 23.48%  |
| Kingston            | 11        | 13     | 9.57%   |
| SanDisk             | 10        | 10     | 8.7%    |
| Micron Technology   | 7         | 8      | 6.09%   |
| SK hynix            | 6         | 11     | 5.22%   |
| Intel               | 5         | 6      | 4.35%   |
| WDC                 | 4         | 6      | 3.48%   |
| Transcend           | 4         | 4      | 3.48%   |
| LITEON              | 4         | 4      | 3.48%   |
| Lexar               | 4         | 5      | 3.48%   |
| China               | 4         | 6      | 3.48%   |
| A-DATA Technology   | 4         | 4      | 3.48%   |
| Toshiba             | 3         | 3      | 2.61%   |
| SPCC                | 3         | 3      | 2.61%   |
| Crucial             | 3         | 4      | 2.61%   |
| Team                | 2         | 2      | 1.74%   |
| HS-SSD-E100         | 2         | 2      | 1.74%   |
| Apple               | 2         | 2      | 1.74%   |
| Vaseky              | 1         | 1      | 0.87%   |
| Supersonic          | 1         | 1      | 0.87%   |
| PNY                 | 1         | 2      | 0.87%   |
| PHD 3.0             | 1         | 1      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| Hewlett-Packard     | 1         | 2      | 0.87%   |
| Gritronix           | 1         | 1      | 0.87%   |
| Emtec               | 1         | 1      | 0.87%   |
| Biostar             | 1         | 1      | 0.87%   |
| Apacer              | 1         | 1      | 0.87%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 135       | 163    | 39.94%  |
| SSD     | 110       | 134    | 32.54%  |
| NVMe    | 76        | 90     | 22.49%  |
| MMC     | 9         | 12     | 2.66%   |
| Unknown | 8         | 9      | 2.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 215       | 300    | 70.26%  |
| NVMe | 76        | 90     | 24.84%  |
| MMC  | 9         | 12     | 2.94%   |
| SAS  | 6         | 6      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 157       | 209    | 67.97%  |
| 0.51-1.0   | 72        | 86     | 31.17%  |
| 1.01-2.0   | 2         | 2      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 115       | 39.38%  |
| 251-500        | 74        | 25.34%  |
| 51-100         | 42        | 14.38%  |
| 501-1000       | 27        | 9.25%   |
| 1-20           | 13        | 4.45%   |
| 21-50          | 11        | 3.77%   |
| 1001-2000      | 9         | 3.08%   |
| More than 3000 | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 108       | 35.64%  |
| 21-50     | 90        | 29.7%   |
| 51-100    | 44        | 14.52%  |
| 101-250   | 40        | 13.2%   |
| 251-500   | 14        | 4.62%   |
| 501-1000  | 6         | 1.98%   |
| 1001-2000 | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB                | 2         | 2      | 8.33%   |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 4.17%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 4.17%   |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 4.17%   |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 4.17%   |
| Supersonic SSD 256 256GB                      | 1         | 1      | 4.17%   |
| SK hynix PC401 NVMe 256GB                     | 1         | 1      | 4.17%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 4.17%   |
| Seagate ST980411ASG 80GB                      | 1         | 2      | 4.17%   |
| Seagate ST9750420AS 752GB                     | 1         | 1      | 4.17%   |
| Seagate ST500LM021-1KJ152 500GB               | 1         | 1      | 4.17%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 4.17%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 4.17%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 4.17%   |
| Intel SSDSC2BF180A4H 180GB                    | 1         | 1      | 4.17%   |
| HS-SSD-E100 SSD 1024G                         | 1         | 1      | 4.17%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 4.17%   |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 4.17%   |
| Gritronix M.2 2280 256GB SSD                  | 1         | 1      | 4.17%   |
| China SSD 240GB                               | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 8      | 29.17%  |
| WDC               | 4         | 5      | 16.67%  |
| Toshiba           | 2         | 2      | 8.33%   |
| SK hynix          | 2         | 2      | 8.33%   |
| Intel             | 2         | 2      | 8.33%   |
| Hitachi           | 2         | 2      | 8.33%   |
| Supersonic        | 1         | 1      | 4.17%   |
| Micron Technology | 1         | 1      | 4.17%   |
| HS-SSD-E100       | 1         | 1      | 4.17%   |
| Gritronix         | 1         | 1      | 4.17%   |
| China             | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 46.67%  |
| WDC     | 4         | 5      | 26.67%  |
| Toshiba | 2         | 2      | 13.33%  |
| Hitachi | 2         | 2      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 17     | 62.5%   |
| SSD  | 8         | 8      | 33.33%  |
| NVMe | 1         | 1      | 4.17%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 177       | 264    | 60.62%  |
| Works    | 91        | 118    | 31.16%  |
| Malfunc  | 24        | 26     | 8.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 239       | 73.31%  |
| Samsung Electronics            | 17        | 5.21%   |
| AMD                            | 13        | 3.99%   |
| SanDisk                        | 11        | 3.37%   |
| KIOXIA                         | 8         | 2.45%   |
| Silicon Motion                 | 7         | 2.15%   |
| SK hynix                       | 6         | 1.84%   |
| Micron Technology              | 5         | 1.53%   |
| Transcend                      | 4         | 1.23%   |
| Kingston Technology Company    | 4         | 1.23%   |
| Apple                          | 3         | 0.92%   |
| Toshiba America Info Systems   | 2         | 0.61%   |
| Phison Electronics             | 2         | 0.61%   |
| Solid State Storage Technology | 1         | 0.31%   |
| Realtek Semiconductor          | 1         | 0.31%   |
| Marvell Technology Group       | 1         | 0.31%   |
| Lenovo                         | 1         | 0.31%   |
| ADATA Technology               | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 47        | 13.39%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 28        | 7.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 5.98%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 4.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 4.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 4.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 3.99%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 3.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 2.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 2.56%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 2.28%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7         | 1.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.99%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 6         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.42%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 4         | 1.14%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 4         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.85%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.85%   |
| Intel SSD 660P Series                                                          | 3         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.85%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 3         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.85%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 0.57%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.57%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 2         | 0.57%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2         | 0.57%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.57%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 0.57%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.57%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 206       | 60.59%  |
| NVMe | 76        | 22.35%  |
| RAID | 44        | 12.94%  |
| IDE  | 14        | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 262       | 93.91%  |
| AMD    | 17        | 6.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 13        | 4.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 11        | 3.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 3.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 2.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 2.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 2.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 2.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 2.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 1.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 1.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 5         | 1.79%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 4         | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 1.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 1.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 4         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 1.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.43%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 4         | 1.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 1.43%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 3         | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.08%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 3         | 1.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.08%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.08%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 3         | 1.08%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 3         | 1.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 1.08%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 3         | 1.08%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.72%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.72%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 0.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.72%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 113       | 40.5%   |
| Intel Core i7        | 76        | 27.24%  |
| Other                | 32        | 11.47%  |
| Intel Core i3        | 11        | 3.94%   |
| Intel Core 2 Duo     | 8         | 2.87%   |
| AMD Ryzen 7          | 7         | 2.51%   |
| Intel Celeron        | 6         | 2.15%   |
| Intel Core m3        | 4         | 1.43%   |
| AMD Ryzen 5          | 4         | 1.43%   |
| Intel Core M         | 3         | 1.08%   |
| Intel Pentium        | 2         | 0.72%   |
| Intel Atom           | 2         | 0.72%   |
| AMD A6               | 2         | 0.72%   |
| Intel Xeon           | 1         | 0.36%   |
| Intel Pentium Dual   | 1         | 0.36%   |
| Intel Genuine        | 1         | 0.36%   |
| Intel Core 2 Extreme | 1         | 0.36%   |
| Intel Core 2         | 1         | 0.36%   |
| AMD FX               | 1         | 0.36%   |
| AMD E                | 1         | 0.36%   |
| AMD A4               | 1         | 0.36%   |
| AMD A12              | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 152       | 54.48%  |
| 4      | 104       | 37.28%  |
| 6      | 12        | 4.3%    |
| 8      | 7         | 2.51%   |
| 10     | 2         | 0.72%   |
| 14     | 1         | 0.36%   |
| 1      | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 279       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 249       | 88.93%  |
| 1      | 31        | 11.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 277       | 98.93%  |
| Unknown        | 2         | 0.71%   |
| 32-bit         | 1         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 32.07%  |
| 0x806c1    | 18        | 6.21%   |
| 0x406e3    | 17        | 5.86%   |
| 0x206a7    | 16        | 5.52%   |
| 0x806ec    | 14        | 4.83%   |
| 0x806e9    | 14        | 4.83%   |
| 0x306a9    | 14        | 4.83%   |
| 0x40651    | 13        | 4.48%   |
| 0x306d4    | 13        | 4.48%   |
| 0x806ea    | 12        | 4.14%   |
| 0x20655    | 9         | 3.1%    |
| 0x706e5    | 6         | 2.07%   |
| 0x306c3    | 6         | 2.07%   |
| 0x906ea    | 4         | 1.38%   |
| 0x1067a    | 4         | 1.38%   |
| 0xa0652    | 3         | 1.03%   |
| 0x30678    | 3         | 1.03%   |
| 0x906e9    | 2         | 0.69%   |
| 0x506e3    | 2         | 0.69%   |
| 0x10676    | 2         | 0.69%   |
| 0x0a50000c | 2         | 0.69%   |
| 0x08608103 | 2         | 0.69%   |
| 0x08600106 | 2         | 0.69%   |
| 0xa0660    | 1         | 0.34%   |
| 0x906a4    | 1         | 0.34%   |
| 0x906a3    | 1         | 0.34%   |
| 0x806eb    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6fd      | 1         | 0.34%   |
| 0x6f6      | 1         | 0.34%   |
| 0x406c4    | 1         | 0.34%   |
| 0x40661    | 1         | 0.34%   |
| 0x20652    | 1         | 0.34%   |
| 0x106e5    | 1         | 0.34%   |
| 0x0a50000d | 1         | 0.34%   |
| 0x08600104 | 1         | 0.34%   |
| 0x08108109 | 1         | 0.34%   |
| 0x0700010f | 1         | 0.34%   |
| 0x0600611a | 1         | 0.34%   |
| 0x0600111f | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 23.93%  |
| Haswell          | 29        | 10.36%  |
| TigerLake        | 28        | 10%     |
| IvyBridge        | 24        | 8.57%   |
| Skylake          | 22        | 7.86%   |
| SandyBridge      | 21        | 7.5%    |
| Broadwell        | 20        | 7.14%   |
| Westmere         | 15        | 5.36%   |
| Penryn           | 8         | 2.86%   |
| IceLake          | 8         | 2.86%   |
| Silvermont       | 7         | 2.5%    |
| Zen 3            | 4         | 1.43%   |
| CometLake        | 4         | 1.43%   |
| Unknown          | 4         | 1.43%   |
| Zen 2            | 3         | 1.07%   |
| Core             | 3         | 1.07%   |
| Zen+             | 2         | 0.71%   |
| Alderlake Hybrid | 2         | 0.71%   |
| Steamroller      | 1         | 0.36%   |
| Piledriver       | 1         | 0.36%   |
| P6               | 1         | 0.36%   |
| Nehalem          | 1         | 0.36%   |
| K10 Llano        | 1         | 0.36%   |
| Jaguar           | 1         | 0.36%   |
| Goldmont plus    | 1         | 0.36%   |
| Excavator        | 1         | 0.36%   |
| Bobcat           | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 244       | 69.91%  |
| Nvidia | 58        | 16.62%  |
| AMD    | 47        | 13.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 27        | 7.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 20        | 5.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 19        | 5.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 19        | 5.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 19        | 5.38%   |
| Intel UHD Graphics 620                                                                | 17        | 4.82%   |
| Intel HD Graphics 5500                                                                | 17        | 4.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 17        | 4.82%   |
| Intel HD Graphics 620                                                                 | 14        | 3.97%   |
| Intel Core Processor Integrated Graphics Controller                                   | 10        | 2.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.98%   |
| Nvidia GP108M [GeForce MX230]                                                         | 6         | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 1.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 6         | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 1.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 6         | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 1.42%   |
| Intel HD Graphics 615                                                                 | 4         | 1.13%   |
| Nvidia TU117M [GeForce MX450]                                                         | 3         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 0.85%   |
| Intel HD Graphics 5300                                                                | 3         | 0.85%   |
| Intel HD Graphics 530                                                                 | 3         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 0.85%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 3         | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.57%   |
| Nvidia GT218M [NVS 3100M]                                                             | 2         | 0.57%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 0.57%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.57%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.57%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.57%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 0.57%   |
| Nvidia GF119M [NVS 4200M]                                                             | 2         | 0.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.57%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 179       | 63.93%  |
| Intel + Nvidia | 42        | 15%     |
| Intel + AMD    | 22        | 7.86%   |
| 1 x AMD        | 21        | 7.5%    |
| 1 x Nvidia     | 11        | 3.93%   |
| AMD + Nvidia   | 5         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 251       | 89.32%  |
| Proprietary | 28        | 9.96%   |
| Unknown     | 2         | 0.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 205       | 72.7%   |
| 1.01-2.0   | 39        | 13.83%  |
| 0.01-0.5   | 14        | 4.96%   |
| 3.01-4.0   | 11        | 3.9%    |
| 0.51-1.0   | 11        | 3.9%    |
| 7.01-8.0   | 1         | 0.35%   |
| 5.01-6.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 65        | 22.11%  |
| AU Optronics            | 53        | 18.03%  |
| Chimei Innolux          | 50        | 17.01%  |
| BOE                     | 41        | 13.95%  |
| Samsung Electronics     | 19        | 6.46%   |
| Dell                    | 10        | 3.4%    |
| Chi Mei Optoelectronics | 9         | 3.06%   |
| Apple                   | 6         | 2.04%   |
| Sharp                   | 5         | 1.7%    |
| InfoVision              | 5         | 1.7%    |
| Lenovo                  | 4         | 1.36%   |
| Hewlett-Packard         | 4         | 1.36%   |
| KDC                     | 3         | 1.02%   |
| Sony                    | 2         | 0.68%   |
| PANDA                   | 2         | 0.68%   |
| MStar                   | 2         | 0.68%   |
| LGD                     | 2         | 0.68%   |
| LG Philips              | 2         | 0.68%   |
| Goldstar                | 2         | 0.68%   |
| BenQ                    | 2         | 0.68%   |
| ViewSonic               | 1         | 0.34%   |
| SDC                     | 1         | 0.34%   |
| LPL                     | 1         | 0.34%   |
| CSO                     | 1         | 0.34%   |
| AOC                     | 1         | 0.34%   |
| Acer                    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 10        | 3.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 5         | 1.69%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 4         | 1.36%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch          | 4         | 1.36%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 4         | 1.36%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 3         | 1.02%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch               | 3         | 1.02%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 1.02%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                      | 3         | 1.02%   |
| InfoVision M116NWR1 R0 IVO0489 1366x768 256x144mm 11.6-inch               | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch             | 3         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch      | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch     | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch      | 2         | 0.68%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                            | 2         | 0.68%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 2         | 0.68%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 2         | 0.68%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 2         | 0.68%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch               | 2         | 0.68%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch                 | 2         | 0.68%   |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                         | 2         | 0.68%   |
| Dell P2212H DELA07F 1920x1080 477x268mm 21.5-inch                         | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch           | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch           | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 2         | 0.68%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                      | 2         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 129       | 45.91%  |
| 1366x768 (WXGA)    | 107       | 38.08%  |
| 1600x900 (HD+)     | 12        | 4.27%   |
| 1280x800 (WXGA)    | 7         | 2.49%   |
| 3840x2160 (4K)     | 6         | 2.14%   |
| 2880x1800          | 4         | 1.42%   |
| 1680x1050 (WSXGA+) | 4         | 1.42%   |
| 1440x900 (WXGA+)   | 4         | 1.42%   |
| 2560x1600          | 2         | 0.71%   |
| 3440x1440          | 1         | 0.36%   |
| 1920x1200 (WUXGA)  | 1         | 0.36%   |
| 1600x1200          | 1         | 0.36%   |
| 1360x768           | 1         | 0.36%   |
| 1280x1024 (SXGA)   | 1         | 0.36%   |
| 1024x768 (XGA)     | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 135       | 46.08%  |
| 14      | 48        | 16.38%  |
| 13      | 45        | 15.36%  |
| 17      | 14        | 4.78%   |
| 12      | 9         | 3.07%   |
| 24      | 7         | 2.39%   |
| 11      | 7         | 2.39%   |
| 21      | 6         | 2.05%   |
| Unknown | 5         | 1.71%   |
| 23      | 4         | 1.37%   |
| 52      | 2         | 0.68%   |
| 22      | 2         | 0.68%   |
| 20      | 2         | 0.68%   |
| 18      | 2         | 0.68%   |
| 16      | 2         | 0.68%   |
| 72      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 31      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 205       | 70.45%  |
| 201-300     | 38        | 13.06%  |
| 351-400     | 16        | 5.5%    |
| 401-500     | 12        | 4.12%   |
| 501-600     | 10        | 3.44%   |
| Unknown     | 5         | 1.72%   |
| 1001-1500   | 2         | 0.69%   |
| 801-900     | 1         | 0.34%   |
| 601-700     | 1         | 0.34%   |
| 1501-2000   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 243       | 89.01%  |
| 16/10   | 21        | 7.69%   |
| Unknown | 5         | 1.83%   |
| 4/3     | 2         | 0.73%   |
| 5/4     | 1         | 0.37%   |
| 3/2     | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 135       | 46.23%  |
| 81-90          | 72        | 24.66%  |
| 71-80          | 19        | 6.51%   |
| 201-250        | 16        | 5.48%   |
| 121-130        | 11        | 3.77%   |
| 61-70          | 9         | 3.08%   |
| 51-60          | 7         | 2.4%    |
| Unknown        | 5         | 1.71%   |
| 151-200        | 4         | 1.37%   |
| More than 1000 | 3         | 1.03%   |
| 141-150        | 3         | 1.03%   |
| 91-100         | 3         | 1.03%   |
| 131-140        | 2         | 0.68%   |
| 351-500        | 1         | 0.34%   |
| 111-120        | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 46.9%   |
| 101-120       | 101       | 34.83%  |
| 51-100        | 26        | 8.97%   |
| 161-240       | 15        | 5.17%   |
| Unknown       | 5         | 1.72%   |
| More than 240 | 4         | 1.38%   |
| 1-50          | 3         | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 254       | 90.39%  |
| 2     | 24        | 8.54%   |
| 0     | 2         | 0.71%   |
| 3     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 192       | 42.95%  |
| Realtek Semiconductor             | 141       | 31.54%  |
| Qualcomm Atheros                  | 33        | 7.38%   |
| Broadcom                          | 25        | 5.59%   |
| Broadcom Limited                  | 11        | 2.46%   |
| MediaTek                          | 6         | 1.34%   |
| Hewlett-Packard                   | 6         | 1.34%   |
| Ralink                            | 4         | 0.89%   |
| ASIX Electronics                  | 4         | 0.89%   |
| Xiaomi                            | 3         | 0.67%   |
| TP-Link                           | 3         | 0.67%   |
| Marvell Technology Group          | 3         | 0.67%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.45%   |
| Spreadtrum Communications         | 2         | 0.45%   |
| Sierra Wireless                   | 2         | 0.45%   |
| Dell                              | 2         | 0.45%   |
| Samsung Electronics               | 1         | 0.22%   |
| Ralink Technology                 | 1         | 0.22%   |
| Qualcomm                          | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| JMicron Technology                | 1         | 0.22%   |
| Huawei Technologies               | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 98        | 17.31%  |
| Intel Wi-Fi 6 AX201                                               | 23        | 4.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 3.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 3.53%   |
| Intel Wireless 7265                                               | 15        | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 2.3%    |
| Intel Wireless 8265 / 8275                                        | 13        | 2.3%    |
| Intel Wireless 7260                                               | 13        | 2.3%    |
| Intel Wireless 3165                                               | 13        | 2.3%    |
| Intel Wireless 8260                                               | 12        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.77%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 1.77%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.24%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.06%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.88%   |
| Intel Wireless 3160                                               | 5         | 0.88%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                   | 5         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.88%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.88%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.53%   |
| Intel Wireless-AC 9260                                            | 3         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 180       | 61.22%  |
| Realtek Semiconductor | 34        | 11.56%  |
| Qualcomm Atheros      | 31        | 10.54%  |
| Broadcom              | 22        | 7.48%   |
| Broadcom Limited      | 8         | 2.72%   |
| Ralink                | 4         | 1.36%   |
| TP-Link               | 3         | 1.02%   |
| MediaTek              | 3         | 1.02%   |
| Hewlett-Packard       | 3         | 1.02%   |
| Sierra Wireless       | 2         | 0.68%   |
| Dell                  | 2         | 0.68%   |
| Ralink Technology     | 1         | 0.34%   |
| D-Link                | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 23        | 7.77%   |
| Intel Wireless 7265                                            | 15        | 5.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 5.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 4.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 4.39%   |
| Intel Wireless 8265 / 8275                                     | 13        | 4.39%   |
| Intel Wireless 7260                                            | 13        | 4.39%   |
| Intel Wireless 3165                                            | 13        | 4.39%   |
| Intel Wireless 8260                                            | 12        | 4.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.03%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 2.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.69%   |
| Intel Wireless 3160                                            | 5         | 1.69%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 1.69%   |
| Intel Ultimate N WiFi Link 5300                                | 5         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.69%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.01%   |
| Intel Wireless-AC 9260                                         | 3         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.01%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.01%   |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 129       | 48.86%  |
| Intel                      | 101       | 38.26%  |
| Qualcomm Atheros           | 4         | 1.52%   |
| Broadcom                   | 4         | 1.52%   |
| ASIX Electronics           | 4         | 1.52%   |
| Xiaomi                     | 3         | 1.14%   |
| MediaTek                   | 3         | 1.14%   |
| Marvell Technology Group   | 3         | 1.14%   |
| Broadcom Limited           | 3         | 1.14%   |
| ZTE WCDMA Technologies MSM | 2         | 0.76%   |
| Spreadtrum Communications  | 2         | 0.76%   |
| Hewlett-Packard            | 2         | 0.76%   |
| Qualcomm                   | 1         | 0.38%   |
| OPPO Electronics           | 1         | 0.38%   |
| JMicron Technology         | 1         | 0.38%   |
| Huawei Technologies        | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 98        | 36.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 8.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20        | 7.49%   |
| Intel Ethernet Connection (3) I218-LM                                          | 14        | 5.24%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 3.75%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 3.37%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 3%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.62%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 2.62%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 2.25%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.87%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.87%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.12%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                            | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.75%   |
| Spreadtrum Unisoc Phone                                                        | 2         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.75%   |
| MediaTek M40Air_EEA                                                            | 2         | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.75%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.75%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.37%   |
| Qualcomm FP3                                                                   | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.37%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.37%   |
| OPPO SM8350-IDP _SN:27BAACC8                                                   | 1         | 0.37%   |
| MediaTek moto e22                                                              | 1         | 0.37%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.37%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.37%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.37%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 277       | 52.07%  |
| Ethernet | 252       | 47.37%  |
| Modem    | 3         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 247       | 86.67%  |
| Ethernet | 38        | 13.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 234       | 83.57%  |
| 1     | 39        | 13.93%  |
| 0     | 4         | 1.43%   |
| 3     | 2         | 0.71%   |
| 4     | 1         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 258       | 91.49%  |
| Yes  | 24        | 8.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 125       | 58.69%  |
| Realtek Semiconductor           | 24        | 11.27%  |
| Qualcomm Atheros Communications | 22        | 10.33%  |
| Broadcom                        | 15        | 7.04%   |
| Dell                            | 6         | 2.82%   |
| Foxconn / Hon Hai               | 5         | 2.35%   |
| Ralink                          | 3         | 1.41%   |
| Cambridge Silicon Radio         | 3         | 1.41%   |
| Apple                           | 3         | 1.41%   |
| IMC Networks                    | 2         | 0.94%   |
| Hewlett-Packard                 | 2         | 0.94%   |
| Ralink Technology               | 1         | 0.47%   |
| Lite-On Technology              | 1         | 0.47%   |
| Askey Computer                  | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 63        | 29.58%  |
| Intel Bluetooth Device                                                              | 28        | 13.15%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 19        | 8.92%   |
| Realtek Bluetooth Radio                                                             | 16        | 7.51%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 6.1%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.82%   |
| Intel AX200 Bluetooth                                                               | 5         | 2.35%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 2.35%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.41%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.94%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.94%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.94%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 2         | 0.94%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.47%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.47%   |
| Ralink CSR BS8510                                                                   | 1         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.47%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.47%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.47%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.47%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.47%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.47%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 260       | 81%     |
| AMD                    | 26        | 8.1%    |
| Nvidia                 | 22        | 6.85%   |
| Logitech               | 4         | 1.25%   |
| Generalplus Technology | 3         | 0.93%   |
| Apple                  | 2         | 0.62%   |
| Realtek Semiconductor  | 1         | 0.31%   |
| OPPO Electronics       | 1         | 0.31%   |
| JMTek                  | 1         | 0.31%   |
| C-Media Electronics    | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 55        | 14.44%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 7.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 6.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 5.25%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 5.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 4.99%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 4.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 4.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 4.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.31%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 1.05%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.79%   |
| Logitech Headset H340                                                      | 3         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.52%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.52%   |
| Nvidia Audio device                                                        | 2         | 0.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.52%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.52%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.52%   |
| Apple Audio Device                                                         | 2         | 0.52%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 0.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 29.28%  |
| SK hynix            | 48        | 26.52%  |
| Micron Technology   | 25        | 13.81%  |
| A-DATA Technology   | 15        | 8.29%   |
| Transcend           | 6         | 3.31%   |
| Crucial             | 6         | 3.31%   |
| Lexar               | 5         | 2.76%   |
| Team                | 4         | 2.21%   |
| Kingston            | 4         | 2.21%   |
| Unknown             | 2         | 1.1%    |
| Spectek             | 2         | 1.1%    |
| Nanya Technology    | 2         | 1.1%    |
| Elpida              | 2         | 1.1%    |
| Unknown (768A)      | 1         | 0.55%   |
| Unknown (0x0BF7)    | 1         | 0.55%   |
| TwinMOS             | 1         | 0.55%   |
| Ramaxel Technology  | 1         | 0.55%   |
| Patriot             | 1         | 0.55%   |
| Hikvision           | 1         | 0.55%   |
| Axiom               | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 3.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 2.6%    |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s               | 5         | 2.6%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 4         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 1.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 3         | 1.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 1.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 1.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 3         | 1.56%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                   | 3         | 1.56%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 2         | 1.04%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.04%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 1.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 2         | 1.04%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s               | 2         | 1.04%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 2         | 1.04%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 2         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.04%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 2         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 1.04%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s     | 2         | 1.04%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 2         | 1.04%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1334MT/s       | 2         | 1.04%   |
| Lexar RAM LD4AS016G-H2666G 16GB SODIMM DDR4 2667MT/s         | 2         | 1.04%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                  | 1         | 0.52%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s            | 1         | 0.52%   |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.52%   |
| Unknown (0x0BF7) RAM DDR-C300 8GB SODIMM DDR4 3200MT/s       | 1         | 0.52%   |
| TwinMOS RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 3200MT/s     | 1         | 0.52%   |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s                | 1         | 0.52%   |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s             | 1         | 0.52%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2400MT/s             | 1         | 0.52%   |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s            | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 84        | 60%     |
| DDR3   | 46        | 32.86%  |
| LPDDR3 | 4         | 2.86%   |
| LPDDR4 | 3         | 2.14%   |
| DDR5   | 1         | 0.71%   |
| DDR2   | 1         | 0.71%   |
| DDR    | 1         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 90.21%  |
| Row Of Chips | 13        | 9.09%   |
| DIMM         | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 72        | 45.57%  |
| 4096  | 42        | 26.58%  |
| 16384 | 27        | 17.09%  |
| 2048  | 10        | 6.33%   |
| 32768 | 7         | 4.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 38        | 24.84%  |
| 2667  | 37        | 24.18%  |
| 3200  | 34        | 22.22%  |
| 2133  | 13        | 8.5%    |
| 2400  | 11        | 7.19%   |
| 1334  | 9         | 5.88%   |
| 1333  | 3         | 1.96%   |
| 4267  | 2         | 1.31%   |
| 8400  | 1         | 0.65%   |
| 4800  | 1         | 0.65%   |
| 2267  | 1         | 0.65%   |
| 1067  | 1         | 0.65%   |
| 1066  | 1         | 0.65%   |
| 975   | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Plustek | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 26.48%  |
| Microdia                               | 32        | 12.65%  |
| Sunplus Innovation Technology          | 26        | 10.28%  |
| Cheng Uei Precision Industry (Foxlink) | 21        | 8.3%    |
| Realtek Semiconductor                  | 19        | 7.51%   |
| Lite-On Technology                     | 15        | 5.93%   |
| Quanta                                 | 13        | 5.14%   |
| IMC Networks                           | 9         | 3.56%   |
| Syntek                                 | 8         | 3.16%   |
| Suyin                                  | 7         | 2.77%   |
| Luxvisions Innotech Limited            | 6         | 2.37%   |
| Bison Electronics                      | 6         | 2.37%   |
| Ricoh                                  | 5         | 1.98%   |
| Silicon Motion                         | 4         | 1.58%   |
| Apple                                  | 3         | 1.19%   |
| Acer                                   | 3         | 1.19%   |
| Primax Electronics                     | 2         | 0.79%   |
| Logitech                               | 2         | 0.79%   |
| SunplusIT                              | 1         | 0.4%    |
| Pixart Imaging                         | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| DigiTech                               | 1         | 0.4%    |
| ALi                                    | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 17        | 6.67%   |
| Microdia Integrated_Webcam_HD                                              | 16        | 6.27%   |
| Chicony Integrated Camera                                                  | 15        | 5.88%   |
| Chicony HP HD Camera                                                       | 11        | 4.31%   |
| Realtek Integrated_Webcam_HD                                               | 7         | 2.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 2.75%   |
| Microdia Integrated Webcam                                                 | 6         | 2.35%   |
| Lite-On HP HD Webcam                                                       | 6         | 2.35%   |
| Lite-On HP HD Camera                                                       | 6         | 2.35%   |
| Syntek Integrated Camera                                                   | 5         | 1.96%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 1.96%   |
| Quanta HP HD Camera                                                        | 5         | 1.96%   |
| IMC Networks Integrated Camera                                             | 5         | 1.96%   |
| Chicony USB 2.0Camera                                                      | 4         | 1.57%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.57%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.57%   |
| Chicony HP TrueVision HD                                                   | 4         | 1.57%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.18%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.18%   |
| Realtek USB camera                                                         | 3         | 1.18%   |
| Realtek Integrated Webcam                                                  | 3         | 1.18%   |
| Lite-On Integrated Camera                                                  | 3         | 1.18%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                                            | 3         | 1.18%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.18%   |
| Chicony EasyCamera                                                         | 3         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 3         | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 1.18%   |
| Suyin HP Truevision HD                                                     | 2         | 0.78%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 0.78%   |
| Sunplus HP Universal Camera                                                | 2         | 0.78%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.78%   |
| Realtek Integrated Webcam_HD                                               | 2         | 0.78%   |
| Realtek HP Truevision HD                                                   | 2         | 0.78%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.78%   |
| Primax HP HD Webcam [Fixed]                                                | 2         | 0.78%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 0.78%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 0.78%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 51        | 62.2%   |
| Synaptics                  | 12        | 14.63%  |
| Shenzhen Goodix Technology | 10        | 12.2%   |
| AuthenTec                  | 4         | 4.88%   |
| Upek                       | 3         | 3.66%   |
| Elan Microelectronics      | 2         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 26.83%  |
| Validity Sensors VFS491                                                    | 10        | 12.2%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 12.2%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 8.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 6.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.66%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.66%   |
| AuthenTec AES2810                                                          | 3         | 3.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.44%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.44%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.22%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.22%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.22%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.22%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.22%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.22%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 27        | 84.38%  |
| O2 Micro         | 3         | 9.38%   |
| SCM Microsystems | 1         | 3.13%   |
| Alcor Micro      | 1         | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 142       | 50%     |
| 1     | 122       | 42.96%  |
| 2     | 17        | 5.99%   |
| 8     | 1         | 0.35%   |
| 4     | 1         | 0.35%   |
| 3     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 48.21%  |
| Chipcard                 | 31        | 18.45%  |
| Graphics card            | 19        | 11.31%  |
| Net/wireless             | 9         | 5.36%   |
| Bluetooth                | 6         | 3.57%   |
| Storage                  | 5         | 2.98%   |
| Sound                    | 4         | 2.38%   |
| Communication controller | 4         | 2.38%   |
| Multimedia controller    | 3         | 1.79%   |
| Camera                   | 3         | 1.79%   |
| Network                  | 1         | 0.6%    |
| Net/ethernet             | 1         | 0.6%    |
| Card reader              | 1         | 0.6%    |


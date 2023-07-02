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

Total: 332

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 69        | 28.05%  |
| Ubuntu 22.04       | 28        | 11.38%  |
| Ubuntu 18.04       | 20        | 8.13%   |
| Zorin 16           | 5         | 2.03%   |
| KDE neon 20.04     | 5         | 2.03%   |
| Arch               | 5         | 2.03%   |
| Ubuntu 22.10       | 4         | 1.63%   |
| Pop!_OS 22.04      | 4         | 1.63%   |
| Debian 11          | 4         | 1.63%   |
| Ubuntu 21.10       | 3         | 1.22%   |
| Ubuntu 21.04       | 3         | 1.22%   |
| Ubuntu 19.04       | 3         | 1.22%   |
| Pop!_OS 21.04      | 3         | 1.22%   |
| Pop!_OS 20.10      | 3         | 1.22%   |
| Pop!_OS 20.04      | 3         | 1.22%   |
| OpenMandriva 4.3   | 3         | 1.22%   |
| Linux Mint 20      | 3         | 1.22%   |
| Fedora 37          | 3         | 1.22%   |
| Fedora 33          | 3         | 1.22%   |
| Elementary 6.1     | 3         | 1.22%   |
| Zorin 15           | 2         | 0.81%   |
| Xero Rolling       | 2         | 0.81%   |
| OpenMandriva 4.2   | 2         | 0.81%   |
| OpenMandriva 23.03 | 2         | 0.81%   |
| OpenMandriva 23.01 | 2         | 0.81%   |
| Linux Mint 21.1    | 2         | 0.81%   |
| Linux Mint 20.3    | 2         | 0.81%   |
| Linux Mint 20.2    | 2         | 0.81%   |
| Linux Mint 20.1    | 2         | 0.81%   |
| Kubuntu 22.04      | 2         | 0.81%   |
| Kali 2023.2        | 2         | 0.81%   |
| Kali 2022.3        | 2         | 0.81%   |
| Fedora 36          | 2         | 0.81%   |
| ArcoLinux Rolling  | 2         | 0.81%   |
| Zorin 12           | 1         | 0.41%   |
| Ubuntu Unity 20.04 | 1         | 0.41%   |
| Ubuntu Unity 18.04 | 1         | 0.41%   |
| Ubuntu Unity 16.04 | 1         | 0.41%   |
| Ubuntu 19.10       | 1         | 0.41%   |
| Ubuntu 18.10       | 1         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 133       | 54.96%  |
| Pop!_OS      | 12        | 4.96%   |
| Fedora       | 12        | 4.96%   |
| Linux Mint   | 10        | 4.13%   |
| Zorin        | 8         | 3.31%   |
| OpenMandriva | 8         | 3.31%   |
| Kali         | 7         | 2.89%   |
| Arch         | 6         | 2.48%   |
| KDE neon     | 5         | 2.07%   |
| Manjaro      | 4         | 1.65%   |
| Kubuntu      | 4         | 1.65%   |
| Debian       | 4         | 1.65%   |
| Ubuntu Unity | 3         | 1.24%   |
| Endless      | 3         | 1.24%   |
| Elementary   | 3         | 1.24%   |
| ArcoLinux    | 3         | 1.24%   |
| Xero         | 2         | 0.83%   |
| Parrot       | 2         | 0.83%   |
| Artix        | 2         | 0.83%   |
| ROSA         | 1         | 0.41%   |
| Rocky Linux  | 1         | 0.41%   |
| RHEL         | 1         | 0.41%   |
| Oracle Linux | 1         | 0.41%   |
| Nobara       | 1         | 0.41%   |
| Lubuntu      | 1         | 0.41%   |
| LinuxFX      | 1         | 0.41%   |
| EndeavourOS  | 1         | 0.41%   |
| Deepin       | 1         | 0.41%   |
| Clear Linux  | 1         | 0.41%   |
| AlmaLinux    | 1         | 0.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 9         | 3.42%   |
| 5.15.0-46-generic       | 8         | 3.04%   |
| 5.19.0-42-generic       | 5         | 1.9%    |
| 5.15.0-47-generic       | 5         | 1.9%    |
| 5.11.0-37-generic       | 5         | 1.9%    |
| 5.4.0-48-generic        | 4         | 1.52%   |
| 5.4.0-47-generic        | 4         | 1.52%   |
| 5.4.0-40-generic        | 4         | 1.52%   |
| 5.8.0-7630-generic      | 3         | 1.14%   |
| 5.8.0-41-generic        | 3         | 1.14%   |
| 5.4.0-54-generic        | 3         | 1.14%   |
| 5.4.0-52-generic        | 3         | 1.14%   |
| 5.4.0-26-generic        | 3         | 1.14%   |
| 5.3.0-28-generic        | 3         | 1.14%   |
| 5.19.0-41-generic       | 3         | 1.14%   |
| 5.16.7-desktop-1omv4003 | 3         | 1.14%   |
| 5.15.0-58-generic       | 3         | 1.14%   |
| 5.15.0-56-generic       | 3         | 1.14%   |
| 5.13.0-39-generic       | 3         | 1.14%   |
| 5.13.0-30-generic       | 3         | 1.14%   |
| 6.2.6-desktop-1omv2390  | 2         | 0.76%   |
| 6.1.1-desktop-1omv2290  | 2         | 0.76%   |
| 6.1.0-kali9-amd64       | 2         | 0.76%   |
| 6.0.8-300.fc37.x86_64   | 2         | 0.76%   |
| 5.9.8-200.fc33.x86_64   | 2         | 0.76%   |
| 5.8.0-59-generic        | 2         | 0.76%   |
| 5.8.0-48-generic        | 2         | 0.76%   |
| 5.4.0-91-generic        | 2         | 0.76%   |
| 5.4.0-58-generic        | 2         | 0.76%   |
| 5.4.0-45-generic        | 2         | 0.76%   |
| 5.4.0-39-generic        | 2         | 0.76%   |
| 5.4.0-33-generic        | 2         | 0.76%   |
| 5.4.0-29-generic        | 2         | 0.76%   |
| 5.19.0-kali2-amd64      | 2         | 0.76%   |
| 5.19.0-43-generic       | 2         | 0.76%   |
| 5.19.0-35-generic       | 2         | 0.76%   |
| 5.19.0-31-generic       | 2         | 0.76%   |
| 5.15.0-50-generic       | 2         | 0.76%   |
| 5.15.0-48-generic       | 2         | 0.76%   |
| 5.15.0-41-generic       | 2         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 20.33%  |
| 5.15.0  | 31        | 12.6%   |
| 5.11.0  | 20        | 8.13%   |
| 5.19.0  | 19        | 7.72%   |
| 5.8.0   | 16        | 6.5%    |
| 5.13.0  | 16        | 6.5%    |
| 4.15.0  | 12        | 4.88%   |
| 5.3.0   | 7         | 2.85%   |
| 5.0.0   | 6         | 2.44%   |
| 5.10.0  | 5         | 2.03%   |
| 6.2.6   | 3         | 1.22%   |
| 6.0.8   | 3         | 1.22%   |
| 5.16.7  | 3         | 1.22%   |
| 4.18.0  | 3         | 1.22%   |
| 6.2.0   | 2         | 0.81%   |
| 6.1.1   | 2         | 0.81%   |
| 6.1.0   | 2         | 0.81%   |
| 5.9.8   | 2         | 0.81%   |
| 5.19.9  | 2         | 0.81%   |
| 5.10.14 | 2         | 0.81%   |
| 6.2.10  | 1         | 0.41%   |
| 6.1.7   | 1         | 0.41%   |
| 6.1.20  | 1         | 0.41%   |
| 6.1.12  | 1         | 0.41%   |
| 6.0.6   | 1         | 0.41%   |
| 6.0.19  | 1         | 0.41%   |
| 6.0.12  | 1         | 0.41%   |
| 6.0.0   | 1         | 0.41%   |
| 5.9.10  | 1         | 0.41%   |
| 5.9.0   | 1         | 0.41%   |
| 5.7.9   | 1         | 0.41%   |
| 5.7.19  | 1         | 0.41%   |
| 5.7.0   | 1         | 0.41%   |
| 5.6.0   | 1         | 0.41%   |
| 5.4.175 | 1         | 0.41%   |
| 5.4.17  | 1         | 0.41%   |
| 5.4.15  | 1         | 0.41%   |
| 5.2.13  | 1         | 0.41%   |
| 5.19.14 | 1         | 0.41%   |
| 5.19.13 | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 21.63%  |
| 5.15    | 32        | 13.06%  |
| 5.19    | 23        | 9.39%   |
| 5.13    | 20        | 8.16%   |
| 5.11    | 20        | 8.16%   |
| 5.8     | 16        | 6.53%   |
| 4.15    | 12        | 4.9%    |
| 5.10    | 8         | 3.27%   |
| 6.1     | 7         | 2.86%   |
| 6.0     | 7         | 2.86%   |
| 5.3     | 7         | 2.86%   |
| 6.2     | 6         | 2.45%   |
| 5.0     | 6         | 2.45%   |
| 5.16    | 5         | 2.04%   |
| 5.14    | 4         | 1.63%   |
| 5.9     | 3         | 1.22%   |
| 5.7     | 3         | 1.22%   |
| 5.17    | 3         | 1.22%   |
| 4.18    | 3         | 1.22%   |
| 5.18    | 2         | 0.82%   |
| 5.12    | 2         | 0.82%   |
| 5.6     | 1         | 0.41%   |
| 5.2     | 1         | 0.41%   |
| 4.9     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 234       | 98.32%  |
| i686   | 4         | 1.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 164       | 67.49%  |
| KDE5       | 22        | 9.05%   |
| Unknown    | 20        | 8.23%   |
| XFCE       | 9         | 3.7%    |
| X-Cinnamon | 9         | 3.7%    |
| KDE        | 5         | 2.06%   |
| Unity      | 3         | 1.23%   |
| Pantheon   | 3         | 1.23%   |
| MATE       | 2         | 0.82%   |
| i3         | 2         | 0.82%   |
| LXQt       | 1         | 0.41%   |
| KDE4       | 1         | 0.41%   |
| Hyprland   | 1         | 0.41%   |
| Deepin     | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 176       | 72.43%  |
| Wayland | 50        | 20.58%  |
| Unknown | 17        | 7%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 112       | 46.67%  |
| GDM3    | 51        | 21.25%  |
| GDM     | 40        | 16.67%  |
| SDDM    | 19        | 7.92%   |
| LightDM | 12        | 5%      |
| TDM     | 4         | 1.67%   |
| XDM     | 1         | 0.42%   |
| KDM     | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 207       | 86.25%  |
| Unknown | 17        | 7.08%   |
| en_GB   | 9         | 3.75%   |
| en_PK   | 2         | 0.83%   |
| en_IN   | 2         | 0.83%   |
| ur_PK   | 1         | 0.42%   |
| en_CA   | 1         | 0.42%   |
| C       | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 125       | 51.65%  |
| BIOS | 117       | 48.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 199       | 82.92%  |
| Btrfs   | 14        | 5.83%   |
| Overlay | 9         | 3.75%   |
| Tmpfs   | 7         | 2.92%   |
| Xfs     | 5         | 2.08%   |
| Unknown | 5         | 2.08%   |
| Zfs     | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 135       | 56.49%  |
| GPT     | 78        | 32.64%  |
| MBR     | 26        | 10.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 87.92%  |
| Yes       | 29        | 12.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 155       | 64.32%  |
| Yes       | 86        | 35.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 93        | 39.08%  |
| Dell                | 68        | 28.57%  |
| Lenovo              | 38        | 15.97%  |
| Haier               | 7         | 2.94%   |
| Apple               | 6         | 2.52%   |
| Toshiba             | 4         | 1.68%   |
| ASUSTek Computer    | 4         | 1.68%   |
| Acer                | 4         | 1.68%   |
| Sony                | 3         | 1.26%   |
| Samsung Electronics | 3         | 1.26%   |
| Timi                | 1         | 0.42%   |
| MOTION              | 1         | 0.42%   |
| Google              | 1         | 0.42%   |
| Gigabyte Technology | 1         | 0.42%   |
| Fujitsu             | 1         | 0.42%   |
| Clevo               | 1         | 0.42%   |
| AMI                 | 1         | 0.42%   |
| Alienware           | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP ProBook 450 G7               | 5         | 2.1%    |
| HP EliteBook 8470p              | 5         | 2.1%    |
| HP EliteBook 840 G3             | 5         | 2.1%    |
| Dell Latitude E7450             | 5         | 2.1%    |
| Haier Y11C                      | 4         | 1.68%   |
| Dell Latitude E6420             | 4         | 1.68%   |
| HP ProBook 450 G5               | 3         | 1.26%   |
| HP EliteBook 840 G2             | 3         | 1.26%   |
| Haier Y11B                      | 3         | 1.26%   |
| Unknown                         | 3         | 1.26%   |
| Lenovo ThinkBook 15-IML 20RW    | 2         | 0.84%   |
| Lenovo ThinkBook 15-IIL 20SM    | 2         | 0.84%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 2         | 0.84%   |
| HP ZBook 15 G3                  | 2         | 0.84%   |
| HP ProBook 450 G8 Notebook PC   | 2         | 0.84%   |
| HP ProBook 450 G3               | 2         | 0.84%   |
| HP ProBook 440 G7               | 2         | 0.84%   |
| HP Pavilion Notebook            | 2         | 0.84%   |
| HP Pavilion g6                  | 2         | 0.84%   |
| HP Pavilion dv6                 | 2         | 0.84%   |
| HP Notebook                     | 2         | 0.84%   |
| HP Laptop 15s-fq5xxx            | 2         | 0.84%   |
| HP EliteBook Folio 9470m        | 2         | 0.84%   |
| HP EliteBook 850 G6             | 2         | 0.84%   |
| HP EliteBook 8440p              | 2         | 0.84%   |
| HP EliteBook 840 G1             | 2         | 0.84%   |
| HP EliteBook 6930p              | 2         | 0.84%   |
| HP 650                          | 2         | 0.84%   |
| Dell Vostro 14-3468             | 2         | 0.84%   |
| Dell Latitude E6440             | 2         | 0.84%   |
| Dell Latitude E5440             | 2         | 0.84%   |
| Dell Latitude E5250             | 2         | 0.84%   |
| Dell Latitude E4300             | 2         | 0.84%   |
| Dell Latitude 3510              | 2         | 0.84%   |
| Dell Inspiron 5593              | 2         | 0.84%   |
| Dell Inspiron 3501              | 2         | 0.84%   |
| Dell Inspiron 15-3567           | 2         | 0.84%   |
| Apple MacBookPro11,3            | 2         | 0.84%   |
| Toshiba Satellite S50t-B        | 1         | 0.42%   |
| Toshiba Satellite L850          | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 39        | 16.39%  |
| HP EliteBook       | 34        | 14.29%  |
| HP ProBook         | 26        | 10.92%  |
| Lenovo ThinkPad    | 22        | 9.24%   |
| Dell Inspiron      | 18        | 7.56%   |
| HP Pavilion        | 11        | 4.62%   |
| HP Laptop          | 8         | 3.36%   |
| Lenovo ThinkBook   | 6         | 2.52%   |
| Lenovo IdeaPad     | 5         | 2.1%    |
| Dell Vostro        | 5         | 2.1%    |
| HP ENVY            | 4         | 1.68%   |
| Haier Y11C         | 4         | 1.68%   |
| Haier Y11B         | 3         | 1.26%   |
| Dell Precision     | 3         | 1.26%   |
| Acer Aspire        | 3         | 1.26%   |
| Unknown            | 3         | 1.26%   |
| Toshiba Satellite  | 2         | 0.84%   |
| Toshiba PORTEGE    | 2         | 0.84%   |
| Lenovo Legion      | 2         | 0.84%   |
| HP ZBook           | 2         | 0.84%   |
| HP Notebook        | 2         | 0.84%   |
| HP 650             | 2         | 0.84%   |
| Dell G3            | 2         | 0.84%   |
| Apple MacBookPro11 | 2         | 0.84%   |
| Timi TM1613        | 1         | 0.42%   |
| Sony VPCEA26FG     | 1         | 0.42%   |
| Sony VPCCB490X     | 1         | 0.42%   |
| Sony SVE15126CXS   | 1         | 0.42%   |
| Samsung QX311      | 1         | 0.42%   |
| Samsung 940Z5L     | 1         | 0.42%   |
| Samsung 300E5EV    | 1         | 0.42%   |
| MOTION J3500       | 1         | 0.42%   |
| Lenovo V110-15IKB  | 1         | 0.42%   |
| Lenovo S20-30      | 1         | 0.42%   |
| Lenovo Edge        | 1         | 0.42%   |
| HP OMEN            | 1         | 0.42%   |
| HP 14              | 1         | 0.42%   |
| Google Glimmer     | 1         | 0.42%   |
| Gigabyte AERO      | 1         | 0.42%   |
| Fujitsu LIFEBOOK   | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 26        | 10.92%  |
| 2011 | 25        | 10.5%   |
| 2020 | 23        | 9.66%   |
| 2016 | 23        | 9.66%   |
| 2014 | 23        | 9.66%   |
| 2017 | 18        | 7.56%   |
| 2013 | 18        | 7.56%   |
| 2012 | 17        | 7.14%   |
| 2018 | 15        | 6.3%    |
| 2015 | 13        | 5.46%   |
| 2010 | 11        | 4.62%   |
| 2021 | 10        | 4.2%    |
| 2008 | 7         | 2.94%   |
| 2022 | 3         | 1.26%   |
| 2009 | 2         | 0.84%   |
| 2006 | 2         | 0.84%   |
| 2023 | 1         | 0.42%   |
| 2007 | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 238       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 223       | 93.31%  |
| Enabled  | 16        | 6.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 237       | 99.58%  |
| Yes  | 1         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 78        | 32.64%  |
| 16.01-24.0 | 49        | 20.5%   |
| 3.01-4.0   | 48        | 20.08%  |
| 8.01-16.0  | 46        | 19.25%  |
| 32.01-64.0 | 10        | 4.18%   |
| 1.01-2.0   | 5         | 2.09%   |
| 24.01-32.0 | 3         | 1.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 81        | 31.89%  |
| 1.01-2.0  | 76        | 29.92%  |
| 4.01-8.0  | 44        | 17.32%  |
| 3.01-4.0  | 36        | 14.17%  |
| 8.01-16.0 | 11        | 4.33%   |
| 0.51-1.0  | 6         | 2.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 183       | 76.57%  |
| 2      | 52        | 21.76%  |
| 3      | 2         | 0.84%   |
| 4      | 1         | 0.42%   |
| 0      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 71.97%  |
| Yes       | 67        | 28.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 92.86%  |
| No        | 17        | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 235       | 98.74%  |
| No        | 3         | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 73.86%  |
| No        | 63        | 26.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Pakistan | 238       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lahore                         | 78        | 32.23%  |
| Karachi                        | 50        | 20.66%  |
| Islamabad                      | 43        | 17.77%  |
| Rawalpindi                     | 19        | 7.85%   |
| Mirpur                         | 7         | 2.89%   |
| Faisalabad                     | 7         | 2.89%   |
| Multan                         | 6         | 2.48%   |
| Bahawalpur                     | 3         | 1.24%   |
| Sargodha                       | 2         | 0.83%   |
| Peshawar                       | 2         | 0.83%   |
| Jhelum                         | 2         | 0.83%   |
| Abbottabad                     | 2         | 0.83%   |
| Wah                            | 1         | 0.41%   |
| Vehari                         | 1         | 0.41%   |
| Topi                           | 1         | 0.41%   |
| Taunsa                         | 1         | 0.41%   |
| Swabi                          | 1         | 0.41%   |
| Sukkur                         | 1         | 0.41%   |
| Sialkot                        | 1         | 0.41%   |
| Rahim Yar Khan                 | 1         | 0.41%   |
| Pindi Gheb                     | 1         | 0.41%   |
| Layyah                         | 1         | 0.41%   |
| Layari                         | 1         | 0.41%   |
| Kohat                          | 1         | 0.41%   |
| Khanewal                       | 1         | 0.41%   |
| Hyderabad                      | 1         | 0.41%   |
| Hassan Abdal                   | 1         | 0.41%   |
| Ghotki                         | 1         | 0.41%   |
| Dina                           | 1         | 0.41%   |
| Daultala                       | 1         | 0.41%   |
| Daska Kalan                    | 1         | 0.41%   |
| Dadu                           | 1         | 0.41%   |
| Chak Five Hundred Seventy-five | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 41        | 50     | 14.04%  |
| Seagate             | 38        | 46     | 13.01%  |
| Samsung Electronics | 37        | 42     | 12.67%  |
| Toshiba             | 34        | 35     | 11.64%  |
| SanDisk             | 15        | 16     | 5.14%   |
| Kingston            | 15        | 17     | 5.14%   |
| Hitachi             | 10        | 12     | 3.42%   |
| Unknown             | 9         | 11     | 3.08%   |
| Transcend           | 9         | 9      | 3.08%   |
| Intel               | 9         | 11     | 3.08%   |
| SK hynix            | 8         | 12     | 2.74%   |
| Micron Technology   | 7         | 7      | 2.4%    |
| HGST                | 7         | 8      | 2.4%    |
| A-DATA Technology   | 6         | 6      | 2.05%   |
| Apple               | 5         | 6      | 1.71%   |
| Silicon Motion      | 4         | 4      | 1.37%   |
| LITEON              | 4         | 4      | 1.37%   |
| KIOXIA              | 4         | 4      | 1.37%   |
| HS-SSD-E100         | 4         | 4      | 1.37%   |
| Lexar               | 3         | 3      | 1.03%   |
| China               | 3         | 4      | 1.03%   |
| SPCC                | 2         | 2      | 0.68%   |
| Fujitsu             | 2         | 2      | 0.68%   |
| Crucial             | 2         | 2      | 0.68%   |
| Vaseky              | 1         | 1      | 0.34%   |
| Team                | 1         | 1      | 0.34%   |
| PNY                 | 1         | 2      | 0.34%   |
| Phison              | 1         | 2      | 0.34%   |
| PHD 3.0             | 1         | 1      | 0.34%   |
| LITEONIT            | 1         | 1      | 0.34%   |
| Kingsand            | 1         | 1      | 0.34%   |
| KESU                | 1         | 1      | 0.34%   |
| Integral            | 1         | 2      | 0.34%   |
| HS-SSD-E100N        | 1         | 1      | 0.34%   |
| Gritronix           | 1         | 1      | 0.34%   |
| CSD                 | 1         | 1      | 0.34%   |
| Biostar             | 1         | 1      | 0.34%   |
| Apacer              | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 7         | 2.33%   |
| WDC WD10SPZX-60Z10T0 1TB             | 6         | 2%      |
| Toshiba MQ04ABF100 1TB               | 6         | 2%      |
| Toshiba MQ01ABF050 500GB             | 6         | 2%      |
| Seagate ST500LT012-1DG142 500GB      | 4         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.33%   |
| Samsung MZALQ512HALU-000L1 512GB     | 4         | 1.33%   |
| WDC PC SN530 NVMe 256GB              | 3         | 1%      |
| Toshiba MQ01ACF050 500GB             | 3         | 1%      |
| Silicon Motion NVMe SSD Drive 512GB  | 3         | 1%      |
| Seagate ST9250311CS 250GB            | 3         | 1%      |
| Seagate ST500LM000-1EJ162 500GB      | 3         | 1%      |
| LITEON CS1-SP32 32GB SSD             | 3         | 1%      |
| Hitachi HTS545032B9A300 320GB        | 3         | 1%      |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.67%   |
| WDC WD10SPZX-75Z10T3 1TB             | 2         | 0.67%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.67%   |
| WDC WD Elements 320GB                | 2         | 0.67%   |
| Unknown MMC Card  32GB               | 2         | 0.67%   |
| Transcend TS512GMTE110S 512GB        | 2         | 0.67%   |
| Transcend TS256GMTS830S 256GB SSD    | 2         | 0.67%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.67%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.67%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.67%   |
| Seagate ST9320423AS 320GB            | 2         | 0.67%   |
| Seagate ST9250315AS 250GB            | 2         | 0.67%   |
| SanDisk X110 MSATA 128GB SSD         | 2         | 0.67%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD  | 2         | 0.67%   |
| SanDisk SD7SN6S-256G-1006 256GB SSD  | 2         | 0.67%   |
| Samsung SSD 870 EVO 500GB            | 2         | 0.67%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB | 2         | 0.67%   |
| Lexar 512GB SSD                      | 2         | 0.67%   |
| KIOXIA NVMe SSD Drive 256GB          | 2         | 0.67%   |
| Intel SSDSC2BF180A4H 180GB           | 2         | 0.67%   |
| Intel SSDSA2M080G2GN 80GB            | 2         | 0.67%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.67%   |
| Hitachi HTS543225A7A384 250GB        | 2         | 0.67%   |
| HGST HTS541010B7E610 1TB             | 2         | 0.67%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.67%   |
| WDC WDS256G2G0B-00EPW0 256GB SSD     | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 46     | 31.4%   |
| WDC                 | 31        | 35     | 25.62%  |
| Toshiba             | 28        | 29     | 23.14%  |
| Hitachi             | 10        | 12     | 8.26%   |
| HGST                | 7         | 8      | 5.79%   |
| Samsung Electronics | 2         | 2      | 1.65%   |
| Fujitsu             | 2         | 2      | 1.65%   |
| Unknown             | 1         | 1      | 0.83%   |
| PHD 3.0             | 1         | 1      | 0.83%   |
| KESU                | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 24     | 23.23%  |
| Kingston            | 11        | 13     | 11.11%  |
| SanDisk             | 10        | 10     | 10.1%   |
| SK hynix            | 6         | 10     | 6.06%   |
| Intel               | 5         | 6      | 5.05%   |
| WDC                 | 4         | 6      | 4.04%   |
| Transcend           | 4         | 4      | 4.04%   |
| Micron Technology   | 4         | 4      | 4.04%   |
| LITEON              | 4         | 4      | 4.04%   |
| A-DATA Technology   | 4         | 4      | 4.04%   |
| Toshiba             | 3         | 3      | 3.03%   |
| Lexar               | 3         | 3      | 3.03%   |
| China               | 3         | 4      | 3.03%   |
| SPCC                | 2         | 2      | 2.02%   |
| HS-SSD-E100         | 2         | 2      | 2.02%   |
| Crucial             | 2         | 2      | 2.02%   |
| Apple               | 2         | 2      | 2.02%   |
| Vaseky              | 1         | 1      | 1.01%   |
| Team                | 1         | 1      | 1.01%   |
| PNY                 | 1         | 2      | 1.01%   |
| LITEONIT            | 1         | 1      | 1.01%   |
| Gritronix           | 1         | 1      | 1.01%   |
| Biostar             | 1         | 1      | 1.01%   |
| Apacer              | 1         | 1      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 117       | 137    | 41.2%   |
| SSD     | 95        | 111    | 33.45%  |
| NVMe    | 58        | 69     | 20.42%  |
| Unknown | 8         | 9      | 2.82%   |
| MMC     | 6         | 8      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 187       | 251    | 72.76%  |
| NVMe | 58        | 69     | 22.57%  |
| SAS  | 6         | 6      | 2.33%   |
| MMC  | 6         | 8      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 138       | 180    | 69%     |
| 0.51-1.0   | 61        | 67     | 30.5%   |
| 4.01-10.0  | 1         | 1      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 96        | 39.02%  |
| 251-500        | 64        | 26.02%  |
| 51-100         | 36        | 14.63%  |
| 501-1000       | 24        | 9.76%   |
| 1-20           | 12        | 4.88%   |
| 21-50          | 9         | 3.66%   |
| 1001-2000      | 4         | 1.63%   |
| More than 3000 | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 96        | 38.1%   |
| 21-50    | 74        | 29.37%  |
| 101-250  | 34        | 13.49%  |
| 51-100   | 33        | 13.1%   |
| 251-500  | 10        | 3.97%   |
| 501-1000 | 5         | 1.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 10%     |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 5%      |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 5%      |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 5%      |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 5%      |
| Seagate ST980411ASG 80GB                      | 1         | 2      | 5%      |
| Seagate ST500LM021-1KJ152 500GB               | 1         | 1      | 5%      |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 5%      |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 5%      |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 5%      |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 5%      |
| Intel SSDSC2BF180A4H 180GB                    | 1         | 1      | 5%      |
| HS-SSD-E100 SSD 1024G                         | 1         | 1      | 5%      |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 5%      |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 5%      |
| Gritronix M.2 2280 256GB SSD                  | 1         | 1      | 5%      |
| China SSD 240GB                               | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 6      | 25%     |
| WDC               | 4         | 5      | 20%     |
| Toshiba           | 2         | 2      | 10%     |
| Intel             | 2         | 2      | 10%     |
| Hitachi           | 2         | 2      | 10%     |
| SK hynix          | 1         | 1      | 5%      |
| Micron Technology | 1         | 1      | 5%      |
| HS-SSD-E100       | 1         | 1      | 5%      |
| Gritronix         | 1         | 1      | 5%      |
| China             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 38.46%  |
| WDC     | 4         | 5      | 30.77%  |
| Toshiba | 2         | 2      | 15.38%  |
| Hitachi | 2         | 2      | 15.38%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 65%     |
| SSD  | 7         | 7      | 35%     |

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
| Detected | 152       | 214    | 61.29%  |
| Works    | 76        | 98     | 30.65%  |
| Malfunc  | 20        | 22     | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 206       | 75.46%  |
| Samsung Electronics          | 15        | 5.49%   |
| SanDisk                      | 11        | 4.03%   |
| AMD                          | 8         | 2.93%   |
| KIOXIA                       | 6         | 2.2%    |
| Silicon Motion               | 5         | 1.83%   |
| Transcend                    | 4         | 1.47%   |
| Kingston Technology Company  | 4         | 1.47%   |
| Micron Technology            | 3         | 1.1%    |
| Apple                        | 3         | 1.1%    |
| Toshiba America Info Systems | 2         | 0.73%   |
| SK hynix                     | 2         | 0.73%   |
| Realtek Semiconductor        | 1         | 0.37%   |
| Phison Electronics           | 1         | 0.37%   |
| Marvell Technology Group     | 1         | 0.37%   |
| ADATA Technology             | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 43        | 14.63%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 22        | 7.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 19        | 6.46%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 15        | 5.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 14        | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 13        | 4.42%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 13        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 13        | 4.42%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 9         | 3.06%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 2.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 7         | 2.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 2.38%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 6         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 2.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 5         | 1.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 5         | 1.7%    |
| Transcend Non-Volatile memory controller                                               | 4         | 1.36%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                  | 4         | 1.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.36%   |
| Micron NVMe Storage Controller                                                         | 3         | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 1.02%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 3         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 0.68%   |
| Kingston Company NVMe Controller                                                       | 2         | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.68%   |
| Intel NVMe Controller                                                                  | 2         | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 0.68%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.68%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.68%   |
| Apple ANS2 NVMe Controller                                                             | 2         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 178       | 62.68%  |
| NVMe | 58        | 20.42%  |
| RAID | 35        | 12.32%  |
| IDE  | 13        | 4.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 228       | 95.8%   |
| AMD    | 10        | 4.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 4.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 3.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 8         | 3.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 2.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 2.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 2.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 2.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 2.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 2.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 2.1%    |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 4         | 1.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.68%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 4         | 1.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 1.68%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 3         | 1.26%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.26%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.26%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 3         | 1.26%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.26%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 1.26%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 1.26%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.26%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.26%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 3         | 1.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.84%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.84%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.84%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.84%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.84%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 2         | 0.84%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 97        | 40.76%  |
| Intel Core i7        | 69        | 28.99%  |
| Other                | 24        | 10.08%  |
| Intel Core i3        | 11        | 4.62%   |
| Intel Core 2 Duo     | 7         | 2.94%   |
| Intel Celeron        | 6         | 2.52%   |
| Intel Core m3        | 4         | 1.68%   |
| AMD Ryzen 7          | 4         | 1.68%   |
| Intel Core M         | 3         | 1.26%   |
| Intel Atom           | 2         | 0.84%   |
| AMD A6               | 2         | 0.84%   |
| Intel Xeon           | 1         | 0.42%   |
| Intel Pentium        | 1         | 0.42%   |
| Intel Genuine        | 1         | 0.42%   |
| Intel Core 2 Extreme | 1         | 0.42%   |
| Intel Core 2         | 1         | 0.42%   |
| AMD Ryzen 5          | 1         | 0.42%   |
| AMD E                | 1         | 0.42%   |
| AMD A4               | 1         | 0.42%   |
| AMD A12              | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 135       | 56.72%  |
| 4      | 86        | 36.13%  |
| 6      | 9         | 3.78%   |
| 8      | 4         | 1.68%   |
| 10     | 2         | 0.84%   |
| 14     | 1         | 0.42%   |
| 1      | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 238       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 210       | 88.24%  |
| 1      | 28        | 11.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 236       | 98.74%  |
| Unknown        | 2         | 0.84%   |
| 32-bit         | 1         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 23.36%  |
| 0x806c1    | 16        | 6.56%   |
| 0x406e3    | 16        | 6.56%   |
| 0x206a7    | 16        | 6.56%   |
| 0x806ec    | 14        | 5.74%   |
| 0x806e9    | 13        | 5.33%   |
| 0x40651    | 13        | 5.33%   |
| 0x306d4    | 13        | 5.33%   |
| 0x306a9    | 13        | 5.33%   |
| 0x806ea    | 11        | 4.51%   |
| 0x20655    | 9         | 3.69%   |
| 0x706e5    | 6         | 2.46%   |
| 0x306c3    | 6         | 2.46%   |
| 0x906ea    | 4         | 1.64%   |
| 0x1067a    | 4         | 1.64%   |
| 0xa0652    | 3         | 1.23%   |
| 0x30678    | 3         | 1.23%   |
| 0x906e9    | 2         | 0.82%   |
| 0x506e3    | 2         | 0.82%   |
| 0x10676    | 2         | 0.82%   |
| 0x08608103 | 2         | 0.82%   |
| 0xa0660    | 1         | 0.41%   |
| 0x906a4    | 1         | 0.41%   |
| 0x906a3    | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |
| 0x706a1    | 1         | 0.41%   |
| 0x6fd      | 1         | 0.41%   |
| 0x6f6      | 1         | 0.41%   |
| 0x406c4    | 1         | 0.41%   |
| 0x40661    | 1         | 0.41%   |
| 0x20652    | 1         | 0.41%   |
| 0x106e5    | 1         | 0.41%   |
| 0x0a50000c | 1         | 0.41%   |
| 0x08600106 | 1         | 0.41%   |
| 0x08600104 | 1         | 0.41%   |
| 0x0700010f | 1         | 0.41%   |
| 0x0600611a | 1         | 0.41%   |
| 0x0600111f | 1         | 0.41%   |
| 0x05000119 | 1         | 0.41%   |
| 0x03000027 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 58        | 24.37%  |
| Haswell          | 26        | 10.92%  |
| Skylake          | 21        | 8.82%   |
| IvyBridge        | 21        | 8.82%   |
| TigerLake        | 20        | 8.4%    |
| SandyBridge      | 20        | 8.4%    |
| Broadwell        | 18        | 7.56%   |
| Westmere         | 11        | 4.62%   |
| Silvermont       | 7         | 2.94%   |
| Penryn           | 7         | 2.94%   |
| Icelake          | 7         | 2.94%   |
| CometLake        | 4         | 1.68%   |
| Unknown          | 3         | 1.26%   |
| Zen 2            | 2         | 0.84%   |
| Core             | 2         | 0.84%   |
| Alderlake Hybrid | 2         | 0.84%   |
| Zen 3            | 1         | 0.42%   |
| Piledriver       | 1         | 0.42%   |
| P6               | 1         | 0.42%   |
| Nehalem          | 1         | 0.42%   |
| K10 Llano        | 1         | 0.42%   |
| Jaguar           | 1         | 0.42%   |
| Goldmont plus    | 1         | 0.42%   |
| Excavator        | 1         | 0.42%   |
| Bobcat           | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 212       | 71.14%  |
| Nvidia | 49        | 16.44%  |
| AMD    | 37        | 12.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 19        | 6.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 18        | 5.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 18        | 5.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 18        | 5.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 17        | 5.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 16        | 5.32%   |
| Intel HD Graphics 5500                                                                | 15        | 4.98%   |
| Intel UHD Graphics 620                                                                | 14        | 4.65%   |
| Intel HD Graphics 620                                                                 | 11        | 3.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 2.66%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 6         | 1.99%   |
| Nvidia GP108M [GeForce MX230]                                                         | 5         | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 1.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 5         | 1.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.33%   |
| Intel HD Graphics 615                                                                 | 4         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 1.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1%      |
| Intel HD Graphics 5300                                                                | 3         | 1%      |
| Intel HD Graphics 530                                                                 | 3         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 1%      |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 0.66%   |
| Nvidia GT218M [NVS 3100M]                                                             | 2         | 0.66%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.66%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 0.66%   |
| Nvidia GF119M [NVS 4200M]                                                             | 2         | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 2         | 0.66%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 2         | 0.66%   |
| AMD Topaz PRO [Radeon R5 M255]                                                        | 2         | 0.66%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 2         | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 0.66%   |
| AMD Renoir                                                                            | 2         | 0.66%   |
| AMD Lucienne                                                                          | 2         | 0.66%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 154       | 64.71%  |
| Intel + Nvidia | 38        | 15.97%  |
| Intel + AMD    | 20        | 8.4%    |
| 1 x AMD        | 15        | 6.3%    |
| 1 x Nvidia     | 9         | 3.78%   |
| AMD + Nvidia   | 2         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 215       | 90.34%  |
| Proprietary | 22        | 9.24%   |
| Unknown     | 1         | 0.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 71.67%  |
| 1.01-2.0   | 34        | 14.17%  |
| 0.01-0.5   | 13        | 5.42%   |
| 3.01-4.0   | 10        | 4.17%   |
| 0.51-1.0   | 10        | 4.17%   |
| 5.01-6.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 60        | 24.19%  |
| AU Optronics            | 43        | 17.34%  |
| Chimei Innolux          | 39        | 15.73%  |
| BOE                     | 34        | 13.71%  |
| Samsung Electronics     | 18        | 7.26%   |
| Dell                    | 9         | 3.63%   |
| Chi Mei Optoelectronics | 8         | 3.23%   |
| Apple                   | 6         | 2.42%   |
| Sharp                   | 4         | 1.61%   |
| InfoVision              | 4         | 1.61%   |
| Hewlett-Packard         | 4         | 1.61%   |
| KDC                     | 3         | 1.21%   |
| Sony                    | 2         | 0.81%   |
| PANDA                   | 2         | 0.81%   |
| LGD                     | 2         | 0.81%   |
| LG Philips              | 2         | 0.81%   |
| Lenovo                  | 2         | 0.81%   |
| Goldstar                | 2         | 0.81%   |
| BenQ                    | 2         | 0.81%   |
| LPL                     | 1         | 0.4%    |
| Acer                    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 2.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 2.02%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 1.61%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 1.21%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 1.21%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 3         | 1.21%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 3         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 1.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 2         | 0.81%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 0.81%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 2         | 0.81%   |
| Dell P2217H DELA0D9 1920x1080 480x270mm 21.7-inch                     | 2         | 0.81%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch       | 2         | 0.81%   |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                 | 2         | 0.81%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 2         | 0.81%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch         | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO3191 1366x768 344x193mm 15.5-inch         | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch         | 2         | 0.81%   |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.4%    |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.4%    |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 104       | 43.7%   |
| 1366x768 (WXGA)    | 95        | 39.92%  |
| 1600x900 (HD+)     | 12        | 5.04%   |
| 1280x800 (WXGA)    | 6         | 2.52%   |
| 3840x2160 (4K)     | 4         | 1.68%   |
| 2880x1800          | 4         | 1.68%   |
| 1680x1050 (WSXGA+) | 4         | 1.68%   |
| 1440x900 (WXGA+)   | 3         | 1.26%   |
| 3440x1440          | 1         | 0.42%   |
| 2560x1600          | 1         | 0.42%   |
| 1920x1200 (WUXGA)  | 1         | 0.42%   |
| 1360x768           | 1         | 0.42%   |
| 1280x1024 (SXGA)   | 1         | 0.42%   |
| 1024x768 (XGA)     | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 116       | 47.15%  |
| 14      | 43        | 17.48%  |
| 13      | 34        | 13.82%  |
| 17      | 12        | 4.88%   |
| 12      | 9         | 3.66%   |
| 24      | 6         | 2.44%   |
| 11      | 6         | 2.44%   |
| 23      | 4         | 1.63%   |
| 21      | 4         | 1.63%   |
| Unknown | 3         | 1.22%   |
| 22      | 2         | 0.81%   |
| 18      | 2         | 0.81%   |
| 72      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 31      | 1         | 0.41%   |
| 20      | 1         | 0.41%   |
| 16      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 173       | 70.9%   |
| 201-300     | 33        | 13.52%  |
| 351-400     | 14        | 5.74%   |
| 501-600     | 9         | 3.69%   |
| 401-500     | 9         | 3.69%   |
| Unknown     | 3         | 1.23%   |
| 801-900     | 1         | 0.41%   |
| 601-700     | 1         | 0.41%   |
| 1501-2000   | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 207       | 89.61%  |
| 16/10   | 18        | 7.79%   |
| Unknown | 3         | 1.3%    |
| 5/4     | 1         | 0.43%   |
| 4/3     | 1         | 0.43%   |
| 3/2     | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 116       | 47.35%  |
| 81-90          | 60        | 24.49%  |
| 71-80          | 15        | 6.12%   |
| 201-250        | 14        | 5.71%   |
| 61-70          | 9         | 3.67%   |
| 121-130        | 9         | 3.67%   |
| 51-60          | 6         | 2.45%   |
| 141-150        | 3         | 1.22%   |
| 91-100         | 3         | 1.22%   |
| Unknown        | 3         | 1.22%   |
| 151-200        | 2         | 0.82%   |
| 131-140        | 2         | 0.82%   |
| More than 1000 | 1         | 0.41%   |
| 351-500        | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 115       | 47.33%  |
| 101-120       | 87        | 35.8%   |
| 51-100        | 23        | 9.47%   |
| 161-240       | 10        | 4.12%   |
| More than 240 | 4         | 1.65%   |
| Unknown       | 3         | 1.23%   |
| 1-50          | 1         | 0.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 218       | 91.21%  |
| 2     | 19        | 7.95%   |
| 3     | 1         | 0.42%   |
| 0     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 166       | 43.46%  |
| Realtek Semiconductor      | 124       | 32.46%  |
| Qualcomm Atheros           | 26        | 6.81%   |
| Broadcom                   | 23        | 6.02%   |
| Broadcom Limited           | 9         | 2.36%   |
| MediaTek                   | 5         | 1.31%   |
| Hewlett-Packard            | 5         | 1.31%   |
| Ralink                     | 4         | 1.05%   |
| ASIX Electronics           | 3         | 0.79%   |
| Xiaomi                     | 2         | 0.52%   |
| Spreadtrum Communications  | 2         | 0.52%   |
| Sierra Wireless            | 2         | 0.52%   |
| Dell                       | 2         | 0.52%   |
| ZTE WCDMA Technologies MSM | 1         | 0.26%   |
| Samsung Electronics        | 1         | 0.26%   |
| Ralink Technology          | 1         | 0.26%   |
| Qualcomm                   | 1         | 0.26%   |
| OPPO Electronics           | 1         | 0.26%   |
| Marvell Technology Group   | 1         | 0.26%   |
| JMicron Technology         | 1         | 0.26%   |
| Huawei Technologies        | 1         | 0.26%   |
| D-Link                     | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 17.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 4.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 3.93%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 3.31%   |
| Intel Wireless 7265                                               | 14        | 2.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 2.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 13        | 2.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 2.48%   |
| Intel Wireless 8260                                               | 12        | 2.48%   |
| Intel Wireless 3165                                               | 12        | 2.48%   |
| Intel Wireless 7260                                               | 11        | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.27%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.03%   |
| Intel Wireless 3160                                               | 5         | 1.03%   |
| Intel Ultimate N WiFi Link 5300                                   | 5         | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.03%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.03%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.03%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.83%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.62%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 155       | 63.01%  |
| Realtek Semiconductor | 26        | 10.57%  |
| Qualcomm Atheros      | 24        | 9.76%   |
| Broadcom              | 21        | 8.54%   |
| Broadcom Limited      | 6         | 2.44%   |
| Ralink                | 4         | 1.63%   |
| Sierra Wireless       | 2         | 0.81%   |
| MediaTek              | 2         | 0.81%   |
| Hewlett-Packard       | 2         | 0.81%   |
| Dell                  | 2         | 0.81%   |
| Ralink Technology     | 1         | 0.41%   |
| D-Link                | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                           | 16        | 6.45%   |
| Intel Wireless 7265                                           | 14        | 5.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 14        | 5.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 12        | 4.84%   |
| Intel Wireless 8260                                           | 12        | 4.84%   |
| Intel Wireless 3165                                           | 12        | 4.84%   |
| Intel Wireless 7260                                           | 11        | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 11        | 4.44%   |
| Intel Wireless 8265 / 8275                                    | 8         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 7         | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 6         | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 2.02%   |
| Intel Wireless 3160                                           | 5         | 2.02%   |
| Intel Ultimate N WiFi Link 5300                               | 5         | 2.02%   |
| Intel Centrino Ultimate-N 6300                                | 5         | 2.02%   |
| Intel Centrino Advanced-N 6235                                | 5         | 2.02%   |
| Intel Centrino Advanced-N 6200                                | 5         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 5         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 4         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 1.61%   |
| Intel Wi-Fi 6 AX200                                           | 4         | 1.61%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 4         | 1.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 3         | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.21%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 3         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 1.21%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.81%   |
| Intel Wireless-AC 9260                                        | 2         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 2         | 0.81%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]          | 2         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 0.81%   |
| HP lt4112 Gobi 4G Module Network Device                       | 2         | 0.81%   |
| Dell Hub of E-Port Replicator                                 | 2         | 0.81%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 2         | 0.81%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 2         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 116       | 50.43%  |
| Intel                     | 89        | 38.7%   |
| MediaTek                  | 3         | 1.3%    |
| Broadcom Limited          | 3         | 1.3%    |
| Broadcom                  | 3         | 1.3%    |
| ASIX Electronics          | 3         | 1.3%    |
| Xiaomi                    | 2         | 0.87%   |
| Spreadtrum Communications | 2         | 0.87%   |
| Qualcomm Atheros          | 2         | 0.87%   |
| Hewlett-Packard           | 2         | 0.87%   |
| Qualcomm                  | 1         | 0.43%   |
| OPPO Electronics          | 1         | 0.43%   |
| Marvell Technology Group  | 1         | 0.43%   |
| JMicron Technology        | 1         | 0.43%   |
| Huawei Technologies       | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 86        | 36.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 9.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 8.15%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 5.58%   |
| Intel Ethernet Connection I218-LM                                              | 9         | 3.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 3%      |
| Intel Ethernet Connection I219-LM                                              | 7         | 3%      |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 3%      |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 2.58%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.15%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 2.15%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 2.15%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.29%   |
| Spreadtrum Spreadtrum Phone                                                    | 2         | 0.86%   |
| MediaTek Armor X10 Pro                                                         | 2         | 0.86%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.86%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.86%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.43%   |
| Qualcomm Nokia G400 5G                                                         | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.43%   |
| OPPO CPH2411                                                                   | 1         | 0.43%   |
| MediaTek WP15                                                                  | 1         | 0.43%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.43%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.43%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.43%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.43%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.43%   |
| Huawei E353/E3131                                                              | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 235       | 51.2%   |
| Ethernet | 221       | 48.15%  |
| Modem    | 3         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 209       | 86.72%  |
| Ethernet | 32        | 13.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 206       | 86.19%  |
| 1     | 27        | 11.3%   |
| 0     | 4         | 1.67%   |
| 4     | 1         | 0.42%   |
| 3     | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 221       | 92.47%  |
| Yes  | 18        | 7.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 61.8%   |
| Qualcomm Atheros Communications | 18        | 10.11%  |
| Realtek Semiconductor           | 17        | 9.55%   |
| Broadcom                        | 13        | 7.3%    |
| Foxconn / Hon Hai               | 4         | 2.25%   |
| Dell                            | 4         | 2.25%   |
| Ralink                          | 3         | 1.69%   |
| Apple                           | 3         | 1.69%   |
| IMC Networks                    | 2         | 1.12%   |
| Hewlett-Packard                 | 2         | 1.12%   |
| Ralink Technology               | 1         | 0.56%   |
| Lite-On Technology              | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 57        | 32.02%  |
| Intel AX201 Bluetooth                                                               | 20        | 11.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 10.11%  |
| Realtek Bluetooth Radio                                                             | 11        | 6.18%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 6.18%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.37%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 2.81%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.25%   |
| Intel AX200 Bluetooth                                                               | 4         | 2.25%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.69%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.12%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.12%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.12%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.12%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.56%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.56%   |
| Ralink CSR BS8510                                                                   | 1         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.56%   |
| Intel Bluetooth Device                                                              | 1         | 0.56%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.56%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.56%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.56%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.56%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.56%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.56%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.56%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.56%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 225       | 83.96%  |
| Nvidia                 | 18        | 6.72%   |
| AMD                    | 16        | 5.97%   |
| Logitech               | 2         | 0.75%   |
| Generalplus Technology | 2         | 0.75%   |
| Apple                  | 2         | 0.75%   |
| Realtek Semiconductor  | 1         | 0.37%   |
| OPPO Electronics       | 1         | 0.37%   |
| JMTek                  | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 48        | 15.05%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 7.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 6.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 5.64%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 5.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18        | 5.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 5.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 5.33%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 5.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 2.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.94%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.94%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.94%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.63%   |
| Nvidia Audio device                                                        | 2         | 0.63%   |
| Logitech Headset H340                                                      | 2         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.63%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.63%   |
| Apple Audio Device                                                         | 2         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.63%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.31%   |
| OPPO Electronics CPH2269                                                   | 1         | 0.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.31%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 30.87%  |
| SK hynix            | 39        | 26.17%  |
| Micron Technology   | 17        | 11.41%  |
| A-DATA Technology   | 12        | 8.05%   |
| Crucial             | 6         | 4.03%   |
| Transcend           | 5         | 3.36%   |
| Kingston            | 4         | 2.68%   |
| Team                | 3         | 2.01%   |
| Lexar               | 3         | 2.01%   |
| Unknown             | 2         | 1.34%   |
| Spectek             | 2         | 1.34%   |
| Nanya Technology    | 2         | 1.34%   |
| Elpida              | 2         | 1.34%   |
| Unknown (768A)      | 1         | 0.67%   |
| TwinMOS             | 1         | 0.67%   |
| Ramaxel Technology  | 1         | 0.67%   |
| Patriot             | 1         | 0.67%   |
| Hikvision           | 1         | 0.67%   |
| Axiom               | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 3.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 5         | 3.13%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s           | 5         | 3.13%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s    | 3         | 1.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 3         | 1.88%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 3         | 1.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s          | 2         | 1.25%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s              | 2         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s           | 2         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s           | 2         | 1.25%   |
| Samsung RAM M471A5143DB0-CPB 4096MB SODIMM DDR4 2133MT/s | 2         | 1.25%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 1.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s    | 2         | 1.25%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s | 2         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 1.25%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 2         | 1.25%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s     | 2         | 1.25%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 2         | 1.25%   |
| Lexar RAM LD4AS016G-H2666G 16GB SODIMM DDR4 2667MT/s     | 2         | 1.25%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s               | 2         | 1.25%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s        | 1         | 0.63%   |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s   | 1         | 0.63%   |
| TwinMOS RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 3200MT/s | 1         | 0.63%   |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s            | 1         | 0.63%   |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.63%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.63%   |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.63%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s    | 1         | 0.63%   |
| Spectek RAM Module 8GB Row Of Chips LPDDR3 1600MT/s      | 1         | 0.63%   |
| Spectek RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s   | 1         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s             | 1         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s          | 1         | 0.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s          | 1         | 0.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s          | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 67        | 57.76%  |
| DDR3   | 42        | 36.21%  |
| LPDDR3 | 3         | 2.59%   |
| LPDDR4 | 2         | 1.72%   |
| DDR5   | 1         | 0.86%   |
| DDR    | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 109       | 93.16%  |
| Row Of Chips | 7         | 5.98%   |
| DIMM         | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 40.94%  |
| 4096  | 37        | 29.13%  |
| 16384 | 25        | 19.69%  |
| 2048  | 9         | 7.09%   |
| 32768 | 4         | 3.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 36        | 27.91%  |
| 2667  | 32        | 24.81%  |
| 3200  | 23        | 17.83%  |
| 2133  | 11        | 8.53%   |
| 2400  | 10        | 7.75%   |
| 1334  | 8         | 6.2%    |
| 1333  | 3         | 2.33%   |
| 8400  | 1         | 0.78%   |
| 4800  | 1         | 0.78%   |
| 4267  | 1         | 0.78%   |
| 2267  | 1         | 0.78%   |
| 1067  | 1         | 0.78%   |
| 1066  | 1         | 0.78%   |

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
| Chicony Electronics                    | 61        | 28.11%  |
| Microdia                               | 27        | 12.44%  |
| Sunplus Innovation Technology          | 21        | 9.68%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 9.22%   |
| Realtek Semiconductor                  | 15        | 6.91%   |
| Lite-On Technology                     | 13        | 5.99%   |
| Quanta                                 | 8         | 3.69%   |
| Suyin                                  | 7         | 3.23%   |
| IMC Networks                           | 7         | 3.23%   |
| Bison Electronics                      | 6         | 2.76%   |
| Syntek                                 | 5         | 2.3%    |
| Ricoh                                  | 5         | 2.3%    |
| Luxvisions Innotech Limited            | 5         | 2.3%    |
| Silicon Motion                         | 4         | 1.84%   |
| Apple                                  | 3         | 1.38%   |
| Acer                                   | 3         | 1.38%   |
| Primax Electronics                     | 2         | 0.92%   |
| Logitech                               | 2         | 0.92%   |
| Pixart Imaging                         | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| DigiTech                               | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 14        | 6.42%   |
| Sunplus Integrated_Webcam_HD                                               | 13        | 5.96%   |
| Chicony Integrated Camera                                                  | 12        | 5.5%    |
| Chicony HP HD Camera                                                       | 10        | 4.59%   |
| Lite-On HP HD Webcam                                                       | 9         | 4.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 3.21%   |
| Microdia Integrated Webcam                                                 | 5         | 2.29%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 1.83%   |
| Quanta HP HD Camera                                                        | 4         | 1.83%   |
| Chicony USB 2.0Camera                                                      | 4         | 1.83%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.83%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.83%   |
| Chicony HP TrueVision HD                                                   | 4         | 1.83%   |
| Syntek Integrated Camera                                                   | 3         | 1.38%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.38%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.38%   |
| Realtek USB2.0 camera                                                      | 3         | 1.38%   |
| Realtek Integrated Webcam                                                  | 3         | 1.38%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.38%   |
| IMC Networks Integrated Camera                                             | 3         | 1.38%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.38%   |
| Chicony EasyCamera                                                         | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 3         | 1.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 3         | 1.38%   |
| Suyin HP Truevision HD                                                     | 2         | 0.92%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 0.92%   |
| Sunplus HP Universal Camera                                                | 2         | 0.92%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.92%   |
| Realtek Integrated Webcam_HD                                               | 2         | 0.92%   |
| Realtek HP Truevision HD                                                   | 2         | 0.92%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.92%   |
| Primax HP HD Webcam [Fixed]                                                | 2         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 0.92%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.92%   |
| Lite-On Integrated Camera                                                  | 2         | 0.92%   |
| Lite-On HP HD Camera                                                       | 2         | 0.92%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.92%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 2         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 47        | 64.38%  |
| Synaptics                  | 11        | 15.07%  |
| Shenzhen Goodix Technology | 6         | 8.22%   |
| AuthenTec                  | 4         | 5.48%   |
| Upek                       | 3         | 4.11%   |
| Elan Microelectronics      | 2         | 2.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 26.03%  |
| Validity Sensors VFS491                                                    | 10        | 13.7%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 9.59%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 8.22%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 5.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.11%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.11%   |
| AuthenTec AES2810                                                          | 3         | 4.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.74%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 2.74%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.74%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.37%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.37%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.37%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.37%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 24        | 88.89%  |
| O2 Micro | 3         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 120       | 50.21%  |
| 1     | 103       | 43.1%   |
| 2     | 14        | 5.86%   |
| 8     | 1         | 0.42%   |
| 4     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 72        | 50.7%   |
| Chipcard                 | 27        | 19.01%  |
| Graphics card            | 12        | 8.45%   |
| Net/wireless             | 6         | 4.23%   |
| Storage                  | 5         | 3.52%   |
| Bluetooth                | 5         | 3.52%   |
| Sound                    | 4         | 2.82%   |
| Multimedia controller    | 3         | 2.11%   |
| Camera                   | 3         | 2.11%   |
| Communication controller | 2         | 1.41%   |
| Network                  | 1         | 0.7%    |
| Net/ethernet             | 1         | 0.7%    |
| Card reader              | 1         | 0.7%    |


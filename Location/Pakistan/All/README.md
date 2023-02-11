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

Total: 423

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 83        | 27.21%  |
| Ubuntu 18.04       | 25        | 8.2%    |
| Ubuntu 22.04       | 23        | 7.54%   |
| Debian 11          | 9         | 2.95%   |
| Arch               | 8         | 2.62%   |
| OpenMandriva 4.3   | 7         | 2.3%    |
| Ubuntu 21.04       | 6         | 1.97%   |
| KDE neon 20.04     | 6         | 1.97%   |
| Debian 10          | 6         | 1.97%   |
| Zorin 15           | 5         | 1.64%   |
| Pop!_OS 20.04      | 5         | 1.64%   |
| Zorin 16           | 4         | 1.31%   |
| Ubuntu 19.04       | 4         | 1.31%   |
| Pop!_OS 22.04      | 4         | 1.31%   |
| Pop!_OS 21.04      | 4         | 1.31%   |
| OpenMandriva 4.2   | 4         | 1.31%   |
| Linux Mint 20      | 4         | 1.31%   |
| Fedora 36          | 4         | 1.31%   |
| Ubuntu 21.10       | 3         | 0.98%   |
| Pop!_OS 20.10      | 3         | 0.98%   |
| OpenMandriva 23.01 | 3         | 0.98%   |
| Manjaro            | 3         | 0.98%   |
| Linux Mint 20.3    | 3         | 0.98%   |
| Linux Mint 20.2    | 3         | 0.98%   |
| Kubuntu 20.04      | 3         | 0.98%   |
| Fedora 34          | 3         | 0.98%   |
| Fedora 33          | 3         | 0.98%   |
| Elementary 6.1     | 3         | 0.98%   |
| ArcoLinux Rolling  | 3         | 0.98%   |
| Xero Rolling       | 2         | 0.66%   |
| Ubuntu 20.10       | 2         | 0.66%   |
| Parrot 4.10        | 2         | 0.66%   |
| Linux Mint 20.1    | 2         | 0.66%   |
| Linux Mint 19.3    | 2         | 0.66%   |
| Kubuntu 22.04      | 2         | 0.66%   |
| Kali 2022.3        | 2         | 0.66%   |
| Kali 2022.2        | 2         | 0.66%   |
| Fedora 37          | 2         | 0.66%   |
| CentOS 7           | 2         | 0.66%   |
| Zorin 12           | 1         | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 149       | 50%     |
| Pop!_OS      | 15        | 5.03%   |
| Fedora       | 15        | 5.03%   |
| OpenMandriva | 14        | 4.7%    |
| Linux Mint   | 14        | 4.7%    |
| Debian       | 12        | 4.03%   |
| Zorin        | 10        | 3.36%   |
| Arch         | 9         | 3.02%   |
| Kubuntu      | 8         | 2.68%   |
| Kali         | 7         | 2.35%   |
| KDE neon     | 6         | 2.01%   |
| Manjaro      | 5         | 1.68%   |
| ArcoLinux    | 4         | 1.34%   |
| Ubuntu Unity | 3         | 1.01%   |
| Endless      | 3         | 1.01%   |
| Elementary   | 3         | 1.01%   |
| Xero         | 2         | 0.67%   |
| ROSA         | 2         | 0.67%   |
| Parrot       | 2         | 0.67%   |
| CentOS       | 2         | 0.67%   |
| Ubuntu MATE  | 1         | 0.34%   |
| Rocky Linux  | 1         | 0.34%   |
| RHEL         | 1         | 0.34%   |
| Oracle Linux | 1         | 0.34%   |
| Nobara       | 1         | 0.34%   |
| LMDE         | 1         | 0.34%   |
| LinuxFX      | 1         | 0.34%   |
| EndeavourOS  | 1         | 0.34%   |
| Deepin       | 1         | 0.34%   |
| Clear Linux  | 1         | 0.34%   |
| BlackPanther | 1         | 0.34%   |
| Alpine       | 1         | 0.34%   |
| AlmaLinux    | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 10        | 3.1%    |
| 5.15.0-46-generic        | 8         | 2.48%   |
| 5.16.7-desktop-1omv4003  | 7         | 2.17%   |
| 5.11.0-37-generic        | 6         | 1.86%   |
| 5.4.106-1-pve            | 5         | 1.55%   |
| 5.15.0-47-generic        | 5         | 1.55%   |
| 5.8.0-59-generic         | 4         | 1.24%   |
| 5.4.0-54-generic         | 4         | 1.24%   |
| 5.4.0-52-generic         | 4         | 1.24%   |
| 5.4.0-48-generic         | 4         | 1.24%   |
| 5.4.0-47-generic         | 4         | 1.24%   |
| 5.4.0-40-generic         | 4         | 1.24%   |
| 5.4.0-26-generic         | 4         | 1.24%   |
| 5.11.0-27-generic        | 4         | 1.24%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.24%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.93%   |
| 5.8.0-7630-generic       | 3         | 0.93%   |
| 5.8.0-44-generic         | 3         | 0.93%   |
| 5.8.0-41-generic         | 3         | 0.93%   |
| 5.4.0-7642-generic       | 3         | 0.93%   |
| 5.4.0-58-generic         | 3         | 0.93%   |
| 5.3.0-28-generic         | 3         | 0.93%   |
| 5.15.0-58-generic        | 3         | 0.93%   |
| 5.15.0-56-generic        | 3         | 0.93%   |
| 5.15.0-53-generic        | 3         | 0.93%   |
| 5.15.0-48-generic        | 3         | 0.93%   |
| 5.15.0-41-generic        | 3         | 0.93%   |
| 5.13.0-39-generic        | 3         | 0.93%   |
| 5.13.0-30-generic        | 3         | 0.93%   |
| 5.11.0-7620-generic      | 3         | 0.93%   |
| 5.11.0-43-generic        | 3         | 0.93%   |
| 5.11.0-41-generic        | 3         | 0.93%   |
| 5.11.0-40-generic        | 3         | 0.93%   |
| 5.11.0-38-generic        | 3         | 0.93%   |
| 5.0.0-23-generic         | 3         | 0.93%   |
| 6.0.8-300.fc37.x86_64    | 2         | 0.62%   |
| 5.9.8-200.fc33.x86_64    | 2         | 0.62%   |
| 5.8.0-48-generic         | 2         | 0.62%   |
| 5.8.0-43-generic         | 2         | 0.62%   |
| 5.7.0-2parrot2-amd64     | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 20.92%  |
| 5.15.0  | 34        | 11.11%  |
| 5.11.0  | 30        | 9.8%    |
| 5.8.0   | 23        | 7.52%   |
| 5.13.0  | 19        | 6.21%   |
| 4.15.0  | 16        | 5.23%   |
| 5.0.0   | 11        | 3.59%   |
| 5.3.0   | 7         | 2.29%   |
| 5.16.7  | 7         | 2.29%   |
| 5.4.106 | 5         | 1.63%   |
| 4.18.0  | 5         | 1.63%   |
| 6.1.1   | 4         | 1.31%   |
| 5.19.0  | 4         | 1.31%   |
| 5.11.22 | 4         | 1.31%   |
| 5.10.14 | 4         | 1.31%   |
| 5.10.0  | 4         | 1.31%   |
| 6.0.8   | 3         | 0.98%   |
| 5.9.8   | 2         | 0.65%   |
| 5.7.0   | 2         | 0.65%   |
| 5.19.9  | 2         | 0.65%   |
| 5.19.13 | 2         | 0.65%   |
| 5.18.0  | 2         | 0.65%   |
| 5.16.15 | 2         | 0.65%   |
| 5.13.4  | 2         | 0.65%   |
| 5.13.19 | 2         | 0.65%   |
| 3.10.0  | 2         | 0.65%   |
| 6.1.7   | 1         | 0.33%   |
| 6.0.6   | 1         | 0.33%   |
| 6.0.12  | 1         | 0.33%   |
| 5.9.10  | 1         | 0.33%   |
| 5.9.0   | 1         | 0.33%   |
| 5.8.3   | 1         | 0.33%   |
| 5.7.9   | 1         | 0.33%   |
| 5.7.19  | 1         | 0.33%   |
| 5.7.10  | 1         | 0.33%   |
| 5.6.0   | 1         | 0.33%   |
| 5.4.41  | 1         | 0.33%   |
| 5.4.36  | 1         | 0.33%   |
| 5.4.175 | 1         | 0.33%   |
| 5.4.17  | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 24.26%  |
| 5.15    | 36        | 11.8%   |
| 5.11    | 34        | 11.15%  |
| 5.13    | 27        | 8.85%   |
| 5.8     | 24        | 7.87%   |
| 4.15    | 16        | 5.25%   |
| 5.10    | 11        | 3.61%   |
| 5.0     | 11        | 3.61%   |
| 5.16    | 10        | 3.28%   |
| 5.19    | 9         | 2.95%   |
| 5.3     | 8         | 2.62%   |
| 4.18    | 6         | 1.97%   |
| 6.1     | 5         | 1.64%   |
| 6.0     | 5         | 1.64%   |
| 5.7     | 5         | 1.64%   |
| 5.18    | 5         | 1.64%   |
| 5.14    | 4         | 1.31%   |
| 5.9     | 3         | 0.98%   |
| 5.17    | 3         | 0.98%   |
| 3.10    | 3         | 0.98%   |
| 5.12    | 2         | 0.66%   |
| 5.6     | 1         | 0.33%   |
| 5.2     | 1         | 0.33%   |
| 4.9     | 1         | 0.33%   |
| 4.19    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 286       | 98.62%  |
| i686   | 4         | 1.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 186       | 62.42%  |
| Unknown    | 36        | 12.08%  |
| KDE5       | 29        | 9.73%   |
| X-Cinnamon | 12        | 4.03%   |
| XFCE       | 8         | 2.68%   |
| KDE        | 8         | 2.68%   |
| MATE       | 5         | 1.68%   |
| i3         | 4         | 1.34%   |
| Unity      | 3         | 1.01%   |
| Pantheon   | 3         | 1.01%   |
| KDE4       | 3         | 1.01%   |
| Deepin     | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 220       | 74.07%  |
| Wayland | 46        | 15.49%  |
| Unknown | 23        | 7.74%   |
| Tty     | 8         | 2.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 156       | 53.24%  |
| GDM3    | 48        | 16.38%  |
| GDM     | 46        | 15.7%   |
| SDDM    | 25        | 8.53%   |
| LightDM | 12        | 4.1%    |
| TDM     | 5         | 1.71%   |
| KDM     | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 251       | 85.67%  |
| Unknown | 23        | 7.85%   |
| en_GB   | 14        | 4.78%   |
| en_PK   | 3         | 1.02%   |
| ur_PK   | 1         | 0.34%   |
| C       | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 160       | 53.87%  |
| EFI  | 137       | 46.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 249       | 83.56%  |
| Overlay | 15        | 5.03%   |
| Btrfs   | 15        | 5.03%   |
| Zfs     | 7         | 2.35%   |
| Xfs     | 6         | 2.01%   |
| Unknown | 6         | 2.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 177       | 60.62%  |
| GPT     | 86        | 29.45%  |
| MBR     | 29        | 9.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 256       | 86.49%  |
| Yes       | 40        | 13.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 187       | 63.18%  |
| Yes       | 109       | 36.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 108       | 37.24%  |
| Dell                | 87        | 30%     |
| Lenovo              | 41        | 14.14%  |
| Gigabyte Technology | 10        | 3.45%   |
| ASUSTek Computer    | 10        | 3.45%   |
| Haier               | 6         | 2.07%   |
| Acer                | 5         | 1.72%   |
| Toshiba             | 4         | 1.38%   |
| Apple               | 4         | 1.38%   |
| Sony                | 3         | 1.03%   |
| Shuttle             | 2         | 0.69%   |
| Samsung Electronics | 2         | 0.69%   |
| Timi                | 1         | 0.34%   |
| Quanta              | 1         | 0.34%   |
| MSI                 | 1         | 0.34%   |
| MOTION              | 1         | 0.34%   |
| Microsoft           | 1         | 0.34%   |
| Fujitsu             | 1         | 0.34%   |
| AMI                 | 1         | 0.34%   |
| Unknown             | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| HP ProBook 450 G7                | 5         | 1.72%   |
| HP EliteBook 8470p               | 5         | 1.72%   |
| HP EliteBook 840 G3              | 5         | 1.72%   |
| Haier Y11C                       | 4         | 1.38%   |
| Dell Precision WorkStation T7500 | 4         | 1.38%   |
| Dell Latitude E7450              | 4         | 1.38%   |
| Dell Latitude E6420              | 4         | 1.38%   |
| Unknown                          | 4         | 1.38%   |
| HP ProBook 450 G5                | 3         | 1.03%   |
| HP EliteBook 840 G2              | 3         | 1.03%   |
| Dell Precision WorkStation T3500 | 3         | 1.03%   |
| Shuttle DS81D                    | 2         | 0.69%   |
| Lenovo ThinkBook 15-IML 20RW     | 2         | 0.69%   |
| Lenovo ThinkBook 15-IIL 20SM     | 2         | 0.69%   |
| Lenovo ThinkBook 15 G2 ITL 20VE  | 2         | 0.69%   |
| HP ZBook 15 G3                   | 2         | 0.69%   |
| HP ProLiant DL380p Gen8          | 2         | 0.69%   |
| HP ProDesk 600 G1 SFF            | 2         | 0.69%   |
| HP ProDesk 400 G7 Microtower PC  | 2         | 0.69%   |
| HP ProBook 450 G3                | 2         | 0.69%   |
| HP ProBook 440 G7                | 2         | 0.69%   |
| HP Pavilion Notebook             | 2         | 0.69%   |
| HP Pavilion dv6                  | 2         | 0.69%   |
| HP ENVY x360 m6 Convertible      | 2         | 0.69%   |
| HP EliteBook Folio 9470m         | 2         | 0.69%   |
| HP EliteBook 8440p               | 2         | 0.69%   |
| HP EliteBook 840 G1              | 2         | 0.69%   |
| HP EliteBook 6930p               | 2         | 0.69%   |
| HP Compaq 8100 Elite SFF PC      | 2         | 0.69%   |
| HP 650                           | 2         | 0.69%   |
| Haier Y11B                       | 2         | 0.69%   |
| Gigabyte Z590 UD AC              | 2         | 0.69%   |
| Gigabyte Q87M-D2H                | 2         | 0.69%   |
| Gigabyte A520M S2H               | 2         | 0.69%   |
| Dell XPS 630i                    | 2         | 0.69%   |
| Dell Vostro 430                  | 2         | 0.69%   |
| Dell Vostro 14-3468              | 2         | 0.69%   |
| Dell Precision WorkStation 490   | 2         | 0.69%   |
| Dell OptiPlex 755                | 2         | 0.69%   |
| Dell Latitude E6440              | 2         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 34        | 11.72%  |
| HP EliteBook       | 29        | 10%     |
| HP ProBook         | 23        | 7.93%   |
| Lenovo ThinkPad    | 21        | 7.24%   |
| Dell Inspiron      | 20        | 6.9%    |
| HP Pavilion        | 12        | 4.14%   |
| Dell Precision     | 12        | 4.14%   |
| HP Compaq          | 9         | 3.1%    |
| Dell OptiPlex      | 9         | 3.1%    |
| Dell Vostro        | 8         | 2.76%   |
| HP Laptop          | 7         | 2.41%   |
| Lenovo ThinkBook   | 6         | 2.07%   |
| HP ProDesk         | 6         | 2.07%   |
| HP ENVY            | 6         | 2.07%   |
| Lenovo ThinkCentre | 5         | 1.72%   |
| Haier Y11C         | 4         | 1.38%   |
| Unknown            | 4         | 1.38%   |
| Lenovo IdeaPad     | 3         | 1.03%   |
| HP ProLiant        | 3         | 1.03%   |
| Acer Aspire        | 3         | 1.03%   |
| Toshiba Satellite  | 2         | 0.69%   |
| Toshiba PORTEGE    | 2         | 0.69%   |
| Shuttle DS81D      | 2         | 0.69%   |
| HP ZBook           | 2         | 0.69%   |
| HP 650             | 2         | 0.69%   |
| Haier Y11B         | 2         | 0.69%   |
| Gigabyte Z590      | 2         | 0.69%   |
| Gigabyte Q87M-D2H  | 2         | 0.69%   |
| Gigabyte A520M     | 2         | 0.69%   |
| Dell XPS           | 2         | 0.69%   |
| ASUS VivoBook      | 2         | 0.69%   |
| ASUS TUF           | 2         | 0.69%   |
| Timi TM1613        | 1         | 0.34%   |
| Sony VPCEA26FG     | 1         | 0.34%   |
| Sony VPCCB490X     | 1         | 0.34%   |
| Sony SVE15126CXS   | 1         | 0.34%   |
| Samsung QX311      | 1         | 0.34%   |
| Samsung 940Z5L     | 1         | 0.34%   |
| Quanta TouchSmart  | 1         | 0.34%   |
| MSI MS-7D09        | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 34        | 11.72%  |
| 2020    | 26        | 8.97%   |
| 2019    | 26        | 8.97%   |
| 2012    | 25        | 8.62%   |
| 2016    | 22        | 7.59%   |
| 2014    | 22        | 7.59%   |
| 2013    | 21        | 7.24%   |
| 2010    | 19        | 6.55%   |
| 2018    | 18        | 6.21%   |
| 2017    | 18        | 6.21%   |
| 2015    | 16        | 5.52%   |
| 2021    | 12        | 4.14%   |
| 2009    | 10        | 3.45%   |
| 2008    | 10        | 3.45%   |
| 2007    | 5         | 1.72%   |
| 2006    | 4         | 1.38%   |
| 2022    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 203       | 70%     |
| Desktop     | 73        | 25.17%  |
| Convertible | 8         | 2.76%   |
| Server      | 3         | 1.03%   |
| Tablet      | 2         | 0.69%   |
| Mini pc     | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 276       | 94.85%  |
| Enabled  | 15        | 5.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 290       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 87        | 29.79%  |
| 16.01-24.0      | 63        | 21.58%  |
| 3.01-4.0        | 58        | 19.86%  |
| 8.01-16.0       | 52        | 17.81%  |
| 32.01-64.0      | 16        | 5.48%   |
| 64.01-256.0     | 7         | 2.4%    |
| 1.01-2.0        | 5         | 1.71%   |
| 24.01-32.0      | 3         | 1.03%   |
| More than 256.0 | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 104       | 33.02%  |
| 2.01-3.0    | 99        | 31.43%  |
| 4.01-8.0    | 43        | 13.65%  |
| 3.01-4.0    | 43        | 13.65%  |
| 8.01-16.0   | 15        | 4.76%   |
| 0.51-1.0    | 6         | 1.9%    |
| 16.01-24.0  | 2         | 0.63%   |
| 32.01-64.0  | 1         | 0.32%   |
| 64.01-256.0 | 1         | 0.32%   |
| Unknown     | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 64.21%  |
| 2      | 74        | 24.75%  |
| 3      | 15        | 5.02%   |
| 6      | 5         | 1.67%   |
| 4      | 4         | 1.34%   |
| 5      | 3         | 1%      |
| 13     | 1         | 0.33%   |
| 11     | 1         | 0.33%   |
| 10     | 1         | 0.33%   |
| 9      | 1         | 0.33%   |
| 8      | 1         | 0.33%   |
| 0      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 199       | 68.38%  |
| Yes       | 92        | 31.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 91.72%  |
| No        | 24        | 8.28%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 86.64%  |
| No        | 39        | 13.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 61.28%  |
| No        | 115       | 38.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Pakistan | 290       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lahore                         | 98        | 33%     |
| Karachi                        | 64        | 21.55%  |
| Islamabad                      | 50        | 16.84%  |
| Rawalpindi                     | 19        | 6.4%    |
| Multan                         | 8         | 2.69%   |
| Mirpur                         | 7         | 2.36%   |
| Faisalabad                     | 7         | 2.36%   |
| Peshawar                       | 5         | 1.68%   |
| Jhelum                         | 3         | 1.01%   |
| Bahawalpur                     | 3         | 1.01%   |
| Abbottabad                     | 3         | 1.01%   |
| Sialkot                        | 2         | 0.67%   |
| Sargodha                       | 2         | 0.67%   |
| Kamoke                         | 2         | 0.67%   |
| Hyderabad                      | 2         | 0.67%   |
| Dina                           | 2         | 0.67%   |
| Vehari                         | 1         | 0.34%   |
| Topi                           | 1         | 0.34%   |
| Tando Allahyar                 | 1         | 0.34%   |
| Sheikhupura                    | 1         | 0.34%   |
| Sahiwal                        | 1         | 0.34%   |
| Rahim Yar Khan                 | 1         | 0.34%   |
| Pindi Gheb                     | 1         | 0.34%   |
| Mardan                         | 1         | 0.34%   |
| Layari                         | 1         | 0.34%   |
| Larkana                        | 1         | 0.34%   |
| Kohat                          | 1         | 0.34%   |
| Khanewal                       | 1         | 0.34%   |
| Hazro City                     | 1         | 0.34%   |
| Hassan Abdal                   | 1         | 0.34%   |
| Gujranwala                     | 1         | 0.34%   |
| Ghotki                         | 1         | 0.34%   |
| Daska Kalan                    | 1         | 0.34%   |
| Dadu                           | 1         | 0.34%   |
| Chak Five Hundred Seventy-five | 1         | 0.34%   |
| Burewala                       | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 71        | 115    | 17.11%  |
| WDC                          | 64        | 89     | 15.42%  |
| Samsung Electronics          | 55        | 65     | 13.25%  |
| Toshiba                      | 31        | 32     | 7.47%   |
| Hitachi                      | 21        | 28     | 5.06%   |
| Kingston                     | 17        | 19     | 4.1%    |
| Intel                        | 12        | 16     | 2.89%   |
| SanDisk                      | 11        | 12     | 2.65%   |
| Transcend                    | 9         | 9      | 2.17%   |
| HGST                         | 9         | 10     | 2.17%   |
| Unknown                      | 8         | 9      | 1.93%   |
| SK hynix                     | 8         | 10     | 1.93%   |
| Micron Technology            | 7         | 8      | 1.69%   |
| LITEON                       | 7         | 8      | 1.69%   |
| Hewlett-Packard              | 7         | 18     | 1.69%   |
| A-DATA Technology            | 7         | 7      | 1.69%   |
| Lexar                        | 6         | 8      | 1.45%   |
| HS-SSD-E100                  | 6         | 6      | 1.45%   |
| Hajaan                       | 6         | 9      | 1.45%   |
| Silicon Motion               | 5         | 5      | 1.2%    |
| LITEONIT                     | 5         | 8      | 1.2%    |
| KIOXIA                       | 4         | 4      | 0.96%   |
| Apple                        | 4         | 5      | 0.96%   |
| Maxtor                       | 3         | 3      | 0.72%   |
| LaCie                        | 3         | 3      | 0.72%   |
| Crucial                      | 3         | 3      | 0.72%   |
| China                        | 3         | 4      | 0.72%   |
| Fujitsu                      | 2         | 2      | 0.48%   |
| ZTE                          | 1         | 1      | 0.24%   |
| Vaseky                       | 1         | 1      | 0.24%   |
| Toshiba America Info Systems | 1         | 1      | 0.24%   |
| Team                         | 1         | 1      | 0.24%   |
| SPCC                         | 1         | 1      | 0.24%   |
| PNY                          | 1         | 2      | 0.24%   |
| Phison                       | 1         | 2      | 0.24%   |
| PHD 3.0                      | 1         | 1      | 0.24%   |
| Netac                        | 1         | 1      | 0.24%   |
| MARSHAL                      | 1         | 1      | 0.24%   |
| Kingsand                     | 1         | 1      | 0.24%   |
| KingFast                     | 1         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST3000NXCLAR3000 3TB          | 7         | 1.53%   |
| WDC WD10SPZX-60Z10T0 1TB              | 6         | 1.31%   |
| HP MB2000EBZQC 2TB                    | 6         | 1.31%   |
| Hajaan SSD 256G                       | 6         | 1.31%   |
| Toshiba MQ04ABF100 1TB                | 5         | 1.09%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 1.09%   |
| Samsung SSD PM830 2.5 7mm 256GB       | 5         | 1.09%   |
| Toshiba MQ01ABF050 500GB              | 4         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 0.87%   |
| Samsung MZALQ512HALU-000L1 512GB      | 4         | 0.87%   |
| Lexar 256GB SSD                       | 4         | 0.87%   |
| WDC WD10SPZX-75Z10T3 1TB              | 3         | 0.66%   |
| WDC PC SN530 NVMe 256GB               | 3         | 0.66%   |
| Toshiba MQ01ACF050 500GB              | 3         | 0.66%   |
| Silicon Motion NVMe SSD Drive 512GB   | 3         | 0.66%   |
| Seagate ST8000DM004-2CX188 8TB        | 3         | 0.66%   |
| Seagate ST6000NM0024 6TB              | 3         | 0.66%   |
| Seagate ST500LM000-1EJ162 500GB       | 3         | 0.66%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 0.66%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD  | 3         | 0.66%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 3         | 0.66%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB     | 3         | 0.66%   |
| LaCie Rugged USB-C 1TB                | 3         | 0.66%   |
| Intel SSDSA2M080G2GN 80GB             | 3         | 0.66%   |
| HS-SSD-E100 128G                      | 3         | 0.66%   |
| Hitachi HTS545032B9A300 320GB         | 3         | 0.66%   |
| WDC WD5002ABYS-02B1B0 500GB           | 2         | 0.44%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 0.44%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2         | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2         | 0.44%   |
| WDC WD10SPZX-24Z10 1TB                | 2         | 0.44%   |
| Transcend TS512GMTE110S 512GB         | 2         | 0.44%   |
| Transcend TS256GMTS830S 256GB SSD     | 2         | 0.44%   |
| Transcend TS120GSSD220S 120GB         | 2         | 0.44%   |
| Toshiba MQ01ABD100 1TB                | 2         | 0.44%   |
| Toshiba MQ01ABD050 500GB              | 2         | 0.44%   |
| SK hynix SC300 M.2 2280 256GB SSD     | 2         | 0.44%   |
| Seagate ST9320423AS 320GB             | 2         | 0.44%   |
| Seagate ST9250315AS 250GB             | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 115    | 35.32%  |
| WDC                 | 55        | 73     | 27.36%  |
| Toshiba             | 25        | 26     | 12.44%  |
| Hitachi             | 21        | 28     | 10.45%  |
| HGST                | 9         | 10     | 4.48%   |
| Hewlett-Packard     | 6         | 17     | 2.99%   |
| Samsung Electronics | 5         | 5      | 2.49%   |
| Maxtor              | 3         | 3      | 1.49%   |
| Fujitsu             | 2         | 2      | 1%      |
| Unknown             | 1         | 1      | 0.5%    |
| PHD 3.0             | 1         | 1      | 0.5%    |
| MARSHAL             | 1         | 1      | 0.5%    |
| KESU                | 1         | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 39     | 25.55%  |
| Kingston            | 12        | 14     | 8.76%   |
| SanDisk             | 8         | 8      | 5.84%   |
| SK hynix            | 7         | 9      | 5.11%   |
| LITEON              | 7         | 8      | 5.11%   |
| WDC                 | 6         | 9      | 4.38%   |
| Lexar               | 6         | 8      | 4.38%   |
| Intel               | 6         | 7      | 4.38%   |
| Hajaan              | 6         | 9      | 4.38%   |
| A-DATA Technology   | 6         | 6      | 4.38%   |
| Transcend           | 5         | 5      | 3.65%   |
| Micron Technology   | 5         | 6      | 3.65%   |
| LITEONIT            | 5         | 8      | 3.65%   |
| Toshiba             | 4         | 4      | 2.92%   |
| Crucial             | 3         | 3      | 2.19%   |
| China               | 3         | 4      | 2.19%   |
| Apple               | 2         | 2      | 1.46%   |
| Vaseky              | 1         | 1      | 0.73%   |
| Team                | 1         | 1      | 0.73%   |
| SPCC                | 1         | 1      | 0.73%   |
| PNY                 | 1         | 2      | 0.73%   |
| Netac               | 1         | 1      | 0.73%   |
| HS-SSD-E100         | 1         | 1      | 0.73%   |
| Hewlett-Packard     | 1         | 1      | 0.73%   |
| Gritronix           | 1         | 1      | 0.73%   |
| Gigabyte Technology | 1         | 2      | 0.73%   |
| Biostar             | 1         | 1      | 0.73%   |
| Apacer              | 1         | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 167       | 283    | 46.65%  |
| SSD     | 113       | 162    | 31.56%  |
| NVMe    | 58        | 72     | 16.2%   |
| Unknown | 15        | 20     | 4.19%   |
| MMC     | 5         | 6      | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 240       | 437    | 75.71%  |
| NVMe | 58        | 72     | 18.3%   |
| SAS  | 14        | 28     | 4.42%   |
| MMC  | 5         | 6      | 1.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 184       | 294    | 64.79%  |
| 0.51-1.0   | 74        | 80     | 26.06%  |
| 1.01-2.0   | 13        | 37     | 4.58%   |
| 2.01-3.0   | 7         | 15     | 2.46%   |
| 4.01-10.0  | 4         | 17     | 1.41%   |
| 3.01-4.0   | 2         | 2      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 108       | 35.41%  |
| 251-500        | 67        | 21.97%  |
| 51-100         | 50        | 16.39%  |
| 501-1000       | 28        | 9.18%   |
| 1-20           | 18        | 5.9%    |
| 21-50          | 13        | 4.26%   |
| 1001-2000      | 10        | 3.28%   |
| Unknown        | 8         | 2.62%   |
| More than 3000 | 2         | 0.66%   |
| 2001-3000      | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 128       | 41.16%  |
| 21-50     | 78        | 25.08%  |
| 101-250   | 37        | 11.9%   |
| 51-100    | 35        | 11.25%  |
| 251-500   | 14        | 4.5%    |
| 501-1000  | 10        | 3.22%   |
| Unknown   | 8         | 2.57%   |
| 1001-2000 | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 5.56%   |
| Seagate ST2000DM008-2FR1                      | 2         | 2      | 5.56%   |
| Hewlett-Packard MB2000EBZQC 2TB               | 2         | 3      | 5.56%   |
| Crucial CT525MX300SSD1 528GB                  | 2         | 2      | 5.56%   |
| WDC WD5000AAKX-75U6AA0 500GB                  | 1         | 1      | 2.78%   |
| WDC WD2500HHTZ-04N21V0 250GB                  | 1         | 1      | 2.78%   |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 2.78%   |
| WDC WD2500AAKS-00F0A0 250GB                   | 1         | 1      | 2.78%   |
| WDC WD20EZRZ-00Z5HB0 2TB                      | 1         | 1      | 2.78%   |
| WDC WD1600AAJS-22L7A0 160GB                   | 1         | 1      | 2.78%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 2.78%   |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 2.78%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 2.78%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 2.78%   |
| Seagate ST3500418AS 500GB                     | 1         | 1      | 2.78%   |
| Seagate ST3160215AS 160GB                     | 1         | 1      | 2.78%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 2      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 2.78%   |
| Seagate ST1000DM010-2EP102 1TB                | 1         | 1      | 2.78%   |
| Samsung Electronics SP2004C 200GB             | 1         | 1      | 2.78%   |
| Samsung Electronics HD080HJ 80GB              | 1         | 1      | 2.78%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 2.78%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 2.78%   |
| Intel SSDSA2M080G2GN 80GB                     | 1         | 1      | 2.78%   |
| Hitachi HUA723020ALA640 2TB                   | 1         | 2      | 2.78%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 2.78%   |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 2.78%   |
| Hitachi HDS721680PLA380 80GB                  | 1         | 1      | 2.78%   |
| Hitachi HDS721050CLA660 500GB                 | 1         | 1      | 2.78%   |
| Gritronix M.2 2280 256GB SSD                  | 1         | 1      | 2.78%   |
| China SSD 240GB                               | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 25.71%  |
| Seagate             | 8         | 10     | 22.86%  |
| Hitachi             | 5         | 6      | 14.29%  |
| Samsung Electronics | 2         | 2      | 5.71%   |
| Intel               | 2         | 2      | 5.71%   |
| Hewlett-Packard     | 2         | 3      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| Toshiba             | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| Gritronix           | 1         | 1      | 2.86%   |
| China               | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 33.33%  |
| Seagate             | 8         | 10     | 29.63%  |
| Hitachi             | 5         | 6      | 18.52%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Hewlett-Packard     | 2         | 3      | 7.41%   |
| Toshiba             | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 32     | 71.43%  |
| SSD  | 8         | 8      | 28.57%  |

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
| Detected | 193       | 321    | 62.06%  |
| Works    | 91        | 182    | 29.26%  |
| Malfunc  | 27        | 40     | 8.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 253       | 74.19%  |
| Samsung Electronics          | 18        | 5.28%   |
| AMD                          | 16        | 4.69%   |
| SanDisk                      | 8         | 2.35%   |
| LSI Logic / Symbios Logic    | 8         | 2.35%   |
| Silicon Motion               | 6         | 1.76%   |
| KIOXIA                       | 6         | 1.76%   |
| Kingston Technology Company  | 5         | 1.47%   |
| Transcend                    | 3         | 0.88%   |
| Hewlett-Packard              | 3         | 0.88%   |
| Toshiba America Info Systems | 2         | 0.59%   |
| Nvidia                       | 2         | 0.59%   |
| Micron Technology            | 2         | 0.59%   |
| Apple                        | 2         | 0.59%   |
| SK hynix                     | 1         | 0.29%   |
| Realtek Semiconductor        | 1         | 0.29%   |
| Phison Electronics           | 1         | 0.29%   |
| Marvell Technology Group     | 1         | 0.29%   |
| Broadcom / LSI               | 1         | 0.29%   |
| ASMedia Technology           | 1         | 0.29%   |
| Adaptec                      | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 40        | 9.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 5.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 4.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 3.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 3.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 3.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 2.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 2.49%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 2.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.24%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 8         | 2%      |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 2%      |
| Samsung NVMe SSD Controller 980                                                | 7         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 1.5%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 6         | 1.5%    |
| Intel SATA Controller [RAID mode]                                              | 5         | 1.25%   |
| Intel Non-Volatile memory controller                                           | 5         | 1.25%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5         | 1.25%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1%      |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1%      |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1%      |
| Transcend Non-Volatile memory controller                                       | 3         | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.75%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 3         | 0.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.75%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3         | 0.75%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 3         | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 3         | 0.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 215       | 57.95%  |
| NVMe | 58        | 15.63%  |
| RAID | 46        | 12.4%   |
| IDE  | 37        | 9.97%   |
| SCSI | 9         | 2.43%   |
| SAS  | 6         | 1.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 274       | 94.48%  |
| AMD    | 16        | 5.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 3.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 3.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 8         | 2.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 2.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 2.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 2.07%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 2.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 2.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 2.07%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 5         | 1.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 1.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 5         | 1.72%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 4         | 1.38%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4         | 1.38%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 3         | 1.03%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.03%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.03%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3         | 1.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.03%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3         | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 1.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 3         | 1.03%   |
| Intel Xeon CPU X5660 @ 2.80GHz          | 2         | 0.69%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 2         | 0.69%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 2         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.69%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 0.69%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 0.69%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.69%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 2         | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 102       | 35.17%  |
| Intel Core i7        | 76        | 26.21%  |
| Other                | 22        | 7.59%   |
| Intel Xeon           | 19        | 6.55%   |
| Intel Core i3        | 16        | 5.52%   |
| Intel Core 2 Duo     | 15        | 5.17%   |
| Intel Celeron        | 6         | 2.07%   |
| AMD Ryzen 7          | 5         | 1.72%   |
| Intel Core m3        | 4         | 1.38%   |
| AMD Ryzen 5          | 4         | 1.38%   |
| Intel Pentium        | 3         | 1.03%   |
| Intel Core M         | 2         | 0.69%   |
| Intel Core 2 Quad    | 2         | 0.69%   |
| Intel Core 2         | 2         | 0.69%   |
| Intel Atom           | 2         | 0.69%   |
| AMD Athlon II X2     | 2         | 0.69%   |
| Intel Pentium Dual   | 1         | 0.34%   |
| Intel Genuine        | 1         | 0.34%   |
| Intel Core 2 Extreme | 1         | 0.34%   |
| AMD Ryzen 3          | 1         | 0.34%   |
| AMD E                | 1         | 0.34%   |
| AMD A6               | 1         | 0.34%   |
| AMD A4               | 1         | 0.34%   |
| AMD A12              | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 150       | 51.55%  |
| 4      | 104       | 35.74%  |
| 6      | 16        | 5.5%    |
| 8      | 14        | 4.81%   |
| 12     | 3         | 1.03%   |
| 16     | 2         | 0.69%   |
| 10     | 1         | 0.34%   |
| 1      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 281       | 96.56%  |
| 2      | 10        | 3.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 222       | 76.55%  |
| 1      | 68        | 23.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 287       | 98.63%  |
| Unknown        | 3         | 1.03%   |
| 32-bit         | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 22.07%  |
| 0x206a7    | 22        | 7.36%   |
| 0x806ec    | 17        | 5.69%   |
| 0x306a9    | 17        | 5.69%   |
| 0x806c1    | 16        | 5.35%   |
| 0x406e3    | 15        | 5.02%   |
| 0x806e9    | 14        | 4.68%   |
| 0x306c3    | 13        | 4.35%   |
| 0x306d4    | 12        | 4.01%   |
| 0x40651    | 11        | 3.68%   |
| 0x1067a    | 11        | 3.68%   |
| 0x806ea    | 10        | 3.34%   |
| 0x20655    | 10        | 3.34%   |
| 0x206c2    | 6         | 2.01%   |
| 0x706e5    | 5         | 1.67%   |
| 0x206d7    | 5         | 1.67%   |
| 0x6f6      | 4         | 1.34%   |
| 0x506e3    | 4         | 1.34%   |
| 0xa0655    | 3         | 1%      |
| 0x906ea    | 3         | 1%      |
| 0x30678    | 3         | 1%      |
| 0x10676    | 3         | 1%      |
| 0xa0652    | 2         | 0.67%   |
| 0x6fd      | 2         | 0.67%   |
| 0x20652    | 2         | 0.67%   |
| 0x106a5    | 2         | 0.67%   |
| 0x08701021 | 2         | 0.67%   |
| 0xa0671    | 1         | 0.33%   |
| 0xa0660    | 1         | 0.33%   |
| 0x906e9    | 1         | 0.33%   |
| 0x906a4    | 1         | 0.33%   |
| 0x806eb    | 1         | 0.33%   |
| 0x706a1    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x406c4    | 1         | 0.33%   |
| 0x40661    | 1         | 0.33%   |
| 0x106e5    | 1         | 0.33%   |
| 0x08608103 | 1         | 0.33%   |
| 0x08600106 | 1         | 0.33%   |
| 0x08600104 | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 56        | 19.31%  |
| Haswell          | 33        | 11.38%  |
| SandyBridge      | 31        | 10.69%  |
| Skylake          | 24        | 8.28%   |
| IvyBridge        | 24        | 8.28%   |
| Westmere         | 22        | 7.59%   |
| TigerLake        | 19        | 6.55%   |
| Penryn           | 16        | 5.52%   |
| Broadwell        | 16        | 5.52%   |
| Core             | 7         | 2.41%   |
| Zen 2            | 6         | 2.07%   |
| CometLake        | 6         | 2.07%   |
| Silvermont       | 5         | 1.72%   |
| Nehalem          | 5         | 1.72%   |
| IceLake          | 5         | 1.72%   |
| Unknown          | 3         | 1.03%   |
| Zen+             | 2         | 0.69%   |
| K10              | 2         | 0.69%   |
| Zen              | 1         | 0.34%   |
| P6               | 1         | 0.34%   |
| K10 Llano        | 1         | 0.34%   |
| Jaguar           | 1         | 0.34%   |
| Goldmont plus    | 1         | 0.34%   |
| Excavator        | 1         | 0.34%   |
| Bobcat           | 1         | 0.34%   |
| Alderlake Hybrid | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 225       | 65.6%   |
| Nvidia                     | 65        | 18.95%  |
| AMD                        | 51        | 14.87%  |
| Matrox Electronics Systems | 2         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 19        | 5.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 18        | 5.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 17        | 4.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 17        | 4.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 16        | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 15        | 4.26%   |
| Intel HD Graphics 5500                                                                | 14        | 3.98%   |
| Intel UHD Graphics 620                                                                | 13        | 3.69%   |
| Intel HD Graphics 620                                                                 | 10        | 2.84%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 2.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 7         | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 6         | 1.7%    |
| Nvidia GT218 [GeForce 210]                                                            | 5         | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 1.42%   |
| Intel HD Graphics 530                                                                 | 5         | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 5         | 1.42%   |
| Nvidia GP108M [GeForce MX230]                                                         | 4         | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 4         | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.14%   |
| Intel HD Graphics 615                                                                 | 4         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 4         | 1.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 3         | 0.85%   |
| AMD Renoir                                                                            | 3         | 0.85%   |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 0.57%   |
| Nvidia GT218M [NVS 3100M]                                                             | 2         | 0.57%   |
| Nvidia GT218 [GeForce 310]                                                            | 2         | 0.57%   |
| Nvidia GP108M [GeForce MX250]                                                         | 2         | 0.57%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 2         | 0.57%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.57%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 2         | 0.57%   |
| Nvidia GF119M [NVS 4200M]                                                             | 2         | 0.57%   |
| Nvidia GF119 [GeForce GT 610]                                                         | 2         | 0.57%   |
| Nvidia GF108 [GeForce GT 730]                                                         | 2         | 0.57%   |
| Matrox Electronics Systems MGA G200EH                                                 | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 175       | 59.73%  |
| 1 x Nvidia     | 32        | 10.92%  |
| Intel + Nvidia | 30        | 10.24%  |
| 1 x AMD        | 28        | 9.56%   |
| Intel + AMD    | 19        | 6.48%   |
| Other          | 2         | 0.68%   |
| 2 x AMD        | 2         | 0.68%   |
| 1 x Matrox     | 2         | 0.68%   |
| AMD + Nvidia   | 2         | 0.68%   |
| 2 x Nvidia     | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 251       | 84.8%   |
| Proprietary | 34        | 11.49%  |
| Unknown     | 11        | 3.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 212       | 71.62%  |
| 1.01-2.0   | 37        | 12.5%   |
| 0.01-0.5   | 20        | 6.76%   |
| 3.01-4.0   | 11        | 3.72%   |
| 0.51-1.0   | 11        | 3.72%   |
| 5.01-6.0   | 2         | 0.68%   |
| 8.01-16.0  | 2         | 0.68%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 55        | 19.64%  |
| AU Optronics            | 42        | 15%     |
| Chimei Innolux          | 38        | 13.57%  |
| BOE                     | 29        | 10.36%  |
| Samsung Electronics     | 23        | 8.21%   |
| Dell                    | 20        | 7.14%   |
| Hewlett-Packard         | 19        | 6.79%   |
| Lenovo                  | 5         | 1.79%   |
| Chi Mei Optoelectronics | 5         | 1.79%   |
| Acer                    | 5         | 1.79%   |
| Unknown                 | 4         | 1.43%   |
| Apple                   | 4         | 1.43%   |
| Sharp                   | 3         | 1.07%   |
| KDC                     | 3         | 1.07%   |
| Goldstar                | 3         | 1.07%   |
| Sony                    | 2         | 0.71%   |
| NEC Computers           | 2         | 0.71%   |
| LGD                     | 2         | 0.71%   |
| LG Philips              | 2         | 0.71%   |
| InfoVision              | 2         | 0.71%   |
| Hitachi                 | 2         | 0.71%   |
| BenQ                    | 2         | 0.71%   |
| ViewSonic               | 1         | 0.36%   |
| Planar                  | 1         | 0.36%   |
| Philips                 | 1         | 0.36%   |
| PANDA                   | 1         | 0.36%   |
| LPL                     | 1         | 0.36%   |
| LED                     | 1         | 0.36%   |
| HannStar                | 1         | 0.36%   |
| DENON                   | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 6         | 2.11%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 5         | 1.76%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch          | 4         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 4         | 1.41%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch          | 3         | 1.06%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                 | 3         | 1.06%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch            | 3         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 3         | 1.06%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 3         | 1.06%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 2         | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2         | 0.7%    |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch    | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch | 2         | 0.7%    |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch         | 2         | 0.7%    |
| LG Display LCD Monitor LGD052F 1920x1080 344x194mm 15.5-inch         | 2         | 0.7%    |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch         | 2         | 0.7%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.7%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 0.7%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 2         | 0.7%    |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch          | 2         | 0.7%    |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch             | 2         | 0.7%    |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                    | 2         | 0.7%    |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                    | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch     | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch      | 2         | 0.7%    |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                | 2         | 0.7%    |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                | 2         | 0.7%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch        | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO3191 1366x768 340x190mm 15.3-inch        | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch        | 2         | 0.7%    |
| ViewSonic LCD Monitor VA2451 SERIES 1920x1080                        | 1         | 0.35%   |
| Unknown LCD Monitor ITE DP2VGA V221 1680x1050                        | 1         | 0.35%   |
| Unknown LCD Monitor DellSP2008WFP 1680x1050                          | 1         | 0.35%   |
| Sony TV SNYAC03 1360x768                                             | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 42.07%  |
| 1366x768 (WXGA)    | 84        | 31%     |
| 1600x900 (HD+)     | 12        | 4.43%   |
| 1680x1050 (WSXGA+) | 10        | 3.69%   |
| 3840x2160 (4K)     | 9         | 3.32%   |
| 1280x1024 (SXGA)   | 8         | 2.95%   |
| 1280x800 (WXGA)    | 6         | 2.21%   |
| 1920x1200 (WUXGA)  | 5         | 1.85%   |
| 1440x900 (WXGA+)   | 4         | 1.48%   |
| 1024x768 (XGA)     | 4         | 1.48%   |
| 3440x1440          | 3         | 1.11%   |
| 2880x1800          | 2         | 0.74%   |
| 2288x1287          | 2         | 0.74%   |
| Unknown            | 2         | 0.74%   |
| 3640x1920          | 1         | 0.37%   |
| 3520x1080          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 2560x1440 (QHD)    | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 1360x768           | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 103       | 37.18%  |
| 14      | 42        | 15.16%  |
| 13      | 34        | 12.27%  |
| 17      | 14        | 5.05%   |
| 21      | 13        | 4.69%   |
| 24      | 12        | 4.33%   |
| Unknown | 11        | 3.97%   |
| 23      | 8         | 2.89%   |
| 12      | 7         | 2.53%   |
| 19      | 6         | 2.17%   |
| 22      | 5         | 1.81%   |
| 11      | 5         | 1.81%   |
| 27      | 4         | 1.44%   |
| 142     | 2         | 0.72%   |
| 72      | 2         | 0.72%   |
| 40      | 2         | 0.72%   |
| 18      | 2         | 0.72%   |
| 84      | 1         | 0.36%   |
| 31      | 1         | 0.36%   |
| 26      | 1         | 0.36%   |
| 20      | 1         | 0.36%   |
| 10      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 161       | 58.55%  |
| 201-300        | 32        | 11.64%  |
| 501-600        | 24        | 8.73%   |
| 401-500        | 23        | 8.36%   |
| 351-400        | 16        | 5.82%   |
| Unknown        | 11        | 4%      |
| 1501-2000      | 3         | 1.09%   |
| More than 2000 | 2         | 0.73%   |
| 801-900        | 2         | 0.73%   |
| 601-700        | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 212       | 80.92%  |
| 16/10   | 24        | 9.16%   |
| Unknown | 11        | 4.2%    |
| 5/4     | 8         | 3.05%   |
| 4/3     | 4         | 1.53%   |
| 1.00    | 2         | 0.76%   |
| 3/2     | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 36.96%  |
| 81-90          | 58        | 21.01%  |
| 201-250        | 31        | 11.23%  |
| 71-80          | 16        | 5.8%    |
| Unknown        | 11        | 3.99%   |
| 151-200        | 10        | 3.62%   |
| 121-130        | 8         | 2.9%    |
| 61-70          | 7         | 2.54%   |
| 141-150        | 6         | 2.17%   |
| More than 1000 | 5         | 1.81%   |
| 51-60          | 5         | 1.81%   |
| 301-350        | 4         | 1.45%   |
| 251-300        | 4         | 1.45%   |
| 91-100         | 3         | 1.09%   |
| 131-140        | 2         | 0.72%   |
| 501-1000       | 2         | 0.72%   |
| 351-500        | 1         | 0.36%   |
| 41-50          | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 101       | 37%     |
| 101-120       | 86        | 31.5%   |
| 51-100        | 55        | 20.15%  |
| Unknown       | 11        | 4.03%   |
| 161-240       | 9         | 3.3%    |
| More than 240 | 7         | 2.56%   |
| 1-50          | 4         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 250       | 85.03%  |
| 2     | 25        | 8.5%    |
| 0     | 18        | 6.12%   |
| 3     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 193       | 40.72%  |
| Realtek Semiconductor           | 137       | 28.9%   |
| Broadcom                        | 46        | 9.7%    |
| Qualcomm Atheros                | 26        | 5.49%   |
| Broadcom Limited                | 10        | 2.11%   |
| Ralink Technology               | 9         | 1.9%    |
| MediaTek                        | 7         | 1.48%   |
| Hewlett-Packard                 | 5         | 1.05%   |
| Sierra Wireless                 | 4         | 0.84%   |
| Marvell Technology Group        | 4         | 0.84%   |
| D-Link                          | 4         | 0.84%   |
| Samsung Electronics             | 3         | 0.63%   |
| Ralink                          | 3         | 0.63%   |
| Qualcomm Atheros Communications | 3         | 0.63%   |
| Huawei Technologies             | 3         | 0.63%   |
| ASIX Electronics                | 3         | 0.63%   |
| Xiaomi                          | 2         | 0.42%   |
| Nvidia                          | 2         | 0.42%   |
| Dell                            | 2         | 0.42%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.21%   |
| VIA Technologies                | 1         | 0.21%   |
| Spreadtrum Communications       | 1         | 0.21%   |
| Qualcomm                        | 1         | 0.21%   |
| QLogic                          | 1         | 0.21%   |
| OPPO Electronics                | 1         | 0.21%   |
| Emulex                          | 1         | 0.21%   |
| 3Com                            | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 91        | 15.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 32        | 5.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 17        | 2.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 16        | 2.79%   |
| Intel Wireless 7265                                                  | 15        | 2.61%   |
| Intel Wi-Fi 6 AX201                                                  | 15        | 2.61%   |
| Intel Wireless 3165                                                  | 12        | 2.09%   |
| Intel Ethernet Connection I217-LM                                    | 12        | 2.09%   |
| Intel Ethernet Connection (3) I218-LM                                | 12        | 2.09%   |
| Intel Wireless 8260                                                  | 11        | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 10        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 9         | 1.57%   |
| Ralink MT7601U Wireless Adapter                                      | 9         | 1.57%   |
| Intel Wireless 7260                                                  | 9         | 1.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                     | 9         | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7         | 1.22%   |
| Intel Ethernet Connection I219-LM                                    | 7         | 1.22%   |
| Intel Ethernet Connection I218-LM                                    | 7         | 1.22%   |
| Intel 82577LM Gigabit Network Connection                             | 7         | 1.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                 | 6         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 5         | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 0.87%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 0.87%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                             | 5         | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 5         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 4         | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 0.7%    |
| MediaTek File-CD Gadget                                              | 4         | 0.7%    |
| Intel Wireless 8265 / 8275                                           | 4         | 0.7%    |
| Intel Wireless 3160                                                  | 4         | 0.7%    |
| Intel Centrino Ultimate-N 6300                                       | 4         | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 0.7%    |
| Intel 82579V Gigabit Network Connection                              | 4         | 0.7%    |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                        | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 145       | 54.51%  |
| Realtek Semiconductor           | 39        | 14.66%  |
| Qualcomm Atheros                | 23        | 8.65%   |
| Broadcom                        | 22        | 8.27%   |
| Ralink Technology               | 9         | 3.38%   |
| Broadcom Limited                | 6         | 2.26%   |
| Sierra Wireless                 | 4         | 1.5%    |
| D-Link                          | 4         | 1.5%    |
| Ralink                          | 3         | 1.13%   |
| Qualcomm Atheros Communications | 3         | 1.13%   |
| MediaTek                        | 2         | 0.75%   |
| Marvell Technology Group        | 2         | 0.75%   |
| Hewlett-Packard                 | 2         | 0.75%   |
| Dell                            | 2         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 16        | 5.95%   |
| Intel Wireless 7265                                                  | 15        | 5.58%   |
| Intel Wi-Fi 6 AX201                                                  | 15        | 5.58%   |
| Intel Wireless 3165                                                  | 12        | 4.46%   |
| Intel Wireless 8260                                                  | 11        | 4.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 4.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 10        | 3.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 9         | 3.35%   |
| Ralink MT7601U Wireless Adapter                                      | 9         | 3.35%   |
| Intel Wireless 7260                                                  | 9         | 3.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7         | 2.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 1.86%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 1.86%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 1.86%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 4         | 1.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 1.49%   |
| Intel Wireless 8265 / 8275                                           | 4         | 1.49%   |
| Intel Wireless 3160                                                  | 4         | 1.49%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 1.49%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3         | 1.12%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.12%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.12%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 3         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 1.12%   |
| Sierra Wireless EM7345 4G LTE                                        | 2         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2         | 0.74%   |
| Intel Wireless-AC 9260                                               | 2         | 0.74%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 118       | 39.86%  |
| Realtek Semiconductor      | 116       | 39.19%  |
| Broadcom                   | 25        | 8.45%   |
| MediaTek                   | 5         | 1.69%   |
| Broadcom Limited           | 4         | 1.35%   |
| Samsung Electronics        | 3         | 1.01%   |
| Qualcomm Atheros           | 3         | 1.01%   |
| Huawei Technologies        | 3         | 1.01%   |
| ASIX Electronics           | 3         | 1.01%   |
| Xiaomi                     | 2         | 0.68%   |
| Nvidia                     | 2         | 0.68%   |
| Marvell Technology Group   | 2         | 0.68%   |
| Hewlett-Packard            | 2         | 0.68%   |
| ZTE WCDMA Technologies MSM | 1         | 0.34%   |
| VIA Technologies           | 1         | 0.34%   |
| Spreadtrum Communications  | 1         | 0.34%   |
| Qualcomm                   | 1         | 0.34%   |
| QLogic                     | 1         | 0.34%   |
| OPPO Electronics           | 1         | 0.34%   |
| Emulex                     | 1         | 0.34%   |
| 3Com                       | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91        | 29.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.59%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 3.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 3.95%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 2.96%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 2.3%    |
| Intel Ethernet Connection I218-LM                                 | 7         | 2.3%    |
| Intel 82577LM Gigabit Network Connection                          | 7         | 2.3%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 1.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 1.64%   |
| MediaTek File-CD Gadget                                           | 4         | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.99%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.99%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.99%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 3         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.99%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.66%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.66%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 2         | 0.66%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.66%   |
| Huawei E353/E3131                                                 | 2         | 0.66%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.33%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.33%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.33%   |
| Qualcomm FP3                                                      | 1         | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 266       | 51.15%  |
| WiFi     | 253       | 48.65%  |
| Modem    | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 210       | 73.17%  |
| Ethernet | 77        | 26.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 204       | 69.86%  |
| 1     | 72        | 24.66%  |
| 3     | 6         | 2.05%   |
| 4     | 5         | 1.71%   |
| 0     | 4         | 1.37%   |
| 8     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 276       | 94.52%  |
| Yes  | 16        | 5.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 55.98%  |
| Realtek Semiconductor           | 20        | 10.87%  |
| Qualcomm Atheros Communications | 16        | 8.7%    |
| Broadcom                        | 14        | 7.61%   |
| Cambridge Silicon Radio         | 12        | 6.52%   |
| Dell                            | 4         | 2.17%   |
| Ralink                          | 3         | 1.63%   |
| Foxconn / Hon Hai               | 3         | 1.63%   |
| IMC Networks                    | 2         | 1.09%   |
| Hewlett-Packard                 | 2         | 1.09%   |
| Apple                           | 2         | 1.09%   |
| Marvell Semiconductor           | 1         | 0.54%   |
| Lite-On Technology              | 1         | 0.54%   |
| AboCom Systems                  | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 52        | 28.26%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 11.41%  |
| Intel Bluetooth Device                                                              | 20        | 10.87%  |
| Realtek Bluetooth Radio                                                             | 12        | 6.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 6.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.89%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 3.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.26%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 2.72%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.09%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.09%   |
| Intel AX200 Bluetooth                                                               | 2         | 1.09%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.09%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.09%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.09%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.54%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.54%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.54%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.54%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.54%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.54%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.54%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.54%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.54%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.54%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.54%   |
| Broadcom HP Bluethunder                                                             | 1         | 0.54%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.54%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.54%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.54%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 266       | 75.57%  |
| Nvidia                 | 41        | 11.65%  |
| AMD                    | 30        | 8.52%   |
| Generalplus Technology | 5         | 1.42%   |
| Logitech               | 2         | 0.57%   |
| C-Media Electronics    | 2         | 0.57%   |
| Texas Instruments      | 1         | 0.28%   |
| Realtek Semiconductor  | 1         | 0.28%   |
| OPPO Electronics       | 1         | 0.28%   |
| FIFINE 683 Microphone  | 1         | 0.28%   |
| Creative Labs          | 1         | 0.28%   |
| Apple                  | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 46        | 11.17%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 6.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 5.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 4.61%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 4.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 4.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 3.88%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 3.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 3.64%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 3.64%   |
| Nvidia High Definition Audio Controller                                    | 10        | 2.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 2.43%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6         | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 0.97%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.97%   |
| Generalplus Technology USB Audio Device                                    | 4         | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3         | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.73%   |
| Nvidia MCP51 High Definition Audio                                         | 2         | 0.49%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.49%   |
| Logitech Headset H340                                                      | 2         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 31.11%  |
| SK hynix            | 50        | 27.78%  |
| Micron Technology   | 18        | 10%     |
| A-DATA Technology   | 11        | 6.11%   |
| Transcend           | 6         | 3.33%   |
| Kingston            | 6         | 3.33%   |
| Unknown             | 5         | 2.78%   |
| Crucial             | 5         | 2.78%   |
| Team                | 4         | 2.22%   |
| Elpida              | 4         | 2.22%   |
| Lexar               | 3         | 1.67%   |
| Unknown (2C0B)      | 2         | 1.11%   |
| Spectek             | 2         | 1.11%   |
| Nanya Technology    | 2         | 1.11%   |
| Unknown (768A)      | 1         | 0.56%   |
| TwinMOS             | 1         | 0.56%   |
| Toshiba-0098        | 1         | 0.56%   |
| Ramaxel Technology  | 1         | 0.56%   |
| Hikvision           | 1         | 0.56%   |
| Axiom               | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s            | 5         | 2.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 4         | 1.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 4         | 1.97%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 3         | 1.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.48%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s     | 3         | 1.48%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM 1333MT/s           | 3         | 1.48%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s      | 3         | 1.48%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s      | 3         | 1.48%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s         | 2         | 0.99%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 2         | 0.99%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s     | 2         | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.99%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.99%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s            | 2         | 0.99%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s            | 2         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 0.99%   |
| Samsung RAM M471A5143DB0-CPB 4096MB SODIMM DDR4 2133MT/s  | 2         | 0.99%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.99%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 0.99%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 2         | 0.99%   |
| Lexar RAM LD4AS016G-H2666G 16GB SODIMM DDR4 2667MT/s      | 2         | 0.99%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s               | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s                | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s              | 1         | 0.49%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s         | 1         | 0.49%   |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.49%   |
| TwinMOS RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 3200MT/s  | 1         | 0.49%   |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s             | 1         | 0.49%   |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s          | 1         | 0.49%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2400MT/s          | 1         | 0.49%   |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.49%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s     | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 64        | 47.06%  |
| DDR3   | 60        | 44.12%  |
| LPDDR3 | 4         | 2.94%   |
| SDRAM  | 3         | 2.21%   |
| LPDDR4 | 3         | 2.21%   |
| DDR2   | 1         | 0.74%   |
| DDR    | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 71.64%  |
| DIMM         | 31        | 23.13%  |
| Row Of Chips | 7         | 5.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 36.24%  |
| 4096  | 41        | 27.52%  |
| 16384 | 29        | 19.46%  |
| 2048  | 20        | 13.42%  |
| 32768 | 5         | 3.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 45        | 28.48%  |
| 2667  | 35        | 22.15%  |
| 3200  | 17        | 10.76%  |
| 2133  | 13        | 8.23%   |
| 1333  | 12        | 7.59%   |
| 2400  | 9         | 5.7%    |
| 1334  | 7         | 4.43%   |
| 1866  | 3         | 1.9%    |
| 1067  | 3         | 1.9%    |
| 4267  | 2         | 1.27%   |
| 1066  | 2         | 1.27%   |
| 8400  | 1         | 0.63%   |
| 4199  | 1         | 0.63%   |
| 3733  | 1         | 0.63%   |
| 3266  | 1         | 0.63%   |
| 2666  | 1         | 0.63%   |
| 2267  | 1         | 0.63%   |
| 2200  | 1         | 0.63%   |
| 2000  | 1         | 0.63%   |
| 1867  | 1         | 0.63%   |
| 800   | 1         | 0.63%   |

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
| Chicony Electronics                    | 57        | 28.36%  |
| Microdia                               | 24        | 11.94%  |
| Sunplus Innovation Technology          | 18        | 8.96%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 8.96%   |
| Realtek Semiconductor                  | 15        | 7.46%   |
| Lite-On Technology                     | 12        | 5.97%   |
| Suyin                                  | 7         | 3.48%   |
| Acer                                   | 7         | 3.48%   |
| IMC Networks                           | 6         | 2.99%   |
| Ricoh                                  | 5         | 2.49%   |
| Quanta                                 | 5         | 2.49%   |
| Syntek                                 | 4         | 1.99%   |
| Luxvisions Innotech Limited            | 4         | 1.99%   |
| Silicon Motion                         | 3         | 1.49%   |
| Apple                                  | 3         | 1.49%   |
| Z-Star Microelectronics                | 2         | 1%      |
| Logitech                               | 2         | 1%      |
| Samsung Electronics                    | 1         | 0.5%    |
| Primax Electronics                     | 1         | 0.5%    |
| Pixart Imaging                         | 1         | 0.5%    |
| OmniVision Technologies                | 1         | 0.5%    |
| Microsoft                              | 1         | 0.5%    |
| MacroSilicon                           | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| DigiTech                               | 1         | 0.5%    |
| Asuscom Network                        | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 12        | 5.91%   |
| Chicony HP HD Camera                                                       | 10        | 4.93%   |
| Sunplus Integrated_Webcam_HD                                               | 9         | 4.43%   |
| Chicony Integrated Camera                                                  | 9         | 4.43%   |
| Lite-On HP HD Webcam                                                       | 8         | 3.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 3.45%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 2.96%   |
| Microdia Integrated Webcam                                                 | 4         | 1.97%   |
| Chicony USB 2.0Camera                                                      | 4         | 1.97%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.97%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.97%   |
| Chicony EasyCamera                                                         | 4         | 1.97%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 1.97%   |
| Acer Integrated Camera                                                     | 4         | 1.97%   |
| Syntek Integrated Camera                                                   | 3         | 1.48%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.48%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.48%   |
| Realtek Integrated Webcam                                                  | 3         | 1.48%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.48%   |
| Chicony HP Truevision HD                                                   | 3         | 1.48%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 1.48%   |
| Z-Star Venus USB2.0 Camera                                                 | 2         | 0.99%   |
| Suyin HP Truevision HD                                                     | 2         | 0.99%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 0.99%   |
| Sunplus HP Universal Camera                                                | 2         | 0.99%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.99%   |
| Realtek MTD camera                                                         | 2         | 0.99%   |
| Realtek HP Truevision HD                                                   | 2         | 0.99%   |
| Quanta HP HD Camera                                                        | 2         | 0.99%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 0.99%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 0.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.99%   |
| Lite-On Integrated Camera                                                  | 2         | 0.99%   |
| Lite-On HP HD Camera                                                       | 2         | 0.99%   |
| IMC Networks Integrated Camera                                             | 2         | 0.99%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 2         | 0.99%   |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 0.99%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.99%   |
| Chicony HP HD Webcam [Fixed]                                               | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 67.19%  |
| Synaptics                  | 10        | 15.63%  |
| AuthenTec                  | 4         | 6.25%   |
| Shenzhen Goodix Technology | 3         | 4.69%   |
| Upek                       | 2         | 3.13%   |
| Elan Microelectronics      | 2         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 28.13%  |
| Validity Sensors VFS491                                                    | 9         | 14.06%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 10.94%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.69%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.69%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.69%   |
| AuthenTec AES2810                                                          | 3         | 4.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.13%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.56%   |
| Synaptics  WBDI                                                            | 1         | 1.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.56%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.56%   |
| Unknown                                                                    | 1         | 1.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 21        | 91.3%   |
| O2 Micro | 2         | 8.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 43.48%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 34.78%  |
| Broadcom 5880                                                                | 2         | 8.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.35%   |
| Broadcom 58200                                                               | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 171       | 57.77%  |
| 1     | 102       | 34.46%  |
| 2     | 18        | 6.08%   |
| 4     | 2         | 0.68%   |
| 3     | 2         | 0.68%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 63        | 42%     |
| Chipcard                 | 23        | 15.33%  |
| Graphics card            | 20        | 13.33%  |
| Net/wireless             | 15        | 10%     |
| Sound                    | 9         | 6%      |
| Storage                  | 5         | 3.33%   |
| Communication controller | 4         | 2.67%   |
| Bluetooth                | 4         | 2.67%   |
| Network                  | 2         | 1.33%   |
| Net/ethernet             | 2         | 1.33%   |
| Multimedia controller    | 2         | 1.33%   |
| Camera                   | 1         | 0.67%   |


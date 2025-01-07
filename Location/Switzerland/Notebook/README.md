Linux in Switzerland - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

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

Total: 2170

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A115-32              | [2c6043fd56](https://linux-hardware.org/?probe=2c6043fd56) | Jan 05, 2025 |
| HP            | Laptop 15-db1xxx            | [7bc8aeba55](https://linux-hardware.org/?probe=7bc8aeba55) | Jan 04, 2025 |
| Acer          | Swift SF713-51              | [0b49901d64](https://linux-hardware.org/?probe=0b49901d64) | Jan 04, 2025 |
| Acer          | Swift SF713-51              | [9dc8059968](https://linux-hardware.org/?probe=9dc8059968) | Jan 04, 2025 |
| Dell          | Inspiron 7386               | [aecd7bdb44](https://linux-hardware.org/?probe=aecd7bdb44) | Jan 04, 2025 |
| Dell          | Latitude E7450              | [03b4f85891](https://linux-hardware.org/?probe=03b4f85891) | Jan 03, 2025 |
| Dell          | Latitude 7440               | [5e2a44e27d](https://linux-hardware.org/?probe=5e2a44e27d) | Jan 03, 2025 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [d086aef8fc](https://linux-hardware.org/?probe=d086aef8fc) | Jan 02, 2025 |
| HP            | Pavilion 13                 | [fece21c1ee](https://linux-hardware.org/?probe=fece21c1ee) | Dec 31, 2024 |
| Lenovo        | ThinkPad SL 2746EHG         | [c058e70d59](https://linux-hardware.org/?probe=c058e70d59) | Dec 30, 2024 |
| HP            | 250 15.6 inch G10 Notebo... | [c4a512bb62](https://linux-hardware.org/?probe=c4a512bb62) | Dec 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2831363437](https://linux-hardware.org/?probe=2831363437) | Dec 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ae31e6ad1c](https://linux-hardware.org/?probe=ae31e6ad1c) | Dec 26, 2024 |
| Fujitsu       | LIFEBOOK A532               | [188aa532e9](https://linux-hardware.org/?probe=188aa532e9) | Dec 22, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [0f99359a6d](https://linux-hardware.org/?probe=0f99359a6d) | Dec 21, 2024 |
| Acer          | Aspire A315-59              | [0b5921ac5c](https://linux-hardware.org/?probe=0b5921ac5c) | Dec 21, 2024 |
| Acer          | Aspire A315-59              | [be2a0dc527](https://linux-hardware.org/?probe=be2a0dc527) | Dec 21, 2024 |
| HP            | EliteBook 840 G6            | [fdcfe34b78](https://linux-hardware.org/?probe=fdcfe34b78) | Dec 21, 2024 |
| Dell          | Latitude E5440              | [f75e103bdb](https://linux-hardware.org/?probe=f75e103bdb) | Dec 20, 2024 |
| Lenovo        | ThinkPad T440p 20AWS2G90... | [d2137239af](https://linux-hardware.org/?probe=d2137239af) | Dec 19, 2024 |
| Lenovo        | ThinkPad T440p 20AWS2G90... | [559aebb775](https://linux-hardware.org/?probe=559aebb775) | Dec 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [305afea5b8](https://linux-hardware.org/?probe=305afea5b8) | Dec 17, 2024 |
| Lenovo        | ThinkPad T440p 20AWS2G90... | [58411691ad](https://linux-hardware.org/?probe=58411691ad) | Dec 17, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6501a529f5](https://linux-hardware.org/?probe=6501a529f5) | Dec 16, 2024 |
| Lenovo        | ThinkPad P1 Gen 7 21KVCT... | [729d84aff8](https://linux-hardware.org/?probe=729d84aff8) | Dec 15, 2024 |
| Apple         | MacBookAir7,2               | [047d8ffeee](https://linux-hardware.org/?probe=047d8ffeee) | Dec 15, 2024 |
| Lenovo        | ThinkPad SL 2746EHG         | [af38d9b12e](https://linux-hardware.org/?probe=af38d9b12e) | Dec 12, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [dba79b373a](https://linux-hardware.org/?probe=dba79b373a) | Dec 12, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [1a2e3700f4](https://linux-hardware.org/?probe=1a2e3700f4) | Dec 11, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [f730a13e27](https://linux-hardware.org/?probe=f730a13e27) | Dec 11, 2024 |
| Apple         | MacBookPro11,5              | [31b95c4a85](https://linux-hardware.org/?probe=31b95c4a85) | Dec 10, 2024 |
| Apple         | MacBookPro12,1              | [229c569c62](https://linux-hardware.org/?probe=229c569c62) | Dec 10, 2024 |
| Apple         | MacBookPro12,1              | [deca3fd9a5](https://linux-hardware.org/?probe=deca3fd9a5) | Dec 10, 2024 |
| Lenovo        | ThinkPad P1 Gen 7 21KVS0... | [4bf04dd3d9](https://linux-hardware.org/?probe=4bf04dd3d9) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [3e1d32a05a](https://linux-hardware.org/?probe=3e1d32a05a) | Dec 10, 2024 |
| HP            | ENVY Laptop 16-h0xxx        | [876b9eb39e](https://linux-hardware.org/?probe=876b9eb39e) | Dec 08, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [1a7bbb4067](https://linux-hardware.org/?probe=1a7bbb4067) | Dec 08, 2024 |
| HP            | ProBook 440 G6              | [38431440fa](https://linux-hardware.org/?probe=38431440fa) | Dec 08, 2024 |
| Acer          | Aspire ES1-512              | [21750c8987](https://linux-hardware.org/?probe=21750c8987) | Dec 07, 2024 |
| Fujitsu       | LIFEBOOK A532               | [1a8413b8c1](https://linux-hardware.org/?probe=1a8413b8c1) | Dec 07, 2024 |
| Apple         | MacBookPro4,1               | [4dba947354](https://linux-hardware.org/?probe=4dba947354) | Dec 06, 2024 |
| Lenovo        | ThinkPad T400 27658JG       | [0e628ec7f3](https://linux-hardware.org/?probe=0e628ec7f3) | Dec 06, 2024 |
| Lenovo        | ThinkPad T400 27658JG       | [19da4f0a7b](https://linux-hardware.org/?probe=19da4f0a7b) | Dec 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [47ec30dab5](https://linux-hardware.org/?probe=47ec30dab5) | Dec 05, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [a7a5047657](https://linux-hardware.org/?probe=a7a5047657) | Dec 05, 2024 |
| Apple         | MacBookAir6,2               | [f880b60a76](https://linux-hardware.org/?probe=f880b60a76) | Dec 03, 2024 |
| Apple         | MacBookAir6,2               | [43eaee20f2](https://linux-hardware.org/?probe=43eaee20f2) | Dec 03, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [33eb230c2a](https://linux-hardware.org/?probe=33eb230c2a) | Dec 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MC0... | [e2e17a6a88](https://linux-hardware.org/?probe=e2e17a6a88) | Dec 03, 2024 |
| HP            | 240 G8 Notebook PC          | [e28f3d21e4](https://linux-hardware.org/?probe=e28f3d21e4) | Dec 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | [cf0dcbdaff](https://linux-hardware.org/?probe=cf0dcbdaff) | Nov 30, 2024 |
| HP            | Laptop 15s-eq1xxx           | [3a04adcfd6](https://linux-hardware.org/?probe=3a04adcfd6) | Nov 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MC0... | [a529dc0e1a](https://linux-hardware.org/?probe=a529dc0e1a) | Nov 29, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [fbac8e7a75](https://linux-hardware.org/?probe=fbac8e7a75) | Nov 28, 2024 |
| MSI           | WT72 6QM                    | [6c800a258c](https://linux-hardware.org/?probe=6c800a258c) | Nov 27, 2024 |
| Apple         | MacBookAir7,2               | [78de1913a3](https://linux-hardware.org/?probe=78de1913a3) | Nov 24, 2024 |
| Acer          | Aspire VN7-791              | [44d9810a30](https://linux-hardware.org/?probe=44d9810a30) | Nov 23, 2024 |
| Acer          | Aspire A115-32              | [fbfb9310ce](https://linux-hardware.org/?probe=fbfb9310ce) | Nov 23, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [39084b6ee1](https://linux-hardware.org/?probe=39084b6ee1) | Nov 22, 2024 |
| HP            | 250 G7 Notebook PC          | [6be5b2a8ec](https://linux-hardware.org/?probe=6be5b2a8ec) | Nov 21, 2024 |
| Dell          | Inspiron 5770               | [e0781253b5](https://linux-hardware.org/?probe=e0781253b5) | Nov 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9365a57030](https://linux-hardware.org/?probe=9365a57030) | Nov 20, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [548d21fd0e](https://linux-hardware.org/?probe=548d21fd0e) | Nov 19, 2024 |
| HP            | ProBook 455 G2              | [a739af0867](https://linux-hardware.org/?probe=a739af0867) | Nov 19, 2024 |
| Apple         | MacBookAir7,2               | [ba3ba814ee](https://linux-hardware.org/?probe=ba3ba814ee) | Nov 18, 2024 |
| Apple         | MacBookPro8,1               | [ba64567726](https://linux-hardware.org/?probe=ba64567726) | Nov 18, 2024 |
| HP            | EliteBook 830 G5            | [83ae373757](https://linux-hardware.org/?probe=83ae373757) | Nov 17, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [4ecadd4fa2](https://linux-hardware.org/?probe=4ecadd4fa2) | Nov 17, 2024 |
| HP            | EliteBook 830 G5            | [0d7c47ffe5](https://linux-hardware.org/?probe=0d7c47ffe5) | Nov 17, 2024 |
| Acer          | Swift SF314-54              | [ae323153bc](https://linux-hardware.org/?probe=ae323153bc) | Nov 15, 2024 |
| Acer          | Swift SF314-54              | [86276b9cec](https://linux-hardware.org/?probe=86276b9cec) | Nov 15, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | [a28646da71](https://linux-hardware.org/?probe=a28646da71) | Nov 13, 2024 |
| Lenovo        | ThinkPad T440 20B7S1MF0J    | [b8a9aa94e7](https://linux-hardware.org/?probe=b8a9aa94e7) | Nov 12, 2024 |
| Lenovo        | ThinkPad E15 20RES6DF01     | [00f82a6232](https://linux-hardware.org/?probe=00f82a6232) | Nov 11, 2024 |
| HUAWEI        | MACHD-WXX9                  | [ad91a529fc](https://linux-hardware.org/?probe=ad91a529fc) | Nov 11, 2024 |
| Apple         | MacBookPro8,1               | [2f0fa7a4fa](https://linux-hardware.org/?probe=2f0fa7a4fa) | Nov 11, 2024 |
| Acer          | AOD270                      | [59b2793787](https://linux-hardware.org/?probe=59b2793787) | Nov 10, 2024 |
| HP            | ProBook 455 G2              | [6fe664f991](https://linux-hardware.org/?probe=6fe664f991) | Nov 09, 2024 |
| Acer          | Aspire ES1-531              | [a7c11e81f1](https://linux-hardware.org/?probe=a7c11e81f1) | Nov 09, 2024 |
| Acer          | Aspire ES1-531              | [eda5406b2d](https://linux-hardware.org/?probe=eda5406b2d) | Nov 09, 2024 |
| HP            | 250 G7 Notebook PC          | [fdac2e572a](https://linux-hardware.org/?probe=fdac2e572a) | Nov 09, 2024 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | [ef73511c69](https://linux-hardware.org/?probe=ef73511c69) | Nov 09, 2024 |
| Acer          | Aspire A115-32              | [20018392dc](https://linux-hardware.org/?probe=20018392dc) | Nov 07, 2024 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [9e252f86d2](https://linux-hardware.org/?probe=9e252f86d2) | Nov 05, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [8bf53827ed](https://linux-hardware.org/?probe=8bf53827ed) | Nov 04, 2024 |
| Apple         | MacBook8,1                  | [f2389d5563](https://linux-hardware.org/?probe=f2389d5563) | Nov 04, 2024 |
| Acer          | Aspire A515-52              | [5466d381ed](https://linux-hardware.org/?probe=5466d381ed) | Nov 04, 2024 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [83cc7bdc1c](https://linux-hardware.org/?probe=83cc7bdc1c) | Nov 04, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [5eb398d916](https://linux-hardware.org/?probe=5eb398d916) | Nov 04, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [c996bdf561](https://linux-hardware.org/?probe=c996bdf561) | Nov 04, 2024 |
| HP            | 250 G8                      | [a1a11558dd](https://linux-hardware.org/?probe=a1a11558dd) | Nov 04, 2024 |
| HP            | 250 G8                      | [e38560cea7](https://linux-hardware.org/?probe=e38560cea7) | Nov 04, 2024 |
| Acer          | Swift SF314-56G             | [1c9ca4707d](https://linux-hardware.org/?probe=1c9ca4707d) | Nov 04, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [c1d52a840a](https://linux-hardware.org/?probe=c1d52a840a) | Nov 03, 2024 |
| Apple         | MacBookPro6,1               | [a3b81fc716](https://linux-hardware.org/?probe=a3b81fc716) | Nov 02, 2024 |
| Dell          | Latitude E4300              | [90b6823b82](https://linux-hardware.org/?probe=90b6823b82) | Nov 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [59116a075c](https://linux-hardware.org/?probe=59116a075c) | Nov 01, 2024 |
| Dell          | XPS 15 7590                 | [597318b1e3](https://linux-hardware.org/?probe=597318b1e3) | Nov 01, 2024 |
| Dell          | Latitude E4300              | [2c7555b016](https://linux-hardware.org/?probe=2c7555b016) | Oct 31, 2024 |
| Apple         | MacBookPro8,1               | [9a9ae9d765](https://linux-hardware.org/?probe=9a9ae9d765) | Oct 24, 2024 |
| Acer          | Aspire A315-44P             | [757f809c22](https://linux-hardware.org/?probe=757f809c22) | Oct 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8S05A0... | [50c322a885](https://linux-hardware.org/?probe=50c322a885) | Oct 20, 2024 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [cd5f8e38ff](https://linux-hardware.org/?probe=cd5f8e38ff) | Oct 20, 2024 |
| Dell          | Latitude 7390 2-in-1        | [ae0ebdeca8](https://linux-hardware.org/?probe=ae0ebdeca8) | Oct 16, 2024 |
| Apple         | MacBookPro8,1               | [18cc7921db](https://linux-hardware.org/?probe=18cc7921db) | Oct 15, 2024 |
| Apple         | MacBookPro8,1               | [e6891ad523](https://linux-hardware.org/?probe=e6891ad523) | Oct 15, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [7d183cab91](https://linux-hardware.org/?probe=7d183cab91) | Oct 14, 2024 |
| Apple         | MacBookPro8,2               | [f20e6b3dc8](https://linux-hardware.org/?probe=f20e6b3dc8) | Oct 13, 2024 |
| Apple         | MacBookPro8,2               | [ecf92c84fe](https://linux-hardware.org/?probe=ecf92c84fe) | Oct 13, 2024 |
| Apple         | MacBookAir7,2               | [cdac18ce01](https://linux-hardware.org/?probe=cdac18ce01) | Oct 13, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [b4a4852367](https://linux-hardware.org/?probe=b4a4852367) | Oct 13, 2024 |
| Lenovo        | ThinkPad T540p 20BFS3H00... | [9e26809480](https://linux-hardware.org/?probe=9e26809480) | Oct 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c9a54bde4c](https://linux-hardware.org/?probe=c9a54bde4c) | Oct 11, 2024 |
| HP            | 250 G7 Notebook PC          | [6c9c0f7683](https://linux-hardware.org/?probe=6c9c0f7683) | Oct 11, 2024 |
| Apple         | MacBookPro8,2               | [b40e0a8447](https://linux-hardware.org/?probe=b40e0a8447) | Oct 11, 2024 |
| HP            | 250 G7 Notebook PC          | [9d7205990c](https://linux-hardware.org/?probe=9d7205990c) | Oct 11, 2024 |
| Dell          | XPS 13 9300                 | [76d3595387](https://linux-hardware.org/?probe=76d3595387) | Oct 11, 2024 |
| ASUSTek       | T100TA                      | [27cc9eff0c](https://linux-hardware.org/?probe=27cc9eff0c) | Oct 09, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [31c9a18f01](https://linux-hardware.org/?probe=31c9a18f01) | Oct 09, 2024 |
| VALE          | Notebook Evolution i5-11... | [bdc3ddf356](https://linux-hardware.org/?probe=bdc3ddf356) | Oct 09, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [a010c0db0b](https://linux-hardware.org/?probe=a010c0db0b) | Oct 09, 2024 |
| Polaroid      | MP1464PR001                 | [3abfe5c9f6](https://linux-hardware.org/?probe=3abfe5c9f6) | Oct 07, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [b2ca6c0d91](https://linux-hardware.org/?probe=b2ca6c0d91) | Oct 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [12798a0ecf](https://linux-hardware.org/?probe=12798a0ecf) | Oct 06, 2024 |
| Valve         | Jupiter                     | [1989d5320d](https://linux-hardware.org/?probe=1989d5320d) | Oct 05, 2024 |
| Acer          | Swift SF314-56G             | [2bbadf63d0](https://linux-hardware.org/?probe=2bbadf63d0) | Oct 05, 2024 |
| Sony          | VPCEC3L1E                   | [748694aa38](https://linux-hardware.org/?probe=748694aa38) | Oct 05, 2024 |
| HP            | OMEN Transcend Gaming La... | [1d5ef3c0cd](https://linux-hardware.org/?probe=1d5ef3c0cd) | Oct 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [bcf10922f9](https://linux-hardware.org/?probe=bcf10922f9) | Oct 02, 2024 |
| HP            | Victus by Gaming Laptop ... | [c64be37a13](https://linux-hardware.org/?probe=c64be37a13) | Sep 30, 2024 |
| Acer          | Swift SF314-54              | [f68cbf046f](https://linux-hardware.org/?probe=f68cbf046f) | Sep 28, 2024 |
| Acer          | Swift SF314-54              | [72d85702bc](https://linux-hardware.org/?probe=72d85702bc) | Sep 28, 2024 |
| HP            | ProBook 4740s               | [8a7c9fbe9c](https://linux-hardware.org/?probe=8a7c9fbe9c) | Sep 27, 2024 |
| Polaroid      | MP1464PR001                 | [10cbba3b2d](https://linux-hardware.org/?probe=10cbba3b2d) | Sep 27, 2024 |
| ASUSTek       | UX305FA                     | [cab58b19a5](https://linux-hardware.org/?probe=cab58b19a5) | Sep 27, 2024 |
| Samsung       | 750XED                      | [f1cbdee67a](https://linux-hardware.org/?probe=f1cbdee67a) | Sep 26, 2024 |
| Samsung       | 750XED                      | [a39a7e8d42](https://linux-hardware.org/?probe=a39a7e8d42) | Sep 26, 2024 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [a6b33db736](https://linux-hardware.org/?probe=a6b33db736) | Sep 25, 2024 |
| HP            | EliteBook 840 G6            | [89171aecc7](https://linux-hardware.org/?probe=89171aecc7) | Sep 24, 2024 |
| HP            | EliteBook 840 G5            | [a6c2ea003a](https://linux-hardware.org/?probe=a6c2ea003a) | Sep 23, 2024 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [bc68caf4f6](https://linux-hardware.org/?probe=bc68caf4f6) | Sep 22, 2024 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [450daa1a07](https://linux-hardware.org/?probe=450daa1a07) | Sep 21, 2024 |
| Dell          | System XPS L702X            | [d2662fe6a6](https://linux-hardware.org/?probe=d2662fe6a6) | Sep 20, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K6... | [a806838bbf](https://linux-hardware.org/?probe=a806838bbf) | Sep 20, 2024 |
| Apple         | MacBookPro12,1              | [3a67e2619d](https://linux-hardware.org/?probe=3a67e2619d) | Sep 17, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c1fca7c250](https://linux-hardware.org/?probe=c1fca7c250) | Sep 15, 2024 |
| AXDIA Inte... | WINBOOK 13                  | [ac236a8450](https://linux-hardware.org/?probe=ac236a8450) | Sep 14, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS1... | [286d8bff4c](https://linux-hardware.org/?probe=286d8bff4c) | Sep 12, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [228aee06a5](https://linux-hardware.org/?probe=228aee06a5) | Sep 07, 2024 |
| Acer          | Aspire A515-56              | [8a2ae21fc4](https://linux-hardware.org/?probe=8a2ae21fc4) | Sep 05, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [b37cf62016](https://linux-hardware.org/?probe=b37cf62016) | Sep 05, 2024 |
| Apple         | MacBookAir6,2               | [3045eea974](https://linux-hardware.org/?probe=3045eea974) | Sep 04, 2024 |
| HP            | EliteBook 8460p             | [f0361f66d3](https://linux-hardware.org/?probe=f0361f66d3) | Sep 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [f76edee790](https://linux-hardware.org/?probe=f76edee790) | Sep 01, 2024 |
| HP            | ZBook Studio G5             | [441ce69609](https://linux-hardware.org/?probe=441ce69609) | Aug 29, 2024 |
| HP            | ZBook Studio G5             | [01c25ba48a](https://linux-hardware.org/?probe=01c25ba48a) | Aug 29, 2024 |
| Dell          | XPS 16 9640                 | [4978f9a29c](https://linux-hardware.org/?probe=4978f9a29c) | Aug 28, 2024 |
| Unknown       | Unknown                     | [d64075ee63](https://linux-hardware.org/?probe=d64075ee63) | Aug 28, 2024 |
| ASUSTek       | G750JX                      | [9e273b8471](https://linux-hardware.org/?probe=9e273b8471) | Aug 27, 2024 |
| ASUSTek       | G750JX                      | [24468fe950](https://linux-hardware.org/?probe=24468fe950) | Aug 27, 2024 |
| Apple         | MacBookAir4,2               | [ba05c4958d](https://linux-hardware.org/?probe=ba05c4958d) | Aug 26, 2024 |
| HP            | ProBook 450 G5              | [691e208374](https://linux-hardware.org/?probe=691e208374) | Aug 25, 2024 |
| Dell          | Latitude 9450 2-in-1        | [c703c4f4cd](https://linux-hardware.org/?probe=c703c4f4cd) | Aug 23, 2024 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a45b840580](https://linux-hardware.org/?probe=a45b840580) | Aug 23, 2024 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [41baef1112](https://linux-hardware.org/?probe=41baef1112) | Aug 22, 2024 |
| Dell          | Latitude 9450 2-in-1        | [a96e1b3995](https://linux-hardware.org/?probe=a96e1b3995) | Aug 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [3f162bf157](https://linux-hardware.org/?probe=3f162bf157) | Aug 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [95fdad7017](https://linux-hardware.org/?probe=95fdad7017) | Aug 19, 2024 |
| HP            | EliteBook 8540p             | [9e8a7b912b](https://linux-hardware.org/?probe=9e8a7b912b) | Aug 19, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [7e6f232032](https://linux-hardware.org/?probe=7e6f232032) | Aug 18, 2024 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [d4e9ec66bb](https://linux-hardware.org/?probe=d4e9ec66bb) | Aug 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [097b659dbb](https://linux-hardware.org/?probe=097b659dbb) | Aug 17, 2024 |
| ASUSTek       | X556URK                     | [7bf3e1b423](https://linux-hardware.org/?probe=7bf3e1b423) | Aug 14, 2024 |
| Lenovo        | ThinkPad T470p 20J7S1KX0... | [8606bb3052](https://linux-hardware.org/?probe=8606bb3052) | Aug 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f3bc04961a](https://linux-hardware.org/?probe=f3bc04961a) | Aug 13, 2024 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [5d349896cb](https://linux-hardware.org/?probe=5d349896cb) | Aug 11, 2024 |
| Apple         | MacBookAir6,2               | [f8aa316fae](https://linux-hardware.org/?probe=f8aa316fae) | Aug 09, 2024 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | [8f39a4a627](https://linux-hardware.org/?probe=8f39a4a627) | Aug 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [63b390b2b6](https://linux-hardware.org/?probe=63b390b2b6) | Aug 05, 2024 |
| Acer          | Aspire F5-571G              | [c6894a9467](https://linux-hardware.org/?probe=c6894a9467) | Aug 04, 2024 |
| AXDIA Inte... | WINBOOK 13                  | [444e5f5564](https://linux-hardware.org/?probe=444e5f5564) | Aug 03, 2024 |
| ASUSTek       | X540LA                      | [802e2c494e](https://linux-hardware.org/?probe=802e2c494e) | Aug 01, 2024 |
| ASUSTek       | X540LA                      | [5db4299943](https://linux-hardware.org/?probe=5db4299943) | Aug 01, 2024 |
| Dell          | XPS 13 9300                 | [ba70115a51](https://linux-hardware.org/?probe=ba70115a51) | Aug 01, 2024 |
| AXDIA Inte... | WINBOOK 13                  | [60eb3cce73](https://linux-hardware.org/?probe=60eb3cce73) | Aug 01, 2024 |
| Lenovo        | Yoga 900-13ISK 80MK         | [7c9476154d](https://linux-hardware.org/?probe=7c9476154d) | Jul 29, 2024 |
| ASUSTek       | N56VZ                       | [faf4684833](https://linux-hardware.org/?probe=faf4684833) | Jul 27, 2024 |
| Apple         | MacBookPro14,2              | [76deccaa1b](https://linux-hardware.org/?probe=76deccaa1b) | Jul 26, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [7cc3ee612a](https://linux-hardware.org/?probe=7cc3ee612a) | Jul 26, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | [1e7a4734ce](https://linux-hardware.org/?probe=1e7a4734ce) | Jul 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [75748267b4](https://linux-hardware.org/?probe=75748267b4) | Jul 25, 2024 |
| Acer          | Aspire E1-531               | [07ce6ddc7c](https://linux-hardware.org/?probe=07ce6ddc7c) | Jul 24, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | [c80f2e729d](https://linux-hardware.org/?probe=c80f2e729d) | Jul 23, 2024 |
| Acer          | Aspire V3-772               | [f1bab48127](https://linux-hardware.org/?probe=f1bab48127) | Jul 23, 2024 |
| ASUSTek       | ROG Strix G834JY_G834JY     | [7fd40ce962](https://linux-hardware.org/?probe=7fd40ce962) | Jul 22, 2024 |
| Google        | Rammus                      | [3e8da4bbf6](https://linux-hardware.org/?probe=3e8da4bbf6) | Jul 22, 2024 |
| Dell          | Latitude E5540              | [34bee156ca](https://linux-hardware.org/?probe=34bee156ca) | Jul 21, 2024 |
| Apple         | MacBookPro7,1               | [2a71582dde](https://linux-hardware.org/?probe=2a71582dde) | Jul 20, 2024 |
| Apple         | MacBookPro7,1               | [e741128eca](https://linux-hardware.org/?probe=e741128eca) | Jul 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [93dfbb775e](https://linux-hardware.org/?probe=93dfbb775e) | Jul 16, 2024 |
| HP            | Laptop 15s-fq2xxx           | [6373f603ae](https://linux-hardware.org/?probe=6373f603ae) | Jul 12, 2024 |
| HP            | Laptop 15s-fq2xxx           | [734da0aed5](https://linux-hardware.org/?probe=734da0aed5) | Jul 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [724097a358](https://linux-hardware.org/?probe=724097a358) | Jul 08, 2024 |
| Dell          | Latitude E7470              | [5ad6dfee76](https://linux-hardware.org/?probe=5ad6dfee76) | Jul 08, 2024 |
| Dell          | Latitude E7470              | [f115f462d4](https://linux-hardware.org/?probe=f115f462d4) | Jul 08, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [2679ed2c9a](https://linux-hardware.org/?probe=2679ed2c9a) | Jul 07, 2024 |
| Lenovo        | IdeaPad Slim 3 16ABR8 82... | [9804cf789a](https://linux-hardware.org/?probe=9804cf789a) | Jul 05, 2024 |
| Lenovo        | Y50-70 20378                | [21494fd560](https://linux-hardware.org/?probe=21494fd560) | Jul 04, 2024 |
| HP            | Compaq 8710w (GC125EA#UU... | [c5f7d9e9bb](https://linux-hardware.org/?probe=c5f7d9e9bb) | Jul 04, 2024 |
| Acer          | Aspire E1-772               | [f2ced6fdae](https://linux-hardware.org/?probe=f2ced6fdae) | Jul 04, 2024 |
| HP            | EliteBook 840 G5            | [2b70c363fa](https://linux-hardware.org/?probe=2b70c363fa) | Jul 03, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [9125035c38](https://linux-hardware.org/?probe=9125035c38) | Jul 03, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [953aa1d90a](https://linux-hardware.org/?probe=953aa1d90a) | Jul 02, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [034de7bdb0](https://linux-hardware.org/?probe=034de7bdb0) | Jul 01, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [94b1f32a89](https://linux-hardware.org/?probe=94b1f32a89) | Jun 29, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [74a2a1e5b3](https://linux-hardware.org/?probe=74a2a1e5b3) | Jun 29, 2024 |
| Dell          | Latitude E5270              | [175a48f67e](https://linux-hardware.org/?probe=175a48f67e) | Jun 27, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3581972f03](https://linux-hardware.org/?probe=3581972f03) | Jun 23, 2024 |
| MSI           | Summit E16Flip A12UCT       | [3179a899d0](https://linux-hardware.org/?probe=3179a899d0) | Jun 22, 2024 |
| MSI           | Summit E16Flip A12UCT       | [abe30071da](https://linux-hardware.org/?probe=abe30071da) | Jun 22, 2024 |
| Dell          | System Vostro 3750          | [11b4029c69](https://linux-hardware.org/?probe=11b4029c69) | Jun 19, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f28969678d](https://linux-hardware.org/?probe=f28969678d) | Jun 19, 2024 |
| Dell          | System Vostro 3750          | [314b7f9b95](https://linux-hardware.org/?probe=314b7f9b95) | Jun 16, 2024 |
| Dell          | Vostro 5481                 | [296f6684ba](https://linux-hardware.org/?probe=296f6684ba) | Jun 16, 2024 |
| Dell          | Vostro 5481                 | [78b78a9764](https://linux-hardware.org/?probe=78b78a9764) | Jun 15, 2024 |
| Sony          | VPCF23S1E                   | [7f890685d2](https://linux-hardware.org/?probe=7f890685d2) | Jun 15, 2024 |
| Lenovo        | Y50-70 20378                | [299f7049e2](https://linux-hardware.org/?probe=299f7049e2) | Jun 14, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | [eec5a148c0](https://linux-hardware.org/?probe=eec5a148c0) | Jun 14, 2024 |
| Valve         | Galileo                     | [0dcc255711](https://linux-hardware.org/?probe=0dcc255711) | Jun 14, 2024 |
| Lenovo        | ThinkPad T460s 20F90044M... | [eb4143f8ad](https://linux-hardware.org/?probe=eb4143f8ad) | Jun 14, 2024 |
| Dell          | Precision 3480              | [f28eb31809](https://linux-hardware.org/?probe=f28eb31809) | Jun 14, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | [fb0d42ccdd](https://linux-hardware.org/?probe=fb0d42ccdd) | Jun 13, 2024 |
| HP            | ProBook 450 G5              | [d063316527](https://linux-hardware.org/?probe=d063316527) | Jun 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8721ba0af6](https://linux-hardware.org/?probe=8721ba0af6) | Jun 13, 2024 |
| Apple         | MacBookPro9,2               | [5b38d05c90](https://linux-hardware.org/?probe=5b38d05c90) | Jun 11, 2024 |
| Apple         | MacBookPro9,2               | [2ef5accb7e](https://linux-hardware.org/?probe=2ef5accb7e) | Jun 11, 2024 |
| HP            | Laptop 15s-fq2xxx           | [e1e9c3ba78](https://linux-hardware.org/?probe=e1e9c3ba78) | Jun 10, 2024 |
| HP            | EliteBook 840 G5            | [c22f374397](https://linux-hardware.org/?probe=c22f374397) | Jun 10, 2024 |
| Valve         | Galileo                     | [de8af0eb2d](https://linux-hardware.org/?probe=de8af0eb2d) | Jun 10, 2024 |
| Lenovo        | ThinkPad T400 2765TDG       | [e51bc89e3b](https://linux-hardware.org/?probe=e51bc89e3b) | Jun 09, 2024 |
| HP            | Elite Dragonfly             | [249269989d](https://linux-hardware.org/?probe=249269989d) | Jun 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 34442... | [e96b185dba](https://linux-hardware.org/?probe=e96b185dba) | Jun 04, 2024 |
| Dell          | G15 5520                    | [1012b8f366](https://linux-hardware.org/?probe=1012b8f366) | Jun 04, 2024 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [a0fd42501a](https://linux-hardware.org/?probe=a0fd42501a) | May 31, 2024 |
| Apple         | MacBookPro9,2               | [a1f1457ffa](https://linux-hardware.org/?probe=a1f1457ffa) | May 31, 2024 |
| Acer          | Swift SF314-54              | [4b1a7ce6c5](https://linux-hardware.org/?probe=4b1a7ce6c5) | May 31, 2024 |
| Acer          | Swift SF314-54              | [1de77abab0](https://linux-hardware.org/?probe=1de77abab0) | May 31, 2024 |
| Apple         | MacBookPro9,2               | [4180537bd8](https://linux-hardware.org/?probe=4180537bd8) | May 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e4547bc1b7](https://linux-hardware.org/?probe=e4547bc1b7) | May 29, 2024 |
| Acer          | Aspire A517-58GM            | [d5a67825e7](https://linux-hardware.org/?probe=d5a67825e7) | May 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [3d5ddf1e32](https://linux-hardware.org/?probe=3d5ddf1e32) | May 29, 2024 |
| HP            | Pavilion dv6                | [70239d9c62](https://linux-hardware.org/?probe=70239d9c62) | May 25, 2024 |
| Lenovo        | ThinkPad T480 20L6SF3R00    | [4e442b5935](https://linux-hardware.org/?probe=4e442b5935) | May 24, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [8fe97e5cbb](https://linux-hardware.org/?probe=8fe97e5cbb) | May 24, 2024 |
| ASUSTek       | X751LK                      | [1a7aa6c23d](https://linux-hardware.org/?probe=1a7aa6c23d) | May 23, 2024 |
| Valve         | Jupiter                     | [e03f67a310](https://linux-hardware.org/?probe=e03f67a310) | May 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [620518bc05](https://linux-hardware.org/?probe=620518bc05) | May 21, 2024 |
| HP            | EliteBook 840 14 inch G9... | [7ccc346dd5](https://linux-hardware.org/?probe=7ccc346dd5) | May 19, 2024 |
| HP            | Laptop 15s-fq2xxx           | [0f3322c110](https://linux-hardware.org/?probe=0f3322c110) | May 17, 2024 |
| MSI           | Summit E14Evo A12M          | [02bfb3adf7](https://linux-hardware.org/?probe=02bfb3adf7) | May 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [bcb19049e8](https://linux-hardware.org/?probe=bcb19049e8) | May 14, 2024 |
| Lenovo        | ThinkPad L450 20DT0003XS    | [76c50cca06](https://linux-hardware.org/?probe=76c50cca06) | May 13, 2024 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [e2c0ec6c03](https://linux-hardware.org/?probe=e2c0ec6c03) | May 11, 2024 |
| VALE          | Notebook Evolution i5-11... | [55764ee04d](https://linux-hardware.org/?probe=55764ee04d) | May 08, 2024 |
| HP            | Laptop 15s-fq2xxx           | [31a04e0322](https://linux-hardware.org/?probe=31a04e0322) | May 08, 2024 |
| HP            | EliteBook 840 G8            | [6d255e156e](https://linux-hardware.org/?probe=6d255e156e) | May 08, 2024 |
| Acer          | Swift SF314-52              | [d112cef6d2](https://linux-hardware.org/?probe=d112cef6d2) | May 07, 2024 |
| HP            | EliteBook 840 G8            | [f60faaeec0](https://linux-hardware.org/?probe=f60faaeec0) | May 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [84cc2abe63](https://linux-hardware.org/?probe=84cc2abe63) | May 06, 2024 |
| Dell          | XPS 13 7390                 | [3132f4ff24](https://linux-hardware.org/?probe=3132f4ff24) | May 06, 2024 |
| HP            | Laptop 15s-fq2xxx           | [c9843fc5d2](https://linux-hardware.org/?probe=c9843fc5d2) | May 05, 2024 |
| ASUSTek       | X510UAR                     | [3317acbe53](https://linux-hardware.org/?probe=3317acbe53) | May 05, 2024 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [7c2c0a0fc2](https://linux-hardware.org/?probe=7c2c0a0fc2) | May 04, 2024 |
| Getac         | S410                        | [a05cbbe577](https://linux-hardware.org/?probe=a05cbbe577) | May 04, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [a70e2b13ca](https://linux-hardware.org/?probe=a70e2b13ca) | May 03, 2024 |
| TUXEDO        | InfinityBook S Gen8         | [19d3fc9c13](https://linux-hardware.org/?probe=19d3fc9c13) | Apr 30, 2024 |
| Acer          | Aspire 7745G                | [1854a5b427](https://linux-hardware.org/?probe=1854a5b427) | Apr 30, 2024 |
| Lenovo        | ThinkPad P1 Gen 5 21DCS0... | [4f23a4a44b](https://linux-hardware.org/?probe=4f23a4a44b) | Apr 30, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [274c1ee480](https://linux-hardware.org/?probe=274c1ee480) | Apr 30, 2024 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [5514986c5d](https://linux-hardware.org/?probe=5514986c5d) | Apr 30, 2024 |
| ASUSTek       | K53SD                       | [058d33ec3c](https://linux-hardware.org/?probe=058d33ec3c) | Apr 29, 2024 |
| Apple         | MacBookPro10,1              | [404e775920](https://linux-hardware.org/?probe=404e775920) | Apr 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f619fc2cb1](https://linux-hardware.org/?probe=f619fc2cb1) | Apr 26, 2024 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [3727b60089](https://linux-hardware.org/?probe=3727b60089) | Apr 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [c207bea569](https://linux-hardware.org/?probe=c207bea569) | Apr 25, 2024 |
| Dell          | Inspiron 17-7779            | [4d2fec89a1](https://linux-hardware.org/?probe=4d2fec89a1) | Apr 24, 2024 |
| PC Special... | Ionico 16                   | [d75ee89a24](https://linux-hardware.org/?probe=d75ee89a24) | Apr 24, 2024 |
| Lenovo        | ThinkPad X220 4291WSH       | [ff6227451a](https://linux-hardware.org/?probe=ff6227451a) | Apr 23, 2024 |
| Dell          | XPS 15 9520                 | [359a02a8cb](https://linux-hardware.org/?probe=359a02a8cb) | Apr 23, 2024 |
| Acer          | Swift SF314-42              | [c5ab9f2681](https://linux-hardware.org/?probe=c5ab9f2681) | Apr 22, 2024 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [f586504622](https://linux-hardware.org/?probe=f586504622) | Apr 22, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [7cecfee468](https://linux-hardware.org/?probe=7cecfee468) | Apr 21, 2024 |
| HP            | ProBook 6560b               | [5ea8af85bf](https://linux-hardware.org/?probe=5ea8af85bf) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [a776a9677a](https://linux-hardware.org/?probe=a776a9677a) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4f7d67acb4](https://linux-hardware.org/?probe=4f7d67acb4) | Apr 17, 2024 |
| Acer          | Nitro AN515-52              | [397f8b0836](https://linux-hardware.org/?probe=397f8b0836) | Apr 15, 2024 |
| ASUSTek       | GL702ZC                     | [bf6ba63bb3](https://linux-hardware.org/?probe=bf6ba63bb3) | Apr 15, 2024 |
| Sony          | VPCF12M1E                   | [a07e465b04](https://linux-hardware.org/?probe=a07e465b04) | Apr 15, 2024 |
| Acer          | Aspire 5742G                | [91d047cef5](https://linux-hardware.org/?probe=91d047cef5) | Apr 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [c28ddacfd6](https://linux-hardware.org/?probe=c28ddacfd6) | Apr 13, 2024 |
| Sony          | VPCF12M1E                   | [b4adc4cd67](https://linux-hardware.org/?probe=b4adc4cd67) | Apr 13, 2024 |
| Lenovo        | G550 2958                   | [2cebfc34df](https://linux-hardware.org/?probe=2cebfc34df) | Apr 12, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [589fd95069](https://linux-hardware.org/?probe=589fd95069) | Apr 11, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [6988114e9a](https://linux-hardware.org/?probe=6988114e9a) | Apr 10, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [217f8e21a7](https://linux-hardware.org/?probe=217f8e21a7) | Apr 10, 2024 |
| Dell          | Inspiron 3521               | [f09f64c924](https://linux-hardware.org/?probe=f09f64c924) | Apr 09, 2024 |
| Dell          | Inspiron 3521               | [690cbe6f29](https://linux-hardware.org/?probe=690cbe6f29) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d21570a024](https://linux-hardware.org/?probe=d21570a024) | Apr 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [97879c1052](https://linux-hardware.org/?probe=97879c1052) | Apr 08, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [9099f440bc](https://linux-hardware.org/?probe=9099f440bc) | Apr 08, 2024 |
| Dell          | Studio 1747                 | [33e2d94187](https://linux-hardware.org/?probe=33e2d94187) | Apr 05, 2024 |
| Dell          | Vostro1710                  | [811cef5fac](https://linux-hardware.org/?probe=811cef5fac) | Apr 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [f7f399c411](https://linux-hardware.org/?probe=f7f399c411) | Apr 04, 2024 |
| MSI           | GX780R/GT780R/GT780DXR      | [c4e752d06c](https://linux-hardware.org/?probe=c4e752d06c) | Apr 04, 2024 |
| MSI           | GX780R/GT780R/GT780DXR      | [100d6d2fcd](https://linux-hardware.org/?probe=100d6d2fcd) | Apr 04, 2024 |
| HP            | EliteBook 8460p             | [6e1fd1f1b0](https://linux-hardware.org/?probe=6e1fd1f1b0) | Apr 04, 2024 |
| Acer          | Predator PH18-71            | [1c854f7ef4](https://linux-hardware.org/?probe=1c854f7ef4) | Apr 04, 2024 |
| HP            | ProBook 650 G1              | [d81b4ee2e3](https://linux-hardware.org/?probe=d81b4ee2e3) | Apr 03, 2024 |
| GPD           | P2 MAX                      | [8e53b3ed39](https://linux-hardware.org/?probe=8e53b3ed39) | Apr 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [9d19446a7f](https://linux-hardware.org/?probe=9d19446a7f) | Apr 01, 2024 |
| Lenovo        | ThinkPad T450 20BV001XMZ    | [cb709fd91f](https://linux-hardware.org/?probe=cb709fd91f) | Mar 31, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [c9ece96124](https://linux-hardware.org/?probe=c9ece96124) | Mar 31, 2024 |
| Lenovo        | ThinkPad E580 20KS006FMZ    | [94d109d91e](https://linux-hardware.org/?probe=94d109d91e) | Mar 30, 2024 |
| Acer          | Predator PH18-71            | [09854145ed](https://linux-hardware.org/?probe=09854145ed) | Mar 28, 2024 |
| Apple         | MacBookPro9,1               | [a5715d4c3e](https://linux-hardware.org/?probe=a5715d4c3e) | Mar 28, 2024 |
| Apple         | MacBookPro8,1               | [48eae7912e](https://linux-hardware.org/?probe=48eae7912e) | Mar 27, 2024 |
| Dell          | Inspiron 17-7779            | [deecf7220f](https://linux-hardware.org/?probe=deecf7220f) | Mar 27, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [e7501b45b5](https://linux-hardware.org/?probe=e7501b45b5) | Mar 27, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [23c0ad0c6d](https://linux-hardware.org/?probe=23c0ad0c6d) | Mar 25, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | [5263d017a2](https://linux-hardware.org/?probe=5263d017a2) | Mar 25, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [fad6108f0a](https://linux-hardware.org/?probe=fad6108f0a) | Mar 24, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [c214e5588e](https://linux-hardware.org/?probe=c214e5588e) | Mar 23, 2024 |
| Acer          | Swift SFE16-43              | [23667b0d01](https://linux-hardware.org/?probe=23667b0d01) | Mar 21, 2024 |
| Fujitsu       | LIFEBOOK E734               | [840661dcba](https://linux-hardware.org/?probe=840661dcba) | Mar 21, 2024 |
| Razer         | Blade 14 - RZ09-0482        | [1c48b858c2](https://linux-hardware.org/?probe=1c48b858c2) | Mar 20, 2024 |
| Dell          | XPS 15 9520                 | [d9ffc0afaf](https://linux-hardware.org/?probe=d9ffc0afaf) | Mar 20, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [0e0638700d](https://linux-hardware.org/?probe=0e0638700d) | Mar 20, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [e8c3803d3c](https://linux-hardware.org/?probe=e8c3803d3c) | Mar 20, 2024 |
| Acer          | Aspire A315-59              | [6c38602470](https://linux-hardware.org/?probe=6c38602470) | Mar 19, 2024 |
| HP            | EliteBook 840 G5            | [e47dc593db](https://linux-hardware.org/?probe=e47dc593db) | Mar 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [01f3900ba8](https://linux-hardware.org/?probe=01f3900ba8) | Mar 18, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [901b436ec2](https://linux-hardware.org/?probe=901b436ec2) | Mar 17, 2024 |
| ASUSTek       | TX201LA                     | [a558be2fb3](https://linux-hardware.org/?probe=a558be2fb3) | Mar 15, 2024 |
| Apple         | MacBookPro11,1              | [e8882adc5a](https://linux-hardware.org/?probe=e8882adc5a) | Mar 14, 2024 |
| Dell          | Latitude 5521               | [0e9ce42ba8](https://linux-hardware.org/?probe=0e9ce42ba8) | Mar 14, 2024 |
| Apple         | MacBookPro11,1              | [22fa6eee3e](https://linux-hardware.org/?probe=22fa6eee3e) | Mar 14, 2024 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [6d944c4cae](https://linux-hardware.org/?probe=6d944c4cae) | Mar 13, 2024 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [2417a59037](https://linux-hardware.org/?probe=2417a59037) | Mar 12, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [5d521873b9](https://linux-hardware.org/?probe=5d521873b9) | Mar 10, 2024 |
| ASUSTek       | X556UAK                     | [b3cf89e59b](https://linux-hardware.org/?probe=b3cf89e59b) | Mar 10, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [98c56ac1d0](https://linux-hardware.org/?probe=98c56ac1d0) | Mar 10, 2024 |
| Lenovo        | ThinkPad T460s 20F9002YC... | [b4721b40b9](https://linux-hardware.org/?probe=b4721b40b9) | Mar 10, 2024 |
| Dell          | XPS 15 9520                 | [c68539af0e](https://linux-hardware.org/?probe=c68539af0e) | Mar 07, 2024 |
| Lenovo        | Y50-70 20378                | [025b4a7dc8](https://linux-hardware.org/?probe=025b4a7dc8) | Mar 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dadfd2990c](https://linux-hardware.org/?probe=dadfd2990c) | Mar 06, 2024 |
| Acer          | Aspire 4820TG               | [a71f8d3b86](https://linux-hardware.org/?probe=a71f8d3b86) | Mar 06, 2024 |
| Acer          | Aspire 4820TG               | [bc8a80bc2f](https://linux-hardware.org/?probe=bc8a80bc2f) | Mar 05, 2024 |
| Lenovo        | ThinkPad X220 429143G       | [65eafaffa2](https://linux-hardware.org/?probe=65eafaffa2) | Mar 03, 2024 |
| HP            | EliteBook 845 14 inch G9... | [322cb37784](https://linux-hardware.org/?probe=322cb37784) | Mar 01, 2024 |
| HP            | ProBook 6540b               | [f37e1b63b3](https://linux-hardware.org/?probe=f37e1b63b3) | Feb 27, 2024 |
| HP            | ZBook 15u G3                | [3da083192b](https://linux-hardware.org/?probe=3da083192b) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [cd90e283a6](https://linux-hardware.org/?probe=cd90e283a6) | Feb 22, 2024 |
| Apple         | MacBookPro5,4               | [44c33e3e95](https://linux-hardware.org/?probe=44c33e3e95) | Feb 22, 2024 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c766f7fd38](https://linux-hardware.org/?probe=c766f7fd38) | Feb 19, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [0fc22adf3c](https://linux-hardware.org/?probe=0fc22adf3c) | Feb 18, 2024 |
| Lenovo        | Y50-70 20378                | [73e4b28a26](https://linux-hardware.org/?probe=73e4b28a26) | Feb 16, 2024 |
| Apple         | MacBookPro5,2               | [ef6d436777](https://linux-hardware.org/?probe=ef6d436777) | Feb 15, 2024 |
| Unknown       | Unknown                     | [d26317ef4d](https://linux-hardware.org/?probe=d26317ef4d) | Feb 15, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [64f9d9da39](https://linux-hardware.org/?probe=64f9d9da39) | Feb 15, 2024 |
| Acer          | Swift SF515-51T             | [15c680d4ba](https://linux-hardware.org/?probe=15c680d4ba) | Feb 14, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [d7abe330f5](https://linux-hardware.org/?probe=d7abe330f5) | Feb 14, 2024 |
| Lenovo        | ThinkPad Edge E531 68859... | [45a495ee7d](https://linux-hardware.org/?probe=45a495ee7d) | Feb 14, 2024 |
| HP            | EliteBook 820 G3            | [113a4666b5](https://linux-hardware.org/?probe=113a4666b5) | Feb 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [4c3d70277f](https://linux-hardware.org/?probe=4c3d70277f) | Feb 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [07b16ebca5](https://linux-hardware.org/?probe=07b16ebca5) | Feb 11, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [d54444ec11](https://linux-hardware.org/?probe=d54444ec11) | Feb 11, 2024 |
| TUXEDO        | InfinityBook 14 v2          | [7c8c800b34](https://linux-hardware.org/?probe=7c8c800b34) | Feb 11, 2024 |
| Unknown       | Unknown                     | [5b951e583b](https://linux-hardware.org/?probe=5b951e583b) | Feb 10, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [1d5c5c6bdc](https://linux-hardware.org/?probe=1d5c5c6bdc) | Feb 07, 2024 |
| Dell          | Latitude 5490               | [e98fe7a023](https://linux-hardware.org/?probe=e98fe7a023) | Feb 07, 2024 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [8be6ec6c09](https://linux-hardware.org/?probe=8be6ec6c09) | Feb 06, 2024 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [318c101ce1](https://linux-hardware.org/?probe=318c101ce1) | Feb 06, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [2de7038910](https://linux-hardware.org/?probe=2de7038910) | Feb 05, 2024 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [cc3af3614a](https://linux-hardware.org/?probe=cc3af3614a) | Feb 04, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [5b810ece22](https://linux-hardware.org/?probe=5b810ece22) | Feb 04, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [1e2603f833](https://linux-hardware.org/?probe=1e2603f833) | Feb 04, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | [7bfa72f494](https://linux-hardware.org/?probe=7bfa72f494) | Feb 01, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | [e17ca19651](https://linux-hardware.org/?probe=e17ca19651) | Feb 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [f7020952b0](https://linux-hardware.org/?probe=f7020952b0) | Jan 31, 2024 |
| Apple         | MacBookPro7,1               | [973c263365](https://linux-hardware.org/?probe=973c263365) | Jan 30, 2024 |
| Acer          | Swift SF314-56G             | [a6aac17123](https://linux-hardware.org/?probe=a6aac17123) | Jan 29, 2024 |
| Acer          | Swift SF314-56G             | [b259912831](https://linux-hardware.org/?probe=b259912831) | Jan 29, 2024 |
| Dell          | Latitude E7450              | [d427866522](https://linux-hardware.org/?probe=d427866522) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [275a598957](https://linux-hardware.org/?probe=275a598957) | Jan 26, 2024 |
| Apple         | MacBookPro8,1               | [bbacd3adf8](https://linux-hardware.org/?probe=bbacd3adf8) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [f9da9c2d2e](https://linux-hardware.org/?probe=f9da9c2d2e) | Jan 23, 2024 |
| HP            | ProBook 650 G2              | [9d5289d615](https://linux-hardware.org/?probe=9d5289d615) | Jan 21, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5df8be927b](https://linux-hardware.org/?probe=5df8be927b) | Jan 20, 2024 |
| HP            | ProBook 6570b               | [a70ac4fd39](https://linux-hardware.org/?probe=a70ac4fd39) | Jan 20, 2024 |
| ASUSTek       | K53SD                       | [0b62b854c0](https://linux-hardware.org/?probe=0b62b854c0) | Jan 20, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [4ec76f803c](https://linux-hardware.org/?probe=4ec76f803c) | Jan 20, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [fbcde01158](https://linux-hardware.org/?probe=fbcde01158) | Jan 20, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [9d2dbd96a5](https://linux-hardware.org/?probe=9d2dbd96a5) | Jan 19, 2024 |
| HP            | Pavilion dv7                | [f1d80ed16c](https://linux-hardware.org/?probe=f1d80ed16c) | Jan 19, 2024 |
| Dell          | Latitude 7330               | [d8b532bbee](https://linux-hardware.org/?probe=d8b532bbee) | Jan 19, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [70a816897a](https://linux-hardware.org/?probe=70a816897a) | Jan 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ae841d1af4](https://linux-hardware.org/?probe=ae841d1af4) | Jan 17, 2024 |
| HP            | EliteBook 840 G3            | [d88b2acd84](https://linux-hardware.org/?probe=d88b2acd84) | Jan 16, 2024 |
| Medion        | Scout E10                   | [10da5c077d](https://linux-hardware.org/?probe=10da5c077d) | Jan 16, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [ea56655c50](https://linux-hardware.org/?probe=ea56655c50) | Jan 14, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6f915e2f99](https://linux-hardware.org/?probe=6f915e2f99) | Jan 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [f68b62b601](https://linux-hardware.org/?probe=f68b62b601) | Jan 13, 2024 |
| Unknown       | Unknown                     | [13ba69dada](https://linux-hardware.org/?probe=13ba69dada) | Jan 13, 2024 |
| Dell          | Precision 3581              | [07c4e8e9b5](https://linux-hardware.org/?probe=07c4e8e9b5) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dac43c256](https://linux-hardware.org/?probe=7dac43c256) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [8d20d6aac5](https://linux-hardware.org/?probe=8d20d6aac5) | Jan 10, 2024 |
| VALE          | Notebook Classic C171V      | [8ecf376e28](https://linux-hardware.org/?probe=8ecf376e28) | Jan 10, 2024 |
| HP            | EliteBook 860 16 inch G1... | [efb5e0a5f7](https://linux-hardware.org/?probe=efb5e0a5f7) | Jan 09, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [b6445a9a78](https://linux-hardware.org/?probe=b6445a9a78) | Jan 09, 2024 |
| HP            | ProBook 6545b               | [278d4aea3c](https://linux-hardware.org/?probe=278d4aea3c) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [c16e85c0b1](https://linux-hardware.org/?probe=c16e85c0b1) | Jan 08, 2024 |
| Unknown       | Unknown                     | [3ea94ff775](https://linux-hardware.org/?probe=3ea94ff775) | Jan 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [8d2846dc8e](https://linux-hardware.org/?probe=8d2846dc8e) | Jan 08, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [fbc5c2c851](https://linux-hardware.org/?probe=fbc5c2c851) | Jan 08, 2024 |
| Medion        | S15449                      | [89a6d2fd3f](https://linux-hardware.org/?probe=89a6d2fd3f) | Jan 07, 2024 |
| HP            | EliteBook 840 G6            | [dfe9486065](https://linux-hardware.org/?probe=dfe9486065) | Jan 07, 2024 |
| Notebook      | P7xxDM-G                    | [7213fe2836](https://linux-hardware.org/?probe=7213fe2836) | Jan 06, 2024 |
| ASUSTek       | UX331UN                     | [dbfb01b59d](https://linux-hardware.org/?probe=dbfb01b59d) | Jan 06, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [90b8ceb64c](https://linux-hardware.org/?probe=90b8ceb64c) | Jan 05, 2024 |
| Dell          | XPS 15 9520                 | [5b8e6d2ed8](https://linux-hardware.org/?probe=5b8e6d2ed8) | Jan 04, 2024 |
| Dell          | XPS 15 9520                 | [c0b874f6b0](https://linux-hardware.org/?probe=c0b874f6b0) | Jan 04, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [183851c797](https://linux-hardware.org/?probe=183851c797) | Jan 04, 2024 |
| Dell          | XPS 15 9570                 | [08ce6196e7](https://linux-hardware.org/?probe=08ce6196e7) | Jan 03, 2024 |
| Apple         | MacBookPro7,1               | [476b332391](https://linux-hardware.org/?probe=476b332391) | Jan 03, 2024 |
| Clevo         | W150ER                      | [c451a552db](https://linux-hardware.org/?probe=c451a552db) | Jan 02, 2024 |
| Clevo         | W150ER                      | [28eb341269](https://linux-hardware.org/?probe=28eb341269) | Jan 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [a333274a33](https://linux-hardware.org/?probe=a333274a33) | Jan 02, 2024 |
| HP            | OMEN by Laptop              | [cb6a8b401a](https://linux-hardware.org/?probe=cb6a8b401a) | Jan 02, 2024 |
| HP            | Pavilion dv3                | [351a45926e](https://linux-hardware.org/?probe=351a45926e) | Jan 02, 2024 |
| Dell          | Latitude 5480               | [cf678e4c6d](https://linux-hardware.org/?probe=cf678e4c6d) | Dec 31, 2023 |
| Dell          | Latitude 5480               | [a1bc8df9e4](https://linux-hardware.org/?probe=a1bc8df9e4) | Dec 30, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [76f94ce16a](https://linux-hardware.org/?probe=76f94ce16a) | Dec 29, 2023 |
| Lenovo        | ThinkPad L390 20NSS29K00    | [a0860fbefb](https://linux-hardware.org/?probe=a0860fbefb) | Dec 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [a135119148](https://linux-hardware.org/?probe=a135119148) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| ASUSTek       | K73SV                       | [2a36715319](https://linux-hardware.org/?probe=2a36715319) | Dec 28, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ee7b7ce7cc](https://linux-hardware.org/?probe=ee7b7ce7cc) | Dec 24, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [dbfd9ef700](https://linux-hardware.org/?probe=dbfd9ef700) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | [5e8dc79e2c](https://linux-hardware.org/?probe=5e8dc79e2c) | Dec 22, 2023 |
| HP            | Laptop 15-dw3xxx            | [1b860f6465](https://linux-hardware.org/?probe=1b860f6465) | Dec 21, 2023 |
| HP            | Compaq 15                   | [e97b5e227e](https://linux-hardware.org/?probe=e97b5e227e) | Dec 21, 2023 |
| Acer          | Aspire 6930G                | [3013bf91cd](https://linux-hardware.org/?probe=3013bf91cd) | Dec 20, 2023 |
| Acer          | Aspire 6930G                | [6bc25073be](https://linux-hardware.org/?probe=6bc25073be) | Dec 20, 2023 |
| HP            | Compaq 15                   | [8224a8ab3d](https://linux-hardware.org/?probe=8224a8ab3d) | Dec 20, 2023 |
| HP            | Laptop 15-dw3xxx            | [17ce825521](https://linux-hardware.org/?probe=17ce825521) | Dec 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [85531f6788](https://linux-hardware.org/?probe=85531f6788) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [4715b83a8c](https://linux-hardware.org/?probe=4715b83a8c) | Dec 19, 2023 |
| Apple         | MacBookPro7,1               | [79499893b8](https://linux-hardware.org/?probe=79499893b8) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [45a0b94112](https://linux-hardware.org/?probe=45a0b94112) | Dec 18, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [4802066fc1](https://linux-hardware.org/?probe=4802066fc1) | Dec 17, 2023 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [6ac6a904be](https://linux-hardware.org/?probe=6ac6a904be) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [5a439f3bc5](https://linux-hardware.org/?probe=5a439f3bc5) | Dec 17, 2023 |
| Apple         | MacBookPro5,3               | [8143805d8a](https://linux-hardware.org/?probe=8143805d8a) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| HP            | ProBook 455 G2              | [4935ac1297](https://linux-hardware.org/?probe=4935ac1297) | Dec 17, 2023 |
| Apple         | MacBookPro8,1               | [f0ed04c975](https://linux-hardware.org/?probe=f0ed04c975) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Dell          | Vostro 3525                 | [c9de3b068b](https://linux-hardware.org/?probe=c9de3b068b) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [42b02a9d8e](https://linux-hardware.org/?probe=42b02a9d8e) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK E736               | [7f788f5265](https://linux-hardware.org/?probe=7f788f5265) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L50004MX    | [691f1ae82f](https://linux-hardware.org/?probe=691f1ae82f) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | [13b8795a4e](https://linux-hardware.org/?probe=13b8795a4e) | Dec 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e70de29c90](https://linux-hardware.org/?probe=e70de29c90) | Dec 13, 2023 |
| Dell          | XPS 13 9350                 | [149a7f254a](https://linux-hardware.org/?probe=149a7f254a) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | [1bb8694fda](https://linux-hardware.org/?probe=1bb8694fda) | Dec 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [e99a0bd1db](https://linux-hardware.org/?probe=e99a0bd1db) | Dec 12, 2023 |
| HP            | Notebook                    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [e340ad2e3a](https://linux-hardware.org/?probe=e340ad2e3a) | Dec 12, 2023 |
| Acer          | Aspire A515-56              | [ec970d7248](https://linux-hardware.org/?probe=ec970d7248) | Dec 10, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [9f6ce5cca9](https://linux-hardware.org/?probe=9f6ce5cca9) | Dec 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [a0670e0719](https://linux-hardware.org/?probe=a0670e0719) | Dec 09, 2023 |
| HP            | Pavilion dv6                | [3ffa0f12b7](https://linux-hardware.org/?probe=3ffa0f12b7) | Dec 08, 2023 |
| Toshiba       | Satellite L50-A-19P         | [cd3314169e](https://linux-hardware.org/?probe=cd3314169e) | Dec 08, 2023 |
| Dell          | XPS 9320                    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S0N10F    | [350da642e5](https://linux-hardware.org/?probe=350da642e5) | Dec 07, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [a7bb755e20](https://linux-hardware.org/?probe=a7bb755e20) | Dec 06, 2023 |
| HP            | ENVY 17                     | [b6048f107e](https://linux-hardware.org/?probe=b6048f107e) | Dec 06, 2023 |
| HP            | Laptop 15-dw3xxx            | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| Polaroid      | MP1464PR001                 | [bd3fa27cfe](https://linux-hardware.org/?probe=bd3fa27cfe) | Dec 02, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [b127bbd876](https://linux-hardware.org/?probe=b127bbd876) | Dec 01, 2023 |
| Medion        | Erazer P7643 MD60133        | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | EliteBook 840 14 inch G9... | [bbfe8e99fc](https://linux-hardware.org/?probe=bbfe8e99fc) | Nov 28, 2023 |
| Sony          | VPCF13M1E                   | [4a6e054f68](https://linux-hardware.org/?probe=4a6e054f68) | Nov 28, 2023 |
| Sony          | VPCSB1Z9E                   | [4eed6bb4ef](https://linux-hardware.org/?probe=4eed6bb4ef) | Nov 28, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ada466b7a0](https://linux-hardware.org/?probe=ada466b7a0) | Nov 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ade10d9872](https://linux-hardware.org/?probe=ade10d9872) | Nov 27, 2023 |
| Acer          | Aspire S5-371               | [d3efa32b61](https://linux-hardware.org/?probe=d3efa32b61) | Nov 26, 2023 |
| Dell          | Precision M6700             | [1817097d25](https://linux-hardware.org/?probe=1817097d25) | Nov 25, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [a58a5557e6](https://linux-hardware.org/?probe=a58a5557e6) | Nov 24, 2023 |
| PC Special... | Ionico 16                   | [2e5bce2d86](https://linux-hardware.org/?probe=2e5bce2d86) | Nov 24, 2023 |
| Lenovo        | Legion 9 16IRX8 83AG        | [f511dac11e](https://linux-hardware.org/?probe=f511dac11e) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [7cd9c24a07](https://linux-hardware.org/?probe=7cd9c24a07) | Nov 23, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [49ec5aa905](https://linux-hardware.org/?probe=49ec5aa905) | Nov 23, 2023 |
| Dell          | Latitude 5280               | [c2d1b79aeb](https://linux-hardware.org/?probe=c2d1b79aeb) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Acer          | Aspire A515-56              | [f1adb28e44](https://linux-hardware.org/?probe=f1adb28e44) | Nov 21, 2023 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [a8668f58d9](https://linux-hardware.org/?probe=a8668f58d9) | Nov 21, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [b7e16888b9](https://linux-hardware.org/?probe=b7e16888b9) | Nov 20, 2023 |
| Dell          | XPS 13 9370                 | [6ef90e528f](https://linux-hardware.org/?probe=6ef90e528f) | Nov 20, 2023 |
| Dell          | XPS 13 9370                 | [f3a2125fad](https://linux-hardware.org/?probe=f3a2125fad) | Nov 20, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [65f7027c84](https://linux-hardware.org/?probe=65f7027c84) | Nov 19, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | [a42aa89d19](https://linux-hardware.org/?probe=a42aa89d19) | Nov 16, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [a9704992fa](https://linux-hardware.org/?probe=a9704992fa) | Nov 16, 2023 |
| ASUSTek       | X705UAR                     | [11e3d24283](https://linux-hardware.org/?probe=11e3d24283) | Nov 15, 2023 |
| Apple         | MacBook6,1                  | [527e45b73b](https://linux-hardware.org/?probe=527e45b73b) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [bceb77e476](https://linux-hardware.org/?probe=bceb77e476) | Nov 15, 2023 |
| Sony          | SVF13N1L2ES                 | [e0b7ae1d8a](https://linux-hardware.org/?probe=e0b7ae1d8a) | Nov 14, 2023 |
| Sony          | SVF13N1L2ES                 | [1fe409a47f](https://linux-hardware.org/?probe=1fe409a47f) | Nov 14, 2023 |
| Apple         | MacBookPro8,1               | [c538f19c9e](https://linux-hardware.org/?probe=c538f19c9e) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| HP            | Laptop 17-cn2xxx            | [59c09c7be1](https://linux-hardware.org/?probe=59c09c7be1) | Nov 11, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [4c87f0ac2c](https://linux-hardware.org/?probe=4c87f0ac2c) | Nov 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3cad0a5b88](https://linux-hardware.org/?probe=3cad0a5b88) | Nov 10, 2023 |
| Valve         | Jupiter                     | [ca05263192](https://linux-hardware.org/?probe=ca05263192) | Nov 08, 2023 |
| Medion        | Crawler E25                 | [945026c1b8](https://linux-hardware.org/?probe=945026c1b8) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| Apple         | MacBookPro10,1              | [8efb96e5d7](https://linux-hardware.org/?probe=8efb96e5d7) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | [e6459bb42f](https://linux-hardware.org/?probe=e6459bb42f) | Nov 04, 2023 |
| HP            | EliteBook 850 G2            | [36646aca12](https://linux-hardware.org/?probe=36646aca12) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Dell          | XPS 13 9380                 | [ee12470303](https://linux-hardware.org/?probe=ee12470303) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| HP            | Laptop 15-dw3xxx            | [d371b7299d](https://linux-hardware.org/?probe=d371b7299d) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8c2a216d7b](https://linux-hardware.org/?probe=8c2a216d7b) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [6cce294b99](https://linux-hardware.org/?probe=6cce294b99) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [c985fdb0b7](https://linux-hardware.org/?probe=c985fdb0b7) | Nov 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [3479b99099](https://linux-hardware.org/?probe=3479b99099) | Nov 01, 2023 |
| Acer          | Predator PH18-71            | [a0393f21c9](https://linux-hardware.org/?probe=a0393f21c9) | Nov 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [924f7f81ce](https://linux-hardware.org/?probe=924f7f81ce) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| HP            | ENVY 17                     | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| Acer          | Aspire V3-772G              | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| HP            | ENVY 17                     | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Notebook      | V1x0PNPx                    | [f1e27c662a](https://linux-hardware.org/?probe=f1e27c662a) | Oct 27, 2023 |
| System76      | Darter Pro                  | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [39e846913d](https://linux-hardware.org/?probe=39e846913d) | Oct 25, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [1406d2f4d5](https://linux-hardware.org/?probe=1406d2f4d5) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [56fa067caa](https://linux-hardware.org/?probe=56fa067caa) | Oct 24, 2023 |
| Dell          | Latitude 5520               | [0c8da2f95a](https://linux-hardware.org/?probe=0c8da2f95a) | Oct 24, 2023 |
| Apple         | MacBookPro14,1              | [557e6a2f27](https://linux-hardware.org/?probe=557e6a2f27) | Oct 21, 2023 |
| Dell          | Latitude E6530              | [e3126b26df](https://linux-hardware.org/?probe=e3126b26df) | Oct 19, 2023 |
| HP            | EliteBook Folio 1040 G3     | [cf4c60a0a8](https://linux-hardware.org/?probe=cf4c60a0a8) | Oct 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [cf522294f8](https://linux-hardware.org/?probe=cf522294f8) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [7f5a3b8e10](https://linux-hardware.org/?probe=7f5a3b8e10) | Oct 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2a5d18299e](https://linux-hardware.org/?probe=2a5d18299e) | Oct 15, 2023 |
| Dell          | XPS 15 9550                 | [4bb651a7a6](https://linux-hardware.org/?probe=4bb651a7a6) | Oct 11, 2023 |
| Dell          | XPS 15 9550                 | [52bbb0243a](https://linux-hardware.org/?probe=52bbb0243a) | Oct 11, 2023 |
| Dell          | XPS 15 9510                 | [89748db0f1](https://linux-hardware.org/?probe=89748db0f1) | Oct 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8dcc2d1ec2](https://linux-hardware.org/?probe=8dcc2d1ec2) | Oct 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [edd7c9e07a](https://linux-hardware.org/?probe=edd7c9e07a) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | [dae43772d4](https://linux-hardware.org/?probe=dae43772d4) | Oct 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| Acer          | Aspire 5741G                | [ade2b406fd](https://linux-hardware.org/?probe=ade2b406fd) | Oct 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [0354977d6c](https://linux-hardware.org/?probe=0354977d6c) | Oct 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [faea5bdeba](https://linux-hardware.org/?probe=faea5bdeba) | Oct 07, 2023 |
| Dell          | Latitude 7480               | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3fdbdfe773](https://linux-hardware.org/?probe=3fdbdfe773) | Oct 03, 2023 |
| Acer          | Swift SFE16-43              | [54231f7059](https://linux-hardware.org/?probe=54231f7059) | Oct 02, 2023 |
| Acer          | Swift SFE16-43              | [045606333c](https://linux-hardware.org/?probe=045606333c) | Oct 02, 2023 |
| Fujitsu       | STYLISTIC R726              | [a4c3a19501](https://linux-hardware.org/?probe=a4c3a19501) | Oct 02, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | [c71241f73d](https://linux-hardware.org/?probe=c71241f73d) | Oct 01, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | [b1af5494c8](https://linux-hardware.org/?probe=b1af5494c8) | Oct 01, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| Dell          | Latitude 5420               | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| Dell          | XPS 15 9520                 | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| Acer          | Aspire A315-34              | [16c09be7f2](https://linux-hardware.org/?probe=16c09be7f2) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [16f80f70a8](https://linux-hardware.org/?probe=16f80f70a8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| HP            | ProBook 650 G1              | [06d67bab4a](https://linux-hardware.org/?probe=06d67bab4a) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| HP            | EliteBook Folio 1040 G3     | [38a985d781](https://linux-hardware.org/?probe=38a985d781) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [1b8a46fc57](https://linux-hardware.org/?probe=1b8a46fc57) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1400ef978f](https://linux-hardware.org/?probe=1400ef978f) | Sep 12, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Lenovo        | G50-30 80G0                 | [bb0f6ff00d](https://linux-hardware.org/?probe=bb0f6ff00d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Apple         | MacBookPro11,2              | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | K53SD                       | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Acer          | Aspire 7745G                | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| HP            | Compaq 15                   | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| Lenovo        | ThinkPad X200 7458AL7       | [763d0f46f4](https://linux-hardware.org/?probe=763d0f46f4) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [14805d08fd](https://linux-hardware.org/?probe=14805d08fd) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [f4af40c36f](https://linux-hardware.org/?probe=f4af40c36f) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [131e36d487](https://linux-hardware.org/?probe=131e36d487) | Aug 22, 2023 |
| Dell          | Latitude E7440              | [7a5bd0f1a6](https://linux-hardware.org/?probe=7a5bd0f1a6) | Aug 19, 2023 |
| Dell          | XPS 13 9350                 | [d3aac86eac](https://linux-hardware.org/?probe=d3aac86eac) | Aug 16, 2023 |
| Dell          | XPS 13 9350                 | [7032d8da96](https://linux-hardware.org/?probe=7032d8da96) | Aug 16, 2023 |
| Sony          | VGN-SR19VN                  | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| PC Special... | Ionico 16                   | [9f04bd8095](https://linux-hardware.org/?probe=9f04bd8095) | Aug 16, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bcda0258e5](https://linux-hardware.org/?probe=bcda0258e5) | Aug 12, 2023 |
| MSI           | Summit E14Evo A12M          | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| GPD           | P2 MAX                      | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | EliteBook 820 G1            | [62889fd683](https://linux-hardware.org/?probe=62889fd683) | Aug 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Dell          | XPS 9320                    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| PC Special... | Ionico 16                   | [0839bbc721](https://linux-hardware.org/?probe=0839bbc721) | Aug 03, 2023 |
| Acer          | TravelMate P614-51-G2       | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Dell          | Latitude E6330              | [75d54a8988](https://linux-hardware.org/?probe=75d54a8988) | Aug 03, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [5bbbd1f3d4](https://linux-hardware.org/?probe=5bbbd1f3d4) | Aug 02, 2023 |
| Schenker      | XMG FOCUS (Mid 2021)        | [d7fa14789f](https://linux-hardware.org/?probe=d7fa14789f) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| Acer          | Aspire A315-34              | [add6831dcd](https://linux-hardware.org/?probe=add6831dcd) | Jul 31, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7cb3479a69](https://linux-hardware.org/?probe=7cb3479a69) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [5518dab193](https://linux-hardware.org/?probe=5518dab193) | Jul 29, 2023 |
| Acer          | Aspire E5-511               | [aef96d4eb8](https://linux-hardware.org/?probe=aef96d4eb8) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| PC Special... | Ionico 16                   | [86d9ab8b73](https://linux-hardware.org/?probe=86d9ab8b73) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | [6ea424234a](https://linux-hardware.org/?probe=6ea424234a) | Jul 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [9c8b9571d9](https://linux-hardware.org/?probe=9c8b9571d9) | Jul 27, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | [03152e1c57](https://linux-hardware.org/?probe=03152e1c57) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [dc537ae22a](https://linux-hardware.org/?probe=dc537ae22a) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cff40caac1](https://linux-hardware.org/?probe=cff40caac1) | Jul 24, 2023 |
| Dell          | Latitude 7480               | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| ASUSTek       | G551JK                      | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a8f79a71f7](https://linux-hardware.org/?probe=a8f79a71f7) | Jul 20, 2023 |
| Acer          | Predator PH317-56           | [248af0e35c](https://linux-hardware.org/?probe=248af0e35c) | Jul 18, 2023 |
| HP            | Pavilion dm1                | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [798ddca1c4](https://linux-hardware.org/?probe=798ddca1c4) | Jul 16, 2023 |
| HP            | Pavilion dm1                | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Dell          | XPS 12 9Q23                 | [5fb9db838e](https://linux-hardware.org/?probe=5fb9db838e) | Jul 12, 2023 |
| ASUSTek       | K53SD                       | [61da77f999](https://linux-hardware.org/?probe=61da77f999) | Jul 09, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ProBook 650 G1              | [9b8d05afca](https://linux-hardware.org/?probe=9b8d05afca) | Jul 08, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [4ff583eb14](https://linux-hardware.org/?probe=4ff583eb14) | Jul 05, 2023 |
| TUXEDO        | InfinityBook 14 v2          | [9447ac0693](https://linux-hardware.org/?probe=9447ac0693) | Jul 02, 2023 |
| Apple         | MacBookPro8,1               | [566b883024](https://linux-hardware.org/?probe=566b883024) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| Star Labs     | LabTop                      | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Star Labs     | LabTop                      | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| ASUSTek       | K53SD                       | [66f2fbfdf4](https://linux-hardware.org/?probe=66f2fbfdf4) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Notebook      | NLxxPUx                     | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Lenovo        | G50-30 80G0                 | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | [223c8d15d4](https://linux-hardware.org/?probe=223c8d15d4) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| Apple         | MacBookPro8,1               | [f008d4c0db](https://linux-hardware.org/?probe=f008d4c0db) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| Apple         | MacBookPro8,1               | [c45597704a](https://linux-hardware.org/?probe=c45597704a) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | [8ea9d60a21](https://linux-hardware.org/?probe=8ea9d60a21) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| Acer          | Aspire V3-772G              | [f077d744cb](https://linux-hardware.org/?probe=f077d744cb) | Jun 04, 2023 |
| Dell          | Latitude E6420              | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| Dell          | Latitude 7490               | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| GPD           | P2 MAX                      | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Acer          | Swift SF514-52T             | [246b95d20f](https://linux-hardware.org/?probe=246b95d20f) | May 24, 2023 |
| Acer          | Aspire V3-772               | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Dell          | Latitude E6530              | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Valve         | Jupiter                     | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Dell          | Latitude E6530              | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| Dell          | Latitude 5520               | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [d71435c79a](https://linux-hardware.org/?probe=d71435c79a) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [62e7f77fdc](https://linux-hardware.org/?probe=62e7f77fdc) | May 12, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f6c8b6c33e](https://linux-hardware.org/?probe=f6c8b6c33e) | May 12, 2023 |
| Acer          | Aspire 5332                 | [e74870bf17](https://linux-hardware.org/?probe=e74870bf17) | May 10, 2023 |
| HP            | Compaq 6910p                | [c17dc1abcf](https://linux-hardware.org/?probe=c17dc1abcf) | May 08, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [71ec2fc5ea](https://linux-hardware.org/?probe=71ec2fc5ea) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [6936dcf305](https://linux-hardware.org/?probe=6936dcf305) | May 03, 2023 |
| Acer          | Predator PH18-71            | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Dell          | Vostro 3558                 | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| Acer          | Aspire E5-575G              | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Dell          | Latitude 5520               | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| HP            | EliteBook 820 G1            | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| Dell          | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| Dell          | XPS 17 9720                 | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [b076a9a807](https://linux-hardware.org/?probe=b076a9a807) | Apr 18, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| Dell          | Latitude 7530               | [133059c3d6](https://linux-hardware.org/?probe=133059c3d6) | Apr 16, 2023 |
| ASUSTek       | X756UJ                      | [a374f8dd26](https://linux-hardware.org/?probe=a374f8dd26) | Apr 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [ec028424ea](https://linux-hardware.org/?probe=ec028424ea) | Apr 09, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | [32f5d43e96](https://linux-hardware.org/?probe=32f5d43e96) | Apr 04, 2023 |
| Apple         | MacBookAir6,1               | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| Sony          | VPCF22C5E                   | [9d122b8bdd](https://linux-hardware.org/?probe=9d122b8bdd) | Apr 03, 2023 |
| Valve         | Jupiter                     | [6f3e488e2b](https://linux-hardware.org/?probe=6f3e488e2b) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [17fb0ed43a](https://linux-hardware.org/?probe=17fb0ed43a) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| HP            | Unknown                     | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [e1d01990f4](https://linux-hardware.org/?probe=e1d01990f4) | Mar 27, 2023 |
| HP            | EliteBook 840 G5            | [405ce5a9c8](https://linux-hardware.org/?probe=405ce5a9c8) | Mar 27, 2023 |
| Fujitsu       | LIFEBOOK E736               | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| Acer          | Predator G9-791             | [1f820516a3](https://linux-hardware.org/?probe=1f820516a3) | Mar 26, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [74be0519cc](https://linux-hardware.org/?probe=74be0519cc) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| HP            | ProBook 430 G4              | [6c83c2a089](https://linux-hardware.org/?probe=6c83c2a089) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Google        | Lillipup                    | [3eca64113c](https://linux-hardware.org/?probe=3eca64113c) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Valve         | Jupiter                     | [bfdb73f825](https://linux-hardware.org/?probe=bfdb73f825) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| ASUSTek       | UX32A                       | [05121bc6af](https://linux-hardware.org/?probe=05121bc6af) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude E6440              | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Notebook      | NS50MU                      | [f5e64711f3](https://linux-hardware.org/?probe=f5e64711f3) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | [aa5eb19101](https://linux-hardware.org/?probe=aa5eb19101) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [55fe24706a](https://linux-hardware.org/?probe=55fe24706a) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d7535fd29e](https://linux-hardware.org/?probe=d7535fd29e) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5b8db1d628](https://linux-hardware.org/?probe=5b8db1d628) | Mar 10, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [e280beba92](https://linux-hardware.org/?probe=e280beba92) | Mar 08, 2023 |
| Fujitsu       | CELSIUS H780                | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Acer          | Predator PH517-61           | [359903fe58](https://linux-hardware.org/?probe=359903fe58) | Mar 07, 2023 |
| Lenovo        | Z51-70 80K6                 | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Lenovo        | ThinkPad E590 20NB000YMZ    | [fb05511be8](https://linux-hardware.org/?probe=fb05511be8) | Mar 05, 2023 |
| HP            | Compaq 15                   | [5c8a185273](https://linux-hardware.org/?probe=5c8a185273) | Mar 05, 2023 |
| HP            | EliteBook 8540w             | [e57a377381](https://linux-hardware.org/?probe=e57a377381) | Mar 05, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [cacb713046](https://linux-hardware.org/?probe=cacb713046) | Mar 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [117d283b7a](https://linux-hardware.org/?probe=117d283b7a) | Mar 02, 2023 |
| Notebook      | PCx0Dx                      | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Lenovo        | ThinkPad Edge E531 6885D... | [0780656106](https://linux-hardware.org/?probe=0780656106) | Mar 01, 2023 |
| HP            | EliteBook 845 14 inch G9... | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Acer          | Aspire V3-371               | [0855d319b4](https://linux-hardware.org/?probe=0855d319b4) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | GL702VM                     | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| HP            | ZBook 14u G5                | [db7a713397](https://linux-hardware.org/?probe=db7a713397) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| HP            | ProBook 4720s               | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| HP            | EliteBook 865 16 inch G9... | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| HP            | Pavilion dv7                | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| HP            | Pavilion dv7                | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Dell          | XPS 13 9360                 | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | B50-10 80QR                 | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | ProBook 650 G4              | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Acer          | Aspire E5-511               | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Acer          | Predator G9-591             | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| Valve         | Jupiter                     | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | X556UAK                     | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| HP            | ENVY dv7                    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Notebook      | L140PU                      | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Dell          | Latitude E6420              | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| Dell          | XPS 9320                    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Apple         | MacBookPro4,1               | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| Dell          | Precision 5520              | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Medion        | S15449                      | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| Samsung       | RC530/RC730                 | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| HP            | ProBook 640 G2              | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| ASUSTek       | K55VJ                       | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| Gigabyte      | RC14UD                      | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 143       | 9.23%   |
| Ubuntu 22.04                 | 92        | 5.94%   |
| Ubuntu 18.04                 | 90        | 5.81%   |
| Debian 11                    | 39        | 2.52%   |
| Debian 12                    | 36        | 2.32%   |
| Arch Rolling                 | 36        | 2.32%   |
| Ubuntu 24.04                 | 35        | 2.26%   |
| Linux Mint 20.3              | 33        | 2.13%   |
| Pop!_OS 22.04                | 30        | 1.94%   |
| Zorin 16                     | 29        | 1.87%   |
| Fedora 39                    | 29        | 1.87%   |
| Debian 10                    | 25        | 1.61%   |
| OpenMandriva 4.3             | 22        | 1.42%   |
| Fedora 40                    | 22        | 1.42%   |
| Linux Mint 21.2              | 21        | 1.35%   |
| Manjaro                      | 20        | 1.29%   |
| Linux Mint 21.1              | 20        | 1.29%   |
| Linux Mint 20.2              | 20        | 1.29%   |
| Linux Mint 20.1              | 20        | 1.29%   |
| Linux Mint 21.3              | 19        | 1.23%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 1.16%   |
| Ubuntu 23.10                 | 17        | 1.1%    |
| Ubuntu 21.10                 | 17        | 1.1%    |
| KDE neon 20.04               | 17        | 1.1%    |
| Fedora 38                    | 17        | 1.1%    |
| Zorin 17                     | 16        | 1.03%   |
| OpenMandriva 4.2             | 16        | 1.03%   |
| ArcoLinux Rolling            | 15        | 0.97%   |
| Ubuntu 20.10                 | 14        | 0.9%    |
| Linux Mint 21                | 14        | 0.9%    |
| Fedora 37                    | 14        | 0.9%    |
| Ubuntu 22.10                 | 13        | 0.84%   |
| Ubuntu 19.10                 | 13        | 0.84%   |
| Fedora 41                    | 13        | 0.84%   |
| Fedora 34                    | 13        | 0.84%   |
| EndeavourOS Rolling          | 13        | 0.84%   |
| Pop!_OS 21.04                | 12        | 0.77%   |
| Linux Mint 19.3              | 12        | 0.77%   |
| Arch                         | 12        | 0.77%   |
| Pop!_OS 20.10                | 11        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 424       | 29.53%  |
| Linux Mint    | 158       | 11%     |
| Fedora        | 142       | 9.89%   |
| Debian        | 112       | 7.8%    |
| OpenMandriva  | 85        | 5.92%   |
| Pop!_OS       | 64        | 4.46%   |
| Zorin         | 53        | 3.69%   |
| Manjaro       | 48        | 3.34%   |
| Arch          | 47        | 3.27%   |
| Kubuntu       | 30        | 2.09%   |
| openSUSE      | 24        | 1.67%   |
| KDE neon      | 21        | 1.46%   |
| Xubuntu       | 18        | 1.25%   |
| ArcoLinux     | 18        | 1.25%   |
| ROSA          | 15        | 1.04%   |
| EndeavourOS   | 14        | 0.97%   |
| Ubuntu MATE   | 12        | 0.84%   |
| Elementary    | 12        | 0.84%   |
| Lubuntu       | 11        | 0.77%   |
| Kali          | 11        | 0.77%   |
| Gentoo        | 11        | 0.77%   |
| LMDE          | 10        | 0.7%    |
| SteamOS       | 8         | 0.56%   |
| Endless       | 6         | 0.42%   |
| Ubuntu Unity  | 5         | 0.35%   |
| MX            | 5         | 0.35%   |
| BlackPanther  | 5         | 0.35%   |
| Void Linux    | 4         | 0.28%   |
| Ubuntu Budgie | 4         | 0.28%   |
| RHEL          | 4         | 0.28%   |
| Parrot        | 4         | 0.28%   |
| NixOS         | 4         | 0.28%   |
| Feren OS      | 4         | 0.28%   |
| Clear Linux   | 4         | 0.28%   |
| Artix         | 4         | 0.28%   |
| TUXEDO OS     | 3         | 0.21%   |
| Garuda Linux  | 3         | 0.21%   |
| Ubuntu Studio | 2         | 0.14%   |
| Q4OS          | 2         | 0.14%   |
| Guix          | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 20        | 1.17%   |
| 5.15.0-56-generic        | 18        | 1.05%   |
| 5.10.14-desktop-1omv4002 | 16        | 0.93%   |
| 5.15.0-91-generic        | 15        | 0.87%   |
| 5.4.0-42-generic         | 14        | 0.82%   |
| 5.4.0-52-generic         | 12        | 0.7%    |
| 6.8.0-48-generic         | 11        | 0.64%   |
| 5.19.0-35-generic        | 11        | 0.64%   |
| 5.15.0-58-generic        | 11        | 0.64%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.58%   |
| 5.4.0-47-generic         | 10        | 0.58%   |
| 5.10.0-21-amd64          | 10        | 0.58%   |
| 6.6.2-desktop-1omv2390   | 9         | 0.52%   |
| 6.5.0-35-generic         | 9         | 0.52%   |
| 5.4.0-58-generic         | 9         | 0.52%   |
| 5.15.0-52-generic        | 9         | 0.52%   |
| 6.8.0-45-generic         | 8         | 0.47%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.47%   |
| 5.4.0-91-generic         | 8         | 0.47%   |
| 5.4.0-80-generic         | 8         | 0.47%   |
| 5.3.0-28-generic         | 8         | 0.47%   |
| 5.15.0-60-generic        | 8         | 0.47%   |
| 6.8.0-49-generic         | 7         | 0.41%   |
| 6.8.0-40-generic         | 7         | 0.41%   |
| 6.8.0-31-generic         | 7         | 0.41%   |
| 6.5.0-28-generic         | 7         | 0.41%   |
| 6.2.0-37-generic         | 7         | 0.41%   |
| 5.8.0-59-generic         | 7         | 0.41%   |
| 5.8.0-55-generic         | 7         | 0.41%   |
| 5.4.0-72-generic         | 7         | 0.41%   |
| 5.4.0-65-generic         | 7         | 0.41%   |
| 5.4.0-62-generic         | 7         | 0.41%   |
| 5.4.0-48-generic         | 7         | 0.41%   |
| 5.15.0-48-generic        | 7         | 0.41%   |
| 5.13.0-30-generic        | 7         | 0.41%   |
| 5.11.0-43-generic        | 7         | 0.41%   |
| 5.10.0-8-amd64           | 7         | 0.41%   |
| 5.0.0-37-generic         | 7         | 0.41%   |
| 6.5.6-300.fc39.x86_64    | 6         | 0.35%   |
| 6.5.0-26-generic         | 6         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 188       | 11.7%   |
| 5.15.0  | 155       | 9.65%   |
| 6.5.0   | 62        | 3.86%   |
| 6.8.0   | 61        | 3.8%    |
| 5.8.0   | 60        | 3.73%   |
| 4.15.0  | 59        | 3.67%   |
| 5.13.0  | 55        | 3.42%   |
| 5.11.0  | 55        | 3.42%   |
| 5.10.0  | 48        | 2.99%   |
| 6.2.0   | 45        | 2.8%    |
| 6.1.0   | 45        | 2.8%    |
| 5.19.0  | 45        | 2.8%    |
| 5.3.0   | 40        | 2.49%   |
| 5.0.0   | 26        | 1.62%   |
| 4.19.0  | 26        | 1.62%   |
| 5.16.7  | 20        | 1.24%   |
| 4.18.0  | 19        | 1.18%   |
| 5.10.14 | 17        | 1.06%   |
| 6.2.6   | 12        | 0.75%   |
| 5.14.0  | 11        | 0.68%   |
| 6.1.1   | 10        | 0.62%   |
| 6.6.2   | 9         | 0.56%   |
| 6.12.1  | 9         | 0.56%   |
| 5.17.5  | 8         | 0.5%    |
| 6.5.6   | 7         | 0.44%   |
| 6.0.0   | 7         | 0.44%   |
| 5.6.0   | 7         | 0.44%   |
| 6.6.10  | 6         | 0.37%   |
| 6.4.11  | 6         | 0.37%   |
| 6.11.5  | 6         | 0.37%   |
| 6.8.7   | 5         | 0.31%   |
| 6.6.9   | 5         | 0.31%   |
| 6.3.5   | 5         | 0.31%   |
| 6.11.0  | 5         | 0.31%   |
| 6.0.15  | 5         | 0.31%   |
| 6.0.12  | 5         | 0.31%   |
| 5.6.14  | 5         | 0.31%   |
| 6.9.3   | 4         | 0.25%   |
| 6.6.8   | 4         | 0.25%   |
| 6.6.6   | 4         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 196       | 12.36%  |
| 5.15    | 179       | 11.29%  |
| 6.5     | 84        | 5.3%    |
| 6.8     | 81        | 5.11%   |
| 5.10    | 79        | 4.98%   |
| 6.1     | 75        | 4.73%   |
| 5.8     | 71        | 4.48%   |
| 5.11    | 71        | 4.48%   |
| 6.2     | 67        | 4.22%   |
| 5.13    | 66        | 4.16%   |
| 4.15    | 59        | 3.72%   |
| 5.19    | 52        | 3.28%   |
| 6.6     | 47        | 2.96%   |
| 5.3     | 46        | 2.9%    |
| 5.16    | 35        | 2.21%   |
| 4.19    | 31        | 1.95%   |
| 6.0     | 30        | 1.89%   |
| 5.0     | 28        | 1.77%   |
| 4.18    | 25        | 1.58%   |
| 5.17    | 24        | 1.51%   |
| 6.4     | 23        | 1.45%   |
| 6.11    | 21        | 1.32%   |
| 6.12    | 18        | 1.13%   |
| 5.6     | 18        | 1.13%   |
| 5.14    | 18        | 1.13%   |
| 6.3     | 17        | 1.07%   |
| 5.9     | 17        | 1.07%   |
| 6.9     | 16        | 1.01%   |
| 6.10    | 16        | 1.01%   |
| 5.18    | 14        | 0.88%   |
| 5.12    | 12        | 0.76%   |
| 6.7     | 11        | 0.69%   |
| 5.7     | 11        | 0.69%   |
| 4.9     | 11        | 0.69%   |
| 5.5     | 6         | 0.38%   |
| 4.4     | 3         | 0.19%   |
| 5.2     | 2         | 0.13%   |
| 4.14    | 2         | 0.13%   |
| 4.8     | 1         | 0.06%   |
| 4.20    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1355      | 98.26%  |
| i686    | 22        | 1.6%    |
| aarch64 | 2         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 662       | 45.53%  |
| KDE5            | 223       | 15.34%  |
| X-Cinnamon      | 143       | 9.83%   |
| Unknown         | 133       | 9.15%   |
| XFCE            | 85        | 5.85%   |
| MATE            | 35        | 2.41%   |
| KDE             | 20        | 1.38%   |
| LXQt            | 19        | 1.31%   |
| Cinnamon        | 18        | 1.24%   |
| KDE6            | 17        | 1.17%   |
| i3              | 16        | 1.1%    |
| LXDE            | 15        | 1.03%   |
| Pantheon        | 12        | 0.83%   |
| KDE4            | 11        | 0.76%   |
| GNOME Flashback | 10        | 0.69%   |
| Budgie          | 7         | 0.48%   |
| Hyprland        | 5         | 0.34%   |
| bspwm           | 4         | 0.28%   |
| Unity           | 3         | 0.21%   |
| qtile           | 3         | 0.21%   |
| GNUstep         | 2         | 0.14%   |
| awesome         | 2         | 0.14%   |
| Trinity         | 1         | 0.07%   |
| sway            | 1         | 0.07%   |
| openbox         | 1         | 0.07%   |
| ICEWM           | 1         | 0.07%   |
| herbstluftwm    | 1         | 0.07%   |
| GNOME Classic   | 1         | 0.07%   |
| fluxbox         | 1         | 0.07%   |
| Enlightenment   | 1         | 0.07%   |
| Deepin          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 942       | 65.37%  |
| Wayland | 393       | 27.27%  |
| Unknown | 81        | 5.62%   |
| Tty     | 25        | 1.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 583       | 40.26%  |
| GDM3    | 220       | 15.19%  |
| SDDM    | 201       | 13.88%  |
| LightDM | 201       | 13.88%  |
| GDM     | 186       | 12.85%  |
| TDM     | 41        | 2.83%   |
| KDM     | 8         | 0.55%   |
| XDM     | 2         | 0.14%   |
| SLiM    | 2         | 0.14%   |
| LY-DM   | 2         | 0.14%   |
| LXDM    | 1         | 0.07%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 522       | 36.45%  |
| de_CH      | 340       | 23.74%  |
| Unknown    | 128       | 8.94%   |
| de_DE      | 108       | 7.54%   |
| fr_CH      | 104       | 7.26%   |
| en_GB      | 73        | 5.1%    |
| fr_FR      | 39        | 2.72%   |
| C          | 29        | 2.03%   |
| it_IT      | 16        | 1.12%   |
| it_CH      | 16        | 1.12%   |
| pt_PT      | 10        | 0.7%    |
| es_ES      | 7         | 0.49%   |
| ru_RU      | 5         | 0.35%   |
| pl_PL      | 5         | 0.35%   |
| en_CH      | 4         | 0.28%   |
| de_AT      | 4         | 0.28%   |
| en_IE      | 3         | 0.21%   |
| en_AU      | 3         | 0.21%   |
| en_CA      | 2         | 0.14%   |
| de_LI      | 2         | 0.14%   |
| tr_TR      | 1         | 0.07%   |
| sk_SK      | 1         | 0.07%   |
| ru_UA      | 1         | 0.07%   |
| POSIX      | 1         | 0.07%   |
| nl_BE      | 1         | 0.07%   |
| hsb_DE     | 1         | 0.07%   |
| fi_FI      | 1         | 0.07%   |
| en_AG      | 1         | 0.07%   |
| de_IT      | 1         | 0.07%   |
| de_CH.UTF8 | 1         | 0.07%   |
| ca_ES      | 1         | 0.07%   |
| C.UTF8     | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 845       | 59.8%   |
| BIOS | 568       | 40.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1027      | 71.37%  |
| Btrfs   | 193       | 13.41%  |
| Overlay | 84        | 5.84%   |
| Tmpfs   | 61        | 4.24%   |
| Unknown | 37        | 2.57%   |
| Xfs     | 16        | 1.11%   |
| Zfs     | 12        | 0.83%   |
| Ext2    | 5         | 0.35%   |
| Ext3    | 3         | 0.21%   |
| F2fs    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 707       | 49.89%  |
| Unknown | 588       | 41.5%   |
| MBR     | 122       | 8.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1250      | 88.78%  |
| Yes       | 158       | 11.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1080      | 76.87%  |
| Yes       | 325       | 23.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 394       | 28.59%  |
| Hewlett-Packard     | 292       | 21.19%  |
| Dell                | 162       | 11.76%  |
| Acer                | 129       | 9.36%   |
| ASUSTek Computer    | 120       | 8.71%   |
| Apple               | 69        | 5.01%   |
| Sony                | 20        | 1.45%   |
| TUXEDO              | 18        | 1.31%   |
| Toshiba             | 17        | 1.23%   |
| Notebook            | 14        | 1.02%   |
| Medion              | 14        | 1.02%   |
| MSI                 | 13        | 0.94%   |
| Samsung Electronics | 11        | 0.8%    |
| HUAWEI              | 11        | 0.8%    |
| Fujitsu             | 10        | 0.73%   |
| Valve               | 8         | 0.58%   |
| Razer               | 7         | 0.51%   |
| Schenker            | 5         | 0.36%   |
| Clevo               | 4         | 0.29%   |
| Alienware           | 4         | 0.29%   |
| Unknown             | 4         | 0.29%   |
| Timi                | 3         | 0.22%   |
| System76            | 3         | 0.22%   |
| Polaroid            | 3         | 0.22%   |
| PC Specialist       | 3         | 0.22%   |
| Packard Bell        | 3         | 0.22%   |
| GPD                 | 3         | 0.22%   |
| Google              | 3         | 0.22%   |
| whyopencomputing    | 2         | 0.15%   |
| VALE                | 2         | 0.15%   |
| TrekStor            | 2         | 0.15%   |
| Purism              | 2         | 0.15%   |
| MPMAN               | 2         | 0.15%   |
| Gigabyte Technology | 2         | 0.15%   |
| Fujitsu Siemens     | 2         | 0.15%   |
| Star Labs           | 1         | 0.07%   |
| SLIMBOOK            | 1         | 0.07%   |
| Shuttle             | 1         | 0.07%   |
| Quanta              | 1         | 0.07%   |
| Quanmax             | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                        | 10        | 0.73%   |
| Unknown                                    | 10        | 0.73%   |
| HP Pavilion dv7                            | 8         | 0.58%   |
| HP EliteBook 840 G5                        | 8         | 0.58%   |
| HP Pavilion dv6                            | 7         | 0.51%   |
| Dell Latitude 7490                         | 7         | 0.51%   |
| Apple MacBookPro9,2                        | 7         | 0.51%   |
| Valve Jupiter                              | 6         | 0.44%   |
| HP Notebook                                | 6         | 0.44%   |
| HP EliteBook 840 G6                        | 6         | 0.44%   |
| Dell XPS 15 9570                           | 6         | 0.44%   |
| HP ProBook 440 G8 Notebook PC              | 5         | 0.36%   |
| HP ENVY 15                                 | 5         | 0.36%   |
| Dell XPS 15 7590                           | 5         | 0.36%   |
| Dell XPS 13 9370                           | 5         | 0.36%   |
| Dell Latitude E7240                        | 5         | 0.36%   |
| Apple MacBookPro11,1                       | 5         | 0.36%   |
| Apple MacBookPro10,1                       | 5         | 0.36%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.29%   |
| HP ProBook 440 G6                          | 4         | 0.29%   |
| HP Pavilion g7                             | 4         | 0.29%   |
| HP Pavilion 15                             | 4         | 0.29%   |
| HP Laptop 15-bs1xx                         | 4         | 0.29%   |
| HP ENVY 17                                 | 4         | 0.29%   |
| HP EliteBook Folio 1040 G1                 | 4         | 0.29%   |
| HP EliteBook 8460p                         | 4         | 0.29%   |
| Dell XPS 15 9560                           | 4         | 0.29%   |
| Dell XPS 15 9520                           | 4         | 0.29%   |
| Dell XPS 13 9350                           | 4         | 0.29%   |
| Dell XPS 13 7390                           | 4         | 0.29%   |
| Dell Latitude E7470                        | 4         | 0.29%   |
| ASUS K53SD                                 | 4         | 0.29%   |
| Apple MacBookAir6,2                        | 4         | 0.29%   |
| Acer Aspire V3-772G                        | 4         | 0.29%   |
| TUXEDO Pulse 15 Gen1                       | 3         | 0.22%   |
| Razer Blade                                | 3         | 0.22%   |
| Polaroid MP1464PR001                       | 3         | 0.22%   |
| Lenovo Yoga Slim 7 14ITL05 82A3            | 3         | 0.22%   |
| Lenovo Yoga 7 16IRL8 82YN                  | 3         | 0.22%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 286       | 20.75%  |
| Acer Aspire         | 84        | 6.1%    |
| HP EliteBook        | 83        | 6.02%   |
| Dell Latitude       | 68        | 4.93%   |
| Dell XPS            | 57        | 4.14%   |
| HP ProBook          | 49        | 3.56%   |
| HP Pavilion         | 49        | 3.56%   |
| Lenovo IdeaPad      | 35        | 2.54%   |
| Lenovo Yoga         | 29        | 2.1%    |
| HP Laptop           | 24        | 1.74%   |
| ASUS VivoBook       | 24        | 1.74%   |
| Acer Swift          | 22        | 1.6%    |
| HP ZBook            | 20        | 1.45%   |
| HP ENVY             | 20        | 1.45%   |
| Dell Inspiron       | 18        | 1.31%   |
| ASUS ROG            | 14        | 1.02%   |
| Toshiba Satellite   | 12        | 0.87%   |
| Apple MacBookPro8   | 11        | 0.8%    |
| ASUS ZenBook        | 10        | 0.73%   |
| ASUS ASUS           | 10        | 0.73%   |
| Unknown             | 10        | 0.73%   |
| Lenovo ThinkBook    | 9         | 0.65%   |
| HP Compaq           | 9         | 0.65%   |
| Dell Precision      | 9         | 0.65%   |
| Apple MacBookPro11  | 9         | 0.65%   |
| HP OMEN             | 8         | 0.58%   |
| Apple MacBookPro9   | 8         | 0.58%   |
| Razer Blade         | 7         | 0.51%   |
| Lenovo Legion       | 7         | 0.51%   |
| HP 250              | 7         | 0.51%   |
| Fujitsu LIFEBOOK    | 7         | 0.51%   |
| Valve Jupiter       | 6         | 0.44%   |
| TUXEDO InfinityBook | 6         | 0.44%   |
| HP Notebook         | 6         | 0.44%   |
| Acer Predator       | 6         | 0.44%   |
| Apple MacBookPro5   | 5         | 0.36%   |
| Apple MacBookPro10  | 5         | 0.36%   |
| Apple MacBookAir6   | 5         | 0.36%   |
| Acer TravelMate     | 5         | 0.36%   |
| Dell Vostro         | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 124       | 9%      |
| 2020    | 123       | 8.93%   |
| 2019    | 107       | 7.76%   |
| 2012    | 103       | 7.47%   |
| 2021    | 91        | 6.6%    |
| 2017    | 91        | 6.6%    |
| 2022    | 87        | 6.31%   |
| 2013    | 86        | 6.24%   |
| 2011    | 85        | 6.17%   |
| 2014    | 84        | 6.1%    |
| 2023    | 74        | 5.37%   |
| 2015    | 70        | 5.08%   |
| 2016    | 64        | 4.64%   |
| 2010    | 62        | 4.5%    |
| 2008    | 46        | 3.34%   |
| 2009    | 27        | 1.96%   |
| 2007    | 25        | 1.81%   |
| 2024    | 17        | 1.23%   |
| 2005    | 5         | 0.36%   |
| 2006    | 4         | 0.29%   |
| Unknown | 2         | 0.15%   |
| 2004    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1378      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1218      | 87.44%  |
| Enabled  | 175       | 12.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1368      | 99.27%  |
| Yes  | 10        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 330       | 23.45%  |
| 4.01-8.0    | 306       | 21.75%  |
| 8.01-16.0   | 248       | 17.63%  |
| 32.01-64.0  | 195       | 13.86%  |
| 3.01-4.0    | 193       | 13.72%  |
| 24.01-32.0  | 47        | 3.34%   |
| 64.01-256.0 | 37        | 2.63%   |
| 1.01-2.0    | 31        | 2.2%    |
| 2.01-3.0    | 11        | 0.78%   |
| 0.51-1.0    | 9         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 455       | 29.24%  |
| 2.01-3.0   | 394       | 25.32%  |
| 4.01-8.0   | 295       | 18.96%  |
| 3.01-4.0   | 214       | 13.75%  |
| 8.01-16.0  | 94        | 6.04%   |
| 0.51-1.0   | 71        | 4.56%   |
| 16.01-24.0 | 19        | 1.22%   |
| 0.01-0.5   | 9         | 0.58%   |
| 24.01-32.0 | 4         | 0.26%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1088      | 77%     |
| 2      | 265       | 18.75%  |
| 3      | 43        | 3.04%   |
| 0      | 8         | 0.57%   |
| 4      | 6         | 0.42%   |
| 5      | 3         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 982       | 70.75%  |
| Yes       | 406       | 29.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1102      | 79.34%  |
| No        | 287       | 20.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1339      | 97.03%  |
| No        | 41        | 2.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1138      | 81.52%  |
| No        | 258       | 18.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 1378      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Zurich        | 333       | 22.1%   |
| Bern          | 76        | 5.04%   |
| Geneva        | 65        | 4.31%   |
| Lucerne       | 41        | 2.72%   |
| Lausanne      | 39        | 2.59%   |
| Winterthur    | 32        | 2.12%   |
| Basel         | 27        | 1.79%   |
| Lugano        | 22        | 1.46%   |
| Neuchatel     | 18        | 1.19%   |
| St. Gallen    | 16        | 1.06%   |
| Dietikon      | 16        | 1.06%   |
| Herrliberg    | 13        | 0.86%   |
| Zweidlen-Dorf | 11        | 0.73%   |
| Wil           | 11        | 0.73%   |
| Thun          | 10        | 0.66%   |
| Suhr          | 10        | 0.66%   |
| Biel/Bienne   | 10        | 0.66%   |
| Sion          | 9         | 0.6%    |
| Gerlafingen   | 8         | 0.53%   |
| Aarburg       | 8         | 0.53%   |
| Widnau        | 7         | 0.46%   |
| Solothurn     | 7         | 0.46%   |
| Lyss          | 7         | 0.46%   |
| Dubendorf     | 7         | 0.46%   |
| Chur          | 7         | 0.46%   |
| Wettingen     | 6         | 0.4%    |
| St. Moritz    | 6         | 0.4%    |
| Prilly        | 6         | 0.4%    |
| Onex          | 6         | 0.4%    |
| Munchenstein  | 6         | 0.4%    |
| Glattbrugg    | 6         | 0.4%    |
| Effretikon    | 6         | 0.4%    |
| Bussigny      | 6         | 0.4%    |
| Bellinzona    | 6         | 0.4%    |
| Aarau         | 6         | 0.4%    |
| Wohlen        | 5         | 0.33%   |
| Willisau      | 5         | 0.33%   |
| Renens        | 5         | 0.33%   |
| Oftringen     | 5         | 0.33%   |
| Muttenz       | 5         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 463       | 659    | 27.63%  |
| WDC                            | 142       | 180    | 8.47%   |
| SanDisk                        | 125       | 155    | 7.46%   |
| Seagate                        | 120       | 145    | 7.16%   |
| Toshiba                        | 111       | 155    | 6.62%   |
| SK hynix                       | 104       | 130    | 6.21%   |
| Intel                          | 78        | 107    | 4.65%   |
| Unknown                        | 71        | 97     | 4.24%   |
| Micron Technology              | 52        | 71     | 3.1%    |
| Kingston                       | 45        | 64     | 2.68%   |
| Hitachi                        | 44        | 55     | 2.63%   |
| Crucial                        | 42        | 61     | 2.51%   |
| Apple                          | 37        | 56     | 2.21%   |
| HGST                           | 23        | 28     | 1.37%   |
| KIOXIA                         | 18        | 21     | 1.07%   |
| LITEON                         | 17        | 22     | 1.01%   |
| Phison Electronics             | 12        | 25     | 0.72%   |
| Intenso                        | 12        | 16     | 0.72%   |
| LITEONIT                       | 11        | 12     | 0.66%   |
| Transcend                      | 9         | 12     | 0.54%   |
| A-DATA Technology              | 9         | 14     | 0.54%   |
| OCZ                            | 8         | 8      | 0.48%   |
| Fujitsu                        | 7         | 10     | 0.42%   |
| Silicon Motion                 | 6         | 7      | 0.36%   |
| Phison                         | 6         | 8      | 0.36%   |
| Kingston Technology Company    | 6         | 7      | 0.36%   |
| JMicron Technology             | 6         | 6      | 0.36%   |
| Corsair                        | 5         | 7      | 0.3%    |
| ASMT                           | 5         | 6      | 0.3%    |
| Unknown                        | 5         | 5      | 0.3%    |
| Union Memory (Shenzhen)        | 4         | 4      | 0.24%   |
| SPCC                           | 4         | 4      | 0.24%   |
| Micron/Crucial Technology      | 4         | 4      | 0.24%   |
| Solid State Storage Technology | 3         | 7      | 0.18%   |
| PNY                            | 3         | 3      | 0.18%   |
| Lenovo                         | 3         | 3      | 0.18%   |
| China                          | 3         | 5      | 0.18%   |
| WALRAM                         | 2         | 2      | 0.12%   |
| USB                            | 2         | 3      | 0.12%   |
| Union Memory                   | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 31        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 28        | 1.58%   |
| Samsung SSD 850 EVO 500GB                            | 15        | 0.85%   |
| HGST HTS721010A9E630 1TB                             | 14        | 0.79%   |
| SanDisk NVMe SSD Drive 512GB                         | 12        | 0.68%   |
| Samsung SSD 860 EVO 500GB                            | 12        | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 11        | 0.62%   |
| SK hynix NVMe SSD Drive 512GB                        | 11        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB                       | 11        | 0.62%   |
| Samsung SSD 860 EVO 250GB                            | 11        | 0.62%   |
| Unknown MMC Card  32GB                               | 10        | 0.56%   |
| Unknown MMC Card  128GB                              | 10        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 10        | 0.56%   |
| Samsung SSD 860 EVO 1TB                              | 10        | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB                       | 9         | 0.51%   |
| Samsung SSD 850 EVO 250GB                            | 9         | 0.51%   |
| Samsung NVMe SSD Drive 256GB                         | 9         | 0.51%   |
| Samsung NVMe SSD Drive 1024GB                        | 9         | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                          | 9         | 0.51%   |
| Toshiba MQ01ABF050 500GB                             | 8         | 0.45%   |
| Toshiba MQ01ABD100 1TB                               | 8         | 0.45%   |
| Unknown MMC Card  64GB                               | 7         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                      | 7         | 0.4%    |
| SanDisk NVMe SSD Drive 2TB                           | 7         | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                           | 7         | 0.4%    |
| Samsung SSD 970 EVO Plus 2TB                         | 7         | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                         | 7         | 0.4%    |
| Samsung NVMe SSD Drive 512GB                         | 7         | 0.4%    |
| Intel NVMe SSD Drive 512GB                           | 7         | 0.4%    |
| SK hynix SKHynix_HFS001TEJ9X162N 1TB                 | 6         | 0.34%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB              | 6         | 0.34%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                | 6         | 0.34%   |
| Seagate ST2000LM015-2E8174 2TB                       | 6         | 0.34%   |
| Seagate Expansion 1TB                                | 6         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB                       | 6         | 0.34%   |
| Samsung SSD 970 EVO 1TB                              | 6         | 0.34%   |
| Samsung SSD 870 EVO 500GB                            | 6         | 0.34%   |
| Samsung SSD 860 EVO M.2 500GB                        | 6         | 0.34%   |
| Samsung NVMe SSD Drive 2TB                           | 6         | 0.34%   |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 6         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 116       | 141    | 34.22%  |
| WDC                 | 70        | 93     | 20.65%  |
| Toshiba             | 53        | 61     | 15.63%  |
| Hitachi             | 44        | 55     | 12.98%  |
| HGST                | 23        | 28     | 6.78%   |
| Fujitsu             | 7         | 10     | 2.06%   |
| Samsung Electronics | 4         | 4      | 1.18%   |
| ASMT                | 4         | 5      | 1.18%   |
| Apple               | 4         | 4      | 1.18%   |
| Unknown             | 3         | 3      | 0.88%   |
| JMicron Technology  | 3         | 3      | 0.88%   |
| External            | 2         | 2      | 0.59%   |
| USB                 | 1         | 2      | 0.29%   |
| Unknown (CF)        | 1         | 1      | 0.29%   |
| SABRENT             | 1         | 1      | 0.29%   |
| Intenso             | 1         | 1      | 0.29%   |
| HGST HTS            | 1         | 1      | 0.29%   |
| ASMedia             | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 206       | 270    | 36.27%  |
| SanDisk             | 57        | 70     | 10.04%  |
| Crucial             | 36        | 54     | 6.34%   |
| Intel               | 33        | 38     | 5.81%   |
| Kingston            | 32        | 48     | 5.63%   |
| WDC                 | 29        | 35     | 5.11%   |
| Apple               | 25        | 29     | 4.4%    |
| Toshiba             | 19        | 29     | 3.35%   |
| SK hynix            | 19        | 21     | 3.35%   |
| Micron Technology   | 18        | 25     | 3.17%   |
| LITEON              | 17        | 22     | 2.99%   |
| LITEONIT            | 11        | 12     | 1.94%   |
| Intenso             | 9         | 11     | 1.58%   |
| OCZ                 | 8         | 8      | 1.41%   |
| Transcend           | 7         | 10     | 1.23%   |
| A-DATA Technology   | 7         | 10     | 1.23%   |
| Corsair             | 5         | 7      | 0.88%   |
| PNY                 | 3         | 3      | 0.53%   |
| China               | 3         | 5      | 0.53%   |
| SPCC                | 2         | 2      | 0.35%   |
| Seagate             | 2         | 2      | 0.35%   |
| Phison              | 2         | 4      | 0.35%   |
| KingSpec            | 2         | 2      | 0.35%   |
| WHALEKOM            | 1         | 1      | 0.18%   |
| WALRAM              | 1         | 1      | 0.18%   |
| Verbatim            | 1         | 1      | 0.18%   |
| USB3.0              | 1         | 2      | 0.18%   |
| TCSUNBOW            | 1         | 2      | 0.18%   |
| Plextor             | 1         | 1      | 0.18%   |
| OWC                 | 1         | 1      | 0.18%   |
| ORIGIN              | 1         | 1      | 0.18%   |
| ORICO               | 1         | 1      | 0.18%   |
| Mushkin             | 1         | 1      | 0.18%   |
| Kolink              | 1         | 1      | 0.18%   |
| KingDian            | 1         | 1      | 0.18%   |
| INTEL SS            | 1         | 1      | 0.18%   |
| GOODRAM             | 1         | 4      | 0.18%   |
| Dogfish             | 1         | 2      | 0.18%   |
| BIWIN               | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 651       | 954    | 40.56%  |
| SSD     | 529       | 739    | 32.96%  |
| HDD     | 327       | 416    | 20.37%  |
| MMC     | 77        | 106    | 4.8%    |
| Unknown | 21        | 25     | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 749       | 1107   | 48.73%  |
| NVMe | 649       | 949    | 42.23%  |
| MMC  | 77        | 106    | 5.01%   |
| SAS  | 62        | 78     | 4.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 559       | 775    | 66%     |
| 0.51-1.0   | 256       | 338    | 30.22%  |
| 1.01-2.0   | 24        | 30     | 2.83%   |
| 4.01-10.0  | 5         | 7      | 0.59%   |
| 3.01-4.0   | 3         | 5      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 363       | 24.64%  |
| 101-250        | 352       | 23.9%   |
| 501-1000       | 283       | 19.21%  |
| 1001-2000      | 128       | 8.69%   |
| 1-20           | 119       | 8.08%   |
| 51-100         | 68        | 4.62%   |
| Unknown        | 55        | 3.73%   |
| More than 3000 | 43        | 2.92%   |
| 21-50          | 43        | 2.92%   |
| 2001-3000      | 19        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 580       | 37.86%  |
| 21-50          | 231       | 15.08%  |
| 101-250        | 222       | 14.49%  |
| 51-100         | 171       | 11.16%  |
| 251-500        | 137       | 8.94%   |
| 501-1000       | 87        | 5.68%   |
| Unknown        | 55        | 3.59%   |
| 1001-2000      | 34        | 2.22%   |
| 2001-3000      | 8         | 0.52%   |
| More than 3000 | 6         | 0.39%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| SK hynix HFS256G39TND-N210A 256GB SSD        | 3         | 3      | 4.48%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 2.99%   |
| Samsung Electronics MZVLQ512HBLU-00B 512GB   | 2         | 2      | 2.99%   |
| Intel SSDSCKKF256G8H 256GB                   | 2         | 2      | 2.99%   |
| Hitachi HTS545050B9A300 500GB                | 2         | 2      | 2.99%   |
| WDC WD5000BEVT-55A0RT0 500GB                 | 1         | 1      | 1.49%   |
| WDC WD1600BEKT-60A25T1 160GB                 | 1         | 1      | 1.49%   |
| WDC WD10JPVX-08JC3T5 1TB                     | 1         | 1      | 1.49%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1         | 1      | 1.49%   |
| Transcend TS1TMTE220S 1TB                    | 1         | 1      | 1.49%   |
| Toshiba MQ01ACF050 500GB                     | 1         | 1      | 1.49%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 2      | 1.49%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.49%   |
| Toshiba MQ01ABD075 752GB                     | 1         | 1      | 1.49%   |
| Toshiba MK1652GSX 160GB                      | 1         | 1      | 1.49%   |
| Toshiba MK1255GSX H 120GB                    | 1         | 1      | 1.49%   |
| TCSUNBOW N8 240GB SSD                        | 1         | 1      | 1.49%   |
| SK hynix SC401 SATA 512GB SSD                | 1         | 2      | 1.49%   |
| SK hynix SC210 mSATA 256GB SSD               | 1         | 1      | 1.49%   |
| SK hynix HFS256GD9TNG-62A0A 256GB            | 1         | 1      | 1.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 1      | 1.49%   |
| SK hynix HFS128G39MNC-2300A 128GB SSD        | 1         | 1      | 1.49%   |
| Seagate ST9500420AS 500GB                    | 1         | 2      | 1.49%   |
| Seagate ST9250827AS 250GB                    | 1         | 1      | 1.49%   |
| Seagate ST9160412AS 160GB                    | 1         | 1      | 1.49%   |
| Seagate ST9120822AS 120GB                    | 1         | 1      | 1.49%   |
| Seagate ST500LM000-SSHD-8GB                  | 1         | 1      | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.49%   |
| Seagate ST1000LM014-SSHD-8GB                 | 1         | 1      | 1.49%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB          | 1         | 1      | 1.49%   |
| SanDisk SSD PLUS 1000GB                      | 1         | 1      | 1.49%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD          | 1         | 1      | 1.49%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD          | 1         | 1      | 1.49%   |
| SanDisk SD7SB3Q256G1002 256GB SSD            | 1         | 2      | 1.49%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 1.49%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1         | 1      | 1.49%   |
| Samsung Electronics SSD 860 EVO M.2 1TB      | 1         | 1      | 1.49%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 1.49%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 3      | 1.49%   |
| Samsung Electronics HM500JI 500GB            | 1         | 1      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 14.93%  |
| SK hynix            | 8         | 9      | 11.94%  |
| Samsung Electronics | 8         | 10     | 11.94%  |
| Hitachi             | 7         | 7      | 10.45%  |
| Toshiba             | 6         | 7      | 8.96%   |
| Intel               | 5         | 5      | 7.46%   |
| WDC                 | 4         | 4      | 5.97%   |
| SanDisk             | 4         | 5      | 5.97%   |
| Micron Technology   | 2         | 2      | 2.99%   |
| Intenso             | 2         | 3      | 2.99%   |
| HGST                | 2         | 2      | 2.99%   |
| Crucial             | 2         | 2      | 2.99%   |
| Transcend           | 1         | 1      | 1.49%   |
| TCSUNBOW            | 1         | 1      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 1      | 1.49%   |
| Kingston            | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 31.25%  |
| Hitachi             | 7         | 7      | 21.88%  |
| Toshiba             | 6         | 7      | 18.75%  |
| WDC                 | 4         | 4      | 12.5%   |
| HGST                | 2         | 2      | 6.25%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 34     | 47.76%  |
| SSD  | 30        | 35     | 44.78%  |
| NVMe | 5         | 5      | 7.46%   |

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
| Detected | 751       | 1213   | 50.64%  |
| Works    | 666       | 953    | 44.91%  |
| Malfunc  | 66        | 74     | 4.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 880       | 54.46%  |
| Samsung Electronics                     | 275       | 17.02%  |
| SanDisk                                 | 107       | 6.62%   |
| SK hynix                                | 79        | 4.89%   |
| AMD                                     | 77        | 4.76%   |
| Toshiba America Info Systems            | 43        | 2.66%   |
| Micron Technology                       | 36        | 2.23%   |
| Phison Electronics                      | 19        | 1.18%   |
| Kingston Technology Company             | 19        | 1.18%   |
| KIOXIA                                  | 15        | 0.93%   |
| Nvidia                                  | 11        | 0.68%   |
| Micron/Crucial Technology               | 8         | 0.5%    |
| Silicon Motion                          | 7         | 0.43%   |
| Marvell Technology Group                | 7         | 0.43%   |
| Solid State Storage Technology          | 5         | 0.31%   |
| Apple                                   | 5         | 0.31%   |
| Union Memory (Shenzhen)                 | 4         | 0.25%   |
| Lite-On Technology                      | 3         | 0.19%   |
| Lenovo                                  | 3         | 0.19%   |
| Yangtze Memory Technologies             | 2         | 0.12%   |
| VIA Technologies                        | 2         | 0.12%   |
| Shenzhen Unionmemory Information System | 2         | 0.12%   |
| Realtek Semiconductor                   | 2         | 0.12%   |
| ADATA Technology                        | 2         | 0.12%   |
| Transcend                               | 1         | 0.06%   |
| Shenzhen Longsys Electronics            | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 122       | 7.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 119       | 6.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 102       | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 77        | 4.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 63        | 3.67%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 60        | 3.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 58        | 3.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 55        | 3.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 40        | 2.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 34        | 1.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 30        | 1.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 25        | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 23        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 22        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 22        | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 20        | 1.17%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 19        | 1.11%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 19        | 1.11%   |
| Intel SSD 660P Series                                                          | 19        | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 18        | 1.05%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 18        | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 18        | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 16        | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 0.93%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 15        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 0.87%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 12        | 0.7%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 12        | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 12        | 0.7%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 12        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 0.7%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 11        | 0.64%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 10        | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 10        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 806       | 48.55%  |
| NVMe | 649       | 39.1%   |
| RAID | 144       | 8.67%   |
| IDE  | 61        | 3.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1183      | 85.79%  |
| AMD          | 192       | 13.92%  |
| CentaurHauls | 2         | 0.15%   |
| Unknown      | 2         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 40        | 2.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz          | 40        | 2.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 38        | 2.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 24        | 1.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 19        | 1.38%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 18        | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz          | 18        | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 18        | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz         | 17        | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 17        | 1.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 16        | 1.16%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 15        | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 15        | 1.09%   |
| Intel 13th Gen Core i7-1355U               | 15        | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 14        | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 13        | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 13        | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz          | 13        | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 13        | 0.94%   |
| Intel 12th Gen Core i7-1260P               | 13        | 0.94%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 13        | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 12        | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 11        | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 11        | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz          | 11        | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz          | 11        | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz          | 11        | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz          | 10        | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 10        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 10        | 0.72%   |
| Intel 12th Gen Core i7-12700H              | 10        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 9         | 0.65%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 9         | 0.65%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 9         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 9         | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 9         | 0.65%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics | 9         | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 9         | 0.65%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz         | 8         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 457       | 33.14%  |
| Intel Core i5           | 322       | 23.35%  |
| Other                   | 193       | 14%     |
| AMD Ryzen 7             | 62        | 4.5%    |
| Intel Core 2 Duo        | 54        | 3.92%   |
| Intel Celeron           | 36        | 2.61%   |
| AMD Ryzen 7 PRO         | 36        | 2.61%   |
| Intel Core i3           | 26        | 1.89%   |
| AMD Ryzen 5             | 26        | 1.89%   |
| Intel Pentium           | 25        | 1.81%   |
| Intel Atom              | 19        | 1.38%   |
| AMD Ryzen 9             | 14        | 1.02%   |
| Intel Core              | 12        | 0.87%   |
| Intel Core i9           | 9         | 0.65%   |
| Intel Core 2            | 8         | 0.58%   |
| Intel Pentium Dual-Core | 6         | 0.44%   |
| Intel Core M            | 6         | 0.44%   |
| AMD Ryzen 5 PRO         | 6         | 0.44%   |
| AMD E                   | 6         | 0.44%   |
| Intel Xeon              | 5         | 0.36%   |
| AMD Ryzen 3             | 4         | 0.29%   |
| AMD A8                  | 4         | 0.29%   |
| Intel Pentium Silver    | 3         | 0.22%   |
| Intel Pentium M         | 3         | 0.22%   |
| AMD E1                  | 3         | 0.22%   |
| AMD A6                  | 3         | 0.22%   |
| AMD A4                  | 3         | 0.22%   |
| Intel Genuine           | 2         | 0.15%   |
| Intel Core m7           | 2         | 0.15%   |
| Intel Core m3           | 2         | 0.15%   |
| Intel Celeron Dual-Core | 2         | 0.15%   |
| AMD Turion 64 X2 Mobile | 2         | 0.15%   |
| AMD Phenom II           | 2         | 0.15%   |
| AMD E2                  | 2         | 0.15%   |
| AMD C-50                | 2         | 0.15%   |
| Intel Pentium Gold      | 1         | 0.07%   |
| Intel Pentium Dual      | 1         | 0.07%   |
| Intel Pentium 4         | 1         | 0.07%   |
| Intel Core m5           | 1         | 0.07%   |
| CentaurHauls VIA Eden   | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 557       | 40.36%  |
| 4       | 478       | 34.64%  |
| 8       | 137       | 9.93%   |
| 6       | 79        | 5.72%   |
| 14      | 34        | 2.46%   |
| 10      | 33        | 2.39%   |
| 12      | 26        | 1.88%   |
| 16      | 15        | 1.09%   |
| 1       | 15        | 1.09%   |
| 24      | 5         | 0.36%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1378      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1161      | 84.01%  |
| 1       | 220       | 15.92%  |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1358      | 98.19%  |
| Unknown        | 17        | 1.23%   |
| 32-bit         | 6         | 0.43%   |
| 64-bit         | 2         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 547       | 38.33%  |
| 0x306a9    | 76        | 5.33%   |
| 0x206a7    | 62        | 4.34%   |
| 0x806ea    | 61        | 4.27%   |
| 0x40651    | 53        | 3.71%   |
| 0x806c1    | 48        | 3.36%   |
| 0x806ec    | 46        | 3.22%   |
| 0x806e9    | 33        | 2.31%   |
| 0x306d4    | 32        | 2.24%   |
| 0x906ea    | 30        | 2.1%    |
| 0x306c3    | 28        | 1.96%   |
| 0x1067a    | 28        | 1.96%   |
| 0x406e3    | 26        | 1.82%   |
| 0x20655    | 20        | 1.4%    |
| 0x0a404102 | 17        | 1.19%   |
| 0x30678    | 16        | 1.12%   |
| 0x906a3    | 15        | 1.05%   |
| 0x506e3    | 15        | 1.05%   |
| 0xa0652    | 14        | 0.98%   |
| 0x806eb    | 14        | 0.98%   |
| 0x20652    | 13        | 0.91%   |
| 0x0a50000c | 13        | 0.91%   |
| 0x08600106 | 12        | 0.84%   |
| 0x906e9    | 11        | 0.77%   |
| 0x406c4    | 10        | 0.7%    |
| 0x10676    | 10        | 0.7%    |
| 0x706e5    | 9         | 0.63%   |
| 0x08600103 | 9         | 0.63%   |
| 0x706a1    | 7         | 0.49%   |
| 0x6fd      | 7         | 0.49%   |
| 0x0a704103 | 7         | 0.49%   |
| 0x806d1    | 6         | 0.42%   |
| 0x6f6      | 6         | 0.42%   |
| 0x08608103 | 6         | 0.42%   |
| 0x906a4    | 5         | 0.35%   |
| 0x406c3    | 5         | 0.35%   |
| 0x0a50000d | 5         | 0.35%   |
| 0x08108102 | 5         | 0.35%   |
| 0x05000119 | 5         | 0.35%   |
| 0x906ed    | 4         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 300       | 21.68%  |
| Haswell           | 126       | 9.1%    |
| Unknown           | 120       | 8.67%   |
| IvyBridge         | 106       | 7.66%   |
| SandyBridge       | 91        | 6.58%   |
| Skylake           | 85        | 6.14%   |
| TigerLake         | 70        | 5.06%   |
| Alderlake Hybrid  | 68        | 4.91%   |
| Penryn            | 55        | 3.97%   |
| Broadwell         | 51        | 3.68%   |
| Westmere          | 43        | 3.11%   |
| Zen 2             | 37        | 2.67%   |
| Silvermont        | 37        | 2.67%   |
| Zen 3             | 35        | 2.53%   |
| CometLake         | 29        | 2.1%    |
| IceLake           | 23        | 1.66%   |
| Core              | 20        | 1.45%   |
| Zen+              | 13        | 0.94%   |
| Goldmont plus     | 12        | 0.87%   |
| Bobcat            | 11        | 0.79%   |
| Nehalem           | 6         | 0.43%   |
| Meteorlake Hybrid | 6         | 0.43%   |
| Bonnell           | 5         | 0.36%   |
| K8 Hammer         | 4         | 0.29%   |
| Jaguar            | 4         | 0.29%   |
| Steamroller       | 3         | 0.22%   |
| P6                | 3         | 0.22%   |
| K10               | 3         | 0.22%   |
| Goldmont          | 3         | 0.22%   |
| Excavator         | 3         | 0.22%   |
| Zen               | 2         | 0.14%   |
| Tremont           | 2         | 0.14%   |
| Puma              | 2         | 0.14%   |
| Piledriver        | 2         | 0.14%   |
| K10 Llano         | 2         | 0.14%   |
| NetBurst          | 1         | 0.07%   |
| Lunarlake Hybrid  | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 1070      | 60.76%  |
| Nvidia           | 412       | 23.4%   |
| AMD              | 277       | 15.73%  |
| VIA Technologies | 2         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 98        | 5.49%   |
| Intel UHD Graphics 620                                                                   | 87        | 4.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 75        | 4.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 72        | 4.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 67        | 3.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 3.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 60        | 3.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 2.58%   |
| Intel HD Graphics 620                                                                    | 42        | 2.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 2.3%    |
| Intel HD Graphics 5500                                                                   | 37        | 2.07%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 36        | 2.02%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 35        | 1.96%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 34        | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 1.46%   |
| AMD Rembrandt [Radeon 680M]                                                              | 26        | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 0.9%    |
| AMD Phoenix1                                                                             | 16        | 0.9%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.84%   |
| Intel HD Graphics 630                                                                    | 14        | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 13        | 0.73%   |
| Intel HD Graphics 530                                                                    | 13        | 0.73%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 0.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 0.67%   |
| AMD Lucienne                                                                             | 12        | 0.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 11        | 0.62%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 11        | 0.62%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 11        | 0.62%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 10        | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.56%   |
| Intel Iris Plus Graphics G7                                                              | 10        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 717       | 51.81%  |
| Intel + Nvidia | 305       | 22.04%  |
| 1 x AMD        | 191       | 13.8%   |
| 1 x Nvidia     | 76        | 5.49%   |
| Intel + AMD    | 47        | 3.4%    |
| AMD + Nvidia   | 31        | 2.24%   |
| 2 x AMD        | 7         | 0.51%   |
| Other          | 3         | 0.22%   |
| 2 x Nvidia     | 3         | 0.22%   |
| 2 x Intel      | 2         | 0.14%   |
| 1 x VIA        | 2         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1135      | 81.54%  |
| Proprietary | 206       | 14.8%   |
| Unknown     | 51        | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 942       | 66.9%   |
| 1.01-2.0   | 141       | 10.01%  |
| 0.01-0.5   | 123       | 8.74%   |
| 3.01-4.0   | 83        | 5.89%   |
| 0.51-1.0   | 73        | 5.18%   |
| 7.01-8.0   | 22        | 1.56%   |
| 5.01-6.0   | 12        | 0.85%   |
| 8.01-16.0  | 7         | 0.5%    |
| 2.01-3.0   | 5         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 316       | 19.58%  |
| LG Display              | 238       | 14.75%  |
| Chimei Innolux          | 171       | 10.59%  |
| BOE                     | 166       | 10.29%  |
| Samsung Electronics     | 143       | 8.86%   |
| Apple                   | 71        | 4.4%    |
| Sharp                   | 66        | 4.09%   |
| Dell                    | 56        | 3.47%   |
| Lenovo                  | 54        | 3.35%   |
| Hewlett-Packard         | 35        | 2.17%   |
| CSO                     | 32        | 1.98%   |
| Chi Mei Optoelectronics | 30        | 1.86%   |
| Philips                 | 28        | 1.73%   |
| Acer                    | 24        | 1.49%   |
| InfoVision              | 20        | 1.24%   |
| Goldstar                | 18        | 1.12%   |
| BenQ                    | 15        | 0.93%   |
| Ancor Communications    | 13        | 0.81%   |
| ASUSTek Computer        | 12        | 0.74%   |
| PANDA                   | 10        | 0.62%   |
| AOC                     | 10        | 0.62%   |
| Valve                   | 8         | 0.5%    |
| Sony                    | 8         | 0.5%    |
| Eizo                    | 7         | 0.43%   |
| LG Philips              | 6         | 0.37%   |
| Toshiba                 | 5         | 0.31%   |
| Panasonic               | 5         | 0.31%   |
| Iiyama                  | 5         | 0.31%   |
| Vestel Elektronik       | 4         | 0.25%   |
| LGD                     | 4         | 0.25%   |
| JDI                     | 4         | 0.25%   |
| HannStar                | 3         | 0.19%   |
| Denver                  | 3         | 0.19%   |
| ViewSonic               | 2         | 0.12%   |
| Tianma XM               | 2         | 0.12%   |
| MSI                     | 2         | 0.12%   |
| IBM                     | 2         | 0.12%   |
| Gigabyte Technology     | 2         | 0.12%   |
| CPT                     | 2         | 0.12%   |
| Unknown                 | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 15        | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.67%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 10        | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 10        | 0.61%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 9         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 8         | 0.49%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 7         | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 7         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 7         | 0.43%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 7         | 0.43%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                     | 7         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 7         | 0.43%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 6         | 0.37%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 6         | 0.37%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                    | 6         | 0.37%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 6         | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 5         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.31%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 5         | 0.31%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch              | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 5         | 0.31%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 5         | 0.31%   |
| BOE LCD Monitor BOE06EE 1920x1080 309x173mm 13.9-inch                     | 5         | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch            | 5         | 0.31%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 5         | 0.31%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch     | 4         | 0.24%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 4         | 0.24%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 4         | 0.24%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch      | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch     | 4         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 668       | 43.83%  |
| 1366x768 (WXGA)    | 194       | 12.73%  |
| 1600x900 (HD+)     | 107       | 7.02%   |
| 3840x2160 (4K)     | 97        | 6.36%   |
| 2560x1440 (QHD)    | 80        | 5.25%   |
| 1920x1200 (WUXGA)  | 78        | 5.12%   |
| 1280x800 (WXGA)    | 47        | 3.08%   |
| 2560x1600          | 40        | 2.62%   |
| 1440x900 (WXGA+)   | 35        | 2.3%    |
| 2880x1800          | 26        | 1.71%   |
| 3440x1440          | 19        | 1.25%   |
| 1680x1050 (WSXGA+) | 19        | 1.25%   |
| 3840x2400          | 18        | 1.18%   |
| 3200x1800 (QHD+)   | 13        | 0.85%   |
| 800x1280           | 8         | 0.52%   |
| 3840x1600          | 8         | 0.52%   |
| 1280x1024 (SXGA)   | 7         | 0.46%   |
| 1024x600           | 6         | 0.39%   |
| 3456x2160          | 5         | 0.33%   |
| 2160x1440          | 5         | 0.33%   |
| 1600x1200          | 5         | 0.33%   |
| 3840x1080          | 4         | 0.26%   |
| 3200x2000          | 4         | 0.26%   |
| 3072x1920          | 4         | 0.26%   |
| 3000x2000          | 4         | 0.26%   |
| 2560x1080          | 4         | 0.26%   |
| 3840x1100          | 2         | 0.13%   |
| 2944x1840          | 2         | 0.13%   |
| 1360x768           | 2         | 0.13%   |
| 1024x768 (XGA)     | 2         | 0.13%   |
| Unknown            | 2         | 0.13%   |
| 3840x2560          | 1         | 0.07%   |
| 3286x1080          | 1         | 0.07%   |
| 2560x1024          | 1         | 0.07%   |
| 2304x1440          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 2256x1504          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 506       | 31.29%  |
| 14      | 241       | 14.9%   |
| 13      | 233       | 14.41%  |
| 17      | 154       | 9.52%   |
| 27      | 104       | 6.43%   |
| 12      | 59        | 3.65%   |
| 24      | 53        | 3.28%   |
| 16      | 50        | 3.09%   |
| 23      | 28        | 1.73%   |
| 31      | 23        | 1.42%   |
| 34      | 21        | 1.3%    |
| 21      | 19        | 1.18%   |
| Unknown | 19        | 1.18%   |
| 11      | 15        | 0.93%   |
| 37      | 8         | 0.49%   |
| 22      | 8         | 0.49%   |
| 7       | 8         | 0.49%   |
| 32      | 6         | 0.37%   |
| 20      | 6         | 0.37%   |
| 10      | 6         | 0.37%   |
| 84      | 5         | 0.31%   |
| 25      | 5         | 0.31%   |
| 18      | 5         | 0.31%   |
| 40      | 4         | 0.25%   |
| 19      | 4         | 0.25%   |
| 72      | 3         | 0.19%   |
| 48      | 3         | 0.19%   |
| 46      | 3         | 0.19%   |
| 65      | 2         | 0.12%   |
| 54      | 2         | 0.12%   |
| 49      | 2         | 0.12%   |
| 35      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 86      | 1         | 0.06%   |
| 69      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 33      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 866       | 54.19%  |
| 201-300        | 223       | 13.95%  |
| 351-400        | 175       | 10.95%  |
| 501-600        | 170       | 10.64%  |
| 401-500        | 35        | 2.19%   |
| 601-700        | 34        | 2.13%   |
| 701-800        | 28        | 1.75%   |
| Unknown        | 19        | 1.19%   |
| 801-900        | 14        | 0.88%   |
| 1001-1500      | 14        | 0.88%   |
| 1501-2000      | 9         | 0.56%   |
| 1-100          | 8         | 0.5%    |
| More than 2000 | 1         | 0.06%   |
| 101-200        | 1         | 0.06%   |
| 901-1000       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1060      | 74.28%  |
| 16/10   | 274       | 19.2%   |
| 21/9    | 30        | 2.1%    |
| 3/2     | 16        | 1.12%   |
| Unknown | 14        | 0.98%   |
| 4/3     | 8         | 0.56%   |
| 5/4     | 7         | 0.49%   |
| 0.67    | 6         | 0.42%   |
| 32/9    | 4         | 0.28%   |
| 3.40    | 2         | 0.14%   |
| 0.62    | 2         | 0.14%   |
| 3.73    | 1         | 0.07%   |
| 2.50    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |
| 0.56    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 505       | 31.31%  |
| 81-90          | 352       | 21.82%  |
| 121-130        | 134       | 8.31%   |
| 71-80          | 114       | 7.07%   |
| 301-350        | 104       | 6.45%   |
| 201-250        | 82        | 5.08%   |
| 61-70          | 58        | 3.6%    |
| 351-500        | 57        | 3.53%   |
| 111-120        | 47        | 2.91%   |
| 251-300        | 26        | 1.61%   |
| 131-140        | 19        | 1.18%   |
| 501-1000       | 19        | 1.18%   |
| Unknown        | 19        | 1.18%   |
| More than 1000 | 17        | 1.05%   |
| 51-60          | 17        | 1.05%   |
| 151-200        | 12        | 0.74%   |
| 1-40           | 9         | 0.56%   |
| 91-100         | 9         | 0.56%   |
| 141-150        | 7         | 0.43%   |
| 41-50          | 6         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 668       | 42.57%  |
| 101-120       | 338       | 21.54%  |
| 51-100        | 211       | 13.45%  |
| 161-240       | 209       | 13.32%  |
| More than 240 | 108       | 6.88%   |
| Unknown       | 19        | 1.21%   |
| 1-50          | 16        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1099      | 77.23%  |
| 2     | 251       | 17.64%  |
| 3     | 37        | 2.6%    |
| 0     | 35        | 2.46%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 876       | 40.24%  |
| Realtek Semiconductor                  | 562       | 25.82%  |
| Qualcomm Atheros                       | 189       | 8.68%   |
| Broadcom                               | 139       | 6.38%   |
| MediaTek                               | 55        | 2.53%   |
| Broadcom Limited                       | 42        | 1.93%   |
| ASIX Electronics                       | 29        | 1.33%   |
| Qualcomm                               | 28        | 1.29%   |
| Lenovo                                 | 27        | 1.24%   |
| Sierra Wireless                        | 23        | 1.06%   |
| Ralink                                 | 23        | 1.06%   |
| Marvell Technology Group               | 20        | 0.92%   |
| Hewlett-Packard                        | 20        | 0.92%   |
| DisplayLink                            | 18        | 0.83%   |
| Dell                                   | 18        | 0.83%   |
| Ericsson Business Mobile Networks      | 14        | 0.64%   |
| Nvidia                                 | 9         | 0.41%   |
| Huawei Technologies                    | 9         | 0.41%   |
| Xiaomi                                 | 8         | 0.37%   |
| TP-Link                                | 8         | 0.37%   |
| Samsung Electronics                    | 8         | 0.37%   |
| ASUSTek Computer                       | 6         | 0.28%   |
| Ralink Technology                      | 5         | 0.23%   |
| Fibocom                                | 5         | 0.23%   |
| Edimax Technology                      | 5         | 0.23%   |
| D-Link                                 | 3         | 0.14%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.09%   |
| QinHeng Electronics                    | 2         | 0.09%   |
| NetGear                                | 2         | 0.09%   |
| Linksys                                | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| AVM                                    | 2         | 0.09%   |
| Arduino SA                             | 2         | 0.09%   |
| Wilocity                               | 1         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.05%   |
| Quectel Wireless Solutions             | 1         | 0.05%   |
| Qualcomm Atheros Communications        | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Novatek Microelectronics               | 1         | 0.05%   |
| MosChip Semiconductor                  | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 370       | 13.85%  |
| Intel Wi-Fi 6 AX200                                                    | 92        | 3.44%   |
| Intel Wireless 8265 / 8275                                             | 90        | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 87        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 67        | 2.51%   |
| Intel Wi-Fi 6 AX201                                                    | 56        | 2.1%    |
| Intel Wireless 7260                                                    | 53        | 1.98%   |
| Intel Wireless 7265                                                    | 49        | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 1.8%    |
| Intel Wireless 8260                                                    | 44        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 44        | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 43        | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 34        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 32        | 1.2%    |
| Intel Raptor Lake PCH CNVi WiFi                                        | 29        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 28        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 28        | 1.05%   |
| Intel Ethernet Connection I218-LM                                      | 27        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 26        | 0.97%   |
| Intel Ethernet Connection I219-LM                                      | 26        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                          | 26        | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 25        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 25        | 0.94%   |
| Intel Centrino Ultimate-N 6300                                         | 25        | 0.94%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 24        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 24        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                   | 23        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 22        | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 22        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 20        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 20        | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 20        | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 19        | 0.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 19        | 0.71%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 19        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 18        | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 18        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 18        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 849       | 59.75%  |
| Qualcomm Atheros                | 159       | 11.19%  |
| Broadcom                        | 110       | 7.74%   |
| Realtek Semiconductor           | 104       | 7.32%   |
| MediaTek                        | 43        | 3.03%   |
| Broadcom Limited                | 29        | 2.04%   |
| Qualcomm                        | 26        | 1.83%   |
| Sierra Wireless                 | 23        | 1.62%   |
| Ralink                          | 23        | 1.62%   |
| Dell                            | 11        | 0.77%   |
| Hewlett-Packard                 | 8         | 0.56%   |
| ASUSTek Computer                | 6         | 0.42%   |
| TP-Link                         | 5         | 0.35%   |
| Ralink Technology               | 5         | 0.35%   |
| Fibocom                         | 5         | 0.35%   |
| Edimax Technology               | 5         | 0.35%   |
| NetGear                         | 2         | 0.14%   |
| D-Link                          | 2         | 0.14%   |
| AVM                             | 2         | 0.14%   |
| Wilocity                        | 1         | 0.07%   |
| Qualcomm Atheros Communications | 1         | 0.07%   |
| Linksys                         | 1         | 0.07%   |
| 3Com                            | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 92        | 6.44%   |
| Intel Wireless 8265 / 8275                                           | 90        | 6.3%    |
| Intel Wi-Fi 6 AX201                                                  | 56        | 3.92%   |
| Intel Wireless 7260                                                  | 53        | 3.71%   |
| Intel Wireless 7265                                                  | 49        | 3.43%   |
| Intel Wireless 8260                                                  | 44        | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 44        | 3.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 43        | 3.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 34        | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 32        | 2.24%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 29        | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 28        | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 26        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 25        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 25        | 1.75%   |
| Intel Centrino Ultimate-N 6300                                       | 25        | 1.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 24        | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 24        | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 22        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 22        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 20        | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 19        | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 18        | 1.26%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 18        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 18        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 17        | 1.19%   |
| Intel Wireless 3160                                                  | 16        | 1.12%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 16        | 1.12%   |
| Intel Wireless 3165                                                  | 15        | 1.05%   |
| Intel Centrino Advanced-N 6235                                       | 15        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 15        | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 14        | 0.98%   |
| Intel Centrino Advanced-N 6200                                       | 14        | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 14        | 0.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 13        | 0.91%   |
| Intel Centrino Wireless-N 2230                                       | 12        | 0.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 11        | 0.77%   |
| Sierra Wireless EM7455                                               | 10        | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 10        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 10        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 522       | 44.5%   |
| Intel                                  | 368       | 31.37%  |
| Broadcom                               | 61        | 5.2%    |
| Qualcomm Atheros                       | 59        | 5.03%   |
| ASIX Electronics                       | 29        | 2.47%   |
| Lenovo                                 | 26        | 2.22%   |
| Marvell Technology Group               | 20        | 1.71%   |
| DisplayLink                            | 18        | 1.53%   |
| Broadcom Limited                       | 13        | 1.11%   |
| MediaTek                               | 12        | 1.02%   |
| Nvidia                                 | 9         | 0.77%   |
| Xiaomi                                 | 8         | 0.68%   |
| Samsung Electronics                    | 5         | 0.43%   |
| TP-Link                                | 3         | 0.26%   |
| Huawei Technologies                    | 3         | 0.26%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.17%   |
| Qualcomm                               | 2         | 0.17%   |
| Hewlett-Packard                        | 2         | 0.17%   |
| Google                                 | 2         | 0.17%   |
| Spreadtrum Communications              | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.09%   |
| MosChip Semiconductor                  | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| JMicron Technology                     | 1         | 0.09%   |
| HMD Global                             | 1         | 0.09%   |
| D-Link                                 | 1         | 0.09%   |
| Aquantia                               | 1         | 0.09%   |
| Apple                                  | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 370       | 31.14%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 87        | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 67        | 5.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 4.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 28        | 2.36%   |
| Intel Ethernet Connection I218-LM                                      | 27        | 2.27%   |
| Intel Ethernet Connection I219-LM                                      | 26        | 2.19%   |
| ASIX AX88179 Gigabit Ethernet                                          | 26        | 2.19%   |
| Intel Ethernet Connection (4) I219-V                                   | 23        | 1.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 1.77%   |
| Intel Ethernet Connection (6) I219-V                                   | 20        | 1.68%   |
| Intel Ethernet Connection (3) I218-LM                                  | 20        | 1.68%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 1.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 19        | 1.6%    |
| Intel Ethernet Connection I219-V                                       | 13        | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 10        | 0.84%   |
| Intel Ethernet Connection (13) I219-V                                  | 10        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.76%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 9         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 0.67%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 8         | 0.67%   |
| Lenovo Thinkpad LAN                                                    | 8         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 8         | 0.67%   |
| Intel 82566MM Gigabit Network Connection                               | 8         | 0.67%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7         | 0.59%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.59%   |
| DisplayLink USB 4K Graphic Docking                                     | 7         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 7         | 0.59%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 7         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 6         | 0.51%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 6         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1339      | 53.75%  |
| Ethernet | 1097      | 44.04%  |
| Modem    | 52        | 2.09%   |
| Unknown  | 3         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1091      | 74.42%  |
| Ethernet | 374       | 25.51%  |
| Modem    | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 931       | 67.51%  |
| 1     | 411       | 29.8%   |
| 3     | 23        | 1.67%   |
| 0     | 14        | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1063      | 74.86%  |
| Yes  | 357       | 25.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 652       | 56.94%  |
| Broadcom                        | 75        | 6.55%   |
| Foxconn / Hon Hai               | 66        | 5.76%   |
| Realtek Semiconductor           | 65        | 5.68%   |
| Apple                           | 61        | 5.33%   |
| IMC Networks                    | 47        | 4.1%    |
| Qualcomm Atheros Communications | 45        | 3.93%   |
| Lite-On Technology              | 37        | 3.23%   |
| Hewlett-Packard                 | 21        | 1.83%   |
| USI                             | 17        | 1.48%   |
| Dell                            | 16        | 1.4%    |
| Cambridge Silicon Radio         | 12        | 1.05%   |
| Ralink                          | 9         | 0.79%   |
| Toshiba                         | 4         | 0.35%   |
| Alps Electric                   | 4         | 0.35%   |
| Realtek                         | 2         | 0.17%   |
| Ralink Technology               | 2         | 0.17%   |
| MediaTek                        | 2         | 0.17%   |
| Chicony Electronics             | 2         | 0.17%   |
| ASUSTek Computer                | 2         | 0.17%   |
| Taiyo Yuden                     | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 260       | 22.67%  |
| Intel AX201 Bluetooth                               | 114       | 9.94%   |
| Intel AX200 Bluetooth                               | 86        | 7.5%    |
| Intel AX211 Bluetooth                               | 75        | 6.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 51        | 4.45%   |
| Apple Bluetooth Host Controller                     | 38        | 3.31%   |
| Realtek Bluetooth Radio                             | 37        | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 2.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 1.74%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 1.66%   |
| IMC Networks Wireless_Device                        | 18        | 1.57%   |
| USI Bluetooth Device                                | 17        | 1.48%   |
| Apple Bluetooth USB Host Controller                 | 17        | 1.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 1.39%   |
| IMC Networks Bluetooth Radio                        | 16        | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 1.39%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 1.13%   |
| Intel AX210 Bluetooth                               | 12        | 1.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.87%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 10        | 0.87%   |
| Realtek 802.11ac WLAN Adapter                       | 9         | 0.78%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.7%    |
| Lite-On Bluetooth Device                            | 8         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 0.7%    |
| IMC Networks Bluetooth Device                       | 8         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.52%   |
| Intel Bluetooth Device                              | 6         | 0.52%   |
| Foxconn / Hon Hai BCM20702A0                        | 6         | 0.52%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 6         | 0.52%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.52%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 5         | 0.44%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1159      | 66.19%  |
| AMD                               | 225       | 12.85%  |
| Nvidia                            | 219       | 12.51%  |
| Lenovo                            | 22        | 1.26%   |
| GN Netcom                         | 20        | 1.14%   |
| Logitech                          | 14        | 0.8%    |
| Hewlett-Packard                   | 14        | 0.8%    |
| Realtek Semiconductor             | 11        | 0.63%   |
| Plantronics                       | 9         | 0.51%   |
| C-Media Electronics               | 8         | 0.46%   |
| Razer USA                         | 4         | 0.23%   |
| Kingston Technology               | 4         | 0.23%   |
| RODE Microphones                  | 3         | 0.17%   |
| Conexant Systems                  | 3         | 0.17%   |
| VIA Technologies                  | 2         | 0.11%   |
| SteelSeries ApS                   | 2         | 0.11%   |
| Other World Computing             | 2         | 0.11%   |
| JMTek                             | 2         | 0.11%   |
| BEHRINGER International           | 2         | 0.11%   |
| Tenx Technology                   | 1         | 0.06%   |
| Sony                              | 1         | 0.06%   |
| Sennheiser Communications         | 1         | 0.06%   |
| Samsung Electronics               | 1         | 0.06%   |
| ROCCAT                            | 1         | 0.06%   |
| Nordic Semiconductor ASA          | 1         | 0.06%   |
| MV-SILICON                        | 1         | 0.06%   |
| miniDSP                           | 1         | 0.06%   |
| Magic Control Technology          | 1         | 0.06%   |
| Huawei Technologies               | 1         | 0.06%   |
| Guillemot                         | 1         | 0.06%   |
| Griffin Technology                | 1         | 0.06%   |
| freeVoice                         | 1         | 0.06%   |
| Focusrite-Novation                | 1         | 0.06%   |
| FiiO Electronics Technology       | 1         | 0.06%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.06%   |
| Elite Silicon                     | 1         | 0.06%   |
| Creative Technology               | 1         | 0.06%   |
| Cisco Systems                     | 1         | 0.06%   |
| Cambridge Silicon Radio           | 1         | 0.06%   |
| Blue Microphones                  | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 206       | 9.86%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 143       | 6.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 113       | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 84        | 4.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 74        | 3.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 73        | 3.49%   |
| Intel 8 Series HD Audio Controller                                         | 73        | 3.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 70        | 3.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 66        | 3.16%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 55        | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 53        | 2.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 50        | 2.39%   |
| Intel Broadwell-U Audio Controller                                         | 50        | 2.39%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 50        | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 49        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 47        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 2.06%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 38        | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 37        | 1.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 34        | 1.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 25        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 23        | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 21        | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 19        | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                         | 18        | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 16        | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 0.72%   |
| AMD FCH Azalia Controller                                                  | 15        | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 13        | 0.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 0.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12        | 0.57%   |
| Hewlett-Packard USB Audio                                                  | 12        | 0.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 0.53%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.53%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 11        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 311       | 32.23%  |
| SK hynix            | 240       | 24.87%  |
| Micron Technology   | 136       | 14.09%  |
| Kingston            | 90        | 9.33%   |
| Unknown             | 53        | 5.49%   |
| Crucial             | 31        | 3.21%   |
| Elpida              | 23        | 2.38%   |
| Corsair             | 21        | 2.18%   |
| Ramaxel Technology  | 15        | 1.55%   |
| A-DATA Technology   | 12        | 1.24%   |
| Unknown             | 12        | 1.24%   |
| Nanya Technology    | 7         | 0.73%   |
| G.Skill             | 4         | 0.41%   |
| ASint Technology    | 3         | 0.31%   |
| Unknown (ABCD)      | 1         | 0.1%    |
| Unknown (08AE)      | 1         | 0.1%    |
| Team                | 1         | 0.1%    |
| OnBoard             | 1         | 0.1%    |
| King Tiger          | 1         | 0.1%    |
| GOODRAM             | 1         | 0.1%    |
| CSX                 | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 20        | 1.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 14        | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 13        | 1.27%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 13        | 1.27%   |
| Unknown                                                      | 12        | 1.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 11        | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 9         | 0.88%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 9         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 8         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 8         | 0.78%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 0.68%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 7         | 0.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 7         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 0.68%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 7         | 0.68%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 7         | 0.68%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 7         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 7         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 7         | 0.68%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 7         | 0.68%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.68%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 6         | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 6         | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 6         | 0.59%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 6         | 0.59%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 6         | 0.59%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s       | 6         | 0.59%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 5         | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 5         | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 5         | 0.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s        | 5         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 0.49%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 5         | 0.49%   |
| Samsung RAM K3KL9L90CM-MGCT 4GB Row Of Chips LPDDR5 7500MT/s | 5         | 0.49%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s   | 5         | 0.49%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s   | 5         | 0.49%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 5         | 0.49%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 5         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 362       | 43.3%   |
| DDR3    | 261       | 31.22%  |
| LPDDR3  | 54        | 6.46%   |
| LPDDR5  | 52        | 6.22%   |
| DDR5    | 39        | 4.67%   |
| LPDDR4  | 33        | 3.95%   |
| DDR2    | 21        | 2.51%   |
| SDRAM   | 7         | 0.84%   |
| Unknown | 4         | 0.48%   |
| DDR     | 3         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 706       | 83.65%  |
| Row Of Chips | 117       | 13.86%  |
| Chip         | 13        | 1.54%   |
| Unknown      | 4         | 0.47%   |
| DIMM         | 3         | 0.36%   |
| RIMM         | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 374       | 41.14%  |
| 4096  | 209       | 22.99%  |
| 16384 | 193       | 21.23%  |
| 2048  | 77        | 8.47%   |
| 32768 | 37        | 4.07%   |
| 1024  | 18        | 1.98%   |
| 512   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 166       | 18.59%  |
| 2667    | 156       | 17.47%  |
| 3200    | 154       | 17.25%  |
| 2133    | 73        | 8.17%   |
| 2400    | 58        | 6.49%   |
| 1334    | 52        | 5.82%   |
| 1333    | 30        | 3.36%   |
| 6400    | 27        | 3.02%   |
| 4800    | 27        | 3.02%   |
| 7500    | 16        | 1.79%   |
| 4267    | 16        | 1.79%   |
| 1067    | 15        | 1.68%   |
| Unknown | 15        | 1.68%   |
| 5600    | 13        | 1.46%   |
| 667     | 12        | 1.34%   |
| 1867    | 10        | 1.12%   |
| 1066    | 7         | 0.78%   |
| 7467    | 6         | 0.67%   |
| 3266    | 6         | 0.67%   |
| 800     | 5         | 0.56%   |
| 8400    | 4         | 0.45%   |
| 4266    | 4         | 0.45%   |
| 8533    | 3         | 0.34%   |
| 4199    | 3         | 0.34%   |
| 3733    | 3         | 0.34%   |
| 2048    | 3         | 0.34%   |
| 975     | 3         | 0.34%   |
| 3800    | 1         | 0.11%   |
| 3600    | 1         | 0.11%   |
| 3000    | 1         | 0.11%   |
| 1639    | 1         | 0.11%   |
| 333     | 1         | 0.11%   |
| 266     | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 5         | 41.67%  |
| Hewlett-Packard     | 3         | 25%     |
| Samsung Electronics | 1         | 8.33%   |
| Prolific Technology | 1         | 8.33%   |
| Konica Minolta      | 1         | 8.33%   |
| Canon               | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| HP OfficeJet 4650 series       | 2         | 16.67%  |
| Brother MFC Composite Device   | 2         | 16.67%  |
| Samsung M337x 387x 407x Series | 1         | 8.33%   |
| Prolific PL2305 Parallel Port  | 1         | 8.33%   |
| Konica Minolta Printer         | 1         | 8.33%   |
| HP Laserjet P1505              | 1         | 8.33%   |
| Canon PIXMA TS6250             | 1         | 8.33%   |
| Brother HL-3040CN series       | 1         | 8.33%   |
| Brother HL-2030 Laser Printer  | 1         | 8.33%   |
| Brother DCP-7055W              | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Seiko Epson       | 1         | 50%     |
| Canon Electronics | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon P-150 Scanner                                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 377       | 29.66%  |
| IMC Networks                           | 106       | 8.34%   |
| Microdia                               | 85        | 6.69%   |
| Bison Electronics                      | 84        | 6.61%   |
| Realtek Semiconductor                  | 80        | 6.29%   |
| Quanta                                 | 63        | 4.96%   |
| Cheng Uei Precision Industry (Foxlink) | 55        | 4.33%   |
| Apple                                  | 55        | 4.33%   |
| Sunplus Innovation Technology          | 53        | 4.17%   |
| Suyin                                  | 37        | 2.91%   |
| Luxvisions Innotech Limited            | 37        | 2.91%   |
| Lite-On Technology                     | 36        | 2.83%   |
| Acer                                   | 28        | 2.2%    |
| Syntek                                 | 26        | 2.05%   |
| Logitech                               | 19        | 1.49%   |
| Lenovo                                 | 19        | 1.49%   |
| Ricoh                                  | 17        | 1.34%   |
| Alcor Micro                            | 14        | 1.1%    |
| Shinetech                              | 10        | 0.79%   |
| Sonix Technology                       | 8         | 0.63%   |
| Silicon Motion                         | 8         | 0.63%   |
| Samsung Electronics                    | 6         | 0.47%   |
| ALi                                    | 6         | 0.47%   |
| Primax Electronics                     | 5         | 0.39%   |
| Z-Star Microelectronics                | 3         | 0.24%   |
| Tripath Technology                     | 2         | 0.16%   |
| SunplusIT                              | 2         | 0.16%   |
| OmniVision Technologies                | 2         | 0.16%   |
| Microsoft                              | 2         | 0.16%   |
| Intel                                  | 2         | 0.16%   |
| Generalplus Technology                 | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |
| Xiaomi                                 | 1         | 0.08%   |
| WCM_USB                                | 1         | 0.08%   |
| Tobii Technology AB                    | 1         | 0.08%   |
| Rayprus                                | 1         | 0.08%   |
| Pixart Imaging                         | 1         | 0.08%   |
| OPPO Electronics                       | 1         | 0.08%   |
| Novatek Microelectronics               | 1         | 0.08%   |
| Nikon                                  | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 107       | 8.35%   |
| Microdia Integrated_Webcam_HD                       | 46        | 3.59%   |
| IMC Networks Integrated Camera                      | 43        | 3.35%   |
| Chicony HD WebCam                                   | 39        | 3.04%   |
| Chicony HP HD Camera                                | 30        | 2.34%   |
| Realtek Integrated_Webcam_HD                        | 26        | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 26        | 2.03%   |
| Bison Integrated Camera                             | 25        | 1.95%   |
| Quanta HP HD Camera                                 | 19        | 1.48%   |
| Apple FaceTime HD Camera                            | 19        | 1.48%   |
| Syntek Integrated Camera                            | 17        | 1.33%   |
| Lite-On Integrated Camera                           | 16        | 1.25%   |
| Chicony USB2.0 Camera                               | 16        | 1.25%   |
| Sunplus HD WebCam                                   | 15        | 1.17%   |
| Sunplus Integrated_Webcam_HD                        | 14        | 1.09%   |
| Apple Built-in iSight                               | 14        | 1.09%   |
| Microdia Integrated Webcam                          | 13        | 1.01%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 13        | 1.01%   |
| Lite-On HP HD Camera                                | 13        | 1.01%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 0.94%   |
| Suyin HP Truevision HD                              | 11        | 0.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 11        | 0.86%   |
| Chicony HP Truevision HD                            | 11        | 0.86%   |
| Chicony HP HD Webcam                                | 11        | 0.86%   |
| Chicony HD User Facing                              | 11        | 0.86%   |
| Bison SunplusIT Integrated Camera                   | 11        | 0.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 11        | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 10        | 0.78%   |
| Lenovo Integrated Webcam                            | 9         | 0.7%    |
| Bison Integrated RGB Camera                         | 9         | 0.7%    |
| Quanta HD Webcam                                    | 8         | 0.62%   |
| Quanta HD User Facing                               | 8         | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 8         | 0.62%   |
| Chicony Integrated HP HD Webcam                     | 8         | 0.62%   |
| Acer BisonCam,NB Pro                                | 8         | 0.62%   |
| Realtek USB2.0 HD UVC WebCam                        | 7         | 0.55%   |
| Realtek Integrated Webcam HD                        | 7         | 0.55%   |
| Luxvisions Innotech Limited Integrated Camera       | 7         | 0.55%   |
| Chicony HP Wide Vision HD Camera                    | 7         | 0.55%   |
| Chicony FJ Camera                                   | 7         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 153       | 37.87%  |
| Synaptics                  | 144       | 35.64%  |
| Shenzhen Goodix Technology | 29        | 7.18%   |
| Upek                       | 21        | 5.2%    |
| Elan Microelectronics      | 21        | 5.2%    |
| AuthenTec                  | 18        | 4.46%   |
| LighTuning Technology      | 15        | 3.71%   |
| STMicroelectronics         | 3         | 0.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 54        | 13.37%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 9.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 5.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.21%   |
| Elan ELAN:ARM-M4                                                           | 16        | 3.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 3.71%   |
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 3.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 3.47%   |
| Synaptics Prometheus Fingerprint Reader                                    | 14        | 3.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 3.22%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.72%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.72%   |
| Validity Sensors VFS491                                                    | 10        | 2.48%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 2.48%   |
| Synaptics UWP WBDI Device                                                  | 10        | 2.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 1.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 1.73%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 1.73%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.73%   |
| AuthenTec AES2810                                                          | 7         | 1.73%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.49%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.99%   |
| Elan ELAN:Fingerprint                                                      | 4         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.99%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.74%   |
| Synaptics  WBDI                                                            | 3         | 0.74%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.74%   |
| Unknown                                                                    | 3         | 0.74%   |
| Synaptics TouchPad                                                         | 2         | 0.5%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.25%   |
| Synaptics WBDI Device                                                      | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 67        | 46.53%  |
| Broadcom                  | 47        | 32.64%  |
| Upek                      | 13        | 9.03%   |
| O2 Micro                  | 7         | 4.86%   |
| Yubico.com                | 3         | 2.08%   |
| Lenovo                    | 3         | 2.08%   |
| OmniKey                   | 1         | 0.69%   |
| Gemalto (was Gemplus)     | 1         | 0.69%   |
| Clay Logic                | 1         | 0.69%   |
| Aladdin Knowledge Systems | 1         | 0.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 67        | 46.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 10.42%  |
| Broadcom 5880                                                                | 14        | 9.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 9.03%   |
| Broadcom 58200                                                               | 10        | 6.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 4.86%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.39%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 0.69%   |
| OmniKey CardMan 4321                                                         | 1         | 0.69%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.69%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.69%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 710       | 49.82%  |
| 1     | 545       | 38.25%  |
| 2     | 136       | 9.54%   |
| 3     | 24        | 1.68%   |
| 4     | 7         | 0.49%   |
| 7     | 2         | 0.14%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 400       | 44.1%   |
| Graphics card            | 148       | 16.32%  |
| Chipcard                 | 121       | 13.34%  |
| Net/wireless             | 63        | 6.95%   |
| Multimedia controller    | 49        | 5.4%    |
| Camera                   | 36        | 3.97%   |
| Bluetooth                | 18        | 1.98%   |
| Communication controller | 16        | 1.76%   |
| Card reader              | 15        | 1.65%   |
| Net/ethernet             | 11        | 1.21%   |
| Storage                  | 9         | 0.99%   |
| Sound                    | 6         | 0.66%   |
| Modem                    | 6         | 0.66%   |
| Unassigned class         | 3         | 0.33%   |
| Network                  | 3         | 0.33%   |
| Storage/nvme             | 1         | 0.11%   |
| Flash memory             | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |


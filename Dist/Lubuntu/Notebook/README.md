Lubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

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

Total: 1814

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir7,1               | [b881312456](https://linux-hardware.org/?probe=b881312456) | Dec 28, 2025 |
| HP            | ZBook 15 G5                 | [187734784b](https://linux-hardware.org/?probe=187734784b) | Dec 27, 2025 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [5446798fde](https://linux-hardware.org/?probe=5446798fde) | Dec 26, 2025 |
| Acer          | Aspire E5-575G              | [52e6e48a01](https://linux-hardware.org/?probe=52e6e48a01) | Dec 25, 2025 |
| Acer          | Aspire E5-575G              | [2039c9fd23](https://linux-hardware.org/?probe=2039c9fd23) | Dec 25, 2025 |
| HP            | Pavilion dv7                | [5ae45d1a7f](https://linux-hardware.org/?probe=5ae45d1a7f) | Dec 23, 2025 |
| Lenovo        | Z40-70 20366                | [8667d54ceb](https://linux-hardware.org/?probe=8667d54ceb) | Dec 15, 2025 |
| Lenovo        | Z40-70 20366                | [7ef2e8140b](https://linux-hardware.org/?probe=7ef2e8140b) | Dec 15, 2025 |
| Lenovo        | G770 20089                  | [d917b60756](https://linux-hardware.org/?probe=d917b60756) | Dec 13, 2025 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [2986f7a77d](https://linux-hardware.org/?probe=2986f7a77d) | Dec 13, 2025 |
| Lenovo        | G770 20089                  | [b98314d6c1](https://linux-hardware.org/?probe=b98314d6c1) | Dec 12, 2025 |
| ASUSTek       | UX21E                       | [fd4b7a4f7f](https://linux-hardware.org/?probe=fd4b7a4f7f) | Dec 11, 2025 |
| Acer          | Aspire V7-582PG             | [8c469925a8](https://linux-hardware.org/?probe=8c469925a8) | Dec 08, 2025 |
| HP            | Laptop 17z-ca200            | [c44a3d9c6e](https://linux-hardware.org/?probe=c44a3d9c6e) | Dec 07, 2025 |
| HP            | Laptop 17-cp2xxx            | [1313a11f35](https://linux-hardware.org/?probe=1313a11f35) | Dec 05, 2025 |
| HP            | ENVY TS 15                  | [43d0571ea8](https://linux-hardware.org/?probe=43d0571ea8) | Dec 03, 2025 |
| Lenovo        | ThinkPad W520 42763JU       | [c286ee9983](https://linux-hardware.org/?probe=c286ee9983) | Dec 02, 2025 |
| Lenovo        | B50-10 80QR                 | [4408a00ac3](https://linux-hardware.org/?probe=4408a00ac3) | Dec 01, 2025 |
| Packard Be... | EasyNote ENLG71BM           | [86fc426e2d](https://linux-hardware.org/?probe=86fc426e2d) | Nov 28, 2025 |
| HP            | ENVY 17                     | [0bbe718927](https://linux-hardware.org/?probe=0bbe718927) | Nov 27, 2025 |
| HP            | ENVY 17                     | [d38e7cb95f](https://linux-hardware.org/?probe=d38e7cb95f) | Nov 27, 2025 |
| HP            | Compaq 6710b                | [12b8f96bf2](https://linux-hardware.org/?probe=12b8f96bf2) | Nov 26, 2025 |
| Acer          | Aspire ES1-571              | [a07407b6f4](https://linux-hardware.org/?probe=a07407b6f4) | Nov 24, 2025 |
| Sony          | VGN-NR11M_S                 | [e0d88cd5d7](https://linux-hardware.org/?probe=e0d88cd5d7) | Nov 23, 2025 |
| HP            | Compaq 6710b                | [61884c946b](https://linux-hardware.org/?probe=61884c946b) | Nov 23, 2025 |
| Fujitsu       | LIFEBOOK A3510              | [01eb79614a](https://linux-hardware.org/?probe=01eb79614a) | Nov 21, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [9b12af1d5b](https://linux-hardware.org/?probe=9b12af1d5b) | Nov 21, 2025 |
| Lenovo        | ThinkPad 11e 20EDS00100     | [94498724d0](https://linux-hardware.org/?probe=94498724d0) | Nov 18, 2025 |
| Lenovo        | IdeaPadFlex 10 20324        | [611809cf58](https://linux-hardware.org/?probe=611809cf58) | Nov 17, 2025 |
| ASUSTek       | X541NA                      | [ba3d843404](https://linux-hardware.org/?probe=ba3d843404) | Nov 17, 2025 |
| ASUSTek       | X541NA                      | [523a4f088b](https://linux-hardware.org/?probe=523a4f088b) | Nov 17, 2025 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [9a9fd2a326](https://linux-hardware.org/?probe=9a9fd2a326) | Nov 14, 2025 |
| Sony          | VPCEL22FX                   | [9a0352c14d](https://linux-hardware.org/?probe=9a0352c14d) | Nov 10, 2025 |
| Dell          | Inspiron N4030              | [1d78d381a1](https://linux-hardware.org/?probe=1d78d381a1) | Nov 06, 2025 |
| Lenovo        | ThinkPad T470p 20J7S0LY0... | [0a836fb3b4](https://linux-hardware.org/?probe=0a836fb3b4) | Nov 03, 2025 |
| eMachines     | D725                        | [ba8479b330](https://linux-hardware.org/?probe=ba8479b330) | Oct 30, 2025 |
| Acer          | Aspire A114-31              | [844e569f33](https://linux-hardware.org/?probe=844e569f33) | Oct 27, 2025 |
| Dell          | Inspiron 5391               | [850af6caf7](https://linux-hardware.org/?probe=850af6caf7) | Oct 26, 2025 |
| Apple         | MacBookPro5,1               | [4bc19563eb](https://linux-hardware.org/?probe=4bc19563eb) | Oct 24, 2025 |
| HP            | EliteBook 650 15.6 inch ... | [5416470867](https://linux-hardware.org/?probe=5416470867) | Oct 22, 2025 |
| Dell          | Inspiron 15-3567            | [3bc87565bb](https://linux-hardware.org/?probe=3bc87565bb) | Oct 21, 2025 |
| Acer          | Aspire ES1-520              | [ec550c4995](https://linux-hardware.org/?probe=ec550c4995) | Oct 20, 2025 |
| Acer          | Aspire ES1-520              | [cf4de4bd8d](https://linux-hardware.org/?probe=cf4de4bd8d) | Oct 20, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [96c9e8193e](https://linux-hardware.org/?probe=96c9e8193e) | Oct 19, 2025 |
| Dell          | Latitude E7270              | [d297fcac05](https://linux-hardware.org/?probe=d297fcac05) | Oct 16, 2025 |
| Dell          | Latitude E7270              | [84182994aa](https://linux-hardware.org/?probe=84182994aa) | Oct 16, 2025 |
| Fujitsu Si... | AMILO A7645                 | [bfb4443389](https://linux-hardware.org/?probe=bfb4443389) | Oct 14, 2025 |
| Apple         | MacBookPro9,2               | [f81897d780](https://linux-hardware.org/?probe=f81897d780) | Oct 12, 2025 |
| HP            | ProBook 4730s               | [e4fa6f7446](https://linux-hardware.org/?probe=e4fa6f7446) | Oct 12, 2025 |
| Acer          | Aspire V5-573               | [0200752dbc](https://linux-hardware.org/?probe=0200752dbc) | Oct 10, 2025 |
| Sony          | VGN-FE41ZR                  | [3c07816a20](https://linux-hardware.org/?probe=3c07816a20) | Oct 08, 2025 |
| Sony          | VGN-FE41ZR                  | [47f9dfeb71](https://linux-hardware.org/?probe=47f9dfeb71) | Oct 08, 2025 |
| PCBOX         | Kant                        | [ae71a58f79](https://linux-hardware.org/?probe=ae71a58f79) | Oct 05, 2025 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [442b3ae465](https://linux-hardware.org/?probe=442b3ae465) | Oct 04, 2025 |
| Acer          | Aspire E1-572               | [e2ab445e9f](https://linux-hardware.org/?probe=e2ab445e9f) | Sep 29, 2025 |
| Apple         | MacBookPro7,1               | [f780867d90](https://linux-hardware.org/?probe=f780867d90) | Sep 27, 2025 |
| HP            | ENVY 15                     | [93595a3107](https://linux-hardware.org/?probe=93595a3107) | Sep 27, 2025 |
| Apple         | MacBookPro7,1               | [cb55cdef5a](https://linux-hardware.org/?probe=cb55cdef5a) | Sep 26, 2025 |
| Lenovo        | V110-15ISK 80TL             | [2046c31731](https://linux-hardware.org/?probe=2046c31731) | Sep 21, 2025 |
| ECS           | SF20PA2                     | [acf2b0e1ee](https://linux-hardware.org/?probe=acf2b0e1ee) | Sep 21, 2025 |
| HP            | EliteBook 840 G2            | [21ef567111](https://linux-hardware.org/?probe=21ef567111) | Sep 19, 2025 |
| Dell          | Latitude E5440              | [bd12814a9e](https://linux-hardware.org/?probe=bd12814a9e) | Sep 16, 2025 |
| Dell          | Precision M2800             | [3535af16c8](https://linux-hardware.org/?probe=3535af16c8) | Sep 16, 2025 |
| HP            | Stream Laptop 14-cb0XX      | [441808f496](https://linux-hardware.org/?probe=441808f496) | Sep 15, 2025 |
| HP            | ProBook 6570b               | [0466cf5fff](https://linux-hardware.org/?probe=0466cf5fff) | Sep 12, 2025 |
| ASUSTek       | X541UAK                     | [b2215a01fb](https://linux-hardware.org/?probe=b2215a01fb) | Sep 12, 2025 |
| Dell          | Latitude E7470              | [d2ff88be31](https://linux-hardware.org/?probe=d2ff88be31) | Sep 10, 2025 |
| Lunnen        | LL4FA                       | [17126e82d7](https://linux-hardware.org/?probe=17126e82d7) | Sep 09, 2025 |
| HP            | EliteBook 2560p             | [23ad372c3e](https://linux-hardware.org/?probe=23ad372c3e) | Sep 03, 2025 |
| Sony          | VPCEB1S1E                   | [907b611abf](https://linux-hardware.org/?probe=907b611abf) | Sep 02, 2025 |
| Apple         | MacBook5,1                  | [5c8d94137f](https://linux-hardware.org/?probe=5c8d94137f) | Aug 31, 2025 |
| HP            | Stream Laptop 14-ax0XX      | [ca404e9c3b](https://linux-hardware.org/?probe=ca404e9c3b) | Aug 31, 2025 |
| Fujitsu       | LIFEBOOK A544               | [cf9feb946f](https://linux-hardware.org/?probe=cf9feb946f) | Aug 30, 2025 |
| Fujitsu       | LIFEBOOK A544               | [0d2cbac126](https://linux-hardware.org/?probe=0d2cbac126) | Aug 30, 2025 |
| Acer          | Aspire V5-471P              | [24f90c7de8](https://linux-hardware.org/?probe=24f90c7de8) | Aug 30, 2025 |
| ASUSTek       | X202E                       | [65cc207f2f](https://linux-hardware.org/?probe=65cc207f2f) | Aug 30, 2025 |
| Lenovo        | Flex 2-14 20404             | [db7fc41efc](https://linux-hardware.org/?probe=db7fc41efc) | Aug 25, 2025 |
| Acer          | Aspire ES1-520              | [1f6b6666b7](https://linux-hardware.org/?probe=1f6b6666b7) | Aug 21, 2025 |
| HP            | Pavilion g6                 | [0bfc6ebf3c](https://linux-hardware.org/?probe=0bfc6ebf3c) | Aug 21, 2025 |
| Dell          | Latitude E6410              | [9c1a57b4d8](https://linux-hardware.org/?probe=9c1a57b4d8) | Aug 19, 2025 |
| Dell          | Latitude E6410              | [54e6c56c74](https://linux-hardware.org/?probe=54e6c56c74) | Aug 19, 2025 |
| Acer          | Aspire 5560                 | [263fc3991c](https://linux-hardware.org/?probe=263fc3991c) | Aug 17, 2025 |
| Lenovo        | ThinkPad X230 23244P9       | [be2fdaf6cf](https://linux-hardware.org/?probe=be2fdaf6cf) | Aug 16, 2025 |
| Lenovo        | V17 G4 IRU 83A2             | [686231c062](https://linux-hardware.org/?probe=686231c062) | Aug 13, 2025 |
| Acer          | Aspire S3                   | [fe375f9016](https://linux-hardware.org/?probe=fe375f9016) | Aug 10, 2025 |
| ASUSTek       | X542UQ                      | [06cf45dcc3](https://linux-hardware.org/?probe=06cf45dcc3) | Aug 09, 2025 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [42160d6019](https://linux-hardware.org/?probe=42160d6019) | Aug 09, 2025 |
| Fujitsu       | LIFEBOOK LH531              | [198ae80d52](https://linux-hardware.org/?probe=198ae80d52) | Aug 07, 2025 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [981f697207](https://linux-hardware.org/?probe=981f697207) | Aug 05, 2025 |
| ASUSTek       | K53BY                       | [3573bf734e](https://linux-hardware.org/?probe=3573bf734e) | Aug 01, 2025 |
| Inter Sale... | NBD-11105ES                 | [9958d67e98](https://linux-hardware.org/?probe=9958d67e98) | Jul 30, 2025 |
| Toshiba       | Satellite C55D-A            | [118b3aab4b](https://linux-hardware.org/?probe=118b3aab4b) | Jul 30, 2025 |
| HP            | Laptop 15-fd0xxx            | [1cbe82910e](https://linux-hardware.org/?probe=1cbe82910e) | Jul 30, 2025 |
| Dell          | Precision M4600             | [4e26e2f00b](https://linux-hardware.org/?probe=4e26e2f00b) | Jul 28, 2025 |
| Fujitsu       | LIFEBOOK LH531              | [52b147e2c8](https://linux-hardware.org/?probe=52b147e2c8) | Jul 22, 2025 |
| Lenovo        | ThinkPad X201 Tablet 309... | [4c53479b0d](https://linux-hardware.org/?probe=4c53479b0d) | Jul 20, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [b3a4ba8426](https://linux-hardware.org/?probe=b3a4ba8426) | Jul 19, 2025 |
| HP            | ProBook 445 G7              | [0a9cd22479](https://linux-hardware.org/?probe=0a9cd22479) | Jul 17, 2025 |
| Lenovo        | ThinkPad L480 20LTS15Q00    | [9a5c80fd2d](https://linux-hardware.org/?probe=9a5c80fd2d) | Jul 15, 2025 |
| Lenovo        | ThinkPad L480 20LTS15Q00    | [ffb9f9b610](https://linux-hardware.org/?probe=ffb9f9b610) | Jul 15, 2025 |
| HP            | Compaq 6730s                | [37aa85d0a0](https://linux-hardware.org/?probe=37aa85d0a0) | Jul 12, 2025 |
| HP            | Compaq 6730s                | [a01ccbfb32](https://linux-hardware.org/?probe=a01ccbfb32) | Jul 12, 2025 |
| AVERATEC      | TS-508 Series               | [3d6760b2a7](https://linux-hardware.org/?probe=3d6760b2a7) | Jul 09, 2025 |
| Lenovo        | G480 20156                  | [fee7e1ecbd](https://linux-hardware.org/?probe=fee7e1ecbd) | Jul 08, 2025 |
| IBM           | 2629HWG                     | [2ae56292a3](https://linux-hardware.org/?probe=2ae56292a3) | Jul 07, 2025 |
| IBM           | 2629HWG                     | [4505d175de](https://linux-hardware.org/?probe=4505d175de) | Jul 07, 2025 |
| HP            | ZBook 17                    | [ab76a79f42](https://linux-hardware.org/?probe=ab76a79f42) | Jul 04, 2025 |
| Apple         | MacBookAir1,1               | [3c69c5fc21](https://linux-hardware.org/?probe=3c69c5fc21) | Jul 04, 2025 |
| Apple         | MacBookAir1,1               | [b7769fdc36](https://linux-hardware.org/?probe=b7769fdc36) | Jun 29, 2025 |
| Acer          | TravelMate P214-53          | [3a8b3fb7e0](https://linux-hardware.org/?probe=3a8b3fb7e0) | Jun 29, 2025 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | [4c85cd4870](https://linux-hardware.org/?probe=4c85cd4870) | Jun 28, 2025 |
| AXDIA Inte... | WINPAD V10                  | [f54e485f83](https://linux-hardware.org/?probe=f54e485f83) | Jun 28, 2025 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | [0d565fa947](https://linux-hardware.org/?probe=0d565fa947) | Jun 28, 2025 |
| ASUSTek       | 1005PXD                     | [4af254cbd7](https://linux-hardware.org/?probe=4af254cbd7) | Jun 23, 2025 |
| ASUSTek       | 1005PXD                     | [d27eb90099](https://linux-hardware.org/?probe=d27eb90099) | Jun 23, 2025 |
| ASUSTek       | 1015PX                      | [fcbda09322](https://linux-hardware.org/?probe=fcbda09322) | Jun 20, 2025 |
| Dell          | Inspiron 15-3567            | [67e88e5327](https://linux-hardware.org/?probe=67e88e5327) | Jun 15, 2025 |
| Samsung       | N150P/N210P/N220P           | [d41ed8aced](https://linux-hardware.org/?probe=d41ed8aced) | Jun 14, 2025 |
| HP            | Stream Notebook PC 13       | [1939591af7](https://linux-hardware.org/?probe=1939591af7) | Jun 11, 2025 |
| HP            | EliteBook 840 G5            | [a8f1d36fc4](https://linux-hardware.org/?probe=a8f1d36fc4) | Jun 10, 2025 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [03785ea821](https://linux-hardware.org/?probe=03785ea821) | Jun 07, 2025 |
| Sony          | VGN-CR260F                  | [ee56468a4c](https://linux-hardware.org/?probe=ee56468a4c) | Jun 07, 2025 |
| Acer          | Extensa 5220                | [459ae76023](https://linux-hardware.org/?probe=459ae76023) | Jun 05, 2025 |
| HP            | Laptop 15-da0xxx            | [7c449be419](https://linux-hardware.org/?probe=7c449be419) | May 25, 2025 |
| Acer          | Aspire ES1-520              | [a033f52b7f](https://linux-hardware.org/?probe=a033f52b7f) | May 24, 2025 |
| ASUSTek       | K73BR                       | [138a809fa8](https://linux-hardware.org/?probe=138a809fa8) | May 24, 2025 |
| Lenovo        | Yoga 300-11IBY 80M0         | [34cd0e4946](https://linux-hardware.org/?probe=34cd0e4946) | May 20, 2025 |
| Acer          | Aspire 5336                 | [a7cf3550b7](https://linux-hardware.org/?probe=a7cf3550b7) | May 20, 2025 |
| HP            | EliteBook 8460p             | [f5d165b107](https://linux-hardware.org/?probe=f5d165b107) | May 19, 2025 |
| Lenovo        | Flex 2-14 20404             | [385da9446f](https://linux-hardware.org/?probe=385da9446f) | May 15, 2025 |
| ASUSTek       | T200TA                      | [5634b07075](https://linux-hardware.org/?probe=5634b07075) | May 14, 2025 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [49a443f528](https://linux-hardware.org/?probe=49a443f528) | May 13, 2025 |
| Samsung       | R530/R730/P590              | [1caece1e67](https://linux-hardware.org/?probe=1caece1e67) | May 11, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [8bb6cff00d](https://linux-hardware.org/?probe=8bb6cff00d) | May 11, 2025 |
| Dell          | Vostro 3360                 | [62cb962cba](https://linux-hardware.org/?probe=62cb962cba) | May 10, 2025 |
| Lenovo        | Yoga 300-11IBY 80M0         | [489f5af827](https://linux-hardware.org/?probe=489f5af827) | May 09, 2025 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [092fe815c8](https://linux-hardware.org/?probe=092fe815c8) | May 08, 2025 |
| Dell          | Inspiron N7010              | [dcd3dde686](https://linux-hardware.org/?probe=dcd3dde686) | May 08, 2025 |
| Dell          | Inspiron N7010              | [158472e8ff](https://linux-hardware.org/?probe=158472e8ff) | May 08, 2025 |
| ASUSTek       | T200TA                      | [c6f4914489](https://linux-hardware.org/?probe=c6f4914489) | May 07, 2025 |
| Toshiba       | K201                        | [1a2734d9d7](https://linux-hardware.org/?probe=1a2734d9d7) | May 07, 2025 |
| Apple         | MacBookPro7,1               | [989dd25d8f](https://linux-hardware.org/?probe=989dd25d8f) | May 06, 2025 |
| Chuwi         | HeroBook Pro                | [d98a0232b2](https://linux-hardware.org/?probe=d98a0232b2) | May 03, 2025 |
| ASUSTek       | K54C                        | [9ac9aadb24](https://linux-hardware.org/?probe=9ac9aadb24) | May 02, 2025 |
| Acer          | Aspire ES1-531              | [ddddeb6319](https://linux-hardware.org/?probe=ddddeb6319) | Apr 30, 2025 |
| Dell          | Latitude 7490               | [067a83a8a8](https://linux-hardware.org/?probe=067a83a8a8) | Apr 30, 2025 |
| Dell          | Latitude 7490               | [feed6c8978](https://linux-hardware.org/?probe=feed6c8978) | Apr 30, 2025 |
| Dell          | Latitude 7400               | [e22e34e51b](https://linux-hardware.org/?probe=e22e34e51b) | Apr 30, 2025 |
| Dell          | Latitude 7480               | [d1396b5509](https://linux-hardware.org/?probe=d1396b5509) | Apr 30, 2025 |
| HP            | EliteBook 840 G3            | [712a773eeb](https://linux-hardware.org/?probe=712a773eeb) | Apr 29, 2025 |
| SK hynix      | HT14CCIC42E                 | [9eae655a49](https://linux-hardware.org/?probe=9eae655a49) | Apr 29, 2025 |
| HP            | EliteBook 840 G3            | [e8909e91b9](https://linux-hardware.org/?probe=e8909e91b9) | Apr 29, 2025 |
| HP            | EliteBook 840 G3            | [178fac9008](https://linux-hardware.org/?probe=178fac9008) | Apr 29, 2025 |
| HP            | EliteBook 840 G3            | [194599afe2](https://linux-hardware.org/?probe=194599afe2) | Apr 29, 2025 |
| Lenovo        | G450 2949                   | [3ad9e4247c](https://linux-hardware.org/?probe=3ad9e4247c) | Apr 28, 2025 |
| Acer          | Aspire A715-72G             | [80425a0c3d](https://linux-hardware.org/?probe=80425a0c3d) | Apr 28, 2025 |
| Lenovo        | B430 62702BP                | [6ce52a0e9a](https://linux-hardware.org/?probe=6ce52a0e9a) | Apr 26, 2025 |
| Lenovo        | B430 62702BP                | [9456f2eadd](https://linux-hardware.org/?probe=9456f2eadd) | Apr 26, 2025 |
| HP            | Stream Laptop 14-cb0XX      | [8b01d0c8bb](https://linux-hardware.org/?probe=8b01d0c8bb) | Apr 21, 2025 |
| Lenovo        | G50-45 80E3                 | [9ccfe014a1](https://linux-hardware.org/?probe=9ccfe014a1) | Apr 20, 2025 |
| Lenovo        | ThinkPad P51 20HJS0BR0E     | [cb7152ef4a](https://linux-hardware.org/?probe=cb7152ef4a) | Apr 19, 2025 |
| Lenovo        | V15 G4 IRU 83A1             | [0c6e121418](https://linux-hardware.org/?probe=0c6e121418) | Apr 17, 2025 |
| Google        | Cyan                        | [631b41039d](https://linux-hardware.org/?probe=631b41039d) | Apr 16, 2025 |
| Fujitsu       | LIFEBOOK U745               | [bfdf53f32b](https://linux-hardware.org/?probe=bfdf53f32b) | Apr 14, 2025 |
| Medion        | S6421 MD60703               | [ed6f7170e1](https://linux-hardware.org/?probe=ed6f7170e1) | Apr 11, 2025 |
| Samsung       | R519/R719                   | [5ffb25cebb](https://linux-hardware.org/?probe=5ffb25cebb) | Apr 10, 2025 |
| Lenovo        | V15 G4 IRU 83A1             | [30be4dfa4c](https://linux-hardware.org/?probe=30be4dfa4c) | Apr 07, 2025 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [11874f224f](https://linux-hardware.org/?probe=11874f224f) | Apr 01, 2025 |
| HP            | 250 G5 Notebook PC          | [4d3f359ef4](https://linux-hardware.org/?probe=4d3f359ef4) | Mar 28, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [8c45cf9d65](https://linux-hardware.org/?probe=8c45cf9d65) | Mar 28, 2025 |
| HP            | Pavilion 11 x360 PC         | [eab98e14e1](https://linux-hardware.org/?probe=eab98e14e1) | Mar 26, 2025 |
| HP            | ProBook 6460b               | [a3a6d64fe2](https://linux-hardware.org/?probe=a3a6d64fe2) | Mar 24, 2025 |
| HP            | ProBook 6460b               | [a060640b1e](https://linux-hardware.org/?probe=a060640b1e) | Mar 24, 2025 |
| HP            | ProBook 6460b               | [852b5001e7](https://linux-hardware.org/?probe=852b5001e7) | Mar 24, 2025 |
| HP            | ProBook 6460b               | [64d1d555fe](https://linux-hardware.org/?probe=64d1d555fe) | Mar 23, 2025 |
| LG Electro... | R510-L.BP42P1               | [74d30a32bf](https://linux-hardware.org/?probe=74d30a32bf) | Mar 21, 2025 |
| LG Electro... | R510-L.BP42P1               | [8009c46e83](https://linux-hardware.org/?probe=8009c46e83) | Mar 21, 2025 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bf7e3d0e2](https://linux-hardware.org/?probe=1bf7e3d0e2) | Mar 20, 2025 |
| Toshiba       | Satellite A215              | [3b623d2fba](https://linux-hardware.org/?probe=3b623d2fba) | Mar 18, 2025 |
| HP            | Pavilion 15                 | [d310efa1b2](https://linux-hardware.org/?probe=d310efa1b2) | Mar 18, 2025 |
| ASUSTek       | K73TA                       | [60e799694d](https://linux-hardware.org/?probe=60e799694d) | Mar 17, 2025 |
| Dell          | Inspiron 15 3515            | [200f54b6ad](https://linux-hardware.org/?probe=200f54b6ad) | Mar 16, 2025 |
| Dell          | Latitude 7310               | [df905e635d](https://linux-hardware.org/?probe=df905e635d) | Mar 14, 2025 |
| Lenovo        | ThinkBook 14 G7 IML 21MR    | [8907fb5752](https://linux-hardware.org/?probe=8907fb5752) | Mar 14, 2025 |
| Dell          | Latitude E6440              | [bb9b7661d4](https://linux-hardware.org/?probe=bb9b7661d4) | Mar 13, 2025 |
| Dell          | Latitude E6440              | [0051bb6671](https://linux-hardware.org/?probe=0051bb6671) | Mar 13, 2025 |
| HP            | Notebook                    | [968d4ecd8a](https://linux-hardware.org/?probe=968d4ecd8a) | Mar 12, 2025 |
| HP            | Notebook                    | [cb7c5e62f5](https://linux-hardware.org/?probe=cb7c5e62f5) | Mar 12, 2025 |
| Dell          | Latitude E6540              | [c412ebe459](https://linux-hardware.org/?probe=c412ebe459) | Mar 12, 2025 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [73b39a0ede](https://linux-hardware.org/?probe=73b39a0ede) | Mar 10, 2025 |
| Apple         | MacBookPro9,2               | [8e77314cdf](https://linux-hardware.org/?probe=8e77314cdf) | Mar 09, 2025 |
| ASUSTek       | UX21E                       | [35cbd54797](https://linux-hardware.org/?probe=35cbd54797) | Mar 08, 2025 |
| Lenovo        | ThinkPad T400 6474B84       | [a1639640b3](https://linux-hardware.org/?probe=a1639640b3) | Mar 08, 2025 |
| Lenovo        | ThinkPad T400 6474B84       | [efcf8daf47](https://linux-hardware.org/?probe=efcf8daf47) | Mar 08, 2025 |
| Dell          | Precision M4600             | [cca2a0bede](https://linux-hardware.org/?probe=cca2a0bede) | Mar 08, 2025 |
| Dell          | Precision M4600             | [da5e065e14](https://linux-hardware.org/?probe=da5e065e14) | Mar 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [c34e227278](https://linux-hardware.org/?probe=c34e227278) | Mar 06, 2025 |
| Acer          | TravelMate B117-M           | [e9e8f04857](https://linux-hardware.org/?probe=e9e8f04857) | Mar 05, 2025 |
| Acer          | Aspire E1-572G              | [41152bfded](https://linux-hardware.org/?probe=41152bfded) | Mar 03, 2025 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [fc29bd79f0](https://linux-hardware.org/?probe=fc29bd79f0) | Mar 03, 2025 |
| Dell          | Inspiron 1525               | [1c4bf1fcef](https://linux-hardware.org/?probe=1c4bf1fcef) | Mar 01, 2025 |
| Dell          | Inspiron 1525               | [5d1bacca4c](https://linux-hardware.org/?probe=5d1bacca4c) | Mar 01, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9205563abd](https://linux-hardware.org/?probe=9205563abd) | Mar 01, 2025 |
| HP            | Laptop 15-bs0xx             | [f493249515](https://linux-hardware.org/?probe=f493249515) | Mar 01, 2025 |
| ASUSTek       | X556UJ                      | [6aa5a962d3](https://linux-hardware.org/?probe=6aa5a962d3) | Feb 27, 2025 |
| Toshiba       | Satellite Pro S500          | [d87b4c540a](https://linux-hardware.org/?probe=d87b4c540a) | Feb 26, 2025 |
| HP            | Laptop 15-da0xxx            | [99a9f8d81e](https://linux-hardware.org/?probe=99a9f8d81e) | Feb 21, 2025 |
| HP            | Laptop 15-bs0xx             | [692770517b](https://linux-hardware.org/?probe=692770517b) | Feb 20, 2025 |
| ASUSTek       | K84L                        | [6cac2213fa](https://linux-hardware.org/?probe=6cac2213fa) | Feb 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [00d4813dc6](https://linux-hardware.org/?probe=00d4813dc6) | Feb 17, 2025 |
| MSI           | Prestige 14Evo A11MO        | [becbf1aef8](https://linux-hardware.org/?probe=becbf1aef8) | Feb 11, 2025 |
| eMachines     | G725                        | [b7ee836429](https://linux-hardware.org/?probe=b7ee836429) | Feb 11, 2025 |
| eMachines     | G725                        | [e54b69b49c](https://linux-hardware.org/?probe=e54b69b49c) | Feb 10, 2025 |
| Toshiba       | Satellite P55W-C            | [4cdab63f23](https://linux-hardware.org/?probe=4cdab63f23) | Feb 09, 2025 |
| HP            | Laptop 17-ak0xx             | [53a1ff62bb](https://linux-hardware.org/?probe=53a1ff62bb) | Feb 09, 2025 |
| ASUSTek       | X451CA                      | [fd5776db86](https://linux-hardware.org/?probe=fd5776db86) | Feb 08, 2025 |
| ASUSTek       | X451CA                      | [308b4050db](https://linux-hardware.org/?probe=308b4050db) | Feb 08, 2025 |
| HP            | Unknown                     | [ef51904b41](https://linux-hardware.org/?probe=ef51904b41) | Feb 06, 2025 |
| HP            | Pavilion g6                 | [748cd34f19](https://linux-hardware.org/?probe=748cd34f19) | Feb 05, 2025 |
| HP            | Pavilion g6                 | [94f3d27d98](https://linux-hardware.org/?probe=94f3d27d98) | Feb 05, 2025 |
| Samsung       | NC210/NC110                 | [8d211624d4](https://linux-hardware.org/?probe=8d211624d4) | Feb 05, 2025 |
| Philco        | 14M2                        | [b3ad4b8037](https://linux-hardware.org/?probe=b3ad4b8037) | Feb 02, 2025 |
| Acer          | Aspire V5-531               | [fdf72272f8](https://linux-hardware.org/?probe=fdf72272f8) | Feb 02, 2025 |
| eMachines     | G430                        | [ca8d6c779a](https://linux-hardware.org/?probe=ca8d6c779a) | Feb 02, 2025 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [429beba248](https://linux-hardware.org/?probe=429beba248) | Feb 01, 2025 |
| HP            | 15                          | [40da2a3290](https://linux-hardware.org/?probe=40da2a3290) | Feb 01, 2025 |
| HP            | 15                          | [ea09f7e536](https://linux-hardware.org/?probe=ea09f7e536) | Feb 01, 2025 |
| Medion        | E5211                       | [8ececdcdc5](https://linux-hardware.org/?probe=8ececdcdc5) | Jan 31, 2025 |
| Fujitsu       | LIFEBOOK AH531              | [6986e60f2e](https://linux-hardware.org/?probe=6986e60f2e) | Jan 30, 2025 |
| HP            | Pavilion g7                 | [f4c5a61524](https://linux-hardware.org/?probe=f4c5a61524) | Jan 27, 2025 |
| HP            | EliteBook 8460p             | [4925a7f8a8](https://linux-hardware.org/?probe=4925a7f8a8) | Jan 26, 2025 |
| Medion        | WIM2180                     | [d2fdd0c96c](https://linux-hardware.org/?probe=d2fdd0c96c) | Jan 24, 2025 |
| Google        | Babymega                    | [ab92ac101a](https://linux-hardware.org/?probe=ab92ac101a) | Jan 21, 2025 |
| PIPO          | X9S                         | [fd01051c66](https://linux-hardware.org/?probe=fd01051c66) | Jan 20, 2025 |
| HP            | Unknown                     | [d160dd68df](https://linux-hardware.org/?probe=d160dd68df) | Jan 19, 2025 |
| Medion        | WIM2180                     | [85c3f47766](https://linux-hardware.org/?probe=85c3f47766) | Jan 19, 2025 |
| HP            | Pavilion dv4                | [bbbfe6c24f](https://linux-hardware.org/?probe=bbbfe6c24f) | Jan 19, 2025 |
| HP            | Compaq nc4400 (RL880AW#A... | [2f8c299d99](https://linux-hardware.org/?probe=2f8c299d99) | Jan 14, 2025 |
| Dell          | Latitude 5590               | [8cd5217873](https://linux-hardware.org/?probe=8cd5217873) | Jan 12, 2025 |
| Positivo      | S14BW01                     | [39679334e6](https://linux-hardware.org/?probe=39679334e6) | Jan 12, 2025 |
| Positivo      | S14BW01                     | [1f63e89a10](https://linux-hardware.org/?probe=1f63e89a10) | Jan 12, 2025 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [e8939502f7](https://linux-hardware.org/?probe=e8939502f7) | Jan 11, 2025 |
| ASUSTek       | X550MJ                      | [4a038e9d8b](https://linux-hardware.org/?probe=4a038e9d8b) | Jan 10, 2025 |
| HP            | Notebook                    | [2173dcc27a](https://linux-hardware.org/?probe=2173dcc27a) | Jan 09, 2025 |
| NVN-ED01      | Unknown                     | [f3e890317d](https://linux-hardware.org/?probe=f3e890317d) | Jan 07, 2025 |
| HP            | Pavilion g7                 | [5692787b6f](https://linux-hardware.org/?probe=5692787b6f) | Dec 31, 2024 |
| Acer          | Aspire A114-32              | [d4aff4e66c](https://linux-hardware.org/?probe=d4aff4e66c) | Dec 30, 2024 |
| Fujitsu       | LIFEBOOK AH531              | [37872e53dc](https://linux-hardware.org/?probe=37872e53dc) | Dec 30, 2024 |
| Fujitsu       | LIFEBOOK AH531              | [0dc9a2432a](https://linux-hardware.org/?probe=0dc9a2432a) | Dec 30, 2024 |
| HP            | Notebook                    | [fb6c3eebe1](https://linux-hardware.org/?probe=fb6c3eebe1) | Dec 29, 2024 |
| Unchartevi... | 6540                        | [1d27092258](https://linux-hardware.org/?probe=1d27092258) | Dec 29, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [5099a4c834](https://linux-hardware.org/?probe=5099a4c834) | Dec 28, 2024 |
| Unknown       | Unknown                     | [dae997fee3](https://linux-hardware.org/?probe=dae997fee3) | Dec 26, 2024 |
| Dell          | Inspiron 1545               | [9cc6330a09](https://linux-hardware.org/?probe=9cc6330a09) | Dec 21, 2024 |
| Dell          | System XPS 15Z              | [9e7fc2d36e](https://linux-hardware.org/?probe=9e7fc2d36e) | Dec 20, 2024 |
| ASUSTek       | X550CL                      | [ca719e1a32](https://linux-hardware.org/?probe=ca719e1a32) | Dec 20, 2024 |
| Medion        | S6421 MD60703               | [609c73a176](https://linux-hardware.org/?probe=609c73a176) | Dec 19, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [bc07631f18](https://linux-hardware.org/?probe=bc07631f18) | Dec 18, 2024 |
| Lenovo        | IdeaPad S405 9802           | [10b9693723](https://linux-hardware.org/?probe=10b9693723) | Dec 17, 2024 |
| Lenovo        | IdeaPad S405 9802           | [3a61babe21](https://linux-hardware.org/?probe=3a61babe21) | Dec 17, 2024 |
| Packard Be... | DOT S                       | [60865a1411](https://linux-hardware.org/?probe=60865a1411) | Dec 14, 2024 |
| HP            | EliteBook 835 13 inch G1... | [501650199f](https://linux-hardware.org/?probe=501650199f) | Dec 12, 2024 |
| HP            | 2000                        | [3c20e6e18c](https://linux-hardware.org/?probe=3c20e6e18c) | Dec 11, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [291861d530](https://linux-hardware.org/?probe=291861d530) | Dec 08, 2024 |
| Dell          | Inspiron 15-3567            | [cbf6bf1b48](https://linux-hardware.org/?probe=cbf6bf1b48) | Dec 06, 2024 |
| HP            | Laptop 15-db0xxx            | [469069638e](https://linux-hardware.org/?probe=469069638e) | Dec 01, 2024 |
| Google        | Candy                       | [035e637f3d](https://linux-hardware.org/?probe=035e637f3d) | Dec 01, 2024 |
| Acer          | AO722                       | [15b4d05c90](https://linux-hardware.org/?probe=15b4d05c90) | Nov 25, 2024 |
| Acer          | AO722                       | [f5300839f0](https://linux-hardware.org/?probe=f5300839f0) | Nov 25, 2024 |
| Apple         | MacBook5,1                  | [c9bc1374b3](https://linux-hardware.org/?probe=c9bc1374b3) | Nov 25, 2024 |
| Google        | Candy                       | [cac90e3ac0](https://linux-hardware.org/?probe=cac90e3ac0) | Nov 25, 2024 |
| Google        | Candy                       | [0cb5a31970](https://linux-hardware.org/?probe=0cb5a31970) | Nov 23, 2024 |
| Sony          | M730                        | [55d7e62f9d](https://linux-hardware.org/?probe=55d7e62f9d) | Nov 23, 2024 |
| HP            | Notebook                    | [bb9e0faf8f](https://linux-hardware.org/?probe=bb9e0faf8f) | Nov 22, 2024 |
| Medion        | E122X                       | [e7c29c8ff7](https://linux-hardware.org/?probe=e7c29c8ff7) | Nov 19, 2024 |
| Apple         | MacBookPro8,1               | [ba64567726](https://linux-hardware.org/?probe=ba64567726) | Nov 18, 2024 |
| Dell          | Inspiron 15-3567            | [815225e627](https://linux-hardware.org/?probe=815225e627) | Nov 18, 2024 |
| Apple         | MacBook5,1                  | [fc4768f63d](https://linux-hardware.org/?probe=fc4768f63d) | Nov 17, 2024 |
| Dell          | XPS MXC062                  | [bb0597c639](https://linux-hardware.org/?probe=bb0597c639) | Nov 15, 2024 |
| Dell          | XPS MXC062                  | [fbc63bd772](https://linux-hardware.org/?probe=fbc63bd772) | Nov 15, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [342d578a5c](https://linux-hardware.org/?probe=342d578a5c) | Nov 13, 2024 |
| Acer          | Aspire ES1-531              | [a7c11e81f1](https://linux-hardware.org/?probe=a7c11e81f1) | Nov 09, 2024 |
| HP            | ProBook 430 G2              | [ea645a6ae1](https://linux-hardware.org/?probe=ea645a6ae1) | Nov 08, 2024 |
| Fujitsu Si... | AMILO A7645                 | [82b3b117c2](https://linux-hardware.org/?probe=82b3b117c2) | Nov 08, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [67b92639b5](https://linux-hardware.org/?probe=67b92639b5) | Nov 05, 2024 |
| Sony          | VPCF132FX                   | [b584189661](https://linux-hardware.org/?probe=b584189661) | Nov 03, 2024 |
| Dell          | Latitude E7240              | [82e1ee846b](https://linux-hardware.org/?probe=82e1ee846b) | Nov 02, 2024 |
| Lenovo        | G770 20089                  | [3547cb6c29](https://linux-hardware.org/?probe=3547cb6c29) | Oct 30, 2024 |
| LG Electro... | X110-L.B7BLP1               | [a71f31873d](https://linux-hardware.org/?probe=a71f31873d) | Oct 29, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d47c826466](https://linux-hardware.org/?probe=d47c826466) | Oct 28, 2024 |
| HP            | 245 G8 Notebook PC          | [8a3413b200](https://linux-hardware.org/?probe=8a3413b200) | Oct 26, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [6028ccb88f](https://linux-hardware.org/?probe=6028ccb88f) | Oct 25, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRT     | [0faadd1106](https://linux-hardware.org/?probe=0faadd1106) | Oct 24, 2024 |
| Toshiba       | Satellite C660              | [11806f6477](https://linux-hardware.org/?probe=11806f6477) | Oct 24, 2024 |
| Dell          | Latitude E5450              | [0465141d52](https://linux-hardware.org/?probe=0465141d52) | Oct 23, 2024 |
| Toshiba       | Satellite P55W-C            | [84c58de68f](https://linux-hardware.org/?probe=84c58de68f) | Oct 23, 2024 |
| Toshiba       | Satellite P55W-C            | [2fbe7927f9](https://linux-hardware.org/?probe=2fbe7927f9) | Oct 23, 2024 |
| Apple         | MacBookPro16,2              | [6e69e5e4a4](https://linux-hardware.org/?probe=6e69e5e4a4) | Oct 23, 2024 |
| HP            | EliteBook 2540p             | [53c668190f](https://linux-hardware.org/?probe=53c668190f) | Oct 23, 2024 |
| Fujitsu       | LIFEBOOK AH531              | [7205fb0b92](https://linux-hardware.org/?probe=7205fb0b92) | Oct 23, 2024 |
| Dell          | Inspiron 1501               | [5ac3420a2b](https://linux-hardware.org/?probe=5ac3420a2b) | Oct 22, 2024 |
| HP            | Pavilion Laptop 15-cs315... | [c61e1c6184](https://linux-hardware.org/?probe=c61e1c6184) | Oct 22, 2024 |
| Lenovo        | Z70-80 80FG                 | [df61da6a87](https://linux-hardware.org/?probe=df61da6a87) | Oct 22, 2024 |
| HP            | EliteBook 830 G6            | [f7d13716ee](https://linux-hardware.org/?probe=f7d13716ee) | Oct 22, 2024 |
| Medion        | S6421 MD60703               | [c92c3514b3](https://linux-hardware.org/?probe=c92c3514b3) | Oct 22, 2024 |
| Dell          | Latitude E5450              | [2ec7e21290](https://linux-hardware.org/?probe=2ec7e21290) | Oct 19, 2024 |
| Chuwi         | GemiBook Pro                | [be2a9177cc](https://linux-hardware.org/?probe=be2a9177cc) | Oct 19, 2024 |
| HP            | InsydeH2O EFI BIOS          | [3d33564930](https://linux-hardware.org/?probe=3d33564930) | Oct 16, 2024 |
| HP            | Compaq CQ58                 | [129913dcc6](https://linux-hardware.org/?probe=129913dcc6) | Oct 14, 2024 |
| Positivo      | C14CU51                     | [a50a121b61](https://linux-hardware.org/?probe=a50a121b61) | Oct 12, 2024 |
| HP            | 255 G5                      | [062ce32d62](https://linux-hardware.org/?probe=062ce32d62) | Oct 11, 2024 |
| HONOR         | NMH-WCX9                    | [03f4ff2833](https://linux-hardware.org/?probe=03f4ff2833) | Oct 09, 2024 |
| HONOR         | NMH-WCX9                    | [e167d1430c](https://linux-hardware.org/?probe=e167d1430c) | Oct 09, 2024 |
| Samsung       | 370E4K                      | [f87816505c](https://linux-hardware.org/?probe=f87816505c) | Oct 07, 2024 |
| Acer          | Aspire 5735                 | [4c1559410d](https://linux-hardware.org/?probe=4c1559410d) | Oct 06, 2024 |
| Acer          | Aspire 5735                 | [50e1561f7d](https://linux-hardware.org/?probe=50e1561f7d) | Oct 06, 2024 |
| Dell          | Vostro 1500                 | [6680201494](https://linux-hardware.org/?probe=6680201494) | Oct 06, 2024 |
| Google        | Rabbid                      | [022398a237](https://linux-hardware.org/?probe=022398a237) | Oct 05, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e15bff83db](https://linux-hardware.org/?probe=e15bff83db) | Oct 05, 2024 |
| HP            | EliteBook 2540p             | [582f0a4f04](https://linux-hardware.org/?probe=582f0a4f04) | Oct 04, 2024 |
| Dell          | Inspiron 1100               | [1012ad2903](https://linux-hardware.org/?probe=1012ad2903) | Oct 02, 2024 |
| Toshiba       | Satellite C660              | [1ce63743fd](https://linux-hardware.org/?probe=1ce63743fd) | Oct 01, 2024 |
| Apple         | MacBook4,1                  | [1b71a4b0c9](https://linux-hardware.org/?probe=1b71a4b0c9) | Oct 01, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3SW0... | [d3f2558562](https://linux-hardware.org/?probe=d3f2558562) | Sep 28, 2024 |
| ASUSTek       | X553MA                      | [a96b018191](https://linux-hardware.org/?probe=a96b018191) | Sep 25, 2024 |
| MicroByte     | ezbook                      | [5b878e7b72](https://linux-hardware.org/?probe=5b878e7b72) | Sep 24, 2024 |
| HP            | Pavilion 15                 | [617c9c6fd3](https://linux-hardware.org/?probe=617c9c6fd3) | Sep 22, 2024 |
| HP            | Pavilion 15                 | [47d81a32ab](https://linux-hardware.org/?probe=47d81a32ab) | Sep 22, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [273c5852ff](https://linux-hardware.org/?probe=273c5852ff) | Sep 18, 2024 |
| HP            | InsydeH2O EFI BIOS          | [7102de50a6](https://linux-hardware.org/?probe=7102de50a6) | Sep 17, 2024 |
| Dell          | Latitude E6410              | [92cd0e0eee](https://linux-hardware.org/?probe=92cd0e0eee) | Sep 17, 2024 |
| Dell          | Latitude E6410              | [d9385745e8](https://linux-hardware.org/?probe=d9385745e8) | Sep 17, 2024 |
| Dell          | Inspiron 1564               | [e2028cccf6](https://linux-hardware.org/?probe=e2028cccf6) | Sep 14, 2024 |
| Apple         | MacBookPro8,1               | [606582cd82](https://linux-hardware.org/?probe=606582cd82) | Sep 10, 2024 |
| Acer          | Aspire ES1-571              | [a5aeb5f264](https://linux-hardware.org/?probe=a5aeb5f264) | Sep 10, 2024 |
| Complet       | MY8305                      | [fdab3231de](https://linux-hardware.org/?probe=fdab3231de) | Sep 07, 2024 |
| Samsung       | RV415                       | [e3d0816997](https://linux-hardware.org/?probe=e3d0816997) | Sep 07, 2024 |
| Chuwi         | HeroBook Air                | [09a139dbbe](https://linux-hardware.org/?probe=09a139dbbe) | Sep 04, 2024 |
| Chuwi         | HeroBook Air                | [163bdd4e80](https://linux-hardware.org/?probe=163bdd4e80) | Sep 04, 2024 |
| HP            | EliteBook 8440p             | [70ad6eb824](https://linux-hardware.org/?probe=70ad6eb824) | Sep 03, 2024 |
| Acer          | AOD255                      | [3dace1f171](https://linux-hardware.org/?probe=3dace1f171) | Sep 03, 2024 |
| Acer          | AOD255                      | [7d7265c514](https://linux-hardware.org/?probe=7d7265c514) | Sep 03, 2024 |
| HP            | Compaq 6735s                | [ef4b082281](https://linux-hardware.org/?probe=ef4b082281) | Sep 02, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [acf0e79f7a](https://linux-hardware.org/?probe=acf0e79f7a) | Aug 31, 2024 |
| Dell          | Latitude 5285               | [ece411e4e4](https://linux-hardware.org/?probe=ece411e4e4) | Aug 27, 2024 |
| Lenovo        | ThinkPad L480 20LTS15Q00    | [c7bd2c3d2e](https://linux-hardware.org/?probe=c7bd2c3d2e) | Aug 26, 2024 |
| Fujitsu Si... | AMILO Pi 1505               | [b62ccb34eb](https://linux-hardware.org/?probe=b62ccb34eb) | Aug 23, 2024 |
| HP            | Pavilion dv6                | [8745b6a8a6](https://linux-hardware.org/?probe=8745b6a8a6) | Aug 22, 2024 |
| Acer          | Aspire E5-571G              | [5d217cd410](https://linux-hardware.org/?probe=5d217cd410) | Aug 22, 2024 |
| eMachines     | E725                        | [22fba92ec4](https://linux-hardware.org/?probe=22fba92ec4) | Aug 20, 2024 |
| Lenovo        | ThinkPad T61 7658CTO        | [c395b3e28c](https://linux-hardware.org/?probe=c395b3e28c) | Aug 19, 2024 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [d4e9ec66bb](https://linux-hardware.org/?probe=d4e9ec66bb) | Aug 17, 2024 |
| Dell          | XPS MXC062                  | [46f9c80883](https://linux-hardware.org/?probe=46f9c80883) | Aug 16, 2024 |
| Lenovo        | IdeaPad S205 Brazos         | [e40f1ca18f](https://linux-hardware.org/?probe=e40f1ca18f) | Aug 15, 2024 |
| HP            | EliteBook 8440p             | [46e4c79baf](https://linux-hardware.org/?probe=46e4c79baf) | Aug 13, 2024 |
| HP            | EliteBook 8440p             | [4a401d3cf7](https://linux-hardware.org/?probe=4a401d3cf7) | Aug 13, 2024 |
| HP            | Compaq Presario CQ60        | [d0e97b8772](https://linux-hardware.org/?probe=d0e97b8772) | Aug 13, 2024 |
| HP            | Notebook                    | [0d521e10c8](https://linux-hardware.org/?probe=0d521e10c8) | Aug 11, 2024 |
| ASUSTek       | X540SA                      | [683c8f3f4b](https://linux-hardware.org/?probe=683c8f3f4b) | Aug 11, 2024 |
| SK hynix      | HT14CCIC42E                 | [eb41114fc3](https://linux-hardware.org/?probe=eb41114fc3) | Aug 10, 2024 |
| Acer          | Aspire 5715Z                | [32b3360c63](https://linux-hardware.org/?probe=32b3360c63) | Aug 07, 2024 |
| Acer          | Aspire 5715Z                | [387c8e5fe4](https://linux-hardware.org/?probe=387c8e5fe4) | Aug 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [ef1df870ea](https://linux-hardware.org/?probe=ef1df870ea) | Aug 07, 2024 |
| HP            | Notebook                    | [1a796d1daf](https://linux-hardware.org/?probe=1a796d1daf) | Aug 04, 2024 |
| Dell          | Inspiron N5110              | [c390f98098](https://linux-hardware.org/?probe=c390f98098) | Aug 03, 2024 |
| Acer          | Aspire A515-51              | [edc0e332b2](https://linux-hardware.org/?probe=edc0e332b2) | Aug 01, 2024 |
| Acer          | Aspire A515-51              | [bd658968cf](https://linux-hardware.org/?probe=bd658968cf) | Aug 01, 2024 |
| HP            | Laptop 15-da0xxx            | [ed33f895c9](https://linux-hardware.org/?probe=ed33f895c9) | Jul 28, 2024 |
| Intel         | STCK1A32WFC H67490-303      | [b12d74f728](https://linux-hardware.org/?probe=b12d74f728) | Jul 27, 2024 |
| HP            | Pavilion x2 Detachable      | [f5fb19db6b](https://linux-hardware.org/?probe=f5fb19db6b) | Jul 27, 2024 |
| Acer          | Swift SF113-31              | [6c63a7574e](https://linux-hardware.org/?probe=6c63a7574e) | Jul 26, 2024 |
| HP            | Pavilion x2 Detachable      | [8f6ba78b79](https://linux-hardware.org/?probe=8f6ba78b79) | Jul 25, 2024 |
| Acer          | Aspire A515-57G             | [e7fba30a89](https://linux-hardware.org/?probe=e7fba30a89) | Jul 23, 2024 |
| Dell          | Inspiron 3135               | [36c80b438d](https://linux-hardware.org/?probe=36c80b438d) | Jul 22, 2024 |
| HP            | 240 G4                      | [74ad43cd86](https://linux-hardware.org/?probe=74ad43cd86) | Jul 19, 2024 |
| PROBOOK       | U SERIES                    | [e9b030a9df](https://linux-hardware.org/?probe=e9b030a9df) | Jul 17, 2024 |
| PROBOOK       | U SERIES                    | [bdc92be04b](https://linux-hardware.org/?probe=bdc92be04b) | Jul 15, 2024 |
| Apple         | MacBookPro9,2               | [e0376fa4fe](https://linux-hardware.org/?probe=e0376fa4fe) | Jul 13, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [64b642a303](https://linux-hardware.org/?probe=64b642a303) | Jul 12, 2024 |
| ASUSTek       | K52JB                       | [d50ec4eed9](https://linux-hardware.org/?probe=d50ec4eed9) | Jul 09, 2024 |
| Lenovo        | ThinkPad L13 Gen 1 20R4S... | [4cc52bfb25](https://linux-hardware.org/?probe=4cc52bfb25) | Jul 07, 2024 |
| Notebook      | PB50_70EF,ED,EC             | [9d7e31a9f6](https://linux-hardware.org/?probe=9d7e31a9f6) | Jul 06, 2024 |
| Dell          | XPS M1330                   | [a01b178b3a](https://linux-hardware.org/?probe=a01b178b3a) | Jul 06, 2024 |
| Acer          | Aspire V5-471P              | [f8a09477f0](https://linux-hardware.org/?probe=f8a09477f0) | Jul 05, 2024 |
| Packard Be... | EasyNote TE69BM             | [e4f954f464](https://linux-hardware.org/?probe=e4f954f464) | Jul 05, 2024 |
| ASUSTek       | K50AD                       | [0fd561ca3c](https://linux-hardware.org/?probe=0fd561ca3c) | Jul 05, 2024 |
| Unknown       | N10(M1N1)                   | [fc2ca6d762](https://linux-hardware.org/?probe=fc2ca6d762) | Jul 04, 2024 |
| HP            | 14                          | [f28a807a2e](https://linux-hardware.org/?probe=f28a807a2e) | Jul 01, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [3f56bdc232](https://linux-hardware.org/?probe=3f56bdc232) | Jul 01, 2024 |
| Dell          | Latitude E6410              | [6f8ffa83ce](https://linux-hardware.org/?probe=6f8ffa83ce) | Jul 01, 2024 |
| HP            | Pavilion 10 TS              | [c2bd71447d](https://linux-hardware.org/?probe=c2bd71447d) | Jun 30, 2024 |
| Dell          | Inspiron 15-3567            | [3eed7f4afe](https://linux-hardware.org/?probe=3eed7f4afe) | Jun 30, 2024 |
| ASUSTek       | K52JB                       | [cda7f38058](https://linux-hardware.org/?probe=cda7f38058) | Jun 29, 2024 |
| HP            | Laptop 15-bw0xx             | [3a1445300b](https://linux-hardware.org/?probe=3a1445300b) | Jun 28, 2024 |
| Dell          | Latitude 3190               | [41e83ac5c5](https://linux-hardware.org/?probe=41e83ac5c5) | Jun 27, 2024 |
| HP            | Pavilion dv6                | [e6342ad374](https://linux-hardware.org/?probe=e6342ad374) | Jun 27, 2024 |
| RWC           | DA-T118-SR                  | [05f141e671](https://linux-hardware.org/?probe=05f141e671) | Jun 26, 2024 |
| Teclast       | tPAD                        | [7fcbabfefd](https://linux-hardware.org/?probe=7fcbabfefd) | Jun 25, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1da0ed40d4](https://linux-hardware.org/?probe=1da0ed40d4) | Jun 24, 2024 |
| Insyde        | Braswell                    | [fb1a3d94f3](https://linux-hardware.org/?probe=fb1a3d94f3) | Jun 19, 2024 |
| Apple         | MacBookPro8,1               | [2639f09193](https://linux-hardware.org/?probe=2639f09193) | Jun 19, 2024 |
| Samsung       | QX311/QX411/QX412/QX511     | [e37830ceb9](https://linux-hardware.org/?probe=e37830ceb9) | Jun 10, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [f495fbd229](https://linux-hardware.org/?probe=f495fbd229) | Jun 04, 2024 |
| HP            | ZBook 15 G2                 | [a788fb84c1](https://linux-hardware.org/?probe=a788fb84c1) | Jun 02, 2024 |
| HP            | ZBook 15 G2                 | [60515e0fa6](https://linux-hardware.org/?probe=60515e0fa6) | Jun 02, 2024 |
| HP            | Laptop 15-bs0xx             | [3e4d7f9fbc](https://linux-hardware.org/?probe=3e4d7f9fbc) | Jun 01, 2024 |
| ASUSTek       | X550WAK                     | [1a64c5c27f](https://linux-hardware.org/?probe=1a64c5c27f) | May 31, 2024 |
| HP            | Laptop 15-bw0xx             | [3bae231b99](https://linux-hardware.org/?probe=3bae231b99) | May 31, 2024 |
| HP            | Laptop 15-bw0xx             | [0c0fc0bbe4](https://linux-hardware.org/?probe=0c0fc0bbe4) | May 31, 2024 |
| Lenovo        | ThinkPad X200 2024B67       | [6d2d7fbbb5](https://linux-hardware.org/?probe=6d2d7fbbb5) | May 28, 2024 |
| ODM           | Unknown                     | [d6a98e94b6](https://linux-hardware.org/?probe=d6a98e94b6) | May 27, 2024 |
| ASUSTek       | GL552VX                     | [9f2697991a](https://linux-hardware.org/?probe=9f2697991a) | May 26, 2024 |
| HP            | Pavilion Notebook           | [133e970ae7](https://linux-hardware.org/?probe=133e970ae7) | May 23, 2024 |
| Lenovo        | ThinkPad T560 20FJS0XX00    | [11d6470b8b](https://linux-hardware.org/?probe=11d6470b8b) | May 23, 2024 |
| Apple         | MacBookAir1,1               | [8c29382ba8](https://linux-hardware.org/?probe=8c29382ba8) | May 21, 2024 |
| ODM           | Unknown                     | [9fcefdfbe9](https://linux-hardware.org/?probe=9fcefdfbe9) | May 19, 2024 |
| Lenovo        | ThinkPad L490 20Q5002GGE    | [c92390a81b](https://linux-hardware.org/?probe=c92390a81b) | May 15, 2024 |
| Dell          | Inspiron 13-5378            | [fcb1c00cb1](https://linux-hardware.org/?probe=fcb1c00cb1) | May 15, 2024 |
| Sony          | VPCW216AG                   | [0e3674f67f](https://linux-hardware.org/?probe=0e3674f67f) | May 14, 2024 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [abf8f16050](https://linux-hardware.org/?probe=abf8f16050) | May 13, 2024 |
| Dell          | Vostro 3400                 | [345ddaf7ed](https://linux-hardware.org/?probe=345ddaf7ed) | May 13, 2024 |
| Lenovo        | G575 20081                  | [581885ea87](https://linux-hardware.org/?probe=581885ea87) | May 11, 2024 |
| Shenzhen B... | XN116B                      | [47dbcecbd7](https://linux-hardware.org/?probe=47dbcecbd7) | May 04, 2024 |
| Dell          | Vostro 3400                 | [93da978d38](https://linux-hardware.org/?probe=93da978d38) | May 04, 2024 |
| HP            | EliteBook 840 G4            | [f9fed717ee](https://linux-hardware.org/?probe=f9fed717ee) | May 03, 2024 |
| ASUSTek       | X540YA                      | [e163aa8e32](https://linux-hardware.org/?probe=e163aa8e32) | May 03, 2024 |
| HP            | Pavilion dm1                | [ba07809953](https://linux-hardware.org/?probe=ba07809953) | May 02, 2024 |
| Notebook      | W54_W94_W955TU,-T,-C        | [c327d5c1a6](https://linux-hardware.org/?probe=c327d5c1a6) | May 01, 2024 |
| Apple         | MacBookPro5,5               | [2ddfed1c8a](https://linux-hardware.org/?probe=2ddfed1c8a) | May 01, 2024 |
| Lenovo        | G50-45 80E3                 | [a12bc9b719](https://linux-hardware.org/?probe=a12bc9b719) | Apr 28, 2024 |
| ASUSTek       | K45A                        | [7bed7e12ab](https://linux-hardware.org/?probe=7bed7e12ab) | Apr 27, 2024 |
| ASUSTek       | K53BY                       | [6f6c4b9d68](https://linux-hardware.org/?probe=6f6c4b9d68) | Apr 26, 2024 |
| HP            | Compaq 8710w (GT649PA#AB... | [00f1c96012](https://linux-hardware.org/?probe=00f1c96012) | Apr 26, 2024 |
| Dell          | Inspiron 15-3567            | [e93fe83f01](https://linux-hardware.org/?probe=e93fe83f01) | Apr 24, 2024 |
| Acer          | Aspire E5-573G              | [216cd2fc72](https://linux-hardware.org/?probe=216cd2fc72) | Apr 24, 2024 |
| ASUSTek       | X555QG                      | [c905efd379](https://linux-hardware.org/?probe=c905efd379) | Apr 23, 2024 |
| ASUSTek       | X555QG                      | [26b8da2305](https://linux-hardware.org/?probe=26b8da2305) | Apr 23, 2024 |
| ASUSTek       | K42F                        | [f29299723c](https://linux-hardware.org/?probe=f29299723c) | Apr 23, 2024 |
| Lenovo        | B575e 36852BG               | [c2c9ec964e](https://linux-hardware.org/?probe=c2c9ec964e) | Apr 23, 2024 |
| ASUSTek       | K42F                        | [63b454fa02](https://linux-hardware.org/?probe=63b454fa02) | Apr 23, 2024 |
| Lenovo        | B575e 36852BG               | [d168fb33c4](https://linux-hardware.org/?probe=d168fb33c4) | Apr 23, 2024 |
| Toshiba       | Satellite C850D-11C         | [beccadec71](https://linux-hardware.org/?probe=beccadec71) | Apr 22, 2024 |
| Fujitsu       | FMVA40B1RJ                  | [b0d3f0b365](https://linux-hardware.org/?probe=b0d3f0b365) | Apr 20, 2024 |
| Dell          | Inspiron 15-3567            | [bf1e4f8d6a](https://linux-hardware.org/?probe=bf1e4f8d6a) | Apr 20, 2024 |
| HP            | EliteBook 6930p             | [263d72f3c6](https://linux-hardware.org/?probe=263d72f3c6) | Apr 17, 2024 |
| Unknown       | Unknown                     | [10d92e98c0](https://linux-hardware.org/?probe=10d92e98c0) | Apr 16, 2024 |
| HP            | 250 G4 Notebook PC          | [2fcb542c43](https://linux-hardware.org/?probe=2fcb542c43) | Apr 14, 2024 |
| Unknown       | M-140BI3                    | [491b1013ab](https://linux-hardware.org/?probe=491b1013ab) | Apr 11, 2024 |
| HP            | Pavilion g7                 | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| Acer          | Aspire ES1-512              | [47ad6cd23e](https://linux-hardware.org/?probe=47ad6cd23e) | Apr 05, 2024 |
| Acer          | Aspire ES1-512              | [9b5914816a](https://linux-hardware.org/?probe=9b5914816a) | Apr 05, 2024 |
| Dell          | Latitude E6410              | [7c4144e1df](https://linux-hardware.org/?probe=7c4144e1df) | Apr 05, 2024 |
| Acer          | Extensa 5630                | [224d74c060](https://linux-hardware.org/?probe=224d74c060) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| Acer          | Aspire 3000                 | [1d2fad06c8](https://linux-hardware.org/?probe=1d2fad06c8) | Apr 02, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E20... | [83edc14408](https://linux-hardware.org/?probe=83edc14408) | Mar 30, 2024 |
| HP            | 250 G4 Notebook PC          | [82ae07c449](https://linux-hardware.org/?probe=82ae07c449) | Mar 29, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | [6c9bf73f0c](https://linux-hardware.org/?probe=6c9bf73f0c) | Mar 28, 2024 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [8d88a75722](https://linux-hardware.org/?probe=8d88a75722) | Mar 27, 2024 |
| HP            | Laptop 15-db0xxx            | [04ef2627e2](https://linux-hardware.org/?probe=04ef2627e2) | Mar 27, 2024 |
| HP            | Laptop 15s-eq2xxx           | [b4e434bb17](https://linux-hardware.org/?probe=b4e434bb17) | Mar 27, 2024 |
| Acer          | Extensa 2540                | [3e49d36612](https://linux-hardware.org/?probe=3e49d36612) | Mar 26, 2024 |
| HP            | 15 Notebook PC              | [46b79e7d26](https://linux-hardware.org/?probe=46b79e7d26) | Mar 26, 2024 |
| HP            | Laptop 14-em0xxx            | [3f937a527b](https://linux-hardware.org/?probe=3f937a527b) | Mar 23, 2024 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [8dfcfff063](https://linux-hardware.org/?probe=8dfcfff063) | Mar 23, 2024 |
| Samsung       | N100                        | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Sony          | VGN-TZ21MN_N                | [1e1a62727b](https://linux-hardware.org/?probe=1e1a62727b) | Mar 19, 2024 |
| Unknown       | Unknown                     | [27317f4bcf](https://linux-hardware.org/?probe=27317f4bcf) | Mar 18, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5603a5896d](https://linux-hardware.org/?probe=5603a5896d) | Mar 17, 2024 |
| ODM           | Unknown                     | [5a87f7eaeb](https://linux-hardware.org/?probe=5a87f7eaeb) | Mar 17, 2024 |
| Sony          | VPCW216AG                   | [c607fc8a6b](https://linux-hardware.org/?probe=c607fc8a6b) | Mar 16, 2024 |
| HP            | Split 13 x2 PC              | [447e4a6951](https://linux-hardware.org/?probe=447e4a6951) | Mar 14, 2024 |
| Lenovo        | ThinkPad L520 5015AH2       | [c63473fd10](https://linux-hardware.org/?probe=c63473fd10) | Mar 12, 2024 |
| HP            | Notebook                    | [51a929c53a](https://linux-hardware.org/?probe=51a929c53a) | Mar 08, 2024 |
| Sony          | SVF1521NSTB                 | [b9f4d235c9](https://linux-hardware.org/?probe=b9f4d235c9) | Mar 06, 2024 |
| HP            | Notebook                    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| Fujitsu       | FMVC05005                   | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| Sony          | VPCEB3C4R                   | [f63a65b29f](https://linux-hardware.org/?probe=f63a65b29f) | Mar 04, 2024 |
| MSI           | MS-168A                     | [1625072479](https://linux-hardware.org/?probe=1625072479) | Mar 02, 2024 |
| MSI           | MS-168A                     | [cae162bcad](https://linux-hardware.org/?probe=cae162bcad) | Mar 02, 2024 |
| HP            | 250 G1                      | [805489bf43](https://linux-hardware.org/?probe=805489bf43) | Feb 26, 2024 |
| Google        | Lindar                      | [0f6ee4fa1f](https://linux-hardware.org/?probe=0f6ee4fa1f) | Feb 25, 2024 |
| Dell          | Latitude D620               | [2ca5ca0cad](https://linux-hardware.org/?probe=2ca5ca0cad) | Feb 24, 2024 |
| Dell          | Latitude D620               | [78a800debc](https://linux-hardware.org/?probe=78a800debc) | Feb 22, 2024 |
| FOUNDER Co... | M672+968                    | [0dd60ea26f](https://linux-hardware.org/?probe=0dd60ea26f) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [7c9a199867](https://linux-hardware.org/?probe=7c9a199867) | Feb 21, 2024 |
| Sony          | VPCEB3C4R                   | [93a9016bf3](https://linux-hardware.org/?probe=93a9016bf3) | Feb 20, 2024 |
| HP            | Presario M2000 (EE629LA#... | [302398d57c](https://linux-hardware.org/?probe=302398d57c) | Feb 18, 2024 |
| HP            | Presario M2000 (EE629LA#... | [c44f12d85d](https://linux-hardware.org/?probe=c44f12d85d) | Feb 18, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d18785d54f](https://linux-hardware.org/?probe=d18785d54f) | Feb 16, 2024 |
| Samsung       | 530XBB                      | [f98c88531f](https://linux-hardware.org/?probe=f98c88531f) | Feb 15, 2024 |
| Digibras      | NH4CU53                     | [1e3d9f1795](https://linux-hardware.org/?probe=1e3d9f1795) | Feb 10, 2024 |
| Dell          | Latitude 3340               | [f1233f10b5](https://linux-hardware.org/?probe=f1233f10b5) | Feb 10, 2024 |
| Google        | Lindar                      | [e3a071ae43](https://linux-hardware.org/?probe=e3a071ae43) | Feb 10, 2024 |
| Dell          | Latitude E5430 vPro         | [9e120d90b8](https://linux-hardware.org/?probe=9e120d90b8) | Feb 09, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [52d94c62ce](https://linux-hardware.org/?probe=52d94c62ce) | Feb 08, 2024 |
| Fujitsu       | LIFEBOOK U7313              | [f1f1ab12ba](https://linux-hardware.org/?probe=f1f1ab12ba) | Feb 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5fa467241b](https://linux-hardware.org/?probe=5fa467241b) | Feb 05, 2024 |
| Itautec       | Infoway w7430               | [4928095170](https://linux-hardware.org/?probe=4928095170) | Feb 05, 2024 |
| Acer          | Aspire 5951G                | [e583f21b3a](https://linux-hardware.org/?probe=e583f21b3a) | Feb 05, 2024 |
| Packard Be... | EasyNote ENTG71BM           | [eb979afe2e](https://linux-hardware.org/?probe=eb979afe2e) | Feb 04, 2024 |
| HP            | Pavilion dv6                | [52c0814c31](https://linux-hardware.org/?probe=52c0814c31) | Feb 03, 2024 |
| HP            | Pavilion dv6                | [d477732dfa](https://linux-hardware.org/?probe=d477732dfa) | Feb 03, 2024 |
| ODM           | Unknown                     | [0ad5efc9ef](https://linux-hardware.org/?probe=0ad5efc9ef) | Feb 03, 2024 |
| Lenovo        | G405 20239                  | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Acer          | Swift SF314-43              | [793c3d3b4c](https://linux-hardware.org/?probe=793c3d3b4c) | Jan 31, 2024 |
| Lenovo        | G575 20081                  | [162e1f81cf](https://linux-hardware.org/?probe=162e1f81cf) | Jan 31, 2024 |
| Lenovo        | V310-15ISK 80SY             | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Dell          | Inspiron N5010              | [dcd752673f](https://linux-hardware.org/?probe=dcd752673f) | Jan 29, 2024 |
| Acer          | Aspire ES1-520              | [633516e35a](https://linux-hardware.org/?probe=633516e35a) | Jan 25, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ODM           | Unknown                     | [2d8310fe96](https://linux-hardware.org/?probe=2d8310fe96) | Jan 24, 2024 |
| Lenovo        | ThinkPad SL 2746F2G         | [47b2e38ff4](https://linux-hardware.org/?probe=47b2e38ff4) | Jan 16, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [45399ef111](https://linux-hardware.org/?probe=45399ef111) | Jan 15, 2024 |
| Dell          | Inspiron N5010              | [d6239c4393](https://linux-hardware.org/?probe=d6239c4393) | Jan 15, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [681ea2eb1a](https://linux-hardware.org/?probe=681ea2eb1a) | Jan 10, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2894cc00dc](https://linux-hardware.org/?probe=2894cc00dc) | Jan 10, 2024 |
| iRU           | 15TLI                       | [4d83aee906](https://linux-hardware.org/?probe=4d83aee906) | Jan 10, 2024 |
| iRU           | 15TLI                       | [d318923a72](https://linux-hardware.org/?probe=d318923a72) | Jan 09, 2024 |
| ASUSTek       | K53U                        | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| Lenovo        | ThinkPad T430 23477C7       | [db1c43a6a6](https://linux-hardware.org/?probe=db1c43a6a6) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| Digibras      | NH4CU03                     | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| Google        | Electro                     | [74ed1caffe](https://linux-hardware.org/?probe=74ed1caffe) | Jan 04, 2024 |
| Packard Be... | EasyNote LM85               | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| Acer          | Aspire ES1-520              | [922ef3d7e1](https://linux-hardware.org/?probe=922ef3d7e1) | Jan 03, 2024 |
| HP            | Notebook                    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Apple         | MacBookAir4,2               | [7ebd4a00e7](https://linux-hardware.org/?probe=7ebd4a00e7) | Dec 31, 2023 |
| Apple         | MacBook6,1                  | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| HP            | ProBook 470 G3              | [22bd0ee412](https://linux-hardware.org/?probe=22bd0ee412) | Dec 30, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| Qilive        | QW20141BSP                  | [3f2d1e03c3](https://linux-hardware.org/?probe=3f2d1e03c3) | Dec 28, 2023 |
| Google        | Swanky                      | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Acer          | Extensa 215-55              | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Google        | Madoo                       | [14e757fdb4](https://linux-hardware.org/?probe=14e757fdb4) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| ATARI         | VCS 800 Black Walnut        | [34456982d3](https://linux-hardware.org/?probe=34456982d3) | Dec 23, 2023 |
| Google        | Treeya                      | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| Toshiba       | Satellite L300              | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| Google        | Candy                       | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| HP            | ZBook 17                    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Dell          | Inspiron 3421               | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| Dell          | Inspiron MM061              | [213b775f8b](https://linux-hardware.org/?probe=213b775f8b) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | [d4c43fe4f4](https://linux-hardware.org/?probe=d4c43fe4f4) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Toshiba       | Satellite L300              | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Chuwi         | X312B                       | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1e58f5a4f9](https://linux-hardware.org/?probe=1e58f5a4f9) | Nov 21, 2023 |
| MSI           | Raider GE76 12UE            | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| HUAWEI        | MRGFG-XX                    | [b7dda3ece0](https://linux-hardware.org/?probe=b7dda3ece0) | Nov 14, 2023 |
| Acer          | Extensa 5620                | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| HP            | 255 G1                      | [988c1c2454](https://linux-hardware.org/?probe=988c1c2454) | Nov 12, 2023 |
| HP            | 255 G1                      | [9aa30be183](https://linux-hardware.org/?probe=9aa30be183) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| ASUSTek       | G75VW                       | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| ASUSTek       | K50IJ                       | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| HP            | EliteBook 820 G3            | [c86a40c419](https://linux-hardware.org/?probe=c86a40c419) | Oct 28, 2023 |
| Acer          | Aspire 9300                 | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| HP            | Compaq Presario CQ40        | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| Positivo      | AT300b                      | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [9d142e587e](https://linux-hardware.org/?probe=9d142e587e) | Oct 17, 2023 |
| Acer          | Aspire A314-23P             | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| BLANK         | Intel powered classmate ... | [78cc4b7937](https://linux-hardware.org/?probe=78cc4b7937) | Oct 11, 2023 |
| BLANK         | Intel powered classmate ... | [bc4093e3c7](https://linux-hardware.org/?probe=bc4093e3c7) | Oct 11, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| Insyde        | Braswell                    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| Apple         | MacBookPro8,1               | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| Getac         | X500G3                      | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| ASUSTek       | X451MA                      | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Dell          | Precision 3570              | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| Google        | Blooglet                    | [79ce749655](https://linux-hardware.org/?probe=79ce749655) | Sep 17, 2023 |
| HP            | 15                          | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| HP            | 2000                        | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| HP            | 255 G2                      | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Dell          | Inspiron 1545               | [8ba55e98ec](https://linux-hardware.org/?probe=8ba55e98ec) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | K52JB                       | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| Packard Be... | EasyNote TJ65               | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [7abf0d31d8](https://linux-hardware.org/?probe=7abf0d31d8) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Compal        | PBL20                       | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Acer          | Aspire 5050                 | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Toshiba       | Satellite L875D             | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron MM061              | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Pavilion 15                 | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Dell          | Inspiron 5576               | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| Dell          | Latitude 5290               | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Fujitsu       | FMVNC4BC4                   | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| LG Electro... | 15Z90N-U.ARS5U1             | [54b03a096b](https://linux-hardware.org/?probe=54b03a096b) | Jul 19, 2023 |
| Acer          | Aspire E5-523G              | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| Acer          | Swift SFE16-42              | [c8b8a7d737](https://linux-hardware.org/?probe=c8b8a7d737) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Google        | Pyro                        | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| eMachines     | eME443                      | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | InsydeH2O EFI BIOS          | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | [e4c0eeb007](https://linux-hardware.org/?probe=e4c0eeb007) | Jun 17, 2023 |
| Dell          | Precision 3570              | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Dell          | Latitude E6430              | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| ASUSTek       | X450CC                      | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| HP            | ProBook 650 G3              | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Lenovo        | ThinkPad T400 276522G       | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| HP            | Notebook                    | [70ee3adf89](https://linux-hardware.org/?probe=70ee3adf89) | May 08, 2023 |
| Samsung       | 530XBB                      | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | XPS 13 9305                 | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| HP            | x2 210                      | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Sony          | SVF1521C6EW                 | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Google        | Chell                       | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| ASUSTek       | K52JB                       | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| HP            | InsydeH2O EFI BIOS          | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| GPU Compan... | GWTN116-3                   | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| HP            | Pavilion dv6                | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Intel         | W7650                       | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| Acer          | Aspire E1-570               | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Pavilion 15                 | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Laptop 15-da0xxx            | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Apple         | MacBookPro9,2               | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| Packard Be... | EasyNote SB65               | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Samsung       | 530XBB                      | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude 7480               | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| HP            | Laptop 15-da0xxx            | [f4e7268671](https://linux-hardware.org/?probe=f4e7268671) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | GS65 Stealth 9SD            | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| HP            | Laptop 14-dk0xxx            | [b492e1c092](https://linux-hardware.org/?probe=b492e1c092) | Mar 04, 2023 |
| DEXP          | Aquilon C15                 | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Google        | Celes                       | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Dell          | Inspiron 1525               | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Unknown       | Unknown                     | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Medion        | Akoya E6412T                | [41a31b6bd1](https://linux-hardware.org/?probe=41a31b6bd1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Toshiba       | Satellite L650              | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Insyde        | CherryTrail                 | [db3d49fa06](https://linux-hardware.org/?probe=db3d49fa06) | Feb 08, 2023 |
| Toshiba       | Satellite C55D-A            | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| Acer          | TravelMate P253             | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Intel         | Unknown                     | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | 1011PX                      | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| HP            | Laptop 15-da0xxx            | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Acer          | Aspire One 721              | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| Google        | Candy                       | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| ASUSTek       | T100TA                      | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Google        | Edgar                       | [738a0d9324](https://linux-hardware.org/?probe=738a0d9324) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Digma         | CITI E401 ET4007EW          | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| HP            | InsydeH2O EFI BIOS          | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | InsydeH2O EFI BIOS          | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| HP            | Stream Notebook PC 11       | [f33ebabb99](https://linux-hardware.org/?probe=f33ebabb99) | Dec 24, 2022 |
| Positivo      | C14CR21                     | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| Google        | Coral                       | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Compaq 6830s                | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| ASUSTek       | K50C                        | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Apple         | MacBookPro8,1               | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| HP            | Laptop 15-da0xxx            | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| ASUSTek       | K55A                        | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | [4825e06bd4](https://linux-hardware.org/?probe=4825e06bd4) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | [57bcd4363a](https://linux-hardware.org/?probe=57bcd4363a) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Acer          | AOD255E                     | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [4b4c00b0a9](https://linux-hardware.org/?probe=4b4c00b0a9) | Oct 28, 2022 |
| Acer          | Extensa 2509                | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Acer          | Aspire one                  | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| HP            | 431 Notebook                | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | Aspire 4739Z                | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Toshiba       | Satellite C655D             | [80ec8503c0](https://linux-hardware.org/?probe=80ec8503c0) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| ASUSTek       | X451CA                      | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Star Labs     | Lite                        | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Acer          | AOA150                      | [3146707963](https://linux-hardware.org/?probe=3146707963) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | ProBook 450 G6              | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Standard      | AHV                         | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Google        | Celes                       | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Toshiba       | NB250                       | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | Presario CQ56               | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASUSTek       | 900                         | [ae42d40b7a](https://linux-hardware.org/?probe=ae42d40b7a) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| Dell          | Inspiron N5010              | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Samsung       | N130                        | [4874e0173d](https://linux-hardware.org/?probe=4874e0173d) | Jul 17, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Standard      | AHV                         | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Nokia         | Booklet 3G                  | [08b1b304ae](https://linux-hardware.org/?probe=08b1b304ae) | Jul 11, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Toshiba       | Satellite A300              | [dd80f74e85](https://linux-hardware.org/?probe=dd80f74e85) | Jul 05, 2022 |
| Toshiba       | Satellite A300              | [69e4341e99](https://linux-hardware.org/?probe=69e4341e99) | Jul 05, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| HP            | Notebook                    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lubuntu 22.04   | 340       | 25.91%  |
| Lubuntu 20.04   | 292       | 22.26%  |
| Lubuntu 24.04   | 182       | 13.87%  |
| Lubuntu 18.04   | 140       | 10.67%  |
| Lubuntu 21.10   | 48        | 3.66%   |
| Lubuntu 19.10   | 43        | 3.28%   |
| Lubuntu 21.04   | 38        | 2.9%    |
| Lubuntu 25.04   | 37        | 2.82%   |
| Lubuntu 23.10   | 33        | 2.52%   |
| Lubuntu 22.10   | 30        | 2.29%   |
| Lubuntu 20.10   | 30        | 2.29%   |
| Lubuntu 24.10   | 24        | 1.83%   |
| Lubuntu 23.04   | 20        | 1.52%   |
| Lubuntu 16.04   | 19        | 1.45%   |
| Lubuntu 19.04   | 12        | 0.91%   |
| Lubuntu 25.10   | 8         | 0.61%   |
| Lubuntu 18.10   | 8         | 0.61%   |
| Lubuntu         | 3         | 0.23%   |
| Lubuntu 12.04   | 2         | 0.15%   |
| Lubuntu 20.04.1 | 1         | 0.08%   |
| Lubuntu 17.10   | 1         | 0.08%   |
| Lubuntu 13.04   | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lubuntu | 1258      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 25        | 1.74%   |
| 5.15.0-43-generic | 23        | 1.6%    |
| 6.14.0-15-generic | 21        | 1.46%   |
| 6.8.0-41-generic  | 17        | 1.18%   |
| 6.8.0-31-generic  | 17        | 1.18%   |
| 5.15.0-56-generic | 16        | 1.11%   |
| 6.8.0-51-generic  | 15        | 1.05%   |
| 5.4.0-52-generic  | 15        | 1.05%   |
| 5.15.0-25-generic | 12        | 0.84%   |
| 6.14.0-27-generic | 11        | 0.77%   |
| 6.11.0-17-generic | 11        | 0.77%   |
| 5.3.0-46-generic  | 11        | 0.77%   |
| 5.15.0-46-generic | 11        | 0.77%   |
| 5.13.0-28-generic | 11        | 0.77%   |
| 5.13.0-19-generic | 11        | 0.77%   |
| 6.8.0-40-generic  | 10        | 0.7%    |
| 6.5.0-28-generic  | 10        | 0.7%    |
| 6.2.0-39-generic  | 10        | 0.7%    |
| 6.2.0-26-generic  | 10        | 0.7%    |
| 5.19.0-41-generic | 10        | 0.7%    |
| 5.13.0-40-generic | 10        | 0.7%    |
| 5.13.0-30-generic | 10        | 0.7%    |
| 5.11.0-16-generic | 10        | 0.7%    |
| 6.8.0-45-generic  | 9         | 0.63%   |
| 6.5.0-18-generic  | 9         | 0.63%   |
| 6.5.0-15-generic  | 9         | 0.63%   |
| 6.2.0-34-generic  | 9         | 0.63%   |
| 6.11.0-8-generic  | 9         | 0.63%   |
| 5.4.0-48-generic  | 9         | 0.63%   |
| 5.4.0-47-generic  | 9         | 0.63%   |
| 5.4.0-26-generic  | 9         | 0.63%   |
| 5.15.0-58-generic | 9         | 0.63%   |
| 5.15.0-41-generic | 9         | 0.63%   |
| 5.13.0-35-generic | 9         | 0.63%   |
| 6.8.0-47-generic  | 8         | 0.56%   |
| 6.8.0-36-generic  | 8         | 0.56%   |
| 6.5.0-9-generic   | 8         | 0.56%   |
| 6.5.0-41-generic  | 8         | 0.56%   |
| 6.5.0-25-generic  | 8         | 0.56%   |
| 6.14.0-29-generic | 8         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 219       | 16.43%  |
| 5.15.0   | 197       | 14.78%  |
| 6.8.0    | 136       | 10.2%   |
| 6.5.0    | 97        | 7.28%   |
| 4.15.0   | 86        | 6.45%   |
| 5.19.0   | 75        | 5.63%   |
| 5.13.0   | 74        | 5.55%   |
| 6.2.0    | 69        | 5.18%   |
| 5.11.0   | 69        | 5.18%   |
| 6.14.0   | 68        | 5.1%    |
| 5.3.0    | 63        | 4.73%   |
| 5.8.0    | 57        | 4.28%   |
| 6.11.0   | 53        | 3.98%   |
| 5.0.0    | 16        | 1.2%    |
| 4.18.0   | 9         | 0.68%   |
| 6.17.0   | 8         | 0.6%    |
| 4.4.0    | 8         | 0.6%    |
| 4.13.0   | 2         | 0.15%   |
| 6.9.5    | 1         | 0.08%   |
| 6.7.8    | 1         | 0.08%   |
| 6.5.1    | 1         | 0.08%   |
| 6.4.12   | 1         | 0.08%   |
| 6.14.8   | 1         | 0.08%   |
| 6.13.6   | 1         | 0.08%   |
| 6.12.15  | 1         | 0.08%   |
| 6.10.6   | 1         | 0.08%   |
| 6.1.6    | 1         | 0.08%   |
| 6.1.12   | 1         | 0.08%   |
| 6.0.12   | 1         | 0.08%   |
| 6.0.0    | 1         | 0.08%   |
| 5.9.0    | 1         | 0.08%   |
| 5.7.9    | 1         | 0.08%   |
| 5.6.0    | 1         | 0.08%   |
| 5.5.2    | 1         | 0.08%   |
| 5.19.8   | 1         | 0.08%   |
| 5.18.0   | 1         | 0.08%   |
| 5.16.0   | 1         | 0.08%   |
| 5.14.0   | 1         | 0.08%   |
| 5.10.0   | 1         | 0.08%   |
| 4.14.225 | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 219       | 16.43%  |
| 5.15    | 197       | 14.78%  |
| 6.8     | 136       | 10.2%   |
| 6.5     | 98        | 7.35%   |
| 4.15    | 86        | 6.45%   |
| 5.19    | 76        | 5.7%    |
| 5.13    | 74        | 5.55%   |
| 6.2     | 69        | 5.18%   |
| 6.14    | 69        | 5.18%   |
| 5.11    | 69        | 5.18%   |
| 5.3     | 63        | 4.73%   |
| 5.8     | 57        | 4.28%   |
| 6.11    | 53        | 3.98%   |
| 5.0     | 16        | 1.2%    |
| 4.18    | 9         | 0.68%   |
| 6.17    | 8         | 0.6%    |
| 4.4     | 8         | 0.6%    |
| 4.13    | 3         | 0.23%   |
| 6.1     | 2         | 0.15%   |
| 6.0     | 2         | 0.15%   |
| 6.9     | 1         | 0.08%   |
| 6.7     | 1         | 0.08%   |
| 6.4     | 1         | 0.08%   |
| 6.13    | 1         | 0.08%   |
| 6.12    | 1         | 0.08%   |
| 6.10    | 1         | 0.08%   |
| 5.9     | 1         | 0.08%   |
| 5.7     | 1         | 0.08%   |
| 5.6     | 1         | 0.08%   |
| 5.5     | 1         | 0.08%   |
| 5.18    | 1         | 0.08%   |
| 5.16    | 1         | 0.08%   |
| 5.14    | 1         | 0.08%   |
| 5.10    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |
| 3.2     | 1         | 0.08%   |
| 3.13    | 1         | 0.08%   |
| 3.1     | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1162      | 92.37%  |
| i686   | 95        | 7.55%   |
| armv7l | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| LXQt            | 1058      | 83.84%  |
| LXDE            | 156       | 12.36%  |
| Unknown         | 16        | 1.27%   |
| GNOME           | 6         | 0.48%   |
| Openbox         | 5         | 0.4%    |
| X-Cinnamon      | 3         | 0.24%   |
| Lubuntu         | 3         | 0.24%   |
| KDE5            | 3         | 0.24%   |
| Cinnamon        | 3         | 0.24%   |
| XFCE            | 2         | 0.16%   |
| i3              | 2         | 0.16%   |
| MATE            | 1         | 0.08%   |
| KDE6            | 1         | 0.08%   |
| KDE             | 1         | 0.08%   |
| GNOME Flashback | 1         | 0.08%   |
| Budgie          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1229      | 97.39%  |
| Tty     | 27        | 2.14%   |
| Wayland | 6         | 0.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 796       | 62.38%  |
| Unknown | 303       | 23.75%  |
| LightDM | 101       | 7.92%   |
| TDM     | 43        | 3.37%   |
| GDM     | 22        | 1.72%   |
| GDM3    | 9         | 0.71%   |
| XDM     | 1         | 0.08%   |
| SLiM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 373       | 29.49%  |
| fr_FR   | 121       | 9.57%   |
| pt_BR   | 82        | 6.48%   |
| it_IT   | 75        | 5.93%   |
| en_GB   | 74        | 5.85%   |
| C       | 70        | 5.53%   |
| de_DE   | 65        | 5.14%   |
| ru_RU   | 44        | 3.48%   |
| pl_PL   | 37        | 2.92%   |
| es_ES   | 30        | 2.37%   |
| en_CA   | 24        | 1.9%    |
| es_MX   | 21        | 1.66%   |
| Unknown | 18        | 1.42%   |
| es_AR   | 17        | 1.34%   |
| en_AU   | 16        | 1.26%   |
| tr_TR   | 14        | 1.11%   |
| en_IN   | 11        | 0.87%   |
| cs_CZ   | 10        | 0.79%   |
| hu_HU   | 9         | 0.71%   |
| en_AG   | 9         | 0.71%   |
| nl_NL   | 8         | 0.63%   |
| es_CL   | 8         | 0.63%   |
| ja_JP   | 7         | 0.55%   |
| es_CR   | 7         | 0.55%   |
| fi_FI   | 6         | 0.47%   |
| es_CO   | 6         | 0.47%   |
| nl_BE   | 5         | 0.4%    |
| fr_CH   | 5         | 0.4%    |
| en_ZA   | 5         | 0.4%    |
| en_PH   | 5         | 0.4%    |
| en_IE   | 5         | 0.4%    |
| zh_CN   | 4         | 0.32%   |
| fr_CA   | 4         | 0.32%   |
| fr_BE   | 4         | 0.32%   |
| en_SG   | 4         | 0.32%   |
| zh_TW   | 3         | 0.24%   |
| sk_SK   | 3         | 0.24%   |
| pt_PT   | 3         | 0.24%   |
| es_VE   | 3         | 0.24%   |
| es_UY   | 3         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 795       | 62.35%  |
| EFI  | 480       | 37.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type      | Notebooks | Percent |
|-----------|-----------|---------|
| Ext4      | 989       | 77.39%  |
| Tmpfs     | 193       | 15.1%   |
| Overlay   | 61        | 4.77%   |
| Btrfs     | 16        | 1.25%   |
| Xfs       | 5         | 0.39%   |
| Aufs      | 5         | 0.39%   |
| Ext2      | 3         | 0.23%   |
| Unknown   | 3         | 0.23%   |
| Ext3      | 2         | 0.16%   |
| Overlayfs | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 550       | 43.17%  |
| Unknown | 380       | 29.83%  |
| MBR     | 344       | 27%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1158      | 91.04%  |
| Yes       | 114       | 8.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 956       | 75.39%  |
| Yes       | 312       | 24.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 263       | 20.91%  |
| Lenovo              | 188       | 14.94%  |
| Dell                | 134       | 10.65%  |
| ASUSTek Computer    | 124       | 9.86%   |
| Acer                | 118       | 9.38%   |
| Toshiba             | 55        | 4.37%   |
| Samsung Electronics | 37        | 2.94%   |
| Google              | 35        | 2.78%   |
| Apple               | 32        | 2.54%   |
| Sony                | 31        | 2.46%   |
| Fujitsu             | 18        | 1.43%   |
| Positivo            | 16        | 1.27%   |
| Unknown             | 16        | 1.27%   |
| Packard Bell        | 14        | 1.11%   |
| MSI                 | 14        | 1.11%   |
| Fujitsu Siemens     | 13        | 1.03%   |
| Mediacom            | 10        | 0.79%   |
| Notebook            | 7         | 0.56%   |
| Medion              | 6         | 0.48%   |
| eMachines           | 6         | 0.48%   |
| Chuwi               | 6         | 0.48%   |
| HUAWEI              | 5         | 0.4%    |
| LG Electronics      | 4         | 0.32%   |
| Intel               | 4         | 0.32%   |
| IBM                 | 4         | 0.32%   |
| Alienware           | 4         | 0.32%   |
| Thomson             | 3         | 0.24%   |
| Panasonic           | 3         | 0.24%   |
| Itautec             | 3         | 0.24%   |
| Insyde              | 3         | 0.24%   |
| GPU Company         | 3         | 0.24%   |
| Gateway             | 3         | 0.24%   |
| Dixonsxp            | 3         | 0.24%   |
| Digibras            | 3         | 0.24%   |
| YASHI               | 2         | 0.16%   |
| TrekStor            | 2         | 0.16%   |
| Teclast             | 2         | 0.16%   |
| Standard            | 2         | 0.16%   |
| SGIN                | 2         | 0.16%   |
| Semp Toshiba        | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 29        | 2.31%   |
| HP Notebook                           | 18        | 1.43%   |
| HP Pavilion 15                        | 8         | 0.64%   |
| HP Pavilion g6                        | 7         | 0.56%   |
| Apple MacBookPro8,1                   | 7         | 0.56%   |
| HP Pavilion dv6                       | 6         | 0.48%   |
| Dell Latitude E6410                   | 6         | 0.48%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS   | 5         | 0.4%    |
| HP Pavilion g7                        | 5         | 0.4%    |
| HP EliteBook 840 G3                   | 5         | 0.4%    |
| Apple MacBookPro9,2                   | 5         | 0.4%    |
| Mediacom WinPad 11,6 FullHD- WPU11    | 4         | 0.32%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 4         | 0.32%   |
| HP Laptop 15-bw0xx                    | 4         | 0.32%   |
| HP 2000                               | 4         | 0.32%   |
| Google Candy                          | 4         | 0.32%   |
| Dell Latitude D630                    | 4         | 0.32%   |
| Dell Inspiron N5010                   | 4         | 0.32%   |
| Dell Inspiron 15-3567                 | 4         | 0.32%   |
| Acer Aspire 5735                      | 4         | 0.32%   |
| Toshiba Satellite C660                | 3         | 0.24%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 3         | 0.24%   |
| Lenovo IdeaPad 320-15IKB 80XL         | 3         | 0.24%   |
| Lenovo IdeaPad 320-15AST 80XV         | 3         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 3         | 0.24%   |
| Lenovo G50-45 80E3                    | 3         | 0.24%   |
| Lenovo G50-30 80G0                    | 3         | 0.24%   |
| HP ProBook 440 G7                     | 3         | 0.24%   |
| HP Laptop 15-bs0xx                    | 3         | 0.24%   |
| HP EliteBook 8460p                    | 3         | 0.24%   |
| HP EliteBook 2560p                    | 3         | 0.24%   |
| HP Compaq Presario CQ60               | 3         | 0.24%   |
| Fujitsu LIFEBOOK AH531                | 3         | 0.24%   |
| Dell Latitude E5450                   | 3         | 0.24%   |
| Dell Latitude 7480                    | 3         | 0.24%   |
| Dell Inspiron 1525                    | 3         | 0.24%   |
| Dell Inspiron 13-5378                 | 3         | 0.24%   |
| ASUS 1000H                            | 3         | 0.24%   |
| Apple MacBook4,1                      | 3         | 0.24%   |
| Acer Aspire ES1-571                   | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 87        | 6.92%   |
| Lenovo IdeaPad          | 70        | 5.56%   |
| Lenovo ThinkPad         | 68        | 5.41%   |
| HP Pavilion             | 57        | 4.53%   |
| Dell Latitude           | 52        | 4.13%   |
| Dell Inspiron           | 52        | 4.13%   |
| Toshiba Satellite       | 50        | 3.97%   |
| HP EliteBook            | 38        | 3.02%   |
| HP ProBook              | 34        | 2.7%    |
| Unknown                 | 29        | 2.31%   |
| HP Laptop               | 27        | 2.15%   |
| HP Compaq               | 25        | 1.99%   |
| HP Notebook             | 18        | 1.43%   |
| ASUS VivoBook           | 16        | 1.27%   |
| Fujitsu LIFEBOOK        | 13        | 1.03%   |
| Packard Bell EasyNote   | 11        | 0.87%   |
| Dell XPS                | 10        | 0.79%   |
| Fujitsu Siemens AMILO   | 9         | 0.72%   |
| Acer Extensa            | 9         | 0.72%   |
| HP Stream               | 8         | 0.64%   |
| Dell Vostro             | 7         | 0.56%   |
| Apple MacBookPro8       | 7         | 0.56%   |
| Lenovo Yoga             | 6         | 0.48%   |
| HP ZBook                | 6         | 0.48%   |
| HP Presario             | 6         | 0.48%   |
| HP 250                  | 6         | 0.48%   |
| Dell Precision          | 6         | 0.48%   |
| Acer Swift              | 6         | 0.48%   |
| HP 255                  | 5         | 0.4%    |
| Apple MacBookPro9       | 5         | 0.4%    |
| Mediacom WinPad         | 4         | 0.32%   |
| Mediacom SmartBook      | 4         | 0.32%   |
| HP 240                  | 4         | 0.32%   |
| HP 2000                 | 4         | 0.32%   |
| Google Candy            | 4         | 0.32%   |
| Fujitsu Siemens ESPRIMO | 4         | 0.32%   |
| ASUS ASUS               | 4         | 0.32%   |
| Acer TravelMate         | 4         | 0.32%   |
| Samsung RV415           | 3         | 0.24%   |
| Notebook W54            | 3         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 125       | 9.94%   |
| 2010    | 101       | 8.03%   |
| 2013    | 98        | 7.79%   |
| 2012    | 93        | 7.39%   |
| 2008    | 90        | 7.15%   |
| 2016    | 78        | 6.2%    |
| 2019    | 72        | 5.72%   |
| 2007    | 70        | 5.56%   |
| 2014    | 69        | 5.48%   |
| 2015    | 64        | 5.09%   |
| 2009    | 64        | 5.09%   |
| 2017    | 63        | 5.01%   |
| 2021    | 57        | 4.53%   |
| 2018    | 57        | 4.53%   |
| 2020    | 44        | 3.5%    |
| 2022    | 37        | 2.94%   |
| 2006    | 28        | 2.23%   |
| 2023    | 24        | 1.91%   |
| 2005    | 9         | 0.72%   |
| 2024    | 7         | 0.56%   |
| Unknown | 3         | 0.24%   |
| 2004    | 2         | 0.16%   |
| 2002    | 2         | 0.16%   |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1258      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1172      | 92.65%  |
| Enabled  | 93        | 7.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1220      | 96.9%   |
| Yes  | 39        | 3.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 423       | 33.15%  |
| 4.01-8.0    | 307       | 24.06%  |
| 1.01-2.0    | 207       | 16.22%  |
| 8.01-16.0   | 113       | 8.86%   |
| 16.01-24.0  | 87        | 6.82%   |
| 2.01-3.0    | 66        | 5.17%   |
| 0.51-1.0    | 39        | 3.06%   |
| 32.01-64.0  | 21        | 1.65%   |
| 24.01-32.0  | 6         | 0.47%   |
| 0.01-0.5    | 4         | 0.31%   |
| 64.01-256.0 | 3         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 599       | 44.4%   |
| 0.51-1.0   | 310       | 22.98%  |
| 2.01-3.0   | 233       | 17.27%  |
| 3.01-4.0   | 73        | 5.41%   |
| 4.01-8.0   | 67        | 4.97%   |
| 0.01-0.5   | 53        | 3.93%   |
| 8.01-16.0  | 9         | 0.67%   |
| Unknown    | 3         | 0.22%   |
| 16.01-24.0 | 2         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 983       | 77.46%  |
| 2      | 245       | 19.31%  |
| 0      | 23        | 1.81%   |
| 3      | 17        | 1.34%   |
| 4      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 653       | 51.78%  |
| Yes       | 608       | 48.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1037      | 82.11%  |
| No        | 226       | 17.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1192      | 94.75%  |
| No        | 66        | 5.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 803       | 63.03%  |
| No        | 471       | 36.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 184       | 14.59%  |
| France       | 133       | 10.55%  |
| Brazil       | 103       | 8.17%   |
| Italy        | 101       | 8.01%   |
| Germany      | 95        | 7.53%   |
| Russia       | 66        | 5.23%   |
| UK           | 50        | 3.97%   |
| Poland       | 39        | 3.09%   |
| Canada       | 35        | 2.78%   |
| Spain        | 32        | 2.54%   |
| Turkey       | 21        | 1.67%   |
| Netherlands  | 21        | 1.67%   |
| Argentina    | 20        | 1.59%   |
| Mexico       | 19        | 1.51%   |
| Indonesia    | 18        | 1.43%   |
| Czechia      | 17        | 1.35%   |
| India        | 15        | 1.19%   |
| Finland      | 15        | 1.19%   |
| Belgium      | 15        | 1.19%   |
| Australia    | 14        | 1.11%   |
| Switzerland  | 13        | 1.03%   |
| Hungary      | 12        | 0.95%   |
| Ukraine      | 11        | 0.87%   |
| Romania      | 10        | 0.79%   |
| Colombia     | 10        | 0.79%   |
| Portugal     | 9         | 0.71%   |
| Costa Rica   | 9         | 0.71%   |
| Chile        | 9         | 0.71%   |
| South Africa | 8         | 0.63%   |
| Japan        | 7         | 0.56%   |
| Ireland      | 7         | 0.56%   |
| Peru         | 6         | 0.48%   |
| Norway       | 6         | 0.48%   |
| Vietnam      | 5         | 0.4%    |
| Taiwan       | 5         | 0.4%    |
| Sweden       | 5         | 0.4%    |
| Slovakia     | 5         | 0.4%    |
| Philippines  | 5         | 0.4%    |
| Malaysia     | 5         | 0.4%    |
| Lithuania    | 5         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 24        | 1.81%   |
| Moscow            | 15        | 1.13%   |
| Milan             | 14        | 1.05%   |
| Rome              | 11        | 0.83%   |
| Helsinki          | 11        | 0.83%   |
| New York          | 9         | 0.68%   |
| Billings          | 8         | 0.6%    |
| Istanbul          | 7         | 0.53%   |
| Curitiba          | 7         | 0.53%   |
| Warsaw            | 6         | 0.45%   |
| St Petersburg     | 6         | 0.45%   |
| Sao Paulo         | 6         | 0.45%   |
| Prague            | 6         | 0.45%   |
| Munich            | 6         | 0.45%   |
| Mexico City       | 6         | 0.45%   |
| Brasília         | 6         | 0.45%   |
| Bengaluru         | 6         | 0.45%   |
| Stuttgart         | 5         | 0.38%   |
| Santiago          | 5         | 0.38%   |
| Porto Alegre      | 5         | 0.38%   |
| Melbourne         | 5         | 0.38%   |
| Kyiv              | 5         | 0.38%   |
| Houston           | 5         | 0.38%   |
| Heredia           | 5         | 0.38%   |
| Grecia            | 5         | 0.38%   |
| Buenos Aires      | 5         | 0.38%   |
| Bogotá           | 5         | 0.38%   |
| Yekaterinburg     | 4         | 0.3%    |
| Winnipeg          | 4         | 0.3%    |
| Uberlândia       | 4         | 0.3%    |
| Strasbourg        | 4         | 0.3%    |
| Rio de Janeiro    | 4         | 0.3%    |
| Montevideo        | 4         | 0.3%    |
| Milano            | 4         | 0.3%    |
| Madrid            | 4         | 0.3%    |
| Krakow            | 4         | 0.3%    |
| Ghent             | 4         | 0.3%    |
| Frankfurt am Main | 4         | 0.3%    |
| Fortaleza         | 4         | 0.3%    |
| Dublin            | 4         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 185       | 216    | 13.15%  |
| Seagate             | 175       | 204    | 12.44%  |
| Unknown             | 158       | 217    | 11.23%  |
| Samsung Electronics | 130       | 180    | 9.24%   |
| Toshiba             | 117       | 132    | 8.32%   |
| Hitachi             | 87        | 105    | 6.18%   |
| Kingston            | 71        | 81     | 5.05%   |
| SanDisk             | 46        | 55     | 3.27%   |
| Crucial             | 46        | 51     | 3.27%   |
| HGST                | 37        | 43     | 2.63%   |
| SK hynix            | 30        | 31     | 2.13%   |
| Intel               | 29        | 41     | 2.06%   |
| Fujitsu             | 26        | 28     | 1.85%   |
| Micron Technology   | 22        | 23     | 1.56%   |
| China               | 20        | 24     | 1.42%   |
| A-DATA Technology   | 17        | 17     | 1.21%   |
| Unknown             | 15        | 17     | 1.07%   |
| Patriot             | 11        | 11     | 0.78%   |
| Apacer              | 11        | 11     | 0.78%   |
| KIOXIA              | 8         | 8      | 0.57%   |
| SPCC                | 7         | 9      | 0.5%    |
| LITEON              | 7         | 8      | 0.5%    |
| UMIS                | 6         | 6      | 0.43%   |
| Transcend           | 6         | 7      | 0.43%   |
| PNY                 | 6         | 8      | 0.43%   |
| Apple               | 6         | 13     | 0.43%   |
| OCZ                 | 5         | 5      | 0.36%   |
| LITEONIT            | 5         | 5      | 0.36%   |
| KingSpec            | 5         | 7      | 0.36%   |
| Silicon Motion      | 4         | 4      | 0.28%   |
| NGFF                | 4         | 4      | 0.28%   |
| Netac               | 4         | 4      | 0.28%   |
| Lexar               | 4         | 7      | 0.28%   |
| IBM/Hitachi         | 4         | 5      | 0.28%   |
| USB                 | 3         | 3      | 0.21%   |
| Phison Electronics  | 3         | 3      | 0.21%   |
| Phison              | 3         | 7      | 0.21%   |
| LDLC                | 3         | 5      | 0.21%   |
| JMicron Technology  | 3         | 3      | 0.21%   |
| GOODRAM             | 3         | 3      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 38        | 2.6%    |
| Unknown MMC Card  64GB              | 26        | 1.78%   |
| Kingston SA400S37240G 240GB SSD     | 19        | 1.3%    |
| Seagate ST500LT012-1DG142 500GB     | 18        | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB      | 17        | 1.16%   |
| Seagate ST9500325AS 500GB           | 16        | 1.1%    |
| Toshiba MQ01ABD100 1TB              | 15        | 1.03%   |
| Unknown                             | 15        | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 0.89%   |
| Toshiba MQ01ABF050 500GB            | 12        | 0.82%   |
| Unknown MMC Card  16GB              | 11        | 0.75%   |
| HGST HTS545050A7E680 500GB          | 11        | 0.75%   |
| Unknown NCard  32GB                 | 10        | 0.68%   |
| Unknown DA4064  64GB                | 10        | 0.68%   |
| Toshiba MQ01ABD050 500GB            | 9         | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 0.62%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 0.62%   |
| HGST HTS545050A7E380 500GB          | 9         | 0.62%   |
| Crucial CT240BX500SSD1 240GB        | 9         | 0.62%   |
| Seagate ST9320325AS 320GB           | 8         | 0.55%   |
| Samsung SSD 850 EVO 250GB           | 8         | 0.55%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 0.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 7         | 0.48%   |
| SanDisk DF4032  32GB                | 7         | 0.48%   |
| Kingston SV300S37A120G 120GB SSD    | 7         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 6         | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB            | 6         | 0.41%   |
| Unknown MMC Card  128GB             | 6         | 0.41%   |
| SK hynix HBG4e  32GB                | 6         | 0.41%   |
| Samsung SSD 860 EVO 500GB           | 6         | 0.41%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 0.41%   |
| Hitachi HTS543232A7A384 320GB       | 6         | 0.41%   |
| Crucial CT480BX500SSD1 480GB        | 6         | 0.41%   |
| China SSD 128GB                     | 6         | 0.41%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 0.34%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 5         | 0.34%   |
| WDC WD10JPVX-60JC3T0 1TB            | 5         | 0.34%   |
| Unknown SD/MMC/MS PRO 2GB           | 5         | 0.34%   |
| Unknown MMC64G  64GB                | 5         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 172       | 201    | 27.48%  |
| WDC                 | 156       | 180    | 24.92%  |
| Toshiba             | 102       | 112    | 16.29%  |
| Hitachi             | 87        | 105    | 13.9%   |
| HGST                | 37        | 43     | 5.91%   |
| Samsung Electronics | 26        | 44     | 4.15%   |
| Fujitsu             | 26        | 28     | 4.15%   |
| Unknown             | 5         | 7      | 0.8%    |
| IBM/Hitachi         | 4         | 5      | 0.64%   |
| STEC                | 2         | 3      | 0.32%   |
| SSK                 | 2         | 2      | 0.32%   |
| XrayDisk            | 1         | 1      | 0.16%   |
| USB3.0              | 1         | 1      | 0.16%   |
| USB                 | 1         | 1      | 0.16%   |
| LaCie               | 1         | 1      | 0.16%   |
| JMicron Technology  | 1         | 1      | 0.16%   |
| Intenso             | 1         | 1      | 0.16%   |
| Apple               | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 66        | 87     | 15.17%  |
| Kingston            | 61        | 69     | 14.02%  |
| Crucial             | 42        | 47     | 9.66%   |
| SanDisk             | 29        | 37     | 6.67%   |
| Intel               | 22        | 34     | 5.06%   |
| China               | 18        | 21     | 4.14%   |
| WDC                 | 17        | 21     | 3.91%   |
| A-DATA Technology   | 17        | 17     | 3.91%   |
| Patriot             | 11        | 11     | 2.53%   |
| Apacer              | 11        | 11     | 2.53%   |
| Toshiba             | 9         | 12     | 2.07%   |
| SK hynix            | 8         | 9      | 1.84%   |
| SPCC                | 7         | 9      | 1.61%   |
| LITEON              | 7         | 8      | 1.61%   |
| Transcend           | 6         | 7      | 1.38%   |
| PNY                 | 6         | 8      | 1.38%   |
| Micron Technology   | 6         | 6      | 1.38%   |
| OCZ                 | 5         | 5      | 1.15%   |
| LITEONIT            | 5         | 5      | 1.15%   |
| KingSpec            | 5         | 7      | 1.15%   |
| NGFF                | 4         | 4      | 0.92%   |
| Netac               | 4         | 4      | 0.92%   |
| Lexar               | 4         | 7      | 0.92%   |
| Apple               | 4         | 10     | 0.92%   |
| GOODRAM             | 3         | 3      | 0.69%   |
| XrayDisk            | 2         | 2      | 0.46%   |
| Teclast             | 2         | 2      | 0.46%   |
| Team                | 2         | 2      | 0.46%   |
| Plextor             | 2         | 2      | 0.46%   |
| LDLC                | 2         | 2      | 0.46%   |
| KingDian            | 2         | 2      | 0.46%   |
| Dogfish             | 2         | 2      | 0.46%   |
| Zheino              | 1         | 1      | 0.23%   |
| WALRAM              | 1         | 1      | 0.23%   |
| W800S               | 1         | 1      | 0.23%   |
| Verbatim            | 1         | 1      | 0.23%   |
| Vaseky              | 1         | 1      | 0.23%   |
| Unknown             | 1         | 1      | 0.23%   |
| Timetec             | 1         | 1      | 0.23%   |
| TEAM T25            | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 616       | 737    | 44.61%  |
| SSD     | 424       | 518    | 30.7%   |
| MMC     | 175       | 237    | 12.67%  |
| NVMe    | 146       | 176    | 10.57%  |
| Unknown | 20        | 23     | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 979       | 1225   | 72.84%  |
| MMC  | 175       | 237    | 13.02%  |
| NVMe | 146       | 175    | 10.86%  |
| SAS  | 44        | 54     | 3.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 799       | 976    | 77.88%  |
| 0.51-1.0   | 189       | 235    | 18.42%  |
| 1.01-2.0   | 28        | 33     | 2.73%   |
| 3.01-4.0   | 7         | 8      | 0.68%   |
| 4.01-10.0  | 3         | 3      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 398       | 31.02%  |
| 251-500        | 324       | 25.25%  |
| 51-100         | 136       | 10.6%   |
| 501-1000       | 131       | 10.21%  |
| 1-20           | 125       | 9.74%   |
| 21-50          | 113       | 8.81%   |
| 1001-2000      | 29        | 2.26%   |
| More than 3000 | 14        | 1.09%   |
| 2001-3000      | 8         | 0.62%   |
| Unknown        | 5         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 727       | 54.87%  |
| 21-50          | 258       | 19.47%  |
| 101-250        | 122       | 9.21%   |
| 51-100         | 111       | 8.38%   |
| 251-500        | 52        | 3.92%   |
| 501-1000       | 27        | 2.04%   |
| 1001-2000      | 14        | 1.06%   |
| More than 3000 | 6         | 0.45%   |
| Unknown        | 5         | 0.38%   |
| 2001-3000      | 3         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 7      | 4.83%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 4.14%   |
| HGST HTS545050A7E680 500GB         | 5         | 5      | 3.45%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 2.76%   |
| HGST HTS545050A7E380 500GB         | 4         | 4      | 2.76%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 2.07%   |
| Hitachi HTS545032B9A300 320GB      | 3         | 3      | 2.07%   |
| WDC WD10SPZX-24Z10T0 1TB           | 2         | 2      | 1.38%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 1.38%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 2      | 1.38%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 1.38%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.38%   |
| Hitachi HTS542512K9SA00 120GB      | 2         | 2      | 1.38%   |
| China G521N256GB                   | 2         | 2      | 1.38%   |
| Apacer 16GB SATA Flash Drive SSD   | 2         | 2      | 1.38%   |
| XrayDisk SSD 512GB                 | 1         | 1      | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 1      | 0.69%   |
| WDC WD800BEVS-60RST0 80GB          | 1         | 1      | 0.69%   |
| WDC WD5000LUCT-62C26Y0 500GB       | 1         | 1      | 0.69%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 0.69%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 0.69%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BEVT-75A23T0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.69%   |
| WDC WD2500BEVT-80A23T0 250GB       | 1         | 2      | 0.69%   |
| WDC WD1600BEVT-22A23T0 160GB       | 1         | 1      | 0.69%   |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.69%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 0.69%   |
| WDC WD10SPCX-21KHST0 1TB           | 1         | 1      | 0.69%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 0.69%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 0.69%   |
| Transcend TS256GSSD720 256GB       | 1         | 1      | 0.69%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 0.69%   |
| Toshiba MK6459GSXP 640GB           | 1         | 1      | 0.69%   |
| Toshiba MK5065GSXN 500GB           | 1         | 1      | 0.69%   |
| Toshiba MK5059GSXP 500GB           | 1         | 1      | 0.69%   |
| Toshiba MK3276GSX 320GB            | 1         | 1      | 0.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 38     | 24.83%  |
| Hitachi             | 22        | 23     | 15.17%  |
| WDC                 | 20        | 21     | 13.79%  |
| HGST                | 13        | 13     | 8.97%   |
| Toshiba             | 11        | 11     | 7.59%   |
| Intel               | 5         | 6      | 3.45%   |
| Crucial             | 5         | 5      | 3.45%   |
| SK hynix            | 4         | 4      | 2.76%   |
| Samsung Electronics | 3         | 11     | 2.07%   |
| Fujitsu             | 3         | 3      | 2.07%   |
| China               | 3         | 3      | 2.07%   |
| SanDisk             | 2         | 2      | 1.38%   |
| OCZ                 | 2         | 2      | 1.38%   |
| LITEON              | 2         | 2      | 1.38%   |
| Kingston            | 2         | 2      | 1.38%   |
| KingSpec            | 2         | 4      | 1.38%   |
| Apacer              | 2         | 2      | 1.38%   |
| XrayDisk            | 1         | 1      | 0.69%   |
| Transcend           | 1         | 1      | 0.69%   |
| TCSUNBOW            | 1         | 1      | 0.69%   |
| Plextor             | 1         | 1      | 0.69%   |
| NGFF                | 1         | 1      | 0.69%   |
| Kingmax             | 1         | 1      | 0.69%   |
| Apple               | 1         | 1      | 0.69%   |
| A-DATA Technology   | 1         | 1      | 0.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 38     | 33.64%  |
| Hitachi             | 22        | 23     | 20.56%  |
| WDC                 | 19        | 20     | 17.76%  |
| HGST                | 13        | 13     | 12.15%  |
| Toshiba             | 11        | 11     | 10.28%  |
| Samsung Electronics | 3         | 11     | 2.8%    |
| Fujitsu             | 3         | 3      | 2.8%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 107       | 119    | 73.79%  |
| SSD  | 36        | 39     | 24.83%  |
| NVMe | 2         | 2      | 1.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB      | 1         | 1      | 14.29%  |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 14.29%  |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 14.29%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 14.29%  |
| Seagate ST9500325AS 500GB         | 1         | 1      | 14.29%  |
| Seagate ST9320325AS 320GB         | 1         | 1      | 14.29%  |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 57.14%  |
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 705       | 983    | 53.9%   |
| Works    | 451       | 540    | 34.48%  |
| Malfunc  | 145       | 160    | 11.09%  |
| Failed   | 7         | 8      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 862       | 69.29%  |
| AMD                                     | 193       | 15.51%  |
| Samsung Electronics                     | 38        | 3.05%   |
| SanDisk                                 | 22        | 1.77%   |
| Nvidia                                  | 22        | 1.77%   |
| Micron Technology                       | 17        | 1.37%   |
| SK hynix                                | 15        | 1.21%   |
| Silicon Integrated Systems [SiS]        | 14        | 1.13%   |
| Kingston Technology Company             | 11        | 0.88%   |
| KIOXIA                                  | 8         | 0.64%   |
| Toshiba America Info Systems            | 6         | 0.48%   |
| Phison Electronics                      | 6         | 0.48%   |
| Micron/Crucial Technology               | 6         | 0.48%   |
| Silicon Motion                          | 5         | 0.4%    |
| VIA Technologies                        | 4         | 0.32%   |
| Union Memory (Shenzhen)                 | 4         | 0.32%   |
| Solid State Storage Technology          | 3         | 0.24%   |
| Silicon Image                           | 2         | 0.16%   |
| Shenzhen Unionmemory Information System | 2         | 0.16%   |
| JMicron Technology                      | 2         | 0.16%   |
| ASMedia Technology                      | 2         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 127       | 9.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 92        | 6.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 72        | 5.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 69        | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 65        | 4.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 62        | 4.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 60        | 4.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 44        | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 43        | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 41        | 2.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 38        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 38        | 2.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 36        | 2.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 31        | 2.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 30        | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 24        | 1.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 23        | 1.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 23        | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 22        | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 21        | 1.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 21        | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 18        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 14        | 0.99%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 13        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 13        | 0.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 13        | 0.92%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 11        | 0.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 11        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 10        | 0.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 10        | 0.71%   |
| AMD SB600 IDE                                                                          | 9         | 0.64%   |
| AMD IXP SB4x0 IDE Controller                                                           | 9         | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 8         | 0.57%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 8         | 0.57%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 7         | 0.5%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 7         | 0.5%    |
| Intel Alder Lake-P SATA AHCI Controller                                                | 7         | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 7         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 7         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 921       | 68.68%  |
| IDE  | 218       | 16.26%  |
| NVMe | 144       | 10.74%  |
| RAID | 58        | 4.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1029      | 81.8%   |
| AMD     | 228       | 18.12%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz           | 21        | 1.67%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 18        | 1.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 17        | 1.35%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 16        | 1.27%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 15        | 1.19%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 15        | 1.19%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 15        | 1.19%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 14        | 1.11%   |
| Intel Atom CPU N270 @ 1.60GHz               | 14        | 1.11%   |
| Intel Atom CPU N450 @ 1.66GHz               | 12        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 11        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 11        | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 11        | 0.87%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 11        | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 11        | 0.87%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 11        | 0.87%   |
| Intel Atom CPU N455 @ 1.66GHz               | 11        | 0.87%   |
| AMD E-450 APU with Radeon HD Graphics       | 11        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 10        | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 10        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 10        | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 10        | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 10        | 0.79%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 10        | 0.79%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 10        | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 10        | 0.79%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 8         | 0.63%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 8         | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 8         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 8         | 0.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 8         | 0.63%   |
| AMD E-300 APU with Radeon HD Graphics       | 8         | 0.63%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 7         | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.56%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 7         | 0.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 7         | 0.56%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 7         | 0.56%   |
| AMD E1-2100 APU with Radeon HD Graphics     | 7         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 215       | 17.08%  |
| Intel Celeron           | 182       | 14.46%  |
| Intel Core i7           | 117       | 9.29%   |
| Intel Atom              | 112       | 8.9%    |
| Intel Core i3           | 106       | 8.42%   |
| Intel Core 2 Duo        | 92        | 7.31%   |
| Other                   | 45        | 3.57%   |
| Intel Pentium           | 44        | 3.49%   |
| Intel Pentium Dual      | 27        | 2.14%   |
| AMD A6                  | 26        | 2.07%   |
| AMD E                   | 25        | 1.99%   |
| Intel Pentium Dual-Core | 24        | 1.91%   |
| AMD E1                  | 22        | 1.75%   |
| AMD A4                  | 20        | 1.59%   |
| Intel Core 2            | 19        | 1.51%   |
| AMD Ryzen 5             | 18        | 1.43%   |
| Intel Genuine           | 16        | 1.27%   |
| AMD Ryzen 7             | 16        | 1.27%   |
| AMD E2                  | 11        | 0.87%   |
| AMD A8                  | 11        | 0.87%   |
| Intel Pentium Silver    | 8         | 0.64%   |
| AMD Athlon              | 8         | 0.64%   |
| Intel Celeron Dual-Core | 7         | 0.56%   |
| AMD A10                 | 7         | 0.56%   |
| Intel Celeron M         | 6         | 0.48%   |
| AMD Turion 64 X2 Mobile | 6         | 0.48%   |
| AMD Mobile Sempron      | 6         | 0.48%   |
| Intel Pentium M         | 5         | 0.4%    |
| AMD C-50                | 5         | 0.4%    |
| AMD Ryzen 7 PRO         | 4         | 0.32%   |
| AMD Ryzen 3             | 4         | 0.32%   |
| AMD C-60                | 4         | 0.32%   |
| AMD Athlon 64 X2        | 4         | 0.32%   |
| Intel Pentium 4         | 3         | 0.24%   |
| AMD Turion 64 Mobile    | 3         | 0.24%   |
| AMD Sempron             | 3         | 0.24%   |
| AMD Athlon X2           | 3         | 0.24%   |
| Intel Core Duo          | 2         | 0.16%   |
| Intel Core              | 2         | 0.16%   |
| AMD Phenom II           | 2         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 847       | 67.33%  |
| 4      | 260       | 20.67%  |
| 1      | 96        | 7.63%   |
| 8      | 22        | 1.75%   |
| 6      | 16        | 1.27%   |
| 10     | 8         | 0.64%   |
| 12     | 3         | 0.24%   |
| 16     | 2         | 0.16%   |
| 14     | 2         | 0.16%   |
| 5      | 1         | 0.08%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1256      | 99.84%  |
| 2      | 2         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 664       | 52.78%  |
| 2      | 594       | 47.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1202      | 95.55%  |
| 32-bit         | 55        | 4.37%   |
| Unknown        | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 572       | 44.41%  |
| 0x206a7    | 56        | 4.35%   |
| 0x306a9    | 47        | 3.65%   |
| 0x6fd      | 44        | 3.42%   |
| 0x1067a    | 32        | 2.48%   |
| 0x40651    | 27        | 2.1%    |
| 0x20655    | 26        | 2.02%   |
| 0x05000119 | 26        | 2.02%   |
| 0x30678    | 24        | 1.86%   |
| 0x106ca    | 23        | 1.79%   |
| 0x406e3    | 21        | 1.63%   |
| 0x406c3    | 21        | 1.63%   |
| 0x406c4    | 20        | 1.55%   |
| 0x106c2    | 17        | 1.32%   |
| 0x806ec    | 15        | 1.16%   |
| 0x706a8    | 15        | 1.16%   |
| 0x706a1    | 14        | 1.09%   |
| 0x20652    | 13        | 1.01%   |
| 0x0700010f | 12        | 0.93%   |
| 0x06006705 | 12        | 0.93%   |
| 0x806ea    | 11        | 0.85%   |
| 0x6f6      | 11        | 0.85%   |
| 0x6e8      | 11        | 0.85%   |
| 0x306c3    | 11        | 0.85%   |
| 0x10676    | 11        | 0.85%   |
| 0x806e9    | 10        | 0.78%   |
| 0x6d8      | 9         | 0.7%    |
| 0x306d4    | 9         | 0.7%    |
| 0x506c9    | 8         | 0.62%   |
| 0x10661    | 8         | 0.62%   |
| 0x06006704 | 8         | 0.62%   |
| 0x05000029 | 8         | 0.62%   |
| 0x6fb      | 7         | 0.54%   |
| 0x07030105 | 7         | 0.54%   |
| 0x806c1    | 6         | 0.47%   |
| 0x30661    | 6         | 0.47%   |
| 0x906ea    | 5         | 0.39%   |
| 0x806eb    | 5         | 0.39%   |
| 0x706e5    | 5         | 0.39%   |
| 0x6ec      | 5         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Silvermont        | 131       | 10.41%  |
| Core              | 105       | 8.35%   |
| SandyBridge       | 99        | 7.87%   |
| KabyLake          | 96        | 7.63%   |
| Penryn            | 80        | 6.36%   |
| IvyBridge         | 77        | 6.12%   |
| Westmere          | 74        | 5.88%   |
| Haswell           | 69        | 5.48%   |
| Bonnell           | 59        | 4.69%   |
| Goldmont plus     | 53        | 4.21%   |
| Skylake           | 47        | 3.74%   |
| Bobcat            | 46        | 3.66%   |
| Excavator         | 38        | 3.02%   |
| P6                | 27        | 2.15%   |
| Goldmont          | 27        | 2.15%   |
| Broadwell         | 24        | 1.91%   |
| K8 Hammer         | 21        | 1.67%   |
| Puma              | 20        | 1.59%   |
| Jaguar            | 20        | 1.59%   |
| Unknown           | 19        | 1.51%   |
| TigerLake         | 16        | 1.27%   |
| Alderlake Hybrid  | 15        | 1.19%   |
| Zen+              | 13        | 1.03%   |
| IceLake           | 11        | 0.87%   |
| Piledriver        | 10        | 0.79%   |
| Zen 2             | 9         | 0.72%   |
| Zen               | 8         | 0.64%   |
| Tremont           | 8         | 0.64%   |
| K8 & K10 hybrid   | 8         | 0.64%   |
| Zen 3             | 7         | 0.56%   |
| K10               | 7         | 0.56%   |
| NetBurst          | 5         | 0.4%    |
| K10 Llano         | 5         | 0.4%    |
| Nehalem           | 2         | 0.16%   |
| Meteorlake Hybrid | 1         | 0.08%   |
| Gracemont         | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 914       | 64.87%  |
| AMD                              | 298       | 21.15%  |
| Nvidia                           | 181       | 12.85%  |
| Silicon Integrated Systems [SiS] | 11        | 0.78%   |
| VIA Technologies                 | 4         | 0.28%   |
| S3 Graphics                      | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91        | 5.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 75        | 4.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 74        | 4.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 61        | 3.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 61        | 3.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 58        | 3.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 57        | 3.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 53        | 3.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 47        | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 3.01%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 36        | 2.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 35        | 2.29%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 2.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 31        | 2.03%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 26        | 1.7%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 25        | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 20        | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.31%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 19        | 1.24%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 18        | 1.18%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 18        | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 1.05%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 15        | 0.98%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 14        | 0.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 11        | 0.72%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 10        | 0.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 0.59%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 9         | 0.59%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 8         | 0.52%   |
| Intel JasperLake [UHD Graphics]                                                          | 8         | 0.52%   |
| AMD Kabini [Radeon HD 8210]                                                              | 8         | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.46%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 7         | 0.46%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 7         | 0.46%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 747       | 59.29%  |
| 1 x AMD         | 224       | 17.78%  |
| Intel + Nvidia  | 100       | 7.94%   |
| 1 x Nvidia      | 76        | 6.03%   |
| Intel + AMD     | 46        | 3.65%   |
| 2 x AMD         | 23        | 1.83%   |
| 2 x Intel       | 13        | 1.03%   |
| 1 x SiS         | 11        | 0.87%   |
| Other           | 10        | 0.79%   |
| AMD + Nvidia    | 5         | 0.4%    |
| 1 x VIA         | 4         | 0.32%   |
| 1 x S3 Graphics | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1164      | 92.38%  |
| Unknown     | 49        | 3.89%   |
| Proprietary | 47        | 3.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 892       | 70.13%  |
| 0.01-0.5   | 226       | 17.77%  |
| 1.01-2.0   | 78        | 6.13%   |
| 0.51-1.0   | 48        | 3.77%   |
| 3.01-4.0   | 19        | 1.49%   |
| 5.01-6.0   | 5         | 0.39%   |
| 2.01-3.0   | 4         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 254       | 20.05%  |
| LG Display              | 182       | 14.36%  |
| Samsung Electronics     | 161       | 12.71%  |
| BOE                     | 157       | 12.39%  |
| Chimei Innolux          | 150       | 11.84%  |
| Chi Mei Optoelectronics | 46        | 3.63%   |
| Apple                   | 34        | 2.68%   |
| LG Philips              | 33        | 2.6%    |
| Lenovo                  | 27        | 2.13%   |
| HannStar                | 21        | 1.66%   |
| CPT                     | 19        | 1.5%    |
| InfoVision              | 17        | 1.34%   |
| Goldstar                | 17        | 1.34%   |
| Acer                    | 15        | 1.18%   |
| Dell                    | 14        | 1.1%    |
| Hewlett-Packard         | 13        | 1.03%   |
| Sharp                   | 11        | 0.87%   |
| PANDA                   | 10        | 0.79%   |
| Philips                 | 6         | 0.47%   |
| AOC                     | 6         | 0.47%   |
| Toshiba                 | 5         | 0.39%   |
| Sony                    | 5         | 0.39%   |
| BenQ                    | 5         | 0.39%   |
| InnoLux Display         | 4         | 0.32%   |
| NEC Computers           | 3         | 0.24%   |
| KDC                     | 3         | 0.24%   |
| ASUSTek Computer        | 3         | 0.24%   |
| Vizio                   | 2         | 0.16%   |
| ViewSonic               | 2         | 0.16%   |
| Unknown                 | 2         | 0.16%   |
| Quanta Display          | 2         | 0.16%   |
| Panasonic               | 2         | 0.16%   |
| ITE                     | 2         | 0.16%   |
| Insignia                | 2         | 0.16%   |
| Iiyama                  | 2         | 0.16%   |
| HKC                     | 2         | 0.16%   |
| CSW                     | 2         | 0.16%   |
| Ancor Communications    | 2         | 0.16%   |
| Westinghouse            | 1         | 0.08%   |
| Videoseven              | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 12        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 11        | 0.86%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 11        | 0.86%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 11        | 0.86%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 10        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 10        | 0.79%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.79%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 9         | 0.71%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 9         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 7         | 0.55%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 7         | 0.55%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 7         | 0.55%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 7         | 0.55%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 7         | 0.55%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 6         | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.47%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 6         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.39%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 0.39%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.39%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 5         | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 4         | 0.31%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 4         | 0.31%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.31%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 4         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 551       | 44.54%  |
| 1920x1080 (FHD)    | 289       | 23.36%  |
| 1280x800 (WXGA)    | 143       | 11.56%  |
| 1600x900 (HD+)     | 73        | 5.9%    |
| 1024x600           | 36        | 2.91%   |
| 1920x1200 (WUXGA)  | 32        | 2.59%   |
| 3840x2160 (4K)     | 25        | 2.02%   |
| 1440x900 (WXGA+)   | 21        | 1.7%    |
| 2560x1440 (QHD)    | 11        | 0.89%   |
| 1680x1050 (WSXGA+) | 11        | 0.89%   |
| 1280x1024 (SXGA)   | 7         | 0.57%   |
| 3840x2400          | 4         | 0.32%   |
| 3200x1800 (QHD+)   | 4         | 0.32%   |
| 1360x768           | 4         | 0.32%   |
| 2880x1800          | 3         | 0.24%   |
| 2288x1287          | 3         | 0.24%   |
| 2160x1440          | 3         | 0.24%   |
| 1280x720 (HD)      | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 3840x1600          | 1         | 0.08%   |
| 3840x1080          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 3120x2080          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2560x1600          | 1         | 0.08%   |
| 2560x1080          | 1         | 0.08%   |
| 1920x540           | 1         | 0.08%   |
| 1920x1280          | 1         | 0.08%   |
| 1528x1222          | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |
| 1280x768           | 1         | 0.08%   |
| Unknown            | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 502       | 39.62%  |
| 14      | 182       | 14.36%  |
| 13      | 180       | 14.21%  |
| 11      | 81        | 6.39%   |
| 17      | 78        | 6.16%   |
| 10      | 42        | 3.31%   |
| 12      | 41        | 3.24%   |
| 27      | 24        | 1.89%   |
| 24      | 22        | 1.74%   |
| 21      | 17        | 1.34%   |
| 23      | 13        | 1.03%   |
| Unknown | 11        | 0.87%   |
| 19      | 9         | 0.71%   |
| 18      | 9         | 0.71%   |
| 22      | 8         | 0.63%   |
| 84      | 6         | 0.47%   |
| 16      | 6         | 0.47%   |
| 31      | 5         | 0.39%   |
| 72      | 4         | 0.32%   |
| 26      | 3         | 0.24%   |
| 9       | 3         | 0.24%   |
| 8       | 3         | 0.24%   |
| 142     | 2         | 0.16%   |
| 48      | 2         | 0.16%   |
| 28      | 2         | 0.16%   |
| 20      | 2         | 0.16%   |
| 65      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 60      | 1         | 0.08%   |
| 54      | 1         | 0.08%   |
| 44      | 1         | 0.08%   |
| 43      | 1         | 0.08%   |
| 42      | 1         | 0.08%   |
| 34      | 1         | 0.08%   |
| 33      | 1         | 0.08%   |
| 25      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 775       | 61.41%  |
| 201-300        | 244       | 19.33%  |
| 351-400        | 96        | 7.61%   |
| 501-600        | 60        | 4.75%   |
| 401-500        | 39        | 3.09%   |
| Unknown        | 11        | 0.87%   |
| 601-700        | 10        | 0.79%   |
| 1501-2000      | 10        | 0.79%   |
| 1001-1500      | 6         | 0.48%   |
| 101-200        | 4         | 0.32%   |
| 901-1000       | 3         | 0.24%   |
| More than 2000 | 2         | 0.16%   |
| 701-800        | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 946       | 80.1%   |
| 16/10   | 203       | 17.19%  |
| 3/2     | 10        | 0.85%   |
| 5/4     | 6         | 0.51%   |
| 4/3     | 6         | 0.51%   |
| Unknown | 6         | 0.51%   |
| 1.00    | 2         | 0.17%   |
| 32/9    | 1         | 0.08%   |
| 21/9    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 497       | 39.2%   |
| 81-90          | 308       | 24.29%  |
| 51-60          | 81        | 6.39%   |
| 121-130        | 62        | 4.89%   |
| 71-80          | 53        | 4.18%   |
| 201-250        | 47        | 3.71%   |
| 41-50          | 45        | 3.55%   |
| 61-70          | 39        | 3.08%   |
| 301-350        | 25        | 1.97%   |
| More than 1000 | 17        | 1.34%   |
| 251-300        | 16        | 1.26%   |
| 131-140        | 15        | 1.18%   |
| 151-200        | 13        | 1.03%   |
| Unknown        | 11        | 0.87%   |
| 141-150        | 10        | 0.79%   |
| 91-100         | 8         | 0.63%   |
| 351-500        | 7         | 0.55%   |
| 111-120        | 6         | 0.47%   |
| 501-1000       | 5         | 0.39%   |
| 1-40           | 3         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 583       | 46.64%  |
| 121-160       | 364       | 29.12%  |
| 51-100        | 221       | 17.68%  |
| 161-240       | 45        | 3.6%    |
| More than 240 | 13        | 1.04%   |
| 1-50          | 13        | 1.04%   |
| Unknown       | 11        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1119      | 88.04%  |
| 2     | 124       | 9.76%   |
| 0     | 23        | 1.81%   |
| 3     | 5         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 654       | 32.44%  |
| Intel                             | 464       | 23.02%  |
| Qualcomm Atheros                  | 362       | 17.96%  |
| Broadcom                          | 176       | 8.73%   |
| Marvell Technology Group          | 52        | 2.58%   |
| Ralink                            | 40        | 1.98%   |
| Broadcom Limited                  | 39        | 1.93%   |
| ASIX Electronics                  | 19        | 0.94%   |
| Ralink Technology                 | 18        | 0.89%   |
| MediaTek                          | 18        | 0.89%   |
| TP-Link                           | 17        | 0.84%   |
| Nvidia                            | 17        | 0.84%   |
| Samsung Electronics               | 13        | 0.64%   |
| Attansic Technology               | 13        | 0.64%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.55%   |
| Xiaomi                            | 10        | 0.5%    |
| JMicron Technology                | 7         | 0.35%   |
| Huawei Technologies               | 6         | 0.3%    |
| Dell                              | 6         | 0.3%    |
| AMD                               | 5         | 0.25%   |
| VIA Technologies                  | 4         | 0.2%    |
| DisplayLink                       | 4         | 0.2%    |
| Sierra Wireless                   | 3         | 0.15%   |
| Qualcomm                          | 3         | 0.15%   |
| OPPO Electronics                  | 3         | 0.15%   |
| Micro Star International          | 3         | 0.15%   |
| Hewlett-Packard                   | 3         | 0.15%   |
| Fibocom                           | 3         | 0.15%   |
| Ericsson Business Mobile Networks | 3         | 0.15%   |
| D-Link                            | 3         | 0.15%   |
| ASUSTek Computer                  | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.1%    |
| Shenzhen Goodix Technology        | 2         | 0.1%    |
| Qualcomm Atheros Communications   | 2         | 0.1%    |
| NetGear                           | 2         | 0.1%    |
| Linksys                           | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| Edimax Technology                 | 2         | 0.1%    |
| 3Com                              | 2         | 0.1%    |
| Texas Instruments                 | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 296       | 12.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 200       | 8.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 81        | 3.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 50        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 46        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 45        | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 44        | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 1.79%   |
| Intel Wireless 7260                                                     | 43        | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 34        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 1.33%   |
| Intel Wireless 7265                                                     | 32        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 31        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 24        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 24        | 1%      |
| Intel Wireless 8265 / 8275                                              | 24        | 1%      |
| Intel 82577LM Gigabit Network Connection                                | 24        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 23        | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 0.87%   |
| Intel Wireless 3165                                                     | 19        | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 18        | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 18        | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 18        | 0.75%   |
| Intel Wireless 8260                                                     | 18        | 0.75%   |
| Intel Wireless 3160                                                     | 17        | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 17        | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 0.66%   |
| Realtek 802.11n WLAN Adapter                                            | 15        | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 0.58%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 14        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 13        | 0.54%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 0.54%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.54%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 13        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 12        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 12        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 12        | 0.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 12        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 435       | 34.39%  |
| Qualcomm Atheros                | 320       | 25.3%   |
| Realtek Semiconductor           | 240       | 18.97%  |
| Broadcom                        | 128       | 10.12%  |
| Ralink                          | 40        | 3.16%   |
| Broadcom Limited                | 21        | 1.66%   |
| Ralink Technology               | 18        | 1.42%   |
| TP-Link                         | 16        | 1.26%   |
| MediaTek                        | 16        | 1.26%   |
| Dell                            | 4         | 0.32%   |
| Sierra Wireless                 | 3         | 0.24%   |
| Micro Star International        | 3         | 0.24%   |
| Fibocom                         | 3         | 0.24%   |
| D-Link                          | 3         | 0.24%   |
| ASUSTek Computer                | 3         | 0.24%   |
| Qualcomm Atheros Communications | 2         | 0.16%   |
| NetGear                         | 2         | 0.16%   |
| Linksys                         | 2         | 0.16%   |
| Edimax Technology               | 2         | 0.16%   |
| Texas Instruments               | 1         | 0.08%   |
| Tenda                           | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Microsoft                       | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 81        | 6.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 50        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 46        | 3.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 45        | 3.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 44        | 3.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 3.37%   |
| Intel Wireless 7260                                                     | 43        | 3.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 34        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 2.51%   |
| Intel Wireless 7265                                                     | 32        | 2.51%   |
| Intel Wireless 8265 / 8275                                              | 24        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 23        | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 1.64%   |
| Intel Wireless 3165                                                     | 19        | 1.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 18        | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 18        | 1.41%   |
| Intel Wireless 8260                                                     | 18        | 1.41%   |
| Intel Wireless 3160                                                     | 17        | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 17        | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 1.25%   |
| Realtek 802.11n WLAN Adapter                                            | 15        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 1.1%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 14        | 1.1%    |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.02%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 12        | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 12        | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 10        | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 0.78%   |
| Realtek 802.11ac NIC                                                    | 10        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 10        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 10        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 557       | 50.91%  |
| Intel                            | 176       | 16.09%  |
| Qualcomm Atheros                 | 92        | 8.41%   |
| Broadcom                         | 73        | 6.67%   |
| Marvell Technology Group         | 52        | 4.75%   |
| ASIX Electronics                 | 19        | 1.74%   |
| Broadcom Limited                 | 18        | 1.65%   |
| Nvidia                           | 17        | 1.55%   |
| Attansic Technology              | 13        | 1.19%   |
| Samsung Electronics              | 12        | 1.1%    |
| Silicon Integrated Systems [SiS] | 11        | 1.01%   |
| Xiaomi                           | 10        | 0.91%   |
| JMicron Technology               | 7         | 0.64%   |
| VIA Technologies                 | 4         | 0.37%   |
| DisplayLink                      | 4         | 0.37%   |
| OPPO Electronics                 | 3         | 0.27%   |
| Huawei Technologies              | 3         | 0.27%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.18%   |
| Qualcomm                         | 2         | 0.18%   |
| MediaTek                         | 2         | 0.18%   |
| ICS Advent                       | 2         | 0.18%   |
| 3Com                             | 2         | 0.18%   |
| TP-Link                          | 1         | 0.09%   |
| Spreadtrum Communications        | 1         | 0.09%   |
| Research In Motion               | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.09%   |
| Motorola PCS                     | 1         | 0.09%   |
| Microchip Technology             | 1         | 0.09%   |
| LG Electronics                   | 1         | 0.09%   |
| Lab126                           | 1         | 0.09%   |
| Intersil                         | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| Davicom Semiconductor            | 1         | 0.09%   |
| Aquantia                         | 1         | 0.09%   |
| ADMtek                           | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 296       | 26.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 200       | 18.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 31        | 2.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 2.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 24        | 2.19%   |
| Intel 82577LM Gigabit Network Connection                                       | 24        | 2.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 18        | 1.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 13        | 1.19%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 13        | 1.19%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 12        | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 12        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 12        | 1.09%   |
| Intel Ethernet Connection I219-LM                                              | 12        | 1.09%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 12        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12        | 1.09%   |
| Intel Ethernet Connection I217-LM                                              | 11        | 1%      |
| Intel 82567LM Gigabit Network Connection                                       | 10        | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 10        | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 9         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 9         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 0.82%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 9         | 0.82%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 8         | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 8         | 0.73%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 8         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7         | 0.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 7         | 0.64%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 7         | 0.64%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 6         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.55%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 6         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 5         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.46%   |
| Nvidia MCP79 Ethernet                                                          | 5         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1194      | 52.81%  |
| Ethernet | 1034      | 45.73%  |
| Modem    | 33        | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 972       | 76.24%  |
| Ethernet | 303       | 23.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 923       | 73.31%  |
| 1     | 250       | 19.86%  |
| 0     | 75        | 5.96%   |
| 3     | 10        | 0.79%   |
| 4     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 973       | 76.19%  |
| Yes  | 304       | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 272       | 33.33%  |
| Realtek Semiconductor           | 107       | 13.11%  |
| Qualcomm Atheros Communications | 80        | 9.8%    |
| Broadcom                        | 59        | 7.23%   |
| Lite-On Technology              | 44        | 5.39%   |
| Foxconn / Hon Hai               | 41        | 5.02%   |
| IMC Networks                    | 34        | 4.17%   |
| Apple                           | 31        | 3.8%    |
| Hewlett-Packard                 | 28        | 3.43%   |
| Dell                            | 27        | 3.31%   |
| Cambridge Silicon Radio         | 24        | 2.94%   |
| Ralink                          | 18        | 2.21%   |
| Toshiba                         | 12        | 1.47%   |
| Alps Electric                   | 11        | 1.35%   |
| ASUSTek Computer                | 7         | 0.86%   |
| MediaTek                        | 4         | 0.49%   |
| Qcom                            | 3         | 0.37%   |
| Micro Star International        | 3         | 0.37%   |
| Ralink Technology               | 2         | 0.25%   |
| Chicony Electronics             | 2         | 0.25%   |
| Askey Computer                  | 2         | 0.25%   |
| USI                             | 1         | 0.12%   |
| TP-Link                         | 1         | 0.12%   |
| Syntek                          | 1         | 0.12%   |
| Realtek                         | 1         | 0.12%   |
| Integrated System Solution      | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 155       | 18.93%  |
| Realtek Bluetooth Radio                                                             | 74        | 9.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 39        | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 36        | 4.4%    |
| Intel AX201 Bluetooth                                                               | 25        | 3.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 24        | 2.93%   |
| Ralink RT3290 Bluetooth                                                             | 18        | 2.2%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 17        | 2.08%   |
| Apple Bluetooth Host Controller                                                     | 17        | 2.08%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 16        | 1.95%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 1.95%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 16        | 1.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 14        | 1.71%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 1.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 13        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.59%   |
| Intel AX200 Bluetooth                                                               | 13        | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 12        | 1.47%   |
| Realtek RTL8723B Bluetooth                                                          | 10        | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 10        | 1.22%   |
| IMC Networks Bluetooth Device                                                       | 10        | 1.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 10        | 1.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 9         | 1.1%    |
| IMC Networks Bluetooth Radio                                                        | 8         | 0.98%   |
| Lite-On Bluetooth Device                                                            | 7         | 0.85%   |
| Intel Bluetooth Device                                                              | 7         | 0.85%   |
| Dell Wireless 365 Bluetooth                                                         | 7         | 0.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 7         | 0.85%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 0.85%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 0.73%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 6         | 0.73%   |
| Apple Bluetooth HCI                                                                 | 6         | 0.73%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 0.61%   |
| IMC Networks Bluetooth module                                                       | 5         | 0.61%   |
| Dell Wireless 355 Bluetooth                                                         | 5         | 0.61%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 5         | 0.61%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 5         | 0.61%   |
| Qualcomm Atheros Bluetooth                                                          | 4         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 943       | 70.69%  |
| AMD                                          | 241       | 18.07%  |
| Nvidia                                       | 100       | 7.5%    |
| Silicon Integrated Systems [SiS]             | 13        | 0.97%   |
| C-Media Electronics                          | 6         | 0.45%   |
| Logitech                                     | 5         | 0.37%   |
| VIA Technologies                             | 4         | 0.3%    |
| GN Netcom                                    | 4         | 0.3%    |
| Plantronics                                  | 3         | 0.22%   |
| Hewlett-Packard                              | 3         | 0.22%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.07%   |
| Texas Instruments                            | 1         | 0.07%   |
| Realtek Semiconductor                        | 1         | 0.07%   |
| QinHeng Electronics                          | 1         | 0.07%   |
| MosArt Semiconductor                         | 1         | 0.07%   |
| KTMicro                                      | 1         | 0.07%   |
| JMTek                                        | 1         | 0.07%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.07%   |
| EGO SYStems                                  | 1         | 0.07%   |
| Cirrus Logic                                 | 1         | 0.07%   |
| ATI Technologies                             | 1         | 0.07%   |
| ASUSTek Computer                             | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 101       | 6.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 88        | 5.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 83        | 5.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 76        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 75        | 4.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 73        | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 70        | 4.37%   |
| AMD FCH Azalia Controller                                                                         | 68        | 4.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 53        | 3.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 52        | 3.24%   |
| AMD Ryzen HD Audio Controller                                                                     | 51        | 3.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 47        | 2.93%   |
| Intel 8 Series HD Audio Controller                                                                | 46        | 2.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 45        | 2.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 41        | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 40        | 2.5%    |
| AMD Wrestler HDMI Audio                                                                           | 35        | 2.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 35        | 2.18%   |
| AMD High Definition Audio Controller                                                              | 30        | 1.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 27        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 24        | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 23        | 1.43%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 21        | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.12%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 1%      |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 0.75%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 10        | 0.62%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10        | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.56%   |
| AMD Radeon High Definition Audio Controller                                                       | 9         | 0.56%   |
| Intel Jasper Lake HD Audio                                                                        | 8         | 0.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 0.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 210       | 23.1%   |
| SK hynix            | 187       | 20.57%  |
| Unknown             | 147       | 16.17%  |
| Micron Technology   | 83        | 9.13%   |
| Kingston            | 51        | 5.61%   |
| Unknown (ABCD)      | 32        | 3.52%   |
| A-DATA Technology   | 24        | 2.64%   |
| Nanya Technology    | 23        | 2.53%   |
| Elpida              | 23        | 2.53%   |
| Crucial             | 20        | 2.2%    |
| Ramaxel Technology  | 15        | 1.65%   |
| Corsair             | 14        | 1.54%   |
| Smart               | 11        | 1.21%   |
| Unknown             | 7         | 0.77%   |
| Teikon              | 5         | 0.55%   |
| Team                | 4         | 0.44%   |
| Transcend           | 3         | 0.33%   |
| Qimonda             | 3         | 0.33%   |
| PNY                 | 3         | 0.33%   |
| High Bridge         | 3         | 0.33%   |
| G.Skill             | 3         | 0.33%   |
| fef5                | 3         | 0.33%   |
| Apacer              | 3         | 0.33%   |
| Toshiba             | 2         | 0.22%   |
| Timetec             | 2         | 0.22%   |
| Smart Brazil        | 2         | 0.22%   |
| Patriot             | 2         | 0.22%   |
| Novatech            | 2         | 0.22%   |
| ASint Technology    | 2         | 0.22%   |
| 48spaces            | 2         | 0.22%   |
| Wilk                | 1         | 0.11%   |
| Unknown (0xD306)    | 1         | 0.11%   |
| TakeMS              | 1         | 0.11%   |
| Sesame              | 1         | 0.11%   |
| Quadratica          | 1         | 0.11%   |
| PUSKILL             | 1         | 0.11%   |
| Neo Forza           | 1         | 0.11%   |
| Multilaser          | 1         | 0.11%   |
| Kllisre             | 1         | 0.11%   |
| Kingmax             | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 27        | 2.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 17        | 1.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 12        | 1.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 1.22%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 12        | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 9         | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.92%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s          | 9         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 7         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 7         | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.71%   |
| Unknown                                                          | 7         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 6         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 6         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 6         | 0.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 6         | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 5         | 0.51%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.51%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 5         | 0.51%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 5         | 0.51%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 4         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 4         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 4         | 0.41%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 4         | 0.41%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 369       | 46.71%  |
| DDR4    | 187       | 23.67%  |
| DDR2    | 93        | 11.77%  |
| LPDDR4  | 59        | 7.47%   |
| SDRAM   | 26        | 3.29%   |
| LPDDR3  | 13        | 1.65%   |
| DRAM    | 12        | 1.52%   |
| LPDDR5  | 10        | 1.27%   |
| DDR     | 9         | 1.14%   |
| Unknown | 7         | 0.89%   |
| DDR5    | 5         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 715       | 91.43%  |
| Row Of Chips | 44        | 5.63%   |
| DIMM         | 12        | 1.53%   |
| Unknown      | 10        | 1.28%   |
| Chip         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 296       | 33.11%  |
| 8192    | 224       | 25.06%  |
| 2048    | 211       | 23.6%   |
| 1024    | 86        | 9.62%   |
| 16384   | 45        | 5.03%   |
| 512     | 15        | 1.68%   |
| 32768   | 10        | 1.12%   |
| 256     | 3         | 0.34%   |
| 12288   | 1         | 0.11%   |
| 6144    | 1         | 0.11%   |
| 128     | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 229       | 26.78%  |
| 2667    | 79        | 9.24%   |
| 3200    | 77        | 9.01%   |
| 2400    | 76        | 8.89%   |
| 1333    | 56        | 6.55%   |
| 667     | 55        | 6.43%   |
| Unknown | 52        | 6.08%   |
| 1334    | 42        | 4.91%   |
| 1067    | 23        | 2.69%   |
| 1066    | 23        | 2.69%   |
| 2133    | 20        | 2.34%   |
| 533     | 18        | 2.11%   |
| 800     | 17        | 1.99%   |
| 2048    | 14        | 1.64%   |
| 3266    | 12        | 1.4%    |
| 6400    | 8         | 0.94%   |
| 1867    | 8         | 0.94%   |
| 975     | 7         | 0.82%   |
| 4267    | 6         | 0.7%    |
| 4199    | 5         | 0.58%   |
| 1866    | 5         | 0.58%   |
| 8400    | 4         | 0.47%   |
| 5600    | 3         | 0.35%   |
| 4800    | 2         | 0.23%   |
| 4266    | 2         | 0.23%   |
| 3733    | 2         | 0.23%   |
| 2933    | 2         | 0.23%   |
| 7500    | 1         | 0.12%   |
| 5500    | 1         | 0.12%   |
| 1200    | 1         | 0.12%   |
| 933     | 1         | 0.12%   |
| 400     | 1         | 0.12%   |
| 266     | 1         | 0.12%   |
| 2       | 1         | 0.12%   |
| 1       | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 5         | 31.25%  |
| Brother Industries       | 4         | 25%     |
| Samsung Electronics      | 2         | 12.5%   |
| STMicroelectronics       | 1         | 6.25%   |
| Seiko Epson              | 1         | 6.25%   |
| Magic Control Technology | 1         | 6.25%   |
| Lexmark International    | 1         | 6.25%   |
| Canon                    | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| STMicroelectronics USB Printing Support | 1         | 6.25%   |
| Seiko Epson L380 Series                 | 1         | 6.25%   |
| Samsung SCX-4200 series                 | 1         | 6.25%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 6.25%   |
| Magic Control BAY-3U1S1P Parallel Port  | 1         | 6.25%   |
| Lexmark International MS617dn           | 1         | 6.25%   |
| HP LaserJet P1102                       | 1         | 6.25%   |
| HP LaserJet P1005                       | 1         | 6.25%   |
| HP LaserJet 1200                        | 1         | 6.25%   |
| HP Deskjet 3520 series                  | 1         | 6.25%   |
| HP Deskjet 1050 J410                    | 1         | 6.25%   |
| Canon MF3110                            | 1         | 6.25%   |
| Brother PTUSB Printing                  | 1         | 6.25%   |
| Brother PT-2450DX                       | 1         | 6.25%   |
| Brother MFC-7340                        | 1         | 6.25%   |
| Brother DCP-7055W                       | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 500F                                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 274       | 26.68%  |
| Realtek Semiconductor                  | 92        | 8.96%   |
| IMC Networks                           | 78        | 7.59%   |
| Microdia                               | 66        | 6.43%   |
| Bison Electronics                      | 66        | 6.43%   |
| Suyin                                  | 52        | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 4.77%   |
| Sunplus Innovation Technology          | 46        | 4.48%   |
| Quanta                                 | 40        | 3.89%   |
| Alcor Micro                            | 35        | 3.41%   |
| Apple                                  | 32        | 3.12%   |
| Silicon Motion                         | 30        | 2.92%   |
| Syntek                                 | 21        | 2.04%   |
| Lite-On Technology                     | 20        | 1.95%   |
| Ricoh                                  | 15        | 1.46%   |
| Lenovo                                 | 13        | 1.27%   |
| Luxvisions Innotech Limited            | 12        | 1.17%   |
| ALi                                    | 10        | 0.97%   |
| Z-Star Microelectronics                | 7         | 0.68%   |
| icSpring                               | 7         | 0.68%   |
| Logitech                               | 6         | 0.58%   |
| Importek                               | 6         | 0.58%   |
| OmniVision Technologies                | 5         | 0.49%   |
| GEMBIRD                                | 5         | 0.49%   |
| Samsung Electronics                    | 4         | 0.39%   |
| Acer                                   | 4         | 0.39%   |
| Y Media                                | 3         | 0.29%   |
| Genesys Logic                          | 3         | 0.29%   |
| USB Camera CS                          | 2         | 0.19%   |
| SunplusIT                              | 2         | 0.19%   |
| Sonix Technology                       | 2         | 0.19%   |
| Shinetech                              | 2         | 0.19%   |
| DigiTech                               | 2         | 0.19%   |
| WCM_USB                                | 1         | 0.1%    |
| Toshiba                                | 1         | 0.1%    |
| Shine-optics                           | 1         | 0.1%    |
| Novatek Microelectronics               | 1         | 0.1%    |
| Nintendo                               | 1         | 0.1%    |
| Microsoft                              | 1         | 0.1%    |
| LG Electronics                         | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 28        | 2.72%   |
| Chicony HD WebCam                                       | 20        | 1.94%   |
| Alcor Micro USB 2.0 Camera                              | 20        | 1.94%   |
| Realtek Integrated_Webcam_HD                            | 18        | 1.75%   |
| Bison Lenovo EasyCamera                                 | 16        | 1.55%   |
| Chicony HP Truevision HD                                | 15        | 1.46%   |
| Chicony HP Webcam                                       | 12        | 1.17%   |
| Chicony EasyCamera                                      | 12        | 1.17%   |
| Sunplus HD WebCam                                       | 11        | 1.07%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 11        | 1.07%   |
| Chicony VGA Webcam                                      | 11        | 1.07%   |
| Apple FaceTime HD Camera                                | 11        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 10        | 0.97%   |
| Chicony TOSHIBA Web Camera - HD                         | 10        | 0.97%   |
| Chicony HP Truevision HD camera                         | 10        | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 0.97%   |
| Bison EasyCamera                                        | 10        | 0.97%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 9         | 0.87%   |
| IMC Networks Integrated Camera                          | 9         | 0.87%   |
| Chicony USB 2.0 Camera                                  | 9         | 0.87%   |
| Chicony HP HD Webcam                                    | 9         | 0.87%   |
| Bison Integrated Camera                                 | 9         | 0.87%   |
| Apple Built-in iSight                                   | 9         | 0.87%   |
| Realtek USB Camera                                      | 8         | 0.78%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 8         | 0.78%   |
| Sunplus Integrated_Webcam_HD                            | 7         | 0.68%   |
| Realtek EasyCamera                                      | 7         | 0.68%   |
| Microdia Integrated_Webcam_HD                           | 7         | 0.68%   |
| Microdia Integrated Webcam                              | 7         | 0.68%   |
| Microdia 1.3 MPixel Integrated Webcam                   | 7         | 0.68%   |
| Lite-On HP HD Camera                                    | 7         | 0.68%   |
| IMC Networks UVC VGA Webcam                             | 7         | 0.68%   |
| icSpring camera                                         | 7         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 7         | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 6         | 0.58%   |
| Realtek Integrated Webcam HD                            | 6         | 0.58%   |
| Realtek Acer 640 x 480 laptop camera                    | 6         | 0.58%   |
| Quanta HP HD Camera                                     | 6         | 0.58%   |
| Lenovo Integrated Webcam                                | 6         | 0.58%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 6         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 57        | 44.88%  |
| AuthenTec                  | 20        | 15.75%  |
| Upek                       | 14        | 11.02%  |
| Synaptics                  | 10        | 7.87%   |
| STMicroelectronics         | 9         | 7.09%   |
| Shenzhen Goodix Technology | 9         | 7.09%   |
| LighTuning Technology      | 4         | 3.15%   |
| Samsung Electronics        | 2         | 1.57%   |
| Elan Microelectronics      | 2         | 1.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 12.6%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 10.24%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 7.09%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 7.09%   |
| AuthenTec AES2810                                                          | 7         | 5.51%   |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 4.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 4.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.15%   |
| AuthenTec AES1600                                                          | 4         | 3.15%   |
| Validity Sensors VFS491                                                    | 3         | 2.36%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 2.36%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.57%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 1.57%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.57%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.57%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.57%   |
| Samsung Fingerprint Device                                                 | 2         | 1.57%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.79%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.79%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.79%   |
| Synaptics WBDI                                                             | 1         | 0.79%   |
| Synaptics TouchPad                                                         | 1         | 0.79%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.79%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.79%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 29        | 49.15%  |
| Alcor Micro           | 14        | 23.73%  |
| O2 Micro              | 9         | 15.25%  |
| Upek                  | 2         | 3.39%   |
| Lenovo                | 2         | 3.39%   |
| Gemalto (was Gemplus) | 2         | 3.39%   |
| Realtek Semiconductor | 1         | 1.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 22.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 20.34%  |
| Broadcom 5880                                                                | 10        | 16.95%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 10.17%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 8.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 5.08%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.39%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.39%   |
| Broadcom 58200                                                               | 2         | 3.39%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.69%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 1.69%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.69%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 862       | 68.2%   |
| 1     | 333       | 26.34%  |
| 2     | 57        | 4.51%   |
| 3     | 9         | 0.71%   |
| 4     | 3         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 155       | 32.43%  |
| Fingerprint reader       | 125       | 26.15%  |
| Chipcard                 | 55        | 11.51%  |
| Net/wireless             | 42        | 8.79%   |
| Bluetooth                | 29        | 6.07%   |
| Camera                   | 17        | 3.56%   |
| Storage                  | 12        | 2.51%   |
| Modem                    | 11        | 2.3%    |
| Multimedia controller    | 8         | 1.67%   |
| Net/ethernet             | 5         | 1.05%   |
| Flash memory             | 5         | 1.05%   |
| Communication controller | 5         | 1.05%   |
| Sound                    | 3         | 0.63%   |
| Dvb card                 | 3         | 0.63%   |
| Network                  | 2         | 0.42%   |
| Card reader              | 1         | 0.21%   |


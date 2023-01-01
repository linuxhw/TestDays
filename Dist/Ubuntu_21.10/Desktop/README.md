Ubuntu 21.10 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 962

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0C3YXR A01                  | [95fbd0e6b4](https://linux-hardware.org/?probe=95fbd0e6b4) | Nov 30, 2022 |
| ASUSTek       | H81M-V3                     | [f6be8306c7](https://linux-hardware.org/?probe=f6be8306c7) | Nov 22, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | [5468f11c01](https://linux-hardware.org/?probe=5468f11c01) | Nov 15, 2022 |
| ASUSTek       | P5Q-E                       | [a37be95e80](https://linux-hardware.org/?probe=a37be95e80) | Nov 10, 2022 |
| Intel         | H61                         | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | [b50165d9c9](https://linux-hardware.org/?probe=b50165d9c9) | Oct 11, 2022 |
| HP            | 3398                        | [8ef4543254](https://linux-hardware.org/?probe=8ef4543254) | Sep 30, 2022 |
| ASRock        | 960GM-VGS3 FX               | [45bf4d54bf](https://linux-hardware.org/?probe=45bf4d54bf) | Sep 26, 2022 |
| HP            | 3398                        | [9add0a56b5](https://linux-hardware.org/?probe=9add0a56b5) | Sep 17, 2022 |
| ASUSTek       | A68HM-PLUS                  | [f585d57226](https://linux-hardware.org/?probe=f585d57226) | Aug 27, 2022 |
| ASUSTek       | H61M-K                      | [1f4f742288](https://linux-hardware.org/?probe=1f4f742288) | Aug 23, 2022 |
| ASRock        | H67M                        | [c09d83ca79](https://linux-hardware.org/?probe=c09d83ca79) | Aug 13, 2022 |
| Dell          | 0J3C2F A00                  | [dc5cc9ef0c](https://linux-hardware.org/?probe=dc5cc9ef0c) | Aug 10, 2022 |
| Dell          | 0J3C2F A00                  | [650bca22c4](https://linux-hardware.org/?probe=650bca22c4) | Aug 10, 2022 |
| MSI           | Z97 GAMING 5                | [a834f9f0ed](https://linux-hardware.org/?probe=a834f9f0ed) | Jul 28, 2022 |
| Dell          | 0GY6Y8 A03                  | [88d49ee4d4](https://linux-hardware.org/?probe=88d49ee4d4) | Jul 21, 2022 |
| Dell          | 0GY6Y8 A03                  | [636819dfaf](https://linux-hardware.org/?probe=636819dfaf) | Jul 21, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d5ebe1a737](https://linux-hardware.org/?probe=d5ebe1a737) | Jul 20, 2022 |
| Intel         | H55                         | [b58f7300e1](https://linux-hardware.org/?probe=b58f7300e1) | Jul 18, 2022 |
| MSI           | B550M-A PRO                 | [15790ffff1](https://linux-hardware.org/?probe=15790ffff1) | Jul 16, 2022 |
| Intel         | H55                         | [f8e7b20a53](https://linux-hardware.org/?probe=f8e7b20a53) | Jul 14, 2022 |
| Intel         | H55                         | [b199ed9707](https://linux-hardware.org/?probe=b199ed9707) | Jul 14, 2022 |
| ASRock        | J5005-ITX                   | [1f6eafefae](https://linux-hardware.org/?probe=1f6eafefae) | Jul 11, 2022 |
| Biostar       | TZ77A                       | [ee21238738](https://linux-hardware.org/?probe=ee21238738) | Jul 11, 2022 |
| MSI           | H110M GAMING                | [92f54d6efd](https://linux-hardware.org/?probe=92f54d6efd) | Jul 09, 2022 |
| Dell          | 0M858N A01                  | [36aca635a8](https://linux-hardware.org/?probe=36aca635a8) | Jul 06, 2022 |
| Dell          | 0GM819                      | [a366983f6a](https://linux-hardware.org/?probe=a366983f6a) | Jul 06, 2022 |
| Dell          | 0GM819                      | [78e233e42f](https://linux-hardware.org/?probe=78e233e42f) | Jul 06, 2022 |
| ASRock        | B450M Gaming                | [7da921047e](https://linux-hardware.org/?probe=7da921047e) | Jul 05, 2022 |
| Dell          | 0GDG8Y A00                  | [4ccd9d239d](https://linux-hardware.org/?probe=4ccd9d239d) | Jun 30, 2022 |
| Unknown       | 1.0                         | [340f931c7f](https://linux-hardware.org/?probe=340f931c7f) | Jun 26, 2022 |
| HP            | 8054                        | [82dd44f05f](https://linux-hardware.org/?probe=82dd44f05f) | Jun 26, 2022 |
| MSI           | Z97 GAMING 5                | [473a0abca4](https://linux-hardware.org/?probe=473a0abca4) | Jun 25, 2022 |
| Foxconn       | 2ADA                        | [d720505734](https://linux-hardware.org/?probe=d720505734) | Jun 20, 2022 |
| Foxconn       | 2ADA                        | [c2b0898c1a](https://linux-hardware.org/?probe=c2b0898c1a) | Jun 20, 2022 |
| Intel         | X79 V2.72B                  | [fbd8e560b4](https://linux-hardware.org/?probe=fbd8e560b4) | Jun 18, 2022 |
| Unknown       | 1.0                         | [de849825ee](https://linux-hardware.org/?probe=de849825ee) | Jun 14, 2022 |
| HP            | 8906 SMVB                   | [772043704c](https://linux-hardware.org/?probe=772043704c) | Jun 13, 2022 |
| Unknown       | X99-GT                      | [0e1115fdc9](https://linux-hardware.org/?probe=0e1115fdc9) | Jun 12, 2022 |
| ASUSTek       | Q87M-E                      | [4b3fedcb8a](https://linux-hardware.org/?probe=4b3fedcb8a) | Jun 06, 2022 |
| Dell          | 0GDG8Y A00                  | [00a4463324](https://linux-hardware.org/?probe=00a4463324) | Jun 04, 2022 |
| HP            | 1632                        | [4f7993cf34](https://linux-hardware.org/?probe=4f7993cf34) | Jun 01, 2022 |
| HP            | 1632                        | [9e69c11025](https://linux-hardware.org/?probe=9e69c11025) | Jun 01, 2022 |
| Gigabyte      | H97N-WIFI                   | [031d4a8f7f](https://linux-hardware.org/?probe=031d4a8f7f) | May 29, 2022 |
| Minix         | NEO Z83-4A V1.1             | [e828d9bd38](https://linux-hardware.org/?probe=e828d9bd38) | May 29, 2022 |
| HP            | 8767 A                      | [553a8de02a](https://linux-hardware.org/?probe=553a8de02a) | May 26, 2022 |
| ASUSTek       | P8Z77-V LX                  | [5f505dd767](https://linux-hardware.org/?probe=5f505dd767) | May 26, 2022 |
| Dell          | 0RF703                      | [228efad4f1](https://linux-hardware.org/?probe=228efad4f1) | May 25, 2022 |
| Lenovo        | 313A NOK                    | [9df6ec850c](https://linux-hardware.org/?probe=9df6ec850c) | May 24, 2022 |
| ASUSTek       | M5A78L-M LX                 | [6c5438b4b4](https://linux-hardware.org/?probe=6c5438b4b4) | May 24, 2022 |
| ASRock        | B365M Pro4-F                | [4cbbeda22c](https://linux-hardware.org/?probe=4cbbeda22c) | May 22, 2022 |
| ASUSTek       | P8H61-I                     | [2b589c0488](https://linux-hardware.org/?probe=2b589c0488) | May 20, 2022 |
| MSI           | B150M MORTAR                | [a2124255a2](https://linux-hardware.org/?probe=a2124255a2) | May 17, 2022 |
| Gigabyte      | Z690 UD DDR4                | [858abd9c59](https://linux-hardware.org/?probe=858abd9c59) | May 15, 2022 |
| MSI           | Z97 GAMING 5                | [e395176aad](https://linux-hardware.org/?probe=e395176aad) | May 13, 2022 |
| Fujitsu Si... | D2817-A1 S26361-D2817-A1    | [8dace3d601](https://linux-hardware.org/?probe=8dace3d601) | May 12, 2022 |
| ASRock        | 960GM/U3S3 FX               | [06dfd102d5](https://linux-hardware.org/?probe=06dfd102d5) | May 11, 2022 |
| ASUSTek       | M4A79T Deluxe               | [92e7a68e33](https://linux-hardware.org/?probe=92e7a68e33) | May 09, 2022 |
| ASUSTek       | Z87-A                       | [ecff4161ad](https://linux-hardware.org/?probe=ecff4161ad) | May 08, 2022 |
| Gigabyte      | G31M-S2L                    | [78b1868a67](https://linux-hardware.org/?probe=78b1868a67) | May 08, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | Z590-A PRO                  | [f4f7118a5a](https://linux-hardware.org/?probe=f4f7118a5a) | May 07, 2022 |
| MSI           | Z590-A PRO                  | [68130c42bb](https://linux-hardware.org/?probe=68130c42bb) | May 07, 2022 |
| Intel         | X79 V2.72B                  | [87dd767f71](https://linux-hardware.org/?probe=87dd767f71) | May 05, 2022 |
| HP            | 0B54h D                     | [a90845be26](https://linux-hardware.org/?probe=a90845be26) | May 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [04c7c1f7f4](https://linux-hardware.org/?probe=04c7c1f7f4) | May 02, 2022 |
| HP            | 0B54h D                     | [2023024a05](https://linux-hardware.org/?probe=2023024a05) | Apr 29, 2022 |
| HP            | 158A                        | [11b5037897](https://linux-hardware.org/?probe=11b5037897) | Apr 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [b07e1c97aa](https://linux-hardware.org/?probe=b07e1c97aa) | Apr 29, 2022 |
| Acer          | Predator G3620              | [556a67d50d](https://linux-hardware.org/?probe=556a67d50d) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | [5e6c23c3b5](https://linux-hardware.org/?probe=5e6c23c3b5) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | [f6df392394](https://linux-hardware.org/?probe=f6df392394) | Apr 27, 2022 |
| NF541         | 1.0                         | [c0999696b6](https://linux-hardware.org/?probe=c0999696b6) | Apr 27, 2022 |
| Foxconn       | 2AB1                        | [2d6ef9c4b6](https://linux-hardware.org/?probe=2d6ef9c4b6) | Apr 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5721b7c107](https://linux-hardware.org/?probe=5721b7c107) | Apr 27, 2022 |
| Gigabyte      | F2A78M-HD2                  | [454d879501](https://linux-hardware.org/?probe=454d879501) | Apr 26, 2022 |
| Unknown       | Unknown                     | [f67ff826d9](https://linux-hardware.org/?probe=f67ff826d9) | Apr 25, 2022 |
| HP            | 3397                        | [754e703cc5](https://linux-hardware.org/?probe=754e703cc5) | Apr 25, 2022 |
| ASUSTek       | P8H61-M LX2                 | [a60c0bf48d](https://linux-hardware.org/?probe=a60c0bf48d) | Apr 24, 2022 |
| Dell          | 0WMJ54 A01                  | [2e3ae2a664](https://linux-hardware.org/?probe=2e3ae2a664) | Apr 24, 2022 |
| ASUSTek       | P5GD1                       | [11b7aa3465](https://linux-hardware.org/?probe=11b7aa3465) | Apr 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [88318f48e8](https://linux-hardware.org/?probe=88318f48e8) | Apr 24, 2022 |
| Gigabyte      | Z370P D3-CF                 | [df7e090d9c](https://linux-hardware.org/?probe=df7e090d9c) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [20d9884cb6](https://linux-hardware.org/?probe=20d9884cb6) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [dac092d7bc](https://linux-hardware.org/?probe=dac092d7bc) | Apr 24, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [347ded3d71](https://linux-hardware.org/?probe=347ded3d71) | Apr 23, 2022 |
| MSI           | Z590-A PRO                  | [5b78ae1e5e](https://linux-hardware.org/?probe=5b78ae1e5e) | Apr 23, 2022 |
| Seco          | C40 C                       | [3e1fffcda7](https://linux-hardware.org/?probe=3e1fffcda7) | Apr 22, 2022 |
| ASUSTek       | P7H55-M BR                  | [e3c7a6ade9](https://linux-hardware.org/?probe=e3c7a6ade9) | Apr 22, 2022 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [18f00ab5d9](https://linux-hardware.org/?probe=18f00ab5d9) | Apr 22, 2022 |
| ASUSTek       | P5QC                        | [63f53fd6cb](https://linux-hardware.org/?probe=63f53fd6cb) | Apr 22, 2022 |
| Gigabyte      | Z590 VISION G               | [597940fbe8](https://linux-hardware.org/?probe=597940fbe8) | Apr 22, 2022 |
| AMI           | Cherry Trail CR             | [61d45f784c](https://linux-hardware.org/?probe=61d45f784c) | Apr 21, 2022 |
| MSI           | B550-A PRO                  | [212c60ebc5](https://linux-hardware.org/?probe=212c60ebc5) | Apr 21, 2022 |
| ASUSTek       | H97-PLUS                    | [6495b55188](https://linux-hardware.org/?probe=6495b55188) | Apr 21, 2022 |
| Unknown       | Unknown                     | [80099b4b7f](https://linux-hardware.org/?probe=80099b4b7f) | Apr 21, 2022 |
| MSI           | Z97 GAMING 5                | [180e1b4ab7](https://linux-hardware.org/?probe=180e1b4ab7) | Apr 21, 2022 |
| HP            | 2AF7                        | [0a92bfa831](https://linux-hardware.org/?probe=0a92bfa831) | Apr 21, 2022 |
| Dell          | 0200DY A01                  | [5cb77cb68e](https://linux-hardware.org/?probe=5cb77cb68e) | Apr 20, 2022 |
| HP            | 3048h                       | [b35df4ed74](https://linux-hardware.org/?probe=b35df4ed74) | Apr 20, 2022 |
| MSI           | H110M PRO-VD PLUS           | [37d0f0bb74](https://linux-hardware.org/?probe=37d0f0bb74) | Apr 20, 2022 |
| MSI           | B450 TOMAHAWK               | [4c46fa8a5b](https://linux-hardware.org/?probe=4c46fa8a5b) | Apr 19, 2022 |
| Medion        | H110H4-EM                   | [358d943521](https://linux-hardware.org/?probe=358d943521) | Apr 19, 2022 |
| ASRock        | Z170 Gaming K4              | [81e06a1dcb](https://linux-hardware.org/?probe=81e06a1dcb) | Apr 18, 2022 |
| MSI           | Z87-GD65 GAMING             | [5bfeeef88e](https://linux-hardware.org/?probe=5bfeeef88e) | Apr 18, 2022 |
| MSI           | X470 GAMING PLUS            | [2ddbae278a](https://linux-hardware.org/?probe=2ddbae278a) | Apr 18, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [028f7e340b](https://linux-hardware.org/?probe=028f7e340b) | Apr 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [98637b4cf2](https://linux-hardware.org/?probe=98637b4cf2) | Apr 18, 2022 |
| MSI           | B450-A PRO MAX              | [9ce44bf30d](https://linux-hardware.org/?probe=9ce44bf30d) | Apr 17, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [d921190f7e](https://linux-hardware.org/?probe=d921190f7e) | Apr 17, 2022 |
| HP            | 339A                        | [7949378026](https://linux-hardware.org/?probe=7949378026) | Apr 17, 2022 |
| Gigabyte      | 970A-UD3                    | [7128f5f2b4](https://linux-hardware.org/?probe=7128f5f2b4) | Apr 17, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [a016ec1bce](https://linux-hardware.org/?probe=a016ec1bce) | Apr 16, 2022 |
| ASUSTek       | B150-PRO                    | [1ebe5f0e99](https://linux-hardware.org/?probe=1ebe5f0e99) | Apr 15, 2022 |
| Lenovo        | SDK0J40700 WIN              | [142a0092f1](https://linux-hardware.org/?probe=142a0092f1) | Apr 15, 2022 |
| MSI           | Z87-GD65 GAMING             | [8c57fd797b](https://linux-hardware.org/?probe=8c57fd797b) | Apr 15, 2022 |
| Medion        | H110H4-EM                   | [d4c3d27956](https://linux-hardware.org/?probe=d4c3d27956) | Apr 15, 2022 |
| Unknown       | Unknown                     | [6476542bc7](https://linux-hardware.org/?probe=6476542bc7) | Apr 14, 2022 |
| Huanan        | X99-AD3 V4.0                | [186bccefad](https://linux-hardware.org/?probe=186bccefad) | Apr 14, 2022 |
| MSI           | H81M-P33                    | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI           | Z390-A PRO                  | [a642b9ec3a](https://linux-hardware.org/?probe=a642b9ec3a) | Apr 14, 2022 |
| HP            | 158B                        | [01b455c74a](https://linux-hardware.org/?probe=01b455c74a) | Apr 14, 2022 |
| MSI           | 970A-G43 PLUS               | [9200891771](https://linux-hardware.org/?probe=9200891771) | Apr 14, 2022 |
| Dell          | 0GN6JF A01                  | [c215aa8e06](https://linux-hardware.org/?probe=c215aa8e06) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2a5f0afcc8](https://linux-hardware.org/?probe=2a5f0afcc8) | Apr 14, 2022 |
| ASUSTek       | M4A78T-E                    | [3cbf78454e](https://linux-hardware.org/?probe=3cbf78454e) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1a7a8bf92e](https://linux-hardware.org/?probe=1a7a8bf92e) | Apr 13, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [a676bf83eb](https://linux-hardware.org/?probe=a676bf83eb) | Apr 13, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [c28c553d03](https://linux-hardware.org/?probe=c28c553d03) | Apr 13, 2022 |
| ASUSTek       | H81M-E                      | [b26d147ae3](https://linux-hardware.org/?probe=b26d147ae3) | Apr 13, 2022 |
| ECS           | H81H3-I                     | [1bf6cc284c](https://linux-hardware.org/?probe=1bf6cc284c) | Apr 13, 2022 |
| ASUSTek       | PRIME Z370-P                | [3b91a78742](https://linux-hardware.org/?probe=3b91a78742) | Apr 13, 2022 |
| Lenovo        | NOK                         | [f99d93fc1e](https://linux-hardware.org/?probe=f99d93fc1e) | Apr 13, 2022 |
| MSI           | X470 GAMING PRO             | [1ba8ee75be](https://linux-hardware.org/?probe=1ba8ee75be) | Apr 13, 2022 |
| MSI           | Indio                       | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | [9d42acb7dc](https://linux-hardware.org/?probe=9d42acb7dc) | Apr 13, 2022 |
| Foxconn       | 2ABF                        | [6267f2f88d](https://linux-hardware.org/?probe=6267f2f88d) | Apr 13, 2022 |
| MSI           | 970A-G43 PLUS               | [5a0a8374bd](https://linux-hardware.org/?probe=5a0a8374bd) | Apr 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [8c88f1c50a](https://linux-hardware.org/?probe=8c88f1c50a) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [97bd95a7bb](https://linux-hardware.org/?probe=97bd95a7bb) | Apr 12, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | [ceb55f32d7](https://linux-hardware.org/?probe=ceb55f32d7) | Apr 12, 2022 |
| ASUSTek       | PRIME Z270-A                | [c31ef29891](https://linux-hardware.org/?probe=c31ef29891) | Apr 11, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [71adeab793](https://linux-hardware.org/?probe=71adeab793) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [63df7871b0](https://linux-hardware.org/?probe=63df7871b0) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [6884809c79](https://linux-hardware.org/?probe=6884809c79) | Apr 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [1345425e85](https://linux-hardware.org/?probe=1345425e85) | Apr 10, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [50cfb4d530](https://linux-hardware.org/?probe=50cfb4d530) | Apr 09, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [648d7a9a57](https://linux-hardware.org/?probe=648d7a9a57) | Apr 09, 2022 |
| Medion        | TJ4125                      | [4541511f38](https://linux-hardware.org/?probe=4541511f38) | Apr 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [c0d7bcd89b](https://linux-hardware.org/?probe=c0d7bcd89b) | Apr 08, 2022 |
| ASUSTek       | PRIME B450M-A II            | [3d20e0e751](https://linux-hardware.org/?probe=3d20e0e751) | Apr 08, 2022 |
| ASUSTek       | PRIME B450M-A II            | [61d0948083](https://linux-hardware.org/?probe=61d0948083) | Apr 08, 2022 |
| ASUSTek       | H170 PRO GAMING             | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| HP            | 1998                        | [0ed4dbebcb](https://linux-hardware.org/?probe=0ed4dbebcb) | Apr 08, 2022 |
| MSI           | Z370-A PRO                  | [52f833f67d](https://linux-hardware.org/?probe=52f833f67d) | Apr 07, 2022 |
| ASUSTek       | Z97-K                       | [6451bf5197](https://linux-hardware.org/?probe=6451bf5197) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | [c610098aac](https://linux-hardware.org/?probe=c610098aac) | Apr 07, 2022 |
| Dell          | 0VD5HY A04                  | [8672ef6c18](https://linux-hardware.org/?probe=8672ef6c18) | Apr 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| Dell          | 0RY007                      | [5ce0e84669](https://linux-hardware.org/?probe=5ce0e84669) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | [4440e8ed7c](https://linux-hardware.org/?probe=4440e8ed7c) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c1e66c6b66](https://linux-hardware.org/?probe=c1e66c6b66) | Apr 06, 2022 |
| Dell          | 0JP3NX A01                  | [159b7c81e0](https://linux-hardware.org/?probe=159b7c81e0) | Apr 06, 2022 |
| ASUSTek       | Z97-K                       | [605aa4f068](https://linux-hardware.org/?probe=605aa4f068) | Apr 06, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [ef16b5252f](https://linux-hardware.org/?probe=ef16b5252f) | Apr 06, 2022 |
| Biostar       | H110MHC                     | [09715fbaf2](https://linux-hardware.org/?probe=09715fbaf2) | Apr 05, 2022 |
| Gigabyte      | B75M-D3H                    | [79aee125b7](https://linux-hardware.org/?probe=79aee125b7) | Apr 05, 2022 |
| ASUSTek       | Z87-PRO                     | [ca1d842423](https://linux-hardware.org/?probe=ca1d842423) | Apr 04, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [7e44cf1d2c](https://linux-hardware.org/?probe=7e44cf1d2c) | Apr 04, 2022 |
| Biostar       | B350GT5                     | [b8aba828d1](https://linux-hardware.org/?probe=b8aba828d1) | Apr 04, 2022 |
| MSI           | P45 Neo-F                   | [8f1c621674](https://linux-hardware.org/?probe=8f1c621674) | Apr 04, 2022 |
| Gigabyte      | F2A68HM-H                   | [bd5be9b918](https://linux-hardware.org/?probe=bd5be9b918) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M LX                 | [2bbc147beb](https://linux-hardware.org/?probe=2bbc147beb) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [d268200bd2](https://linux-hardware.org/?probe=d268200bd2) | Apr 03, 2022 |
| HP            | 0AA8h                       | [f599c9dc5b](https://linux-hardware.org/?probe=f599c9dc5b) | Apr 03, 2022 |
| Packard Be... | M2N-NM                      | [7231602b33](https://linux-hardware.org/?probe=7231602b33) | Apr 03, 2022 |
| Gigabyte      | H61M-D2-B3                  | [d95c37955a](https://linux-hardware.org/?probe=d95c37955a) | Apr 03, 2022 |
| Alienware     | 07W25T A01                  | [e7280e6116](https://linux-hardware.org/?probe=e7280e6116) | Apr 03, 2022 |
| ASUSTek       | Maximus VI HERO             | [bf16aedd75](https://linux-hardware.org/?probe=bf16aedd75) | Apr 03, 2022 |
| ASUSTek       | H170 PRO GAMING             | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [53df2c9f1a](https://linux-hardware.org/?probe=53df2c9f1a) | Apr 03, 2022 |
| ASUSTek       | Maximus VI HERO             | [3c0ef3960c](https://linux-hardware.org/?probe=3c0ef3960c) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a8425c2df8](https://linux-hardware.org/?probe=a8425c2df8) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | [6655399773](https://linux-hardware.org/?probe=6655399773) | Apr 02, 2022 |
| Gigabyte      | H87-HD3                     | [0a4247912e](https://linux-hardware.org/?probe=0a4247912e) | Apr 02, 2022 |
| ASUSTek       | PB50                        | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [68483bc13a](https://linux-hardware.org/?probe=68483bc13a) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Unknown       | HX90                        | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| ASRock        | B85M-ITX                    | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| Unknown       | HX90                        | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [3ac2dfc728](https://linux-hardware.org/?probe=3ac2dfc728) | Apr 01, 2022 |
| BESSTAR Te... | JB9                         | [ad56d40441](https://linux-hardware.org/?probe=ad56d40441) | Mar 31, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [ff4a7768d2](https://linux-hardware.org/?probe=ff4a7768d2) | Mar 31, 2022 |
| Positivo      | POS-PIG41BO                 | [865f71148c](https://linux-hardware.org/?probe=865f71148c) | Mar 31, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [f265f5e3b1](https://linux-hardware.org/?probe=f265f5e3b1) | Mar 31, 2022 |
| MSI           | 770-C45                     | [f77be5fea4](https://linux-hardware.org/?probe=f77be5fea4) | Mar 30, 2022 |
| ASUSTek       | PRIME Z270-A                | [e8bc504167](https://linux-hardware.org/?probe=e8bc504167) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [69e5ad3c75](https://linux-hardware.org/?probe=69e5ad3c75) | Mar 30, 2022 |
| HP            | 0AA8h                       | [374efb9d66](https://linux-hardware.org/?probe=374efb9d66) | Mar 29, 2022 |
| ASRock        | B75M-GL R2.0                | [b951c3cc48](https://linux-hardware.org/?probe=b951c3cc48) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| Gigabyte      | X99-UD4-CF                  | [2a9a30b011](https://linux-hardware.org/?probe=2a9a30b011) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| Dell          | 0F3KHR A00                  | [edee0670e3](https://linux-hardware.org/?probe=edee0670e3) | Mar 28, 2022 |
| ASRock        | B365M Pro4                  | [6920de7907](https://linux-hardware.org/?probe=6920de7907) | Mar 28, 2022 |
| Google        | Guado                       | [b9e3791c3d](https://linux-hardware.org/?probe=b9e3791c3d) | Mar 28, 2022 |
| Dell          | 0VD92X A00                  | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [6f2a0d378d](https://linux-hardware.org/?probe=6f2a0d378d) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| Dell          | 0F3KHR A00                  | [17a15d4648](https://linux-hardware.org/?probe=17a15d4648) | Mar 27, 2022 |
| HP            | 18E7                        | [18decc1420](https://linux-hardware.org/?probe=18decc1420) | Mar 27, 2022 |
| Dell          | 0VD92X A00                  | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| ASRock        | AMCP7AION-HT                | [23f929c975](https://linux-hardware.org/?probe=23f929c975) | Mar 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8cdf89a270](https://linux-hardware.org/?probe=8cdf89a270) | Mar 27, 2022 |
| MSI           | PRO Z690-A WIFI             | [f4e7cba010](https://linux-hardware.org/?probe=f4e7cba010) | Mar 27, 2022 |
| Dell          | 0F3KHR A00                  | [5019c3645d](https://linux-hardware.org/?probe=5019c3645d) | Mar 26, 2022 |
| ASRock        | H110M-HDS                   | [4d571e07cc](https://linux-hardware.org/?probe=4d571e07cc) | Mar 25, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [d975f1b581](https://linux-hardware.org/?probe=d975f1b581) | Mar 25, 2022 |
| MSI           | B550M PRO-VDH               | [acd7be917a](https://linux-hardware.org/?probe=acd7be917a) | Mar 25, 2022 |
| HP            | 3398                        | [b84864ecc4](https://linux-hardware.org/?probe=b84864ecc4) | Mar 25, 2022 |
| HP            | 82FF                        | [cb8d5d95bb](https://linux-hardware.org/?probe=cb8d5d95bb) | Mar 24, 2022 |
| Gigabyte      | H270-Gaming 3               | [90ce7b8310](https://linux-hardware.org/?probe=90ce7b8310) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4c70e2fa37](https://linux-hardware.org/?probe=4c70e2fa37) | Mar 24, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4bc13fce28](https://linux-hardware.org/?probe=4bc13fce28) | Mar 24, 2022 |
| HP            | 8643 SMVB                   | [3b5e516908](https://linux-hardware.org/?probe=3b5e516908) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd0e0e448b](https://linux-hardware.org/?probe=bd0e0e448b) | Mar 23, 2022 |
| Gigabyte      | X79-UD3                     | [6a88c14776](https://linux-hardware.org/?probe=6a88c14776) | Mar 23, 2022 |
| Gigabyte      | GA-73PVM-S2H                | [ac9f20a77c](https://linux-hardware.org/?probe=ac9f20a77c) | Mar 23, 2022 |
| HP            | 18E9                        | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| HP            | ProLiant ML310e Gen8        | [db93476384](https://linux-hardware.org/?probe=db93476384) | Mar 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| ASRock        | X370 Killer SLI             | [8f2239d221](https://linux-hardware.org/?probe=8f2239d221) | Mar 22, 2022 |
| Dell          | 04GJJT A00                  | [0b2a7b240f](https://linux-hardware.org/?probe=0b2a7b240f) | Mar 22, 2022 |
| ASUSTek       | Q87M-E                      | [42e766a482](https://linux-hardware.org/?probe=42e766a482) | Mar 22, 2022 |
| HP            | ProLiant ML310e Gen8        | [c8afce0622](https://linux-hardware.org/?probe=c8afce0622) | Mar 22, 2022 |
| Supermicro    | C2SBC-Q                     | [338275254e](https://linux-hardware.org/?probe=338275254e) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| HP            | 8054                        | [38288fadf8](https://linux-hardware.org/?probe=38288fadf8) | Mar 21, 2022 |
| Dell          | 04GJJT A00                  | [b94dc1035d](https://linux-hardware.org/?probe=b94dc1035d) | Mar 21, 2022 |
| MSI           | A320M-A PRO MAX             | [7504eeaaa1](https://linux-hardware.org/?probe=7504eeaaa1) | Mar 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d98f42c86b](https://linux-hardware.org/?probe=d98f42c86b) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [0008f2b843](https://linux-hardware.org/?probe=0008f2b843) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [34d7600473](https://linux-hardware.org/?probe=34d7600473) | Mar 20, 2022 |
| Unknown       | Unknown                     | [4f882f4865](https://linux-hardware.org/?probe=4f882f4865) | Mar 20, 2022 |
| Biostar       | G41D3+                      | [8d6a4e54b1](https://linux-hardware.org/?probe=8d6a4e54b1) | Mar 20, 2022 |
| Gigabyte      | Z170-Gaming K3-CF           | [fb3415d61d](https://linux-hardware.org/?probe=fb3415d61d) | Mar 19, 2022 |
| Dell          | 0VRWRC A01                  | [48a73bd70f](https://linux-hardware.org/?probe=48a73bd70f) | Mar 19, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [a763963402](https://linux-hardware.org/?probe=a763963402) | Mar 19, 2022 |
| Gigabyte      | Z170-Gaming K3-CF           | [f7c5c30266](https://linux-hardware.org/?probe=f7c5c30266) | Mar 18, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| Dell          | 0YNVJG A01                  | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| Dell          | 0VD92X A00                  | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| ASUSTek       | P5E                         | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| HP            | 3398                        | [5f018df1dd](https://linux-hardware.org/?probe=5f018df1dd) | Mar 17, 2022 |
| Medion        | TJ4125                      | [d8535f37cc](https://linux-hardware.org/?probe=d8535f37cc) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b68926de8f](https://linux-hardware.org/?probe=b68926de8f) | Mar 17, 2022 |
| ASUSTek       | M5A78L/USB3                 | [15a04898a4](https://linux-hardware.org/?probe=15a04898a4) | Mar 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [42ce115c70](https://linux-hardware.org/?probe=42ce115c70) | Mar 17, 2022 |
| Gigabyte      | H110M-S2H-CF                | [d62422fe16](https://linux-hardware.org/?probe=d62422fe16) | Mar 17, 2022 |
| ECS           | H110I-C4P                   | [de40e2a12d](https://linux-hardware.org/?probe=de40e2a12d) | Mar 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2b4181439](https://linux-hardware.org/?probe=d2b4181439) | Mar 16, 2022 |
| MSI           | A320M-A PRO MAX             | [dceb87e505](https://linux-hardware.org/?probe=dceb87e505) | Mar 16, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [0d0e297d92](https://linux-hardware.org/?probe=0d0e297d92) | Mar 16, 2022 |
| ASUSTek       | M5A78L-M LX                 | [33a4b92bf4](https://linux-hardware.org/?probe=33a4b92bf4) | Mar 16, 2022 |
| ASUSTek       | M5A99X EVO                  | [117ebec9fc](https://linux-hardware.org/?probe=117ebec9fc) | Mar 15, 2022 |
| Dell          | 0XHGV1 A00                  | [605d83cd15](https://linux-hardware.org/?probe=605d83cd15) | Mar 15, 2022 |
| ASRock        | X300M-STX                   | [5b18945822](https://linux-hardware.org/?probe=5b18945822) | Mar 15, 2022 |
| Gigabyte      | Z690 UD DDR4                | [e2c193b366](https://linux-hardware.org/?probe=e2c193b366) | Mar 15, 2022 |
| ASUSTek       | M5A78L-M LX                 | [3eb18e0c33](https://linux-hardware.org/?probe=3eb18e0c33) | Mar 14, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [cc0cf690b8](https://linux-hardware.org/?probe=cc0cf690b8) | Mar 14, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [d555e645ce](https://linux-hardware.org/?probe=d555e645ce) | Mar 14, 2022 |
| MSI           | X470 GAMING PLUS            | [45b54744d3](https://linux-hardware.org/?probe=45b54744d3) | Mar 13, 2022 |
| ASUSTek       | P5QC                        | [144a20f079](https://linux-hardware.org/?probe=144a20f079) | Mar 13, 2022 |
| Dell          | 0D28YY A00                  | [065495a18e](https://linux-hardware.org/?probe=065495a18e) | Mar 13, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [9391de1a74](https://linux-hardware.org/?probe=9391de1a74) | Mar 12, 2022 |
| Intel         | DX79SR AAG57199-200         | [1ab5b833d9](https://linux-hardware.org/?probe=1ab5b833d9) | Mar 12, 2022 |
| MSI           | MS-7502 Fab D               | [8c29483032](https://linux-hardware.org/?probe=8c29483032) | Mar 12, 2022 |
| ASRock        | B450M/ac R2.0               | [27ad4e792a](https://linux-hardware.org/?probe=27ad4e792a) | Mar 12, 2022 |
| MSI           | B450 GAMING PLUS            | [f5aebd2929](https://linux-hardware.org/?probe=f5aebd2929) | Mar 12, 2022 |
| Gigabyte      | H61MA-D3V                   | [d8b0e137ea](https://linux-hardware.org/?probe=d8b0e137ea) | Mar 12, 2022 |
| Gigabyte      | G1.Sniper 3                 | [718c17782e](https://linux-hardware.org/?probe=718c17782e) | Mar 12, 2022 |
| ZYREX COMP... | TACTICAL                    | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0b912c2834](https://linux-hardware.org/?probe=0b912c2834) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [c92ad1d825](https://linux-hardware.org/?probe=c92ad1d825) | Mar 12, 2022 |
| ASUSTek       | X99-A                       | [4c62821984](https://linux-hardware.org/?probe=4c62821984) | Mar 12, 2022 |
| HP            | 3398                        | [6afe044e03](https://linux-hardware.org/?probe=6afe044e03) | Mar 12, 2022 |
| ASRock        | FM2A55M-VG3+                | [ebf747ad50](https://linux-hardware.org/?probe=ebf747ad50) | Mar 12, 2022 |
| ASUSTek       | PRIME H410M-E               | [671a3fc70b](https://linux-hardware.org/?probe=671a3fc70b) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [110670e1e6](https://linux-hardware.org/?probe=110670e1e6) | Mar 11, 2022 |
| Unknown       | Intel X79                   | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| Dell          | 0F3KHR A00                  | [f486888101](https://linux-hardware.org/?probe=f486888101) | Mar 10, 2022 |
| Gigabyte      | A520M H                     | [db7727accf](https://linux-hardware.org/?probe=db7727accf) | Mar 09, 2022 |
| Gigabyte      | A520M H                     | [b8038bbdc8](https://linux-hardware.org/?probe=b8038bbdc8) | Mar 09, 2022 |
| Gigabyte      | Z690 UD DDR4                | [40e96f459b](https://linux-hardware.org/?probe=40e96f459b) | Mar 09, 2022 |
| Dell          | 0XHGV1 A00                  | [8d3cfb2f81](https://linux-hardware.org/?probe=8d3cfb2f81) | Mar 09, 2022 |
| Gigabyte      | Z690 UD DDR4                | [0d20279113](https://linux-hardware.org/?probe=0d20279113) | Mar 09, 2022 |
| Acer          | FX58M                       | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7c7762632c](https://linux-hardware.org/?probe=7c7762632c) | Mar 08, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c99d57dabd](https://linux-hardware.org/?probe=c99d57dabd) | Mar 07, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [4946a1c5b0](https://linux-hardware.org/?probe=4946a1c5b0) | Mar 07, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [f68258a39f](https://linux-hardware.org/?probe=f68258a39f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [8b6d3c257a](https://linux-hardware.org/?probe=8b6d3c257a) | Mar 07, 2022 |
| Gigabyte      | X58A-UD3R                   | [f56996aab6](https://linux-hardware.org/?probe=f56996aab6) | Mar 07, 2022 |
| Gigabyte      | B75M-D3P                    | [ffa701db86](https://linux-hardware.org/?probe=ffa701db86) | Mar 06, 2022 |
| Acer          | H57M01                      | [7519d0fded](https://linux-hardware.org/?probe=7519d0fded) | Mar 06, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [2bb4d5ab6d](https://linux-hardware.org/?probe=2bb4d5ab6d) | Mar 06, 2022 |
| MSI           | A320M-A PRO MAX             | [f37fbd930e](https://linux-hardware.org/?probe=f37fbd930e) | Mar 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a95029db57](https://linux-hardware.org/?probe=a95029db57) | Mar 05, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d37684f01f](https://linux-hardware.org/?probe=d37684f01f) | Mar 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | [30da3f764c](https://linux-hardware.org/?probe=30da3f764c) | Mar 04, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [2b6fd5817c](https://linux-hardware.org/?probe=2b6fd5817c) | Mar 03, 2022 |
| ASUSTek       | B150M-D                     | [98291d2c13](https://linux-hardware.org/?probe=98291d2c13) | Mar 03, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [0f8e19d199](https://linux-hardware.org/?probe=0f8e19d199) | Mar 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [154e9a732e](https://linux-hardware.org/?probe=154e9a732e) | Mar 02, 2022 |
| Gigabyte      | X58A-UD3R                   | [3cc5bac970](https://linux-hardware.org/?probe=3cc5bac970) | Mar 02, 2022 |
| ASRock        | N68C-S UCC                  | [22b1e02dcd](https://linux-hardware.org/?probe=22b1e02dcd) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [35d5963329](https://linux-hardware.org/?probe=35d5963329) | Mar 02, 2022 |
| ASRock        | B450M/ac R2.0               | [a88394b0f9](https://linux-hardware.org/?probe=a88394b0f9) | Feb 28, 2022 |
| ASUSTek       | H97M-E                      | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| HP            | 18E7                        | [07d0861eff](https://linux-hardware.org/?probe=07d0861eff) | Feb 28, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [0da8223b4e](https://linux-hardware.org/?probe=0da8223b4e) | Feb 28, 2022 |
| Minix         | NEO Z83-4 V1.1              | [8aa7469422](https://linux-hardware.org/?probe=8aa7469422) | Feb 27, 2022 |
| ASUSTek       | M4A87TD EVO                 | [b9bec9d182](https://linux-hardware.org/?probe=b9bec9d182) | Feb 27, 2022 |
| ASUSTek       | M4A87TD EVO                 | [0bf1a63f98](https://linux-hardware.org/?probe=0bf1a63f98) | Feb 27, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [b2e75d51bb](https://linux-hardware.org/?probe=b2e75d51bb) | Feb 26, 2022 |
| ASUSTek       | PRIME B550M-K               | [dfcdd05598](https://linux-hardware.org/?probe=dfcdd05598) | Feb 26, 2022 |
| HP            | 339A                        | [118fee2993](https://linux-hardware.org/?probe=118fee2993) | Feb 26, 2022 |
| ASRock        | Z370 Pro4                   | [e996ec20ea](https://linux-hardware.org/?probe=e996ec20ea) | Feb 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [cb5e72732d](https://linux-hardware.org/?probe=cb5e72732d) | Feb 25, 2022 |
| MSI           | H110M PRO-VH PLUS           | [6754afe86b](https://linux-hardware.org/?probe=6754afe86b) | Feb 25, 2022 |
| ASRock        | B450M Steel Legend          | [dfebbb508b](https://linux-hardware.org/?probe=dfebbb508b) | Feb 24, 2022 |
| ASUSTek       | H81M-K                      | [22061aea18](https://linux-hardware.org/?probe=22061aea18) | Feb 24, 2022 |
| Gigabyte      | H510M S2                    | [2049c813f6](https://linux-hardware.org/?probe=2049c813f6) | Feb 24, 2022 |
| Gigabyte      | H510M S2                    | [ae837f007b](https://linux-hardware.org/?probe=ae837f007b) | Feb 24, 2022 |
| Medion        | MS-7501                     | [3f2b6c92b5](https://linux-hardware.org/?probe=3f2b6c92b5) | Feb 24, 2022 |
| EVGA          | Z390 FTW                    | [fe3889fa32](https://linux-hardware.org/?probe=fe3889fa32) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| ASUSTek       | Q87M-E                      | [9d4c111e9a](https://linux-hardware.org/?probe=9d4c111e9a) | Feb 23, 2022 |
| ASRock        | P67 Professional            | [3135f5a2d7](https://linux-hardware.org/?probe=3135f5a2d7) | Feb 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ee4e2d4e73](https://linux-hardware.org/?probe=ee4e2d4e73) | Feb 23, 2022 |
| ASUSTek       | B75M-PLUS                   | [c408f72a53](https://linux-hardware.org/?probe=c408f72a53) | Feb 23, 2022 |
| ASUSTek       | PRIME X570-P                | [9bef02ada7](https://linux-hardware.org/?probe=9bef02ada7) | Feb 22, 2022 |
| ASRock        | J4005M                      | [bff0e9d532](https://linux-hardware.org/?probe=bff0e9d532) | Feb 22, 2022 |
| HP            | 1850                        | [6e1dca6cb5](https://linux-hardware.org/?probe=6e1dca6cb5) | Feb 22, 2022 |
| ASRock        | B450M Steel Legend          | [26729d3227](https://linux-hardware.org/?probe=26729d3227) | Feb 22, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f6ac7c7952](https://linux-hardware.org/?probe=f6ac7c7952) | Feb 21, 2022 |
| ASRock        | J4005M                      | [aa149b39ea](https://linux-hardware.org/?probe=aa149b39ea) | Feb 20, 2022 |
| Packard Be... | TBGM01                      | [01fcf9c4ce](https://linux-hardware.org/?probe=01fcf9c4ce) | Feb 20, 2022 |
| Dell          | 0WMJ54 A01                  | [eb584535c7](https://linux-hardware.org/?probe=eb584535c7) | Feb 20, 2022 |
| HP            | 843F                        | [8dfd1523c9](https://linux-hardware.org/?probe=8dfd1523c9) | Feb 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | [5b7a77242b](https://linux-hardware.org/?probe=5b7a77242b) | Feb 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | [8e70b5fb30](https://linux-hardware.org/?probe=8e70b5fb30) | Feb 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [b9e6d11567](https://linux-hardware.org/?probe=b9e6d11567) | Feb 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5d16d8202f](https://linux-hardware.org/?probe=5d16d8202f) | Feb 20, 2022 |
| Gigabyte      | B450M DS3H V2               | [9d3a5fd18e](https://linux-hardware.org/?probe=9d3a5fd18e) | Feb 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | [2ce44e02c7](https://linux-hardware.org/?probe=2ce44e02c7) | Feb 19, 2022 |
| ASRock        | FM2A55M-VG3+                | [546d09f207](https://linux-hardware.org/?probe=546d09f207) | Feb 19, 2022 |
| EVGA          | X570 FTW WIFI.0             | [8780994e21](https://linux-hardware.org/?probe=8780994e21) | Feb 18, 2022 |
| Gigabyte      | Z68MX-UD2H-B3               | [4ee5a962df](https://linux-hardware.org/?probe=4ee5a962df) | Feb 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | [01c12eb94c](https://linux-hardware.org/?probe=01c12eb94c) | Feb 18, 2022 |
| ASRock        | B450M Steel Legend          | [024513d4a8](https://linux-hardware.org/?probe=024513d4a8) | Feb 18, 2022 |
| Dell          | 0NW73C A00                  | [6b25bd6a18](https://linux-hardware.org/?probe=6b25bd6a18) | Feb 18, 2022 |
| ASRock        | A520M-HVS                   | [f9705ca187](https://linux-hardware.org/?probe=f9705ca187) | Feb 18, 2022 |
| ASRock        | A520M-HVS                   | [54887060c2](https://linux-hardware.org/?probe=54887060c2) | Feb 18, 2022 |
| Gigabyte      | MSH87TN-00                  | [6baa824f3a](https://linux-hardware.org/?probe=6baa824f3a) | Feb 17, 2022 |
| ASRock        | X299 Taichi XE              | [04a1425dca](https://linux-hardware.org/?probe=04a1425dca) | Feb 17, 2022 |
| HP            | 339A                        | [d35aeac271](https://linux-hardware.org/?probe=d35aeac271) | Feb 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| ASUSTek       | M4A87TD/USB3                | [041b4e9976](https://linux-hardware.org/?probe=041b4e9976) | Feb 16, 2022 |
| Dell          | 0GXM1W A00                  | [f54569882a](https://linux-hardware.org/?probe=f54569882a) | Feb 16, 2022 |
| HP            | 339A                        | [aac8acdafe](https://linux-hardware.org/?probe=aac8acdafe) | Feb 16, 2022 |
| Dell          | 0GXM1W A01                  | [c06de8e7c6](https://linux-hardware.org/?probe=c06de8e7c6) | Feb 15, 2022 |
| Gigabyte      | X58A-UD3R                   | [87774dacdd](https://linux-hardware.org/?probe=87774dacdd) | Feb 15, 2022 |
| Gigabyte      | X58A-UD3R                   | [3cf4dc7f97](https://linux-hardware.org/?probe=3cf4dc7f97) | Feb 15, 2022 |
| ASRock        | B450 Pro4                   | [1b2a216e13](https://linux-hardware.org/?probe=1b2a216e13) | Feb 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [9f58500ff7](https://linux-hardware.org/?probe=9f58500ff7) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [f3f17f2dd0](https://linux-hardware.org/?probe=f3f17f2dd0) | Feb 13, 2022 |
| ASRock        | H55M                        | [85a293bc45](https://linux-hardware.org/?probe=85a293bc45) | Feb 13, 2022 |
| HP            | 18E7                        | [b047f83746](https://linux-hardware.org/?probe=b047f83746) | Feb 12, 2022 |
| MSI           | B85M ECO                    | [4639d833bb](https://linux-hardware.org/?probe=4639d833bb) | Feb 12, 2022 |
| ASUSTek       | Berkeley                    | [e189134b88](https://linux-hardware.org/?probe=e189134b88) | Feb 12, 2022 |
| MSI           | H81M-P33                    | [e40a9cf57a](https://linux-hardware.org/?probe=e40a9cf57a) | Feb 11, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [f4dec544b7](https://linux-hardware.org/?probe=f4dec544b7) | Feb 11, 2022 |
| Unknown       | Unknown                     | [f8ea6734a8](https://linux-hardware.org/?probe=f8ea6734a8) | Feb 11, 2022 |
| HP            | 2B2C                        | [e5b45f315c](https://linux-hardware.org/?probe=e5b45f315c) | Feb 11, 2022 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [cdc87c7a4d](https://linux-hardware.org/?probe=cdc87c7a4d) | Feb 10, 2022 |
| ASRock        | Z370 Pro4                   | [c9aa1fb558](https://linux-hardware.org/?probe=c9aa1fb558) | Feb 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | [a530f2976f](https://linux-hardware.org/?probe=a530f2976f) | Feb 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | [5480f2aa6c](https://linux-hardware.org/?probe=5480f2aa6c) | Feb 10, 2022 |
| Gigabyte      | Z77X-D3H                    | [62d5812547](https://linux-hardware.org/?probe=62d5812547) | Feb 09, 2022 |
| HP            | 8906 SMVB                   | [454f14e47d](https://linux-hardware.org/?probe=454f14e47d) | Feb 09, 2022 |
| Gigabyte      | X58A-UD3R                   | [f4c4b60509](https://linux-hardware.org/?probe=f4c4b60509) | Feb 09, 2022 |
| HP            | 18E7                        | [11c3f1c67f](https://linux-hardware.org/?probe=11c3f1c67f) | Feb 09, 2022 |
| ASRock        | G31M-GS                     | [b6e2355249](https://linux-hardware.org/?probe=b6e2355249) | Feb 09, 2022 |
| Dell          | 0J3C2F A00                  | [44eeacc539](https://linux-hardware.org/?probe=44eeacc539) | Feb 08, 2022 |
| HP            | 843F                        | [9e9ad83053](https://linux-hardware.org/?probe=9e9ad83053) | Feb 08, 2022 |
| HP            | 2B2C                        | [524718f4ab](https://linux-hardware.org/?probe=524718f4ab) | Feb 08, 2022 |
| DFI           | LP UT X58                   | [ecb951c819](https://linux-hardware.org/?probe=ecb951c819) | Feb 07, 2022 |
| HP            | 859C                        | [e984dd6733](https://linux-hardware.org/?probe=e984dd6733) | Feb 07, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [733ee79a8f](https://linux-hardware.org/?probe=733ee79a8f) | Feb 07, 2022 |
| ASUSTek       | P5Q                         | [52e57261d3](https://linux-hardware.org/?probe=52e57261d3) | Feb 07, 2022 |
| ASUSTek       | P5Q                         | [1fc7c3bed9](https://linux-hardware.org/?probe=1fc7c3bed9) | Feb 06, 2022 |
| Packard Be... | TBGM01                      | [295ffc3ec6](https://linux-hardware.org/?probe=295ffc3ec6) | Feb 06, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [7030f02dfa](https://linux-hardware.org/?probe=7030f02dfa) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [3a8c47094b](https://linux-hardware.org/?probe=3a8c47094b) | Feb 05, 2022 |
| MSI           | 760GM-P23                   | [d0df7d6097](https://linux-hardware.org/?probe=d0df7d6097) | Feb 05, 2022 |
| ASRock        | A300M-STX                   | [ed9e69a65f](https://linux-hardware.org/?probe=ed9e69a65f) | Feb 05, 2022 |
| ASRock        | 970 Extreme3                | [2ea42468c2](https://linux-hardware.org/?probe=2ea42468c2) | Feb 04, 2022 |
| HP            | 2B2C                        | [45c409ba35](https://linux-hardware.org/?probe=45c409ba35) | Feb 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Packard Be... | IMEDIA S2985                | [661d923ce2](https://linux-hardware.org/?probe=661d923ce2) | Feb 03, 2022 |
| Foxconn       | 2A8C                        | [6b15540146](https://linux-hardware.org/?probe=6b15540146) | Feb 03, 2022 |
| ASUSTek       | X99-A II                    | [6b87d8987b](https://linux-hardware.org/?probe=6b87d8987b) | Feb 03, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [9f9648d05c](https://linux-hardware.org/?probe=9f9648d05c) | Feb 02, 2022 |
| Dell          | 0Y7WYT A00                  | [f7cf8b586e](https://linux-hardware.org/?probe=f7cf8b586e) | Feb 01, 2022 |
| MSI           | B450-A PRO MAX              | [08a40b3e98](https://linux-hardware.org/?probe=08a40b3e98) | Feb 01, 2022 |
| ASRock        | B75M-GL R2.0                | [4cf4045deb](https://linux-hardware.org/?probe=4cf4045deb) | Feb 01, 2022 |
| Acer          | FX58M                       | [e68b127961](https://linux-hardware.org/?probe=e68b127961) | Feb 01, 2022 |
| ASUSTek       | H87M-PRO                    | [0f96c91905](https://linux-hardware.org/?probe=0f96c91905) | Feb 01, 2022 |
| BESSTAR Te... | UM300 V1.0                  | [13b724ceeb](https://linux-hardware.org/?probe=13b724ceeb) | Feb 01, 2022 |
| ASRock        | 4X4-4000 Series             | [4b00e6b290](https://linux-hardware.org/?probe=4b00e6b290) | Feb 01, 2022 |
| MSI           | Z370 GAMING PLUS            | [72ad880143](https://linux-hardware.org/?probe=72ad880143) | Jan 31, 2022 |
| ASUSTek       | CM6870                      | [f217244fb2](https://linux-hardware.org/?probe=f217244fb2) | Jan 31, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [44411daa5a](https://linux-hardware.org/?probe=44411daa5a) | Jan 31, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [f3ed6567f9](https://linux-hardware.org/?probe=f3ed6567f9) | Jan 31, 2022 |
| BESSTAR Te... | UM300 V1.0                  | [66320a8981](https://linux-hardware.org/?probe=66320a8981) | Jan 31, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [927a82eb86](https://linux-hardware.org/?probe=927a82eb86) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fc9ddc34b0](https://linux-hardware.org/?probe=fc9ddc34b0) | Jan 30, 2022 |
| Gigabyte      | GA-890FXA-UD5               | [a7a2a13e23](https://linux-hardware.org/?probe=a7a2a13e23) | Jan 30, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [87a19ca6bd](https://linux-hardware.org/?probe=87a19ca6bd) | Jan 30, 2022 |
| HP            | 3048h                       | [cb51d0cf78](https://linux-hardware.org/?probe=cb51d0cf78) | Jan 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [38eb148f2e](https://linux-hardware.org/?probe=38eb148f2e) | Jan 29, 2022 |
| ASRock        | H570M-ITX/ac                | [e901364a26](https://linux-hardware.org/?probe=e901364a26) | Jan 28, 2022 |
| ASRock        | 970 Extreme3                | [82d0c3e60e](https://linux-hardware.org/?probe=82d0c3e60e) | Jan 28, 2022 |
| MSI           | B560M PRO                   | [00b3d4717d](https://linux-hardware.org/?probe=00b3d4717d) | Jan 28, 2022 |
| ASRock        | H570M-ITX/ac                | [7295dda221](https://linux-hardware.org/?probe=7295dda221) | Jan 28, 2022 |
| MSI           | B560M PRO                   | [b3a84eebc3](https://linux-hardware.org/?probe=b3a84eebc3) | Jan 28, 2022 |
| Dell          | 0WMJ54 A01                  | [d4c6610ae0](https://linux-hardware.org/?probe=d4c6610ae0) | Jan 28, 2022 |
| ASUSTek       | H81M-K                      | [74149e531c](https://linux-hardware.org/?probe=74149e531c) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| ASUSTek       | PRIME Z370-A                | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| HP            | 8054                        | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [00cdb626d7](https://linux-hardware.org/?probe=00cdb626d7) | Jan 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [12e94e5413](https://linux-hardware.org/?probe=12e94e5413) | Jan 25, 2022 |
| Gigabyte      | B460M AORUS PRO             | [33521b66a1](https://linux-hardware.org/?probe=33521b66a1) | Jan 25, 2022 |
| Medion        | H110H4-CM2                  | [8574d37f58](https://linux-hardware.org/?probe=8574d37f58) | Jan 25, 2022 |
| Dell          | 0DXYK6 A01                  | [f270a1ab38](https://linux-hardware.org/?probe=f270a1ab38) | Jan 25, 2022 |
| Medion        | P2A4-EM                     | [6e80bcdcd1](https://linux-hardware.org/?probe=6e80bcdcd1) | Jan 24, 2022 |
| Dell          | 0DXYK6 A01                  | [a145a49fc6](https://linux-hardware.org/?probe=a145a49fc6) | Jan 23, 2022 |
| ASUSTek       | D642MF                      | [1d59c9470c](https://linux-hardware.org/?probe=1d59c9470c) | Jan 23, 2022 |
| MSI           | 760GM-P23                   | [65ce5265d3](https://linux-hardware.org/?probe=65ce5265d3) | Jan 23, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [d9cbf7e314](https://linux-hardware.org/?probe=d9cbf7e314) | Jan 23, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [b1cfd38100](https://linux-hardware.org/?probe=b1cfd38100) | Jan 23, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [b63214b1e1](https://linux-hardware.org/?probe=b63214b1e1) | Jan 23, 2022 |
| ASUSTek       | P8B75-M LX                  | [dc2c32aac2](https://linux-hardware.org/?probe=dc2c32aac2) | Jan 23, 2022 |
| Acer          | FIH57                       | [af79e42583](https://linux-hardware.org/?probe=af79e42583) | Jan 23, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [7f92d6ff46](https://linux-hardware.org/?probe=7f92d6ff46) | Jan 22, 2022 |
| ASUSTek       | PRIME B360M-A               | [3825d7e113](https://linux-hardware.org/?probe=3825d7e113) | Jan 22, 2022 |
| ASUSTek       | H81M-R                      | [d324ae2959](https://linux-hardware.org/?probe=d324ae2959) | Jan 22, 2022 |
| MSI           | H55M-E33                    | [bb0b689514](https://linux-hardware.org/?probe=bb0b689514) | Jan 22, 2022 |
| HP            | 843F                        | [75459e99d4](https://linux-hardware.org/?probe=75459e99d4) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [ff2dd45add](https://linux-hardware.org/?probe=ff2dd45add) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [234acd7143](https://linux-hardware.org/?probe=234acd7143) | Jan 21, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [773f86769e](https://linux-hardware.org/?probe=773f86769e) | Jan 21, 2022 |
| MSI           | MS-7469 100                 | [8476ffa27e](https://linux-hardware.org/?probe=8476ffa27e) | Jan 20, 2022 |
| ASUSTek       | Z97-K                       | [7d370214de](https://linux-hardware.org/?probe=7d370214de) | Jan 20, 2022 |
| HP            | 18EB                        | [59cce3a9a2](https://linux-hardware.org/?probe=59cce3a9a2) | Jan 19, 2022 |
| Gigabyte      | X58A-UD3R                   | [93b6fafb6e](https://linux-hardware.org/?probe=93b6fafb6e) | Jan 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [8cf30a73c8](https://linux-hardware.org/?probe=8cf30a73c8) | Jan 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| Acer          | Predator G6-710             | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASRock        | Z270M-ITX/ac                | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Dell          | 0KH290                      | [1ec02399c2](https://linux-hardware.org/?probe=1ec02399c2) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [e3f87f47e8](https://linux-hardware.org/?probe=e3f87f47e8) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M71e 3157R75    | [871b2aecd9](https://linux-hardware.org/?probe=871b2aecd9) | Jan 17, 2022 |
| PCWare        | IPMH61R1                    | [9bad24f3d9](https://linux-hardware.org/?probe=9bad24f3d9) | Jan 17, 2022 |
| Gigabyte      | Z270X-Gaming 5              | [d1cf9b9344](https://linux-hardware.org/?probe=d1cf9b9344) | Jan 17, 2022 |
| Gigabyte      | X58A-UD3R                   | [dc02dbb307](https://linux-hardware.org/?probe=dc02dbb307) | Jan 16, 2022 |
| HP            | 8906 SMVB                   | [566e943f08](https://linux-hardware.org/?probe=566e943f08) | Jan 16, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [17d01b9a1d](https://linux-hardware.org/?probe=17d01b9a1d) | Jan 16, 2022 |
| ASUSTek       | Z97-K                       | [4b03f84c93](https://linux-hardware.org/?probe=4b03f84c93) | Jan 16, 2022 |
| HP            | 8266                        | [c2cbb29774](https://linux-hardware.org/?probe=c2cbb29774) | Jan 15, 2022 |
| HP            | 3048h                       | [d6f6435471](https://linux-hardware.org/?probe=d6f6435471) | Jan 15, 2022 |
| ASUSTek       | SABERTOOTH P67              | [5d9e7dcdd1](https://linux-hardware.org/?probe=5d9e7dcdd1) | Jan 15, 2022 |
| MSI           | Z490-A PRO                  | [62d5c59aec](https://linux-hardware.org/?probe=62d5c59aec) | Jan 15, 2022 |
| HP            | 1495                        | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [9b8c21a3d0](https://linux-hardware.org/?probe=9b8c21a3d0) | Jan 14, 2022 |
| HP            | 0AECh D                     | [c42b2d840d](https://linux-hardware.org/?probe=c42b2d840d) | Jan 14, 2022 |
| Unknown       | X99-GT                      | [4562aa0142](https://linux-hardware.org/?probe=4562aa0142) | Jan 13, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [7723b652d9](https://linux-hardware.org/?probe=7723b652d9) | Jan 13, 2022 |
| Dell          | 0KWVT8 A00                  | [c4a3e67da7](https://linux-hardware.org/?probe=c4a3e67da7) | Jan 13, 2022 |
| MSI           | H510I PRO WIFI              | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| MSI           | A320M-A PRO MAX             | [c0cb966fb7](https://linux-hardware.org/?probe=c0cb966fb7) | Jan 13, 2022 |
| MSI           | Z270 GAMING PLUS            | [bf0493bb07](https://linux-hardware.org/?probe=bf0493bb07) | Jan 13, 2022 |
| MSI           | Z270 GAMING PLUS            | [cbc37c86d0](https://linux-hardware.org/?probe=cbc37c86d0) | Jan 13, 2022 |
| MSI           | B75MA-P45                   | [dc73e7a540](https://linux-hardware.org/?probe=dc73e7a540) | Jan 12, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [2b42fd9ee4](https://linux-hardware.org/?probe=2b42fd9ee4) | Jan 12, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1dd4561367](https://linux-hardware.org/?probe=1dd4561367) | Jan 12, 2022 |
| MSI           | B75MA-P45                   | [60d7670ca3](https://linux-hardware.org/?probe=60d7670ca3) | Jan 12, 2022 |
| Packard Be... | EG43M                       | [bd7097f415](https://linux-hardware.org/?probe=bd7097f415) | Jan 12, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [7dac64a6ff](https://linux-hardware.org/?probe=7dac64a6ff) | Jan 12, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [1e08ba87bd](https://linux-hardware.org/?probe=1e08ba87bd) | Jan 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [2afab06632](https://linux-hardware.org/?probe=2afab06632) | Jan 11, 2022 |
| HP            | 212B                        | [c8d010ae43](https://linux-hardware.org/?probe=c8d010ae43) | Jan 11, 2022 |
| ASRock        | FM2A88M-HD+                 | [2d834a40f5](https://linux-hardware.org/?probe=2d834a40f5) | Jan 10, 2022 |
| MSI           | B550M-A PRO                 | [450ef59cb0](https://linux-hardware.org/?probe=450ef59cb0) | Jan 10, 2022 |
| ASUSTek       | H81M-PLUS                   | [67ab65d5f0](https://linux-hardware.org/?probe=67ab65d5f0) | Jan 10, 2022 |
| HP            | 0AECh D                     | [f755fbe60f](https://linux-hardware.org/?probe=f755fbe60f) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [78f18e59c9](https://linux-hardware.org/?probe=78f18e59c9) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [569783a078](https://linux-hardware.org/?probe=569783a078) | Jan 09, 2022 |
| Gigabyte      | B85M-D3PH                   | [5602ba99c2](https://linux-hardware.org/?probe=5602ba99c2) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | B550M PRO-VDH               | [5c63b79779](https://linux-hardware.org/?probe=5c63b79779) | Jan 07, 2022 |
| TYAN Compu... | Tempest-i5000VS-S5372-LC... | [d1cfd7ca04](https://linux-hardware.org/?probe=d1cfd7ca04) | Jan 07, 2022 |
| ASUSTek       | P8H77-M PRO                 | [14a4cdc223](https://linux-hardware.org/?probe=14a4cdc223) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | [32cae94f00](https://linux-hardware.org/?probe=32cae94f00) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | [c103969fdf](https://linux-hardware.org/?probe=c103969fdf) | Jan 06, 2022 |
| MSI           | Z390-A PRO                  | [b1fe0d9671](https://linux-hardware.org/?probe=b1fe0d9671) | Jan 06, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f00aac4419](https://linux-hardware.org/?probe=f00aac4419) | Jan 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [40324b4766](https://linux-hardware.org/?probe=40324b4766) | Jan 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [81efe23b11](https://linux-hardware.org/?probe=81efe23b11) | Jan 04, 2022 |
| Dell          | 0D28YY A00                  | [8525880542](https://linux-hardware.org/?probe=8525880542) | Jan 04, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [ad7422345b](https://linux-hardware.org/?probe=ad7422345b) | Jan 04, 2022 |
| Intel         | HURONRIVER                  | [85b441d7cb](https://linux-hardware.org/?probe=85b441d7cb) | Jan 04, 2022 |
| MSI           | B85M ECO                    | [927ae260f1](https://linux-hardware.org/?probe=927ae260f1) | Jan 04, 2022 |
| MSI           | A320M PRO-VD/S              | [40afcf3662](https://linux-hardware.org/?probe=40afcf3662) | Jan 03, 2022 |
| HP            | 0AECh D                     | [c25b4d18af](https://linux-hardware.org/?probe=c25b4d18af) | Jan 03, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| HP            | 0AECh D                     | [6cf0733967](https://linux-hardware.org/?probe=6cf0733967) | Jan 03, 2022 |
| HP            | 0AECh D                     | [78a40041d5](https://linux-hardware.org/?probe=78a40041d5) | Jan 03, 2022 |
| Biostar       | Z490A-SILVER                | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [c30b1e6110](https://linux-hardware.org/?probe=c30b1e6110) | Jan 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [eeb310ed49](https://linux-hardware.org/?probe=eeb310ed49) | Jan 02, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [f5589634ef](https://linux-hardware.org/?probe=f5589634ef) | Jan 01, 2022 |
| MSI           | A320M-A PRO MAX             | [b010826415](https://linux-hardware.org/?probe=b010826415) | Jan 01, 2022 |
| HP            | 0AA0h                       | [bf7b3e968e](https://linux-hardware.org/?probe=bf7b3e968e) | Jan 01, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [3df571fbbb](https://linux-hardware.org/?probe=3df571fbbb) | Jan 01, 2022 |
| Gigabyte      | Z77X-D3H                    | [3ebf180dc4](https://linux-hardware.org/?probe=3ebf180dc4) | Jan 01, 2022 |
| MSI           | A320M-A PRO MAX             | [6601708090](https://linux-hardware.org/?probe=6601708090) | Dec 31, 2021 |
| MSI           | A320M PRO-M2 V2             | [4e84971678](https://linux-hardware.org/?probe=4e84971678) | Dec 30, 2021 |
| Gigabyte      | X570 GAMING X               | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| MSI           | Q45MDO                      | [e3ea0d80d3](https://linux-hardware.org/?probe=e3ea0d80d3) | Dec 30, 2021 |
| ASUSTek       | P8H61                       | [682efb70d7](https://linux-hardware.org/?probe=682efb70d7) | Dec 29, 2021 |
| Pegatron      | Narra6                      | [da3be9b31b](https://linux-hardware.org/?probe=da3be9b31b) | Dec 29, 2021 |
| ASRock        | B550M-ITX/ac                | [1e4bffb013](https://linux-hardware.org/?probe=1e4bffb013) | Dec 29, 2021 |
| ASRock        | Z170 Gaming K4              | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| Gigabyte      | 965P-DS3                    | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| EVGA          | 134-KS-E377                 | [503b4d620c](https://linux-hardware.org/?probe=503b4d620c) | Dec 29, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [a3af4e5057](https://linux-hardware.org/?probe=a3af4e5057) | Dec 28, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [bae2ef5b28](https://linux-hardware.org/?probe=bae2ef5b28) | Dec 28, 2021 |
| ASUSTek       | Maximus VIII EXTREME        | [ccc49903fd](https://linux-hardware.org/?probe=ccc49903fd) | Dec 28, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | [cb6cfc3c5e](https://linux-hardware.org/?probe=cb6cfc3c5e) | Dec 27, 2021 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [5ea8f7d7a8](https://linux-hardware.org/?probe=5ea8f7d7a8) | Dec 27, 2021 |
| ASUSTek       | CM6870                      | [0a24371b49](https://linux-hardware.org/?probe=0a24371b49) | Dec 27, 2021 |
| Acer          | Predator PO3-620            | [d33f608e2e](https://linux-hardware.org/?probe=d33f608e2e) | Dec 27, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [757d6a5d20](https://linux-hardware.org/?probe=757d6a5d20) | Dec 27, 2021 |
| Dell          | 0HD5W2 A01                  | [143f0ef296](https://linux-hardware.org/?probe=143f0ef296) | Dec 27, 2021 |
| Positivo      | POS-MIH61CF                 | [a8fd13db4c](https://linux-hardware.org/?probe=a8fd13db4c) | Dec 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | [05b30c96fd](https://linux-hardware.org/?probe=05b30c96fd) | Dec 26, 2021 |
| ASRock        | Z690M-ITX/ax                | [0a35834719](https://linux-hardware.org/?probe=0a35834719) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| Dell          | 0WN7Y6 A01                  | [45220bb46c](https://linux-hardware.org/?probe=45220bb46c) | Dec 26, 2021 |
| ASRock        | Z690M-ITX/ax                | [fcc19136e0](https://linux-hardware.org/?probe=fcc19136e0) | Dec 26, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [8881d4e351](https://linux-hardware.org/?probe=8881d4e351) | Dec 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [0ed55de90b](https://linux-hardware.org/?probe=0ed55de90b) | Dec 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e93a789ba7](https://linux-hardware.org/?probe=e93a789ba7) | Dec 25, 2021 |
| Foxconn       | 2ABF                        | [fdc6aac853](https://linux-hardware.org/?probe=fdc6aac853) | Dec 25, 2021 |
| Medion        | MS-7707                     | [2590f9fac3](https://linux-hardware.org/?probe=2590f9fac3) | Dec 25, 2021 |
| Medion        | MS-7707                     | [9a64e7919f](https://linux-hardware.org/?probe=9a64e7919f) | Dec 25, 2021 |
| HP            | 8643 SMVB                   | [18fdb46bb5](https://linux-hardware.org/?probe=18fdb46bb5) | Dec 24, 2021 |
| Positivo      | POS-MIH61CF                 | [f10e90bd72](https://linux-hardware.org/?probe=f10e90bd72) | Dec 24, 2021 |
| Dell          | 0F3KHR A00                  | [3efe58bf92](https://linux-hardware.org/?probe=3efe58bf92) | Dec 24, 2021 |
| HP            | 158A                        | [dc1212a83a](https://linux-hardware.org/?probe=dc1212a83a) | Dec 24, 2021 |
| Gigabyte      | B150M-HD3-CF                | [8b9eeb5990](https://linux-hardware.org/?probe=8b9eeb5990) | Dec 24, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [26b64d67a9](https://linux-hardware.org/?probe=26b64d67a9) | Dec 24, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| HP            | 83EE                        | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| Lenovo        | NOK                         | [5671e681fe](https://linux-hardware.org/?probe=5671e681fe) | Dec 24, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [04f1714e45](https://linux-hardware.org/?probe=04f1714e45) | Dec 23, 2021 |
| HP            | 3048h                       | [2e47687170](https://linux-hardware.org/?probe=2e47687170) | Dec 23, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [35e30d5285](https://linux-hardware.org/?probe=35e30d5285) | Dec 23, 2021 |
| MSI           | Z97 GAMING 5                | [4f71fa3090](https://linux-hardware.org/?probe=4f71fa3090) | Dec 23, 2021 |
| ASRock        | Z370 Pro4                   | [482842307e](https://linux-hardware.org/?probe=482842307e) | Dec 23, 2021 |
| Dell          | 0VHWTR A02                  | [3be006d99a](https://linux-hardware.org/?probe=3be006d99a) | Dec 23, 2021 |
| ASUSTek       | P5P43TD PRO                 | [6019461793](https://linux-hardware.org/?probe=6019461793) | Dec 22, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [c66f391530](https://linux-hardware.org/?probe=c66f391530) | Dec 22, 2021 |
| MSI           | H81M PRO-VD                 | [b0c70d78fd](https://linux-hardware.org/?probe=b0c70d78fd) | Dec 22, 2021 |
| Dell          | 0MM599                      | [91a32378db](https://linux-hardware.org/?probe=91a32378db) | Dec 22, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [427ddfb2d9](https://linux-hardware.org/?probe=427ddfb2d9) | Dec 21, 2021 |
| MSI           | B85M ECO                    | [034b632cee](https://linux-hardware.org/?probe=034b632cee) | Dec 21, 2021 |
| MSI           | B85M ECO                    | [9c63b4bd85](https://linux-hardware.org/?probe=9c63b4bd85) | Dec 21, 2021 |
| MSI           | 790XT-G45                   | [8f8e171a52](https://linux-hardware.org/?probe=8f8e171a52) | Dec 20, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [bcd3f5edf4](https://linux-hardware.org/?probe=bcd3f5edf4) | Dec 20, 2021 |
| ASRock        | X58 Extreme3                | [0e188e9dd0](https://linux-hardware.org/?probe=0e188e9dd0) | Dec 19, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [16017b88bc](https://linux-hardware.org/?probe=16017b88bc) | Dec 19, 2021 |
| MSI           | B450 TOMAHAWK               | [125b9e5965](https://linux-hardware.org/?probe=125b9e5965) | Dec 19, 2021 |
| ASUSTek       | M4A77TD PRO                 | [4e65d26e64](https://linux-hardware.org/?probe=4e65d26e64) | Dec 18, 2021 |
| Dell          | 042P49 A02                  | [56afcbdd15](https://linux-hardware.org/?probe=56afcbdd15) | Dec 18, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| MSI           | X399 SLI PLUS               | [08c23ed037](https://linux-hardware.org/?probe=08c23ed037) | Dec 17, 2021 |
| ASUSTek       | PRIME B450M-A               | [b639c498bb](https://linux-hardware.org/?probe=b639c498bb) | Dec 17, 2021 |
| MSI           | MAG B460 TORPEDO            | [a26f1ed9a0](https://linux-hardware.org/?probe=a26f1ed9a0) | Dec 17, 2021 |
| Gigabyte      | EP35-DS4                    | [46e2648ab6](https://linux-hardware.org/?probe=46e2648ab6) | Dec 16, 2021 |
| Dell          | 0WR7PY A02                  | [459b162eab](https://linux-hardware.org/?probe=459b162eab) | Dec 16, 2021 |
| Biostar       | H61MLC                      | [ff1c843adf](https://linux-hardware.org/?probe=ff1c843adf) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| ASUSTek       | P6T DELUXE V2               | [275bcfce49](https://linux-hardware.org/?probe=275bcfce49) | Dec 15, 2021 |
| Dell          | 0WN7Y6 A01                  | [48e34ad548](https://linux-hardware.org/?probe=48e34ad548) | Dec 15, 2021 |
| Dell          | 0TP412                      | [8c26fae09d](https://linux-hardware.org/?probe=8c26fae09d) | Dec 15, 2021 |
| Positivo      | POS-MIH61CF                 | [20ecdbd153](https://linux-hardware.org/?probe=20ecdbd153) | Dec 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [906909677d](https://linux-hardware.org/?probe=906909677d) | Dec 14, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [38d013c7db](https://linux-hardware.org/?probe=38d013c7db) | Dec 14, 2021 |
| HP            | 8054                        | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASRock        | Z170 Gaming K4              | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | [648ce917b9](https://linux-hardware.org/?probe=648ce917b9) | Dec 13, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a85c1b3793](https://linux-hardware.org/?probe=a85c1b3793) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1ee5ab4347](https://linux-hardware.org/?probe=1ee5ab4347) | Dec 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6e9b3e47ac](https://linux-hardware.org/?probe=6e9b3e47ac) | Dec 12, 2021 |
| Dell          | 0YXT71 A01                  | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| ASRock        | N68-GS4 FX                  | [17296e4753](https://linux-hardware.org/?probe=17296e4753) | Dec 11, 2021 |
| ASRock        | N68-GS4 FX                  | [883dca4bce](https://linux-hardware.org/?probe=883dca4bce) | Dec 11, 2021 |
| EVGA          | 134-KS-E377                 | [537cce12a4](https://linux-hardware.org/?probe=537cce12a4) | Dec 11, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [19a0f28f2f](https://linux-hardware.org/?probe=19a0f28f2f) | Dec 11, 2021 |
| EVGA          | 134-KS-E377                 | [1ad3ddd70b](https://linux-hardware.org/?probe=1ad3ddd70b) | Dec 11, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [15df6092b7](https://linux-hardware.org/?probe=15df6092b7) | Dec 11, 2021 |
| ASUSTek       | P5N-D                       | [772d984bb8](https://linux-hardware.org/?probe=772d984bb8) | Dec 10, 2021 |
| Dell          | 03KWTV A02                  | [446130659d](https://linux-hardware.org/?probe=446130659d) | Dec 10, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [2ad79030d4](https://linux-hardware.org/?probe=2ad79030d4) | Dec 10, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8d9bc5957a](https://linux-hardware.org/?probe=8d9bc5957a) | Dec 10, 2021 |
| Dell          | 03KWTV A02                  | [643a045c8b](https://linux-hardware.org/?probe=643a045c8b) | Dec 09, 2021 |
| MSI           | Z87-G45 GAMING              | [1a012f2f1f](https://linux-hardware.org/?probe=1a012f2f1f) | Dec 09, 2021 |
| ASRock        | X58 Extreme3                | [5c8c08277f](https://linux-hardware.org/?probe=5c8c08277f) | Dec 09, 2021 |
| ASRock        | X58 Extreme3                | [73fa8b0ca4](https://linux-hardware.org/?probe=73fa8b0ca4) | Dec 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [b6e2e39051](https://linux-hardware.org/?probe=b6e2e39051) | Dec 09, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [83df1d7ac7](https://linux-hardware.org/?probe=83df1d7ac7) | Dec 09, 2021 |
| ASUSTek       | H97I-PLUS                   | [47f631ff16](https://linux-hardware.org/?probe=47f631ff16) | Dec 09, 2021 |
| Gigabyte      | 945GCM-S2L                  | [a253c74be5](https://linux-hardware.org/?probe=a253c74be5) | Dec 08, 2021 |
| Dell          | 088DT1 A00                  | [1825e90eed](https://linux-hardware.org/?probe=1825e90eed) | Dec 08, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [160b6097cd](https://linux-hardware.org/?probe=160b6097cd) | Dec 08, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [caa363c86c](https://linux-hardware.org/?probe=caa363c86c) | Dec 08, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [38c5e135f8](https://linux-hardware.org/?probe=38c5e135f8) | Dec 08, 2021 |
| OEM           | TOP77D Ver1.0               | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| Gigabyte      | EX58-UD5                    | [29f0eb6b67](https://linux-hardware.org/?probe=29f0eb6b67) | Dec 07, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [70d51853a0](https://linux-hardware.org/?probe=70d51853a0) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| MSI           | MEG X570 ACE                | [ce4bd7acd9](https://linux-hardware.org/?probe=ce4bd7acd9) | Dec 07, 2021 |
| Gigabyte      | B450 AORUS M                | [1493fa959b](https://linux-hardware.org/?probe=1493fa959b) | Dec 06, 2021 |
| EVGA          | 111-CS-E371                 | [e6af9b4e1e](https://linux-hardware.org/?probe=e6af9b4e1e) | Dec 06, 2021 |
| Gigabyte      | B365M DS3H                  | [8365e0bff7](https://linux-hardware.org/?probe=8365e0bff7) | Dec 05, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0a69990530](https://linux-hardware.org/?probe=0a69990530) | Dec 05, 2021 |
| Dell          | 0KRC95 A00                  | [d16dfb27de](https://linux-hardware.org/?probe=d16dfb27de) | Dec 05, 2021 |
| ASUSTek       | M4A87TD/USB3                | [6550b760b5](https://linux-hardware.org/?probe=6550b760b5) | Dec 05, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7a511dda3d](https://linux-hardware.org/?probe=7a511dda3d) | Dec 04, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60e7267ddb](https://linux-hardware.org/?probe=60e7267ddb) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [1f37d4567d](https://linux-hardware.org/?probe=1f37d4567d) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [142f88e753](https://linux-hardware.org/?probe=142f88e753) | Dec 04, 2021 |
| HP            | 1587h                       | [aaa0c74349](https://linux-hardware.org/?probe=aaa0c74349) | Dec 04, 2021 |
| Gigabyte      | X79-UP4                     | [c98cb8462e](https://linux-hardware.org/?probe=c98cb8462e) | Dec 04, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [a83c80b9bd](https://linux-hardware.org/?probe=a83c80b9bd) | Dec 04, 2021 |
| ASUSTek       | A88XM-PLUS                  | [16fa85e296](https://linux-hardware.org/?probe=16fa85e296) | Dec 03, 2021 |
| ASRock        | ConRoe1333-D667             | [dce4f3f103](https://linux-hardware.org/?probe=dce4f3f103) | Dec 03, 2021 |
| HP            | 0AECh D                     | [b9550ddc31](https://linux-hardware.org/?probe=b9550ddc31) | Dec 03, 2021 |
| HP            | 0AECh D                     | [61d0324f27](https://linux-hardware.org/?probe=61d0324f27) | Dec 03, 2021 |
| MSI           | B450M-A PRO MAX             | [17a6983b50](https://linux-hardware.org/?probe=17a6983b50) | Dec 03, 2021 |
| Gigabyte      | 970A-DS3P                   | [054aa7b858](https://linux-hardware.org/?probe=054aa7b858) | Dec 02, 2021 |
| Lenovo        | NO DPK                      | [0d7784e414](https://linux-hardware.org/?probe=0d7784e414) | Dec 02, 2021 |
| Gigabyte      | X570 UD                     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [876f4598f0](https://linux-hardware.org/?probe=876f4598f0) | Dec 01, 2021 |
| HP            | 212B                        | [b8688e6712](https://linux-hardware.org/?probe=b8688e6712) | Dec 01, 2021 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [0e0cd0b225](https://linux-hardware.org/?probe=0e0cd0b225) | Dec 01, 2021 |
| OEM           | TOP77D Ver1.0               | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| MSI           | B460M-A PRO                 | [f972dc5e2a](https://linux-hardware.org/?probe=f972dc5e2a) | Nov 30, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [b3f648de8e](https://linux-hardware.org/?probe=b3f648de8e) | Nov 29, 2021 |
| ECS           | G31T-M7                     | [749da166c4](https://linux-hardware.org/?probe=749da166c4) | Nov 29, 2021 |
| ASRock        | G31M-VS                     | [b042297ea5](https://linux-hardware.org/?probe=b042297ea5) | Nov 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8c2024b822](https://linux-hardware.org/?probe=8c2024b822) | Nov 28, 2021 |
| Dell          | 0WR7PY A01                  | [f886714ec5](https://linux-hardware.org/?probe=f886714ec5) | Nov 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [17bd2e3558](https://linux-hardware.org/?probe=17bd2e3558) | Nov 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [629e6cac75](https://linux-hardware.org/?probe=629e6cac75) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [88cf97c553](https://linux-hardware.org/?probe=88cf97c553) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [59f124bbad](https://linux-hardware.org/?probe=59f124bbad) | Nov 27, 2021 |
| Pegatron      | 2A86E01                     | [17a1186394](https://linux-hardware.org/?probe=17a1186394) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [551c45ed6b](https://linux-hardware.org/?probe=551c45ed6b) | Nov 26, 2021 |
| HP            | 2129                        | [8379f5fd56](https://linux-hardware.org/?probe=8379f5fd56) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [58da56c671](https://linux-hardware.org/?probe=58da56c671) | Nov 26, 2021 |
| Gigabyte      | H77M-D3H                    | [a2606aebd8](https://linux-hardware.org/?probe=a2606aebd8) | Nov 26, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [52d32ab3be](https://linux-hardware.org/?probe=52d32ab3be) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1c3cabc42a](https://linux-hardware.org/?probe=1c3cabc42a) | Nov 25, 2021 |
| MSI           | MPG Z590 GAMING CARBON W... | [651bc7560d](https://linux-hardware.org/?probe=651bc7560d) | Nov 25, 2021 |
| Acer          | G31T-M5                     | [a561aa834a](https://linux-hardware.org/?probe=a561aa834a) | Nov 25, 2021 |
| Gigabyte      | 970A-D3P                    | [76e0745afc](https://linux-hardware.org/?probe=76e0745afc) | Nov 24, 2021 |
| ASRock        | A320M-HDV R4.0              | [e7ab7b2011](https://linux-hardware.org/?probe=e7ab7b2011) | Nov 24, 2021 |
| MSI           | H510I PRO WIFI              | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [148f8b6de1](https://linux-hardware.org/?probe=148f8b6de1) | Nov 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | [011f4ef64a](https://linux-hardware.org/?probe=011f4ef64a) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [021d70dbf2](https://linux-hardware.org/?probe=021d70dbf2) | Nov 24, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [bcf9812525](https://linux-hardware.org/?probe=bcf9812525) | Nov 24, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [dab9856bd1](https://linux-hardware.org/?probe=dab9856bd1) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9bd8ca78c3](https://linux-hardware.org/?probe=9bd8ca78c3) | Nov 24, 2021 |
| HP            | 3397                        | [5412dd8b52](https://linux-hardware.org/?probe=5412dd8b52) | Nov 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [2d5ec95a93](https://linux-hardware.org/?probe=2d5ec95a93) | Nov 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [3fcd092ee3](https://linux-hardware.org/?probe=3fcd092ee3) | Nov 23, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [8e73316539](https://linux-hardware.org/?probe=8e73316539) | Nov 23, 2021 |
| ASUSTek       | PRIME Z590-P                | [69fe9cde99](https://linux-hardware.org/?probe=69fe9cde99) | Nov 23, 2021 |
| Unknown       | Unknown                     | [57364e93b2](https://linux-hardware.org/?probe=57364e93b2) | Nov 23, 2021 |
| MSI           | PRO Z690-A DDR4             | [1022ba26e4](https://linux-hardware.org/?probe=1022ba26e4) | Nov 22, 2021 |
| JGINYUE       | H97I PLUS V2.0              | [fcefb22fe5](https://linux-hardware.org/?probe=fcefb22fe5) | Nov 22, 2021 |
| Gigabyte      | A320M-DS2-CF                | [02020c5820](https://linux-hardware.org/?probe=02020c5820) | Nov 22, 2021 |
| Gigabyte      | B75M-D3H                    | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [4c603f8b64](https://linux-hardware.org/?probe=4c603f8b64) | Nov 22, 2021 |
| Dell          | 0C27VV A00                  | [d3a7b5b39b](https://linux-hardware.org/?probe=d3a7b5b39b) | Nov 22, 2021 |
| Unknown       | Unknown                     | [ebc991da95](https://linux-hardware.org/?probe=ebc991da95) | Nov 22, 2021 |
| ASRock        | X99M Extreme4               | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASRock        | Z390 Extreme4               | [12f1aecfc3](https://linux-hardware.org/?probe=12f1aecfc3) | Nov 21, 2021 |
| ASUSTek       | P5L-VM 1394                 | [a43426b94f](https://linux-hardware.org/?probe=a43426b94f) | Nov 21, 2021 |
| ASUSTek       | M2N                         | [06bba5770c](https://linux-hardware.org/?probe=06bba5770c) | Nov 21, 2021 |
| HP            | 0AECh D                     | [4edef515e0](https://linux-hardware.org/?probe=4edef515e0) | Nov 21, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [64591821a6](https://linux-hardware.org/?probe=64591821a6) | Nov 20, 2021 |
| Lenovo        | ThinkServer TS140           | [da5af2478e](https://linux-hardware.org/?probe=da5af2478e) | Nov 20, 2021 |
| MSI           | PRO Z690-A DDR4             | [64e545e8b1](https://linux-hardware.org/?probe=64e545e8b1) | Nov 20, 2021 |
| Dell          | 0Y5DDC A00                  | [9f04ac4715](https://linux-hardware.org/?probe=9f04ac4715) | Nov 20, 2021 |
| Fujitsu       | FujitsuTP7000 -1            | [a509f56734](https://linux-hardware.org/?probe=a509f56734) | Nov 20, 2021 |
| ASUSTek       | M2N                         | [dfc5087439](https://linux-hardware.org/?probe=dfc5087439) | Nov 20, 2021 |
| ASRock        | Z690 Steel Legend           | [73afa3e4f2](https://linux-hardware.org/?probe=73afa3e4f2) | Nov 19, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [50dbf1ce3d](https://linux-hardware.org/?probe=50dbf1ce3d) | Nov 19, 2021 |
| MSI           | Z170A SLI                   | [2705718ac8](https://linux-hardware.org/?probe=2705718ac8) | Nov 19, 2021 |
| Gigabyte      | A320M-H-CF                  | [8eeef70a27](https://linux-hardware.org/?probe=8eeef70a27) | Nov 19, 2021 |
| MSI           | Z270 GAMING PLUS            | [28b50f68d2](https://linux-hardware.org/?probe=28b50f68d2) | Nov 19, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [a1261a6eca](https://linux-hardware.org/?probe=a1261a6eca) | Nov 19, 2021 |
| HP            | ProLiant ML350 Gen9         | [9a5ec34f4b](https://linux-hardware.org/?probe=9a5ec34f4b) | Nov 18, 2021 |
| HP            | 0AECh D                     | [e52cea7894](https://linux-hardware.org/?probe=e52cea7894) | Nov 18, 2021 |
| HP            | 304Ah                       | [988e1e374a](https://linux-hardware.org/?probe=988e1e374a) | Nov 18, 2021 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [61ba55d34f](https://linux-hardware.org/?probe=61ba55d34f) | Nov 18, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [c754a471ba](https://linux-hardware.org/?probe=c754a471ba) | Nov 17, 2021 |
| MSI           | Z97-G45 GAMING              | [fc7a1caa36](https://linux-hardware.org/?probe=fc7a1caa36) | Nov 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8377977aee](https://linux-hardware.org/?probe=8377977aee) | Nov 17, 2021 |
| Gigabyte      | Z77X-UD5H                   | [f1cd45b49a](https://linux-hardware.org/?probe=f1cd45b49a) | Nov 17, 2021 |
| HP            | 1494                        | [a1e8628159](https://linux-hardware.org/?probe=a1e8628159) | Nov 17, 2021 |
| Gigabyte      | Z690 UD DDR4                | [8435741705](https://linux-hardware.org/?probe=8435741705) | Nov 17, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e460a37b0f](https://linux-hardware.org/?probe=e460a37b0f) | Nov 17, 2021 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2c5829a148](https://linux-hardware.org/?probe=2c5829a148) | Nov 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3cc581951b](https://linux-hardware.org/?probe=3cc581951b) | Nov 17, 2021 |
| MSI           | H270 GAMING M3              | [d863ad50dd](https://linux-hardware.org/?probe=d863ad50dd) | Nov 16, 2021 |
| Dell          | 0FM586                      | [79a63f7f55](https://linux-hardware.org/?probe=79a63f7f55) | Nov 16, 2021 |
| MSI           | PRO Z690-A DDR4             | [63c901cb53](https://linux-hardware.org/?probe=63c901cb53) | Nov 16, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [22cf0835fb](https://linux-hardware.org/?probe=22cf0835fb) | Nov 16, 2021 |
| Dell          | 088DT1 A00                  | [0a20b8ab82](https://linux-hardware.org/?probe=0a20b8ab82) | Nov 16, 2021 |
| MSI           | MEG B550 UNIFY-X            | [c50d253bab](https://linux-hardware.org/?probe=c50d253bab) | Nov 16, 2021 |
| MSI           | MEG B550 UNIFY-X            | [d9142d6737](https://linux-hardware.org/?probe=d9142d6737) | Nov 16, 2021 |
| HP            | 8056                        | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| ASRock        | Z590M-ITX/ax                | [aa81c59d8a](https://linux-hardware.org/?probe=aa81c59d8a) | Nov 16, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [1eac89d527](https://linux-hardware.org/?probe=1eac89d527) | Nov 15, 2021 |
| Gigabyte      | A320M-H-CF                  | [a8e3d44c9e](https://linux-hardware.org/?probe=a8e3d44c9e) | Nov 15, 2021 |
| MSI           | MS-7250                     | [84c50a42f3](https://linux-hardware.org/?probe=84c50a42f3) | Nov 15, 2021 |
| Dell          | 0HJ054                      | [f7dee29940](https://linux-hardware.org/?probe=f7dee29940) | Nov 14, 2021 |
| Dell          | 0VRWRC A01                  | [e202cef308](https://linux-hardware.org/?probe=e202cef308) | Nov 14, 2021 |
| Pegatron      | 2AB6                        | [3f03379235](https://linux-hardware.org/?probe=3f03379235) | Nov 14, 2021 |
| HP            | 1998                        | [2e830badd5](https://linux-hardware.org/?probe=2e830badd5) | Nov 14, 2021 |
| ASUSTek       | PRIME Z370-A                | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| ASUSTek       | Z87-EXPERT                  | [445090e2b7](https://linux-hardware.org/?probe=445090e2b7) | Nov 14, 2021 |
| Dell          | 0HJ054                      | [298206106c](https://linux-hardware.org/?probe=298206106c) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ae75212ce](https://linux-hardware.org/?probe=7ae75212ce) | Nov 13, 2021 |
| ASUSTek       | H110M-C                     | [594c61d37a](https://linux-hardware.org/?probe=594c61d37a) | Nov 13, 2021 |
| MSI           | MS-7346                     | [66b30282c8](https://linux-hardware.org/?probe=66b30282c8) | Nov 13, 2021 |
| Acer          | RS780DV                     | [415847f244](https://linux-hardware.org/?probe=415847f244) | Nov 13, 2021 |
| Dell          | 0Y5DDC A00                  | [66188284bd](https://linux-hardware.org/?probe=66188284bd) | Nov 13, 2021 |
| Dell          | 0WMJ54 A01                  | [12892e0de3](https://linux-hardware.org/?probe=12892e0de3) | Nov 13, 2021 |
| Acer          | RS780DV                     | [610927f2e1](https://linux-hardware.org/?probe=610927f2e1) | Nov 12, 2021 |
| Gigabyte      | Z690 UD DDR4                | [7f1c2cfc0b](https://linux-hardware.org/?probe=7f1c2cfc0b) | Nov 12, 2021 |
| Dell          | 0WMJ54 A01                  | [eccf63021f](https://linux-hardware.org/?probe=eccf63021f) | Nov 12, 2021 |
| MSI           | B75MA-P45                   | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [27171367d8](https://linux-hardware.org/?probe=27171367d8) | Nov 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [15600f6f21](https://linux-hardware.org/?probe=15600f6f21) | Nov 11, 2021 |
| Dell          | 08HPGT A02                  | [9bf3a3f311](https://linux-hardware.org/?probe=9bf3a3f311) | Nov 10, 2021 |
| ASRock        | Z370 Pro4                   | [e0856ca7fa](https://linux-hardware.org/?probe=e0856ca7fa) | Nov 10, 2021 |
| HP            | 1494                        | [b748a69ed1](https://linux-hardware.org/?probe=b748a69ed1) | Nov 10, 2021 |
| ASRock        | A300M-STX                   | [712e203294](https://linux-hardware.org/?probe=712e203294) | Nov 10, 2021 |
| Gigabyte      | GA-790XTA-UD4               | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| ASUSTek       | P5QP18L/T5-P5G41E           | [c64c41d162](https://linux-hardware.org/?probe=c64c41d162) | Nov 10, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [da9d9b9d1e](https://linux-hardware.org/?probe=da9d9b9d1e) | Nov 10, 2021 |
| EVGA          | 111-CS-E371                 | [fd202c951f](https://linux-hardware.org/?probe=fd202c951f) | Nov 09, 2021 |
| Gigabyte      | B85M-D2V                    | [6fbd588373](https://linux-hardware.org/?probe=6fbd588373) | Nov 09, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [2458e67cf5](https://linux-hardware.org/?probe=2458e67cf5) | Nov 09, 2021 |
| MSI           | B350M PRO-VDH               | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | 1998                        | [c2ab98c42f](https://linux-hardware.org/?probe=c2ab98c42f) | Nov 07, 2021 |
| ASUSTek       | H87-PLUS                    | [a699d4683c](https://linux-hardware.org/?probe=a699d4683c) | Nov 07, 2021 |
| MSI           | MAG B550M MORTAR            | [35b24a070f](https://linux-hardware.org/?probe=35b24a070f) | Nov 07, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3cf5d9865c](https://linux-hardware.org/?probe=3cf5d9865c) | Nov 07, 2021 |
| HP            | 0A98h                       | [faff7d4f1b](https://linux-hardware.org/?probe=faff7d4f1b) | Nov 07, 2021 |
| MSI           | MEG X570 UNIFY              | [651ac91f37](https://linux-hardware.org/?probe=651ac91f37) | Nov 06, 2021 |
| Lenovo        | ThinkCentre A62 9935B5U     | [85db2ee229](https://linux-hardware.org/?probe=85db2ee229) | Nov 06, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [9ceab9ce1b](https://linux-hardware.org/?probe=9ceab9ce1b) | Nov 06, 2021 |
| Lenovo        | SHARKBAY No DPK             | [92be8f6c8b](https://linux-hardware.org/?probe=92be8f6c8b) | Nov 06, 2021 |
| HP            | Compaq 8200 Elite SFF PC    | [8227932323](https://linux-hardware.org/?probe=8227932323) | Nov 06, 2021 |
| Dell          | 088DT1 A00                  | [1c0647daa9](https://linux-hardware.org/?probe=1c0647daa9) | Nov 05, 2021 |
| Gigabyte      | H510M S2H                   | [1a749d9336](https://linux-hardware.org/?probe=1a749d9336) | Nov 05, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [6d1875bdd9](https://linux-hardware.org/?probe=6d1875bdd9) | Nov 04, 2021 |
| MSI           | A75MA-G55                   | [ccdd789559](https://linux-hardware.org/?probe=ccdd789559) | Nov 04, 2021 |
| MSI           | B150 PC MATE                | [3fdd2f72ac](https://linux-hardware.org/?probe=3fdd2f72ac) | Nov 04, 2021 |
| Dell          | 0NW73C A00                  | [b02dd0e75e](https://linux-hardware.org/?probe=b02dd0e75e) | Nov 04, 2021 |
| MSI           | 3664h                       | [f2547bae94](https://linux-hardware.org/?probe=f2547bae94) | Nov 03, 2021 |
| Gigabyte      | GA-MA74GMT-S2               | [a94050d3b2](https://linux-hardware.org/?probe=a94050d3b2) | Nov 03, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| ASUSTek       | Z97-K                       | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| Dell          | 0N826N A03                  | [d7d0a0b507](https://linux-hardware.org/?probe=d7d0a0b507) | Nov 03, 2021 |
| HP            | 18E8                        | [bd9d548890](https://linux-hardware.org/?probe=bd9d548890) | Nov 03, 2021 |
| Gigabyte      | EP45-UD3R                   | [30d809be04](https://linux-hardware.org/?probe=30d809be04) | Nov 03, 2021 |
| MSI           | Z370M MORTAR                | [b6d4cdb6b9](https://linux-hardware.org/?probe=b6d4cdb6b9) | Nov 03, 2021 |
| MSI           | Z370M MORTAR                | [af4e356569](https://linux-hardware.org/?probe=af4e356569) | Nov 03, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [2e8569e851](https://linux-hardware.org/?probe=2e8569e851) | Nov 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [290c114444](https://linux-hardware.org/?probe=290c114444) | Nov 02, 2021 |
| ASUSTek       | M3N78                       | [07562bbf08](https://linux-hardware.org/?probe=07562bbf08) | Nov 01, 2021 |
| MSI           | B550-A PRO                  | [ee7c2851a5](https://linux-hardware.org/?probe=ee7c2851a5) | Nov 01, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [e4aeb69a18](https://linux-hardware.org/?probe=e4aeb69a18) | Nov 01, 2021 |
| EVGA          | Z390 FTW                    | [22e9e0f01b](https://linux-hardware.org/?probe=22e9e0f01b) | Nov 01, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [2bee1e8a30](https://linux-hardware.org/?probe=2bee1e8a30) | Nov 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [3676c4f8f0](https://linux-hardware.org/?probe=3676c4f8f0) | Nov 01, 2021 |
| EVGA          | 134-KS-E377                 | [27e29303bc](https://linux-hardware.org/?probe=27e29303bc) | Nov 01, 2021 |
| EVGA          | 111-CS-E371                 | [2fc377709d](https://linux-hardware.org/?probe=2fc377709d) | Nov 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [068bee7912](https://linux-hardware.org/?probe=068bee7912) | Oct 31, 2021 |
| Gigabyte      | G1.Assassin                 | [40c84c9637](https://linux-hardware.org/?probe=40c84c9637) | Oct 31, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [5b55e39c35](https://linux-hardware.org/?probe=5b55e39c35) | Oct 31, 2021 |
| ASUSTek       | M2N-E                       | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| HP            | 1587h                       | [2aeea457fd](https://linux-hardware.org/?probe=2aeea457fd) | Oct 31, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [e13dd10e78](https://linux-hardware.org/?probe=e13dd10e78) | Oct 31, 2021 |
| Gigabyte      | G31M-ES2L                   | [23b6458508](https://linux-hardware.org/?probe=23b6458508) | Oct 30, 2021 |
| ASUSTek       | PRIME H310T R2.0            | [9f69e439bc](https://linux-hardware.org/?probe=9f69e439bc) | Oct 30, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [0184e22e18](https://linux-hardware.org/?probe=0184e22e18) | Oct 30, 2021 |
| ASRock        | 960GM/U3S3 FX               | [7a2ec5ecff](https://linux-hardware.org/?probe=7a2ec5ecff) | Oct 30, 2021 |
| HP            | 0AA8h                       | [40da7a8ae9](https://linux-hardware.org/?probe=40da7a8ae9) | Oct 30, 2021 |
| Dell          | 0N826N A03                  | [ffb75356ef](https://linux-hardware.org/?probe=ffb75356ef) | Oct 30, 2021 |
| MSI           | 3664h                       | [7d44291de8](https://linux-hardware.org/?probe=7d44291de8) | Oct 30, 2021 |
| MSI           | B450M MORTAR MAX            | [cadb142111](https://linux-hardware.org/?probe=cadb142111) | Oct 29, 2021 |
| MSI           | B150M BAZOOKA               | [b396e1c4f4](https://linux-hardware.org/?probe=b396e1c4f4) | Oct 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [2ce7e668c7](https://linux-hardware.org/?probe=2ce7e668c7) | Oct 29, 2021 |
| Dell          | 0N826N A03                  | [db2a7eba35](https://linux-hardware.org/?probe=db2a7eba35) | Oct 29, 2021 |
| HP            | 0AECh D                     | [665bae2867](https://linux-hardware.org/?probe=665bae2867) | Oct 29, 2021 |
| Dell          | 0C3YXR A00                  | [3fbbe71d21](https://linux-hardware.org/?probe=3fbbe71d21) | Oct 28, 2021 |
| Dell          | 0773VG A00                  | [f17f22efdc](https://linux-hardware.org/?probe=f17f22efdc) | Oct 28, 2021 |
| ASUSTek       | CM6870                      | [1575e2c682](https://linux-hardware.org/?probe=1575e2c682) | Oct 28, 2021 |
| MSI           | A88X-G43                    | [1c7a02bd63](https://linux-hardware.org/?probe=1c7a02bd63) | Oct 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d10e4364a0](https://linux-hardware.org/?probe=d10e4364a0) | Oct 27, 2021 |
| Foxconn       | 2ABF                        | [380d5ab9f0](https://linux-hardware.org/?probe=380d5ab9f0) | Oct 27, 2021 |
| Dell          | 05CNYF A01                  | [95530db3a8](https://linux-hardware.org/?probe=95530db3a8) | Oct 27, 2021 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [0e8d69e9b8](https://linux-hardware.org/?probe=0e8d69e9b8) | Oct 27, 2021 |
| Acer          | Aspire X3450                | [8f27aff70b](https://linux-hardware.org/?probe=8f27aff70b) | Oct 27, 2021 |
| Gigabyte      | GA-970A-UD3                 | [aae0c56d3a](https://linux-hardware.org/?probe=aae0c56d3a) | Oct 27, 2021 |
| MSI           | H61M-P31                    | [e5bf692305](https://linux-hardware.org/?probe=e5bf692305) | Oct 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [16a6718949](https://linux-hardware.org/?probe=16a6718949) | Oct 26, 2021 |
| MSI           | Z270 PC MATE                | [24329438d1](https://linux-hardware.org/?probe=24329438d1) | Oct 26, 2021 |
| Unknown       | Unknown                     | [668f61352d](https://linux-hardware.org/?probe=668f61352d) | Oct 26, 2021 |
| ASRock        | Z590M-ITX/ax                | [1fcc4e6895](https://linux-hardware.org/?probe=1fcc4e6895) | Oct 26, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [f5ede0a97c](https://linux-hardware.org/?probe=f5ede0a97c) | Oct 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [97620628a8](https://linux-hardware.org/?probe=97620628a8) | Oct 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f15c4d9b54](https://linux-hardware.org/?probe=f15c4d9b54) | Oct 25, 2021 |
| Gigabyte      | P67A-UD3                    | [ecaeb257a3](https://linux-hardware.org/?probe=ecaeb257a3) | Oct 24, 2021 |
| Dell          | 0V8F20 A01                  | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| Dell          | 0J3C2F A01                  | [e8cf16b696](https://linux-hardware.org/?probe=e8cf16b696) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [9333e233d6](https://linux-hardware.org/?probe=9333e233d6) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [7d78a3c31f](https://linux-hardware.org/?probe=7d78a3c31f) | Oct 24, 2021 |
| ASUSTek       | H110M-C                     | [ba3ddf870d](https://linux-hardware.org/?probe=ba3ddf870d) | Oct 24, 2021 |
| ASUSTek       | PRIME Z390-P                | [681b537e82](https://linux-hardware.org/?probe=681b537e82) | Oct 23, 2021 |
| Acer          | Aspire TC-281               | [5114976821](https://linux-hardware.org/?probe=5114976821) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [6e3084cf7f](https://linux-hardware.org/?probe=6e3084cf7f) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [c1808f5d2f](https://linux-hardware.org/?probe=c1808f5d2f) | Oct 23, 2021 |
| Dell          | 0T10XW A00                  | [971b85f5db](https://linux-hardware.org/?probe=971b85f5db) | Oct 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | [48db1afdd3](https://linux-hardware.org/?probe=48db1afdd3) | Oct 23, 2021 |
| Supermicro    | X7DVL                       | [bcbe094156](https://linux-hardware.org/?probe=bcbe094156) | Oct 23, 2021 |
| Dell          | 051FJ8 A02                  | [d04dae2a56](https://linux-hardware.org/?probe=d04dae2a56) | Oct 23, 2021 |
| MSI           | MEG X570 UNIFY              | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | NO DPK                      | [ad7c805198](https://linux-hardware.org/?probe=ad7c805198) | Oct 22, 2021 |
| Dell          | 0J3C2F A01                  | [a5ca7f2501](https://linux-hardware.org/?probe=a5ca7f2501) | Oct 22, 2021 |
| Gigabyte      | B550 AORUS PRO              | [f5c3648170](https://linux-hardware.org/?probe=f5c3648170) | Oct 22, 2021 |
| Gigabyte      | B75M-D3H                    | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [5fea6b8b9a](https://linux-hardware.org/?probe=5fea6b8b9a) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [eb508ab31e](https://linux-hardware.org/?probe=eb508ab31e) | Oct 22, 2021 |
| ICP / iEi     | SA58 V1.01                  | [bca4498e5d](https://linux-hardware.org/?probe=bca4498e5d) | Oct 21, 2021 |
| Dell          | 0200DY A01                  | [c67a8bb677](https://linux-hardware.org/?probe=c67a8bb677) | Oct 21, 2021 |
| Gigabyte      | B450M S2H                   | [71c19b42fc](https://linux-hardware.org/?probe=71c19b42fc) | Oct 21, 2021 |
| Google        | Guado                       | [5aba3d29f4](https://linux-hardware.org/?probe=5aba3d29f4) | Oct 21, 2021 |
| Google        | Guado                       | [2393c52b33](https://linux-hardware.org/?probe=2393c52b33) | Oct 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | [b914028ca9](https://linux-hardware.org/?probe=b914028ca9) | Oct 20, 2021 |
| ASRock        | TRX40 Creator               | [8789f3f1e1](https://linux-hardware.org/?probe=8789f3f1e1) | Oct 20, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [1d5227420f](https://linux-hardware.org/?probe=1d5227420f) | Oct 20, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [b961168b44](https://linux-hardware.org/?probe=b961168b44) | Oct 20, 2021 |
| ASUSTek       | Q87M-E                      | [a549c95cbd](https://linux-hardware.org/?probe=a549c95cbd) | Oct 20, 2021 |
| MSI           | 2A9C                        | [a47442aa1f](https://linux-hardware.org/?probe=a47442aa1f) | Oct 19, 2021 |
| Gigabyte      | H61M-S1                     | [9978664bd7](https://linux-hardware.org/?probe=9978664bd7) | Oct 19, 2021 |
| Gigabyte      | H61M-S1                     | [b0fb0061f2](https://linux-hardware.org/?probe=b0fb0061f2) | Oct 19, 2021 |
| ASUSTek       | P7P55 LX                    | [d2e3eb969f](https://linux-hardware.org/?probe=d2e3eb969f) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [92647c0170](https://linux-hardware.org/?probe=92647c0170) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [c7372168fd](https://linux-hardware.org/?probe=c7372168fd) | Oct 18, 2021 |
| ASRock        | Z87 Extreme4                | [2ec87a3f6f](https://linux-hardware.org/?probe=2ec87a3f6f) | Oct 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7e6f5e6e9f](https://linux-hardware.org/?probe=7e6f5e6e9f) | Oct 18, 2021 |
| Acer          | Aspire XC600 v1.0           | [56dd661396](https://linux-hardware.org/?probe=56dd661396) | Oct 18, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | [6522d9dc18](https://linux-hardware.org/?probe=6522d9dc18) | Oct 18, 2021 |
| HP            | 1998                        | [3228ce7734](https://linux-hardware.org/?probe=3228ce7734) | Oct 18, 2021 |
| EPSON DIRE... | ST170E                      | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [fcc82222d9](https://linux-hardware.org/?probe=fcc82222d9) | Oct 17, 2021 |
| MSI           | Z77A-G45                    | [3d516c23c5](https://linux-hardware.org/?probe=3d516c23c5) | Oct 17, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| Gigabyte      | Z77-D3H                     | [f7ffa54af0](https://linux-hardware.org/?probe=f7ffa54af0) | Oct 17, 2021 |
| Gigabyte      | M68MT-S2P                   | [d10202fe29](https://linux-hardware.org/?probe=d10202fe29) | Oct 17, 2021 |
| ASRock        | B560M-HDV                   | [200bfff8ba](https://linux-hardware.org/?probe=200bfff8ba) | Oct 17, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [122a03804e](https://linux-hardware.org/?probe=122a03804e) | Oct 17, 2021 |
| Intel         | DG31PR AAE39516-304         | [b6addf8d7b](https://linux-hardware.org/?probe=b6addf8d7b) | Oct 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [dd6513e107](https://linux-hardware.org/?probe=dd6513e107) | Oct 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [35b768567f](https://linux-hardware.org/?probe=35b768567f) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| HP            | 870C                        | [8b056a8a9f](https://linux-hardware.org/?probe=8b056a8a9f) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [8b50d81590](https://linux-hardware.org/?probe=8b50d81590) | Oct 16, 2021 |
| Dell          | 0G214D A00                  | [69857eb3a8](https://linux-hardware.org/?probe=69857eb3a8) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7f15c21293](https://linux-hardware.org/?probe=7f15c21293) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [6e15fcad52](https://linux-hardware.org/?probe=6e15fcad52) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [6499d1cf77](https://linux-hardware.org/?probe=6499d1cf77) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [a456734f94](https://linux-hardware.org/?probe=a456734f94) | Oct 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [e646d30e4f](https://linux-hardware.org/?probe=e646d30e4f) | Oct 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [152b670fcb](https://linux-hardware.org/?probe=152b670fcb) | Oct 15, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [22b047f0a1](https://linux-hardware.org/?probe=22b047f0a1) | Oct 15, 2021 |
| ASRock        | 990FX Extreme3              | [5de7270820](https://linux-hardware.org/?probe=5de7270820) | Oct 11, 2021 |
| ASRock        | 990FX Extreme3              | [b4eb4dbe24](https://linux-hardware.org/?probe=b4eb4dbe24) | Oct 11, 2021 |
| Dell          | 0Y2MRG A00                  | [d60ca7a452](https://linux-hardware.org/?probe=d60ca7a452) | Oct 09, 2021 |
| HP            | 3647h                       | [729a9e9683](https://linux-hardware.org/?probe=729a9e9683) | Oct 05, 2021 |
| ASRock        | X370 Killer SLI/ac          | [52d4dd8f39](https://linux-hardware.org/?probe=52d4dd8f39) | Oct 02, 2021 |
| Dell          | 0RY007                      | [4e574a8988](https://linux-hardware.org/?probe=4e574a8988) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [db26b44773](https://linux-hardware.org/?probe=db26b44773) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [3be52ed98f](https://linux-hardware.org/?probe=3be52ed98f) | Oct 02, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [b6f82cf92b](https://linux-hardware.org/?probe=b6f82cf92b) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| ASUSTek       | A68HM-PLUS                  | [8ea8e6afe8](https://linux-hardware.org/?probe=8ea8e6afe8) | Sep 30, 2021 |
| ASRock        | 990FX Extreme4              | [9c631b51b1](https://linux-hardware.org/?probe=9c631b51b1) | Sep 28, 2021 |
| Gigabyte      | H81M-D2V                    | [e8749db36a](https://linux-hardware.org/?probe=e8749db36a) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [b05cdb0bab](https://linux-hardware.org/?probe=b05cdb0bab) | Sep 26, 2021 |
| ASRock        | X399M Taichi                | [eba541c6b9](https://linux-hardware.org/?probe=eba541c6b9) | Sep 25, 2021 |
| Gigabyte      | H81M-S                      | [357f7466e6](https://linux-hardware.org/?probe=357f7466e6) | Sep 25, 2021 |
| ASRock        | Z390M Pro4                  | [138ae00012](https://linux-hardware.org/?probe=138ae00012) | Sep 23, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Gigabyte      | B85M-D3H                    | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| HP            | 3032h                       | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Huanan        | X99 F8D V2.2                | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Huanan        | X99 F8D V2.2                | [30fe8d6bb3](https://linux-hardware.org/?probe=30fe8d6bb3) | Aug 26, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| MSI           | MAG B550M MORTAR            | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| Huanan        | X99 F8D V2.2                | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_21.10/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.13.0-22-generic           | 101      | 13.08%  |
| 5.13.0-19-generic           | 90       | 11.66%  |
| 5.13.0-21-generic           | 84       | 10.88%  |
| 5.13.0-39-generic           | 73       | 9.46%   |
| 5.13.0-20-generic           | 72       | 9.33%   |
| 5.13.0-28-generic           | 41       | 5.31%   |
| 5.13.0-27-generic           | 36       | 4.66%   |
| 5.13.0-30-generic           | 35       | 4.53%   |
| 5.13.0-35-generic           | 34       | 4.4%    |
| 5.13.0-40-generic           | 32       | 4.15%   |
| 5.13.0-37-generic           | 29       | 3.76%   |
| 5.13.0-23-generic           | 26       | 3.37%   |
| 5.13.0-25-generic           | 22       | 2.85%   |
| 5.13.0-52-generic           | 14       | 1.81%   |
| 5.13.0-16-generic           | 12       | 1.55%   |
| 5.13.0-41-generic           | 8        | 1.04%   |
| 5.15.2-051502-generic       | 5        | 0.65%   |
| 5.13.0-44-generic           | 5        | 0.65%   |
| 5.13.0-14-generic           | 3        | 0.39%   |
| 5.14.0-051400rc7-lowlatency | 2        | 0.26%   |
| 5.13.0-48-generic           | 2        | 0.26%   |
| 5.13.0-40-lowlatency        | 2        | 0.26%   |
| 5.13.0-37-lowlatency        | 2        | 0.26%   |
| 5.13.0-35-lowlatency        | 2        | 0.26%   |
| 5.13.0-32-generic           | 2        | 0.26%   |
| 5.13.0-29-generic           | 2        | 0.26%   |
| 5.13.0-272202022022-generic | 2        | 0.26%   |
| 5.13.0-24-generic           | 2        | 0.26%   |
| 5.13.0-22-lowlatency        | 2        | 0.26%   |
| 5.13.0-192110311031-generic | 2        | 0.26%   |
| 5.13.0-17-generic           | 2        | 0.26%   |
| 5.13.0-12-generic           | 2        | 0.26%   |
| 5.8.0-50-generic            | 1        | 0.13%   |
| 5.17.3-051703-generic       | 1        | 0.13%   |
| 5.17.1-051701-generic       | 1        | 0.13%   |
| 5.17.0-2.2-liquorix-amd64   | 1        | 0.13%   |
| 5.16.3-051603-generic       | 1        | 0.13%   |
| 5.16.18-051618-generic      | 1        | 0.13%   |
| 5.16.1-tkg-pds              | 1        | 0.13%   |
| 5.16.0-18.1-liquorix-amd64  | 1        | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 686      | 96.48%  |
| 5.15.2  | 5        | 0.7%    |
| 5.11.0  | 4        | 0.56%   |
| 5.16.0  | 2        | 0.28%   |
| 5.14.14 | 2        | 0.28%   |
| 5.14.0  | 2        | 0.28%   |
| 5.8.0   | 1        | 0.14%   |
| 5.17.3  | 1        | 0.14%   |
| 5.17.1  | 1        | 0.14%   |
| 5.17.0  | 1        | 0.14%   |
| 5.16.3  | 1        | 0.14%   |
| 5.16.18 | 1        | 0.14%   |
| 5.16.1  | 1        | 0.14%   |
| 5.15.11 | 1        | 0.14%   |
| 5.15.0  | 1        | 0.14%   |
| 5.13.19 | 1        | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 687      | 96.62%  |
| 5.15    | 7        | 0.98%   |
| 5.16    | 5        | 0.7%    |
| 5.14    | 4        | 0.56%   |
| 5.11    | 4        | 0.56%   |
| 5.17    | 3        | 0.42%   |
| 5.8     | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 709      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 657      | 92.15%  |
| Unknown         | 35       | 4.91%   |
| X-Cinnamon      | 8        | 1.12%   |
| GNOME Flashback | 5        | 0.7%    |
| i3              | 2        | 0.28%   |
| Cinnamon        | 2        | 0.28%   |
| sway            | 1        | 0.14%   |
| openbox         | 1        | 0.14%   |
| kde             | 1        | 0.14%   |
| awesome         | 1        | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 388      | 54.27%  |
| X11     | 293      | 40.98%  |
| Tty     | 24       | 3.36%   |
| Unknown | 10       | 1.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 464      | 65.17%  |
| GDM     | 170      | 23.88%  |
| Unknown | 59       | 8.29%   |
| LightDM | 13       | 1.83%   |
| SDDM    | 6        | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 273      | 38.24%  |
| de_DE       | 129      | 18.07%  |
| fr_FR       | 36       | 5.04%   |
| en_GB       | 27       | 3.78%   |
| it_IT       | 25       | 3.5%    |
| pt_BR       | 24       | 3.36%   |
| en_CA       | 20       | 2.8%    |
| en_AU       | 19       | 2.66%   |
| es_ES       | 16       | 2.24%   |
| C           | 15       | 2.1%    |
| pl_PL       | 12       | 1.68%   |
| ru_RU       | 10       | 1.4%    |
| ja_JP       | 9        | 1.26%   |
| en_IN       | 9        | 1.26%   |
| hu_HU       | 7        | 0.98%   |
| nl_NL       | 6        | 0.84%   |
| es_AR       | 5        | 0.7%    |
| de_CH       | 5        | 0.7%    |
| zh_CN       | 4        | 0.56%   |
| sv_SE       | 4        | 0.56%   |
| es_MX       | 4        | 0.56%   |
| el_GR       | 4        | 0.56%   |
| de_AT       | 4        | 0.56%   |
| cs_CZ       | 4        | 0.56%   |
| ru_UA       | 3        | 0.42%   |
| fr_BE       | 3        | 0.42%   |
| zh_TW       | 2        | 0.28%   |
| pt_PT       | 2        | 0.28%   |
| nb_NO       | 2        | 0.28%   |
| fi_FI       | 2        | 0.28%   |
| et_EE       | 2        | 0.28%   |
| es_PE       | 2        | 0.28%   |
| en_PH       | 2        | 0.28%   |
| da_DK       | 2        | 0.28%   |
| ar_EG       | 2        | 0.28%   |
| Unknown     | 2        | 0.28%   |
| tr_TR       | 1        | 0.14%   |
| sr_RS@latin | 1        | 0.14%   |
| sk_SK       | 1        | 0.14%   |
| nl_BE       | 1        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 545      | 76.22%  |
| EFI  | 170      | 23.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 638      | 89.99%  |
| Overlay | 31       | 4.37%   |
| Zfs     | 18       | 2.54%   |
| Btrfs   | 15       | 2.12%   |
| Xfs     | 4        | 0.56%   |
| Ext2    | 2        | 0.28%   |
| Ext3    | 1        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 516      | 72.68%  |
| GPT     | 169      | 23.8%   |
| MBR     | 25       | 3.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 573      | 79.81%  |
| Yes       | 145      | 20.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 397      | 55.84%  |
| Yes       | 314      | 44.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUSTek Computer       | 176      | 24.82%  |
| Gigabyte Technology    | 112      | 15.8%   |
| MSI                    | 108      | 15.23%  |
| Dell                   | 66       | 9.31%   |
| ASRock                 | 62       | 8.74%   |
| Hewlett-Packard        | 59       | 8.32%   |
| Lenovo                 | 22       | 3.1%    |
| Acer                   | 13       | 1.83%   |
| Intel                  | 9        | 1.27%   |
| Unknown                | 8        | 1.13%   |
| Medion                 | 7        | 0.99%   |
| Fujitsu                | 7        | 0.99%   |
| Foxconn                | 7        | 0.99%   |
| Biostar                | 6        | 0.85%   |
| EVGA                   | 5        | 0.71%   |
| Pegatron               | 4        | 0.56%   |
| Packard Bell           | 4        | 0.56%   |
| Huanan                 | 4        | 0.56%   |
| ECS                    | 3        | 0.42%   |
| Supermicro             | 2        | 0.28%   |
| Positivo               | 2        | 0.28%   |
| Minix                  | 2        | 0.28%   |
| Google                 | 2        | 0.28%   |
| BESSTAR Tech           | 2        | 0.28%   |
| Apple                  | 2        | 0.28%   |
| AMI                    | 2        | 0.28%   |
| ZYREX COMPUTER SYSTEMS | 1        | 0.14%   |
| TYAN Computer          | 1        | 0.14%   |
| Seco                   | 1        | 0.14%   |
| PCWare                 | 1        | 0.14%   |
| OEM                    | 1        | 0.14%   |
| NF541                  | 1        | 0.14%   |
| MACHINIST              | 1        | 0.14%   |
| JGINYUE                | 1        | 0.14%   |
| ICP / iEi              | 1        | 0.14%   |
| Fujitsu Siemens        | 1        | 0.14%   |
| EPSON DIRECT           | 1        | 0.14%   |
| DFI                    | 1        | 0.14%   |
| Alienware              | 1        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 25       | 3.53%   |
| Dell OptiPlex 7010         | 8        | 1.13%   |
| Unknown                    | 8        | 1.13%   |
| MSI MS-7D25                | 5        | 0.71%   |
| MSI MS-7817                | 5        | 0.71%   |
| Dell OptiPlex 9010         | 5        | 0.71%   |
| Dell OptiPlex 790          | 5        | 0.71%   |
| MSI MS-7B86                | 4        | 0.56%   |
| HP Z800 Workstation        | 4        | 0.56%   |
| HP ProDesk 600 G1 SFF      | 4        | 0.56%   |
| Dell OptiPlex 3020         | 4        | 0.56%   |
| ASUS TUF Gaming X570-PLUS  | 4        | 0.56%   |
| ASUS PRIME B450M-A         | 4        | 0.56%   |
| MSI MS-7C94                | 3        | 0.42%   |
| MSI MS-7C52                | 3        | 0.42%   |
| MSI MS-7C37                | 3        | 0.42%   |
| MSI MS-7C35                | 3        | 0.42%   |
| MSI MS-7C02                | 3        | 0.42%   |
| MSI MS-7B79                | 3        | 0.42%   |
| MSI MS-7917                | 3        | 0.42%   |
| HP EliteDesk 800 G2 SFF    | 3        | 0.42%   |
| HP EliteDesk 800 G1 SFF    | 3        | 0.42%   |
| HP Compaq Elite 8300 USDT  | 3        | 0.42%   |
| Gigabyte X570 AORUS MASTER | 3        | 0.42%   |
| Gigabyte GA-78LMT-USB3     | 3        | 0.42%   |
| Gigabyte B450M DS3H        | 3        | 0.42%   |
| Dell OptiPlex 780          | 3        | 0.42%   |
| ASUS TUF Gaming B550-PLUS  | 3        | 0.42%   |
| ASUS PRIME Z690-P WIFI D4  | 3        | 0.42%   |
| ASUS PRIME A320M-K         | 3        | 0.42%   |
| MSI MS-7C95                | 2        | 0.28%   |
| MSI MS-7C80                | 2        | 0.28%   |
| MSI MS-7C56                | 2        | 0.28%   |
| MSI MS-7B98                | 2        | 0.28%   |
| MSI MS-7B85                | 2        | 0.28%   |
| MSI MS-7B84                | 2        | 0.28%   |
| MSI MS-7B09                | 2        | 0.28%   |
| MSI MS-7A38                | 2        | 0.28%   |
| MSI MS-7A15                | 2        | 0.28%   |
| MSI MS-7821                | 2        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 43       | 6.06%   |
| ASUS PRIME             | 35       | 4.94%   |
| ASUS All               | 25       | 3.53%   |
| ASUS ROG               | 20       | 2.82%   |
| HP Compaq              | 17       | 2.4%    |
| Lenovo ThinkCentre     | 13       | 1.83%   |
| ASUS TUF               | 12       | 1.69%   |
| HP ProDesk             | 9        | 1.27%   |
| HP EliteDesk           | 9        | 1.27%   |
| Dell Inspiron          | 9        | 1.27%   |
| Gigabyte X570          | 8        | 1.13%   |
| Acer Aspire            | 8        | 1.13%   |
| Unknown                | 8        | 1.13%   |
| Gigabyte B450M         | 6        | 0.85%   |
| Dell Precision         | 6        | 0.85%   |
| MSI MS-7D25            | 5        | 0.71%   |
| MSI MS-7817            | 5        | 0.71%   |
| Gigabyte GA-78LMT-USB3 | 5        | 0.71%   |
| MSI MS-7B86            | 4        | 0.56%   |
| HP Z800                | 4        | 0.56%   |
| HP Pavilion            | 4        | 0.56%   |
| Fujitsu ESPRIMO        | 4        | 0.56%   |
| Dell XPS               | 4        | 0.56%   |
| ASUS M5A78L-M          | 4        | 0.56%   |
| MSI MS-7C94            | 3        | 0.42%   |
| MSI MS-7C52            | 3        | 0.42%   |
| MSI MS-7C37            | 3        | 0.42%   |
| MSI MS-7C35            | 3        | 0.42%   |
| MSI MS-7C02            | 3        | 0.42%   |
| MSI MS-7B79            | 3        | 0.42%   |
| MSI MS-7917            | 3        | 0.42%   |
| Gigabyte Z690          | 3        | 0.42%   |
| Gigabyte B550          | 3        | 0.42%   |
| Gigabyte B450          | 3        | 0.42%   |
| ASUS Pro               | 3        | 0.42%   |
| ASUS P8Z77-V           | 3        | 0.42%   |
| ASUS P8H61-M           | 3        | 0.42%   |
| ASUS M5A97             | 3        | 0.42%   |
| ASRock B450M           | 3        | 0.42%   |
| Acer Predator          | 3        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 71       | 10.01%  |
| 2012 | 69       | 9.73%   |
| 2013 | 62       | 8.74%   |
| 2021 | 60       | 8.46%   |
| 2020 | 60       | 8.46%   |
| 2019 | 59       | 8.32%   |
| 2014 | 57       | 8.04%   |
| 2011 | 49       | 6.91%   |
| 2017 | 41       | 5.78%   |
| 2009 | 35       | 4.94%   |
| 2008 | 34       | 4.8%    |
| 2010 | 33       | 4.65%   |
| 2015 | 31       | 4.37%   |
| 2016 | 20       | 2.82%   |
| 2007 | 19       | 2.68%   |
| 2006 | 8        | 1.13%   |
| 2005 | 1        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 709      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 697      | 97.89%  |
| Enabled  | 15       | 2.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 706      | 99.58%  |
| Yes  | 3        | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 168      | 23.6%   |
| 32.01-64.0      | 134      | 18.82%  |
| 4.01-8.0        | 123      | 17.28%  |
| 8.01-16.0       | 121      | 16.99%  |
| 3.01-4.0        | 88       | 12.36%  |
| 64.01-256.0     | 43       | 6.04%   |
| 24.01-32.0      | 16       | 2.25%   |
| 1.01-2.0        | 16       | 2.25%   |
| More than 256.0 | 2        | 0.28%   |
| 2.01-3.0        | 1        | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 302      | 40.65%  |
| 2.01-3.0   | 209      | 28.13%  |
| 4.01-8.0   | 110      | 14.8%   |
| 3.01-4.0   | 84       | 11.31%  |
| 8.01-16.0  | 23       | 3.1%    |
| 0.51-1.0   | 10       | 1.35%   |
| 32.01-64.0 | 2        | 0.27%   |
| 16.01-24.0 | 2        | 0.27%   |
| 0.01-0.5   | 1        | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 286      | 39.56%  |
| 2      | 190      | 26.28%  |
| 3      | 99       | 13.69%  |
| 4      | 70       | 9.68%   |
| 5      | 42       | 5.81%   |
| 6      | 14       | 1.94%   |
| 7      | 7        | 0.97%   |
| 0      | 6        | 0.83%   |
| 11     | 5        | 0.69%   |
| 8      | 2        | 0.28%   |
| 45     | 1        | 0.14%   |
| 13     | 1        | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 372      | 52.25%  |
| Yes       | 340      | 47.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 703      | 99.15%  |
| No        | 6        | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 386      | 54.14%  |
| Yes       | 327      | 45.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 480      | 67.04%  |
| Yes       | 236      | 32.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 152      | 21.44%  |
| Germany      | 142      | 20.03%  |
| France       | 39       | 5.5%    |
| UK           | 31       | 4.37%   |
| Brazil       | 31       | 4.37%   |
| Italy        | 30       | 4.23%   |
| Canada       | 24       | 3.39%   |
| Australia    | 18       | 2.54%   |
| Russia       | 16       | 2.26%   |
| Switzerland  | 15       | 2.12%   |
| Poland       | 15       | 2.12%   |
| Spain        | 14       | 1.97%   |
| Sweden       | 11       | 1.55%   |
| Netherlands  | 10       | 1.41%   |
| India        | 10       | 1.41%   |
| Japan        | 9        | 1.27%   |
| Hungary      | 9        | 1.27%   |
| Mexico       | 8        | 1.13%   |
| Ukraine      | 7        | 0.99%   |
| Argentina    | 7        | 0.99%   |
| Greece       | 6        | 0.85%   |
| Finland      | 6        | 0.85%   |
| Czechia      | 6        | 0.85%   |
| Belgium      | 6        | 0.85%   |
| Serbia       | 5        | 0.71%   |
| China        | 5        | 0.71%   |
| Norway       | 4        | 0.56%   |
| Lithuania    | 4        | 0.56%   |
| Denmark      | 4        | 0.56%   |
| Austria      | 4        | 0.56%   |
| Taiwan       | 3        | 0.42%   |
| South Africa | 3        | 0.42%   |
| Peru         | 3        | 0.42%   |
| New Zealand  | 3        | 0.42%   |
| Indonesia    | 3        | 0.42%   |
| Estonia      | 3        | 0.42%   |
| Chile        | 3        | 0.42%   |
| Turkey       | 2        | 0.28%   |
| Thailand     | 2        | 0.28%   |
| South Korea  | 2        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Cleveland         | 12       | 1.66%   |
| Berlin            | 9        | 1.25%   |
| Sao Paulo         | 7        | 0.97%   |
| Stuttgart         | 6        | 0.83%   |
| Milan             | 6        | 0.83%   |
| Toronto           | 5        | 0.69%   |
| Paris             | 5        | 0.69%   |
| Madrid            | 5        | 0.69%   |
| Warsaw            | 4        | 0.55%   |
| Vilnius           | 4        | 0.55%   |
| Sydney            | 4        | 0.55%   |
| San Francisco     | 4        | 0.55%   |
| Budapest          | 4        | 0.55%   |
| Bristol           | 4        | 0.55%   |
| Wuhan             | 3        | 0.42%   |
| Wiesbaden         | 3        | 0.42%   |
| Västerås        | 3        | 0.42%   |
| Phoenix           | 3        | 0.42%   |
| Perth             | 3        | 0.42%   |
| Munich            | 3        | 0.42%   |
| Moscow            | 3        | 0.42%   |
| Mayen             | 3        | 0.42%   |
| Lima              | 3        | 0.42%   |
| Houston           | 3        | 0.42%   |
| Hamburg           | 3        | 0.42%   |
| Frankfurt am Main | 3        | 0.42%   |
| El Paso           | 3        | 0.42%   |
| Dubuque           | 3        | 0.42%   |
| Dresden           | 3        | 0.42%   |
| Brisbane          | 3        | 0.42%   |
| Zdanice           | 2        | 0.28%   |
| Wroclaw           | 2        | 0.28%   |
| Washington        | 2        | 0.28%   |
| Vladivostok       | 2        | 0.28%   |
| Vienna            | 2        | 0.28%   |
| Tijuana           | 2        | 0.28%   |
| Thessaloniki      | 2        | 0.28%   |
| Tehran            | 2        | 0.28%   |
| Tallinn           | 2        | 0.28%   |
| Stockholm         | 2        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 251      | 371    | 19.84%  |
| Seagate                   | 226      | 342    | 17.87%  |
| Samsung Electronics       | 216      | 351    | 17.08%  |
| Kingston                  | 73       | 92     | 5.77%   |
| SanDisk                   | 62       | 90     | 4.9%    |
| Toshiba                   | 60       | 92     | 4.74%   |
| Crucial                   | 55       | 72     | 4.35%   |
| Hitachi                   | 48       | 83     | 3.79%   |
| A-DATA Technology         | 22       | 26     | 1.74%   |
| Intel                     | 19       | 24     | 1.5%    |
| Unknown                   | 17       | 24     | 1.34%   |
| Silicon Motion            | 15       | 20     | 1.19%   |
| PNY                       | 15       | 19     | 1.19%   |
| Phison                    | 15       | 18     | 1.19%   |
| HGST                      | 13       | 19     | 1.03%   |
| Corsair                   | 8        | 10     | 0.63%   |
| Maxtor                    | 7        | 7      | 0.55%   |
| Intenso                   | 7        | 8      | 0.55%   |
| Unknown                   | 7        | 7      | 0.55%   |
| SK hynix                  | 6        | 15     | 0.47%   |
| Phison Electronics        | 6        | 7      | 0.47%   |
| Micron/Crucial Technology | 6        | 6      | 0.47%   |
| China                     | 6        | 8      | 0.47%   |
| OCZ                       | 5        | 7      | 0.4%    |
| Team                      | 4        | 4      | 0.32%   |
| SPCC                      | 4        | 4      | 0.32%   |
| Realtek Semiconductor     | 4        | 4      | 0.32%   |
| Patriot                   | 4        | 4      | 0.32%   |
| Micron Technology         | 4        | 6      | 0.32%   |
| JMicron Technology        | 4        | 4      | 0.32%   |
| GOODRAM                   | 4        | 5      | 0.32%   |
| Gigabyte Technology       | 4        | 5      | 0.32%   |
| SABRENT                   | 3        | 3      | 0.24%   |
| Netac                     | 3        | 4      | 0.24%   |
| LITEON                    | 3        | 3      | 0.24%   |
| Lexar                     | 3        | 4      | 0.24%   |
| Hewlett-Packard           | 3        | 3      | 0.24%   |
| ASMT                      | 3        | 4      | 0.24%   |
| XPG                       | 2        | 2      | 0.16%   |
| Transcend                 | 2        | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 20       | 1.32%   |
| Seagate ST500DM002-1BD142 500GB  | 18       | 1.19%   |
| Samsung SSD 850 EVO 250GB        | 17       | 1.13%   |
| Seagate ST2000DM008-2FR102 2TB   | 16       | 1.06%   |
| Samsung NVMe SSD Drive 1TB       | 16       | 1.06%   |
| Samsung NVMe SSD Drive 250GB     | 15       | 0.99%   |
| Samsung SSD 860 EVO 1TB          | 14       | 0.93%   |
| Samsung SSD 850 EVO 500GB        | 14       | 0.93%   |
| Samsung SSD 860 EVO 500GB        | 12       | 0.79%   |
| Samsung SSD 970 EVO 500GB        | 11       | 0.73%   |
| Samsung NVMe SSD Drive 500GB     | 11       | 0.73%   |
| Seagate ST1000DM003-1ER162 1TB   | 10       | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB   | 10       | 0.66%   |
| Crucial CT500MX500SSD1 500GB     | 10       | 0.66%   |
| Toshiba DT01ACA100 1TB           | 9        | 0.6%    |
| SanDisk NVMe SSD Drive 500GB     | 9        | 0.6%    |
| SanDisk NVMe SSD Drive 1TB       | 9        | 0.6%    |
| Kingston SA400S37480G 480GB SSD  | 9        | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB         | 8        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB   | 8        | 0.53%   |
| SanDisk SSD PLUS 240GB           | 8        | 0.53%   |
| Samsung SSD 860 EVO 250GB        | 8        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD | 8        | 0.53%   |
| Kingston SA400S37120G 120GB SSD  | 8        | 0.53%   |
| Hitachi HDS721010CLA332 1TB      | 8        | 0.53%   |
| Unknown SD/MMC/MS PRO 64GB       | 7        | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB   | 7        | 0.46%   |
| Seagate ST3500418AS 500GB        | 7        | 0.46%   |
| Seagate ST3500413AS 500GB        | 7        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB     | 7        | 0.46%   |
| Unknown                          | 7        | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 6        | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB         | 6        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 0.4%    |
| Seagate ST3500312CS 500GB        | 6        | 0.4%    |
| Seagate ST3250318AS 250GB        | 6        | 0.4%    |
| Seagate ST31000524AS 1TB         | 6        | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB   | 6        | 0.4%    |
| Seagate Expansion 4TB            | 6        | 0.4%    |
| Phison PCIe SSD 1TB              | 6        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 227      | 334    | 35.92%  |
| Seagate             | 225      | 339    | 35.6%   |
| Toshiba             | 54       | 81     | 8.54%   |
| Hitachi             | 48       | 83     | 7.59%   |
| Samsung Electronics | 38       | 51     | 6.01%   |
| HGST                | 13       | 19     | 2.06%   |
| Unknown             | 7        | 7      | 1.11%   |
| Maxtor              | 7        | 7      | 1.11%   |
| ASMT                | 3        | 4      | 0.47%   |
| Intenso             | 2        | 2      | 0.32%   |
| USB 3.0             | 1        | 1      | 0.16%   |
| Pioneer             | 1        | 1      | 0.16%   |
| Maxone              | 1        | 1      | 0.16%   |
| MARVELL             | 1        | 1      | 0.16%   |
| HGST HTS            | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 1      | 0.16%   |
| Unknown             | 1        | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 114      | 172    | 26.64%  |
| Kingston            | 60       | 77     | 14.02%  |
| Crucial             | 49       | 65     | 11.45%  |
| SanDisk             | 38       | 59     | 8.88%   |
| WDC                 | 28       | 29     | 6.54%   |
| A-DATA Technology   | 17       | 20     | 3.97%   |
| PNY                 | 12       | 15     | 2.8%    |
| Intel               | 10       | 13     | 2.34%   |
| Toshiba             | 8        | 9      | 1.87%   |
| China               | 6        | 8      | 1.4%    |
| OCZ                 | 5        | 7      | 1.17%   |
| Corsair             | 5        | 7      | 1.17%   |
| Team                | 4        | 4      | 0.93%   |
| SK hynix            | 4        | 6      | 0.93%   |
| Patriot             | 4        | 4      | 0.93%   |
| Micron Technology   | 4        | 6      | 0.93%   |
| Intenso             | 4        | 5      | 0.93%   |
| SPCC                | 3        | 3      | 0.7%    |
| Netac               | 3        | 4      | 0.7%    |
| LITEON              | 3        | 3      | 0.7%    |
| Lexar               | 3        | 4      | 0.7%    |
| JMicron Technology  | 3        | 3      | 0.7%    |
| GOODRAM             | 3        | 3      | 0.7%    |
| Gigabyte Technology | 3        | 4      | 0.7%    |
| Transcend           | 2        | 2      | 0.47%   |
| Plextor             | 2        | 3      | 0.47%   |
| Phison              | 2        | 3      | 0.47%   |
| LITEONIT            | 2        | 2      | 0.47%   |
| LDLC                | 2        | 2      | 0.47%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.47%   |
| KingDian            | 2        | 2      | 0.47%   |
| Hewlett-Packard     | 2        | 2      | 0.47%   |
| Apacer              | 2        | 2      | 0.47%   |
| Unknown             | 2        | 2      | 0.47%   |
| Unknown             | 1        | 1      | 0.23%   |
| TO Exter            | 1        | 3      | 0.23%   |
| StoreJet            | 1        | 1      | 0.23%   |
| Seagate             | 1        | 1      | 0.23%   |
| Q200                | 1        | 4      | 0.23%   |
| OYUNKEY             | 1        | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 481      | 935    | 45.46%  |
| SSD     | 348      | 575    | 32.89%  |
| NVMe    | 202      | 291    | 19.09%  |
| Unknown | 20       | 28     | 1.89%   |
| MMC     | 7        | 7      | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 630      | 1437   | 70.23%  |
| NVMe | 202      | 288    | 22.52%  |
| SAS  | 58       | 104    | 6.47%   |
| MMC  | 7        | 7      | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 453      | 771    | 48.61%  |
| 0.51-1.0   | 262      | 390    | 28.11%  |
| 1.01-2.0   | 112      | 168    | 12.02%  |
| 3.01-4.0   | 48       | 78     | 5.15%   |
| 2.01-3.0   | 28       | 43     | 3%      |
| 4.01-10.0  | 25       | 56     | 2.68%   |
| 10.01-20.0 | 3        | 3      | 0.32%   |
| 0          | 1        | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 188      | 25.9%   |
| 501-1000       | 120      | 16.53%  |
| 251-500        | 117      | 16.12%  |
| 1001-2000      | 86       | 11.85%  |
| More than 3000 | 62       | 8.54%   |
| 2001-3000      | 50       | 6.89%   |
| 1-20           | 49       | 6.75%   |
| 51-100         | 30       | 4.13%   |
| 21-50          | 18       | 2.48%   |
| Unknown        | 6        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 262      | 35.26%  |
| 21-50          | 120      | 16.15%  |
| 51-100         | 89       | 11.98%  |
| 101-250        | 86       | 11.57%  |
| 501-1000       | 49       | 6.59%   |
| 251-500        | 48       | 6.46%   |
| 1001-2000      | 43       | 5.79%   |
| More than 3000 | 25       | 3.36%   |
| 2001-3000      | 15       | 2.02%   |
| Unknown        | 6        | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD10EZEX-00BN5A0 1TB                     | 2        | 2      | 3.45%   |
| WDC WD10EARS-00Y5B1 1TB                      | 2        | 2      | 3.45%   |
| Seagate ST3500320AS 500GB                    | 2        | 2      | 3.45%   |
| Seagate ST31000528AS 1TB                     | 2        | 2      | 3.45%   |
| Seagate ST2000DM001-1CH164 2TB               | 2        | 2      | 3.45%   |
| Seagate ST1000DM003-1CH162 1TB               | 2        | 2      | 3.45%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2        | 2      | 3.45%   |
| WDC WD740GD-00FLA1 74GB                      | 1        | 1      | 1.72%   |
| WDC WD5000BPVT-00HXZT3 500GB                 | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-083CA1 500GB                  | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1        | 1      | 1.72%   |
| WDC WD3200SD-01KNB0 320GB                    | 1        | 2      | 1.72%   |
| WDC WD3200AAKS-75L9A0 320GB                  | 1        | 1      | 1.72%   |
| WDC WD30EZRX-00DC0B0 3TB                     | 1        | 1      | 1.72%   |
| WDC WD2500HHTZ-04N21V0 250GB                 | 1        | 1      | 1.72%   |
| WDC WD20EARX-00PASB0 2TB                     | 1        | 1      | 1.72%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1        | 1      | 1.72%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 1        | 1      | 1.72%   |
| WDC WD10EALX-009BA0 1TB                      | 1        | 1      | 1.72%   |
| WDC WD10EADS-00L5B1 1TB                      | 1        | 1      | 1.72%   |
| WDC WD1002FBYS-02A6B0 1TB                    | 1        | 1      | 1.72%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1        | 1      | 1.72%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1        | 1      | 1.72%   |
| Toshiba MQ01ABD100 1TB                       | 1        | 3      | 1.72%   |
| Toshiba MK5055GSXF 500GB                     | 1        | 1      | 1.72%   |
| SK hynix HFS256G32MND-2200A 256GB SSD        | 1        | 1      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 1.72%   |
| Seagate ST3500418AS 500GB                    | 1        | 1      | 1.72%   |
| Seagate ST3250823AS 250GB                    | 1        | 1      | 1.72%   |
| Seagate ST32000644NS 59Y5483 59Y1807IBMV 2TB | 1        | 1      | 1.72%   |
| Seagate ST3120813AS 120GB                    | 1        | 1      | 1.72%   |
| Seagate ST3000DM008-2DM166 3TB               | 1        | 1      | 1.72%   |
| Seagate ST3000DM001-1ER166 3TB               | 1        | 1      | 1.72%   |
| Seagate ST2000DL003-9VT166 2TB               | 1        | 1      | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1        | 1      | 1.72%   |
| Seagate ST1000DM003-9YN162 1TB               | 1        | 1      | 1.72%   |
| SanDisk SSD PLUS 240GB                       | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1        | 1      | 1.72%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB   | 1        | 1      | 1.72%   |
| Samsung Electronics HM121HI 120GB            | 1        | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 21     | 35.71%  |
| Seagate             | 17       | 18     | 30.36%  |
| Samsung Electronics | 5        | 6      | 8.93%   |
| Hitachi             | 4        | 4      | 7.14%   |
| Toshiba             | 2        | 4      | 3.57%   |
| Kingston            | 2        | 2      | 3.57%   |
| SK hynix            | 1        | 1      | 1.79%   |
| SanDisk             | 1        | 1      | 1.79%   |
| Patriot             | 1        | 1      | 1.79%   |
| Micron Technology   | 1        | 1      | 1.79%   |
| Maxtor              | 1        | 1      | 1.79%   |
| Intel               | 1        | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 21     | 43.48%  |
| Seagate             | 17       | 18     | 36.96%  |
| Hitachi             | 4        | 4      | 8.7%    |
| Toshiba             | 2        | 4      | 4.35%   |
| Samsung Electronics | 2        | 2      | 4.35%   |
| Maxtor              | 1        | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 50     | 82%     |
| SSD  | 8        | 10     | 16%     |
| NVMe | 1        | 1      | 2%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST31000520AS 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 521      | 1318   | 68.19%  |
| Works    | 195      | 456    | 25.52%  |
| Malfunc  | 47       | 61     | 6.15%   |
| Failed   | 1        | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 475      | 46.03%  |
| AMD                           | 214      | 20.74%  |
| Samsung Electronics           | 93       | 9.01%   |
| Marvell Technology Group      | 34       | 3.29%   |
| JMicron Technology            | 31       | 3%      |
| SanDisk                       | 30       | 2.91%   |
| ASMedia Technology            | 28       | 2.71%   |
| Phison Electronics            | 27       | 2.62%   |
| Silicon Motion                | 17       | 1.65%   |
| Nvidia                        | 13       | 1.26%   |
| Kingston Technology Company   | 12       | 1.16%   |
| Micron/Crucial Technology     | 11       | 1.07%   |
| Realtek Semiconductor         | 6        | 0.58%   |
| LSI Logic / Symbios Logic     | 6        | 0.58%   |
| Broadcom / LSI                | 6        | 0.58%   |
| ADATA Technology              | 4        | 0.39%   |
| Toshiba America Info Systems  | 3        | 0.29%   |
| SK hynix                      | 3        | 0.29%   |
| Silicon Image                 | 3        | 0.29%   |
| Integrated Technology Express | 3        | 0.29%   |
| VIA Technologies              | 2        | 0.19%   |
| Adaptec                       | 2        | 0.19%   |
| Shenzhen Longsys Electronics  | 1        | 0.1%    |
| Seagate Technology            | 1        | 0.1%    |
| Micron Technology             | 1        | 0.1%    |
| MAXIO Technology (Hangzhou)   | 1        | 0.1%    |
| Lite-On IT Corp. / Plextor    | 1        | 0.1%    |
| KIOXIA                        | 1        | 0.1%    |
| Hewlett-Packard               | 1        | 0.1%    |
| Advanced System Products      | 1        | 0.1%    |
| 3ware                         | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 118      | 9.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 66       | 5.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 57       | 4.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 46       | 3.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 38       | 2.98%   |
| Intel SATA Controller [RAID mode]                                                       | 37       | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 37       | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 36       | 2.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 34       | 2.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29       | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 28       | 2.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 27       | 2.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 26       | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25       | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 24       | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 23       | 1.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 20       | 1.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 18       | 1.41%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 17       | 1.33%   |
| Phison E12 NVMe Controller                                                              | 16       | 1.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16       | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 15       | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15       | 1.18%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 15       | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14       | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14       | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13       | 1.02%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 13       | 1.02%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 12       | 0.94%   |
| AMD FCH SATA Controller D                                                               | 12       | 0.94%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 11       | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 10       | 0.78%   |
| JMicron JMB368 IDE controller                                                           | 10       | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9        | 0.71%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 9        | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 8        | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                         | 8        | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8        | 0.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 8        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 565      | 55.23%  |
| NVMe | 200      | 19.55%  |
| IDE  | 175      | 17.11%  |
| RAID | 66       | 6.45%   |
| SCSI | 10       | 0.98%   |
| SAS  | 7        | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 482      | 67.98%  |
| AMD    | 227      | 32.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700K CPU @ 3.70GHz           | 13       | 1.83%   |
| AMD Ryzen 5 3600 6-Core Processor           | 13       | 1.83%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 12       | 1.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 1.55%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 11       | 1.55%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 11       | 1.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 10       | 1.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 10       | 1.41%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 9        | 1.27%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 1.27%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 8        | 1.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 1.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 1.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 8        | 1.13%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 8        | 1.13%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 1.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 8        | 1.13%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 7        | 0.99%   |
| Intel 12th Gen Core i7-12700K               | 7        | 0.99%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 0.99%   |
| AMD FX-6300 Six-Core Processor              | 7        | 0.99%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 6        | 0.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6        | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 0.85%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 6        | 0.85%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 0.85%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 5        | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5        | 0.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 5        | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.7%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 5        | 0.7%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 0.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.7%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 0.7%    |
| AMD FX-8320 Eight-Core Processor            | 5        | 0.7%    |
| AMD FX-4300 Quad-Core Processor             | 5        | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 125      | 17.61%  |
| Intel Core i7           | 121      | 17.04%  |
| Intel Core i3           | 57       | 8.03%   |
| AMD Ryzen 7             | 51       | 7.18%   |
| AMD Ryzen 5             | 48       | 6.76%   |
| Intel Xeon              | 36       | 5.07%   |
| Other                   | 28       | 3.94%   |
| Intel Core 2 Duo        | 24       | 3.38%   |
| AMD FX                  | 24       | 3.38%   |
| Intel Core 2 Quad       | 20       | 2.82%   |
| AMD Ryzen 9             | 20       | 2.82%   |
| Intel Celeron           | 18       | 2.54%   |
| Intel Core i9           | 15       | 2.11%   |
| AMD Ryzen 3             | 10       | 1.41%   |
| AMD Phenom II X4        | 10       | 1.41%   |
| Intel Pentium Dual-Core | 9        | 1.27%   |
| Intel Pentium           | 9        | 1.27%   |
| Intel Atom              | 7        | 0.99%   |
| AMD Ryzen Threadripper  | 7        | 0.99%   |
| AMD A8                  | 7        | 0.99%   |
| AMD Athlon II X2        | 6        | 0.85%   |
| AMD Athlon 64 X2        | 6        | 0.85%   |
| AMD A10                 | 6        | 0.85%   |
| AMD Phenom II X6        | 4        | 0.56%   |
| AMD A4                  | 4        | 0.56%   |
| Intel Pentium Gold      | 3        | 0.42%   |
| Intel Pentium Dual      | 3        | 0.42%   |
| Intel Core 2            | 3        | 0.42%   |
| AMD Ryzen 5 PRO         | 3        | 0.42%   |
| AMD Phenom II X2        | 3        | 0.42%   |
| AMD Athlon II X4        | 3        | 0.42%   |
| AMD A6                  | 3        | 0.42%   |
| Intel Pentium D         | 2        | 0.28%   |
| AMD Phenom              | 2        | 0.28%   |
| Intel Pentium Silver    | 1        | 0.14%   |
| Intel Pentium 4         | 1        | 0.14%   |
| Intel Genuine           | 1        | 0.14%   |
| Intel Celeron D         | 1        | 0.14%   |
| AMD Sempron             | 1        | 0.14%   |
| AMD Ryzen Embedded      | 1        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 270      | 38.08%  |
| 2      | 167      | 23.55%  |
| 6      | 102      | 14.39%  |
| 8      | 86       | 12.13%  |
| 12     | 32       | 4.51%   |
| 3      | 13       | 1.83%   |
| 16     | 12       | 1.69%   |
| 10     | 12       | 1.69%   |
| 1      | 9        | 1.27%   |
| 32     | 2        | 0.28%   |
| 24     | 2        | 0.28%   |
| 28     | 1        | 0.14%   |
| 14     | 1        | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 694      | 97.88%  |
| 2      | 15       | 2.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 411      | 57.89%  |
| 1      | 299      | 42.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 709      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 487      | 67.36%  |
| 0x306c3    | 20       | 2.77%   |
| 0x906ea    | 14       | 1.94%   |
| 0x90672    | 13       | 1.8%    |
| 0x206a7    | 13       | 1.8%    |
| 0x306a9    | 12       | 1.66%   |
| 0x906e9    | 11       | 1.52%   |
| 0x08701021 | 11       | 1.52%   |
| 0x1067a    | 9        | 1.24%   |
| 0x0a201016 | 8        | 1.11%   |
| 0x08701013 | 8        | 1.11%   |
| 0x06000852 | 7        | 0.97%   |
| 0xa0671    | 6        | 0.83%   |
| 0xa0655    | 6        | 0.83%   |
| 0x906ed    | 6        | 0.83%   |
| 0x506e3    | 6        | 0.83%   |
| 0x0a201009 | 6        | 0.83%   |
| 0x0800820d | 6        | 0.83%   |
| 0x206d7    | 5        | 0.69%   |
| 0x0a50000c | 5        | 0.69%   |
| 0x08001138 | 5        | 0.69%   |
| 0x106a5    | 4        | 0.55%   |
| 0x08108109 | 4        | 0.55%   |
| 0x706a8    | 2        | 0.28%   |
| 0x50654    | 2        | 0.28%   |
| 0x306f2    | 2        | 0.28%   |
| 0x306d4    | 2        | 0.28%   |
| 0x206c2    | 2        | 0.28%   |
| 0x10677    | 2        | 0.28%   |
| 0x10676    | 2        | 0.28%   |
| 0x0a201204 | 2        | 0.28%   |
| 0x08600103 | 2        | 0.28%   |
| 0x08108102 | 2        | 0.28%   |
| 0x08001137 | 2        | 0.28%   |
| 0x0600063e | 2        | 0.28%   |
| 0x010000dc | 2        | 0.28%   |
| 0x010000db | 2        | 0.28%   |
| 0xf65      | 1        | 0.14%   |
| 0xf47      | 1        | 0.14%   |
| 0xa0653    | 1        | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 94       | 13.26%  |
| KabyLake         | 73       | 10.3%   |
| IvyBridge        | 64       | 9.03%   |
| SandyBridge      | 52       | 7.33%   |
| Penryn           | 52       | 7.33%   |
| Zen 2            | 48       | 6.77%   |
| Zen 3            | 39       | 5.5%    |
| Piledriver       | 33       | 4.65%   |
| Zen+             | 32       | 4.51%   |
| K10              | 31       | 4.37%   |
| Skylake          | 28       | 3.95%   |
| Zen              | 23       | 3.24%   |
| CometLake        | 21       | 2.96%   |
| Core             | 17       | 2.4%    |
| Nehalem          | 16       | 2.26%   |
| Westmere         | 12       | 1.69%   |
| Alderlake Hybrid | 12       | 1.69%   |
| Unknown          | 10       | 1.41%   |
| K8 Hammer        | 7        | 0.99%   |
| Silvermont       | 6        | 0.85%   |
| Icelake          | 6        | 0.85%   |
| Excavator        | 6        | 0.85%   |
| Broadwell        | 6        | 0.85%   |
| Goldmont plus    | 5        | 0.71%   |
| NetBurst         | 4        | 0.56%   |
| Bulldozer        | 4        | 0.56%   |
| Bonnell          | 3        | 0.42%   |
| Steamroller      | 2        | 0.28%   |
| Puma             | 1        | 0.14%   |
| K10 Llano        | 1        | 0.14%   |
| Goldmont         | 1        | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 309      | 41.2%   |
| Intel                                        | 223      | 29.73%  |
| AMD                                          | 216      | 28.8%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.13%   |
| ASPEED Technology                            | 1        | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40       | 5.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 23       | 3.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 22       | 2.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 21       | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20       | 2.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18       | 2.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 13       | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13       | 1.7%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 12       | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 12       | 1.57%   |
| Intel HD Graphics 530                                                                    | 12       | 1.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 12       | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12       | 1.57%   |
| Intel HD Graphics 630                                                                    | 11       | 1.44%   |
| Intel AlderLake-S GT1                                                                    | 11       | 1.44%   |
| Nvidia GT218 [GeForce 210]                                                               | 10       | 1.31%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 10       | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10       | 1.31%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10       | 1.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10       | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 8        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 8        | 1.05%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 8        | 1.05%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 8        | 1.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7        | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 7        | 0.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 7        | 0.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7        | 0.92%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 6        | 0.79%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 6        | 0.79%   |
| AMD RS780L [Radeon 3000]                                                                 | 6        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 5        | 0.66%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 5        | 0.66%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 5        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5        | 0.66%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 5        | 0.66%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 5        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 286      | 40.17%  |
| 1 x AMD                  | 197      | 27.67%  |
| 1 x Intel                | 193      | 27.11%  |
| Intel + Nvidia           | 10       | 1.4%    |
| 2 x AMD                  | 7        | 0.98%   |
| Intel + AMD              | 6        | 0.84%   |
| 2 x Nvidia               | 5        | 0.7%    |
| AMD + Nvidia             | 5        | 0.7%    |
| 1 x XGI                  | 1        | 0.14%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.14%   |
| 1 x ASPEED               | 1        | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 503      | 70.25%  |
| Proprietary | 179      | 25%     |
| Unknown     | 34       | 4.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 501      | 70.17%  |
| 1.01-2.0   | 62       | 8.68%   |
| 7.01-8.0   | 36       | 5.04%   |
| 3.01-4.0   | 30       | 4.2%    |
| 0.51-1.0   | 30       | 4.2%    |
| 8.01-16.0  | 18       | 2.52%   |
| 0.01-0.5   | 16       | 2.24%   |
| 5.01-6.0   | 13       | 1.82%   |
| 2.01-3.0   | 7        | 0.98%   |
| 16.01-24.0 | 1        | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 118      | 15.67%  |
| Dell                 | 93       | 12.35%  |
| Goldstar             | 74       | 9.83%   |
| Acer                 | 46       | 6.11%   |
| Ancor Communications | 44       | 5.84%   |
| Hewlett-Packard      | 43       | 5.71%   |
| AOC                  | 40       | 5.31%   |
| Philips              | 36       | 4.78%   |
| BenQ                 | 26       | 3.45%   |
| Lenovo               | 17       | 2.26%   |
| ASUSTek Computer     | 16       | 2.12%   |
| ViewSonic            | 15       | 1.99%   |
| Unknown              | 15       | 1.99%   |
| Sony                 | 14       | 1.86%   |
| Iiyama               | 13       | 1.73%   |
| Vizio                | 8        | 1.06%   |
| NEC Computers        | 8        | 1.06%   |
| Medion               | 8        | 1.06%   |
| LG Electronics       | 7        | 0.93%   |
| Toshiba              | 5        | 0.66%   |
| Fujitsu Siemens      | 5        | 0.66%   |
| Eizo                 | 5        | 0.66%   |
| Panasonic            | 4        | 0.53%   |
| MSI                  | 4        | 0.53%   |
| Sceptre Tech         | 3        | 0.4%    |
| Packard Bell         | 3        | 0.4%    |
| IEI                  | 3        | 0.4%    |
| Hyundai ImageQuest   | 3        | 0.4%    |
| HJW                  | 3        | 0.4%    |
| HannStar             | 3        | 0.4%    |
| Denver               | 3        | 0.4%    |
| Compaq Computer      | 3        | 0.4%    |
| Westinghouse         | 2        | 0.27%   |
| VIZ                  | 2        | 0.27%   |
| UGD                  | 2        | 0.27%   |
| SKY                  | 2        | 0.27%   |
| OEM                  | 2        | 0.27%   |
| Hitachi              | 2        | 0.27%   |
| Gigabyte Technology  | 2        | 0.27%   |
| CVT                  | 2        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 6        | 0.75%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6        | 0.75%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5        | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.5%    |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 4        | 0.5%    |
| ASUSTek Computer VP278 AUS27AE 1920x1080 598x336mm 27.0-inch          | 4        | 0.5%    |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                        | 4        | 0.5%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4        | 0.5%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3        | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.38%   |
| Philips LCD Monitor FTV 1920x1080                                     | 3        | 0.38%   |
| IEI 150 IEI2044 1152x870 304x228mm 15.0-inch                          | 3        | 0.38%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 3        | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.38%   |
| Dell U2410 DELF016 1920x1200 520x320mm 24.0-inch                      | 3        | 0.38%   |
| Dell AW3418DW DELA0FA 3440x1440 798x335mm 34.1-inch                   | 3        | 0.38%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 3        | 0.38%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 0.38%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                      | 3        | 0.38%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 3        | 0.38%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 3        | 0.38%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                     | 3        | 0.38%   |
| Acer G246HYL ACR035B 1920x1080 527x296mm 23.8-inch                    | 3        | 0.38%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 2        | 0.25%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 0.25%   |
| ViewSonic PF790-2 VSC4500 1600x1200 353x265mm 17.4-inch               | 2        | 0.25%   |
| Unknown LCD Monitor XXX WXGA TV 1360x768                              | 2        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.25%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 2        | 0.25%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch   | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 2        | 0.25%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch     | 2        | 0.25%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch               | 2        | 0.25%   |
| Philips 220XW PHLC01B 1680x1050 474x297mm 22.0-inch                   | 2        | 0.25%   |
| Philips 220SW PHL086F 1680x1050 474x296mm 22.0-inch                   | 2        | 0.25%   |
| Philips 200CW PHLC019 1680x1050 460x300mm 21.6-inch                   | 2        | 0.25%   |
| Panasonic TV MEIC303 1920x1080 698x392mm 31.5-inch                    | 2        | 0.25%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 2        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 319      | 43.64%  |
| 3840x2160 (4K)     | 70       | 9.58%   |
| 1280x1024 (SXGA)   | 51       | 6.98%   |
| 1680x1050 (WSXGA+) | 50       | 6.84%   |
| 2560x1440 (QHD)    | 42       | 5.75%   |
| 1440x900 (WXGA+)   | 27       | 3.69%   |
| 1920x1200 (WUXGA)  | 25       | 3.42%   |
| 1366x768 (WXGA)    | 19       | 2.6%    |
| 1600x900 (HD+)     | 18       | 2.46%   |
| Unknown            | 18       | 2.46%   |
| 1360x768           | 16       | 2.19%   |
| 3440x1440          | 15       | 2.05%   |
| 2560x1080          | 14       | 1.92%   |
| 3840x1080          | 7        | 0.96%   |
| 1024x768 (XGA)     | 6        | 0.82%   |
| 1600x1200          | 5        | 0.68%   |
| 2560x1600          | 3        | 0.41%   |
| 2288x1287          | 3        | 0.41%   |
| 1920x540           | 3        | 0.41%   |
| 1400x1050          | 3        | 0.41%   |
| 4480x1440          | 2        | 0.27%   |
| 3200x1080          | 2        | 0.27%   |
| 1280x720 (HD)      | 2        | 0.27%   |
| 7280x1440          | 1        | 0.14%   |
| 5760x1080          | 1        | 0.14%   |
| 5520x2160          | 1        | 0.14%   |
| 4480x1080          | 1        | 0.14%   |
| 3840x1600          | 1        | 0.14%   |
| 3520x1200          | 1        | 0.14%   |
| 3360x1200          | 1        | 0.14%   |
| 3360x1050          | 1        | 0.14%   |
| 2048x1152          | 1        | 0.14%   |
| 1360x765           | 1        | 0.14%   |
| 1280x768           | 1        | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 108      | 14.63%  |
| 23      | 93       | 12.6%   |
| 24      | 87       | 11.79%  |
| 21      | 77       | 10.43%  |
| Unknown | 68       | 9.21%   |
| 19      | 44       | 5.96%   |
| 22      | 37       | 5.01%   |
| 17      | 30       | 4.07%   |
| 18      | 26       | 3.52%   |
| 34      | 24       | 3.25%   |
| 31      | 24       | 3.25%   |
| 20      | 22       | 2.98%   |
| 15      | 12       | 1.63%   |
| 84      | 9        | 1.22%   |
| 72      | 9        | 1.22%   |
| 40      | 9        | 1.22%   |
| 26      | 8        | 1.08%   |
| 54      | 5        | 0.68%   |
| 32      | 5        | 0.68%   |
| 29      | 4        | 0.54%   |
| 142     | 3        | 0.41%   |
| 49      | 3        | 0.41%   |
| 33      | 3        | 0.41%   |
| 28      | 3        | 0.41%   |
| 74      | 2        | 0.27%   |
| 65      | 2        | 0.27%   |
| 46      | 2        | 0.27%   |
| 42      | 2        | 0.27%   |
| 25      | 2        | 0.27%   |
| 75      | 1        | 0.14%   |
| 64      | 1        | 0.14%   |
| 63      | 1        | 0.14%   |
| 60      | 1        | 0.14%   |
| 59      | 1        | 0.14%   |
| 57      | 1        | 0.14%   |
| 52      | 1        | 0.14%   |
| 48      | 1        | 0.14%   |
| 41      | 1        | 0.14%   |
| 38      | 1        | 0.14%   |
| 37      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 269      | 37.78%  |
| 401-500        | 177      | 24.86%  |
| Unknown        | 68       | 9.55%   |
| 601-700        | 42       | 5.9%    |
| 301-350        | 36       | 5.06%   |
| 701-800        | 33       | 4.63%   |
| 351-400        | 28       | 3.93%   |
| 1501-2000      | 20       | 2.81%   |
| 1001-1500      | 19       | 2.67%   |
| 801-900        | 11       | 1.54%   |
| More than 2000 | 3        | 0.42%   |
| 201-300        | 3        | 0.42%   |
| 901-1000       | 3        | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 409      | 59.8%   |
| 16/10   | 106      | 15.5%   |
| Unknown | 62       | 9.06%   |
| 5/4     | 47       | 6.87%   |
| 21/9    | 30       | 4.39%   |
| 4/3     | 18       | 2.63%   |
| 3/2     | 5        | 0.73%   |
| 1.00    | 4        | 0.58%   |
| 6/5     | 3        | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 234      | 32.23%  |
| 301-350        | 115      | 15.84%  |
| 151-200        | 94       | 12.95%  |
| Unknown        | 68       | 9.37%   |
| 351-500        | 61       | 8.4%    |
| 141-150        | 42       | 5.79%   |
| More than 1000 | 40       | 5.51%   |
| 251-300        | 39       | 5.37%   |
| 501-1000       | 17       | 2.34%   |
| 101-110        | 11       | 1.52%   |
| 131-140        | 2        | 0.28%   |
| 71-80          | 1        | 0.14%   |
| 121-130        | 1        | 0.14%   |
| 91-100         | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 434      | 62.72%  |
| 101-120 | 117      | 16.91%  |
| Unknown | 68       | 9.83%   |
| 1-50    | 35       | 5.06%   |
| 121-160 | 24       | 3.47%   |
| 161-240 | 14       | 2.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 519      | 72.49%  |
| 2     | 133      | 18.58%  |
| 0     | 48       | 6.7%    |
| 3     | 15       | 2.09%   |
| 4     | 1        | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 433      | 42.91%  |
| Intel                           | 314      | 31.12%  |
| Qualcomm Atheros                | 67       | 6.64%   |
| Broadcom                        | 34       | 3.37%   |
| TP-Link                         | 30       | 2.97%   |
| Ralink Technology               | 19       | 1.88%   |
| Ralink                          | 10       | 0.99%   |
| Nvidia                          | 9        | 0.89%   |
| Marvell Technology Group        | 9        | 0.89%   |
| NetGear                         | 8        | 0.79%   |
| Qualcomm Atheros Communications | 7        | 0.69%   |
| Microsoft                       | 7        | 0.69%   |
| Aquantia                        | 6        | 0.59%   |
| MediaTek                        | 5        | 0.5%    |
| D-Link                          | 4        | 0.4%    |
| ASUSTek Computer                | 4        | 0.4%    |
| Samsung Electronics             | 3        | 0.3%    |
| Linksys                         | 3        | 0.3%    |
| D-Link System                   | 3        | 0.3%    |
| Broadcom Limited                | 3        | 0.3%    |
| Belkin Components               | 3        | 0.3%    |
| VIA Technologies                | 2        | 0.2%    |
| Micro Star International        | 2        | 0.2%    |
| DisplayLink                     | 2        | 0.2%    |
| AVM                             | 2        | 0.2%    |
| ASIX Electronics                | 2        | 0.2%    |
| Xiaomi                          | 1        | 0.1%    |
| Wilocity                        | 1        | 0.1%    |
| Wacom                           | 1        | 0.1%    |
| Tenda                           | 1        | 0.1%    |
| STMicroelectronics              | 1        | 0.1%    |
| SILICON Laboratories            | 1        | 0.1%    |
| OPPO Electronics                | 1        | 0.1%    |
| Montage                         | 1        | 0.1%    |
| Microchip Technology            | 1        | 0.1%    |
| Manta                           | 1        | 0.1%    |
| JMicron Technology              | 1        | 0.1%    |
| IMC Networks                    | 1        | 0.1%    |
| Google                          | 1        | 0.1%    |
| GDMicroelectronics              | 1        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 324      | 28.1%   |
| Realtek RTL8125 2.5GbE Controller                                 | 45       | 3.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42       | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 39       | 3.38%   |
| Intel Wi-Fi 6 AX200                                               | 38       | 3.3%    |
| Intel Ethernet Connection (2) I219-V                              | 31       | 2.69%   |
| Intel Ethernet Controller I225-V                                  | 21       | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 19       | 1.65%   |
| Intel Ethernet Connection (7) I219-V                              | 18       | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15       | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 12       | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 12       | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 11       | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 11       | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 11       | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 11       | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10       | 0.87%   |
| Ralink MT7601U Wireless Adapter                                   | 10       | 0.87%   |
| Intel Wireless-AC 9260                                            | 10       | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10       | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9        | 0.78%   |
| Realtek 802.11ac NIC                                              | 9        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 9        | 0.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 7        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 7        | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 7        | 0.61%   |
| Intel Wireless 7260                                               | 7        | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7        | 0.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 6        | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6        | 0.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 5        | 0.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.43%   |
| Intel Wireless 7265                                               | 5        | 0.43%   |
| Intel Wireless 3165                                               | 5        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 118      | 33.62%  |
| Realtek Semiconductor           | 75       | 21.37%  |
| Qualcomm Atheros                | 33       | 9.4%    |
| TP-Link                         | 29       | 8.26%   |
| Ralink Technology               | 19       | 5.41%   |
| Broadcom                        | 15       | 4.27%   |
| Ralink                          | 10       | 2.85%   |
| NetGear                         | 8        | 2.28%   |
| Qualcomm Atheros Communications | 7        | 1.99%   |
| Microsoft                       | 7        | 1.99%   |
| D-Link                          | 4        | 1.14%   |
| ASUSTek Computer                | 4        | 1.14%   |
| MediaTek                        | 3        | 0.85%   |
| Linksys                         | 3        | 0.85%   |
| D-Link System                   | 3        | 0.85%   |
| Belkin Components               | 3        | 0.85%   |
| Micro Star International        | 2        | 0.57%   |
| AVM                             | 2        | 0.57%   |
| Wilocity                        | 1        | 0.28%   |
| Wacom                           | 1        | 0.28%   |
| Tenda                           | 1        | 0.28%   |
| IMC Networks                    | 1        | 0.28%   |
| Elecom                          | 1        | 0.28%   |
| Broadcom Limited                | 1        | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 38       | 10.76%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12       | 3.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 11       | 3.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11       | 3.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10       | 2.83%   |
| Ralink MT7601U Wireless Adapter                                | 10       | 2.83%   |
| Intel Wireless-AC 9260                                         | 10       | 2.83%   |
| Realtek 802.11ac NIC                                           | 9        | 2.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 9        | 2.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 7        | 1.98%   |
| Qualcomm Atheros AR9271 802.11n                                | 7        | 1.98%   |
| Intel Wireless 7260                                            | 7        | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7        | 1.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7        | 1.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 6        | 1.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6        | 1.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 5        | 1.42%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 1.42%   |
| Intel Wireless 7265                                            | 5        | 1.42%   |
| Intel Wireless 3165                                            | 5        | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4        | 1.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4        | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4        | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 4        | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3        | 0.85%   |
| TP-Link 802.11n NIC                                            | 3        | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 3        | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 3        | 0.85%   |
| Ralink RT5372 Wireless Adapter                                 | 3        | 0.85%   |
| Ralink RT2800 802.11n PCI                                      | 3        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3        | 0.85%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3        | 0.85%   |
| Microsoft Wireless XBox Controller Dongle                      | 3        | 0.85%   |
| Intel Wireless 8260                                            | 3        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 0.85%   |
| D-Link 802.11 n WLAN                                           | 3        | 0.85%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 2        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 401      | 52.42%  |
| Intel                    | 267      | 34.9%   |
| Qualcomm Atheros         | 34       | 4.44%   |
| Broadcom                 | 19       | 2.48%   |
| Nvidia                   | 9        | 1.18%   |
| Marvell Technology Group | 9        | 1.18%   |
| Aquantia                 | 6        | 0.78%   |
| Samsung Electronics      | 3        | 0.39%   |
| VIA Technologies         | 2        | 0.26%   |
| MediaTek                 | 2        | 0.26%   |
| DisplayLink              | 2        | 0.26%   |
| Broadcom Limited         | 2        | 0.26%   |
| ASIX Electronics         | 2        | 0.26%   |
| Xiaomi                   | 1        | 0.13%   |
| TP-Link                  | 1        | 0.13%   |
| OPPO Electronics         | 1        | 0.13%   |
| Microchip Technology     | 1        | 0.13%   |
| JMicron Technology       | 1        | 0.13%   |
| Google                   | 1        | 0.13%   |
| 3Com                     | 1        | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 324      | 40.86%  |
| Realtek RTL8125 2.5GbE Controller                                             | 45       | 5.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 42       | 5.3%    |
| Intel I211 Gigabit Network Connection                                         | 39       | 4.92%   |
| Intel Ethernet Connection (2) I219-V                                          | 31       | 3.91%   |
| Intel Ethernet Controller I225-V                                              | 21       | 2.65%   |
| Intel Ethernet Connection I217-LM                                             | 19       | 2.4%    |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 15       | 1.89%   |
| Intel 82579V Gigabit Network Connection                                       | 12       | 1.51%   |
| Intel Ethernet Connection I217-V                                              | 11       | 1.39%   |
| Intel Ethernet Connection (2) I218-V                                          | 11       | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 10       | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 9        | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                                         | 9        | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 8        | 1.01%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 6        | 0.76%   |
| Nvidia MCP61 Ethernet                                                         | 5        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                                         | 5        | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 5        | 0.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 5        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 4        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 0.5%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 4        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 3        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 3        | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.38%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.38%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.38%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 0.38%   |
| Intel 82562V-2 10/100 Network Connection                                      | 3        | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 3        | 0.38%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.38%   |
| Nvidia MCP51 Ethernet Controller                                              | 2        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 704      | 67.89%  |
| WiFi     | 326      | 31.44%  |
| Modem    | 5        | 0.48%   |
| Unknown  | 2        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 541      | 73.81%  |
| WiFi     | 192      | 26.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 451      | 63.61%  |
| 2     | 208      | 29.34%  |
| 3     | 37       | 5.22%   |
| 0     | 5        | 0.71%   |
| 6     | 2        | 0.28%   |
| 5     | 2        | 0.28%   |
| 4     | 2        | 0.28%   |
| 13    | 1        | 0.14%   |
| 7     | 1        | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 458      | 63.97%  |
| Yes  | 258      | 36.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 100      | 41.84%  |
| Cambridge Silicon Radio         | 61       | 25.52%  |
| ASUSTek Computer                | 21       | 8.79%   |
| Realtek Semiconductor           | 20       | 8.37%   |
| Qualcomm Atheros Communications | 12       | 5.02%   |
| Broadcom                        | 11       | 4.6%    |
| Micro Star International        | 2        | 0.84%   |
| Edimax Technology               | 2        | 0.84%   |
| Belkin Components               | 2        | 0.84%   |
| Apple                           | 2        | 0.84%   |
| TP-Link                         | 1        | 0.42%   |
| Mobile Action Technology        | 1        | 0.42%   |
| MediaTek                        | 1        | 0.42%   |
| Integrated System Solution      | 1        | 0.42%   |
| IMC Networks                    | 1        | 0.42%   |
| Dynex                           | 1        | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 61       | 25.52%  |
| Intel AX200 Bluetooth                                        | 34       | 14.23%  |
| Intel Bluetooth wireless interface                           | 20       | 8.37%   |
| Realtek Bluetooth Radio                                      | 15       | 6.28%   |
| Intel AX210 Bluetooth                                        | 11       | 4.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 10       | 4.18%   |
| Intel Wireless-AC 3168 Bluetooth                             | 9        | 3.77%   |
| ASUS Bluetooth Device                                        | 9        | 3.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 8        | 3.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                            | 7        | 2.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 6        | 2.51%   |
| Qualcomm Atheros  Bluetooth Device                           | 5        | 2.09%   |
| Intel AX201 Bluetooth                                        | 5        | 2.09%   |
| Realtek  Bluetooth 4.2 Adapter                               | 3        | 1.26%   |
| Qualcomm Atheros Bluetooth USB Host Controller               | 3        | 1.26%   |
| Intel Bluetooth Device                                       | 3        | 1.26%   |
| Realtek RTL8821A Bluetooth                                   | 2        | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                            | 2        | 0.84%   |
| Micro Star International Bluetooth Device                    | 2        | 0.84%   |
| Edimax Bluetooth Adapter                                     | 2        | 0.84%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE        | 2        | 0.84%   |
| ASUS Bluetooth Radio                                         | 2        | 0.84%   |
| Apple Bluetooth HCI                                          | 2        | 0.84%   |
| TP-Link UB500 Adapter                                        | 1        | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                       | 1        | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                            | 1        | 0.42%   |
| Mobile Action MA-700 Bluetooth Adapter                       | 1        | 0.42%   |
| MediaTek Wireless_Device                                     | 1        | 0.42%   |
| Integrated System Solution Bluetooth Device                  | 1        | 0.42%   |
| IMC Networks Bluetooth Radio                                 | 1        | 0.42%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]     | 1        | 0.42%   |
| Broadcom Bluetooth dongle                                    | 1        | 0.42%   |
| Broadcom BCM43142A0 Bluetooth Device                         | 1        | 0.42%   |
| Broadcom BCM2045 Bluetooth                                   | 1        | 0.42%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 0.42%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter        | 1        | 0.42%   |
| Belkin Components F8T001v2 Bluetooth                         | 1        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 0.42%   |
| ASUS Bluetooth Adapter                                       | 1        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 452      | 37.86%  |
| Nvidia                     | 289      | 24.2%   |
| AMD                        | 286      | 23.95%  |
| Creative Labs              | 26       | 2.18%   |
| C-Media Electronics        | 26       | 2.18%   |
| Logitech                   | 17       | 1.42%   |
| Focusrite-Novation         | 8        | 0.67%   |
| ASUSTek Computer           | 7        | 0.59%   |
| Razer USA                  | 6        | 0.5%    |
| GN Netcom                  | 6        | 0.5%    |
| Corsair                    | 6        | 0.5%    |
| Texas Instruments          | 5        | 0.42%   |
| Tenx Technology            | 4        | 0.34%   |
| Creative Technology        | 4        | 0.34%   |
| XMOS                       | 3        | 0.25%   |
| JMTek                      | 3        | 0.25%   |
| Generalplus Technology     | 3        | 0.25%   |
| Yamaha                     | 2        | 0.17%   |
| VIA Technologies           | 2        | 0.17%   |
| Unknown                    | 2        | 0.17%   |
| Sony                       | 2        | 0.17%   |
| Realtek Semiconductor      | 2        | 0.17%   |
| PreSonus Audio Electronics | 2        | 0.17%   |
| Plantronics                | 2        | 0.17%   |
| Philips (or NXP)           | 2        | 0.17%   |
| Micro Star International   | 2        | 0.17%   |
| Digidesign                 | 2        | 0.17%   |
| Bose                       | 2        | 0.17%   |
| Unknown (ABC)              | 1        | 0.08%   |
| SteelSeries ApS            | 1        | 0.08%   |
| Shure                      | 1        | 0.08%   |
| Sennheiser Communications  | 1        | 0.08%   |
| SAVITECH                   | 1        | 0.08%   |
| Samson Technologies        | 1        | 0.08%   |
| RODE Microphones           | 1        | 0.08%   |
| Panasonic (Matsushita)     | 1        | 0.08%   |
| Native Instruments         | 1        | 0.08%   |
| Medeli Electronics         | 1        | 0.08%   |
| M-Audio                    | 1        | 0.08%   |
| KTMicro                    | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 70       | 5.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 64       | 4.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 53       | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 52       | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 48       | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 45       | 3.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 36       | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 35       | 2.54%   |
| Intel 200 Series PCH HD Audio                                              | 34       | 2.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 33       | 2.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 31       | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 26       | 1.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25       | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24       | 1.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 20       | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 20       | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18       | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 17       | 1.23%   |
| AMD FCH Azalia Controller                                                  | 17       | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                         | 16       | 1.16%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16       | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16       | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 15       | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15       | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 1.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 1.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 1.02%   |
| AMD Navi 10 HDMI Audio                                                     | 13       | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13       | 0.94%   |
| Nvidia TU104 HD Audio Controller                                           | 12       | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 12       | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 11       | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 10       | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                              | 10       | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 10       | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10       | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 0.73%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 48       | 14.86%  |
| Corsair                      | 47       | 14.55%  |
| G.Skill                      | 38       | 11.76%  |
| Unknown                      | 36       | 11.15%  |
| Crucial                      | 33       | 10.22%  |
| Samsung Electronics          | 27       | 8.36%   |
| SK hynix                     | 24       | 7.43%   |
| Micron Technology            | 15       | 4.64%   |
| Team                         | 9        | 2.79%   |
| Nanya Technology             | 7        | 2.17%   |
| A-DATA Technology            | 5        | 1.55%   |
| Patriot                      | 4        | 1.24%   |
| Unknown                      | 4        | 1.24%   |
| Elpida                       | 3        | 0.93%   |
| Unknown (ABCD)               | 2        | 0.62%   |
| Transcend                    | 2        | 0.62%   |
| PNY                          | 2        | 0.62%   |
| GeIL                         | 2        | 0.62%   |
| Apacer                       | 2        | 0.62%   |
| V-Color                      | 1        | 0.31%   |
| Undefined-00FE               | 1        | 0.31%   |
| Smart                        | 1        | 0.31%   |
| Silicon Power                | 1        | 0.31%   |
| Ramaxel Technology           | 1        | 0.31%   |
| Patriot Memory (PDP Systems) | 1        | 0.31%   |
| Kingmax                      | 1        | 0.31%   |
| Innodisk                     | 1        | 0.31%   |
| Hikvision                    | 1        | 0.31%   |
| Hewlett-Packard              | 1        | 0.31%   |
| GOODRAM                      | 1        | 0.31%   |
| ASint Technology             | 1        | 0.31%   |
| AMD                          | 1        | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 8        | 2.31%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 6        | 1.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 6        | 1.73%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 4        | 1.15%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 4        | 1.15%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s        | 4        | 1.15%   |
| Unknown                                                      | 4        | 1.15%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 3        | 0.86%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 3        | 0.86%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 3        | 0.86%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 3        | 0.86%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 3        | 0.86%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s    | 3        | 0.86%   |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s              | 3        | 0.86%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                     | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 2        | 0.58%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 2        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 2        | 0.58%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 0.58%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2        | 0.58%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 2        | 0.58%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.58%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s          | 2        | 0.58%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s           | 2        | 0.58%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s           | 2        | 0.58%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 2        | 0.58%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s         | 2        | 0.58%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s          | 2        | 0.58%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s         | 2        | 0.58%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 2        | 0.58%   |
| Kingston RAM CL16-18-18 D4-3200 8192MB DIMM DDR4 3200MT/s    | 2        | 0.58%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s       | 2        | 0.58%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s        | 2        | 0.58%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s          | 2        | 0.58%   |
| G.Skill RAM F3-2133C9-8GXH 8GB DIMM DDR3 2133MT/s            | 2        | 0.58%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s          | 2        | 0.58%   |
| Corsair RAM CMV4GX3M1A1333C9 4096MB DIMM DDR3 1600MT/s       | 2        | 0.58%   |
| Corsair RAM CMT32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 2        | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 153      | 54.06%  |
| DDR3    | 78       | 27.56%  |
| Unknown | 17       | 6.01%   |
| DDR2    | 15       | 5.3%    |
| SDRAM   | 12       | 4.24%   |
| DDR     | 4        | 1.41%   |
| LPDDR4  | 2        | 0.71%   |
| DRAM    | 2        | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 263      | 95.29%  |
| SODIMM  | 11       | 3.99%   |
| Unknown | 2        | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 123      | 39.94%  |
| 16384 | 62       | 20.13%  |
| 4096  | 60       | 19.48%  |
| 2048  | 34       | 11.04%  |
| 32768 | 21       | 6.82%   |
| 1024  | 8        | 2.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 50       | 15.82%  |
| 3200    | 36       | 11.39%  |
| 3600    | 32       | 10.13%  |
| 1333    | 32       | 10.13%  |
| 2400    | 18       | 5.7%    |
| 2133    | 16       | 5.06%   |
| 2667    | 14       | 4.43%   |
| 3866    | 8        | 2.53%   |
| 3733    | 8        | 2.53%   |
| 1800    | 8        | 2.53%   |
| 800     | 8        | 2.53%   |
| 1867    | 7        | 2.22%   |
| 3400    | 6        | 1.9%    |
| 3000    | 6        | 1.9%    |
| Unknown | 6        | 1.9%    |
| 3800    | 5        | 1.58%   |
| 1066    | 5        | 1.58%   |
| 2800    | 4        | 1.27%   |
| 2666    | 4        | 1.27%   |
| 667     | 4        | 1.27%   |
| 49926   | 3        | 0.95%   |
| 2933    | 3        | 0.95%   |
| 2048    | 3        | 0.95%   |
| 1866    | 3        | 0.95%   |
| 4000    | 2        | 0.63%   |
| 1067    | 2        | 0.63%   |
| 533     | 2        | 0.63%   |
| 400     | 2        | 0.63%   |
| 5600    | 1        | 0.32%   |
| 4800    | 1        | 0.32%   |
| 4400    | 1        | 0.32%   |
| 4200    | 1        | 0.32%   |
| 3666    | 1        | 0.32%   |
| 3500    | 1        | 0.32%   |
| 3467    | 1        | 0.32%   |
| 3466    | 1        | 0.32%   |
| 3334    | 1        | 0.32%   |
| 3134    | 1        | 0.32%   |
| 3100    | 1        | 0.32%   |
| 3066    | 1        | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 14       | 32.56%  |
| Samsung Electronics      | 11       | 25.58%  |
| Canon                    | 9        | 20.93%  |
| Brother Industries       | 6        | 13.95%  |
| Zhuhai Poskey Technology | 1        | 2.33%   |
| Seiko Epson              | 1        | 2.33%   |
| QinHeng Electronics      | 1        | 2.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SCX-3400 Series              | 2        | 4.65%   |
| Samsung M283x Series                 | 2        | 4.65%   |
| Samsung C48x Series                  | 2        | 4.65%   |
| HP ENVY Photo 6200 series            | 2        | 4.65%   |
| HP ENVY 4520 series                  | 2        | 4.65%   |
| HP Deskjet 1050 J410                 | 2        | 4.65%   |
| Brother Printer                      | 2        | 4.65%   |
| Zhuhai Poskey Printer                | 1        | 2.33%   |
| Seiko Epson L3160 Series             | 1        | 2.33%   |
| Samsung ML-216x Series Laser Printer | 1        | 2.33%   |
| Samsung ML-1865                      | 1        | 2.33%   |
| Samsung ML-1640 Series Laser Printer | 1        | 2.33%   |
| Samsung Composite Device             | 1        | 2.33%   |
| Samsung C43x Series                  | 1        | 2.33%   |
| QinHeng CH340S                       | 1        | 2.33%   |
| HP OfficeJet 5200 series             | 1        | 2.33%   |
| HP LaserJet 400 M401n                | 1        | 2.33%   |
| HP LaserJet 400 colorMFP M475dw      | 1        | 2.33%   |
| HP DeskJet F4100 Printer series      | 1        | 2.33%   |
| HP DeskJet 5810 series               | 1        | 2.33%   |
| HP DeskJet 5150c                     | 1        | 2.33%   |
| HP DeskJet 3700 series               | 1        | 2.33%   |
| HP DeskJet 2620 All-in-One Printer   | 1        | 2.33%   |
| Canon TR8600 series                  | 1        | 2.33%   |
| Canon TR4500 series                  | 1        | 2.33%   |
| Canon PIXMA MP280                    | 1        | 2.33%   |
| Canon PIXMA MG3600 Series            | 1        | 2.33%   |
| Canon PIXMA MG2500 Series            | 1        | 2.33%   |
| Canon Pixma iP4500 Printer           | 1        | 2.33%   |
| Canon MF731C/733C                    | 1        | 2.33%   |
| Canon iP7200 series                  | 1        | 2.33%   |
| Canon G3000 series                   | 1        | 2.33%   |
| Brother HL-3140CW series             | 1        | 2.33%   |
| Brother HL-3040CN series             | 1        | 2.33%   |
| Brother HL-2130 series               | 1        | 2.33%   |
| Brother HL-1430 Laser Printer        | 1        | 2.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 8        | 66.67%  |
| Seiko Epson     | 3        | 25%     |
| Hewlett-Packard | 1        | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                              | 2        | 15.38%  |
| Canon CanoScan LiDE 210                             | 2        | 15.38%  |
| Seiko Epson Scanner                                 | 1        | 7.69%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]    | 1        | 7.69%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1        | 7.69%   |
| Seiko Epson GT-9400UF [Perfection 3170]             | 1        | 7.69%   |
| HP ScanJet 3970c                                    | 1        | 7.69%   |
| Canon CanoScan N1240U/LiDE 30                       | 1        | 7.69%   |
| Canon CanoScan LiDE 220                             | 1        | 7.69%   |
| Canon CanoScan LiDE 200                             | 1        | 7.69%   |
| Canon CanoScan LiDE 100                             | 1        | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 62       | 44.93%  |
| Microdia                      | 13       | 9.42%   |
| Microsoft                     | 9        | 6.52%   |
| Generalplus Technology        | 8        | 5.8%    |
| Apple                         | 6        | 4.35%   |
| ARC International             | 4        | 2.9%    |
| Sunplus Innovation Technology | 3        | 2.17%   |
| Samsung Electronics           | 3        | 2.17%   |
| OmniVision Technologies       | 3        | 2.17%   |
| Unknown                       | 2        | 1.45%   |
| Realtek Semiconductor         | 2        | 1.45%   |
| Razer USA                     | 2        | 1.45%   |
| Huawei Technologies           | 2        | 1.45%   |
| Creative Technology           | 2        | 1.45%   |
| Z-Star Microelectronics       | 1        | 0.72%   |
| Sony                          | 1        | 0.72%   |
| PrehKeyTec                    | 1        | 0.72%   |
| Philips (or NXP)              | 1        | 0.72%   |
| Panasonic (Matsushita)        | 1        | 0.72%   |
| Motorola PCS                  | 1        | 0.72%   |
| MacroSilicon                  | 1        | 0.72%   |
| KYE Systems (Mouse Systems)   | 1        | 0.72%   |
| Jieli Technology              | 1        | 0.72%   |
| HD 2MP WEBCAM                 | 1        | 0.72%   |
| Genesys Logic                 | 1        | 0.72%   |
| GEMBIRD                       | 1        | 0.72%   |
| Chicony Electronics           | 1        | 0.72%   |
| Asuscom Network               | 1        | 0.72%   |
| Arkmicro Technologies         | 1        | 0.72%   |
| Alcor Micro                   | 1        | 0.72%   |
| A4Tech                        | 1        | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 17       | 12.23%  |
| Logitech HD Pro Webcam C920               | 6        | 4.32%   |
| Logitech C922 Pro Stream Webcam           | 6        | 4.32%   |
| Microdia USB 2.0 Camera                   | 5        | 3.6%    |
| Logitech HD Webcam C615                   | 5        | 3.6%    |
| Generalplus GENERAL WEBCAM                | 5        | 3.6%    |
| Microdia Webcam Vitade AF                 | 4        | 2.88%   |
| Logitech Webcam C930e                     | 4        | 2.88%   |
| Logitech HD Webcam C910                   | 4        | 2.88%   |
| ARC International Camera                  | 4        | 2.88%   |
| Samsung Galaxy A5 (MTP)                   | 3        | 2.16%   |
| OmniVision Monitor Webcam                 | 3        | 2.16%   |
| Microsoft LifeCam HD-3000                 | 3        | 2.16%   |
| Logitech Webcam C310                      | 3        | 2.16%   |
| Apple iPhone5/5C/5S/6                     | 3        | 2.16%   |
| Razer USA Gaming Webcam [Kiyo]            | 2        | 1.44%   |
| Microsoft LifeCam Studio                  | 2        | 1.44%   |
| Microdia Sonix USB 2.0 Camera             | 2        | 1.44%   |
| Logitech QuickCam Pro 9000                | 2        | 1.44%   |
| Logitech BRIO Ultra HD Webcam             | 2        | 1.44%   |
| Huawei UVC Camera                         | 2        | 1.44%   |
| Generalplus 808 Camera #9 (web-cam mode)  | 2        | 1.44%   |
| Z-Star Lenovo USB 2.0 UVC Camera          | 1        | 0.72%   |
| Unknown Integrated RGB Camera             | 1        | 0.72%   |
| Unknown HD camera                         | 1        | 0.72%   |
| Sunplus SPCA2650 AV Camera                | 1        | 0.72%   |
| Sunplus HD 720P webcam                    | 1        | 0.72%   |
| Sunplus Full HD webcam                    | 1        | 0.72%   |
| Sony CEVCECM                              | 1        | 0.72%   |
| Realtek NexiGo N660P FHD Webcam           | 1        | 0.72%   |
| Realtek HK 2M CAM                         | 1        | 0.72%   |
| PrehKeyTec TA-0120-AS                     | 1        | 0.72%   |
| Philips (or NXP) SPC 520/525NC PC Camera  | 1        | 0.72%   |
| Panasonic (Matsushita) TY-CC20W           | 1        | 0.72%   |
| Motorola PCS XT1033 [Moto G], PTP mode    | 1        | 0.72%   |
| Microsoft MicrosoftÂ LifeCam VX-5500     | 1        | 0.72%   |
| Microsoft LifeCam VX-7000 (UVC-compliant) | 1        | 0.72%   |
| Microsoft LifeCam NX-6000                 | 1        | 0.72%   |
| Microsoft LifeCam HD-5000                 | 1        | 0.72%   |
| Microdia USB camera                       | 1        | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| SCM Microsystems         | 1        | 20%     |
| Reiner SCT Kartensysteme | 1        | 20%     |
| Realtek Semiconductor    | 1        | 20%     |
| Hewlett-Packard          | 1        | 20%     |
| Alcor Micro              | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR35xx Smart Card Reader                                 | 1        | 20%     |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 20%     |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 20%     |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                              | 1        | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 612      | 85.12%  |
| 1     | 93       | 12.93%  |
| 2     | 9        | 1.25%   |
| 5     | 2        | 0.28%   |
| 3     | 2        | 0.28%   |
| 6     | 1        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 45       | 37.19%  |
| Net/wireless             | 33       | 27.27%  |
| Unassigned class         | 12       | 9.92%   |
| Multimedia controller    | 6        | 4.96%   |
| Communication controller | 6        | 4.96%   |
| Sound                    | 5        | 4.13%   |
| Chipcard                 | 4        | 3.31%   |
| Storage/raid             | 2        | 1.65%   |
| Fingerprint reader       | 2        | 1.65%   |
| Card reader              | 2        | 1.65%   |
| Camera                   | 2        | 1.65%   |
| Modem                    | 1        | 0.83%   |
| Bluetooth                | 1        | 0.83%   |


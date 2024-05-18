Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 15880

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5290 2-in-1        | Notebook    | [56d2614671](https://linux-hardware.org/?probe=56d2614671) | May 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [03e53efb87](https://linux-hardware.org/?probe=03e53efb87) | May 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2786d2f8f8](https://linux-hardware.org/?probe=2786d2f8f8) | May 08, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [38ae310bd0](https://linux-hardware.org/?probe=38ae310bd0) | May 08, 2024 |
| HP            | 8AC1                        | Desktop     | [34fb750829](https://linux-hardware.org/?probe=34fb750829) | May 08, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [73ee3d2b74](https://linux-hardware.org/?probe=73ee3d2b74) | May 08, 2024 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [e6839a3d70](https://linux-hardware.org/?probe=e6839a3d70) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [9122522638](https://linux-hardware.org/?probe=9122522638) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3064d4fb1f](https://linux-hardware.org/?probe=3064d4fb1f) | May 07, 2024 |
| System76      | Gazelle                     | Notebook    | [fbe88df732](https://linux-hardware.org/?probe=fbe88df732) | May 07, 2024 |
| System76      | Darter Pro                  | Notebook    | [e6da92d97e](https://linux-hardware.org/?probe=e6da92d97e) | May 06, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [3132f4ff24](https://linux-hardware.org/?probe=3132f4ff24) | May 06, 2024 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [1181eb41ee](https://linux-hardware.org/?probe=1181eb41ee) | May 06, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [db900f1cd1](https://linux-hardware.org/?probe=db900f1cd1) | May 05, 2024 |
| Lenovo        | ThinkPad T420s 41732AU      | Notebook    | [be5eeed803](https://linux-hardware.org/?probe=be5eeed803) | May 05, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [05c21dbea4](https://linux-hardware.org/?probe=05c21dbea4) | May 05, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [672e653276](https://linux-hardware.org/?probe=672e653276) | May 05, 2024 |
| System76      | Oryx Pro                    | Notebook    | [6d05743481](https://linux-hardware.org/?probe=6d05743481) | May 05, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [9cdeec0464](https://linux-hardware.org/?probe=9cdeec0464) | May 05, 2024 |
| Getac         | S410                        | Notebook    | [a05cbbe577](https://linux-hardware.org/?probe=a05cbbe577) | May 04, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [2e9e3f6434](https://linux-hardware.org/?probe=2e9e3f6434) | May 04, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [28d0d4304f](https://linux-hardware.org/?probe=28d0d4304f) | May 04, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [bb83948d6a](https://linux-hardware.org/?probe=bb83948d6a) | May 04, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1f42d0fe27](https://linux-hardware.org/?probe=1f42d0fe27) | May 04, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0839696375](https://linux-hardware.org/?probe=0839696375) | May 04, 2024 |
| Lenovo        | CRESCENTBAY SDK0E50515 S... | All in one  | [bbd9a3f7ae](https://linux-hardware.org/?probe=bbd9a3f7ae) | May 04, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [868dd4d0bd](https://linux-hardware.org/?probe=868dd4d0bd) | May 03, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ba1456ce87](https://linux-hardware.org/?probe=ba1456ce87) | May 03, 2024 |
| SZMZ          | X99-S3                      | Desktop     | [9dc9366e04](https://linux-hardware.org/?probe=9dc9366e04) | May 03, 2024 |
| Dell          | XPS 13 9340                 | Notebook    | [4446c73008](https://linux-hardware.org/?probe=4446c73008) | May 03, 2024 |
| Dell          | Latitude E6330              | Notebook    | [02c85088bc](https://linux-hardware.org/?probe=02c85088bc) | May 03, 2024 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [b7cb9e7573](https://linux-hardware.org/?probe=b7cb9e7573) | May 03, 2024 |
| Alienware     | M14xR1                      | Notebook    | [501de2a1ec](https://linux-hardware.org/?probe=501de2a1ec) | May 02, 2024 |
| Intel         | B75                         | Desktop     | [4925a7fcb7](https://linux-hardware.org/?probe=4925a7fcb7) | May 02, 2024 |
| HP            | 3646h                       | Desktop     | [3c2faf0d32](https://linux-hardware.org/?probe=3c2faf0d32) | May 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c23a3238c0](https://linux-hardware.org/?probe=c23a3238c0) | May 02, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [0299f8321b](https://linux-hardware.org/?probe=0299f8321b) | May 01, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [569772c380](https://linux-hardware.org/?probe=569772c380) | May 01, 2024 |
| HP            | Pavilion dv7                | Notebook    | [d191e30bf7](https://linux-hardware.org/?probe=d191e30bf7) | May 01, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [2ffc5da09f](https://linux-hardware.org/?probe=2ffc5da09f) | May 01, 2024 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [9ae885f7fd](https://linux-hardware.org/?probe=9ae885f7fd) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | Notebook    | [5712b06d98](https://linux-hardware.org/?probe=5712b06d98) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | Notebook    | [a032f50d3f](https://linux-hardware.org/?probe=a032f50d3f) | Apr 30, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [1780065067](https://linux-hardware.org/?probe=1780065067) | Apr 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [701927cf4d](https://linux-hardware.org/?probe=701927cf4d) | Apr 30, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [4ef11d14a3](https://linux-hardware.org/?probe=4ef11d14a3) | Apr 29, 2024 |
| ASUSTek       | M4N72-E                     | Desktop     | [c8920341bc](https://linux-hardware.org/?probe=c8920341bc) | Apr 29, 2024 |
| Alienware     | M14xR1                      | Notebook    | [dc1461c536](https://linux-hardware.org/?probe=dc1461c536) | Apr 29, 2024 |
| MSI           | Katana 15 B12VGK            | Notebook    | [c8e4cb337e](https://linux-hardware.org/?probe=c8e4cb337e) | Apr 29, 2024 |
| Supermicro    | X12SPA-TF                   | Server      | [965ec5db00](https://linux-hardware.org/?probe=965ec5db00) | Apr 29, 2024 |
| HP            | 2129                        | Desktop     | [40fa42996a](https://linux-hardware.org/?probe=40fa42996a) | Apr 29, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [2afe25d1f8](https://linux-hardware.org/?probe=2afe25d1f8) | Apr 28, 2024 |
| ASUSTek       | X451CA                      | Notebook    | [30d9b5f4ee](https://linux-hardware.org/?probe=30d9b5f4ee) | Apr 28, 2024 |
| Dell          | Inspiron 16 7610            | Notebook    | [2427197c56](https://linux-hardware.org/?probe=2427197c56) | Apr 28, 2024 |
| MSI           | 970A-G46                    | Desktop     | [156b1bab44](https://linux-hardware.org/?probe=156b1bab44) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [b024eb05d1](https://linux-hardware.org/?probe=b024eb05d1) | Apr 28, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [48a48b4523](https://linux-hardware.org/?probe=48a48b4523) | Apr 28, 2024 |
| HP            | 2129                        | Desktop     | [03800251ed](https://linux-hardware.org/?probe=03800251ed) | Apr 28, 2024 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [14dbfab450](https://linux-hardware.org/?probe=14dbfab450) | Apr 27, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [3fbd54c33d](https://linux-hardware.org/?probe=3fbd54c33d) | Apr 27, 2024 |
| Dell          | Precision 5680              | Notebook    | [95bc853549](https://linux-hardware.org/?probe=95bc853549) | Apr 27, 2024 |
| Medion        | Akoya E6227                 | Notebook    | [76bfce53f4](https://linux-hardware.org/?probe=76bfce53f4) | Apr 26, 2024 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [a1fbe8858b](https://linux-hardware.org/?probe=a1fbe8858b) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [6d6b67129d](https://linux-hardware.org/?probe=6d6b67129d) | Apr 26, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [ce253ebd01](https://linux-hardware.org/?probe=ce253ebd01) | Apr 26, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [6b932e4eb7](https://linux-hardware.org/?probe=6b932e4eb7) | Apr 26, 2024 |
| Acer          | FX58M                       | Desktop     | [d8aec92fe1](https://linux-hardware.org/?probe=d8aec92fe1) | Apr 25, 2024 |
| HP            | 8704                        | Desktop     | [deeb399937](https://linux-hardware.org/?probe=deeb399937) | Apr 25, 2024 |
| HP            | EliteBook 745 G6            | Notebook    | [5354993cb7](https://linux-hardware.org/?probe=5354993cb7) | Apr 25, 2024 |
| HP            | EliteBook 745 G6            | Notebook    | [3b5f41d264](https://linux-hardware.org/?probe=3b5f41d264) | Apr 25, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [554822996a](https://linux-hardware.org/?probe=554822996a) | Apr 24, 2024 |
| HP            | ENVY 15                     | Notebook    | [20cb7a828b](https://linux-hardware.org/?probe=20cb7a828b) | Apr 24, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [31838248fa](https://linux-hardware.org/?probe=31838248fa) | Apr 24, 2024 |
| ASUSTek       | Maximus IX CODE             | Desktop     | [db21083720](https://linux-hardware.org/?probe=db21083720) | Apr 24, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [cbcc357ce6](https://linux-hardware.org/?probe=cbcc357ce6) | Apr 24, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [188e5e5bde](https://linux-hardware.org/?probe=188e5e5bde) | Apr 24, 2024 |
| Gigabyte      | B560M H                     | Desktop     | [db05a445f8](https://linux-hardware.org/?probe=db05a445f8) | Apr 24, 2024 |
| Dell          | 0C1R19 A02                  | Desktop     | [de862a6d95](https://linux-hardware.org/?probe=de862a6d95) | Apr 24, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0253ffc79c](https://linux-hardware.org/?probe=0253ffc79c) | Apr 24, 2024 |
| ASRock        | FM2A68M-HD+                 | Notebook    | [74967df09a](https://linux-hardware.org/?probe=74967df09a) | Apr 23, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [965595373d](https://linux-hardware.org/?probe=965595373d) | Apr 23, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [5453cfa265](https://linux-hardware.org/?probe=5453cfa265) | Apr 23, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [a3842c8188](https://linux-hardware.org/?probe=a3842c8188) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [ecc36cef1b](https://linux-hardware.org/?probe=ecc36cef1b) | Apr 23, 2024 |
| MSI           | GE62VR 6RF                  | Notebook    | [68b99dae1a](https://linux-hardware.org/?probe=68b99dae1a) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b6aa6b2262](https://linux-hardware.org/?probe=b6aa6b2262) | Apr 22, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [5a88798ad6](https://linux-hardware.org/?probe=5a88798ad6) | Apr 22, 2024 |
| ASUSTek       | ROG Strix SCAR 18 G834JZ... | Notebook    | [28007aea7c](https://linux-hardware.org/?probe=28007aea7c) | Apr 22, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d24a794778](https://linux-hardware.org/?probe=d24a794778) | Apr 22, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [7fb64c7bef](https://linux-hardware.org/?probe=7fb64c7bef) | Apr 22, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [8436ef6ebc](https://linux-hardware.org/?probe=8436ef6ebc) | Apr 22, 2024 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [e63cba3bfa](https://linux-hardware.org/?probe=e63cba3bfa) | Apr 22, 2024 |
| Dell          | XPS 13 9340                 | Notebook    | [5b25704805](https://linux-hardware.org/?probe=5b25704805) | Apr 22, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [d3e9e01950](https://linux-hardware.org/?probe=d3e9e01950) | Apr 21, 2024 |
| Unknown       | MAGNUS III                  | Tablet      | [9796ca9436](https://linux-hardware.org/?probe=9796ca9436) | Apr 21, 2024 |
| System76      | Lemur Pro                   | Notebook    | [3b7243efe7](https://linux-hardware.org/?probe=3b7243efe7) | Apr 21, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ff86440a74](https://linux-hardware.org/?probe=ff86440a74) | Apr 21, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [42a4ba108a](https://linux-hardware.org/?probe=42a4ba108a) | Apr 21, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [63baa07920](https://linux-hardware.org/?probe=63baa07920) | Apr 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ee83ed7c12](https://linux-hardware.org/?probe=ee83ed7c12) | Apr 20, 2024 |
| Intel         | B75                         | Desktop     | [27d3a826f4](https://linux-hardware.org/?probe=27d3a826f4) | Apr 20, 2024 |
| ASRock        | Z77 Extreme4                | Desktop     | [52009ffcd0](https://linux-hardware.org/?probe=52009ffcd0) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [8fd0a624a7](https://linux-hardware.org/?probe=8fd0a624a7) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [5e91dc2b03](https://linux-hardware.org/?probe=5e91dc2b03) | Apr 20, 2024 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [1091b6a34e](https://linux-hardware.org/?probe=1091b6a34e) | Apr 20, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [f8fa58a83b](https://linux-hardware.org/?probe=f8fa58a83b) | Apr 19, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [8dde47a60c](https://linux-hardware.org/?probe=8dde47a60c) | Apr 19, 2024 |
| ASRock        | X570 Taichi                 | Desktop     | [2de05483c5](https://linux-hardware.org/?probe=2de05483c5) | Apr 19, 2024 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [712655c5bd](https://linux-hardware.org/?probe=712655c5bd) | Apr 19, 2024 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [4f5d1a37c3](https://linux-hardware.org/?probe=4f5d1a37c3) | Apr 19, 2024 |
| Google        | Morphius                    | Notebook    | [a8361bc931](https://linux-hardware.org/?probe=a8361bc931) | Apr 19, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [6190a14941](https://linux-hardware.org/?probe=6190a14941) | Apr 19, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5bcf08b4b0](https://linux-hardware.org/?probe=5bcf08b4b0) | Apr 19, 2024 |
| HP            | OMEN by Latpop 16-c0100n... | Notebook    | [0ee401b99c](https://linux-hardware.org/?probe=0ee401b99c) | Apr 19, 2024 |
| HP            | 8299                        | Desktop     | [aecdc0598b](https://linux-hardware.org/?probe=aecdc0598b) | Apr 19, 2024 |
| Toshiba       | Satellite L755D             | Notebook    | [47d623ed44](https://linux-hardware.org/?probe=47d623ed44) | Apr 19, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8f4cd3f89d](https://linux-hardware.org/?probe=8f4cd3f89d) | Apr 19, 2024 |
| HP            | 8949 11                     | Desktop     | [ab13748833](https://linux-hardware.org/?probe=ab13748833) | Apr 18, 2024 |
| HP            | 8949 11                     | Desktop     | [3f180801bd](https://linux-hardware.org/?probe=3f180801bd) | Apr 18, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e25b6a6321](https://linux-hardware.org/?probe=e25b6a6321) | Apr 18, 2024 |
| Dell          | Precision 5680              | Notebook    | [165f135e49](https://linux-hardware.org/?probe=165f135e49) | Apr 18, 2024 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | Notebook    | [7b5eee5473](https://linux-hardware.org/?probe=7b5eee5473) | Apr 18, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [ec68301ab8](https://linux-hardware.org/?probe=ec68301ab8) | Apr 17, 2024 |
| MSI           | Z87-G45 GAMING              | Desktop     | [f646b54913](https://linux-hardware.org/?probe=f646b54913) | Apr 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bcbc28897f](https://linux-hardware.org/?probe=bcbc28897f) | Apr 17, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [5b510f5ccd](https://linux-hardware.org/?probe=5b510f5ccd) | Apr 17, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9fcf03a9f](https://linux-hardware.org/?probe=e9fcf03a9f) | Apr 17, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [224785342d](https://linux-hardware.org/?probe=224785342d) | Apr 17, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [53055c8335](https://linux-hardware.org/?probe=53055c8335) | Apr 17, 2024 |
| ASUSTek       | UX305CA                     | Notebook    | [0793f271ed](https://linux-hardware.org/?probe=0793f271ed) | Apr 17, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [d3ad81315d](https://linux-hardware.org/?probe=d3ad81315d) | Apr 17, 2024 |
| Acer          | Spin SP314-54N              | Convertible | [4c9c9bdfa3](https://linux-hardware.org/?probe=4c9c9bdfa3) | Apr 17, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9945f26789](https://linux-hardware.org/?probe=9945f26789) | Apr 17, 2024 |
| Samsung       | 940X3G/930X3G               | Notebook    | [7ae2ace4e3](https://linux-hardware.org/?probe=7ae2ace4e3) | Apr 17, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e45ac0e9cc](https://linux-hardware.org/?probe=e45ac0e9cc) | Apr 16, 2024 |
| Samsung       | 940X3G/930X3G               | Notebook    | [ebcb51ed9c](https://linux-hardware.org/?probe=ebcb51ed9c) | Apr 16, 2024 |
| ASRock        | Z790 Nova WiFi              | Desktop     | [e7087ec7e4](https://linux-hardware.org/?probe=e7087ec7e4) | Apr 16, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [fd0c46bab2](https://linux-hardware.org/?probe=fd0c46bab2) | Apr 16, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d504f8b8a6](https://linux-hardware.org/?probe=d504f8b8a6) | Apr 16, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [088cb90432](https://linux-hardware.org/?probe=088cb90432) | Apr 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [bcaf7cac1a](https://linux-hardware.org/?probe=bcaf7cac1a) | Apr 15, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [96b786aa6f](https://linux-hardware.org/?probe=96b786aa6f) | Apr 15, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [ddb98658ed](https://linux-hardware.org/?probe=ddb98658ed) | Apr 15, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [91d047cef5](https://linux-hardware.org/?probe=91d047cef5) | Apr 15, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [47f139152e](https://linux-hardware.org/?probe=47f139152e) | Apr 15, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e27137024f](https://linux-hardware.org/?probe=e27137024f) | Apr 15, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [eae63cf682](https://linux-hardware.org/?probe=eae63cf682) | Apr 15, 2024 |
| ASUSTek       | P5Q-EM                      | Desktop     | [dc780bc9a5](https://linux-hardware.org/?probe=dc780bc9a5) | Apr 15, 2024 |
| Acer          | Spin SP314-54N              | Convertible | [745ac651f0](https://linux-hardware.org/?probe=745ac651f0) | Apr 14, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e6a1712a7](https://linux-hardware.org/?probe=6e6a1712a7) | Apr 14, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [0e240e7a70](https://linux-hardware.org/?probe=0e240e7a70) | Apr 14, 2024 |
| Acer          | Nitro AN515-51              | Notebook    | [46d9c6bc98](https://linux-hardware.org/?probe=46d9c6bc98) | Apr 14, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9dc06b7a85](https://linux-hardware.org/?probe=9dc06b7a85) | Apr 13, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ad14cabff5](https://linux-hardware.org/?probe=ad14cabff5) | Apr 13, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [b120a1a8eb](https://linux-hardware.org/?probe=b120a1a8eb) | Apr 13, 2024 |
| System76      | Lemur Pro                   | Notebook    | [7c9425e33a](https://linux-hardware.org/?probe=7c9425e33a) | Apr 13, 2024 |
| Dell          | Latitude E5520              | Notebook    | [0f03f7a01f](https://linux-hardware.org/?probe=0f03f7a01f) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [31b430e45e](https://linux-hardware.org/?probe=31b430e45e) | Apr 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [858512aecf](https://linux-hardware.org/?probe=858512aecf) | Apr 12, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [b977bc3a0a](https://linux-hardware.org/?probe=b977bc3a0a) | Apr 12, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7ee4741505](https://linux-hardware.org/?probe=7ee4741505) | Apr 12, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [57c2d76c65](https://linux-hardware.org/?probe=57c2d76c65) | Apr 12, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3007... | Notebook    | [696b2e9290](https://linux-hardware.org/?probe=696b2e9290) | Apr 12, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3007... | Notebook    | [7d473643db](https://linux-hardware.org/?probe=7d473643db) | Apr 12, 2024 |
| System76      | Oryx Pro                    | Notebook    | [0204db931b](https://linux-hardware.org/?probe=0204db931b) | Apr 12, 2024 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | Notebook    | [e72d400eb3](https://linux-hardware.org/?probe=e72d400eb3) | Apr 11, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [bcff49116b](https://linux-hardware.org/?probe=bcff49116b) | Apr 11, 2024 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [66cbd66636](https://linux-hardware.org/?probe=66cbd66636) | Apr 11, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | Notebook    | [589fd95069](https://linux-hardware.org/?probe=589fd95069) | Apr 11, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [df536172a9](https://linux-hardware.org/?probe=df536172a9) | Apr 10, 2024 |
| System76      | Oryx Pro                    | Notebook    | [ea8426e115](https://linux-hardware.org/?probe=ea8426e115) | Apr 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [2b7f101b88](https://linux-hardware.org/?probe=2b7f101b88) | Apr 10, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [e9b9656231](https://linux-hardware.org/?probe=e9b9656231) | Apr 09, 2024 |
| Itautec       | ST 4271                     | Desktop     | [8fc18963b3](https://linux-hardware.org/?probe=8fc18963b3) | Apr 09, 2024 |
| HP            | 250 G4                      | Notebook    | [8f21075772](https://linux-hardware.org/?probe=8f21075772) | Apr 09, 2024 |
| Dell          | 0VTJVC A00                  | Desktop     | [edb54fbe32](https://linux-hardware.org/?probe=edb54fbe32) | Apr 09, 2024 |
| Lenovo        | ThinkPad T470 20HEA0TLUS    | Notebook    | [fac79c8b6b](https://linux-hardware.org/?probe=fac79c8b6b) | Apr 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [43618657fd](https://linux-hardware.org/?probe=43618657fd) | Apr 09, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [a22e72117f](https://linux-hardware.org/?probe=a22e72117f) | Apr 09, 2024 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [732523a553](https://linux-hardware.org/?probe=732523a553) | Apr 09, 2024 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [d53567aeb3](https://linux-hardware.org/?probe=d53567aeb3) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [03de80c7da](https://linux-hardware.org/?probe=03de80c7da) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [7b9ff3d8a5](https://linux-hardware.org/?probe=7b9ff3d8a5) | Apr 08, 2024 |
| Dell          | Latitude E7240              | Notebook    | [a323cf8e2e](https://linux-hardware.org/?probe=a323cf8e2e) | Apr 08, 2024 |
| Alienware     | m15 R7                      | Notebook    | [5b8340f20c](https://linux-hardware.org/?probe=5b8340f20c) | Apr 08, 2024 |
| Alienware     | m15 R7                      | Notebook    | [2b7f9cd75d](https://linux-hardware.org/?probe=2b7f9cd75d) | Apr 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [471a22d2d2](https://linux-hardware.org/?probe=471a22d2d2) | Apr 08, 2024 |
| HP            | 15                          | Notebook    | [6cb916bc6b](https://linux-hardware.org/?probe=6cb916bc6b) | Apr 08, 2024 |
| MSI           | Titan GT77HX 13VI           | Notebook    | [81cf9688bd](https://linux-hardware.org/?probe=81cf9688bd) | Apr 08, 2024 |
| HP            | 15                          | Notebook    | [c3dd3707a8](https://linux-hardware.org/?probe=c3dd3707a8) | Apr 08, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [91b4de4e2a](https://linux-hardware.org/?probe=91b4de4e2a) | Apr 07, 2024 |
| Dell          | Latitude 5401               | Notebook    | [50c9a92ed4](https://linux-hardware.org/?probe=50c9a92ed4) | Apr 07, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [071a57efd2](https://linux-hardware.org/?probe=071a57efd2) | Apr 07, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [25ee9e6b9c](https://linux-hardware.org/?probe=25ee9e6b9c) | Apr 07, 2024 |
| Acer          | Aspire TC-105               | Desktop     | [7ecc002fc3](https://linux-hardware.org/?probe=7ecc002fc3) | Apr 07, 2024 |
| Acer          | Aspire TC-105               | Desktop     | [9c7c1f6869](https://linux-hardware.org/?probe=9c7c1f6869) | Apr 07, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [85dd650b73](https://linux-hardware.org/?probe=85dd650b73) | Apr 07, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [b36f589241](https://linux-hardware.org/?probe=b36f589241) | Apr 06, 2024 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [75363d665b](https://linux-hardware.org/?probe=75363d665b) | Apr 06, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3242172c38](https://linux-hardware.org/?probe=3242172c38) | Apr 06, 2024 |
| HP            | Stream 11 Pro G5            | Notebook    | [60dbf47721](https://linux-hardware.org/?probe=60dbf47721) | Apr 06, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [20ceba9415](https://linux-hardware.org/?probe=20ceba9415) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [e7b99f79ab](https://linux-hardware.org/?probe=e7b99f79ab) | Apr 06, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [575fd0d93d](https://linux-hardware.org/?probe=575fd0d93d) | Apr 06, 2024 |
| Dell          | Inspiron 7306 2n1           | Convertible | [37831e9cc3](https://linux-hardware.org/?probe=37831e9cc3) | Apr 06, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [cf5333f4e5](https://linux-hardware.org/?probe=cf5333f4e5) | Apr 06, 2024 |
| Intel         | DH67CF AAG10215-203         | Desktop     | [c26c93bb88](https://linux-hardware.org/?probe=c26c93bb88) | Apr 06, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [2a11ab4791](https://linux-hardware.org/?probe=2a11ab4791) | Apr 06, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [e786bc1b13](https://linux-hardware.org/?probe=e786bc1b13) | Apr 06, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [9afed2e851](https://linux-hardware.org/?probe=9afed2e851) | Apr 06, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f519652f57](https://linux-hardware.org/?probe=f519652f57) | Apr 06, 2024 |
| Biostar       | TA970                       | Desktop     | [b95526c668](https://linux-hardware.org/?probe=b95526c668) | Apr 05, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [b1f7625755](https://linux-hardware.org/?probe=b1f7625755) | Apr 05, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [836a40664c](https://linux-hardware.org/?probe=836a40664c) | Apr 05, 2024 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [bdde2d1fe9](https://linux-hardware.org/?probe=bdde2d1fe9) | Apr 05, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [b06fe332d7](https://linux-hardware.org/?probe=b06fe332d7) | Apr 05, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a92eac3002](https://linux-hardware.org/?probe=a92eac3002) | Apr 05, 2024 |
| HP            | EliteBook 8730w             | Notebook    | [342f90f8c1](https://linux-hardware.org/?probe=342f90f8c1) | Apr 05, 2024 |
| BESSTAR Te... | HM90                        | Desktop     | [6dda4c2573](https://linux-hardware.org/?probe=6dda4c2573) | Apr 05, 2024 |
| HP            | EliteBook 8730w             | Notebook    | [b4c4b71cdb](https://linux-hardware.org/?probe=b4c4b71cdb) | Apr 05, 2024 |
| BESSTAR Te... | HM90                        | Desktop     | [e9b2e7f701](https://linux-hardware.org/?probe=e9b2e7f701) | Apr 05, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [bf584291d2](https://linux-hardware.org/?probe=bf584291d2) | Apr 04, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [5aa6e72318](https://linux-hardware.org/?probe=5aa6e72318) | Apr 04, 2024 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [bbc6cfb633](https://linux-hardware.org/?probe=bbc6cfb633) | Apr 04, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [ed6e28b85c](https://linux-hardware.org/?probe=ed6e28b85c) | Apr 04, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [00ca2164cf](https://linux-hardware.org/?probe=00ca2164cf) | Apr 03, 2024 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [0b96c3a901](https://linux-hardware.org/?probe=0b96c3a901) | Apr 02, 2024 |
| ASUSTek       | P5G41T-M                    | Desktop     | [731881f720](https://linux-hardware.org/?probe=731881f720) | Apr 02, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [58db4322b8](https://linux-hardware.org/?probe=58db4322b8) | Apr 02, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [4ba0812bcd](https://linux-hardware.org/?probe=4ba0812bcd) | Apr 02, 2024 |
| MSI           | Titan GT77HX 13VI           | Notebook    | [c6da8fe194](https://linux-hardware.org/?probe=c6da8fe194) | Apr 02, 2024 |
| Acer          | TravelMate P277-MG          | Notebook    | [49a90af61e](https://linux-hardware.org/?probe=49a90af61e) | Apr 02, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [0855016a44](https://linux-hardware.org/?probe=0855016a44) | Apr 01, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [43a3819af7](https://linux-hardware.org/?probe=43a3819af7) | Apr 01, 2024 |
| Dell          | Latitude E6430              | Notebook    | [bf9cac92e7](https://linux-hardware.org/?probe=bf9cac92e7) | Apr 01, 2024 |
| GPD           | G1619-04                    | Notebook    | [4d8878864a](https://linux-hardware.org/?probe=4d8878864a) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2a00b77a69](https://linux-hardware.org/?probe=2a00b77a69) | Apr 01, 2024 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [98c3893edd](https://linux-hardware.org/?probe=98c3893edd) | Apr 01, 2024 |
| Acer          | Aspire A315-35              | Notebook    | [554a38529a](https://linux-hardware.org/?probe=554a38529a) | Mar 31, 2024 |
| Dell          | Latitude E6430              | Notebook    | [c871f1007a](https://linux-hardware.org/?probe=c871f1007a) | Mar 31, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [a02628f1b4](https://linux-hardware.org/?probe=a02628f1b4) | Mar 31, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | Notebook    | [c19f043267](https://linux-hardware.org/?probe=c19f043267) | Mar 31, 2024 |
| HP            | 250 G4                      | Notebook    | [fbf0b206e8](https://linux-hardware.org/?probe=fbf0b206e8) | Mar 31, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [449d0ad45b](https://linux-hardware.org/?probe=449d0ad45b) | Mar 31, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [77d2d8ef3e](https://linux-hardware.org/?probe=77d2d8ef3e) | Mar 31, 2024 |
| Toshiba       | Satellite P105              | Notebook    | [7b87f631be](https://linux-hardware.org/?probe=7b87f631be) | Mar 31, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [fd278af3a5](https://linux-hardware.org/?probe=fd278af3a5) | Mar 31, 2024 |
| Dell          | Latitude E5520              | Notebook    | [875fc34b64](https://linux-hardware.org/?probe=875fc34b64) | Mar 31, 2024 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0a8f92ffe1](https://linux-hardware.org/?probe=0a8f92ffe1) | Mar 30, 2024 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [0af90b54ec](https://linux-hardware.org/?probe=0af90b54ec) | Mar 30, 2024 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [d558b17c2d](https://linux-hardware.org/?probe=d558b17c2d) | Mar 30, 2024 |
| Timi          | TM1604                      | Notebook    | [9ef2ec37c2](https://linux-hardware.org/?probe=9ef2ec37c2) | Mar 29, 2024 |
| Timi          | TM1604                      | Notebook    | [ec2ab8fb5f](https://linux-hardware.org/?probe=ec2ab8fb5f) | Mar 29, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [943c4e0f41](https://linux-hardware.org/?probe=943c4e0f41) | Mar 29, 2024 |
| Acer          | Swift SFX14-51G             | Notebook    | [a0aaa7eb1d](https://linux-hardware.org/?probe=a0aaa7eb1d) | Mar 29, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [29ee5ea6b5](https://linux-hardware.org/?probe=29ee5ea6b5) | Mar 29, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [6f6c4699f5](https://linux-hardware.org/?probe=6f6c4699f5) | Mar 29, 2024 |
| ASUSTek       | ProArt Studiobook H7604J... | Notebook    | [ce5acdd8b0](https://linux-hardware.org/?probe=ce5acdd8b0) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [90614a5f0b](https://linux-hardware.org/?probe=90614a5f0b) | Mar 28, 2024 |
| Acer          | Aspire 4349                 | Notebook    | [8bf51e5557](https://linux-hardware.org/?probe=8bf51e5557) | Mar 28, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d93e2bd101](https://linux-hardware.org/?probe=d93e2bd101) | Mar 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [951f003b12](https://linux-hardware.org/?probe=951f003b12) | Mar 28, 2024 |
| Biostar       | A960D+V2                    | Desktop     | [1295e48af0](https://linux-hardware.org/?probe=1295e48af0) | Mar 28, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [ba5d17c1d9](https://linux-hardware.org/?probe=ba5d17c1d9) | Mar 28, 2024 |
| ASUSTek       | P8P67                       | Desktop     | [6ab2d189e5](https://linux-hardware.org/?probe=6ab2d189e5) | Mar 28, 2024 |
| ASUSTek       | P8P67                       | Desktop     | [eae7373113](https://linux-hardware.org/?probe=eae7373113) | Mar 28, 2024 |
| Gigabyte      | A620M DS3H                  | Desktop     | [2b5f386cb4](https://linux-hardware.org/?probe=2b5f386cb4) | Mar 28, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [c1a3cee107](https://linux-hardware.org/?probe=c1a3cee107) | Mar 28, 2024 |
| Dell          | 0MN1TX A00                  | Desktop     | [8cef7b13b5](https://linux-hardware.org/?probe=8cef7b13b5) | Mar 27, 2024 |
| Dell          | 0MN1TX A00                  | Desktop     | [6a8ffef6f2](https://linux-hardware.org/?probe=6a8ffef6f2) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [deae5b6cdf](https://linux-hardware.org/?probe=deae5b6cdf) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [602d79d663](https://linux-hardware.org/?probe=602d79d663) | Mar 27, 2024 |
| Acer          | Aspire A515-57G             | Notebook    | [95c573af0a](https://linux-hardware.org/?probe=95c573af0a) | Mar 27, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [35cbc2ccda](https://linux-hardware.org/?probe=35cbc2ccda) | Mar 27, 2024 |
| Dell          | 02GDWG A00                  | Desktop     | [a138fcbf39](https://linux-hardware.org/?probe=a138fcbf39) | Mar 26, 2024 |
| Dell          | 0GU083 A00                  | Desktop     | [c7a2de496a](https://linux-hardware.org/?probe=c7a2de496a) | Mar 26, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [27255ef603](https://linux-hardware.org/?probe=27255ef603) | Mar 26, 2024 |
| Dell          | Inspiron 1440               | Notebook    | [e7bae8d9bc](https://linux-hardware.org/?probe=e7bae8d9bc) | Mar 26, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [e98dcc5095](https://linux-hardware.org/?probe=e98dcc5095) | Mar 26, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [8f754c740b](https://linux-hardware.org/?probe=8f754c740b) | Mar 26, 2024 |
| ASUSTek       | G750JZA                     | Notebook    | [12d8540af3](https://linux-hardware.org/?probe=12d8540af3) | Mar 26, 2024 |
| MSI           | PRO Z790-S WIFI             | Desktop     | [ecaa8a51cb](https://linux-hardware.org/?probe=ecaa8a51cb) | Mar 26, 2024 |
| HP            | ENVY 15                     | Notebook    | [11821b80b7](https://linux-hardware.org/?probe=11821b80b7) | Mar 26, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [d31e841f4d](https://linux-hardware.org/?probe=d31e841f4d) | Mar 25, 2024 |
| Alienware     | m15 R4                      | Notebook    | [3f0488b05c](https://linux-hardware.org/?probe=3f0488b05c) | Mar 25, 2024 |
| System76      | Bonobo WS                   | Notebook    | [856360e11c](https://linux-hardware.org/?probe=856360e11c) | Mar 25, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [efbd82bed8](https://linux-hardware.org/?probe=efbd82bed8) | Mar 25, 2024 |
| Intel         | NUC7i5BNB J31144-312        | Mini pc     | [f54e1033d4](https://linux-hardware.org/?probe=f54e1033d4) | Mar 25, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [4aa12cd64e](https://linux-hardware.org/?probe=4aa12cd64e) | Mar 24, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [c9a90af50f](https://linux-hardware.org/?probe=c9a90af50f) | Mar 24, 2024 |
| Google        | Markarth                    | Notebook    | [9987cda5ae](https://linux-hardware.org/?probe=9987cda5ae) | Mar 24, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [b63a7b1490](https://linux-hardware.org/?probe=b63a7b1490) | Mar 24, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [fad6108f0a](https://linux-hardware.org/?probe=fad6108f0a) | Mar 24, 2024 |
| System76      | Gazelle                     | Notebook    | [a2b4d889db](https://linux-hardware.org/?probe=a2b4d889db) | Mar 24, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [0cd4aa5f8a](https://linux-hardware.org/?probe=0cd4aa5f8a) | Mar 24, 2024 |
| Alienware     | m15 R7                      | Notebook    | [27cc6ca1d6](https://linux-hardware.org/?probe=27cc6ca1d6) | Mar 24, 2024 |
| Dell          | Vostro 1015                 | Notebook    | [5cea7dba17](https://linux-hardware.org/?probe=5cea7dba17) | Mar 23, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [7fc01abc25](https://linux-hardware.org/?probe=7fc01abc25) | Mar 23, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [90d0e194f9](https://linux-hardware.org/?probe=90d0e194f9) | Mar 23, 2024 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [e294f4440c](https://linux-hardware.org/?probe=e294f4440c) | Mar 22, 2024 |
| Acer          | Aspire Z5600                | All in one  | [0a3febbfe2](https://linux-hardware.org/?probe=0a3febbfe2) | Mar 22, 2024 |
| MSI           | Cyborg 15 A12VE             | Notebook    | [012a9393ab](https://linux-hardware.org/?probe=012a9393ab) | Mar 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [a0855ed46b](https://linux-hardware.org/?probe=a0855ed46b) | Mar 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [899cb71147](https://linux-hardware.org/?probe=899cb71147) | Mar 22, 2024 |
| HP            | 83EF                        | Desktop     | [a2e4b98916](https://linux-hardware.org/?probe=a2e4b98916) | Mar 22, 2024 |
| HP            | 83EF                        | Desktop     | [79c2564db3](https://linux-hardware.org/?probe=79c2564db3) | Mar 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2c74228344](https://linux-hardware.org/?probe=2c74228344) | Mar 22, 2024 |
| Dell          | Latitude E7240              | Notebook    | [a295e64d94](https://linux-hardware.org/?probe=a295e64d94) | Mar 21, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [eecdc4a970](https://linux-hardware.org/?probe=eecdc4a970) | Mar 21, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0a1b9c732b](https://linux-hardware.org/?probe=0a1b9c732b) | Mar 21, 2024 |
| Lenovo        | ThinkPad X395 20NMS13801    | Notebook    | [bf71f2099b](https://linux-hardware.org/?probe=bf71f2099b) | Mar 21, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [0565d53d0c](https://linux-hardware.org/?probe=0565d53d0c) | Mar 21, 2024 |
| Dell          | Precision M4700             | Notebook    | [212d29f26d](https://linux-hardware.org/?probe=212d29f26d) | Mar 21, 2024 |
| Dell          | 03X6X0 A03                  | Server      | [7ded435bf2](https://linux-hardware.org/?probe=7ded435bf2) | Mar 21, 2024 |
| Dell          | 03X6X0 A06                  | Server      | [bb6453dda7](https://linux-hardware.org/?probe=bb6453dda7) | Mar 21, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0293382f9b](https://linux-hardware.org/?probe=0293382f9b) | Mar 21, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [caecf9a750](https://linux-hardware.org/?probe=caecf9a750) | Mar 21, 2024 |
| Dell          | Latitude E6540              | Notebook    | [c3883595b9](https://linux-hardware.org/?probe=c3883595b9) | Mar 21, 2024 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [e7ea34fd49](https://linux-hardware.org/?probe=e7ea34fd49) | Mar 20, 2024 |
| MSI           | Z170A GAMING M3             | Desktop     | [8e89b3ef32](https://linux-hardware.org/?probe=8e89b3ef32) | Mar 20, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [302a31192b](https://linux-hardware.org/?probe=302a31192b) | Mar 20, 2024 |
| MSI           | Cyborg 15 A12VE             | Notebook    | [e0dce5359f](https://linux-hardware.org/?probe=e0dce5359f) | Mar 20, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [56b4e033b8](https://linux-hardware.org/?probe=56b4e033b8) | Mar 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | Notebook    | [b912e786a3](https://linux-hardware.org/?probe=b912e786a3) | Mar 20, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [a06517f205](https://linux-hardware.org/?probe=a06517f205) | Mar 20, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | Notebook    | [0e0638700d](https://linux-hardware.org/?probe=0e0638700d) | Mar 20, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | Notebook    | [e8c3803d3c](https://linux-hardware.org/?probe=e8c3803d3c) | Mar 20, 2024 |
| Dell          | Latitude 5410               | Notebook    | [291ea4843c](https://linux-hardware.org/?probe=291ea4843c) | Mar 20, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [d1ba139b4e](https://linux-hardware.org/?probe=d1ba139b4e) | Mar 19, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [6c38602470](https://linux-hardware.org/?probe=6c38602470) | Mar 19, 2024 |
| HONOR         | GLO-GXXX                    | Notebook    | [aa0a3c2273](https://linux-hardware.org/?probe=aa0a3c2273) | Mar 19, 2024 |
| HONOR         | GLO-GXXX                    | Notebook    | [e6fbe7ffad](https://linux-hardware.org/?probe=e6fbe7ffad) | Mar 19, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [7400d40886](https://linux-hardware.org/?probe=7400d40886) | Mar 19, 2024 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [f8a39666b9](https://linux-hardware.org/?probe=f8a39666b9) | Mar 19, 2024 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [74127be2ca](https://linux-hardware.org/?probe=74127be2ca) | Mar 19, 2024 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [3bef14d11e](https://linux-hardware.org/?probe=3bef14d11e) | Mar 19, 2024 |
| Dell          | Latitude 7440               | Notebook    | [143c9f9828](https://linux-hardware.org/?probe=143c9f9828) | Mar 19, 2024 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [eaea13606f](https://linux-hardware.org/?probe=eaea13606f) | Mar 19, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [37a57d5b70](https://linux-hardware.org/?probe=37a57d5b70) | Mar 19, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [f391ae9078](https://linux-hardware.org/?probe=f391ae9078) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8SCLH0... | Notebook    | [a568c4313e](https://linux-hardware.org/?probe=a568c4313e) | Mar 18, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [0eaf5f5be0](https://linux-hardware.org/?probe=0eaf5f5be0) | Mar 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402NU... | Notebook    | [10d62d48f9](https://linux-hardware.org/?probe=10d62d48f9) | Mar 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2d61b43821](https://linux-hardware.org/?probe=2d61b43821) | Mar 18, 2024 |
| Notebook      | N15_N17RD1                  | Notebook    | [7bf6fa9d9f](https://linux-hardware.org/?probe=7bf6fa9d9f) | Mar 18, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [2cc34ee9da](https://linux-hardware.org/?probe=2cc34ee9da) | Mar 18, 2024 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [9a29b7badd](https://linux-hardware.org/?probe=9a29b7badd) | Mar 17, 2024 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [6e83554006](https://linux-hardware.org/?probe=6e83554006) | Mar 17, 2024 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [16b029f8b8](https://linux-hardware.org/?probe=16b029f8b8) | Mar 17, 2024 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [aae3b4bf83](https://linux-hardware.org/?probe=aae3b4bf83) | Mar 17, 2024 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [311809b062](https://linux-hardware.org/?probe=311809b062) | Mar 16, 2024 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [72eb92fb02](https://linux-hardware.org/?probe=72eb92fb02) | Mar 16, 2024 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e9eaacfaa2](https://linux-hardware.org/?probe=e9eaacfaa2) | Mar 15, 2024 |
| Lenovo        | ThinkPad T480s 20L8SCLH0... | Notebook    | [fd91f6e0b8](https://linux-hardware.org/?probe=fd91f6e0b8) | Mar 15, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [0ba8678964](https://linux-hardware.org/?probe=0ba8678964) | Mar 15, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [7f865ffb79](https://linux-hardware.org/?probe=7f865ffb79) | Mar 15, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [ed06ccc20a](https://linux-hardware.org/?probe=ed06ccc20a) | Mar 15, 2024 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [d1bf96e346](https://linux-hardware.org/?probe=d1bf96e346) | Mar 14, 2024 |
| Lenovo        | Yoga 7 14IRL8 82YL          | Convertible | [386d1f0817](https://linux-hardware.org/?probe=386d1f0817) | Mar 14, 2024 |
| Lenovo        | ThinkPad T420 4236PFG       | Notebook    | [66167283a7](https://linux-hardware.org/?probe=66167283a7) | Mar 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [37260aa51d](https://linux-hardware.org/?probe=37260aa51d) | Mar 14, 2024 |
| Jumper        | EZbook                      | Notebook    | [65469deb97](https://linux-hardware.org/?probe=65469deb97) | Mar 14, 2024 |
| System76      | Thelio thelio-r2            | Desktop     | [609e72eef1](https://linux-hardware.org/?probe=609e72eef1) | Mar 14, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [d2921f8721](https://linux-hardware.org/?probe=d2921f8721) | Mar 13, 2024 |
| Gigabyte      | H310M S2P                   | Desktop     | [3d5cf9dd65](https://linux-hardware.org/?probe=3d5cf9dd65) | Mar 13, 2024 |
| Dell          | Inspiron 5575               | Notebook    | [982b876f87](https://linux-hardware.org/?probe=982b876f87) | Mar 13, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [6a41c6be0e](https://linux-hardware.org/?probe=6a41c6be0e) | Mar 13, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [3eb6a86b95](https://linux-hardware.org/?probe=3eb6a86b95) | Mar 13, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [4cfd0ba254](https://linux-hardware.org/?probe=4cfd0ba254) | Mar 13, 2024 |
| Google        | Gallop                      | Notebook    | [eeaa5535f7](https://linux-hardware.org/?probe=eeaa5535f7) | Mar 12, 2024 |
| HP            | ProBook 470 G3              | Notebook    | [7acbeb9e50](https://linux-hardware.org/?probe=7acbeb9e50) | Mar 12, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [006a9be33e](https://linux-hardware.org/?probe=006a9be33e) | Mar 12, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [d5d941f35c](https://linux-hardware.org/?probe=d5d941f35c) | Mar 12, 2024 |
| Dell          | Latitude 5420               | Notebook    | [e49cabfe78](https://linux-hardware.org/?probe=e49cabfe78) | Mar 12, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4dd7fe8d84](https://linux-hardware.org/?probe=4dd7fe8d84) | Mar 11, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c5a33c09f1](https://linux-hardware.org/?probe=c5a33c09f1) | Mar 11, 2024 |
| Dell          | G7 7588                     | Notebook    | [201e08795e](https://linux-hardware.org/?probe=201e08795e) | Mar 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [66ebc0d790](https://linux-hardware.org/?probe=66ebc0d790) | Mar 11, 2024 |
| Dell          | Vostro 15 5510              | Notebook    | [1635f8ee88](https://linux-hardware.org/?probe=1635f8ee88) | Mar 11, 2024 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [c0420b6b81](https://linux-hardware.org/?probe=c0420b6b81) | Mar 11, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [03dbb01a57](https://linux-hardware.org/?probe=03dbb01a57) | Mar 11, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [bf63e4ac63](https://linux-hardware.org/?probe=bf63e4ac63) | Mar 10, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [f3fc324ad6](https://linux-hardware.org/?probe=f3fc324ad6) | Mar 10, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | Notebook    | [695773aa7b](https://linux-hardware.org/?probe=695773aa7b) | Mar 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [a56ff930d5](https://linux-hardware.org/?probe=a56ff930d5) | Mar 10, 2024 |
| Intel         | B75                         | Desktop     | [d0ba74ec7d](https://linux-hardware.org/?probe=d0ba74ec7d) | Mar 10, 2024 |
| Dell          | Latitude 7490               | Notebook    | [93e3272d83](https://linux-hardware.org/?probe=93e3272d83) | Mar 10, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [174fa8b213](https://linux-hardware.org/?probe=174fa8b213) | Mar 09, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d8c5dd5832](https://linux-hardware.org/?probe=d8c5dd5832) | Mar 09, 2024 |
| eMachines     | E525                        | Notebook    | [4a4a1ac342](https://linux-hardware.org/?probe=4a4a1ac342) | Mar 09, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [35cdd04e44](https://linux-hardware.org/?probe=35cdd04e44) | Mar 08, 2024 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e4a401d044](https://linux-hardware.org/?probe=e4a401d044) | Mar 08, 2024 |
| Dell          | Latitude 5530               | Notebook    | [474a88cccf](https://linux-hardware.org/?probe=474a88cccf) | Mar 08, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [ded3e0cf33](https://linux-hardware.org/?probe=ded3e0cf33) | Mar 08, 2024 |
| System76      | Gazelle                     | Notebook    | [c054444856](https://linux-hardware.org/?probe=c054444856) | Mar 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [439a24ca9f](https://linux-hardware.org/?probe=439a24ca9f) | Mar 07, 2024 |
| Dell          | Latitude 5530               | Notebook    | [252c53438e](https://linux-hardware.org/?probe=252c53438e) | Mar 07, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b07882e6fb](https://linux-hardware.org/?probe=b07882e6fb) | Mar 07, 2024 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [6f9c47ea33](https://linux-hardware.org/?probe=6f9c47ea33) | Mar 07, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | Desktop     | [f9fa747b4f](https://linux-hardware.org/?probe=f9fa747b4f) | Mar 07, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [635244de96](https://linux-hardware.org/?probe=635244de96) | Mar 07, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [431439414a](https://linux-hardware.org/?probe=431439414a) | Mar 07, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [571cf278dd](https://linux-hardware.org/?probe=571cf278dd) | Mar 07, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [bb4c0ce2be](https://linux-hardware.org/?probe=bb4c0ce2be) | Mar 06, 2024 |
| Lenovo        | ThinkPad E15 20RD0014RT     | Notebook    | [b12b855825](https://linux-hardware.org/?probe=b12b855825) | Mar 06, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [d5ee5ee229](https://linux-hardware.org/?probe=d5ee5ee229) | Mar 06, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [994590f6a8](https://linux-hardware.org/?probe=994590f6a8) | Mar 06, 2024 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [b62ec8f9a0](https://linux-hardware.org/?probe=b62ec8f9a0) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1446f9eae8](https://linux-hardware.org/?probe=1446f9eae8) | Mar 05, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [957fd824c5](https://linux-hardware.org/?probe=957fd824c5) | Mar 05, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bc08a4f316](https://linux-hardware.org/?probe=bc08a4f316) | Mar 05, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d746e0ee2c](https://linux-hardware.org/?probe=d746e0ee2c) | Mar 05, 2024 |
| Alienware     | M14xR1                      | Notebook    | [67cc7d7e63](https://linux-hardware.org/?probe=67cc7d7e63) | Mar 05, 2024 |
| Dell          | G7 7500                     | Notebook    | [89b81d9c37](https://linux-hardware.org/?probe=89b81d9c37) | Mar 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b11673c68a](https://linux-hardware.org/?probe=b11673c68a) | Mar 05, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [3772b43c62](https://linux-hardware.org/?probe=3772b43c62) | Mar 05, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f015ff4f75](https://linux-hardware.org/?probe=f015ff4f75) | Mar 05, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [141c46ed9d](https://linux-hardware.org/?probe=141c46ed9d) | Mar 05, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [3b0efc2689](https://linux-hardware.org/?probe=3b0efc2689) | Mar 05, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e415b0c776](https://linux-hardware.org/?probe=e415b0c776) | Mar 04, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [01c04e14c0](https://linux-hardware.org/?probe=01c04e14c0) | Mar 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c3d8b404f8](https://linux-hardware.org/?probe=c3d8b404f8) | Mar 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ce218789c2](https://linux-hardware.org/?probe=ce218789c2) | Mar 04, 2024 |
| Intel         | B75                         | Desktop     | [2b0d558a5e](https://linux-hardware.org/?probe=2b0d558a5e) | Mar 04, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2f64045bb9](https://linux-hardware.org/?probe=2f64045bb9) | Mar 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [95bfa43508](https://linux-hardware.org/?probe=95bfa43508) | Mar 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1eb604d726](https://linux-hardware.org/?probe=1eb604d726) | Mar 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [c304c6e324](https://linux-hardware.org/?probe=c304c6e324) | Mar 04, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [d65faae98f](https://linux-hardware.org/?probe=d65faae98f) | Mar 03, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [abbcee09db](https://linux-hardware.org/?probe=abbcee09db) | Mar 03, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [040699f391](https://linux-hardware.org/?probe=040699f391) | Mar 03, 2024 |
| ASUSTek       | GL552VX                     | Notebook    | [01ea0912c3](https://linux-hardware.org/?probe=01ea0912c3) | Mar 03, 2024 |
| AZW           | MINI S                      | Desktop     | [dc07e234d0](https://linux-hardware.org/?probe=dc07e234d0) | Mar 03, 2024 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [94a7d20873](https://linux-hardware.org/?probe=94a7d20873) | Mar 03, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b957a4b5d8](https://linux-hardware.org/?probe=b957a4b5d8) | Mar 03, 2024 |
| Alienware     | M14xR1                      | Notebook    | [5b5b4ae985](https://linux-hardware.org/?probe=5b5b4ae985) | Mar 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c2b4500a60](https://linux-hardware.org/?probe=c2b4500a60) | Mar 03, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [73bd3cf050](https://linux-hardware.org/?probe=73bd3cf050) | Mar 03, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a0a450644b](https://linux-hardware.org/?probe=a0a450644b) | Mar 02, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [e8dae907db](https://linux-hardware.org/?probe=e8dae907db) | Mar 02, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [7749349961](https://linux-hardware.org/?probe=7749349961) | Mar 02, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [67a9619322](https://linux-hardware.org/?probe=67a9619322) | Mar 02, 2024 |
| System76      | Pangolin                    | Notebook    | [a130fc52f6](https://linux-hardware.org/?probe=a130fc52f6) | Mar 02, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [78090262bb](https://linux-hardware.org/?probe=78090262bb) | Mar 02, 2024 |
| Dell          | 02GDWG A00                  | Desktop     | [dd54511393](https://linux-hardware.org/?probe=dd54511393) | Mar 01, 2024 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [13c3d127e8](https://linux-hardware.org/?probe=13c3d127e8) | Mar 01, 2024 |
| System76      | Oryx Pro                    | Notebook    | [6f389be12b](https://linux-hardware.org/?probe=6f389be12b) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [cda628788e](https://linux-hardware.org/?probe=cda628788e) | Mar 01, 2024 |
| HP            | 843B                        | Desktop     | [4293861b42](https://linux-hardware.org/?probe=4293861b42) | Mar 01, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [6e720badd3](https://linux-hardware.org/?probe=6e720badd3) | Mar 01, 2024 |
| HP            | 18E9                        | Desktop     | [9bdda08a35](https://linux-hardware.org/?probe=9bdda08a35) | Mar 01, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [223fbfa988](https://linux-hardware.org/?probe=223fbfa988) | Feb 29, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [d418108f92](https://linux-hardware.org/?probe=d418108f92) | Feb 29, 2024 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [470be089f8](https://linux-hardware.org/?probe=470be089f8) | Feb 29, 2024 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [07e47bd9aa](https://linux-hardware.org/?probe=07e47bd9aa) | Feb 29, 2024 |
| ASRock        | H97 Anniversary             | Desktop     | [f4f4c960d4](https://linux-hardware.org/?probe=f4f4c960d4) | Feb 28, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [ecfd2b2c9f](https://linux-hardware.org/?probe=ecfd2b2c9f) | Feb 28, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [365e852379](https://linux-hardware.org/?probe=365e852379) | Feb 28, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [5c749148f2](https://linux-hardware.org/?probe=5c749148f2) | Feb 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [bccc7e9b25](https://linux-hardware.org/?probe=bccc7e9b25) | Feb 27, 2024 |
| Intel         | H410M                       | Desktop     | [b22fd32a7d](https://linux-hardware.org/?probe=b22fd32a7d) | Feb 27, 2024 |
| ASUSTek       | N53SN                       | Notebook    | [c628351d6c](https://linux-hardware.org/?probe=c628351d6c) | Feb 27, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [df29939277](https://linux-hardware.org/?probe=df29939277) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [3ea80caf07](https://linux-hardware.org/?probe=3ea80caf07) | Feb 27, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [19a2ccc504](https://linux-hardware.org/?probe=19a2ccc504) | Feb 27, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ac48e41763](https://linux-hardware.org/?probe=ac48e41763) | Feb 27, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [a7e7b853e8](https://linux-hardware.org/?probe=a7e7b853e8) | Feb 27, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [15510ee9c4](https://linux-hardware.org/?probe=15510ee9c4) | Feb 27, 2024 |
| JGINYUE       | B550i-GAMING                | Desktop     | [8d44c9ccdd](https://linux-hardware.org/?probe=8d44c9ccdd) | Feb 27, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1817f5af30](https://linux-hardware.org/?probe=1817f5af30) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0ef3ee0033](https://linux-hardware.org/?probe=0ef3ee0033) | Feb 27, 2024 |
| Acer          | Aspire V3-372               | Notebook    | [fcd3114d4b](https://linux-hardware.org/?probe=fcd3114d4b) | Feb 26, 2024 |
| Dell          | Latitude 5300               | Notebook    | [8ab46e0ae3](https://linux-hardware.org/?probe=8ab46e0ae3) | Feb 26, 2024 |
| TrekStor      | Notebook Slim S130          | Notebook    | [534a53e131](https://linux-hardware.org/?probe=534a53e131) | Feb 26, 2024 |
| ASUSTek       | F2A85-M                     | Desktop     | [a78b141db1](https://linux-hardware.org/?probe=a78b141db1) | Feb 26, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [2ddd148d6c](https://linux-hardware.org/?probe=2ddd148d6c) | Feb 26, 2024 |
| Microsoft     | Surface Laptop              | Tablet      | [5c52c359bc](https://linux-hardware.org/?probe=5c52c359bc) | Feb 26, 2024 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [4f5f9307d6](https://linux-hardware.org/?probe=4f5f9307d6) | Feb 25, 2024 |
| Sony          | VPCCA2S0E                   | Notebook    | [ded9134c14](https://linux-hardware.org/?probe=ded9134c14) | Feb 25, 2024 |
| Sony          | VPCCA2S0E                   | Notebook    | [360e87199c](https://linux-hardware.org/?probe=360e87199c) | Feb 25, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2b4ed9044c](https://linux-hardware.org/?probe=2b4ed9044c) | Feb 25, 2024 |
| TrekStor      | Notebook Slim S130          | Notebook    | [829f6953a7](https://linux-hardware.org/?probe=829f6953a7) | Feb 25, 2024 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [e302c30d09](https://linux-hardware.org/?probe=e302c30d09) | Feb 25, 2024 |
| Dell          | Inspiron 7559               | Notebook    | [678e86bdeb](https://linux-hardware.org/?probe=678e86bdeb) | Feb 25, 2024 |
| Apple         | MacBookAir3,2               | Notebook    | [82df38cf02](https://linux-hardware.org/?probe=82df38cf02) | Feb 24, 2024 |
| Microsoft     | Surface Book 3              | Tablet      | [57bf97260f](https://linux-hardware.org/?probe=57bf97260f) | Feb 24, 2024 |
| Intel         | NUC7i3BNB J22859-315        | Mini pc     | [f043196e8c](https://linux-hardware.org/?probe=f043196e8c) | Feb 24, 2024 |
| HP            | ProBook 4730s               | Notebook    | [9441592753](https://linux-hardware.org/?probe=9441592753) | Feb 24, 2024 |
| HP            | ProBook 4730s               | Notebook    | [558fc0a500](https://linux-hardware.org/?probe=558fc0a500) | Feb 24, 2024 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [f6c4f78658](https://linux-hardware.org/?probe=f6c4f78658) | Feb 24, 2024 |
| Dell          | Precision 3571              | Notebook    | [4392bfe153](https://linux-hardware.org/?probe=4392bfe153) | Feb 24, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [edd37fc93e](https://linux-hardware.org/?probe=edd37fc93e) | Feb 24, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [650af37e87](https://linux-hardware.org/?probe=650af37e87) | Feb 23, 2024 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [bc9dad6852](https://linux-hardware.org/?probe=bc9dad6852) | Feb 23, 2024 |
| Lenovo        | 330B SDK0T76538 WIN 3556... | Mini pc     | [c352bcabc4](https://linux-hardware.org/?probe=c352bcabc4) | Feb 23, 2024 |
| MSI           | MS-B9171                    | Desktop     | [8d8e1e76c8](https://linux-hardware.org/?probe=8d8e1e76c8) | Feb 23, 2024 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [be154598ff](https://linux-hardware.org/?probe=be154598ff) | Feb 23, 2024 |
| ASUSTek       | Z87-K                       | Desktop     | [82f0780a43](https://linux-hardware.org/?probe=82f0780a43) | Feb 23, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [7ed2cffcae](https://linux-hardware.org/?probe=7ed2cffcae) | Feb 23, 2024 |
| Dell          | Precision 5550              | Notebook    | [f362deda15](https://linux-hardware.org/?probe=f362deda15) | Feb 22, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [bade017d6b](https://linux-hardware.org/?probe=bade017d6b) | Feb 22, 2024 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [9c9f621388](https://linux-hardware.org/?probe=9c9f621388) | Feb 21, 2024 |
| Dell          | Latitude E5420              | Notebook    | [910bc98f57](https://linux-hardware.org/?probe=910bc98f57) | Feb 21, 2024 |
| ASUSTek       | Z87-K                       | Desktop     | [d091e6a911](https://linux-hardware.org/?probe=d091e6a911) | Feb 21, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [8070df1f8e](https://linux-hardware.org/?probe=8070df1f8e) | Feb 21, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [9dae96099a](https://linux-hardware.org/?probe=9dae96099a) | Feb 21, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [dd7412b565](https://linux-hardware.org/?probe=dd7412b565) | Feb 21, 2024 |
| Dell          | Precision M4800             | Notebook    | [60660b2530](https://linux-hardware.org/?probe=60660b2530) | Feb 21, 2024 |
| Dell          | Latitude 5580               | Notebook    | [b83380f87b](https://linux-hardware.org/?probe=b83380f87b) | Feb 21, 2024 |
| Dream Mach... | Gaming Laptop               | Notebook    | [fb169a7c4d](https://linux-hardware.org/?probe=fb169a7c4d) | Feb 20, 2024 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [119689a507](https://linux-hardware.org/?probe=119689a507) | Feb 20, 2024 |
| Dell          | Latitude 7480               | Notebook    | [99c8492288](https://linux-hardware.org/?probe=99c8492288) | Feb 20, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [801c073182](https://linux-hardware.org/?probe=801c073182) | Feb 20, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [a5ad93fa0a](https://linux-hardware.org/?probe=a5ad93fa0a) | Feb 20, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [08191524c7](https://linux-hardware.org/?probe=08191524c7) | Feb 20, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [caf3ea0d9a](https://linux-hardware.org/?probe=caf3ea0d9a) | Feb 20, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [109256318a](https://linux-hardware.org/?probe=109256318a) | Feb 20, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [e65b561651](https://linux-hardware.org/?probe=e65b561651) | Feb 20, 2024 |
| Intel         | H55                         | Desktop     | [77825586e5](https://linux-hardware.org/?probe=77825586e5) | Feb 20, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [f8d09630be](https://linux-hardware.org/?probe=f8d09630be) | Feb 20, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [5eb44e20c3](https://linux-hardware.org/?probe=5eb44e20c3) | Feb 20, 2024 |
| HP            | 885F A                      | Desktop     | [0e14337b75](https://linux-hardware.org/?probe=0e14337b75) | Feb 20, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [f0a5c0c659](https://linux-hardware.org/?probe=f0a5c0c659) | Feb 19, 2024 |
| Dell          | Latitude E7250              | Notebook    | [4dbb95d349](https://linux-hardware.org/?probe=4dbb95d349) | Feb 19, 2024 |
| BESSTAR Te... | B550                        | Desktop     | [864d3987bc](https://linux-hardware.org/?probe=864d3987bc) | Feb 19, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [748c41cfa2](https://linux-hardware.org/?probe=748c41cfa2) | Feb 19, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [b05150cb04](https://linux-hardware.org/?probe=b05150cb04) | Feb 19, 2024 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [d0562f4f40](https://linux-hardware.org/?probe=d0562f4f40) | Feb 19, 2024 |
| Dell          | 0J3C2F A02                  | Desktop     | [17a18809d8](https://linux-hardware.org/?probe=17a18809d8) | Feb 18, 2024 |
| Pegatron      | B34C                        | Notebook    | [a062b68bf6](https://linux-hardware.org/?probe=a062b68bf6) | Feb 18, 2024 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e115b602d3](https://linux-hardware.org/?probe=e115b602d3) | Feb 18, 2024 |
| Acer          | Aspire A515-56              | Notebook    | [11f162f567](https://linux-hardware.org/?probe=11f162f567) | Feb 18, 2024 |
| Gigabyte      | Q87M-MK                     | Desktop     | [31f52cfaa6](https://linux-hardware.org/?probe=31f52cfaa6) | Feb 18, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [1a618047be](https://linux-hardware.org/?probe=1a618047be) | Feb 18, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a7cb58e0b9](https://linux-hardware.org/?probe=a7cb58e0b9) | Feb 18, 2024 |
| System76      | Gazelle                     | Notebook    | [6e2b31138f](https://linux-hardware.org/?probe=6e2b31138f) | Feb 18, 2024 |
| Dell          | XPS 12 9Q23                 | Notebook    | [7246414ea4](https://linux-hardware.org/?probe=7246414ea4) | Feb 18, 2024 |
| HP            | 82F2                        | Desktop     | [10051f1b07](https://linux-hardware.org/?probe=10051f1b07) | Feb 18, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [2d7aaba177](https://linux-hardware.org/?probe=2d7aaba177) | Feb 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [df466668e4](https://linux-hardware.org/?probe=df466668e4) | Feb 17, 2024 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [c6883405b2](https://linux-hardware.org/?probe=c6883405b2) | Feb 17, 2024 |
| MSI           | GE72 6QC                    | Notebook    | [bf8edb1354](https://linux-hardware.org/?probe=bf8edb1354) | Feb 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ac497abd97](https://linux-hardware.org/?probe=ac497abd97) | Feb 17, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [8c9f92e873](https://linux-hardware.org/?probe=8c9f92e873) | Feb 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5e4e265aeb](https://linux-hardware.org/?probe=5e4e265aeb) | Feb 16, 2024 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [993110fab0](https://linux-hardware.org/?probe=993110fab0) | Feb 16, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [16a3b93921](https://linux-hardware.org/?probe=16a3b93921) | Feb 16, 2024 |
| ASUSTek       | K95VJ                       | Notebook    | [c82a491d01](https://linux-hardware.org/?probe=c82a491d01) | Feb 16, 2024 |
| Microsoft     | Surface 3                   | Tablet      | [f1cb1cf700](https://linux-hardware.org/?probe=f1cb1cf700) | Feb 16, 2024 |
| Acer          | Aspire S3                   | Notebook    | [015a6bdb09](https://linux-hardware.org/?probe=015a6bdb09) | Feb 16, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [1c2c9a3671](https://linux-hardware.org/?probe=1c2c9a3671) | Feb 16, 2024 |
| HP            | Pavilion dv6                | Notebook    | [27bd273fa1](https://linux-hardware.org/?probe=27bd273fa1) | Feb 16, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dbe01c0fc4](https://linux-hardware.org/?probe=dbe01c0fc4) | Feb 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [176496db32](https://linux-hardware.org/?probe=176496db32) | Feb 16, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [17be6d540f](https://linux-hardware.org/?probe=17be6d540f) | Feb 16, 2024 |
| Microsoft     | Surface 3                   | Tablet      | [31c8d647b1](https://linux-hardware.org/?probe=31c8d647b1) | Feb 16, 2024 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [c98ffdb659](https://linux-hardware.org/?probe=c98ffdb659) | Feb 16, 2024 |
| Dell          | Precision 7510              | Notebook    | [c6c77a8fc8](https://linux-hardware.org/?probe=c6c77a8fc8) | Feb 16, 2024 |
| HP            | Pavilion dv6                | Notebook    | [fd84d867f4](https://linux-hardware.org/?probe=fd84d867f4) | Feb 15, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [06ec01ce9a](https://linux-hardware.org/?probe=06ec01ce9a) | Feb 15, 2024 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [8e7c6becd2](https://linux-hardware.org/?probe=8e7c6becd2) | Feb 14, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [76f7aa1d25](https://linux-hardware.org/?probe=76f7aa1d25) | Feb 14, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cef87c0391](https://linux-hardware.org/?probe=cef87c0391) | Feb 14, 2024 |
| Fujitsu       | D3118-A2 S26361-D3118-A2    | Desktop     | [169a2bedd3](https://linux-hardware.org/?probe=169a2bedd3) | Feb 14, 2024 |
| Acer          | Aspire A515-56              | Notebook    | [8145ab17cc](https://linux-hardware.org/?probe=8145ab17cc) | Feb 14, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [66417e286c](https://linux-hardware.org/?probe=66417e286c) | Feb 14, 2024 |
| Acer          | Predator PO3-640            | Desktop     | [4e920c60c3](https://linux-hardware.org/?probe=4e920c60c3) | Feb 14, 2024 |
| Acer          | Predator PO3-640            | Desktop     | [b081b6359d](https://linux-hardware.org/?probe=b081b6359d) | Feb 13, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [dca7100475](https://linux-hardware.org/?probe=dca7100475) | Feb 13, 2024 |
| ASRock        | A320M/ac                    | Desktop     | [adc9f93ca8](https://linux-hardware.org/?probe=adc9f93ca8) | Feb 13, 2024 |
| HP            | 2B2C                        | Desktop     | [a39c469e43](https://linux-hardware.org/?probe=a39c469e43) | Feb 13, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [25f5e2c229](https://linux-hardware.org/?probe=25f5e2c229) | Feb 12, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [1e8eb3e275](https://linux-hardware.org/?probe=1e8eb3e275) | Feb 12, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [6fb885473c](https://linux-hardware.org/?probe=6fb885473c) | Feb 12, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [0ccb8813c9](https://linux-hardware.org/?probe=0ccb8813c9) | Feb 12, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [cd577ce860](https://linux-hardware.org/?probe=cd577ce860) | Feb 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [07b16ebca5](https://linux-hardware.org/?probe=07b16ebca5) | Feb 11, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [6e8ebecbf2](https://linux-hardware.org/?probe=6e8ebecbf2) | Feb 11, 2024 |
| ASUSTek       | P8H61                       | Desktop     | [6b53ddd469](https://linux-hardware.org/?probe=6b53ddd469) | Feb 11, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [49dbf62b09](https://linux-hardware.org/?probe=49dbf62b09) | Feb 11, 2024 |
| Dell          | Latitude E7270              | Notebook    | [cd13d3c338](https://linux-hardware.org/?probe=cd13d3c338) | Feb 11, 2024 |
| Supermicro    | X12SPA-TF                   | Server      | [90e037efc5](https://linux-hardware.org/?probe=90e037efc5) | Feb 10, 2024 |
| Acer          | Aspire A514-53              | Notebook    | [70b16c69f0](https://linux-hardware.org/?probe=70b16c69f0) | Feb 10, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGC... | Notebook    | [8567f0b4d1](https://linux-hardware.org/?probe=8567f0b4d1) | Feb 10, 2024 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [bc3902b1d1](https://linux-hardware.org/?probe=bc3902b1d1) | Feb 09, 2024 |
| HP            | 18E5                        | Desktop     | [3e90471e97](https://linux-hardware.org/?probe=3e90471e97) | Feb 09, 2024 |
| HP            | 18E5                        | Desktop     | [9ae685a4cb](https://linux-hardware.org/?probe=9ae685a4cb) | Feb 09, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [b87e3aded5](https://linux-hardware.org/?probe=b87e3aded5) | Feb 09, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [0d1cdf2ae8](https://linux-hardware.org/?probe=0d1cdf2ae8) | Feb 09, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [5ecacd2214](https://linux-hardware.org/?probe=5ecacd2214) | Feb 09, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [329de876ea](https://linux-hardware.org/?probe=329de876ea) | Feb 09, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [76eb2071c4](https://linux-hardware.org/?probe=76eb2071c4) | Feb 09, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [7f77d98ba4](https://linux-hardware.org/?probe=7f77d98ba4) | Feb 09, 2024 |
| HP            | ProBook 6450b               | Notebook    | [423b15dea2](https://linux-hardware.org/?probe=423b15dea2) | Feb 09, 2024 |
| Acer          | Aspire 6530G                | Notebook    | [a52bd02af6](https://linux-hardware.org/?probe=a52bd02af6) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [34d8638e1b](https://linux-hardware.org/?probe=34d8638e1b) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [0d70b31ec1](https://linux-hardware.org/?probe=0d70b31ec1) | Feb 08, 2024 |
| Gigabyte      | AORUS 17H BXF               | Notebook    | [4146726cc9](https://linux-hardware.org/?probe=4146726cc9) | Feb 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [661b2efa7b](https://linux-hardware.org/?probe=661b2efa7b) | Feb 08, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [33988a8ce4](https://linux-hardware.org/?probe=33988a8ce4) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [e3a70ea869](https://linux-hardware.org/?probe=e3a70ea869) | Feb 07, 2024 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [f7a3dcea60](https://linux-hardware.org/?probe=f7a3dcea60) | Feb 07, 2024 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [b38c4f6d04](https://linux-hardware.org/?probe=b38c4f6d04) | Feb 07, 2024 |
| System76      | Pangolin                    | Notebook    | [c5d7319f7c](https://linux-hardware.org/?probe=c5d7319f7c) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [18bb015935](https://linux-hardware.org/?probe=18bb015935) | Feb 07, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [692854bb38](https://linux-hardware.org/?probe=692854bb38) | Feb 07, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [4c44ba2081](https://linux-hardware.org/?probe=4c44ba2081) | Feb 07, 2024 |
| Acer          | Aspire XC-603G              | Desktop     | [f4bc1814e8](https://linux-hardware.org/?probe=f4bc1814e8) | Feb 06, 2024 |
| Lenovo        | ThinkPad P50 20EQS2GL00     | Notebook    | [ebd3065955](https://linux-hardware.org/?probe=ebd3065955) | Feb 06, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [0e9a586cf0](https://linux-hardware.org/?probe=0e9a586cf0) | Feb 06, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [a820fbd52d](https://linux-hardware.org/?probe=a820fbd52d) | Feb 06, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [0d44d5cc60](https://linux-hardware.org/?probe=0d44d5cc60) | Feb 06, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [5f19079461](https://linux-hardware.org/?probe=5f19079461) | Feb 06, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0f58d5d24e](https://linux-hardware.org/?probe=0f58d5d24e) | Feb 06, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [e90f84656d](https://linux-hardware.org/?probe=e90f84656d) | Feb 06, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [965e14a38d](https://linux-hardware.org/?probe=965e14a38d) | Feb 06, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [0f0883d52e](https://linux-hardware.org/?probe=0f0883d52e) | Feb 06, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [bfccd0df6e](https://linux-hardware.org/?probe=bfccd0df6e) | Feb 06, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [50d7951466](https://linux-hardware.org/?probe=50d7951466) | Feb 05, 2024 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [8700336241](https://linux-hardware.org/?probe=8700336241) | Feb 05, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [a688c4fc6e](https://linux-hardware.org/?probe=a688c4fc6e) | Feb 05, 2024 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [6565663228](https://linux-hardware.org/?probe=6565663228) | Feb 05, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [ca4e5e8f49](https://linux-hardware.org/?probe=ca4e5e8f49) | Feb 05, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [708ee3c7ac](https://linux-hardware.org/?probe=708ee3c7ac) | Feb 05, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [ddb4c7f91a](https://linux-hardware.org/?probe=ddb4c7f91a) | Feb 05, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d83dd7b361](https://linux-hardware.org/?probe=d83dd7b361) | Feb 05, 2024 |
| Dell          | Precision 7710              | Notebook    | [93bdd1915c](https://linux-hardware.org/?probe=93bdd1915c) | Feb 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [34e9a5b730](https://linux-hardware.org/?probe=34e9a5b730) | Feb 04, 2024 |
| Lenovo        | 31900058 STD                | All in one  | [a459170172](https://linux-hardware.org/?probe=a459170172) | Feb 04, 2024 |
| System76      | Galago Pro                  | Notebook    | [a6e796d4a9](https://linux-hardware.org/?probe=a6e796d4a9) | Feb 04, 2024 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [c2ee1a3fc6](https://linux-hardware.org/?probe=c2ee1a3fc6) | Feb 04, 2024 |
| Dell          | 0C522T A03                  | Desktop     | [8a0946f2b4](https://linux-hardware.org/?probe=8a0946f2b4) | Feb 04, 2024 |
| Dell          | XPS 9320                    | Notebook    | [74d4b364f8](https://linux-hardware.org/?probe=74d4b364f8) | Feb 03, 2024 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [d28656e6f3](https://linux-hardware.org/?probe=d28656e6f3) | Feb 03, 2024 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [eb7d7aa84f](https://linux-hardware.org/?probe=eb7d7aa84f) | Feb 03, 2024 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [7f1b60be2a](https://linux-hardware.org/?probe=7f1b60be2a) | Feb 03, 2024 |
| Gigabyte      | H55M-S2H                    | Desktop     | [e5a8865f78](https://linux-hardware.org/?probe=e5a8865f78) | Feb 03, 2024 |
| Dell          | Precision 3550              | Notebook    | [780747a577](https://linux-hardware.org/?probe=780747a577) | Feb 03, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [b3a0560548](https://linux-hardware.org/?probe=b3a0560548) | Feb 03, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [67951a8bdd](https://linux-hardware.org/?probe=67951a8bdd) | Feb 03, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [15a025fa0c](https://linux-hardware.org/?probe=15a025fa0c) | Feb 03, 2024 |
| HP            | ZBook 15 G4                 | Notebook    | [72ea56fdbe](https://linux-hardware.org/?probe=72ea56fdbe) | Feb 03, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2b98b922fe](https://linux-hardware.org/?probe=2b98b922fe) | Feb 03, 2024 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [671c2add93](https://linux-hardware.org/?probe=671c2add93) | Feb 03, 2024 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [2994236383](https://linux-hardware.org/?probe=2994236383) | Feb 03, 2024 |
| ASUSTek       | M4N72-E                     | Desktop     | [815b251540](https://linux-hardware.org/?probe=815b251540) | Feb 02, 2024 |
| HP            | Pavilion g6                 | Notebook    | [795109303b](https://linux-hardware.org/?probe=795109303b) | Feb 02, 2024 |
| Dell          | G7 7588                     | Notebook    | [fdc746ce61](https://linux-hardware.org/?probe=fdc746ce61) | Feb 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [6d6e6af46b](https://linux-hardware.org/?probe=6d6e6af46b) | Feb 02, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [77c29c5fe1](https://linux-hardware.org/?probe=77c29c5fe1) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f659cc07fc](https://linux-hardware.org/?probe=f659cc07fc) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [bb6dd71048](https://linux-hardware.org/?probe=bb6dd71048) | Feb 01, 2024 |
| HP            | Elite x2 1013 G3            | Tablet      | [bdf4429b2f](https://linux-hardware.org/?probe=bdf4429b2f) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7adc6ac4b3](https://linux-hardware.org/?probe=7adc6ac4b3) | Feb 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e94976b6d9](https://linux-hardware.org/?probe=e94976b6d9) | Feb 01, 2024 |
| Samsung       | 750XFH                      | Notebook    | [47d573ccf5](https://linux-hardware.org/?probe=47d573ccf5) | Feb 01, 2024 |
| Dell          | 0V8WGR A00                  | Desktop     | [9762a633ab](https://linux-hardware.org/?probe=9762a633ab) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [4e6e527f34](https://linux-hardware.org/?probe=4e6e527f34) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [16a348ccd1](https://linux-hardware.org/?probe=16a348ccd1) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [fc52040fc1](https://linux-hardware.org/?probe=fc52040fc1) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f833c48d57](https://linux-hardware.org/?probe=f833c48d57) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [bc7890c0fe](https://linux-hardware.org/?probe=bc7890c0fe) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ef62bb8257](https://linux-hardware.org/?probe=ef62bb8257) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [a5425cfc63](https://linux-hardware.org/?probe=a5425cfc63) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [67539ba367](https://linux-hardware.org/?probe=67539ba367) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [841cef0b98](https://linux-hardware.org/?probe=841cef0b98) | Feb 01, 2024 |
| HP            | Pavilion dv6                | Notebook    | [9d58677c2a](https://linux-hardware.org/?probe=9d58677c2a) | Feb 01, 2024 |
| ASUSTek       | X556UQK                     | Notebook    | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [54beeb17dc](https://linux-hardware.org/?probe=54beeb17dc) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [65272ffc77](https://linux-hardware.org/?probe=65272ffc77) | Jan 31, 2024 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [5dcee96cdb](https://linux-hardware.org/?probe=5dcee96cdb) | Jan 31, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5222452ba4](https://linux-hardware.org/?probe=5222452ba4) | Jan 30, 2024 |
| Hot Pepper... | HPPMC10                     | Notebook    | [1bfdadd09f](https://linux-hardware.org/?probe=1bfdadd09f) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [454433be44](https://linux-hardware.org/?probe=454433be44) | Jan 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0b6e8d1e4b](https://linux-hardware.org/?probe=0b6e8d1e4b) | Jan 30, 2024 |
| Apple         | MacBook9,1                  | Notebook    | [e81979cbdf](https://linux-hardware.org/?probe=e81979cbdf) | Jan 29, 2024 |
| Alienware     | 07HV66 A01                  | Desktop     | [732d349380](https://linux-hardware.org/?probe=732d349380) | Jan 29, 2024 |
| HP            | ProBook 4540s               | Notebook    | [ba6e31a8d3](https://linux-hardware.org/?probe=ba6e31a8d3) | Jan 29, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [dda1c0dfa9](https://linux-hardware.org/?probe=dda1c0dfa9) | Jan 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0bba02c4c8](https://linux-hardware.org/?probe=0bba02c4c8) | Jan 29, 2024 |
| SZMZ          | X99-S3                      | Desktop     | [acf24ed760](https://linux-hardware.org/?probe=acf24ed760) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [9fcbf2b096](https://linux-hardware.org/?probe=9fcbf2b096) | Jan 29, 2024 |
| MSI           | MS-B0961                    | All in one  | [5c66f68a0e](https://linux-hardware.org/?probe=5c66f68a0e) | Jan 29, 2024 |
| MSI           | MS-B0961                    | All in one  | [231209ac00](https://linux-hardware.org/?probe=231209ac00) | Jan 29, 2024 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [7eaf280c7a](https://linux-hardware.org/?probe=7eaf280c7a) | Jan 29, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4e6d22c388](https://linux-hardware.org/?probe=4e6d22c388) | Jan 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a7826ae1af](https://linux-hardware.org/?probe=a7826ae1af) | Jan 28, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f80e16d62d](https://linux-hardware.org/?probe=f80e16d62d) | Jan 28, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [c347f95f5e](https://linux-hardware.org/?probe=c347f95f5e) | Jan 28, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [14f153b6c9](https://linux-hardware.org/?probe=14f153b6c9) | Jan 28, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [d5f5ab4b3f](https://linux-hardware.org/?probe=d5f5ab4b3f) | Jan 27, 2024 |
| ASUSTek       | Z170-A                      | Desktop     | [0f1f062eda](https://linux-hardware.org/?probe=0f1f062eda) | Jan 27, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [077619fc48](https://linux-hardware.org/?probe=077619fc48) | Jan 27, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [f0ac1844ad](https://linux-hardware.org/?probe=f0ac1844ad) | Jan 27, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b1d979bcb3](https://linux-hardware.org/?probe=b1d979bcb3) | Jan 27, 2024 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [94257ca4de](https://linux-hardware.org/?probe=94257ca4de) | Jan 27, 2024 |
| Acer          | Aspire 6530G                | Notebook    | [cd71356945](https://linux-hardware.org/?probe=cd71356945) | Jan 26, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [91412d213a](https://linux-hardware.org/?probe=91412d213a) | Jan 26, 2024 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [1eb12a361c](https://linux-hardware.org/?probe=1eb12a361c) | Jan 26, 2024 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [1f2bb560a8](https://linux-hardware.org/?probe=1f2bb560a8) | Jan 26, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [afbea953be](https://linux-hardware.org/?probe=afbea953be) | Jan 26, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [43bf0c55e8](https://linux-hardware.org/?probe=43bf0c55e8) | Jan 26, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [068df25275](https://linux-hardware.org/?probe=068df25275) | Jan 26, 2024 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [5be9da4fbd](https://linux-hardware.org/?probe=5be9da4fbd) | Jan 26, 2024 |
| Lenovo        | G460 0677                   | Notebook    | [d4624cb524](https://linux-hardware.org/?probe=d4624cb524) | Jan 26, 2024 |
| Huanan        | X99-8M-F V1.4               | Desktop     | [65388b76e1](https://linux-hardware.org/?probe=65388b76e1) | Jan 25, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [4b9ba374ee](https://linux-hardware.org/?probe=4b9ba374ee) | Jan 25, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [4cedf6ee3a](https://linux-hardware.org/?probe=4cedf6ee3a) | Jan 25, 2024 |
| Acer          | Aspire VX5-591G             | Notebook    | [3e5671c66a](https://linux-hardware.org/?probe=3e5671c66a) | Jan 24, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [863ad9098e](https://linux-hardware.org/?probe=863ad9098e) | Jan 24, 2024 |
| Gigabyte      | X99-Gaming 5P               | Desktop     | [e306ef8710](https://linux-hardware.org/?probe=e306ef8710) | Jan 24, 2024 |
| HP            | ProBook 4530s               | Notebook    | [db169567f6](https://linux-hardware.org/?probe=db169567f6) | Jan 24, 2024 |
| Toshiba       | Satellite C55-C             | Notebook    | [3f59e64e0e](https://linux-hardware.org/?probe=3f59e64e0e) | Jan 24, 2024 |
| System76      | Oryx Pro                    | Notebook    | [cb490beb63](https://linux-hardware.org/?probe=cb490beb63) | Jan 24, 2024 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [8b3e1a6d31](https://linux-hardware.org/?probe=8b3e1a6d31) | Jan 24, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | Desktop     | [340fdb1832](https://linux-hardware.org/?probe=340fdb1832) | Jan 24, 2024 |
| MSI           | H55M-E33                    | Desktop     | [2935476b48](https://linux-hardware.org/?probe=2935476b48) | Jan 23, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [d195c1f908](https://linux-hardware.org/?probe=d195c1f908) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [5d754d0510](https://linux-hardware.org/?probe=5d754d0510) | Jan 23, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [2f77e5be01](https://linux-hardware.org/?probe=2f77e5be01) | Jan 22, 2024 |
| MSI           | B350M MORTAR                | Desktop     | [f728e7ad76](https://linux-hardware.org/?probe=f728e7ad76) | Jan 22, 2024 |
| Dell          | Inspiron 5490               | Notebook    | [e879f5dd00](https://linux-hardware.org/?probe=e879f5dd00) | Jan 22, 2024 |
| MOMENTPLUS    | MP90                        | Mini pc     | [44e57438d0](https://linux-hardware.org/?probe=44e57438d0) | Jan 22, 2024 |
| MOMENTPLUS    | MP90                        | Mini pc     | [fee086244e](https://linux-hardware.org/?probe=fee086244e) | Jan 22, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [5ac29b012d](https://linux-hardware.org/?probe=5ac29b012d) | Jan 22, 2024 |
| MOMENTPLUS    | MP90                        | Mini pc     | [35ef2ea38e](https://linux-hardware.org/?probe=35ef2ea38e) | Jan 22, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [ed9635f427](https://linux-hardware.org/?probe=ed9635f427) | Jan 22, 2024 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [dcb0ce6ffa](https://linux-hardware.org/?probe=dcb0ce6ffa) | Jan 22, 2024 |
| HP            | Notebook                    | Notebook    | [efbf2736f3](https://linux-hardware.org/?probe=efbf2736f3) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d248b6e5a9](https://linux-hardware.org/?probe=d248b6e5a9) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [66cf4b0b5a](https://linux-hardware.org/?probe=66cf4b0b5a) | Jan 21, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [41a62ec1d4](https://linux-hardware.org/?probe=41a62ec1d4) | Jan 21, 2024 |
| Gigabyte      | B660 AORUS MASTER DDR4      | Desktop     | [d36c2b07fd](https://linux-hardware.org/?probe=d36c2b07fd) | Jan 20, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [a0637d4400](https://linux-hardware.org/?probe=a0637d4400) | Jan 20, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f41b6b7f9](https://linux-hardware.org/?probe=8f41b6b7f9) | Jan 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [af503dbdd1](https://linux-hardware.org/?probe=af503dbdd1) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [9fd92c9632](https://linux-hardware.org/?probe=9fd92c9632) | Jan 20, 2024 |
| ASUSTek       | H97M-E                      | Desktop     | [d6fe598f33](https://linux-hardware.org/?probe=d6fe598f33) | Jan 20, 2024 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [14acfc6be1](https://linux-hardware.org/?probe=14acfc6be1) | Jan 19, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [e9423fb2cd](https://linux-hardware.org/?probe=e9423fb2cd) | Jan 19, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [09fe6e6426](https://linux-hardware.org/?probe=09fe6e6426) | Jan 19, 2024 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [7e5eb5a38c](https://linux-hardware.org/?probe=7e5eb5a38c) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [35c8f1855d](https://linux-hardware.org/?probe=35c8f1855d) | Jan 19, 2024 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e5d9f41477](https://linux-hardware.org/?probe=e5d9f41477) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e555a2c32c](https://linux-hardware.org/?probe=e555a2c32c) | Jan 19, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| ASUSTek       | N55SL                       | Notebook    | [a6c913a5e2](https://linux-hardware.org/?probe=a6c913a5e2) | Jan 19, 2024 |
| Dell          | Latitude 9420               | Convertible | [66e5db6523](https://linux-hardware.org/?probe=66e5db6523) | Jan 18, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [06cced7a39](https://linux-hardware.org/?probe=06cced7a39) | Jan 18, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [8f90ab1bfb](https://linux-hardware.org/?probe=8f90ab1bfb) | Jan 18, 2024 |
| ASRock        | H670 PG Riptide             | Desktop     | [d1a75ad00a](https://linux-hardware.org/?probe=d1a75ad00a) | Jan 18, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [97b9d61c1b](https://linux-hardware.org/?probe=97b9d61c1b) | Jan 18, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [3da744b1f4](https://linux-hardware.org/?probe=3da744b1f4) | Jan 18, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [612d6f9b0e](https://linux-hardware.org/?probe=612d6f9b0e) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [048d450a50](https://linux-hardware.org/?probe=048d450a50) | Jan 17, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [42e7298c19](https://linux-hardware.org/?probe=42e7298c19) | Jan 17, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [3b62b0b588](https://linux-hardware.org/?probe=3b62b0b588) | Jan 17, 2024 |
| Dell          | Latitude 9420               | Convertible | [cb8166fe94](https://linux-hardware.org/?probe=cb8166fe94) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [1364b82d7c](https://linux-hardware.org/?probe=1364b82d7c) | Jan 17, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [0b16d083fa](https://linux-hardware.org/?probe=0b16d083fa) | Jan 17, 2024 |
| ASRock        | FM2A68M-HD+                 | Notebook    | [8ba2ab423f](https://linux-hardware.org/?probe=8ba2ab423f) | Jan 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [dd442d6fef](https://linux-hardware.org/?probe=dd442d6fef) | Jan 17, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a5bd71f259](https://linux-hardware.org/?probe=a5bd71f259) | Jan 17, 2024 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [3cdf937732](https://linux-hardware.org/?probe=3cdf937732) | Jan 17, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [48399b3fc4](https://linux-hardware.org/?probe=48399b3fc4) | Jan 16, 2024 |
| Compaq        | 430                         | Notebook    | [a8dc50fedd](https://linux-hardware.org/?probe=a8dc50fedd) | Jan 16, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [be6d425c5a](https://linux-hardware.org/?probe=be6d425c5a) | Jan 16, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [58d64e6a70](https://linux-hardware.org/?probe=58d64e6a70) | Jan 16, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [adb9343764](https://linux-hardware.org/?probe=adb9343764) | Jan 16, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cb4fc4f2da](https://linux-hardware.org/?probe=cb4fc4f2da) | Jan 16, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8e26115f48](https://linux-hardware.org/?probe=8e26115f48) | Jan 16, 2024 |
| MSI           | Z68A-G43                    | Desktop     | [9ab9ae7952](https://linux-hardware.org/?probe=9ab9ae7952) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d124634554](https://linux-hardware.org/?probe=d124634554) | Jan 15, 2024 |
| Acer          | Swift SF315-52G             | Notebook    | [b1df864ab5](https://linux-hardware.org/?probe=b1df864ab5) | Jan 15, 2024 |
| ASUSTek       | X550JK                      | Notebook    | [1e70a82b32](https://linux-hardware.org/?probe=1e70a82b32) | Jan 15, 2024 |
| System76      | Pangolin                    | Notebook    | [bb8766a339](https://linux-hardware.org/?probe=bb8766a339) | Jan 15, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [75e74c82af](https://linux-hardware.org/?probe=75e74c82af) | Jan 15, 2024 |
| Dell          | 0J8H4R A00                  | Desktop     | [ce34102531](https://linux-hardware.org/?probe=ce34102531) | Jan 15, 2024 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e77609cb6](https://linux-hardware.org/?probe=8e77609cb6) | Jan 14, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [fe987e391e](https://linux-hardware.org/?probe=fe987e391e) | Jan 14, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6ede7a7cc8](https://linux-hardware.org/?probe=6ede7a7cc8) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [19467f2a4d](https://linux-hardware.org/?probe=19467f2a4d) | Jan 14, 2024 |
| Acer          | Aspire 5560                 | Notebook    | [fcc49083ec](https://linux-hardware.org/?probe=fcc49083ec) | Jan 14, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [08074470dd](https://linux-hardware.org/?probe=08074470dd) | Jan 13, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1b6a4a4985](https://linux-hardware.org/?probe=1b6a4a4985) | Jan 13, 2024 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [f1b5487574](https://linux-hardware.org/?probe=f1b5487574) | Jan 13, 2024 |
| Samsung       | 550XED                      | Notebook    | [a9cdc1201c](https://linux-hardware.org/?probe=a9cdc1201c) | Jan 13, 2024 |
| Gigabyte      | H610M H DDR4                | Desktop     | [7ad8786f92](https://linux-hardware.org/?probe=7ad8786f92) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [60f88b1f3f](https://linux-hardware.org/?probe=60f88b1f3f) | Jan 13, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [3d70c9ce2f](https://linux-hardware.org/?probe=3d70c9ce2f) | Jan 13, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [dbcc44707c](https://linux-hardware.org/?probe=dbcc44707c) | Jan 13, 2024 |
| Dell          | Inspiron 5447               | Notebook    | [12ec54ffaf](https://linux-hardware.org/?probe=12ec54ffaf) | Jan 12, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [e5e36f25f0](https://linux-hardware.org/?probe=e5e36f25f0) | Jan 12, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [50ff1c2eb6](https://linux-hardware.org/?probe=50ff1c2eb6) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [5ff6a8a29a](https://linux-hardware.org/?probe=5ff6a8a29a) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [ea8bf22b21](https://linux-hardware.org/?probe=ea8bf22b21) | Jan 12, 2024 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [b9fe694efb](https://linux-hardware.org/?probe=b9fe694efb) | Jan 12, 2024 |
| Lenovo        | ThinkPad X260 20F5S4A901    | Notebook    | [75e671c163](https://linux-hardware.org/?probe=75e671c163) | Jan 12, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8b5a2519fa](https://linux-hardware.org/?probe=8b5a2519fa) | Jan 12, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6ac65457ae](https://linux-hardware.org/?probe=6ac65457ae) | Jan 11, 2024 |
| System76      | Adder WS                    | Notebook    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | Notebook    | [9066b38bfc](https://linux-hardware.org/?probe=9066b38bfc) | Jan 11, 2024 |
| Acer          | Swift SF314-54              | Notebook    | [c947abcab4](https://linux-hardware.org/?probe=c947abcab4) | Jan 11, 2024 |
| ASUSTek       | G73Jh                       | Notebook    | [9f34698cbf](https://linux-hardware.org/?probe=9f34698cbf) | Jan 11, 2024 |
| Dell          | Latitude E7240              | Notebook    | [5661525290](https://linux-hardware.org/?probe=5661525290) | Jan 11, 2024 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [5e75e6b11a](https://linux-hardware.org/?probe=5e75e6b11a) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6462a9e611](https://linux-hardware.org/?probe=6462a9e611) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [145f213442](https://linux-hardware.org/?probe=145f213442) | Jan 10, 2024 |
| ASUSTek       | N55SL                       | Notebook    | [b2c935edc3](https://linux-hardware.org/?probe=b2c935edc3) | Jan 10, 2024 |
| ASUSTek       | X550JK                      | Notebook    | [53f8040dbd](https://linux-hardware.org/?probe=53f8040dbd) | Jan 10, 2024 |
| Dell          | Precision 7510              | Notebook    | [8902e4fb7f](https://linux-hardware.org/?probe=8902e4fb7f) | Jan 10, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [4ec27cc26b](https://linux-hardware.org/?probe=4ec27cc26b) | Jan 10, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3002... | Notebook    | [374798f039](https://linux-hardware.org/?probe=374798f039) | Jan 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [76fb94009e](https://linux-hardware.org/?probe=76fb94009e) | Jan 09, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [b85af627bb](https://linux-hardware.org/?probe=b85af627bb) | Jan 09, 2024 |
| Dell          | Precision 5480              | Notebook    | [17ef519eb9](https://linux-hardware.org/?probe=17ef519eb9) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8107ad3adc](https://linux-hardware.org/?probe=8107ad3adc) | Jan 09, 2024 |
| Gigabyte      | H610M S2H                   | Desktop     | [c2a2c8a049](https://linux-hardware.org/?probe=c2a2c8a049) | Jan 09, 2024 |
| Gigabyte      | H610M S2H                   | Desktop     | [8a7432cd09](https://linux-hardware.org/?probe=8a7432cd09) | Jan 09, 2024 |
| Dell          | Precision 5560              | Notebook    | [947f10a53a](https://linux-hardware.org/?probe=947f10a53a) | Jan 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [50ff3c4620](https://linux-hardware.org/?probe=50ff3c4620) | Jan 08, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [22a09bce1a](https://linux-hardware.org/?probe=22a09bce1a) | Jan 08, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [a0e28b82f1](https://linux-hardware.org/?probe=a0e28b82f1) | Jan 08, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [33a2ceb954](https://linux-hardware.org/?probe=33a2ceb954) | Jan 08, 2024 |
| HP            | 8434 11                     | Desktop     | [3c7307cadb](https://linux-hardware.org/?probe=3c7307cadb) | Jan 08, 2024 |
| Dell          | Vostro 5402                 | Notebook    | [4c1d546ae0](https://linux-hardware.org/?probe=4c1d546ae0) | Jan 08, 2024 |
| Lenovo        | ThinkPad X220 4291RD2       | Notebook    | [dc1b40ea6f](https://linux-hardware.org/?probe=dc1b40ea6f) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [f63753ff07](https://linux-hardware.org/?probe=f63753ff07) | Jan 08, 2024 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | Notebook    | [2068373a62](https://linux-hardware.org/?probe=2068373a62) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [29104c358b](https://linux-hardware.org/?probe=29104c358b) | Jan 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [040fa6a049](https://linux-hardware.org/?probe=040fa6a049) | Jan 07, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [605ea399c5](https://linux-hardware.org/?probe=605ea399c5) | Jan 07, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [cdc7802fc3](https://linux-hardware.org/?probe=cdc7802fc3) | Jan 07, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [46148b3b7a](https://linux-hardware.org/?probe=46148b3b7a) | Jan 07, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [8363cb44ef](https://linux-hardware.org/?probe=8363cb44ef) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [fcf858ac50](https://linux-hardware.org/?probe=fcf858ac50) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [a10fc58132](https://linux-hardware.org/?probe=a10fc58132) | Jan 06, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [8ca8b318eb](https://linux-hardware.org/?probe=8ca8b318eb) | Jan 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [8f7440e4aa](https://linux-hardware.org/?probe=8f7440e4aa) | Jan 06, 2024 |
| Lenovo        | ThinkPad X390 20Q1S7RB00    | Notebook    | [cfcb27d0b7](https://linux-hardware.org/?probe=cfcb27d0b7) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ae18260ba9](https://linux-hardware.org/?probe=ae18260ba9) | Jan 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [b247cc09d2](https://linux-hardware.org/?probe=b247cc09d2) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [cae755fe43](https://linux-hardware.org/?probe=cae755fe43) | Jan 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [a620a3be8d](https://linux-hardware.org/?probe=a620a3be8d) | Jan 06, 2024 |
| Dell          | Latitude 3420               | Notebook    | [39d522ead5](https://linux-hardware.org/?probe=39d522ead5) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [d135277737](https://linux-hardware.org/?probe=d135277737) | Jan 05, 2024 |
| HP            | 83E9                        | Notebook    | [5794eaa509](https://linux-hardware.org/?probe=5794eaa509) | Jan 05, 2024 |
| HP            | 83E9                        | Notebook    | [ca6565530d](https://linux-hardware.org/?probe=ca6565530d) | Jan 05, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [0fd8636acb](https://linux-hardware.org/?probe=0fd8636acb) | Jan 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [5e7209bd1a](https://linux-hardware.org/?probe=5e7209bd1a) | Jan 05, 2024 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [204ff304cf](https://linux-hardware.org/?probe=204ff304cf) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [18ebf2cf02](https://linux-hardware.org/?probe=18ebf2cf02) | Jan 04, 2024 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [ef860dc55b](https://linux-hardware.org/?probe=ef860dc55b) | Jan 04, 2024 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [2eb9de52ab](https://linux-hardware.org/?probe=2eb9de52ab) | Jan 04, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1c7845bdee](https://linux-hardware.org/?probe=1c7845bdee) | Jan 04, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [4c587bc867](https://linux-hardware.org/?probe=4c587bc867) | Jan 04, 2024 |
| ASUSTek       | Z87-K                       | Desktop     | [4bd9034918](https://linux-hardware.org/?probe=4bd9034918) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1973735eec](https://linux-hardware.org/?probe=1973735eec) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [1593858ec2](https://linux-hardware.org/?probe=1593858ec2) | Jan 04, 2024 |
| Dell          | Latitude E5270              | Notebook    | [c0a4dbd80f](https://linux-hardware.org/?probe=c0a4dbd80f) | Jan 03, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [70cf9e639e](https://linux-hardware.org/?probe=70cf9e639e) | Jan 03, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [0e5397d3f1](https://linux-hardware.org/?probe=0e5397d3f1) | Jan 03, 2024 |
| Microsoft     | Surface Go 3                | Tablet      | [1531aba226](https://linux-hardware.org/?probe=1531aba226) | Jan 03, 2024 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [cd96de915f](https://linux-hardware.org/?probe=cd96de915f) | Jan 03, 2024 |
| Acidanther... | Mac-F221DCC8                | All in one  | [3cd35cddda](https://linux-hardware.org/?probe=3cd35cddda) | Jan 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [d29c58fd8a](https://linux-hardware.org/?probe=d29c58fd8a) | Jan 03, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [95995dd66f](https://linux-hardware.org/?probe=95995dd66f) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [8fe843e69b](https://linux-hardware.org/?probe=8fe843e69b) | Jan 02, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8bb04983f7](https://linux-hardware.org/?probe=8bb04983f7) | Jan 02, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [e80580f306](https://linux-hardware.org/?probe=e80580f306) | Jan 02, 2024 |
| ASUSTek       | Z87-K                       | Desktop     | [3f1ffd98e9](https://linux-hardware.org/?probe=3f1ffd98e9) | Jan 02, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [09d807a864](https://linux-hardware.org/?probe=09d807a864) | Jan 02, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [b74d7acff4](https://linux-hardware.org/?probe=b74d7acff4) | Jan 02, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [7f8494ffcf](https://linux-hardware.org/?probe=7f8494ffcf) | Jan 02, 2024 |
| Dell          | Latitude 5540               | Notebook    | [96e1aad010](https://linux-hardware.org/?probe=96e1aad010) | Jan 02, 2024 |
| System76      | Oryx Pro                    | Notebook    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Unknown       | X99H                        | Desktop     | [61c57cb006](https://linux-hardware.org/?probe=61c57cb006) | Jan 01, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| ASUSTek       | P6T                         | Desktop     | [7b5a14566d](https://linux-hardware.org/?probe=7b5a14566d) | Jan 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [58557ae7c7](https://linux-hardware.org/?probe=58557ae7c7) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [eb47ce9900](https://linux-hardware.org/?probe=eb47ce9900) | Jan 01, 2024 |
| ASUSTek       | M4N72-E                     | Desktop     | [7d21517ee3](https://linux-hardware.org/?probe=7d21517ee3) | Dec 31, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa478c5226](https://linux-hardware.org/?probe=fa478c5226) | Dec 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | Notebook    | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| Google        | Delbin                      | Notebook    | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [63fd2a4477](https://linux-hardware.org/?probe=63fd2a4477) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [faf34bf75f](https://linux-hardware.org/?probe=faf34bf75f) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | Notebook    | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b1b1057a4b](https://linux-hardware.org/?probe=b1b1057a4b) | Dec 30, 2023 |
| Acer          | SF314-71-50E8               | Notebook    | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| HP            | 802E                        | Desktop     | [a519d89c9e](https://linux-hardware.org/?probe=a519d89c9e) | Dec 29, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [e0e92720cb](https://linux-hardware.org/?probe=e0e92720cb) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | Notebook    | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | Notebook    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94b90795bb](https://linux-hardware.org/?probe=94b90795bb) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2d2449e5d7](https://linux-hardware.org/?probe=2d2449e5d7) | Dec 28, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [f52a281bd2](https://linux-hardware.org/?probe=f52a281bd2) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [42460d0cd3](https://linux-hardware.org/?probe=42460d0cd3) | Dec 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [61116b6285](https://linux-hardware.org/?probe=61116b6285) | Dec 27, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [0927068d89](https://linux-hardware.org/?probe=0927068d89) | Dec 27, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [77d5e43585](https://linux-hardware.org/?probe=77d5e43585) | Dec 26, 2023 |
| SZMZ          | X99-S3                      | Desktop     | [85c9abf0f3](https://linux-hardware.org/?probe=85c9abf0f3) | Dec 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [e63c96ff95](https://linux-hardware.org/?probe=e63c96ff95) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [96aa7493e0](https://linux-hardware.org/?probe=96aa7493e0) | Dec 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [634e14ff4c](https://linux-hardware.org/?probe=634e14ff4c) | Dec 25, 2023 |
| MicroByte     | ezbook                      | Notebook    | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [325376d316](https://linux-hardware.org/?probe=325376d316) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | Notebook    | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| PC Special... | N150CU                      | Notebook    | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f9cf1edcee](https://linux-hardware.org/?probe=f9cf1edcee) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | Notebook    | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8decde512f](https://linux-hardware.org/?probe=8decde512f) | Dec 23, 2023 |
| System76      | Serval WS                   | Notebook    | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | Notebook    | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [de502eec48](https://linux-hardware.org/?probe=de502eec48) | Dec 22, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [ec6847b7f2](https://linux-hardware.org/?probe=ec6847b7f2) | Dec 22, 2023 |
| Gigabyte      | H610M S2H                   | Desktop     | [6c554a9668](https://linux-hardware.org/?probe=6c554a9668) | Dec 22, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [bf0861748d](https://linux-hardware.org/?probe=bf0861748d) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1b8100314e](https://linux-hardware.org/?probe=1b8100314e) | Dec 21, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ecefa48588](https://linux-hardware.org/?probe=ecefa48588) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | Notebook    | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [67098aebca](https://linux-hardware.org/?probe=67098aebca) | Dec 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9a3cef62bc](https://linux-hardware.org/?probe=9a3cef62bc) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [d2ed93003e](https://linux-hardware.org/?probe=d2ed93003e) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | Notebook    | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | Notebook    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [86b686b3cf](https://linux-hardware.org/?probe=86b686b3cf) | Dec 19, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [047feb8e76](https://linux-hardware.org/?probe=047feb8e76) | Dec 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [9ec714a02b](https://linux-hardware.org/?probe=9ec714a02b) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [29169b6700](https://linux-hardware.org/?probe=29169b6700) | Dec 19, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1375b869d1](https://linux-hardware.org/?probe=1375b869d1) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [0759f6c04f](https://linux-hardware.org/?probe=0759f6c04f) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [939c3a4be6](https://linux-hardware.org/?probe=939c3a4be6) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [8efe53adcb](https://linux-hardware.org/?probe=8efe53adcb) | Dec 18, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f051e1ba58](https://linux-hardware.org/?probe=f051e1ba58) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [85358f7505](https://linux-hardware.org/?probe=85358f7505) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [2d78f7257c](https://linux-hardware.org/?probe=2d78f7257c) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 4448      | 39.61%  |
| Pop!_OS 20.04 | 2134      | 19%     |
| Pop!_OS 21.04 | 1805      | 16.07%  |
| Pop!_OS 20.10 | 1653      | 14.72%  |
| Pop!_OS 21.10 | 1114      | 9.92%   |
| Pop!_OS 19.10 | 47        | 0.42%   |
| Pop!_OS 19.04 | 12        | 0.11%   |
| Pop!_OS 18.04 | 11        | 0.1%    |
| Pop!_OS 18.10 | 5         | 0.04%   |
| Pop!_OS 24.04 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 10685     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.11.0-7620-generic                 | 838       | 6.85%   |
| 6.2.6-76060206-generic              | 835       | 6.82%   |
| 5.8.0-7630-generic                  | 739       | 6.04%   |
| 5.4.0-7634-generic                  | 667       | 5.45%   |
| 5.13.0-7614-generic                 | 497       | 4.06%   |
| 5.8.0-7642-generic                  | 484       | 3.96%   |
| 6.0.12-76060006-generic             | 480       | 3.92%   |
| 5.4.0-7642-generic                  | 465       | 3.8%    |
| 5.17.5-76051705-generic             | 464       | 3.79%   |
| 5.19.0-76051900-generic             | 449       | 3.67%   |
| 5.11.0-7614-generic                 | 442       | 3.61%   |
| 5.13.0-7620-generic                 | 411       | 3.36%   |
| 6.6.10-76060610-generic             | 317       | 2.59%   |
| 6.5.6-76060506-generic              | 309       | 2.53%   |
| 6.0.6-76060006-generic              | 302       | 2.47%   |
| 6.4.6-76060406-generic              | 299       | 2.44%   |
| 5.15.15-76051515-generic            | 280       | 2.29%   |
| 5.16.11-76051611-generic            | 264       | 2.16%   |
| 5.15.5-76051505-generic             | 238       | 1.94%   |
| 6.6.6-76060606-generic              | 233       | 1.9%    |
| 5.11.0-7612-generic                 | 224       | 1.83%   |
| 5.18.10-76051810-generic            | 214       | 1.75%   |
| 5.8.0-7625-generic                  | 197       | 1.61%   |
| 6.8.0-76060800daily20240311-generic | 196       | 1.6%    |
| 5.17.15-76051715-generic            | 190       | 1.55%   |
| 5.16.19-76051619-generic            | 180       | 1.47%   |
| 5.11.0-7633-generic                 | 179       | 1.46%   |
| 5.15.8-76051508-generic             | 169       | 1.38%   |
| 5.16.15-76051615-generic            | 151       | 1.23%   |
| 5.4.0-7626-generic                  | 144       | 1.18%   |
| 6.5.4-76060504-generic              | 132       | 1.08%   |
| 6.2.0-76060200-generic              | 123       | 1.01%   |
| 5.15.11-76051511-generic            | 117       | 0.96%   |
| 6.1.11-76060111-generic             | 91        | 0.74%   |
| 6.0.2-76060002-generic              | 91        | 0.74%   |
| 5.15.23-76051523-generic            | 91        | 0.74%   |
| 5.4.0-7625-generic                  | 74        | 0.6%    |
| 5.4.0-7629-generic                  | 62        | 0.51%   |
| 5.19.16-76051916-generic            | 43        | 0.35%   |
| 6.0.3-76060003-generic              | 40        | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1626      | 13.52%  |
| 5.4.0   | 1371      | 11.4%   |
| 5.8.0   | 1360      | 11.31%  |
| 5.13.0  | 910       | 7.57%   |
| 6.2.6   | 836       | 6.95%   |
| 6.0.12  | 494       | 4.11%   |
| 5.17.5  | 467       | 3.88%   |
| 5.19.0  | 453       | 3.77%   |
| 6.6.10  | 317       | 2.64%   |
| 6.5.6   | 309       | 2.57%   |
| 6.0.6   | 303       | 2.52%   |
| 6.4.6   | 299       | 2.49%   |
| 5.15.15 | 281       | 2.34%   |
| 5.16.11 | 264       | 2.19%   |
| 5.15.5  | 238       | 1.98%   |
| 6.6.6   | 233       | 1.94%   |
| 5.18.10 | 214       | 1.78%   |
| 6.8.0   | 198       | 1.65%   |
| 5.17.15 | 190       | 1.58%   |
| 5.16.19 | 180       | 1.5%    |
| 5.15.8  | 169       | 1.4%    |
| 5.16.15 | 151       | 1.26%   |
| 6.5.4   | 132       | 1.1%    |
| 6.2.0   | 123       | 1.02%   |
| 5.15.11 | 117       | 0.97%   |
| 6.0.2   | 94        | 0.78%   |
| 6.1.11  | 92        | 0.76%   |
| 5.15.23 | 91        | 0.76%   |
| 5.3.0   | 51        | 0.42%   |
| 5.19.16 | 43        | 0.36%   |
| 6.0.3   | 40        | 0.33%   |
| 5.15.0  | 16        | 0.13%   |
| 5.0.0   | 12        | 0.1%    |
| 5.8.5   | 8         | 0.07%   |
| 5.7.0   | 8         | 0.07%   |
| 5.8.12  | 7         | 0.06%   |
| 4.18.0  | 7         | 0.06%   |
| 6.1.0   | 6         | 0.05%   |
| 5.13.12 | 6         | 0.05%   |
| 5.10.0  | 6         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1636      | 13.75%  |
| 5.8     | 1397      | 11.74%  |
| 5.4     | 1375      | 11.56%  |
| 6.2     | 958       | 8.05%   |
| 5.13    | 930       | 7.82%   |
| 6.0     | 909       | 7.64%   |
| 5.15    | 908       | 7.63%   |
| 5.17    | 657       | 5.52%   |
| 5.16    | 586       | 4.93%   |
| 6.6     | 539       | 4.53%   |
| 5.19    | 498       | 4.19%   |
| 6.5     | 446       | 3.75%   |
| 6.4     | 307       | 2.58%   |
| 5.18    | 221       | 1.86%   |
| 6.8     | 200       | 1.68%   |
| 6.1     | 109       | 0.92%   |
| 5.3     | 51        | 0.43%   |
| 5.10    | 28        | 0.24%   |
| 5.7     | 27        | 0.23%   |
| 5.12    | 19        | 0.16%   |
| 6.3     | 18        | 0.15%   |
| 5.14    | 16        | 0.13%   |
| 5.9     | 15        | 0.13%   |
| 5.6     | 15        | 0.13%   |
| 5.0     | 12        | 0.1%    |
| 4.18    | 8         | 0.07%   |
| 6.7     | 5         | 0.04%   |
| 4.15    | 3         | 0.03%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 10663     | 99.79%  |
| aarch64 | 22        | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 10347     | 96.27%  |
| KDE5            | 109       | 1.01%   |
| Unknown         | 72        | 0.67%   |
| KDE             | 59        | 0.55%   |
| X-Cinnamon      | 44        | 0.41%   |
| MATE            | 21        | 0.2%    |
| GNOME Flashback | 20        | 0.19%   |
| XFCE            | 17        | 0.16%   |
| Cinnamon        | 17        | 0.16%   |
| LXQt            | 13        | 0.12%   |
| Unity           | 9         | 0.08%   |
| i3              | 6         | 0.06%   |
| Budgie          | 6         | 0.06%   |
| awesome         | 3         | 0.03%   |
| Deepin          | 2         | 0.02%   |
| UKUI            | 1         | 0.01%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 10342     | 96.21%  |
| Wayland | 351       | 3.27%   |
| Unknown | 37        | 0.34%   |
| Tty     | 19        | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8341      | 77.09%  |
| GDM     | 1236      | 11.42%  |
| GDM3    | 1208      | 11.16%  |
| SDDM    | 23        | 0.21%   |
| TDM     | 8         | 0.07%   |
| LightDM | 4         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 6124      | 56.81%  |
| en_GB   | 788       | 7.31%   |
| pt_BR   | 721       | 6.69%   |
| de_DE   | 531       | 4.93%   |
| C       | 350       | 3.25%   |
| en_AU   | 285       | 2.64%   |
| en_CA   | 236       | 2.19%   |
| fr_FR   | 223       | 2.07%   |
| it_IT   | 185       | 1.72%   |
| es_ES   | 166       | 1.54%   |
| ru_RU   | 141       | 1.31%   |
| pl_PL   | 95        | 0.88%   |
| Unknown | 88        | 0.82%   |
| pt_PT   | 73        | 0.68%   |
| sv_SE   | 69        | 0.64%   |
| nl_NL   | 58        | 0.54%   |
| en_IN   | 49        | 0.45%   |
| fi_FI   | 36        | 0.33%   |
| nb_NO   | 34        | 0.32%   |
| en_ZA   | 31        | 0.29%   |
| tr_TR   | 30        | 0.28%   |
| es_MX   | 30        | 0.28%   |
| en_NZ   | 28        | 0.26%   |
| fr_CA   | 26        | 0.24%   |
| es_AR   | 25        | 0.23%   |
| en_DK   | 24        | 0.22%   |
| da_DK   | 22        | 0.2%    |
| es_CL   | 20        | 0.19%   |
| cs_CZ   | 20        | 0.19%   |
| de_CH   | 18        | 0.17%   |
| hu_HU   | 16        | 0.15%   |
| sk_SK   | 15        | 0.14%   |
| ja_JP   | 15        | 0.14%   |
| de_AT   | 15        | 0.14%   |
| zh_TW   | 14        | 0.13%   |
| en_IE   | 14        | 0.13%   |
| nl_BE   | 13        | 0.12%   |
| zh_CN   | 12        | 0.11%   |
| hr_HR   | 12        | 0.11%   |
| ro_RO   | 10        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7919      | 73.03%  |
| EFI  | 2925      | 26.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 10243     | 95.48%  |
| Btrfs   | 245       | 2.28%   |
| Overlay | 184       | 1.72%   |
| Xfs     | 32        | 0.3%    |
| Unknown | 13        | 0.12%   |
| Zfs     | 9         | 0.08%   |
| Tmpfs   | 1         | 0.01%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8284      | 76.72%  |
| GPT     | 2287      | 21.18%  |
| MBR     | 227       | 2.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10405     | 96.97%  |
| Yes       | 325       | 3.03%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9692      | 90.17%  |
| Yes       | 1057      | 9.83%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1882      | 17.61%  |
| Lenovo                  | 1464      | 13.7%   |
| Dell                    | 1385      | 12.96%  |
| Hewlett-Packard         | 1163      | 10.88%  |
| MSI                     | 807       | 7.55%   |
| Gigabyte Technology     | 786       | 7.36%   |
| Acer                    | 511       | 4.78%   |
| Apple                   | 477       | 4.46%   |
| ASRock                  | 388       | 3.63%   |
| System76                | 250       | 2.34%   |
| Intel                   | 145       | 1.36%   |
| Toshiba                 | 111       | 1.04%   |
| Samsung Electronics     | 111       | 1.04%   |
| HUAWEI                  | 75        | 0.7%    |
| Alienware               | 67        | 0.63%   |
| Microsoft               | 62        | 0.58%   |
| Notebook                | 55        | 0.51%   |
| Sony                    | 52        | 0.49%   |
| Google                  | 51        | 0.48%   |
| Fujitsu                 | 50        | 0.47%   |
| Unknown                 | 50        | 0.47%   |
| Positivo                | 43        | 0.4%    |
| Pegatron                | 29        | 0.27%   |
| Razer                   | 28        | 0.26%   |
| Medion                  | 23        | 0.22%   |
| Biostar                 | 23        | 0.22%   |
| Raspberry Pi Foundation | 22        | 0.21%   |
| Supermicro              | 21        | 0.2%    |
| Timi                    | 20        | 0.19%   |
| Foxconn                 | 19        | 0.18%   |
| PC Specialist           | 18        | 0.17%   |
| LG Electronics          | 16        | 0.15%   |
| Framework               | 15        | 0.14%   |
| ECS                     | 15        | 0.14%   |
| AZW                     | 15        | 0.14%   |
| TUXEDO                  | 14        | 0.13%   |
| Packard Bell            | 14        | 0.13%   |
| Gateway                 | 14        | 0.13%   |
| BESSTAR Tech            | 14        | 0.13%   |
| Huanan                  | 13        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 99        | 0.93%   |
| Unknown                      | 67        | 0.63%   |
| System76 Oryx Pro            | 51        | 0.48%   |
| ASUS TUF Gaming X570-PLUS    | 46        | 0.43%   |
| System76 Lemur Pro           | 42        | 0.39%   |
| Dell XPS 15 7590             | 35        | 0.33%   |
| Gigabyte B450M DS3H          | 34        | 0.32%   |
| MSI MS-7C02                  | 33        | 0.31%   |
| ASUS ROG STRIX B550-F GAMING | 33        | 0.31%   |
| MSI MS-7C37                  | 31        | 0.29%   |
| ASUS ROG STRIX B450-F GAMING | 31        | 0.29%   |
| System76 Gazelle             | 30        | 0.28%   |
| MSI MS-7B86                  | 29        | 0.27%   |
| Apple MacBookPro9,2          | 28        | 0.26%   |
| Apple MacBookPro8,1          | 27        | 0.25%   |
| Dell OptiPlex 9020           | 25        | 0.23%   |
| ASUS PRIME B450M-A           | 24        | 0.22%   |
| System76 Galago Pro          | 23        | 0.22%   |
| Apple MacBookPro12,1         | 23        | 0.22%   |
| Apple MacBookAir7,2          | 23        | 0.22%   |
| System76 Darter Pro          | 22        | 0.21%   |
| Dell XPS 15 9500             | 22        | 0.21%   |
| Apple MacBookAir6,2          | 22        | 0.21%   |
| System76 Thelio              | 21        | 0.2%    |
| HP Notebook                  | 21        | 0.2%    |
| Gigabyte X570 AORUS ELITE    | 21        | 0.2%    |
| HP Pavilion Notebook         | 20        | 0.19%   |
| Dell OptiPlex 7010           | 20        | 0.19%   |
| Gigabyte A320M-S2H           | 19        | 0.18%   |
| HP Pavilion 15               | 18        | 0.17%   |
| MSI MS-7C91                  | 17        | 0.16%   |
| HP Pavilion dv6              | 17        | 0.16%   |
| Dell XPS 15 9570             | 17        | 0.16%   |
| ASRock B450M Steel Legend    | 17        | 0.16%   |
| ASRock B450M Pro4            | 17        | 0.16%   |
| Apple MacBookPro7,1          | 17        | 0.16%   |
| RPi Raspberry Pi             | 16        | 0.15%   |
| Dell XPS 15 9560             | 16        | 0.15%   |
| Gigabyte X570 AORUS MASTER   | 15        | 0.14%   |
| Gigabyte B450 AORUS PRO WIFI | 15        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 621       | 5.81%   |
| ASUS ROG           | 388       | 3.63%   |
| Dell Inspiron      | 379       | 3.55%   |
| Acer Aspire        | 339       | 3.17%   |
| Lenovo IdeaPad     | 334       | 3.13%   |
| Dell Latitude      | 273       | 2.55%   |
| Dell XPS           | 246       | 2.3%    |
| ASUS PRIME         | 218       | 2.04%   |
| HP Pavilion        | 212       | 1.98%   |
| ASUS TUF           | 187       | 1.75%   |
| Dell OptiPlex      | 169       | 1.58%   |
| HP EliteBook       | 141       | 1.32%   |
| Dell Precision     | 130       | 1.22%   |
| ASUS VivoBook      | 128       | 1.2%    |
| HP Laptop          | 119       | 1.11%   |
| Lenovo Legion      | 102       | 0.95%   |
| ASUS All           | 99        | 0.93%   |
| Toshiba Satellite  | 95        | 0.89%   |
| HP ProBook         | 92        | 0.86%   |
| Lenovo Yoga        | 86        | 0.8%    |
| HP ENVY            | 86        | 0.8%    |
| Gigabyte X570      | 80        | 0.75%   |
| HP Compaq          | 79        | 0.74%   |
| Dell Vostro        | 70        | 0.66%   |
| Unknown            | 67        | 0.63%   |
| Lenovo ThinkCentre | 64        | 0.6%    |
| ASUS ASUS          | 63        | 0.59%   |
| Acer Nitro         | 63        | 0.59%   |
| Microsoft Surface  | 62        | 0.58%   |
| Gigabyte B450      | 56        | 0.52%   |
| HP OMEN            | 52        | 0.49%   |
| Gigabyte B450M     | 52        | 0.49%   |
| System76 Oryx      | 51        | 0.48%   |
| ASUS ZenBook       | 48        | 0.45%   |
| Acer Swift         | 46        | 0.43%   |
| System76 Lemur     | 45        | 0.42%   |
| Apple MacBookPro11 | 45        | 0.42%   |
| ASRock B450M       | 42        | 0.39%   |
| ASRock X570        | 39        | 0.36%   |
| Apple MacBookPro8  | 38        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1251      | 11.71%  |
| 2020    | 1248      | 11.68%  |
| 2018    | 1198      | 11.21%  |
| 2021    | 944       | 8.83%   |
| 2012    | 757       | 7.08%   |
| 2017    | 716       | 6.7%    |
| 2013    | 660       | 6.18%   |
| 2011    | 606       | 5.67%   |
| 2014    | 553       | 5.18%   |
| 2015    | 534       | 5%      |
| 2022    | 494       | 4.62%   |
| 2016    | 493       | 4.61%   |
| 2010    | 369       | 3.45%   |
| 2009    | 279       | 2.61%   |
| 2008    | 218       | 2.04%   |
| 2023    | 186       | 1.74%   |
| 2007    | 126       | 1.18%   |
| 2006    | 23        | 0.22%   |
| Unknown | 23        | 0.22%   |
| 2024    | 4         | 0.04%   |
| 2005    | 2         | 0.02%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5915      | 55.36%  |
| Desktop        | 3991      | 37.35%  |
| Convertible    | 298       | 2.79%   |
| Mini pc        | 148       | 1.39%   |
| All in one     | 140       | 1.31%   |
| Tablet         | 130       | 1.22%   |
| Server         | 39        | 0.36%   |
| System on chip | 23        | 0.22%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 10678     | 99.92%  |
| Enabled  | 9         | 0.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10498     | 98.25%  |
| Yes  | 187       | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2808      | 25.92%  |
| 4.01-8.0        | 2313      | 21.35%  |
| 8.01-16.0       | 1989      | 18.36%  |
| 32.01-64.0      | 1589      | 14.67%  |
| 3.01-4.0        | 1243      | 11.47%  |
| 64.01-256.0     | 460       | 4.25%   |
| 24.01-32.0      | 248       | 2.29%   |
| 1.01-2.0        | 124       | 1.14%   |
| 2.01-3.0        | 50        | 0.46%   |
| More than 256.0 | 10        | 0.09%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 3235      | 27.58%  |
| 4.01-8.0    | 2881      | 24.56%  |
| 1.01-2.0    | 2470      | 21.06%  |
| 3.01-4.0    | 2172      | 18.52%  |
| 8.01-16.0   | 785       | 6.69%   |
| 16.01-24.0  | 106       | 0.9%    |
| 24.01-32.0  | 34        | 0.29%   |
| 0.51-1.0    | 23        | 0.2%    |
| 32.01-64.0  | 20        | 0.17%   |
| 64.01-256.0 | 4         | 0.03%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 6117      | 55.84%  |
| 2      | 2965      | 27.07%  |
| 3      | 967       | 8.83%   |
| 4      | 474       | 4.33%   |
| 5      | 202       | 1.84%   |
| 6      | 91        | 0.83%   |
| 0      | 59        | 0.54%   |
| 7      | 38        | 0.35%   |
| 8      | 13        | 0.12%   |
| 11     | 9         | 0.08%   |
| 9      | 9         | 0.08%   |
| 10     | 3         | 0.03%   |
| 26     | 1         | 0.01%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7788      | 72.52%  |
| Yes       | 2951      | 27.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9035      | 84.2%   |
| No        | 1696      | 15.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8722      | 81.26%  |
| No        | 2012      | 18.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7354      | 68.15%  |
| No        | 3437      | 31.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3218      | 29.97%  |
| Brazil       | 980       | 9.13%   |
| Germany      | 743       | 6.92%   |
| UK           | 536       | 4.99%   |
| Canada       | 468       | 4.36%   |
| Australia    | 335       | 3.12%   |
| Italy        | 306       | 2.85%   |
| India        | 301       | 2.8%    |
| France       | 283       | 2.64%   |
| Netherlands  | 233       | 2.17%   |
| Russia       | 193       | 1.8%    |
| Sweden       | 186       | 1.73%   |
| Poland       | 170       | 1.58%   |
| Spain        | 154       | 1.43%   |
| Portugal     | 121       | 1.13%   |
| Mexico       | 120       | 1.12%   |
| Switzerland  | 108       | 1.01%   |
| Norway       | 100       | 0.93%   |
| Finland      | 98        | 0.91%   |
| South Africa | 96        | 0.89%   |
| Romania      | 92        | 0.86%   |
| Austria      | 85        | 0.79%   |
| Belgium      | 76        | 0.71%   |
| New Zealand  | 75        | 0.7%    |
| Philippines  | 74        | 0.69%   |
| Denmark      | 74        | 0.69%   |
| Turkey       | 71        | 0.66%   |
| Greece       | 70        | 0.65%   |
| Argentina    | 70        | 0.65%   |
| Indonesia    | 67        | 0.62%   |
| Czechia      | 65        | 0.61%   |
| Chile        | 54        | 0.5%    |
| Japan        | 50        | 0.47%   |
| Hungary      | 49        | 0.46%   |
| Bulgaria     | 49        | 0.46%   |
| Ireland      | 44        | 0.41%   |
| Malaysia     | 40        | 0.37%   |
| Serbia       | 38        | 0.35%   |
| Croatia      | 38        | 0.35%   |
| Ukraine      | 36        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 116       | 1.03%   |
| Sydney         | 86        | 0.76%   |
| Melbourne      | 82        | 0.73%   |
| Berlin         | 65        | 0.58%   |
| Rio de Janeiro | 62        | 0.55%   |
| Brisbane       | 58        | 0.52%   |
| Milan          | 55        | 0.49%   |
| Helsinki       | 54        | 0.48%   |
| Vienna         | 51        | 0.45%   |
| Warsaw         | 48        | 0.43%   |
| Moscow         | 47        | 0.42%   |
| New York       | 46        | 0.41%   |
| Denver         | 44        | 0.39%   |
| Chicago        | 44        | 0.39%   |
| London         | 43        | 0.38%   |
| Dallas         | 43        | 0.38%   |
| Bengaluru      | 42        | 0.37%   |
| Amsterdam      | 40        | 0.36%   |
| Toronto        | 39        | 0.35%   |
| Seattle        | 38        | 0.34%   |
| Paris          | 38        | 0.34%   |
| Rome           | 37        | 0.33%   |
| Montreal       | 35        | 0.31%   |
| Madrid         | 35        | 0.31%   |
| Auckland       | 35        | 0.31%   |
| Athens         | 35        | 0.31%   |
| Sofia          | 33        | 0.29%   |
| Los Angeles    | 33        | 0.29%   |
| Bucharest      | 33        | 0.29%   |
| Istanbul       | 31        | 0.28%   |
| Zurich         | 30        | 0.27%   |
| Stockholm      | 30        | 0.27%   |
| Miami          | 30        | 0.27%   |
| Lisbon         | 30        | 0.27%   |
| Edmonton       | 30        | 0.27%   |
| Calgary        | 30        | 0.27%   |
| Oslo           | 29        | 0.26%   |
| Johannesburg   | 29        | 0.26%   |
| Hamburg        | 29        | 0.26%   |
| Brasília      | 28        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 3002      | 4629   | 18.22%  |
| WDC                         | 2087      | 2912   | 12.67%  |
| Seagate                     | 2072      | 3004   | 12.58%  |
| SanDisk                     | 1126      | 1501   | 6.84%   |
| Kingston                    | 914       | 1155   | 5.55%   |
| Toshiba                     | 832       | 1034   | 5.05%   |
| Crucial                     | 669       | 886    | 4.06%   |
| Unknown                     | 514       | 677    | 3.12%   |
| SK hynix                    | 487       | 617    | 2.96%   |
| Intel                       | 458       | 617    | 2.78%   |
| Micron Technology           | 311       | 367    | 1.89%   |
| Hitachi                     | 311       | 406    | 1.89%   |
| HGST                        | 268       | 322    | 1.63%   |
| Phison                      | 245       | 337    | 1.49%   |
| A-DATA Technology           | 240       | 296    | 1.46%   |
| Apple                       | 236       | 277    | 1.43%   |
| Micron/Crucial Technology   | 167       | 225    | 1.01%   |
| China                       | 162       | 216    | 0.98%   |
| Silicon Motion              | 152       | 200    | 0.92%   |
| PNY                         | 151       | 187    | 0.92%   |
| Phison Electronics          | 111       | 154    | 0.67%   |
| KIOXIA                      | 111       | 129    | 0.67%   |
| SPCC                        | 76        | 106    | 0.46%   |
| Kingston Technology Company | 69        | 84     | 0.42%   |
| LITEON                      | 66        | 79     | 0.4%    |
| OCZ                         | 65        | 84     | 0.39%   |
| Transcend                   | 61        | 70     | 0.37%   |
| Team                        | 59        | 70     | 0.36%   |
| XPG                         | 53        | 69     | 0.32%   |
| Realtek Semiconductor       | 53        | 60     | 0.32%   |
| Patriot                     | 51        | 70     | 0.31%   |
| Corsair                     | 49        | 64     | 0.3%    |
| ADATA Technology            | 45        | 57     | 0.27%   |
| JMicron Technology          | 44        | 63     | 0.27%   |
| LITEONIT                    | 43        | 64     | 0.26%   |
| Intenso                     | 43        | 56     | 0.26%   |
| Hewlett-Packard             | 42        | 62     | 0.25%   |
| ASMT                        | 41        | 49     | 0.25%   |
| Unknown                     | 39        | 44     | 0.24%   |
| Netac                       | 38        | 45     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 230       | 1.26%   |
| Samsung NVMe SSD Drive 1TB                         | 197       | 1.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 183       | 1%      |
| Samsung NVMe SSD Drive 500GB                       | 178       | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB                     | 144       | 0.79%   |
| Samsung SSD 850 EVO 250GB                          | 140       | 0.77%   |
| Samsung SSD 850 EVO 500GB                          | 132       | 0.72%   |
| Samsung SSD 860 EVO 500GB                          | 130       | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                         | 123       | 0.67%   |
| Samsung SSD 860 EVO 1TB                            | 118       | 0.65%   |
| Samsung NVMe SSD Drive 512GB                       | 118       | 0.65%   |
| Unknown MMC Card  64GB                             | 117       | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 115       | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                     | 112       | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                     | 107       | 0.59%   |
| Kingston SA400S37480G 480GB SSD                    | 107       | 0.59%   |
| Kingston SA400S37120G 120GB SSD                    | 105       | 0.58%   |
| SanDisk NVMe SSD Drive 500GB                       | 97        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                        | 94        | 0.52%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 91        | 0.5%    |
| HGST HTS721010A9E630 1TB                           | 91        | 0.5%    |
| Toshiba MQ01ABD100 1TB                             | 88        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                    | 86        | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 86        | 0.47%   |
| Crucial CT500MX500SSD1 500GB                       | 85        | 0.47%   |
| Unknown MMC Card  32GB                             | 80        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 74        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                       | 74        | 0.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 74        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                       | 72        | 0.39%   |
| Intel NVMe SSD Drive 512GB                         | 69        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                       | 68        | 0.37%   |
| Unknown MMC Card  128GB                            | 63        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                      | 61        | 0.33%   |
| Seagate Expansion 2TB                              | 61        | 0.33%   |
| Unknown SD/MMC/MS PRO 128GB                        | 60        | 0.33%   |
| Toshiba MQ04ABF100 1TB                             | 59        | 0.32%   |
| Samsung NVMe SSD Drive 2TB                         | 59        | 0.32%   |
| Samsung NVMe SSD Drive 1024GB                      | 58        | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                   | 58        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2004      | 2849   | 38.46%  |
| WDC                 | 1575      | 2197   | 30.23%  |
| Toshiba             | 589       | 717    | 11.31%  |
| Hitachi             | 311       | 406    | 5.97%   |
| HGST                | 268       | 322    | 5.14%   |
| Samsung Electronics | 162       | 192    | 3.11%   |
| Unknown             | 64        | 77     | 1.23%   |
| Apple               | 61        | 74     | 1.17%   |
| JMicron Technology  | 29        | 43     | 0.56%   |
| Maxtor              | 27        | 28     | 0.52%   |
| Fujitsu             | 25        | 30     | 0.48%   |
| SABRENT             | 23        | 28     | 0.44%   |
| TO Exter            | 14        | 17     | 0.27%   |
| Hewlett-Packard     | 11        | 23     | 0.21%   |
| ASMT                | 8         | 10     | 0.15%   |
| MaxDigital          | 3         | 3      | 0.06%   |
| Intenso             | 3         | 7      | 0.06%   |
| ExcelStor           | 3         | 3      | 0.06%   |
| WD MediaMax         | 2         | 3      | 0.04%   |
| USB                 | 2         | 3      | 0.04%   |
| RSH-339             | 2         | 2      | 0.04%   |
| Magnetic Data       | 2         | 2      | 0.04%   |
| LaCie               | 2         | 3      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| Unknown             | 2         | 3      | 0.04%   |
| XrayDisk            | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| External            | 1         | 1      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1365      | 2015   | 24.24%  |
| Kingston            | 729       | 902    | 12.94%  |
| Crucial             | 606       | 797    | 10.76%  |
| SanDisk             | 506       | 648    | 8.98%   |
| WDC                 | 363       | 459    | 6.45%   |
| A-DATA Technology   | 186       | 229    | 3.3%    |
| China               | 160       | 214    | 2.84%   |
| Apple               | 148       | 164    | 2.63%   |
| PNY                 | 147       | 183    | 2.61%   |
| Intel               | 120       | 152    | 2.13%   |
| SK hynix            | 102       | 127    | 1.81%   |
| Micron Technology   | 96        | 106    | 1.7%    |
| Toshiba             | 80        | 93     | 1.42%   |
| SPCC                | 68        | 86     | 1.21%   |
| OCZ                 | 64        | 80     | 1.14%   |
| LITEON              | 60        | 73     | 1.07%   |
| Transcend           | 58        | 67     | 1.03%   |
| Patriot             | 50        | 69     | 0.89%   |
| Team                | 46        | 56     | 0.82%   |
| LITEONIT            | 43        | 64     | 0.76%   |
| Corsair             | 38        | 46     | 0.67%   |
| KingSpec            | 37        | 43     | 0.66%   |
| Seagate             | 35        | 51     | 0.62%   |
| Netac               | 31        | 36     | 0.55%   |
| Lexar               | 29        | 36     | 0.51%   |
| Intenso             | 29        | 37     | 0.51%   |
| Hewlett-Packard     | 25        | 33     | 0.44%   |
| Apacer              | 24        | 33     | 0.43%   |
| Gigabyte Technology | 18        | 21     | 0.32%   |
| KingDian            | 16        | 27     | 0.28%   |
| GOODRAM             | 16        | 18     | 0.28%   |
| Plextor             | 13        | 17     | 0.23%   |
| Mushkin             | 13        | 16     | 0.23%   |
| Dogfish             | 12        | 17     | 0.21%   |
| ASMT                | 12        | 18     | 0.21%   |
| Verbatim            | 9         | 13     | 0.16%   |
| OWC                 | 9         | 18     | 0.16%   |
| KIOXIA-EXCERIA      | 9         | 10     | 0.16%   |
| Maxtor              | 8         | 8      | 0.14%   |
| External            | 8         | 8      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 4862      | 7376   | 33.12%  |
| NVMe    | 4716      | 7119   | 32.12%  |
| HDD     | 4430      | 7065   | 30.17%  |
| MMC     | 395       | 490    | 2.69%   |
| Unknown | 279       | 421    | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 7355      | 13834  | 56.03%  |
| NVMe | 4711      | 7094   | 35.89%  |
| SAS  | 667       | 1053   | 5.08%   |
| MMC  | 395       | 490    | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 5336      | 8016   | 54.75%  |
| 0.51-1.0        | 2921      | 4085   | 29.97%  |
| 1.01-2.0        | 877       | 1282   | 9%      |
| 3.01-4.0        | 276       | 463    | 2.83%   |
| 2.01-3.0        | 158       | 241    | 1.62%   |
| 4.01-10.0       | 148       | 293    | 1.52%   |
| 10.01-20.0      | 30        | 60     | 0.31%   |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3245      | 29.14%  |
| 251-500        | 2785      | 25.01%  |
| 501-1000       | 2112      | 18.97%  |
| 1001-2000      | 1054      | 9.47%   |
| More than 3000 | 546       | 4.9%    |
| 51-100         | 483       | 4.34%   |
| 2001-3000      | 358       | 3.22%   |
| 1-20           | 255       | 2.29%   |
| 21-50          | 224       | 2.01%   |
| Unknown        | 73        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4090      | 35.01%  |
| 21-50          | 2404      | 20.58%  |
| 101-250        | 1509      | 12.92%  |
| 51-100         | 1404      | 12.02%  |
| 251-500        | 920       | 7.88%   |
| 501-1000       | 618       | 5.29%   |
| 1001-2000      | 349       | 2.99%   |
| More than 3000 | 197       | 1.69%   |
| 2001-3000      | 117       | 1%      |
| Unknown        | 73        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 7         | 7      | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 1.81%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.81%   |
| HGST HTS721010A9E630 1TB                 | 5         | 5      | 1.51%   |
| HGST HTS541010A9E680 1TB                 | 5         | 5      | 1.51%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 4         | 4      | 1.21%   |
| Seagate ST500LT012-9WS142 500GB          | 4         | 5      | 1.21%   |
| Seagate ST500DM002-1BD142 500GB          | 4         | 4      | 1.21%   |
| Seagate ST1000LX015-1U7172 1TB           | 4         | 4      | 1.21%   |
| Crucial CT525MX300SSD1 528GB             | 4         | 4      | 1.21%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 3         | 3      | 0.91%   |
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 0.91%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 0.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 3         | 3      | 0.91%   |
| Seagate ST1500DL003-9VT16L 1TB           | 3         | 5      | 0.91%   |
| Seagate ST1000DM003-9YN162 1TB           | 3         | 3      | 0.91%   |
| Samsung Electronics HD502HI 500GB        | 3         | 5      | 0.91%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 5      | 0.91%   |
| Kingston SA400S37120G 120GB SSD          | 3         | 5      | 0.91%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 0.91%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 0.91%   |
| Crucial CT1000P1SSD8 1TB                 | 3         | 3      | 0.91%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2         | 2      | 0.6%    |
| WDC WD10JPVX-60JC3T0 1TB                 | 2         | 2      | 0.6%    |
| WDC WD10EZEX-60WN4A0 1TB                 | 2         | 2      | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB                 | 2         | 3      | 0.6%    |
| WDC WD1002FAEX-00Z3A0 1TB                | 2         | 2      | 0.6%    |
| Toshiba MK7559GSXP 752GB                 | 2         | 2      | 0.6%    |
| Toshiba HDWD110 1TB                      | 2         | 2      | 0.6%    |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 2         | 2      | 0.6%    |
| Seagate ST9750420AS 752GB                | 2         | 2      | 0.6%    |
| Seagate ST9500325AS 500GB                | 2         | 3      | 0.6%    |
| Seagate ST9320325AS 320GB                | 2         | 2      | 0.6%    |
| Seagate ST3250310AS 250GB                | 2         | 4      | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB           | 2         | 2      | 0.6%    |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 0.6%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 0.6%    |
| Samsung Electronics SSD 970 EVO Plus 1TB | 2         | 2      | 0.6%    |
| Samsung Electronics SSD 850 EVO 500GB    | 2         | 2      | 0.6%    |
| Samsung Electronics SSD 850 EVO 250GB    | 2         | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 78        | 91     | 24.07%  |
| WDC                         | 68        | 85     | 20.99%  |
| Samsung Electronics         | 33        | 41     | 10.19%  |
| HGST                        | 22        | 25     | 6.79%   |
| Toshiba                     | 21        | 22     | 6.48%   |
| Kingston                    | 13        | 17     | 4.01%   |
| Hitachi                     | 13        | 16     | 4.01%   |
| SK hynix                    | 12        | 14     | 3.7%    |
| Crucial                     | 12        | 12     | 3.7%    |
| Intel                       | 8         | 8      | 2.47%   |
| A-DATA Technology           | 8         | 8      | 2.47%   |
| SanDisk                     | 7         | 7      | 2.16%   |
| Micron Technology           | 6         | 8      | 1.85%   |
| China                       | 3         | 3      | 0.93%   |
| Team                        | 2         | 2      | 0.62%   |
| LITEON                      | 2         | 2      | 0.62%   |
| Apple                       | 2         | 2      | 0.62%   |
| SPCC                        | 1         | 1      | 0.31%   |
| Silicon Motion              | 1         | 1      | 0.31%   |
| SABRENT                     | 1         | 1      | 0.31%   |
| S3+                         | 1         | 1      | 0.31%   |
| Plextor                     | 1         | 1      | 0.31%   |
| Maxtor                      | 1         | 1      | 0.31%   |
| Lexar                       | 1         | 1      | 0.31%   |
| Leven                       | 1         | 1      | 0.31%   |
| Kingston Technology Company | 1         | 1      | 0.31%   |
| Intenso                     | 1         | 1      | 0.31%   |
| Flashwar                    | 1         | 1      | 0.31%   |
| BAITITON                    | 1         | 1      | 0.31%   |
| ASMT                        | 1         | 1      | 0.31%   |
| Apacer                      | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 91     | 37.14%  |
| WDC                 | 64        | 81     | 30.48%  |
| HGST                | 22        | 25     | 10.48%  |
| Toshiba             | 18        | 18     | 8.57%   |
| Hitachi             | 13        | 16     | 6.19%   |
| Samsung Electronics | 11        | 13     | 5.24%   |
| Apple               | 2         | 2      | 0.95%   |
| SABRENT             | 1         | 1      | 0.48%   |
| Maxtor              | 1         | 1      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 197       | 248    | 63.14%  |
| SSD  | 81        | 93     | 25.96%  |
| NVMe | 34        | 36     | 10.9%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 16.67%  |
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 16.67%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 16.67%  |
| Patriot Pyro SSD 120GB            | 1         | 2      | 16.67%  |
| KingDian S400 120GB SSD           | 1         | 2      | 16.67%  |
| Intenso JAJP600M1TB               | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Patriot             | 1         | 2      | 16.67%  |
| KingDian            | 1         | 2      | 16.67%  |
| Intenso             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8523      | 18080  | 75.85%  |
| Works    | 2406      | 4005   | 21.41%  |
| Malfunc  | 300       | 377    | 2.67%   |
| Failed   | 6         | 8      | 0.05%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6418      | 43.39%  |
| AMD                              | 2584      | 17.47%  |
| Samsung Electronics              | 1844      | 12.47%  |
| SanDisk                          | 813       | 5.5%    |
| SK hynix                         | 385       | 2.6%    |
| Phison Electronics               | 371       | 2.51%   |
| Kingston Technology Company      | 259       | 1.75%   |
| ASMedia Technology               | 241       | 1.63%   |
| Micron/Crucial Technology        | 223       | 1.51%   |
| Micron Technology                | 218       | 1.47%   |
| Toshiba America Info Systems     | 184       | 1.24%   |
| Nvidia                           | 174       | 1.18%   |
| Silicon Motion                   | 172       | 1.16%   |
| ADATA Technology                 | 133       | 0.9%    |
| Marvell Technology Group         | 131       | 0.89%   |
| KIOXIA                           | 112       | 0.76%   |
| JMicron Technology               | 96        | 0.65%   |
| Realtek Semiconductor            | 72        | 0.49%   |
| Solid State Storage Technology   | 48        | 0.32%   |
| Union Memory (Shenzhen)          | 42        | 0.28%   |
| Seagate Technology               | 32        | 0.22%   |
| Broadcom / LSI                   | 32        | 0.22%   |
| Apple                            | 30        | 0.2%    |
| LSI Logic / Symbios Logic        | 22        | 0.15%   |
| Lite-On Technology               | 19        | 0.13%   |
| Shenzhen Longsys Electronics     | 18        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 18        | 0.12%   |
| VIA Technologies                 | 12        | 0.08%   |
| Solidigm                         | 12        | 0.08%   |
| Silicon Integrated Systems [SiS] | 10        | 0.07%   |
| INNOGRIT                         | 10        | 0.07%   |
| Silicon Image                    | 8         | 0.05%   |
| Hewlett-Packard                  | 8         | 0.05%   |
| Lenovo                           | 7         | 0.05%   |
| Adaptec                          | 6         | 0.04%   |
| Netac Technology                 | 5         | 0.03%   |
| Biwin Storage Technology         | 4         | 0.03%   |
| Yangtze Memory Technologies      | 3         | 0.02%   |
| Transcend                        | 3         | 0.02%   |
| HighPoint Technologies           | 3         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1848      | 11.13%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 966       | 5.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 514       | 3.09%   |
| AMD 400 Series Chipset SATA Controller                                         | 496       | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 434       | 2.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 401       | 2.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 372       | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 340       | 2.05%   |
| AMD 500 Series Chipset SATA Controller                                         | 297       | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 286       | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 274       | 1.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 270       | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 261       | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 249       | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 234       | 1.41%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 228       | 1.37%   |
| Intel SATA Controller [RAID mode]                                              | 210       | 1.26%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 208       | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 204       | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 196       | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 194       | 1.17%   |
| Phison E12 NVMe Controller                                                     | 174       | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 172       | 1.04%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 170       | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 169       | 1.02%   |
| Intel SSD 660P Series                                                          | 167       | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 159       | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 157       | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 149       | 0.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 144       | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 136       | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 132       | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 129       | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 128       | 0.77%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 111       | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 108       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 106       | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 103       | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 93        | 0.56%   |
| AMD 300 Series Chipset SATA Controller                                         | 92        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7870      | 54.51%  |
| NVMe | 4707      | 32.6%   |
| RAID | 973       | 6.74%   |
| IDE  | 823       | 5.7%    |
| SAS  | 47        | 0.33%   |
| SCSI | 17        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 7512      | 70.3%   |
| AMD    | 3151      | 29.49%  |
| ARM    | 22        | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 162       | 1.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 143       | 1.33%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 126       | 1.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 122       | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 120       | 1.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 111       | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 111       | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 106       | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 95        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 93        | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 86        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 85        | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 84        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 81        | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 80        | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 79        | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 75        | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 74        | 0.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 71        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 69        | 0.64%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 69        | 0.64%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 64        | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 63        | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 62        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 61        | 0.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 60        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 59        | 0.55%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 59        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 58        | 0.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 56        | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 55        | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 54        | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 53        | 0.49%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 53        | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 48        | 0.45%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 48        | 0.45%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 48        | 0.45%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 48        | 0.45%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 48        | 0.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 47        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2453      | 22.92%  |
| Intel Core i5           | 2297      | 21.46%  |
| AMD Ryzen 5             | 1014      | 9.47%   |
| Other                   | 850       | 7.94%   |
| AMD Ryzen 7             | 837       | 7.82%   |
| Intel Core i3           | 585       | 5.47%   |
| AMD Ryzen 9             | 326       | 3.05%   |
| Intel Core 2 Duo        | 282       | 2.63%   |
| Intel Celeron           | 271       | 2.53%   |
| Intel Xeon              | 238       | 2.22%   |
| AMD FX                  | 144       | 1.35%   |
| AMD Ryzen 3             | 140       | 1.31%   |
| Intel Pentium           | 125       | 1.17%   |
| Intel Core i9           | 123       | 1.15%   |
| AMD A8                  | 71        | 0.66%   |
| AMD A6                  | 69        | 0.64%   |
| Intel Pentium Dual-Core | 67        | 0.63%   |
| Intel Atom              | 67        | 0.63%   |
| AMD A10                 | 64        | 0.6%    |
| AMD Ryzen 7 PRO         | 56        | 0.52%   |
| Intel Core 2 Quad       | 53        | 0.5%    |
| AMD Ryzen Threadripper  | 52        | 0.49%   |
| AMD A4                  | 42        | 0.39%   |
| AMD Ryzen 5 PRO         | 36        | 0.34%   |
| Intel Core 2            | 35        | 0.33%   |
| AMD Phenom II X4        | 35        | 0.33%   |
| AMD Athlon              | 34        | 0.32%   |
| AMD Athlon II X2        | 26        | 0.24%   |
| Intel Pentium Dual      | 22        | 0.21%   |
| Intel Pentium Silver    | 18        | 0.17%   |
| Intel Genuine           | 18        | 0.17%   |
| Intel Core m3           | 18        | 0.17%   |
| AMD Athlon II X4        | 18        | 0.17%   |
| AMD E1                  | 16        | 0.15%   |
| AMD E                   | 16        | 0.15%   |
| AMD Phenom II X6        | 14        | 0.13%   |
| AMD Athlon 64 X2        | 13        | 0.12%   |
| Intel Pentium Gold      | 12        | 0.11%   |
| AMD E2                  | 12        | 0.11%   |
| Intel Core m5           | 10        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3854      | 36.01%  |
| 2       | 3193      | 29.83%  |
| 6       | 1538      | 14.37%  |
| 8       | 1276      | 11.92%  |
| 12      | 262       | 2.45%   |
| 16      | 151       | 1.41%   |
| 10      | 115       | 1.07%   |
| 14      | 113       | 1.06%   |
| 1       | 62        | 0.58%   |
| 3       | 57        | 0.53%   |
| 24      | 39        | 0.36%   |
| 32      | 16        | 0.15%   |
| Unknown | 10        | 0.09%   |
| 64      | 4         | 0.04%   |
| 20      | 4         | 0.04%   |
| 40      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 48      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10614     | 99.33%  |
| 2       | 62        | 0.58%   |
| Unknown | 10        | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8323      | 77.79%  |
| 1       | 2366      | 22.11%  |
| Unknown | 10        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10659     | 99.76%  |
| 64-bit         | 15        | 0.14%   |
| Unknown        | 11        | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7728      | 70.64%  |
| 0x906ea    | 193       | 1.76%   |
| 0x306a9    | 168       | 1.54%   |
| 0x206a7    | 147       | 1.34%   |
| 0x306c3    | 136       | 1.24%   |
| 0x806ea    | 126       | 1.15%   |
| 0x806ec    | 124       | 1.13%   |
| 0x806c1    | 118       | 1.08%   |
| 0x08701021 | 112       | 1.02%   |
| 0x406e3    | 95        | 0.87%   |
| 0x906e9    | 88        | 0.8%    |
| 0x40651    | 87        | 0.8%    |
| 0x806e9    | 81        | 0.74%   |
| 0x506e3    | 79        | 0.72%   |
| 0x0800820d | 79        | 0.72%   |
| 0x08701013 | 77        | 0.7%    |
| 0xa0652    | 75        | 0.69%   |
| 0x0a50000c | 73        | 0.67%   |
| 0x1067a    | 63        | 0.58%   |
| 0x08108109 | 59        | 0.54%   |
| 0x08600106 | 54        | 0.49%   |
| 0x08108102 | 51        | 0.47%   |
| 0x906ed    | 44        | 0.4%    |
| 0x306d4    | 44        | 0.4%    |
| 0x806d1    | 38        | 0.35%   |
| 0x806eb    | 37        | 0.34%   |
| 0x08608103 | 36        | 0.33%   |
| 0x20655    | 30        | 0.27%   |
| 0x08600104 | 29        | 0.27%   |
| 0x0a201016 | 28        | 0.26%   |
| 0x08001138 | 28        | 0.26%   |
| 0x706e5    | 27        | 0.25%   |
| 0x906a3    | 26        | 0.24%   |
| 0x406c4    | 26        | 0.24%   |
| 0x0810100b | 26        | 0.24%   |
| 0x0a404102 | 25        | 0.23%   |
| 0x06000852 | 25        | 0.23%   |
| 0x0a50000d | 24        | 0.22%   |
| 0x06006705 | 23        | 0.21%   |
| 0x0a601203 | 22        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1897      | 17.72%  |
| Haswell          | 977       | 9.12%   |
| Zen 2            | 801       | 7.48%   |
| SandyBridge      | 694       | 6.48%   |
| IvyBridge        | 691       | 6.45%   |
| Unknown          | 626       | 5.85%   |
| Zen 3            | 598       | 5.58%   |
| Skylake          | 592       | 5.53%   |
| Zen+             | 536       | 5.01%   |
| Penryn           | 355       | 3.32%   |
| CometLake        | 355       | 3.32%   |
| TigerLake        | 325       | 3.04%   |
| Zen              | 265       | 2.47%   |
| Broadwell        | 237       | 2.21%   |
| Westmere         | 228       | 2.13%   |
| Piledriver       | 199       | 1.86%   |
| Silvermont       | 161       | 1.5%    |
| IceLake          | 148       | 1.38%   |
| Core             | 146       | 1.36%   |
| Alderlake Hybrid | 143       | 1.34%   |
| K10              | 126       | 1.18%   |
| Nehalem          | 110       | 1.03%   |
| Excavator        | 99        | 0.92%   |
| Goldmont plus    | 95        | 0.89%   |
| Puma             | 49        | 0.46%   |
| Steamroller      | 45        | 0.42%   |
| Goldmont         | 39        | 0.36%   |
| Bobcat           | 34        | 0.32%   |
| K8 Hammer        | 31        | 0.29%   |
| K10 Llano        | 31        | 0.29%   |
| Jaguar           | 23        | 0.21%   |
| Bulldozer        | 17        | 0.16%   |
| NetBurst         | 9         | 0.08%   |
| K8 & K10 hybrid  | 9         | 0.08%   |
| Bonnell          | 7         | 0.07%   |
| Tremont          | 5         | 0.05%   |
| Gracemont        | 5         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5624      | 42.86%  |
| Nvidia                           | 4350      | 33.15%  |
| AMD                              | 3115      | 23.74%  |
| Matrox Electronics Systems       | 17        | 0.13%   |
| Silicon Integrated Systems [SiS] | 8         | 0.06%   |
| ASPEED Technology                | 8         | 0.06%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 489       | 3.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 374       | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 368       | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 306       | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 303       | 2.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 299       | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 299       | 2.22%   |
| Intel UHD Graphics 620                                                                   | 298       | 2.21%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 257       | 1.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 245       | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 231       | 1.71%   |
| Intel HD Graphics 620                                                                    | 208       | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 200       | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 192       | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 189       | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 180       | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 173       | 1.28%   |
| Intel HD Graphics 630                                                                    | 171       | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 156       | 1.16%   |
| Intel HD Graphics 5500                                                                   | 154       | 1.14%   |
| Intel HD Graphics 530                                                                    | 142       | 1.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 138       | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 134       | 0.99%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 118       | 0.88%   |
| AMD Lucienne                                                                             | 117       | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 105       | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 103       | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 103       | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 101       | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 98        | 0.73%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 98        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 90        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 89        | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 88        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 84        | 0.62%   |
| AMD Rembrandt [Radeon 680M]                                                              | 81        | 0.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 80        | 0.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 79        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 74        | 0.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 72        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 3664      | 33.9%   |
| 1 x Nvidia              | 2333      | 21.59%  |
| 1 x AMD                 | 2297      | 21.25%  |
| Intel + Nvidia          | 1575      | 14.57%  |
| AMD + Nvidia            | 362       | 3.35%   |
| Intel + AMD             | 258       | 2.39%   |
| 2 x AMD                 | 198       | 1.83%   |
| 2 x Nvidia              | 50        | 0.46%   |
| Other                   | 27        | 0.25%   |
| 1 x Matrox              | 10        | 0.09%   |
| 1 x SiS                 | 8         | 0.07%   |
| Nvidia + Matrox         | 4         | 0.04%   |
| Nvidia + ASPEED         | 4         | 0.04%   |
| Intel + 2 x Nvidia      | 4         | 0.04%   |
| AMD + ASPEED            | 3         | 0.03%   |
| AMD + Matrox            | 2         | 0.02%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x Intel               | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| 1 x ASPEED              | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6913      | 63.86%  |
| Proprietary | 3492      | 32.26%  |
| Unknown     | 420       | 3.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7594      | 69.61%  |
| 1.01-2.0   | 705       | 6.46%   |
| 3.01-4.0   | 651       | 5.97%   |
| 7.01-8.0   | 624       | 5.72%   |
| 5.01-6.0   | 449       | 4.12%   |
| 0.01-0.5   | 364       | 3.34%   |
| 8.01-16.0  | 203       | 1.86%   |
| 0.51-1.0   | 199       | 1.82%   |
| 2.01-3.0   | 85        | 0.78%   |
| 16.01-24.0 | 31        | 0.28%   |
| 4.01-5.0   | 3         | 0.03%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1438      | 11.83%  |
| AU Optronics            | 1326      | 10.91%  |
| Chimei Innolux          | 1058      | 8.71%   |
| BOE                     | 997       | 8.2%    |
| LG Display              | 993       | 8.17%   |
| Goldstar                | 766       | 6.3%    |
| Dell                    | 741       | 6.1%    |
| Acer                    | 480       | 3.95%   |
| Hewlett-Packard         | 369       | 3.04%   |
| Apple                   | 367       | 3.02%   |
| AOC                     | 344       | 2.83%   |
| Sharp                   | 288       | 2.37%   |
| BenQ                    | 264       | 2.17%   |
| Ancor Communications    | 258       | 2.12%   |
| Philips                 | 203       | 1.67%   |
| ASUSTek Computer        | 201       | 1.65%   |
| Lenovo                  | 185       | 1.52%   |
| PANDA                   | 165       | 1.36%   |
| ViewSonic               | 109       | 0.9%    |
| Chi Mei Optoelectronics | 106       | 0.87%   |
| Iiyama                  | 94        | 0.77%   |
| InfoVision              | 85        | 0.7%    |
| Sony                    | 76        | 0.63%   |
| MSI                     | 76        | 0.63%   |
| Sceptre Tech            | 57        | 0.47%   |
| Panasonic               | 52        | 0.43%   |
| Vizio                   | 51        | 0.42%   |
| CSO                     | 47        | 0.39%   |
| Gigabyte Technology     | 41        | 0.34%   |
| Toshiba                 | 37        | 0.3%    |
| NEC Computers           | 29        | 0.24%   |
| Unknown                 | 27        | 0.22%   |
| Eizo                    | 27        | 0.22%   |
| Insignia                | 25        | 0.21%   |
| Vestel Elektronik       | 22        | 0.18%   |
| TMX                     | 22        | 0.18%   |
| Hitachi                 | 22        | 0.18%   |
| Fujitsu Siemens         | 22        | 0.18%   |
| LG Electronics          | 18        | 0.15%   |
| MStar                   | 17        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 76        | 0.61%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 75        | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 59        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 56        | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 56        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 52        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 51        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 50        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 50        | 0.4%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 40        | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 35        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 35        | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 35        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 32        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 32        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 31        | 0.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 30        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 28        | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 27        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 27        | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 26        | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 26        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 26        | 0.21%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 26        | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 25        | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 25        | 0.2%    |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 25        | 0.2%    |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 24        | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 24        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 24        | 0.19%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 24        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 23        | 0.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 23        | 0.18%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 22        | 0.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 21        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 21        | 0.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 21        | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 20        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 20        | 0.16%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 20        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5396      | 47%     |
| 1366x768 (WXGA)    | 1713      | 14.92%  |
| 3840x2160 (4K)     | 1016      | 8.85%   |
| 2560x1440 (QHD)    | 741       | 6.45%   |
| 1600x900 (HD+)     | 348       | 3.03%   |
| 1920x1200 (WUXGA)  | 283       | 2.46%   |
| 3440x1440          | 225       | 1.96%   |
| 1440x900 (WXGA+)   | 219       | 1.91%   |
| 1680x1050 (WSXGA+) | 214       | 1.86%   |
| 2560x1080          | 201       | 1.75%   |
| 1280x1024 (SXGA)   | 175       | 1.52%   |
| 1280x800 (WXGA)    | 147       | 1.28%   |
| 2560x1600          | 130       | 1.13%   |
| 2880x1800          | 88        | 0.77%   |
| 1360x768           | 74        | 0.64%   |
| 3840x1080          | 53        | 0.46%   |
| 1920x540           | 51        | 0.44%   |
| 3840x2400          | 48        | 0.42%   |
| Unknown            | 38        | 0.33%   |
| 2160x1440          | 36        | 0.31%   |
| 2736x1824          | 24        | 0.21%   |
| 3200x1800 (QHD+)   | 21        | 0.18%   |
| 3840x1600          | 18        | 0.16%   |
| 2256x1504          | 18        | 0.16%   |
| 3072x1920          | 16        | 0.14%   |
| 1024x768 (XGA)     | 16        | 0.14%   |
| 3000x2000          | 15        | 0.13%   |
| 1280x720 (HD)      | 15        | 0.13%   |
| 1920x1280          | 14        | 0.12%   |
| 1600x1200          | 14        | 0.12%   |
| 3456x2160          | 9         | 0.08%   |
| 3200x2000          | 9         | 0.08%   |
| 3840x1200          | 7         | 0.06%   |
| 2048x1152          | 6         | 0.05%   |
| 3840x1100          | 5         | 0.04%   |
| 2288x1287          | 5         | 0.04%   |
| 2240x1400          | 5         | 0.04%   |
| 4480x1440          | 4         | 0.03%   |
| 2880x1620          | 4         | 0.03%   |
| 2520x1680          | 4         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3007      | 24.79%  |
| 13      | 1176      | 9.69%   |
| 27      | 1100      | 9.07%   |
| 24      | 966       | 7.96%   |
| 14      | 897       | 7.39%   |
| 23      | 717       | 5.91%   |
| 21      | 604       | 4.98%   |
| 17      | 587       | 4.84%   |
| 31      | 432       | 3.56%   |
| 34      | 359       | 2.96%   |
| 19      | 222       | 1.83%   |
| Unknown | 199       | 1.64%   |
| 12      | 184       | 1.52%   |
| 18      | 179       | 1.48%   |
| 16      | 165       | 1.36%   |
| 22      | 145       | 1.2%    |
| 20      | 131       | 1.08%   |
| 84      | 125       | 1.03%   |
| 32      | 104       | 0.86%   |
| 11      | 95        | 0.78%   |
| 72      | 85        | 0.7%    |
| 40      | 77        | 0.63%   |
| 54      | 66        | 0.54%   |
| 48      | 49        | 0.4%    |
| 26      | 45        | 0.37%   |
| 25      | 41        | 0.34%   |
| 28      | 37        | 0.3%    |
| 52      | 30        | 0.25%   |
| 35      | 30        | 0.25%   |
| 65      | 23        | 0.19%   |
| 49      | 22        | 0.18%   |
| 37      | 22        | 0.18%   |
| 29      | 21        | 0.17%   |
| 46      | 20        | 0.16%   |
| 36      | 17        | 0.14%   |
| 33      | 16        | 0.13%   |
| 42      | 15        | 0.12%   |
| 43      | 12        | 0.1%    |
| 74      | 10        | 0.08%   |
| 47      | 9         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4596      | 38.7%   |
| 501-600        | 2515      | 21.18%  |
| 401-500        | 1157      | 9.74%   |
| 201-300        | 897       | 7.55%   |
| 351-400        | 721       | 6.07%   |
| 601-700        | 628       | 5.29%   |
| 701-800        | 484       | 4.08%   |
| 1001-1500      | 256       | 2.16%   |
| 1501-2000      | 232       | 1.95%   |
| Unknown        | 199       | 1.68%   |
| 801-900        | 150       | 1.26%   |
| 901-1000       | 31        | 0.26%   |
| 101-200        | 4         | 0.03%   |
| More than 2000 | 3         | 0.03%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 8450      | 79.15%  |
| 16/10   | 1237      | 11.59%  |
| 21/9    | 432       | 4.05%   |
| 5/4     | 173       | 1.62%   |
| 3/2     | 124       | 1.16%   |
| Unknown | 109       | 1.02%   |
| 32/9    | 60        | 0.56%   |
| 4/3     | 52        | 0.49%   |
| 6/5     | 10        | 0.09%   |
| 3.20    | 6         | 0.06%   |
| 1.96    | 6         | 0.06%   |
| 3.40    | 5         | 0.05%   |
| 0.62    | 3         | 0.03%   |
| 3.73    | 2         | 0.02%   |
| 1.00    | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 0.89    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2996      | 24.99%  |
| 201-250        | 1909      | 15.92%  |
| 81-90          | 1622      | 13.53%  |
| 301-350        | 1132      | 9.44%   |
| 351-500        | 949       | 7.91%   |
| 151-200        | 519       | 4.33%   |
| 121-130        | 474       | 3.95%   |
| 71-80          | 456       | 3.8%    |
| More than 1000 | 399       | 3.33%   |
| 251-300        | 360       | 3%      |
| 501-1000       | 252       | 2.1%    |
| 141-150        | 228       | 1.9%    |
| Unknown        | 199       | 1.66%   |
| 61-70          | 153       | 1.28%   |
| 111-120        | 153       | 1.28%   |
| 51-60          | 101       | 0.84%   |
| 131-140        | 49        | 0.41%   |
| 91-100         | 25        | 0.21%   |
| 41-50          | 8         | 0.07%   |
| 1-40           | 6         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3607      | 31.22%  |
| 121-160       | 3441      | 29.78%  |
| 101-120       | 2804      | 24.27%  |
| 161-240       | 800       | 6.92%   |
| More than 240 | 381       | 3.3%    |
| 1-50          | 321       | 2.78%   |
| Unknown       | 199       | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8199      | 74.85%  |
| 2     | 1996      | 18.22%  |
| 0     | 489       | 4.46%   |
| 3     | 244       | 2.23%   |
| 4     | 23        | 0.21%   |
| 5     | 2         | 0.02%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5821      | 35.39%  |
| Intel                             | 5530      | 33.62%  |
| Qualcomm Atheros                  | 1646      | 10.01%  |
| Broadcom                          | 945       | 5.75%   |
| MediaTek                          | 313       | 1.9%    |
| Broadcom Limited                  | 225       | 1.37%   |
| TP-Link                           | 182       | 1.11%   |
| Ralink Technology                 | 163       | 0.99%   |
| Marvell Technology Group          | 150       | 0.91%   |
| Nvidia                            | 130       | 0.79%   |
| Ralink                            | 115       | 0.7%    |
| Samsung Electronics               | 100       | 0.61%   |
| ASIX Electronics                  | 97        | 0.59%   |
| Microsoft                         | 86        | 0.52%   |
| NetGear                           | 61        | 0.37%   |
| Xiaomi                            | 51        | 0.31%   |
| Aquantia                          | 49        | 0.3%    |
| DisplayLink                       | 45        | 0.27%   |
| Qualcomm Atheros Communications   | 43        | 0.26%   |
| Google                            | 43        | 0.26%   |
| InterBiometrics                   | 39        | 0.24%   |
| Dell                              | 39        | 0.24%   |
| Qualcomm                          | 36        | 0.22%   |
| Lenovo                            | 36        | 0.22%   |
| ASUSTek Computer                  | 36        | 0.22%   |
| Sierra Wireless                   | 34        | 0.21%   |
| Huawei Technologies               | 31        | 0.19%   |
| D-Link                            | 31        | 0.19%   |
| Linksys                           | 28        | 0.17%   |
| Ericsson Business Mobile Networks | 24        | 0.15%   |
| JMicron Technology                | 22        | 0.13%   |
| OnePlus Technology (Shenzhen)     | 20        | 0.12%   |
| OPPO Electronics                  | 19        | 0.12%   |
| Motorola PCS                      | 18        | 0.11%   |
| Hewlett-Packard                   | 18        | 0.11%   |
| Edimax Technology                 | 18        | 0.11%   |
| D-Link System                     | 14        | 0.09%   |
| FIBOCOM                           | 10        | 0.06%   |
| Belkin Components                 | 10        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3956      | 20.46%  |
| Intel Wi-Fi 6 AX200                                                    | 812       | 4.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 527       | 2.72%   |
| Intel I211 Gigabit Network Connection                                  | 448       | 2.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 370       | 1.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 348       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 341       | 1.76%   |
| Intel Wireless 8265 / 8275                                             | 339       | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 311       | 1.61%   |
| Intel Wi-Fi 6 AX201                                                    | 253       | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 237       | 1.23%   |
| Intel Wireless 7265                                                    | 223       | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 218       | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 215       | 1.11%   |
| Intel Wireless 7260                                                    | 214       | 1.11%   |
| Intel Ethernet Controller I225-V                                       | 209       | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 203       | 1.05%   |
| Intel Wireless 8260                                                    | 194       | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 190       | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 189       | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 179       | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 176       | 0.91%   |
| Intel Ethernet Connection (2) I219-V                                   | 175       | 0.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 169       | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 167       | 0.86%   |
| Intel Ethernet Connection I217-LM                                      | 150       | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 147       | 0.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 140       | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 138       | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 131       | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 125       | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 120       | 0.62%   |
| Intel Wireless 3165                                                    | 119       | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 118       | 0.61%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 101       | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                          | 95        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 94        | 0.49%   |
| Realtek 802.11ac NIC                                                   | 93        | 0.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 92        | 0.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 91        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4387      | 47.47%  |
| Realtek Semiconductor                 | 1399      | 15.14%  |
| Qualcomm Atheros                      | 1282      | 13.87%  |
| Broadcom                              | 727       | 7.87%   |
| MediaTek                              | 304       | 3.29%   |
| Broadcom Limited                      | 179       | 1.94%   |
| TP-Link                               | 166       | 1.8%    |
| Ralink Technology                     | 163       | 1.76%   |
| Ralink                                | 115       | 1.24%   |
| Microsoft                             | 81        | 0.88%   |
| NetGear                               | 58        | 0.63%   |
| Marvell Technology Group              | 45        | 0.49%   |
| Qualcomm Atheros Communications       | 43        | 0.47%   |
| Sierra Wireless                       | 34        | 0.37%   |
| Dell                                  | 33        | 0.36%   |
| ASUSTek Computer                      | 33        | 0.36%   |
| D-Link                                | 29        | 0.31%   |
| Qualcomm                              | 28        | 0.3%    |
| Linksys                               | 24        | 0.26%   |
| Edimax Technology                     | 18        | 0.19%   |
| FIBOCOM                               | 10        | 0.11%   |
| D-Link System                         | 10        | 0.11%   |
| Belkin Components                     | 10        | 0.11%   |
| AVM                                   | 8         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 8         | 0.09%   |
| Hewlett-Packard                       | 7         | 0.08%   |
| Sitecom Europe                        | 6         | 0.06%   |
| Gemtek                                | 5         | 0.05%   |
| Mercucys                              | 4         | 0.04%   |
| IMC Networks                          | 3         | 0.03%   |
| Accton Technology                     | 3         | 0.03%   |
| ZyDAS                                 | 2         | 0.02%   |
| Wilocity                              | 2         | 0.02%   |
| Wacom                                 | 2         | 0.02%   |
| Samsung Electronics                   | 2         | 0.02%   |
| Qualcomm Technologies                 | 2         | 0.02%   |
| Ovislink                              | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 812       | 8.72%   |
| Intel Wireless 8265 / 8275                                           | 339       | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 311       | 3.34%   |
| Intel Wi-Fi 6 AX201                                                  | 253       | 2.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 237       | 2.55%   |
| Intel Wireless 7265                                                  | 223       | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 218       | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 215       | 2.31%   |
| Intel Wireless 7260                                                  | 214       | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 203       | 2.18%   |
| Intel Wireless 8260                                                  | 194       | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 190       | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 189       | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 179       | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 176       | 1.89%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 169       | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 167       | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 147       | 1.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 140       | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 138       | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 131       | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 125       | 1.34%   |
| Intel Wireless 3165                                                  | 119       | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 118       | 1.27%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 101       | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                        | 95        | 1.02%   |
| Realtek 802.11ac NIC                                                 | 93        | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 92        | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 91        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 89        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 88        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 82        | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 81        | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 79        | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 79        | 0.85%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 77        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 72        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 72        | 0.77%   |
| Intel Wireless 3160                                                  | 71        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                      | 64        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 5252      | 54.23%  |
| Intel                                  | 2604      | 26.89%  |
| Qualcomm Atheros                       | 501       | 5.17%   |
| Broadcom                               | 401       | 4.14%   |
| Nvidia                                 | 130       | 1.34%   |
| Marvell Technology Group               | 105       | 1.08%   |
| Samsung Electronics                    | 98        | 1.01%   |
| ASIX Electronics                       | 97        | 1%      |
| Xiaomi                                 | 51        | 0.53%   |
| Broadcom Limited                       | 50        | 0.52%   |
| Aquantia                               | 49        | 0.51%   |
| DisplayLink                            | 45        | 0.46%   |
| Google                                 | 43        | 0.44%   |
| Lenovo                                 | 36        | 0.37%   |
| Huawei Technologies                    | 27        | 0.28%   |
| JMicron Technology                     | 22        | 0.23%   |
| OPPO Electronics                       | 19        | 0.2%    |
| TP-Link                                | 16        | 0.17%   |
| OnePlus Technology (Shenzhen)          | 16        | 0.17%   |
| Motorola PCS                           | 13        | 0.13%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.09%   |
| Qualcomm                               | 8         | 0.08%   |
| MediaTek                               | 8         | 0.08%   |
| ICS Advent                             | 7         | 0.07%   |
| Apple                                  | 6         | 0.06%   |
| VIA Technologies                       | 5         | 0.05%   |
| Microsoft                              | 5         | 0.05%   |
| Hewlett-Packard                        | 5         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.04%   |
| Mellanox Technologies                  | 4         | 0.04%   |
| Linksys                                | 4         | 0.04%   |
| D-Link System                          | 4         | 0.04%   |
| T & A Mobile Phones                    | 3         | 0.03%   |
| NetGear                                | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.02%   |
| LSI                                    | 2         | 0.02%   |
| D-Link                                 | 2         | 0.02%   |
| American Megatrends                    | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3956      | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 527       | 5.33%   |
| Intel I211 Gigabit Network Connection                                  | 448       | 4.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 370       | 3.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 348       | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 341       | 3.45%   |
| Intel Ethernet Controller I225-V                                       | 209       | 2.11%   |
| Intel Ethernet Connection (2) I219-V                                   | 175       | 1.77%   |
| Intel Ethernet Connection I217-LM                                      | 150       | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 120       | 1.21%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 94        | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 88        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 81        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 79        | 0.8%    |
| Intel Ethernet Connection I219-LM                                      | 76        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 75        | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 68        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                  | 66        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 65        | 0.66%   |
| Nvidia MCP79 Ethernet                                                  | 65        | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 63        | 0.64%   |
| Intel Ethernet Connection I218-LM                                      | 60        | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 59        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 57        | 0.58%   |
| Intel Ethernet Connection I217-V                                       | 57        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                   | 53        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 50        | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 50        | 0.51%   |
| Intel I210 Gigabit Network Connection                                  | 46        | 0.47%   |
| Realtek Killer E2600 GbE Controller                                    | 45        | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                  | 45        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 44        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 41        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 41        | 0.41%   |
| Nvidia MCP61 Ethernet                                                  | 40        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                  | 40        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                                   | 40        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 38        | 0.38%   |
| Intel 82574L Gigabit Network Connection                                | 36        | 0.36%   |
| Intel 82577LM Gigabit Network Connection                               | 34        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 9020      | 50.42%  |
| WiFi     | 8725      | 48.78%  |
| Modem    | 113       | 0.63%   |
| Unknown  | 30        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6786      | 59.8%   |
| Ethernet | 4558      | 40.17%  |
| Unknown  | 3         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5999      | 55.97%  |
| 1     | 4282      | 39.95%  |
| 3     | 258       | 2.41%   |
| 0     | 128       | 1.19%   |
| 4     | 39        | 0.36%   |
| 5     | 8         | 0.07%   |
| 10    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8330      | 76.54%  |
| Yes  | 2553      | 23.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3831      | 51.48%  |
| Realtek Semiconductor           | 632       | 8.49%   |
| Qualcomm Atheros Communications | 553       | 7.43%   |
| Apple                           | 449       | 6.03%   |
| Cambridge Silicon Radio         | 381       | 5.12%   |
| IMC Networks                    | 319       | 4.29%   |
| Broadcom                        | 281       | 3.78%   |
| Lite-On Technology              | 227       | 3.05%   |
| Foxconn / Hon Hai               | 204       | 2.74%   |
| ASUSTek Computer                | 119       | 1.6%    |
| Dell                            | 78        | 1.05%   |
| MediaTek                        | 62        | 0.83%   |
| Marvell Semiconductor           | 48        | 0.64%   |
| Realtek                         | 39        | 0.52%   |
| Ralink                          | 36        | 0.48%   |
| Hewlett-Packard                 | 33        | 0.44%   |
| Toshiba                         | 32        | 0.43%   |
| TP-Link                         | 22        | 0.3%    |
| Foxconn International           | 12        | 0.16%   |
| Dynex                           | 9         | 0.12%   |
| Ralink Technology               | 8         | 0.11%   |
| USI                             | 7         | 0.09%   |
| Alps Electric                   | 7         | 0.09%   |
| Actions                         | 6         | 0.08%   |
| Integrated System Solution      | 5         | 0.07%   |
| Smart Modular Technologies      | 4         | 0.05%   |
| HTC (High Tech Computer)        | 4         | 0.05%   |
| Askey Computer                  | 4         | 0.05%   |
| Taiyo Yuden                     | 3         | 0.04%   |
| SINO WEALTH                     | 3         | 0.04%   |
| Qcom                            | 3         | 0.04%   |
| Opticis                         | 3         | 0.04%   |
| Micro Star International        | 3         | 0.04%   |
| Logitech                        | 3         | 0.04%   |
| Creative Technology             | 3         | 0.04%   |
| Fujitsu                         | 2         | 0.03%   |
| Edimax Technology               | 2         | 0.03%   |
| Conwise Technology              | 2         | 0.03%   |
| Belkin Components               | 2         | 0.03%   |
| Primax Electronics              | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 774       | 10.39%  |
| Intel AX201 Bluetooth                               | 684       | 9.18%   |
| Intel Bluetooth wireless interface                  | 639       | 8.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 501       | 6.73%   |
| Intel Bluetooth Device                              | 479       | 6.43%   |
| Realtek Bluetooth Radio                             | 391       | 5.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 381       | 5.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 299       | 4.01%   |
| Apple Bluetooth Host Controller                     | 224       | 3.01%   |
| Intel AX211 Bluetooth                               | 180       | 2.42%   |
| Intel Wireless-AC 3168 Bluetooth                    | 163       | 2.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 157       | 2.11%   |
| Intel AX210 Bluetooth                               | 131       | 1.76%   |
| Apple Bluetooth USB Host Controller                 | 131       | 1.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 110       | 1.48%   |
| IMC Networks Wireless_Device                        | 106       | 1.42%   |
| IMC Networks Bluetooth Radio                        | 100       | 1.34%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 82        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 78        | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                  | 71        | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 69        | 0.93%   |
| Realtek 802.11ac WLAN Adapter                       | 62        | 0.83%   |
| MediaTek Wireless_Device                            | 62        | 0.83%   |
| IMC Networks Bluetooth Device                       | 59        | 0.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 59        | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 57        | 0.77%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 57        | 0.77%   |
| Lite-On Bluetooth Device                            | 52        | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 51        | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 51        | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 46        | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 45        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 40        | 0.54%   |
| Realtek Bluetooth Radio                             | 39        | 0.52%   |
| Apple Bluetooth HCI                                 | 37        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 36        | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 36        | 0.48%   |
| Marvell Bluetooth and Wireless LAN Composite        | 33        | 0.44%   |
| Dell DW375 Bluetooth Module                         | 28        | 0.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 27        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 7224      | 43.9%   |
| AMD                                             | 3668      | 22.29%  |
| Nvidia                                          | 3470      | 21.09%  |
| C-Media Electronics                             | 289       | 1.76%   |
| Logitech                                        | 173       | 1.05%   |
| Kingston Technology                             | 88        | 0.53%   |
| JMTek                                           | 84        | 0.51%   |
| Razer USA                                       | 82        | 0.5%    |
| Creative Labs                                   | 81        | 0.49%   |
| Corsair                                         | 70        | 0.43%   |
| SteelSeries ApS                                 | 67        | 0.41%   |
| Texas Instruments                               | 64        | 0.39%   |
| Realtek Semiconductor                           | 64        | 0.39%   |
| ASUSTek Computer                                | 60        | 0.36%   |
| Focusrite-Novation                              | 58        | 0.35%   |
| Generalplus Technology                          | 51        | 0.31%   |
| GN Netcom                                       | 46        | 0.28%   |
| Creative Technology                             | 42        | 0.26%   |
| Lenovo                                          | 40        | 0.24%   |
| Blue Microphones                                | 35        | 0.21%   |
| Micro Star International                        | 34        | 0.21%   |
| Sony                                            | 31        | 0.19%   |
| Plantronics                                     | 29        | 0.18%   |
| Apple                                           | 26        | 0.16%   |
| DSEA A/S                                        | 20        | 0.12%   |
| Astro Gaming                                    | 20        | 0.12%   |
| Giga-Byte Technology                            | 19        | 0.12%   |
| Hewlett-Packard                                 | 18        | 0.11%   |
| Tenx Technology                                 | 16        | 0.1%    |
| Samson Technologies                             | 16        | 0.1%    |
| Yamaha                                          | 15        | 0.09%   |
| FiiO Electronics Technology                     | 15        | 0.09%   |
| Valve Software                                  | 14        | 0.09%   |
| Turtle Beach                                    | 13        | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 13        | 0.08%   |
| SAVITECH                                        | 12        | 0.07%   |
| M-Audio                                         | 12        | 0.07%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 10        | 0.06%   |
| Dell                                            | 10        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1279      | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 813       | 4.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 803       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 655       | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 643       | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 582       | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 552       | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 526       | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 380       | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 341       | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 331       | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 325       | 1.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 309       | 1.57%   |
| Intel 8 Series HD Audio Controller                                         | 306       | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 304       | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 302       | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 276       | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 262       | 1.34%   |
| Intel Comet Lake PCH cAVS                                                  | 254       | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 244       | 1.24%   |
| AMD FCH Azalia Controller                                                  | 242       | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 239       | 1.22%   |
| Nvidia GP104 High Definition Audio Controller                              | 230       | 1.17%   |
| Intel Broadwell-U Audio Controller                                         | 226       | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                              | 225       | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 225       | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 223       | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 219       | 1.12%   |
| Intel 200 Series PCH HD Audio                                              | 217       | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 216       | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                              | 215       | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 214       | 1.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 203       | 1.03%   |
| AMD Navi 10 HDMI Audio                                                     | 177       | 0.9%    |
| Nvidia Audio device                                                        | 175       | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 168       | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 165       | 0.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 160       | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 159       | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 155       | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 714       | 23.18%  |
| SK hynix                     | 558       | 18.12%  |
| Micron Technology            | 357       | 11.59%  |
| Kingston                     | 309       | 10.03%  |
| Corsair                      | 226       | 7.34%   |
| Crucial                      | 203       | 6.59%   |
| G.Skill                      | 142       | 4.61%   |
| Unknown                      | 128       | 4.16%   |
| A-DATA Technology            | 66        | 2.14%   |
| Team                         | 48        | 1.56%   |
| Smart                        | 37        | 1.2%    |
| Ramaxel Technology           | 37        | 1.2%    |
| Unknown                      | 30        | 0.97%   |
| Elpida                       | 29        | 0.94%   |
| Goldkey                      | 24        | 0.78%   |
| Neo Forza                    | 22        | 0.71%   |
| Unknown (ABCD)               | 18        | 0.58%   |
| Patriot                      | 15        | 0.49%   |
| Smart Brazil                 | 10        | 0.32%   |
| Nanya Technology             | 10        | 0.32%   |
| Teikon                       | 8         | 0.26%   |
| Apacer                       | 8         | 0.26%   |
| PNY                          | 6         | 0.19%   |
| Avant                        | 6         | 0.19%   |
| Transcend                    | 5         | 0.16%   |
| Timetec                      | 4         | 0.13%   |
| Silicon Power                | 4         | 0.13%   |
| High Bridge                  | 3         | 0.1%    |
| GSkill                       | 3         | 0.1%    |
| GOODRAM                      | 3         | 0.1%    |
| CSX                          | 3         | 0.1%    |
| ChangXin Memory              | 3         | 0.1%    |
| Wodposit                     | 2         | 0.06%   |
| Patriot Memory (PDP Systems) | 2         | 0.06%   |
| Patriot Memory               | 2         | 0.06%   |
| OLOY                         | 2         | 0.06%   |
| Gold Key                     | 2         | 0.06%   |
| AMD                          | 2         | 0.06%   |
| Wilk                         | 1         | 0.03%   |
| Unknown (8A02)               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 54        | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 36        | 1.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 35        | 1.08%   |
| Unknown                                                          | 30        | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 26        | 0.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.71%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 21        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 21        | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.46%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.46%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 15        | 0.46%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.43%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 12        | 0.37%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 12        | 0.37%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.37%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 11        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1741      | 65.21%  |
| DDR3    | 482       | 18.05%  |
| DDR5    | 119       | 4.46%   |
| LPDDR4  | 116       | 4.34%   |
| LPDDR3  | 87        | 3.26%   |
| LPDDR5  | 61        | 2.28%   |
| DDR2    | 28        | 1.05%   |
| Unknown | 20        | 0.75%   |
| SDRAM   | 14        | 0.52%   |
| DDR     | 2         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1646      | 61.01%  |
| DIMM         | 734       | 27.21%  |
| Row Of Chips | 298       | 11.05%  |
| Chip         | 14        | 0.52%   |
| Unknown      | 5         | 0.19%   |
| RIMM         | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1266      | 43.96%  |
| 16384 | 663       | 23.02%  |
| 4096  | 601       | 20.87%  |
| 32768 | 192       | 6.67%   |
| 2048  | 134       | 4.65%   |
| 1024  | 22        | 0.76%   |
| 512   | 2         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 625       | 21.66%  |
| 2667    | 571       | 19.79%  |
| 1600    | 344       | 11.92%  |
| 2400    | 215       | 7.45%   |
| 3600    | 150       | 5.2%    |
| 2133    | 147       | 5.1%    |
| 1333    | 79        | 2.74%   |
| 4800    | 73        | 2.53%   |
| 6400    | 63        | 2.18%   |
| 4267    | 62        | 2.15%   |
| 1867    | 52        | 1.8%    |
| 3733    | 38        | 1.32%   |
| 3266    | 38        | 1.32%   |
| 3800    | 35        | 1.21%   |
| 1334    | 34        | 1.18%   |
| 3000    | 29        | 1.01%   |
| 800     | 23        | 0.8%    |
| 5600    | 22        | 0.76%   |
| 8400    | 21        | 0.73%   |
| 3400    | 21        | 0.73%   |
| 3866    | 20        | 0.69%   |
| 2933    | 19        | 0.66%   |
| 4266    | 16        | 0.55%   |
| 1067    | 15        | 0.52%   |
| 1866    | 14        | 0.49%   |
| 2666    | 13        | 0.45%   |
| 667     | 13        | 0.45%   |
| 6000    | 11        | 0.38%   |
| 3534    | 11        | 0.38%   |
| 1800    | 9         | 0.31%   |
| Unknown | 9         | 0.31%   |
| 3466    | 8         | 0.28%   |
| 5200    | 7         | 0.24%   |
| 4000    | 7         | 0.24%   |
| 3066    | 7         | 0.24%   |
| 3666    | 6         | 0.21%   |
| 2800    | 6         | 0.21%   |
| 4400    | 5         | 0.17%   |
| 3333    | 4         | 0.14%   |
| 2048    | 4         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 66        | 32.51%  |
| Brother Industries    | 37        | 18.23%  |
| Canon                 | 30        | 14.78%  |
| Samsung Electronics   | 22        | 10.84%  |
| Seiko Epson           | 21        | 10.34%  |
| Dymo-CoStar           | 6         | 2.96%   |
| STMicroelectronics    | 3         | 1.48%   |
| Fuji Xerox            | 3         | 1.48%   |
| Xerox                 | 2         | 0.99%   |
| QinHeng Electronics   | 2         | 0.99%   |
| Kyocera               | 2         | 0.99%   |
| Ricoh                 | 1         | 0.49%   |
| Prolific Technology   | 1         | 0.49%   |
| Pantum                | 1         | 0.49%   |
| Oki Data              | 1         | 0.49%   |
| MIIIW                 | 1         | 0.49%   |
| Lexmark International | 1         | 0.49%   |
| ICS Advent            | 1         | 0.49%   |
| Dell                  | 1         | 0.49%   |
| Apple                 | 1         | 0.49%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                               | 5         | 2.45%   |
| Samsung M2020 Series                                      | 4         | 1.96%   |
| Canon PIXMA MX920 Series                                  | 4         | 1.96%   |
| Brother Printer                                           | 4         | 1.96%   |
| Seiko Epson ET-2700 Series                                | 3         | 1.47%   |
| Samsung SCX-3400 Series                                   | 3         | 1.47%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 1.47%   |
| HP LaserJet Professional P 1102w                          | 3         | 1.47%   |
| Dymo-CoStar LabelWriter 450                               | 3         | 1.47%   |
| Canon PIXMA MG2500 Series                                 | 3         | 1.47%   |
| Brother HL-2270DW Laser Printer                           | 3         | 1.47%   |
| Brother HL-2130 series                                    | 3         | 1.47%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.98%   |
| Seiko Epson WF-4830 Series                                | 2         | 0.98%   |
| Seiko Epson WF-3520 Series                                | 2         | 0.98%   |
| Seiko Epson L395 Series                                   | 2         | 0.98%   |
| Seiko Epson L355 Series                                   | 2         | 0.98%   |
| Seiko Epson L3110 Series                                  | 2         | 0.98%   |
| Samsung M2070 Series                                      | 2         | 0.98%   |
| QinHeng CH340S                                            | 2         | 0.98%   |
| HP OfficeJet 3830 series                                  | 2         | 0.98%   |
| HP HP LaserJet M14-M17                                    | 2         | 0.98%   |
| HP ENVY Pro 6400 series                                   | 2         | 0.98%   |
| HP ENVY Photo 6200 series                                 | 2         | 0.98%   |
| HP ENVY 4520 series                                       | 2         | 0.98%   |
| HP ENVY 4500 series                                       | 2         | 0.98%   |
| HP DeskJet F4100 Printer series                           | 2         | 0.98%   |
| HP Deskjet F2280 series                                   | 2         | 0.98%   |
| HP DeskJet 2600 series                                    | 2         | 0.98%   |
| HP Deskjet 2540 series                                    | 2         | 0.98%   |
| HP Deskjet 1000 J110 series                               | 2         | 0.98%   |
| Fuji Xerox DocuPrint CM315/318 z                          | 2         | 0.98%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2         | 0.98%   |
| Brother HL-L3230CDW series                                | 2         | 0.98%   |
| Brother HL-1110 series                                    | 2         | 0.98%   |
| Xerox Phaser 6000B                                        | 1         | 0.49%   |
| Xerox B215                                                | 1         | 0.49%   |
| STMicroelectronics USB Printer P                          | 1         | 0.49%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.49%   |
| Seiko Epson L6160 Series                                  | 1         | 0.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 47.83%  |
| Seiko Epson     | 7         | 30.43%  |
| Hewlett-Packard | 4         | 17.39%  |
| Mustek Systems  | 1         | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson Scanner                                     | 2         | 8.7%    |
| Canon CanoScan N1240U/LiDE 30                           | 2         | 8.7%    |
| Canon CanoScan LiDE 210                                 | 2         | 8.7%    |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 4.35%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.35%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1         | 4.35%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 4.35%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4.35%   |
| HP Scanjet G2710                                        | 1         | 4.35%   |
| HP ScanJet 82x0C                                        | 1         | 4.35%   |
| HP Scanjet 300                                          | 1         | 4.35%   |
| HP ScanJet 2400c                                        | 1         | 4.35%   |
| Canon CanoScan N650U/N656U                              | 1         | 4.35%   |
| Canon CanoScan LiDE 60                                  | 1         | 4.35%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 4.35%   |
| Canon CanoScan LiDE 220                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 200                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 110                                 | 1         | 4.35%   |
| Canon CanoScan 9000F Mark II                            | 1         | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1328      | 20.24%  |
| IMC Networks                           | 621       | 9.47%   |
| Microdia                               | 603       | 9.19%   |
| Realtek Semiconductor                  | 474       | 7.23%   |
| Bison Electronics                      | 448       | 6.83%   |
| Logitech                               | 428       | 6.52%   |
| Apple                                  | 344       | 5.24%   |
| Sunplus Innovation Technology          | 335       | 5.11%   |
| Quanta                                 | 308       | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 192       | 2.93%   |
| Syntek                                 | 161       | 2.45%   |
| Suyin                                  | 144       | 2.2%    |
| Acer                                   | 138       | 2.1%    |
| Lite-On Technology                     | 125       | 1.91%   |
| Luxvisions Innotech Limited            | 120       | 1.83%   |
| Microsoft                              | 77        | 1.17%   |
| Silicon Motion                         | 75        | 1.14%   |
| Samsung Electronics                    | 53        | 0.81%   |
| Sonix Technology                       | 41        | 0.63%   |
| Ricoh                                  | 41        | 0.63%   |
| Alcor Micro                            | 41        | 0.63%   |
| Generalplus Technology                 | 28        | 0.43%   |
| Z-Star Microelectronics                | 23        | 0.35%   |
| SunplusIT                              | 19        | 0.29%   |
| Razer USA                              | 19        | 0.29%   |
| ARC International                      | 18        | 0.27%   |
| ALi                                    | 15        | 0.23%   |
| Primax Electronics                     | 14        | 0.21%   |
| MacroSilicon                           | 14        | 0.21%   |
| Valve Software                         | 13        | 0.2%    |
| Lenovo                                 | 13        | 0.2%    |
| Jieli Technology                       | 13        | 0.2%    |
| Creative Technology                    | 12        | 0.18%   |
| KYE Systems (Mouse Systems)            | 11        | 0.17%   |
| Intel                                  | 11        | 0.17%   |
| Importek                               | 11        | 0.17%   |
| OmniVision Technologies                | 10        | 0.15%   |
| DigiTech                               | 10        | 0.15%   |
| AVerMedia Technologies                 | 10        | 0.15%   |
| Hewlett-Packard                        | 8         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 285       | 4.3%    |
| Chicony integrated camera                           | 281       | 4.24%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 200       | 3.02%   |
| Realtek Integrated_Webcam_HD                        | 181       | 2.73%   |
| IMC Networks Integrated Camera                      | 181       | 2.73%   |
| Chicony HD WebCam                                   | 150       | 2.26%   |
| Bison BisonCam,NB Pro                               | 118       | 1.78%   |
| Syntek Integrated Camera                            | 105       | 1.59%   |
| Apple Built-in iSight                               | 105       | 1.59%   |
| Chicony USB2.0 Camera                               | 104       | 1.57%   |
| Bison Integrated Camera                             | 95        | 1.43%   |
| Sunplus Integrated_Webcam_HD                        | 88        | 1.33%   |
| Logitech HD Pro Webcam C920                         | 88        | 1.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 78        | 1.18%   |
| Logitech Webcam C270                                | 77        | 1.16%   |
| Apple FaceTime HD Camera                            | 74        | 1.12%   |
| Apple FaceTime HD Camera (Built-in)                 | 70        | 1.06%   |
| Bison HD Webcam                                     | 67        | 1.01%   |
| Quanta HD User Facing                               | 64        | 0.97%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 63        | 0.95%   |
| Acer Integrated Camera                              | 54        | 0.82%   |
| Realtek USB Camera                                  | 52        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)             | 50        | 0.75%   |
| Lite-On Integrated Camera                           | 49        | 0.74%   |
| Chicony HP HD Camera                                | 46        | 0.69%   |
| Microdia Webcam Vitade AF                           | 42        | 0.63%   |
| Logitech C922 Pro Stream Webcam                     | 42        | 0.63%   |
| Chicony HP Wide Vision HD Camera                    | 41        | 0.62%   |
| Chicony HD User Facing                              | 41        | 0.62%   |
| Microdia Integrated Webcam                          | 40        | 0.6%    |
| Microdia Laptop_Integrated_Webcam_HD                | 39        | 0.59%   |
| Bison SunplusIT Integrated Camera                   | 38        | 0.57%   |
| Chicony Integrated Camera (1280x720@30)             | 37        | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                        | 36        | 0.54%   |
| Sunplus Asus Webcam                                 | 35        | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 35        | 0.53%   |
| Chicony TOSHIBA Web Camera - HD                     | 34        | 0.51%   |
| Sunplus HD WebCam                                   | 33        | 0.5%    |
| Quanta HP TrueVision HD Camera                      | 33        | 0.5%    |
| Microdia USB 2.0 Camera                             | 33        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 406       | 34.18%  |
| Validity Sensors                   | 333       | 28.03%  |
| Shenzhen Goodix Technology         | 217       | 18.27%  |
| Elan Microelectronics              | 69        | 5.81%   |
| Upek                               | 56        | 4.71%   |
| LighTuning Technology              | 47        | 3.96%   |
| AuthenTec                          | 31        | 2.61%   |
| STMicroelectronics                 | 8         | 0.67%   |
| Realtek USB2.0 Finger Print Bridge | 8         | 0.67%   |
| Focal-systems.Corp                 | 5         | 0.42%   |
| HOLTEK                             | 4         | 0.34%   |
| Samsung Electronics                | 2         | 0.17%   |
| DigitalPersona                     | 2         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 107       | 9.01%   |
| Shenzhen Goodix  Fingerprint Device                                        | 89        | 7.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 76        | 6.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 71        | 5.98%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 64        | 5.39%   |
| Shenzhen Goodix FingerPrint                                                | 52        | 4.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 51        | 4.29%   |
| Elan ELAN:Fingerprint                                                      | 46        | 3.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 43        | 3.62%   |
| Validity Sensors Synaptics WBDI                                            | 30        | 2.53%   |
| Synaptics  WBDI                                                            | 30        | 2.53%   |
| Synaptics TouchPad                                                         | 28        | 2.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 25        | 2.1%    |
| Synaptics WBDI                                                             | 24        | 2.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 23        | 1.94%   |
| Synaptics WBDI Device                                                      | 23        | 1.94%   |
| Synaptics UWP WBDI                                                         | 23        | 1.94%   |
| Validity Sensors Fingerprint scanner                                       | 22        | 1.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 22        | 1.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 21        | 1.77%   |
| Validity Sensors VFS491                                                    | 21        | 1.77%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 1.77%   |
| Elan ELAN:ARM-M4                                                           | 21        | 1.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 1.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 18        | 1.52%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 1.52%   |
| Unknown                                                                    | 17        | 1.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.18%   |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 1.18%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 1.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.01%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 0.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 9         | 0.76%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.67%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 8         | 0.67%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.67%   |
| AuthenTec AES2810                                                          | 8         | 0.67%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 193       | 47.54%  |
| Alcor Micro               | 111       | 27.34%  |
| Upek                      | 29        | 7.14%   |
| O2 Micro                  | 28        | 6.9%    |
| Lenovo                    | 20        | 4.93%   |
| SCM Microsystems          | 7         | 1.72%   |
| OmniKey                   | 5         | 1.23%   |
| Realtek Semiconductor     | 3         | 0.74%   |
| Gemalto (was Gemplus)     | 2         | 0.49%   |
| Chicony Electronics       | 2         | 0.49%   |
| Aladdin Knowledge Systems | 2         | 0.49%   |
| Advanced Card Systems     | 2         | 0.49%   |
| Giesecke & Devrient       | 1         | 0.25%   |
| Clay Logic                | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 109       | 26.85%  |
| Broadcom 5880                                                                | 53        | 13.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 52        | 12.81%  |
| Broadcom 58200                                                               | 43        | 10.59%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 10.34%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 5.91%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 4.93%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.23%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.99%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.74%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.49%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.49%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.49%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.49%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.25%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.25%   |
| OmniKey CardMan 4321                                                         | 1         | 0.25%   |
| OmniKey CardMan 1021                                                         | 1         | 0.25%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.25%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.25%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.25%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.25%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.25%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.25%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7465      | 68.4%   |
| 1     | 2830      | 25.93%  |
| 2     | 530       | 4.86%   |
| 3     | 70        | 0.64%   |
| 4     | 13        | 0.12%   |
| 5     | 4         | 0.04%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1163      | 28.82%  |
| Net/wireless             | 672       | 16.65%  |
| Graphics card            | 669       | 16.58%  |
| Multimedia controller    | 489       | 12.12%  |
| Chipcard                 | 391       | 9.69%   |
| Bluetooth                | 129       | 3.2%    |
| Camera                   | 107       | 2.65%   |
| Communication controller | 71        | 1.76%   |
| Unassigned class         | 67        | 1.66%   |
| Sound                    | 65        | 1.61%   |
| Net/ethernet             | 52        | 1.29%   |
| Storage                  | 46        | 1.14%   |
| Card reader              | 27        | 0.67%   |
| Network                  | 26        | 0.64%   |
| Storage/raid             | 19        | 0.47%   |
| Modem                    | 15        | 0.37%   |
| Storage/ide              | 11        | 0.27%   |
| Storage/nvme             | 6         | 0.15%   |
| Firewire controller      | 4         | 0.1%    |
| Flash memory             | 2         | 0.05%   |
| Dvb card                 | 2         | 0.05%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |


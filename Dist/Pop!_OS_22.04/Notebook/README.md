Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 3673

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5290 2-in-1        | [56d2614671](https://linux-hardware.org/?probe=56d2614671) | May 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [03e53efb87](https://linux-hardware.org/?probe=03e53efb87) | May 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | [2786d2f8f8](https://linux-hardware.org/?probe=2786d2f8f8) | May 08, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [73ee3d2b74](https://linux-hardware.org/?probe=73ee3d2b74) | May 08, 2024 |
| Lenovo        | ThinkPad T420s 417032U      | [e6839a3d70](https://linux-hardware.org/?probe=e6839a3d70) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [9122522638](https://linux-hardware.org/?probe=9122522638) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3064d4fb1f](https://linux-hardware.org/?probe=3064d4fb1f) | May 07, 2024 |
| System76      | Gazelle                     | [fbe88df732](https://linux-hardware.org/?probe=fbe88df732) | May 07, 2024 |
| System76      | Darter Pro                  | [e6da92d97e](https://linux-hardware.org/?probe=e6da92d97e) | May 06, 2024 |
| Dell          | XPS 13 7390                 | [3132f4ff24](https://linux-hardware.org/?probe=3132f4ff24) | May 06, 2024 |
| ASUSTek       | X550CC                      | [db900f1cd1](https://linux-hardware.org/?probe=db900f1cd1) | May 05, 2024 |
| Lenovo        | ThinkPad T420s 41732AU      | [be5eeed803](https://linux-hardware.org/?probe=be5eeed803) | May 05, 2024 |
| ASUSTek       | GL753VD                     | [05c21dbea4](https://linux-hardware.org/?probe=05c21dbea4) | May 05, 2024 |
| Apple         | MacBookAir6,2               | [672e653276](https://linux-hardware.org/?probe=672e653276) | May 05, 2024 |
| System76      | Oryx Pro                    | [6d05743481](https://linux-hardware.org/?probe=6d05743481) | May 05, 2024 |
| Getac         | S410                        | [a05cbbe577](https://linux-hardware.org/?probe=a05cbbe577) | May 04, 2024 |
| Dell          | Latitude 5290 2-in-1        | [2e9e3f6434](https://linux-hardware.org/?probe=2e9e3f6434) | May 04, 2024 |
| Dell          | Inspiron 5520               | [bb83948d6a](https://linux-hardware.org/?probe=bb83948d6a) | May 04, 2024 |
| HP            | Victus by Gaming Laptop ... | [1f42d0fe27](https://linux-hardware.org/?probe=1f42d0fe27) | May 04, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0839696375](https://linux-hardware.org/?probe=0839696375) | May 04, 2024 |
| Dell          | XPS 13 9310                 | [868dd4d0bd](https://linux-hardware.org/?probe=868dd4d0bd) | May 03, 2024 |
| Dell          | XPS 13 9340                 | [4446c73008](https://linux-hardware.org/?probe=4446c73008) | May 03, 2024 |
| Dell          | Latitude E6330              | [02c85088bc](https://linux-hardware.org/?probe=02c85088bc) | May 03, 2024 |
| Alienware     | M14xR1                      | [501de2a1ec](https://linux-hardware.org/?probe=501de2a1ec) | May 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c23a3238c0](https://linux-hardware.org/?probe=c23a3238c0) | May 02, 2024 |
| HP            | Pavilion dv7                | [d191e30bf7](https://linux-hardware.org/?probe=d191e30bf7) | May 01, 2024 |
| ASUSTek       | UX430UNR                    | [5712b06d98](https://linux-hardware.org/?probe=5712b06d98) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | [a032f50d3f](https://linux-hardware.org/?probe=a032f50d3f) | Apr 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [701927cf4d](https://linux-hardware.org/?probe=701927cf4d) | Apr 30, 2024 |
| Alienware     | M14xR1                      | [dc1461c536](https://linux-hardware.org/?probe=dc1461c536) | Apr 29, 2024 |
| MSI           | Katana 15 B12VGK            | [c8e4cb337e](https://linux-hardware.org/?probe=c8e4cb337e) | Apr 29, 2024 |
| ASUSTek       | X451CA                      | [30d9b5f4ee](https://linux-hardware.org/?probe=30d9b5f4ee) | Apr 28, 2024 |
| Dell          | Inspiron 16 7610            | [2427197c56](https://linux-hardware.org/?probe=2427197c56) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [b024eb05d1](https://linux-hardware.org/?probe=b024eb05d1) | Apr 28, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [3fbd54c33d](https://linux-hardware.org/?probe=3fbd54c33d) | Apr 27, 2024 |
| Dell          | Precision 5680              | [95bc853549](https://linux-hardware.org/?probe=95bc853549) | Apr 27, 2024 |
| Medion        | Akoya E6227                 | [76bfce53f4](https://linux-hardware.org/?probe=76bfce53f4) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [6d6b67129d](https://linux-hardware.org/?probe=6d6b67129d) | Apr 26, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ce253ebd01](https://linux-hardware.org/?probe=ce253ebd01) | Apr 26, 2024 |
| HP            | EliteBook 745 G6            | [5354993cb7](https://linux-hardware.org/?probe=5354993cb7) | Apr 25, 2024 |
| HP            | EliteBook 745 G6            | [3b5f41d264](https://linux-hardware.org/?probe=3b5f41d264) | Apr 25, 2024 |
| HP            | ENVY 15                     | [20cb7a828b](https://linux-hardware.org/?probe=20cb7a828b) | Apr 24, 2024 |
| Dell          | Inspiron N4050              | [cbcc357ce6](https://linux-hardware.org/?probe=cbcc357ce6) | Apr 24, 2024 |
| ASRock        | FM2A68M-HD+                 | [74967df09a](https://linux-hardware.org/?probe=74967df09a) | Apr 23, 2024 |
| Apple         | MacBookPro8,2               | [965595373d](https://linux-hardware.org/?probe=965595373d) | Apr 23, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [5453cfa265](https://linux-hardware.org/?probe=5453cfa265) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | [ecc36cef1b](https://linux-hardware.org/?probe=ecc36cef1b) | Apr 23, 2024 |
| MSI           | GE62VR 6RF                  | [68b99dae1a](https://linux-hardware.org/?probe=68b99dae1a) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | [5a88798ad6](https://linux-hardware.org/?probe=5a88798ad6) | Apr 22, 2024 |
| ASUSTek       | ROG Strix SCAR 18 G834JZ... | [28007aea7c](https://linux-hardware.org/?probe=28007aea7c) | Apr 22, 2024 |
| Dell          | XPS 13 9340                 | [5b25704805](https://linux-hardware.org/?probe=5b25704805) | Apr 22, 2024 |
| System76      | Lemur Pro                   | [3b7243efe7](https://linux-hardware.org/?probe=3b7243efe7) | Apr 21, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [63baa07920](https://linux-hardware.org/?probe=63baa07920) | Apr 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ee83ed7c12](https://linux-hardware.org/?probe=ee83ed7c12) | Apr 20, 2024 |
| Apple         | MacBookPro9,2               | [f8fa58a83b](https://linux-hardware.org/?probe=f8fa58a83b) | Apr 19, 2024 |
| Apple         | MacBookPro9,2               | [8dde47a60c](https://linux-hardware.org/?probe=8dde47a60c) | Apr 19, 2024 |
| Google        | Morphius                    | [a8361bc931](https://linux-hardware.org/?probe=a8361bc931) | Apr 19, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5bcf08b4b0](https://linux-hardware.org/?probe=5bcf08b4b0) | Apr 19, 2024 |
| HP            | OMEN by Latpop 16-c0100n... | [0ee401b99c](https://linux-hardware.org/?probe=0ee401b99c) | Apr 19, 2024 |
| Toshiba       | Satellite L755D             | [47d623ed44](https://linux-hardware.org/?probe=47d623ed44) | Apr 19, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8f4cd3f89d](https://linux-hardware.org/?probe=8f4cd3f89d) | Apr 19, 2024 |
| Dell          | Precision 5680              | [165f135e49](https://linux-hardware.org/?probe=165f135e49) | Apr 18, 2024 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [7b5eee5473](https://linux-hardware.org/?probe=7b5eee5473) | Apr 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bcbc28897f](https://linux-hardware.org/?probe=bcbc28897f) | Apr 17, 2024 |
| Dell          | XPS 15 7590                 | [5b510f5ccd](https://linux-hardware.org/?probe=5b510f5ccd) | Apr 17, 2024 |
| Acer          | Nitro AN515-45              | [224785342d](https://linux-hardware.org/?probe=224785342d) | Apr 17, 2024 |
| ASUSTek       | UX305CA                     | [0793f271ed](https://linux-hardware.org/?probe=0793f271ed) | Apr 17, 2024 |
| HP            | 255 G8 Notebook PC          | [9945f26789](https://linux-hardware.org/?probe=9945f26789) | Apr 17, 2024 |
| Samsung       | 940X3G/930X3G               | [7ae2ace4e3](https://linux-hardware.org/?probe=7ae2ace4e3) | Apr 17, 2024 |
| Samsung       | 940X3G/930X3G               | [ebcb51ed9c](https://linux-hardware.org/?probe=ebcb51ed9c) | Apr 16, 2024 |
| Apple         | MacBookAir4,1               | [fd0c46bab2](https://linux-hardware.org/?probe=fd0c46bab2) | Apr 16, 2024 |
| Dell          | Inspiron 5547               | [088cb90432](https://linux-hardware.org/?probe=088cb90432) | Apr 16, 2024 |
| Acer          | Aspire E1-572G              | [96b786aa6f](https://linux-hardware.org/?probe=96b786aa6f) | Apr 15, 2024 |
| Dell          | Vostro 3400                 | [ddb98658ed](https://linux-hardware.org/?probe=ddb98658ed) | Apr 15, 2024 |
| Acer          | Aspire 5742G                | [91d047cef5](https://linux-hardware.org/?probe=91d047cef5) | Apr 15, 2024 |
| HUAWEI        | BOHB-WAX9                   | [e27137024f](https://linux-hardware.org/?probe=e27137024f) | Apr 15, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [0e240e7a70](https://linux-hardware.org/?probe=0e240e7a70) | Apr 14, 2024 |
| Acer          | Nitro AN515-51              | [46d9c6bc98](https://linux-hardware.org/?probe=46d9c6bc98) | Apr 14, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [b120a1a8eb](https://linux-hardware.org/?probe=b120a1a8eb) | Apr 13, 2024 |
| System76      | Lemur Pro                   | [7c9425e33a](https://linux-hardware.org/?probe=7c9425e33a) | Apr 13, 2024 |
| Dell          | Latitude E5520              | [0f03f7a01f](https://linux-hardware.org/?probe=0f03f7a01f) | Apr 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [858512aecf](https://linux-hardware.org/?probe=858512aecf) | Apr 12, 2024 |
| HP            | Victus by Gaming Laptop ... | [7ee4741505](https://linux-hardware.org/?probe=7ee4741505) | Apr 12, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3007... | [696b2e9290](https://linux-hardware.org/?probe=696b2e9290) | Apr 12, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3007... | [7d473643db](https://linux-hardware.org/?probe=7d473643db) | Apr 12, 2024 |
| System76      | Oryx Pro                    | [0204db931b](https://linux-hardware.org/?probe=0204db931b) | Apr 12, 2024 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [e72d400eb3](https://linux-hardware.org/?probe=e72d400eb3) | Apr 11, 2024 |
| Acer          | Aspire A515-44              | [bcff49116b](https://linux-hardware.org/?probe=bcff49116b) | Apr 11, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [589fd95069](https://linux-hardware.org/?probe=589fd95069) | Apr 11, 2024 |
| MSI           | Modern 15 A5M               | [df536172a9](https://linux-hardware.org/?probe=df536172a9) | Apr 10, 2024 |
| System76      | Oryx Pro                    | [ea8426e115](https://linux-hardware.org/?probe=ea8426e115) | Apr 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2b7f101b88](https://linux-hardware.org/?probe=2b7f101b88) | Apr 10, 2024 |
| HP            | EliteBook 8560p             | [e9b9656231](https://linux-hardware.org/?probe=e9b9656231) | Apr 09, 2024 |
| HP            | 250 G4                      | [8f21075772](https://linux-hardware.org/?probe=8f21075772) | Apr 09, 2024 |
| Lenovo        | ThinkPad T470 20HEA0TLUS    | [fac79c8b6b](https://linux-hardware.org/?probe=fac79c8b6b) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [03de80c7da](https://linux-hardware.org/?probe=03de80c7da) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7b9ff3d8a5](https://linux-hardware.org/?probe=7b9ff3d8a5) | Apr 08, 2024 |
| Dell          | Latitude E7240              | [a323cf8e2e](https://linux-hardware.org/?probe=a323cf8e2e) | Apr 08, 2024 |
| Alienware     | m15 R7                      | [5b8340f20c](https://linux-hardware.org/?probe=5b8340f20c) | Apr 08, 2024 |
| Alienware     | m15 R7                      | [2b7f9cd75d](https://linux-hardware.org/?probe=2b7f9cd75d) | Apr 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [471a22d2d2](https://linux-hardware.org/?probe=471a22d2d2) | Apr 08, 2024 |
| HP            | 15                          | [6cb916bc6b](https://linux-hardware.org/?probe=6cb916bc6b) | Apr 08, 2024 |
| MSI           | Titan GT77HX 13VI           | [81cf9688bd](https://linux-hardware.org/?probe=81cf9688bd) | Apr 08, 2024 |
| HP            | 15                          | [c3dd3707a8](https://linux-hardware.org/?probe=c3dd3707a8) | Apr 08, 2024 |
| Dell          | Latitude 5401               | [50c9a92ed4](https://linux-hardware.org/?probe=50c9a92ed4) | Apr 07, 2024 |
| Acer          | Swift SF314-71              | [071a57efd2](https://linux-hardware.org/?probe=071a57efd2) | Apr 07, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [25ee9e6b9c](https://linux-hardware.org/?probe=25ee9e6b9c) | Apr 07, 2024 |
| HP            | 255 G8 Notebook PC          | [85dd650b73](https://linux-hardware.org/?probe=85dd650b73) | Apr 07, 2024 |
| Acer          | Nitro AN515-52              | [b36f589241](https://linux-hardware.org/?probe=b36f589241) | Apr 06, 2024 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [75363d665b](https://linux-hardware.org/?probe=75363d665b) | Apr 06, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [3242172c38](https://linux-hardware.org/?probe=3242172c38) | Apr 06, 2024 |
| HP            | Stream 11 Pro G5            | [60dbf47721](https://linux-hardware.org/?probe=60dbf47721) | Apr 06, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [20ceba9415](https://linux-hardware.org/?probe=20ceba9415) | Apr 06, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [cf5333f4e5](https://linux-hardware.org/?probe=cf5333f4e5) | Apr 06, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [9afed2e851](https://linux-hardware.org/?probe=9afed2e851) | Apr 06, 2024 |
| HP            | EliteBook 8730w             | [342f90f8c1](https://linux-hardware.org/?probe=342f90f8c1) | Apr 05, 2024 |
| HP            | EliteBook 8730w             | [b4c4b71cdb](https://linux-hardware.org/?probe=b4c4b71cdb) | Apr 05, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [bf584291d2](https://linux-hardware.org/?probe=bf584291d2) | Apr 04, 2024 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [bbc6cfb633](https://linux-hardware.org/?probe=bbc6cfb633) | Apr 04, 2024 |
| HP            | EliteBook 840 G1            | [ed6e28b85c](https://linux-hardware.org/?probe=ed6e28b85c) | Apr 04, 2024 |
| MSI           | Titan GT77HX 13VI           | [c6da8fe194](https://linux-hardware.org/?probe=c6da8fe194) | Apr 02, 2024 |
| Acer          | TravelMate P277-MG          | [49a90af61e](https://linux-hardware.org/?probe=49a90af61e) | Apr 02, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [0855016a44](https://linux-hardware.org/?probe=0855016a44) | Apr 01, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [43a3819af7](https://linux-hardware.org/?probe=43a3819af7) | Apr 01, 2024 |
| Dell          | Latitude E6430              | [bf9cac92e7](https://linux-hardware.org/?probe=bf9cac92e7) | Apr 01, 2024 |
| GPD           | G1619-04                    | [4d8878864a](https://linux-hardware.org/?probe=4d8878864a) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [2a00b77a69](https://linux-hardware.org/?probe=2a00b77a69) | Apr 01, 2024 |
| Acer          | Aspire A315-35              | [554a38529a](https://linux-hardware.org/?probe=554a38529a) | Mar 31, 2024 |
| Dell          | Latitude E6430              | [c871f1007a](https://linux-hardware.org/?probe=c871f1007a) | Mar 31, 2024 |
| Apple         | MacBookPro7,1               | [a02628f1b4](https://linux-hardware.org/?probe=a02628f1b4) | Mar 31, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | [c19f043267](https://linux-hardware.org/?probe=c19f043267) | Mar 31, 2024 |
| HP            | 250 G4                      | [fbf0b206e8](https://linux-hardware.org/?probe=fbf0b206e8) | Mar 31, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [449d0ad45b](https://linux-hardware.org/?probe=449d0ad45b) | Mar 31, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [77d2d8ef3e](https://linux-hardware.org/?probe=77d2d8ef3e) | Mar 31, 2024 |
| Apple         | MacBookAir7,2               | [fd278af3a5](https://linux-hardware.org/?probe=fd278af3a5) | Mar 31, 2024 |
| Timi          | TM1604                      | [9ef2ec37c2](https://linux-hardware.org/?probe=9ef2ec37c2) | Mar 29, 2024 |
| Timi          | TM1604                      | [ec2ab8fb5f](https://linux-hardware.org/?probe=ec2ab8fb5f) | Mar 29, 2024 |
| Acer          | Swift SFX14-51G             | [a0aaa7eb1d](https://linux-hardware.org/?probe=a0aaa7eb1d) | Mar 29, 2024 |
| ASUSTek       | ProArt Studiobook H7604J... | [ce5acdd8b0](https://linux-hardware.org/?probe=ce5acdd8b0) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [90614a5f0b](https://linux-hardware.org/?probe=90614a5f0b) | Mar 28, 2024 |
| Acer          | Aspire 4349                 | [8bf51e5557](https://linux-hardware.org/?probe=8bf51e5557) | Mar 28, 2024 |
| HP            | Victus by Gaming Laptop ... | [d93e2bd101](https://linux-hardware.org/?probe=d93e2bd101) | Mar 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [951f003b12](https://linux-hardware.org/?probe=951f003b12) | Mar 28, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [c1a3cee107](https://linux-hardware.org/?probe=c1a3cee107) | Mar 28, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [deae5b6cdf](https://linux-hardware.org/?probe=deae5b6cdf) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [602d79d663](https://linux-hardware.org/?probe=602d79d663) | Mar 27, 2024 |
| Acer          | Aspire A515-57G             | [95c573af0a](https://linux-hardware.org/?probe=95c573af0a) | Mar 27, 2024 |
| Dell          | Inspiron 5520               | [27255ef603](https://linux-hardware.org/?probe=27255ef603) | Mar 26, 2024 |
| Dell          | Inspiron 1440               | [e7bae8d9bc](https://linux-hardware.org/?probe=e7bae8d9bc) | Mar 26, 2024 |
| ASUSTek       | G750JZA                     | [12d8540af3](https://linux-hardware.org/?probe=12d8540af3) | Mar 26, 2024 |
| HP            | ENVY 15                     | [11821b80b7](https://linux-hardware.org/?probe=11821b80b7) | Mar 26, 2024 |
| Apple         | MacBookAir4,2               | [d31e841f4d](https://linux-hardware.org/?probe=d31e841f4d) | Mar 25, 2024 |
| Alienware     | m15 R4                      | [3f0488b05c](https://linux-hardware.org/?probe=3f0488b05c) | Mar 25, 2024 |
| System76      | Bonobo WS                   | [856360e11c](https://linux-hardware.org/?probe=856360e11c) | Mar 25, 2024 |
| Acer          | Aspire 5755G                | [4aa12cd64e](https://linux-hardware.org/?probe=4aa12cd64e) | Mar 24, 2024 |
| Google        | Markarth                    | [9987cda5ae](https://linux-hardware.org/?probe=9987cda5ae) | Mar 24, 2024 |
| Lenovo        | G510 20238                  | [b63a7b1490](https://linux-hardware.org/?probe=b63a7b1490) | Mar 24, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [fad6108f0a](https://linux-hardware.org/?probe=fad6108f0a) | Mar 24, 2024 |
| System76      | Gazelle                     | [a2b4d889db](https://linux-hardware.org/?probe=a2b4d889db) | Mar 24, 2024 |
| Alienware     | m15 R7                      | [27cc6ca1d6](https://linux-hardware.org/?probe=27cc6ca1d6) | Mar 24, 2024 |
| Dell          | Vostro 1015                 | [5cea7dba17](https://linux-hardware.org/?probe=5cea7dba17) | Mar 23, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [7fc01abc25](https://linux-hardware.org/?probe=7fc01abc25) | Mar 23, 2024 |
| HUAWEI        | BOHB-WAX9                   | [90d0e194f9](https://linux-hardware.org/?probe=90d0e194f9) | Mar 23, 2024 |
| MSI           | Cyborg 15 A12VE             | [012a9393ab](https://linux-hardware.org/?probe=012a9393ab) | Mar 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [a0855ed46b](https://linux-hardware.org/?probe=a0855ed46b) | Mar 22, 2024 |
| HP            | Victus by Gaming Laptop ... | [899cb71147](https://linux-hardware.org/?probe=899cb71147) | Mar 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2c74228344](https://linux-hardware.org/?probe=2c74228344) | Mar 22, 2024 |
| Dell          | Latitude E7240              | [a295e64d94](https://linux-hardware.org/?probe=a295e64d94) | Mar 21, 2024 |
| Dell          | Inspiron 5558               | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| HUAWEI        | BOHB-WAX9                   | [eecdc4a970](https://linux-hardware.org/?probe=eecdc4a970) | Mar 21, 2024 |
| HUAWEI        | BOHB-WAX9                   | [0a1b9c732b](https://linux-hardware.org/?probe=0a1b9c732b) | Mar 21, 2024 |
| Lenovo        | ThinkPad X395 20NMS13801    | [bf71f2099b](https://linux-hardware.org/?probe=bf71f2099b) | Mar 21, 2024 |
| Dell          | Precision M4700             | [212d29f26d](https://linux-hardware.org/?probe=212d29f26d) | Mar 21, 2024 |
| HP            | 255 G8 Notebook PC          | [0293382f9b](https://linux-hardware.org/?probe=0293382f9b) | Mar 21, 2024 |
| Dell          | Latitude E6540              | [c3883595b9](https://linux-hardware.org/?probe=c3883595b9) | Mar 21, 2024 |
| MSI           | Cyborg 15 A12VE             | [e0dce5359f](https://linux-hardware.org/?probe=e0dce5359f) | Mar 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | [b912e786a3](https://linux-hardware.org/?probe=b912e786a3) | Mar 20, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | [a06517f205](https://linux-hardware.org/?probe=a06517f205) | Mar 20, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [0e0638700d](https://linux-hardware.org/?probe=0e0638700d) | Mar 20, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [e8c3803d3c](https://linux-hardware.org/?probe=e8c3803d3c) | Mar 20, 2024 |
| Dell          | Latitude 5410               | [291ea4843c](https://linux-hardware.org/?probe=291ea4843c) | Mar 20, 2024 |
| Acer          | Aspire A315-59              | [6c38602470](https://linux-hardware.org/?probe=6c38602470) | Mar 19, 2024 |
| HONOR         | GLO-GXXX                    | [aa0a3c2273](https://linux-hardware.org/?probe=aa0a3c2273) | Mar 19, 2024 |
| HONOR         | GLO-GXXX                    | [e6fbe7ffad](https://linux-hardware.org/?probe=e6fbe7ffad) | Mar 19, 2024 |
| HUAWEI        | KLVL-WXXW                   | [7400d40886](https://linux-hardware.org/?probe=7400d40886) | Mar 19, 2024 |
| HUAWEI        | KLVD-WXX9                   | [f8a39666b9](https://linux-hardware.org/?probe=f8a39666b9) | Mar 19, 2024 |
| HUAWEI        | KLVD-WXX9                   | [74127be2ca](https://linux-hardware.org/?probe=74127be2ca) | Mar 19, 2024 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [3bef14d11e](https://linux-hardware.org/?probe=3bef14d11e) | Mar 19, 2024 |
| Dell          | Latitude 7440               | [143c9f9828](https://linux-hardware.org/?probe=143c9f9828) | Mar 19, 2024 |
| HP            | EliteBook 840 14 inch G9... | [eaea13606f](https://linux-hardware.org/?probe=eaea13606f) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8SCLH0... | [a568c4313e](https://linux-hardware.org/?probe=a568c4313e) | Mar 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402NU... | [10d62d48f9](https://linux-hardware.org/?probe=10d62d48f9) | Mar 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2d61b43821](https://linux-hardware.org/?probe=2d61b43821) | Mar 18, 2024 |
| Notebook      | N15_N17RD1                  | [7bf6fa9d9f](https://linux-hardware.org/?probe=7bf6fa9d9f) | Mar 18, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [2cc34ee9da](https://linux-hardware.org/?probe=2cc34ee9da) | Mar 18, 2024 |
| Lenovo        | Legion 7 15IMH05 81YT       | [6e83554006](https://linux-hardware.org/?probe=6e83554006) | Mar 17, 2024 |
| Lenovo        | Y520-15IKBM 80YY            | [aae3b4bf83](https://linux-hardware.org/?probe=aae3b4bf83) | Mar 17, 2024 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [72eb92fb02](https://linux-hardware.org/?probe=72eb92fb02) | Mar 16, 2024 |
| Lenovo        | ThinkPad T480s 20L8SCLH0... | [fd91f6e0b8](https://linux-hardware.org/?probe=fd91f6e0b8) | Mar 15, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [0ba8678964](https://linux-hardware.org/?probe=0ba8678964) | Mar 15, 2024 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [d1bf96e346](https://linux-hardware.org/?probe=d1bf96e346) | Mar 14, 2024 |
| Lenovo        | ThinkPad T420 4236PFG       | [66167283a7](https://linux-hardware.org/?probe=66167283a7) | Mar 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [37260aa51d](https://linux-hardware.org/?probe=37260aa51d) | Mar 14, 2024 |
| Jumper        | EZbook                      | [65469deb97](https://linux-hardware.org/?probe=65469deb97) | Mar 14, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [d2921f8721](https://linux-hardware.org/?probe=d2921f8721) | Mar 13, 2024 |
| Dell          | Inspiron 5575               | [982b876f87](https://linux-hardware.org/?probe=982b876f87) | Mar 13, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6a41c6be0e](https://linux-hardware.org/?probe=6a41c6be0e) | Mar 13, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [3eb6a86b95](https://linux-hardware.org/?probe=3eb6a86b95) | Mar 13, 2024 |
| Dell          | XPS 15 9530                 | [4cfd0ba254](https://linux-hardware.org/?probe=4cfd0ba254) | Mar 13, 2024 |
| Google        | Gallop                      | [eeaa5535f7](https://linux-hardware.org/?probe=eeaa5535f7) | Mar 12, 2024 |
| HP            | ProBook 470 G3              | [7acbeb9e50](https://linux-hardware.org/?probe=7acbeb9e50) | Mar 12, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [006a9be33e](https://linux-hardware.org/?probe=006a9be33e) | Mar 12, 2024 |
| Acer          | Nitro AN515-45              | [d5d941f35c](https://linux-hardware.org/?probe=d5d941f35c) | Mar 12, 2024 |
| Dell          | Latitude 5420               | [e49cabfe78](https://linux-hardware.org/?probe=e49cabfe78) | Mar 12, 2024 |
| Dell          | G7 7588                     | [201e08795e](https://linux-hardware.org/?probe=201e08795e) | Mar 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [66ebc0d790](https://linux-hardware.org/?probe=66ebc0d790) | Mar 11, 2024 |
| Dell          | Vostro 15 5510              | [1635f8ee88](https://linux-hardware.org/?probe=1635f8ee88) | Mar 11, 2024 |
| Apple         | MacBookAir7,2               | [03dbb01a57](https://linux-hardware.org/?probe=03dbb01a57) | Mar 11, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [695773aa7b](https://linux-hardware.org/?probe=695773aa7b) | Mar 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [a56ff930d5](https://linux-hardware.org/?probe=a56ff930d5) | Mar 10, 2024 |
| Dell          | Latitude 7490               | [93e3272d83](https://linux-hardware.org/?probe=93e3272d83) | Mar 10, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [174fa8b213](https://linux-hardware.org/?probe=174fa8b213) | Mar 09, 2024 |
| Dell          | Latitude 7490               | [d8c5dd5832](https://linux-hardware.org/?probe=d8c5dd5832) | Mar 09, 2024 |
| eMachines     | E525                        | [4a4a1ac342](https://linux-hardware.org/?probe=4a4a1ac342) | Mar 09, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [35cdd04e44](https://linux-hardware.org/?probe=35cdd04e44) | Mar 08, 2024 |
| HP            | Laptop 15s-eq0xxx           | [e4a401d044](https://linux-hardware.org/?probe=e4a401d044) | Mar 08, 2024 |
| Dell          | Latitude 5530               | [474a88cccf](https://linux-hardware.org/?probe=474a88cccf) | Mar 08, 2024 |
| Dell          | Inspiron 5520               | [ded3e0cf33](https://linux-hardware.org/?probe=ded3e0cf33) | Mar 08, 2024 |
| System76      | Gazelle                     | [c054444856](https://linux-hardware.org/?probe=c054444856) | Mar 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [439a24ca9f](https://linux-hardware.org/?probe=439a24ca9f) | Mar 07, 2024 |
| Dell          | Latitude 5530               | [252c53438e](https://linux-hardware.org/?probe=252c53438e) | Mar 07, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [635244de96](https://linux-hardware.org/?probe=635244de96) | Mar 07, 2024 |
| HP            | EliteBook 840 G2            | [431439414a](https://linux-hardware.org/?probe=431439414a) | Mar 07, 2024 |
| HP            | EliteBook 840 G2            | [571cf278dd](https://linux-hardware.org/?probe=571cf278dd) | Mar 07, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [bb4c0ce2be](https://linux-hardware.org/?probe=bb4c0ce2be) | Mar 06, 2024 |
| Lenovo        | ThinkPad E15 20RD0014RT     | [b12b855825](https://linux-hardware.org/?probe=b12b855825) | Mar 06, 2024 |
| HP            | ProBook 650 G1              | [994590f6a8](https://linux-hardware.org/?probe=994590f6a8) | Mar 06, 2024 |
| HP            | EliteBook 840 14 inch G1... | [b62ec8f9a0](https://linux-hardware.org/?probe=b62ec8f9a0) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [1446f9eae8](https://linux-hardware.org/?probe=1446f9eae8) | Mar 05, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bc08a4f316](https://linux-hardware.org/?probe=bc08a4f316) | Mar 05, 2024 |
| Alienware     | M14xR1                      | [67cc7d7e63](https://linux-hardware.org/?probe=67cc7d7e63) | Mar 05, 2024 |
| Dell          | G7 7500                     | [89b81d9c37](https://linux-hardware.org/?probe=89b81d9c37) | Mar 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [b11673c68a](https://linux-hardware.org/?probe=b11673c68a) | Mar 05, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [141c46ed9d](https://linux-hardware.org/?probe=141c46ed9d) | Mar 05, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [3b0efc2689](https://linux-hardware.org/?probe=3b0efc2689) | Mar 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c3d8b404f8](https://linux-hardware.org/?probe=c3d8b404f8) | Mar 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ce218789c2](https://linux-hardware.org/?probe=ce218789c2) | Mar 04, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [2f64045bb9](https://linux-hardware.org/?probe=2f64045bb9) | Mar 04, 2024 |
| Acer          | Nitro AN515-57              | [d65faae98f](https://linux-hardware.org/?probe=d65faae98f) | Mar 03, 2024 |
| ASUSTek       | GL552VX                     | [01ea0912c3](https://linux-hardware.org/?probe=01ea0912c3) | Mar 03, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b957a4b5d8](https://linux-hardware.org/?probe=b957a4b5d8) | Mar 03, 2024 |
| Alienware     | M14xR1                      | [5b5b4ae985](https://linux-hardware.org/?probe=5b5b4ae985) | Mar 03, 2024 |
| Dell          | XPS 15 9570                 | [73bd3cf050](https://linux-hardware.org/?probe=73bd3cf050) | Mar 03, 2024 |
| Dell          | Inspiron 1525               | [7749349961](https://linux-hardware.org/?probe=7749349961) | Mar 02, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [67a9619322](https://linux-hardware.org/?probe=67a9619322) | Mar 02, 2024 |
| System76      | Pangolin                    | [a130fc52f6](https://linux-hardware.org/?probe=a130fc52f6) | Mar 02, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [78090262bb](https://linux-hardware.org/?probe=78090262bb) | Mar 02, 2024 |
| System76      | Oryx Pro                    | [6f389be12b](https://linux-hardware.org/?probe=6f389be12b) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [cda628788e](https://linux-hardware.org/?probe=cda628788e) | Mar 01, 2024 |
| HP            | Laptop 15-dw0xxx            | [6e720badd3](https://linux-hardware.org/?probe=6e720badd3) | Mar 01, 2024 |
| Apple         | MacBookPro11,3              | [d418108f92](https://linux-hardware.org/?probe=d418108f92) | Feb 29, 2024 |
| Lenovo        | ThinkPad T420 4236BD5       | [470be089f8](https://linux-hardware.org/?probe=470be089f8) | Feb 29, 2024 |
| HP            | Laptop 14s-dq0xxx           | [07e47bd9aa](https://linux-hardware.org/?probe=07e47bd9aa) | Feb 29, 2024 |
| Acer          | Nitro AN515-57              | [ecfd2b2c9f](https://linux-hardware.org/?probe=ecfd2b2c9f) | Feb 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bccc7e9b25](https://linux-hardware.org/?probe=bccc7e9b25) | Feb 27, 2024 |
| ASUSTek       | N53SN                       | [c628351d6c](https://linux-hardware.org/?probe=c628351d6c) | Feb 27, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [df29939277](https://linux-hardware.org/?probe=df29939277) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [3ea80caf07](https://linux-hardware.org/?probe=3ea80caf07) | Feb 27, 2024 |
| Casper        | NIRVANA NOTEBOOK            | [19a2ccc504](https://linux-hardware.org/?probe=19a2ccc504) | Feb 27, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ac48e41763](https://linux-hardware.org/?probe=ac48e41763) | Feb 27, 2024 |
| Dell          | Inspiron 5547               | [a7e7b853e8](https://linux-hardware.org/?probe=a7e7b853e8) | Feb 27, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1817f5af30](https://linux-hardware.org/?probe=1817f5af30) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0ef3ee0033](https://linux-hardware.org/?probe=0ef3ee0033) | Feb 27, 2024 |
| Acer          | Aspire V3-372               | [fcd3114d4b](https://linux-hardware.org/?probe=fcd3114d4b) | Feb 26, 2024 |
| Dell          | Latitude 5300               | [8ab46e0ae3](https://linux-hardware.org/?probe=8ab46e0ae3) | Feb 26, 2024 |
| TrekStor      | Notebook Slim S130          | [534a53e131](https://linux-hardware.org/?probe=534a53e131) | Feb 26, 2024 |
| Apple         | MacBookPro8,2               | [2ddd148d6c](https://linux-hardware.org/?probe=2ddd148d6c) | Feb 26, 2024 |
| ASUSTek       | Strix GL704GW_GL704GW       | [4f5f9307d6](https://linux-hardware.org/?probe=4f5f9307d6) | Feb 25, 2024 |
| Sony          | VPCCA2S0E                   | [ded9134c14](https://linux-hardware.org/?probe=ded9134c14) | Feb 25, 2024 |
| Sony          | VPCCA2S0E                   | [360e87199c](https://linux-hardware.org/?probe=360e87199c) | Feb 25, 2024 |
| TrekStor      | Notebook Slim S130          | [829f6953a7](https://linux-hardware.org/?probe=829f6953a7) | Feb 25, 2024 |
| Dell          | Inspiron 7559               | [678e86bdeb](https://linux-hardware.org/?probe=678e86bdeb) | Feb 25, 2024 |
| Apple         | MacBookAir3,2               | [82df38cf02](https://linux-hardware.org/?probe=82df38cf02) | Feb 24, 2024 |
| HP            | ProBook 4730s               | [9441592753](https://linux-hardware.org/?probe=9441592753) | Feb 24, 2024 |
| HP            | ProBook 4730s               | [558fc0a500](https://linux-hardware.org/?probe=558fc0a500) | Feb 24, 2024 |
| Dell          | Precision 3571              | [4392bfe153](https://linux-hardware.org/?probe=4392bfe153) | Feb 24, 2024 |
| Acer          | Swift SFX14-41G             | [edd37fc93e](https://linux-hardware.org/?probe=edd37fc93e) | Feb 24, 2024 |
| HP            | EliteBook 840 14 inch G9... | [be154598ff](https://linux-hardware.org/?probe=be154598ff) | Feb 23, 2024 |
| HP            | EliteBook 850 G6            | [7ed2cffcae](https://linux-hardware.org/?probe=7ed2cffcae) | Feb 23, 2024 |
| Dell          | Precision 5550              | [f362deda15](https://linux-hardware.org/?probe=f362deda15) | Feb 22, 2024 |
| Dell          | Latitude E5420              | [910bc98f57](https://linux-hardware.org/?probe=910bc98f57) | Feb 21, 2024 |
| Dell          | Precision M4800             | [60660b2530](https://linux-hardware.org/?probe=60660b2530) | Feb 21, 2024 |
| Dell          | Latitude 5580               | [b83380f87b](https://linux-hardware.org/?probe=b83380f87b) | Feb 21, 2024 |
| Dream Mach... | Gaming Laptop               | [fb169a7c4d](https://linux-hardware.org/?probe=fb169a7c4d) | Feb 20, 2024 |
| Razer         | Blade 14 - RZ09-0370        | [119689a507](https://linux-hardware.org/?probe=119689a507) | Feb 20, 2024 |
| Dell          | Latitude 7480               | [99c8492288](https://linux-hardware.org/?probe=99c8492288) | Feb 20, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [801c073182](https://linux-hardware.org/?probe=801c073182) | Feb 20, 2024 |
| Acer          | Aspire A315-24P             | [a5ad93fa0a](https://linux-hardware.org/?probe=a5ad93fa0a) | Feb 20, 2024 |
| Acer          | Aspire A315-24P             | [08191524c7](https://linux-hardware.org/?probe=08191524c7) | Feb 20, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [caf3ea0d9a](https://linux-hardware.org/?probe=caf3ea0d9a) | Feb 20, 2024 |
| Acer          | SF314-71-50E8               | [109256318a](https://linux-hardware.org/?probe=109256318a) | Feb 20, 2024 |
| Apple         | MacBookPro8,1               | [f8d09630be](https://linux-hardware.org/?probe=f8d09630be) | Feb 20, 2024 |
| Apple         | MacBookPro8,1               | [5eb44e20c3](https://linux-hardware.org/?probe=5eb44e20c3) | Feb 20, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [f0a5c0c659](https://linux-hardware.org/?probe=f0a5c0c659) | Feb 19, 2024 |
| Dell          | Latitude E7250              | [4dbb95d349](https://linux-hardware.org/?probe=4dbb95d349) | Feb 19, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [748c41cfa2](https://linux-hardware.org/?probe=748c41cfa2) | Feb 19, 2024 |
| Acer          | SF314-71-50E8               | [b05150cb04](https://linux-hardware.org/?probe=b05150cb04) | Feb 19, 2024 |
| HP            | ZBook Firefly 15.6 inch ... | [d0562f4f40](https://linux-hardware.org/?probe=d0562f4f40) | Feb 19, 2024 |
| Pegatron      | B34C                        | [a062b68bf6](https://linux-hardware.org/?probe=a062b68bf6) | Feb 18, 2024 |
| Acer          | Aspire A515-56              | [11f162f567](https://linux-hardware.org/?probe=11f162f567) | Feb 18, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [1a618047be](https://linux-hardware.org/?probe=1a618047be) | Feb 18, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [a7cb58e0b9](https://linux-hardware.org/?probe=a7cb58e0b9) | Feb 18, 2024 |
| System76      | Gazelle                     | [6e2b31138f](https://linux-hardware.org/?probe=6e2b31138f) | Feb 18, 2024 |
| Dell          | XPS 12 9Q23                 | [7246414ea4](https://linux-hardware.org/?probe=7246414ea4) | Feb 18, 2024 |
| Unknown       | Unknown                     | [df466668e4](https://linux-hardware.org/?probe=df466668e4) | Feb 17, 2024 |
| MSI           | GE72 6QC                    | [bf8edb1354](https://linux-hardware.org/?probe=bf8edb1354) | Feb 17, 2024 |
| Acer          | SF314-71-50E8               | [8c9f92e873](https://linux-hardware.org/?probe=8c9f92e873) | Feb 17, 2024 |
| ASUSTek       | K95VJ                       | [c82a491d01](https://linux-hardware.org/?probe=c82a491d01) | Feb 16, 2024 |
| Acer          | Aspire S3                   | [015a6bdb09](https://linux-hardware.org/?probe=015a6bdb09) | Feb 16, 2024 |
| HP            | Pavilion dv6                | [27bd273fa1](https://linux-hardware.org/?probe=27bd273fa1) | Feb 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [176496db32](https://linux-hardware.org/?probe=176496db32) | Feb 16, 2024 |
| Apple         | MacBookAir7,2               | [17be6d540f](https://linux-hardware.org/?probe=17be6d540f) | Feb 16, 2024 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [c98ffdb659](https://linux-hardware.org/?probe=c98ffdb659) | Feb 16, 2024 |
| Dell          | Precision 7510              | [c6c77a8fc8](https://linux-hardware.org/?probe=c6c77a8fc8) | Feb 16, 2024 |
| HP            | Pavilion dv6                | [fd84d867f4](https://linux-hardware.org/?probe=fd84d867f4) | Feb 15, 2024 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [8e7c6becd2](https://linux-hardware.org/?probe=8e7c6becd2) | Feb 14, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [cef87c0391](https://linux-hardware.org/?probe=cef87c0391) | Feb 14, 2024 |
| Acer          | Aspire A515-56              | [8145ab17cc](https://linux-hardware.org/?probe=8145ab17cc) | Feb 14, 2024 |
| Dell          | XPS 15 9510                 | [25f5e2c229](https://linux-hardware.org/?probe=25f5e2c229) | Feb 12, 2024 |
| Dell          | XPS 15 9510                 | [1e8eb3e275](https://linux-hardware.org/?probe=1e8eb3e275) | Feb 12, 2024 |
| Casper        | NIRVANA NOTEBOOK            | [6fb885473c](https://linux-hardware.org/?probe=6fb885473c) | Feb 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [07b16ebca5](https://linux-hardware.org/?probe=07b16ebca5) | Feb 11, 2024 |
| Dell          | Latitude E7270              | [cd13d3c338](https://linux-hardware.org/?probe=cd13d3c338) | Feb 11, 2024 |
| Acer          | Aspire A514-53              | [70b16c69f0](https://linux-hardware.org/?probe=70b16c69f0) | Feb 10, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGC... | [8567f0b4d1](https://linux-hardware.org/?probe=8567f0b4d1) | Feb 10, 2024 |
| HP            | EliteBook 845 14 inch G9... | [bc3902b1d1](https://linux-hardware.org/?probe=bc3902b1d1) | Feb 09, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | [b87e3aded5](https://linux-hardware.org/?probe=b87e3aded5) | Feb 09, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | [0d1cdf2ae8](https://linux-hardware.org/?probe=0d1cdf2ae8) | Feb 09, 2024 |
| Casper        | NIRVANA NOTEBOOK            | [5ecacd2214](https://linux-hardware.org/?probe=5ecacd2214) | Feb 09, 2024 |
| Dell          | Inspiron 3558               | [76eb2071c4](https://linux-hardware.org/?probe=76eb2071c4) | Feb 09, 2024 |
| Digibras      | NH4CU03                     | [7f77d98ba4](https://linux-hardware.org/?probe=7f77d98ba4) | Feb 09, 2024 |
| HP            | ProBook 6450b               | [423b15dea2](https://linux-hardware.org/?probe=423b15dea2) | Feb 09, 2024 |
| Acer          | Aspire 6530G                | [a52bd02af6](https://linux-hardware.org/?probe=a52bd02af6) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [34d8638e1b](https://linux-hardware.org/?probe=34d8638e1b) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [0d70b31ec1](https://linux-hardware.org/?probe=0d70b31ec1) | Feb 08, 2024 |
| Gigabyte      | AORUS 17H BXF               | [4146726cc9](https://linux-hardware.org/?probe=4146726cc9) | Feb 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [661b2efa7b](https://linux-hardware.org/?probe=661b2efa7b) | Feb 08, 2024 |
| HP            | Laptop 14-dq2xxx            | [f7a3dcea60](https://linux-hardware.org/?probe=f7a3dcea60) | Feb 07, 2024 |
| HP            | Laptop 14-dq2xxx            | [b38c4f6d04](https://linux-hardware.org/?probe=b38c4f6d04) | Feb 07, 2024 |
| System76      | Pangolin                    | [c5d7319f7c](https://linux-hardware.org/?probe=c5d7319f7c) | Feb 07, 2024 |
| Apple         | MacBookAir6,2               | [692854bb38](https://linux-hardware.org/?probe=692854bb38) | Feb 07, 2024 |
| Acer          | Aspire A315-510P            | [4c44ba2081](https://linux-hardware.org/?probe=4c44ba2081) | Feb 07, 2024 |
| Lenovo        | ThinkPad P50 20EQS2GL00     | [ebd3065955](https://linux-hardware.org/?probe=ebd3065955) | Feb 06, 2024 |
| MSI           | GF63 Thin 10SC              | [0e9a586cf0](https://linux-hardware.org/?probe=0e9a586cf0) | Feb 06, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | [a820fbd52d](https://linux-hardware.org/?probe=a820fbd52d) | Feb 06, 2024 |
| Acer          | SF314-71-50E8               | [0d44d5cc60](https://linux-hardware.org/?probe=0d44d5cc60) | Feb 06, 2024 |
| ASUSTek       | X555LB                      | [5f19079461](https://linux-hardware.org/?probe=5f19079461) | Feb 06, 2024 |
| Lenovo        | G40-45 80E1                 | [0f58d5d24e](https://linux-hardware.org/?probe=0f58d5d24e) | Feb 06, 2024 |
| Acer          | Aspire A315-510P            | [e90f84656d](https://linux-hardware.org/?probe=e90f84656d) | Feb 06, 2024 |
| Apple         | MacBookPro5,1               | [965e14a38d](https://linux-hardware.org/?probe=965e14a38d) | Feb 06, 2024 |
| Apple         | MacBookPro5,1               | [0f0883d52e](https://linux-hardware.org/?probe=0f0883d52e) | Feb 06, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [bfccd0df6e](https://linux-hardware.org/?probe=bfccd0df6e) | Feb 06, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [50d7951466](https://linux-hardware.org/?probe=50d7951466) | Feb 05, 2024 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [8700336241](https://linux-hardware.org/?probe=8700336241) | Feb 05, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a688c4fc6e](https://linux-hardware.org/?probe=a688c4fc6e) | Feb 05, 2024 |
| Apple         | MacBookAir6,2               | [ca4e5e8f49](https://linux-hardware.org/?probe=ca4e5e8f49) | Feb 05, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [708ee3c7ac](https://linux-hardware.org/?probe=708ee3c7ac) | Feb 05, 2024 |
| Dell          | Inspiron 3558               | [ddb4c7f91a](https://linux-hardware.org/?probe=ddb4c7f91a) | Feb 05, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [d83dd7b361](https://linux-hardware.org/?probe=d83dd7b361) | Feb 05, 2024 |
| Dell          | Precision 7710              | [93bdd1915c](https://linux-hardware.org/?probe=93bdd1915c) | Feb 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [34e9a5b730](https://linux-hardware.org/?probe=34e9a5b730) | Feb 04, 2024 |
| System76      | Galago Pro                  | [a6e796d4a9](https://linux-hardware.org/?probe=a6e796d4a9) | Feb 04, 2024 |
| Dell          | XPS 9320                    | [74d4b364f8](https://linux-hardware.org/?probe=74d4b364f8) | Feb 03, 2024 |
| Dell          | Precision 3550              | [780747a577](https://linux-hardware.org/?probe=780747a577) | Feb 03, 2024 |
| Lenovo        | Y50-70 20378                | [b3a0560548](https://linux-hardware.org/?probe=b3a0560548) | Feb 03, 2024 |
| Lenovo        | Y50-70 20378                | [67951a8bdd](https://linux-hardware.org/?probe=67951a8bdd) | Feb 03, 2024 |
| HP            | ZBook 15 G4                 | [72ea56fdbe](https://linux-hardware.org/?probe=72ea56fdbe) | Feb 03, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [671c2add93](https://linux-hardware.org/?probe=671c2add93) | Feb 03, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [2994236383](https://linux-hardware.org/?probe=2994236383) | Feb 03, 2024 |
| HP            | Pavilion g6                 | [795109303b](https://linux-hardware.org/?probe=795109303b) | Feb 02, 2024 |
| Dell          | G7 7588                     | [fdc746ce61](https://linux-hardware.org/?probe=fdc746ce61) | Feb 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [6d6e6af46b](https://linux-hardware.org/?probe=6d6e6af46b) | Feb 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f659cc07fc](https://linux-hardware.org/?probe=f659cc07fc) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | [bb6dd71048](https://linux-hardware.org/?probe=bb6dd71048) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7adc6ac4b3](https://linux-hardware.org/?probe=7adc6ac4b3) | Feb 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e94976b6d9](https://linux-hardware.org/?probe=e94976b6d9) | Feb 01, 2024 |
| Samsung       | 750XFH                      | [47d573ccf5](https://linux-hardware.org/?probe=47d573ccf5) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [4e6e527f34](https://linux-hardware.org/?probe=4e6e527f34) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [16a348ccd1](https://linux-hardware.org/?probe=16a348ccd1) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [fc52040fc1](https://linux-hardware.org/?probe=fc52040fc1) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f833c48d57](https://linux-hardware.org/?probe=f833c48d57) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [bc7890c0fe](https://linux-hardware.org/?probe=bc7890c0fe) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ef62bb8257](https://linux-hardware.org/?probe=ef62bb8257) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [841cef0b98](https://linux-hardware.org/?probe=841cef0b98) | Feb 01, 2024 |
| HP            | Pavilion dv6                | [9d58677c2a](https://linux-hardware.org/?probe=9d58677c2a) | Feb 01, 2024 |
| ASUSTek       | X556UQK                     | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| Lenovo        | V330-14ARR 81B1             | [5dcee96cdb](https://linux-hardware.org/?probe=5dcee96cdb) | Jan 31, 2024 |
| Hot Pepper... | HPPMC10                     | [1bfdadd09f](https://linux-hardware.org/?probe=1bfdadd09f) | Jan 30, 2024 |
| Apple         | MacBook9,1                  | [e81979cbdf](https://linux-hardware.org/?probe=e81979cbdf) | Jan 29, 2024 |
| HP            | ProBook 4540s               | [ba6e31a8d3](https://linux-hardware.org/?probe=ba6e31a8d3) | Jan 29, 2024 |
| Acer          | Nitro AN515-58              | [dda1c0dfa9](https://linux-hardware.org/?probe=dda1c0dfa9) | Jan 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0bba02c4c8](https://linux-hardware.org/?probe=0bba02c4c8) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9fcbf2b096](https://linux-hardware.org/?probe=9fcbf2b096) | Jan 29, 2024 |
| Dell          | Inspiron 3558               | [c347f95f5e](https://linux-hardware.org/?probe=c347f95f5e) | Jan 28, 2024 |
| ASUSTek       | X541UJ                      | [14f153b6c9](https://linux-hardware.org/?probe=14f153b6c9) | Jan 28, 2024 |
| HP            | Laptop 15-db0xxx            | [077619fc48](https://linux-hardware.org/?probe=077619fc48) | Jan 27, 2024 |
| Acer          | Aspire 6530G                | [cd71356945](https://linux-hardware.org/?probe=cd71356945) | Jan 26, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [43bf0c55e8](https://linux-hardware.org/?probe=43bf0c55e8) | Jan 26, 2024 |
| MSI           | GF65 Thin 9SEXR             | [5be9da4fbd](https://linux-hardware.org/?probe=5be9da4fbd) | Jan 26, 2024 |
| Lenovo        | G460 0677                   | [d4624cb524](https://linux-hardware.org/?probe=d4624cb524) | Jan 26, 2024 |
| Dell          | XPS 15 9570                 | [4b9ba374ee](https://linux-hardware.org/?probe=4b9ba374ee) | Jan 25, 2024 |
| Acer          | Aspire VX5-591G             | [3e5671c66a](https://linux-hardware.org/?probe=3e5671c66a) | Jan 24, 2024 |
| MSI           | P65 Creator 9SE             | [863ad9098e](https://linux-hardware.org/?probe=863ad9098e) | Jan 24, 2024 |
| HP            | ProBook 4530s               | [db169567f6](https://linux-hardware.org/?probe=db169567f6) | Jan 24, 2024 |
| Toshiba       | Satellite C55-C             | [3f59e64e0e](https://linux-hardware.org/?probe=3f59e64e0e) | Jan 24, 2024 |
| System76      | Oryx Pro                    | [cb490beb63](https://linux-hardware.org/?probe=cb490beb63) | Jan 24, 2024 |
| Acer          | Nitro AN515-58              | [d195c1f908](https://linux-hardware.org/?probe=d195c1f908) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [5d754d0510](https://linux-hardware.org/?probe=5d754d0510) | Jan 23, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [2f77e5be01](https://linux-hardware.org/?probe=2f77e5be01) | Jan 22, 2024 |
| Dell          | Inspiron 5490               | [e879f5dd00](https://linux-hardware.org/?probe=e879f5dd00) | Jan 22, 2024 |
| HP            | Laptop 14-fq1xxx            | [dcb0ce6ffa](https://linux-hardware.org/?probe=dcb0ce6ffa) | Jan 22, 2024 |
| HP            | Notebook                    | [efbf2736f3](https://linux-hardware.org/?probe=efbf2736f3) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [9fd92c9632](https://linux-hardware.org/?probe=9fd92c9632) | Jan 20, 2024 |
| Acer          | Nitro AN515-57              | [e9423fb2cd](https://linux-hardware.org/?probe=e9423fb2cd) | Jan 19, 2024 |
| HP            | ProBook 450 G1              | [09fe6e6426](https://linux-hardware.org/?probe=09fe6e6426) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [35c8f1855d](https://linux-hardware.org/?probe=35c8f1855d) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e555a2c32c](https://linux-hardware.org/?probe=e555a2c32c) | Jan 19, 2024 |
| HP            | ENVY TS 15                  | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| ASUSTek       | N55SL                       | [a6c913a5e2](https://linux-hardware.org/?probe=a6c913a5e2) | Jan 19, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Apple         | MacBookAir6,2               | [8f90ab1bfb](https://linux-hardware.org/?probe=8f90ab1bfb) | Jan 18, 2024 |
| Acer          | Swift SFX14-41G             | [612d6f9b0e](https://linux-hardware.org/?probe=612d6f9b0e) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [048d450a50](https://linux-hardware.org/?probe=048d450a50) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [1364b82d7c](https://linux-hardware.org/?probe=1364b82d7c) | Jan 17, 2024 |
| HP            | EliteBook 840 G3            | [0b16d083fa](https://linux-hardware.org/?probe=0b16d083fa) | Jan 17, 2024 |
| ASRock        | FM2A68M-HD+                 | [8ba2ab423f](https://linux-hardware.org/?probe=8ba2ab423f) | Jan 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [dd442d6fef](https://linux-hardware.org/?probe=dd442d6fef) | Jan 17, 2024 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [3cdf937732](https://linux-hardware.org/?probe=3cdf937732) | Jan 17, 2024 |
| Compaq        | 430                         | [a8dc50fedd](https://linux-hardware.org/?probe=a8dc50fedd) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d124634554](https://linux-hardware.org/?probe=d124634554) | Jan 15, 2024 |
| Acer          | Swift SF315-52G             | [b1df864ab5](https://linux-hardware.org/?probe=b1df864ab5) | Jan 15, 2024 |
| ASUSTek       | X550JK                      | [1e70a82b32](https://linux-hardware.org/?probe=1e70a82b32) | Jan 15, 2024 |
| System76      | Pangolin                    | [bb8766a339](https://linux-hardware.org/?probe=bb8766a339) | Jan 15, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6ede7a7cc8](https://linux-hardware.org/?probe=6ede7a7cc8) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [19467f2a4d](https://linux-hardware.org/?probe=19467f2a4d) | Jan 14, 2024 |
| Acer          | Aspire 5560                 | [fcc49083ec](https://linux-hardware.org/?probe=fcc49083ec) | Jan 14, 2024 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [f1b5487574](https://linux-hardware.org/?probe=f1b5487574) | Jan 13, 2024 |
| Samsung       | 550XED                      | [a9cdc1201c](https://linux-hardware.org/?probe=a9cdc1201c) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | [60f88b1f3f](https://linux-hardware.org/?probe=60f88b1f3f) | Jan 13, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [3d70c9ce2f](https://linux-hardware.org/?probe=3d70c9ce2f) | Jan 13, 2024 |
| Dell          | Inspiron 5447               | [12ec54ffaf](https://linux-hardware.org/?probe=12ec54ffaf) | Jan 12, 2024 |
| Lenovo        | ThinkPad X260 20F5S4A901    | [75e671c163](https://linux-hardware.org/?probe=75e671c163) | Jan 12, 2024 |
| System76      | Adder WS                    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [9066b38bfc](https://linux-hardware.org/?probe=9066b38bfc) | Jan 11, 2024 |
| Acer          | Swift SF314-54              | [c947abcab4](https://linux-hardware.org/?probe=c947abcab4) | Jan 11, 2024 |
| ASUSTek       | G73Jh                       | [9f34698cbf](https://linux-hardware.org/?probe=9f34698cbf) | Jan 11, 2024 |
| Dell          | Latitude E7240              | [5661525290](https://linux-hardware.org/?probe=5661525290) | Jan 11, 2024 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [5e75e6b11a](https://linux-hardware.org/?probe=5e75e6b11a) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6462a9e611](https://linux-hardware.org/?probe=6462a9e611) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [145f213442](https://linux-hardware.org/?probe=145f213442) | Jan 10, 2024 |
| ASUSTek       | N55SL                       | [b2c935edc3](https://linux-hardware.org/?probe=b2c935edc3) | Jan 10, 2024 |
| ASUSTek       | X550JK                      | [53f8040dbd](https://linux-hardware.org/?probe=53f8040dbd) | Jan 10, 2024 |
| Dell          | Precision 7510              | [8902e4fb7f](https://linux-hardware.org/?probe=8902e4fb7f) | Jan 10, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3002... | [374798f039](https://linux-hardware.org/?probe=374798f039) | Jan 09, 2024 |
| Unknown       | Unknown                     | [76fb94009e](https://linux-hardware.org/?probe=76fb94009e) | Jan 09, 2024 |
| Acer          | Aspire A715-51G             | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [b85af627bb](https://linux-hardware.org/?probe=b85af627bb) | Jan 09, 2024 |
| Dell          | Precision 5480              | [17ef519eb9](https://linux-hardware.org/?probe=17ef519eb9) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8107ad3adc](https://linux-hardware.org/?probe=8107ad3adc) | Jan 09, 2024 |
| Dell          | Precision 5560              | [947f10a53a](https://linux-hardware.org/?probe=947f10a53a) | Jan 09, 2024 |
| Apple         | MacBookPro11,4              | [a0e28b82f1](https://linux-hardware.org/?probe=a0e28b82f1) | Jan 08, 2024 |
| MSI           | P65 Creator 9SE             | [33a2ceb954](https://linux-hardware.org/?probe=33a2ceb954) | Jan 08, 2024 |
| Dell          | Vostro 5402                 | [4c1d546ae0](https://linux-hardware.org/?probe=4c1d546ae0) | Jan 08, 2024 |
| Lenovo        | ThinkPad X220 4291RD2       | [dc1b40ea6f](https://linux-hardware.org/?probe=dc1b40ea6f) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | [2068373a62](https://linux-hardware.org/?probe=2068373a62) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HUAWEI        | CREM-WXX9                   | [29104c358b](https://linux-hardware.org/?probe=29104c358b) | Jan 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [040fa6a049](https://linux-hardware.org/?probe=040fa6a049) | Jan 07, 2024 |
| HP            | EliteBook 850 G6            | [605ea399c5](https://linux-hardware.org/?probe=605ea399c5) | Jan 07, 2024 |
| Apple         | MacBookPro8,1               | [cdc7802fc3](https://linux-hardware.org/?probe=cdc7802fc3) | Jan 07, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | [8363cb44ef](https://linux-hardware.org/?probe=8363cb44ef) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | [fcf858ac50](https://linux-hardware.org/?probe=fcf858ac50) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | [a10fc58132](https://linux-hardware.org/?probe=a10fc58132) | Jan 06, 2024 |
| Dell          | XPS 15 9570                 | [8ca8b318eb](https://linux-hardware.org/?probe=8ca8b318eb) | Jan 06, 2024 |
| Lenovo        | ThinkPad X390 20Q1S7RB00    | [cfcb27d0b7](https://linux-hardware.org/?probe=cfcb27d0b7) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ae18260ba9](https://linux-hardware.org/?probe=ae18260ba9) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| Apple         | MacBookPro8,1               | [a620a3be8d](https://linux-hardware.org/?probe=a620a3be8d) | Jan 06, 2024 |
| Dell          | Latitude 3420               | [39d522ead5](https://linux-hardware.org/?probe=39d522ead5) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| Unknown       | Unknown                     | [d135277737](https://linux-hardware.org/?probe=d135277737) | Jan 05, 2024 |
| HP            | 83E9                        | [5794eaa509](https://linux-hardware.org/?probe=5794eaa509) | Jan 05, 2024 |
| HP            | 83E9                        | [ca6565530d](https://linux-hardware.org/?probe=ca6565530d) | Jan 05, 2024 |
| Unknown       | Unknown                     | [5e7209bd1a](https://linux-hardware.org/?probe=5e7209bd1a) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [1973735eec](https://linux-hardware.org/?probe=1973735eec) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Apple         | MacBookPro8,1               | [1593858ec2](https://linux-hardware.org/?probe=1593858ec2) | Jan 04, 2024 |
| Dell          | Latitude E5270              | [c0a4dbd80f](https://linux-hardware.org/?probe=c0a4dbd80f) | Jan 03, 2024 |
| Dell          | Vostro 3500                 | [70cf9e639e](https://linux-hardware.org/?probe=70cf9e639e) | Jan 03, 2024 |
| Lenovo        | Z50-75 80EC                 | [0e5397d3f1](https://linux-hardware.org/?probe=0e5397d3f1) | Jan 03, 2024 |
| HP            | OMEN by Laptop 15-dh0xxx    | [cd96de915f](https://linux-hardware.org/?probe=cd96de915f) | Jan 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [d29c58fd8a](https://linux-hardware.org/?probe=d29c58fd8a) | Jan 03, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [95995dd66f](https://linux-hardware.org/?probe=95995dd66f) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [8fe843e69b](https://linux-hardware.org/?probe=8fe843e69b) | Jan 02, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [09d807a864](https://linux-hardware.org/?probe=09d807a864) | Jan 02, 2024 |
| Acer          | SF314-71-50E8               | [b74d7acff4](https://linux-hardware.org/?probe=b74d7acff4) | Jan 02, 2024 |
| ASUSTek       | G75VX                       | [7f8494ffcf](https://linux-hardware.org/?probe=7f8494ffcf) | Jan 02, 2024 |
| Dell          | Latitude 5540               | [96e1aad010](https://linux-hardware.org/?probe=96e1aad010) | Jan 02, 2024 |
| System76      | Oryx Pro                    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| Google        | Delbin                      | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| Acer          | SF314-71-50E8               | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | G73Jh                       | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| ASUSTek       | K75VM                       | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| Dell          | Latitude E6520              | [634e14ff4c](https://linux-hardware.org/?probe=634e14ff4c) | Dec 25, 2023 |
| MicroByte     | ezbook                      | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| PC Special... | N150CU                      | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| System76      | Serval WS                   | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Dell          | Latitude E6430s             | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | ProBook 4535s               | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Dell          | Latitude E7450              | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [801f62b573](https://linux-hardware.org/?probe=801f62b573) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d16bd87505](https://linux-hardware.org/?probe=d16bd87505) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7f32922e8f](https://linux-hardware.org/?probe=7f32922e8f) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Apple         | MacBookAir7,2               | [d227968843](https://linux-hardware.org/?probe=d227968843) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| realme        | RMNBXXXX                    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Apple         | MacBookPro11,1              | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| System76      | Lemur Pro                   | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| ASUSTek       | X542URR                     | [3e42bedcd3](https://linux-hardware.org/?probe=3e42bedcd3) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| Razer         | Blade                       | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e7d15edec4](https://linux-hardware.org/?probe=e7d15edec4) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| ASUSTek       | G53SX                       | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | [944218c6ec](https://linux-hardware.org/?probe=944218c6ec) | Dec 08, 2023 |
| Dell          | Inspiron 1525               | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | [2499101d89](https://linux-hardware.org/?probe=2499101d89) | Dec 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| HP            | ProBook 640 G5              | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [48a8d668d9](https://linux-hardware.org/?probe=48a8d668d9) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Acer          | Aspire A515-44G             | [7e41d52591](https://linux-hardware.org/?probe=7e41d52591) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| MSI           | Modern 14 B4MW              | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| Dell          | Latitude E7240              | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| Notebook      | NJ50_70CU                   | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| Acer          | Aspire A314-22              | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| HP            | Victus by Gaming Laptop ... | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| Dell          | Latitude 5420               | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| Dell          | Precision 3550              | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Dell          | Precision M4700             | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | GL553VW                     | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| HP            | ProBook 4540s               | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| HP            | Pavilion 14                 | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Dell          | Inspiron 5547               | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| Dell          | Latitude E6330              | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| HP            | 250 G8 Notebook PC          | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| Dell          | Precision 5680              | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Dell          | Precision 5680              | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| Apple         | MacBookPro8,1               | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ProBook 4540s               | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| Dell          | XPS 9320                    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| Acer          | Aspire V3-471G              | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| HP            | ProBook 4540s               | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| System76      | Adder WS                    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| ASUSTek       | X55U                        | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision 7720              | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| Unknown       | Unknown                     | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| System76      | Lemur Pro                   | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| Google        | Edgar                       | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| Google        | Edgar                       | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [1946d2a10c](https://linux-hardware.org/?probe=1946d2a10c) | Nov 11, 2023 |
| HP            | G42                         | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Dell          | Latitude E5420              | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| Notebook      | PA70Hx                      | [f22d74d5eb](https://linux-hardware.org/?probe=f22d74d5eb) | Nov 11, 2023 |
| HP            | Pavilion g7                 | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [93d7b2bcdc](https://linux-hardware.org/?probe=93d7b2bcdc) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [03b4295585](https://linux-hardware.org/?probe=03b4295585) | Nov 09, 2023 |
| Dell          | Inspiron 1525               | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [c048c3b791](https://linux-hardware.org/?probe=c048c3b791) | Nov 09, 2023 |
| HP            | G42                         | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Precision 5520              | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Dell          | Latitude E7270              | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [d2ce7f8ca6](https://linux-hardware.org/?probe=d2ce7f8ca6) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [e4f3bd771d](https://linux-hardware.org/?probe=e4f3bd771d) | Nov 08, 2023 |
| HONOR         | NBR-WAX9                    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Acer          | Aspire A517-51              | [9b0700130f](https://linux-hardware.org/?probe=9b0700130f) | Nov 08, 2023 |
| System76      | Lemur Pro                   | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2ae66ef2b](https://linux-hardware.org/?probe=c2ae66ef2b) | Nov 06, 2023 |
| Dell          | Vostro 5402                 | [2716ef5f71](https://linux-hardware.org/?probe=2716ef5f71) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| System76      | Lemur Pro                   | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| System76      | Lemur Pro                   | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| HUAWEI        | CREF-XX                     | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| System76      | Adder WS                    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Lenovo        | Z50-70 20354                | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| System76      | Lemur Pro                   | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| System76      | Darter Pro                  | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| Haier         | U1520SD                     | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Dell          | Latitude E7240              | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | G750JW                      | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| System76      | Gazelle                     | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| HP            | 250 G4                      | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| HP            | ProBook 4730s               | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| System76      | Lemur Pro                   | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| Acer          | Aspire A314-23P             | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Notebook      | P9XXEN_EF_ED                | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| Acer          | Aspire E1-571               | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Dell          | Inspiron 15 3525            | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| System76      | Serval WS                   | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| HP            | Laptop 15-db1xxx            | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Dell          | Latitude 7400               | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| System76      | Oryx Pro                    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| HUAWEI        | NbDE-WXX9                   | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| System76      | Darter Pro                  | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| HP            | Dev One Notebook PC         | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 6.2.6-76060206-generic              | 471       | 16.44%  |
| 5.19.0-76051900-generic             | 274       | 9.56%   |
| 6.0.12-76060006-generic             | 269       | 9.39%   |
| 5.17.5-76051705-generic             | 234       | 8.17%   |
| 6.6.10-76060610-generic             | 190       | 6.63%   |
| 6.4.6-76060406-generic              | 187       | 6.53%   |
| 6.0.6-76060006-generic              | 164       | 5.72%   |
| 6.5.6-76060506-generic              | 162       | 5.65%   |
| 6.6.6-76060606-generic              | 127       | 4.43%   |
| 5.18.10-76051810-generic            | 117       | 4.08%   |
| 6.8.0-76060800daily20240311-generic | 116       | 4.05%   |
| 5.17.15-76051715-generic            | 105       | 3.66%   |
| 6.2.0-76060200-generic              | 79        | 2.76%   |
| 5.16.19-76051619-generic            | 72        | 2.51%   |
| 6.5.4-76060504-generic              | 66        | 2.3%    |
| 6.0.2-76060002-generic              | 58        | 2.02%   |
| 6.1.11-76060111-generic             | 54        | 1.88%   |
| 6.0.3-76060003-generic              | 24        | 0.84%   |
| 5.19.16-76051916-generic            | 21        | 0.73%   |
| 6.5.7-060507-generic                | 3         | 0.1%    |
| 6.7.10-x64v3-xanmod1                | 2         | 0.07%   |
| 6.4.0-060400-generic                | 2         | 0.07%   |
| 6.3.7-060307-generic                | 2         | 0.07%   |
| 6.2.11-060211-generic               | 2         | 0.07%   |
| 6.1.0-1006-oem                      | 2         | 0.07%   |
| 5.17.5-051705-generic               | 2         | 0.07%   |
| 5.16.15-76051615-generic            | 2         | 0.07%   |
| 6.8.0-060800rc1-generic             | 1         | 0.03%   |
| 6.7.5-060705-generic                | 1         | 0.03%   |
| 6.5.8-x64v1-xanmod1                 | 1         | 0.03%   |
| 6.5.5-x64v3-xanmod1                 | 1         | 0.03%   |
| 6.5.12-x64v3-xanmod1                | 1         | 0.03%   |
| 6.5.10-x64v2-xanmod1                | 1         | 0.03%   |
| 6.5.0-rc2                           | 1         | 0.03%   |
| 6.4.5-x64v2-xanmod1                 | 1         | 0.03%   |
| 6.4.3-060403-generic                | 1         | 0.03%   |
| 6.4.12-2-liquorix-amd64             | 1         | 0.03%   |
| 6.3.9-x64v3-xanmod1                 | 1         | 0.03%   |
| 6.3.9-060309-generic                | 1         | 0.03%   |
| 6.3.4-060304-generic                | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.6   | 472       | 16.49%  |
| 5.19.0  | 277       | 9.68%   |
| 6.0.12  | 269       | 9.4%    |
| 5.17.5  | 237       | 8.28%   |
| 6.6.10  | 190       | 6.64%   |
| 6.4.6   | 187       | 6.53%   |
| 6.0.6   | 164       | 5.73%   |
| 6.5.6   | 162       | 5.66%   |
| 6.6.6   | 127       | 4.44%   |
| 6.8.0   | 117       | 4.09%   |
| 5.18.10 | 117       | 4.09%   |
| 5.17.15 | 105       | 3.67%   |
| 6.2.0   | 79        | 2.76%   |
| 5.16.19 | 72        | 2.51%   |
| 6.5.4   | 66        | 2.31%   |
| 6.0.2   | 59        | 2.06%   |
| 6.1.11  | 54        | 1.89%   |
| 6.0.3   | 24        | 0.84%   |
| 5.19.16 | 21        | 0.73%   |
| 6.5.7   | 3         | 0.1%    |
| 5.15.0  | 3         | 0.1%    |
| 6.7.10  | 2         | 0.07%   |
| 6.4.0   | 2         | 0.07%   |
| 6.3.9   | 2         | 0.07%   |
| 6.3.7   | 2         | 0.07%   |
| 6.2.11  | 2         | 0.07%   |
| 6.1.9   | 2         | 0.07%   |
| 6.1.0   | 2         | 0.07%   |
| 6.0.9   | 2         | 0.07%   |
| 6.0.0   | 2         | 0.07%   |
| 5.17.0  | 2         | 0.07%   |
| 5.16.15 | 2         | 0.07%   |
| 6.7.5   | 1         | 0.03%   |
| 6.5.8   | 1         | 0.03%   |
| 6.5.5   | 1         | 0.03%   |
| 6.5.12  | 1         | 0.03%   |
| 6.5.10  | 1         | 0.03%   |
| 6.5.0   | 1         | 0.03%   |
| 6.4.5   | 1         | 0.03%   |
| 6.4.3   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 552       | 19.59%  |
| 6.0     | 501       | 17.78%  |
| 5.17    | 341       | 12.1%   |
| 6.6     | 310       | 11%     |
| 5.19    | 300       | 10.65%  |
| 6.5     | 233       | 8.27%   |
| 6.4     | 191       | 6.78%   |
| 5.18    | 121       | 4.29%   |
| 6.8     | 117       | 4.15%   |
| 5.16    | 75        | 2.66%   |
| 6.1     | 61        | 2.16%   |
| 6.3     | 8         | 0.28%   |
| 5.15    | 5         | 0.18%   |
| 6.7     | 3         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2564      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 2499      | 97.28%  |
| KDE5            | 25        | 0.97%   |
| Unknown         | 18        | 0.7%    |
| X-Cinnamon      | 8         | 0.31%   |
| GNOME Flashback | 5         | 0.19%   |
| Unity           | 4         | 0.16%   |
| MATE            | 2         | 0.08%   |
| LXQt            | 2         | 0.08%   |
| Cinnamon        | 2         | 0.08%   |
| awesome         | 2         | 0.08%   |
| XFCE            | 1         | 0.04%   |
| i3              | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2437      | 94.49%  |
| Wayland | 125       | 4.85%   |
| Unknown | 13        | 0.5%    |
| Tty     | 4         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1793      | 69.15%  |
| GDM3    | 790       | 30.47%  |
| GDM     | 6         | 0.23%   |
| SDDM    | 3         | 0.12%   |
| LightDM | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1510      | 58.57%  |
| en_GB   | 166       | 6.44%   |
| pt_BR   | 145       | 5.62%   |
| de_DE   | 111       | 4.31%   |
| C       | 73        | 2.83%   |
| en_AU   | 65        | 2.52%   |
| fr_FR   | 59        | 2.29%   |
| it_IT   | 54        | 2.09%   |
| en_CA   | 41        | 1.59%   |
| es_ES   | 36        | 1.4%    |
| ru_RU   | 33        | 1.28%   |
| pl_PL   | 25        | 0.97%   |
| pt_PT   | 22        | 0.85%   |
| nb_NO   | 17        | 0.66%   |
| Unknown | 17        | 0.66%   |
| sv_SE   | 16        | 0.62%   |
| tr_TR   | 14        | 0.54%   |
| en_IN   | 14        | 0.54%   |
| en_NZ   | 12        | 0.47%   |
| es_MX   | 10        | 0.39%   |
| en_IE   | 10        | 0.39%   |
| fi_FI   | 9         | 0.35%   |
| de_CH   | 9         | 0.35%   |
| nl_NL   | 8         | 0.31%   |
| cs_CZ   | 8         | 0.31%   |
| en_ZA   | 7         | 0.27%   |
| fr_CA   | 6         | 0.23%   |
| es_AR   | 6         | 0.23%   |
| en_DK   | 6         | 0.23%   |
| da_DK   | 6         | 0.23%   |
| es_CO   | 5         | 0.19%   |
| es_CL   | 5         | 0.19%   |
| hu_HU   | 4         | 0.16%   |
| fr_CH   | 4         | 0.16%   |
| de_AT   | 4         | 0.16%   |
| zh_TW   | 3         | 0.12%   |
| zh_CN   | 3         | 0.12%   |
| en_PH   | 3         | 0.12%   |
| sk_SK   | 2         | 0.08%   |
| ru_UA   | 2         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1824      | 70.42%  |
| EFI  | 766       | 29.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2443      | 94.95%  |
| Btrfs   | 81        | 3.15%   |
| Overlay | 41        | 1.59%   |
| Xfs     | 7         | 0.27%   |
| Zfs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1775      | 68.48%  |
| GPT     | 769       | 29.67%  |
| MBR     | 48        | 1.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2489      | 96.81%  |
| Yes       | 82        | 3.19%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2293      | 88.98%  |
| Yes       | 284       | 11.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 548       | 21.37%  |
| Dell                   | 409       | 15.95%  |
| Hewlett-Packard        | 359       | 14%     |
| ASUSTek Computer       | 322       | 12.56%  |
| Acer                   | 191       | 7.45%   |
| Apple                  | 170       | 6.63%   |
| MSI                    | 91        | 3.55%   |
| System76               | 87        | 3.39%   |
| Toshiba                | 42        | 1.64%   |
| Samsung Electronics    | 40        | 1.56%   |
| HUAWEI                 | 36        | 1.4%    |
| Google                 | 24        | 0.94%   |
| Notebook               | 20        | 0.78%   |
| Alienware              | 20        | 0.78%   |
| Razer                  | 12        | 0.47%   |
| Sony                   | 11        | 0.43%   |
| Fujitsu                | 11        | 0.43%   |
| Unknown                | 11        | 0.43%   |
| GPU Company            | 10        | 0.39%   |
| Gigabyte Technology    | 10        | 0.39%   |
| Timi                   | 9         | 0.35%   |
| Framework              | 9         | 0.35%   |
| Positivo               | 8         | 0.31%   |
| HONOR                  | 8         | 0.31%   |
| PC Specialist          | 6         | 0.23%   |
| Avell High Performance | 6         | 0.23%   |
| TUXEDO                 | 4         | 0.16%   |
| Schenker               | 4         | 0.16%   |
| Medion                 | 4         | 0.16%   |
| GPD                    | 4         | 0.16%   |
| Clevo                  | 4         | 0.16%   |
| Panasonic              | 3         | 0.12%   |
| LG Electronics         | 3         | 0.12%   |
| ASRock                 | 3         | 0.12%   |
| Valve                  | 2         | 0.08%   |
| realme                 | 2         | 0.08%   |
| Pegatron               | 2         | 0.08%   |
| Packard Bell           | 2         | 0.08%   |
| OriginPC               | 2         | 0.08%   |
| Maibenben              | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| System76 Oryx Pro                     | 22        | 0.86%   |
| Unknown                               | 18        | 0.7%    |
| System76 Lemur Pro                    | 17        | 0.66%   |
| Apple MacBookAir7,2                   | 16        | 0.62%   |
| Apple MacBookAir6,2                   | 15        | 0.59%   |
| System76 Gazelle                      | 14        | 0.55%   |
| HP Dev One Notebook PC                | 13        | 0.51%   |
| Apple MacBookPro8,1                   | 12        | 0.47%   |
| Apple MacBookPro12,1                  | 12        | 0.47%   |
| Apple MacBookPro9,2                   | 11        | 0.43%   |
| System76 Pangolin                     | 9         | 0.35%   |
| System76 Darter Pro                   | 9         | 0.35%   |
| Apple MacBookPro7,1                   | 9         | 0.35%   |
| Apple MacBookPro11,3                  | 9         | 0.35%   |
| Lenovo Legion 5 15ACH6H 82JU          | 8         | 0.31%   |
| Dell XPS 15 9570                      | 8         | 0.31%   |
| Dell XPS 15 9520                      | 8         | 0.31%   |
| Dell XPS 15 7590                      | 8         | 0.31%   |
| System76 Galago Pro                   | 7         | 0.27%   |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.27%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9   | 7         | 0.27%   |
| Lenovo IdeaPad 3 15ALC6 82MF          | 7         | 0.27%   |
| HP Notebook                           | 7         | 0.27%   |
| Dell XPS 13 9310                      | 7         | 0.27%   |
| Apple MacBookPro11,1                  | 7         | 0.27%   |
| Acer Nitro AN515-58                   | 7         | 0.27%   |
| Lenovo Y50-70 20378                   | 6         | 0.23%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN      | 6         | 0.23%   |
| HP Pavilion 15                        | 6         | 0.23%   |
| HP EliteBook 840 G5                   | 6         | 0.23%   |
| Dell Latitude E7240                   | 6         | 0.23%   |
| Dell Inspiron 15 7000 Gaming          | 6         | 0.23%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 6         | 0.23%   |
| Acer Aspire A515-45                   | 6         | 0.23%   |
| Razer Blade                           | 5         | 0.2%    |
| Lenovo Legion 5 15ARH05H 82B1         | 5         | 0.2%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 5         | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81FE         | 5         | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81DE         | 5         | 0.2%    |
| HP Victus by Laptop 16-e0xxx          | 5         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 256       | 9.98%   |
| Lenovo IdeaPad     | 139       | 5.42%   |
| Acer Aspire        | 119       | 4.64%   |
| Dell Latitude      | 110       | 4.29%   |
| Dell Inspiron      | 107       | 4.17%   |
| Dell XPS           | 85        | 3.32%   |
| ASUS VivoBook      | 70        | 2.73%   |
| ASUS ROG           | 66        | 2.57%   |
| HP Pavilion        | 65        | 2.54%   |
| HP EliteBook       | 63        | 2.46%   |
| Lenovo Legion      | 61        | 2.38%   |
| HP Laptop          | 56        | 2.18%   |
| Dell Precision     | 47        | 1.83%   |
| HP ProBook         | 40        | 1.56%   |
| ASUS ASUS          | 38        | 1.48%   |
| Toshiba Satellite  | 35        | 1.37%   |
| Acer Swift         | 28        | 1.09%   |
| Acer Nitro         | 27        | 1.05%   |
| HP ZBook           | 25        | 0.98%   |
| Apple MacBookPro11 | 25        | 0.98%   |
| Dell Vostro        | 24        | 0.94%   |
| ASUS Zenbook       | 23        | 0.9%    |
| System76 Oryx      | 22        | 0.86%   |
| HP OMEN            | 20        | 0.78%   |
| Unknown            | 18        | 0.7%    |
| System76 Lemur     | 17        | 0.66%   |
| Apple MacBookPro8  | 17        | 0.66%   |
| Lenovo ThinkBook   | 16        | 0.62%   |
| Apple MacBookAir7  | 16        | 0.62%   |
| Apple MacBookAir6  | 16        | 0.62%   |
| Lenovo Yoga        | 15        | 0.59%   |
| System76 Gazelle   | 14        | 0.55%   |
| HP ENVY            | 14        | 0.55%   |
| HP Victus          | 13        | 0.51%   |
| HP Dev             | 13        | 0.51%   |
| Razer Blade        | 12        | 0.47%   |
| Apple MacBookPro9  | 12        | 0.47%   |
| Apple MacBookPro5  | 12        | 0.47%   |
| Apple MacBookPro12 | 12        | 0.47%   |
| Dell G15           | 11        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 396       | 15.44%  |
| 2022    | 290       | 11.31%  |
| 2020    | 276       | 10.76%  |
| 2019    | 207       | 8.07%   |
| 2018    | 195       | 7.61%   |
| 2013    | 154       | 6.01%   |
| 2012    | 146       | 5.69%   |
| 2011    | 132       | 5.15%   |
| 2023    | 128       | 4.99%   |
| 2017    | 125       | 4.88%   |
| 2016    | 120       | 4.68%   |
| 2015    | 116       | 4.52%   |
| 2014    | 111       | 4.33%   |
| 2010    | 63        | 2.46%   |
| 2009    | 49        | 1.91%   |
| 2008    | 28        | 1.09%   |
| 2007    | 22        | 0.86%   |
| 2024    | 4         | 0.16%   |
| 2006    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2564      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2564      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2475      | 96.53%  |
| Yes  | 89        | 3.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 704       | 27.22%  |
| 16.01-24.0  | 626       | 24.21%  |
| 8.01-16.0   | 499       | 19.3%   |
| 32.01-64.0  | 319       | 12.34%  |
| 3.01-4.0    | 291       | 11.25%  |
| 64.01-256.0 | 75        | 2.9%    |
| 24.01-32.0  | 54        | 2.09%   |
| 1.01-2.0    | 11        | 0.43%   |
| 2.01-3.0    | 7         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 947       | 34.18%  |
| 2.01-3.0   | 715       | 25.8%   |
| 3.01-4.0   | 591       | 21.33%  |
| 8.01-16.0  | 259       | 9.35%   |
| 1.01-2.0   | 209       | 7.54%   |
| 16.01-24.0 | 39        | 1.41%   |
| 24.01-32.0 | 9         | 0.32%   |
| 0.51-1.0   | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1859      | 71.61%  |
| 2      | 636       | 24.5%   |
| 3      | 82        | 3.16%   |
| 0      | 10        | 0.39%   |
| 4      | 7         | 0.27%   |
| 7      | 1         | 0.04%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2032      | 79.13%  |
| Yes       | 536       | 20.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1933      | 74.95%  |
| No        | 646       | 25.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2536      | 98.87%  |
| No        | 29        | 1.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2211      | 85.63%  |
| No        | 371       | 14.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 678       | 26.32%  |
| Brazil       | 209       | 8.11%   |
| Germany      | 163       | 6.33%   |
| UK           | 112       | 4.35%   |
| Italy        | 100       | 3.88%   |
| India        | 97        | 3.77%   |
| Canada       | 96        | 3.73%   |
| Australia    | 82        | 3.18%   |
| France       | 79        | 3.07%   |
| Russia       | 58        | 2.25%   |
| Spain        | 47        | 1.82%   |
| Netherlands  | 47        | 1.82%   |
| Sweden       | 42        | 1.63%   |
| Poland       | 41        | 1.59%   |
| Portugal     | 36        | 1.4%    |
| Norway       | 34        | 1.32%   |
| Mexico       | 32        | 1.24%   |
| Turkey       | 31        | 1.2%    |
| Czechia      | 29        | 1.13%   |
| Switzerland  | 26        | 1.01%   |
| Indonesia    | 26        | 1.01%   |
| Philippines  | 24        | 0.93%   |
| New Zealand  | 21        | 0.82%   |
| Finland      | 21        | 0.82%   |
| Denmark      | 21        | 0.82%   |
| Romania      | 18        | 0.7%    |
| Argentina    | 17        | 0.66%   |
| Serbia       | 16        | 0.62%   |
| Bulgaria     | 16        | 0.62%   |
| Hungary      | 15        | 0.58%   |
| Greece       | 15        | 0.58%   |
| Chile        | 15        | 0.58%   |
| Belgium      | 15        | 0.58%   |
| Austria      | 15        | 0.58%   |
| Thailand     | 14        | 0.54%   |
| South Africa | 12        | 0.47%   |
| Ireland      | 12        | 0.47%   |
| Egypt        | 9         | 0.35%   |
| Colombia     | 9         | 0.35%   |
| Vietnam      | 8         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Melbourne      | 33        | 1.22%   |
| Sao Paulo      | 24        | 0.89%   |
| Warsaw         | 17        | 0.63%   |
| Oslo           | 17        | 0.63%   |
| Milan          | 17        | 0.63%   |
| Helsinki       | 17        | 0.63%   |
| Brisbane       | 17        | 0.63%   |
| Berlin         | 17        | 0.63%   |
| Sydney         | 16        | 0.59%   |
| Istanbul       | 15        | 0.56%   |
| Bengaluru      | 15        | 0.56%   |
| Rio de Janeiro | 14        | 0.52%   |
| Prague         | 14        | 0.52%   |
| New York       | 14        | 0.52%   |
| Moscow         | 14        | 0.52%   |
| Chicago        | 13        | 0.48%   |
| Madrid         | 12        | 0.45%   |
| Denver         | 12        | 0.45%   |
| Sofia          | 11        | 0.41%   |
| Paris          | 11        | 0.41%   |
| St Petersburg  | 10        | 0.37%   |
| Seattle        | 10        | 0.37%   |
| Rome           | 10        | 0.37%   |
| Lisbon         | 10        | 0.37%   |
| Auckland       | 10        | 0.37%   |
| Vienna         | 9         | 0.33%   |
| Stockholm      | 9         | 0.33%   |
| Munich         | 9         | 0.33%   |
| Mumbai         | 9         | 0.33%   |
| Los Angeles    | 9         | 0.33%   |
| London         | 9         | 0.33%   |
| Budapest       | 9         | 0.33%   |
| Belgrade       | 9         | 0.33%   |
| Singapore      | 8         | 0.3%    |
| Minneapolis    | 8         | 0.3%    |
| Leipzig        | 8         | 0.3%    |
| Hamburg        | 8         | 0.3%    |
| Dallas         | 8         | 0.3%    |
| Calgary        | 8         | 0.3%    |
| Bucharest      | 8         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 619       | 829    | 18.97%  |
| Sandisk                        | 280       | 358    | 8.58%   |
| WDC                            | 275       | 319    | 8.43%   |
| Seagate                        | 206       | 240    | 6.31%   |
| SK hynix                       | 194       | 221    | 5.95%   |
| Kingston                       | 169       | 199    | 5.18%   |
| Toshiba                        | 165       | 197    | 5.06%   |
| Micron Technology              | 159       | 181    | 4.87%   |
| Unknown                        | 115       | 139    | 3.52%   |
| Intel                          | 113       | 132    | 3.46%   |
| Crucial                        | 106       | 122    | 3.25%   |
| Apple                          | 97        | 111    | 2.97%   |
| HGST                           | 66        | 73     | 2.02%   |
| KIOXIA                         | 62        | 68     | 1.9%    |
| Micron/Crucial Technology      | 38        | 45     | 1.16%   |
| A-DATA Technology              | 34        | 42     | 1.04%   |
| Hitachi                        | 33        | 39     | 1.01%   |
| Phison                         | 32        | 35     | 0.98%   |
| Phison Electronics             | 30        | 35     | 0.92%   |
| China                          | 30        | 36     | 0.92%   |
| Kingston Technology Company    | 28        | 29     | 0.86%   |
| PNY                            | 27        | 34     | 0.83%   |
| Silicon Motion                 | 26        | 31     | 0.8%    |
| Unknown                        | 17        | 21     | 0.52%   |
| LITEON                         | 15        | 18     | 0.46%   |
| ASMT                           | 15        | 15     | 0.46%   |
| Transcend                      | 14        | 16     | 0.43%   |
| Intenso                        | 13        | 19     | 0.4%    |
| ADATA Technology               | 13        | 13     | 0.4%    |
| SPCC                           | 12        | 12     | 0.37%   |
| LITEONIT                       | 12        | 24     | 0.37%   |
| KingSpec                       | 12        | 13     | 0.37%   |
| Netac                          | 11        | 11     | 0.34%   |
| Team                           | 10        | 10     | 0.31%   |
| Union Memory (Shenzhen)        | 9         | 12     | 0.28%   |
| Solid State Storage Technology | 9         | 9      | 0.28%   |
| Solid State Storage            | 9         | 10     | 0.28%   |
| Patriot                        | 7         | 9      | 0.21%   |
| Lexar                          | 7         | 8      | 0.21%   |
| JMicron Technology             | 7         | 8      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 77        | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 49        | 1.44%   |
| Kingston SA400S37240G 240GB SSD                       | 41        | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB                        | 36        | 1.06%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 27        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 26        | 0.76%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 24        | 0.71%   |
| HGST HTS721010A9E630 1TB                              | 24        | 0.71%   |
| Toshiba MQ04ABF100 1TB                                | 22        | 0.65%   |
| SanDisk NVMe SSD Drive 1TB                            | 22        | 0.65%   |
| Toshiba MQ01ABD100 1TB                                | 21        | 0.62%   |
| Unknown MMC Card  64GB                                | 20        | 0.59%   |
| Unknown MMC Card  32GB                                | 20        | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 20        | 0.59%   |
| Kingston SA400S37480G 480GB SSD                       | 20        | 0.59%   |
| Intel SSD 660P Series 1024GB                          | 20        | 0.59%   |
| Apple SSD SM0128G 121GB                               | 20        | 0.59%   |
| Crucial CT240BX500SSD1 240GB                          | 18        | 0.53%   |
| Samsung NVMe SSD Drive 512GB                          | 17        | 0.5%    |
| Unknown                                               | 17        | 0.5%    |
| Unknown MMC Card  128GB                               | 16        | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                             | 16        | 0.47%   |
| ASMT USB 3.0 TOSATA 120GB                             | 15        | 0.44%   |
| WDC WD10SPZX-24Z10 1TB                                | 14        | 0.41%   |
| SK hynix NVMe SSD Drive 512GB                         | 14        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 14        | 0.41%   |
| Samsung SSD 850 EVO 500GB                             | 14        | 0.41%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 13        | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 13        | 0.38%   |
| Seagate ST1000LM049-2GH172 1TB                        | 13        | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                          | 13        | 0.38%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 13        | 0.38%   |
| Sandisk WD Black SN850 512GB                          | 12        | 0.35%   |
| SanDisk NVMe SSD Drive 256GB                          | 12        | 0.35%   |
| Samsung SSD 870 EVO 500GB                             | 12        | 0.35%   |
| Phison E12 NVMe Controller 2TB                        | 12        | 0.35%   |
| Kingston SA400S37120G 120GB SSD                       | 12        | 0.35%   |
| Crucial CT500MX500SSD1 500GB                          | 12        | 0.35%   |
| Unknown MMC Card  16GB                                | 11        | 0.32%   |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 11        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 200       | 233    | 34.48%  |
| WDC                 | 143       | 168    | 24.66%  |
| Toshiba             | 99        | 116    | 17.07%  |
| HGST                | 66        | 73     | 11.38%  |
| Hitachi             | 33        | 39     | 5.69%   |
| Samsung Electronics | 9         | 9      | 1.55%   |
| Unknown             | 8         | 8      | 1.38%   |
| JMicron Technology  | 5         | 6      | 0.86%   |
| Apple               | 5         | 6      | 0.86%   |
| Fujitsu             | 4         | 4      | 0.69%   |
| SABRENT             | 2         | 3      | 0.34%   |
| Intenso             | 2         | 6      | 0.34%   |
| TO Exter            | 1         | 1      | 0.17%   |
| StoreJet            | 1         | 1      | 0.17%   |
| HGST HDN            | 1         | 1      | 0.17%   |
| Asm                 | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 182       | 230    | 19.04%  |
| Kingston            | 123       | 139    | 12.87%  |
| Crucial             | 92        | 107    | 9.62%   |
| SanDisk             | 91        | 117    | 9.52%   |
| Apple               | 79        | 90     | 8.26%   |
| WDC                 | 54        | 65     | 5.65%   |
| China               | 30        | 36     | 3.14%   |
| Micron Technology   | 28        | 31     | 2.93%   |
| PNY                 | 25        | 32     | 2.62%   |
| SK hynix            | 23        | 24     | 2.41%   |
| Toshiba             | 21        | 21     | 2.2%    |
| A-DATA Technology   | 15        | 18     | 1.57%   |
| Intel               | 14        | 16     | 1.46%   |
| LITEON              | 13        | 16     | 1.36%   |
| Transcend           | 12        | 14     | 1.26%   |
| LITEONIT            | 12        | 24     | 1.26%   |
| KingSpec            | 12        | 13     | 1.26%   |
| SPCC                | 9         | 9      | 0.94%   |
| Netac               | 8         | 8      | 0.84%   |
| Intenso             | 8         | 9      | 0.84%   |
| Patriot             | 6         | 8      | 0.63%   |
| Apacer              | 5         | 9      | 0.52%   |
| Lexar               | 4         | 5      | 0.42%   |
| Hewlett-Packard     | 4         | 4      | 0.42%   |
| Team                | 3         | 3      | 0.31%   |
| MyDigitalSSD        | 3         | 3      | 0.31%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.31%   |
| Fanxiang            | 3         | 3      | 0.31%   |
| Dogfish             | 3         | 4      | 0.31%   |
| Corsair             | 3         | 3      | 0.31%   |
| Wibtek              | 2         | 4      | 0.21%   |
| Verbatim            | 2         | 2      | 0.21%   |
| Teclast             | 2         | 2      | 0.21%   |
| PHD 3.0             | 2         | 2      | 0.21%   |
| KingDian            | 2         | 2      | 0.21%   |
| Inland              | 2         | 2      | 0.21%   |
| Hikvision           | 2         | 2      | 0.21%   |
| GOODRAM             | 2         | 2      | 0.21%   |
| External            | 2         | 2      | 0.21%   |
| Unknown             | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1411      | 1917   | 46.78%  |
| SSD     | 881       | 1138   | 29.21%  |
| HDD     | 558       | 675    | 18.5%   |
| MMC     | 106       | 127    | 3.51%   |
| Unknown | 60        | 75     | 1.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1410      | 1915   | 48.4%   |
| SATA | 1270      | 1729   | 43.6%   |
| SAS  | 127       | 161    | 4.36%   |
| MMC  | 106       | 127    | 3.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 911       | 1189   | 63.48%  |
| 0.51-1.0   | 447       | 526    | 31.15%  |
| 1.01-2.0   | 58        | 70     | 4.04%   |
| 3.01-4.0   | 11        | 16     | 0.77%   |
| 2.01-3.0   | 3         | 7      | 0.21%   |
| 4.01-10.0  | 3         | 3      | 0.21%   |
| 10.01-20.0 | 2         | 2      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 836       | 31.69%  |
| 251-500        | 783       | 29.68%  |
| 501-1000       | 535       | 20.28%  |
| 1001-2000      | 188       | 7.13%   |
| 51-100         | 87        | 3.3%    |
| 1-20           | 53        | 2.01%   |
| 2001-3000      | 51        | 1.93%   |
| More than 3000 | 48        | 1.82%   |
| 21-50          | 40        | 1.52%   |
| Unknown        | 17        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 853       | 31.02%  |
| 21-50          | 668       | 24.29%  |
| 101-250        | 418       | 15.2%   |
| 51-100         | 373       | 13.56%  |
| 251-500        | 243       | 8.84%   |
| 501-1000       | 122       | 4.44%   |
| 1001-2000      | 35        | 1.27%   |
| Unknown        | 17        | 0.62%   |
| More than 3000 | 14        | 0.51%   |
| 2001-3000      | 7         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1024GB       | 4         | 4      | 6.45%   |
| Seagate ST1000LX015-1U7172 1TB              | 2         | 2      | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB              | 2         | 2      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 3.23%   |
| HGST HTS725050A7E630 500GB                  | 2         | 3      | 3.23%   |
| HGST HTS545050A7E680 500GB                  | 2         | 2      | 3.23%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD            | 1         | 1      | 1.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.61%   |
| WDC WDS100T2B0B-00YS70 1TB SSD              | 1         | 1      | 1.61%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 1.61%   |
| WDC WD3200BEKX-75B7WT0 320GB                | 1         | 1      | 1.61%   |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.61%   |
| WDC WD10SPZX-24Z10T0 1TB                    | 1         | 1      | 1.61%   |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.61%   |
| WDC WD10SPZX-16Z10T0 1TB                    | 1         | 1      | 1.61%   |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.61%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1      | 1.61%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.61%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.61%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.61%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.61%   |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.61%   |
| Toshiba MK7559GSXP 752GB                    | 1         | 1      | 1.61%   |
| Toshiba MK3252GSX 320GB                     | 1         | 1      | 1.61%   |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.61%   |
| SK hynix PC711 HFS512GDE9X073N 512GB        | 1         | 1      | 1.61%   |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.61%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.61%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.61%   |
| Silicon Motion 1TB PCS PCIe M.2 SSD         | 1         | 1      | 1.61%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.61%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1      | 1.61%   |
| Seagate ST500LM030-2E717D 500GB             | 1         | 1      | 1.61%   |
| Seagate ST320LT009-9WC142 320GB             | 1         | 1      | 1.61%   |
| Seagate ST1000LM049-2GH172 1TB              | 1         | 1      | 1.61%   |
| SanDisk Z400s M.2 2280 256GB SSD            | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 980 PRO 500GB       | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 970 EVO Plus 1TB    | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 870 EVO 500GB       | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 850 EVO 500GB       | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 19.35%  |
| Seagate             | 11        | 11     | 17.74%  |
| SK hynix            | 8         | 8      | 12.9%   |
| HGST                | 7         | 8      | 11.29%  |
| Toshiba             | 6         | 6      | 9.68%   |
| Samsung Electronics | 4         | 4      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 3.23%   |
| Team                | 1         | 1      | 1.61%   |
| Silicon Motion      | 1         | 1      | 1.61%   |
| SanDisk             | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| Lexar               | 1         | 1      | 1.61%   |
| Leven               | 1         | 1      | 1.61%   |
| Kingston            | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Hitachi             | 1         | 3      | 1.61%   |
| Crucial             | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 11     | 35.48%  |
| WDC     | 8         | 8      | 25.81%  |
| HGST    | 7         | 8      | 22.58%  |
| Toshiba | 4         | 4      | 12.9%   |
| Hitachi | 1         | 3      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 34     | 50%     |
| NVMe | 16        | 16     | 25.81%  |
| SSD  | 15        | 15     | 24.19%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1877      | 2875   | 69.6%   |
| Works    | 757       | 990    | 28.07%  |
| Malfunc  | 61        | 65     | 2.26%   |
| Failed   | 2         | 2      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1472      | 44.16%  |
| Samsung Electronics                     | 494       | 14.82%  |
| AMD                                     | 301       | 9.03%   |
| SanDisk                                 | 258       | 7.74%   |
| SK hynix                                | 171       | 5.13%   |
| Micron Technology                       | 130       | 3.9%    |
| Kingston Technology Company             | 74        | 2.22%   |
| Phison Electronics                      | 68        | 2.04%   |
| KIOXIA                                  | 57        | 1.71%   |
| Toshiba America Info Systems            | 52        | 1.56%   |
| Micron/Crucial Technology               | 48        | 1.44%   |
| Nvidia                                  | 36        | 1.08%   |
| Silicon Motion                          | 33        | 0.99%   |
| ADATA Technology                        | 31        | 0.93%   |
| Solid State Storage Technology          | 23        | 0.69%   |
| Marvell Technology Group                | 16        | 0.48%   |
| Apple                                   | 13        | 0.39%   |
| Union Memory (Shenzhen)                 | 12        | 0.36%   |
| Shenzhen Longsys Electronics            | 8         | 0.24%   |
| Realtek Semiconductor                   | 7         | 0.21%   |
| Solidigm                                | 6         | 0.18%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.18%   |
| Yangtze Memory Technologies             | 3         | 0.09%   |
| INNOGRIT                                | 3         | 0.09%   |
| Transcend                               | 2         | 0.06%   |
| Seagate Technology                      | 2         | 0.06%   |
| Lite-On Technology                      | 2         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| O2 Micro                                | 1         | 0.03%   |
| Netac Technology                        | 1         | 0.03%   |
| Hosin Global Electronics                | 1         | 0.03%   |
| ASMedia Technology                      | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 290       | 8.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 182       | 5.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 165       | 4.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 145       | 4.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 126       | 3.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 121       | 3.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 119       | 3.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 114       | 3.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 103       | 2.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 83        | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 81        | 2.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 71        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 67        | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 62        | 1.78%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 58        | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 49        | 1.41%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 45        | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 44        | 1.26%   |
| Intel SSD 660P Series                                                          | 42        | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 42        | 1.2%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 39        | 1.12%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 39        | 1.12%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 39        | 1.12%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 36        | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 34        | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                            | 33        | 0.95%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 32        | 0.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 32        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 32        | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 31        | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 29        | 0.83%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 28        | 0.8%    |
| Phison E12 NVMe Controller                                                     | 28        | 0.8%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 27        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 27        | 0.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 27        | 0.77%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 26        | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 26        | 0.75%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 23        | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1534      | 46.7%   |
| NVMe | 1407      | 42.83%  |
| RAID | 296       | 9.01%   |
| IDE  | 48        | 1.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1958      | 76.37%  |
| AMD    | 606       | 23.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 51        | 1.99%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 49        | 1.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 44        | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 40        | 1.56%   |
| Intel 12th Gen Core i7-12700H                 | 40        | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 1.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 1.4%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 36        | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 31        | 1.21%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 31        | 1.21%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 31        | 1.21%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 30        | 1.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 28        | 1.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 1.01%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 26        | 1.01%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 25        | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 24        | 0.94%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 24        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 22        | 0.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 20        | 0.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 20        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 19        | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 18        | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 18        | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 0.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 17        | 0.66%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 17        | 0.66%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 17        | 0.66%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 15        | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 15        | 0.58%   |
| Intel 12th Gen Core i7-1260P                  | 15        | 0.58%   |
| Intel 12th Gen Core i7-1255U                  | 15        | 0.58%   |
| Intel 12th Gen Core i5-1235U                  | 15        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 611       | 23.83%  |
| Intel Core i5           | 548       | 21.37%  |
| Other                   | 454       | 17.71%  |
| AMD Ryzen 7             | 207       | 8.07%   |
| AMD Ryzen 5             | 171       | 6.67%   |
| Intel Core i3           | 131       | 5.11%   |
| Intel Celeron           | 84        | 3.28%   |
| Intel Core 2 Duo        | 64        | 2.5%    |
| AMD Ryzen 9             | 47        | 1.83%   |
| AMD Ryzen 7 PRO         | 37        | 1.44%   |
| AMD Ryzen 3             | 22        | 0.86%   |
| Intel Pentium           | 20        | 0.78%   |
| AMD A8                  | 19        | 0.74%   |
| AMD Ryzen 5 PRO         | 18        | 0.7%    |
| AMD A10                 | 17        | 0.66%   |
| Intel Core i9           | 15        | 0.59%   |
| AMD A6                  | 15        | 0.59%   |
| Intel Pentium Dual-Core | 9         | 0.35%   |
| Intel Xeon              | 8         | 0.31%   |
| Intel Pentium Silver    | 7         | 0.27%   |
| AMD A4                  | 7         | 0.27%   |
| AMD Athlon              | 6         | 0.23%   |
| AMD E1                  | 5         | 0.2%    |
| AMD E                   | 5         | 0.2%    |
| AMD E2                  | 4         | 0.16%   |
| Intel Core m3           | 3         | 0.12%   |
| AMD Athlon X2           | 3         | 0.12%   |
| Intel Genuine           | 2         | 0.08%   |
| Intel Core m5           | 2         | 0.08%   |
| Intel Core M            | 2         | 0.08%   |
| Intel Core 2            | 2         | 0.08%   |
| Intel Core              | 2         | 0.08%   |
| Intel Atom              | 2         | 0.08%   |
| AMD Ryzen 3 PRO         | 2         | 0.08%   |
| AMD Phenom II           | 2         | 0.08%   |
| AMD FX                  | 2         | 0.08%   |
| AMD A12                 | 2         | 0.08%   |
| Intel Pentium Gold      | 1         | 0.04%   |
| Intel Pentium Dual      | 1         | 0.04%   |
| Intel Core 2 Quad       | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 870       | 33.93%  |
| 4      | 829       | 32.33%  |
| 8      | 363       | 14.16%  |
| 6      | 279       | 10.88%  |
| 14     | 92        | 3.59%   |
| 10     | 51        | 1.99%   |
| 12     | 46        | 1.79%   |
| 16     | 13        | 0.51%   |
| 24     | 12        | 0.47%   |
| 1      | 8         | 0.31%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2564      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2248      | 87.61%  |
| 1      | 318       | 12.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2564      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2098      | 80.72%  |
| 0x0a50000c | 44        | 1.69%   |
| 0x806c1    | 36        | 1.39%   |
| 0x906a3    | 23        | 0.88%   |
| 0x806d1    | 23        | 0.88%   |
| 0x08608103 | 22        | 0.85%   |
| 0xa0652    | 20        | 0.77%   |
| 0x806ea    | 20        | 0.77%   |
| 0x0a404102 | 20        | 0.77%   |
| 0x08600106 | 20        | 0.77%   |
| 0x806ec    | 19        | 0.73%   |
| 0x906ea    | 17        | 0.65%   |
| 0x306a9    | 16        | 0.62%   |
| 0x0a50000d | 14        | 0.54%   |
| 0x406e3    | 13        | 0.5%    |
| 0x0a404101 | 13        | 0.5%    |
| 0x08108109 | 13        | 0.5%    |
| 0x806e9    | 12        | 0.46%   |
| 0x40651    | 11        | 0.42%   |
| 0x08600104 | 11        | 0.42%   |
| 0x906a4    | 9         | 0.35%   |
| 0x306d4    | 8         | 0.31%   |
| 0x206a7    | 8         | 0.31%   |
| 0x1067a    | 8         | 0.31%   |
| 0x906e9    | 7         | 0.27%   |
| 0x706e5    | 7         | 0.27%   |
| 0x506e3    | 7         | 0.27%   |
| 0x306c3    | 7         | 0.27%   |
| 0x0a704103 | 7         | 0.27%   |
| 0x08108102 | 7         | 0.27%   |
| 0x08600103 | 6         | 0.23%   |
| 0x806eb    | 5         | 0.19%   |
| 0x706a8    | 4         | 0.15%   |
| 0x0a601203 | 4         | 0.15%   |
| 0x08608102 | 4         | 0.15%   |
| 0x906c0    | 3         | 0.12%   |
| 0x806c2    | 3         | 0.12%   |
| 0x08a00008 | 3         | 0.12%   |
| 0x0810100b | 3         | 0.12%   |
| 0xa0660    | 2         | 0.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 475       | 18.48%  |
| Unknown          | 320       | 12.45%  |
| Haswell          | 196       | 7.62%   |
| TigerLake        | 154       | 5.99%   |
| Zen 3            | 153       | 5.95%   |
| SandyBridge      | 153       | 5.95%   |
| IvyBridge        | 128       | 4.98%   |
| Skylake          | 127       | 4.94%   |
| Alderlake Hybrid | 108       | 4.2%    |
| Broadwell        | 99        | 3.85%   |
| Zen 2            | 91        | 3.54%   |
| CometLake        | 87        | 3.38%   |
| Zen+             | 86        | 3.35%   |
| Penryn           | 71        | 2.76%   |
| IceLake          | 67        | 2.61%   |
| Westmere         | 46        | 1.79%   |
| Goldmont plus    | 36        | 1.4%    |
| Silvermont       | 31        | 1.21%   |
| Excavator        | 24        | 0.93%   |
| Zen              | 22        | 0.86%   |
| Puma             | 18        | 0.7%    |
| Piledriver       | 13        | 0.51%   |
| K10 Llano        | 11        | 0.43%   |
| Core             | 9         | 0.35%   |
| Goldmont         | 8         | 0.31%   |
| Bobcat           | 8         | 0.31%   |
| Steamroller      | 7         | 0.27%   |
| Tremont          | 4         | 0.16%   |
| Nehalem          | 4         | 0.16%   |
| Jaguar           | 4         | 0.16%   |
| K8 Hammer        | 3         | 0.12%   |
| K10              | 3         | 0.12%   |
| Gracemont        | 3         | 0.12%   |
| K8 & K10 hybrid  | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1807      | 52.47%  |
| Nvidia | 937       | 27.21%  |
| AMD    | 700       | 20.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 141       | 4.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 137       | 3.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 128       | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 118       | 3.36%   |
| Intel UHD Graphics 620                                                                | 108       | 3.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 103       | 2.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 97        | 2.76%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 90        | 2.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 89        | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 85        | 2.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 81        | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 71        | 2.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 70        | 1.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 67        | 1.91%   |
| Intel HD Graphics 5500                                                                | 67        | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 66        | 1.88%   |
| AMD Rembrandt [Radeon 680M]                                                           | 66        | 1.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 64        | 1.82%   |
| Intel HD Graphics 620                                                                 | 64        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 62        | 1.76%   |
| AMD Lucienne                                                                          | 62        | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 53        | 1.51%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 52        | 1.48%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 50        | 1.42%   |
| Intel HD Graphics 630                                                                 | 43        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                   | 39        | 1.11%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 38        | 1.08%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 32        | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 32        | 0.91%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 30        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 29        | 0.82%   |
| Intel HD Graphics 530                                                                 | 28        | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 27        | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 27        | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 23        | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 22        | 0.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 22        | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 22        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 20        | 0.57%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                       | 20        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1117      | 43.31%  |
| Intel + Nvidia     | 606       | 23.5%   |
| 1 x AMD            | 393       | 15.24%  |
| AMD + Nvidia       | 179       | 6.94%   |
| 1 x Nvidia         | 143       | 5.54%   |
| Intel + AMD        | 80        | 3.1%    |
| 2 x AMD            | 50        | 1.94%   |
| 2 x Nvidia         | 5         | 0.19%   |
| Other              | 3         | 0.12%   |
| Intel + 2 x Nvidia | 2         | 0.08%   |
| 2 x Intel          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1813      | 70.05%  |
| Proprietary | 738       | 28.52%  |
| Unknown     | 37        | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2240      | 86.59%  |
| 0.01-0.5   | 133       | 5.14%   |
| 1.01-2.0   | 68        | 2.63%   |
| 3.01-4.0   | 46        | 1.78%   |
| 7.01-8.0   | 35        | 1.35%   |
| 5.01-6.0   | 34        | 1.31%   |
| 0.51-1.0   | 20        | 0.77%   |
| 8.01-16.0  | 7         | 0.27%   |
| 2.01-3.0   | 4         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 562       | 18.51%  |
| BOE                     | 469       | 15.44%  |
| Chimei Innolux          | 434       | 14.29%  |
| LG Display              | 357       | 11.76%  |
| Samsung Electronics     | 241       | 7.94%   |
| Apple                   | 142       | 4.68%   |
| Dell                    | 103       | 3.39%   |
| Sharp                   | 102       | 3.36%   |
| Goldstar                | 87        | 2.86%   |
| PANDA                   | 70        | 2.3%    |
| Lenovo                  | 46        | 1.51%   |
| InfoVision              | 40        | 1.32%   |
| CSO                     | 34        | 1.12%   |
| Chi Mei Optoelectronics | 34        | 1.12%   |
| Acer                    | 32        | 1.05%   |
| Hewlett-Packard         | 27        | 0.89%   |
| AOC                     | 25        | 0.82%   |
| Philips                 | 23        | 0.76%   |
| ASUSTek Computer        | 21        | 0.69%   |
| BenQ                    | 17        | 0.56%   |
| TMX                     | 15        | 0.49%   |
| Ancor Communications    | 15        | 0.49%   |
| Iiyama                  | 13        | 0.43%   |
| ViewSonic               | 9         | 0.3%    |
| MSI                     | 8         | 0.26%   |
| Panasonic               | 6         | 0.2%    |
| HKC                     | 6         | 0.2%    |
| Vestel Elektronik       | 5         | 0.16%   |
| Sony                    | 5         | 0.16%   |
| NEC Computers           | 5         | 0.16%   |
| Gigabyte Technology     | 5         | 0.16%   |
| Vizio                   | 4         | 0.13%   |
| JDI                     | 4         | 0.13%   |
| Hitachi                 | 4         | 0.13%   |
| Toshiba                 | 3         | 0.1%    |
| TCL                     | 3         | 0.1%    |
| RTK                     | 3         | 0.1%    |
| HUAWEI                  | 3         | 0.1%    |
| Unknown                 | 2         | 0.07%   |
| TMA                     | 2         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 35        | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 27        | 0.88%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 25        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 23        | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 23        | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 22        | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 15        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 0.49%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 15        | 0.49%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 14        | 0.46%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 14        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.46%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 14        | 0.46%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 13        | 0.42%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 12        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 11        | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 11        | 0.36%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 10        | 0.33%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 10        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 9         | 0.29%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 9         | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 8         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 8         | 0.26%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 8         | 0.26%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                  | 8         | 0.26%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 7         | 0.23%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 7         | 0.23%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 7         | 0.23%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 7         | 0.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 7         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1404      | 49.3%   |
| 1366x768 (WXGA)    | 552       | 19.38%  |
| 3840x2160 (4K)     | 132       | 4.63%   |
| 2560x1440 (QHD)    | 126       | 4.42%   |
| 1920x1200 (WUXGA)  | 107       | 3.76%   |
| 1600x900 (HD+)     | 91        | 3.2%    |
| 2560x1600          | 81        | 2.84%   |
| 1440x900 (WXGA+)   | 54        | 1.9%    |
| 2880x1800          | 52        | 1.83%   |
| 1280x800 (WXGA)    | 48        | 1.69%   |
| 3440x1440          | 22        | 0.77%   |
| 3840x2400          | 21        | 0.74%   |
| 2560x1080          | 21        | 0.74%   |
| 3072x1920          | 14        | 0.49%   |
| 1680x1050 (WSXGA+) | 14        | 0.49%   |
| 2160x1440          | 12        | 0.42%   |
| 3200x1800 (QHD+)   | 9         | 0.32%   |
| 1280x1024 (SXGA)   | 9         | 0.32%   |
| 2256x1504          | 8         | 0.28%   |
| 3456x2160          | 7         | 0.25%   |
| 3200x2000          | 7         | 0.25%   |
| 1360x768           | 7         | 0.25%   |
| 3840x1080          | 6         | 0.21%   |
| 1920x1280          | 5         | 0.18%   |
| 3840x1100          | 4         | 0.14%   |
| 2520x1680          | 4         | 0.14%   |
| 2240x1400          | 4         | 0.14%   |
| 2880x1620          | 3         | 0.11%   |
| 2304x1440          | 3         | 0.11%   |
| 1920x540           | 3         | 0.11%   |
| 1280x720 (HD)      | 3         | 0.11%   |
| 800x1280           | 2         | 0.07%   |
| 3000x2000          | 2         | 0.07%   |
| 4096x2304          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3120x2080          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |
| 1600x2560          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1200      | 39.63%  |
| 13      | 478       | 15.79%  |
| 14      | 374       | 12.35%  |
| 17      | 192       | 6.34%   |
| 27      | 125       | 4.13%   |
| 16      | 113       | 3.73%   |
| 24      | 97        | 3.2%    |
| 23      | 70        | 2.31%   |
| 21      | 56        | 1.85%   |
| 12      | 55        | 1.82%   |
| 31      | 43        | 1.42%   |
| 34      | 36        | 1.19%   |
| 11      | 31        | 1.02%   |
| 18      | 18        | 0.59%   |
| 19      | 17        | 0.56%   |
| Unknown | 14        | 0.46%   |
| 32      | 13        | 0.43%   |
| 84      | 11        | 0.36%   |
| 40      | 11        | 0.36%   |
| 22      | 9         | 0.3%    |
| 20      | 8         | 0.26%   |
| 72      | 6         | 0.2%    |
| 48      | 6         | 0.2%    |
| 35      | 6         | 0.2%    |
| 54      | 5         | 0.17%   |
| 49      | 4         | 0.13%   |
| 28      | 4         | 0.13%   |
| 29      | 3         | 0.1%    |
| 74      | 2         | 0.07%   |
| 42      | 2         | 0.07%   |
| 33      | 2         | 0.07%   |
| 26      | 2         | 0.07%   |
| 25      | 2         | 0.07%   |
| 8       | 2         | 0.07%   |
| 60      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 46      | 1         | 0.03%   |
| 44      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1884      | 62.74%  |
| 201-300     | 331       | 11.02%  |
| 501-600     | 264       | 8.79%   |
| 351-400     | 228       | 7.59%   |
| 401-500     | 98        | 3.26%   |
| 601-700     | 68        | 2.26%   |
| 701-800     | 51        | 1.7%    |
| 1001-1500   | 20        | 0.67%   |
| 1501-2000   | 19        | 0.63%   |
| 801-900     | 18        | 0.6%    |
| Unknown     | 14        | 0.47%   |
| 901-1000    | 4         | 0.13%   |
| 101-200     | 2         | 0.07%   |
| 1-100       | 2         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2137      | 80.13%  |
| 16/10   | 416       | 15.6%   |
| 21/9    | 46        | 1.72%   |
| 3/2     | 35        | 1.31%   |
| 5/4     | 10        | 0.37%   |
| 32/9    | 7         | 0.26%   |
| 3.40    | 4         | 0.15%   |
| Unknown | 3         | 0.11%   |
| 4/3     | 2         | 0.07%   |
| 6/5     | 1         | 0.04%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 0.67    | 1         | 0.04%   |
| 0.63    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1206      | 39.91%  |
| 81-90          | 668       | 22.1%   |
| 201-250        | 191       | 6.32%   |
| 121-130        | 178       | 5.89%   |
| 71-80          | 166       | 5.49%   |
| 301-350        | 127       | 4.2%    |
| 111-120        | 103       | 3.41%   |
| 351-500        | 102       | 3.38%   |
| 61-70          | 53        | 1.75%   |
| 151-200        | 41        | 1.36%   |
| 51-60          | 35        | 1.16%   |
| More than 1000 | 31        | 1.03%   |
| 251-300        | 28        | 0.93%   |
| 501-1000       | 25        | 0.83%   |
| 141-150        | 21        | 0.69%   |
| 91-100         | 15        | 0.5%    |
| 131-140        | 14        | 0.46%   |
| Unknown        | 14        | 0.46%   |
| 1-40           | 4         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1385      | 46.74%  |
| 101-120       | 685       | 23.12%  |
| 51-100        | 379       | 12.79%  |
| 161-240       | 329       | 11.1%   |
| More than 240 | 140       | 4.72%   |
| 1-50          | 31        | 1.05%   |
| Unknown       | 14        | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2032      | 77.77%  |
| 2     | 453       | 17.34%  |
| 3     | 67        | 2.56%   |
| 0     | 57        | 2.18%   |
| 4     | 4         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1405      | 34.81%  |
| Intel                                 | 1370      | 33.94%  |
| Qualcomm Atheros                      | 424       | 10.51%  |
| Broadcom                              | 232       | 5.75%   |
| MediaTek                              | 164       | 4.06%   |
| Broadcom Limited                      | 91        | 2.25%   |
| ASIX Electronics                      | 42        | 1.04%   |
| Samsung Electronics                   | 23        | 0.57%   |
| Nvidia                                | 21        | 0.52%   |
| TP-Link                               | 20        | 0.5%    |
| Ralink                                | 20        | 0.5%    |
| Qualcomm                              | 19        | 0.47%   |
| Dell                                  | 19        | 0.47%   |
| Marvell Technology Group              | 18        | 0.45%   |
| DisplayLink                           | 17        | 0.42%   |
| Xiaomi                                | 15        | 0.37%   |
| Ralink Technology                     | 14        | 0.35%   |
| Lenovo                                | 14        | 0.35%   |
| Sierra Wireless                       | 12        | 0.3%    |
| JMicron Technology                    | 9         | 0.22%   |
| Hewlett-Packard                       | 8         | 0.2%    |
| ASUSTek Computer                      | 8         | 0.2%    |
| OPPO Electronics                      | 7         | 0.17%   |
| NetGear                               | 6         | 0.15%   |
| Ericsson Business Mobile Networks     | 6         | 0.15%   |
| OnePlus Technology (Shenzhen)         | 5         | 0.12%   |
| Google                                | 5         | 0.12%   |
| Motorola PCS                          | 4         | 0.1%    |
| FIBOCOM                               | 4         | 0.1%    |
| Qualcomm Atheros Communications       | 3         | 0.07%   |
| Huawei Technologies                   | 3         | 0.07%   |
| Edimax Technology                     | 3         | 0.07%   |
| D-Link                                | 3         | 0.07%   |
| Arduino SA                            | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| Apple                                 | 2         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 875       | 18.32%  |
| Intel Wi-Fi 6 AX200                                                    | 162       | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 141       | 2.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 134       | 2.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 121       | 2.53%   |
| Intel Wi-Fi 6 AX201                                                    | 116       | 2.43%   |
| Intel Wireless 8265 / 8275                                             | 114       | 2.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 94        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 86        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 79        | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 77        | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 71        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 67        | 1.4%    |
| Intel Wireless 8260                                                    | 66        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 65        | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 64        | 1.34%   |
| Intel Wireless 7265                                                    | 61        | 1.28%   |
| Intel Wireless 7260                                                    | 60        | 1.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 57        | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 56        | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 55        | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 48        | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 43        | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 43        | 0.9%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 43        | 0.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 41        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                      | 41        | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 41        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 39        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 39        | 0.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 38        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 37        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 36        | 0.75%   |
| Intel Ethernet Connection I219-LM                                      | 35        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 33        | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 31        | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 31        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 29        | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                          | 29        | 0.61%   |
| Intel Ethernet Connection I217-LM                                      | 28        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1329      | 49.68%  |
| Realtek Semiconductor                 | 407       | 15.21%  |
| Qualcomm Atheros                      | 362       | 13.53%  |
| Broadcom                              | 202       | 7.55%   |
| MediaTek                              | 163       | 6.09%   |
| Broadcom Limited                      | 78        | 2.92%   |
| Ralink                                | 20        | 0.75%   |
| Qualcomm                              | 18        | 0.67%   |
| TP-Link                               | 16        | 0.6%    |
| Dell                                  | 16        | 0.6%    |
| Ralink Technology                     | 14        | 0.52%   |
| Sierra Wireless                       | 12        | 0.45%   |
| ASUSTek Computer                      | 6         | 0.22%   |
| NetGear                               | 5         | 0.19%   |
| Hewlett-Packard                       | 4         | 0.15%   |
| FIBOCOM                               | 4         | 0.15%   |
| Qualcomm Atheros Communications       | 3         | 0.11%   |
| Edimax Technology                     | 3         | 0.11%   |
| Microsoft                             | 2         | 0.07%   |
| Linksys                               | 2         | 0.07%   |
| D-Link                                | 2         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.07%   |
| ZyDAS                                 | 1         | 0.04%   |
| Qualcomm Technologies                 | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| Arduino SA                            | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 162       | 6.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 121       | 4.5%    |
| Intel Wi-Fi 6 AX201                                                  | 116       | 4.32%   |
| Intel Wireless 8265 / 8275                                           | 114       | 4.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 94        | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 86        | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 79        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 77        | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 71        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 67        | 2.49%   |
| Intel Wireless 8260                                                  | 66        | 2.46%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 65        | 2.42%   |
| Intel Wireless 7265                                                  | 61        | 2.27%   |
| Intel Wireless 7260                                                  | 60        | 2.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 57        | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 56        | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 55        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 48        | 1.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 43        | 1.6%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 43        | 1.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 41        | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 41        | 1.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 39        | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 39        | 1.45%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 38        | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 37        | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 33        | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 31        | 1.15%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 31        | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                        | 29        | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 25        | 0.93%   |
| Intel Wireless 3165                                                  | 23        | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 20        | 0.74%   |
| Intel Centrino Advanced-N 6235                                       | 20        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 19        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 19        | 0.71%   |
| Intel Centrino Ultimate-N 6300                                       | 19        | 0.71%   |
| Intel Wireless 3160                                                  | 18        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 17        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 17        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1225      | 60.17%  |
| Intel                                  | 414       | 20.33%  |
| Qualcomm Atheros                       | 103       | 5.06%   |
| Broadcom                               | 82        | 4.03%   |
| ASIX Electronics                       | 42        | 2.06%   |
| Samsung Electronics                    | 23        | 1.13%   |
| Nvidia                                 | 21        | 1.03%   |
| Marvell Technology Group               | 18        | 0.88%   |
| DisplayLink                            | 17        | 0.83%   |
| Xiaomi                                 | 15        | 0.74%   |
| Lenovo                                 | 14        | 0.69%   |
| Broadcom Limited                       | 13        | 0.64%   |
| JMicron Technology                     | 9         | 0.44%   |
| OPPO Electronics                       | 7         | 0.34%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.25%   |
| Google                                 | 5         | 0.25%   |
| TP-Link                                | 4         | 0.2%    |
| Motorola PCS                           | 3         | 0.15%   |
| Hewlett-Packard                        | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.1%    |
| Huawei Technologies                    | 2         | 0.1%    |
| ASUSTek Computer                       | 2         | 0.1%    |
| Apple                                  | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Qualcomm                               | 1         | 0.05%   |
| NetGear                                | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 875       | 42.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 141       | 6.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 134       | 6.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 64        | 3.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 43        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 41        | 1.98%   |
| ASIX AX88179 Gigabit Ethernet                                          | 36        | 1.74%   |
| Intel Ethernet Connection I219-LM                                      | 35        | 1.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 29        | 1.4%    |
| Intel Ethernet Connection I217-LM                                      | 28        | 1.35%   |
| Realtek Killer E2600 GbE Controller                                    | 25        | 1.21%   |
| Intel Ethernet Connection (3) I218-LM                                  | 21        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 0.92%   |
| Nvidia MCP79 Ethernet                                                  | 19        | 0.92%   |
| Intel Ethernet Connection I218-LM                                      | 18        | 0.87%   |
| Intel Ethernet Connection (4) I219-V                                   | 17        | 0.82%   |
| Intel Ethernet Connection (13) I219-V                                  | 15        | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 14        | 0.68%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 14        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 14        | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 14        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 13        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13        | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 12        | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                                  | 12        | 0.58%   |
| Intel Ethernet Connection (16) I219-V                                  | 11        | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 11        | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 10        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 10        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 10        | 0.48%   |
| Intel Ethernet Connection I219-V                                       | 10        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                  | 10        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                   | 10        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 9         | 0.44%   |
| Intel Ethernet Connection (16) I219-LM                                 | 8         | 0.39%   |
| Intel Ethernet Connection (13) I219-LM                                 | 8         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 7         | 0.34%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 7         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2537      | 56.62%  |
| Ethernet | 1924      | 42.94%  |
| Modem    | 16        | 0.36%   |
| Unknown  | 4         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2166      | 79.54%  |
| Ethernet | 557       | 20.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1725      | 67.28%  |
| 1     | 804       | 31.36%  |
| 0     | 23        | 0.9%    |
| 3     | 12        | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1798      | 69.02%  |
| Yes  | 807       | 30.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1176      | 52.81%  |
| Realtek Semiconductor           | 230       | 10.33%  |
| Qualcomm Atheros Communications | 177       | 7.95%   |
| Apple                           | 148       | 6.65%   |
| IMC Networks                    | 138       | 6.2%    |
| Foxconn / Hon Hai               | 105       | 4.71%   |
| Lite-On Technology              | 76        | 3.41%   |
| Broadcom                        | 53        | 2.38%   |
| Dell                            | 22        | 0.99%   |
| Realtek                         | 15        | 0.67%   |
| Cambridge Silicon Radio         | 15        | 0.67%   |
| MediaTek                        | 13        | 0.58%   |
| Toshiba                         | 12        | 0.54%   |
| Hewlett-Packard                 | 10        | 0.45%   |
| Ralink                          | 8         | 0.36%   |
| USI                             | 5         | 0.22%   |
| Foxconn International           | 4         | 0.18%   |
| ASUSTek Computer                | 4         | 0.18%   |
| Opticis                         | 3         | 0.13%   |
| TP-Link                         | 2         | 0.09%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| Smart Modular Technologies      | 2         | 0.09%   |
| Ralink Technology               | 2         | 0.09%   |
| Fujitsu                         | 2         | 0.09%   |
| Micro Star International        | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 283       | 12.7%   |
| Intel Bluetooth wireless interface                  | 169       | 7.59%   |
| Intel Bluetooth Device                              | 161       | 7.23%   |
| Intel AX200 Bluetooth                               | 158       | 7.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 144       | 6.46%   |
| Realtek Bluetooth Radio                             | 137       | 6.15%   |
| Intel AX211 Bluetooth                               | 137       | 6.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 97        | 4.35%   |
| Apple Bluetooth Host Controller                     | 84        | 3.77%   |
| IMC Networks Wireless_Device                        | 67        | 3.01%   |
| Apple Bluetooth USB Host Controller                 | 51        | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                      | 38        | 1.71%   |
| Intel AX210 Bluetooth                               | 38        | 1.71%   |
| Realtek 802.11ac WLAN Adapter                       | 36        | 1.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 31        | 1.39%   |
| IMC Networks Bluetooth Radio                        | 30        | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                  | 28        | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 23        | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 0.99%   |
| IMC Networks Bluetooth Device                       | 21        | 0.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 21        | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 19        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.81%   |
| Lite-On Wireless_Device                             | 18        | 0.81%   |
| Lite-On Bluetooth Device                            | 16        | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 16        | 0.72%   |
| Realtek Bluetooth Radio                             | 15        | 0.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.63%   |
| MediaTek Wireless_Device                            | 13        | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.36%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.36%   |
| Lite-On Bluetooth Radio                             | 8         | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.36%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 7         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1917      | 55.65%  |
| AMD                                  | 644       | 18.69%  |
| Nvidia                               | 621       | 18.03%  |
| C-Media Electronics                  | 25        | 0.73%   |
| Logitech                             | 24        | 0.7%    |
| Lenovo                               | 19        | 0.55%   |
| GN Netcom                            | 17        | 0.49%   |
| Realtek Semiconductor                | 15        | 0.44%   |
| Generalplus Technology               | 14        | 0.41%   |
| Kingston Technology                  | 13        | 0.38%   |
| Sony                                 | 11        | 0.32%   |
| JMTek                                | 11        | 0.32%   |
| Apple                                | 10        | 0.29%   |
| Hewlett-Packard                      | 9         | 0.26%   |
| SteelSeries ApS                      | 8         | 0.23%   |
| Texas Instruments                    | 7         | 0.2%    |
| Plantronics                          | 7         | 0.2%    |
| Focusrite-Novation                   | 7         | 0.2%    |
| Razer USA                            | 6         | 0.17%   |
| Corsair                              | 6         | 0.17%   |
| DSEA A/S                             | 4         | 0.12%   |
| ASUSTek Computer                     | 4         | 0.12%   |
| FiiO Electronics Technology          | 3         | 0.09%   |
| Turtle Beach                         | 2         | 0.06%   |
| TerraTec Electronic                  | 2         | 0.06%   |
| Samson Technologies                  | 2         | 0.06%   |
| Microsoft                            | 2         | 0.06%   |
| Dell                                 | 2         | 0.06%   |
| Creative Technology                  | 2         | 0.06%   |
| Bose                                 | 2         | 0.06%   |
| Blue Microphones                     | 2         | 0.06%   |
| Yamaha                               | 1         | 0.03%   |
| THX                                  | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| STMicroelectronics                   | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Reloop                               | 1         | 0.03%   |
| Plugable                             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 493       | 11.62%  |
| Intel Sunrise Point-LP HD Audio                                            | 269       | 6.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 250       | 5.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 154       | 3.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 150       | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 144       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 137       | 3.23%   |
| Nvidia Audio device                                                        | 133       | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 117       | 2.76%   |
| Intel Broadwell-U Audio Controller                                         | 99        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 99        | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 98        | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 97        | 2.29%   |
| Intel 8 Series HD Audio Controller                                         | 97        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 94        | 2.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 79        | 1.86%   |
| Intel Comet Lake PCH cAVS                                                  | 78        | 1.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 73        | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 71        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 69        | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 68        | 1.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 65        | 1.53%   |
| Nvidia GA104 High Definition Audio Controller                              | 63        | 1.49%   |
| AMD FCH Azalia Controller                                                  | 58        | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 57        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 54        | 1.27%   |
| Intel CM238 HD Audio Controller                                            | 53        | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 50        | 1.18%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 43        | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 38        | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 36        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 33        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 32        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 29        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 27        | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 27        | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 27        | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 22        | 0.52%   |
| Nvidia MCP79 High Definition Audio                                         | 21        | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 21        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 301       | 30.04%  |
| SK hynix                                | 230       | 22.95%  |
| Micron Technology                       | 162       | 16.17%  |
| Kingston                                | 65        | 6.49%   |
| Crucial                                 | 53        | 5.29%   |
| Unknown                                 | 22        | 2.2%    |
| Unknown                                 | 21        | 2.1%    |
| A-DATA Technology                       | 16        | 1.6%    |
| Corsair                                 | 14        | 1.4%    |
| Smart                                   | 13        | 1.3%    |
| Ramaxel Technology                      | 13        | 1.3%    |
| Team                                    | 10        | 1%      |
| Neo Forza                               | 9         | 0.9%    |
| Goldkey                                 | 9         | 0.9%    |
| G.Skill                                 | 9         | 0.9%    |
| Elpida                                  | 9         | 0.9%    |
| Unknown (ABCD)                          | 5         | 0.5%    |
| PNY                                     | 5         | 0.5%    |
| Nanya Technology                        | 4         | 0.4%    |
| Transcend                               | 3         | 0.3%    |
| Timetec                                 | 3         | 0.3%    |
| GSkill                                  | 3         | 0.3%    |
| Teikon                                  | 2         | 0.2%    |
| Smart Brazil                            | 2         | 0.2%    |
| Gold Key                                | 2         | 0.2%    |
| ChangXin Memory                         | 2         | 0.2%    |
| Avant                                   | 2         | 0.2%    |
| Wilk                                    | 1         | 0.1%    |
| Unknown (8A02)                          | 1         | 0.1%    |
| Unknown (0x0CAB)                        | 1         | 0.1%    |
| Unknown (0x0C26)                        | 1         | 0.1%    |
| Unknown (09B6)                          | 1         | 0.1%    |
| Unknown (09A4)                          | 1         | 0.1%    |
| Silicon Power Computer & Communications | 1         | 0.1%    |
| Silicon Power                           | 1         | 0.1%    |
| Patriot Memory (PDP Systems)            | 1         | 0.1%    |
| Kllisre                                 | 1         | 0.1%    |
| HT Micron                               | 1         | 0.1%    |
| CSX                                     | 1         | 0.1%    |
| Apacer                                  | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 24        | 2.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 2.19%   |
| Unknown                                                          | 22        | 2.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 1.43%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.24%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 13        | 1.24%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 0.95%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.86%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.86%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 0.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.76%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 8         | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.67%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.67%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 7         | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.67%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.57%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s           | 6         | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.57%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 6         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.57%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 6         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.48%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s         | 5         | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.48%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 5         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.48%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 5         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 519       | 60.77%  |
| DDR3   | 123       | 14.4%   |
| DDR5   | 77        | 9.02%   |
| LPDDR5 | 50        | 5.85%   |
| LPDDR4 | 49        | 5.74%   |
| LPDDR3 | 28        | 3.28%   |
| SDRAM  | 5         | 0.59%   |
| DDR2   | 3         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 726       | 83.16%  |
| Row Of Chips | 138       | 15.81%  |
| Chip         | 4         | 0.46%   |
| Unknown      | 4         | 0.46%   |
| DIMM         | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 413       | 44.6%   |
| 16384 | 212       | 22.89%  |
| 4096  | 193       | 20.84%  |
| 32768 | 63        | 6.8%    |
| 2048  | 40        | 4.32%   |
| 1024  | 5         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 301       | 33.04%  |
| 2667  | 177       | 19.43%  |
| 1600  | 91        | 9.99%   |
| 4800  | 58        | 6.37%   |
| 2400  | 54        | 5.93%   |
| 6400  | 48        | 5.27%   |
| 2133  | 43        | 4.72%   |
| 4267  | 27        | 2.96%   |
| 5600  | 18        | 1.98%   |
| 1867  | 13        | 1.43%   |
| 3266  | 12        | 1.32%   |
| 1334  | 12        | 1.32%   |
| 1333  | 10        | 1.1%    |
| 8400  | 9         | 0.99%   |
| 4266  | 7         | 0.77%   |
| 1067  | 7         | 0.77%   |
| 3733  | 4         | 0.44%   |
| 2933  | 4         | 0.44%   |
| 2048  | 3         | 0.33%   |
| 800   | 3         | 0.33%   |
| 5200  | 2         | 0.22%   |
| 4199  | 2         | 0.22%   |
| 7500  | 1         | 0.11%   |
| 5500  | 1         | 0.11%   |
| 3000  | 1         | 0.11%   |
| 1200  | 1         | 0.11%   |
| 1066  | 1         | 0.11%   |
| 666   | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 30.77%  |
| Canon               | 3         | 23.08%  |
| Xerox               | 1         | 7.69%   |
| Seiko Epson         | 1         | 7.69%   |
| Samsung Electronics | 1         | 7.69%   |
| ICS Advent          | 1         | 7.69%   |
| Dymo-CoStar         | 1         | 7.69%   |
| Brother Industries  | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon PIXMA MX920 Series        | 2         | 15.38%  |
| Xerox B215                      | 1         | 7.69%   |
| Seiko Epson L382 Series         | 1         | 7.69%   |
| Samsung M2020 Series            | 1         | 7.69%   |
| ICS Advent Parallel Adapter     | 1         | 7.69%   |
| HP OfficeJet 3830 series        | 1         | 7.69%   |
| HP Ink Tank Wireless 410 series | 1         | 7.69%   |
| HP DeskJet Plus 4100 series     | 1         | 7.69%   |
| HP Color LaserJet CP2025dn      | 1         | 7.69%   |
| Dymo-CoStar LabelWriter 450     | 1         | 7.69%   |
| Canon E400 series               | 1         | 7.69%   |
| Brother HL-L2370DW series       | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 502       | 21.55%  |
| IMC Networks                           | 252       | 10.82%  |
| Microdia                               | 218       | 9.36%   |
| Bison Electronics                      | 191       | 8.2%    |
| Realtek Semiconductor                  | 178       | 7.64%   |
| Quanta                                 | 152       | 6.52%   |
| Sunplus Innovation Technology          | 118       | 5.06%   |
| Apple                                  | 104       | 4.46%   |
| Luxvisions Innotech Limited            | 81        | 3.48%   |
| Acer                                   | 67        | 2.88%   |
| Cheng Uei Precision Industry (Foxlink) | 63        | 2.7%    |
| Syntek                                 | 61        | 2.62%   |
| Lite-On Technology                     | 52        | 2.23%   |
| Suyin                                  | 39        | 1.67%   |
| Sonix Technology                       | 36        | 1.55%   |
| Logitech                               | 30        | 1.29%   |
| Silicon Motion                         | 26        | 1.12%   |
| Samsung Electronics                    | 16        | 0.69%   |
| SunplusIT                              | 15        | 0.64%   |
| Alcor Micro                            | 14        | 0.6%    |
| Z-Star Microelectronics                | 8         | 0.34%   |
| Ricoh                                  | 8         | 0.34%   |
| Microsoft                              | 8         | 0.34%   |
| Shinetech                              | 7         | 0.3%    |
| Primax Electronics                     | 7         | 0.3%    |
| Razer USA                              | 5         | 0.21%   |
| Generalplus Technology                 | 5         | 0.21%   |
| Lenovo                                 | 4         | 0.17%   |
| icSpring                               | 4         | 0.17%   |
| ALi                                    | 4         | 0.17%   |
| Tobii Technology AB                    | 3         | 0.13%   |
| Importek                               | 3         | 0.13%   |
| HRY                                    | 3         | 0.13%   |
| AVerMedia Technologies                 | 3         | 0.13%   |
| Y Media                                | 2         | 0.09%   |
| Tripath Technology                     | 2         | 0.09%   |
| Sunplus IT                             | 2         | 0.09%   |
| OmniVision Technologies                | 2         | 0.09%   |
| Intel                                  | 2         | 0.09%   |
| Goodong                                | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 133       | 5.68%   |
| Microdia Integrated_Webcam_HD                       | 116       | 4.95%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 86        | 3.67%   |
| Realtek Integrated_Webcam_HD                        | 69        | 2.95%   |
| IMC Networks Integrated Camera                      | 67        | 2.86%   |
| Bison BisonCam,NB Pro                               | 53        | 2.26%   |
| Chicony HD WebCam                                   | 48        | 2.05%   |
| Syntek Integrated Camera                            | 44        | 1.88%   |
| Chicony USB2.0 Camera                               | 38        | 1.62%   |
| Bison HD Webcam                                     | 36        | 1.54%   |
| Quanta HD User Facing                               | 34        | 1.45%   |
| Sunplus Integrated_Webcam_HD                        | 33        | 1.41%   |
| Bison Integrated Camera                             | 33        | 1.41%   |
| Acer Integrated Camera                              | 33        | 1.41%   |
| Apple Built-in iSight                               | 31        | 1.32%   |
| Apple FaceTime HD Camera                            | 30        | 1.28%   |
| Chicony HP HD Camera                                | 25        | 1.07%   |
| Sonix USB2.0 HD UVC WebCam                          | 24        | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 24        | 1.02%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 24        | 1.02%   |
| Realtek USB Camera                                  | 23        | 0.98%   |
| Quanta HP HD Camera                                 | 22        | 0.94%   |
| Lite-On Integrated Camera                           | 22        | 0.94%   |
| Chicony HD User Facing                              | 21        | 0.9%    |
| Luxvisions Innotech Limited Integrated Camera       | 20        | 0.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 20        | 0.85%   |
| Microdia Integrated Webcam                          | 19        | 0.81%   |
| Bison SunplusIT Integrated Camera                   | 19        | 0.81%   |
| Quanta HP TrueVision HD Camera                      | 18        | 0.77%   |
| Quanta ACER HD User Facing                          | 17        | 0.73%   |
| Chicony HP Truevision HD camera                     | 17        | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode)             | 16        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 0.64%   |
| Realtek Integrated Webcam                           | 14        | 0.6%    |
| Chicony Integrated IR Camera                        | 14        | 0.6%    |
| Chicony Integrated Camera (1280x720@30)             | 14        | 0.6%    |
| Quanta HP Wide Vision HD Camera                     | 13        | 0.56%   |
| Luxvisions Innotech Limited HP HD Camera            | 13        | 0.56%   |
| IMC Networks HD Camera                              | 13        | 0.56%   |
| Chicony HP Wide Vision HD Camera                    | 13        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 164       | 36.61%  |
| Validity Sensors                   | 122       | 27.23%  |
| Shenzhen Goodix Technology         | 73        | 16.29%  |
| Elan Microelectronics              | 26        | 5.8%    |
| Upek                               | 19        | 4.24%   |
| LighTuning Technology              | 18        | 4.02%   |
| AuthenTec                          | 9         | 2.01%   |
| Realtek USB2.0 Finger Print Bridge | 8         | 1.79%   |
| Focal-systems.Corp                 | 5         | 1.12%   |
| HOLTEK                             | 4         | 0.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 51        | 11.38%  |
| Shenzhen Goodix  Fingerprint Device                                        | 42        | 9.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 6.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 29        | 6.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.24%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 4.02%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 3.79%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.9%    |
| Elan ELAN:Fingerprint                                                      | 13        | 2.9%    |
| Elan ELAN:ARM-M4                                                           | 13        | 2.9%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 11        | 2.46%   |
| Synaptics WBDI Device                                                      | 11        | 2.46%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 10        | 2.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 2.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.01%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.79%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 1.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.79%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 8         | 1.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.56%   |
| Synaptics UWP WBDI Device                                                  | 7         | 1.56%   |
| Unknown                                                                    | 7         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.34%   |
| Synaptics TouchPad                                                         | 6         | 1.34%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.34%   |
| Validity Sensors VFS491                                                    | 5         | 1.12%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.12%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.89%   |
| Synaptics  WBDI                                                            | 4         | 0.89%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 0.89%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.67%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.45%   |
| AuthenTec AES2810                                                          | 2         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 86        | 56.58%  |
| Alcor Micro           | 44        | 28.95%  |
| O2 Micro              | 10        | 6.58%   |
| Lenovo                | 5         | 3.29%   |
| Upek                  | 4         | 2.63%   |
| OmniKey               | 1         | 0.66%   |
| Gemalto (was Gemplus) | 1         | 0.66%   |
| Clay Logic            | 1         | 0.66%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 28.95%  |
| Broadcom 58200                                                               | 31        | 20.39%  |
| Broadcom 5880                                                                | 24        | 15.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.24%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 5.92%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.29%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.63%   |
| OmniKey CardMan 4321                                                         | 1         | 0.66%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.66%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.66%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.66%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.66%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1530      | 58.44%  |
| 1     | 879       | 33.58%  |
| 2     | 184       | 7.03%   |
| 3     | 20        | 0.76%   |
| 4     | 4         | 0.15%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 434       | 33.62%  |
| Multimedia controller    | 213       | 16.5%   |
| Graphics card            | 153       | 11.85%  |
| Chipcard                 | 145       | 11.23%  |
| Net/wireless             | 130       | 10.07%  |
| Camera                   | 71        | 5.5%    |
| Bluetooth                | 59        | 4.57%   |
| Sound                    | 17        | 1.32%   |
| Storage                  | 14        | 1.08%   |
| Net/ethernet             | 14        | 1.08%   |
| Network                  | 10        | 0.77%   |
| Modem                    | 10        | 0.77%   |
| Card reader              | 10        | 0.77%   |
| Communication controller | 8         | 0.62%   |
| Storage/ide              | 2         | 0.15%   |
| Storage/nvme             | 1         | 0.08%   |


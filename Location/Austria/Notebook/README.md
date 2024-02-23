Linux in Austria - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

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

Total: 1706

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire VN7-592G             | [95f618bdeb](https://linux-hardware.org/?probe=95f618bdeb) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cb15afccd0](https://linux-hardware.org/?probe=cb15afccd0) | Feb 02, 2024 |
| HP            | EliteBook 8460p             | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c62ec1a167](https://linux-hardware.org/?probe=c62ec1a167) | Jan 31, 2024 |
| HP            | Laptop 17-ak0xx             | [0b511ae973](https://linux-hardware.org/?probe=0b511ae973) | Jan 30, 2024 |
| Acer          | Aspire A114-31              | [9c767147fc](https://linux-hardware.org/?probe=9c767147fc) | Jan 29, 2024 |
| Dell          | Latitude 5290 2-in-1        | [5f28b98de6](https://linux-hardware.org/?probe=5f28b98de6) | Jan 27, 2024 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [b1abb90a3f](https://linux-hardware.org/?probe=b1abb90a3f) | Jan 25, 2024 |
| Hampoo        | Cherry Trail CR             | [1c0466fe53](https://linux-hardware.org/?probe=1c0466fe53) | Jan 25, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | [356b235b8b](https://linux-hardware.org/?probe=356b235b8b) | Jan 24, 2024 |
| Acer          | Aspire A114-31              | [f08742602c](https://linux-hardware.org/?probe=f08742602c) | Jan 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [09cb74358d](https://linux-hardware.org/?probe=09cb74358d) | Jan 23, 2024 |
| Dell          | Latitude E7440              | [4e05575433](https://linux-hardware.org/?probe=4e05575433) | Jan 22, 2024 |
| HP            | EliteBook 8460p             | [3055120492](https://linux-hardware.org/?probe=3055120492) | Jan 22, 2024 |
| Dell          | Latitude 5490               | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| Dell          | Latitude 5290 2-in-1        | [a06ba088e5](https://linux-hardware.org/?probe=a06ba088e5) | Jan 21, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [aa40e37f96](https://linux-hardware.org/?probe=aa40e37f96) | Jan 19, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | [5c18e1a4bc](https://linux-hardware.org/?probe=5c18e1a4bc) | Jan 18, 2024 |
| Acer          | Aspire A515-44G             | [6d540c596b](https://linux-hardware.org/?probe=6d540c596b) | Jan 17, 2024 |
| Fujitsu       | LIFEBOOK U7613              | [9e38b7368d](https://linux-hardware.org/?probe=9e38b7368d) | Jan 14, 2024 |
| SGIN          | M15                         | [022c34815c](https://linux-hardware.org/?probe=022c34815c) | Jan 12, 2024 |
| HP            | EliteBook 8470p             | [4ed2b7527c](https://linux-hardware.org/?probe=4ed2b7527c) | Jan 11, 2024 |
| Lenovo        | V15-ADA 82C7                | [e12995730c](https://linux-hardware.org/?probe=e12995730c) | Jan 11, 2024 |
| Lenovo        | ThinkPad W530 24474LG       | [7c1349e97d](https://linux-hardware.org/?probe=7c1349e97d) | Jan 10, 2024 |
| Valve         | Jupiter                     | [3462a5ad9f](https://linux-hardware.org/?probe=3462a5ad9f) | Jan 09, 2024 |
| Valve         | Jupiter                     | [eac99b5d0a](https://linux-hardware.org/?probe=eac99b5d0a) | Jan 09, 2024 |
| HP            | EliteBook 8440p             | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| SGIN          | M15                         | [b0b7267ad7](https://linux-hardware.org/?probe=b0b7267ad7) | Jan 08, 2024 |
| Valve         | Galileo                     | [e71ef9c36d](https://linux-hardware.org/?probe=e71ef9c36d) | Jan 07, 2024 |
| ASUSTek       | X75VC                       | [348451dd8f](https://linux-hardware.org/?probe=348451dd8f) | Jan 06, 2024 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [6e0b491486](https://linux-hardware.org/?probe=6e0b491486) | Jan 05, 2024 |
| Notebook      | P7xxTM1                     | [9ed3be2a69](https://linux-hardware.org/?probe=9ed3be2a69) | Jan 04, 2024 |
| Fujitsu       | LIFEBOOK U7413              | [b709a3069c](https://linux-hardware.org/?probe=b709a3069c) | Jan 03, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2cf15e0bf0](https://linux-hardware.org/?probe=2cf15e0bf0) | Jan 02, 2024 |
| Dell          | Latitude 5540               | [96e1aad010](https://linux-hardware.org/?probe=96e1aad010) | Jan 02, 2024 |
| ASUSTek       | X75VC                       | [6e3608409f](https://linux-hardware.org/?probe=6e3608409f) | Jan 02, 2024 |
| ASUSTek       | X75VC                       | [c80297163a](https://linux-hardware.org/?probe=c80297163a) | Jan 02, 2024 |
| Medion        | E11202                      | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| ASUSTek       | X75VC                       | [cb47b15eb9](https://linux-hardware.org/?probe=cb47b15eb9) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [c0587a6f3f](https://linux-hardware.org/?probe=c0587a6f3f) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | [92906e6c95](https://linux-hardware.org/?probe=92906e6c95) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | [e2ebd9354f](https://linux-hardware.org/?probe=e2ebd9354f) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3b6d015d5a](https://linux-hardware.org/?probe=3b6d015d5a) | Dec 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [fb4b958ae6](https://linux-hardware.org/?probe=fb4b958ae6) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | [ab4628dffe](https://linux-hardware.org/?probe=ab4628dffe) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | [9a7ee6f89e](https://linux-hardware.org/?probe=9a7ee6f89e) | Dec 29, 2023 |
| Medion        | E11202                      | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| Medion        | E7220                       | [8a10d2f8d1](https://linux-hardware.org/?probe=8a10d2f8d1) | Dec 28, 2023 |
| Acer          | Swift SF314-56              | [d230832e06](https://linux-hardware.org/?probe=d230832e06) | Dec 28, 2023 |
| HUAWEI        | BOD-WXX9                    | [d8e2dd481d](https://linux-hardware.org/?probe=d8e2dd481d) | Dec 28, 2023 |
| Apple         | MacBookAir6,2               | [eaa0ff8b0c](https://linux-hardware.org/?probe=eaa0ff8b0c) | Dec 27, 2023 |
| Apple         | MacBookAir6,2               | [4a28e0da3c](https://linux-hardware.org/?probe=4a28e0da3c) | Dec 27, 2023 |
| Acer          | Aspire A114-31              | [dfa2a6458d](https://linux-hardware.org/?probe=dfa2a6458d) | Dec 27, 2023 |
| Lenovo        | ThinkPad W530 24474LG       | [180b4817c4](https://linux-hardware.org/?probe=180b4817c4) | Dec 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [77553a2b0e](https://linux-hardware.org/?probe=77553a2b0e) | Dec 26, 2023 |
| Dell          | XPS 13 9310                 | [78b73643ff](https://linux-hardware.org/?probe=78b73643ff) | Dec 23, 2023 |
| Lenovo        | ThinkPad T500 20564RG       | [e17f4b51d6](https://linux-hardware.org/?probe=e17f4b51d6) | Dec 22, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [72084f8af0](https://linux-hardware.org/?probe=72084f8af0) | Dec 22, 2023 |
| Medion        | E11202                      | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | BU201LA                     | [2985f7a222](https://linux-hardware.org/?probe=2985f7a222) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [5d41a0e0d5](https://linux-hardware.org/?probe=5d41a0e0d5) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [ad67aeb103](https://linux-hardware.org/?probe=ad67aeb103) | Dec 22, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [62624ca97b](https://linux-hardware.org/?probe=62624ca97b) | Dec 21, 2023 |
| Apple         | MacBookPro9,2               | [da159da872](https://linux-hardware.org/?probe=da159da872) | Dec 20, 2023 |
| Valve         | Jupiter                     | [091511a6c2](https://linux-hardware.org/?probe=091511a6c2) | Dec 20, 2023 |
| Apple         | MacBookAir6,2               | [ef17f12758](https://linux-hardware.org/?probe=ef17f12758) | Dec 20, 2023 |
| Apple         | MacBook5,1                  | [9839cacb3a](https://linux-hardware.org/?probe=9839cacb3a) | Dec 19, 2023 |
| Apple         | MacBook5,1                  | [8268b72759](https://linux-hardware.org/?probe=8268b72759) | Dec 19, 2023 |
| HP            | Unknown                     | [43fae5ce53](https://linux-hardware.org/?probe=43fae5ce53) | Dec 19, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | [020e3af833](https://linux-hardware.org/?probe=020e3af833) | Dec 18, 2023 |
| Dell          | Latitude E5550              | [671595a2e5](https://linux-hardware.org/?probe=671595a2e5) | Dec 18, 2023 |
| Dell          | Latitude E7440              | [c2dce135e4](https://linux-hardware.org/?probe=c2dce135e4) | Dec 18, 2023 |
| ASUSTek       | K53SD                       | [4b43240ccd](https://linux-hardware.org/?probe=4b43240ccd) | Dec 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f64fa9a501](https://linux-hardware.org/?probe=f64fa9a501) | Dec 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [56e95fc392](https://linux-hardware.org/?probe=56e95fc392) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [933e5b48f2](https://linux-hardware.org/?probe=933e5b48f2) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [9df7fd000e](https://linux-hardware.org/?probe=9df7fd000e) | Dec 16, 2023 |
| Dell          | Latitude E5550              | [dc16864fb6](https://linux-hardware.org/?probe=dc16864fb6) | Dec 15, 2023 |
| Dell          | Precision 5680              | [1e063996da](https://linux-hardware.org/?probe=1e063996da) | Dec 14, 2023 |
| HP            | ZBook 15 G6                 | [1d935cbf02](https://linux-hardware.org/?probe=1d935cbf02) | Dec 13, 2023 |
| HP            | ZBook 15 G6                 | [3deb250922](https://linux-hardware.org/?probe=3deb250922) | Dec 13, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [ba6f8efad6](https://linux-hardware.org/?probe=ba6f8efad6) | Dec 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b949261978](https://linux-hardware.org/?probe=b949261978) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK U7413              | [088a24eb7d](https://linux-hardware.org/?probe=088a24eb7d) | Dec 13, 2023 |
| Toshiba       | Satellite Pro C660          | [63cf57fa53](https://linux-hardware.org/?probe=63cf57fa53) | Dec 12, 2023 |
| Lenovo        | ThinkPad L470 20J5S1FW00    | [9ea0dccce0](https://linux-hardware.org/?probe=9ea0dccce0) | Dec 11, 2023 |
| HP            | Compaq Presario CQ60        | [0bf86693bc](https://linux-hardware.org/?probe=0bf86693bc) | Dec 11, 2023 |
| Lenovo        | Yoga Slim 6 14IRH8 83E0     | [a8b759b4a8](https://linux-hardware.org/?probe=a8b759b4a8) | Dec 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [afd68e777f](https://linux-hardware.org/?probe=afd68e777f) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [9a8395654c](https://linux-hardware.org/?probe=9a8395654c) | Dec 06, 2023 |
| Samsung       | R580/R590                   | [89f285aacc](https://linux-hardware.org/?probe=89f285aacc) | Dec 05, 2023 |
| ASUSTek       | X751LN                      | [72bc3137f4](https://linux-hardware.org/?probe=72bc3137f4) | Dec 05, 2023 |
| HP            | Notebook                    | [4f0e8aad8c](https://linux-hardware.org/?probe=4f0e8aad8c) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [452f677f7f](https://linux-hardware.org/?probe=452f677f7f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [1f6674a16b](https://linux-hardware.org/?probe=1f6674a16b) | Dec 03, 2023 |
| MSI           | GE72 6QF                    | [2cce4d92fe](https://linux-hardware.org/?probe=2cce4d92fe) | Dec 02, 2023 |
| Lenovo        | ThinkPad T470 20HDA01RKR    | [f7fb5f1e5d](https://linux-hardware.org/?probe=f7fb5f1e5d) | Dec 01, 2023 |
| Apple         | MacBookPro12,1              | [d956dae97a](https://linux-hardware.org/?probe=d956dae97a) | Nov 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [bfa4423c0f](https://linux-hardware.org/?probe=bfa4423c0f) | Nov 30, 2023 |
| Lenovo        | ThinkPad T470 20HDA01RKR    | [46a5719afb](https://linux-hardware.org/?probe=46a5719afb) | Nov 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ad9b9e5fd1](https://linux-hardware.org/?probe=ad9b9e5fd1) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | [970202f2a1](https://linux-hardware.org/?probe=970202f2a1) | Nov 30, 2023 |
| Notebook      | P9XXEN_EF_ED                | [cd5316e290](https://linux-hardware.org/?probe=cd5316e290) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | [29e5da6013](https://linux-hardware.org/?probe=29e5da6013) | Nov 29, 2023 |
| HP            | EliteBook 840 G1            | [bb1d8fb09e](https://linux-hardware.org/?probe=bb1d8fb09e) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [a638d25ff0](https://linux-hardware.org/?probe=a638d25ff0) | Nov 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [8c51aa422e](https://linux-hardware.org/?probe=8c51aa422e) | Nov 27, 2023 |
| Acer          | Aspire A114-31              | [43921895ea](https://linux-hardware.org/?probe=43921895ea) | Nov 27, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [2a870ea79e](https://linux-hardware.org/?probe=2a870ea79e) | Nov 27, 2023 |
| Toshiba       | Satellite Z30-B             | [80f2583617](https://linux-hardware.org/?probe=80f2583617) | Nov 27, 2023 |
| Fujitsu       | LIFEBOOK U7413              | [b8569ba845](https://linux-hardware.org/?probe=b8569ba845) | Nov 27, 2023 |
| VALE          | Notebook Classic C170       | [fcb0ab721b](https://linux-hardware.org/?probe=fcb0ab721b) | Nov 26, 2023 |
| HP            | EliteBook 8570p             | [f31c8412d9](https://linux-hardware.org/?probe=f31c8412d9) | Nov 26, 2023 |
| ASUSTek       | K53SD                       | [e7c6d5b018](https://linux-hardware.org/?probe=e7c6d5b018) | Nov 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [e225477a30](https://linux-hardware.org/?probe=e225477a30) | Nov 24, 2023 |
| Apple         | MacBookPro11,5              | [a89e3b5a9d](https://linux-hardware.org/?probe=a89e3b5a9d) | Nov 24, 2023 |
| Apple         | MacBookPro11,5              | [52ff8830e8](https://linux-hardware.org/?probe=52ff8830e8) | Nov 24, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [7e25b00cb4](https://linux-hardware.org/?probe=7e25b00cb4) | Nov 22, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [43be1d8514](https://linux-hardware.org/?probe=43be1d8514) | Nov 21, 2023 |
| Apple         | MacBook3,1                  | [d73c12597f](https://linux-hardware.org/?probe=d73c12597f) | Nov 21, 2023 |
| HUAWEI        | CREFG-XX                    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [69d60bac42](https://linux-hardware.org/?probe=69d60bac42) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Dell          | XPS 13 9310                 | [ee45badecb](https://linux-hardware.org/?probe=ee45badecb) | Nov 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [2f1ba470f6](https://linux-hardware.org/?probe=2f1ba470f6) | Nov 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [f3170951f8](https://linux-hardware.org/?probe=f3170951f8) | Nov 18, 2023 |
| Fujitsu       | LIFEBOOK U7413              | [62b13a5829](https://linux-hardware.org/?probe=62b13a5829) | Nov 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [56ae69a7dc](https://linux-hardware.org/?probe=56ae69a7dc) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Lenovo        | ThinkPad E485 20KU000ACD    | [e03dd77d39](https://linux-hardware.org/?probe=e03dd77d39) | Nov 16, 2023 |
| Notebook      | P9XXEN_EF_ED                | [9119b16d75](https://linux-hardware.org/?probe=9119b16d75) | Nov 15, 2023 |
| Notebook      | P9XXEN_EF_ED                | [ac5c2d0218](https://linux-hardware.org/?probe=ac5c2d0218) | Nov 15, 2023 |
| Fujitsu       | LIFEBOOK U7413              | [b5ac0ee2ca](https://linux-hardware.org/?probe=b5ac0ee2ca) | Nov 13, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [feaa9f3eac](https://linux-hardware.org/?probe=feaa9f3eac) | Nov 11, 2023 |
| HP            | Pavilion dv7                | [bd4b3a096e](https://linux-hardware.org/?probe=bd4b3a096e) | Nov 10, 2023 |
| Fujitsu       | LIFEBOOK S710               | [ab1560cd77](https://linux-hardware.org/?probe=ab1560cd77) | Nov 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [4eb5901f8c](https://linux-hardware.org/?probe=4eb5901f8c) | Nov 08, 2023 |
| ASUSTek       | GL702VMK                    | [4cb218a4f4](https://linux-hardware.org/?probe=4cb218a4f4) | Nov 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed6ede63bc](https://linux-hardware.org/?probe=ed6ede63bc) | Nov 07, 2023 |
| HP            | ProBook 6570b               | [d9cfeee9df](https://linux-hardware.org/?probe=d9cfeee9df) | Nov 06, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | ProBook 430 G1              | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [30a0e0602f](https://linux-hardware.org/?probe=30a0e0602f) | Nov 04, 2023 |
| ASUSTek       | K53SD                       | [e26ed8b740](https://linux-hardware.org/?probe=e26ed8b740) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S710               | [b0ee1e5f32](https://linux-hardware.org/?probe=b0ee1e5f32) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S710               | [a8ae4206d4](https://linux-hardware.org/?probe=a8ae4206d4) | Oct 31, 2023 |
| MSI           | Modern 15 A11M              | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| Acer          | Aspire E1-572G              | [ebfb310a2d](https://linux-hardware.org/?probe=ebfb310a2d) | Oct 23, 2023 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [c096ac6500](https://linux-hardware.org/?probe=c096ac6500) | Oct 22, 2023 |
| HP            | Pavilion dv7                | [d2beead33c](https://linux-hardware.org/?probe=d2beead33c) | Oct 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [686e5c87a9](https://linux-hardware.org/?probe=686e5c87a9) | Oct 18, 2023 |
| MSI           | Prestige 14H B12UCX         | [17314417bf](https://linux-hardware.org/?probe=17314417bf) | Oct 17, 2023 |
| Unknown       | Unknown                     | [f776cdb186](https://linux-hardware.org/?probe=f776cdb186) | Oct 17, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [67ad226870](https://linux-hardware.org/?probe=67ad226870) | Oct 17, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | [5298e96c35](https://linux-hardware.org/?probe=5298e96c35) | Oct 13, 2023 |
| Packard Be... | EasyNote ENTG81BA           | [f25cb1517e](https://linux-hardware.org/?probe=f25cb1517e) | Oct 12, 2023 |
| AMI           | Intel                       | [e60ced0b11](https://linux-hardware.org/?probe=e60ced0b11) | Oct 12, 2023 |
| AMI           | Intel                       | [4b7c1bc00c](https://linux-hardware.org/?probe=4b7c1bc00c) | Oct 12, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [7108bb9955](https://linux-hardware.org/?probe=7108bb9955) | Oct 10, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [7e264895bf](https://linux-hardware.org/?probe=7e264895bf) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [f91905858e](https://linux-hardware.org/?probe=f91905858e) | Oct 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRC... | [a5e4eeba7f](https://linux-hardware.org/?probe=a5e4eeba7f) | Oct 10, 2023 |
| HP            | Notebook                    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| HP            | Notebook                    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [3a5617ed7c](https://linux-hardware.org/?probe=3a5617ed7c) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [fb307526fa](https://linux-hardware.org/?probe=fb307526fa) | Oct 01, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [411e8279da](https://linux-hardware.org/?probe=411e8279da) | Oct 01, 2023 |
| Acer          | Aspire F5-573G              | [dea46b2302](https://linux-hardware.org/?probe=dea46b2302) | Sep 29, 2023 |
| HP            | EliteBook 850 G1            | [35f0e18f04](https://linux-hardware.org/?probe=35f0e18f04) | Sep 28, 2023 |
| Toshiba       | Satellite L550              | [d93c40647f](https://linux-hardware.org/?probe=d93c40647f) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [0b8e5fc8d0](https://linux-hardware.org/?probe=0b8e5fc8d0) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| HP            | 350 G2                      | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Sony          | VPCEH2J1E                   | [2a09805fe9](https://linux-hardware.org/?probe=2a09805fe9) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [ddac5bba05](https://linux-hardware.org/?probe=ddac5bba05) | Sep 23, 2023 |
| Dell          | Latitude E7270              | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| HP            | EliteBook 840 G6            | [10cd0244af](https://linux-hardware.org/?probe=10cd0244af) | Sep 23, 2023 |
| HP            | ProBook 4515s               | [0b755bf978](https://linux-hardware.org/?probe=0b755bf978) | Sep 22, 2023 |
| Acer          | Aspire A114-31              | [968cd24afa](https://linux-hardware.org/?probe=968cd24afa) | Sep 22, 2023 |
| AMI           | Intel                       | [687044ba01](https://linux-hardware.org/?probe=687044ba01) | Sep 21, 2023 |
| Toshiba       | Satellite L550              | [f55adbf4eb](https://linux-hardware.org/?probe=f55adbf4eb) | Sep 20, 2023 |
| Acer          | Aspire E1-572G              | [139fc573bf](https://linux-hardware.org/?probe=139fc573bf) | Sep 19, 2023 |
| Apple         | MacBook3,1                  | [faa5140c74](https://linux-hardware.org/?probe=faa5140c74) | Sep 18, 2023 |
| Acer          | Aspire E1-572G              | [0578825483](https://linux-hardware.org/?probe=0578825483) | Sep 18, 2023 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [b9f92fec9c](https://linux-hardware.org/?probe=b9f92fec9c) | Sep 17, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [0379270fb2](https://linux-hardware.org/?probe=0379270fb2) | Sep 15, 2023 |
| Valve         | Jupiter                     | [5f155701b1](https://linux-hardware.org/?probe=5f155701b1) | Sep 13, 2023 |
| Valve         | Jupiter                     | [3ae7c4440b](https://linux-hardware.org/?probe=3ae7c4440b) | Sep 10, 2023 |
| Valve         | Jupiter                     | [bbbc40365d](https://linux-hardware.org/?probe=bbbc40365d) | Sep 10, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [780a68ac11](https://linux-hardware.org/?probe=780a68ac11) | Sep 09, 2023 |
| HP            | Pavilion dv7                | [a928ff5a33](https://linux-hardware.org/?probe=a928ff5a33) | Sep 09, 2023 |
| HP            | EliteBook 8740w             | [e34200af0f](https://linux-hardware.org/?probe=e34200af0f) | Sep 08, 2023 |
| Inter Sale... | NID-11125DE                 | [2c94bcc096](https://linux-hardware.org/?probe=2c94bcc096) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [4764776393](https://linux-hardware.org/?probe=4764776393) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | [75ad357b16](https://linux-hardware.org/?probe=75ad357b16) | Sep 01, 2023 |
| Sony          | VPCEH2J1E                   | [0d1017e65a](https://linux-hardware.org/?probe=0d1017e65a) | Aug 31, 2023 |
| ASUSTek       | X555LAB                     | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | [05b083817c](https://linux-hardware.org/?probe=05b083817c) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | [f6f76a2e9d](https://linux-hardware.org/?probe=f6f76a2e9d) | Aug 30, 2023 |
| Acer          | Aspire A114-31              | [6bf92318e7](https://linux-hardware.org/?probe=6bf92318e7) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | [0e3563cf3e](https://linux-hardware.org/?probe=0e3563cf3e) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | [1025de1dcf](https://linux-hardware.org/?probe=1025de1dcf) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Chuwi         | LapBook SE                  | [8c338913ab](https://linux-hardware.org/?probe=8c338913ab) | Aug 19, 2023 |
| Acer          | Predator PH317-52           | [c942508cf0](https://linux-hardware.org/?probe=c942508cf0) | Aug 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| Chuwi         | HeroBook Pro                | [0122fef8fd](https://linux-hardware.org/?probe=0122fef8fd) | Aug 15, 2023 |
| Dell          | Latitude 5290 2-in-1        | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| HP            | EliteBook 8740w             | [69a5fc6981](https://linux-hardware.org/?probe=69a5fc6981) | Aug 10, 2023 |
| Toshiba       | Satellite C70D-B            | [ac775a3228](https://linux-hardware.org/?probe=ac775a3228) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | [e3f3b2fcfb](https://linux-hardware.org/?probe=e3f3b2fcfb) | Aug 09, 2023 |
| Dell          | Latitude 5540               | [08c875f58b](https://linux-hardware.org/?probe=08c875f58b) | Aug 08, 2023 |
| Dell          | XPS 13 9310                 | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| HP            | EliteBook 8740w             | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| Lenovo        | ThinkPad X230 23205XG       | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| HP            | EliteBook 8740w             | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Dell          | Latitude E6400              | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad T470 20HES2C000    | [6cb5b31808](https://linux-hardware.org/?probe=6cb5b31808) | Jul 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [68d5cb02bf](https://linux-hardware.org/?probe=68d5cb02bf) | Jul 29, 2023 |
| Dell          | Inspiron 5720               | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Valve         | Jupiter                     | [db220d13d6](https://linux-hardware.org/?probe=db220d13d6) | Jul 20, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [01b8ada2a7](https://linux-hardware.org/?probe=01b8ada2a7) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [3ad7db3176](https://linux-hardware.org/?probe=3ad7db3176) | Jul 10, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [919d1fc65b](https://linux-hardware.org/?probe=919d1fc65b) | Jul 09, 2023 |
| ASUSTek       | G60VX                       | [3273a8de27](https://linux-hardware.org/?probe=3273a8de27) | Jul 09, 2023 |
| Acer          | TravelMate P215-53          | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| HP            | ZBook 17 G3                 | [e328019dd8](https://linux-hardware.org/?probe=e328019dd8) | Jul 07, 2023 |
| Medion        | Unknown                     | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bbce89859f](https://linux-hardware.org/?probe=bbce89859f) | Jul 06, 2023 |
| HP            | ProBook 4740s               | [c920d177db](https://linux-hardware.org/?probe=c920d177db) | Jul 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [5f2c613312](https://linux-hardware.org/?probe=5f2c613312) | Jul 03, 2023 |
| Valve         | Jupiter                     | [cd28af9419](https://linux-hardware.org/?probe=cd28af9419) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | Aspire VN7-593G             | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [eeb516967a](https://linux-hardware.org/?probe=eeb516967a) | Jun 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a2a87af2a4](https://linux-hardware.org/?probe=a2a87af2a4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Acer          | Aspire A114-31              | [3cb015a09d](https://linux-hardware.org/?probe=3cb015a09d) | Jun 23, 2023 |
| ASUSTek       | K56CB                       | [e00f1f735d](https://linux-hardware.org/?probe=e00f1f735d) | Jun 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [9fa828d2e4](https://linux-hardware.org/?probe=9fa828d2e4) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Valve         | Jupiter                     | [576a62665a](https://linux-hardware.org/?probe=576a62665a) | Jun 20, 2023 |
| MSI           | Bravo 17 A4DDR              | [bae46c4d0b](https://linux-hardware.org/?probe=bae46c4d0b) | Jun 19, 2023 |
| Apple         | MacBookPro8,2               | [d254709437](https://linux-hardware.org/?probe=d254709437) | Jun 15, 2023 |
| HP            | Notebook                    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Acer          | TravelMate 5742Z            | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [93fe499e47](https://linux-hardware.org/?probe=93fe499e47) | Jun 12, 2023 |
| Lenovo        | ThinkPad W541 20EGS15J0N    | [ba935e9d5c](https://linux-hardware.org/?probe=ba935e9d5c) | Jun 12, 2023 |
| HP            | ProBook 440 G4              | [411faeafd4](https://linux-hardware.org/?probe=411faeafd4) | Jun 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [d6be89e452](https://linux-hardware.org/?probe=d6be89e452) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Valve         | Jupiter                     | [7e07a9c15d](https://linux-hardware.org/?probe=7e07a9c15d) | Jun 07, 2023 |
| Dell          | Latitude E7250              | [a80182e728](https://linux-hardware.org/?probe=a80182e728) | Jun 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5b7617b9c0](https://linux-hardware.org/?probe=5b7617b9c0) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Dell          | Latitude E7450              | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| Apple         | MacBookAir7,2               | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HP            | Compaq Presario CQ60        | [2378902ae8](https://linux-hardware.org/?probe=2378902ae8) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2cacb34a0d](https://linux-hardware.org/?probe=2cacb34a0d) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| Valve         | Jupiter                     | [f2f00bcfcc](https://linux-hardware.org/?probe=f2f00bcfcc) | May 29, 2023 |
| Valve         | Jupiter                     | [242a13f378](https://linux-hardware.org/?probe=242a13f378) | May 27, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| Acer          | Aspire V3-772               | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [44bc1d8d62](https://linux-hardware.org/?probe=44bc1d8d62) | May 17, 2023 |
| HP            | ProBook 6570b               | [7d8b9d4be1](https://linux-hardware.org/?probe=7d8b9d4be1) | May 16, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [996d19a70c](https://linux-hardware.org/?probe=996d19a70c) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [3bd39e50a8](https://linux-hardware.org/?probe=3bd39e50a8) | May 15, 2023 |
| Valve         | Jupiter                     | [a130b1b1d0](https://linux-hardware.org/?probe=a130b1b1d0) | May 14, 2023 |
| MSI           | GF65 Thin 10UE              | [7d8bb12818](https://linux-hardware.org/?probe=7d8bb12818) | May 14, 2023 |
| HP            | ProBook 640 G1              | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Sony          | VPCEH2J1E                   | [fb307bc1bb](https://linux-hardware.org/?probe=fb307bc1bb) | May 11, 2023 |
| TUXEDO        | Book XP1511                 | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Dell          | Latitude 5310               | [d72db172f0](https://linux-hardware.org/?probe=d72db172f0) | May 07, 2023 |
| Toshiba       | TECRA A11                   | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Acer          | Aspire A114-31              | [a7e0c2d3b6](https://linux-hardware.org/?probe=a7e0c2d3b6) | May 05, 2023 |
| Toshiba       | Satellite U300              | [470632e542](https://linux-hardware.org/?probe=470632e542) | May 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [65ddedbd24](https://linux-hardware.org/?probe=65ddedbd24) | May 05, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| Sony          | VPCEH2J1E                   | [c9b6063699](https://linux-hardware.org/?probe=c9b6063699) | May 04, 2023 |
| Fujitsu       | LIFEBOOK E752               | [22f50229d9](https://linux-hardware.org/?probe=22f50229d9) | May 03, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [e3984b7285](https://linux-hardware.org/?probe=e3984b7285) | May 01, 2023 |
| Medion        | E16402                      | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Dell          | Latitude D630               | [0fecf73eea](https://linux-hardware.org/?probe=0fecf73eea) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [57261fe5ec](https://linux-hardware.org/?probe=57261fe5ec) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Valve         | Jupiter                     | [0d6278dd3a](https://linux-hardware.org/?probe=0d6278dd3a) | Apr 22, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a7359e872e](https://linux-hardware.org/?probe=a7359e872e) | Apr 22, 2023 |
| Valve         | Jupiter                     | [d315f00cd8](https://linux-hardware.org/?probe=d315f00cd8) | Apr 21, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3219512811](https://linux-hardware.org/?probe=3219512811) | Apr 20, 2023 |
| Medion        | P17605                      | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| Acer          | AS5755                      | [1c163eb17f](https://linux-hardware.org/?probe=1c163eb17f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| HUAWEI        | RLEF-XX                     | [b425e2afaf](https://linux-hardware.org/?probe=b425e2afaf) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [19bb54bd98](https://linux-hardware.org/?probe=19bb54bd98) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Medion        | E7220                       | [ab189f426b](https://linux-hardware.org/?probe=ab189f426b) | Apr 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | [e9fa009df9](https://linux-hardware.org/?probe=e9fa009df9) | Apr 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [0ca203f8b0](https://linux-hardware.org/?probe=0ca203f8b0) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | [8e769590fb](https://linux-hardware.org/?probe=8e769590fb) | Apr 05, 2023 |
| Valve         | Jupiter                     | [a3c3e3267a](https://linux-hardware.org/?probe=a3c3e3267a) | Apr 02, 2023 |
| Valve         | Jupiter                     | [774af9fced](https://linux-hardware.org/?probe=774af9fced) | Apr 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [68dade8d0a](https://linux-hardware.org/?probe=68dade8d0a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| HP            | EliteBook 2530p (KR059AV... | [e7f9bce466](https://linux-hardware.org/?probe=e7f9bce466) | Mar 31, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [225e13e1f0](https://linux-hardware.org/?probe=225e13e1f0) | Mar 30, 2023 |
| HP            | Pavilion 17                 | [46e0a0aed1](https://linux-hardware.org/?probe=46e0a0aed1) | Mar 30, 2023 |
| HP            | Pavilion 17                 | [3da4500905](https://linux-hardware.org/?probe=3da4500905) | Mar 30, 2023 |
| HP            | ProBook 640 G1              | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Samsung       | RC530/RC730                 | [ad2be3eba7](https://linux-hardware.org/?probe=ad2be3eba7) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [64485e9b53](https://linux-hardware.org/?probe=64485e9b53) | Mar 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Hampoo        | Cherry Trail CR             | [b293f3ba3e](https://linux-hardware.org/?probe=b293f3ba3e) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | [f4830d41d6](https://linux-hardware.org/?probe=f4830d41d6) | Mar 21, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [42629ad13b](https://linux-hardware.org/?probe=42629ad13b) | Mar 21, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | [aef19ecbd7](https://linux-hardware.org/?probe=aef19ecbd7) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | [82d9122ebf](https://linux-hardware.org/?probe=82d9122ebf) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Valve         | Jupiter                     | [192fe75be4](https://linux-hardware.org/?probe=192fe75be4) | Mar 19, 2023 |
| Dell          | Vostro 5471                 | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| Hampoo        | Cherry Trail CR             | [fcb7a079cf](https://linux-hardware.org/?probe=fcb7a079cf) | Mar 18, 2023 |
| HP            | EliteBook 1050 G1           | [6dcfa134ac](https://linux-hardware.org/?probe=6dcfa134ac) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Valve         | Jupiter                     | [36eacafa6f](https://linux-hardware.org/?probe=36eacafa6f) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Hampoo        | Cherry Trail CR             | [c9936da6ba](https://linux-hardware.org/?probe=c9936da6ba) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| HP            | ProBook 450 G6              | [44c6479881](https://linux-hardware.org/?probe=44c6479881) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Clevo         | P370EM                      | [4ac46a0dab](https://linux-hardware.org/?probe=4ac46a0dab) | Mar 07, 2023 |
| HP            | ProBook 450 G6              | [b27b730e8f](https://linux-hardware.org/?probe=b27b730e8f) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Apple         | MacBookAir4,2               | [a9605bf85e](https://linux-hardware.org/?probe=a9605bf85e) | Feb 27, 2023 |
| Dell          | Latitude E7250              | [db6ac786ef](https://linux-hardware.org/?probe=db6ac786ef) | Feb 26, 2023 |
| Valve         | Jupiter                     | [c8006c3bd5](https://linux-hardware.org/?probe=c8006c3bd5) | Feb 26, 2023 |
| Toshiba       | Satellite C70D-B            | [0c69e8ef9b](https://linux-hardware.org/?probe=0c69e8ef9b) | Feb 23, 2023 |
| Toshiba       | Satellite C70D-B            | [bcae8ff254](https://linux-hardware.org/?probe=bcae8ff254) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | [49007433d0](https://linux-hardware.org/?probe=49007433d0) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | [e67cca4a6c](https://linux-hardware.org/?probe=e67cca4a6c) | Feb 23, 2023 |
| Unknown       | Unknown                     | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| Chuwi         | HeroBook Pro                | [f49ba07c1e](https://linux-hardware.org/?probe=f49ba07c1e) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [9c461d33db](https://linux-hardware.org/?probe=9c461d33db) | Feb 16, 2023 |
| Medion        | E7220                       | [dd9de8bf69](https://linux-hardware.org/?probe=dd9de8bf69) | Feb 15, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3S... | [580215c6bb](https://linux-hardware.org/?probe=580215c6bb) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ca4349a929](https://linux-hardware.org/?probe=ca4349a929) | Feb 15, 2023 |
| Apple         | MacBook5,2                  | [72b8d495ff](https://linux-hardware.org/?probe=72b8d495ff) | Feb 13, 2023 |
| Acer          | Aspire 7740                 | [caeb61e835](https://linux-hardware.org/?probe=caeb61e835) | Feb 12, 2023 |
| Apple         | MacBookPro11,5              | [78e7a0ae85](https://linux-hardware.org/?probe=78e7a0ae85) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| Apple         | MacBookPro5,4               | [b7e924b0cd](https://linux-hardware.org/?probe=b7e924b0cd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [d08c46c46d](https://linux-hardware.org/?probe=d08c46c46d) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| MSI           | GF63 Thin 11UC              | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Apple         | MacBookPro11,5              | [3407774ba7](https://linux-hardware.org/?probe=3407774ba7) | Feb 05, 2023 |
| Dell          | MXG061                      | [40883298a9](https://linux-hardware.org/?probe=40883298a9) | Feb 04, 2023 |
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Acer          | Aspire A515-54G             | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude 5480               | [8b43efc7ea](https://linux-hardware.org/?probe=8b43efc7ea) | Jan 31, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Dell          | XPS 15 7590                 | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| TUXEDO        | Unknown                     | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | [f1c0237cc0](https://linux-hardware.org/?probe=f1c0237cc0) | Jan 22, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| MSI           | VR630                       | [943c1d68fa](https://linux-hardware.org/?probe=943c1d68fa) | Jan 19, 2023 |
| ASUSTek       | K53TA                       | [a56a3691e9](https://linux-hardware.org/?probe=a56a3691e9) | Jan 18, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [b68853abf6](https://linux-hardware.org/?probe=b68853abf6) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [80f9124e5a](https://linux-hardware.org/?probe=80f9124e5a) | Jan 14, 2023 |
| TUXEDO        | Unknown                     | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Latitude E5550              | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Medion        | E6222                       | [e3b3da28fa](https://linux-hardware.org/?probe=e3b3da28fa) | Jan 11, 2023 |
| Dell          | Latitude E5550              | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| Dell          | Latitude E7440              | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Dell          | XPS 13 9380                 | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| MSI           | GS63VR 7RF                  | [95aadb3cc4](https://linux-hardware.org/?probe=95aadb3cc4) | Jan 09, 2023 |
| Sony          | SVE1512H1EB                 | [723e8bfbe6](https://linux-hardware.org/?probe=723e8bfbe6) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | [297380c89a](https://linux-hardware.org/?probe=297380c89a) | Jan 09, 2023 |
| Acer          | Iconia W700                 | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| Google        | Kled                        | [3cb98a4497](https://linux-hardware.org/?probe=3cb98a4497) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Sony          | VPCEH2D0E                   | [78367f11f5](https://linux-hardware.org/?probe=78367f11f5) | Jan 04, 2023 |
| ASUSTek       | K93SM                       | [c0fb78e9a3](https://linux-hardware.org/?probe=c0fb78e9a3) | Jan 03, 2023 |
| Dell          | Latitude 7430               | [ad796336f7](https://linux-hardware.org/?probe=ad796336f7) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Chuwi         | HeroBook Pro                | [cdc31b8338](https://linux-hardware.org/?probe=cdc31b8338) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c28fb2edb2](https://linux-hardware.org/?probe=c28fb2edb2) | Dec 30, 2022 |
| Medion        | X782X/X783X                 | [a8befc040f](https://linux-hardware.org/?probe=a8befc040f) | Dec 26, 2022 |
| Notebook      | P64_HJ,HK1                  | [26a548a6f3](https://linux-hardware.org/?probe=26a548a6f3) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [431eac7d11](https://linux-hardware.org/?probe=431eac7d11) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire A715-72G             | [8e15fef839](https://linux-hardware.org/?probe=8e15fef839) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| Google        | Cyan                        | [fff3502929](https://linux-hardware.org/?probe=fff3502929) | Dec 19, 2022 |
| Acer          | Nitro AN515-42              | [88d7491a00](https://linux-hardware.org/?probe=88d7491a00) | Dec 19, 2022 |
| AXDIA Inte... | myBook PRO14 SE V2          | [14b79d7a8b](https://linux-hardware.org/?probe=14b79d7a8b) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| HP            | EliteBook 850 G2            | [d0d30cd96f](https://linux-hardware.org/?probe=d0d30cd96f) | Dec 14, 2022 |
| Acer          | Swift SF314-59              | [943bcd1d12](https://linux-hardware.org/?probe=943bcd1d12) | Dec 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [b518609312](https://linux-hardware.org/?probe=b518609312) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [f815a2e4a3](https://linux-hardware.org/?probe=f815a2e4a3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| HUAWEI        | RLEF-XX                     | [e0b1d50b7c](https://linux-hardware.org/?probe=e0b1d50b7c) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [50e5b72a10](https://linux-hardware.org/?probe=50e5b72a10) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [b7171256c0](https://linux-hardware.org/?probe=b7171256c0) | Dec 07, 2022 |
| Packard Be... | EasyNote TS11HR             | [cd166beede](https://linux-hardware.org/?probe=cd166beede) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Acer          | Aspire A514-53              | [f0c20f1a0a](https://linux-hardware.org/?probe=f0c20f1a0a) | Dec 04, 2022 |
| ASUSTek       | X580VD                      | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| Apple         | MacBookPro14,1              | [eb13a8db03](https://linux-hardware.org/?probe=eb13a8db03) | Dec 02, 2022 |
| Acer          | Aspire A514-53              | [07ff06f360](https://linux-hardware.org/?probe=07ff06f360) | Dec 02, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| W271ELQ       | Unknown                     | [ae170d1e81](https://linux-hardware.org/?probe=ae170d1e81) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| Dell          | Latitude 3520               | [896180c55d](https://linux-hardware.org/?probe=896180c55d) | Nov 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [6646978243](https://linux-hardware.org/?probe=6646978243) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [ddcb37ea55](https://linux-hardware.org/?probe=ddcb37ea55) | Nov 23, 2022 |
| Dell          | Precision 5560              | [f20218fb35](https://linux-hardware.org/?probe=f20218fb35) | Nov 23, 2022 |
| TUXEDO        | N7x0WU                      | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [dc848e747b](https://linux-hardware.org/?probe=dc848e747b) | Nov 21, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [4ea8f7dbb0](https://linux-hardware.org/?probe=4ea8f7dbb0) | Nov 19, 2022 |
| Valve         | Jupiter                     | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Latitude E6220              | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| HP            | EliteBook 850 G1            | [a83e2b1a92](https://linux-hardware.org/?probe=a83e2b1a92) | Nov 13, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [4406929fb6](https://linux-hardware.org/?probe=4406929fb6) | Nov 11, 2022 |
| Apple         | MacBookPro9,2               | [695b0b0356](https://linux-hardware.org/?probe=695b0b0356) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| ASUSTek       | X55A                        | [6391006e3d](https://linux-hardware.org/?probe=6391006e3d) | Nov 07, 2022 |
| ASUSTek       | X55A                        | [ae4277aa87](https://linux-hardware.org/?probe=ae4277aa87) | Nov 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
| HP            | EliteBook 8460p             | [565ad502cc](https://linux-hardware.org/?probe=565ad502cc) | Nov 02, 2022 |
| HP            | ZBook 15 G2                 | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| ASUSTek       | K54L                        | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| Adlinktech    | SB-MLC                      | [203d95e012](https://linux-hardware.org/?probe=203d95e012) | Oct 31, 2022 |
| Dell          | Latitude E6400              | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Lenovo        | ThinkPad T510 4384WKU       | [86fee6e260](https://linux-hardware.org/?probe=86fee6e260) | Oct 30, 2022 |
| Dell          | Studio 1737                 | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | EliteBook 820 G4            | [c41402e832](https://linux-hardware.org/?probe=c41402e832) | Oct 29, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [c079764998](https://linux-hardware.org/?probe=c079764998) | Oct 28, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [5ef9b4213f](https://linux-hardware.org/?probe=5ef9b4213f) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| ASUSTek       | UX303LAB                    | [5748274da1](https://linux-hardware.org/?probe=5748274da1) | Oct 27, 2022 |
| Dell          | Precision 7530              | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| ASUSTek       | UX303LAB                    | [622aa11277](https://linux-hardware.org/?probe=622aa11277) | Oct 26, 2022 |
| Lenovo        | ThinkPad P1 20MD000NGE      | [561f09ba0f](https://linux-hardware.org/?probe=561f09ba0f) | Oct 25, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Valve         | Jupiter                     | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [99da3e6f09](https://linux-hardware.org/?probe=99da3e6f09) | Oct 22, 2022 |
| Dell          | XPS 13 9343                 | [1ce3fc664e](https://linux-hardware.org/?probe=1ce3fc664e) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Dell          | Latitude 5520               | [fc014585a8](https://linux-hardware.org/?probe=fc014585a8) | Oct 19, 2022 |
| Dell          | Latitude 5520               | [3589f77c74](https://linux-hardware.org/?probe=3589f77c74) | Oct 19, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20US... | [ec42bc932e](https://linux-hardware.org/?probe=ec42bc932e) | Oct 18, 2022 |
| Dell          | Precision 5510              | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| Dell          | Latitude 3520               | [f556b42181](https://linux-hardware.org/?probe=f556b42181) | Oct 16, 2022 |
| ASUSTek       | X580VD                      | [59ecc7da84](https://linux-hardware.org/?probe=59ecc7da84) | Oct 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [766f4b2d1f](https://linux-hardware.org/?probe=766f4b2d1f) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [bf46cd0c9e](https://linux-hardware.org/?probe=bf46cd0c9e) | Oct 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [bc23ce28e0](https://linux-hardware.org/?probe=bc23ce28e0) | Oct 14, 2022 |
| Dell          | Inspiron 3505               | [04147466b3](https://linux-hardware.org/?probe=04147466b3) | Oct 13, 2022 |
| Dell          | Latitude E6440              | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| Dell          | Latitude E6540              | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [e860301211](https://linux-hardware.org/?probe=e860301211) | Oct 09, 2022 |
| Valve         | Jupiter                     | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| MSI           | Modern 14 B11M              | [e0391b5084](https://linux-hardware.org/?probe=e0391b5084) | Oct 05, 2022 |
| HP            | ProBook 450 G3              | [16b58b369a](https://linux-hardware.org/?probe=16b58b369a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| HP            | EliteBook 850 G1            | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e829c9c0c6](https://linux-hardware.org/?probe=e829c9c0c6) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [3c0a494baa](https://linux-hardware.org/?probe=3c0a494baa) | Sep 26, 2022 |
| Dell          | Latitude E6400              | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| AMI           | Intel                       | [56de8f8b8a](https://linux-hardware.org/?probe=56de8f8b8a) | Sep 25, 2022 |
| AMI           | Intel                       | [330585dcd8](https://linux-hardware.org/?probe=330585dcd8) | Sep 25, 2022 |
| Acer          | Aspire E5-771G              | [39dc43058e](https://linux-hardware.org/?probe=39dc43058e) | Sep 23, 2022 |
| HP            | Compaq 15                   | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Dell          | Latitude E6510              | [fa644f90c4](https://linux-hardware.org/?probe=fa644f90c4) | Sep 22, 2022 |
| HP            | Pavilion 17                 | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| HP            | EliteBook 840 G3            | [233ba928b8](https://linux-hardware.org/?probe=233ba928b8) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Dell          | XPS 13 9380                 | [0c6c042af0](https://linux-hardware.org/?probe=0c6c042af0) | Sep 20, 2022 |
| Samsung       | R530/R730                   | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| HP            | ProBook 470 G4              | [c11b354c39](https://linux-hardware.org/?probe=c11b354c39) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| Valve         | Jupiter                     | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| HP            | ProBook 450 G0              | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Acer          | Aspire S3                   | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| HP            | EliteBook 8460p             | [12abaecf7e](https://linux-hardware.org/?probe=12abaecf7e) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| TrekStor      | Notebook Slim S130          | [abd3c1ccf8](https://linux-hardware.org/?probe=abd3c1ccf8) | Sep 05, 2022 |
| Lenovo        | ThinkPad T500 2241WH7       | [1e14648d27](https://linux-hardware.org/?probe=1e14648d27) | Sep 04, 2022 |
| BESSTAR Te... | X400                        | [8eb69c0ad6](https://linux-hardware.org/?probe=8eb69c0ad6) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [6109fc3fa8](https://linux-hardware.org/?probe=6109fc3fa8) | Sep 02, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [9f98c80601](https://linux-hardware.org/?probe=9f98c80601) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Panasonic     | CF-191HACHFG                | [c1f0177dcb](https://linux-hardware.org/?probe=c1f0177dcb) | Sep 01, 2022 |
| BESSTAR Te... | X400                        | [ab70086ae7](https://linux-hardware.org/?probe=ab70086ae7) | Aug 27, 2022 |
| Fujitsu       | LIFEBOOK E752               | [adf76251c5](https://linux-hardware.org/?probe=adf76251c5) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [7c7a83f951](https://linux-hardware.org/?probe=7c7a83f951) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| HP            | 250 G7 Notebook PC          | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| TrekStor      | Notebook Slim S130          | [2b5689655d](https://linux-hardware.org/?probe=2b5689655d) | Aug 16, 2022 |
| TrekStor      | Notebook Slim S130          | [baf685c170](https://linux-hardware.org/?probe=baf685c170) | Aug 16, 2022 |
| VALE          | Notebook Classic C170       | [e1563aa775](https://linux-hardware.org/?probe=e1563aa775) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | [ce03a2383e](https://linux-hardware.org/?probe=ce03a2383e) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | [cb10c34587](https://linux-hardware.org/?probe=cb10c34587) | Aug 15, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [4a52da1c38](https://linux-hardware.org/?probe=4a52da1c38) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [f71b1992c9](https://linux-hardware.org/?probe=f71b1992c9) | Aug 13, 2022 |
| BESSTAR Te... | X400                        | [e8424e153d](https://linux-hardware.org/?probe=e8424e153d) | Aug 12, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [0f33fa05f5](https://linux-hardware.org/?probe=0f33fa05f5) | Aug 10, 2022 |
| AMI           | Intel                       | [8d8db9dc8b](https://linux-hardware.org/?probe=8d8db9dc8b) | Aug 09, 2022 |
| AMI           | Intel                       | [0958b0a578](https://linux-hardware.org/?probe=0958b0a578) | Aug 09, 2022 |
| ASUSTek       | N56VZ                       | [3ee621b609](https://linux-hardware.org/?probe=3ee621b609) | Aug 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Dell          | Latitude E5550              | [c1d9204443](https://linux-hardware.org/?probe=c1d9204443) | Aug 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [91998a6bfe](https://linux-hardware.org/?probe=91998a6bfe) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [8f934de8ef](https://linux-hardware.org/?probe=8f934de8ef) | Aug 03, 2022 |
| Dell          | Latitude E6430              | [82abc4b330](https://linux-hardware.org/?probe=82abc4b330) | Aug 03, 2022 |
| Sony          | VGN-FW51ZF_H                | [f42e9458c7](https://linux-hardware.org/?probe=f42e9458c7) | Jul 31, 2022 |
| Toshiba       | Satellite L70-B             | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Acer          | Aspire 3810T                | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| ASUSTek       | X556UQK                     | [3e6c333747](https://linux-hardware.org/?probe=3e6c333747) | Jul 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [f611683c8a](https://linux-hardware.org/?probe=f611683c8a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [bad36e8ab5](https://linux-hardware.org/?probe=bad36e8ab5) | Jul 19, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | [b8220c7bb8](https://linux-hardware.org/?probe=b8220c7bb8) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| ASUSTek       | UX31E                       | [b3059e0094](https://linux-hardware.org/?probe=b3059e0094) | Jul 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | [01fae3a07c](https://linux-hardware.org/?probe=01fae3a07c) | Jul 15, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6606cb7d46](https://linux-hardware.org/?probe=6606cb7d46) | Jul 06, 2022 |
| Sony          | VPCEH2J1E                   | [e51b908744](https://linux-hardware.org/?probe=e51b908744) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| AXDIA Inte... | WINPAD 12                   | [c263197569](https://linux-hardware.org/?probe=c263197569) | Jul 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Clevo         | Modified by dsanke          | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | [e18983e0d8](https://linux-hardware.org/?probe=e18983e0d8) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | [d59ef2842d](https://linux-hardware.org/?probe=d59ef2842d) | Jun 21, 2022 |
| Razer         | Blade 15 Advanced Model ... | [de5d975c12](https://linux-hardware.org/?probe=de5d975c12) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [bfc7b65dee](https://linux-hardware.org/?probe=bfc7b65dee) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb60cda77f](https://linux-hardware.org/?probe=eb60cda77f) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Acer          | Aspire A515-44G             | [f07dc47259](https://linux-hardware.org/?probe=f07dc47259) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6db07f5434](https://linux-hardware.org/?probe=6db07f5434) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| Valve         | Jupiter                     | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| HP            | ProBook 450 G6              | [898eff4fae](https://linux-hardware.org/?probe=898eff4fae) | Jun 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [5ad950659b](https://linux-hardware.org/?probe=5ad950659b) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [24da0cf09c](https://linux-hardware.org/?probe=24da0cf09c) | Jun 06, 2022 |
| Acer          | Swift SFX14-41G             | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Dell          | Latitude 5520               | [03622600a8](https://linux-hardware.org/?probe=03622600a8) | May 30, 2022 |
| Dell          | Latitude E6410              | [72345f9352](https://linux-hardware.org/?probe=72345f9352) | May 28, 2022 |
| HP            | ProBook 470 G4              | [6049c10c3c](https://linux-hardware.org/?probe=6049c10c3c) | May 28, 2022 |
| System76      | Lemur Pro                   | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| Valve         | Jupiter                     | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| Dell          | Latitude E6410              | [39be06dd23](https://linux-hardware.org/?probe=39be06dd23) | May 19, 2022 |
| Acer          | Extensa 2509                | [46df59d8b3](https://linux-hardware.org/?probe=46df59d8b3) | May 19, 2022 |
| Acer          | Aspire A515-51G             | [9a945a6cf5](https://linux-hardware.org/?probe=9a945a6cf5) | May 17, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [b28d047360](https://linux-hardware.org/?probe=b28d047360) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [36ccfac84d](https://linux-hardware.org/?probe=36ccfac84d) | May 14, 2022 |
| Valve         | Jupiter                     | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d3d6871bf7](https://linux-hardware.org/?probe=d3d6871bf7) | May 12, 2022 |
| Dell          | Latitude 5520               | [927a4b0ed0](https://linux-hardware.org/?probe=927a4b0ed0) | May 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [17dda821a0](https://linux-hardware.org/?probe=17dda821a0) | May 11, 2022 |
| Apple         | MacBook1,1                  | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Dell          | XPS 13 9310                 | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Dell          | Latitude E6430              | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| HP            | ZBook 17 G5                 | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | [0bc5a5fb9f](https://linux-hardware.org/?probe=0bc5a5fb9f) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Sony          | VPCEH2J1E                   | [86f6b8c750](https://linux-hardware.org/?probe=86f6b8c750) | Apr 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Fujitsu       | LIFEBOOK E751               | [ace84bb1e5](https://linux-hardware.org/?probe=ace84bb1e5) | Apr 25, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [a8038d3972](https://linux-hardware.org/?probe=a8038d3972) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bbc4928d39](https://linux-hardware.org/?probe=bbc4928d39) | Apr 19, 2022 |
| Apple         | MacBookPro9,2               | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [b228a9bf01](https://linux-hardware.org/?probe=b228a9bf01) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c68c62f98c](https://linux-hardware.org/?probe=c68c62f98c) | Apr 14, 2022 |
| Medion        | X6816                       | [41350ad402](https://linux-hardware.org/?probe=41350ad402) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [ac82d62350](https://linux-hardware.org/?probe=ac82d62350) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [60a1fc5c39](https://linux-hardware.org/?probe=60a1fc5c39) | Apr 12, 2022 |
| TUXEDO        | P65xHP                      | [a29da5ce79](https://linux-hardware.org/?probe=a29da5ce79) | Apr 11, 2022 |
| Acer          | Aspire A114-31              | [8779ba2891](https://linux-hardware.org/?probe=8779ba2891) | Apr 09, 2022 |
| Acer          | Aspire A114-31              | [298acab48c](https://linux-hardware.org/?probe=298acab48c) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [0b5e11625d](https://linux-hardware.org/?probe=0b5e11625d) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fed3e90b10](https://linux-hardware.org/?probe=fed3e90b10) | Apr 08, 2022 |
| HP            | Pavilion dv6                | [b69de03677](https://linux-hardware.org/?probe=b69de03677) | Apr 06, 2022 |
| HP            | Pavilion dv6                | [9e8312e9c1](https://linux-hardware.org/?probe=9e8312e9c1) | Apr 06, 2022 |
| Dell          | XPS 13 9305                 | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Medion        | E7216                       | [58f12f9e91](https://linux-hardware.org/?probe=58f12f9e91) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [edf4c472c3](https://linux-hardware.org/?probe=edf4c472c3) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [35e0c67fed](https://linux-hardware.org/?probe=35e0c67fed) | Apr 03, 2022 |
| Acer          | TravelMate 7730             | [c0c1bedcec](https://linux-hardware.org/?probe=c0c1bedcec) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [26082e6921](https://linux-hardware.org/?probe=26082e6921) | Apr 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [0f191252cb](https://linux-hardware.org/?probe=0f191252cb) | Apr 02, 2022 |
| MSI           | Bravo 17 A4DDR              | [590d188f5d](https://linux-hardware.org/?probe=590d188f5d) | Apr 01, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Acer          | TravelMate 7730             | [6cabffccbe](https://linux-hardware.org/?probe=6cabffccbe) | Mar 30, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Sony          | VPCEH2J1E                   | [23d5b99aca](https://linux-hardware.org/?probe=23d5b99aca) | Mar 27, 2022 |
| Acer          | Nitro AN515-45              | [c6fa89e81f](https://linux-hardware.org/?probe=c6fa89e81f) | Mar 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [76b97dcfe7](https://linux-hardware.org/?probe=76b97dcfe7) | Mar 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [ec3089df82](https://linux-hardware.org/?probe=ec3089df82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| HP            | Pavilion dv7                | [64d5f14244](https://linux-hardware.org/?probe=64d5f14244) | Mar 22, 2022 |
| HP            | Pavilion dv7                | [e2bfdae482](https://linux-hardware.org/?probe=e2bfdae482) | Mar 22, 2022 |
| MSI           | Modern 14 B10MW             | [e8bbca6adf](https://linux-hardware.org/?probe=e8bbca6adf) | Mar 21, 2022 |
| Fujitsu Si... | AMILO Pro Edition V3545     | [be2c23f4a5](https://linux-hardware.org/?probe=be2c23f4a5) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Medion        | E14410                      | [800f98d1ef](https://linux-hardware.org/?probe=800f98d1ef) | Mar 21, 2022 |
| Sony          | VPCEH2J1E                   | [ae54fc4033](https://linux-hardware.org/?probe=ae54fc4033) | Mar 19, 2022 |
| ASUSTek       | X201EP                      | [864fc80ac3](https://linux-hardware.org/?probe=864fc80ac3) | Mar 17, 2022 |
| MSI           | Alpha 15 B5EEK              | [f4c72eaa35](https://linux-hardware.org/?probe=f4c72eaa35) | Mar 15, 2022 |
| MSI           | Alpha 15 B5EEK              | [8859888f0c](https://linux-hardware.org/?probe=8859888f0c) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [1aa06e7b53](https://linux-hardware.org/?probe=1aa06e7b53) | Mar 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e2eacd6969](https://linux-hardware.org/?probe=e2eacd6969) | Mar 12, 2022 |
| Lenovo        | ThinkPad E15 20RES12P00     | [200b3a0b69](https://linux-hardware.org/?probe=200b3a0b69) | Mar 12, 2022 |
| ASUSTek       | UX303LAB                    | [f3d0e8fbea](https://linux-hardware.org/?probe=f3d0e8fbea) | Mar 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [adf7b6c95e](https://linux-hardware.org/?probe=adf7b6c95e) | Mar 10, 2022 |
| ASUSTek       | UX305FA                     | [f1641a436c](https://linux-hardware.org/?probe=f1641a436c) | Mar 09, 2022 |
| Dell          | Vostro 5471                 | [6e46455791](https://linux-hardware.org/?probe=6e46455791) | Mar 09, 2022 |
| Sony          | VPCEH2J1E                   | [713f08757a](https://linux-hardware.org/?probe=713f08757a) | Mar 09, 2022 |
| HP            | EliteBook 850 G1            | [b2aeea55e5](https://linux-hardware.org/?probe=b2aeea55e5) | Mar 07, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | Pavilion g6                 | [e9b1f4c1ec](https://linux-hardware.org/?probe=e9b1f4c1ec) | Mar 03, 2022 |
| HP            | Pavilion g6                 | [f378d8a1df](https://linux-hardware.org/?probe=f378d8a1df) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| Toshiba       | Satellite L775-166          | [f0ad0a4da5](https://linux-hardware.org/?probe=f0ad0a4da5) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [16281a52e8](https://linux-hardware.org/?probe=16281a52e8) | Feb 26, 2022 |
| Toshiba       | Satellite P500              | [980cb1d4af](https://linux-hardware.org/?probe=980cb1d4af) | Feb 25, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [6bf461797c](https://linux-hardware.org/?probe=6bf461797c) | Feb 25, 2022 |
| HP            | ZBook 15 G3                 | [7b9e3082bf](https://linux-hardware.org/?probe=7b9e3082bf) | Feb 25, 2022 |
| HP            | EliteBook 820 G1            | [916b00f114](https://linux-hardware.org/?probe=916b00f114) | Feb 24, 2022 |
| Lenovo        | IdeaPad S206 2638           | [84772cc34d](https://linux-hardware.org/?probe=84772cc34d) | Feb 23, 2022 |
| HP            | EliteBook 6930p             | [82000c3346](https://linux-hardware.org/?probe=82000c3346) | Feb 22, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Acer          | Aspire A517-51              | [997108b078](https://linux-hardware.org/?probe=997108b078) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| HP            | EliteBook 840 G1            | [3047069a4f](https://linux-hardware.org/?probe=3047069a4f) | Feb 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [934591472d](https://linux-hardware.org/?probe=934591472d) | Feb 16, 2022 |
| Dell          | XPS 15 9550                 | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Acer          | Swift SF114-34              | [31d020671e](https://linux-hardware.org/?probe=31d020671e) | Feb 13, 2022 |
| Lenovo        | ThinkPad X230T 34382AG      | [bec561800f](https://linux-hardware.org/?probe=bec561800f) | Feb 13, 2022 |
| HP            | ProBook 4730s               | [2a3ff15659](https://linux-hardware.org/?probe=2a3ff15659) | Feb 12, 2022 |
| HP            | Compaq 15                   | [78b2f3bfa6](https://linux-hardware.org/?probe=78b2f3bfa6) | Feb 11, 2022 |
| Acer          | Aspire A315-54              | [d4e5b617c7](https://linux-hardware.org/?probe=d4e5b617c7) | Feb 10, 2022 |
| Fujitsu       | LIFEBOOK E559               | [66696218c1](https://linux-hardware.org/?probe=66696218c1) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK S751               | [42d5c28f38](https://linux-hardware.org/?probe=42d5c28f38) | Feb 09, 2022 |
| Medion        | P6402 MD60800               | [a749ba246d](https://linux-hardware.org/?probe=a749ba246d) | Feb 08, 2022 |
| HP            | ProBook 450 G2              | [57c513ecbc](https://linux-hardware.org/?probe=57c513ecbc) | Feb 08, 2022 |
| Acer          | Predator G9-792             | [8404f2e6d1](https://linux-hardware.org/?probe=8404f2e6d1) | Feb 08, 2022 |
| HP            | EliteBook 840 G3            | [82d892f3e5](https://linux-hardware.org/?probe=82d892f3e5) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Acer          | TravelMate 5720             | [9db7cd9351](https://linux-hardware.org/?probe=9db7cd9351) | Feb 06, 2022 |
| Chuwi         | HeroBook Pro                | [9f5da53181](https://linux-hardware.org/?probe=9f5da53181) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Acer          | Swift SF314-54              | [d11fb8c7b6](https://linux-hardware.org/?probe=d11fb8c7b6) | Feb 04, 2022 |
| Acer          | Aspire A114-31              | [caa9365785](https://linux-hardware.org/?probe=caa9365785) | Feb 04, 2022 |
| Sony          | VPCEH2J1E                   | [f5ed0cbaa4](https://linux-hardware.org/?probe=f5ed0cbaa4) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5a1723f28e](https://linux-hardware.org/?probe=5a1723f28e) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [7db46606ab](https://linux-hardware.org/?probe=7db46606ab) | Feb 04, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [376503f06d](https://linux-hardware.org/?probe=376503f06d) | Feb 03, 2022 |
| HP            | ProBook 4310s               | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | ThinkPad X280 20KF001GGE    | [f076061f22](https://linux-hardware.org/?probe=f076061f22) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| Acer          | Aspire E1-571G              | [440bc30637](https://linux-hardware.org/?probe=440bc30637) | Jan 31, 2022 |
| Acer          | Aspire E1-571G              | [dd2d541140](https://linux-hardware.org/?probe=dd2d541140) | Jan 31, 2022 |
| Dell          | XPS M1530                   | [4b402569cc](https://linux-hardware.org/?probe=4b402569cc) | Jan 29, 2022 |
| Acer          | Predator G9-792             | [863bce4abe](https://linux-hardware.org/?probe=863bce4abe) | Jan 28, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5edb2eb3](https://linux-hardware.org/?probe=4d5edb2eb3) | Jan 25, 2022 |
| Lenovo        | ThinkPad T495 20NJS0KB00    | [e92c44b58a](https://linux-hardware.org/?probe=e92c44b58a) | Jan 24, 2022 |
| Dell          | Inspiron 1720               | [0b6d89660a](https://linux-hardware.org/?probe=0b6d89660a) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | [e9f3d5c785](https://linux-hardware.org/?probe=e9f3d5c785) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [e19ee364b0](https://linux-hardware.org/?probe=e19ee364b0) | Jan 21, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [a0399b1c6b](https://linux-hardware.org/?probe=a0399b1c6b) | Jan 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0410ba28b0](https://linux-hardware.org/?probe=0410ba28b0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [24c10d9f2d](https://linux-hardware.org/?probe=24c10d9f2d) | Jan 20, 2022 |
| Acer          | Nitro AN515-44              | [f45a7eb0bb](https://linux-hardware.org/?probe=f45a7eb0bb) | Jan 20, 2022 |
| Acer          | Swift SF114-34              | [7ea8fc4686](https://linux-hardware.org/?probe=7ea8fc4686) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5ba89b6e26](https://linux-hardware.org/?probe=5ba89b6e26) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fca800793f](https://linux-hardware.org/?probe=fca800793f) | Jan 18, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | [11340212f2](https://linux-hardware.org/?probe=11340212f2) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| Dell          | XPS 15 9570                 | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [dd69f44bab](https://linux-hardware.org/?probe=dd69f44bab) | Jan 15, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| Medion        | CRAWLER E10                 | [d658e7cd88](https://linux-hardware.org/?probe=d658e7cd88) | Jan 13, 2022 |
| HP            | EliteBook 1030 G1           | [73839f5dd5](https://linux-hardware.org/?probe=73839f5dd5) | Jan 09, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f212038b15](https://linux-hardware.org/?probe=f212038b15) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| HP            | Laptop 15-db1xxx            | [28db094e56](https://linux-hardware.org/?probe=28db094e56) | Jan 08, 2022 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [2dbdfe4883](https://linux-hardware.org/?probe=2dbdfe4883) | Jan 08, 2022 |
| Dell          | Vostro 5370                 | [0d027d4b84](https://linux-hardware.org/?probe=0d027d4b84) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| HP            | Laptop 17-ak0xx             | [fee6068743](https://linux-hardware.org/?probe=fee6068743) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| HP            | EliteBook 8540p             | [a321b2cfd9](https://linux-hardware.org/?probe=a321b2cfd9) | Jan 03, 2022 |
| HP            | EliteBook 8540p             | [6130b11204](https://linux-hardware.org/?probe=6130b11204) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| TUXEDO        | P65_67HSHP                  | [4d448637c0](https://linux-hardware.org/?probe=4d448637c0) | Jan 02, 2022 |
| ASUSTek       | N50Vn                       | [8fadb8c7af](https://linux-hardware.org/?probe=8fadb8c7af) | Jan 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS05V0... | [7c496e685d](https://linux-hardware.org/?probe=7c496e685d) | Dec 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [5095c47f07](https://linux-hardware.org/?probe=5095c47f07) | Dec 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [1724d0d357](https://linux-hardware.org/?probe=1724d0d357) | Dec 26, 2021 |
| HP            | ProBook 470 G1              | [0e99096fe2](https://linux-hardware.org/?probe=0e99096fe2) | Dec 26, 2021 |
| Dell          | Inspiron 3505               | [fe87929ac5](https://linux-hardware.org/?probe=fe87929ac5) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [cb2ae92d82](https://linux-hardware.org/?probe=cb2ae92d82) | Dec 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [492fc37142](https://linux-hardware.org/?probe=492fc37142) | Dec 22, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [d7f3d69923](https://linux-hardware.org/?probe=d7f3d69923) | Dec 21, 2021 |
| HP            | EliteBook 8460p             | [59ec7afd71](https://linux-hardware.org/?probe=59ec7afd71) | Dec 20, 2021 |
| ASUSTek       | GL702ZC                     | [ff27d21705](https://linux-hardware.org/?probe=ff27d21705) | Dec 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [a8713c0bd9](https://linux-hardware.org/?probe=a8713c0bd9) | Dec 18, 2021 |
| MSI           | Modern 14 B10MW             | [1771ceeb4e](https://linux-hardware.org/?probe=1771ceeb4e) | Dec 14, 2021 |
| Dell          | XPS 17 9700                 | [eef9ef9d60](https://linux-hardware.org/?probe=eef9ef9d60) | Dec 12, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c33bc12a7a](https://linux-hardware.org/?probe=c33bc12a7a) | Dec 11, 2021 |
| Dell          | XPS 17 9700                 | [d5ec843ea7](https://linux-hardware.org/?probe=d5ec843ea7) | Dec 11, 2021 |
| Toshiba       | Satellite L500              | [aaab078915](https://linux-hardware.org/?probe=aaab078915) | Dec 11, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [ec9930ae99](https://linux-hardware.org/?probe=ec9930ae99) | Dec 11, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [f2bfaaf185](https://linux-hardware.org/?probe=f2bfaaf185) | Dec 11, 2021 |
| Dell          | XPS M1530                   | [ad4bfb0cbd](https://linux-hardware.org/?probe=ad4bfb0cbd) | Dec 08, 2021 |
| HP            | Pavilion dv6                | [9dd21ffaf4](https://linux-hardware.org/?probe=9dd21ffaf4) | Dec 08, 2021 |
| Medion        | P7624                       | [05d0f23734](https://linux-hardware.org/?probe=05d0f23734) | Dec 08, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [600faccbe5](https://linux-hardware.org/?probe=600faccbe5) | Dec 07, 2021 |
| ASUSTek       | T100HAN                     | [9ad6409a34](https://linux-hardware.org/?probe=9ad6409a34) | Dec 06, 2021 |
| Dell          | Vostro 5471                 | [0d989a4f1f](https://linux-hardware.org/?probe=0d989a4f1f) | Dec 05, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [cd254ead05](https://linux-hardware.org/?probe=cd254ead05) | Dec 04, 2021 |
| HP            | ProBook 470 G1              | [4359617795](https://linux-hardware.org/?probe=4359617795) | Dec 03, 2021 |
| Lenovo        | ThinkPad Edge E330 33549... | [d8c1e34c94](https://linux-hardware.org/?probe=d8c1e34c94) | Dec 02, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6204315459](https://linux-hardware.org/?probe=6204315459) | Dec 02, 2021 |
| HP            | Pavilion dv6                | [640e1f0491](https://linux-hardware.org/?probe=640e1f0491) | Dec 01, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [d77b252a78](https://linux-hardware.org/?probe=d77b252a78) | Dec 01, 2021 |
| Acer          | Swift SF314-42              | [c77012b538](https://linux-hardware.org/?probe=c77012b538) | Nov 30, 2021 |
| HP            | 625                         | [75b1dd3ee1](https://linux-hardware.org/?probe=75b1dd3ee1) | Nov 29, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Medion        | P15648                      | [1328e63002](https://linux-hardware.org/?probe=1328e63002) | Nov 25, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5632c40eac](https://linux-hardware.org/?probe=5632c40eac) | Nov 24, 2021 |
| HP            | Pavilion g7                 | [c8b8a8bed7](https://linux-hardware.org/?probe=c8b8a8bed7) | Nov 24, 2021 |
| HP            | Pavilion g7                 | [fab49120f0](https://linux-hardware.org/?probe=fab49120f0) | Nov 23, 2021 |
| HP            | ProBook 455 G8 Notebook ... | [56cd58b089](https://linux-hardware.org/?probe=56cd58b089) | Nov 23, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| HP            | ENVY 15                     | [f4752615c9](https://linux-hardware.org/?probe=f4752615c9) | Nov 19, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | [73b9b15b14](https://linux-hardware.org/?probe=73b9b15b14) | Nov 19, 2021 |
| Lenovo        | ThinkPad P50 20EQS15P00     | [4c9b03387c](https://linux-hardware.org/?probe=4c9b03387c) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [915853adf6](https://linux-hardware.org/?probe=915853adf6) | Nov 18, 2021 |
| HP            | Laptop 15-db1xxx            | [cd32f937e9](https://linux-hardware.org/?probe=cd32f937e9) | Nov 17, 2021 |
| Acer          | Aspire 7750G                | [79eb5a8344](https://linux-hardware.org/?probe=79eb5a8344) | Nov 16, 2021 |
| Dell          | Vostro 5471                 | [348b6bc909](https://linux-hardware.org/?probe=348b6bc909) | Nov 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [1976dd6a72](https://linux-hardware.org/?probe=1976dd6a72) | Nov 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [039fb54354](https://linux-hardware.org/?probe=039fb54354) | Nov 12, 2021 |
| HP            | Laptop 15-db1xxx            | [c34d10b1c8](https://linux-hardware.org/?probe=c34d10b1c8) | Nov 12, 2021 |
| Sony          | VPCEH2J1E                   | [02a4a3ea01](https://linux-hardware.org/?probe=02a4a3ea01) | Nov 06, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f0d8cb68f0](https://linux-hardware.org/?probe=f0d8cb68f0) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [f4273d4dc1](https://linux-hardware.org/?probe=f4273d4dc1) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [86f7bd9873](https://linux-hardware.org/?probe=86f7bd9873) | Nov 06, 2021 |
| Lenovo        | G500s 20245                 | [e16940fe24](https://linux-hardware.org/?probe=e16940fe24) | Nov 05, 2021 |
| Medion        | E6220                       | [45d5f5ec30](https://linux-hardware.org/?probe=45d5f5ec30) | Nov 04, 2021 |
| ASUSTek       | X580VD                      | [2970522382](https://linux-hardware.org/?probe=2970522382) | Nov 01, 2021 |
| Panasonic     | FZG1-3                      | [8a52b831d7](https://linux-hardware.org/?probe=8a52b831d7) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ba228b1ed7](https://linux-hardware.org/?probe=ba228b1ed7) | Oct 31, 2021 |
| Medion        | Akoya S4220 MD99660         | [fd406382b2](https://linux-hardware.org/?probe=fd406382b2) | Oct 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0c865ddf24](https://linux-hardware.org/?probe=0c865ddf24) | Oct 30, 2021 |
| Dell          | Latitude 5490               | [4efdbaeea5](https://linux-hardware.org/?probe=4efdbaeea5) | Oct 30, 2021 |
| Acer          | Aspire A317-33              | [ad0f3b8799](https://linux-hardware.org/?probe=ad0f3b8799) | Oct 24, 2021 |
| Acer          | TravelMate P253             | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Medion        | E7216                       | [f4c7def4b7](https://linux-hardware.org/?probe=f4c7def4b7) | Oct 24, 2021 |
| Medion        | P7624                       | [efc2ccc6a2](https://linux-hardware.org/?probe=efc2ccc6a2) | Oct 24, 2021 |
| HP            | ProBook 430 G5              | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| Lenovo        | ThinkPad T440s 20AQS0090... | [415cc7fe56](https://linux-hardware.org/?probe=415cc7fe56) | Oct 18, 2021 |
| HP            | Pavilion dv6                | [0392f507d0](https://linux-hardware.org/?probe=0392f507d0) | Oct 18, 2021 |
| HP            | Laptop 14s-fq1xxx           | [61d5829888](https://linux-hardware.org/?probe=61d5829888) | Oct 14, 2021 |
| HP            | Laptop 14s-fq1xxx           | [c42ff576c7](https://linux-hardware.org/?probe=c42ff576c7) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| Medion        | P15648                      | [5ea319450e](https://linux-hardware.org/?probe=5ea319450e) | Oct 13, 2021 |
| HP            | Laptop 14s-fq1xxx           | [1e047e7a9a](https://linux-hardware.org/?probe=1e047e7a9a) | Oct 12, 2021 |
| ASUSTek       | N61Jv                       | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [037a558c7d](https://linux-hardware.org/?probe=037a558c7d) | Oct 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [1984f59bbe](https://linux-hardware.org/?probe=1984f59bbe) | Oct 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [a631c78255](https://linux-hardware.org/?probe=a631c78255) | Oct 09, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [b6715f92f7](https://linux-hardware.org/?probe=b6715f92f7) | Oct 08, 2021 |
| Dell          | Latitude E5550              | [a4f8896675](https://linux-hardware.org/?probe=a4f8896675) | Oct 07, 2021 |
| Medion        | E6415 MD99904               | [4b24e7fb1a](https://linux-hardware.org/?probe=4b24e7fb1a) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| ASUSTek       | X556UQK                     | [363c1a3642](https://linux-hardware.org/?probe=363c1a3642) | Oct 03, 2021 |
| Apple         | MacBookPro12,1              | [2a4757a98f](https://linux-hardware.org/?probe=2a4757a98f) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [a7e79f067e](https://linux-hardware.org/?probe=a7e79f067e) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [0b2f645654](https://linux-hardware.org/?probe=0b2f645654) | Sep 30, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [c63b30f0df](https://linux-hardware.org/?probe=c63b30f0df) | Sep 29, 2021 |
| Lenovo        | Z50-70 20354                | [0aef47a401](https://linux-hardware.org/?probe=0aef47a401) | Sep 29, 2021 |
| TUXEDO        | Book BA1510                 | [e408c8fb46](https://linux-hardware.org/?probe=e408c8fb46) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | [ae6c812e4c](https://linux-hardware.org/?probe=ae6c812e4c) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | [6bbaec4cfc](https://linux-hardware.org/?probe=6bbaec4cfc) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [4850590ac5](https://linux-hardware.org/?probe=4850590ac5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e7f361c688](https://linux-hardware.org/?probe=e7f361c688) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [17bef7f4cf](https://linux-hardware.org/?probe=17bef7f4cf) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Dell          | Latitude E7450              | [f600127ab1](https://linux-hardware.org/?probe=f600127ab1) | Sep 24, 2021 |
| Lenovo        | B575e 368523G               | [f795bbcedc](https://linux-hardware.org/?probe=f795bbcedc) | Sep 22, 2021 |
| HP            | Compaq nc6400 (EH522AV)     | [8e613adf36](https://linux-hardware.org/?probe=8e613adf36) | Sep 22, 2021 |
| Apple         | MacBookPro15,1              | [3a3ccf8143](https://linux-hardware.org/?probe=3a3ccf8143) | Sep 21, 2021 |
| TUXEDO        | N130BU                      | [12a72404ea](https://linux-hardware.org/?probe=12a72404ea) | Sep 18, 2021 |
| Dell          | XPS 13 9305                 | [369e99699a](https://linux-hardware.org/?probe=369e99699a) | Sep 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [318f8d1653](https://linux-hardware.org/?probe=318f8d1653) | Sep 18, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| TUXEDO        | Book BA1510                 | [2397ee987d](https://linux-hardware.org/?probe=2397ee987d) | Sep 15, 2021 |
| Apple         | MacBookPro15,1              | [73bab0d19c](https://linux-hardware.org/?probe=73bab0d19c) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| Lenovo        | ThinkPad E580 20KS0039GE    | [d85ddde9ba](https://linux-hardware.org/?probe=d85ddde9ba) | Sep 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [216f21f8d5](https://linux-hardware.org/?probe=216f21f8d5) | Sep 13, 2021 |
| Dell          | Precision 5540              | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| ASUSTek       | G750JX                      | [185445c775](https://linux-hardware.org/?probe=185445c775) | Sep 12, 2021 |
| Dell          | Latitude E4300              | [4c52be511c](https://linux-hardware.org/?probe=4c52be511c) | Sep 11, 2021 |
| TUXEDO        | N130BU                      | [e81e4cc415](https://linux-hardware.org/?probe=e81e4cc415) | Sep 08, 2021 |
| Medion        | P6618                       | [3fabc658b8](https://linux-hardware.org/?probe=3fabc658b8) | Sep 07, 2021 |
| Unknown       | T3 MRD                      | [e4aff60504](https://linux-hardware.org/?probe=e4aff60504) | Sep 05, 2021 |
| Lenovo        | ThinkPad X130e 06222EU      | [a5822f49a3](https://linux-hardware.org/?probe=a5822f49a3) | Sep 05, 2021 |
| Lenovo        | ThinkPad X270 20HN0016GE    | [cecb5eb453](https://linux-hardware.org/?probe=cecb5eb453) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | [686ecdcfdb](https://linux-hardware.org/?probe=686ecdcfdb) | Sep 04, 2021 |
| Acer          | Aspire A517-52G             | [2d3edcffdd](https://linux-hardware.org/?probe=2d3edcffdd) | Sep 04, 2021 |
| Acer          | Nitro AN517-41              | [5e1633d787](https://linux-hardware.org/?probe=5e1633d787) | Sep 04, 2021 |
| Acer          | Nitro AN517-41              | [37968ff92c](https://linux-hardware.org/?probe=37968ff92c) | Sep 04, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [8c8a4d9cdf](https://linux-hardware.org/?probe=8c8a4d9cdf) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [bb2bba4301](https://linux-hardware.org/?probe=bb2bba4301) | Aug 31, 2021 |
| Apple         | MacBookPro8,1               | [cf9595f120](https://linux-hardware.org/?probe=cf9595f120) | Aug 31, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [2db9a5db96](https://linux-hardware.org/?probe=2db9a5db96) | Aug 29, 2021 |
| ASUSTek       | X556UQK                     | [e0132c63a3](https://linux-hardware.org/?probe=e0132c63a3) | Aug 29, 2021 |
| Medion        | P6618                       | [39c6d2480b](https://linux-hardware.org/?probe=39c6d2480b) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [39ae07c4d8](https://linux-hardware.org/?probe=39ae07c4d8) | Aug 27, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 150       | 12.4%   |
| Ubuntu 22.04                 | 67        | 5.54%   |
| Ubuntu 18.04                 | 61        | 5.04%   |
| Arch Rolling                 | 33        | 2.73%   |
| Zorin 16                     | 32        | 2.64%   |
| Linux Mint 20.2              | 30        | 2.48%   |
| OpenMandriva 4.3             | 24        | 1.98%   |
| Debian 11                    | 24        | 1.98%   |
| Arch                         | 23        | 1.9%    |
| BlackPanther 18.1            | 22        | 1.82%   |
| Manjaro                      | 20        | 1.65%   |
| Linux Mint 21.2              | 20        | 1.65%   |
| Fedora 37                    | 19        | 1.57%   |
| Fedora 35                    | 19        | 1.57%   |
| Linux Mint 21.1              | 17        | 1.4%    |
| Linux Mint 20.1              | 17        | 1.4%    |
| Ubuntu 21.04                 | 16        | 1.32%   |
| Fedora 38                    | 16        | 1.32%   |
| Fedora 33                    | 15        | 1.24%   |
| Debian 12                    | 15        | 1.24%   |
| Linux Mint 19.3              | 14        | 1.16%   |
| KDE neon 20.04               | 14        | 1.16%   |
| Ubuntu 19.10                 | 13        | 1.07%   |
| Ubuntu 22.10                 | 12        | 0.99%   |
| Ubuntu 21.10                 | 12        | 0.99%   |
| Pop!_OS 22.04                | 12        | 0.99%   |
| Linux Mint 20.3              | 12        | 0.99%   |
| Fedora 36                    | 12        | 0.99%   |
| Fedora 32                    | 12        | 0.99%   |
| EndeavourOS Rolling          | 12        | 0.99%   |
| OpenMandriva 4.2             | 11        | 0.91%   |
| Fedora 39                    | 11        | 0.91%   |
| Fedora 34                    | 11        | 0.91%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.83%   |
| Linux Mint 21                | 10        | 0.83%   |
| Linux Mint 20                | 10        | 0.83%   |
| Zorin 15                     | 9         | 0.74%   |
| Pop!_OS 21.04                | 9         | 0.74%   |
| Ubuntu 23.04                 | 8         | 0.66%   |
| Ubuntu 20.10                 | 8         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 354       | 31.13%  |
| Linux Mint    | 126       | 11.08%  |
| Fedora        | 102       | 8.97%   |
| OpenMandriva  | 61        | 5.36%   |
| Manjaro       | 56        | 4.93%   |
| Debian        | 53        | 4.66%   |
| Arch          | 53        | 4.66%   |
| Zorin         | 45        | 3.96%   |
| Pop!_OS       | 36        | 3.17%   |
| BlackPanther  | 25        | 2.2%    |
| KDE neon      | 21        | 1.85%   |
| openSUSE      | 19        | 1.67%   |
| Xubuntu       | 16        | 1.41%   |
| Kubuntu       | 16        | 1.41%   |
| Elementary    | 16        | 1.41%   |
| SteamOS       | 14        | 1.23%   |
| EndeavourOS   | 12        | 1.06%   |
| ROSA          | 11        | 0.97%   |
| Endless       | 9         | 0.79%   |
| ArcoLinux     | 8         | 0.7%    |
| Kali          | 7         | 0.62%   |
| Ubuntu Unity  | 6         | 0.53%   |
| Ubuntu Budgie | 6         | 0.53%   |
| MX            | 6         | 0.53%   |
| LMDE          | 6         | 0.53%   |
| Ubuntu MATE   | 5         | 0.44%   |
| Gentoo        | 5         | 0.44%   |
| Nobara        | 3         | 0.26%   |
| NixOS         | 3         | 0.26%   |
| Clear Linux   | 3         | 0.26%   |
| TUXEDO OS     | 2         | 0.18%   |
| Solus         | 2         | 0.18%   |
| Siduction     | 2         | 0.18%   |
| Parrot        | 2         | 0.18%   |
| Lubuntu       | 2         | 0.18%   |
| Garuda Linux  | 2         | 0.18%   |
| Devuan        | 2         | 0.18%   |
| Deepin        | 2         | 0.18%   |
| CentOS        | 2         | 0.18%   |
| CachyOS       | 2         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 24        | 1.79%   |
| 5.4.0-42-generic         | 16        | 1.19%   |
| 5.15.0-56-generic        | 14        | 1.04%   |
| 5.15.0-43-generic        | 14        | 1.04%   |
| 4.18.16-desktop-1bP      | 13        | 0.97%   |
| 5.4.0-58-generic         | 12        | 0.89%   |
| 5.3.0-46-generic         | 12        | 0.89%   |
| 5.15.0-52-generic        | 11        | 0.82%   |
| 5.10.14-desktop-1omv4002 | 11        | 0.82%   |
| 5.6.14-desktop-2bP       | 10        | 0.74%   |
| 5.4.0-52-generic         | 10        | 0.74%   |
| 5.3.0-26-generic         | 10        | 0.74%   |
| 5.4.0-29-generic         | 9         | 0.67%   |
| 5.4.0-26-generic         | 9         | 0.67%   |
| 5.13.0-39-generic        | 9         | 0.67%   |
| 5.13.0-28-generic        | 9         | 0.67%   |
| 5.13.0-27-generic        | 9         | 0.67%   |
| 6.2.0-39-generic         | 8         | 0.6%    |
| 5.4.0-91-generic         | 8         | 0.6%    |
| 5.11.0-37-generic        | 8         | 0.6%    |
| 5.4.0-74-generic         | 7         | 0.52%   |
| 5.4.0-48-generic         | 7         | 0.52%   |
| 5.15.0-91-generic        | 7         | 0.52%   |
| 5.15.0-58-generic        | 7         | 0.52%   |
| 5.15.0-46-generic        | 7         | 0.52%   |
| 5.13.0-valve36-1-neptune | 7         | 0.52%   |
| 5.11.0-27-generic        | 7         | 0.52%   |
| 5.11.0-25-generic        | 7         | 0.52%   |
| 6.5.0-14-generic         | 6         | 0.45%   |
| 6.1.1-desktop-1omv2290   | 6         | 0.45%   |
| 5.4.0-33-generic         | 6         | 0.45%   |
| 5.3.0-42-generic         | 6         | 0.45%   |
| 5.15.0-50-generic        | 6         | 0.45%   |
| 5.11.0-38-generic        | 6         | 0.45%   |
| 5.10.0-8-amd64           | 6         | 0.45%   |
| 6.6.6-200.fc39.x86_64    | 5         | 0.37%   |
| 6.2.0-36-generic         | 5         | 0.37%   |
| 6.2.0-32-generic         | 5         | 0.37%   |
| 5.8.0-43-generic         | 5         | 0.37%   |
| 5.4.0-28-generic         | 5         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 171       | 13.52%  |
| 5.15.0  | 123       | 9.72%   |
| 5.13.0  | 73        | 5.77%   |
| 5.11.0  | 64        | 5.06%   |
| 5.8.0   | 49        | 3.87%   |
| 5.3.0   | 47        | 3.72%   |
| 4.15.0  | 46        | 3.64%   |
| 6.2.0   | 37        | 2.92%   |
| 5.19.0  | 34        | 2.69%   |
| 5.10.0  | 30        | 2.37%   |
| 5.16.7  | 25        | 1.98%   |
| 5.0.0   | 22        | 1.74%   |
| 6.1.0   | 21        | 1.66%   |
| 4.18.0  | 14        | 1.11%   |
| 4.18.16 | 13        | 1.03%   |
| 6.5.0   | 12        | 0.95%   |
| 5.10.14 | 11        | 0.87%   |
| 4.19.0  | 11        | 0.87%   |
| 5.6.14  | 10        | 0.79%   |
| 6.2.6   | 9         | 0.71%   |
| 6.6.6   | 7         | 0.55%   |
| 6.6.8   | 6         | 0.47%   |
| 6.6.2   | 6         | 0.47%   |
| 6.3.5   | 6         | 0.47%   |
| 6.2.11  | 6         | 0.47%   |
| 6.1.1   | 6         | 0.47%   |
| 5.17.5  | 6         | 0.47%   |
| 6.0.7   | 5         | 0.4%    |
| 5.15.12 | 5         | 0.4%    |
| 6.5.3   | 4         | 0.32%   |
| 6.4.11  | 4         | 0.32%   |
| 6.1.52  | 4         | 0.32%   |
| 6.0.12  | 4         | 0.32%   |
| 5.9.11  | 4         | 0.32%   |
| 5.7.9   | 4         | 0.32%   |
| 5.7.0   | 4         | 0.32%   |
| 5.3.18  | 4         | 0.32%   |
| 5.19.7  | 4         | 0.32%   |
| 5.17.1  | 4         | 0.32%   |
| 5.11.12 | 4         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 185       | 14.85%  |
| 5.15    | 145       | 11.64%  |
| 5.13    | 84        | 6.74%   |
| 5.11    | 75        | 6.02%   |
| 5.8     | 64        | 5.14%   |
| 6.2     | 63        | 5.06%   |
| 5.10    | 61        | 4.9%    |
| 5.3     | 55        | 4.41%   |
| 6.1     | 52        | 4.17%   |
| 5.19    | 47        | 3.77%   |
| 4.15    | 46        | 3.69%   |
| 5.16    | 41        | 3.29%   |
| 6.6     | 29        | 2.33%   |
| 6.0     | 29        | 2.33%   |
| 4.18    | 27        | 2.17%   |
| 6.5     | 26        | 2.09%   |
| 5.6     | 25        | 2.01%   |
| 5.0     | 23        | 1.85%   |
| 5.17    | 22        | 1.77%   |
| 6.4     | 18        | 1.44%   |
| 5.7     | 18        | 1.44%   |
| 5.9     | 15        | 1.2%    |
| 5.18    | 13        | 1.04%   |
| 4.19    | 13        | 1.04%   |
| 6.3     | 12        | 0.96%   |
| 5.14    | 12        | 0.96%   |
| 5.12    | 11        | 0.88%   |
| 4.9     | 7         | 0.56%   |
| 5.5     | 6         | 0.48%   |
| 4.4     | 5         | 0.4%    |
| 4.17    | 4         | 0.32%   |
| 5.2     | 3         | 0.24%   |
| 4.12    | 3         | 0.24%   |
| 5.1     | 2         | 0.16%   |
| 4.13    | 2         | 0.16%   |
| 4.8     | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1087      | 98.82%  |
| i686   | 13        | 1.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 506       | 44.42%  |
| KDE5            | 212       | 18.61%  |
| X-Cinnamon      | 101       | 8.87%   |
| Unknown         | 97        | 8.52%   |
| XFCE            | 91        | 7.99%   |
| MATE            | 28        | 2.46%   |
| KDE             | 18        | 1.58%   |
| Pantheon        | 16        | 1.4%    |
| Cinnamon        | 15        | 1.32%   |
| Budgie          | 8         | 0.7%    |
| i3              | 7         | 0.61%   |
| Unity           | 6         | 0.53%   |
| KDE4            | 5         | 0.44%   |
| LXQt            | 4         | 0.35%   |
| LXDE            | 4         | 0.35%   |
| Deepin          | 4         | 0.35%   |
| awesome         | 4         | 0.35%   |
| sway            | 3         | 0.26%   |
| GNOME Flashback | 3         | 0.26%   |
| qtile           | 1         | 0.09%   |
| openbox         | 1         | 0.09%   |
| Hyprland        | 1         | 0.09%   |
| gamescope       | 1         | 0.09%   |
| fluxbox         | 1         | 0.09%   |
| Enlightenment   | 1         | 0.09%   |
| Bspwm           | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 859       | 75.75%  |
| Wayland | 216       | 19.05%  |
| Unknown | 51        | 4.5%    |
| Tty     | 8         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 515       | 44.9%   |
| SDDM    | 178       | 15.52%  |
| GDM3    | 147       | 12.82%  |
| GDM     | 144       | 12.55%  |
| LightDM | 131       | 11.42%  |
| TDM     | 25        | 2.18%   |
| KDM     | 5         | 0.44%   |
| SLiM    | 1         | 0.09%   |
| MDM     | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| de_AT   | 392       | 34.54%  |
| en_US   | 349       | 30.75%  |
| de_DE   | 171       | 15.07%  |
| Unknown | 113       | 9.96%   |
| en_GB   | 44        | 3.88%   |
| C       | 15        | 1.32%   |
| es_ES   | 7         | 0.62%   |
| pl_PL   | 6         | 0.53%   |
| en_IE   | 5         | 0.44%   |
| it_IT   | 4         | 0.35%   |
| ru_RU   | 3         | 0.26%   |
| POSIX   | 3         | 0.26%   |
| en_AT   | 3         | 0.26%   |
| de_CH   | 3         | 0.26%   |
| tr_TR   | 2         | 0.18%   |
| en_DE   | 2         | 0.18%   |
| uk_UA   | 1         | 0.09%   |
| sv_SE   | 1         | 0.09%   |
| ro_RO   | 1         | 0.09%   |
| pt_BR   | 1         | 0.09%   |
| nl_NL   | 1         | 0.09%   |
| hr_HR   | 1         | 0.09%   |
| fr_FR   | 1         | 0.09%   |
| en_CA   | 1         | 0.09%   |
| en_AU   | 1         | 0.09%   |
| en      | 1         | 0.09%   |
| de_LI   | 1         | 0.09%   |
| C.UTF8  | 1         | 0.09%   |
| bg_BG   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 625       | 55.11%  |
| BIOS | 509       | 44.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 841       | 74.76%  |
| Btrfs   | 121       | 10.76%  |
| Overlay | 89        | 7.91%   |
| Unknown | 30        | 2.67%   |
| Tmpfs   | 21        | 1.87%   |
| Xfs     | 9         | 0.8%    |
| Zfs     | 6         | 0.53%   |
| Ext2    | 3         | 0.27%   |
| Ext3    | 2         | 0.18%   |
| XXXXXXX | 1         | 0.09%   |
| Nfs     | 1         | 0.09%   |
| Aufs    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 548       | 48.5%   |
| GPT     | 465       | 41.15%  |
| MBR     | 117       | 10.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 993       | 88.82%  |
| Yes       | 125       | 11.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 843       | 75.61%  |
| Yes       | 272       | 24.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 310       | 28.21%  |
| Hewlett-Packard     | 203       | 18.47%  |
| Dell                | 110       | 10.01%  |
| ASUSTek Computer    | 102       | 9.28%   |
| Acer                | 95        | 8.64%   |
| Apple               | 38        | 3.46%   |
| Medion              | 32        | 2.91%   |
| Toshiba             | 28        | 2.55%   |
| TUXEDO              | 22        | 2%      |
| Sony                | 19        | 1.73%   |
| MSI                 | 16        | 1.46%   |
| Valve               | 14        | 1.27%   |
| HUAWEI              | 13        | 1.18%   |
| Fujitsu             | 13        | 1.18%   |
| Samsung Electronics | 9         | 0.82%   |
| Notebook            | 7         | 0.64%   |
| Unknown             | 7         | 0.64%   |
| TrekStor            | 4         | 0.36%   |
| Razer               | 4         | 0.36%   |
| Fujitsu Siemens     | 4         | 0.36%   |
| Clevo               | 4         | 0.36%   |
| VALE                | 3         | 0.27%   |
| Wortmann AG         | 2         | 0.18%   |
| Timi                | 2         | 0.18%   |
| System76            | 2         | 0.18%   |
| Shuttle             | 2         | 0.18%   |
| Schenker            | 2         | 0.18%   |
| Panasonic           | 2         | 0.18%   |
| Packard Bell        | 2         | 0.18%   |
| Hampoo              | 2         | 0.18%   |
| Google              | 2         | 0.18%   |
| Gigabyte Technology | 2         | 0.18%   |
| Framework           | 2         | 0.18%   |
| Chuwi               | 2         | 0.18%   |
| AXDIA International | 2         | 0.18%   |
| W271ELQ             | 1         | 0.09%   |
| TWJ                 | 1         | 0.09%   |
| TENKU               | 1         | 0.09%   |
| Teclast             | 1         | 0.09%   |
| SGIN                | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 14        | 1.27%   |
| Valve Jupiter                   | 13        | 1.18%   |
| Apple MacBookPro15,1            | 8         | 0.73%   |
| HP EliteBook 8570p              | 7         | 0.64%   |
| HP EliteBook 840 G3             | 6         | 0.55%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 5         | 0.45%   |
| HP Pavilion dv6                 | 5         | 0.45%   |
| HP Notebook                     | 5         | 0.45%   |
| HP EliteBook 8460p              | 5         | 0.45%   |
| HP EliteBook 840 G6             | 5         | 0.45%   |
| Toshiba Satellite C70D-B        | 4         | 0.36%   |
| Lenovo Yoga Slim 7 14ARE05 82A2 | 4         | 0.36%   |
| Lenovo IdeaPad 700-15ISK 80RU   | 4         | 0.36%   |
| HP Pavilion dv7                 | 4         | 0.36%   |
| HP EliteBook 840 G1             | 4         | 0.36%   |
| HP EliteBook 6930p              | 4         | 0.36%   |
| Dell XPS 15 9570                | 4         | 0.36%   |
| Dell Latitude E7450             | 4         | 0.36%   |
| Dell Latitude E6400             | 4         | 0.36%   |
| Dell Latitude 5520              | 4         | 0.36%   |
| ASUS UX303LAB                   | 4         | 0.36%   |
| Apple MacBookPro9,2             | 4         | 0.36%   |
| Apple MacBookPro8,1             | 4         | 0.36%   |
| TrekStor Notebook Slim S130     | 3         | 0.27%   |
| Toshiba Satellite Pro C660      | 3         | 0.27%   |
| Medion P15648                   | 3         | 0.27%   |
| Lenovo ThinkPad E470 20H2S00700 | 3         | 0.27%   |
| Lenovo ThinkBook 16p Gen 2 20YM | 3         | 0.27%   |
| HP ZBook 17 G5                  | 3         | 0.27%   |
| HP Pavilion g7                  | 3         | 0.27%   |
| HP EliteBook 850 G1             | 3         | 0.27%   |
| HP EliteBook 840 G8 Notebook PC | 3         | 0.27%   |
| HP EliteBook 2560p              | 3         | 0.27%   |
| Dell XPS 17 9700                | 3         | 0.27%   |
| Dell XPS 13 9343                | 3         | 0.27%   |
| Dell XPS 13 9305                | 3         | 0.27%   |
| Dell Latitude E7440             | 3         | 0.27%   |
| Dell Latitude E5550             | 3         | 0.27%   |
| Dell Latitude 5490              | 3         | 0.27%   |
| Dell Inspiron 1720              | 3         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 213       | 19.38%  |
| HP EliteBook        | 75        | 6.82%   |
| Acer Aspire         | 60        | 5.46%   |
| Dell Latitude       | 53        | 4.82%   |
| Lenovo IdeaPad      | 35        | 3.18%   |
| HP ProBook          | 33        | 3%      |
| HP Pavilion         | 28        | 2.55%   |
| Dell XPS            | 28        | 2.55%   |
| Toshiba Satellite   | 25        | 2.27%   |
| ASUS VivoBook       | 16        | 1.46%   |
| Lenovo Yoga         | 14        | 1.27%   |
| HP ZBook            | 14        | 1.27%   |
| Dell Inspiron       | 14        | 1.27%   |
| Unknown             | 14        | 1.27%   |
| Valve Jupiter       | 13        | 1.18%   |
| Fujitsu LIFEBOOK    | 13        | 1.18%   |
| Lenovo ThinkBook    | 12        | 1.09%   |
| HP Laptop           | 11        | 1%      |
| Acer TravelMate     | 11        | 1%      |
| Dell Precision      | 10        | 0.91%   |
| Acer Swift          | 10        | 0.91%   |
| Lenovo Legion       | 9         | 0.82%   |
| ASUS ROG            | 9         | 0.82%   |
| Apple MacBookPro15  | 8         | 0.73%   |
| HP OMEN             | 7         | 0.64%   |
| ASUS ZenBook        | 7         | 0.64%   |
| HP Compaq           | 6         | 0.55%   |
| HP 250              | 6         | 0.55%   |
| Acer Nitro          | 6         | 0.55%   |
| HP Notebook         | 5         | 0.45%   |
| Apple MacBookPro8   | 5         | 0.45%   |
| TUXEDO InfinityBook | 4         | 0.36%   |
| Razer Blade         | 4         | 0.36%   |
| HP 255              | 4         | 0.36%   |
| ASUS UX303LAB       | 4         | 0.36%   |
| Apple MacBookPro9   | 4         | 0.36%   |
| VALE Notebook       | 3         | 0.27%   |
| TUXEDO Book         | 3         | 0.27%   |
| TrekStor Notebook   | 3         | 0.27%   |
| MSI Modern          | 3         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 136       | 12.37%  |
| 2021    | 92        | 8.37%   |
| 2012    | 90        | 8.19%   |
| 2011    | 81        | 7.37%   |
| 2019    | 78        | 7.1%    |
| 2018    | 78        | 7.1%    |
| 2017    | 78        | 7.1%    |
| 2014    | 68        | 6.19%   |
| 2016    | 63        | 5.73%   |
| 2013    | 63        | 5.73%   |
| 2015    | 60        | 5.46%   |
| 2008    | 49        | 4.46%   |
| 2022    | 41        | 3.73%   |
| 2010    | 38        | 3.46%   |
| 2009    | 32        | 2.91%   |
| 2023    | 24        | 2.18%   |
| 2007    | 20        | 1.82%   |
| 2006    | 6         | 0.55%   |
| 2005    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1099      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 979       | 87.72%  |
| Enabled  | 137       | 12.28%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1094      | 99.55%  |
| Yes  | 5         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 284       | 25.56%  |
| 16.01-24.0  | 222       | 19.98%  |
| 8.01-16.0   | 217       | 19.53%  |
| 3.01-4.0    | 194       | 17.46%  |
| 32.01-64.0  | 101       | 9.09%   |
| 1.01-2.0    | 38        | 3.42%   |
| 24.01-32.0  | 23        | 2.07%   |
| 64.01-256.0 | 14        | 1.26%   |
| 2.01-3.0    | 11        | 0.99%   |
| 0.51-1.0    | 7         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 422       | 34.06%  |
| 2.01-3.0   | 321       | 25.91%  |
| 4.01-8.0   | 190       | 15.33%  |
| 3.01-4.0   | 154       | 12.43%  |
| 0.51-1.0   | 66        | 5.33%   |
| 8.01-16.0  | 59        | 4.76%   |
| 16.01-24.0 | 16        | 1.29%   |
| 24.01-32.0 | 5         | 0.4%    |
| 0.01-0.5   | 5         | 0.4%    |
| 32.01-64.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 829       | 73.95%  |
| 2      | 239       | 21.32%  |
| 3      | 40        | 3.57%   |
| 0      | 7         | 0.62%   |
| 5      | 3         | 0.27%   |
| 4      | 3         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 739       | 66.94%  |
| Yes       | 365       | 33.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 902       | 81.78%  |
| No        | 201       | 18.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1088      | 99%     |
| No        | 11        | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 871       | 78.75%  |
| No        | 235       | 21.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 1099      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 668       | 57.34%  |
| Graz                      | 64        | 5.49%   |
| Innsbruck                 | 31        | 2.66%   |
| Salzburg                  | 30        | 2.58%   |
| Linz                      | 30        | 2.58%   |
| Bad Hall                  | 18        | 1.55%   |
| Klagenfurt                | 16        | 1.37%   |
| Leonding                  | 9         | 0.77%   |
| Wiener Neustadt           | 8         | 0.69%   |
| Wels                      | 8         | 0.69%   |
| Baden bei Wien            | 7         | 0.6%    |
| Villach                   | 6         | 0.52%   |
| Sankt Pölten             | 6         | 0.52%   |
| Perg                      | 6         | 0.52%   |
| Dornbirn                  | 6         | 0.52%   |
| Wörgl                    | 5         | 0.43%   |
| Traun                     | 5         | 0.43%   |
| Korneuburg                | 5         | 0.43%   |
| Umhausen                  | 4         | 0.34%   |
| Gaenserndorf              | 4         | 0.34%   |
| Feldkirch                 | 4         | 0.34%   |
| Bregenz                   | 4         | 0.34%   |
| Traunkirchen              | 3         | 0.26%   |
| Lustenau                  | 3         | 0.26%   |
| Knittelfeld               | 3         | 0.26%   |
| Hard                      | 3         | 0.26%   |
| Woerdern                  | 2         | 0.17%   |
| Traiskirchen              | 2         | 0.17%   |
| Steyr                     | 2         | 0.17%   |
| Spillern                  | 2         | 0.17%   |
| Spielberg bei Knittelfeld | 2         | 0.17%   |
| Sommerein                 | 2         | 0.17%   |
| Schleinbach               | 2         | 0.17%   |
| Oberneukirchen            | 2         | 0.17%   |
| Neusiedl am See           | 2         | 0.17%   |
| Mauthausen                | 2         | 0.17%   |
| Mautern                   | 2         | 0.17%   |
| Mattersburg               | 2         | 0.17%   |
| Lech                      | 2         | 0.17%   |
| Krems                     | 2         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 328       | 460    | 23.89%  |
| SanDisk                        | 136       | 182    | 9.91%   |
| Seagate                        | 116       | 154    | 8.45%   |
| Toshiba                        | 103       | 128    | 7.5%    |
| WDC                            | 98        | 133    | 7.14%   |
| Unknown                        | 76        | 106    | 5.54%   |
| SK hynix                       | 65        | 85     | 4.73%   |
| Kingston                       | 55        | 70     | 4.01%   |
| Crucial                        | 51        | 69     | 3.71%   |
| Intel                          | 42        | 46     | 3.06%   |
| Micron Technology              | 32        | 42     | 2.33%   |
| Hitachi                        | 31        | 36     | 2.26%   |
| HGST                           | 28        | 36     | 2.04%   |
| Intenso                        | 24        | 30     | 1.75%   |
| Apple                          | 17        | 29     | 1.24%   |
| Transcend                      | 16        | 18     | 1.17%   |
| KIOXIA                         | 16        | 23     | 1.17%   |
| China                          | 10        | 10     | 0.73%   |
| LITEONIT                       | 7         | 10     | 0.51%   |
| Unknown                        | 7         | 12     | 0.51%   |
| Phison                         | 6         | 6      | 0.44%   |
| Micron/Crucial Technology      | 6         | 6      | 0.44%   |
| SABRENT                        | 5         | 5      | 0.36%   |
| Phison Electronics             | 5         | 6      | 0.36%   |
| LITEON                         | 5         | 6      | 0.36%   |
| A-DATA Technology              | 5         | 8      | 0.36%   |
| MAXIO Technology (Hangzhou)    | 4         | 4      | 0.29%   |
| Lenovo                         | 4         | 5      | 0.29%   |
| ASMT                           | 4         | 6      | 0.29%   |
| Union Memory (Shenzhen)        | 3         | 4      | 0.22%   |
| OCZ                            | 3         | 4      | 0.22%   |
| Kingston Technology Company    | 3         | 3      | 0.22%   |
| JMicron Technology             | 3         | 3      | 0.22%   |
| INNOVATION IT                  | 3         | 5      | 0.22%   |
| Verbatim                       | 2         | 2      | 0.15%   |
| UMIS                           | 2         | 2      | 0.15%   |
| SPCC                           | 2         | 2      | 0.15%   |
| Solid State Storage Technology | 2         | 2      | 0.15%   |
| Silicon Motion                 | 2         | 3      | 0.15%   |
| Leven                          | 2         | 2      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                       | 23        | 1.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 18        | 1.25%   |
| Toshiba MQ01ABD100 1TB                             | 15        | 1.04%   |
| Unknown MMC Card  64GB                             | 13        | 0.9%    |
| Samsung SSD 860 EVO 500GB                          | 13        | 0.9%    |
| Samsung SSD 850 EVO 250GB                          | 13        | 0.9%    |
| SanDisk NVMe SSD Drive 512GB                       | 12        | 0.83%   |
| Samsung NVMe SSD Drive 1TB                         | 12        | 0.83%   |
| Unknown MMC Card  32GB                             | 11        | 0.76%   |
| Toshiba MQ04ABF100 1TB                             | 10        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 10        | 0.69%   |
| Seagate ST500LT012-1DG142 500GB                    | 9         | 0.62%   |
| SanDisk SSD PLUS 240GB                             | 9         | 0.62%   |
| Samsung NVMe SSD Drive 1024GB                      | 9         | 0.62%   |
| Crucial CT240BX500SSD1 240GB                       | 9         | 0.62%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 8         | 0.55%   |
| Transcend TS240GMTS420S 240GB SSD                  | 8         | 0.55%   |
| SK hynix NVMe SSD Drive 512GB                      | 8         | 0.55%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 8         | 0.55%   |
| Samsung SSD 850 PRO 256GB                          | 8         | 0.55%   |
| Toshiba MQ01ABF050 500GB                           | 7         | 0.48%   |
| Seagate ST9500325AS 500GB                          | 7         | 0.48%   |
| Samsung SSD 850 EVO 500GB                          | 7         | 0.48%   |
| Samsung NVMe SSD Drive 500GB                       | 7         | 0.48%   |
| Crucial CT500MX500SSD1 500GB                       | 7         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                        | 7         | 0.48%   |
| Apple SSD AP0512M 500GB                            | 7         | 0.48%   |
| Unknown                                            | 7         | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB                     | 6         | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 6         | 0.42%   |
| SanDisk NVMe SSD Drive 1TB                         | 6         | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                       | 6         | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 6         | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                   | 6         | 0.42%   |
| Kingston SA400S37480G 480GB SSD                    | 6         | 0.42%   |
| Kingston NVMe SSD Drive 512GB                      | 6         | 0.42%   |
| HGST HTS721010A9E630 1TB                           | 6         | 0.42%   |
| HGST HTS541010A9E680 1TB                           | 6         | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 5         | 0.35%   |
| Unknown MMC Card  128GB                            | 5         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 114       | 152    | 36.08%  |
| Toshiba             | 66        | 87     | 20.89%  |
| WDC                 | 59        | 79     | 18.67%  |
| Hitachi             | 31        | 36     | 9.81%   |
| HGST                | 28        | 36     | 8.86%   |
| Samsung Electronics | 6         | 7      | 1.9%    |
| JMicron Technology  | 3         | 3      | 0.95%   |
| Fujitsu             | 2         | 2      | 0.63%   |
| Unknown             | 1         | 2      | 0.32%   |
| SABRENT             | 1         | 1      | 0.32%   |
| LaCie               | 1         | 1      | 0.32%   |
| Inateck             | 1         | 1      | 0.32%   |
| IB-1122             | 1         | 1      | 0.32%   |
| IB                  | 1         | 2      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 144       | 188    | 28.97%  |
| SanDisk             | 89        | 122    | 17.91%  |
| Crucial             | 48        | 66     | 9.66%   |
| Kingston            | 37        | 47     | 7.44%   |
| Intenso             | 22        | 28     | 4.43%   |
| SK hynix            | 19        | 24     | 3.82%   |
| Transcend           | 16        | 18     | 3.22%   |
| Intel               | 16        | 17     | 3.22%   |
| Micron Technology   | 12        | 17     | 2.41%   |
| China               | 10        | 10     | 2.01%   |
| Toshiba             | 9         | 11     | 1.81%   |
| Apple               | 8         | 9      | 1.61%   |
| WDC                 | 7         | 8      | 1.41%   |
| LITEONIT            | 7         | 10     | 1.41%   |
| LITEON              | 5         | 6      | 1.01%   |
| A-DATA Technology   | 5         | 8      | 1.01%   |
| SABRENT             | 4         | 4      | 0.8%    |
| OCZ                 | 3         | 4      | 0.6%    |
| INNOVATION IT       | 3         | 5      | 0.6%    |
| SPCC                | 2         | 2      | 0.4%    |
| Phison              | 2         | 2      | 0.4%    |
| Leven               | 2         | 2      | 0.4%    |
| KingDian            | 2         | 2      | 0.4%    |
| GOODRAM             | 2         | 2      | 0.4%    |
| Corsair             | 2         | 2      | 0.4%    |
| ASMT                | 2         | 2      | 0.4%    |
| Wdxsky              | 1         | 2      | 0.2%    |
| WDC WDS             | 1         | 1      | 0.2%    |
| Verbatim            | 1         | 1      | 0.2%    |
| Vaseky              | 1         | 1      | 0.2%    |
| Unknown             | 1         | 2      | 0.2%    |
| Teclast             | 1         | 1      | 0.2%    |
| TCSUNBOW            | 1         | 1      | 0.2%    |
| Seagate             | 1         | 1      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| Netac               | 1         | 4      | 0.2%    |
| Mushkin             | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Gigabyte Technology | 1         | 1      | 0.2%    |
| FORESEE             | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 460       | 640    | 35.06%  |
| NVMe    | 456       | 628    | 34.76%  |
| HDD     | 299       | 411    | 22.79%  |
| MMC     | 79        | 116    | 6.02%   |
| Unknown | 18        | 20     | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 673       | 993    | 53.2%   |
| NVMe | 456       | 627    | 36.05%  |
| MMC  | 79        | 116    | 6.25%   |
| SAS  | 57        | 79     | 4.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 521       | 739    | 68.73%  |
| 0.51-1.0   | 201       | 264    | 26.52%  |
| 1.01-2.0   | 29        | 39     | 3.83%   |
| 3.01-4.0   | 3         | 3      | 0.4%    |
| 4.01-10.0  | 3         | 5      | 0.4%    |
| 2.01-3.0   | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 334       | 28.47%  |
| 251-500        | 279       | 23.79%  |
| 501-1000       | 173       | 14.75%  |
| 1-20           | 84        | 7.16%   |
| 1001-2000      | 75        | 6.39%   |
| 51-100         | 71        | 6.05%   |
| Unknown        | 56        | 4.77%   |
| 21-50          | 46        | 3.92%   |
| More than 3000 | 31        | 2.64%   |
| 2001-3000      | 24        | 2.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 444       | 36.39%  |
| 21-50          | 230       | 18.85%  |
| 101-250        | 166       | 13.61%  |
| 51-100         | 127       | 10.41%  |
| 251-500        | 88        | 7.21%   |
| 501-1000       | 66        | 5.41%   |
| Unknown        | 56        | 4.59%   |
| 1001-2000      | 25        | 2.05%   |
| 2001-3000      | 10        | 0.82%   |
| More than 3000 | 8         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB               | 5         | 5      | 7.35%   |
| Toshiba MQ01ABF050 500GB                         | 3         | 4      | 4.41%   |
| Seagate ST500LT012-9WS142 500GB                  | 3         | 6      | 4.41%   |
| Seagate ST9250315AS 250GB                        | 2         | 2      | 2.94%   |
| Seagate ST9160412AS 160GB                        | 2         | 2      | 2.94%   |
| HGST HTS721010A9E630 1TB                         | 2         | 3      | 2.94%   |
| WDC WD5000LPLX-00ZNTT0 500GB                     | 1         | 1      | 1.47%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 1.47%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 1.47%   |
| Toshiba MQ01ABD100M 1TB                          | 1         | 1      | 1.47%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.47%   |
| Toshiba MK7559GSXP 752GB                         | 1         | 1      | 1.47%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 1.47%   |
| Toshiba MK3276GSX 320GB                          | 1         | 1      | 1.47%   |
| Toshiba MK2035GSS 200GB                          | 1         | 1      | 1.47%   |
| Toshiba MK1233GSG 120GB                          | 1         | 1      | 1.47%   |
| Seagate ST9750420AS 752GB                        | 1         | 1      | 1.47%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 1.47%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.47%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 2      | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 1.47%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB              | 1         | 9      | 1.47%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.47%   |
| SanDisk SSD PLUS 120GB                           | 1         | 1      | 1.47%   |
| SanDisk SDSSDH3 1T00 1TB                         | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 870 EVO 500GB            | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 870 EVO 1TB              | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 840 Series 120GB         | 1         | 1      | 1.47%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB SSD | 1         | 1      | 1.47%   |
| Samsung Electronics MMCRE28G8MXP-0VBH1 128GB SSD | 1         | 1      | 1.47%   |
| Samsung Electronics HN-M101MBB 1TB               | 1         | 1      | 1.47%   |
| Samsung Electronics HM500JI 500GB                | 1         | 1      | 1.47%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 1.47%   |
| LITEONIT LCS-128L9S-11 2.5 7mm 128GB SSD         | 1         | 1      | 1.47%   |
| LITEONIT CMT-64L3M 64GB SSD                      | 1         | 2      | 1.47%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 1      | 1.47%   |
| Kingston SMSM150S324G 24GB SSD                   | 1         | 1      | 1.47%   |
| Kingston SA400S37240G 240GB SSD                  | 1         | 1      | 1.47%   |
| Intel SSDSCKJF180A5L 180GB                       | 1         | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 30     | 25.76%  |
| Toshiba             | 11        | 12     | 16.67%  |
| Samsung Electronics | 7         | 8      | 10.61%  |
| Hitachi             | 5         | 6      | 7.58%   |
| HGST                | 5         | 6      | 7.58%   |
| Intel               | 4         | 4      | 6.06%   |
| SanDisk             | 3         | 3      | 4.55%   |
| WDC                 | 2         | 2      | 3.03%   |
| LITEONIT            | 2         | 3      | 3.03%   |
| Kingston            | 2         | 2      | 3.03%   |
| Micron Technology   | 1         | 1      | 1.52%   |
| LITEON              | 1         | 1      | 1.52%   |
| GOODRAM             | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |
| Crucial             | 1         | 1      | 1.52%   |
| Corsair             | 1         | 1      | 1.52%   |
| China               | 1         | 1      | 1.52%   |
| A-DATA Technology   | 1         | 3      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 30     | 39.53%  |
| Toshiba             | 11        | 12     | 25.58%  |
| Hitachi             | 5         | 6      | 11.63%  |
| HGST                | 5         | 6      | 11.63%  |
| WDC                 | 2         | 2      | 4.65%   |
| Samsung Electronics | 2         | 2      | 4.65%   |
| Fujitsu             | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 59     | 64.62%  |
| SSD  | 22        | 26     | 33.85%  |
| NVMe | 1         | 1      | 1.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Sandisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 661       | 1081   | 55.78%  |
| Works    | 458       | 647    | 38.65%  |
| Malfunc  | 65        | 86     | 5.49%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 704       | 55%     |
| Samsung Electronics                     | 194       | 15.16%  |
| AMD                                     | 111       | 8.67%   |
| SanDisk                                 | 75        | 5.86%   |
| SK hynix                                | 46        | 3.59%   |
| Toshiba America Info Systems            | 33        | 2.58%   |
| Micron Technology                       | 21        | 1.64%   |
| Kingston Technology Company             | 20        | 1.56%   |
| KIOXIA                                  | 14        | 1.09%   |
| Nvidia                                  | 11        | 0.86%   |
| Phison Electronics                      | 8         | 0.63%   |
| Micron/Crucial Technology               | 8         | 0.63%   |
| Apple                                   | 8         | 0.63%   |
| Union Memory (Shenzhen)                 | 6         | 0.47%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.31%   |
| Lenovo                                  | 4         | 0.31%   |
| Silicon Motion                          | 3         | 0.23%   |
| Solid State Storage Technology          | 2         | 0.16%   |
| VIA Technologies                        | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.08%   |
| Shenzhen Unionmemory Information System | 1         | 0.08%   |
| Seagate Technology                      | 1         | 0.08%   |
| Realtek Semiconductor                   | 1         | 0.08%   |
| O2 Micro                                | 1         | 0.08%   |
| Marvell Technology Group                | 1         | 0.08%   |
| ADATA Technology                        | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 99        | 7.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 91        | 6.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 85        | 6.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 82        | 6%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 78        | 5.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 52        | 3.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 44        | 3.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 42        | 3.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 37        | 2.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 34        | 2.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 32        | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 26        | 1.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 25        | 1.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 24        | 1.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 24        | 1.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 22        | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 21        | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 21        | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 19        | 1.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 18        | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 17        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 16        | 1.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 13        | 0.95%   |
| Intel SSD 660P Series                                                            | 13        | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 13        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 0.88%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 11        | 0.8%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 11        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 10        | 0.73%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 10        | 0.73%   |
| SK hynix BC511 NVMe SSD                                                          | 9         | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.59%   |
| Apple ANS2 NVMe Controller                                                       | 8         | 0.59%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 7         | 0.51%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 7         | 0.51%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 7         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 724       | 54.31%  |
| NVMe | 457       | 34.28%  |
| RAID | 89        | 6.68%   |
| IDE  | 63        | 4.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 884       | 80.44%  |
| AMD    | 215       | 19.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 2.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 1.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 17        | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 1.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 1.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 1.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 1.27%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 14        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 1.27%   |
| AMD Custom APU 0405                           | 14        | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 13        | 1.18%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 1.09%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 1.09%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 11        | 1%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 10        | 0.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.82%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.73%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 8         | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 7         | 0.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.64%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 284       | 25.82%  |
| Intel Core i5           | 276       | 25.09%  |
| Other                   | 104       | 9.45%   |
| Intel Core 2 Duo        | 59        | 5.36%   |
| AMD Ryzen 7             | 55        | 5%      |
| Intel Core i3           | 47        | 4.27%   |
| AMD Ryzen 5             | 44        | 4%      |
| Intel Celeron           | 39        | 3.55%   |
| Intel Pentium           | 28        | 2.55%   |
| AMD Ryzen 7 PRO         | 24        | 2.18%   |
| Intel Atom              | 20        | 1.82%   |
| Intel Pentium Dual-Core | 9         | 0.82%   |
| Intel Core i9           | 9         | 0.82%   |
| AMD Ryzen 9             | 9         | 0.82%   |
| AMD A6                  | 9         | 0.82%   |
| AMD A4                  | 9         | 0.82%   |
| AMD A8                  | 8         | 0.73%   |
| AMD Ryzen 5 PRO         | 7         | 0.64%   |
| Intel Core 2            | 6         | 0.55%   |
| AMD E2                  | 6         | 0.55%   |
| Intel Pentium Silver    | 5         | 0.45%   |
| Intel Genuine           | 4         | 0.36%   |
| AMD E1                  | 4         | 0.36%   |
| AMD Ryzen 3             | 3         | 0.27%   |
| AMD E                   | 3         | 0.27%   |
| AMD Athlon II           | 3         | 0.27%   |
| AMD Athlon              | 3         | 0.27%   |
| AMD A10                 | 3         | 0.27%   |
| Intel Xeon              | 2         | 0.18%   |
| Intel Pentium Dual      | 2         | 0.18%   |
| Intel Core m5           | 2         | 0.18%   |
| AMD Turion 64 X2 Mobile | 2         | 0.18%   |
| Intel Pentium Gold      | 1         | 0.09%   |
| Intel Core m7           | 1         | 0.09%   |
| Intel Core M            | 1         | 0.09%   |
| Intel Core 2 Solo       | 1         | 0.09%   |
| Intel Celeron M         | 1         | 0.09%   |
| AMD Sempron             | 1         | 0.09%   |
| AMD PRO A8              | 1         | 0.09%   |
| AMD Phenom II           | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 497       | 45.18%  |
| 4       | 370       | 33.64%  |
| 8       | 104       | 9.45%   |
| 6       | 85        | 7.73%   |
| 1       | 14        | 1.27%   |
| 12      | 10        | 0.91%   |
| 14      | 8         | 0.73%   |
| 10      | 8         | 0.73%   |
| 24      | 1         | 0.09%   |
| 16      | 1         | 0.09%   |
| 5       | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1099      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 849       | 77.11%  |
| 1       | 251       | 22.8%   |
| Unknown | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1080      | 98.18%  |
| Unknown        | 13        | 1.18%   |
| 32-bit         | 7         | 0.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 306       | 26.75%  |
| 0x206a7    | 76        | 6.64%   |
| 0x306a9    | 62        | 5.42%   |
| 0x806ec    | 49        | 4.28%   |
| 0x806ea    | 36        | 3.15%   |
| 0x406e3    | 36        | 3.15%   |
| 0x306d4    | 35        | 3.06%   |
| 0x806c1    | 34        | 2.97%   |
| 0x1067a    | 33        | 2.88%   |
| 0x906ea    | 31        | 2.71%   |
| 0x40651    | 30        | 2.62%   |
| 0x806e9    | 23        | 2.01%   |
| 0x08600106 | 22        | 1.92%   |
| 0x306c3    | 21        | 1.84%   |
| 0x0a50000c | 19        | 1.66%   |
| 0x506e3    | 15        | 1.31%   |
| 0x20655    | 15        | 1.31%   |
| 0x10676    | 14        | 1.22%   |
| 0xa0652    | 13        | 1.14%   |
| 0x08600103 | 13        | 1.14%   |
| 0x906e9    | 12        | 1.05%   |
| 0x08108102 | 12        | 1.05%   |
| 0x706e5    | 11        | 0.96%   |
| 0x08608103 | 11        | 0.96%   |
| 0x07030105 | 11        | 0.96%   |
| 0x506c9    | 10        | 0.87%   |
| 0x806eb    | 9         | 0.79%   |
| 0x406c3    | 9         | 0.79%   |
| 0x906a3    | 8         | 0.7%    |
| 0x30678    | 8         | 0.7%    |
| 0x08600104 | 8         | 0.7%    |
| 0x906ed    | 7         | 0.61%   |
| 0x706a8    | 7         | 0.61%   |
| 0x406c4    | 7         | 0.61%   |
| 0x20652    | 7         | 0.61%   |
| 0x06006705 | 6         | 0.52%   |
| 0x05000119 | 6         | 0.52%   |
| 0x806d1    | 5         | 0.44%   |
| 0x6fd      | 5         | 0.44%   |
| 0x6fb      | 5         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 222       | 20.16%  |
| SandyBridge      | 90        | 8.17%   |
| IvyBridge        | 84        | 7.63%   |
| Haswell          | 75        | 6.81%   |
| Skylake          | 63        | 5.72%   |
| Penryn           | 59        | 5.36%   |
| Zen 2            | 56        | 5.09%   |
| TigerLake        | 50        | 4.54%   |
| Unknown          | 49        | 4.45%   |
| Broadwell        | 44        | 4%      |
| Zen 3            | 34        | 3.09%   |
| Silvermont       | 30        | 2.72%   |
| Westmere         | 29        | 2.63%   |
| Icelake          | 23        | 2.09%   |
| Alderlake Hybrid | 22        | 2%      |
| Zen+             | 21        | 1.91%   |
| Core             | 20        | 1.82%   |
| CometLake        | 18        | 1.63%   |
| Puma             | 14        | 1.27%   |
| Goldmont plus    | 14        | 1.27%   |
| Excavator        | 13        | 1.18%   |
| Goldmont         | 12        | 1.09%   |
| Zen              | 10        | 0.91%   |
| Bobcat           | 9         | 0.82%   |
| Bonnell          | 8         | 0.73%   |
| Nehalem          | 5         | 0.45%   |
| K10              | 5         | 0.45%   |
| Jaguar           | 5         | 0.45%   |
| K8 Hammer        | 4         | 0.36%   |
| Piledriver       | 3         | 0.27%   |
| P6               | 3         | 0.27%   |
| K10 Llano        | 3         | 0.27%   |
| Tremont          | 2         | 0.18%   |
| K8 & K10 hybrid  | 2         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 767       | 55.9%   |
| Nvidia                           | 307       | 22.38%  |
| AMD                              | 297       | 21.65%  |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 77        | 5.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 5.26%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 53        | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 45        | 3.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 3.2%    |
| Intel UHD Graphics 620                                                                   | 43        | 3.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 2.92%   |
| Intel HD Graphics 5500                                                                   | 37        | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 2.56%   |
| Intel HD Graphics 620                                                                    | 35        | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 2.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 2.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.49%   |
| Intel HD Graphics 530                                                                    | 17        | 1.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 1.07%   |
| AMD Lucienne                                                                             | 15        | 1.07%   |
| Nvidia GP108M [GeForce MX250]                                                            | 14        | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 0.92%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 13        | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.85%   |
| Intel HD Graphics 630                                                                    | 12        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                             | 10        | 0.71%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 10        | 0.71%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 10        | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 0.64%   |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.64%   |
| Intel HD Graphics 500                                                                    | 9         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 8         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 511       | 46.37%  |
| 1 x AMD        | 214       | 19.42%  |
| Intel + Nvidia | 210       | 19.06%  |
| 1 x Nvidia     | 81        | 7.35%   |
| Intel + AMD    | 46        | 4.17%   |
| 2 x AMD        | 20        | 1.81%   |
| AMD + Nvidia   | 17        | 1.54%   |
| 2 x Intel      | 2         | 0.18%   |
| 1 x SiS        | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 946       | 85.15%  |
| Proprietary | 142       | 12.78%  |
| Unknown     | 23        | 2.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 702       | 62.07%  |
| 0.01-0.5   | 138       | 12.2%   |
| 1.01-2.0   | 123       | 10.88%  |
| 0.51-1.0   | 72        | 6.37%   |
| 3.01-4.0   | 65        | 5.75%   |
| 5.01-6.0   | 14        | 1.24%   |
| 7.01-8.0   | 13        | 1.15%   |
| 2.01-3.0   | 2         | 0.18%   |
| 8.01-16.0  | 2         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 258       | 20.14%  |
| LG Display              | 186       | 14.52%  |
| BOE                     | 141       | 11.01%  |
| Chimei Innolux          | 140       | 10.93%  |
| Samsung Electronics     | 132       | 10.3%   |
| Apple                   | 40        | 3.12%   |
| Lenovo                  | 39        | 3.04%   |
| Dell                    | 37        | 2.89%   |
| Sharp                   | 36        | 2.81%   |
| Goldstar                | 27        | 2.11%   |
| Hewlett-Packard         | 23        | 1.8%    |
| Chi Mei Optoelectronics | 22        | 1.72%   |
| Acer                    | 15        | 1.17%   |
| InfoVision              | 14        | 1.09%   |
| AOC                     | 14        | 1.09%   |
| Valve                   | 12        | 0.94%   |
| PANDA                   | 12        | 0.94%   |
| Philips                 | 9         | 0.7%    |
| LG Philips              | 9         | 0.7%    |
| CSO                     | 9         | 0.7%    |
| BenQ                    | 9         | 0.7%    |
| Ancor Communications    | 9         | 0.7%    |
| Iiyama                  | 8         | 0.62%   |
| Eizo                    | 6         | 0.47%   |
| HannStar                | 5         | 0.39%   |
| CPT                     | 5         | 0.39%   |
| Sony                    | 4         | 0.31%   |
| Panasonic               | 4         | 0.31%   |
| Gericom                 | 4         | 0.31%   |
| Toshiba                 | 3         | 0.23%   |
| TMX                     | 3         | 0.23%   |
| LGD                     | 3         | 0.23%   |
| Analogix                | 3         | 0.23%   |
| ViewSonic               | 2         | 0.16%   |
| Unknown                 | 2         | 0.16%   |
| Medion Akoya            | 2         | 0.16%   |
| Medion                  | 2         | 0.16%   |
| KDB                     | 2         | 0.16%   |
| HUAWEI                  | 2         | 0.16%   |
| Fujitsu Siemens         | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 11        | 0.84%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 10        | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 10        | 0.77%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 9         | 0.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 9         | 0.69%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.61%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 8         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 8         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 8         | 0.61%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                | 8         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 7         | 0.54%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 7         | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 7         | 0.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch              | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch     | 6         | 0.46%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                | 6         | 0.46%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch         | 5         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch     | 5         | 0.38%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch       | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 5         | 0.38%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 5         | 0.38%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 5         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 4         | 0.31%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 4         | 0.31%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch          | 4         | 0.31%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 4         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 4         | 0.31%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 4         | 0.31%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch          | 4         | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch      | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch      | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 340x190mm 15.3-inch     | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 4         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 558       | 46.27%  |
| 1366x768 (WXGA)    | 211       | 17.5%   |
| 1600x900 (HD+)     | 90        | 7.46%   |
| 3840x2160 (4K)     | 58        | 4.81%   |
| 2560x1440 (QHD)    | 51        | 4.23%   |
| 1280x800 (WXGA)    | 48        | 3.98%   |
| 1920x1200 (WUXGA)  | 31        | 2.57%   |
| 1440x900 (WXGA+)   | 28        | 2.32%   |
| 2880x1800          | 16        | 1.33%   |
| 1680x1050 (WSXGA+) | 15        | 1.24%   |
| 800x1280           | 13        | 1.08%   |
| 3440x1440          | 13        | 1.08%   |
| 2560x1600          | 11        | 0.91%   |
| 3840x2400          | 8         | 0.66%   |
| 1280x1024 (SXGA)   | 6         | 0.5%    |
| 1024x600           | 6         | 0.5%    |
| Unknown            | 6         | 0.5%    |
| 2560x1080          | 5         | 0.41%   |
| 3840x1080          | 4         | 0.33%   |
| 3200x1800 (QHD+)   | 4         | 0.33%   |
| 2288x1287          | 3         | 0.25%   |
| 2256x1504          | 3         | 0.25%   |
| 2160x1440          | 3         | 0.25%   |
| 1920x540           | 3         | 0.25%   |
| 3456x2160          | 2         | 0.17%   |
| 1600x1200          | 2         | 0.17%   |
| 1360x768           | 2         | 0.17%   |
| 3000x2000          | 1         | 0.08%   |
| 2960x1050          | 1         | 0.08%   |
| 2880x1620          | 1         | 0.08%   |
| 2520x1680          | 1         | 0.08%   |
| 1920x1280          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 426       | 33.26%  |
| 14      | 168       | 13.11%  |
| 13      | 168       | 13.11%  |
| 17      | 133       | 10.38%  |
| 27      | 63        | 4.92%   |
| 12      | 45        | 3.51%   |
| 24      | 44        | 3.43%   |
| 23      | 31        | 2.42%   |
| 21      | 22        | 1.72%   |
| 16      | 22        | 1.72%   |
| 11      | 19        | 1.48%   |
| Unknown | 19        | 1.48%   |
| 34      | 17        | 1.33%   |
| 31      | 15        | 1.17%   |
| 7       | 11        | 0.86%   |
| 22      | 9         | 0.7%    |
| 10      | 9         | 0.7%    |
| 18      | 8         | 0.62%   |
| 54      | 7         | 0.55%   |
| 25      | 7         | 0.55%   |
| 19      | 7         | 0.55%   |
| 20      | 5         | 0.39%   |
| 84      | 4         | 0.31%   |
| 40      | 3         | 0.23%   |
| 3       | 3         | 0.23%   |
| 142     | 2         | 0.16%   |
| 39      | 2         | 0.16%   |
| 32      | 2         | 0.16%   |
| 28      | 2         | 0.16%   |
| 85      | 1         | 0.08%   |
| 72      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 38      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 674       | 53.24%  |
| 201-300        | 164       | 12.95%  |
| 351-400        | 157       | 12.4%   |
| 501-600        | 123       | 9.72%   |
| 401-500        | 41        | 3.24%   |
| 601-700        | 31        | 2.45%   |
| 701-800        | 19        | 1.5%    |
| Unknown        | 19        | 1.5%    |
| 1-100          | 13        | 1.03%   |
| 1001-1500      | 11        | 0.87%   |
| 801-900        | 6         | 0.47%   |
| 1501-2000      | 6         | 0.47%   |
| More than 2000 | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 900       | 79.72%  |
| 16/10   | 160       | 14.17%  |
| 21/9    | 18        | 1.59%   |
| Unknown | 15        | 1.33%   |
| 3/2     | 10        | 0.89%   |
| 0.67    | 10        | 0.89%   |
| 5/4     | 6         | 0.53%   |
| 6/5     | 4         | 0.35%   |
| 32/9    | 2         | 0.18%   |
| 1.00    | 2         | 0.18%   |
| 4/3     | 1         | 0.09%   |
| 0.62    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 429       | 33.7%   |
| 81-90          | 267       | 20.97%  |
| 121-130        | 117       | 9.19%   |
| 201-250        | 72        | 5.66%   |
| 71-80          | 68        | 5.34%   |
| 301-350        | 63        | 4.95%   |
| 61-70          | 45        | 3.53%   |
| 351-500        | 35        | 2.75%   |
| 251-300        | 28        | 2.2%    |
| 151-200        | 22        | 1.73%   |
| 51-60          | 19        | 1.49%   |
| 131-140        | 19        | 1.49%   |
| Unknown        | 19        | 1.49%   |
| More than 1000 | 18        | 1.41%   |
| 111-120        | 14        | 1.1%    |
| 1-40           | 13        | 1.02%   |
| 41-50          | 9         | 0.71%   |
| 141-150        | 7         | 0.55%   |
| 501-1000       | 7         | 0.55%   |
| 91-100         | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 547       | 43.59%  |
| 101-120       | 302       | 24.06%  |
| 51-100        | 204       | 16.25%  |
| 161-240       | 123       | 9.8%    |
| More than 240 | 48        | 3.82%   |
| Unknown       | 19        | 1.51%   |
| 1-50          | 12        | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 879       | 77.51%  |
| 2     | 186       | 16.4%   |
| 3     | 34        | 3%      |
| 0     | 30        | 2.65%   |
| 4     | 5         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 677       | 38.23%  |
| Realtek Semiconductor             | 517       | 29.19%  |
| Qualcomm Atheros                  | 195       | 11.01%  |
| Broadcom                          | 100       | 5.65%   |
| MediaTek                          | 24        | 1.36%   |
| Broadcom Limited                  | 20        | 1.13%   |
| Sierra Wireless                   | 19        | 1.07%   |
| Ralink                            | 16        | 0.9%    |
| Marvell Technology Group          | 16        | 0.9%    |
| Lenovo                            | 16        | 0.9%    |
| Ericsson Business Mobile Networks | 16        | 0.9%    |
| Dell                              | 16        | 0.9%    |
| Hewlett-Packard                   | 11        | 0.62%   |
| ASIX Electronics                  | 11        | 0.62%   |
| Huawei Technologies               | 9         | 0.51%   |
| Fibocom                           | 9         | 0.51%   |
| DisplayLink                       | 9         | 0.51%   |
| Qualcomm                          | 8         | 0.45%   |
| Nvidia                            | 8         | 0.45%   |
| Samsung Electronics               | 7         | 0.4%    |
| NetGear                           | 7         | 0.4%    |
| TP-Link                           | 6         | 0.34%   |
| Edimax Technology                 | 6         | 0.34%   |
| Google                            | 5         | 0.28%   |
| ZyXEL Communications              | 4         | 0.23%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.23%   |
| JMicron Technology                | 4         | 0.23%   |
| Ralink Technology                 | 3         | 0.17%   |
| ASUSTek Computer                  | 3         | 0.17%   |
| Xiaomi                            | 2         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.11%   |
| Motorola PCS                      | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| D-Link System                     | 2         | 0.11%   |
| Apple                             | 2         | 0.11%   |
| ZyDAS                             | 1         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| Sitecom Europe                    | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |
| Research In Motion                | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 331       | 15.15%  |
| Intel Wi-Fi 6 AX200                                                    | 85        | 3.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 61        | 2.79%   |
| Intel Wireless 8265 / 8275                                             | 60        | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 58        | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 56        | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 40        | 1.83%   |
| Intel Wireless 7265                                                    | 39        | 1.78%   |
| Intel Wi-Fi 6 AX201                                                    | 39        | 1.78%   |
| Intel Wireless 8260                                                    | 37        | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 33        | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 32        | 1.46%   |
| Intel Wireless 7260                                                    | 30        | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 28        | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 27        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 25        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 24        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 1.05%   |
| Intel Centrino Ultimate-N 6300                                         | 23        | 1.05%   |
| Intel Wireless 3165                                                    | 22        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 22        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 20        | 0.92%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                   | 18        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                               | 18        | 0.82%   |
| Intel 82567LM Gigabit Network Connection                               | 18        | 0.82%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 17        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 16        | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                   | 16        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 15        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                          | 15        | 0.69%   |
| Intel WiFi Link 5100                                                   | 14        | 0.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 14        | 0.64%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 14        | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 13        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 651       | 55.17%  |
| Qualcomm Atheros                  | 159       | 13.47%  |
| Realtek Semiconductor             | 151       | 12.8%   |
| Broadcom                          | 80        | 6.78%   |
| MediaTek                          | 23        | 1.95%   |
| Sierra Wireless                   | 19        | 1.61%   |
| Ralink                            | 16        | 1.36%   |
| Dell                              | 12        | 1.02%   |
| Broadcom Limited                  | 11        | 0.93%   |
| Fibocom                           | 9         | 0.76%   |
| Qualcomm                          | 7         | 0.59%   |
| TP-Link                           | 6         | 0.51%   |
| NetGear                           | 6         | 0.51%   |
| Edimax Technology                 | 6         | 0.51%   |
| ZyXEL Communications              | 4         | 0.34%   |
| Ericsson Business Mobile Networks | 4         | 0.34%   |
| Ralink Technology                 | 3         | 0.25%   |
| ASUSTek Computer                  | 3         | 0.25%   |
| Qualcomm Atheros Communications   | 2         | 0.17%   |
| Hewlett-Packard                   | 2         | 0.17%   |
| D-Link System                     | 2         | 0.17%   |
| ZyDAS                             | 1         | 0.08%   |
| Sitecom Europe                    | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| D-Link                            | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 85        | 7.2%    |
| Intel Wireless 8265 / 8275                                              | 60        | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 3.39%   |
| Intel Wireless 7265                                                     | 39        | 3.3%    |
| Intel Wi-Fi 6 AX201                                                     | 39        | 3.3%    |
| Intel Wireless 8260                                                     | 37        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 32        | 2.71%   |
| Intel Wireless 7260                                                     | 30        | 2.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 2.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 1.95%   |
| Intel Centrino Ultimate-N 6300                                          | 23        | 1.95%   |
| Intel Wireless 3165                                                     | 22        | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 22        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 17        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 15        | 1.27%   |
| Intel WiFi Link 5100                                                    | 14        | 1.19%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 14        | 1.19%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 14        | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 13        | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 12        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.02%   |
| Intel Wireless 3160                                                     | 12        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 12        | 1.02%   |
| Sierra Wireless EM7455                                                  | 11        | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 450       | 47.02%  |
| Intel                         | 301       | 31.45%  |
| Qualcomm Atheros              | 60        | 6.27%   |
| Broadcom                      | 37        | 3.87%   |
| Marvell Technology Group      | 16        | 1.67%   |
| Lenovo                        | 16        | 1.67%   |
| ASIX Electronics              | 11        | 1.15%   |
| DisplayLink                   | 9         | 0.94%   |
| Broadcom Limited              | 9         | 0.94%   |
| Nvidia                        | 8         | 0.84%   |
| Samsung Electronics           | 7         | 0.73%   |
| Google                        | 5         | 0.52%   |
| OnePlus Technology (Shenzhen) | 4         | 0.42%   |
| JMicron Technology            | 4         | 0.42%   |
| Huawei Technologies           | 4         | 0.42%   |
| Xiaomi                        | 2         | 0.21%   |
| Motorola PCS                  | 2         | 0.21%   |
| Hewlett-Packard               | 2         | 0.21%   |
| Apple                         | 2         | 0.21%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.1%    |
| Research In Motion            | 1         | 0.1%    |
| Qualcomm                      | 1         | 0.1%    |
| NetGear                       | 1         | 0.1%    |
| MediaTek                      | 1         | 0.1%    |
| Linksys                       | 1         | 0.1%    |
| Cypress Semiconductor         | 1         | 0.1%    |
| Attansic Technology           | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 331       | 34.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 61        | 6.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 58        | 5.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 56        | 5.77%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 1.96%   |
| Intel Ethernet Connection (6) I219-V                                   | 18        | 1.86%   |
| Intel 82577LM Gigabit Network Connection                               | 18        | 1.86%   |
| Intel 82567LM Gigabit Network Connection                               | 18        | 1.86%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 1.75%   |
| Intel Ethernet Connection (4) I219-V                                   | 16        | 1.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 1.55%   |
| Intel Ethernet Connection (3) I218-LM                                  | 15        | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 1.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 11        | 1.13%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.03%   |
| Intel Ethernet Connection I219-V                                       | 9         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                                  | 9         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                                  | 8         | 0.82%   |
| Lenovo USB-C Dock Ethernet                                             | 7         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.62%   |
| Intel Ethernet Connection (23) I219-LM                                 | 6         | 0.62%   |
| Intel Ethernet Connection (13) I219-LM                                 | 6         | 0.62%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 6         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.52%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.41%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.41%   |
| OnePlus (Shenzhen) Android                                             | 4         | 0.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 4         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                                   | 4         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                                  | 4         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1088      | 53.83%  |
| Ethernet | 900       | 44.53%  |
| Modem    | 31        | 1.53%   |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 900       | 77.72%  |
| Ethernet | 258       | 22.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 804       | 73.16%  |
| 1     | 263       | 23.93%  |
| 3     | 18        | 1.64%   |
| 0     | 14        | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 946       | 84.54%  |
| Yes  | 173       | 15.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 483       | 54.64%  |
| Realtek Semiconductor           | 88        | 9.95%   |
| Broadcom                        | 53        | 6%      |
| Qualcomm Atheros Communications | 52        | 5.88%   |
| IMC Networks                    | 40        | 4.52%   |
| Lite-On Technology              | 33        | 3.73%   |
| Apple                           | 29        | 3.28%   |
| Foxconn / Hon Hai               | 27        | 3.05%   |
| Hewlett-Packard                 | 17        | 1.92%   |
| Dell                            | 14        | 1.58%   |
| Cambridge Silicon Radio         | 10        | 1.13%   |
| Toshiba                         | 9         | 1.02%   |
| Ralink                          | 5         | 0.57%   |
| Foxconn International           | 5         | 0.57%   |
| MediaTek                        | 4         | 0.45%   |
| USI                             | 3         | 0.34%   |
| Realtek                         | 2         | 0.23%   |
| ASUSTek Computer                | 2         | 0.23%   |
| Alps Electric                   | 2         | 0.23%   |
| TP-Link                         | 1         | 0.11%   |
| i.Tech Dynamic Limited          | 1         | 0.11%   |
| Fujitsu                         | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 188       | 21.27%  |
| Intel AX201 Bluetooth                               | 90        | 10.18%  |
| Intel AX200 Bluetooth                               | 81        | 9.16%   |
| Realtek Bluetooth Radio                             | 65        | 7.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 47        | 5.32%   |
| Intel Bluetooth Device                              | 31        | 3.51%   |
| IMC Networks Bluetooth Radio                        | 19        | 2.15%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 1.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.47%   |
| Apple Bluetooth Host Controller                     | 13        | 1.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 1.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 1.13%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.13%   |
| Intel AX210 Bluetooth                               | 9         | 1.02%   |
| IMC Networks Wireless_Device                        | 8         | 0.9%    |
| IMC Networks Bluetooth Device                       | 8         | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 8         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.79%   |
| Lite-On Bluetooth Device                            | 7         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.68%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.57%   |
| Lite-On Wireless_Device                             | 5         | 0.57%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.57%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.45%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.45%   |
| Apple Bluetooth HCI                                 | 4         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 858       | 61.15%  |
| AMD                              | 251       | 17.89%  |
| Nvidia                           | 154       | 10.98%  |
| Lenovo                           | 16        | 1.14%   |
| C-Media Electronics              | 14        | 1%      |
| Logitech                         | 13        | 0.93%   |
| GN Netcom                        | 11        | 0.78%   |
| Realtek Semiconductor            | 9         | 0.64%   |
| Hewlett-Packard                  | 8         | 0.57%   |
| Apple                            | 8         | 0.57%   |
| Texas Instruments                | 6         | 0.43%   |
| Creative Technology              | 6         | 0.43%   |
| Plantronics                      | 4         | 0.29%   |
| Yamaha                           | 3         | 0.21%   |
| SteelSeries ApS                  | 3         | 0.21%   |
| Sony                             | 3         | 0.21%   |
| Sennheiser Communications        | 3         | 0.21%   |
| Focusrite-Novation               | 3         | 0.21%   |
| ZOOM                             | 2         | 0.14%   |
| RODE Microphones                 | 2         | 0.14%   |
| Kingston Technology              | 2         | 0.14%   |
| XMOS                             | 1         | 0.07%   |
| Valve Software                   | 1         | 0.07%   |
| Tenx Technology                  | 1         | 0.07%   |
| Silicon Motion                   | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Samsung Electronics              | 1         | 0.07%   |
| Roland                           | 1         | 0.07%   |
| No brand                         | 1         | 0.07%   |
| Microsoft                        | 1         | 0.07%   |
| Medeli Electronics               | 1         | 0.07%   |
| Mackie Designs                   | 1         | 0.07%   |
| M-Audio                          | 1         | 0.07%   |
| JMTek                            | 1         | 0.07%   |
| GYROCOM C&C                      | 1         | 0.07%   |
| Generalplus Technology           | 1         | 0.07%   |
| FiiO Electronics Technology      | 1         | 0.07%   |
| DSEA A/S                         | 1         | 0.07%   |
| Corsair                          | 1         | 0.07%   |
| Conexant Systems                 | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 139       | 8.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 127       | 7.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 95        | 5.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 88        | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 79        | 4.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 46        | 2.71%   |
| Intel 8 Series HD Audio Controller                                                                | 46        | 2.71%   |
| Intel Broadwell-U Audio Controller                                                                | 44        | 2.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 44        | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 43        | 2.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 36        | 2.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 1.71%   |
| AMD FCH Azalia Controller                                                                         | 29        | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 24        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 1.3%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 21        | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 18        | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 16        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 0.88%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 14        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 0.65%   |
| Realtek Semiconductor USB Audio                                                                   | 9         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 228       | 30.56%  |
| SK hynix              | 179       | 23.99%  |
| Micron Technology     | 105       | 14.08%  |
| Kingston              | 54        | 7.24%   |
| Unknown               | 44        | 5.9%    |
| Crucial               | 38        | 5.09%   |
| Ramaxel Technology    | 24        | 3.22%   |
| Elpida                | 16        | 2.14%   |
| Corsair               | 13        | 1.74%   |
| Unknown (ABCD)        | 11        | 1.47%   |
| G.Skill               | 7         | 0.94%   |
| Nanya Technology      | 6         | 0.8%    |
| A-DATA Technology     | 6         | 0.8%    |
| Transcend             | 2         | 0.27%   |
| Silicon Power         | 2         | 0.27%   |
| GOODRAM               | 2         | 0.27%   |
| Unknown               | 2         | 0.27%   |
| Vaseky                | 1         | 0.13%   |
| Smart                 | 1         | 0.13%   |
| Kingmax Semiconductor | 1         | 0.13%   |
| CSX                   | 1         | 0.13%   |
| ChangXin Memory       | 1         | 0.13%   |
| Avant                 | 1         | 0.13%   |
| ASint Technology      | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 20        | 2.55%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 11        | 1.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 10        | 1.28%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 9         | 1.15%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 9         | 1.15%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 8         | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 0.89%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 0.77%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 6         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 6         | 0.77%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 6         | 0.77%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 5         | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 0.64%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 5         | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 0.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 5         | 0.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 5         | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 4         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 4         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 4         | 0.51%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 4         | 0.51%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 4         | 0.51%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s               | 4         | 0.51%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                | 4         | 0.51%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                          | 4         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 314       | 50.4%   |
| DDR3    | 193       | 30.98%  |
| LPDDR4  | 36        | 5.78%   |
| DDR2    | 31        | 4.98%   |
| LPDDR3  | 17        | 2.73%   |
| SDRAM   | 13        | 2.09%   |
| LPDDR5  | 12        | 1.93%   |
| DDR5    | 6         | 0.96%   |
| Unknown | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 553       | 87.36%  |
| Row Of Chips | 70        | 11.06%  |
| Chip         | 8         | 1.26%   |
| DIMM         | 2         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 293       | 42.96%  |
| 4096  | 149       | 21.85%  |
| 16384 | 129       | 18.91%  |
| 2048  | 76        | 11.14%  |
| 32768 | 21        | 3.08%   |
| 1024  | 14        | 2.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 153       | 22.77%  |
| 1600    | 132       | 19.64%  |
| 2667    | 131       | 19.49%  |
| 2400    | 53        | 7.89%   |
| 2133    | 30        | 4.46%   |
| 1334    | 26        | 3.87%   |
| 1333    | 25        | 3.72%   |
| 667     | 18        | 2.68%   |
| 4267    | 13        | 1.93%   |
| 6400    | 11        | 1.64%   |
| 800     | 9         | 1.34%   |
| 4800    | 8         | 1.19%   |
| 4199    | 8         | 1.19%   |
| 1067    | 8         | 1.19%   |
| Unknown | 8         | 1.19%   |
| 1867    | 7         | 1.04%   |
| 3266    | 6         | 0.89%   |
| 2048    | 5         | 0.74%   |
| 8400    | 4         | 0.6%    |
| 4266    | 4         | 0.6%    |
| 5600    | 2         | 0.3%    |
| 3733    | 2         | 0.3%    |
| 975     | 2         | 0.3%    |
| 533     | 2         | 0.3%    |
| 333     | 2         | 0.3%    |
| 7467    | 1         | 0.15%   |
| 7400    | 1         | 0.15%   |
| 1066    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 54.55%  |
| Samsung Electronics | 2         | 18.18%  |
| Canon               | 2         | 18.18%  |
| Seiko Epson         | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-235 Series  | 1         | 9.09%   |
| Samsung SCX-4300 Series    | 1         | 9.09%   |
| Samsung C48x Series        | 1         | 9.09%   |
| HP LaserJet P1102          | 1         | 9.09%   |
| HP LaserJet 1200           | 1         | 9.09%   |
| HP LaserJet 1022           | 1         | 9.09%   |
| HP ENVY Pro 6400 series    | 1         | 9.09%   |
| HP Deskjet 3520 series     | 1         | 9.09%   |
| HP DeskJet 2600 series     | 1         | 9.09%   |
| Canon PIXMA iX6850 Printer | 1         | 9.09%   |
| Canon MG2100 series        | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30      | 1         | 33.33%  |
| Canon CanoScan                     | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 286       | 29.79%  |
| IMC Networks                           | 106       | 11.04%  |
| Bison Electronics                      | 58        | 6.04%   |
| Microdia                               | 57        | 5.94%   |
| Realtek Semiconductor                  | 51        | 5.31%   |
| Sunplus Innovation Technology          | 50        | 5.21%   |
| Quanta                                 | 49        | 5.1%    |
| Acer                                   | 39        | 4.06%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 3.54%   |
| Lite-On Technology                     | 33        | 3.44%   |
| Suyin                                  | 30        | 3.13%   |
| Apple                                  | 27        | 2.81%   |
| Syntek                                 | 22        | 2.29%   |
| Luxvisions Innotech Limited            | 19        | 1.98%   |
| Alcor Micro                            | 13        | 1.35%   |
| Logitech                               | 12        | 1.25%   |
| Lenovo                                 | 9         | 0.94%   |
| Ricoh                                  | 7         | 0.73%   |
| Primax Electronics                     | 6         | 0.63%   |
| Z-Star Microelectronics                | 5         | 0.52%   |
| Samsung Electronics                    | 5         | 0.52%   |
| USB Camera                             | 4         | 0.42%   |
| OmniVision Technologies                | 4         | 0.42%   |
| Silicon Motion                         | 3         | 0.31%   |
| Microsoft                              | 3         | 0.31%   |
| DigiTech                               | 3         | 0.31%   |
| SunplusIT                              | 2         | 0.21%   |
| Sony                                   | 2         | 0.21%   |
| Sonix Technology                       | 2         | 0.21%   |
| SHENZHEN AONI ELECTRONIC               | 2         | 0.21%   |
| Generalplus Technology                 | 2         | 0.21%   |
| 8SSC21D67422V1SR3AV5KW1                | 2         | 0.21%   |
| Valve Software                         | 1         | 0.1%    |
| Sunplus Technology                     | 1         | 0.1%    |
| SJ-180517-N                            | 1         | 0.1%    |
| ShineTech                              | 1         | 0.1%    |
| OYT Tech                               | 1         | 0.1%    |
| Nebraska Furniture Mart                | 1         | 0.1%    |
| KYE Systems (Mouse Systems)            | 1         | 0.1%    |
| Jieli Technology                       | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 74        | 7.68%   |
| IMC Networks Integrated Camera                      | 51        | 5.3%    |
| Microdia Integrated_Webcam_HD                       | 27        | 2.8%    |
| Chicony HD WebCam                                   | 26        | 2.7%    |
| Chicony HP HD Camera                                | 19        | 1.97%   |
| Bison Integrated Camera                             | 19        | 1.97%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 18        | 1.87%   |
| Quanta HD User Facing                               | 15        | 1.56%   |
| Realtek Integrated_Webcam_HD                        | 14        | 1.45%   |
| Lite-On Integrated Camera                           | 14        | 1.45%   |
| Acer Integrated Camera                              | 14        | 1.45%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 1.35%   |
| Quanta HP HD Camera                                 | 12        | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 1.25%   |
| Syntek Integrated Camera                            | 11        | 1.14%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 1.14%   |
| Realtek USB2.0 HD UVC WebCam                        | 10        | 1.04%   |
| Lite-On HP HD Camera                                | 10        | 1.04%   |
| Chicony USB2.0 HD UVC WebCam                        | 10        | 1.04%   |
| Chicony HP HD Webcam                                | 10        | 1.04%   |
| Chicony VGA WebCam                                  | 9         | 0.93%   |
| Bison Lenovo EasyCamera                             | 9         | 0.93%   |
| Apple FaceTime HD Camera                            | 9         | 0.93%   |
| Chicony USB 2.0 Camera                              | 8         | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 8         | 0.83%   |
| Acer SunplusIT Integrated Camera                    | 8         | 0.83%   |
| Realtek HD WebCam                                   | 7         | 0.73%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 7         | 0.73%   |
| Chicony Integrated HP HD Webcam                     | 7         | 0.73%   |
| Chicony Integrated Camera (1280x720@30)             | 7         | 0.73%   |
| Chicony HP Truevision HD camera                     | 7         | 0.73%   |
| Chicony HD User Facing                              | 7         | 0.73%   |
| Chicony FJ Camera                                   | 7         | 0.73%   |
| Syntek Lenovo EasyCamera                            | 6         | 0.62%   |
| Sunplus HD WebCam                                   | 6         | 0.62%   |
| Luxvisions Innotech Limited HP HD Camera            | 6         | 0.62%   |
| Lenovo Integrated Webcam [R5U877]                   | 6         | 0.62%   |
| Chicony USB2.0 Camera                               | 6         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 6         | 0.62%   |
| Apple Built-in iSight                               | 6         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 114       | 38.26%  |
| Synaptics                  | 106       | 35.57%  |
| Shenzhen Goodix Technology | 28        | 9.4%    |
| Upek                       | 17        | 5.7%    |
| AuthenTec                  | 17        | 5.7%    |
| LighTuning Technology      | 7         | 2.35%   |
| Elan Microelectronics      | 7         | 2.35%   |
| STMicroelectronics         | 1         | 0.34%   |
| Focal-systems.Corp         | 1         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 51        | 17.06%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 10.7%   |
| Shenzhen Goodix  Fingerprint Device                                        | 20        | 6.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.69%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 5.02%   |
| Validity Sensors VFS491                                                    | 11        | 3.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 3.68%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 3.01%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.68%   |
| AuthenTec AES2810                                                          | 8         | 2.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.34%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 2.34%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.67%   |
| Synaptics WBDI                                                             | 5         | 1.67%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.67%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.34%   |
| Synaptics WBDI Device                                                      | 4         | 1.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.34%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.34%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.34%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1%      |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1%      |
| Elan ELAN:ARM-M4                                                           | 3         | 1%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1%      |
| Synaptics TouchPad                                                         | 2         | 0.67%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.67%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.33%   |
| Synaptics UWP WBDI                                                         | 1         | 0.33%   |
| Synaptics  WBDI                                                            | 1         | 0.33%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.33%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 81        | 52.94%  |
| Broadcom              | 43        | 28.1%   |
| Lenovo                | 11        | 7.19%   |
| Upek                  | 10        | 6.54%   |
| O2 Micro              | 5         | 3.27%   |
| SCM Microsystems      | 1         | 0.65%   |
| Realtek Semiconductor | 1         | 0.65%   |
| Advanced Card Systems | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 52.94%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.19%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 6.54%   |
| Broadcom 58200                                                               | 8         | 5.23%   |
| Broadcom 5880                                                                | 7         | 4.58%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 2.61%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.65%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.65%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 601       | 52.58%  |
| 1     | 403       | 35.26%  |
| 2     | 103       | 9.01%   |
| 3     | 24        | 2.1%    |
| 4     | 6         | 0.52%   |
| 8     | 2         | 0.17%   |
| 6     | 2         | 0.17%   |
| 5     | 2         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 293       | 41.56%  |
| Chipcard                 | 124       | 17.59%  |
| Graphics card            | 97        | 13.76%  |
| Net/wireless             | 69        | 9.79%   |
| Multimedia controller    | 30        | 4.26%   |
| Bluetooth                | 18        | 2.55%   |
| Camera                   | 17        | 2.41%   |
| Sound                    | 15        | 2.13%   |
| Communication controller | 11        | 1.56%   |
| Card reader              | 8         | 1.13%   |
| Storage                  | 6         | 0.85%   |
| Unassigned class         | 4         | 0.57%   |
| Net/ethernet             | 4         | 0.57%   |
| Modem                    | 4         | 0.57%   |
| Flash memory             | 2         | 0.28%   |
| Storage/ide              | 1         | 0.14%   |
| Network                  | 1         | 0.14%   |
| Firewire controller      | 1         | 0.14%   |


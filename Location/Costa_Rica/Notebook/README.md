Linux in Costa Rica - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 333

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a40f8a9531](https://linux-hardware.org/?probe=a40f8a9531) | Jan 05, 2025 |
| HP            | EliteBook 840 G6            | [b2c0345c76](https://linux-hardware.org/?probe=b2c0345c76) | Dec 24, 2024 |
| Acer          | Aspire V5-472               | [4f7f3b1702](https://linux-hardware.org/?probe=4f7f3b1702) | Dec 05, 2024 |
| Acer          | Aspire V5-472               | [f653a24c52](https://linux-hardware.org/?probe=f653a24c52) | Dec 05, 2024 |
| Google        | Kefka                       | [1bab1809fc](https://linux-hardware.org/?probe=1bab1809fc) | Nov 27, 2024 |
| Samsung       | 300E5K/300E5Q               | [073b6e567f](https://linux-hardware.org/?probe=073b6e567f) | Nov 26, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6a69e8dd2b](https://linux-hardware.org/?probe=6a69e8dd2b) | Nov 14, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [cb6f1609b1](https://linux-hardware.org/?probe=cb6f1609b1) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [6028ccb88f](https://linux-hardware.org/?probe=6028ccb88f) | Oct 25, 2024 |
| Dell          | Latitude E5470              | [430ace52f3](https://linux-hardware.org/?probe=430ace52f3) | Oct 24, 2024 |
| HP            | ProBook 4510s               | [82921bfaa3](https://linux-hardware.org/?probe=82921bfaa3) | Oct 16, 2024 |
| HP            | Notebook                    | [5d34e36859](https://linux-hardware.org/?probe=5d34e36859) | Oct 12, 2024 |
| Dell          | Inspiron 3543               | [8867a3f043](https://linux-hardware.org/?probe=8867a3f043) | Oct 05, 2024 |
| Dell          | Latitude 7420               | [bdec0be003](https://linux-hardware.org/?probe=bdec0be003) | Sep 30, 2024 |
| Acer          | Aspire A315-44P             | [a60bab1d76](https://linux-hardware.org/?probe=a60bab1d76) | Sep 16, 2024 |
| Acer          | Aspire A315-44P             | [a2e4ae9bf4](https://linux-hardware.org/?probe=a2e4ae9bf4) | Sep 16, 2024 |
| Apple         | MacBookPro8,1               | [606582cd82](https://linux-hardware.org/?probe=606582cd82) | Sep 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b92c75fb55](https://linux-hardware.org/?probe=b92c75fb55) | Aug 26, 2024 |
| HP            | EliteBook 8540w             | [37bf22daf9](https://linux-hardware.org/?probe=37bf22daf9) | Aug 16, 2024 |
| HP            | EliteBook 8540w             | [e96ce0732d](https://linux-hardware.org/?probe=e96ce0732d) | Aug 16, 2024 |
| Acer          | Aspire 5742                 | [280430e59d](https://linux-hardware.org/?probe=280430e59d) | Jul 30, 2024 |
| HP            | Laptop 15-da0xxx            | [ed33f895c9](https://linux-hardware.org/?probe=ed33f895c9) | Jul 28, 2024 |
| Samsung       | 700T1C                      | [33a6415fdc](https://linux-hardware.org/?probe=33a6415fdc) | Jul 07, 2024 |
| Toshiba       | Satellite L755              | [f146c7cd82](https://linux-hardware.org/?probe=f146c7cd82) | Jul 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [845660f83a](https://linux-hardware.org/?probe=845660f83a) | Jul 06, 2024 |
| Acer          | Aspire E1-431               | [7927c359f4](https://linux-hardware.org/?probe=7927c359f4) | Jul 05, 2024 |
| Apple         | MacBookPro8,1               | [b749879a8b](https://linux-hardware.org/?probe=b749879a8b) | Jul 04, 2024 |
| TCL Commun... | 8085                        | [e0f28c27e1](https://linux-hardware.org/?probe=e0f28c27e1) | Jul 03, 2024 |
| TCL Commun... | 8085                        | [9163504543](https://linux-hardware.org/?probe=9163504543) | Jul 03, 2024 |
| HP            | Laptop 15-dy1xxx            | [91276fd4b3](https://linux-hardware.org/?probe=91276fd4b3) | Jul 02, 2024 |
| Dell          | Inspiron N4010              | [dad60b8122](https://linux-hardware.org/?probe=dad60b8122) | Jun 20, 2024 |
| Apple         | MacBookPro8,1               | [2639f09193](https://linux-hardware.org/?probe=2639f09193) | Jun 19, 2024 |
| Dell          | Latitude 7410               | [51a29349b7](https://linux-hardware.org/?probe=51a29349b7) | Jun 02, 2024 |
| Dell          | Latitude E5470              | [0471527291](https://linux-hardware.org/?probe=0471527291) | May 30, 2024 |
| Dell          | Latitude E5470              | [cb017d9ab6](https://linux-hardware.org/?probe=cb017d9ab6) | May 29, 2024 |
| Dell          | XPS 15 9560                 | [35684afb98](https://linux-hardware.org/?probe=35684afb98) | May 28, 2024 |
| Unknown       | Unknown                     | [c9abc346e8](https://linux-hardware.org/?probe=c9abc346e8) | May 27, 2024 |
| Dell          | XPS 15 9560                 | [134bad9ba1](https://linux-hardware.org/?probe=134bad9ba1) | May 25, 2024 |
| Samsung       | 930X2K/931X2K               | [f69d6ceb2c](https://linux-hardware.org/?probe=f69d6ceb2c) | May 23, 2024 |
| Samsung       | 930X2K/931X2K               | [032615adcb](https://linux-hardware.org/?probe=032615adcb) | May 23, 2024 |
| HP            | Notebook                    | [143a137ce0](https://linux-hardware.org/?probe=143a137ce0) | May 17, 2024 |
| HP            | Laptop 14-ck0xxx            | [94f1e2e58a](https://linux-hardware.org/?probe=94f1e2e58a) | May 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | [a0a81ab433](https://linux-hardware.org/?probe=a0a81ab433) | May 11, 2024 |
| Apple         | MacBookPro8,1               | [ac1a840bb3](https://linux-hardware.org/?probe=ac1a840bb3) | May 10, 2024 |
| Apple         | MacBookPro8,1               | [f6c6a3c2cb](https://linux-hardware.org/?probe=f6c6a3c2cb) | Apr 28, 2024 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [a9c83df6f3](https://linux-hardware.org/?probe=a9c83df6f3) | Apr 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | [0ccf03f0d9](https://linux-hardware.org/?probe=0ccf03f0d9) | Apr 13, 2024 |
| Apple         | MacBookPro8,1               | [ab1cbc61a9](https://linux-hardware.org/?probe=ab1cbc61a9) | Mar 30, 2024 |
| Valve         | Jupiter                     | [a4d5199429](https://linux-hardware.org/?probe=a4d5199429) | Mar 23, 2024 |
| Unknown       | WY133A                      | [de159f4170](https://linux-hardware.org/?probe=de159f4170) | Mar 20, 2024 |
| Unknown       | WY133A                      | [1abe291a71](https://linux-hardware.org/?probe=1abe291a71) | Mar 20, 2024 |
| Dell          | XPS 15 9530                 | [4cfd0ba254](https://linux-hardware.org/?probe=4cfd0ba254) | Mar 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | [b136a57d61](https://linux-hardware.org/?probe=b136a57d61) | Mar 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [644841f4df](https://linux-hardware.org/?probe=644841f4df) | Mar 07, 2024 |
| EVOO          | EV-C-125-3                  | [d452f3776a](https://linux-hardware.org/?probe=d452f3776a) | Feb 26, 2024 |
| HP            | EliteBook 840 G6            | [997fde90ec](https://linux-hardware.org/?probe=997fde90ec) | Feb 26, 2024 |
| HP            | EliteBook 840 G6            | [49371cd72c](https://linux-hardware.org/?probe=49371cd72c) | Feb 23, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [496f8751d2](https://linux-hardware.org/?probe=496f8751d2) | Feb 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8888984d3d](https://linux-hardware.org/?probe=8888984d3d) | Feb 14, 2024 |
| Acer          | Aspire E5-473               | [0a294c97ee](https://linux-hardware.org/?probe=0a294c97ee) | Jan 31, 2024 |
| HP            | Pavilion g4                 | [1edc58a524](https://linux-hardware.org/?probe=1edc58a524) | Jan 22, 2024 |
| GPU Compan... | GWTN141-10                  | [cd417ed644](https://linux-hardware.org/?probe=cd417ed644) | Jan 10, 2024 |
| GPU Compan... | GWTN141-10                  | [443e0e2a67](https://linux-hardware.org/?probe=443e0e2a67) | Jan 04, 2024 |
| HP            | G60                         | [a151a8084c](https://linux-hardware.org/?probe=a151a8084c) | Jan 01, 2024 |
| HP            | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Lenovo        | ThinkPad T420 4236DA4       | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Dell          | G15 5515                    | [259739c8b5](https://linux-hardware.org/?probe=259739c8b5) | Dec 14, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| HP            | EliteBook 8470p             | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Apple         | MacBookPro8,1               | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| Apple         | MacBookPro5,4               | [7045b84f52](https://linux-hardware.org/?probe=7045b84f52) | Nov 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| Toshiba       | Satellite L845              | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Dell          | Inspiron 3443               | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d8335b95a8](https://linux-hardware.org/?probe=d8335b95a8) | Oct 19, 2023 |
| Apple         | MacBookPro8,1               | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | [a814d9fa4b](https://linux-hardware.org/?probe=a814d9fa4b) | Sep 25, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| ASUSTek       | X541UV                      | [a66fcc9edb](https://linux-hardware.org/?probe=a66fcc9edb) | Sep 11, 2023 |
| Sony          | SVE14123CLW                 | [2fffba7739](https://linux-hardware.org/?probe=2fffba7739) | Sep 08, 2023 |
| Dell          | Inspiron 5567               | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [40693c0171](https://linux-hardware.org/?probe=40693c0171) | Aug 29, 2023 |
| Lenovo        | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | Katana 15 B13VGK            | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Samsung       | 930X2K/931X2K               | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| ASUSTek       | Q551LN                      | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Toshiba       | Satellite L755              | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Samsung       | 930X2K/931X2K               | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| HP            | ENVY 15                     | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| HP            | Notebook                    | [42558904aa](https://linux-hardware.org/?probe=42558904aa) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP            | Notebook                    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| HP            | Notebook                    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Samsung       | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Apple         | MacBookPro9,2               | [ba104d9250](https://linux-hardware.org/?probe=ba104d9250) | May 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b06388c1f4](https://linux-hardware.org/?probe=b06388c1f4) | May 09, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP            | ProBook 6570b               | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung       | 930X2K/931X2K               | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung       | 930X2K/931X2K               | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP            | EliteBook 8560p             | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Apple         | MacBookPro8,1               | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Laptop 15-da0xxx            | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer          | Aspire E1-431               | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| Dell          | XPS 15 9510                 | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| Acer          | Aspire V3-571G              | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| Unknown       | Unknown                     | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| HP            | Laptop 15-da0xxx            | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple         | MacBookPro8,1               | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP            | Laptop 15-da0xxx            | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Toshiba       | Satellite S55-A             | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba       | Satellite S55-A             | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| Dell          | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell          | Inspiron 3543               | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba       | Satellite C55-C             | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Toshiba       | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba       | Satellite C55-C             | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer          | Aspire E5-576               | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| Acer          | Aspire R3-131T              | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad        | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell          | Inspiron 3520               | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Dell          | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| HP            | Pavilion Notebook           | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Acer          | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP            | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Toshiba       | Satellite L45-B             | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| HP            | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Apple         | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Olivetti      | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Olivetti      | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP            | EliteBook 8570p             | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Toshiba       | Satellite C845              | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Acer          | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Apple         | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| Dell          | G3 3590                     | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Dell          | Inspiron 5584               | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| HP            | Laptop 14-bp0xx             | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| Dell          | XPS 15 9560                 | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | EliteBook 8570p             | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Acer          | Aspire 4739Z                | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Dell          | Latitude E5440              | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Dell          | G3 3590                     | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| Dell          | Inspiron 5559               | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| HP            | ProBook 455 G4              | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| HP            | 245 G4 Notebook PC          | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| HP            | Notebook                    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Toshiba       | Satellite C855D             | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| HP            | Pavilion Notebook           | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| HP            | 240 G6 Notebook PC          | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| System76      | Lemur                       | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| HP            | ProBook 450 G2              | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Purism        | Librem 15 v3                | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 14        | 6.01%   |
| Ubuntu 22.04                 | 13        | 5.58%   |
| Ubuntu 18.04                 | 12        | 5.15%   |
| Debian 12                    | 11        | 4.72%   |
| Zorin 16                     | 7         | 3%      |
| OpenMandriva 4.2             | 7         | 3%      |
| Zorin 17                     | 5         | 2.15%   |
| Ubuntu 24.04                 | 5         | 2.15%   |
| Ubuntu 19.04                 | 4         | 1.72%   |
| OpenMandriva 4.3             | 4         | 1.72%   |
| Debian 11                    | 4         | 1.72%   |
| Ubuntu 23.04                 | 3         | 1.29%   |
| Pop!_OS 22.04                | 3         | 1.29%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.29%   |
| OpenMandriva 23.08           | 3         | 1.29%   |
| Manjaro                      | 3         | 1.29%   |
| Lubuntu 24.04                | 3         | 1.29%   |
| Lubuntu 22.10                | 3         | 1.29%   |
| Lubuntu 22.04                | 3         | 1.29%   |
| Lubuntu 21.10                | 3         | 1.29%   |
| Lubuntu 21.04                | 3         | 1.29%   |
| Fedora 38                    | 3         | 1.29%   |
| Xubuntu 20.04                | 2         | 0.86%   |
| Ubuntu Studio 20.04          | 2         | 0.86%   |
| Ubuntu 21.04                 | 2         | 0.86%   |
| ROSA 12.5                    | 2         | 0.86%   |
| OpenMandriva 23.03           | 2         | 0.86%   |
| OpenMandriva 23.01           | 2         | 0.86%   |
| Manjaro 20.2.1               | 2         | 0.86%   |
| Lubuntu 23.10                | 2         | 0.86%   |
| Lubuntu 23.04                | 2         | 0.86%   |
| Linux Mint 21.2              | 2         | 0.86%   |
| Linux Mint 20.3              | 2         | 0.86%   |
| Linux Mint 20.1              | 2         | 0.86%   |
| Linux Mint 20                | 2         | 0.86%   |
| Kubuntu 22.04                | 2         | 0.86%   |
| KDE neon 20.04               | 2         | 0.86%   |
| Fedora 36                    | 2         | 0.86%   |
| Debian 10                    | 2         | 0.86%   |
| Arch Rolling                 | 2         | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 54        | 26.47%  |
| OpenMandriva     | 18        | 8.82%   |
| Debian           | 18        | 8.82%   |
| Linux Mint       | 13        | 6.37%   |
| Zorin            | 12        | 5.88%   |
| Fedora           | 11        | 5.39%   |
| Manjaro          | 9         | 4.41%   |
| Lubuntu          | 7         | 3.43%   |
| ROSA             | 5         | 2.45%   |
| Pop!_OS          | 5         | 2.45%   |
| Kubuntu          | 5         | 2.45%   |
| Xubuntu          | 3         | 1.47%   |
| openSUSE         | 3         | 1.47%   |
| KDE neon         | 3         | 1.47%   |
| Kali             | 3         | 1.47%   |
| Arch             | 3         | 1.47%   |
| Ubuntu Unity     | 2         | 0.98%   |
| Ubuntu Studio    | 2         | 0.98%   |
| Ubuntu MATE      | 2         | 0.98%   |
| Ubuntu Budgie    | 2         | 0.98%   |
| Parrot           | 2         | 0.98%   |
| Endless          | 2         | 0.98%   |
| Elementary       | 2         | 0.98%   |
| UbuntuDDE        | 1         | 0.49%   |
| SteamOS          | 1         | 0.49%   |
| Rocky Linux      | 1         | 0.49%   |
| Reborn OS        | 1         | 0.49%   |
| PureOS           | 1         | 0.49%   |
| Peppermint       | 1         | 0.49%   |
| org.kde.Platform | 1         | 0.49%   |
| Nobara           | 1         | 0.49%   |
| Mageia           | 1         | 0.49%   |
| LMDE             | 1         | 0.49%   |
| LinuxFX          | 1         | 0.49%   |
| Crystal Linux    | 1         | 0.49%   |
| Clear Linux      | 1         | 0.49%   |
| ChimeraOS        | 1         | 0.49%   |
| BigLinux         | 1         | 0.49%   |
| Bazzite          | 1         | 0.49%   |
| ArcoLinux        | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002          | 7         | 2.69%   |
| 6.4.11-desktop-1omv2390           | 4         | 1.54%   |
| 5.16.7-desktop-1omv4003           | 4         | 1.54%   |
| 5.0.0-23-generic                  | 4         | 1.54%   |
| 6.8.0-31-generic                  | 3         | 1.15%   |
| 5.4.0-77-generic                  | 3         | 1.15%   |
| 5.4.0-42-generic                  | 3         | 1.15%   |
| 5.19.0-32-generic                 | 3         | 1.15%   |
| 5.19.0-26-generic                 | 3         | 1.15%   |
| 5.13.0-16-generic                 | 3         | 1.15%   |
| 5.11.0-27-generic                 | 3         | 1.15%   |
| 5.0.0-25-generic                  | 3         | 1.15%   |
| 6.8.0-36-generic                  | 2         | 0.77%   |
| 6.6.21-generic-8rosa2021.1-x86_64 | 2         | 0.77%   |
| 6.5.0-5-generic                   | 2         | 0.77%   |
| 6.5.0-41-generic                  | 2         | 0.77%   |
| 6.3.8-200.fc38.x86_64             | 2         | 0.77%   |
| 6.2.6-desktop-1omv2390            | 2         | 0.77%   |
| 6.2.0-20-generic                  | 2         | 0.77%   |
| 6.2.0-18-generic                  | 2         | 0.77%   |
| 6.11.0-9-generic                  | 2         | 0.77%   |
| 6.1.0-10-amd64                    | 2         | 0.77%   |
| 6.0.6-76060006-generic            | 2         | 0.77%   |
| 5.9.16-1-MANJARO                  | 2         | 0.77%   |
| 5.8.0-50-generic                  | 2         | 0.77%   |
| 5.4.0-21-generic                  | 2         | 0.77%   |
| 5.3.0-40-generic                  | 2         | 0.77%   |
| 5.3.0-28-generic                  | 2         | 0.77%   |
| 5.15.0-91-generic                 | 2         | 0.77%   |
| 5.15.0-83-generic                 | 2         | 0.77%   |
| 5.15.0-58-generic                 | 2         | 0.77%   |
| 5.15.0-52-generic                 | 2         | 0.77%   |
| 5.15.0-41-generic                 | 2         | 0.77%   |
| 5.13.0-35-generic                 | 2         | 0.77%   |
| 5.13.0-20-generic                 | 2         | 0.77%   |
| 5.11.0-16-generic                 | 2         | 0.77%   |
| 4.15.0-112-generic                | 2         | 0.77%   |
| 6.9.7-sandy-custom                | 1         | 0.38%   |
| 6.9.6-200.fc40.x86_64             | 1         | 0.38%   |
| 6.9.5-sandy-custom                | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 9.39%   |
| 5.15.0  | 22        | 8.98%   |
| 6.5.0   | 13        | 5.31%   |
| 5.11.0  | 11        | 4.49%   |
| 6.8.0   | 10        | 4.08%   |
| 6.1.0   | 10        | 4.08%   |
| 5.19.0  | 10        | 4.08%   |
| 6.2.0   | 8         | 3.27%   |
| 5.13.0  | 8         | 3.27%   |
| 5.0.0   | 8         | 3.27%   |
| 5.3.0   | 7         | 2.86%   |
| 5.10.14 | 7         | 2.86%   |
| 5.10.0  | 7         | 2.86%   |
| 5.8.0   | 5         | 2.04%   |
| 4.15.0  | 5         | 2.04%   |
| 6.4.11  | 4         | 1.63%   |
| 5.16.7  | 4         | 1.63%   |
| 6.6.21  | 2         | 0.82%   |
| 6.6.2   | 2         | 0.82%   |
| 6.3.8   | 2         | 0.82%   |
| 6.3.6   | 2         | 0.82%   |
| 6.2.6   | 2         | 0.82%   |
| 6.12.1  | 2         | 0.82%   |
| 6.11.0  | 2         | 0.82%   |
| 6.1.1   | 2         | 0.82%   |
| 6.0.6   | 2         | 0.82%   |
| 5.9.16  | 2         | 0.82%   |
| 5.18.13 | 2         | 0.82%   |
| 5.14.0  | 2         | 0.82%   |
| 4.19.0  | 2         | 0.82%   |
| 6.9.7   | 1         | 0.41%   |
| 6.9.6   | 1         | 0.41%   |
| 6.9.5   | 1         | 0.41%   |
| 6.9.12  | 1         | 0.41%   |
| 6.8.9   | 1         | 0.41%   |
| 6.8.8   | 1         | 0.41%   |
| 6.8.1   | 1         | 0.41%   |
| 6.7.4   | 1         | 0.41%   |
| 6.7.12  | 1         | 0.41%   |
| 6.6.9   | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 9.54%   |
| 5.15    | 23        | 9.54%   |
| 5.10    | 18        | 7.47%   |
| 6.1     | 16        | 6.64%   |
| 6.5     | 15        | 6.22%   |
| 5.11    | 14        | 5.81%   |
| 5.19    | 13        | 5.39%   |
| 6.8     | 11        | 4.56%   |
| 6.2     | 11        | 4.56%   |
| 6.6     | 9         | 3.73%   |
| 5.0     | 9         | 3.73%   |
| 5.13    | 8         | 3.32%   |
| 5.3     | 7         | 2.9%    |
| 5.8     | 6         | 2.49%   |
| 6.4     | 5         | 2.07%   |
| 6.3     | 5         | 2.07%   |
| 4.15    | 5         | 2.07%   |
| 6.9     | 4         | 1.66%   |
| 6.11    | 4         | 1.66%   |
| 6.0     | 4         | 1.66%   |
| 5.16    | 4         | 1.66%   |
| 5.9     | 3         | 1.24%   |
| 5.18    | 3         | 1.24%   |
| 5.12    | 3         | 1.24%   |
| 4.19    | 3         | 1.24%   |
| 6.7     | 2         | 0.83%   |
| 6.12    | 2         | 0.83%   |
| 6.10    | 2         | 0.83%   |
| 5.14    | 2         | 0.83%   |
| 4.18    | 2         | 0.83%   |
| 5.7     | 1         | 0.41%   |
| 5.2     | 1         | 0.41%   |
| 5.17    | 1         | 0.41%   |
| 4.9     | 1         | 0.41%   |
| 4.1     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 191       | 98.96%  |
| i686   | 2         | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 95        | 47.26%  |
| KDE5       | 32        | 15.92%  |
| Unknown    | 17        | 8.46%   |
| XFCE       | 14        | 6.97%   |
| LXQt       | 8         | 3.98%   |
| X-Cinnamon | 7         | 3.48%   |
| MATE       | 7         | 3.48%   |
| KDE        | 4         | 1.99%   |
| KDE6       | 3         | 1.49%   |
| Unity      | 2         | 1%      |
| Pantheon   | 2         | 1%      |
| i3         | 2         | 1%      |
| Deepin     | 2         | 1%      |
| Budgie     | 2         | 1%      |
| onyx:GNOME | 1         | 0.5%    |
| LXDE       | 1         | 0.5%    |
| DDE        | 1         | 0.5%    |
| Cinnamon   | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 129       | 64.82%  |
| Wayland | 60        | 30.15%  |
| Unknown | 8         | 4.02%   |
| Tty     | 2         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 40%     |
| SDDM    | 44        | 22%     |
| GDM3    | 31        | 15.5%   |
| LightDM | 19        | 9.5%    |
| GDM     | 18        | 9%      |
| TDM     | 8         | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 92        | 46.7%   |
| es_CR   | 66        | 33.5%   |
| es_ES   | 14        | 7.11%   |
| Unknown | 14        | 7.11%   |
| es_MX   | 6         | 3.05%   |
| C       | 2         | 1.02%   |
| fr_FR   | 1         | 0.51%   |
| es_EC   | 1         | 0.51%   |
| en_AG   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 103       | 50.99%  |
| BIOS | 99        | 49.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 141       | 70.85%  |
| Btrfs   | 22        | 11.06%  |
| Overlay | 18        | 9.05%   |
| Tmpfs   | 12        | 6.03%   |
| Unknown | 4         | 2.01%   |
| Xfs     | 2         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 44.95%  |
| GPT     | 88        | 44.44%  |
| MBR     | 21        | 10.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 178       | 89.9%   |
| Yes       | 20        | 10.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 65.83%  |
| Yes       | 68        | 34.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 47        | 24.35%  |
| Dell                | 39        | 20.21%  |
| Lenovo              | 32        | 16.58%  |
| Toshiba             | 15        | 7.77%   |
| Acer                | 15        | 7.77%   |
| ASUSTek Computer    | 13        | 6.74%   |
| Apple               | 7         | 3.63%   |
| MSI                 | 4         | 2.07%   |
| Samsung Electronics | 3         | 1.55%   |
| Google              | 3         | 1.55%   |
| Unknown             | 3         | 1.55%   |
| Sony                | 2         | 1.04%   |
| Valve               | 1         | 0.52%   |
| TCL Communication   | 1         | 0.52%   |
| System76            | 1         | 0.52%   |
| Purism              | 1         | 0.52%   |
| Olivetti            | 1         | 0.52%   |
| HUAWEI              | 1         | 0.52%   |
| GPU Company         | 1         | 0.52%   |
| EVOO                | 1         | 0.52%   |
| Deffad              | 1         | 0.52%   |
| AZW                 | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 6         | 3.11%   |
| HP Notebook                                  | 4         | 2.07%   |
| Apple MacBookPro8,1                          | 4         | 2.07%   |
| HP Laptop 15-da0xxx                          | 3         | 1.55%   |
| Dell Inspiron 5584                           | 3         | 1.55%   |
| Toshiba Satellite L755                       | 2         | 1.04%   |
| HP ProBook 6460b                             | 2         | 1.04%   |
| HP Pavilion Notebook                         | 2         | 1.04%   |
| HP Pavilion g4                               | 2         | 1.04%   |
| HP Laptop 14-ck0xxx                          | 2         | 1.04%   |
| HP EliteBook 840 G6                          | 2         | 1.04%   |
| Dell Latitude E5470                          | 2         | 1.04%   |
| Valve Jupiter                                | 1         | 0.52%   |
| Toshiba Satellite X205                       | 1         | 0.52%   |
| Toshiba Satellite S55-A                      | 1         | 0.52%   |
| Toshiba Satellite L845                       | 1         | 0.52%   |
| Toshiba Satellite L655                       | 1         | 0.52%   |
| Toshiba Satellite L45-B                      | 1         | 0.52%   |
| Toshiba Satellite C855D                      | 1         | 0.52%   |
| Toshiba Satellite C845                       | 1         | 0.52%   |
| Toshiba Satellite C645D                      | 1         | 0.52%   |
| Toshiba Satellite C55-C                      | 1         | 0.52%   |
| Toshiba Satellite C55-B                      | 1         | 0.52%   |
| Toshiba Satellite C45-A                      | 1         | 0.52%   |
| Toshiba Satellite A305D                      | 1         | 0.52%   |
| Toshiba QOSMIO X775                          | 1         | 0.52%   |
| TCL Communication 8085                       | 1         | 0.52%   |
| System76 Lemur                               | 1         | 0.52%   |
| Sony SVE14123CLW                             | 1         | 0.52%   |
| Sony SVD13215PLB                             | 1         | 0.52%   |
| Samsung 930X2K/931X2K                        | 1         | 0.52%   |
| Samsung 700T1C                               | 1         | 0.52%   |
| Samsung 300E5K/300E5Q                        | 1         | 0.52%   |
| Purism Librem 15 v3                          | 1         | 0.52%   |
| Olivetti CL133A                              | 1         | 0.52%   |
| MSI Katana 15 B13VGK                         | 1         | 0.52%   |
| MSI GF75 Thin 9SD                            | 1         | 0.52%   |
| MSI GF65 Thin 10SDR                          | 1         | 0.52%   |
| MSI GE60 2OC\2OD\2OE                         | 1         | 0.52%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y50010US | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 22        | 11.4%   |
| Dell Latitude          | 16        | 8.29%   |
| Toshiba Satellite      | 14        | 7.25%   |
| Dell Inspiron          | 14        | 7.25%   |
| Acer Aspire            | 13        | 6.74%   |
| HP EliteBook           | 11        | 5.7%    |
| HP Pavilion            | 9         | 4.66%   |
| HP Laptop              | 9         | 4.66%   |
| Lenovo IdeaPad         | 8         | 4.15%   |
| HP ProBook             | 6         | 3.11%   |
| Unknown                | 6         | 3.11%   |
| HP Notebook            | 4         | 2.07%   |
| Dell XPS               | 4         | 2.07%   |
| ASUS VivoBook          | 4         | 2.07%   |
| Apple MacBookPro8      | 4         | 2.07%   |
| Dell G3                | 2         | 1.04%   |
| Valve Jupiter          | 1         | 0.52%   |
| Toshiba QOSMIO         | 1         | 0.52%   |
| TCL Communication 8085 | 1         | 0.52%   |
| System76 Lemur         | 1         | 0.52%   |
| Sony SVE14123CLW       | 1         | 0.52%   |
| Sony SVD13215PLB       | 1         | 0.52%   |
| Samsung 930X2K         | 1         | 0.52%   |
| Samsung 700T1C         | 1         | 0.52%   |
| Samsung 300E5K         | 1         | 0.52%   |
| Purism Librem          | 1         | 0.52%   |
| Olivetti CL133A        | 1         | 0.52%   |
| MSI Katana             | 1         | 0.52%   |
| MSI GF75               | 1         | 0.52%   |
| MSI GF65               | 1         | 0.52%   |
| MSI GE60               | 1         | 0.52%   |
| Lenovo Legion          | 1         | 0.52%   |
| Lenovo B590            | 1         | 0.52%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.52%   |
| HP OMEN                | 1         | 0.52%   |
| HP Mini                | 1         | 0.52%   |
| HP G60                 | 1         | 0.52%   |
| HP ENVY                | 1         | 0.52%   |
| HP 245                 | 1         | 0.52%   |
| HP 240                 | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 23        | 11.92%  |
| 2011 | 19        | 9.84%   |
| 2020 | 17        | 8.81%   |
| 2018 | 17        | 8.81%   |
| 2012 | 16        | 8.29%   |
| 2016 | 14        | 7.25%   |
| 2014 | 12        | 6.22%   |
| 2021 | 11        | 5.7%    |
| 2015 | 11        | 5.7%    |
| 2017 | 10        | 5.18%   |
| 2013 | 9         | 4.66%   |
| 2023 | 6         | 3.11%   |
| 2010 | 6         | 3.11%   |
| 2022 | 5         | 2.59%   |
| 2009 | 5         | 2.59%   |
| 2008 | 5         | 2.59%   |
| 2007 | 3         | 1.55%   |
| 2006 | 3         | 1.55%   |
| 2024 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 193       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 179       | 91.79%  |
| Enabled  | 16        | 8.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 189       | 97.93%  |
| Yes  | 4         | 2.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 55        | 27.78%  |
| 8.01-16.0   | 43        | 21.72%  |
| 3.01-4.0    | 40        | 20.2%   |
| 16.01-24.0  | 28        | 14.14%  |
| 32.01-64.0  | 15        | 7.58%   |
| 1.01-2.0    | 5         | 2.53%   |
| 24.01-32.0  | 4         | 2.02%   |
| 2.01-3.0    | 4         | 2.02%   |
| 64.01-256.0 | 3         | 1.52%   |
| 0.51-1.0    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 85        | 39.53%  |
| 2.01-3.0   | 52        | 24.19%  |
| 4.01-8.0   | 33        | 15.35%  |
| 3.01-4.0   | 26        | 12.09%  |
| 8.01-16.0  | 9         | 4.19%   |
| 0.51-1.0   | 7         | 3.26%   |
| 16.01-24.0 | 3         | 1.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 145       | 74.74%  |
| 2      | 46        | 23.71%  |
| 3      | 3         | 1.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 59.28%  |
| Yes       | 79        | 40.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 81.35%  |
| No        | 36        | 18.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 97.41%  |
| No        | 5         | 2.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 75.9%   |
| No        | 47        | 24.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Costa Rica | 193       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San José     | 96        | 44.44%  |
| Heredia       | 30        | 13.89%  |
| Alajuela      | 14        | 6.48%   |
| Cartago       | 7         | 3.24%   |
| Grecia        | 6         | 2.78%   |
| Quesada       | 5         | 2.31%   |
| Escazu        | 5         | 2.31%   |
| Rio Segundo   | 4         | 1.85%   |
| Puntarenas    | 4         | 1.85%   |
| Santa Cruz    | 3         | 1.39%   |
| San Ramon     | 3         | 1.39%   |
| Perez Zeledon | 3         | 1.39%   |
| Pavas         | 3         | 1.39%   |
| Esparza       | 3         | 1.39%   |
| Siquirres     | 2         | 0.93%   |
| Santa Fe      | 2         | 0.93%   |
| San Pedro     | 2         | 0.93%   |
| Naranjo       | 2         | 0.93%   |
| Colon         | 2         | 0.93%   |
| Bagaces       | 2         | 0.93%   |
| Zarcero       | 1         | 0.46%   |
| Tres Rios     | 1         | 0.46%   |
| Santo Domingo | 1         | 0.46%   |
| Santiago      | 1         | 0.46%   |
| San Rafael    | 1         | 0.46%   |
| San Pablo     | 1         | 0.46%   |
| San Juan      | 1         | 0.46%   |
| San Francisco | 1         | 0.46%   |
| San Felipe    | 1         | 0.46%   |
| Quepos        | 1         | 0.46%   |
| Palmares      | 1         | 0.46%   |
| Nosara        | 1         | 0.46%   |
| Mercedes      | 1         | 0.46%   |
| Liberia       | 1         | 0.46%   |
| Guapiles      | 1         | 0.46%   |
| Guacima       | 1         | 0.46%   |
| Curridabat    | 1         | 0.46%   |
| Alpes         | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 29        | 45     | 12.34%  |
| Samsung Electronics         | 28        | 39     | 11.91%  |
| Toshiba                     | 25        | 30     | 10.64%  |
| Seagate                     | 25        | 34     | 10.64%  |
| Unknown                     | 15        | 20     | 6.38%   |
| Kingston                    | 14        | 19     | 5.96%   |
| Intel                       | 13        | 40     | 5.53%   |
| HGST                        | 9         | 10     | 3.83%   |
| A-DATA Technology           | 9         | 9      | 3.83%   |
| Patriot                     | 8         | 8      | 3.4%    |
| SK hynix                    | 7         | 14     | 2.98%   |
| SanDisk                     | 7         | 7      | 2.98%   |
| Micron Technology           | 5         | 6      | 2.13%   |
| Crucial                     | 5         | 5      | 2.13%   |
| Team                        | 4         | 4      | 1.7%    |
| KIOXIA                      | 4         | 6      | 1.7%    |
| Netac                       | 3         | 4      | 1.28%   |
| LITEON                      | 3         | 3      | 1.28%   |
| Kingston Technology Company | 3         | 6      | 1.28%   |
| JMicron Technology          | 2         | 2      | 0.85%   |
| Hitachi                     | 2         | 3      | 0.85%   |
| Zheino                      | 1         | 1      | 0.43%   |
| Wibtek                      | 1         | 1      | 0.43%   |
| UMIS                        | 1         | 1      | 0.43%   |
| Transcend                   | 1         | 1      | 0.43%   |
| Silicon Motion              | 1         | 1      | 0.43%   |
| ShiJi                       | 1         | 1      | 0.43%   |
| O2 Micro                    | 1         | 1      | 0.43%   |
| Mushkin                     | 1         | 1      | 0.43%   |
| LITEONIT                    | 1         | 1      | 0.43%   |
| Gigabyte Technology         | 1         | 1      | 0.43%   |
| Fujitsu                     | 1         | 1      | 0.43%   |
| Dell                        | 1         | 1      | 0.43%   |
| BP4                         | 1         | 1      | 0.43%   |
| ASMedia                     | 1         | 1      | 0.43%   |
| Unknown                     | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 7         | 2.81%   |
| Toshiba MQ01ABF050 500GB                            | 6         | 2.41%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 2.41%   |
| Unknown MMC Card  32GB                              | 4         | 1.61%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 1.2%    |
| Unknown MMC Card  128GB                             | 3         | 1.2%    |
| Toshiba KBG30ZMS256G NVMe 256GB                     | 3         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.2%    |
| Intel SSDSC2MH250A2 250GB                           | 3         | 1.2%    |
| Intel SSDSC2BF180A4H 180GB                          | 3         | 1.2%    |
| Intel SSDSA2CW300G3 304GB                           | 3         | 1.2%    |
| HGST HTS541010A9E680 1TB                            | 3         | 1.2%    |
| WDC WD20SPZX-08UA7 2TB                              | 2         | 0.8%    |
| Toshiba NVMe SSD Drive 256GB                        | 2         | 0.8%    |
| SK hynix NVMe SSD Drive 128GB                       | 2         | 0.8%    |
| Seagate ST9500325AS 500GB                           | 2         | 0.8%    |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 0.8%    |
| Samsung MZVLQ256HAJD-000H1 256GB                    | 2         | 0.8%    |
| Patriot P210 256GB SSD                              | 2         | 0.8%    |
| Patriot P210 1024GB SSD                             | 2         | 0.8%    |
| Netac SSD 120GB                                     | 2         | 0.8%    |
| LITEON LCH-256V2S 256GB SSD                         | 2         | 0.8%    |
| Kingston Company SNV2S1000G 1TB                     | 2         | 0.8%    |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.8%    |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.8%    |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.8%    |
| JMicron Generic 500GB                               | 2         | 0.8%    |
| Intel HBRPEKNX0101AHO 16GB                          | 2         | 0.8%    |
| Intel HBRPEKNX0101AH 256GB                          | 2         | 0.8%    |
| HGST HTS541075A9E680 752GB                          | 2         | 0.8%    |
| Zheino CHN 25SATAA3 240 240GB                       | 1         | 0.4%    |
| Wibtek W800S 512GB SSD                              | 1         | 0.4%    |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.4%    |
| WDC WDS120G1G0B-00RC30 120GB SSD                    | 1         | 0.4%    |
| WDC WD800BEVT-75ZCT2 80GB                           | 1         | 0.4%    |
| WDC WD7500BPVT-22HXZT3 752GB                        | 1         | 0.4%    |
| WDC WD5000LPVX-80V0TT0 500GB                        | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 23        | 32     | 29.11%  |
| Toshiba            | 21        | 22     | 26.58%  |
| WDC                | 20        | 24     | 25.32%  |
| HGST               | 9         | 10     | 11.39%  |
| JMicron Technology | 2         | 2      | 2.53%   |
| Hitachi            | 2         | 3      | 2.53%   |
| Fujitsu            | 1         | 1      | 1.27%   |
| ASMedia            | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 14     | 16.05%  |
| Samsung Electronics | 10        | 20     | 12.35%  |
| Intel               | 8         | 28     | 9.88%   |
| A-DATA Technology   | 8         | 8      | 9.88%   |
| WDC                 | 7         | 16     | 8.64%   |
| Patriot             | 7         | 7      | 8.64%   |
| Micron Technology   | 4         | 4      | 4.94%   |
| Crucial             | 4         | 4      | 4.94%   |
| Team                | 3         | 3      | 3.7%    |
| SanDisk             | 3         | 3      | 3.7%    |
| Netac               | 3         | 4      | 3.7%    |
| LITEON              | 3         | 3      | 3.7%    |
| Wibtek              | 1         | 1      | 1.23%   |
| Transcend           | 1         | 1      | 1.23%   |
| ShiJi               | 1         | 1      | 1.23%   |
| Seagate             | 1         | 1      | 1.23%   |
| Mushkin             | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 1      | 1.23%   |
| BP4                 | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 78        | 122    | 34.06%  |
| HDD     | 78        | 95     | 34.06%  |
| NVMe    | 55        | 89     | 24.02%  |
| MMC     | 15        | 20     | 6.55%   |
| Unknown | 3         | 3      | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 144       | 213    | 65.16%  |
| NVMe | 54        | 88     | 24.43%  |
| MMC  | 15        | 20     | 6.79%   |
| SAS  | 8         | 8      | 3.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 135    | 62.34%  |
| 0.51-1.0   | 49        | 72     | 31.82%  |
| 1.01-2.0   | 8         | 9      | 5.19%   |
| 2.01-3.0   | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 30.1%   |
| 251-500        | 40        | 19.42%  |
| 501-1000       | 37        | 17.96%  |
| 1-20           | 16        | 7.77%   |
| 1001-2000      | 14        | 6.8%    |
| 21-50          | 13        | 6.31%   |
| 51-100         | 12        | 5.83%   |
| More than 3000 | 5         | 2.43%   |
| 2001-3000      | 4         | 1.94%   |
| Unknown        | 3         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 90        | 41.67%  |
| 21-50     | 39        | 18.06%  |
| 101-250   | 29        | 13.43%  |
| 51-100    | 24        | 11.11%  |
| 251-500   | 19        | 8.8%    |
| 501-1000  | 10        | 4.63%   |
| Unknown   | 3         | 1.39%   |
| 1001-2000 | 2         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 5.88%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.88%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 5.88%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 5.88%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 5.88%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 5.88%   |
| Netac SSD 120GB                                     | 1         | 2      | 5.88%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 5.88%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 5.88%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 5.88%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 5.88%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 5         | 5      | 29.41%  |
| Seagate           | 4         | 4      | 23.53%  |
| WDC               | 2         | 2      | 11.76%  |
| HGST              | 2         | 2      | 11.76%  |
| Netac             | 1         | 2      | 5.88%   |
| Micron Technology | 1         | 1      | 5.88%   |
| Intel             | 1         | 1      | 5.88%   |
| Hitachi           | 1         | 2      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 35.71%  |
| Seagate | 4         | 4      | 28.57%  |
| WDC     | 2         | 2      | 14.29%  |
| HGST    | 2         | 2      | 14.29%  |
| Hitachi | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 82.35%  |
| SSD  | 3         | 4      | 17.65%  |

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
| Detected | 111       | 178    | 54.68%  |
| Works    | 75        | 132    | 36.95%  |
| Malfunc  | 17        | 19     | 8.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 140       | 63.35%  |
| AMD                          | 23        | 10.41%  |
| Samsung Electronics          | 18        | 8.14%   |
| SanDisk                      | 7         | 3.17%   |
| SK hynix                     | 6         | 2.71%   |
| Toshiba America Info Systems | 5         | 2.26%   |
| Kingston Technology Company  | 4         | 1.81%   |
| KIOXIA                       | 3         | 1.36%   |
| Nvidia                       | 2         | 0.9%    |
| Micron Technology            | 2         | 0.9%    |
| ASMedia Technology           | 2         | 0.9%    |
| Union Memory (Shenzhen)      | 1         | 0.45%   |
| Solidigm                     | 1         | 0.45%   |
| Silicon Motion               | 1         | 0.45%   |
| Realtek Semiconductor        | 1         | 0.45%   |
| Phison Electronics           | 1         | 0.45%   |
| O2 Micro                     | 1         | 0.45%   |
| Micron/Crucial Technology    | 1         | 0.45%   |
| Hosin Global Electronics     | 1         | 0.45%   |
| ADATA Technology             | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 20        | 8.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 16        | 6.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 16        | 6.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 16        | 6.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 5.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 3.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 7         | 2.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 2.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 2.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 5         | 2.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 1.67%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 3         | 1.26%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 3         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.84%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 2         | 0.84%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 2         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 0.84%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                   | 2         | 0.84%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 0.84%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 2         | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.84%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                     | 2         | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 0.84%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                          | 2         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 135       | 59.47%  |
| NVMe | 55        | 24.23%  |
| RAID | 21        | 9.25%   |
| IDE  | 16        | 7.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 162       | 83.94%  |
| AMD    | 31        | 16.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz               | 6         | 3.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 2.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 4         | 2.07%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 4         | 2.07%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 4         | 2.07%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 4         | 2.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.55%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.55%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 3         | 1.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 3         | 1.55%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3         | 1.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 1.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.04%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.04%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.04%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 2         | 1.04%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 2         | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.04%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.04%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 2         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.04%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.04%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 2         | 1.04%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 1.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 1.04%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 2         | 1.04%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 1.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 2         | 1.04%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.04%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.52%   |
| Intel Pentium Silver N6000 @ 1.10GHz            | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.52%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz               | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 44        | 22.8%   |
| Intel Core i5                  | 41        | 21.24%  |
| Intel Core i3                  | 22        | 11.4%   |
| Other                          | 18        | 9.33%   |
| Intel Celeron                  | 18        | 9.33%   |
| AMD Ryzen 7                    | 8         | 4.15%   |
| Intel Core 2 Duo               | 5         | 2.59%   |
| AMD Ryzen 5                    | 5         | 2.59%   |
| Intel Atom                     | 4         | 2.07%   |
| Intel Pentium                  | 3         | 1.55%   |
| Intel Core 2                   | 3         | 1.55%   |
| AMD A10                        | 3         | 1.55%   |
| Intel Genuine                  | 2         | 1.04%   |
| AMD Ryzen 3                    | 2         | 1.04%   |
| AMD E1                         | 2         | 1.04%   |
| AMD A8                         | 2         | 1.04%   |
| Intel Xeon                     | 1         | 0.52%   |
| Intel Pentium Silver           | 1         | 0.52%   |
| Intel Pentium Dual-Core        | 1         | 0.52%   |
| Intel Core M                   | 1         | 0.52%   |
| AMD V120                       | 1         | 0.52%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.52%   |
| AMD Turion 64 X2               | 1         | 0.52%   |
| AMD Ryzen 5 PRO                | 1         | 0.52%   |
| AMD PRO A10                    | 1         | 0.52%   |
| AMD E                          | 1         | 0.52%   |
| AMD Athlon                     | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 114       | 59.07%  |
| 4      | 50        | 25.91%  |
| 6      | 12        | 6.22%   |
| 8      | 9         | 4.66%   |
| 12     | 2         | 1.04%   |
| 1      | 2         | 1.04%   |
| 24     | 1         | 0.52%   |
| 16     | 1         | 0.52%   |
| 14     | 1         | 0.52%   |
| 10     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 193       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 141       | 73.06%  |
| 1      | 52        | 26.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 190       | 97.94%  |
| 32-bit         | 2         | 1.03%   |
| Unknown        | 2         | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 39.11%  |
| 0x206a7    | 14        | 6.93%   |
| 0x40651    | 7         | 3.47%   |
| 0x306d4    | 7         | 3.47%   |
| 0x406e3    | 6         | 2.97%   |
| 0x406c4    | 6         | 2.97%   |
| 0x306a9    | 6         | 2.97%   |
| 0x08108109 | 6         | 2.97%   |
| 0x806ec    | 5         | 2.48%   |
| 0x806e9    | 5         | 2.48%   |
| 0x906ea    | 4         | 1.98%   |
| 0x706a1    | 4         | 1.98%   |
| 0x306c3    | 4         | 1.98%   |
| 0x1067a    | 4         | 1.98%   |
| 0x806eb    | 3         | 1.49%   |
| 0x806ea    | 3         | 1.49%   |
| 0x806c1    | 3         | 1.49%   |
| 0x20655    | 3         | 1.49%   |
| 0x6fd      | 2         | 0.99%   |
| 0x506e3    | 2         | 0.99%   |
| 0x0a50000d | 2         | 0.99%   |
| 0x05000119 | 2         | 0.99%   |
| 0xb06a2    | 1         | 0.5%    |
| 0xa0652    | 1         | 0.5%    |
| 0x906ed    | 1         | 0.5%    |
| 0x906e9    | 1         | 0.5%    |
| 0x706a8    | 1         | 0.5%    |
| 0x6f6      | 1         | 0.5%    |
| 0x6ec      | 1         | 0.5%    |
| 0x506c9    | 1         | 0.5%    |
| 0x30678    | 1         | 0.5%    |
| 0x106c2    | 1         | 0.5%    |
| 0x0a50000f | 1         | 0.5%    |
| 0x08a00008 | 1         | 0.5%    |
| 0x08a00006 | 1         | 0.5%    |
| 0x08608102 | 1         | 0.5%    |
| 0x08600106 | 1         | 0.5%    |
| 0x08600104 | 1         | 0.5%    |
| 0x08600103 | 1         | 0.5%    |
| 0x07030105 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 17.01%  |
| SandyBridge      | 23        | 11.86%  |
| Haswell          | 13        | 6.7%    |
| IvyBridge        | 12        | 6.19%   |
| Skylake          | 11        | 5.67%   |
| Silvermont       | 10        | 5.15%   |
| Broadwell        | 10        | 5.15%   |
| Unknown          | 10        | 5.15%   |
| Zen+             | 7         | 3.61%   |
| TigerLake        | 7         | 3.61%   |
| Goldmont plus    | 7         | 3.61%   |
| Westmere         | 6         | 3.09%   |
| Penryn           | 5         | 2.58%   |
| IceLake          | 5         | 2.58%   |
| Core             | 5         | 2.58%   |
| Zen 2            | 4         | 2.06%   |
| Excavator        | 4         | 2.06%   |
| Alderlake Hybrid | 4         | 2.06%   |
| Zen 3            | 3         | 1.55%   |
| Goldmont         | 2         | 1.03%   |
| Bobcat           | 2         | 1.03%   |
| Tremont          | 1         | 0.52%   |
| Puma             | 1         | 0.52%   |
| Piledriver       | 1         | 0.52%   |
| P6               | 1         | 0.52%   |
| K8 Hammer        | 1         | 0.52%   |
| K8 & K10 hybrid  | 1         | 0.52%   |
| K10 Llano        | 1         | 0.52%   |
| K10              | 1         | 0.52%   |
| Jaguar           | 1         | 0.52%   |
| CometLake        | 1         | 0.52%   |
| Bonnell          | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 154       | 67.25%  |
| Nvidia | 38        | 16.59%  |
| AMD    | 37        | 16.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 7.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 3.77%   |
| Intel HD Graphics 620                                                                    | 8         | 3.35%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.51%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.09%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.67%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.26%   |
| Intel HD Graphics 530                                                                    | 3         | 1.26%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.26%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.26%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.84%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.84%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 2         | 0.84%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.84%   |
| Intel HD Graphics 500                                                                    | 2         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.84%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.84%   |
| AMD Lucienne                                                                             | 2         | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.84%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.42%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 120       | 62.18%  |
| Intel + Nvidia | 30        | 15.54%  |
| 1 x AMD        | 27        | 13.99%  |
| 1 x Nvidia     | 5         | 2.59%   |
| 2 x AMD        | 4         | 2.07%   |
| Intel + AMD    | 3         | 1.55%   |
| AMD + Nvidia   | 3         | 1.55%   |
| Other          | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 171       | 88.14%  |
| Proprietary | 19        | 9.79%   |
| Unknown     | 4         | 2.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 148       | 75.51%  |
| 1.01-2.0   | 15        | 7.65%   |
| 0.01-0.5   | 15        | 7.65%   |
| 3.01-4.0   | 8         | 4.08%   |
| 0.51-1.0   | 8         | 4.08%   |
| 5.01-6.0   | 2         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 47        | 20.17%  |
| LG Display              | 42        | 18.03%  |
| BOE                     | 29        | 12.45%  |
| Chimei Innolux          | 23        | 9.87%   |
| Samsung Electronics     | 22        | 9.44%   |
| Goldstar                | 8         | 3.43%   |
| Dell                    | 8         | 3.43%   |
| Apple                   | 7         | 3%      |
| AOC                     | 7         | 3%      |
| Chi Mei Optoelectronics | 4         | 1.72%   |
| PANDA                   | 3         | 1.29%   |
| Acer                    | 3         | 1.29%   |
| Sony                    | 2         | 0.86%   |
| Sharp                   | 2         | 0.86%   |
| Lenovo                  | 2         | 0.86%   |
| Hewlett-Packard         | 2         | 0.86%   |
| CPT                     | 2         | 0.86%   |
| ASUSTek Computer        | 2         | 0.86%   |
| ViewSonic               | 1         | 0.43%   |
| Valve                   | 1         | 0.43%   |
| Sun                     | 1         | 0.43%   |
| RTK                     | 1         | 0.43%   |
| PRISM+                  | 1         | 0.43%   |
| Panasonic               | 1         | 0.43%   |
| Mi                      | 1         | 0.43%   |
| LG Philips              | 1         | 0.43%   |
| LED                     | 1         | 0.43%   |
| KDC                     | 1         | 0.43%   |
| InnoLux Display         | 1         | 0.43%   |
| InfoVision              | 1         | 0.43%   |
| Hitachi                 | 1         | 0.43%   |
| GAOMON                  | 1         | 0.43%   |
| Envision                | 1         | 0.43%   |
| CVT                     | 1         | 0.43%   |
| Ancor Communications    | 1         | 0.43%   |
| AGO                     | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 5         | 2.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 1.28%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.28%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.85%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch         | 2         | 0.85%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.85%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 2         | 0.85%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.85%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.85%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.85%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.43%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.43%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch               | 1         | 0.43%   |
| Sony TV SNY1B02 1360x768                                             | 1         | 0.43%   |
| Sony TV SNY0902 1920x1080                                            | 1         | 0.43%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.43%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch | 1         | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 82        | 37.44%  |
| 1920x1080 (FHD)    | 76        | 34.7%   |
| 3840x2160 (4K)     | 12        | 5.48%   |
| 1600x900 (HD+)     | 11        | 5.02%   |
| 1280x800 (WXGA)    | 11        | 5.02%   |
| 1920x1200 (WUXGA)  | 5         | 2.28%   |
| 2560x1440 (QHD)    | 4         | 1.83%   |
| 1440x900 (WXGA+)   | 4         | 1.83%   |
| 1280x1024 (SXGA)   | 4         | 1.83%   |
| 1360x768           | 2         | 0.91%   |
| 800x1280           | 1         | 0.46%   |
| 3840x2400          | 1         | 0.46%   |
| 3200x2000          | 1         | 0.46%   |
| 2880x1800          | 1         | 0.46%   |
| 2560x1600          | 1         | 0.46%   |
| 1680x1050 (WSXGA+) | 1         | 0.46%   |
| 1400x1050          | 1         | 0.46%   |
| 1024x576           | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 87        | 37.34%  |
| 14     | 41        | 17.6%   |
| 13     | 34        | 14.59%  |
| 17     | 9         | 3.86%   |
| 21     | 8         | 3.43%   |
| 23     | 7         | 3%      |
| 31     | 6         | 2.58%   |
| 24     | 5         | 2.15%   |
| 19     | 5         | 2.15%   |
| 11     | 5         | 2.15%   |
| 18     | 4         | 1.72%   |
| 12     | 4         | 1.72%   |
| 84     | 3         | 1.29%   |
| 27     | 3         | 1.29%   |
| 16     | 3         | 1.29%   |
| 72     | 2         | 0.86%   |
| 57     | 2         | 0.86%   |
| 39     | 1         | 0.43%   |
| 32     | 1         | 0.43%   |
| 20     | 1         | 0.43%   |
| 10     | 1         | 0.43%   |
| 7      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 155       | 67.1%   |
| 201-300     | 20        | 8.66%   |
| 401-500     | 16        | 6.93%   |
| 501-600     | 15        | 6.49%   |
| 351-400     | 9         | 3.9%    |
| 601-700     | 6         | 2.6%    |
| 1501-2000   | 5         | 2.16%   |
| 701-800     | 2         | 0.87%   |
| 801-900     | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |
| 1-100       | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 167       | 83.08%  |
| 16/10 | 26        | 12.94%  |
| 5/4   | 4         | 1.99%   |
| 4/3   | 2         | 1%      |
| 0.67  | 1         | 0.5%    |
| 0.56  | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 37.5%   |
| 81-90          | 71        | 30.6%   |
| 201-250        | 15        | 6.47%   |
| 151-200        | 10        | 4.31%   |
| More than 1000 | 7         | 3.02%   |
| 351-500        | 7         | 3.02%   |
| 121-130        | 6         | 2.59%   |
| 51-60          | 5         | 2.16%   |
| 141-150        | 5         | 2.16%   |
| 71-80          | 4         | 1.72%   |
| 61-70          | 3         | 1.29%   |
| 301-350        | 3         | 1.29%   |
| 111-120        | 3         | 1.29%   |
| 41-50          | 1         | 0.43%   |
| 1-40           | 1         | 0.43%   |
| 251-300        | 1         | 0.43%   |
| 131-140        | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |
| 91-100         | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 96        | 42.29%  |
| 121-160       | 77        | 33.92%  |
| 51-100        | 35        | 15.42%  |
| 161-240       | 8         | 3.52%   |
| More than 240 | 6         | 2.64%   |
| 1-50          | 5         | 2.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 154       | 75.86%  |
| 2     | 41        | 20.2%   |
| 3     | 5         | 2.46%   |
| 0     | 3         | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 33.76%  |
| Intel                    | 89        | 28.62%  |
| Qualcomm Atheros         | 49        | 15.76%  |
| Broadcom                 | 28        | 9%      |
| Broadcom Limited         | 8         | 2.57%   |
| TP-Link                  | 6         | 1.93%   |
| MediaTek                 | 6         | 1.93%   |
| ASIX Electronics         | 4         | 1.29%   |
| Nvidia                   | 2         | 0.64%   |
| Marvell Technology Group | 2         | 0.64%   |
| Xiaomi                   | 1         | 0.32%   |
| Qualcomm                 | 1         | 0.32%   |
| Lenovo                   | 1         | 0.32%   |
| JMicron Technology       | 1         | 0.32%   |
| Huawei Technologies      | 1         | 0.32%   |
| Hewlett-Packard          | 1         | 0.32%   |
| DisplayLink              | 1         | 0.32%   |
| Dell                     | 1         | 0.32%   |
| D-Link System            | 1         | 0.32%   |
| D-Link                   | 1         | 0.32%   |
| Aquantia                 | 1         | 0.32%   |
| Apple                    | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 13.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 7.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 3.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 3.15%   |
| Intel Wireless 7265                                                    | 10        | 2.62%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 8         | 2.1%    |
| Intel Wireless 7260                                                    | 8         | 2.1%    |
| Intel Wi-Fi 6 AX200                                                    | 8         | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 1.31%   |
| Intel Wireless 8260                                                    | 5         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 1.31%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 1.31%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 5         | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.05%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.05%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 3         | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.79%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.79%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                              | 2         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.52%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 79        | 40.1%   |
| Qualcomm Atheros      | 38        | 19.29%  |
| Realtek Semiconductor | 36        | 18.27%  |
| Broadcom              | 23        | 11.68%  |
| Broadcom Limited      | 7         | 3.55%   |
| TP-Link               | 6         | 3.05%   |
| MediaTek              | 4         | 2.03%   |
| Qualcomm              | 1         | 0.51%   |
| Dell                  | 1         | 0.51%   |
| D-Link System         | 1         | 0.51%   |
| D-Link                | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 6%      |
| Intel Wireless 7265                                            | 10        | 5%      |
| Realtek RTL8723DE Wireless Network Adapter                     | 8         | 4%      |
| Intel Wireless 7260                                            | 8         | 4%      |
| Intel Wi-Fi 6 AX200                                            | 8         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 4%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 3%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 3%      |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.5%    |
| Intel Wireless 8260                                            | 5         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2%      |
| Intel Wi-Fi 6 AX201                                            | 4         | 2%      |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 2%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.5%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 2         | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1%      |
| Realtek 802.11ac NIC                                           | 2         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1%      |
| Intel Wireless 8265 / 8275                                     | 2         | 1%      |
| Intel Wireless 3160                                            | 2         | 1%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1%      |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1%      |
| Intel Centrino Advanced-N 6200                                 | 2         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1%      |
| Broadcom Limited BCM4311 802.11a/b/g                           | 2         | 1%      |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 90        | 52.33%  |
| Intel                    | 38        | 22.09%  |
| Qualcomm Atheros         | 14        | 8.14%   |
| Broadcom                 | 12        | 6.98%   |
| ASIX Electronics         | 4         | 2.33%   |
| Nvidia                   | 2         | 1.16%   |
| MediaTek                 | 2         | 1.16%   |
| Marvell Technology Group | 2         | 1.16%   |
| Xiaomi                   | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| Huawei Technologies      | 1         | 0.58%   |
| DisplayLink              | 1         | 0.58%   |
| Broadcom Limited         | 1         | 0.58%   |
| Aquantia                 | 1         | 0.58%   |
| Apple                    | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 28.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 16.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 2.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 2.78%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 1.67%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.11%   |
| Intel 82599 10 Gigabit Network Connection                              | 2         | 1.11%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.11%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 2         | 1.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.56%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.56%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.56%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.56%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.56%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                       | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 0.56%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 188       | 54.34%  |
| Ethernet | 157       | 45.38%  |
| Modem    | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 75.12%  |
| Ethernet | 50        | 24.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 144       | 74.23%  |
| 1     | 40        | 20.62%  |
| 3     | 5         | 2.58%   |
| 0     | 5         | 2.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 184       | 93.4%   |
| Yes  | 13        | 6.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 40.94%  |
| Realtek Semiconductor           | 22        | 14.77%  |
| Qualcomm Atheros Communications | 18        | 12.08%  |
| Broadcom                        | 11        | 7.38%   |
| Lite-On Technology              | 7         | 4.7%    |
| Apple                           | 7         | 4.7%    |
| Foxconn / Hon Hai               | 6         | 4.03%   |
| IMC Networks                    | 5         | 3.36%   |
| Hewlett-Packard                 | 4         | 2.68%   |
| Toshiba                         | 3         | 2.01%   |
| Dell                            | 2         | 1.34%   |
| Cambridge Silicon Radio         | 2         | 1.34%   |
| Realtek                         | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 16.78%  |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 7.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 6.71%   |
| Realtek Bluetooth Radio                             | 10        | 6.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 6.71%   |
| Intel AX200 Bluetooth                               | 8         | 5.37%   |
| Intel AX201 Bluetooth                               | 7         | 4.7%    |
| Apple Bluetooth Host Controller                     | 5         | 3.36%   |
| Intel AX211 Bluetooth                               | 4         | 2.68%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 2.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.01%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.01%   |
| Broadcom HP Portable SoftSailing                    | 3         | 2.01%   |
| Toshiba Bluetooth Device                            | 2         | 1.34%   |
| Lite-On Wireless_Device                             | 2         | 1.34%   |
| Lite-On Bluetooth Device                            | 2         | 1.34%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.34%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.34%   |
| Intel AX210 Bluetooth                               | 2         | 1.34%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.34%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.34%   |
| Toshiba BCM43142A0                                  | 1         | 0.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.67%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.67%   |
| Realtek Bluetooth Radio                             | 1         | 0.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.67%   |
| IMC Networks Wireless_Device                        | 1         | 0.67%   |
| IMC Networks Bluetooth                              | 1         | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.67%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 159       | 65.98%  |
| AMD                    | 35        | 14.52%  |
| Nvidia                 | 22        | 9.13%   |
| GN Netcom              | 3         | 1.24%   |
| Generalplus Technology | 3         | 1.24%   |
| Realtek Semiconductor  | 2         | 0.83%   |
| Plantronics            | 2         | 0.83%   |
| Logitech               | 2         | 0.83%   |
| Lenovo                 | 2         | 0.83%   |
| KTMicro                | 2         | 0.83%   |
| JMTek                  | 2         | 0.83%   |
| C-Media Electronics    | 2         | 0.83%   |
| Unknown                | 1         | 0.41%   |
| Sony                   | 1         | 0.41%   |
| Hewlett-Packard        | 1         | 0.41%   |
| CMX Systems            | 1         | 0.41%   |
| Afatech                | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 6.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 6.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 5.92%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 17        | 5.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.48%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.79%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.74%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.05%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.05%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.05%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.7%    |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.7%    |
| KTMicro KT_USB_AUDIO                                                                              | 2         | 0.7%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.7%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 30.83%  |
| SK hynix            | 26        | 19.55%  |
| Kingston            | 14        | 10.53%  |
| Micron Technology   | 12        | 9.02%   |
| Crucial             | 9         | 6.77%   |
| Nanya Technology    | 5         | 3.76%   |
| Unknown             | 4         | 3.01%   |
| Team                | 4         | 3.01%   |
| Corsair             | 4         | 3.01%   |
| A-DATA Technology   | 4         | 3.01%   |
| Ramaxel Technology  | 3         | 2.26%   |
| Unknown (ABCD)      | 2         | 1.5%    |
| Transcend           | 1         | 0.75%   |
| Super Talent        | 1         | 0.75%   |
| Patriot             | 1         | 0.75%   |
| G.Skill             | 1         | 0.75%   |
| fef5                | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 3.31%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 4         | 2.65%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 4         | 2.65%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.65%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 1.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.66%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.66%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 0.66%   |
| Super Talent RAM SUPERTALENT02 2GB SODIMM DDR2 1600MT/s          | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.66%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.66%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.66%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.66%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.66%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 50        | 45.05%  |
| DDR3    | 41        | 36.94%  |
| LPDDR4  | 5         | 4.5%    |
| SDRAM   | 4         | 3.6%    |
| DDR2    | 4         | 3.6%    |
| DDR5    | 3         | 2.7%    |
| LPDDR5  | 2         | 1.8%    |
| LPDDR3  | 1         | 0.9%    |
| Unknown | 1         | 0.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 91.74%  |
| Row Of Chips | 7         | 6.42%   |
| Chip         | 1         | 0.92%   |
| Unknown      | 1         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 50        | 38.17%  |
| 4096  | 47        | 35.88%  |
| 16384 | 14        | 10.69%  |
| 2048  | 10        | 7.63%   |
| 32768 | 8         | 6.11%   |
| 1024  | 2         | 1.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 30        | 23.44%  |
| 1600    | 30        | 23.44%  |
| 3200    | 16        | 12.5%   |
| 2400    | 8         | 6.25%   |
| 1334    | 8         | 6.25%   |
| 1333    | 7         | 5.47%   |
| 3266    | 5         | 3.91%   |
| 2133    | 4         | 3.13%   |
| 667     | 3         | 2.34%   |
| Unknown | 3         | 2.34%   |
| 6400    | 2         | 1.56%   |
| 4800    | 2         | 1.56%   |
| 4199    | 2         | 1.56%   |
| 1067    | 2         | 1.56%   |
| 8400    | 1         | 0.78%   |
| 5600    | 1         | 0.78%   |
| 4267    | 1         | 0.78%   |
| 2933    | 1         | 0.78%   |
| 2048    | 1         | 0.78%   |
| 800     | 1         | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L382 Series | 1         | 50%     |
| Seiko Epson L360 Series | 1         | 50%     |

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
| Chicony Electronics                    | 37        | 21.76%  |
| Microdia                               | 20        | 11.76%  |
| Sunplus Innovation Technology          | 15        | 8.82%   |
| Realtek Semiconductor                  | 15        | 8.82%   |
| IMC Networks                           | 15        | 8.82%   |
| Quanta                                 | 7         | 4.12%   |
| Lite-On Technology                     | 7         | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.12%   |
| Apple                                  | 7         | 4.12%   |
| Bison Electronics                      | 5         | 2.94%   |
| Primax Electronics                     | 4         | 2.35%   |
| Luxvisions Innotech Limited            | 4         | 2.35%   |
| Alcor Micro                            | 4         | 2.35%   |
| Syntek                                 | 3         | 1.76%   |
| Suyin                                  | 3         | 1.76%   |
| Silicon Motion                         | 3         | 1.76%   |
| Logitech                               | 2         | 1.18%   |
| Z-Star Microelectronics                | 1         | 0.59%   |
| Sonix Technology                       | 1         | 0.59%   |
| Samsung Electronics                    | 1         | 0.59%   |
| Microsoft                              | 1         | 0.59%   |
| LG Electronics                         | 1         | 0.59%   |
| Importek                               | 1         | 0.59%   |
| GEMBIRD                                | 1         | 0.59%   |
| Creative Technology                    | 1         | 0.59%   |
| BRS 2Mp Camera                         | 1         | 0.59%   |
| Alpha Imaging Technology               | 1         | 0.59%   |
| ALi                                    | 1         | 0.59%   |
| Acer                                   | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 14        | 8.09%   |
| Chicony Integrated Camera                           | 9         | 5.2%    |
| Sunplus HD WebCam                                   | 5         | 2.89%   |
| IMC Networks Integrated Camera                      | 5         | 2.89%   |
| Apple FaceTime HD Camera                            | 5         | 2.89%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 2.31%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.31%   |
| Realtek Integrated Webcam                           | 3         | 1.73%   |
| Primax HP HD Webcam [Fixed]                         | 3         | 1.73%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 1.73%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.73%   |
| Chicony HP HD Camera                                | 3         | 1.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.73%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.73%   |
| Syntek Integrated Camera                            | 2         | 1.16%   |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 1.16%   |
| Realtek Integrated Webcam HD                        | 2         | 1.16%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.16%   |
| Quanta HD WebCam                                    | 2         | 1.16%   |
| Microdia Integrated Webcam                          | 2         | 1.16%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.16%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.16%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.16%   |
| Lite-On HP HD Camera                                | 2         | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.16%   |
| Chicony USB 2.0 Camera                              | 2         | 1.16%   |
| Chicony Integrated HP HD Webcam                     | 2         | 1.16%   |
| Chicony HP Truevision HD                            | 2         | 1.16%   |
| Chicony HP HD Webcam                                | 2         | 1.16%   |
| Chicony HD WebCam                                   | 2         | 1.16%   |
| Z-Star Vega USB2.0 Camera                           | 1         | 0.58%   |
| Syntek EasyCamera                                   | 1         | 0.58%   |
| Suyin TOSHIBA Web Camera - HD                       | 1         | 0.58%   |
| Suyin HP TrueVision HD                              | 1         | 0.58%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.58%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.58%   |
| Sunplus Integrated Camera                           | 1         | 0.58%   |
| Sunplus Dell Integrated Webcam                      | 1         | 0.58%   |
| Sunplus Dell E5570 integrated webcam                | 1         | 0.58%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 44.44%  |
| Synaptics                  | 10        | 27.78%  |
| Shenzhen Goodix Technology | 4         | 11.11%  |
| Elan Microelectronics      | 2         | 5.56%   |
| Upek                       | 1         | 2.78%   |
| STMicroelectronics         | 1         | 2.78%   |
| LighTuning Technology      | 1         | 2.78%   |
| AuthenTec                  | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                    | 4         | 11.11%  |
| Validity Sensors VFS491                                | 3         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 5.56%   |
| Synaptics Fingerprint reader [HP G6]                   | 2         | 5.56%   |
| Elan ELAN:ARM-M4                                       | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors Synaptics WBDI                        | 1         | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.78%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 2.78%   |
| Synaptics WBDI                                         | 1         | 2.78%   |
| Synaptics Prometheus Fingerprint Reader                | 1         | 2.78%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.78%   |
| AuthenTec AES1600                                      | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 5         | 45.45%  |
| O2 Micro                   | 3         | 27.27%  |
| Athena Smartcard Solutions | 2         | 18.18%  |
| Alcor Micro                | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 3         | 27.27%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 18.18%  |
| Athena Smartcard Solutions ASEDrive V3C                                      | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 124       | 62%     |
| 1     | 64        | 32%     |
| 2     | 8         | 4%      |
| 3     | 4         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 35        | 37.63%  |
| Graphics card            | 19        | 20.43%  |
| Net/wireless             | 15        | 16.13%  |
| Chipcard                 | 9         | 9.68%   |
| Multimedia controller    | 4         | 4.3%    |
| Firewire controller      | 2         | 2.15%   |
| Communication controller | 2         | 2.15%   |
| Camera                   | 2         | 2.15%   |
| Storage                  | 1         | 1.08%   |
| Sound                    | 1         | 1.08%   |
| Net/ethernet             | 1         | 1.08%   |
| Card reader              | 1         | 1.08%   |
| Bluetooth                | 1         | 1.08%   |


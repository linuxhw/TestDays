Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 5015

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E490 20N80017RT    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [85c3968edc](https://linux-hardware.org/?probe=85c3968edc) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | Precision 5570              | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| HP            | EliteBook 840 G3            | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| Dell          | XPS 9315                    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| MSI           | GS63 7RD                    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Precision 3581              | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26a3b9b3e9](https://linux-hardware.org/?probe=26a3b9b3e9) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| Acer          | Nitro AN517-51              | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| Dell          | Inspiron 3558               | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S14V00    | [6f81cc6d57](https://linux-hardware.org/?probe=6f81cc6d57) | Jun 19, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| Dell          | Latitude E7440              | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| HP            | Pavilion dv7                | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| Samsung       | 750XDA                      | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| Dell          | XPS 13 9350                 | [1150629ceb](https://linux-hardware.org/?probe=1150629ceb) | Jun 16, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| HP            | ProBook 650 G2              | [535950bae5](https://linux-hardware.org/?probe=535950bae5) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Acer          | Aspire A715-41G             | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | [41526d21bc](https://linux-hardware.org/?probe=41526d21bc) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | [6154060edd](https://linux-hardware.org/?probe=6154060edd) | Jun 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Dell          | Latitude E5470              | [cc81f6c74c](https://linux-hardware.org/?probe=cc81f6c74c) | Jun 11, 2023 |
| HP            | EliteBook 840 G2            | [80bc2607fb](https://linux-hardware.org/?probe=80bc2607fb) | Jun 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| Dell          | Latitude E5470              | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| HP            | 14                          | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Dell          | XPS 17 9730                 | [bb7335618d](https://linux-hardware.org/?probe=bb7335618d) | Jun 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Dell          | G15 5520                    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Google        | Edgar                       | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1f4ef72dbd](https://linux-hardware.org/?probe=1f4ef72dbd) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire A515-47              | [db7f17cbe1](https://linux-hardware.org/?probe=db7f17cbe1) | Jun 07, 2023 |
| Acer          | Swift SF314-43              | [9636ea4dc5](https://linux-hardware.org/?probe=9636ea4dc5) | Jun 07, 2023 |
| Dell          | Latitude 5480               | [dd2fef35ee](https://linux-hardware.org/?probe=dd2fef35ee) | Jun 06, 2023 |
| Dell          | Latitude 5480               | [7917512387](https://linux-hardware.org/?probe=7917512387) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| MSI           | Crosshair 15 C12VF          | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| Apple         | MacBookPro7,1               | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| MSI           | Katana GF66 11UG            | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Cube          | i16-L                       | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| Acer          | Swift SF314-511             | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [e0f06316db](https://linux-hardware.org/?probe=e0f06316db) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| Gigabyte      | AERO 15WV8                  | [a8700141be](https://linux-hardware.org/?probe=a8700141be) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Acer          | Nitro AN515-55              | [947c70d6b6](https://linux-hardware.org/?probe=947c70d6b6) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Inspiron 5515               | [f383c5193d](https://linux-hardware.org/?probe=f383c5193d) | Jun 01, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| Dell          | Inspiron 5593               | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| Dell          | Latitude E6420              | [102e4634b1](https://linux-hardware.org/?probe=102e4634b1) | May 31, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| ASUSTek       | N61Jv                       | [7184d6add6](https://linux-hardware.org/?probe=7184d6add6) | May 30, 2023 |
| HP            | Laptop 15-ef1xxx            | [55b500a1a9](https://linux-hardware.org/?probe=55b500a1a9) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| Dell          | Inspiron 1525               | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | 14                          | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Dell          | Inspiron 1525               | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Acer          | Aspire A515-41G             | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Dell          | Inspiron 5447               | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [12838b3e3b](https://linux-hardware.org/?probe=12838b3e3b) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Apple         | MacBookPro7,1               | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| HP            | EliteBook 840 G5            | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Dell          | Latitude E6440              | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| Acer          | Swift SF514-54GT            | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | EliteBook 8440p             | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| Dell          | Precision 3581              | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Dell          | Latitude 5430               | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Nitro AN515-45              | [a9e0505d3f](https://linux-hardware.org/?probe=a9e0505d3f) | May 26, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Z580                | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| ASUSTek       | S551LB                      | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Acer          | Swift SF314-71              | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| Acer          | Swift SF314-71              | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e6c958dd68](https://linux-hardware.org/?probe=e6c958dd68) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| Acer          | Aspire A315-58              | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Toshiba       | Satellite C645D             | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| HP            | Pavilion 17                 | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Acer          | Nitro AN515-45              | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Apple         | MacBookPro7,1               | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Dell          | G3 3500                     | [490bdc1f92](https://linux-hardware.org/?probe=490bdc1f92) | May 21, 2023 |
| HP            | Laptop 15-dy4xxx            | [d739b1ab41](https://linux-hardware.org/?probe=d739b1ab41) | May 21, 2023 |
| HASEE Comp... | V1x0PNPx                    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [d82bf9332f](https://linux-hardware.org/?probe=d82bf9332f) | May 20, 2023 |
| Dell          | Latitude D630               | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| Apple         | MacBookPro15,2              | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| HP            | Unknown                     | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| ASUSTek       | X555LPB                     | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| Dell          | Latitude 5500               | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| Dell          | Latitude 5420               | [bd0c08b7b8](https://linux-hardware.org/?probe=bd0c08b7b8) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Apple         | MacBookPro11,1              | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Acer          | Swift SF315-51G             | [4361a75669](https://linux-hardware.org/?probe=4361a75669) | May 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [42f598550a](https://linux-hardware.org/?probe=42f598550a) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| Emdoor        | AG958                       | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Google        | Cyan                        | [41811cace9](https://linux-hardware.org/?probe=41811cace9) | May 17, 2023 |
| Dell          | Latitude 5330               | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| GPD           | MicroPC                     | [0da3fc7738](https://linux-hardware.org/?probe=0da3fc7738) | May 16, 2023 |
| Google        | Cyan                        | [65c63caab7](https://linux-hardware.org/?probe=65c63caab7) | May 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [dc5dd8c32a](https://linux-hardware.org/?probe=dc5dd8c32a) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [85c2869727](https://linux-hardware.org/?probe=85c2869727) | May 15, 2023 |
| Acer          | Swift SF114-34              | [360db31139](https://linux-hardware.org/?probe=360db31139) | May 14, 2023 |
| Acer          | Swift SF114-34              | [c3bbc544d3](https://linux-hardware.org/?probe=c3bbc544d3) | May 14, 2023 |
| Lenovo        | ThinkPad T570 20H90002GE    | [e6ff63678e](https://linux-hardware.org/?probe=e6ff63678e) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| HP            | EliteBook 8470p             | [b9f9ed1b25](https://linux-hardware.org/?probe=b9f9ed1b25) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [92c052d9b4](https://linux-hardware.org/?probe=92c052d9b4) | May 14, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [4b296f5c40](https://linux-hardware.org/?probe=4b296f5c40) | May 12, 2023 |
| Razer         | Blade 15 Studio Edition ... | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| realme        | RMNBXXXX                    | [16782746d8](https://linux-hardware.org/?probe=16782746d8) | May 12, 2023 |
| Dell          | Latitude 7390               | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Medion        | Crawler E40                 | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| Medion        | Crawler E40                 | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| Dell          | Latitude 7400               | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Dell          | Latitude 5480               | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [39dd8fc09a](https://linux-hardware.org/?probe=39dd8fc09a) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [0a1c43b710](https://linux-hardware.org/?probe=0a1c43b710) | May 09, 2023 |
| MSI           | PS42 Modern 8RA             | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire A315-22              | [8849d7a1c9](https://linux-hardware.org/?probe=8849d7a1c9) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Acer          | Aspire V3-772G              | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| MSI           | GV63 8SE                    | [55bfa86f43](https://linux-hardware.org/?probe=55bfa86f43) | May 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [af9591cedc](https://linux-hardware.org/?probe=af9591cedc) | May 07, 2023 |
| Dell          | Precision 7720              | [9e0a1bd8ef](https://linux-hardware.org/?probe=9e0a1bd8ef) | May 06, 2023 |
| Toshiba       | Satellite C855              | [775c7346eb](https://linux-hardware.org/?probe=775c7346eb) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Dell          | Precision 7550              | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| HP            | Laptop 15s-eq0xxx           | [a5252d48f3](https://linux-hardware.org/?probe=a5252d48f3) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| Lenovo        | ThinkPad X131e 33712MU      | [6957336ed7](https://linux-hardware.org/?probe=6957336ed7) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5f4447aa45](https://linux-hardware.org/?probe=5f4447aa45) | May 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [907a94ae07](https://linux-hardware.org/?probe=907a94ae07) | May 05, 2023 |
| MSI           | GV63 8SE                    | [1c78e3feb9](https://linux-hardware.org/?probe=1c78e3feb9) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Apple         | MacBookPro14,2              | [4124bb2dde](https://linux-hardware.org/?probe=4124bb2dde) | May 04, 2023 |
| ASUSTek       | N550JK                      | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | G505s 20255                 | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Quanta        | UW3 TBD                     | [0c951d032e](https://linux-hardware.org/?probe=0c951d032e) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | [abc1819fc1](https://linux-hardware.org/?probe=abc1819fc1) | May 04, 2023 |
| Lenovo        | B490 37722XP                | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Quanta        | UW3 TBD                     | [c138f57a47](https://linux-hardware.org/?probe=c138f57a47) | May 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| Acer          | Predator G9-793             | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Samsung       | 750XDA                      | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [abd1474dfc](https://linux-hardware.org/?probe=abd1474dfc) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| HP            | ProBook 430 G1              | [56542de280](https://linux-hardware.org/?probe=56542de280) | May 01, 2023 |
| Dell          | Inspiron 5458               | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [6b61472a4a](https://linux-hardware.org/?probe=6b61472a4a) | May 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| HP            | Laptop 15s-eq3xxx           | [3c321c476a](https://linux-hardware.org/?probe=3c321c476a) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| Dell          | XPS 13 9310                 | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [34420e9478](https://linux-hardware.org/?probe=34420e9478) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [96194bc912](https://linux-hardware.org/?probe=96194bc912) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| Dell          | Latitude 7420               | [7ceeb888fd](https://linux-hardware.org/?probe=7ceeb888fd) | Apr 27, 2023 |
| Dell          | Latitude E5440              | [0217386dbe](https://linux-hardware.org/?probe=0217386dbe) | Apr 27, 2023 |
| Sony          | SVE11113FXW                 | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| MSI           | Prestige 14 A12UC           | [137a3623dc](https://linux-hardware.org/?probe=137a3623dc) | Apr 25, 2023 |
| Notebook      | N85_N87HCHNHZ               | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Notebook      | N15_N17RD1                  | [8bba7a7447](https://linux-hardware.org/?probe=8bba7a7447) | Apr 23, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| HP            | 240 G4                      | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| HP            | 15                          | [4f563db114](https://linux-hardware.org/?probe=4f563db114) | Apr 21, 2023 |
| Valve         | Jupiter                     | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| Acer          | Aspire A715-71G             | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [be217cbc1e](https://linux-hardware.org/?probe=be217cbc1e) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d5e90c4b14](https://linux-hardware.org/?probe=d5e90c4b14) | Apr 19, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [146c678131](https://linux-hardware.org/?probe=146c678131) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [65a5b3f43d](https://linux-hardware.org/?probe=65a5b3f43d) | Apr 17, 2023 |
| MSI           | GF75 Thin 9SC               | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2fcbae14f2](https://linux-hardware.org/?probe=2fcbae14f2) | Apr 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [fff7f3dd1f](https://linux-hardware.org/?probe=fff7f3dd1f) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [e0ad93045c](https://linux-hardware.org/?probe=e0ad93045c) | Apr 14, 2023 |
| Lenovo        | V15-ADA 82C7                | [f604f6e212](https://linux-hardware.org/?probe=f604f6e212) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Avell High... | B.ON                        | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| HP            | ProBook 430 G6              | [9a4bce918e](https://linux-hardware.org/?probe=9a4bce918e) | Apr 14, 2023 |
| System76      | Pangolin                    | [b5dd9f13b9](https://linux-hardware.org/?probe=b5dd9f13b9) | Apr 14, 2023 |
| System76      | Pangolin                    | [a1a17fa4c4](https://linux-hardware.org/?probe=a1a17fa4c4) | Apr 14, 2023 |
| Lenovo        | ThinkPad T460 20FMS0E22C    | [ee911053e5](https://linux-hardware.org/?probe=ee911053e5) | Apr 13, 2023 |
| MSI           | Prestige 14 A12UC           | [43e044c37a](https://linux-hardware.org/?probe=43e044c37a) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| MSI           | Stealth 14Studio A13VF      | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Dell          | Latitude E7440              | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Toshiba       | Satellite S50-B             | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| HP            | Laptop 14s-cr0xxx           | [f95d67a702](https://linux-hardware.org/?probe=f95d67a702) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| Google        | Phaser360                   | [64953bc26c](https://linux-hardware.org/?probe=64953bc26c) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [772414cda4](https://linux-hardware.org/?probe=772414cda4) | Apr 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK S935               | [e7ba943509](https://linux-hardware.org/?probe=e7ba943509) | Apr 07, 2023 |
| HP            | ZBook 15 G5                 | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Dell          | Vostro 5620                 | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a02839d653](https://linux-hardware.org/?probe=a02839d653) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| Timi          | RedmiBook Pro 15            | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Alienware     | M17xR3                      | [514f79bd8e](https://linux-hardware.org/?probe=514f79bd8e) | Apr 05, 2023 |
| Acer          | AO756                       | [4e33479949](https://linux-hardware.org/?probe=4e33479949) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Prestigio     | PSB133S01ZFH                | [ba6746febf](https://linux-hardware.org/?probe=ba6746febf) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Google        | Snappy                      | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Schenker      | S405                        | [6d89f7e662](https://linux-hardware.org/?probe=6d89f7e662) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| Dell          | Inspiron 13 5310            | [32bdbfa581](https://linux-hardware.org/?probe=32bdbfa581) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440p              | [4057e0c5e9](https://linux-hardware.org/?probe=4057e0c5e9) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Dell          | XPS 17 9700                 | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440p              | [1063ba3fb9](https://linux-hardware.org/?probe=1063ba3fb9) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [0ab4f4cd55](https://linux-hardware.org/?probe=0ab4f4cd55) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [2e8eab25be](https://linux-hardware.org/?probe=2e8eab25be) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [d96583e702](https://linux-hardware.org/?probe=d96583e702) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| Acer          | Aspire ES1-512              | [f6357798c5](https://linux-hardware.org/?probe=f6357798c5) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| HP            | ElitePad 1000 G2            | [4b16a78f3e](https://linux-hardware.org/?probe=4b16a78f3e) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| Dell          | XPS 15 9500                 | [cebc7c547a](https://linux-hardware.org/?probe=cebc7c547a) | Mar 26, 2023 |
| Dell          | XPS 15 9500                 | [4391dcbdd2](https://linux-hardware.org/?probe=4391dcbdd2) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [0933beb0f7](https://linux-hardware.org/?probe=0933beb0f7) | Mar 26, 2023 |
| Dell          | G3 3590                     | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| HP            | ENVY Laptop 17-ce1xxx       | [f9ff96064b](https://linux-hardware.org/?probe=f9ff96064b) | Mar 24, 2023 |
| Toshiba       | Satellite C850-140          | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| Toshiba       | Satellite C55D-B            | [ae6069d9bb](https://linux-hardware.org/?probe=ae6069d9bb) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Acer          | Aspire A515-57              | [748d918a61](https://linux-hardware.org/?probe=748d918a61) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [38b0e00744](https://linux-hardware.org/?probe=38b0e00744) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [ad1134944b](https://linux-hardware.org/?probe=ad1134944b) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| ASUSTek       | T100HAN                     | [5f0061dd7b](https://linux-hardware.org/?probe=5f0061dd7b) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [0880214933](https://linux-hardware.org/?probe=0880214933) | Mar 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [e7b50c8f22](https://linux-hardware.org/?probe=e7b50c8f22) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [1da76d59b2](https://linux-hardware.org/?probe=1da76d59b2) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| MSI           | Modern 14 B10MW             | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| HP            | ProBook 440 G3              | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | [8d13f6eef9](https://linux-hardware.org/?probe=8d13f6eef9) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | [5b4e0532f8](https://linux-hardware.org/?probe=5b4e0532f8) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Dell          | G15 5511                    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0500018bce](https://linux-hardware.org/?probe=0500018bce) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [aa4184ac0c](https://linux-hardware.org/?probe=aa4184ac0c) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [00de843c75](https://linux-hardware.org/?probe=00de843c75) | Mar 19, 2023 |
| MSI           | GP66 Leopard 11UG           | [7210f8c423](https://linux-hardware.org/?probe=7210f8c423) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Unknown       | Unknown                     | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [434b76d9cd](https://linux-hardware.org/?probe=434b76d9cd) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [2ffc3ebd28](https://linux-hardware.org/?probe=2ffc3ebd28) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [304f8b71db](https://linux-hardware.org/?probe=304f8b71db) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [4bfe066835](https://linux-hardware.org/?probe=4bfe066835) | Mar 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [590a3ca248](https://linux-hardware.org/?probe=590a3ca248) | Mar 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [e4254565ed](https://linux-hardware.org/?probe=e4254565ed) | Mar 15, 2023 |
| Star Labs     | StarBook                    | [13efc22826](https://linux-hardware.org/?probe=13efc22826) | Mar 15, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [29ebc422fe](https://linux-hardware.org/?probe=29ebc422fe) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Acer          | Aspire E5-571               | [6c7886396a](https://linux-hardware.org/?probe=6c7886396a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| Dell          | Vostro 2420                 | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Star Labs     | StarBook                    | [3e534c533a](https://linux-hardware.org/?probe=3e534c533a) | Mar 14, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [2906d8ad11](https://linux-hardware.org/?probe=2906d8ad11) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Panasonic     | FZ40-1                      | [1dfcc0c545](https://linux-hardware.org/?probe=1dfcc0c545) | Mar 13, 2023 |
| HP            | ProBook 6460b               | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [87331b21e8](https://linux-hardware.org/?probe=87331b21e8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [5522717dc5](https://linux-hardware.org/?probe=5522717dc5) | Mar 12, 2023 |
| MSI           | Pulse GL66 11UGKV           | [1abb09da1a](https://linux-hardware.org/?probe=1abb09da1a) | Mar 12, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [a081c489c9](https://linux-hardware.org/?probe=a081c489c9) | Mar 12, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Dell          | Latitude E6530              | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | [5d082aaf0e](https://linux-hardware.org/?probe=5d082aaf0e) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | [9eac1dc6f5](https://linux-hardware.org/?probe=9eac1dc6f5) | Mar 10, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [06971429a7](https://linux-hardware.org/?probe=06971429a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| HP            | Laptop 14-fq0xxx            | [8574146364](https://linux-hardware.org/?probe=8574146364) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | [c397e2fa8b](https://linux-hardware.org/?probe=c397e2fa8b) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [79fc708bbd](https://linux-hardware.org/?probe=79fc708bbd) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [c768e8ff8f](https://linux-hardware.org/?probe=c768e8ff8f) | Mar 08, 2023 |
| Dell          | Precision 3520              | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude 5590               | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| GPD           | P2 MAX                      | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | Pavilion dv6                | [6485870687](https://linux-hardware.org/?probe=6485870687) | Mar 06, 2023 |
| Acer          | Aspire A114-31              | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [0047dd8b2a](https://linux-hardware.org/?probe=0047dd8b2a) | Mar 06, 2023 |
| Lenovo        | Unknown                     | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [6a7ad331f8](https://linux-hardware.org/?probe=6a7ad331f8) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [6a6864f933](https://linux-hardware.org/?probe=6a6864f933) | Mar 05, 2023 |
| Acer          | Aspire A514-55              | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [ea211d74ee](https://linux-hardware.org/?probe=ea211d74ee) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| Dell          | Latitude 5480               | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Acer          | Nitro AN515-58              | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Dell          | Latitude E6510              | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| Dell          | XPS 15 9500                 | [13f585159e](https://linux-hardware.org/?probe=13f585159e) | Mar 02, 2023 |
| DTRI          | DT317CR                     | [b78d90835c](https://linux-hardware.org/?probe=b78d90835c) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| Dell          | Precision 5520              | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | [f61c295d09](https://linux-hardware.org/?probe=f61c295d09) | Mar 01, 2023 |
| Dell          | XPS 15 9550                 | [0ffe1f9541](https://linux-hardware.org/?probe=0ffe1f9541) | Feb 28, 2023 |
| HP            | Laptop 15s-eq3xxx           | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookPro8,1               | [ec1f27de09](https://linux-hardware.org/?probe=ec1f27de09) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | [1643b96eae](https://linux-hardware.org/?probe=1643b96eae) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | [b48cc99ce3](https://linux-hardware.org/?probe=b48cc99ce3) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| HP            | ProBook 430 G1              | [fa75658ee0](https://linux-hardware.org/?probe=fa75658ee0) | Feb 28, 2023 |
| Dell          | G15 5510                    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| Dell          | G15 5510                    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| Dell          | Latitude 7390               | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| HP            | ProBook 430 G1              | [1354e0b47e](https://linux-hardware.org/?probe=1354e0b47e) | Feb 26, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [848e43f7c3](https://linux-hardware.org/?probe=848e43f7c3) | Feb 26, 2023 |
| Sony          | SVE1712C1EW                 | [20bd9411d9](https://linux-hardware.org/?probe=20bd9411d9) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [e07445a583](https://linux-hardware.org/?probe=e07445a583) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| Star Labs     | StarBook                    | [fbd529b953](https://linux-hardware.org/?probe=fbd529b953) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [64504d9860](https://linux-hardware.org/?probe=64504d9860) | Feb 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [8a573735cb](https://linux-hardware.org/?probe=8a573735cb) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Dell          | XPS 13 9310                 | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [028814b990](https://linux-hardware.org/?probe=028814b990) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| Avell High... | A70 MOB                     | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [c69ac67426](https://linux-hardware.org/?probe=c69ac67426) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| Acer          | Swift SF514-54GT            | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [14cf9e07e0](https://linux-hardware.org/?probe=14cf9e07e0) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [388f34d16e](https://linux-hardware.org/?probe=388f34d16e) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| HP            | ProBook 640 G5              | [e90b71c2fd](https://linux-hardware.org/?probe=e90b71c2fd) | Feb 22, 2023 |
| Acer          | Aspire ES1-533              | [4a7563bd8e](https://linux-hardware.org/?probe=4a7563bd8e) | Feb 22, 2023 |
| Compaq        | 430                         | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [dd12dc45d7](https://linux-hardware.org/?probe=dd12dc45d7) | Feb 21, 2023 |
| Dell          | XPS 13 9360                 | [f36328511d](https://linux-hardware.org/?probe=f36328511d) | Feb 21, 2023 |
| HP            | ProBook 430 G1              | [1505165a73](https://linux-hardware.org/?probe=1505165a73) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [e008fd489b](https://linux-hardware.org/?probe=e008fd489b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [defde684a0](https://linux-hardware.org/?probe=defde684a0) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [1832e70d83](https://linux-hardware.org/?probe=1832e70d83) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [9adf6b834b](https://linux-hardware.org/?probe=9adf6b834b) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| HUAWEI        | MACHC-WAX9                  | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6aae20aa14](https://linux-hardware.org/?probe=6aae20aa14) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Google        | Celes                       | [3004fce0ed](https://linux-hardware.org/?probe=3004fce0ed) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [c4ec00ef99](https://linux-hardware.org/?probe=c4ec00ef99) | Feb 17, 2023 |
| TUXEDO        | Unknown                     | [d770ba8b7b](https://linux-hardware.org/?probe=d770ba8b7b) | Feb 17, 2023 |
| Acer          | Nitro AN515-46              | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Acer          | Aspire A515-51G             | [065827a397](https://linux-hardware.org/?probe=065827a397) | Feb 16, 2023 |
| Dell          | Latitude 5330               | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Dell          | Latitude 5330               | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| Lenovo        | B40-70 20392                | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Dell          | Latitude 5480               | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [138839541a](https://linux-hardware.org/?probe=138839541a) | Feb 15, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | [dc352cd9dc](https://linux-hardware.org/?probe=dc352cd9dc) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Dell          | Venue 8 Pro 5855            | [6e5eacb53a](https://linux-hardware.org/?probe=6e5eacb53a) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E6530              | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Acer          | Swift SF514-54GT            | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [b3ab77c355](https://linux-hardware.org/?probe=b3ab77c355) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [37c223623f](https://linux-hardware.org/?probe=37c223623f) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [3f25b64868](https://linux-hardware.org/?probe=3f25b64868) | Feb 13, 2023 |
| ASUSTek       | X205TA                      | [dfc9ada1af](https://linux-hardware.org/?probe=dfc9ada1af) | Feb 13, 2023 |
| HP            | ProBook 430 G1              | [8d414de313](https://linux-hardware.org/?probe=8d414de313) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [afb25c8733](https://linux-hardware.org/?probe=afb25c8733) | Feb 12, 2023 |
| MSI           | Modern 14 B11MOU            | [547c8e5750](https://linux-hardware.org/?probe=547c8e5750) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [35d68b3769](https://linux-hardware.org/?probe=35d68b3769) | Feb 12, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [5335da53d0](https://linux-hardware.org/?probe=5335da53d0) | Feb 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [5f2fb779b4](https://linux-hardware.org/?probe=5f2fb779b4) | Feb 11, 2023 |
| Samsung       | 767XCL                      | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| HP            | Laptop 15s-eq3xxx           | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Unknown       | Unknown                     | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | [cb3ab0bbf5](https://linux-hardware.org/?probe=cb3ab0bbf5) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [482b3ea2be](https://linux-hardware.org/?probe=482b3ea2be) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | [132d55b2ed](https://linux-hardware.org/?probe=132d55b2ed) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [fc292cd441](https://linux-hardware.org/?probe=fc292cd441) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | G50-70 20351                | [af3d5cd04c](https://linux-hardware.org/?probe=af3d5cd04c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [02b69364a6](https://linux-hardware.org/?probe=02b69364a6) | Feb 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [83efc68bd7](https://linux-hardware.org/?probe=83efc68bd7) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | [e39c3cefa0](https://linux-hardware.org/?probe=e39c3cefa0) | Feb 08, 2023 |
| Dell          | Latitude E5470              | [e0634fdc6e](https://linux-hardware.org/?probe=e0634fdc6e) | Feb 08, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [0e174666ba](https://linux-hardware.org/?probe=0e174666ba) | Feb 07, 2023 |
| HUAWEI        | NBD-WXX9                    | [2bb967f6b3](https://linux-hardware.org/?probe=2bb967f6b3) | Feb 07, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [a127a79277](https://linux-hardware.org/?probe=a127a79277) | Feb 07, 2023 |
| Dell          | Precision M4800             | [2572c61169](https://linux-hardware.org/?probe=2572c61169) | Feb 07, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [6e7434a708](https://linux-hardware.org/?probe=6e7434a708) | Feb 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [149a2716a8](https://linux-hardware.org/?probe=149a2716a8) | Feb 06, 2023 |
| Lenovo        | G505 20240                  | [31e2c2f5e1](https://linux-hardware.org/?probe=31e2c2f5e1) | Feb 06, 2023 |
| Toshiba       | Satellite Pro L510          | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| Apple         | MacBookPro11,4              | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ba7531b9db](https://linux-hardware.org/?probe=ba7531b9db) | Feb 05, 2023 |
| Acer          | Nitro AN517-52              | [e409f042e2](https://linux-hardware.org/?probe=e409f042e2) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | [72228118bb](https://linux-hardware.org/?probe=72228118bb) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Apple         | MacBookPro13,1              | [76cf23841d](https://linux-hardware.org/?probe=76cf23841d) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [42d855f568](https://linux-hardware.org/?probe=42d855f568) | Feb 04, 2023 |
| Dell          | G3 3579                     | [a3b4edbfd9](https://linux-hardware.org/?probe=a3b4edbfd9) | Feb 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [cee7b3fa93](https://linux-hardware.org/?probe=cee7b3fa93) | Feb 04, 2023 |
| HUAWEI        | NBD-WXX9                    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | [48d07b6859](https://linux-hardware.org/?probe=48d07b6859) | Feb 04, 2023 |
| Medion        | S17405                      | [85cdfa1290](https://linux-hardware.org/?probe=85cdfa1290) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| MSI           | GE63 Raider RGB 9SE         | [b7ec016843](https://linux-hardware.org/?probe=b7ec016843) | Feb 02, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [7c6794cc63](https://linux-hardware.org/?probe=7c6794cc63) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ee219f2f82](https://linux-hardware.org/?probe=ee219f2f82) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [af2f6edc6f](https://linux-hardware.org/?probe=af2f6edc6f) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [b88f08d400](https://linux-hardware.org/?probe=b88f08d400) | Jan 29, 2023 |
| Dell          | G15 5520                    | [ae4bf1777e](https://linux-hardware.org/?probe=ae4bf1777e) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8727d22cba](https://linux-hardware.org/?probe=8727d22cba) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [4603f92b18](https://linux-hardware.org/?probe=4603f92b18) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [608c0b8c88](https://linux-hardware.org/?probe=608c0b8c88) | Jan 29, 2023 |
| Dell          | Latitude E6530              | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| Dell          | G15 5520                    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [85e23fef85](https://linux-hardware.org/?probe=85e23fef85) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [ff67a5eb33](https://linux-hardware.org/?probe=ff67a5eb33) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| Acer          | Aspire ES1-411              | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| Dell          | XPS 15 9500                 | [4109360c56](https://linux-hardware.org/?probe=4109360c56) | Jan 26, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Dell          | G3 3500                     | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [4a3c63f3f0](https://linux-hardware.org/?probe=4a3c63f3f0) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2026175299](https://linux-hardware.org/?probe=2026175299) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [702b3c77fc](https://linux-hardware.org/?probe=702b3c77fc) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [5258f49771](https://linux-hardware.org/?probe=5258f49771) | Jan 24, 2023 |
| Dell          | XPS 15 9570                 | [270a9bf553](https://linux-hardware.org/?probe=270a9bf553) | Jan 24, 2023 |
| TUXEDO        | Unknown                     | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [647c279ad4](https://linux-hardware.org/?probe=647c279ad4) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4c6da4840e](https://linux-hardware.org/?probe=4c6da4840e) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Lenovo        | ThinkPad L430 2466DS2       | [8be9a889b7](https://linux-hardware.org/?probe=8be9a889b7) | Jan 22, 2023 |
| Dell          | G3 3500                     | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [15b2f3fc5e](https://linux-hardware.org/?probe=15b2f3fc5e) | Jan 22, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [cd1f6d8306](https://linux-hardware.org/?probe=cd1f6d8306) | Jan 21, 2023 |
| Dell          | Vostro 15 3515              | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [45bc9c5f3f](https://linux-hardware.org/?probe=45bc9c5f3f) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f33b08f626](https://linux-hardware.org/?probe=f33b08f626) | Jan 21, 2023 |
| Sony          | VPCF13Z1E                   | [3eaeffde09](https://linux-hardware.org/?probe=3eaeffde09) | Jan 21, 2023 |
| MSI           | GP66 Leopard 11UH           | [cf6837bb85](https://linux-hardware.org/?probe=cf6837bb85) | Jan 20, 2023 |
| Dell          | Vostro 5620                 | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Unknown       | Unknown                     | [1de254a697](https://linux-hardware.org/?probe=1de254a697) | Jan 20, 2023 |
| Dell          | G3 3579                     | [d418b797c8](https://linux-hardware.org/?probe=d418b797c8) | Jan 20, 2023 |
| HP            | 1000                        | [62ee01ee38](https://linux-hardware.org/?probe=62ee01ee38) | Jan 20, 2023 |
| Dell          | XPS 13 7390                 | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | [c0667c5ea5](https://linux-hardware.org/?probe=c0667c5ea5) | Jan 18, 2023 |
| HP            | ProBook 640 G5              | [095355c9fc](https://linux-hardware.org/?probe=095355c9fc) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [987dcf118c](https://linux-hardware.org/?probe=987dcf118c) | Jan 17, 2023 |
| Sony          | VPCF13Z1E                   | [aa93abde02](https://linux-hardware.org/?probe=aa93abde02) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| MSI           | GP66 Leopard 11UH           | [269015d6a4](https://linux-hardware.org/?probe=269015d6a4) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a5ddfa16b9](https://linux-hardware.org/?probe=a5ddfa16b9) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| BANGHO        | MOV                         | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Lenovo        | Legion R70002021 82JW       | [5e5628739f](https://linux-hardware.org/?probe=5e5628739f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | [4c9bb70ea2](https://linux-hardware.org/?probe=4c9bb70ea2) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | XPS 15 9570                 | [bff6278ed8](https://linux-hardware.org/?probe=bff6278ed8) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Dell          | Latitude E6430              | [5951bc10ca](https://linux-hardware.org/?probe=5951bc10ca) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | N53SM                       | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e4912e6bfc](https://linux-hardware.org/?probe=e4912e6bfc) | Jan 12, 2023 |
| Acer          | Aspire A315-58              | [855dfb5e62](https://linux-hardware.org/?probe=855dfb5e62) | Jan 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [998a408a04](https://linux-hardware.org/?probe=998a408a04) | Jan 12, 2023 |
| Notebook      | NS50MU                      | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | [b5d071346b](https://linux-hardware.org/?probe=b5d071346b) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3b767cfcef](https://linux-hardware.org/?probe=3b767cfcef) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ac7ae437c8](https://linux-hardware.org/?probe=ac7ae437c8) | Jan 10, 2023 |
| Dell          | Latitude 3570               | [2748121a05](https://linux-hardware.org/?probe=2748121a05) | Jan 10, 2023 |
| Dell          | Inspiron 5502               | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| MSI           | Modern 14 B11MOU            | [0db2c1a27c](https://linux-hardware.org/?probe=0db2c1a27c) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b6e56e8d87](https://linux-hardware.org/?probe=b6e56e8d87) | Jan 08, 2023 |
| HP            | ZHAN 66 Pro G1              | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [66ba6bf6d3](https://linux-hardware.org/?probe=66ba6bf6d3) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7a02a3b48b](https://linux-hardware.org/?probe=7a02a3b48b) | Jan 08, 2023 |
| Toshiba       | Satellite C55Dt-A           | [e7b268e7e5](https://linux-hardware.org/?probe=e7b268e7e5) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| Acer          | Nitro AN515-54              | [cfabe67812](https://linux-hardware.org/?probe=cfabe67812) | Jan 07, 2023 |
| HP            | Pavilion dv6                | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| HP            | ZBook 15                    | [3e2f33f6c1](https://linux-hardware.org/?probe=3e2f33f6c1) | Jan 07, 2023 |
| Dell          | Inspiron 5515               | [3b8a41b7af](https://linux-hardware.org/?probe=3b8a41b7af) | Jan 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| Gigabyte      | AERO 16 XE4                 | [e05dd3f797](https://linux-hardware.org/?probe=e05dd3f797) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| MSI           | GP66 Leopard 11UH           | [63f0536a21](https://linux-hardware.org/?probe=63f0536a21) | Jan 04, 2023 |
| Valve         | Jupiter                     | [e7e5475978](https://linux-hardware.org/?probe=e7e5475978) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Lenovo        | ThinkPad X230 2320LFG       | [e8e510f4e6](https://linux-hardware.org/?probe=e8e510f4e6) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Acer          | Aspire R7-572G              | [56e5de8317](https://linux-hardware.org/?probe=56e5de8317) | Jan 03, 2023 |
| Acer          | Aspire A515-57G             | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| HUAWEI        | MACH-WX9                    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| HP            | ProBook 635 Aero G8         | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Toshiba       | Satellite P755              | [1296e73b50](https://linux-hardware.org/?probe=1296e73b50) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [acdb8c643e](https://linux-hardware.org/?probe=acdb8c643e) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| Dell          | Latitude E7450              | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| Dell          | Latitude E6430              | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Dell          | Latitude 3420               | [05095533cd](https://linux-hardware.org/?probe=05095533cd) | Dec 31, 2022 |
| Dell          | G3 3579                     | [cad48f0160](https://linux-hardware.org/?probe=cad48f0160) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | [4409746122](https://linux-hardware.org/?probe=4409746122) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [3f4178001d](https://linux-hardware.org/?probe=3f4178001d) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| Acer          | Aspire A715-41G             | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | AO756                       | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Acer          | Swift SF314-41              | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| System76      | Darter Pro                  | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | [a86fddc0b9](https://linux-hardware.org/?probe=a86fddc0b9) | Dec 28, 2022 |
| Acer          | Aspire 5741                 | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [9fb13764cc](https://linux-hardware.org/?probe=9fb13764cc) | Dec 26, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [6e3d39b4ae](https://linux-hardware.org/?probe=6e3d39b4ae) | Dec 25, 2022 |
| ASUSTek       | GL752VW                     | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1ae154433a](https://linux-hardware.org/?probe=1ae154433a) | Dec 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| Google        | Babytiger                   | [352d1a547b](https://linux-hardware.org/?probe=352d1a547b) | Dec 23, 2022 |
| Google        | Babytiger                   | [4b2ae6579f](https://linux-hardware.org/?probe=4b2ae6579f) | Dec 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [0246231a61](https://linux-hardware.org/?probe=0246231a61) | Dec 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0ee0790d0a](https://linux-hardware.org/?probe=0ee0790d0a) | Dec 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c2dd6d0281](https://linux-hardware.org/?probe=c2dd6d0281) | Dec 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [95b8e650ce](https://linux-hardware.org/?probe=95b8e650ce) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [5262e622da](https://linux-hardware.org/?probe=5262e622da) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [bbc48ee483](https://linux-hardware.org/?probe=bbc48ee483) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | [cd16c6fb41](https://linux-hardware.org/?probe=cd16c6fb41) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [593cdd8cf6](https://linux-hardware.org/?probe=593cdd8cf6) | Dec 19, 2022 |
| Dell          | XPS 15 9560                 | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| Alienware     | x14                         | [d965b3510e](https://linux-hardware.org/?probe=d965b3510e) | Dec 19, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [b0f674ae6f](https://linux-hardware.org/?probe=b0f674ae6f) | Dec 17, 2022 |
| Gigabyte      | G5 KE                       | [9ff3d65e35](https://linux-hardware.org/?probe=9ff3d65e35) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [87b21382ec](https://linux-hardware.org/?probe=87b21382ec) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [9768b1fe82](https://linux-hardware.org/?probe=9768b1fe82) | Dec 16, 2022 |
| Dell          | Precision 5570              | [9468beba51](https://linux-hardware.org/?probe=9468beba51) | Dec 16, 2022 |
| HP            | Laptop 15-dw4xxx            | [ac9c6384ca](https://linux-hardware.org/?probe=ac9c6384ca) | Dec 16, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6d51ea5c76](https://linux-hardware.org/?probe=6d51ea5c76) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [302dc680df](https://linux-hardware.org/?probe=302dc680df) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [d289646ec3](https://linux-hardware.org/?probe=d289646ec3) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7ea1bad26b](https://linux-hardware.org/?probe=7ea1bad26b) | Dec 15, 2022 |
| MSI           | GL75 Leopard 10SDK          | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Dell          | Latitude 5490               | [d05d57e241](https://linux-hardware.org/?probe=d05d57e241) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [40cf8dd049](https://linux-hardware.org/?probe=40cf8dd049) | Dec 12, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [304bad9c19](https://linux-hardware.org/?probe=304bad9c19) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [1461a09931](https://linux-hardware.org/?probe=1461a09931) | Dec 12, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | [f8dae62b0c](https://linux-hardware.org/?probe=f8dae62b0c) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| Sony          | VPCEB3D4R                   | [5f85b7c516](https://linux-hardware.org/?probe=5f85b7c516) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| MSI           | Modern 14 B11MOU            | [ec8ac9bbd7](https://linux-hardware.org/?probe=ec8ac9bbd7) | Dec 11, 2022 |
| HP            | Laptop 14s-fq1xxx           | [811092647b](https://linux-hardware.org/?probe=811092647b) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Acer          | Swift SF314-57G             | [3ba8e00e00](https://linux-hardware.org/?probe=3ba8e00e00) | Dec 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [92d1403bdf](https://linux-hardware.org/?probe=92d1403bdf) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Dell          | XPS 15 9500                 | [a933e298c7](https://linux-hardware.org/?probe=a933e298c7) | Dec 10, 2022 |
| Dell          | XPS 15 9500                 | [0e7dd9fbdb](https://linux-hardware.org/?probe=0e7dd9fbdb) | Dec 10, 2022 |
| Dell          | Latitude E6430              | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Acer          | Swift SFX16-52G             | [02a7a5e487](https://linux-hardware.org/?probe=02a7a5e487) | Dec 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [91b65d2fa1](https://linux-hardware.org/?probe=91b65d2fa1) | Dec 09, 2022 |
| Dell          | Inspiron 3583               | [93934b74f5](https://linux-hardware.org/?probe=93934b74f5) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [6af7fadd72](https://linux-hardware.org/?probe=6af7fadd72) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [7e1510d6c6](https://linux-hardware.org/?probe=7e1510d6c6) | Dec 09, 2022 |
| HP            | EliteBook 840 G5            | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| Dell          | Latitude 3400               | [d01726a4d0](https://linux-hardware.org/?probe=d01726a4d0) | Dec 08, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2a30990d9](https://linux-hardware.org/?probe=d2a30990d9) | Dec 08, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8924598f09](https://linux-hardware.org/?probe=8924598f09) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | [426e23829e](https://linux-hardware.org/?probe=426e23829e) | Dec 08, 2022 |
| HP            | ZBook Fury 17 G7 Mobile ... | [cb45484bb6](https://linux-hardware.org/?probe=cb45484bb6) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| MSI           | Modern 14 B11MOU            | [49e70cf65f](https://linux-hardware.org/?probe=49e70cf65f) | Dec 07, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [8575adb47e](https://linux-hardware.org/?probe=8575adb47e) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | [383bc11a0d](https://linux-hardware.org/?probe=383bc11a0d) | Dec 07, 2022 |
| Packard Be... | EasyNote LJ65               | [1ca8a161fd](https://linux-hardware.org/?probe=1ca8a161fd) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [db1a2c7a74](https://linux-hardware.org/?probe=db1a2c7a74) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [6ae5470891](https://linux-hardware.org/?probe=6ae5470891) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| HP            | ProBook 6560b               | [a73750fc79](https://linux-hardware.org/?probe=a73750fc79) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| eMachines     | E520 V1.06                  | [0ef424fa9b](https://linux-hardware.org/?probe=0ef424fa9b) | Dec 05, 2022 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [3dfd18754f](https://linux-hardware.org/?probe=3dfd18754f) | Dec 05, 2022 |
| Google        | Lick                        | [7ee6b1918e](https://linux-hardware.org/?probe=7ee6b1918e) | Dec 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cf810b2e09](https://linux-hardware.org/?probe=cf810b2e09) | Dec 04, 2022 |
| Lenovo        | ThinkPad P51 20HJS1G900     | [aaf35cbcc4](https://linux-hardware.org/?probe=aaf35cbcc4) | Dec 04, 2022 |
| Acer          | Aspire A315-23              | [8c3beba1e1](https://linux-hardware.org/?probe=8c3beba1e1) | Dec 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [f34caf87d5](https://linux-hardware.org/?probe=f34caf87d5) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HONOR         | NMH-WCX9                    | [3f107d24d1](https://linux-hardware.org/?probe=3f107d24d1) | Dec 03, 2022 |
| ASUSTek       | X580VD                      | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e16c372c9c](https://linux-hardware.org/?probe=e16c372c9c) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ae8f8361c1](https://linux-hardware.org/?probe=ae8f8361c1) | Dec 02, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d57de89542](https://linux-hardware.org/?probe=d57de89542) | Dec 01, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [cccb2da575](https://linux-hardware.org/?probe=cccb2da575) | Dec 01, 2022 |
| ASUSTek       | E403SA                      | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Positivo B... | S14SL03                     | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| MSI           | GF75 Thin 9SC               | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [9f473cbdeb](https://linux-hardware.org/?probe=9f473cbdeb) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | [b06377f324](https://linux-hardware.org/?probe=b06377f324) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a3c2004787](https://linux-hardware.org/?probe=a3c2004787) | Nov 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Arch Rolling  | 1831      | 51.07%  |
| Arch          | 1744      | 48.65%  |
| Arch V20.5.7  | 2         | 0.06%   |
| Arch V19.04.4 | 2         | 0.06%   |
| Arch V6.9.2   | 1         | 0.03%   |
| Arch V20.3.4  | 1         | 0.03%   |
| Arch V19.07.9 | 1         | 0.03%   |
| Arch V19.06.1 | 1         | 0.03%   |
| Arch V19.01.4 | 1         | 0.03%   |
| Arch 2.7      | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 3476      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 52        | 1.26%   |
| 6.0.2-arch1-1   | 51        | 1.24%   |
| 5.9.14-arch1-1  | 31        | 0.75%   |
| 5.9.1-arch1-1   | 31        | 0.75%   |
| 6.0.9-arch1-1   | 28        | 0.68%   |
| 5.8.5-arch1-1   | 28        | 0.68%   |
| 5.17.5-arch1-1  | 28        | 0.68%   |
| 5.8.10-arch1-1  | 26        | 0.63%   |
| 6.2.8-arch1-1   | 25        | 0.61%   |
| 6.1.1-arch1-1   | 25        | 0.61%   |
| 5.17.9-arch1-1  | 25        | 0.61%   |
| 5.11.16-arch1-1 | 24        | 0.58%   |
| 6.3.2-arch1-1   | 23        | 0.56%   |
| 6.2.10-arch1-1  | 23        | 0.56%   |
| 6.0.12-arch1-1  | 23        | 0.56%   |
| 5.8.14-arch1-1  | 23        | 0.56%   |
| 5.8.1-arch1-1   | 23        | 0.56%   |
| 5.7.12-arch1-1  | 23        | 0.56%   |
| 5.18.1-arch1-1  | 22        | 0.53%   |
| 5.13.13-arch1-1 | 22        | 0.53%   |
| 5.13.12-arch1-1 | 22        | 0.53%   |
| 5.18.16-arch1-1 | 21        | 0.51%   |
| 5.9.10-arch1-1  | 20        | 0.49%   |
| 5.8.12-arch1-1  | 20        | 0.49%   |
| 6.3.5-arch1-1   | 19        | 0.46%   |
| 6.0.7-arch1-1   | 19        | 0.46%   |
| 5.8.3-arch1-1   | 19        | 0.46%   |
| 5.16.16-arch1-1 | 19        | 0.46%   |
| 5.11.11-arch1-1 | 19        | 0.46%   |
| 6.3.9-arch1-1   | 18        | 0.44%   |
| 6.0.10-arch2-1  | 18        | 0.44%   |
| 5.9.11-arch2-1  | 18        | 0.44%   |
| 5.19.13-arch1-1 | 18        | 0.44%   |
| 5.16.2-arch1-1  | 18        | 0.44%   |
| 5.12.15-arch1-1 | 18        | 0.44%   |
| 5.11.2-arch1-1  | 18        | 0.44%   |
| 6.3.6-arch1-1   | 17        | 0.41%   |
| 6.2.2-arch1-1   | 17        | 0.41%   |
| 6.2.11-arch1-1  | 17        | 0.41%   |
| 6.1.9-arch1-1   | 17        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 1.58%   |
| 6.0.2   | 60        | 1.46%   |
| 5.9.1   | 40        | 0.97%   |
| 5.9.14  | 38        | 0.92%   |
| 5.8.5   | 38        | 0.92%   |
| 5.17.5  | 38        | 0.92%   |
| 6.3.1   | 36        | 0.87%   |
| 6.0.9   | 34        | 0.83%   |
| 6.3.2   | 31        | 0.75%   |
| 6.1.9   | 31        | 0.75%   |
| 5.13.13 | 31        | 0.75%   |
| 6.2.8   | 30        | 0.73%   |
| 6.1.1   | 30        | 0.73%   |
| 5.8.14  | 30        | 0.73%   |
| 5.17.9  | 30        | 0.73%   |
| 6.3.5   | 29        | 0.7%    |
| 5.8.10  | 29        | 0.7%    |
| 6.2.10  | 28        | 0.68%   |
| 6.0.12  | 28        | 0.68%   |
| 5.18.16 | 27        | 0.66%   |
| 6.2.2   | 26        | 0.63%   |
| 5.8.12  | 26        | 0.63%   |
| 5.8.1   | 26        | 0.63%   |
| 5.18.1  | 26        | 0.63%   |
| 5.16.2  | 26        | 0.63%   |
| 5.13.12 | 26        | 0.63%   |
| 5.11.16 | 26        | 0.63%   |
| 6.1.12  | 25        | 0.61%   |
| 6.0.11  | 25        | 0.61%   |
| 5.7.12  | 25        | 0.61%   |
| 5.19.13 | 24        | 0.58%   |
| 5.16.16 | 24        | 0.58%   |
| 5.14.8  | 24        | 0.58%   |
| 5.11.2  | 24        | 0.58%   |
| 5.10.16 | 24        | 0.58%   |
| 6.0.8   | 23        | 0.56%   |
| 6.0.10  | 23        | 0.56%   |
| 5.18.3  | 23        | 0.56%   |
| 5.12.15 | 23        | 0.56%   |
| 6.3.6   | 22        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 266       | 6.72%   |
| 6.0     | 244       | 6.16%   |
| 6.1     | 233       | 5.89%   |
| 5.8     | 232       | 5.86%   |
| 6.2     | 222       | 5.61%   |
| 5.18    | 219       | 5.53%   |
| 5.9     | 208       | 5.26%   |
| 6.3     | 202       | 5.1%    |
| 5.17    | 198       | 5%      |
| 5.4     | 193       | 4.88%   |
| 5.16    | 188       | 4.75%   |
| 5.10    | 182       | 4.6%    |
| 5.19    | 177       | 4.47%   |
| 5.11    | 168       | 4.24%   |
| 5.12    | 154       | 3.89%   |
| 5.13    | 143       | 3.61%   |
| 5.7     | 138       | 3.49%   |
| 5.6     | 135       | 3.41%   |
| 5.14    | 128       | 3.23%   |
| 5.5     | 93        | 2.35%   |
| 5.3     | 64        | 1.62%   |
| 5.2     | 33        | 0.83%   |
| 4.19    | 26        | 0.66%   |
| 5.0     | 19        | 0.48%   |
| 5.1     | 16        | 0.4%    |
| 4.18    | 16        | 0.4%    |
| 4.17    | 12        | 0.3%    |
| 4.20    | 9         | 0.23%   |
| 4.14    | 9         | 0.23%   |
| 4.15    | 5         | 0.13%   |
| 4.9     | 4         | 0.1%    |
| 4.7     | 4         | 0.1%    |
| 4.16    | 4         | 0.1%    |
| 4.6     | 3         | 0.08%   |
| 4.4     | 3         | 0.08%   |
| 4.8     | 2         | 0.05%   |
| 4.13    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 6.4     | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3472      | 99.88%  |
| i686   | 4         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1211      | 33.42%  |
| KDE5                     | 914       | 25.22%  |
| Unknown                  | 444       | 12.25%  |
| XFCE                     | 270       | 7.45%   |
| i3                       | 200       | 5.52%   |
| KDE                      | 144       | 3.97%   |
| sway                     | 55        | 1.52%   |
| X-Cinnamon               | 45        | 1.24%   |
| MATE                     | 42        | 1.16%   |
| Cinnamon                 | 41        | 1.13%   |
| Budgie                   | 40        | 1.1%    |
| LXQt                     | 35        | 0.97%   |
| awesome                  | 25        | 0.69%   |
| Hyprland                 | 23        | 0.63%   |
| Deepin                   | 23        | 0.63%   |
| bspwm                    | 20        | 0.55%   |
| LXDE                     | 18        | 0.5%    |
| xmonad                   | 9         | 0.25%   |
| qtile                    | 9         | 0.25%   |
| GNOME Flashback          | 9         | 0.25%   |
| DWM                      | 9         | 0.25%   |
| Unity                    | 8         | 0.22%   |
| openbox                  | 5         | 0.14%   |
| GNOME Classic            | 5         | 0.14%   |
| Enlightenment            | 4         | 0.11%   |
| i3-with-shmlog           | 3         | 0.08%   |
| LeftWM                   | 2         | 0.06%   |
| X-Generic                | 1         | 0.03%   |
| river                    | 1         | 0.03%   |
| Pantheon                 | 1         | 0.03%   |
| jwm                      | 1         | 0.03%   |
| instantwm                | 1         | 0.03%   |
| ICEWM                    | 1         | 0.03%   |
| herbstluftwm             | 1         | 0.03%   |
| dusk                     | 1         | 0.03%   |
| default                  | 1         | 0.03%   |
| chadwm                   | 1         | 0.03%   |
| /usr/bin/openbox-session | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2045      | 56.77%  |
| Wayland | 1002      | 27.82%  |
| Tty     | 303       | 8.41%   |
| Unknown | 252       | 7%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1476      | 41.08%  |
| SDDM    | 852       | 23.71%  |
| GDM     | 536       | 14.92%  |
| LightDM | 415       | 11.55%  |
| TDM     | 188       | 5.23%   |
| Ly      | 37        | 1.03%   |
| XDM     | 29        | 0.81%   |
| LXDM    | 26        | 0.72%   |
| SLiM    | 14        | 0.39%   |
| GREETD  | 9         | 0.25%   |
| EMPTTY  | 5         | 0.14%   |
| NODM    | 3         | 0.08%   |
| LY-DM   | 2         | 0.06%   |
| MDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1717      | 48.41%  |
| Unknown | 359       | 10.12%  |
| en_GB   | 202       | 5.69%   |
| C       | 193       | 5.44%   |
| it_IT   | 121       | 3.41%   |
| de_DE   | 116       | 3.27%   |
| pt_BR   | 100       | 2.82%   |
| ru_RU   | 90        | 2.54%   |
| fr_FR   | 87        | 2.45%   |
| zh_CN   | 50        | 1.41%   |
| pl_PL   | 44        | 1.24%   |
| en_IN   | 44        | 1.24%   |
| es_ES   | 37        | 1.04%   |
| en_CA   | 37        | 1.04%   |
| en_AU   | 29        | 0.82%   |
| es_MX   | 20        | 0.56%   |
| es_AR   | 13        | 0.37%   |
| de_AT   | 13        | 0.37%   |
| pt_PT   | 12        | 0.34%   |
| en_IE   | 12        | 0.34%   |
| en_DK   | 12        | 0.34%   |
| tr_TR   | 11        | 0.31%   |
| ja_JP   | 9         | 0.25%   |
| hu_HU   | 9         | 0.25%   |
| es_CO   | 9         | 0.25%   |
| nl_NL   | 8         | 0.23%   |
| es_CL   | 8         | 0.23%   |
| en_NZ   | 8         | 0.23%   |
| zh_TW   | 7         | 0.2%    |
| ru_UA   | 7         | 0.2%    |
| en_ZA   | 7         | 0.2%    |
| en_SG   | 7         | 0.2%    |
| cs_CZ   | 7         | 0.2%    |
| es_PE   | 6         | 0.17%   |
| en_AG   | 6         | 0.17%   |
| lv_LV   | 5         | 0.14%   |
| fr_CA   | 5         | 0.14%   |
| en-US   | 5         | 0.14%   |
| ca_ES   | 5         | 0.14%   |
| ko_KR   | 4         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2218      | 62.44%  |
| BIOS | 1334      | 37.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2531      | 71.96%  |
| Btrfs   | 702       | 19.96%  |
| Unknown | 112       | 3.18%   |
| Xfs     | 81        | 2.3%    |
| F2fs    | 43        | 1.22%   |
| Overlay | 19        | 0.54%   |
| Zfs     | 17        | 0.48%   |
| Tmpfs   | 4         | 0.11%   |
| Ext2    | 3         | 0.09%   |
| XXXXX   | 2         | 0.06%   |
| XXX4    | 1         | 0.03%   |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2213      | 62.78%  |
| Unknown | 1016      | 28.82%  |
| MBR     | 296       | 8.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3163      | 90.11%  |
| Yes       | 347       | 9.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2604      | 73.75%  |
| Yes       | 927       | 26.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1003      | 28.86%  |
| Dell                   | 556       | 16%     |
| Hewlett-Packard        | 481       | 13.84%  |
| ASUSTek Computer       | 407       | 11.71%  |
| Acer                   | 276       | 7.94%   |
| MSI                    | 106       | 3.05%   |
| Apple                  | 66        | 1.9%    |
| HUAWEI                 | 64        | 1.84%   |
| Samsung Electronics    | 51        | 1.47%   |
| Toshiba                | 47        | 1.35%   |
| Notebook               | 33        | 0.95%   |
| Timi                   | 27        | 0.78%   |
| Google                 | 26        | 0.75%   |
| Sony                   | 23        | 0.66%   |
| TUXEDO                 | 20        | 0.58%   |
| Framework              | 19        | 0.55%   |
| Alienware              | 17        | 0.49%   |
| Fujitsu                | 16        | 0.46%   |
| Razer                  | 14        | 0.4%    |
| Unknown                | 14        | 0.4%    |
| Gigabyte Technology    | 11        | 0.32%   |
| Avell High Performance | 11        | 0.32%   |
| System76               | 10        | 0.29%   |
| Schenker               | 10        | 0.29%   |
| LG Electronics         | 10        | 0.29%   |
| MECHREVO               | 8         | 0.23%   |
| Packard Bell           | 7         | 0.2%    |
| Intel                  | 7         | 0.2%    |
| Medion                 | 6         | 0.17%   |
| GPD                    | 6         | 0.17%   |
| Chuwi                  | 6         | 0.17%   |
| Positivo               | 5         | 0.14%   |
| Monster                | 5         | 0.14%   |
| HONOR                  | 5         | 0.14%   |
| Teclast                | 4         | 0.12%   |
| Star Labs              | 4         | 0.12%   |
| SLIMBOOK               | 4         | 0.12%   |
| Koompi                 | 4         | 0.12%   |
| Intel Client Systems   | 4         | 0.12%   |
| Valve                  | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 35        | 1.01%   |
| Dell XPS 15 9570                | 18        | 0.52%   |
| Framework Laptop                | 16        | 0.46%   |
| HP Notebook                     | 15        | 0.43%   |
| Dell XPS 15 9500                | 14        | 0.4%    |
| Dell XPS 13 9360                | 13        | 0.37%   |
| Dell XPS 13 9380                | 11        | 0.32%   |
| HUAWEI NBLK-WAX9X               | 10        | 0.29%   |
| Dell XPS 13 9310                | 10        | 0.29%   |
| Dell Latitude E6430             | 10        | 0.29%   |
| Dell Inspiron 15 7000 Gaming    | 10        | 0.29%   |
| ASUS ROG Strix G513QY_G513QY    | 10        | 0.29%   |
| HP EliteBook 840 G6             | 9         | 0.26%   |
| Dell XPS 15 7590                | 9         | 0.26%   |
| Dell XPS 13 9370                | 9         | 0.26%   |
| Dell XPS 13 9350                | 9         | 0.26%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 8         | 0.23%   |
| Lenovo IdeaPad 5 14ARE05 81YM   | 8         | 0.23%   |
| HUAWEI BOHK-WAX9X               | 8         | 0.23%   |
| HP Pavilion dv6                 | 8         | 0.23%   |
| HP EliteBook 840 G5             | 8         | 0.23%   |
| Dell Latitude E7450             | 8         | 0.23%   |
| Dell Latitude 5480              | 8         | 0.23%   |
| Dell Inspiron 5570              | 8         | 0.23%   |
| ASUS TUF Gaming FX505DT_FX505DT | 8         | 0.23%   |
| HP Pavilion Notebook            | 7         | 0.2%    |
| HP Laptop 15-da0xxx             | 7         | 0.2%    |
| HP 250 G6 Notebook PC           | 7         | 0.2%    |
| Dell XPS 13 7390                | 7         | 0.2%    |
| Dell Precision 7540             | 7         | 0.2%    |
| Dell G3 3579                    | 7         | 0.2%    |
| Dell G3 3500                    | 7         | 0.2%    |
| Acer Swift SF314-43             | 7         | 0.2%    |
| Acer Nitro AN515-52             | 7         | 0.2%    |
| Acer Nitro AN515-45             | 7         | 0.2%    |
| Acer Aspire E5-571              | 7         | 0.2%    |
| Acer Aspire A515-45             | 7         | 0.2%    |
| Lenovo Y520-15IKBN 80WK         | 6         | 0.17%   |
| Lenovo ThinkPad T480 20L5CTO1WW | 6         | 0.17%   |
| Lenovo Legion 5 15ARH05 82B5    | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 600       | 17.26%  |
| Lenovo IdeaPad     | 196       | 5.64%   |
| Acer Aspire        | 160       | 4.6%    |
| Dell Latitude      | 147       | 4.23%   |
| Dell Inspiron      | 146       | 4.2%    |
| Dell XPS           | 144       | 4.14%   |
| HP Pavilion        | 100       | 2.88%   |
| HP EliteBook       | 99        | 2.85%   |
| HP Laptop          | 72        | 2.07%   |
| Lenovo Legion      | 63        | 1.81%   |
| ASUS ROG           | 63        | 1.81%   |
| ASUS VivoBook      | 59        | 1.7%    |
| HP ProBook         | 57        | 1.64%   |
| Dell Precision     | 49        | 1.41%   |
| Acer Nitro         | 44        | 1.27%   |
| Toshiba Satellite  | 38        | 1.09%   |
| Acer Swift         | 37        | 1.06%   |
| ASUS ASUS          | 36        | 1.04%   |
| Unknown            | 35        | 1.01%   |
| ASUS TUF           | 32        | 0.92%   |
| ASUS ZenBook       | 31        | 0.89%   |
| Lenovo ThinkBook   | 29        | 0.83%   |
| Dell Vostro        | 29        | 0.83%   |
| HP OMEN            | 25        | 0.72%   |
| HP ENVY            | 24        | 0.69%   |
| Lenovo Yoga        | 20        | 0.58%   |
| Framework Laptop   | 19        | 0.55%   |
| Dell G3            | 16        | 0.46%   |
| MSI Modern         | 15        | 0.43%   |
| HP Notebook        | 15        | 0.43%   |
| HP 250             | 15        | 0.43%   |
| Fujitsu LIFEBOOK   | 15        | 0.43%   |
| Razer Blade        | 14        | 0.4%    |
| HP ZBook           | 13        | 0.37%   |
| HUAWEI NBLK-WAX9X  | 10        | 0.29%   |
| Acer Predator      | 10        | 0.29%   |
| HP 255             | 9         | 0.26%   |
| ASUS Strix         | 9         | 0.26%   |
| Apple MacBookPro11 | 9         | 0.26%   |
| Timi RedmiBook     | 8         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 464       | 13.35%  |
| 2020    | 457       | 13.15%  |
| 2021    | 414       | 11.91%  |
| 2018    | 404       | 11.62%  |
| 2017    | 261       | 7.51%   |
| 2015    | 198       | 5.7%    |
| 2016    | 196       | 5.64%   |
| 2012    | 189       | 5.44%   |
| 2013    | 173       | 4.98%   |
| 2022    | 170       | 4.89%   |
| 2014    | 161       | 4.63%   |
| 2011    | 151       | 4.34%   |
| 2010    | 98        | 2.82%   |
| 2008    | 60        | 1.73%   |
| 2009    | 43        | 1.24%   |
| 2023    | 20        | 0.58%   |
| 2007    | 12        | 0.35%   |
| 2006    | 4         | 0.12%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3476      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3435      | 98.62%  |
| Enabled  | 48        | 1.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3430      | 98.68%  |
| Yes  | 46        | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 909       | 25.85%  |
| 16.01-24.0  | 848       | 24.11%  |
| 8.01-16.0   | 792       | 22.52%  |
| 3.01-4.0    | 386       | 10.98%  |
| 32.01-64.0  | 362       | 10.29%  |
| 24.01-32.0  | 68        | 1.93%   |
| 64.01-256.0 | 66        | 1.88%   |
| 1.01-2.0    | 53        | 1.51%   |
| 2.01-3.0    | 28        | 0.8%    |
| 0.51-1.0    | 5         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 969       | 25.2%   |
| 1.01-2.0   | 914       | 23.76%  |
| 4.01-8.0   | 820       | 21.32%  |
| 3.01-4.0   | 673       | 17.5%   |
| 8.01-16.0  | 250       | 6.5%    |
| 0.51-1.0   | 150       | 3.9%    |
| 0.01-0.5   | 31        | 0.81%   |
| 16.01-24.0 | 24        | 0.62%   |
| 24.01-32.0 | 13        | 0.34%   |
| 32.01-64.0 | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2428      | 68.67%  |
| 2      | 948       | 26.81%  |
| 3      | 130       | 3.68%   |
| 0      | 14        | 0.4%    |
| 4      | 12        | 0.34%   |
| 5      | 3         | 0.08%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2805      | 80.35%  |
| Yes       | 686       | 19.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2672      | 76.5%   |
| No        | 821       | 23.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3447      | 99.08%  |
| No        | 32        | 0.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3010      | 85.78%  |
| No        | 499       | 14.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 594       | 16.97%  |
| Germany     | 299       | 8.54%   |
| Russia      | 210       | 6%      |
| Italy       | 208       | 5.94%   |
| Brazil      | 192       | 5.48%   |
| France      | 168       | 4.8%    |
| India       | 140       | 4%      |
| UK          | 116       | 3.31%   |
| Poland      | 99        | 2.83%   |
| Canada      | 89        | 2.54%   |
| Spain       | 77        | 2.2%    |
| China       | 69        | 1.97%   |
| Netherlands | 68        | 1.94%   |
| Turkey      | 54        | 1.54%   |
| Australia   | 51        | 1.46%   |
| Austria     | 45        | 1.29%   |
| Ukraine     | 41        | 1.17%   |
| Indonesia   | 41        | 1.17%   |
| Sweden      | 40        | 1.14%   |
| Portugal    | 34        | 0.97%   |
| Mexico      | 34        | 0.97%   |
| Romania     | 33        | 0.94%   |
| Czechia     | 33        | 0.94%   |
| Belgium     | 32        | 0.91%   |
| Argentina   | 29        | 0.83%   |
| Vietnam     | 28        | 0.8%    |
| Switzerland | 27        | 0.77%   |
| Hungary     | 25        | 0.71%   |
| Iran        | 24        | 0.69%   |
| Japan       | 23        | 0.66%   |
| Finland     | 23        | 0.66%   |
| Colombia    | 23        | 0.66%   |
| New Zealand | 22        | 0.63%   |
| Denmark     | 21        | 0.6%    |
| Greece      | 20        | 0.57%   |
| Chile       | 18        | 0.51%   |
| Belarus     | 18        | 0.51%   |
| Taiwan      | 17        | 0.49%   |
| Peru        | 17        | 0.49%   |
| Norway      | 17        | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 60        | 1.61%   |
| Paris             | 36        | 0.97%   |
| Milan             | 36        | 0.97%   |
| Sao Paulo         | 32        | 0.86%   |
| St Petersburg     | 31        | 0.83%   |
| Warsaw            | 28        | 0.75%   |
| Berlin            | 28        | 0.75%   |
| Munich            | 26        | 0.7%    |
| Vienna            | 23        | 0.62%   |
| Los Angeles       | 22        | 0.59%   |
| Melbourne         | 21        | 0.56%   |
| Istanbul          | 20        | 0.54%   |
| Bengaluru         | 20        | 0.54%   |
| Valencia          | 19        | 0.51%   |
| Amsterdam         | 18        | 0.48%   |
| Prague            | 16        | 0.43%   |
| Kyiv              | 16        | 0.43%   |
| Sydney            | 15        | 0.4%    |
| Montreal          | 15        | 0.4%    |
| Frankfurt am Main | 15        | 0.4%    |
| Tehran            | 14        | 0.38%   |
| Helsinki          | 14        | 0.38%   |
| Budapest          | 14        | 0.38%   |
| Rome              | 13        | 0.35%   |
| Phoenix           | 13        | 0.35%   |
| Mexico City       | 13        | 0.35%   |
| Lima              | 13        | 0.35%   |
| Jakarta           | 13        | 0.35%   |
| Hamburg           | 13        | 0.35%   |
| Bogotá           | 13        | 0.35%   |
| New York          | 12        | 0.32%   |
| Curitiba          | 12        | 0.32%   |
| Cologne           | 12        | 0.32%   |
| Turin             | 11        | 0.29%   |
| Singapore         | 11        | 0.29%   |
| Madrid            | 11        | 0.29%   |
| Buenos Aires      | 11        | 0.29%   |
| Beijing           | 11        | 0.29%   |
| Athens            | 11        | 0.29%   |
| Seattle           | 10        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 975       | 1304   | 21.36%  |
| WDC                            | 457       | 559    | 10.01%  |
| Sandisk                        | 383       | 455    | 8.39%   |
| Seagate                        | 378       | 460    | 8.28%   |
| Toshiba                        | 307       | 356    | 6.73%   |
| SK hynix                       | 259       | 314    | 5.67%   |
| Kingston                       | 218       | 272    | 4.78%   |
| Unknown                        | 191       | 227    | 4.18%   |
| Intel                          | 170       | 221    | 3.72%   |
| Micron Technology              | 156       | 190    | 3.42%   |
| Crucial                        | 127       | 180    | 2.78%   |
| HGST                           | 118       | 126    | 2.58%   |
| Hitachi                        | 65        | 66     | 1.42%   |
| A-DATA Technology              | 61        | 85     | 1.34%   |
| KIOXIA                         | 40        | 46     | 0.88%   |
| Apple                          | 40        | 51     | 0.88%   |
| Phison Electronics             | 36        | 41     | 0.79%   |
| Phison                         | 31        | 36     | 0.68%   |
| LITEON                         | 28        | 29     | 0.61%   |
| Transcend                      | 26        | 28     | 0.57%   |
| Micron/Crucial Technology      | 23        | 25     | 0.5%    |
| China                          | 23        | 28     | 0.5%    |
| Silicon Motion                 | 22        | 23     | 0.48%   |
| Kingston Technology Company    | 22        | 22     | 0.48%   |
| SPCC                           | 19        | 21     | 0.42%   |
| Lenovo                         | 17        | 21     | 0.37%   |
| PNY                            | 16        | 19     | 0.35%   |
| JMicron Technology             | 15        | 16     | 0.33%   |
| ADATA Technology               | 14        | 16     | 0.31%   |
| LITEONIT                       | 12        | 12     | 0.26%   |
| KingSpec                       | 11        | 12     | 0.24%   |
| GOODRAM                        | 11        | 11     | 0.24%   |
| OCZ                            | 10        | 10     | 0.22%   |
| Patriot                        | 9         | 10     | 0.2%    |
| Plextor                        | 8         | 8      | 0.18%   |
| Lite-On                        | 8         | 10     | 0.18%   |
| Intenso                        | 8         | 9      | 0.18%   |
| Yangtze Memory Technologies    | 7         | 7      | 0.15%   |
| Union Memory (Shenzhen)        | 7         | 7      | 0.15%   |
| Solid State Storage Technology | 7         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 106       | 2.21%   |
| Seagate ST1000LM035-1RK172 1TB                      | 84        | 1.76%   |
| Samsung NVMe SSD Drive 512GB                        | 63        | 1.32%   |
| HGST HTS721010A9E630 1TB                            | 47        | 0.98%   |
| SanDisk NVMe SSD Drive 512GB                        | 46        | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 46        | 0.96%   |
| Toshiba MQ04ABF100 1TB                              | 39        | 0.81%   |
| SK hynix NVMe SSD Drive 512GB                       | 39        | 0.81%   |
| Toshiba MQ01ABD100 1TB                              | 37        | 0.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 37        | 0.77%   |
| Unknown MMC Card  32GB                              | 36        | 0.75%   |
| Samsung SSD 860 EVO 500GB                           | 36        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 36        | 0.75%   |
| Samsung NVMe SSD Drive 256GB                        | 35        | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 34        | 0.71%   |
| Unknown MMC Card  64GB                              | 28        | 0.59%   |
| Samsung SSD 850 EVO 500GB                           | 28        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 26        | 0.54%   |
| Seagate ST1000LM048-2E7172 1TB                      | 25        | 0.52%   |
| SanDisk NVMe SSD Drive 256GB                        | 24        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                        | 24        | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 23        | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB                      | 22        | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                          | 21        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB                        | 21        | 0.44%   |
| Toshiba NVMe SSD Drive 512GB                        | 20        | 0.42%   |
| Seagate ST1000LX015-1U7172 1TB                      | 20        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                      | 20        | 0.42%   |
| Samsung NVMe SSD Drive 1TB                          | 20        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.42%   |
| Intel SSDPEKNU512GZ 512GB                           | 20        | 0.42%   |
| HGST HTS541010A9E680 1TB                            | 20        | 0.42%   |
| Unknown MMC Card  128GB                             | 19        | 0.4%    |
| Toshiba MQ01ABF050 500GB                            | 19        | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                     | 19        | 0.4%    |
| Kingston SA400S37480G 480GB SSD                     | 19        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                         | 19        | 0.4%    |
| Samsung SSD 860 EVO 1TB                             | 18        | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 17        | 0.36%   |
| Samsung NVMe SSD Drive 500GB                        | 17        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 370       | 450    | 36.27%  |
| WDC                 | 259       | 297    | 25.39%  |
| Toshiba             | 167       | 188    | 16.37%  |
| HGST                | 118       | 126    | 11.57%  |
| Hitachi             | 65        | 66     | 6.37%   |
| Unknown             | 10        | 13     | 0.98%   |
| Samsung Electronics | 10        | 10     | 0.98%   |
| Fujitsu             | 4         | 4      | 0.39%   |
| HGST HTS            | 3         | 3      | 0.29%   |
| Apple               | 3         | 3      | 0.29%   |
| SAGE                | 2         | 2      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| SSK                 | 1         | 1      | 0.1%    |
| Pioneer             | 1         | 1      | 0.1%    |
| PHD 3.0             | 1         | 1      | 0.1%    |
| NeoTech             | 1         | 1      | 0.1%    |
| Maxone              | 1         | 1      | 0.1%    |
| Generic-            | 1         | 2      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |
| ACASIS              | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 341       | 425    | 25.7%   |
| SanDisk             | 150       | 170    | 11.3%   |
| Kingston            | 143       | 176    | 10.78%  |
| Crucial             | 113       | 156    | 8.52%   |
| WDC                 | 84        | 108    | 6.33%   |
| A-DATA Technology   | 38        | 56     | 2.86%   |
| Toshiba             | 36        | 44     | 2.71%   |
| SK hynix            | 35        | 41     | 2.64%   |
| Intel               | 34        | 38     | 2.56%   |
| Micron Technology   | 33        | 40     | 2.49%   |
| Transcend           | 25        | 27     | 1.88%   |
| LITEON              | 25        | 26     | 1.88%   |
| Apple               | 24        | 25     | 1.81%   |
| China               | 23        | 28     | 1.73%   |
| SPCC                | 15        | 16     | 1.13%   |
| PNY                 | 15        | 18     | 1.13%   |
| LITEONIT            | 12        | 12     | 0.9%    |
| KingSpec            | 11        | 12     | 0.83%   |
| OCZ                 | 10        | 10     | 0.75%   |
| GOODRAM             | 10        | 10     | 0.75%   |
| Patriot             | 9         | 10     | 0.68%   |
| Plextor             | 8         | 8      | 0.6%    |
| Intenso             | 8         | 9      | 0.6%    |
| FORESEE             | 6         | 9      | 0.45%   |
| Lexar               | 5         | 10     | 0.38%   |
| Gigabyte Technology | 5         | 5      | 0.38%   |
| External            | 5         | 6      | 0.38%   |
| ASMT                | 5         | 5      | 0.38%   |
| TO Exter            | 4         | 9      | 0.3%    |
| Mushkin             | 4         | 4      | 0.3%    |
| Hewlett-Packard     | 4         | 5      | 0.3%    |
| Unknown             | 3         | 3      | 0.23%   |
| Team                | 3         | 3      | 0.23%   |
| Netac               | 3         | 3      | 0.23%   |
| BIWIN               | 3         | 3      | 0.23%   |
| BHT                 | 3         | 5      | 0.23%   |
| Apacer              | 3         | 3      | 0.23%   |
| Unknown             | 3         | 3      | 0.23%   |
| ZHITAI              | 2         | 3      | 0.15%   |
| Verbatim            | 2         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1841      | 2567   | 43.05%  |
| SSD     | 1221      | 1616   | 28.55%  |
| HDD     | 990       | 1172   | 23.15%  |
| MMC     | 181       | 213    | 4.23%   |
| Unknown | 43        | 46     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1883      | 2672   | 46.59%  |
| NVMe | 1833      | 2546   | 45.35%  |
| MMC  | 181       | 213    | 4.48%   |
| SAS  | 145       | 183    | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1316      | 1741   | 60.31%  |
| 0.51-1.0   | 774       | 932    | 35.47%  |
| 1.01-2.0   | 80        | 101    | 3.67%   |
| 4.01-10.0  | 6         | 8      | 0.27%   |
| 3.01-4.0   | 4         | 4      | 0.18%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |
| 10.01-20.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 976       | 26.98%  |
| 101-250        | 948       | 26.2%   |
| 501-1000       | 687       | 18.99%  |
| 1001-2000      | 405       | 11.19%  |
| 51-100         | 161       | 4.45%   |
| More than 3000 | 132       | 3.65%   |
| 2001-3000      | 110       | 3.04%   |
| Unknown        | 86        | 2.38%   |
| 21-50          | 60        | 1.66%   |
| 1-20           | 53        | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 829       | 21.92%  |
| 101-250        | 724       | 19.14%  |
| 21-50          | 631       | 16.68%  |
| 51-100         | 548       | 14.49%  |
| 251-500        | 496       | 13.11%  |
| 501-1000       | 300       | 7.93%   |
| 1001-2000      | 106       | 2.8%    |
| Unknown        | 86        | 2.27%   |
| More than 3000 | 32        | 0.85%   |
| 2001-3000      | 29        | 0.77%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                                  | 10        | 10     | 4.39%   |
| HGST HTS721010A9E630 1TB                                        | 10        | 10     | 4.39%   |
| HGST HTS541010A9E680 1TB                                        | 6         | 6      | 2.63%   |
| Seagate ST9500325AS 500GB                                       | 5         | 5      | 2.19%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 2.19%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 1.75%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 4         | 5      | 1.75%   |
| HGST HTS725050A7E630 500GB                                      | 4         | 4      | 1.75%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 3         | 3      | 1.32%   |
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 3      | 1.32%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 3         | 3      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 3      | 1.32%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 3         | 3      | 1.32%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 4      | 1.32%   |
| Hitachi HTS545025B9A300 250GB                                   | 3         | 3      | 1.32%   |
| Toshiba MQ01ABD100 1TB                                          | 2         | 2      | 0.88%   |
| Toshiba MK3276GSX 320GB                                         | 2         | 2      | 0.88%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 2         | 2      | 0.88%   |
| Seagate ST9320325AS 320GB                                       | 2         | 2      | 0.88%   |
| Seagate ST9250315AS 250GB                                       | 2         | 2      | 0.88%   |
| Seagate ST500LT012-9WS142 500GB                                 | 2         | 2      | 0.88%   |
| Seagate ST500LM012 HN-M500MBB 500GB                             | 2         | 2      | 0.88%   |
| Seagate ST500LM000-SSHD-8GB                                     | 2         | 2      | 0.88%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 2         | 2      | 0.88%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 2         | 2      | 0.88%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 2         | 2      | 0.88%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                               | 2         | 2      | 0.88%   |
| Samsung Electronics SSD 970 EVO 2TB                             | 2         | 2      | 0.88%   |
| LITEON CV8-8E128-HP 128GB SSD                                   | 2         | 2      | 0.88%   |
| Intel SSDSC2BF240A4L 240GB                                      | 2         | 2      | 0.88%   |
| Hitachi HTS723232A7A364 320GB                                   | 2         | 2      | 0.88%   |
| Hitachi HTS545050A7E380 500GB                                   | 2         | 3      | 0.88%   |
| Hitachi HTS541680J9SA00 80GB                                    | 2         | 2      | 0.88%   |
| Hitachi HTS541616J9SA00 160GB                                   | 2         | 2      | 0.88%   |
| HGST HTS545050A7E380 500GB                                      | 2         | 2      | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 0.44%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                  | 1         | 1      | 0.44%   |
| WDC WD7500BPKT-00PK4T0 752GB                                    | 1         | 1      | 0.44%   |
| WDC WD6400BEVT-22A0RT0 640GB                                    | 1         | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 67     | 27.63%  |
| HGST                | 30        | 31     | 13.16%  |
| WDC                 | 26        | 28     | 11.4%   |
| Toshiba             | 23        | 26     | 10.09%  |
| Hitachi             | 20        | 21     | 8.77%   |
| Samsung Electronics | 14        | 20     | 6.14%   |
| SK hynix            | 12        | 13     | 5.26%   |
| Intel               | 7         | 8      | 3.07%   |
| SanDisk             | 6         | 7      | 2.63%   |
| Kingston            | 5         | 5      | 2.19%   |
| Crucial             | 5         | 5      | 2.19%   |
| Micron Technology   | 4         | 5      | 1.75%   |
| LITEON              | 3         | 3      | 1.32%   |
| China               | 2         | 2      | 0.88%   |
| ASMT                | 2         | 2      | 0.88%   |
| A-DATA Technology   | 2         | 2      | 0.88%   |
| VNYEZ               | 1         | 1      | 0.44%   |
| OCZ                 | 1         | 1      | 0.44%   |
| KingSpec            | 1         | 1      | 0.44%   |
| Apple               | 1         | 1      | 0.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 63        | 67     | 40.13%  |
| HGST    | 30        | 31     | 19.11%  |
| WDC     | 24        | 26     | 15.29%  |
| Hitachi | 20        | 21     | 12.74%  |
| Toshiba | 18        | 21     | 11.46%  |
| ASMT    | 1         | 1      | 0.64%   |
| Apple   | 1         | 1      | 0.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 156       | 168    | 68.72%  |
| SSD  | 54        | 59     | 23.79%  |
| NVMe | 17        | 22     | 7.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 20%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 20%     |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 20%     |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 20%     |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Phison              | 1         | 1      | 20%     |
| Kingston            | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1784      | 2658   | 47.17%  |
| Works    | 1770      | 2701   | 46.8%   |
| Malfunc  | 223       | 249    | 5.9%    |
| Failed   | 5         | 6      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2109      | 47.81%  |
| Samsung Electronics              | 662       | 15.01%  |
| AMD                              | 424       | 9.61%   |
| SanDisk                          | 329       | 7.46%   |
| SK hynix                         | 221       | 5.01%   |
| Micron Technology                | 124       | 2.81%   |
| Toshiba America Info Systems     | 104       | 2.36%   |
| Kingston Technology Company      | 95        | 2.15%   |
| Phison Electronics               | 75        | 1.7%    |
| KIOXIA                           | 41        | 0.93%   |
| Micron/Crucial Technology        | 38        | 0.86%   |
| ADATA Technology                 | 33        | 0.75%   |
| Silicon Motion                   | 29        | 0.66%   |
| Union Memory (Shenzhen)          | 18        | 0.41%   |
| Solid State Storage Technology   | 16        | 0.36%   |
| Lenovo                           | 15        | 0.34%   |
| Apple                            | 13        | 0.29%   |
| Realtek Semiconductor            | 12        | 0.27%   |
| Lite-On Technology               | 11        | 0.25%   |
| Yangtze Memory Technologies      | 9         | 0.2%    |
| MAXIO Technology (Hangzhou)      | 7         | 0.16%   |
| Nvidia                           | 6         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 3         | 0.07%   |
| Marvell Technology Group         | 3         | 0.07%   |
| Biwin Storage Technology         | 3         | 0.07%   |
| Netac Technology                 | 2         | 0.05%   |
| INNOGRIT                         | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Transcend                        | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 403       | 8.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 367       | 8.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 301       | 6.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 197       | 4.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 195       | 4.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 161       | 3.52%   |
| Samsung NVMe SSD Controller 980                                                | 145       | 3.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 124       | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 122       | 2.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 114       | 2.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 111       | 2.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 103       | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 102       | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 92        | 2.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 88        | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 74        | 1.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 68        | 1.49%   |
| Intel SSD 660P Series                                                          | 65        | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 62        | 1.35%   |
| Micron NVMe Storage Controller                                                 | 62        | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 59        | 1.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 56        | 1.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 48        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 42        | 0.92%   |
| Phison E12 NVMe Controller                                                     | 40        | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 38        | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 38        | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 36        | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 34        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 33        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 32        | 0.7%    |
| Micron 2200S NVMe SSD                                                          | 32        | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 32        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 31        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 30        | 0.66%   |
| Intel Non-Volatile memory controller                                           | 30        | 0.66%   |
| SK hynix BC511 NVMe SSD                                                        | 29        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 28        | 0.61%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 26        | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                        | 25        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2177      | 49.74%  |
| NVMe | 1837      | 41.97%  |
| RAID | 312       | 7.13%   |
| IDE  | 51        | 1.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2700      | 77.68%  |
| AMD    | 776       | 22.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 79        | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 77        | 2.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 76        | 2.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 73        | 2.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 71        | 2.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 71        | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 68        | 1.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 66        | 1.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 61        | 1.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 53        | 1.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 47        | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 46        | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 45        | 1.29%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 42        | 1.21%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 42        | 1.21%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 42        | 1.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 41        | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 41        | 1.18%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 39        | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 37        | 1.06%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 36        | 1.03%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 35        | 1.01%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 33        | 0.95%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 0.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 27        | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 27        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 0.75%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.75%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 25        | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 25        | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 24        | 0.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 24        | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.69%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 23        | 0.66%   |
| Intel 12th Gen Core i7-12700H                 | 23        | 0.66%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 23        | 0.66%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 21        | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 21        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 968       | 27.82%  |
| Intel Core i5           | 851       | 24.46%  |
| Other                   | 343       | 9.86%   |
| AMD Ryzen 5             | 247       | 7.1%    |
| AMD Ryzen 7             | 241       | 6.93%   |
| Intel Core i3           | 192       | 5.52%   |
| Intel Celeron           | 102       | 2.93%   |
| Intel Core 2 Duo        | 81        | 2.33%   |
| AMD Ryzen 7 PRO         | 69        | 1.98%   |
| AMD Ryzen 9             | 55        | 1.58%   |
| Intel Pentium           | 49        | 1.41%   |
| Intel Atom              | 37        | 1.06%   |
| AMD Ryzen 3             | 34        | 0.98%   |
| Intel Core i9           | 30        | 0.86%   |
| AMD Ryzen 5 PRO         | 22        | 0.63%   |
| AMD A6                  | 16        | 0.46%   |
| Intel Pentium Silver    | 13        | 0.37%   |
| AMD A4                  | 13        | 0.37%   |
| AMD A10                 | 13        | 0.37%   |
| Intel Xeon              | 12        | 0.34%   |
| AMD A8                  | 10        | 0.29%   |
| AMD E2                  | 9         | 0.26%   |
| Intel Pentium Dual-Core | 7         | 0.2%    |
| Intel Genuine           | 6         | 0.17%   |
| Intel Core m3           | 6         | 0.17%   |
| AMD E1                  | 6         | 0.17%   |
| AMD E                   | 5         | 0.14%   |
| Intel Core 2            | 4         | 0.11%   |
| AMD Athlon              | 4         | 0.11%   |
| AMD A12                 | 4         | 0.11%   |
| Intel Celeron Dual-Core | 3         | 0.09%   |
| Intel Pentium Dual      | 2         | 0.06%   |
| Intel Core m7           | 2         | 0.06%   |
| Intel Core m5           | 2         | 0.06%   |
| Intel Core M            | 2         | 0.06%   |
| AMD Turion Neo X2       | 2         | 0.06%   |
| AMD Phenom II           | 2         | 0.06%   |
| AMD Athlon X2           | 2         | 0.06%   |
| Intel Pentium Gold      | 1         | 0.03%   |
| Intel Core 2 Solo       | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1320      | 37.94%  |
| 2      | 1253      | 36.02%  |
| 8      | 409       | 11.76%  |
| 6      | 387       | 11.12%  |
| 14     | 33        | 0.95%   |
| 12     | 31        | 0.89%   |
| 1      | 22        | 0.63%   |
| 10     | 18        | 0.52%   |
| 16     | 3         | 0.09%   |
| 24     | 1         | 0.03%   |
| 5      | 1         | 0.03%   |
| 3      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3476      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2982      | 85.69%  |
| 1      | 498       | 14.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3415      | 98.19%  |
| Unknown        | 60        | 1.73%   |
| 32-bit         | 3         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1284      | 35.51%  |
| 0x906ea    | 137       | 3.79%   |
| 0x806ea    | 137       | 3.79%   |
| 0x306a9    | 118       | 3.26%   |
| 0x806ec    | 116       | 3.21%   |
| 0x806c1    | 111       | 3.07%   |
| 0x206a7    | 104       | 2.88%   |
| 0x406e3    | 99        | 2.74%   |
| 0x0a50000c | 94        | 2.6%    |
| 0x306d4    | 88        | 2.43%   |
| 0x40651    | 86        | 2.38%   |
| 0x906e9    | 84        | 2.32%   |
| 0x806e9    | 78        | 2.16%   |
| 0x08108102 | 73        | 2.02%   |
| 0x08600106 | 70        | 1.94%   |
| 0x306c3    | 66        | 1.83%   |
| 0xa0652    | 61        | 1.69%   |
| 0x08108109 | 53        | 1.47%   |
| 0x20655    | 46        | 1.27%   |
| 0x506e3    | 44        | 1.22%   |
| 0x08600104 | 42        | 1.16%   |
| 0x806eb    | 40        | 1.11%   |
| 0x08600103 | 39        | 1.08%   |
| 0x1067a    | 34        | 0.94%   |
| 0x08608103 | 34        | 0.94%   |
| 0x0a404102 | 26        | 0.72%   |
| 0x906a3    | 24        | 0.66%   |
| 0x706e5    | 24        | 0.66%   |
| 0x0810100b | 24        | 0.66%   |
| 0x08608102 | 23        | 0.64%   |
| 0x806d1    | 21        | 0.58%   |
| 0x406c4    | 21        | 0.58%   |
| 0x30678    | 20        | 0.55%   |
| 0x10676    | 19        | 0.53%   |
| 0x906ed    | 18        | 0.5%    |
| 0x706a1    | 16        | 0.44%   |
| 0x506c9    | 16        | 0.44%   |
| 0x20652    | 15        | 0.41%   |
| 0x06006705 | 13        | 0.36%   |
| 0x0a404101 | 11        | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 933       | 26.82%  |
| Haswell          | 230       | 6.61%   |
| Skylake          | 227       | 6.52%   |
| TigerLake        | 195       | 5.61%   |
| IvyBridge        | 192       | 5.52%   |
| Zen 2            | 191       | 5.49%   |
| Unknown          | 186       | 5.35%   |
| Zen+             | 159       | 4.57%   |
| SandyBridge      | 155       | 4.46%   |
| Zen 3            | 148       | 4.25%   |
| Broadwell        | 132       | 3.79%   |
| CometLake        | 115       | 3.31%   |
| Penryn           | 81        | 2.33%   |
| Westmere         | 76        | 2.18%   |
| Silvermont       | 76        | 2.18%   |
| IceLake          | 65        | 1.87%   |
| Alderlake Hybrid | 60        | 1.72%   |
| Zen              | 46        | 1.32%   |
| Goldmont plus    | 38        | 1.09%   |
| Excavator        | 34        | 0.98%   |
| Core             | 24        | 0.69%   |
| Goldmont         | 21        | 0.6%    |
| Bobcat           | 15        | 0.43%   |
| Bonnell          | 14        | 0.4%    |
| Puma             | 11        | 0.32%   |
| Nehalem          | 9         | 0.26%   |
| Piledriver       | 8         | 0.23%   |
| Jaguar           | 8         | 0.23%   |
| K10 Llano        | 7         | 0.2%    |
| K10              | 7         | 0.2%    |
| Tremont          | 6         | 0.17%   |
| Steamroller      | 3         | 0.09%   |
| K8 Hammer        | 3         | 0.09%   |
| P6               | 2         | 0.06%   |
| K8 & K10 hybrid  | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2530      | 53.6%   |
| Nvidia                           | 1238      | 26.23%  |
| AMD                              | 948       | 20.08%  |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 211       | 4.39%   |
| Intel UHD Graphics 620                                                                   | 208       | 4.33%   |
| AMD Renoir                                                                               | 183       | 3.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 182       | 3.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 175       | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 161       | 3.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 154       | 3.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 139       | 2.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 130       | 2.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 129       | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 126       | 2.62%   |
| Intel HD Graphics 620                                                                    | 119       | 2.48%   |
| Intel HD Graphics 5500                                                                   | 112       | 2.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 102       | 2.12%   |
| Intel HD Graphics 630                                                                    | 97        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 94        | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 80        | 1.67%   |
| AMD Lucienne                                                                             | 78        | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 76        | 1.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 74        | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 63        | 1.31%   |
| Intel HD Graphics 530                                                                    | 60        | 1.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 55        | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 52        | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 52        | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 1.04%   |
| AMD Rembrandt [Radeon 680M]                                                              | 49        | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 48        | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 46        | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 46        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 41        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 40        | 0.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 38        | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 37        | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 0.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 33        | 0.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 33        | 0.69%   |
| Nvidia TU117M                                                                            | 31        | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 28        | 0.58%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1447      | 41.49%  |
| Intel + Nvidia           | 939       | 26.92%  |
| 1 x AMD                  | 588       | 16.86%  |
| AMD + Nvidia             | 160       | 4.59%   |
| 1 x Nvidia               | 138       | 3.96%   |
| Intel + AMD              | 133       | 3.81%   |
| 2 x AMD                  | 66        | 1.89%   |
| 2 x Intel                | 6         | 0.17%   |
| Other                    | 3         | 0.09%   |
| 1 x SiS                  | 3         | 0.09%   |
| Intel + 2 x Nvidia       | 2         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.06%   |
| 2 x Nvidia               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2741      | 78.14%  |
| Proprietary | 757       | 21.58%  |
| Unknown     | 10        | 0.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2434      | 68.12%  |
| 0.01-0.5   | 361       | 10.1%   |
| 1.01-2.0   | 301       | 8.42%   |
| 3.01-4.0   | 184       | 5.15%   |
| 0.51-1.0   | 135       | 3.78%   |
| 7.01-8.0   | 69        | 1.93%   |
| 5.01-6.0   | 67        | 1.88%   |
| 2.01-3.0   | 12        | 0.34%   |
| 8.01-16.0  | 10        | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 794       | 18.82%  |
| BOE                     | 618       | 14.64%  |
| Chimei Innolux          | 573       | 13.58%  |
| LG Display              | 552       | 13.08%  |
| Samsung Electronics     | 350       | 8.29%   |
| Sharp                   | 185       | 4.38%   |
| Dell                    | 147       | 3.48%   |
| PANDA                   | 109       | 2.58%   |
| Goldstar                | 101       | 2.39%   |
| Lenovo                  | 86        | 2.04%   |
| Apple                   | 68        | 1.61%   |
| Hewlett-Packard         | 62        | 1.47%   |
| AOC                     | 48        | 1.14%   |
| Acer                    | 44        | 1.04%   |
| InfoVision              | 43        | 1.02%   |
| BenQ                    | 43        | 1.02%   |
| CSO                     | 38        | 0.9%    |
| Philips                 | 34        | 0.81%   |
| Chi Mei Optoelectronics | 29        | 0.69%   |
| Ancor Communications    | 28        | 0.66%   |
| Iiyama                  | 22        | 0.52%   |
| ASUSTek Computer        | 16        | 0.38%   |
| Sony                    | 15        | 0.36%   |
| TMX                     | 14        | 0.33%   |
| ViewSonic               | 13        | 0.31%   |
| JDI                     | 9         | 0.21%   |
| CPT                     | 9         | 0.21%   |
| NEC Computers           | 8         | 0.19%   |
| Toshiba                 | 7         | 0.17%   |
| Panasonic               | 7         | 0.17%   |
| MSI                     | 7         | 0.17%   |
| Eizo                    | 7         | 0.17%   |
| BOE Technology Group    | 7         | 0.17%   |
| LG Philips              | 6         | 0.14%   |
| Pixio                   | 5         | 0.12%   |
| LGD                     | 5         | 0.12%   |
| InnoLux Display         | 5         | 0.12%   |
| HannStar                | 5         | 0.12%   |
| Mi                      | 4         | 0.09%   |
| KDC                     | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 45        | 1.05%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 34        | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 31        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 27        | 0.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 27        | 0.63%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 19        | 0.45%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 19        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 18        | 0.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch         | 17        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 17        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 17        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 15        | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.35%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 15        | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 14        | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 14        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 14        | 0.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 14        | 0.33%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 13        | 0.3%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.28%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 11        | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 11        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 11        | 0.26%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 10        | 0.23%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch  | 10        | 0.23%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 10        | 0.23%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 10        | 0.23%   |
| LG Display LCD Monitor LGD058B 2560x1440 309x174mm 14.0-inch         | 10        | 0.23%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 10        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2043      | 52.17%  |
| 1366x768 (WXGA)    | 758       | 19.36%  |
| 3840x2160 (4K)     | 200       | 5.11%   |
| 2560x1440 (QHD)    | 165       | 4.21%   |
| 1600x900 (HD+)     | 136       | 3.47%   |
| 1920x1200 (WUXGA)  | 97        | 2.48%   |
| 2560x1600          | 59        | 1.51%   |
| 1280x800 (WXGA)    | 56        | 1.43%   |
| 2880x1800          | 43        | 1.1%    |
| 1440x900 (WXGA+)   | 39        | 1%      |
| 3840x2400          | 33        | 0.84%   |
| 1680x1050 (WSXGA+) | 33        | 0.84%   |
| 3440x1440          | 32        | 0.82%   |
| 2560x1080          | 23        | 0.59%   |
| 3200x1800 (QHD+)   | 20        | 0.51%   |
| 2256x1504          | 19        | 0.49%   |
| 1280x1024 (SXGA)   | 18        | 0.46%   |
| 2160x1440          | 16        | 0.41%   |
| 1360x768           | 15        | 0.38%   |
| 3072x1920          | 10        | 0.26%   |
| 3840x1600          | 9         | 0.23%   |
| 3000x2000          | 9         | 0.23%   |
| Unknown            | 9         | 0.23%   |
| 2240x1400          | 7         | 0.18%   |
| 1024x600           | 7         | 0.18%   |
| 3200x2000          | 6         | 0.15%   |
| 1920x540           | 6         | 0.15%   |
| 2520x1680          | 5         | 0.13%   |
| 1280x720 (HD)      | 5         | 0.13%   |
| 800x1280           | 3         | 0.08%   |
| 3840x1080          | 3         | 0.08%   |
| 3456x2160          | 3         | 0.08%   |
| 1680x945           | 3         | 0.08%   |
| 1600x1200          | 3         | 0.08%   |
| 3840x1100          | 2         | 0.05%   |
| 1920x550           | 2         | 0.05%   |
| 1920x1280          | 2         | 0.05%   |
| 1400x1050          | 2         | 0.05%   |
| 7680x1440          | 1         | 0.03%   |
| 5760x2160          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1621      | 38.41%  |
| 13      | 661       | 15.66%  |
| 14      | 601       | 14.24%  |
| 17      | 201       | 4.76%   |
| 27      | 190       | 4.5%    |
| 24      | 181       | 4.29%   |
| 23      | 129       | 3.06%   |
| 12      | 103       | 2.44%   |
| 21      | 87        | 2.06%   |
| 16      | 66        | 1.56%   |
| 11      | 52        | 1.23%   |
| Unknown | 51        | 1.21%   |
| 34      | 49        | 1.16%   |
| 18      | 33        | 0.78%   |
| 31      | 28        | 0.66%   |
| 19      | 22        | 0.52%   |
| 22      | 17        | 0.4%    |
| 20      | 15        | 0.36%   |
| 10      | 13        | 0.31%   |
| 84      | 10        | 0.24%   |
| 72      | 8         | 0.19%   |
| 40      | 8         | 0.19%   |
| 37      | 8         | 0.19%   |
| 28      | 8         | 0.19%   |
| 54      | 7         | 0.17%   |
| 25      | 7         | 0.17%   |
| 29      | 6         | 0.14%   |
| 32      | 5         | 0.12%   |
| 48      | 4         | 0.09%   |
| 52      | 3         | 0.07%   |
| 26      | 3         | 0.07%   |
| 74      | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 43      | 2         | 0.05%   |
| 42      | 2         | 0.05%   |
| 38      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 3       | 2         | 0.05%   |
| 57      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2562      | 61.37%  |
| 201-300     | 498       | 11.93%  |
| 501-600     | 461       | 11.04%  |
| 351-400     | 254       | 6.08%   |
| 401-500     | 160       | 3.83%   |
| 601-700     | 64        | 1.53%   |
| 701-800     | 55        | 1.32%   |
| Unknown     | 51        | 1.22%   |
| 1001-1500   | 21        | 0.5%    |
| 801-900     | 20        | 0.48%   |
| 1501-2000   | 20        | 0.48%   |
| 901-1000    | 4         | 0.1%    |
| 1-100       | 3         | 0.07%   |
| 101-200     | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3051      | 83.63%  |
| 16/10   | 391       | 10.72%  |
| 21/9    | 63        | 1.73%   |
| 3/2     | 61        | 1.67%   |
| Unknown | 34        | 0.93%   |
| 5/4     | 19        | 0.52%   |
| 4/3     | 11        | 0.3%    |
| 32/9    | 8         | 0.22%   |
| 2.65    | 4         | 0.11%   |
| 6/5     | 2         | 0.05%   |
| 3.40    | 2         | 0.05%   |
| 1.03    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1617      | 38.44%  |
| 81-90          | 1000      | 23.77%  |
| 201-250        | 345       | 8.2%    |
| 71-80          | 252       | 5.99%   |
| 301-350        | 193       | 4.59%   |
| 121-130        | 170       | 4.04%   |
| 61-70          | 100       | 2.38%   |
| 351-500        | 89        | 2.12%   |
| 251-300        | 60        | 1.43%   |
| 111-120        | 60        | 1.43%   |
| 151-200        | 56        | 1.33%   |
| 51-60          | 54        | 1.28%   |
| Unknown        | 51        | 1.21%   |
| More than 1000 | 36        | 0.86%   |
| 141-150        | 36        | 0.86%   |
| 501-1000       | 27        | 0.64%   |
| 131-140        | 23        | 0.55%   |
| 91-100         | 20        | 0.48%   |
| 41-50          | 14        | 0.33%   |
| 1-40           | 4         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1948      | 47.21%  |
| 101-120       | 864       | 20.94%  |
| 51-100        | 593       | 14.37%  |
| 161-240       | 426       | 10.32%  |
| More than 240 | 206       | 4.99%   |
| Unknown       | 51        | 1.24%   |
| 1-50          | 38        | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2756      | 77.59%  |
| 2     | 685       | 19.28%  |
| 3     | 90        | 2.53%   |
| 0     | 14        | 0.39%   |
| 4     | 7         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2117      | 38.75%  |
| Realtek Semiconductor             | 1836      | 33.61%  |
| Qualcomm Atheros                  | 654       | 11.97%  |
| Broadcom                          | 206       | 3.77%   |
| MediaTek                          | 133       | 2.43%   |
| Broadcom Limited                  | 53        | 0.97%   |
| Lenovo                            | 41        | 0.75%   |
| ASIX Electronics                  | 38        | 0.7%    |
| TP-Link                           | 35        | 0.64%   |
| Qualcomm                          | 34        | 0.62%   |
| Sierra Wireless                   | 30        | 0.55%   |
| Ericsson Business Mobile Networks | 26        | 0.48%   |
| Marvell Technology Group          | 24        | 0.44%   |
| Ralink                            | 20        | 0.37%   |
| Ralink Technology                 | 19        | 0.35%   |
| DisplayLink                       | 19        | 0.35%   |
| Xiaomi                            | 17        | 0.31%   |
| Dell                              | 17        | 0.31%   |
| Samsung Electronics               | 15        | 0.27%   |
| Hewlett-Packard                   | 15        | 0.27%   |
| Apple                             | 12        | 0.22%   |
| Google                            | 9         | 0.16%   |
| D-Link                            | 9         | 0.16%   |
| Huawei Technologies               | 8         | 0.15%   |
| Cypress Semiconductor             | 7         | 0.13%   |
| NetGear                           | 6         | 0.11%   |
| Fibocom                           | 6         | 0.11%   |
| Qualcomm Atheros Communications   | 5         | 0.09%   |
| Linksys                           | 5         | 0.09%   |
| JMicron Technology                | 5         | 0.09%   |
| Nvidia                            | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |
| Microsoft                         | 3         | 0.05%   |
| ASUSTek Computer                  | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| U-Blox                            | 2         | 0.04%   |
| OPPO Electronics                  | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1218      | 18.64%  |
| Intel Wi-Fi 6 AX200                                               | 298       | 4.56%   |
| Intel Wireless 8265 / 8275                                        | 215       | 3.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 214       | 3.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 150       | 2.3%    |
| Intel Wi-Fi 6 AX201                                               | 141       | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 131       | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 128       | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 128       | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 128       | 1.96%   |
| Intel Wireless 7265                                               | 117       | 1.79%   |
| Intel Wireless 8260                                               | 102       | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 97        | 1.48%   |
| Intel Wireless 7260                                               | 94        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 91        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 88        | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 85        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 84        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 83        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 77        | 1.18%   |
| Intel Wireless 3165                                               | 76        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 68        | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 68        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 66        | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 65        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 64        | 0.98%   |
| Intel Wireless-AC 9260                                            | 52        | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 51        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 47        | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 0.67%   |
| Intel Wireless 3160                                               | 42        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 39        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 38        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 38        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 38        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 36        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 36        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2037      | 56.58%  |
| Qualcomm Atheros                | 554       | 15.39%  |
| Realtek Semiconductor           | 480       | 13.33%  |
| Broadcom                        | 177       | 4.92%   |
| MediaTek                        | 130       | 3.61%   |
| Broadcom Limited                | 42        | 1.17%   |
| Qualcomm                        | 31        | 0.86%   |
| Sierra Wireless                 | 30        | 0.83%   |
| TP-Link                         | 27        | 0.75%   |
| Ralink                          | 20        | 0.56%   |
| Ralink Technology               | 19        | 0.53%   |
| Dell                            | 10        | 0.28%   |
| D-Link                          | 7         | 0.19%   |
| Hewlett-Packard                 | 6         | 0.17%   |
| Fibocom                         | 6         | 0.17%   |
| Qualcomm Atheros Communications | 5         | 0.14%   |
| NetGear                         | 5         | 0.14%   |
| Linksys                         | 5         | 0.14%   |
| ASUSTek Computer                | 3         | 0.08%   |
| Xiaomi                          | 2         | 0.06%   |
| Quectel Wireless Solutions      | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 298       | 8.25%   |
| Intel Wireless 8265 / 8275                                     | 215       | 5.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 150       | 4.15%   |
| Intel Wi-Fi 6 AX201                                            | 141       | 3.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 131       | 3.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 128       | 3.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 128       | 3.54%   |
| Intel Wireless 7265                                            | 117       | 3.24%   |
| Intel Wireless 8260                                            | 102       | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 97        | 2.69%   |
| Intel Wireless 7260                                            | 94        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 91        | 2.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 88        | 2.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 85        | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 84        | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 83        | 2.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 77        | 2.13%   |
| Intel Wireless 3165                                            | 76        | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 68        | 1.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 68        | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 66        | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 64        | 1.77%   |
| Intel Wireless-AC 9260                                         | 52        | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 47        | 1.3%    |
| Intel Wireless 3160                                            | 42        | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 39        | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 38        | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 38        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 36        | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 36        | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 29        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                 | 28        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 28        | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 27        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 26        | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 24        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 21        | 0.58%   |
| Intel Centrino Advanced-N 6200                                 | 20        | 0.55%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 19        | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 17        | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1636      | 58.22%  |
| Intel                            | 732       | 26.05%  |
| Qualcomm Atheros                 | 151       | 5.37%   |
| Broadcom                         | 54        | 1.92%   |
| Lenovo                           | 40        | 1.42%   |
| ASIX Electronics                 | 38        | 1.35%   |
| Marvell Technology Group         | 23        | 0.82%   |
| DisplayLink                      | 19        | 0.68%   |
| Xiaomi                           | 15        | 0.53%   |
| Apple                            | 12        | 0.43%   |
| Samsung Electronics              | 11        | 0.39%   |
| Broadcom Limited                 | 11        | 0.39%   |
| Google                           | 9         | 0.32%   |
| TP-Link                          | 8         | 0.28%   |
| Cypress Semiconductor            | 7         | 0.25%   |
| JMicron Technology               | 5         | 0.18%   |
| Nvidia                           | 4         | 0.14%   |
| Huawei Technologies              | 4         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| Qualcomm                         | 3         | 0.11%   |
| Motorola PCS                     | 3         | 0.11%   |
| MediaTek                         | 3         | 0.11%   |
| Hewlett-Packard                  | 3         | 0.11%   |
| OPPO Electronics                 | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| Microsoft                        | 2         | 0.07%   |
| D-Link                           | 2         | 0.07%   |
| QNAP System                      | 1         | 0.04%   |
| NetGear                          | 1         | 0.04%   |
| Microchip Technology             | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HTC (High Tech Computer)         | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Aquantia                         | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1218      | 42.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 214       | 7.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 5.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 128       | 4.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 65        | 2.27%   |
| Intel Ethernet Connection (4) I219-V                              | 51        | 1.78%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 1.47%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 1.33%   |
| Intel Ethernet Connection (6) I219-V                              | 38        | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 36        | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 35        | 1.22%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 1.05%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 27        | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 26        | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 25        | 0.87%   |
| Intel Ethernet Connection (6) I219-LM                             | 25        | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.63%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.49%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 12        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.38%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.31%   |
| Lenovo USB-C Dock Ethernet                                        | 9         | 0.31%   |
| Intel Ethernet Connection (16) I219-V                             | 9         | 0.31%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 8         | 0.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 8         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3448      | 55.82%  |
| Ethernet | 2666      | 43.16%  |
| Modem    | 59        | 0.96%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2940      | 79.4%   |
| Ethernet | 760       | 20.52%  |
| Modem    | 3         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2414      | 69.35%  |
| 1     | 993       | 28.53%  |
| 3     | 42        | 1.21%   |
| 0     | 30        | 0.86%   |
| 4     | 2         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2912      | 82.35%  |
| Yes  | 624       | 17.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1717      | 56.59%  |
| Realtek Semiconductor           | 289       | 9.53%   |
| Qualcomm Atheros Communications | 246       | 8.11%   |
| IMC Networks                    | 150       | 4.94%   |
| Lite-On Technology              | 133       | 4.38%   |
| Broadcom                        | 129       | 4.25%   |
| Foxconn / Hon Hai               | 115       | 3.79%   |
| Apple                           | 50        | 1.65%   |
| Realtek                         | 41        | 1.35%   |
| Dell                            | 33        | 1.09%   |
| Cambridge Silicon Radio         | 25        | 0.82%   |
| Hewlett-Packard                 | 19        | 0.63%   |
| MediaTek                        | 14        | 0.46%   |
| Toshiba                         | 13        | 0.43%   |
| USI                             | 11        | 0.36%   |
| Ralink                          | 11        | 0.36%   |
| Foxconn International           | 7         | 0.23%   |
| ASUSTek Computer                | 5         | 0.16%   |
| Opticis                         | 4         | 0.13%   |
| TP-Link                         | 3         | 0.1%    |
| Chicony Electronics             | 3         | 0.1%    |
| Askey Computer                  | 3         | 0.1%    |
| Smart Modular Technologies      | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Dynex                           | 2         | 0.07%   |
| Alps Electric                   | 2         | 0.07%   |
| Syntek                          | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 622       | 20.47%  |
| Intel AX201 Bluetooth                               | 305       | 10.04%  |
| Intel AX200 Bluetooth                               | 280       | 9.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 254       | 8.36%   |
| Realtek Bluetooth Radio                             | 183       | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 133       | 4.38%   |
| Intel AX210 Bluetooth                               | 77        | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                      | 63        | 2.07%   |
| Intel Bluetooth Device                              | 55        | 1.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 50        | 1.65%   |
| IMC Networks Wireless_Device                        | 49        | 1.61%   |
| IMC Networks Bluetooth Radio                        | 49        | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 46        | 1.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 43        | 1.41%   |
| Realtek Bluetooth Radio                             | 41        | 1.35%   |
| Lite-On Bluetooth Device                            | 41        | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 41        | 1.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 36        | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                    | 34        | 1.12%   |
| IMC Networks Bluetooth Device                       | 33        | 1.09%   |
| Apple Bluetooth Host Controller                     | 31        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 0.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 0.82%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 24        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 23        | 0.76%   |
| Lite-On Wireless_Device                             | 21        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 17        | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.56%   |
| MediaTek Wireless_Device                            | 13        | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.43%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.39%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.39%   |
| USI Bluetooth Device                                | 11        | 0.36%   |
| Realtek RTL8821A Bluetooth                          | 11        | 0.36%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.36%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2659      | 58.12%  |
| AMD                              | 834       | 18.23%  |
| Nvidia                           | 683       | 14.93%  |
| C-Media Electronics              | 44        | 0.96%   |
| Lenovo                           | 37        | 0.81%   |
| Realtek Semiconductor            | 35        | 0.77%   |
| Logitech                         | 22        | 0.48%   |
| Texas Instruments                | 21        | 0.46%   |
| JMTek                            | 20        | 0.44%   |
| GN Netcom                        | 15        | 0.33%   |
| Apple                            | 15        | 0.33%   |
| Kingston Technology              | 14        | 0.31%   |
| Focusrite-Novation               | 13        | 0.28%   |
| Razer USA                        | 11        | 0.24%   |
| SteelSeries ApS                  | 9         | 0.2%    |
| Plantronics                      | 8         | 0.17%   |
| Hewlett-Packard                  | 7         | 0.15%   |
| Creative Technology              | 7         | 0.15%   |
| Generalplus Technology           | 5         | 0.11%   |
| ASUSTek Computer                 | 5         | 0.11%   |
| Sennheiser Communications        | 4         | 0.09%   |
| Samson Technologies              | 4         | 0.09%   |
| Corsair                          | 4         | 0.09%   |
| Yamaha                           | 3         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| SAVITECH                         | 3         | 0.07%   |
| Conexant Systems                 | 3         | 0.07%   |
| XMOS                             | 2         | 0.04%   |
| Valve Software                   | 2         | 0.04%   |
| Sony                             | 2         | 0.04%   |
| Schiit Audio                     | 2         | 0.04%   |
| Scarlett                         | 2         | 0.04%   |
| No brand                         | 2         | 0.04%   |
| Native Instruments               | 2         | 0.04%   |
| Medeli Electronics               | 2         | 0.04%   |
| Mackie Designs                   | 2         | 0.04%   |
| Jieli Technology                 | 2         | 0.04%   |
| JBL                              | 2         | 0.04%   |
| GYROCOM C&C                      | 2         | 0.04%   |
| Goldvish                         | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 654       | 11.65%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 489       | 8.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 334       | 5.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 228       | 4.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 217       | 3.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 195       | 3.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 185       | 3.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 163       | 2.9%    |
| Intel Broadwell-U Audio Controller                                                                | 131       | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 129       | 2.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 127       | 2.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 127       | 2.26%   |
| Intel 8 Series HD Audio Controller                                                                | 127       | 2.26%   |
| Intel CM238 HD Audio Controller                                                                   | 116       | 2.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 108       | 1.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 107       | 1.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 106       | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 93        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 91        | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 87        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 85        | 1.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 76        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 73        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 72        | 1.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 68        | 1.21%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 51        | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 50        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 49        | 0.87%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 47        | 0.84%   |
| AMD FCH Azalia Controller                                                                         | 44        | 0.78%   |
| Nvidia Audio device                                                                               | 42        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 40        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 38        | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 36        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 34        | 0.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 34        | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 31        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 29        | 0.52%   |
| Realtek Semiconductor USB Audio                                                                   | 28        | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 27        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 924       | 30.19%  |
| SK hynix            | 697       | 22.77%  |
| Micron Technology   | 408       | 13.33%  |
| Kingston            | 293       | 9.57%   |
| Crucial             | 186       | 6.08%   |
| Unknown             | 103       | 3.36%   |
| Ramaxel Technology  | 76        | 2.48%   |
| A-DATA Technology   | 66        | 2.16%   |
| Corsair             | 50        | 1.63%   |
| Elpida              | 42        | 1.37%   |
| G.Skill             | 22        | 0.72%   |
| Nanya Technology    | 18        | 0.59%   |
| Team                | 16        | 0.52%   |
| Patriot             | 15        | 0.49%   |
| Transcend           | 13        | 0.42%   |
| Smart               | 13        | 0.42%   |
| GOODRAM             | 13        | 0.42%   |
| Unknown (ABCD)      | 12        | 0.39%   |
| Unknown             | 8         | 0.26%   |
| Teikon              | 6         | 0.2%    |
| Smart Brazil        | 6         | 0.2%    |
| PNY                 | 5         | 0.16%   |
| Goldkey             | 5         | 0.16%   |
| AMD                 | 5         | 0.16%   |
| Avant               | 4         | 0.13%   |
| Apacer              | 4         | 0.13%   |
| V-GeN               | 3         | 0.1%    |
| GSkill              | 3         | 0.1%    |
| 48spaces            | 3         | 0.1%    |
| V-Color             | 2         | 0.07%   |
| Unknown (08AE)      | 2         | 0.07%   |
| Silicon Power       | 2         | 0.07%   |
| PKI/Kingston        | 2         | 0.07%   |
| Neo Forza           | 2         | 0.07%   |
| High Bridge         | 2         | 0.07%   |
| fef5                | 2         | 0.07%   |
| ASint Technology    | 2         | 0.07%   |
| 4ea5                | 2         | 0.07%   |
| Wilk                | 1         | 0.03%   |
| Unknown (C509)      | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 60        | 1.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 56        | 1.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 55        | 1.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 1.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 34        | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 30        | 0.93%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 28        | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.81%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 25        | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 24        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 23        | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.71%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 18        | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 17        | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 17        | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.5%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 16        | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 14        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 14        | 0.43%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 14        | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 13        | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 13        | 0.4%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 13        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1489      | 58.97%  |
| DDR3    | 631       | 24.99%  |
| LPDDR4  | 131       | 5.19%   |
| LPDDR3  | 102       | 4.04%   |
| LPDDR5  | 50        | 1.98%   |
| DDR5    | 45        | 1.78%   |
| DDR2    | 38        | 1.5%    |
| SDRAM   | 32        | 1.27%   |
| Unknown | 5         | 0.2%    |
| DRAM    | 1         | 0.04%   |
| DDR     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2186      | 86.37%  |
| Row Of Chips | 294       | 11.62%  |
| Chip         | 30        | 1.19%   |
| Unknown      | 13        | 0.51%   |
| DIMM         | 8         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1225      | 44.32%  |
| 4096  | 701       | 25.36%  |
| 16384 | 501       | 18.13%  |
| 2048  | 206       | 7.45%   |
| 32768 | 97        | 3.51%   |
| 1024  | 34        | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 685       | 24.95%  |
| 3200    | 578       | 21.05%  |
| 1600    | 454       | 16.53%  |
| 2400    | 262       | 9.54%   |
| 2133    | 158       | 5.75%   |
| 1334    | 91        | 3.31%   |
| 4267    | 66        | 2.4%    |
| 1333    | 56        | 2.04%   |
| 3266    | 55        | 2%      |
| 6400    | 48        | 1.75%   |
| 4800    | 46        | 1.68%   |
| 1867    | 45        | 1.64%   |
| 1067    | 32        | 1.17%   |
| 667     | 29        | 1.06%   |
| 4266    | 23        | 0.84%   |
| 4199    | 19        | 0.69%   |
| 8400    | 18        | 0.66%   |
| Unknown | 14        | 0.51%   |
| 1066    | 12        | 0.44%   |
| 2048    | 10        | 0.36%   |
| 975     | 8         | 0.29%   |
| 800     | 8         | 0.29%   |
| 2933    | 7         | 0.25%   |
| 3733    | 5         | 0.18%   |
| 1866    | 2         | 0.07%   |
| 1777    | 2         | 0.07%   |
| 1200    | 2         | 0.07%   |
| 533     | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 5600    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 3000    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 200     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 50%     |
| Samsung Electronics | 2         | 11.11%  |
| Prolific Technology | 2         | 11.11%  |
| Canon               | 2         | 11.11%  |
| Seiko Epson         | 1         | 5.56%   |
| Dymo-CoStar         | 1         | 5.56%   |
| Brother Industries  | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port      | 2         | 11.11%  |
| HP DeskJet 2130 series             | 2         | 11.11%  |
| Seiko Epson WF-2530 Series         | 1         | 5.56%   |
| Samsung SCX-3200 Series            | 1         | 5.56%   |
| Samsung M2020 Series               | 1         | 5.56%   |
| HP OfficeJet 5600 (USBHUB)         | 1         | 5.56%   |
| HP LaserJet 1320                   | 1         | 5.56%   |
| HP LaserJet 1022                   | 1         | 5.56%   |
| HP ENVY 5000 series                | 1         | 5.56%   |
| HP DeskJet 840c                    | 1         | 5.56%   |
| HP DeskJet 4100 series             | 1         | 5.56%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 5.56%   |
| Dymo-CoStar LabelWriter 400        | 1         | 5.56%   |
| Canon PIXMA MG2500 Series          | 1         | 5.56%   |
| Canon LiDE 400                     | 1         | 5.56%   |
| Brother HL-1110 series             | 1         | 5.56%   |

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
| Chicony Electronics                    | 753       | 23.61%  |
| IMC Networks                           | 404       | 12.66%  |
| Microdia                               | 294       | 9.22%   |
| Realtek Semiconductor                  | 230       | 7.21%   |
| Bison Electronics                      | 208       | 6.52%   |
| Quanta                                 | 203       | 6.36%   |
| Sunplus Innovation Technology          | 157       | 4.92%   |
| Acer                                   | 138       | 4.33%   |
| Cheng Uei Precision Industry (Foxlink) | 114       | 3.57%   |
| Syntek                                 | 98        | 3.07%   |
| Lite-On Technology                     | 88        | 2.76%   |
| Luxvisions Innotech Limited            | 64        | 2.01%   |
| Logitech                               | 59        | 1.85%   |
| Suyin                                  | 56        | 1.76%   |
| Apple                                  | 55        | 1.72%   |
| Silicon Motion                         | 40        | 1.25%   |
| Alcor Micro                            | 33        | 1.03%   |
| Lenovo                                 | 21        | 0.66%   |
| Samsung Electronics                    | 17        | 0.53%   |
| Sonix Technology                       | 16        | 0.5%    |
| Importek                               | 13        | 0.41%   |
| SunplusIT                              | 12        | 0.38%   |
| Ricoh                                  | 11        | 0.34%   |
| ALi                                    | 11        | 0.34%   |
| Primax Electronics                     | 8         | 0.25%   |
| Microsoft                              | 7         | 0.22%   |
| Z-Star Microelectronics                | 6         | 0.19%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.16%   |
| OmniVision Technologies                | 4         | 0.13%   |
| Google                                 | 4         | 0.13%   |
| ARC International                      | 4         | 0.13%   |
| MacroSilicon                           | 3         | 0.09%   |
| YGTek                                  | 2         | 0.06%   |
| Valve Software                         | 2         | 0.06%   |
| USB Camera                             | 2         | 0.06%   |
| ShineTech                              | 2         | 0.06%   |
| Razer USA                              | 2         | 0.06%   |
| Pixart Imaging                         | 2         | 0.06%   |
| LG Electronics                         | 2         | 0.06%   |
| Intel                                  | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 212       | 6.59%   |
| Microdia Integrated_Webcam_HD                                              | 168       | 5.23%   |
| IMC Networks Integrated Camera                                             | 136       | 4.23%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 120       | 3.73%   |
| Chicony HD WebCam                                                          | 87        | 2.71%   |
| Realtek Integrated_Webcam_HD                                               | 83        | 2.58%   |
| Sunplus Integrated_Webcam_HD                                               | 70        | 2.18%   |
| Bison Integrated Camera                                                    | 66        | 2.05%   |
| Syntek Integrated Camera                                                   | 63        | 1.96%   |
| Quanta HD User Facing                                                      | 49        | 1.52%   |
| Lite-On Integrated Camera                                                  | 46        | 1.43%   |
| Acer HD Webcam                                                             | 46        | 1.43%   |
| Bison SunplusIT Integrated Camera                                          | 42        | 1.31%   |
| Acer Integrated Camera                                                     | 39        | 1.21%   |
| Chicony USB2.0 Camera                                                      | 35        | 1.09%   |
| Chicony Integrated Camera (1280x720@30)                                    | 34        | 1.06%   |
| Chicony HD User Facing                                                     | 33        | 1.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 32        | 1%      |
| Chicony HP HD Camera                                                       | 30        | 0.93%   |
| Microdia Integrated Webcam                                                 | 29        | 0.9%    |
| IMC Networks ov9734_azurewave_camera                                       | 25        | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 24        | 0.75%   |
| Realtek Integrated Webcam                                                  | 23        | 0.72%   |
| Chicony HP Wide Vision HD Camera                                           | 23        | 0.72%   |
| Quanta VGA WebCam                                                          | 22        | 0.68%   |
| Quanta HP Wide Vision HD Camera                                            | 22        | 0.68%   |
| Quanta HP TrueVision HD Camera                                             | 22        | 0.68%   |
| Chicony Integrated IR Camera                                               | 22        | 0.68%   |
| Realtek USB Camera                                                         | 21        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 21        | 0.65%   |
| Sunplus HD WebCam                                                          | 20        | 0.62%   |
| Chicony HP TrueVision HD Camera                                            | 20        | 0.62%   |
| Chicony HP Truevision HD                                                   | 20        | 0.62%   |
| Chicony EasyCamera                                                         | 20        | 0.62%   |
| Quanta HP HD Camera                                                        | 19        | 0.59%   |
| Quanta HD Webcam                                                           | 19        | 0.59%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.56%   |
| Microdia Integrated Webcam HD                                              | 18        | 0.56%   |
| Lite-On HP HD Camera                                                       | 18        | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                                               | 18        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 262       | 34.98%  |
| Validity Sensors                   | 204       | 27.24%  |
| Shenzhen Goodix Technology         | 141       | 18.83%  |
| Elan Microelectronics              | 49        | 6.54%   |
| LighTuning Technology              | 29        | 3.87%   |
| Upek                               | 27        | 3.6%    |
| AuthenTec                          | 20        | 2.67%   |
| STMicroelectronics                 | 9         | 1.2%    |
| Samsung Electronics                | 3         | 0.4%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.27%   |
| HOLTEK                             | 2         | 0.27%   |
| Focal-systems.Corp                 | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 113       | 15.09%  |
| Shenzhen Goodix  Fingerprint Device                                        | 82        | 10.95%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 52        | 6.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 38        | 5.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 4.54%   |
| Shenzhen Goodix FingerPrint                                                | 31        | 4.14%   |
| Elan ELAN:Fingerprint                                                      | 30        | 4.01%   |
| Shenzhen Goodix Fingerprint Reader                                         | 28        | 3.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 3.34%   |
| Validity Sensors Synaptics WBDI                                            | 24        | 3.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 3.07%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 19        | 2.54%   |
| Elan ELAN:ARM-M4                                                           | 19        | 2.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 18        | 2.4%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 2.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.87%   |
| Validity Sensors VFS491                                                    | 13        | 1.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.74%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 1.6%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.47%   |
| AuthenTec AES2810                                                          | 11        | 1.47%   |
| Synaptics UWP WBDI Device                                                  | 10        | 1.34%   |
| Synaptics UWP WBDI                                                         | 10        | 1.34%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.2%    |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.2%    |
| Synaptics  WBDI                                                            | 6         | 0.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.53%   |
| Synaptics WBDI Device                                                      | 4         | 0.53%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.4%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.4%    |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.27%   |
| Synaptics WBDI                                                             | 2         | 0.27%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 129       | 43.14%  |
| Broadcom                  | 112       | 37.46%  |
| Upek                      | 23        | 7.69%   |
| Lenovo                    | 11        | 3.68%   |
| O2 Micro                  | 8         | 2.68%   |
| SCM Microsystems          | 4         | 1.34%   |
| Yubico.com                | 3         | 1%      |
| Gemalto (was Gemplus)     | 3         | 1%      |
| Clay Logic                | 2         | 0.67%   |
| Realtek Semiconductor     | 1         | 0.33%   |
| Hewlett-Packard           | 1         | 0.33%   |
| Chicony Electronics       | 1         | 0.33%   |
| Aladdin Knowledge Systems | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 129       | 43.14%  |
| Broadcom 5880                                                                | 32        | 10.7%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 10.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 8.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 23        | 7.69%   |
| Broadcom 58200                                                               | 23        | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 3.68%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 2.34%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 1%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1%      |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.67%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.33%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.33%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2127      | 59.76%  |
| 1     | 1119      | 31.44%  |
| 2     | 247       | 6.94%   |
| 3     | 56        | 1.57%   |
| 4     | 8         | 0.22%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 731       | 41.37%  |
| Graphics card            | 323       | 18.28%  |
| Chipcard                 | 263       | 14.88%  |
| Multimedia controller    | 121       | 6.85%   |
| Net/wireless             | 105       | 5.94%   |
| Camera                   | 92        | 5.21%   |
| Bluetooth                | 33        | 1.87%   |
| Storage                  | 17        | 0.96%   |
| Net/ethernet             | 17        | 0.96%   |
| Sound                    | 16        | 0.91%   |
| Communication controller | 13        | 0.74%   |
| Card reader              | 11        | 0.62%   |
| Network                  | 9         | 0.51%   |
| Modem                    | 6         | 0.34%   |
| Dvb card                 | 3         | 0.17%   |
| Wireless                 | 2         | 0.11%   |
| Unassigned class         | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |
| Flash memory             | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |


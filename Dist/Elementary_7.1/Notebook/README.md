Elementary 7.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.1.

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

Total: 585

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [5c77a53c22](https://linux-hardware.org/?probe=5c77a53c22) | Dec 25, 2025 |
| Dell          | Latitude E5470              | [e5400c2e38](https://linux-hardware.org/?probe=e5400c2e38) | Dec 13, 2025 |
| ASUSTek       | GL752VW                     | [ff85424fb4](https://linux-hardware.org/?probe=ff85424fb4) | Dec 06, 2025 |
| Lenovo        | V14 G2 ITL 82KA             | [60c3603a43](https://linux-hardware.org/?probe=60c3603a43) | Nov 21, 2025 |
| Apple         | MacBookPro8,1               | [d713ff600d](https://linux-hardware.org/?probe=d713ff600d) | Nov 15, 2025 |
| Apple         | MacBookPro8,1               | [cb1f3b706e](https://linux-hardware.org/?probe=cb1f3b706e) | Oct 30, 2025 |
| Apple         | MacBookPro8,1               | [9fdff90cbd](https://linux-hardware.org/?probe=9fdff90cbd) | Oct 30, 2025 |
| Apple         | MacBook6,1                  | [5a53960e9a](https://linux-hardware.org/?probe=5a53960e9a) | Oct 28, 2025 |
| Apple         | MacBook6,1                  | [dbc8f4f3ab](https://linux-hardware.org/?probe=dbc8f4f3ab) | Oct 23, 2025 |
| HP            | Pavilion dv7                | [d4a2d26dfe](https://linux-hardware.org/?probe=d4a2d26dfe) | Oct 04, 2025 |
| Dell          | Latitude E6420              | [5efb6c4bc2](https://linux-hardware.org/?probe=5efb6c4bc2) | Oct 04, 2025 |
| HP            | ZBook 15                    | [787e1db37e](https://linux-hardware.org/?probe=787e1db37e) | Sep 27, 2025 |
| AZW           | GT-R                        | [e44ff94248](https://linux-hardware.org/?probe=e44ff94248) | Sep 23, 2025 |
| Star Labs     | StarBook                    | [ce9448d5e8](https://linux-hardware.org/?probe=ce9448d5e8) | Aug 31, 2025 |
| ASUSTek       | X555LA                      | [1eec7134a2](https://linux-hardware.org/?probe=1eec7134a2) | Jul 24, 2025 |
| HP            | EliteBook 8470p             | [543bb5c5ee](https://linux-hardware.org/?probe=543bb5c5ee) | Jul 16, 2025 |
| HP            | EliteBook 8470p             | [ceb27b6e9a](https://linux-hardware.org/?probe=ceb27b6e9a) | Jul 16, 2025 |
| HP            | Pavilion dv7                | [7e04c5ff73](https://linux-hardware.org/?probe=7e04c5ff73) | Jul 14, 2025 |
| TUXEDO        | N85_N87HCHNHZ               | [944efa8a15](https://linux-hardware.org/?probe=944efa8a15) | Jul 03, 2025 |
| Apple         | MacBookAir7,2               | [631e136e6b](https://linux-hardware.org/?probe=631e136e6b) | Jun 25, 2025 |
| Toshiba       | Satellite L50-B             | [65d84e16b9](https://linux-hardware.org/?probe=65d84e16b9) | May 31, 2025 |
| Toshiba       | Satellite L50-B             | [22f45326e2](https://linux-hardware.org/?probe=22f45326e2) | May 31, 2025 |
| Clevo         | M860TU                      | [19839c5808](https://linux-hardware.org/?probe=19839c5808) | Apr 20, 2025 |
| Dell          | Inspiron 15 3515            | [142f88c0e7](https://linux-hardware.org/?probe=142f88c0e7) | Apr 15, 2025 |
| Sony          | SVS151190X                  | [7ffeb7fab1](https://linux-hardware.org/?probe=7ffeb7fab1) | Mar 30, 2025 |
| Toshiba       | Satellite L15W-B            | [2cbc15f4f1](https://linux-hardware.org/?probe=2cbc15f4f1) | Mar 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e02ff3872b](https://linux-hardware.org/?probe=e02ff3872b) | Mar 24, 2025 |
| ASUSTek       | TP300LA                     | [116335b0c6](https://linux-hardware.org/?probe=116335b0c6) | Mar 24, 2025 |
| HP            | Compaq 6730b (KE717AV)      | [4d05160c8f](https://linux-hardware.org/?probe=4d05160c8f) | Mar 21, 2025 |
| HP            | ProBook 640 G8 Notebook ... | [6d76c73345](https://linux-hardware.org/?probe=6d76c73345) | Mar 10, 2025 |
| HP            | Laptop 14-cf1xxx            | [6dbdba4503](https://linux-hardware.org/?probe=6dbdba4503) | Mar 08, 2025 |
| ASUSTek       | TP300LA                     | [bd5141417a](https://linux-hardware.org/?probe=bd5141417a) | Mar 03, 2025 |
| ASUSTek       | TP300LA                     | [d34ec4e1c9](https://linux-hardware.org/?probe=d34ec4e1c9) | Mar 01, 2025 |
| Apple         | MacBookPro8,1               | [84b16f9e0b](https://linux-hardware.org/?probe=84b16f9e0b) | Feb 28, 2025 |
| HP            | Laptop 14-cf1xxx            | [d188eaf072](https://linux-hardware.org/?probe=d188eaf072) | Feb 28, 2025 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [f855a3facf](https://linux-hardware.org/?probe=f855a3facf) | Feb 27, 2025 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a934b12213](https://linux-hardware.org/?probe=a934b12213) | Feb 25, 2025 |
| HP            | Laptop 17-by3xxx            | [98f0606758](https://linux-hardware.org/?probe=98f0606758) | Feb 19, 2025 |
| HP            | Pavilion dv7                | [527154a620](https://linux-hardware.org/?probe=527154a620) | Feb 14, 2025 |
| Sony          | SVF1521A1EW                 | [b31f8e7865](https://linux-hardware.org/?probe=b31f8e7865) | Feb 13, 2025 |
| Thomson       | N17V3C8WH512                | [12cead9c03](https://linux-hardware.org/?probe=12cead9c03) | Jan 29, 2025 |
| Apple         | MacBookPro9,2               | [a35023f16c](https://linux-hardware.org/?probe=a35023f16c) | Jan 29, 2025 |
| Thomson       | N17V3C8WH512                | [7bf5e0c404](https://linux-hardware.org/?probe=7bf5e0c404) | Jan 27, 2025 |
| Apple         | MacBookPro10,2              | [43ba3065b1](https://linux-hardware.org/?probe=43ba3065b1) | Jan 24, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fde29a0789](https://linux-hardware.org/?probe=fde29a0789) | Jan 22, 2025 |
| Apple         | MacBookPro9,2               | [add0826738](https://linux-hardware.org/?probe=add0826738) | Jan 21, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [4d186a07ef](https://linux-hardware.org/?probe=4d186a07ef) | Jan 20, 2025 |
| HP            | Laptop 17-by3xxx            | [93544fbfaa](https://linux-hardware.org/?probe=93544fbfaa) | Jan 18, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3e5ea876fa](https://linux-hardware.org/?probe=3e5ea876fa) | Jan 13, 2025 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [92181b0356](https://linux-hardware.org/?probe=92181b0356) | Jan 11, 2025 |
| Apple         | MacBookPro8,1               | [ec217c6326](https://linux-hardware.org/?probe=ec217c6326) | Jan 11, 2025 |
| Samsung       | 900X3C/900X4C/900X4D        | [cbe6ed9631](https://linux-hardware.org/?probe=cbe6ed9631) | Jan 05, 2025 |
| NEC Comput... | PC-LL750MSW                 | [55d20a7230](https://linux-hardware.org/?probe=55d20a7230) | Dec 27, 2024 |
| Dell          | XPS 15 9550                 | [f1502af093](https://linux-hardware.org/?probe=f1502af093) | Dec 23, 2024 |
| Dell          | Precision 5530              | [3292cf1103](https://linux-hardware.org/?probe=3292cf1103) | Dec 18, 2024 |
| ASUSTek       | X751MA                      | [016d948a0c](https://linux-hardware.org/?probe=016d948a0c) | Dec 17, 2024 |
| HP            | Laptop 17-by3xxx            | [cb8341eaca](https://linux-hardware.org/?probe=cb8341eaca) | Dec 17, 2024 |
| HP            | ProBook 6570b               | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| Acer          | Aspire A515-48M             | [1bd13cf77f](https://linux-hardware.org/?probe=1bd13cf77f) | Dec 14, 2024 |
| Unknown       | Unknown                     | [2e17fa2c66](https://linux-hardware.org/?probe=2e17fa2c66) | Dec 12, 2024 |
| ASUSTek       | X550CL                      | [e471757e1c](https://linux-hardware.org/?probe=e471757e1c) | Dec 11, 2024 |
| Microtech     | ebookPro                    | [4e6f89ca56](https://linux-hardware.org/?probe=4e6f89ca56) | Dec 10, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [fc797d558c](https://linux-hardware.org/?probe=fc797d558c) | Dec 08, 2024 |
| Unknown       | Unknown                     | [bd30f7f45d](https://linux-hardware.org/?probe=bd30f7f45d) | Dec 08, 2024 |
| Dell          | Latitude 3340               | [07c627667a](https://linux-hardware.org/?probe=07c627667a) | Dec 07, 2024 |
| Apple         | MacBook4,1                  | [915a1dbb22](https://linux-hardware.org/?probe=915a1dbb22) | Dec 04, 2024 |
| HP            | EliteBook 2170p             | [39de9fd95f](https://linux-hardware.org/?probe=39de9fd95f) | Dec 04, 2024 |
| Apple         | MacBookAir3,1               | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | [085d5938c0](https://linux-hardware.org/?probe=085d5938c0) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | [99cb99a15c](https://linux-hardware.org/?probe=99cb99a15c) | Dec 03, 2024 |
| Toshiba       | Satellite L50-B             | [f0195c6929](https://linux-hardware.org/?probe=f0195c6929) | Dec 02, 2024 |
| Apple         | MacBookPro12,1              | [deda79f6f5](https://linux-hardware.org/?probe=deda79f6f5) | Dec 01, 2024 |
| Toshiba       | Satellite L50-B             | [344eaec320](https://linux-hardware.org/?probe=344eaec320) | Nov 29, 2024 |
| Apple         | MacBookPro8,1               | [a817c04b09](https://linux-hardware.org/?probe=a817c04b09) | Nov 29, 2024 |
| Dell          | Latitude 5420               | [9e6c2d1825](https://linux-hardware.org/?probe=9e6c2d1825) | Nov 28, 2024 |
| Acer          | Aspire E3-111               | [f90ddc6433](https://linux-hardware.org/?probe=f90ddc6433) | Nov 26, 2024 |
| Apple         | MacBookAir6,1               | [a42587525c](https://linux-hardware.org/?probe=a42587525c) | Nov 25, 2024 |
| Apple         | MacBookAir6,1               | [1d464cc8ce](https://linux-hardware.org/?probe=1d464cc8ce) | Nov 25, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [d24fd529d4](https://linux-hardware.org/?probe=d24fd529d4) | Nov 25, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [d7914ef50d](https://linux-hardware.org/?probe=d7914ef50d) | Nov 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [8ecfb38136](https://linux-hardware.org/?probe=8ecfb38136) | Nov 22, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | [c785c1f7dd](https://linux-hardware.org/?probe=c785c1f7dd) | Nov 21, 2024 |
| HP            | ProBook 6560b               | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | [058f6bf1ac](https://linux-hardware.org/?probe=058f6bf1ac) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | [541dd7b9fb](https://linux-hardware.org/?probe=541dd7b9fb) | Nov 19, 2024 |
| Apple         | MacBookPro5,5               | [3f2eff0083](https://linux-hardware.org/?probe=3f2eff0083) | Nov 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A2FXTH    | [8609525ceb](https://linux-hardware.org/?probe=8609525ceb) | Nov 18, 2024 |
| Apple         | MacBookPro7,1               | [7d86d39596](https://linux-hardware.org/?probe=7d86d39596) | Nov 17, 2024 |
| Apple         | MacBookPro5,5               | [001f8b1280](https://linux-hardware.org/?probe=001f8b1280) | Nov 17, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [8715440da3](https://linux-hardware.org/?probe=8715440da3) | Nov 17, 2024 |
| Dell          | Inspiron N5030              | [acf692231b](https://linux-hardware.org/?probe=acf692231b) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0d4cb9a88f](https://linux-hardware.org/?probe=0d4cb9a88f) | Nov 16, 2024 |
| Lenovo        | G50-80 80L0                 | [d31664cad1](https://linux-hardware.org/?probe=d31664cad1) | Nov 15, 2024 |
| Apple         | MacBookPro8,2               | [0259216292](https://linux-hardware.org/?probe=0259216292) | Nov 15, 2024 |
| Apple         | MacBookPro9,2               | [7029186fa5](https://linux-hardware.org/?probe=7029186fa5) | Nov 14, 2024 |
| Apple         | MacBookPro8,1               | [2f0fa7a4fa](https://linux-hardware.org/?probe=2f0fa7a4fa) | Nov 11, 2024 |
| Apple         | MacBookPro5,2               | [a0db5bcf03](https://linux-hardware.org/?probe=a0db5bcf03) | Nov 08, 2024 |
| Acer          | Aspire E5-771               | [9b889ed10a](https://linux-hardware.org/?probe=9b889ed10a) | Nov 08, 2024 |
| Apple         | MacBookPro8,1               | [0b5989c295](https://linux-hardware.org/?probe=0b5989c295) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | [71249fccac](https://linux-hardware.org/?probe=71249fccac) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | [ebcff700e9](https://linux-hardware.org/?probe=ebcff700e9) | Nov 06, 2024 |
| LTD Delovo... | 15Y                         | [5553e46796](https://linux-hardware.org/?probe=5553e46796) | Nov 04, 2024 |
| LTD Delovo... | 15Y                         | [0187f0b5ab](https://linux-hardware.org/?probe=0187f0b5ab) | Nov 04, 2024 |
| Samsung       | 940XFG                      | [8d09e8db06](https://linux-hardware.org/?probe=8d09e8db06) | Nov 04, 2024 |
| HUAWEI        | BOM-WXX9                    | [f0b28bde30](https://linux-hardware.org/?probe=f0b28bde30) | Nov 03, 2024 |
| Dell          | Latitude 7420               | [2454ee0dbb](https://linux-hardware.org/?probe=2454ee0dbb) | Nov 03, 2024 |
| Lenovo        | G700 20251                  | [3af4ad6599](https://linux-hardware.org/?probe=3af4ad6599) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | [9d4e69ab29](https://linux-hardware.org/?probe=9d4e69ab29) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | [a48e5acfb4](https://linux-hardware.org/?probe=a48e5acfb4) | Nov 01, 2024 |
| HP            | ProBook 4535s               | [f66c124f3a](https://linux-hardware.org/?probe=f66c124f3a) | Oct 31, 2024 |
| Apple         | MacBookPro8,1               | [3fe4d1a80a](https://linux-hardware.org/?probe=3fe4d1a80a) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| Apple         | MacBookPro9,2               | [91eb0db216](https://linux-hardware.org/?probe=91eb0db216) | Oct 30, 2024 |
| HP            | Laptop 15s-eq2xxx           | [1755d407c9](https://linux-hardware.org/?probe=1755d407c9) | Oct 29, 2024 |
| HP            | Compaq 15                   | [fd2b849a08](https://linux-hardware.org/?probe=fd2b849a08) | Oct 28, 2024 |
| Apple         | MacBookPro9,2               | [59f6758081](https://linux-hardware.org/?probe=59f6758081) | Oct 25, 2024 |
| Apple         | MacBookAir7,2               | [73fb34d315](https://linux-hardware.org/?probe=73fb34d315) | Oct 25, 2024 |
| HUAWEI        | BOD-WXX9                    | [c4829d7d0c](https://linux-hardware.org/?probe=c4829d7d0c) | Oct 25, 2024 |
| HUAWEI        | BOHB-WAX9                   | [e114c5afe5](https://linux-hardware.org/?probe=e114c5afe5) | Oct 24, 2024 |
| Dell          | Latitude 7370               | [355bbe7ecc](https://linux-hardware.org/?probe=355bbe7ecc) | Oct 24, 2024 |
| Apple         | MacBookAir7,2               | [92672f3d2c](https://linux-hardware.org/?probe=92672f3d2c) | Oct 23, 2024 |
| Apple         | MacBookAir7,2               | [8bbb5c5a53](https://linux-hardware.org/?probe=8bbb5c5a53) | Oct 23, 2024 |
| HP            | ProBook 6465b               | [3afb9ebed6](https://linux-hardware.org/?probe=3afb9ebed6) | Oct 23, 2024 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [18058066d2](https://linux-hardware.org/?probe=18058066d2) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | [a899fd963a](https://linux-hardware.org/?probe=a899fd963a) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | [6c25a578b8](https://linux-hardware.org/?probe=6c25a578b8) | Oct 22, 2024 |
| Sony          | VPCEJ1Z1E                   | [d1da65abb4](https://linux-hardware.org/?probe=d1da65abb4) | Oct 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [76d8c86d01](https://linux-hardware.org/?probe=76d8c86d01) | Oct 22, 2024 |
| HUAWEI        | KLVL-WXX9                   | [faeb5479f8](https://linux-hardware.org/?probe=faeb5479f8) | Oct 21, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [e188597923](https://linux-hardware.org/?probe=e188597923) | Oct 19, 2024 |
| Apple         | MacBookAir7,2               | [f63adab3c7](https://linux-hardware.org/?probe=f63adab3c7) | Oct 19, 2024 |
| Fujitsu       | LIFEBOOK A530               | [afb324991b](https://linux-hardware.org/?probe=afb324991b) | Oct 18, 2024 |
| Fujitsu       | LIFEBOOK A530               | [3337802835](https://linux-hardware.org/?probe=3337802835) | Oct 18, 2024 |
| Apple         | MacBookPro8,1               | [83508d3840](https://linux-hardware.org/?probe=83508d3840) | Oct 17, 2024 |
| Samsung       | 940XFG                      | [741f7a6544](https://linux-hardware.org/?probe=741f7a6544) | Oct 17, 2024 |
| Apple         | MacBook6,1                  | [d3b5f5da93](https://linux-hardware.org/?probe=d3b5f5da93) | Oct 17, 2024 |
| HP            | Laptop 15s-eq2xxx           | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| Acer          | Aspire 7736                 | [be7f2e237f](https://linux-hardware.org/?probe=be7f2e237f) | Oct 15, 2024 |
| ASUSTek       | X555LPB                     | [2f3f2073da](https://linux-hardware.org/?probe=2f3f2073da) | Oct 14, 2024 |
| Acer          | Aspire 7736                 | [96c83e0281](https://linux-hardware.org/?probe=96c83e0281) | Oct 14, 2024 |
| Apple         | MacBookPro8,1               | [d2d644c166](https://linux-hardware.org/?probe=d2d644c166) | Oct 13, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [cee555c4f8](https://linux-hardware.org/?probe=cee555c4f8) | Oct 13, 2024 |
| Apple         | MacBookPro8,3               | [030dbaca80](https://linux-hardware.org/?probe=030dbaca80) | Oct 13, 2024 |
| Positivo      | VJF154                      | [dbd1be19a4](https://linux-hardware.org/?probe=dbd1be19a4) | Oct 12, 2024 |
| Positivo      | VJF154                      | [11a95affa0](https://linux-hardware.org/?probe=11a95affa0) | Oct 12, 2024 |
| Sony          | VPCEJ1Z1E                   | [627da18a5d](https://linux-hardware.org/?probe=627da18a5d) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | [8a25a02400](https://linux-hardware.org/?probe=8a25a02400) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [2db6bf65e8](https://linux-hardware.org/?probe=2db6bf65e8) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [a9cb352415](https://linux-hardware.org/?probe=a9cb352415) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | [ca109e5057](https://linux-hardware.org/?probe=ca109e5057) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [08d25ef16b](https://linux-hardware.org/?probe=08d25ef16b) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c5d0a8a4b](https://linux-hardware.org/?probe=6c5d0a8a4b) | Oct 12, 2024 |
| HP            | 15                          | [812b65f0fe](https://linux-hardware.org/?probe=812b65f0fe) | Oct 11, 2024 |
| Apple         | MacBook6,1                  | [3623e327b2](https://linux-hardware.org/?probe=3623e327b2) | Oct 11, 2024 |
| HP            | EliteBook 830 G5            | [64cebe30ad](https://linux-hardware.org/?probe=64cebe30ad) | Oct 10, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | [bf025aaa26](https://linux-hardware.org/?probe=bf025aaa26) | Oct 08, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [ecf4696b37](https://linux-hardware.org/?probe=ecf4696b37) | Oct 07, 2024 |
| Apple         | MacBookAir3,1               | [01cd6549a5](https://linux-hardware.org/?probe=01cd6549a5) | Oct 06, 2024 |
| Apple         | MacBookPro9,2               | [0f138dcac0](https://linux-hardware.org/?probe=0f138dcac0) | Oct 06, 2024 |
| HP            | EliteBook 830 G5            | [c8c6a6269b](https://linux-hardware.org/?probe=c8c6a6269b) | Oct 06, 2024 |
| ARCELIK       | 1M7-GNB1595B6I7             | [cbf522f76a](https://linux-hardware.org/?probe=cbf522f76a) | Oct 05, 2024 |
| Sony          | VPCEC3L1E                   | [748694aa38](https://linux-hardware.org/?probe=748694aa38) | Oct 05, 2024 |
| Positivo      | VJF154                      | [70bb906734](https://linux-hardware.org/?probe=70bb906734) | Oct 04, 2024 |
| Dell          | Latitude E6520              | [5af0de6a9c](https://linux-hardware.org/?probe=5af0de6a9c) | Oct 04, 2024 |
| Dell          | Precision 5530              | [7d736763e8](https://linux-hardware.org/?probe=7d736763e8) | Oct 04, 2024 |
| Alienware     | 17 R3                       | [b22f85d157](https://linux-hardware.org/?probe=b22f85d157) | Oct 03, 2024 |
| Samsung       | 900X3F                      | [12e6b46207](https://linux-hardware.org/?probe=12e6b46207) | Oct 03, 2024 |
| Samsung       | 900X3F                      | [5b7f51059a](https://linux-hardware.org/?probe=5b7f51059a) | Oct 03, 2024 |
| HP            | G60                         | [b2cbfa9c26](https://linux-hardware.org/?probe=b2cbfa9c26) | Oct 02, 2024 |
| HP            | Laptop 15-bw0xx             | [1046a844db](https://linux-hardware.org/?probe=1046a844db) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [bfd414e273](https://linux-hardware.org/?probe=bfd414e273) | Sep 30, 2024 |
| Dell          | Inspiron N5110              | [39053cddd2](https://linux-hardware.org/?probe=39053cddd2) | Sep 29, 2024 |
| Apple         | MacBookPro5,1               | [ea1547836b](https://linux-hardware.org/?probe=ea1547836b) | Sep 27, 2024 |
| Apple         | MacBookAir3,1               | [ce465db6d8](https://linux-hardware.org/?probe=ce465db6d8) | Sep 26, 2024 |
| realme        | RMNBXXXX                    | [a56e71a36d](https://linux-hardware.org/?probe=a56e71a36d) | Sep 25, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [eb1144d5d0](https://linux-hardware.org/?probe=eb1144d5d0) | Sep 23, 2024 |
| Apple         | MacBookPro9,2               | [d02c3ea8d2](https://linux-hardware.org/?probe=d02c3ea8d2) | Sep 22, 2024 |
| Apple         | MacBookPro9,2               | [de3ad3dcb2](https://linux-hardware.org/?probe=de3ad3dcb2) | Sep 22, 2024 |
| Acer          | Aspire E5-511G              | [eb212c1295](https://linux-hardware.org/?probe=eb212c1295) | Sep 21, 2024 |
| Samsung       | 900X3J                      | [84b81dc973](https://linux-hardware.org/?probe=84b81dc973) | Sep 19, 2024 |
| Apple         | MacBook6,1                  | [754a9d1a14](https://linux-hardware.org/?probe=754a9d1a14) | Sep 19, 2024 |
| Acer          | Nitro AN515-52              | [0bc35e551d](https://linux-hardware.org/?probe=0bc35e551d) | Sep 18, 2024 |
| Apple         | MacBookPro9,2               | [e386b9f60a](https://linux-hardware.org/?probe=e386b9f60a) | Sep 18, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [22c790176f](https://linux-hardware.org/?probe=22c790176f) | Sep 18, 2024 |
| Lenovo        | G400 20235                  | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| Acer          | Aspire E5-511G              | [0b1a846a69](https://linux-hardware.org/?probe=0b1a846a69) | Sep 17, 2024 |
| HP            | EliteBook 840 G1            | [a2f78f9d5a](https://linux-hardware.org/?probe=a2f78f9d5a) | Sep 17, 2024 |
| HP            | Pavilion 17                 | [fb7884d776](https://linux-hardware.org/?probe=fb7884d776) | Sep 16, 2024 |
| HP            | Pavilion dv6700             | [79316bc8bf](https://linux-hardware.org/?probe=79316bc8bf) | Sep 16, 2024 |
| Acer          | Aspire 5750                 | [d030037b8b](https://linux-hardware.org/?probe=d030037b8b) | Sep 14, 2024 |
| Acer          | Aspire 7745G                | [76a55f9bb1](https://linux-hardware.org/?probe=76a55f9bb1) | Sep 14, 2024 |
| Dell          | Inspiron 3721               | [dd0fd36c69](https://linux-hardware.org/?probe=dd0fd36c69) | Sep 14, 2024 |
| Lenovo        | V14 G2 ITL 82KA             | [156f5f004e](https://linux-hardware.org/?probe=156f5f004e) | Sep 13, 2024 |
| Apple         | MacBookPro11,3              | [ce91008479](https://linux-hardware.org/?probe=ce91008479) | Sep 13, 2024 |
| Dell          | XPS 13 9343                 | [ca52ff1c29](https://linux-hardware.org/?probe=ca52ff1c29) | Sep 13, 2024 |
| Alienware     | 17 R3                       | [d95edb94cd](https://linux-hardware.org/?probe=d95edb94cd) | Sep 13, 2024 |
| Toshiba       | Satellite L50-B             | [bb130f4634](https://linux-hardware.org/?probe=bb130f4634) | Sep 11, 2024 |
| Acer          | Aspire 5750                 | [0c7144d06b](https://linux-hardware.org/?probe=0c7144d06b) | Sep 10, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [cd6caa40b8](https://linux-hardware.org/?probe=cd6caa40b8) | Sep 10, 2024 |
| Lenovo        | B590 20206                  | [38ef54ca0c](https://linux-hardware.org/?probe=38ef54ca0c) | Sep 09, 2024 |
| Lenovo        | B590 20206                  | [3e57e1486e](https://linux-hardware.org/?probe=3e57e1486e) | Sep 09, 2024 |
| Sony          | SVF15A1B4E                  | [08c43f2d50](https://linux-hardware.org/?probe=08c43f2d50) | Sep 09, 2024 |
| Dell          | Inspiron 3721               | [8c75a1af97](https://linux-hardware.org/?probe=8c75a1af97) | Sep 05, 2024 |
| Dell          | Inspiron 3721               | [8a051dce97](https://linux-hardware.org/?probe=8a051dce97) | Sep 03, 2024 |
| Dell          | Latitude 5510               | [634228ff35](https://linux-hardware.org/?probe=634228ff35) | Sep 02, 2024 |
| Apple         | MacBookPro9,1               | [41e0375932](https://linux-hardware.org/?probe=41e0375932) | Sep 02, 2024 |
| Apple         | MacBookPro8,1               | [c1c6557769](https://linux-hardware.org/?probe=c1c6557769) | Sep 01, 2024 |
| Apple         | MacBookPro6,2               | [7a30d49834](https://linux-hardware.org/?probe=7a30d49834) | Sep 01, 2024 |
| Lenovo        | G50-70 20351                | [8175aeac94](https://linux-hardware.org/?probe=8175aeac94) | Aug 31, 2024 |
| Apple         | MacBookPro9,2               | [60e3c48bbc](https://linux-hardware.org/?probe=60e3c48bbc) | Aug 30, 2024 |
| ASUSTek       | TP300LA                     | [55fb687fea](https://linux-hardware.org/?probe=55fb687fea) | Aug 30, 2024 |
| Dell          | Latitude E5420              | [1aa4784afb](https://linux-hardware.org/?probe=1aa4784afb) | Aug 29, 2024 |
| ASUSTek       | 1015PX                      | [b83d98a551](https://linux-hardware.org/?probe=b83d98a551) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [9f47f2b01b](https://linux-hardware.org/?probe=9f47f2b01b) | Aug 29, 2024 |
| Gigabyte      | G5 GD                       | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [2aa427ea2b](https://linux-hardware.org/?probe=2aa427ea2b) | Aug 27, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [a0dc16409e](https://linux-hardware.org/?probe=a0dc16409e) | Aug 26, 2024 |
| Apple         | MacBookPro5,1               | [5add020da3](https://linux-hardware.org/?probe=5add020da3) | Aug 25, 2024 |
| Toshiba       | Satellite C660D             | [fb51658e06](https://linux-hardware.org/?probe=fb51658e06) | Aug 23, 2024 |
| MSI           | GF63 8RC                    | [ea6d76ec59](https://linux-hardware.org/?probe=ea6d76ec59) | Aug 23, 2024 |
| Apple         | MacBook4,1                  | [b366ec9d80](https://linux-hardware.org/?probe=b366ec9d80) | Aug 23, 2024 |
| Apple         | MacBookPro8,1               | [a8f4d7f114](https://linux-hardware.org/?probe=a8f4d7f114) | Aug 22, 2024 |
| Apple         | MacBookPro8,1               | [de194919c2](https://linux-hardware.org/?probe=de194919c2) | Aug 21, 2024 |
| Dell          | XPS 13 9343                 | [e9a7ac7834](https://linux-hardware.org/?probe=e9a7ac7834) | Aug 21, 2024 |
| Apple         | MacBookPro11,5              | [b31f952991](https://linux-hardware.org/?probe=b31f952991) | Aug 19, 2024 |
| Dell          | Inspiron 15-3567            | [5040de05ac](https://linux-hardware.org/?probe=5040de05ac) | Aug 18, 2024 |
| Apple         | MacBookPro8,1               | [b7eb460f7e](https://linux-hardware.org/?probe=b7eb460f7e) | Aug 17, 2024 |
| Apple         | MacBookPro8,1               | [dc84101f95](https://linux-hardware.org/?probe=dc84101f95) | Aug 17, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2ffa4f7ffc](https://linux-hardware.org/?probe=2ffa4f7ffc) | Aug 15, 2024 |
| Dell          | G15 5510                    | [bd868cf551](https://linux-hardware.org/?probe=bd868cf551) | Aug 15, 2024 |
| Apple         | MacBookAir1,1               | [46b20c4ffe](https://linux-hardware.org/?probe=46b20c4ffe) | Aug 10, 2024 |
| Apple         | MacBookAir4,2               | [463b931271](https://linux-hardware.org/?probe=463b931271) | Aug 08, 2024 |
| HP            | G56                         | [28f40c35e9](https://linux-hardware.org/?probe=28f40c35e9) | Aug 07, 2024 |
| HP            | Compaq 6730b (KE717AV)      | [c6ce1872c3](https://linux-hardware.org/?probe=c6ce1872c3) | Aug 07, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [9359d579a1](https://linux-hardware.org/?probe=9359d579a1) | Aug 07, 2024 |
| Lenovo        | Unknown                     | [f228fbc5ba](https://linux-hardware.org/?probe=f228fbc5ba) | Aug 04, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [bb3e675ece](https://linux-hardware.org/?probe=bb3e675ece) | Aug 04, 2024 |
| Lenovo        | G400 20235                  | [ffa298e6de](https://linux-hardware.org/?probe=ffa298e6de) | Aug 03, 2024 |
| Lenovo        | B50-80 80EW                 | [39cd7e2e3c](https://linux-hardware.org/?probe=39cd7e2e3c) | Aug 03, 2024 |
| Lenovo        | ThinkPad T480 20L6S0HG00    | [641f0fa927](https://linux-hardware.org/?probe=641f0fa927) | Aug 03, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [6332bb4a7c](https://linux-hardware.org/?probe=6332bb4a7c) | Jul 29, 2024 |
| HUAWEI        | BOM-WXX9                    | [00af61adcc](https://linux-hardware.org/?probe=00af61adcc) | Jul 29, 2024 |
| Google        | Dratini                     | [8bb5dafec1](https://linux-hardware.org/?probe=8bb5dafec1) | Jul 28, 2024 |
| MSI           | GP63 Leopard 8RE            | [fd419bc9ef](https://linux-hardware.org/?probe=fd419bc9ef) | Jul 27, 2024 |
| Unknown       | Unknown                     | [350031c0ed](https://linux-hardware.org/?probe=350031c0ed) | Jul 27, 2024 |
| Apple         | MacBookAir4,2               | [9d37505b50](https://linux-hardware.org/?probe=9d37505b50) | Jul 26, 2024 |
| Lenovo        | G460 20041                  | [67670a0f4a](https://linux-hardware.org/?probe=67670a0f4a) | Jul 25, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | [1e7a4734ce](https://linux-hardware.org/?probe=1e7a4734ce) | Jul 25, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | [c80f2e729d](https://linux-hardware.org/?probe=c80f2e729d) | Jul 23, 2024 |
| Lenovo        | B50-80 80EW                 | [1896ed136c](https://linux-hardware.org/?probe=1896ed136c) | Jul 23, 2024 |
| Apple         | MacBookPro6,2               | [72c27fa1c1](https://linux-hardware.org/?probe=72c27fa1c1) | Jul 23, 2024 |
| HP            | ENVY 17                     | [8d586d3909](https://linux-hardware.org/?probe=8d586d3909) | Jul 22, 2024 |
| HP            | ENVY 17                     | [f97fdd96f8](https://linux-hardware.org/?probe=f97fdd96f8) | Jul 22, 2024 |
| HP            | Pavilion 17                 | [ea65b65978](https://linux-hardware.org/?probe=ea65b65978) | Jul 22, 2024 |
| Sony          | VPCEB2H4E                   | [144fb934d0](https://linux-hardware.org/?probe=144fb934d0) | Jul 22, 2024 |
| Apple         | MacBookPro6,2               | [298b035882](https://linux-hardware.org/?probe=298b035882) | Jul 22, 2024 |
| HP            | ProBook 450 G3              | [2bac99deff](https://linux-hardware.org/?probe=2bac99deff) | Jul 21, 2024 |
| Lenovo        | G460 20041                  | [2baabb5540](https://linux-hardware.org/?probe=2baabb5540) | Jul 20, 2024 |
| HP            | 250 G5 Notebook PC          | [687e56399a](https://linux-hardware.org/?probe=687e56399a) | Jul 20, 2024 |
| Lenovo        | ThinkPad E480 20KN009QGE    | [96b86c74c8](https://linux-hardware.org/?probe=96b86c74c8) | Jul 19, 2024 |
| Dell          | Inspiron 3580               | [8ef4654d8c](https://linux-hardware.org/?probe=8ef4654d8c) | Jul 18, 2024 |
| Dell          | Inspiron 3583               | [dccbf42cb3](https://linux-hardware.org/?probe=dccbf42cb3) | Jul 16, 2024 |
| Apple         | MacBookPro9,2               | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Apple         | MacBookPro8,1               | [e673ae4869](https://linux-hardware.org/?probe=e673ae4869) | Jul 14, 2024 |
| Apple         | MacBookPro8,1               | [20850127a9](https://linux-hardware.org/?probe=20850127a9) | Jul 14, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [4da9ebe6b5](https://linux-hardware.org/?probe=4da9ebe6b5) | Jul 13, 2024 |
| Dell          | Inspiron 3580               | [7a2073b0b4](https://linux-hardware.org/?probe=7a2073b0b4) | Jul 13, 2024 |
| Apple         | MacBook6,1                  | [54ed747270](https://linux-hardware.org/?probe=54ed747270) | Jul 13, 2024 |
| HP            | G42                         | [1ab8c40d0d](https://linux-hardware.org/?probe=1ab8c40d0d) | Jul 11, 2024 |
| Apple         | MacBookPro9,1               | [5e25885998](https://linux-hardware.org/?probe=5e25885998) | Jul 09, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [fdb5740619](https://linux-hardware.org/?probe=fdb5740619) | Jul 08, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [344a3a1381](https://linux-hardware.org/?probe=344a3a1381) | Jul 08, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [389c663679](https://linux-hardware.org/?probe=389c663679) | Jul 08, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [72dc55770d](https://linux-hardware.org/?probe=72dc55770d) | Jul 08, 2024 |
| Apple         | MacBookPro8,3               | [7f3622744d](https://linux-hardware.org/?probe=7f3622744d) | Jul 07, 2024 |
| Apple         | MacBookPro8,3               | [bb167dd1e3](https://linux-hardware.org/?probe=bb167dd1e3) | Jul 07, 2024 |
| Compaq        | Presario CQ-17              | [ac298b1a45](https://linux-hardware.org/?probe=ac298b1a45) | Jul 04, 2024 |
| Dell          | Precision 7720              | [26f2413f41](https://linux-hardware.org/?probe=26f2413f41) | Jul 04, 2024 |
| Lenovo        | Y520-15IKBA 80WY            | [e3fc209866](https://linux-hardware.org/?probe=e3fc209866) | Jul 03, 2024 |
| Apple         | MacBookPro7,1               | [22f634f998](https://linux-hardware.org/?probe=22f634f998) | Jul 02, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [e09d0fb605](https://linux-hardware.org/?probe=e09d0fb605) | Jul 01, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [f91526c63f](https://linux-hardware.org/?probe=f91526c63f) | Jul 01, 2024 |
| HP            | Pavilion dv6                | [25259c90d4](https://linux-hardware.org/?probe=25259c90d4) | Jun 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bed62e6b3c](https://linux-hardware.org/?probe=bed62e6b3c) | Jun 26, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [c8bce44bed](https://linux-hardware.org/?probe=c8bce44bed) | Jun 26, 2024 |
| Samsung       | 305V4A/305V5A               | [e4f376bd36](https://linux-hardware.org/?probe=e4f376bd36) | Jun 26, 2024 |
| Apple         | MacBookPro5,5               | [85c379a6a8](https://linux-hardware.org/?probe=85c379a6a8) | Jun 25, 2024 |
| Dell          | Latitude E4310              | [c2303e5967](https://linux-hardware.org/?probe=c2303e5967) | Jun 25, 2024 |
| Dell          | Latitude E4310              | [f985372e98](https://linux-hardware.org/?probe=f985372e98) | Jun 25, 2024 |
| HP            | Pavilion dv2000 (GM691LA... | [de1b028bbb](https://linux-hardware.org/?probe=de1b028bbb) | Jun 24, 2024 |
| ASUSTek       | K42F                        | [384052ea34](https://linux-hardware.org/?probe=384052ea34) | Jun 24, 2024 |
| ASUSTek       | K42F                        | [7978cdf8b4](https://linux-hardware.org/?probe=7978cdf8b4) | Jun 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [6e291c60fd](https://linux-hardware.org/?probe=6e291c60fd) | Jun 22, 2024 |
| Acer          | Aspire A515-54              | [14565c27bf](https://linux-hardware.org/?probe=14565c27bf) | Jun 22, 2024 |
| Lenovo        | ThinkPad T530 2392CTO       | [e7921f65ce](https://linux-hardware.org/?probe=e7921f65ce) | Jun 20, 2024 |
| Dell          | Latitude E7440              | [5fc427cc24](https://linux-hardware.org/?probe=5fc427cc24) | Jun 20, 2024 |
| Dell          | Inspiron N4010              | [dad60b8122](https://linux-hardware.org/?probe=dad60b8122) | Jun 20, 2024 |
| Apple         | MacBookPro9,2               | [59ab2f562b](https://linux-hardware.org/?probe=59ab2f562b) | Jun 19, 2024 |
| Apple         | MacBookPro9,2               | [c2e291249c](https://linux-hardware.org/?probe=c2e291249c) | Jun 19, 2024 |
| Apple         | MacBookAir7,2               | [e381ac4c82](https://linux-hardware.org/?probe=e381ac4c82) | Jun 19, 2024 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [f476dc9a4c](https://linux-hardware.org/?probe=f476dc9a4c) | Jun 18, 2024 |
| Dell          | System XPS L502X            | [58023857ae](https://linux-hardware.org/?probe=58023857ae) | Jun 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [14aecfba4d](https://linux-hardware.org/?probe=14aecfba4d) | Jun 16, 2024 |
| Dell          | Latitude 5424 Rugged        | [8ce01f0186](https://linux-hardware.org/?probe=8ce01f0186) | Jun 16, 2024 |
| Dell          | XPS 15 9500                 | [36b06bd4db](https://linux-hardware.org/?probe=36b06bd4db) | Jun 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e2f4b2305a](https://linux-hardware.org/?probe=e2f4b2305a) | Jun 15, 2024 |
| ASUSTek       | G750JS                      | [1be0b00e6a](https://linux-hardware.org/?probe=1be0b00e6a) | Jun 15, 2024 |
| Dell          | Latitude 5424 Rugged        | [2286699120](https://linux-hardware.org/?probe=2286699120) | Jun 14, 2024 |
| Chuwi         | UBook XPro                  | [1a9ca58ced](https://linux-hardware.org/?probe=1a9ca58ced) | Jun 13, 2024 |
| ASUSTek       | K501UX                      | [ccf68ea2d8](https://linux-hardware.org/?probe=ccf68ea2d8) | Jun 13, 2024 |
| Myway         | U1306i                      | [a029a374de](https://linux-hardware.org/?probe=a029a374de) | Jun 12, 2024 |
| HP            | EliteBook 8460p             | [ef3581ab2b](https://linux-hardware.org/?probe=ef3581ab2b) | Jun 12, 2024 |
| Google        | Nospike                     | [da6fe22637](https://linux-hardware.org/?probe=da6fe22637) | Jun 12, 2024 |
| Google        | Nospike                     | [86096b4ac8](https://linux-hardware.org/?probe=86096b4ac8) | Jun 11, 2024 |
| Apple         | MacBookPro7,1               | [cbccdbbf42](https://linux-hardware.org/?probe=cbccdbbf42) | Jun 10, 2024 |
| HP            | Compaq Presario CQ61        | [ab0cc4ab6b](https://linux-hardware.org/?probe=ab0cc4ab6b) | Jun 09, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [f30cff4982](https://linux-hardware.org/?probe=f30cff4982) | Jun 09, 2024 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [2bde6824fc](https://linux-hardware.org/?probe=2bde6824fc) | Jun 09, 2024 |
| ASUSTek       | X45U                        | [21e364e5a7](https://linux-hardware.org/?probe=21e364e5a7) | Jun 07, 2024 |
| Dell          | Latitude E6440              | [74814a37e4](https://linux-hardware.org/?probe=74814a37e4) | Jun 05, 2024 |
| HP            | ProBook 450 G3              | [14d13ac22c](https://linux-hardware.org/?probe=14d13ac22c) | Jun 03, 2024 |
| Lenovo        | V580c 20160                 | [7895c2caac](https://linux-hardware.org/?probe=7895c2caac) | Jun 03, 2024 |
| ASUSTek       | X555LAB                     | [93f930012f](https://linux-hardware.org/?probe=93f930012f) | Jun 02, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [a627db0998](https://linux-hardware.org/?probe=a627db0998) | Jun 02, 2024 |
| Apple         | MacBookAir5,2               | [11cbeead14](https://linux-hardware.org/?probe=11cbeead14) | May 31, 2024 |
| Dell          | Latitude E6320              | [356970f66c](https://linux-hardware.org/?probe=356970f66c) | May 30, 2024 |
| Apple         | MacBookPro8,1               | [b545c96334](https://linux-hardware.org/?probe=b545c96334) | May 28, 2024 |
| HP            | 15 Notebook PC              | [640586659d](https://linux-hardware.org/?probe=640586659d) | May 24, 2024 |
| HP            | 15 Notebook PC              | [174405df46](https://linux-hardware.org/?probe=174405df46) | May 24, 2024 |
| Apple         | MacBookPro8,2               | [2919242003](https://linux-hardware.org/?probe=2919242003) | May 23, 2024 |
| HP            | ProBook 450 G3              | [5a3bf3b0e5](https://linux-hardware.org/?probe=5a3bf3b0e5) | May 23, 2024 |
| Apple         | MacBookPro5,3               | [67d2c0a830](https://linux-hardware.org/?probe=67d2c0a830) | May 23, 2024 |
| Apple         | MacBookPro5,3               | [8789f1352d](https://linux-hardware.org/?probe=8789f1352d) | May 23, 2024 |
| Dell          | Inspiron 3442               | [3fa98588d7](https://linux-hardware.org/?probe=3fa98588d7) | May 20, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [e010a46aaa](https://linux-hardware.org/?probe=e010a46aaa) | May 20, 2024 |
| Apple         | MacBookPro9,1               | [81ca91875c](https://linux-hardware.org/?probe=81ca91875c) | May 19, 2024 |
| Apple         | MacBookPro9,1               | [9af9e45749](https://linux-hardware.org/?probe=9af9e45749) | May 19, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [ef53a24225](https://linux-hardware.org/?probe=ef53a24225) | May 19, 2024 |
| Lenovo        | U41-70 80JV                 | [5570ce9cbf](https://linux-hardware.org/?probe=5570ce9cbf) | May 18, 2024 |
| HP            | Compaq 6730b (KE717AV)      | [3832c9ecea](https://linux-hardware.org/?probe=3832c9ecea) | May 14, 2024 |
| HP            | Victus by Gaming Laptop ... | [2b749bf5c4](https://linux-hardware.org/?probe=2b749bf5c4) | May 14, 2024 |
| HP            | Pavilion 17                 | [1a80d822d4](https://linux-hardware.org/?probe=1a80d822d4) | May 14, 2024 |
| HP            | Pavilion g4                 | [e4d725eba3](https://linux-hardware.org/?probe=e4d725eba3) | May 11, 2024 |
| Apple         | MacBookPro9,2               | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
| Dell          | Latitude E6320              | [3d34ee9056](https://linux-hardware.org/?probe=3d34ee9056) | May 10, 2024 |
| Dell          | Inspiron 3481               | [78cf24846f](https://linux-hardware.org/?probe=78cf24846f) | May 09, 2024 |
| Packard Be... | EasyNote LM81               | [0ea4d18648](https://linux-hardware.org/?probe=0ea4d18648) | May 06, 2024 |
| Samsung       | 550XDA                      | [1ea7dfb8ae](https://linux-hardware.org/?probe=1ea7dfb8ae) | May 06, 2024 |
| Apple         | MacBookPro11,4              | [3c0f7c8c00](https://linux-hardware.org/?probe=3c0f7c8c00) | May 06, 2024 |
| HP            | EliteBook 830 G5            | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| HP            | EliteBook 830 G5            | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| Apple         | MacBookAir4,1               | [2e67b6ba22](https://linux-hardware.org/?probe=2e67b6ba22) | May 04, 2024 |
| Lenovo        | ThinkPad T530 2429HR5       | [c5640e6fae](https://linux-hardware.org/?probe=c5640e6fae) | May 04, 2024 |
| Dell          | Latitude 5490               | [b31473028c](https://linux-hardware.org/?probe=b31473028c) | May 04, 2024 |
| Packard Be... | EasyNote LM81               | [44ead9f439](https://linux-hardware.org/?probe=44ead9f439) | May 03, 2024 |
| Google        | Nospike                     | [549d690ae1](https://linux-hardware.org/?probe=549d690ae1) | May 02, 2024 |
| Dell          | Latitude 5490               | [c83e9f5562](https://linux-hardware.org/?probe=c83e9f5562) | May 01, 2024 |
| Lenovo        | IdeaPad P400 Touch 20211    | [cacd80cba3](https://linux-hardware.org/?probe=cacd80cba3) | May 01, 2024 |
| HP            | ProBook 470 G5              | [8ba873e85d](https://linux-hardware.org/?probe=8ba873e85d) | Apr 30, 2024 |
| MSI           | GT62VR 6RE                  | [b7768b7ee9](https://linux-hardware.org/?probe=b7768b7ee9) | Apr 28, 2024 |
| HP            | EliteBook 8440p             | [0dbed15c85](https://linux-hardware.org/?probe=0dbed15c85) | Apr 27, 2024 |
| HUAWEI        | KPL-W0X                     | [0ce65136da](https://linux-hardware.org/?probe=0ce65136da) | Apr 27, 2024 |
| Apple         | MacBook5,1                  | [8da3b01d13](https://linux-hardware.org/?probe=8da3b01d13) | Apr 26, 2024 |
| HP            | EliteBook 745 G4            | [f38a6451f0](https://linux-hardware.org/?probe=f38a6451f0) | Apr 24, 2024 |
| HP            | Pavilion dv6                | [c8d73c3a23](https://linux-hardware.org/?probe=c8d73c3a23) | Apr 24, 2024 |
| HP            | Pavilion dv6                | [08f01fc7ed](https://linux-hardware.org/?probe=08f01fc7ed) | Apr 24, 2024 |
| Acer          | Aspire A515-43              | [ff74a6262e](https://linux-hardware.org/?probe=ff74a6262e) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | [674850b624](https://linux-hardware.org/?probe=674850b624) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | [c7cbc009ef](https://linux-hardware.org/?probe=c7cbc009ef) | Apr 23, 2024 |
| Acer          | Aspire 5750G                | [39ed7553a3](https://linux-hardware.org/?probe=39ed7553a3) | Apr 23, 2024 |
| TECNO         | MEGABOOK T1                 | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Apple         | MacBookPro11,1              | [3f4e9ae066](https://linux-hardware.org/?probe=3f4e9ae066) | Apr 21, 2024 |
| Apple         | MacBookPro11,1              | [e70b7338c2](https://linux-hardware.org/?probe=e70b7338c2) | Apr 21, 2024 |
| Acer          | Aspire 5750                 | [9e2621b213](https://linux-hardware.org/?probe=9e2621b213) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8740fd113c](https://linux-hardware.org/?probe=8740fd113c) | Apr 19, 2024 |
| HP            | Pavilion Notebook           | [8b925ca8f0](https://linux-hardware.org/?probe=8b925ca8f0) | Apr 19, 2024 |
| ASUSTek       | K42F                        | [d127923f98](https://linux-hardware.org/?probe=d127923f98) | Apr 17, 2024 |
| HP            | Pavilion x2 Detachable      | [9e5556a266](https://linux-hardware.org/?probe=9e5556a266) | Apr 17, 2024 |
| Apple         | MacBookPro16,1              | [40fd2c63cb](https://linux-hardware.org/?probe=40fd2c63cb) | Apr 16, 2024 |
| DEPO Compu... | W25CEW                      | [6653a2975d](https://linux-hardware.org/?probe=6653a2975d) | Apr 15, 2024 |
| Apple         | MacBookPro9,2               | [5a62c14a1f](https://linux-hardware.org/?probe=5a62c14a1f) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | [97f0209510](https://linux-hardware.org/?probe=97f0209510) | Apr 14, 2024 |
| Acer          | Aspire 6935                 | [d26ee0494f](https://linux-hardware.org/?probe=d26ee0494f) | Apr 13, 2024 |
| Apple         | MacBookPro8,2               | [e57c02860c](https://linux-hardware.org/?probe=e57c02860c) | Apr 13, 2024 |
| Acer          | Aspire 5750                 | [f64263bd19](https://linux-hardware.org/?probe=f64263bd19) | Apr 12, 2024 |
| Apple         | MacBookAir7,2               | [569f9614a5](https://linux-hardware.org/?probe=569f9614a5) | Apr 12, 2024 |
| HP            | ProBook 6360b               | [81b9d0706b](https://linux-hardware.org/?probe=81b9d0706b) | Apr 11, 2024 |
| Apple         | MacBookPro8,2               | [461d5dfd8d](https://linux-hardware.org/?probe=461d5dfd8d) | Apr 11, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [35b206d8f8](https://linux-hardware.org/?probe=35b206d8f8) | Apr 10, 2024 |
| HP            | EliteBook 745 G4            | [0d92302707](https://linux-hardware.org/?probe=0d92302707) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | [ac137b7cb7](https://linux-hardware.org/?probe=ac137b7cb7) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | [e964beb301](https://linux-hardware.org/?probe=e964beb301) | Apr 09, 2024 |
| Apple         | MacBookPro5,4               | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [9099f440bc](https://linux-hardware.org/?probe=9099f440bc) | Apr 08, 2024 |
| Apple         | MacBookPro8,1               | [7efef6a0ae](https://linux-hardware.org/?probe=7efef6a0ae) | Apr 07, 2024 |
| Apple         | MacBookPro8,1               | [d28398beb7](https://linux-hardware.org/?probe=d28398beb7) | Apr 07, 2024 |
| Dell          | XPS 15 9570                 | [ccdb5dcad9](https://linux-hardware.org/?probe=ccdb5dcad9) | Apr 07, 2024 |
| Apple         | MacBookPro9,2               | [a90b694613](https://linux-hardware.org/?probe=a90b694613) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | [27d64e5b3c](https://linux-hardware.org/?probe=27d64e5b3c) | Apr 05, 2024 |
| Apple         | MacBookPro8,1               | [733d6c6e2b](https://linux-hardware.org/?probe=733d6c6e2b) | Apr 05, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [3d64dfc3a9](https://linux-hardware.org/?probe=3d64dfc3a9) | Apr 04, 2024 |
| Acer          | Aspire 5750                 | [e2cef27ef8](https://linux-hardware.org/?probe=e2cef27ef8) | Apr 03, 2024 |
| HP            | Pavilion dv7                | [483e1957a4](https://linux-hardware.org/?probe=483e1957a4) | Apr 02, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [fe5490324f](https://linux-hardware.org/?probe=fe5490324f) | Apr 01, 2024 |
| HP            | Pavilion dv7                | [a86e8cccf5](https://linux-hardware.org/?probe=a86e8cccf5) | Mar 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b68181d354](https://linux-hardware.org/?probe=b68181d354) | Mar 29, 2024 |
| Dell          | Inspiron 5423               | [0c6c4c6a58](https://linux-hardware.org/?probe=0c6c4c6a58) | Mar 29, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | [71c868292f](https://linux-hardware.org/?probe=71c868292f) | Mar 27, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | [01d1ef9c31](https://linux-hardware.org/?probe=01d1ef9c31) | Mar 26, 2024 |
| Lenovo        | ThinkPad T410 2537CQ7       | [8b91ec68dd](https://linux-hardware.org/?probe=8b91ec68dd) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | [3e86099c28](https://linux-hardware.org/?probe=3e86099c28) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | [598015ca49](https://linux-hardware.org/?probe=598015ca49) | Mar 24, 2024 |
| Samsung       | 535U3C                      | [6b29450ac6](https://linux-hardware.org/?probe=6b29450ac6) | Mar 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [20d2290d1c](https://linux-hardware.org/?probe=20d2290d1c) | Mar 23, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [e5c5d49216](https://linux-hardware.org/?probe=e5c5d49216) | Mar 22, 2024 |
| HP            | ProBook 450 G3              | [a32e851ddd](https://linux-hardware.org/?probe=a32e851ddd) | Mar 21, 2024 |
| HP            | ENVY 17                     | [0ee4da384d](https://linux-hardware.org/?probe=0ee4da384d) | Mar 20, 2024 |
| MSI           | GE70 2QE                    | [31b45c6de7](https://linux-hardware.org/?probe=31b45c6de7) | Mar 17, 2024 |
| HP            | Laptop 17-by3xxx            | [430290e97d](https://linux-hardware.org/?probe=430290e97d) | Mar 17, 2024 |
| Dell          | Latitude E6420              | [dc953135d3](https://linux-hardware.org/?probe=dc953135d3) | Mar 16, 2024 |
| Dell          | Latitude E7240              | [d159f296d4](https://linux-hardware.org/?probe=d159f296d4) | Mar 16, 2024 |
| ASUSTek       | X541UAK                     | [4b33512569](https://linux-hardware.org/?probe=4b33512569) | Mar 16, 2024 |
| Dell          | Latitude E7470              | [4addfb5619](https://linux-hardware.org/?probe=4addfb5619) | Mar 14, 2024 |
| Dell          | Latitude E7470              | [fbf1fe3963](https://linux-hardware.org/?probe=fbf1fe3963) | Mar 14, 2024 |
| Acer          | Aspire E5-573G              | [36653be57c](https://linux-hardware.org/?probe=36653be57c) | Mar 13, 2024 |
| ASUSTek       | X555LAB                     | [8b2310099c](https://linux-hardware.org/?probe=8b2310099c) | Mar 13, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [cfb2591a20](https://linux-hardware.org/?probe=cfb2591a20) | Mar 12, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [9160e106f1](https://linux-hardware.org/?probe=9160e106f1) | Mar 12, 2024 |
| Apple         | MacBookAir7,2               | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| ASUSTek       | X541UAK                     | [8b527dc9c9](https://linux-hardware.org/?probe=8b527dc9c9) | Mar 09, 2024 |
| HP            | ENVY Notebook               | [6ab7868737](https://linux-hardware.org/?probe=6ab7868737) | Mar 08, 2024 |
| Apple         | MacBookPro11,2              | [486387c7ef](https://linux-hardware.org/?probe=486387c7ef) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | [f701ce67f5](https://linux-hardware.org/?probe=f701ce67f5) | Mar 07, 2024 |
| Apple         | MacBookAir7,2               | [4c046066f7](https://linux-hardware.org/?probe=4c046066f7) | Mar 05, 2024 |
| Lenovo        | ThinkPad X250 20CLS3NA00    | [ecea244114](https://linux-hardware.org/?probe=ecea244114) | Mar 03, 2024 |
| Unknown       | Unknown                     | [2ca2d631cc](https://linux-hardware.org/?probe=2ca2d631cc) | Mar 02, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [d7d8cc5cc7](https://linux-hardware.org/?probe=d7d8cc5cc7) | Mar 02, 2024 |
| HP            | ProBook 4540s               | [46cdfe37d6](https://linux-hardware.org/?probe=46cdfe37d6) | Mar 02, 2024 |
| HP            | ProBook 4540s               | [ec5752452f](https://linux-hardware.org/?probe=ec5752452f) | Mar 02, 2024 |
| Apple         | MacBookPro5,4               | [681e76d909](https://linux-hardware.org/?probe=681e76d909) | Feb 29, 2024 |
| Apple         | MacBookPro5,4               | [ca45519759](https://linux-hardware.org/?probe=ca45519759) | Feb 29, 2024 |
| UNOWHY        | Y13G011S4EI                 | [f785899192](https://linux-hardware.org/?probe=f785899192) | Feb 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [11a760c545](https://linux-hardware.org/?probe=11a760c545) | Feb 28, 2024 |
| HP            | 15                          | [6fb113d856](https://linux-hardware.org/?probe=6fb113d856) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [49ac7f8a77](https://linux-hardware.org/?probe=49ac7f8a77) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
| HUAWEI        | KLVL-WXX9                   | [b1c31d32ab](https://linux-hardware.org/?probe=b1c31d32ab) | Feb 27, 2024 |
| ASUSTek       | X441UA                      | [1185900ace](https://linux-hardware.org/?probe=1185900ace) | Feb 26, 2024 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [61e571e08f](https://linux-hardware.org/?probe=61e571e08f) | Feb 26, 2024 |
| Acer          | TravelMate P256-MG          | [abcfd5362f](https://linux-hardware.org/?probe=abcfd5362f) | Feb 25, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [ca33f4c1c6](https://linux-hardware.org/?probe=ca33f4c1c6) | Feb 25, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [6d31b35e19](https://linux-hardware.org/?probe=6d31b35e19) | Feb 25, 2024 |
| Apple         | MacBook5,1                  | [be026cabc8](https://linux-hardware.org/?probe=be026cabc8) | Feb 24, 2024 |
| Acer          | Swift SF314-43              | [56b060901d](https://linux-hardware.org/?probe=56b060901d) | Feb 23, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [83bf2661f0](https://linux-hardware.org/?probe=83bf2661f0) | Feb 23, 2024 |
| Apple         | MacBookAir7,2               | [627c4721b6](https://linux-hardware.org/?probe=627c4721b6) | Feb 21, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [96fb9606bf](https://linux-hardware.org/?probe=96fb9606bf) | Feb 20, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [520188b3c6](https://linux-hardware.org/?probe=520188b3c6) | Feb 20, 2024 |
| HP            | ProBook 450 G1              | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| Apple         | MacBookAir6,1               | [f11ff820e7](https://linux-hardware.org/?probe=f11ff820e7) | Feb 18, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [b5bad706ef](https://linux-hardware.org/?probe=b5bad706ef) | Feb 15, 2024 |
| HP            | 245 G8                      | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Dell          | Vostro 1540                 | [ed9ed14ad8](https://linux-hardware.org/?probe=ed9ed14ad8) | Feb 14, 2024 |
| HP            | ZBook 15                    | [bcb41f3b4c](https://linux-hardware.org/?probe=bcb41f3b4c) | Feb 14, 2024 |
| MSI           | GF72VR 7RF                  | [8fb108b426](https://linux-hardware.org/?probe=8fb108b426) | Feb 13, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d1856c355f](https://linux-hardware.org/?probe=d1856c355f) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [498af1a9a2](https://linux-hardware.org/?probe=498af1a9a2) | Feb 06, 2024 |
| Teclast       | F7                          | [04b33deb97](https://linux-hardware.org/?probe=04b33deb97) | Feb 04, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [fdc21a05c2](https://linux-hardware.org/?probe=fdc21a05c2) | Feb 02, 2024 |
| Acer          | AOD255                      | [43304c651c](https://linux-hardware.org/?probe=43304c651c) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| HP            | Pavilion g6                 | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Apple         | MacBookPro7,1               | [973c263365](https://linux-hardware.org/?probe=973c263365) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK E734               | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Acer          | Aspire E5-571               | [6ebe6ae5be](https://linux-hardware.org/?probe=6ebe6ae5be) | Jan 28, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Dell          | Latitude E7240              | [d8e5d4a8da](https://linux-hardware.org/?probe=d8e5d4a8da) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [34369cc7eb](https://linux-hardware.org/?probe=34369cc7eb) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [d48bdbaec0](https://linux-hardware.org/?probe=d48bdbaec0) | Jan 24, 2024 |
| Acer          | Aspire E5-573G              | [14eec10d5e](https://linux-hardware.org/?probe=14eec10d5e) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Apple         | MacBook6,1                  | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| Apple         | MacBookPro9,2               | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Apple         | MacBook5,1                  | [75835b3764](https://linux-hardware.org/?probe=75835b3764) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [c3a6a2da37](https://linux-hardware.org/?probe=c3a6a2da37) | Jan 09, 2024 |
| Apple         | MacBook5,1                  | [3a4a960ff8](https://linux-hardware.org/?probe=3a4a960ff8) | Jan 06, 2024 |
| Apple         | MacBookPro7,1               | [75fc0fa74a](https://linux-hardware.org/?probe=75fc0fa74a) | Jan 06, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | [deadd2cf3d](https://linux-hardware.org/?probe=deadd2cf3d) | Jan 05, 2024 |
| HP            | Laptop 17-by3xxx            | [32486bf070](https://linux-hardware.org/?probe=32486bf070) | Jan 04, 2024 |
| Dell          | Latitude E7440              | [75ba78537c](https://linux-hardware.org/?probe=75ba78537c) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| Medion        | E11202                      | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Positivo      | C4128A-15                   | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Medion        | E11202                      | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| Acer          | Swift SFX14-41G             | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| THTF          | WUJIE 14                    | [c402523a2c](https://linux-hardware.org/?probe=c402523a2c) | Dec 25, 2023 |
| THTF          | WUJIE 14                    | [39ee354a27](https://linux-hardware.org/?probe=39ee354a27) | Dec 25, 2023 |
| Medion        | E11202                      | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | X555LAB                     | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Acer          | Aspire 4736Z                | [38866fae79](https://linux-hardware.org/?probe=38866fae79) | Dec 17, 2023 |
| Dell          | Precision 7560              | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [abc0a9283d](https://linux-hardware.org/?probe=abc0a9283d) | Dec 14, 2023 |
| ASUSTek       | X75A1                       | [e7d274ca96](https://linux-hardware.org/?probe=e7d274ca96) | Dec 13, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Sony          | SVE11115ELW                 | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [4c18329d9d](https://linux-hardware.org/?probe=4c18329d9d) | Dec 09, 2023 |
| HP            | Laptop 15-dw3xxx            | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| Dell          | Inspiron 15-3552            | [8ca2d01e7c](https://linux-hardware.org/?probe=8ca2d01e7c) | Dec 05, 2023 |
| Acer          | Aspire 4736Z                | [844b16d408](https://linux-hardware.org/?probe=844b16d408) | Dec 03, 2023 |
| HP            | EliteBook 840 G3            | [fa8d37e46b](https://linux-hardware.org/?probe=fa8d37e46b) | Nov 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf1e883f11](https://linux-hardware.org/?probe=cf1e883f11) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| Apple         | MacBookPro5,5               | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| Fujitsu       | LIFEBOOK E780               | [d3a64f5368](https://linux-hardware.org/?probe=d3a64f5368) | Nov 16, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| Alienware     | 15 R3                       | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| HP            | 245 G8                      | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [9b881d355c](https://linux-hardware.org/?probe=9b881d355c) | Nov 09, 2023 |
| Dell          | Vostro 3500                 | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| Dell          | G7 7500                     | [91adca1093](https://linux-hardware.org/?probe=91adca1093) | Nov 07, 2023 |
| Timi          | Redmi G 2022                | [f8cecbac55](https://linux-hardware.org/?probe=f8cecbac55) | Nov 07, 2023 |
| ASUSTek       | X555LAB                     | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| Dell          | G7 7500                     | [3678c5437b](https://linux-hardware.org/?probe=3678c5437b) | Nov 06, 2023 |
| Apple         | MacBookPro11,1              | [2d84377719](https://linux-hardware.org/?probe=2d84377719) | Nov 06, 2023 |
| HP            | 245 G8                      | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| HP            | ProBook 6545b               | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| Acer          | Aspire E5-551G              | [f8e737dbde](https://linux-hardware.org/?probe=f8e737dbde) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| Alienware     | 14                          | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| Dell          | Inspiron 1545               | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [300d56f39e](https://linux-hardware.org/?probe=300d56f39e) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [29a362f501](https://linux-hardware.org/?probe=29a362f501) | Oct 29, 2023 |
| Apple         | MacBook7,1                  | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| Dell          | Latitude E6520              | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| Dell          | Latitude E6400              | [250c9ddcfe](https://linux-hardware.org/?probe=250c9ddcfe) | Oct 24, 2023 |
| Apple         | MacBookPro6,2               | [89f29afb19](https://linux-hardware.org/?probe=89f29afb19) | Oct 24, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Google        | Cave                        | [287887d308](https://linux-hardware.org/?probe=287887d308) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
| Apple         | MacBookPro6,2               | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| Apple         | MacBookPro5,3               | [1e3660c797](https://linux-hardware.org/?probe=1e3660c797) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | [3dde86d447](https://linux-hardware.org/?probe=3dde86d447) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | [87edaec977](https://linux-hardware.org/?probe=87edaec977) | Oct 17, 2023 |
| Acer          | Nitro AN517-54              | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Lenovo        | B570 1068FRG                | [e912de748b](https://linux-hardware.org/?probe=e912de748b) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| HP            | EliteBook 2570p             | [c41bac6f71](https://linux-hardware.org/?probe=c41bac6f71) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [ccc23328e5](https://linux-hardware.org/?probe=ccc23328e5) | Oct 07, 2023 |
| Dell          | Vostro 1510                 | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Dell          | Latitude E7270              | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | [e9478deeae](https://linux-hardware.org/?probe=e9478deeae) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [c8bbae1068](https://linux-hardware.org/?probe=c8bbae1068) | Sep 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary_7.1/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.2.0-33-generic     | 79        | 17.87%  |
| 6.8.0-40-generic     | 39        | 8.82%   |
| 6.5.0-41-generic     | 27        | 6.11%   |
| 6.5.0-35-generic     | 27        | 6.11%   |
| 6.5.0-28-generic     | 24        | 5.43%   |
| 6.8.0-45-generic     | 21        | 4.75%   |
| 6.8.0-48-generic     | 17        | 3.85%   |
| 6.8.0-47-generic     | 17        | 3.85%   |
| 6.8.0-49-generic     | 16        | 3.62%   |
| 6.5.0-27-generic     | 13        | 2.94%   |
| 6.5.0-26-generic     | 13        | 2.94%   |
| 6.5.0-21-generic     | 11        | 2.49%   |
| 6.2.0-39-generic     | 11        | 2.49%   |
| 6.5.0-25-generic     | 10        | 2.26%   |
| 6.5.0-15-generic     | 10        | 2.26%   |
| 6.2.0-36-generic     | 10        | 2.26%   |
| 6.2.0-34-generic     | 10        | 2.26%   |
| 6.5.0-44-generic     | 9         | 2.04%   |
| 6.2.0-37-generic     | 9         | 2.04%   |
| 6.5.0-45-generic     | 8         | 1.81%   |
| 6.8.0-52-generic     | 7         | 1.58%   |
| 6.5.0-14-generic     | 6         | 1.36%   |
| 6.2.0-35-generic     | 6         | 1.36%   |
| 6.8.0-51-generic     | 5         | 1.13%   |
| 6.5.0-18-generic     | 5         | 1.13%   |
| 6.8.0-60-generic     | 4         | 0.9%    |
| 6.5.0-17-generic     | 4         | 0.9%    |
| 6.8.0-87-generic     | 2         | 0.45%   |
| 6.8.0-83-generic     | 2         | 0.45%   |
| 6.8.0-50-generic     | 2         | 0.45%   |
| 6.2.0-26-generic     | 2         | 0.45%   |
| 5.15.0-58-generic    | 2         | 0.45%   |
| 6.8.0-85-generic     | 1         | 0.23%   |
| 6.8.0-79-generic     | 1         | 0.23%   |
| 6.8.0-64-generic     | 1         | 0.23%   |
| 6.8.0-59-generic     | 1         | 0.23%   |
| 6.8.0-57-generic     | 1         | 0.23%   |
| 6.7.3-060703-generic | 1         | 0.23%   |
| 6.5.7-060507-generic | 1         | 0.23%   |
| 6.5.5-x64v3-xanmod1  | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.0   | 165       | 38.82%  |
| 6.8.0   | 126       | 29.65%  |
| 6.2.0   | 125       | 29.41%  |
| 5.19.0  | 3         | 0.71%   |
| 5.15.0  | 2         | 0.47%   |
| 6.7.3   | 1         | 0.24%   |
| 6.5.7   | 1         | 0.24%   |
| 6.5.5   | 1         | 0.24%   |
| 6.13.6  | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5     | 167       | 39.29%  |
| 6.8     | 126       | 29.65%  |
| 6.2     | 125       | 29.41%  |
| 5.19    | 3         | 0.71%   |
| 5.15    | 2         | 0.47%   |
| 6.7     | 1         | 0.24%   |
| 6.13    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 412       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 410       | 99.51%  |
| KDE5     | 1         | 0.24%   |
| Unknown  | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 412       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 359       | 86.51%  |
| LightDM | 55        | 13.25%  |
| SDDM    | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 161       | 38.89%  |
| de_DE   | 55        | 13.29%  |
| ru_RU   | 39        | 9.42%   |
| es_ES   | 38        | 9.18%   |
| it_IT   | 24        | 5.8%    |
| fr_FR   | 19        | 4.59%   |
| pt_BR   | 15        | 3.62%   |
| en_GB   | 12        | 2.9%    |
| pl_PL   | 10        | 2.42%   |
| nl_NL   | 5         | 1.21%   |
| tr_TR   | 4         | 0.97%   |
| pt_PT   | 3         | 0.72%   |
| cs_CZ   | 3         | 0.72%   |
| uk_UA   | 2         | 0.48%   |
| sv_SE   | 2         | 0.48%   |
| id_ID   | 2         | 0.48%   |
| hu_HU   | 2         | 0.48%   |
| fi_FI   | 2         | 0.48%   |
| de_CH   | 2         | 0.48%   |
| da_DK   | 2         | 0.48%   |
| zh_TW   | 1         | 0.24%   |
| zh_CN   | 1         | 0.24%   |
| nb_NO   | 1         | 0.24%   |
| ja_JP   | 1         | 0.24%   |
| hr_HR   | 1         | 0.24%   |
| fr_CA   | 1         | 0.24%   |
| et_EE   | 1         | 0.24%   |
| es_AR   | 1         | 0.24%   |
| en_AU   | 1         | 0.24%   |
| el_GR   | 1         | 0.24%   |
| ar_EG   | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 377       | 90.84%  |
| EFI  | 38        | 9.16%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 387       | 93.25%  |
| Tmpfs   | 19        | 4.58%   |
| Xfs     | 4         | 0.96%   |
| Btrfs   | 4         | 0.96%   |
| Overlay | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 358       | 86.06%  |
| GPT     | 47        | 11.3%   |
| MBR     | 11        | 2.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 408       | 99.03%  |
| Yes       | 4         | 0.97%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 399       | 96.38%  |
| Yes       | 15        | 3.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Apple                | 94        | 22.82%  |
| Hewlett-Packard      | 72        | 17.48%  |
| Lenovo               | 68        | 16.5%   |
| Dell                 | 51        | 12.38%  |
| ASUSTek Computer     | 29        | 7.04%   |
| Acer                 | 22        | 5.34%   |
| HUAWEI               | 12        | 2.91%   |
| Samsung Electronics  | 9         | 2.18%   |
| Sony                 | 6         | 1.46%   |
| Toshiba              | 4         | 0.97%   |
| MSI                  | 4         | 0.97%   |
| Google               | 4         | 0.97%   |
| Unknown              | 4         | 0.97%   |
| Fujitsu              | 3         | 0.73%   |
| Alienware            | 3         | 0.73%   |
| Positivo             | 2         | 0.49%   |
| UNOWHY               | 1         | 0.24%   |
| UMAX                 | 1         | 0.24%   |
| TUXEDO               | 1         | 0.24%   |
| Timi                 | 1         | 0.24%   |
| THTF                 | 1         | 0.24%   |
| Thomson              | 1         | 0.24%   |
| TECNO Mobile Limited | 1         | 0.24%   |
| TECNO                | 1         | 0.24%   |
| Teclast              | 1         | 0.24%   |
| Star Labs            | 1         | 0.24%   |
| realme               | 1         | 0.24%   |
| Packard Bell         | 1         | 0.24%   |
| NEC Computers        | 1         | 0.24%   |
| Myway                | 1         | 0.24%   |
| Microtech            | 1         | 0.24%   |
| Medion               | 1         | 0.24%   |
| LTD Delovoy Office   | 1         | 0.24%   |
| HONOR                | 1         | 0.24%   |
| Gigabyte Technology  | 1         | 0.24%   |
| DEPO Computers       | 1         | 0.24%   |
| Compaq               | 1         | 0.24%   |
| Clevo                | 1         | 0.24%   |
| Chuwi                | 1         | 0.24%   |
| AZW                  | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                      | 15        | 3.64%   |
| Apple MacBookPro9,2                      | 13        | 3.16%   |
| Apple MacBookAir7,2                      | 12        | 2.91%   |
| Apple MacBookPro7,1                      | 6         | 1.46%   |
| Unknown                                  | 5         | 1.21%   |
| HP Pavilion 17                           | 4         | 0.97%   |
| Apple MacBookPro6,2                      | 4         | 0.97%   |
| HUAWEI BOM-WXX9                          | 3         | 0.73%   |
| HP ProBook 450 G3                        | 3         | 0.73%   |
| Apple MacBookPro9,1                      | 3         | 0.73%   |
| Apple MacBookPro8,2                      | 3         | 0.73%   |
| Apple MacBookPro5,5                      | 3         | 0.73%   |
| Apple MacBookPro11,1                     | 3         | 0.73%   |
| Apple MacBookAir3,1                      | 3         | 0.73%   |
| Toshiba Satellite L50-B                  | 2         | 0.49%   |
| Lenovo IdeaPad Slim 3 15IAH8 83ER        | 2         | 0.49%   |
| HUAWEI NBLB-WAX9N                        | 2         | 0.49%   |
| HUAWEI KLVL-WXX9                         | 2         | 0.49%   |
| HUAWEI BOD-WXX9                          | 2         | 0.49%   |
| HP ProBook 440 G8 Notebook PC            | 2         | 0.49%   |
| HP Pavilion Sleekbook 15 PC              | 2         | 0.49%   |
| HP Pavilion dv6                          | 2         | 0.49%   |
| HP Laptop 15s-eq2xxx                     | 2         | 0.49%   |
| HP ENVY 17                               | 2         | 0.49%   |
| HP EliteBook 840 G1                      | 2         | 0.49%   |
| HP 15                                    | 2         | 0.49%   |
| Google Nospike                           | 2         | 0.49%   |
| Dell Latitude E7440                      | 2         | 0.49%   |
| Dell Latitude E7240                      | 2         | 0.49%   |
| Dell Latitude E6520                      | 2         | 0.49%   |
| Dell Latitude E6420                      | 2         | 0.49%   |
| Dell Inspiron 5567                       | 2         | 0.49%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA | 2         | 0.49%   |
| Apple MacBookPro8,3                      | 2         | 0.49%   |
| Apple MacBookPro5,4                      | 2         | 0.49%   |
| Apple MacBookPro5,3                      | 2         | 0.49%   |
| Apple MacBookPro5,1                      | 2         | 0.49%   |
| Apple MacBookAir6,1                      | 2         | 0.49%   |
| Apple MacBookAir4,1                      | 2         | 0.49%   |
| Apple MacBook6,1                         | 2         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 25        | 6.07%   |
| Lenovo IdeaPad     | 23        | 5.58%   |
| Dell Latitude      | 23        | 5.58%   |
| Apple MacBookPro8  | 20        | 4.85%   |
| HP Pavilion        | 19        | 4.61%   |
| HP ProBook         | 16        | 3.88%   |
| Apple MacBookPro9  | 16        | 3.88%   |
| Acer Aspire        | 16        | 3.88%   |
| Dell Inspiron      | 15        | 3.64%   |
| HP EliteBook       | 12        | 2.91%   |
| Apple MacBookAir7  | 12        | 2.91%   |
| Apple MacBookPro5  | 10        | 2.43%   |
| ASUS VivoBook      | 7         | 1.7%    |
| Apple MacBookPro11 | 7         | 1.7%    |
| HP Laptop          | 6         | 1.46%   |
| Apple MacBookPro7  | 6         | 1.46%   |
| Unknown            | 5         | 1.21%   |
| Toshiba Satellite  | 4         | 0.97%   |
| HP ENVY            | 4         | 0.97%   |
| HP Compaq          | 4         | 0.97%   |
| Dell XPS           | 4         | 0.97%   |
| Apple MacBookPro6  | 4         | 0.97%   |
| HUAWEI BOM-WXX9    | 3         | 0.73%   |
| HP 15              | 3         | 0.73%   |
| Fujitsu LIFEBOOK   | 3         | 0.73%   |
| Dell Vostro        | 3         | 0.73%   |
| Dell Precision     | 3         | 0.73%   |
| Apple MacBookAir4  | 3         | 0.73%   |
| Apple MacBookAir3  | 3         | 0.73%   |
| Lenovo Yoga        | 2         | 0.49%   |
| HUAWEI NBLB-WAX9N  | 2         | 0.49%   |
| HUAWEI KLVL-WXX9   | 2         | 0.49%   |
| HUAWEI BOD-WXX9    | 2         | 0.49%   |
| Google Nospike     | 2         | 0.49%   |
| ASUS Zenbook       | 2         | 0.49%   |
| ASUS ASUS          | 2         | 0.49%   |
| Apple MacBookAir6  | 2         | 0.49%   |
| Apple MacBook6     | 2         | 0.49%   |
| Apple MacBook5     | 2         | 0.49%   |
| Apple MacBook4     | 2         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 49        | 11.89%  |
| 2011 | 40        | 9.71%   |
| 2021 | 34        | 8.25%   |
| 2013 | 34        | 8.25%   |
| 2010 | 33        | 8.01%   |
| 2014 | 26        | 6.31%   |
| 2020 | 23        | 5.58%   |
| 2016 | 23        | 5.58%   |
| 2018 | 22        | 5.34%   |
| 2017 | 20        | 4.85%   |
| 2009 | 20        | 4.85%   |
| 2015 | 18        | 4.37%   |
| 2023 | 16        | 3.88%   |
| 2022 | 14        | 3.4%    |
| 2008 | 14        | 3.4%    |
| 2006 | 12        | 2.91%   |
| 2019 | 10        | 2.43%   |
| 2024 | 2         | 0.49%   |
| 2025 | 1         | 0.24%   |
| 2007 | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 412       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 407       | 98.79%  |
| Enabled  | 5         | 1.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 407       | 98.79%  |
| Yes  | 5         | 1.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 176       | 42.31%  |
| 3.01-4.0    | 75        | 18.03%  |
| 16.01-24.0  | 72        | 17.31%  |
| 8.01-16.0   | 49        | 11.78%  |
| 32.01-64.0  | 16        | 3.85%   |
| 1.01-2.0    | 10        | 2.4%    |
| 2.01-3.0    | 9         | 2.16%   |
| 24.01-32.0  | 6         | 1.44%   |
| 64.01-256.0 | 3         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 180       | 40.54%  |
| 1.01-2.0  | 117       | 26.35%  |
| 3.01-4.0  | 78        | 17.57%  |
| 4.01-8.0  | 53        | 11.94%  |
| 0.51-1.0  | 10        | 2.25%   |
| 8.01-16.0 | 6         | 1.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 318       | 76.81%  |
| 2      | 86        | 20.77%  |
| 3      | 9         | 2.17%   |
| 4      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 251       | 60.92%  |
| Yes       | 161       | 39.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 328       | 79.42%  |
| No        | 85        | 20.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 409       | 99.27%  |
| No        | 3         | 0.73%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 365       | 88.59%  |
| No        | 47        | 11.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 68        | 16.5%   |
| Germany      | 56        | 13.59%  |
| Russia       | 30        | 7.28%   |
| Italy        | 23        | 5.58%   |
| Brazil       | 21        | 5.1%    |
| France       | 15        | 3.64%   |
| Spain        | 12        | 2.91%   |
| Poland       | 10        | 2.43%   |
| UK           | 9         | 2.18%   |
| Netherlands  | 9         | 2.18%   |
| Mexico       | 9         | 2.18%   |
| Indonesia    | 9         | 2.18%   |
| India        | 9         | 2.18%   |
| Canada       | 7         | 1.7%    |
| Switzerland  | 6         | 1.46%   |
| Sweden       | 6         | 1.46%   |
| Hungary      | 6         | 1.46%   |
| Chile        | 6         | 1.46%   |
| Austria      | 6         | 1.46%   |
| Argentina    | 5         | 1.21%   |
| Ukraine      | 4         | 0.97%   |
| Turkey       | 4         | 0.97%   |
| Romania      | 4         | 0.97%   |
| Morocco      | 4         | 0.97%   |
| Finland      | 4         | 0.97%   |
| Colombia     | 4         | 0.97%   |
| Australia    | 4         | 0.97%   |
| Greece       | 3         | 0.73%   |
| Czechia      | 3         | 0.73%   |
| Bulgaria     | 3         | 0.73%   |
| Belarus      | 3         | 0.73%   |
| Vietnam      | 2         | 0.49%   |
| Thailand     | 2         | 0.49%   |
| South Africa | 2         | 0.49%   |
| Serbia       | 2         | 0.49%   |
| Puerto Rico  | 2         | 0.49%   |
| Portugal     | 2         | 0.49%   |
| Peru         | 2         | 0.49%   |
| Norway       | 2         | 0.49%   |
| New Zealand  | 2         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 7         | 1.63%   |
| Budapest         | 5         | 1.16%   |
| Berlin           | 5         | 1.16%   |
| St Petersburg    | 4         | 0.93%   |
| Santiago         | 4         | 0.93%   |
| Munich           | 4         | 0.93%   |
| Warsaw           | 3         | 0.7%    |
| Vienna           | 3         | 0.7%    |
| Rio de Janeiro   | 3         | 0.7%    |
| Paris            | 3         | 0.7%    |
| Naples           | 3         | 0.7%    |
| Melbourne        | 3         | 0.7%    |
| Los Angeles      | 3         | 0.7%    |
| Hamburg          | 3         | 0.7%    |
| Yekaterinburg    | 2         | 0.47%   |
| Vitebsk          | 2         | 0.47%   |
| Temuco           | 2         | 0.47%   |
| Stockholm        | 2         | 0.47%   |
| Sarasota         | 2         | 0.47%   |
| San José        | 2         | 0.47%   |
| Rosenheim        | 2         | 0.47%   |
| Rome             | 2         | 0.47%   |
| Prague           | 2         | 0.47%   |
| Phoenix          | 2         | 0.47%   |
| Perm             | 2         | 0.47%   |
| Oslo             | 2         | 0.47%   |
| Milan            | 2         | 0.47%   |
| Mažeikiai       | 2         | 0.47%   |
| Madrid           | 2         | 0.47%   |
| Lima             | 2         | 0.47%   |
| Lille            | 2         | 0.47%   |
| Jakarta          | 2         | 0.47%   |
| Istanbul         | 2         | 0.47%   |
| Ho Chi Minh City | 2         | 0.47%   |
| Helsinki         | 2         | 0.47%   |
| Groningen        | 2         | 0.47%   |
| Delhi            | 2         | 0.47%   |
| Cuernavaca       | 2         | 0.47%   |
| Cleveland        | 2         | 0.47%   |
| Chelyabinsk      | 2         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 70        | 85     | 14.06%  |
| WDC                          | 37        | 43     | 7.43%   |
| Apple                        | 36        | 37     | 7.23%   |
| Toshiba                      | 35        | 41     | 7.03%   |
| Sandisk                      | 35        | 42     | 7.03%   |
| Seagate                      | 34        | 35     | 6.83%   |
| Kingston                     | 30        | 35     | 6.02%   |
| Crucial                      | 25        | 29     | 5.02%   |
| Unknown                      | 21        | 25     | 4.22%   |
| Hitachi                      | 14        | 16     | 2.81%   |
| SK hynix                     | 13        | 15     | 2.61%   |
| Intel                        | 12        | 17     | 2.41%   |
| KIOXIA                       | 9         | 13     | 1.81%   |
| HGST                         | 9         | 13     | 1.81%   |
| Phison Electronics           | 7         | 7      | 1.41%   |
| China                        | 7         | 9      | 1.41%   |
| Micron Technology            | 6         | 7      | 1.2%    |
| A-DATA Technology            | 6         | 6      | 1.2%    |
| Unknown                      | 6         | 7      | 1.2%    |
| Silicon Motion               | 5         | 5      | 1%      |
| LITEON                       | 5         | 5      | 1%      |
| Intenso                      | 4         | 4      | 0.8%    |
| SPCC                         | 3         | 3      | 0.6%    |
| Phison                       | 3         | 3      | 0.6%    |
| Patriot                      | 3         | 3      | 0.6%    |
| OWC                          | 3         | 3      | 0.6%    |
| Lexar                        | 3         | 3      | 0.6%    |
| Kingston Technology Company  | 3         | 3      | 0.6%    |
| Fanxiang                     | 3         | 3      | 0.6%    |
| Yangtze Memory Technologies  | 2         | 2      | 0.4%    |
| Union Memory                 | 2         | 4      | 0.4%    |
| Transcend                    | 2         | 3      | 0.4%    |
| Shenzhen Longsys Electronics | 2         | 2      | 0.4%    |
| PNY                          | 2         | 2      | 0.4%    |
| Netac                        | 2         | 2      | 0.4%    |
| LITEONIT                     | 2         | 2      | 0.4%    |
| Gigabyte Technology          | 2         | 2      | 0.4%    |
| Fujitsu                      | 2         | 2      | 0.4%    |
| Apacer                       | 2         | 2      | 0.4%    |
| XUM                          | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                               | 8         | 1.57%   |
| Apple SSD SM0128G 121GB                              | 8         | 1.57%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 1.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 6         | 1.18%   |
| Kingston SA400S37240G 240GB SSD                      | 6         | 1.18%   |
| Unknown                                              | 6         | 1.18%   |
| Seagate ST500LT012-1DG142 500GB                      | 5         | 0.98%   |
| Kingston SA400S37120G 120GB SSD                      | 5         | 0.98%   |
| Crucial CT240BX500SSD1 240GB                         | 5         | 0.98%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.78%   |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.78%   |
| Samsung SSD 850 EVO 500GB                            | 4         | 0.78%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 4         | 0.78%   |
| HGST HTS721010A9E630 1TB                             | 4         | 0.78%   |
| Crucial CT500MX500SSD1 500GB                         | 4         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 3         | 0.59%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 3         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 0.59%   |
| Sandisk WD_BLACK SN770 1TB                           | 3         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 3         | 0.59%   |
| SanDisk SSD PLUS 240GB                               | 3         | 0.59%   |
| Samsung SSD 870 EVO 1TB                              | 3         | 0.59%   |
| Samsung SSD 860 EVO 250GB                            | 3         | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 3         | 0.59%   |
| Samsung MZVL4512HBLU-00BTW 512GB                     | 3         | 0.59%   |
| Kingston SA400S37480G 480GB SSD                      | 3         | 0.59%   |
| Hitachi HTS545032B9A302 320GB                        | 3         | 0.59%   |
| Crucial CT1000BX500SSD1 1TB                          | 3         | 0.59%   |
| Apple SSD SM256C 256GB                               | 3         | 0.59%   |
| Apple SSD SM0256G 256GB                              | 3         | 0.59%   |
| Apple HDD HTS545050A7E362 500GB                      | 3         | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 2         | 0.39%   |
| WDC WD5000LPCX-21VHAT0 500GB                         | 2         | 0.39%   |
| WDC WD10JPVX-60JC3T1 1TB                             | 2         | 0.39%   |
| Unknown NVMe SSD Drive 512GB                         | 2         | 0.39%   |
| Unknown MMC Card  32GB                               | 2         | 0.39%   |
| Unknown MMC Card  16GB                               | 2         | 0.39%   |
| Unknown MMC Card  128GB                              | 2         | 0.39%   |
| Toshiba THNSFJ256GCSU 256GB SSD                      | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 33     | 25.4%   |
| Toshiba             | 29        | 34     | 23.02%  |
| WDC                 | 26        | 28     | 20.63%  |
| Hitachi             | 14        | 16     | 11.11%  |
| HGST                | 9         | 13     | 7.14%   |
| Apple               | 7         | 7      | 5.56%   |
| Samsung Electronics | 3         | 3      | 2.38%   |
| Fujitsu             | 2         | 2      | 1.59%   |
| Unknown             | 1         | 1      | 0.79%   |
| TO Exter            | 1         | 1      | 0.79%   |
| JMicron Technology  | 1         | 1      | 0.79%   |
| External            | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 48     | 17.11%  |
| Kingston            | 28        | 33     | 12.28%  |
| Apple               | 28        | 29     | 12.28%  |
| Crucial             | 25        | 29     | 10.96%  |
| SanDisk             | 21        | 26     | 9.21%   |
| WDC                 | 12        | 14     | 5.26%   |
| Intel               | 7         | 11     | 3.07%   |
| China               | 7         | 9      | 3.07%   |
| LITEON              | 5         | 5      | 2.19%   |
| Intenso             | 4         | 4      | 1.75%   |
| A-DATA Technology   | 4         | 4      | 1.75%   |
| SPCC                | 3         | 3      | 1.32%   |
| Patriot             | 3         | 3      | 1.32%   |
| OWC                 | 3         | 3      | 1.32%   |
| Lexar               | 3         | 3      | 1.32%   |
| Unknown             | 3         | 3      | 1.32%   |
| Transcend           | 2         | 3      | 0.88%   |
| Toshiba             | 2         | 2      | 0.88%   |
| SK hynix            | 2         | 2      | 0.88%   |
| PNY                 | 2         | 2      | 0.88%   |
| Micron Technology   | 2         | 2      | 0.88%   |
| LITEONIT            | 2         | 2      | 0.88%   |
| Apacer              | 2         | 2      | 0.88%   |
| XUM                 | 1         | 1      | 0.44%   |
| XrayDisk            | 1         | 2      | 0.44%   |
| Verbatim            | 1         | 1      | 0.44%   |
| Teclast             | 1         | 1      | 0.44%   |
| Seagate             | 1         | 1      | 0.44%   |
| SABRENT             | 1         | 1      | 0.44%   |
| OCZ                 | 1         | 1      | 0.44%   |
| NGFF                | 1         | 1      | 0.44%   |
| Netac               | 1         | 1      | 0.44%   |
| LS                  | 1         | 1      | 0.44%   |
| KingSpec            | 1         | 2      | 0.44%   |
| HUSKY               | 1         | 1      | 0.44%   |
| Hewlett-Packard     | 1         | 2      | 0.44%   |
| GOODRAM             | 1         | 2      | 0.44%   |
| Gigabyte Technology | 1         | 1      | 0.44%   |
| Fanxiang            | 1         | 1      | 0.44%   |
| Emtec               | 1         | 2      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 211       | 266    | 44.61%  |
| HDD     | 121       | 140    | 25.58%  |
| NVMe    | 109       | 132    | 23.04%  |
| MMC     | 19        | 25     | 4.02%   |
| Unknown | 13        | 14     | 2.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 315       | 406    | 68.93%  |
| NVMe | 109       | 132    | 23.85%  |
| MMC  | 19        | 25     | 4.16%   |
| SAS  | 14        | 14     | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 253       | 311    | 75.75%  |
| 0.51-1.0   | 73        | 86     | 21.86%  |
| 1.01-2.0   | 7         | 8      | 2.1%    |
| 3.01-4.0   | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 180       | 43.17%  |
| 251-500        | 126       | 30.22%  |
| 501-1000       | 57        | 13.67%  |
| 51-100         | 27        | 6.47%   |
| 21-50          | 12        | 2.88%   |
| 1001-2000      | 9         | 2.16%   |
| More than 3000 | 2         | 0.48%   |
| 1-20           | 2         | 0.48%   |
| 2001-3000      | 1         | 0.24%   |
| Unknown        | 1         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 209       | 48.38%  |
| 21-50     | 130       | 30.09%  |
| 51-100    | 37        | 8.56%   |
| 101-250   | 31        | 7.18%   |
| 251-500   | 19        | 4.4%    |
| 501-1000  | 4         | 0.93%   |
| 2001-3000 | 1         | 0.23%   |
| Unknown   | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 16.67%  |
| Samsung Electronics HM320II 320GB           | 1         | 1      | 16.67%  |
| LS 128GB M300                               | 1         | 1      | 16.67%  |
| Intel SSDPEKKF512G7H BTPY71141D7T512F 512GB | 1         | 1      | 16.67%  |
| Crucial CT240M500SSD3 240GB                 | 1         | 1      | 16.67%  |
| BIWIN SSD 64GB                              | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| LS                  | 1         | 1      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |
| Crucial             | 1         | 1      | 16.67%  |
| BIWIN               | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 50%     |
| HDD  | 2         | 2      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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
| Detected | 384       | 531    | 91.43%  |
| Works    | 30        | 40     | 7.14%   |
| Malfunc  | 6         | 6      | 1.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 286       | 60.72%  |
| Samsung Electronics            | 45        | 9.55%   |
| AMD                            | 32        | 6.79%   |
| Nvidia                         | 24        | 5.1%    |
| SanDisk                        | 15        | 3.18%   |
| SK hynix                       | 11        | 2.34%   |
| Phison Electronics             | 10        | 2.12%   |
| KIOXIA                         | 9         | 1.91%   |
| Toshiba America Info Systems   | 6         | 1.27%   |
| Silicon Motion                 | 6         | 1.27%   |
| Kingston Technology Company    | 5         | 1.06%   |
| Micron Technology              | 4         | 0.85%   |
| Union Memory (Shenzhen)        | 3         | 0.64%   |
| Yangtze Memory Technologies    | 2         | 0.42%   |
| Shenzhen Longsys Electronics   | 2         | 0.42%   |
| ASMedia Technology             | 2         | 0.42%   |
| ADATA Technology               | 2         | 0.42%   |
| Solidigm                       | 1         | 0.21%   |
| Solid State Storage Technology | 1         | 0.21%   |
| Micron/Crucial Technology      | 1         | 0.21%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.21%   |
| Marvell Technology Group       | 1         | 0.21%   |
| Lite-On Technology             | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 43        | 8.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 36        | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 35        | 7.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 5.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 4.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 3.66%   |
| Nvidia MCP79 AHCI Controller                                                   | 14        | 2.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 13        | 2.64%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 12        | 2.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 2.44%   |
| Intel Tiger Lake-LP SATA Controller                                            | 11        | 2.24%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 9         | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 1.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 1.63%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 7         | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.42%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 6         | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 1.22%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.81%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 4         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.61%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.61%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 3         | 0.61%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 3         | 0.61%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.61%   |
| Yangtze Memory PC005 NVMe SSD                                                  | 2         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 321       | 66.88%  |
| NVMe | 109       | 22.71%  |
| RAID | 37        | 7.71%   |
| IDE  | 13        | 2.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 354       | 85.92%  |
| AMD    | 58        | 14.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 3.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 2.43%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 10        | 2.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.43%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 9         | 2.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.94%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 8         | 1.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.21%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 5         | 1.21%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 1.21%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 1.21%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 1.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.97%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 4         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.97%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.97%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 4         | 0.97%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.73%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 3         | 0.73%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.73%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 3         | 0.73%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 3         | 0.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.73%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.73%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 3         | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.73%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 0.73%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.73%   |
| AMD V140 Processor                            | 3         | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.73%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.49%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 131       | 31.8%   |
| Intel Core i7           | 80        | 19.42%  |
| Intel Core 2 Duo        | 36        | 8.74%   |
| Other                   | 34        | 8.25%   |
| Intel Core i3           | 28        | 6.8%    |
| Intel Celeron           | 20        | 4.85%   |
| AMD Ryzen 5             | 17        | 4.13%   |
| Intel Pentium           | 12        | 2.91%   |
| AMD Ryzen 7             | 11        | 2.67%   |
| AMD A4                  | 6         | 1.46%   |
| Intel Pentium Dual-Core | 4         | 0.97%   |
| AMD Ryzen 3             | 4         | 0.97%   |
| Intel Atom              | 3         | 0.73%   |
| AMD V140                | 3         | 0.73%   |
| AMD A6                  | 3         | 0.73%   |
| Intel Pentium Silver    | 2         | 0.49%   |
| AMD E2                  | 2         | 0.49%   |
| AMD A8                  | 2         | 0.49%   |
| AMD A12                 | 2         | 0.49%   |
| Intel Xeon              | 1         | 0.24%   |
| Intel Pentium Dual      | 1         | 0.24%   |
| Intel Core m7           | 1         | 0.24%   |
| Intel Core m5           | 1         | 0.24%   |
| Intel Core m3           | 1         | 0.24%   |
| Intel Core 2            | 1         | 0.24%   |
| Intel Celeron Dual-Core | 1         | 0.24%   |
| AMD Turion II Dual-Core | 1         | 0.24%   |
| AMD Ryzen 9             | 1         | 0.24%   |
| AMD Ryzen 5 PRO         | 1         | 0.24%   |
| AMD PRO A10             | 1         | 0.24%   |
| AMD FX                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 254       | 61.65%  |
| 4      | 113       | 27.43%  |
| 6      | 20        | 4.85%   |
| 8      | 16        | 3.88%   |
| 1      | 5         | 1.21%   |
| 12     | 2         | 0.49%   |
| 14     | 1         | 0.24%   |
| 10     | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 412       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 313       | 75.79%  |
| 1      | 100       | 24.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 412       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 403       | 97.58%  |
| 0x08608104 | 2         | 0.48%   |
| 0x08608103 | 2         | 0.48%   |
| 0x806c1    | 1         | 0.24%   |
| 0x0a704104 | 1         | 0.24%   |
| 0x0a404102 | 1         | 0.24%   |
| 0x08108109 | 1         | 0.24%   |
| 0x06001119 | 1         | 0.24%   |
| 0x05000119 | 1         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 11.62%  |
| SandyBridge      | 47        | 11.38%  |
| Haswell          | 42        | 10.17%  |
| IvyBridge        | 41        | 9.93%   |
| Penryn           | 40        | 9.69%   |
| Skylake          | 27        | 6.54%   |
| Unknown          | 23        | 5.57%   |
| Westmere         | 21        | 5.08%   |
| TigerLake        | 21        | 5.08%   |
| Broadwell        | 20        | 4.84%   |
| Goldmont plus    | 10        | 2.42%   |
| Zen+             | 8         | 1.94%   |
| Silvermont       | 8         | 1.94%   |
| Zen 3            | 7         | 1.69%   |
| IceLake          | 6         | 1.45%   |
| Excavator        | 6         | 1.45%   |
| Zen 2            | 4         | 0.97%   |
| Puma             | 4         | 0.97%   |
| K10              | 4         | 0.97%   |
| Goldmont         | 4         | 0.97%   |
| CometLake        | 4         | 0.97%   |
| K10 Llano        | 3         | 0.73%   |
| Core             | 3         | 0.73%   |
| Zen              | 2         | 0.48%   |
| Jaguar           | 2         | 0.48%   |
| Bonnell          | 2         | 0.48%   |
| Bobcat           | 2         | 0.48%   |
| Alderlake Hybrid | 2         | 0.48%   |
| Steamroller      | 1         | 0.24%   |
| Piledriver       | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 311       | 61.83%  |
| Nvidia | 104       | 20.68%  |
| AMD    | 88        | 17.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 45        | 8.69%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 39        | 7.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 25        | 4.83%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 19        | 3.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 17        | 3.28%   |
| Intel Core Processor Integrated Graphics Controller                           | 16        | 3.09%   |
| Nvidia C79 [GeForce 9400M]                                                    | 14        | 2.7%    |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                      | 13        | 2.51%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 12        | 2.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 12        | 2.32%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 10        | 1.93%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                      | 10        | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 9         | 1.74%   |
| AMD Lucienne                                                                  | 9         | 1.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 8         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 6         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 6         | 1.16%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 6         | 1.16%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                       | 6         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 6         | 1.16%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 6         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 6         | 1.16%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 5         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 0.77%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 4         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 0.77%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                       | 4         | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 0.77%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 4         | 0.77%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 4         | 0.77%   |
| AMD Barcelo                                                                   | 4         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 3         | 0.58%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                   | 3         | 0.58%   |
| Nvidia GF119M [NVS 4200M]                                                     | 3         | 0.58%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 3         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 223       | 54%     |
| Intel + Nvidia | 60        | 14.53%  |
| 1 x AMD        | 54        | 13.08%  |
| 1 x Nvidia     | 35        | 8.47%   |
| Intel + AMD    | 25        | 6.05%   |
| 2 x Nvidia     | 5         | 1.21%   |
| AMD + Nvidia   | 5         | 1.21%   |
| 2 x AMD        | 4         | 0.97%   |
| Other          | 2         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 395       | 95.64%  |
| Proprietary | 10        | 2.42%   |
| Unknown     | 8         | 1.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 392       | 94.69%  |
| 0.01-0.5   | 12        | 2.9%    |
| 0.51-1.0   | 4         | 0.97%   |
| 1.01-2.0   | 3         | 0.72%   |
| 3.01-4.0   | 2         | 0.48%   |
| 7.01-8.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 92        | 20.63%  |
| AU Optronics            | 62        | 13.9%   |
| BOE                     | 61        | 13.68%  |
| LG Display              | 52        | 11.66%  |
| Chimei Innolux          | 52        | 11.66%  |
| Samsung Electronics     | 42        | 9.42%   |
| Chi Mei Optoelectronics | 12        | 2.69%   |
| Sharp                   | 8         | 1.79%   |
| Lenovo                  | 7         | 1.57%   |
| PANDA                   | 5         | 1.12%   |
| InfoVision              | 4         | 0.9%    |
| Dell                    | 4         | 0.9%    |
| Acer                    | 4         | 0.9%    |
| Goldstar                | 3         | 0.67%   |
| Unknown (XXX)           | 2         | 0.45%   |
| Toshiba                 | 2         | 0.45%   |
| Sony                    | 2         | 0.45%   |
| Panasonic               | 2         | 0.45%   |
| Mi                      | 2         | 0.45%   |
| HKC                     | 2         | 0.45%   |
| HannStar                | 2         | 0.45%   |
| Fujitsu Siemens         | 2         | 0.45%   |
| ASUSTek Computer        | 2         | 0.45%   |
| Westinghouse            | 1         | 0.22%   |
| Vita                    | 1         | 0.22%   |
| ViewSonic               | 1         | 0.22%   |
| VIE                     | 1         | 0.22%   |
| Vestel Elektronik       | 1         | 0.22%   |
| TMX                     | 1         | 0.22%   |
| Quanta Display          | 1         | 0.22%   |
| QIA                     | 1         | 0.22%   |
| LG Philips              | 1         | 0.22%   |
| KDB                     | 1         | 0.22%   |
| ITE                     | 1         | 0.22%   |
| InnoLux Display         | 1         | 0.22%   |
| HJW                     | 1         | 0.22%   |
| HGC                     | 1         | 0.22%   |
| Hewlett-Packard         | 1         | 0.22%   |
| Gigabyte Technology     | 1         | 0.22%   |
| CTO                     | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 12        | 2.68%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 11        | 2.46%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 7         | 1.56%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 6         | 1.34%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 1.12%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                     | 5         | 1.12%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 5         | 1.12%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 4         | 0.89%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 4         | 0.89%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 3         | 0.67%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch         | 3         | 0.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.67%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.67%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                   | 3         | 0.67%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 3         | 0.67%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 2         | 0.45%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.45%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.45%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch             | 2         | 0.45%   |
| LG Display LCD Monitor LGD03DC 1366x768 277x156mm 12.5-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD02D1 1600x900 382x215mm 17.3-inch              | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 2         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 138       | 32.32%  |
| 1366x768 (WXGA)    | 118       | 27.63%  |
| 1280x800 (WXGA)    | 49        | 11.48%  |
| 1440x900 (WXGA+)   | 28        | 6.56%   |
| 1600x900 (HD+)     | 27        | 6.32%   |
| 3840x2160 (4K)     | 12        | 2.81%   |
| 1920x1200 (WUXGA)  | 11        | 2.58%   |
| 2880x1800          | 7         | 1.64%   |
| 2560x1600          | 7         | 1.64%   |
| 2560x1440 (QHD)    | 7         | 1.64%   |
| 1680x1050 (WSXGA+) | 5         | 1.17%   |
| 2160x1440          | 4         | 0.94%   |
| 3440x1440          | 2         | 0.47%   |
| 1280x1024 (SXGA)   | 2         | 0.47%   |
| 1024x600           | 2         | 0.47%   |
| 3840x2400          | 1         | 0.23%   |
| 3200x1800 (QHD+)   | 1         | 0.23%   |
| 3072x1920          | 1         | 0.23%   |
| 2560x1080          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1600x2560          | 1         | 0.23%   |
| 1400x1050          | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 158       | 35.43%  |
| 13     | 116       | 26.01%  |
| 14     | 55        | 12.33%  |
| 17     | 37        | 8.3%    |
| 11     | 11        | 2.47%   |
| 12     | 9         | 2.02%   |
| 27     | 8         | 1.79%   |
| 23     | 8         | 1.79%   |
| 16     | 7         | 1.57%   |
| 31     | 6         | 1.35%   |
| 24     | 6         | 1.35%   |
| 54     | 4         | 0.9%    |
| 21     | 4         | 0.9%    |
| 84     | 3         | 0.67%   |
| 19     | 3         | 0.67%   |
| 32     | 2         | 0.45%   |
| 10     | 2         | 0.45%   |
| 72     | 1         | 0.22%   |
| 63     | 1         | 0.22%   |
| 35     | 1         | 0.22%   |
| 34     | 1         | 0.22%   |
| 26     | 1         | 0.22%   |
| 22     | 1         | 0.22%   |
| 18     | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 249       | 55.96%  |
| 201-300     | 105       | 23.6%   |
| 351-400     | 43        | 9.66%   |
| 501-600     | 22        | 4.94%   |
| 401-500     | 7         | 1.57%   |
| 601-700     | 6         | 1.35%   |
| 1001-1500   | 5         | 1.12%   |
| 1501-2000   | 4         | 0.9%    |
| 701-800     | 3         | 0.67%   |
| 801-900     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 296       | 71.84%  |
| 16/10 | 107       | 25.97%  |
| 3/2   | 5         | 1.21%   |
| 5/4   | 2         | 0.49%   |
| 21/9  | 2         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 157       | 35.2%   |
| 81-90          | 138       | 30.94%  |
| 71-80          | 31        | 6.95%   |
| 121-130        | 28        | 6.28%   |
| 201-250        | 16        | 3.59%   |
| 51-60          | 11        | 2.47%   |
| 351-500        | 10        | 2.24%   |
| More than 1000 | 9         | 2.02%   |
| 61-70          | 9         | 2.02%   |
| 131-140        | 9         | 2.02%   |
| 301-350        | 8         | 1.79%   |
| 111-120        | 7         | 1.57%   |
| 151-200        | 4         | 0.9%    |
| 251-300        | 3         | 0.67%   |
| 91-100         | 3         | 0.67%   |
| 41-50          | 2         | 0.45%   |
| 141-150        | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 181       | 40.86%  |
| 121-160       | 163       | 36.79%  |
| 51-100        | 53        | 11.96%  |
| 161-240       | 30        | 6.77%   |
| More than 240 | 9         | 2.03%   |
| 1-50          | 7         | 1.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 363       | 87.26%  |
| 2     | 46        | 11.06%  |
| 0     | 6         | 1.44%   |
| 3     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 187       | 28.29%  |
| Intel                             | 158       | 23.9%   |
| Broadcom                          | 118       | 17.85%  |
| Qualcomm Atheros                  | 69        | 10.44%  |
| Broadcom Limited                  | 31        | 4.69%   |
| Nvidia                            | 15        | 2.27%   |
| MediaTek                          | 15        | 2.27%   |
| Samsung Electronics               | 9         | 1.36%   |
| Marvell Technology Group          | 7         | 1.06%   |
| Ralink Technology                 | 6         | 0.91%   |
| Hewlett-Packard                   | 5         | 0.76%   |
| Xiaomi                            | 4         | 0.61%   |
| TP-Link                           | 3         | 0.45%   |
| Sierra Wireless                   | 3         | 0.45%   |
| Ralink                            | 3         | 0.45%   |
| Qualcomm Atheros Communications   | 3         | 0.45%   |
| Ericsson Business Mobile Networks | 3         | 0.45%   |
| Dell                              | 3         | 0.45%   |
| ASIX Electronics                  | 3         | 0.45%   |
| Apple                             | 3         | 0.45%   |
| D-Link System                     | 2         | 0.3%    |
| ZyDAS                             | 1         | 0.15%   |
| U-Blox                            | 1         | 0.15%   |
| Shenzhen Goodix Technology        | 1         | 0.15%   |
| Qualcomm                          | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| ICS Advent                        | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| Bose                              | 1         | 0.15%   |
| Attansic Technology               | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 94        | 11.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 4.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 37        | 4.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 36        | 4.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 19        | 2.4%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 17        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 16        | 2.02%   |
| Nvidia MCP79 Ethernet                                                  | 14        | 1.77%   |
| Intel Wireless 7260                                                    | 14        | 1.77%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 1.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 14        | 1.77%   |
| Intel Wireless 8265 / 8275                                             | 13        | 1.64%   |
| Intel Wireless 7265                                                    | 12        | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                          | 12        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 1.39%   |
| Intel Wireless 8260                                                    | 11        | 1.39%   |
| Intel Wireless 3165                                                    | 11        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 11        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10        | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 10        | 1.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 10        | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.14%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 0.76%   |
| Intel Wireless 3160                                                    | 6         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 6         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.63%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 5         | 0.63%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 5         | 0.63%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.63%   |
| Intel Centrino Advanced-N 6235                                         | 5         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 146       | 32.52%  |
| Broadcom                        | 114       | 25.39%  |
| Realtek Semiconductor           | 64        | 14.25%  |
| Qualcomm Atheros                | 57        | 12.69%  |
| Broadcom Limited                | 26        | 5.79%   |
| MediaTek                        | 14        | 3.12%   |
| Ralink Technology               | 6         | 1.34%   |
| TP-Link                         | 3         | 0.67%   |
| Sierra Wireless                 | 3         | 0.67%   |
| Ralink                          | 3         | 0.67%   |
| Qualcomm Atheros Communications | 3         | 0.67%   |
| Dell                            | 2         | 0.45%   |
| D-Link System                   | 2         | 0.45%   |
| ZyDAS                           | 1         | 0.22%   |
| Qualcomm                        | 1         | 0.22%   |
| Hewlett-Packard                 | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |
| D-Link                          | 1         | 0.22%   |
| ASUSTek Computer                | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                                       | 37        | 8.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 19        | 4.22%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 17        | 3.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 16        | 3.56%   |
| Intel Wireless 7260                                                  | 14        | 3.11%   |
| Intel Wi-Fi 6 AX201                                                  | 14        | 3.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 14        | 3.11%   |
| Intel Wireless 8265 / 8275                                           | 13        | 2.89%   |
| Intel Wireless 7265                                                  | 12        | 2.67%   |
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 11        | 2.44%   |
| Intel Wireless 8260                                                  | 11        | 2.44%   |
| Intel Wireless 3165                                                  | 11        | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 11        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 10        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 10        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 10        | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 9         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 1.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 6         | 1.33%   |
| Intel Wireless 3160                                                  | 6         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 6         | 1.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 6         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 5         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 1.11%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 5         | 1.11%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 5         | 1.11%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4         | 0.89%   |
| Realtek 802.11ac NIC                                                 | 4         | 0.89%   |
| Ralink MT7601U Wireless Adapter                                      | 4         | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 4         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 0.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 4         | 0.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 3         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 3         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 0.67%   |
| Intel Wi-Fi 6 AX200                                                  | 3         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 146       | 44.38%  |
| Intel                    | 62        | 18.84%  |
| Broadcom                 | 51        | 15.5%   |
| Qualcomm Atheros         | 20        | 6.08%   |
| Nvidia                   | 15        | 4.56%   |
| Samsung Electronics      | 9         | 2.74%   |
| Marvell Technology Group | 7         | 2.13%   |
| Broadcom Limited         | 5         | 1.52%   |
| Xiaomi                   | 4         | 1.22%   |
| ASIX Electronics         | 3         | 0.91%   |
| Apple                    | 3         | 0.91%   |
| MediaTek                 | 1         | 0.3%    |
| JMicron Technology       | 1         | 0.3%    |
| ICS Advent               | 1         | 0.3%    |
| Attansic Technology      | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 94        | 28.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 39        | 11.82%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 36        | 10.91%  |
| Nvidia MCP79 Ethernet                                                          | 14        | 4.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 3.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 10        | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 2.73%   |
| Intel Ethernet Connection I218-LM                                              | 8         | 2.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 7         | 2.12%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.52%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.21%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.21%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.21%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.91%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.91%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.91%   |
| Apple Ethernet Adapter [A1277]                                                 | 3         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.61%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.61%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.61%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.3%    |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 409       | 55.12%  |
| Ethernet | 322       | 43.4%   |
| Modem    | 11        | 1.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 320       | 77.86%  |
| Ethernet | 91        | 22.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 293       | 71.12%  |
| 1     | 113       | 27.43%  |
| 3     | 3         | 0.73%   |
| 0     | 3         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 287       | 68.82%  |
| Yes  | 130       | 31.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 33.42%  |
| Apple                           | 93        | 25.27%  |
| Realtek Semiconductor           | 37        | 10.05%  |
| Qualcomm Atheros Communications | 26        | 7.07%   |
| Broadcom                        | 17        | 4.62%   |
| IMC Networks                    | 14        | 3.8%    |
| Foxconn / Hon Hai               | 13        | 3.53%   |
| Hewlett-Packard                 | 9         | 2.45%   |
| Lite-On Technology              | 7         | 1.9%    |
| Dell                            | 7         | 1.9%    |
| Realtek                         | 6         | 1.63%   |
| Cambridge Silicon Radio         | 5         | 1.36%   |
| Foxconn International           | 3         | 0.82%   |
| Toshiba                         | 2         | 0.54%   |
| Ralink                          | 2         | 0.54%   |
| Ralink Technology               | 1         | 0.27%   |
| Opticis                         | 1         | 0.27%   |
| MediaTek                        | 1         | 0.27%   |
| Askey Computer                  | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 67        | 18.21%  |
| Apple Bluetooth Host Controller                                                     | 52        | 14.13%  |
| Apple Bluetooth USB Host Controller                                                 | 35        | 9.51%   |
| Realtek Bluetooth Radio                                                             | 28        | 7.61%   |
| Intel AX201 Bluetooth                                                               | 21        | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 3.26%   |
| IMC Networks Wireless_Device                                                        | 8         | 2.17%   |
| Realtek Bluetooth Radio                                                             | 6         | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 1.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.36%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 1.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.09%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 4         | 1.09%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 1.09%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.82%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 0.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.82%   |
| Intel Bluetooth Device                                                              | 3         | 0.82%   |
| Intel AX200 Bluetooth                                                               | 3         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.82%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.82%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.82%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 3         | 0.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.54%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.54%   |
| Lite-On Wireless_Device                                                             | 2         | 0.54%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.54%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.54%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.54%   |
| IMC Networks BCM20702A0                                                             | 2         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.54%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 328       | 66.8%   |
| AMD                                  | 73        | 14.87%  |
| Nvidia                               | 70        | 14.26%  |
| Logitech                             | 2         | 0.41%   |
| Generalplus Technology               | 2         | 0.41%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.2%    |
| Texas Instruments                    | 1         | 0.2%    |
| TerraTec Electronic                  | 1         | 0.2%    |
| Realtek Semiconductor                | 1         | 0.2%    |
| liyuany                              | 1         | 0.2%    |
| Lenovo                               | 1         | 0.2%    |
| Kingston Technology                  | 1         | 0.2%    |
| JMTek                                | 1         | 0.2%    |
| JBL                                  | 1         | 0.2%    |
| Huawei Technologies                  | 1         | 0.2%    |
| Hewlett-Packard                      | 1         | 0.2%    |
| Guillemot                            | 1         | 0.2%    |
| GN Netcom                            | 1         | 0.2%    |
| fifine Microphones                   | 1         | 0.2%    |
| C-Media Electronics                  | 1         | 0.2%    |
| Apple                                | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 47        | 7.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 46        | 7.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42        | 7.01%   |
| AMD Ryzen HD Audio Controller                                              | 30        | 5.01%   |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 4.17%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 4.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 3.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 3.34%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 3.34%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 20        | 3.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 2.84%   |
| Nvidia MCP79 High Definition Audio                                         | 14        | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 2.17%   |
| AMD FCH Azalia Controller                                                  | 13        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 1.84%   |
| Nvidia MCP89 High Definition Audio                                         | 10        | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.17%   |
| Nvidia GT216 HDMI Audio Controller                                         | 6         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1%      |
| Intel CM238 HD Audio Controller                                            | 6         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 1%      |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.67%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 0.67%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 0.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 26.76%  |
| SK hynix            | 13        | 18.31%  |
| Micron Technology   | 10        | 14.08%  |
| Kingston            | 6         | 8.45%   |
| Crucial             | 5         | 7.04%   |
| Unknown             | 4         | 5.63%   |
| Elpida              | 3         | 4.23%   |
| Corsair             | 3         | 4.23%   |
| Unknown (ABCD)      | 2         | 2.82%   |
| Ramaxel Technology  | 2         | 2.82%   |
| Unknown (0x0C26)    | 1         | 1.41%   |
| Timetec             | 1         | 1.41%   |
| ASint Technology    | 1         | 1.41%   |
| A-DATA Technology   | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.56%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 2         | 2.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 2.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.56%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 2.56%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.28%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.28%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                       | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM DDR3                               | 1         | 1.28%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.28%   |
| Unknown (0x0C26) RAM TIMETEC-SD4-2666 16GB SODIMM DDR4 2667MT/s  | 1         | 1.28%   |
| Timetec RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.28%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 1         | 1.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.28%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.28%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.28%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.28%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 1.28%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.28%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.28%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s          | 1         | 1.28%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.28%   |
| Samsung RAM M04GD08P1333C9 4GB SODIMM DDR3 667MT/s               | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 29        | 49.15%  |
| DDR4   | 19        | 32.2%   |
| LPDDR4 | 3         | 5.08%   |
| LPDDR5 | 2         | 3.39%   |
| LPDDR3 | 2         | 3.39%   |
| DDR2   | 2         | 3.39%   |
| SDRAM  | 1         | 1.69%   |
| DDR5   | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 85%     |
| Row Of Chips | 9         | 15%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 38.81%  |
| 4096  | 21        | 31.34%  |
| 2048  | 12        | 17.91%  |
| 16384 | 5         | 7.46%   |
| 1024  | 2         | 2.99%   |
| 32768 | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 23.44%  |
| 3200    | 10        | 15.63%  |
| 2667    | 9         | 14.06%  |
| 1333    | 7         | 10.94%  |
| 2133    | 4         | 6.25%   |
| 2400    | 3         | 4.69%   |
| 1067    | 3         | 4.69%   |
| 1334    | 2         | 3.13%   |
| 800     | 2         | 3.13%   |
| 7500    | 1         | 1.56%   |
| 6400    | 1         | 1.56%   |
| 4800    | 1         | 1.56%   |
| 4266    | 1         | 1.56%   |
| 3266    | 1         | 1.56%   |
| 2048    | 1         | 1.56%   |
| 1867    | 1         | 1.56%   |
| 667     | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 2         | 40%     |
| Brother Industries    | 2         | 40%     |
| Lexmark International | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lexmark International f+ imaging M40adn | 1         | 20%     |
| Canon LiDE 400                          | 1         | 20%     |
| Canon LBP3360                           | 1         | 20%     |
| Brother HL-2250DN Laser Printer         | 1         | 20%     |
| Brother HL-1110 series                  | 1         | 20%     |

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
| Apple                                  | 76        | 20.71%  |
| Chicony Electronics                    | 57        | 15.53%  |
| Microdia                               | 31        | 8.45%   |
| Realtek Semiconductor                  | 24        | 6.54%   |
| IMC Networks                           | 24        | 6.54%   |
| Sunplus Innovation Technology          | 21        | 5.72%   |
| Quanta                                 | 19        | 5.18%   |
| Bison Electronics                      | 18        | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 16        | 4.36%   |
| Suyin                                  | 14        | 3.81%   |
| Syntek                                 | 11        | 3%      |
| Lite-On Technology                     | 9         | 2.45%   |
| Silicon Motion                         | 8         | 2.18%   |
| Luxvisions Innotech Limited            | 5         | 1.36%   |
| Ricoh                                  | 4         | 1.09%   |
| SunplusIT                              | 3         | 0.82%   |
| Sonix Technology                       | 3         | 0.82%   |
| Samsung Electronics                    | 3         | 0.82%   |
| Primax Electronics                     | 3         | 0.82%   |
| Alcor Micro                            | 3         | 0.82%   |
| ShineTech                              | 2         | 0.54%   |
| Y Media                                | 1         | 0.27%   |
| Sunplus Technology                     | 1         | 0.27%   |
| OYT Tech                               | 1         | 0.27%   |
| MacroSilicon                           | 1         | 0.27%   |
| Logitech                               | 1         | 0.27%   |
| LG Electronics                         | 1         | 0.27%   |
| Goodong Industry                       | 1         | 0.27%   |
| GEMBIRD                                | 1         | 0.27%   |
| Foxconn / Hon Hai                      | 1         | 0.27%   |
| Denron                                 | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |
| Acer                                   | 1         | 0.27%   |
| Unknown                                | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                    | 36        | 9.68%   |
| Apple Built-in iSight                                       | 25        | 6.72%   |
| Microdia Integrated_Webcam_HD                               | 12        | 3.23%   |
| Chicony Integrated Camera                                   | 11        | 2.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                             | 10        | 2.69%   |
| Realtek Integrated_Webcam_HD                                | 8         | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 2.15%   |
| Chicony HP Truevision HD                                    | 6         | 1.61%   |
| Apple FaceTime Camera                                       | 6         | 1.61%   |
| Microdia Integrated Webcam                                  | 5         | 1.34%   |
| IMC Networks Integrated Camera                              | 5         | 1.34%   |
| Syntek Integrated Camera                                    | 4         | 1.08%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 1.08%   |
| Realtek USB Camera                                          | 4         | 1.08%   |
| Quanta HD User Facing                                       | 4         | 1.08%   |
| Luxvisions Innotech Limited HP HD Camera                    | 4         | 1.08%   |
| Chicony Integrated Camera (1280x720@30)                     | 4         | 1.08%   |
| Chicony HP Truevision HD camera                             | 4         | 1.08%   |
| Chicony HD WebCam                                           | 4         | 1.08%   |
| Bison Integrated Camera                                     | 4         | 1.08%   |
| Syntek Lenovo EasyCamera                                    | 3         | 0.81%   |
| Syntek EasyCamera                                           | 3         | 0.81%   |
| Suyin HP Truevision HD                                      | 3         | 0.81%   |
| Sunplus Integrated Camera                                   | 3         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 3         | 0.81%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 3         | 0.81%   |
| Quanta ov9734_techfront_camera                              | 3         | 0.81%   |
| Quanta HP Webcam                                            | 3         | 0.81%   |
| Quanta HD Camera                                            | 3         | 0.81%   |
| Lite-On Integrated Camera                                   | 3         | 0.81%   |
| Chicony EasyCamera                                          | 3         | 0.81%   |
| Bison SunplusIT Integrated Camera                           | 3         | 0.81%   |
| Bison Lenovo EasyCamera                                     | 3         | 0.81%   |
| Suyin HD WebCam                                             | 2         | 0.54%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.54%   |
| Sunplus Laptop Integrated Webcam FHD                        | 2         | 0.54%   |
| Sunplus HP Universal Camera                                 | 2         | 0.54%   |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 0.54%   |
| Sunplus Asus Webcam                                         | 2         | 0.54%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.]     | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 51.11%  |
| Shenzhen Goodix Technology | 9         | 20%     |
| Synaptics                  | 6         | 13.33%  |
| Upek                       | 3         | 6.67%   |
| AuthenTec                  | 3         | 6.67%   |
| LighTuning Technology      | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 17.78%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 8.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 4.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4.44%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 4.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 4.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4.44%   |
| AuthenTec AES2810                                                          | 2         | 4.44%   |
| Validity Sensors VFS491                                                    | 1         | 2.22%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.22%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 20        | 68.97%  |
| Alcor Micro      | 5         | 17.24%  |
| Upek             | 1         | 3.45%   |
| SCM Microsystems | 1         | 3.45%   |
| O2 Micro         | 1         | 3.45%   |
| Lenovo           | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 20.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 17.24%  |
| Broadcom 5880                                                                | 5         | 17.24%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 17.24%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 10.34%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.45%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 3.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.45%   |
| Broadcom 58200                                                               | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 237       | 57.11%  |
| 1     | 139       | 33.49%  |
| 2     | 35        | 8.43%   |
| 3     | 3         | 0.72%   |
| 9     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 68        | 30.77%  |
| Fingerprint reader    | 45        | 20.36%  |
| Multimedia controller | 30        | 13.57%  |
| Graphics card         | 28        | 12.67%  |
| Chipcard              | 28        | 12.67%  |
| Storage               | 7         | 3.17%   |
| Camera                | 4         | 1.81%   |
| Bluetooth             | 4         | 1.81%   |
| Sound                 | 2         | 0.9%    |
| Net/ethernet          | 2         | 0.9%    |
| Storage/ata           | 1         | 0.45%   |
| Network               | 1         | 0.45%   |
| Modem                 | 1         | 0.45%   |


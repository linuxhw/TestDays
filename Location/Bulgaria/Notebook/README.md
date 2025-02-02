Linux in Bulgaria - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

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

Total: 1325

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [0baddf7cbe](https://linux-hardware.org/?probe=0baddf7cbe) | Jan 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5e3d055319](https://linux-hardware.org/?probe=5e3d055319) | Jan 05, 2025 |
| Lenovo        | ThinkPad T490 20N3S82N1P    | [b9e31a2832](https://linux-hardware.org/?probe=b9e31a2832) | Jan 05, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8a0d66e0ae](https://linux-hardware.org/?probe=8a0d66e0ae) | Jan 02, 2025 |
| Acer          | Aspire A315-44P             | [52b26cac3f](https://linux-hardware.org/?probe=52b26cac3f) | Dec 31, 2024 |
| Lenovo        | Unknown                     | [89b1437fa2](https://linux-hardware.org/?probe=89b1437fa2) | Dec 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [a135b01a74](https://linux-hardware.org/?probe=a135b01a74) | Dec 29, 2024 |
| Lenovo        | IdeaPad Y560                | [e36139662d](https://linux-hardware.org/?probe=e36139662d) | Dec 28, 2024 |
| HP            | Pavilion Gaming Notebook    | [0afcb0e788](https://linux-hardware.org/?probe=0afcb0e788) | Dec 28, 2024 |
| HP            | 250 G8 Notebook PC          | [2163561381](https://linux-hardware.org/?probe=2163561381) | Dec 27, 2024 |
| HP            | Pavilion dv6700             | [d9ccd55fd5](https://linux-hardware.org/?probe=d9ccd55fd5) | Dec 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d48fae0d86](https://linux-hardware.org/?probe=d48fae0d86) | Dec 26, 2024 |
| HP            | Pavilion dv6700             | [06e2ee69ef](https://linux-hardware.org/?probe=06e2ee69ef) | Dec 26, 2024 |
| Toshiba       | NB100                       | [1041e6c170](https://linux-hardware.org/?probe=1041e6c170) | Dec 24, 2024 |
| TongFang      | GX5HRXL                     | [c16d33a7aa](https://linux-hardware.org/?probe=c16d33a7aa) | Dec 23, 2024 |
| MSI           | GF63 Thin 10SCSR            | [c0a219ed53](https://linux-hardware.org/?probe=c0a219ed53) | Dec 22, 2024 |
| TongFang      | GX5HRXL                     | [27406f56fd](https://linux-hardware.org/?probe=27406f56fd) | Dec 18, 2024 |
| ASUSTek       | X555LF                      | [7c3dbd59b5](https://linux-hardware.org/?probe=7c3dbd59b5) | Dec 17, 2024 |
| Acer          | Aspire A315-23              | [e51fcf8215](https://linux-hardware.org/?probe=e51fcf8215) | Dec 16, 2024 |
| Dell          | Latitude 7340               | [01bf0e0d2c](https://linux-hardware.org/?probe=01bf0e0d2c) | Dec 16, 2024 |
| Fujitsu       | LIFEBOOK N532               | [6cb47f13c6](https://linux-hardware.org/?probe=6cb47f13c6) | Dec 15, 2024 |
| Dell          | XPS 15 9510                 | [f66ce0b3ee](https://linux-hardware.org/?probe=f66ce0b3ee) | Dec 14, 2024 |
| Toshiba       | NB100                       | [976e6530d5](https://linux-hardware.org/?probe=976e6530d5) | Dec 14, 2024 |
| Dell          | Inspiron 5570               | [2219eae21d](https://linux-hardware.org/?probe=2219eae21d) | Dec 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [5d948ce651](https://linux-hardware.org/?probe=5d948ce651) | Dec 08, 2024 |
| Panasonic     | CF-52PFP54QL                | [bcafd21454](https://linux-hardware.org/?probe=bcafd21454) | Dec 06, 2024 |
| Dell          | Inspiron 3537               | [2d71a66a13](https://linux-hardware.org/?probe=2d71a66a13) | Dec 05, 2024 |
| Acer          | Swift SF314-43              | [133b87bc4b](https://linux-hardware.org/?probe=133b87bc4b) | Dec 03, 2024 |
| Sony          | VPCEH25FD                   | [a5e2ac76fc](https://linux-hardware.org/?probe=a5e2ac76fc) | Dec 03, 2024 |
| Unknown       | Unknown                     | [5b5b439904](https://linux-hardware.org/?probe=5b5b439904) | Nov 29, 2024 |
| Acer          | Aspire A315-34              | [16257c3b4b](https://linux-hardware.org/?probe=16257c3b4b) | Nov 27, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | [2711562e60](https://linux-hardware.org/?probe=2711562e60) | Nov 19, 2024 |
| Dell          | Precision 7710              | [f328fe1be2](https://linux-hardware.org/?probe=f328fe1be2) | Nov 18, 2024 |
| Dell          | Precision 7710              | [658f311eb3](https://linux-hardware.org/?probe=658f311eb3) | Nov 18, 2024 |
| Lenovo        | ThinkPad T530 2429AE1       | [3effeec5aa](https://linux-hardware.org/?probe=3effeec5aa) | Nov 17, 2024 |
| SLIMBOOK      | PROX-AMD5                   | [25010cdc93](https://linux-hardware.org/?probe=25010cdc93) | Nov 16, 2024 |
| HP            | 15                          | [79f04083ac](https://linux-hardware.org/?probe=79f04083ac) | Nov 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c71e9a6fb2](https://linux-hardware.org/?probe=c71e9a6fb2) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [5ddb463c28](https://linux-hardware.org/?probe=5ddb463c28) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b50cd6c13b](https://linux-hardware.org/?probe=b50cd6c13b) | Nov 12, 2024 |
| Lenovo        | ThinkPad T550 20CK0004GE    | [e7943e539d](https://linux-hardware.org/?probe=e7943e539d) | Nov 05, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [3d56cceb9e](https://linux-hardware.org/?probe=3d56cceb9e) | Oct 28, 2024 |
| Lenovo        | G50-30 80G0                 | [d0905f7bb9](https://linux-hardware.org/?probe=d0905f7bb9) | Oct 26, 2024 |
| ASUSTek       | G551JM                      | [d6d0bfa34e](https://linux-hardware.org/?probe=d6d0bfa34e) | Oct 26, 2024 |
| ASUSTek       | G551JM                      | [c411632c1c](https://linux-hardware.org/?probe=c411632c1c) | Oct 26, 2024 |
| Apple         | MacBookPro16,1              | [fc397bc6c0](https://linux-hardware.org/?probe=fc397bc6c0) | Oct 26, 2024 |
| Acer          | Aspire A515-57              | [1eb6d26665](https://linux-hardware.org/?probe=1eb6d26665) | Oct 25, 2024 |
| Acer          | Aspire A515-57              | [fcfd360705](https://linux-hardware.org/?probe=fcfd360705) | Oct 24, 2024 |
| Acer          | Aspire A15-41M              | [b5a44016cd](https://linux-hardware.org/?probe=b5a44016cd) | Oct 23, 2024 |
| Acer          | Nitro AN515-45              | [38add3c407](https://linux-hardware.org/?probe=38add3c407) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [c2aa718daa](https://linux-hardware.org/?probe=c2aa718daa) | Oct 15, 2024 |
| HP            | Pavilion dv8                | [21df937346](https://linux-hardware.org/?probe=21df937346) | Oct 14, 2024 |
| Dell          | Precision 5510              | [8b7f1841e7](https://linux-hardware.org/?probe=8b7f1841e7) | Oct 14, 2024 |
| Dell          | Precision 5510              | [0182ff27ab](https://linux-hardware.org/?probe=0182ff27ab) | Oct 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | [fe8096e733](https://linux-hardware.org/?probe=fe8096e733) | Oct 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e9c7cab546](https://linux-hardware.org/?probe=e9c7cab546) | Oct 10, 2024 |
| Dell          | Latitude E6540              | [c6635fa1dd](https://linux-hardware.org/?probe=c6635fa1dd) | Oct 08, 2024 |
| Dell          | G15 5511                    | [ed9b86e723](https://linux-hardware.org/?probe=ed9b86e723) | Oct 08, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [eb6a4540f2](https://linux-hardware.org/?probe=eb6a4540f2) | Oct 08, 2024 |
| HP            | Pavilion dv6700             | [707360a70f](https://linux-hardware.org/?probe=707360a70f) | Sep 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [a312838803](https://linux-hardware.org/?probe=a312838803) | Sep 24, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [db77b134d1](https://linux-hardware.org/?probe=db77b134d1) | Sep 24, 2024 |
| ASUSTek       | X555LJ                      | [9dc481d73a](https://linux-hardware.org/?probe=9dc481d73a) | Sep 22, 2024 |
| HP            | Victus by Gaming Laptop ... | [e647d35e74](https://linux-hardware.org/?probe=e647d35e74) | Sep 20, 2024 |
| Lenovo        | ThinkPad W530 2463A52       | [68f2429248](https://linux-hardware.org/?probe=68f2429248) | Sep 19, 2024 |
| Acer          | Nitro AN515-52              | [0bc35e551d](https://linux-hardware.org/?probe=0bc35e551d) | Sep 18, 2024 |
| Lenovo        | ThinkPad W530 2463A52       | [c0860a78cd](https://linux-hardware.org/?probe=c0860a78cd) | Sep 18, 2024 |
| HP            | Pavilion 17                 | [fb7884d776](https://linux-hardware.org/?probe=fb7884d776) | Sep 16, 2024 |
| Sony          | VPCEH2E0E                   | [0db705664d](https://linux-hardware.org/?probe=0db705664d) | Sep 14, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [bea14db033](https://linux-hardware.org/?probe=bea14db033) | Sep 11, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [121ee8244a](https://linux-hardware.org/?probe=121ee8244a) | Sep 05, 2024 |
| HP            | EliteBook 840 G1            | [453cbe339f](https://linux-hardware.org/?probe=453cbe339f) | Sep 05, 2024 |
| HP            | ZBook Power 15.6 inch G8... | [d8b60dcb98](https://linux-hardware.org/?probe=d8b60dcb98) | Sep 02, 2024 |
| Dell          | Latitude 5510               | [634228ff35](https://linux-hardware.org/?probe=634228ff35) | Sep 02, 2024 |
| Notebook      | W54_55SU1,SUW               | [151da93887](https://linux-hardware.org/?probe=151da93887) | Aug 31, 2024 |
| Dell          | Vostro 5481                 | [04820e5465](https://linux-hardware.org/?probe=04820e5465) | Aug 30, 2024 |
| Dell          | Latitude E7270              | [7b008f6780](https://linux-hardware.org/?probe=7b008f6780) | Aug 30, 2024 |
| HP            | Pavilion dv8                | [33c6d5838c](https://linux-hardware.org/?probe=33c6d5838c) | Aug 30, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [e9c6b514ef](https://linux-hardware.org/?probe=e9c6b514ef) | Aug 30, 2024 |
| Dell          | G15 5530                    | [601308044e](https://linux-hardware.org/?probe=601308044e) | Aug 26, 2024 |
| HP            | Pavilion dv6700             | [8a6c458a6b](https://linux-hardware.org/?probe=8a6c458a6b) | Aug 25, 2024 |
| HP            | Pavilion dv6700             | [f3eedcecc1](https://linux-hardware.org/?probe=f3eedcecc1) | Aug 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [75931341d7](https://linux-hardware.org/?probe=75931341d7) | Aug 25, 2024 |
| Gigabyte      | G5 KF                       | [0e5c227ff1](https://linux-hardware.org/?probe=0e5c227ff1) | Aug 23, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a223c3c2be](https://linux-hardware.org/?probe=a223c3c2be) | Aug 23, 2024 |
| Dell          | Vostro 5481                 | [c76a7034cd](https://linux-hardware.org/?probe=c76a7034cd) | Aug 16, 2024 |
| Toshiba       | Satellite L50-B             | [e259b80ab9](https://linux-hardware.org/?probe=e259b80ab9) | Aug 14, 2024 |
| Lenovo        | ThinkPad T560 20FJS3X800    | [6a14a30f0c](https://linux-hardware.org/?probe=6a14a30f0c) | Aug 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [458556ade2](https://linux-hardware.org/?probe=458556ade2) | Aug 08, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | [d415774845](https://linux-hardware.org/?probe=d415774845) | Aug 07, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [f21bd1a58e](https://linux-hardware.org/?probe=f21bd1a58e) | Aug 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [feaff16732](https://linux-hardware.org/?probe=feaff16732) | Aug 05, 2024 |
| Lenovo        | Unknown                     | [60da7baec5](https://linux-hardware.org/?probe=60da7baec5) | Aug 05, 2024 |
| Fujitsu       | FARQ04001                   | [6196b6b339](https://linux-hardware.org/?probe=6196b6b339) | Aug 04, 2024 |
| Valve         | Jupiter                     | [185cee5333](https://linux-hardware.org/?probe=185cee5333) | Aug 04, 2024 |
| TUXEDO        | Pulse 14 Gen1               | [0a09eb534e](https://linux-hardware.org/?probe=0a09eb534e) | Aug 02, 2024 |
| Dell          | Vostro 1700                 | [c3520cb3d6](https://linux-hardware.org/?probe=c3520cb3d6) | Aug 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [846f130e8f](https://linux-hardware.org/?probe=846f130e8f) | Jul 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [99bd685bab](https://linux-hardware.org/?probe=99bd685bab) | Jul 30, 2024 |
| Unknown       | Unknown                     | [e667d93a6d](https://linux-hardware.org/?probe=e667d93a6d) | Jul 30, 2024 |
| Lenovo        | ThinkPad T480s 20L8002XM... | [5a1984e44d](https://linux-hardware.org/?probe=5a1984e44d) | Jul 30, 2024 |
| HP            | EliteBook 745 G6            | [d4583a12a6](https://linux-hardware.org/?probe=d4583a12a6) | Jul 27, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | [a818073a3d](https://linux-hardware.org/?probe=a818073a3d) | Jul 27, 2024 |
| MSI           | Katana 15 B13VEK            | [c8c421d5c3](https://linux-hardware.org/?probe=c8c421d5c3) | Jul 26, 2024 |
| Dell          | Vostro 15 3510              | [9e97e029b6](https://linux-hardware.org/?probe=9e97e029b6) | Jul 26, 2024 |
| Alienware     | Area-51m R2 A00             | [b81380e2f7](https://linux-hardware.org/?probe=b81380e2f7) | Jul 17, 2024 |
| Acer          | Aspire A315-24P             | [60b1f0475f](https://linux-hardware.org/?probe=60b1f0475f) | Jul 17, 2024 |
| HP            | 15                          | [382f3aa7d4](https://linux-hardware.org/?probe=382f3aa7d4) | Jul 15, 2024 |
| HP            | Compaq 6720s                | [7eeec5b052](https://linux-hardware.org/?probe=7eeec5b052) | Jul 09, 2024 |
| HP            | Compaq 6720s                | [df5b153030](https://linux-hardware.org/?probe=df5b153030) | Jul 09, 2024 |
| Dell          | Inspiron 1564               | [3c5c95d839](https://linux-hardware.org/?probe=3c5c95d839) | Jul 07, 2024 |
| Acer          | Aspire 5251                 | [ee4236aa4b](https://linux-hardware.org/?probe=ee4236aa4b) | Jul 05, 2024 |
| Acer          | Aspire 5251                 | [738fcb5042](https://linux-hardware.org/?probe=738fcb5042) | Jul 04, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | [d3426ed926](https://linux-hardware.org/?probe=d3426ed926) | Jul 02, 2024 |
| ASUSTek       | T100TAF                     | [05c827f54c](https://linux-hardware.org/?probe=05c827f54c) | Jun 29, 2024 |
| Lenovo        | ThinkPad P53 20QN000DGE     | [7f25d623fe](https://linux-hardware.org/?probe=7f25d623fe) | Jun 28, 2024 |
| ASUSTek       | X510UQR                     | [c4b1e2a969](https://linux-hardware.org/?probe=c4b1e2a969) | Jun 27, 2024 |
| Apple         | MacBookPro11,1              | [0d84f70d08](https://linux-hardware.org/?probe=0d84f70d08) | Jun 25, 2024 |
| Acer          | Predator PH317-53           | [d93de492ee](https://linux-hardware.org/?probe=d93de492ee) | Jun 25, 2024 |
| Acer          | Predator PH317-53           | [d2b4fa437b](https://linux-hardware.org/?probe=d2b4fa437b) | Jun 25, 2024 |
| Apple         | MacBookPro11,1              | [7945e52c36](https://linux-hardware.org/?probe=7945e52c36) | Jun 22, 2024 |
| Lenovo        | ThinkPad X390 20Q00055MX    | [edfa886a82](https://linux-hardware.org/?probe=edfa886a82) | Jun 20, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [54e7691c73](https://linux-hardware.org/?probe=54e7691c73) | Jun 15, 2024 |
| Lenovo        | ThinkPad X230 23257G6       | [faeb824333](https://linux-hardware.org/?probe=faeb824333) | Jun 13, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [8462e256b8](https://linux-hardware.org/?probe=8462e256b8) | Jun 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a8b17e7809](https://linux-hardware.org/?probe=a8b17e7809) | Jun 07, 2024 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | [144cbd14af](https://linux-hardware.org/?probe=144cbd14af) | Jun 07, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [6ccb04db71](https://linux-hardware.org/?probe=6ccb04db71) | Jun 03, 2024 |
| ASUSTek       | GL553VD                     | [0019cc311b](https://linux-hardware.org/?probe=0019cc311b) | Jun 02, 2024 |
| HP            | EliteBook 1050 G1           | [25ad5b6cb8](https://linux-hardware.org/?probe=25ad5b6cb8) | May 30, 2024 |
| HP            | G62                         | [122c14c90c](https://linux-hardware.org/?probe=122c14c90c) | May 28, 2024 |
| Lenovo        | ThinkPad X270 20HMS7LM00    | [2d489a62b7](https://linux-hardware.org/?probe=2d489a62b7) | May 26, 2024 |
| Acer          | Aspire A515-57              | [c4026575a0](https://linux-hardware.org/?probe=c4026575a0) | May 25, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d945b21cae](https://linux-hardware.org/?probe=d945b21cae) | May 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [db5d8ff53d](https://linux-hardware.org/?probe=db5d8ff53d) | May 22, 2024 |
| HP            | Pavilion 15                 | [d266ada5a0](https://linux-hardware.org/?probe=d266ada5a0) | May 21, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [9002cd7940](https://linux-hardware.org/?probe=9002cd7940) | May 19, 2024 |
| HP            | 650                         | [4e91cb9494](https://linux-hardware.org/?probe=4e91cb9494) | May 19, 2024 |
| HP            | Pavilion dv8                | [e9722285d5](https://linux-hardware.org/?probe=e9722285d5) | May 16, 2024 |
| Lenovo        | ThinkPad X390 20Q00055MX    | [4501efe852](https://linux-hardware.org/?probe=4501efe852) | May 15, 2024 |
| HP            | Pavilion dv8                | [a44fe4349b](https://linux-hardware.org/?probe=a44fe4349b) | May 13, 2024 |
| HP            | EliteBook 840 G6            | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| Lenovo        | IdeaPad S12 20021,2959      | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| Lenovo        | ThinkPad X230 2325BK0       | [0c39b2e745](https://linux-hardware.org/?probe=0c39b2e745) | May 05, 2024 |
| Dell          | Inspiron 11-3162            | [ccf99ca586](https://linux-hardware.org/?probe=ccf99ca586) | May 05, 2024 |
| Lenovo        | ThinkPad X270 20HMS34L00    | [dcc424b27d](https://linux-hardware.org/?probe=dcc424b27d) | May 04, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [c03d3e0508](https://linux-hardware.org/?probe=c03d3e0508) | May 03, 2024 |
| Toshiba       | Satellite P200              | [f9f88ee996](https://linux-hardware.org/?probe=f9f88ee996) | May 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [01432a3384](https://linux-hardware.org/?probe=01432a3384) | Apr 23, 2024 |
| Allview       | Allbook J                   | [77d90c2a69](https://linux-hardware.org/?probe=77d90c2a69) | Apr 23, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [e0c405894c](https://linux-hardware.org/?probe=e0c405894c) | Apr 21, 2024 |
| Toshiba       | Satellite C850-124          | [b580358635](https://linux-hardware.org/?probe=b580358635) | Apr 20, 2024 |
| Unknown       | Unknown                     | [7ee99946ca](https://linux-hardware.org/?probe=7ee99946ca) | Apr 19, 2024 |
| Acer          | Aspire 7738                 | [dc56784ca7](https://linux-hardware.org/?probe=dc56784ca7) | Apr 19, 2024 |
| HP            | ProBook 640 G1              | [a5d4162d2f](https://linux-hardware.org/?probe=a5d4162d2f) | Apr 19, 2024 |
| Allview       | Allbook J                   | [a106195c34](https://linux-hardware.org/?probe=a106195c34) | Apr 18, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [2d02eae5ec](https://linux-hardware.org/?probe=2d02eae5ec) | Apr 13, 2024 |
| Lenovo        | ThinkPad T440 20B7A0MN04    | [2244374672](https://linux-hardware.org/?probe=2244374672) | Apr 13, 2024 |
| HP            | Pavilion dv8                | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e5830d8754](https://linux-hardware.org/?probe=e5830d8754) | Apr 07, 2024 |
| Acer          | Predator PH315-53           | [4c8bbd0426](https://linux-hardware.org/?probe=4c8bbd0426) | Apr 07, 2024 |
| Lenovo        | Unknown                     | [18961ee7a8](https://linux-hardware.org/?probe=18961ee7a8) | Apr 07, 2024 |
| Lenovo        | Unknown                     | [d74a81067e](https://linux-hardware.org/?probe=d74a81067e) | Apr 07, 2024 |
| Acer          | Aspire V5-572G              | [ca5e1f767e](https://linux-hardware.org/?probe=ca5e1f767e) | Apr 04, 2024 |
| ASUSTek       | X55VD                       | [bc22ba01de](https://linux-hardware.org/?probe=bc22ba01de) | Apr 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [708291ee28](https://linux-hardware.org/?probe=708291ee28) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [449d0ad45b](https://linux-hardware.org/?probe=449d0ad45b) | Mar 31, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [431002bc2d](https://linux-hardware.org/?probe=431002bc2d) | Mar 30, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [3d2abf7e0d](https://linux-hardware.org/?probe=3d2abf7e0d) | Mar 30, 2024 |
| Dell          | Latitude 5580               | [db427c180d](https://linux-hardware.org/?probe=db427c180d) | Mar 28, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [deae5b6cdf](https://linux-hardware.org/?probe=deae5b6cdf) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [602d79d663](https://linux-hardware.org/?probe=602d79d663) | Mar 27, 2024 |
| HP            | Compaq CQ58                 | [bfe7fd8a2e](https://linux-hardware.org/?probe=bfe7fd8a2e) | Mar 26, 2024 |
| HP            | Compaq CQ58                 | [806d659258](https://linux-hardware.org/?probe=806d659258) | Mar 26, 2024 |
| HP            | EliteBook 2540p             | [99983f8fbf](https://linux-hardware.org/?probe=99983f8fbf) | Mar 25, 2024 |
| Dell          | Precision M4700             | [212d29f26d](https://linux-hardware.org/?probe=212d29f26d) | Mar 21, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [f8fa83eaf5](https://linux-hardware.org/?probe=f8fa83eaf5) | Mar 20, 2024 |
| Acer          | Predator PT516-52s          | [86614957f2](https://linux-hardware.org/?probe=86614957f2) | Mar 17, 2024 |
| Lenovo        | ThinkPad X230 2325CL7       | [9bde6bc531](https://linux-hardware.org/?probe=9bde6bc531) | Mar 17, 2024 |
| ASUSTek       | X55VD                       | [a959f1dfec](https://linux-hardware.org/?probe=a959f1dfec) | Mar 17, 2024 |
| Lenovo        | G50-30 80G0                 | [3ec06d0273](https://linux-hardware.org/?probe=3ec06d0273) | Mar 16, 2024 |
| ASUSTek       | X541NA                      | [75bc4f3af5](https://linux-hardware.org/?probe=75bc4f3af5) | Mar 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [fbc1335ccc](https://linux-hardware.org/?probe=fbc1335ccc) | Mar 12, 2024 |
| Acer          | Aspire A315-59              | [edf84e43ee](https://linux-hardware.org/?probe=edf84e43ee) | Mar 11, 2024 |
| HP            | 255 G8 Notebook PC          | [ca3f8b06ab](https://linux-hardware.org/?probe=ca3f8b06ab) | Mar 10, 2024 |
| Allview       | Allbook J                   | [58b6452c8f](https://linux-hardware.org/?probe=58b6452c8f) | Mar 08, 2024 |
| Dell          | XPS 15 9560                 | [898154cbf9](https://linux-hardware.org/?probe=898154cbf9) | Mar 05, 2024 |
| HP            | ZBook Studio G5             | [208ce1e5fd](https://linux-hardware.org/?probe=208ce1e5fd) | Mar 04, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b957a4b5d8](https://linux-hardware.org/?probe=b957a4b5d8) | Mar 03, 2024 |
| Allview       | Allbook J                   | [dd1b4469c1](https://linux-hardware.org/?probe=dd1b4469c1) | Mar 01, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [935b64ed30](https://linux-hardware.org/?probe=935b64ed30) | Feb 29, 2024 |
| MSI           | Thin GF63 12UDX             | [648c7d0aa4](https://linux-hardware.org/?probe=648c7d0aa4) | Feb 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [27c2f0156e](https://linux-hardware.org/?probe=27c2f0156e) | Feb 25, 2024 |
| MSI           | Modern 14 B11MO             | [6f5a4e6e1e](https://linux-hardware.org/?probe=6f5a4e6e1e) | Feb 23, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [e2780e976f](https://linux-hardware.org/?probe=e2780e976f) | Feb 18, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [95978292b2](https://linux-hardware.org/?probe=95978292b2) | Feb 18, 2024 |
| Dell          | Latitude E5470              | [4f6f03415f](https://linux-hardware.org/?probe=4f6f03415f) | Feb 12, 2024 |
| Acer          | Predator PT516-52s          | [d271f4b0ca](https://linux-hardware.org/?probe=d271f4b0ca) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | [a3255728e7](https://linux-hardware.org/?probe=a3255728e7) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | [aa78cf8909](https://linux-hardware.org/?probe=aa78cf8909) | Feb 12, 2024 |
| Dell          | Vostro 3580                 | [1d2758029b](https://linux-hardware.org/?probe=1d2758029b) | Feb 08, 2024 |
| Dell          | Vostro 3580                 | [0b028612c5](https://linux-hardware.org/?probe=0b028612c5) | Feb 08, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | [d01b52dd20](https://linux-hardware.org/?probe=d01b52dd20) | Feb 05, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | [1e6645fdc9](https://linux-hardware.org/?probe=1e6645fdc9) | Feb 05, 2024 |
| Acer          | Swift SF314-43              | [e87efb031b](https://linux-hardware.org/?probe=e87efb031b) | Feb 02, 2024 |
| HP            | Pavilion Notebook           | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| HP            | 255 G8 Notebook PC          | [62254b1636](https://linux-hardware.org/?probe=62254b1636) | Jan 31, 2024 |
| Acer          | Aspire A315-41              | [a78d79030e](https://linux-hardware.org/?probe=a78d79030e) | Jan 30, 2024 |
| Dell          | Studio 1747                 | [b43d9b4a13](https://linux-hardware.org/?probe=b43d9b4a13) | Jan 29, 2024 |
| Dell          | Studio 1747                 | [9fe0b059bc](https://linux-hardware.org/?probe=9fe0b059bc) | Jan 29, 2024 |
| HP            | Victus by Gaming Laptop ... | [49e891b67d](https://linux-hardware.org/?probe=49e891b67d) | Jan 28, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [be74f076bd](https://linux-hardware.org/?probe=be74f076bd) | Jan 23, 2024 |
| Dell          | Latitude 7280               | [21e6e4a581](https://linux-hardware.org/?probe=21e6e4a581) | Jan 22, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [36cb9057d7](https://linux-hardware.org/?probe=36cb9057d7) | Jan 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [f6204361d0](https://linux-hardware.org/?probe=f6204361d0) | Jan 19, 2024 |
| Apple         | MacBookAir6,2               | [12539bda5e](https://linux-hardware.org/?probe=12539bda5e) | Jan 19, 2024 |
| HP            | 255 G8 Notebook PC          | [667df4a998](https://linux-hardware.org/?probe=667df4a998) | Jan 17, 2024 |
| HP            | 255 G3                      | [7f8af802a0](https://linux-hardware.org/?probe=7f8af802a0) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [82f1c7e4f3](https://linux-hardware.org/?probe=82f1c7e4f3) | Jan 14, 2024 |
| HP            | EliteBook 745 G5            | [64314a5149](https://linux-hardware.org/?probe=64314a5149) | Jan 13, 2024 |
| Dell          | Latitude 5431               | [45d7b96fb3](https://linux-hardware.org/?probe=45d7b96fb3) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Dell          | Latitude E7470              | [2d36d1a363](https://linux-hardware.org/?probe=2d36d1a363) | Jan 11, 2024 |
| MSI           | Katana GF66 12UG            | [d4affacb08](https://linux-hardware.org/?probe=d4affacb08) | Jan 08, 2024 |
| Dell          | Latitude 7280               | [9557a37753](https://linux-hardware.org/?probe=9557a37753) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [26ec173956](https://linux-hardware.org/?probe=26ec173956) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [514f7e46c3](https://linux-hardware.org/?probe=514f7e46c3) | Jan 04, 2024 |
| Dell          | Latitude D630               | [e48315d3aa](https://linux-hardware.org/?probe=e48315d3aa) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [88f364d196](https://linux-hardware.org/?probe=88f364d196) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | [15ae58d88c](https://linux-hardware.org/?probe=15ae58d88c) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | [c9312cc676](https://linux-hardware.org/?probe=c9312cc676) | Jan 03, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Sony          | VGN-CS21Z_Q                 | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Dell          | Precision 5560              | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| Lenovo        | G570 20079                  | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| Lenovo        | G50-30 80G0                 | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| Lenovo        | G580 20150                  | [c6c8d22a8e](https://linux-hardware.org/?probe=c6c8d22a8e) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [c71041fa59](https://linux-hardware.org/?probe=c71041fa59) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| Dell          | Vostro 3400                 | [0841e29863](https://linux-hardware.org/?probe=0841e29863) | Dec 10, 2023 |
| HP            | EliteBook 830 G5            | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| Lenovo        | 3000 G410                   | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| MSI           | Modern 14 B4MW              | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [80e09b727b](https://linux-hardware.org/?probe=80e09b727b) | Nov 30, 2023 |
| HP            | EliteBook 8530p             | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DV0Y    | [c68289cf4c](https://linux-hardware.org/?probe=c68289cf4c) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Lenovo        | Unknown                     | [2ab4754aa8](https://linux-hardware.org/?probe=2ab4754aa8) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| Acer          | Aspire 5750G                | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Lenovo        | ThinkPad X270 20HMS76D02    | [7da50d5ad3](https://linux-hardware.org/?probe=7da50d5ad3) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Apple         | MacBookPro6,2               | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [4a2561319d](https://linux-hardware.org/?probe=4a2561319d) | Nov 08, 2023 |
| Lenovo        | ThinkPad X230 23252EG       | [143a351fe0](https://linux-hardware.org/?probe=143a351fe0) | Nov 08, 2023 |
| Valve         | Jupiter                     | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c06d2e60fc](https://linux-hardware.org/?probe=c06d2e60fc) | Nov 01, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [09b312b58c](https://linux-hardware.org/?probe=09b312b58c) | Oct 30, 2023 |
| Acer          | Aspire 5810T                | [9b65c56faa](https://linux-hardware.org/?probe=9b65c56faa) | Oct 29, 2023 |
| Sony          | SVE1712V1EB                 | [3b8803286b](https://linux-hardware.org/?probe=3b8803286b) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | [63963cbe04](https://linux-hardware.org/?probe=63963cbe04) | Oct 25, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [9c136d661d](https://linux-hardware.org/?probe=9c136d661d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| Dell          | Latitude E5410              | [b1559718de](https://linux-hardware.org/?probe=b1559718de) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| ASUSTek       | K73SV                       | [63341aa786](https://linux-hardware.org/?probe=63341aa786) | Oct 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ec7aee0455](https://linux-hardware.org/?probe=ec7aee0455) | Oct 10, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e06a9dcd7d](https://linux-hardware.org/?probe=e06a9dcd7d) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| HP            | 635                         | [ef474a26d0](https://linux-hardware.org/?probe=ef474a26d0) | Oct 07, 2023 |
| Dell          | Vostro 15 3510              | [233fe08ffd](https://linux-hardware.org/?probe=233fe08ffd) | Oct 07, 2023 |
| ONDA          | V80 PLUS                    | [8651e33f83](https://linux-hardware.org/?probe=8651e33f83) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5584c834bc](https://linux-hardware.org/?probe=5584c834bc) | Oct 04, 2023 |
| HP            | 15                          | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| HP            | 15                          | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Dell          | Precision 5510              | [34ddd03339](https://linux-hardware.org/?probe=34ddd03339) | Sep 25, 2023 |
| Toshiba       | Satellite A300              | [03aa0d1366](https://linux-hardware.org/?probe=03aa0d1366) | Sep 25, 2023 |
| Acer          | Nitro AN515-58              | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Acer          | Extensa 5635ZG              | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Timi          | A30                         | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [744362d446](https://linux-hardware.org/?probe=744362d446) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [82d4f51421](https://linux-hardware.org/?probe=82d4f51421) | Sep 12, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ae29792d70](https://linux-hardware.org/?probe=ae29792d70) | Sep 11, 2023 |
| Dell          | Latitude 5431               | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| Dell          | Latitude 5431               | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| MSI           | Bravo 15 C7VF               | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [245964564e](https://linux-hardware.org/?probe=245964564e) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| ASUSTek       | K55VD                       | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6dc701c67d](https://linux-hardware.org/?probe=6dc701c67d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| Dell          | Studio 1747                 | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| MSI           | GL65 9SE                    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Acer          | Aspire 5755G                | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [3dacfd8a02](https://linux-hardware.org/?probe=3dacfd8a02) | Aug 16, 2023 |
| Dell          | Latitude E4300              | [7c153c96f5](https://linux-hardware.org/?probe=7c153c96f5) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Dell          | Latitude E4300              | [ec4bac7b02](https://linux-hardware.org/?probe=ec4bac7b02) | Aug 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Dell          | Inspiron 15 3520            | [7723e84488](https://linux-hardware.org/?probe=7723e84488) | Aug 09, 2023 |
| Dell          | Latitude E4300              | [9ae3d19a62](https://linux-hardware.org/?probe=9ae3d19a62) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | Vostro 1700                 | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| Dell          | Precision 7750              | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| HP            | ProBook 4530s               | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| TUXEDO        | Gemini Gen2                 | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| HP            | ProBook 6570b               | [0a74371e23](https://linux-hardware.org/?probe=0a74371e23) | Jul 18, 2023 |
| Dell          | Inspiron 3551               | [543382ea16](https://linux-hardware.org/?probe=543382ea16) | Jul 16, 2023 |
| Dell          | Inspiron 3551               | [74050e892f](https://linux-hardware.org/?probe=74050e892f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire A515-52G             | [639eb4733c](https://linux-hardware.org/?probe=639eb4733c) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Dell          | G15 5511                    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| HP            | Notebook                    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Dell          | Latitude 3180               | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [3c0316ef92](https://linux-hardware.org/?probe=3c0316ef92) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Lenovo        | Unknown                     | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| Dell          | Vostro 3500                 | [3d694e1b9a](https://linux-hardware.org/?probe=3d694e1b9a) | Jun 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Dell          | Precision 7710              | [f1b57ded18](https://linux-hardware.org/?probe=f1b57ded18) | Jun 08, 2023 |
| Dell          | Latitude 3350               | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| Cube          | i16-L                       | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| HP            | Laptop 15-dw3xxx            | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Dell          | Inspiron 7577               | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Lenovo        | Unknown                     | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Dell          | Inspiron 1501               | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Inspiron N5110              | [4280ce2bd4](https://linux-hardware.org/?probe=4280ce2bd4) | May 15, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Beelink       | BT3 PRO                     | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| MSI           | Modern 15 A5M               | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| Acer          | Aspire A515-51G             | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Dell          | Vostro 3500                 | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| Dell          | Latitude E4300              | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| HP            | ProBook 4540s               | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [3b0ab63643](https://linux-hardware.org/?probe=3b0ab63643) | Apr 17, 2023 |
| Valve         | Jupiter                     | [f05e3341d3](https://linux-hardware.org/?probe=f05e3341d3) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Acer          | Aspire A515-57              | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Gigabyte      | G5 KF                       | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Dell          | Vostro 5620                 | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| HP            | Notebook                    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [90b9eaf3fe](https://linux-hardware.org/?probe=90b9eaf3fe) | Apr 02, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| Acer          | Aspire A515-51G             | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [88caf7c0d1](https://linux-hardware.org/?probe=88caf7c0d1) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Toshiba       | Satellite C850-140          | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| HP            | Pavilion g6                 | [abd4bb0963](https://linux-hardware.org/?probe=abd4bb0963) | Mar 21, 2023 |
| HP            | Pavilion g6                 | [4dcebf6a41](https://linux-hardware.org/?probe=4dcebf6a41) | Mar 21, 2023 |
| HP            | ProBook 6475b               | [1b7a5f385c](https://linux-hardware.org/?probe=1b7a5f385c) | Mar 18, 2023 |
| HP            | ProBook 6475b               | [0fd12da29b](https://linux-hardware.org/?probe=0fd12da29b) | Mar 18, 2023 |
| HP            | ProBook 6475b               | [701aca7f61](https://linux-hardware.org/?probe=701aca7f61) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | 255 G6 Notebook PC          | [47df31e0fb](https://linux-hardware.org/?probe=47df31e0fb) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [c14956dd2d](https://linux-hardware.org/?probe=c14956dd2d) | Mar 12, 2023 |
| Acer          | Aspire 5333                 | [214db069e4](https://linux-hardware.org/?probe=214db069e4) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [65c2aab8aa](https://linux-hardware.org/?probe=65c2aab8aa) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [e03e243c84](https://linux-hardware.org/?probe=e03e243c84) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Dell          | Latitude E4300              | [3c777f1c07](https://linux-hardware.org/?probe=3c777f1c07) | Mar 10, 2023 |
| HP            | ProBook 6475b               | [be06cdc105](https://linux-hardware.org/?probe=be06cdc105) | Mar 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| ASUSTek       | X580VD                      | [f4b107fbf3](https://linux-hardware.org/?probe=f4b107fbf3) | Mar 02, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | [c068117b39](https://linux-hardware.org/?probe=c068117b39) | Mar 01, 2023 |
| Valve         | Jupiter                     | [df09052bac](https://linux-hardware.org/?probe=df09052bac) | Mar 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| HP            | Notebook                    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [4f7bbbdd28](https://linux-hardware.org/?probe=4f7bbbdd28) | Feb 24, 2023 |
| Google        | Astronaut                   | [71e8582f54](https://linux-hardware.org/?probe=71e8582f54) | Feb 22, 2023 |
| Google        | Astronaut                   | [4949e50dad](https://linux-hardware.org/?probe=4949e50dad) | Feb 22, 2023 |
| HP            | Notebook                    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Valve         | Jupiter                     | [74b6676de3](https://linux-hardware.org/?probe=74b6676de3) | Feb 19, 2023 |
| HP            | Notebook                    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| HP            | Notebook                    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| HP            | ProBook 6460b               | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Valve         | Jupiter                     | [1df562d2d8](https://linux-hardware.org/?probe=1df562d2d8) | Feb 13, 2023 |
| Dell          | Precision M4700             | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Dell          | Latitude E7470              | [9b58106fd6](https://linux-hardware.org/?probe=9b58106fd6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| Dell          | Precision M4700             | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| Dell          | Precision 5540              | [de6a1c523e](https://linux-hardware.org/?probe=de6a1c523e) | Jan 28, 2023 |
| HP            | ProBook 455 G1              | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| HP            | Pavilion g6                 | [c34bc63cb0](https://linux-hardware.org/?probe=c34bc63cb0) | Jan 24, 2023 |
| HP            | Pavilion g6                 | [a9a199e6f7](https://linux-hardware.org/?probe=a9a199e6f7) | Jan 24, 2023 |
| Dell          | Vostro 5620                 | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Acer          | Aspire A315-59              | [ca332b4905](https://linux-hardware.org/?probe=ca332b4905) | Jan 13, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| Google        | Kled                        | [6380ae012e](https://linux-hardware.org/?probe=6380ae012e) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| Dell          | Precision M6400             | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [be5212ebcc](https://linux-hardware.org/?probe=be5212ebcc) | Jan 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [c51bc128e2](https://linux-hardware.org/?probe=c51bc128e2) | Dec 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Valve         | Jupiter                     | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Dell          | Latitude E5410              | [969f85bfc3](https://linux-hardware.org/?probe=969f85bfc3) | Dec 21, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Valve         | Jupiter                     | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| Acer          | AO756                       | [ebc4d7cfcb](https://linux-hardware.org/?probe=ebc4d7cfcb) | Dec 16, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| Dell          | Vostro 5620                 | [6987aeacd5](https://linux-hardware.org/?probe=6987aeacd5) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Dell          | Precision 5510              | [f464385b16](https://linux-hardware.org/?probe=f464385b16) | Dec 13, 2022 |
| Dell          | Precision 5510              | [f4188b30c9](https://linux-hardware.org/?probe=f4188b30c9) | Dec 13, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| HP            | Compaq Presario CQ71        | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Acer          | Aspire ES1-731G             | [589cce31c8](https://linux-hardware.org/?probe=589cce31c8) | Dec 09, 2022 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [ff0997b72a](https://linux-hardware.org/?probe=ff0997b72a) | Dec 09, 2022 |
| HP            | ProBook 450 G0              | [01e7f95a23](https://linux-hardware.org/?probe=01e7f95a23) | Dec 07, 2022 |
| HP            | ProBook 450 G0              | [c3b6c86431](https://linux-hardware.org/?probe=c3b6c86431) | Dec 07, 2022 |
| Dell          | Vostro 5620                 | [50acc3b3b8](https://linux-hardware.org/?probe=50acc3b3b8) | Dec 04, 2022 |
| ASUSTek       | X541NA                      | [9da9a87b5b](https://linux-hardware.org/?probe=9da9a87b5b) | Dec 03, 2022 |
| Acer          | Aspire ES1-731G             | [06918f4cc5](https://linux-hardware.org/?probe=06918f4cc5) | Dec 03, 2022 |
| Dell          | Inspiron N7010              | [3e9458fd24](https://linux-hardware.org/?probe=3e9458fd24) | Dec 02, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| Acer          | AO756                       | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Dell          | Latitude 5420               | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| HP            | EliteBook 2730p             | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| HP            | ProBook 450 G6              | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Acer          | Aspire 5830T                | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Lenovo        | Y50-70 20378                | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| Acer          | Nitro AN515-45              | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| HP            | ProBook 640 G1              | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Apple         | MacBookPro16,4              | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| Lenovo        | Unknown                     | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Toshiba       | PORTEGE Z930                | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| HP            | ProBook 450 G3              | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| HP            | ProBook 450 G0              | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| HP            | Compaq 6730s                | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Dell          | XPS 15 9570                 | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Acer          | Aspire E5-571               | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| ASUSTek       | X540LJ                      | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Toshiba       | Satellite C650              | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Dell          | Precision M6800             | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| MSI           | Modern 15 A4M               | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| HP            | ProBook 455 G7              | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Dell          | Precision M4600             | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Dell          | Inspiron 7559               | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASUSTek       | N551VW                      | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Dell          | Latitude E6330              | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| HP            | 250 G6 Notebook PC          | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| Toshiba       | Satellite A200              | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| HP            | Notebook                    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| Acer          | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| HP            | ProBook 4540s               | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| HP            | EliteBook 8460p             | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| HP            | Pavilion dv7                | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Acer          | Aspire A515-52G             | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| Acer          | Extensa 5630                | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| HP            | EliteBook 850 G5            | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| AMI           | Cherry Trail CR             | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | ProBook 6450b               | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Lenovo        | V15-ADA 82C7                | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| Acer          | Aspire V3-571G              | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Dell          | Latitude 5410               | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Acer          | Extensa 5630                | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Dell          | Studio 1747                 | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| ASUSTek       | GL553VE                     | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| Dell          | Studio 1535                 | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| HP            | EliteBook 8460p             | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Lenovo        | ThinkPad T61 765912G        | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| HP            | EliteBook 850 G5            | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| HP            | Notebook                    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| Lenovo        | ThinkPad X230 232425U       | [69e5ab7b60](https://linux-hardware.org/?probe=69e5ab7b60) | Apr 24, 2021 |
| Dell          | Vostro 3580                 | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Dell          | Vostro 3558                 | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Acer          | Nitro AN515-43              | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| Dell          | Latitude E6330              | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| Dell          | Inspiron MM061              | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| Dell          | Inspiron 3584               | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| ASUSTek       | G752VL                      | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Toshiba       | TECRA A11                   | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| Dell          | Vostro 3580                 | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| Dell          | Vostro 3580                 | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| Apple         | MacBook4,1                  | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| HP            | Laptop 15-da0xxx            | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| MSI           | GP60 2PE                    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| HP            | EliteBook 850 G5            | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Packard Be... | EasyNote TK87               | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Dell          | Latitude E6410              | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| Toshiba       | Satellite C50-A-19T         | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Apple         | MacBook4,1                  | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Dell          | Latitude E5430 non-vPro     | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Apple         | MacBook4,1                  | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| HP            | EliteBook 8560p             | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| Dell          | Latitude 5591               | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| Dell          | Inspiron N5110              | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| ASUSTek       | G551JM                      | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 74        | 7.87%   |
| Ubuntu 22.04                 | 60        | 6.38%   |
| Ubuntu 18.04                 | 50        | 5.32%   |
| Pop!_OS 22.04                | 18        | 1.91%   |
| Manjaro                      | 16        | 1.7%    |
| OpenMandriva 4.3             | 15        | 1.6%    |
| Fedora 39                    | 15        | 1.6%    |
| Fedora 38                    | 15        | 1.6%    |
| Arch Rolling                 | 15        | 1.6%    |
| Debian 11                    | 14        | 1.49%   |
| Ubuntu 24.04                 | 13        | 1.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 13        | 1.38%   |
| OpenMandriva 4.2             | 13        | 1.38%   |
| Linux Mint 20.3              | 13        | 1.38%   |
| Linux Mint 21.1              | 12        | 1.28%   |
| KDE neon 20.04               | 12        | 1.28%   |
| Linux Mint 20.1              | 11        | 1.17%   |
| Fedora 40                    | 11        | 1.17%   |
| ArcoLinux Rolling            | 11        | 1.17%   |
| Zorin 16                     | 10        | 1.06%   |
| ROSA R11                     | 10        | 1.06%   |
| Linux Mint 20.2              | 10        | 1.06%   |
| Linux Mint 19.3              | 10        | 1.06%   |
| Kubuntu 20.04                | 10        | 1.06%   |
| Ubuntu 22.10                 | 9         | 0.96%   |
| Ubuntu 19.04                 | 9         | 0.96%   |
| OpenMandriva 23.08           | 9         | 0.96%   |
| Arch                         | 9         | 0.96%   |
| Xubuntu 20.04                | 8         | 0.85%   |
| Ubuntu 23.10                 | 8         | 0.85%   |
| ROSA R10                     | 8         | 0.85%   |
| Linux Mint 21.2              | 8         | 0.85%   |
| Linux Mint 20                | 8         | 0.85%   |
| Fedora 33                    | 8         | 0.85%   |
| Ubuntu 19.10                 | 7         | 0.74%   |
| Debian 12                    | 7         | 0.74%   |
| Zorin 15                     | 6         | 0.64%   |
| Xubuntu 18.04                | 6         | 0.64%   |
| Ubuntu 23.04                 | 6         | 0.64%   |
| ROSA R9                      | 6         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 235       | 27.94%  |
| Linux Mint    | 80        | 9.51%   |
| Fedora        | 73        | 8.68%   |
| OpenMandriva  | 54        | 6.42%   |
| ROSA          | 35        | 4.16%   |
| Manjaro       | 35        | 4.16%   |
| Pop!_OS       | 30        | 3.57%   |
| Endless       | 25        | 2.97%   |
| Debian        | 25        | 2.97%   |
| Kubuntu       | 24        | 2.85%   |
| Arch          | 23        | 2.73%   |
| Zorin         | 21        | 2.5%    |
| Kali          | 21        | 2.5%    |
| KDE neon      | 19        | 2.26%   |
| Xubuntu       | 18        | 2.14%   |
| openSUSE      | 16        | 1.9%    |
| ArcoLinux     | 13        | 1.55%   |
| Clear Linux   | 9         | 1.07%   |
| Elementary    | 8         | 0.95%   |
| Ubuntu Unity  | 7         | 0.83%   |
| LMDE          | 6         | 0.71%   |
| EndeavourOS   | 6         | 0.71%   |
| SteamOS       | 5         | 0.59%   |
| TUXEDO OS     | 3         | 0.36%   |
| Nobara        | 3         | 0.36%   |
| MX            | 3         | 0.36%   |
| Lubuntu       | 3         | 0.36%   |
| Gentoo        | 3         | 0.36%   |
| CentOS        | 3         | 0.36%   |
| Artix         | 3         | 0.36%   |
| Void Linux    | 2         | 0.24%   |
| Ubuntu MATE   | 2         | 0.24%   |
| Ubuntu Budgie | 2         | 0.24%   |
| Parrot        | 2         | 0.24%   |
| NixOS         | 2         | 0.24%   |
| Mageia        | 2         | 0.24%   |
| Garuda Linux  | 2         | 0.24%   |
| Deepin        | 2         | 0.24%   |
| BunsenLabs    | 2         | 0.24%   |
| Ubuntu Studio | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003        | 14        | 1.36%   |
| 5.10.14-desktop-1omv4002       | 13        | 1.26%   |
| 5.15.0-56-generic              | 12        | 1.16%   |
| 5.4.0-42-generic               | 10        | 0.97%   |
| 5.4.0-58-generic               | 8         | 0.77%   |
| 6.8.0-40-generic               | 7         | 0.68%   |
| 5.3.0-28-generic               | 7         | 0.68%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 7         | 0.68%   |
| 6.4.11-desktop-1omv2390        | 6         | 0.58%   |
| 6.2.0-39-generic               | 6         | 0.58%   |
| 6.2.0-26-generic               | 6         | 0.58%   |
| 5.8.0-14-generic               | 6         | 0.58%   |
| 6.8.0-51-generic               | 5         | 0.48%   |
| 6.10.0-desktop-1omv2490        | 5         | 0.48%   |
| 5.4.0-91-generic               | 5         | 0.48%   |
| 5.4.0-48-generic               | 5         | 0.48%   |
| 5.4.0-29-generic               | 5         | 0.48%   |
| 5.4.0-26-generic               | 5         | 0.48%   |
| 4.15.0-20-generic              | 5         | 0.48%   |
| 6.8.0-41-generic               | 4         | 0.39%   |
| 6.8.0-31-generic               | 4         | 0.39%   |
| 6.4.8-desktop-2omv2390         | 4         | 0.39%   |
| 6.2.6-desktop-1omv2390         | 4         | 0.39%   |
| 5.9.16-1-MANJARO               | 4         | 0.39%   |
| 5.4.0-90-generic               | 4         | 0.39%   |
| 5.4.0-77-generic               | 4         | 0.39%   |
| 5.4.0-73-generic               | 4         | 0.39%   |
| 5.4.0-65-generic               | 4         | 0.39%   |
| 5.4.0-47-generic               | 4         | 0.39%   |
| 5.4.0-40-generic               | 4         | 0.39%   |
| 5.4.0-19-generic               | 4         | 0.39%   |
| 5.3.0-53-generic               | 4         | 0.39%   |
| 5.3.0-46-generic               | 4         | 0.39%   |
| 5.19.0-35-generic              | 4         | 0.39%   |
| 5.15.0-52-generic              | 4         | 0.39%   |
| 5.15.0-47-generic              | 4         | 0.39%   |
| 5.13.0-28-generic              | 4         | 0.39%   |
| 5.13.0-27-generic              | 4         | 0.39%   |
| 5.11.0-37-generic              | 4         | 0.39%   |
| 5.0.0-37-generic               | 4         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 112       | 11.45%  |
| 5.15.0  | 72        | 7.36%   |
| 4.15.0  | 46        | 4.7%    |
| 6.8.0   | 39        | 3.99%   |
| 6.2.0   | 34        | 3.48%   |
| 5.3.0   | 32        | 3.27%   |
| 5.8.0   | 31        | 3.17%   |
| 6.5.0   | 29        | 2.97%   |
| 5.13.0  | 29        | 2.97%   |
| 5.19.0  | 25        | 2.56%   |
| 5.11.0  | 25        | 2.56%   |
| 5.0.0   | 23        | 2.35%   |
| 5.10.0  | 19        | 1.94%   |
| 4.18.0  | 16        | 1.64%   |
| 6.1.0   | 14        | 1.43%   |
| 5.16.7  | 14        | 1.43%   |
| 5.10.14 | 14        | 1.43%   |
| 4.19.0  | 9         | 0.92%   |
| 6.2.6   | 7         | 0.72%   |
| 5.9.16  | 7         | 0.72%   |
| 6.4.11  | 6         | 0.61%   |
| 4.9.20  | 6         | 0.61%   |
| 6.6.10  | 5         | 0.51%   |
| 6.10.0  | 5         | 0.51%   |
| 6.1.1   | 5         | 0.51%   |
| 5.17.5  | 5         | 0.51%   |
| 6.6.9   | 4         | 0.41%   |
| 6.4.8   | 4         | 0.41%   |
| 6.0.12  | 4         | 0.41%   |
| 6.0.0   | 4         | 0.41%   |
| 5.6.8   | 4         | 0.41%   |
| 5.18.0  | 4         | 0.41%   |
| 5.14.0  | 4         | 0.41%   |
| 4.4.0   | 4         | 0.41%   |
| 6.9.3   | 3         | 0.31%   |
| 6.8.11  | 3         | 0.31%   |
| 6.7.7   | 3         | 0.31%   |
| 6.7.4   | 3         | 0.31%   |
| 6.7.0   | 3         | 0.31%   |
| 6.6.8   | 3         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 120       | 12.57%  |
| 5.15    | 92        | 9.63%   |
| 6.2     | 51        | 5.34%   |
| 6.8     | 50        | 5.24%   |
| 5.10    | 46        | 4.82%   |
| 4.15    | 46        | 4.82%   |
| 6.5     | 44        | 4.61%   |
| 5.8     | 36        | 3.77%   |
| 5.3     | 36        | 3.77%   |
| 6.1     | 33        | 3.46%   |
| 5.13    | 33        | 3.46%   |
| 5.11    | 31        | 3.25%   |
| 5.19    | 29        | 3.04%   |
| 6.6     | 28        | 2.93%   |
| 5.0     | 26        | 2.72%   |
| 5.16    | 25        | 2.62%   |
| 6.4     | 20        | 2.09%   |
| 4.18    | 17        | 1.78%   |
| 6.10    | 15        | 1.57%   |
| 4.9     | 15        | 1.57%   |
| 6.0     | 14        | 1.47%   |
| 4.19    | 14        | 1.47%   |
| 6.7     | 13        | 1.36%   |
| 6.11    | 12        | 1.26%   |
| 5.9     | 12        | 1.26%   |
| 5.6     | 11        | 1.15%   |
| 5.17    | 11        | 1.15%   |
| 6.9     | 9         | 0.94%   |
| 6.3     | 9         | 0.94%   |
| 6.12    | 9         | 0.94%   |
| 5.14    | 9         | 0.94%   |
| 5.18    | 8         | 0.84%   |
| 5.12    | 8         | 0.84%   |
| 5.7     | 6         | 0.63%   |
| 5.5     | 6         | 0.63%   |
| 4.4     | 4         | 0.42%   |
| 5.1     | 2         | 0.21%   |
| 5.2     | 1         | 0.1%    |
| 4.13    | 1         | 0.1%    |
| 4.1     | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 778       | 96.65%  |
| i686   | 27        | 3.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 341       | 39.61%  |
| KDE5             | 149       | 17.31%  |
| Unknown          | 81        | 9.41%   |
| XFCE             | 79        | 9.18%   |
| X-Cinnamon       | 67        | 7.78%   |
| KDE              | 19        | 2.21%   |
| KDE4             | 18        | 2.09%   |
| KDE6             | 17        | 1.97%   |
| MATE             | 16        | 1.86%   |
| Cinnamon         | 16        | 1.86%   |
| LXQt             | 10        | 1.16%   |
| Pantheon         | 8         | 0.93%   |
| Unity            | 7         | 0.81%   |
| i3               | 6         | 0.7%    |
| Deepin           | 4         | 0.46%   |
| GNOME Flashback  | 3         | 0.35%   |
| GNOME Classic    | 3         | 0.35%   |
| Budgie           | 3         | 0.35%   |
| Sway             | 2         | 0.23%   |
| LXDE             | 2         | 0.23%   |
| lightdm-xsession | 2         | 0.23%   |
| Hyprland         | 2         | 0.23%   |
| xmonad           | 1         | 0.12%   |
| openbox          | 1         | 0.12%   |
| icewm            | 1         | 0.12%   |
| Endless:GNOME    | 1         | 0.12%   |
| COSMIC           | 1         | 0.12%   |
| bspwm            | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 600       | 71.17%  |
| Wayland | 189       | 22.42%  |
| Unknown | 47        | 5.58%   |
| Tty     | 7         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 374       | 43.95%  |
| SDDM    | 140       | 16.45%  |
| GDM3    | 115       | 13.51%  |
| LightDM | 109       | 12.81%  |
| GDM     | 75        | 8.81%   |
| TDM     | 18        | 2.12%   |
| KDM     | 17        | 2%      |
| XDM     | 2         | 0.24%   |
| MDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 537       | 64.54%  |
| bg_BG   | 138       | 16.59%  |
| Unknown | 85        | 10.22%  |
| en_GB   | 25        | 3%      |
| C       | 18        | 2.16%   |
| ru_RU   | 12        | 1.44%   |
| POSIX   | 2         | 0.24%   |
| it_IT   | 2         | 0.24%   |
| es_ES   | 2         | 0.24%   |
| en_DK   | 2         | 0.24%   |
| de_DE   | 2         | 0.24%   |
| uk_UA   | 1         | 0.12%   |
| tr_TR   | 1         | 0.12%   |
| sv_SE   | 1         | 0.12%   |
| fr_FR   | 1         | 0.12%   |
| en_NZ   | 1         | 0.12%   |
| en_AG   | 1         | 0.12%   |
| C.UTF8  | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 425       | 51.27%  |
| EFI  | 404       | 48.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 585       | 70.74%  |
| Btrfs   | 90        | 10.88%  |
| Overlay | 52        | 6.29%   |
| Tmpfs   | 45        | 5.44%   |
| Unknown | 32        | 3.87%   |
| Xfs     | 14        | 1.69%   |
| Zfs     | 4         | 0.48%   |
| Ext2    | 3         | 0.36%   |
| Ext3    | 2         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 394       | 47.3%   |
| GPT     | 335       | 40.22%  |
| MBR     | 104       | 12.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 718       | 87.99%  |
| Yes       | 98        | 12.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 583       | 71.18%  |
| Yes       | 236       | 28.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 231       | 28.77%  |
| Hewlett-Packard     | 144       | 17.93%  |
| Dell                | 122       | 15.19%  |
| ASUSTek Computer    | 98        | 12.2%   |
| Acer                | 83        | 10.34%  |
| Toshiba             | 36        | 4.48%   |
| MSI                 | 18        | 2.24%   |
| Apple               | 10        | 1.25%   |
| Sony                | 6         | 0.75%   |
| Fujitsu             | 6         | 0.75%   |
| Valve               | 5         | 0.62%   |
| Fujitsu Siemens     | 4         | 0.5%    |
| TUXEDO              | 3         | 0.37%   |
| Samsung Electronics | 3         | 0.37%   |
| HUAWEI              | 3         | 0.37%   |
| Gigabyte Technology | 3         | 0.37%   |
| TongFang            | 2         | 0.25%   |
| Packard Bell        | 2         | 0.25%   |
| Notebook            | 2         | 0.25%   |
| Medion              | 2         | 0.25%   |
| Google              | 2         | 0.25%   |
| AMI                 | 2         | 0.25%   |
| Unknown             | 2         | 0.25%   |
| Timi                | 1         | 0.12%   |
| System76            | 1         | 0.12%   |
| SLIMBOOK            | 1         | 0.12%   |
| Razer               | 1         | 0.12%   |
| Pegatron            | 1         | 0.12%   |
| Panasonic           | 1         | 0.12%   |
| ONDA                | 1         | 0.12%   |
| LG Electronics      | 1         | 0.12%   |
| IBM                 | 1         | 0.12%   |
| Cube                | 1         | 0.12%   |
| Compal              | 1         | 0.12%   |
| Beelink             | 1         | 0.12%   |
| Allview             | 1         | 0.12%   |
| Alienware           | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 6         | 0.75%   |
| Valve Jupiter                              | 5         | 0.62%   |
| Lenovo G500 20236                          | 5         | 0.62%   |
| Dell Inspiron N5110                        | 5         | 0.62%   |
| ASUS X541NA                                | 5         | 0.62%   |
| HP ProBook 4540s                           | 4         | 0.5%    |
| HP ProBook 450 G8 Notebook PC              | 4         | 0.5%    |
| HP Pavilion 15                             | 4         | 0.5%    |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA   | 4         | 0.5%    |
| Lenovo Y520-15IKBN 80WK                    | 3         | 0.37%   |
| HP ProBook 450 G0                          | 3         | 0.37%   |
| HP Notebook                                | 3         | 0.37%   |
| HP EliteBook 840 G1                        | 3         | 0.37%   |
| HP 255 G8 Notebook PC                      | 3         | 0.37%   |
| Dell Precision M4600                       | 3         | 0.37%   |
| Dell Latitude E6410                        | 3         | 0.37%   |
| Dell Latitude E4300                        | 3         | 0.37%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.37%   |
| ASUS N551VW                                | 3         | 0.37%   |
| Apple MacBookPro11,1                       | 3         | 0.37%   |
| Acer Aspire 5738                           | 3         | 0.37%   |
| Toshiba Satellite L50-B                    | 2         | 0.25%   |
| Toshiba Satellite L300                     | 2         | 0.25%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.25%   |
| Toshiba Satellite A300                     | 2         | 0.25%   |
| Toshiba Satellite A200                     | 2         | 0.25%   |
| TongFang GX5HRXL                           | 2         | 0.25%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.25%   |
| MSI Modern 15 A5M                          | 2         | 0.25%   |
| MSI GF63 Thin 10SCSR                       | 2         | 0.25%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.25%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.25%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.25%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.25%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.25%   |
| Lenovo ThinkPad T14 Gen 1 20S0000NBM       | 2         | 0.25%   |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.25%   |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.25%   |
| Lenovo ThinkPad E15 Gen 4 21E6006WBM       | 2         | 0.25%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 112       | 13.95%  |
| Acer Aspire           | 58        | 7.22%   |
| Lenovo IdeaPad        | 54        | 6.72%   |
| Dell Latitude         | 45        | 5.6%    |
| HP ProBook            | 34        | 4.23%   |
| Dell Inspiron         | 34        | 4.23%   |
| HP Pavilion           | 30        | 3.74%   |
| Toshiba Satellite     | 29        | 3.61%   |
| HP EliteBook          | 28        | 3.49%   |
| ASUS VivoBook         | 28        | 3.49%   |
| Lenovo Legion         | 16        | 1.99%   |
| Dell Vostro           | 14        | 1.74%   |
| Dell Precision        | 12        | 1.49%   |
| HP Compaq             | 11        | 1.37%   |
| ASUS ROG              | 9         | 1.12%   |
| Lenovo Yoga           | 8         | 1%      |
| Acer Nitro            | 8         | 1%      |
| HP 255                | 7         | 0.87%   |
| MSI Modern            | 6         | 0.75%   |
| Lenovo ThinkBook      | 6         | 0.75%   |
| HP Laptop             | 6         | 0.75%   |
| Dell XPS              | 6         | 0.75%   |
| ASUS ASUS             | 6         | 0.75%   |
| Unknown               | 6         | 0.75%   |
| Valve Jupiter         | 5         | 0.62%   |
| Lenovo G500           | 5         | 0.62%   |
| HP ZBook              | 5         | 0.62%   |
| HP 250                | 5         | 0.62%   |
| ASUS X541NA           | 5         | 0.62%   |
| Acer Predator         | 5         | 0.62%   |
| MSI GF63              | 4         | 0.5%    |
| Lenovo V15            | 4         | 0.5%    |
| ASUS ZenBook          | 4         | 0.5%    |
| Acer Swift            | 4         | 0.5%    |
| Lenovo Y520-15IKBN    | 3         | 0.37%   |
| HP Notebook           | 3         | 0.37%   |
| Fujitsu Siemens AMILO | 3         | 0.37%   |
| Fujitsu LIFEBOOK      | 3         | 0.37%   |
| Dell Studio           | 3         | 0.37%   |
| Dell G15              | 3         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 75        | 9.34%   |
| 2019 | 62        | 7.72%   |
| 2017 | 62        | 7.72%   |
| 2012 | 59        | 7.35%   |
| 2021 | 58        | 7.22%   |
| 2011 | 57        | 7.1%    |
| 2013 | 56        | 6.97%   |
| 2022 | 53        | 6.6%    |
| 2018 | 49        | 6.1%    |
| 2014 | 42        | 5.23%   |
| 2015 | 41        | 5.11%   |
| 2008 | 41        | 5.11%   |
| 2010 | 39        | 4.86%   |
| 2023 | 28        | 3.49%   |
| 2016 | 25        | 3.11%   |
| 2009 | 25        | 3.11%   |
| 2007 | 16        | 1.99%   |
| 2024 | 7         | 0.87%   |
| 2006 | 6         | 0.75%   |
| 2004 | 2         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 803       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 752       | 92.95%  |
| Enabled  | 57        | 7.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 799       | 99.5%   |
| Yes  | 4         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 227       | 27.62%  |
| 8.01-16.0   | 174       | 21.17%  |
| 3.01-4.0    | 154       | 18.73%  |
| 16.01-24.0  | 119       | 14.48%  |
| 32.01-64.0  | 69        | 8.39%   |
| 1.01-2.0    | 23        | 2.8%    |
| 24.01-32.0  | 22        | 2.68%   |
| 2.01-3.0    | 17        | 2.07%   |
| 64.01-256.0 | 13        | 1.58%   |
| 0.51-1.0    | 4         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 259       | 27.82%  |
| 1.01-2.0   | 256       | 27.5%   |
| 4.01-8.0   | 160       | 17.19%  |
| 3.01-4.0   | 142       | 15.25%  |
| 0.51-1.0   | 52        | 5.59%   |
| 8.01-16.0  | 46        | 4.94%   |
| 16.01-24.0 | 10        | 1.07%   |
| 0.01-0.5   | 4         | 0.43%   |
| 32.01-64.0 | 1         | 0.11%   |
| Unknown    | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 609       | 73.91%  |
| 2      | 187       | 22.69%  |
| 3      | 20        | 2.43%   |
| 0      | 7         | 0.85%   |
| 4      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 534       | 65.93%  |
| Yes       | 276       | 34.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 673       | 83.4%   |
| No        | 134       | 16.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 785       | 97.64%  |
| No        | 19        | 2.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 641       | 78.36%  |
| No        | 177       | 21.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Bulgaria | 803       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sofia               | 430       | 50.23%  |
| Varna               | 73        | 8.53%   |
| Plovdiv             | 59        | 6.89%   |
| Burgas              | 44        | 5.14%   |
| Stara Zagora        | 14        | 1.64%   |
| Pleven              | 10        | 1.17%   |
| Pernik              | 10        | 1.17%   |
| Rousse              | 9         | 1.05%   |
| Yambol              | 8         | 0.93%   |
| Veliko Tarnovo      | 8         | 0.93%   |
| Pazardzhik          | 8         | 0.93%   |
| Montana             | 8         | 0.93%   |
| Svilengrad          | 6         | 0.7%    |
| Haskovo             | 6         | 0.7%    |
| Gabrovo             | 6         | 0.7%    |
| Dobrich             | 6         | 0.7%    |
| Blagoevgrad         | 6         | 0.7%    |
| Shumen              | 5         | 0.58%   |
| Razgrad             | 5         | 0.58%   |
| Kazanlak            | 5         | 0.58%   |
| Vidin               | 4         | 0.47%   |
| Sistov              | 4         | 0.47%   |
| Gorna Oryahovitsa   | 4         | 0.47%   |
| Botevgrad           | 4         | 0.47%   |
| Asenovgrad          | 4         | 0.47%   |
| Troyan Municipality | 3         | 0.35%   |
| Smolyan             | 3         | 0.35%   |
| Silistra            | 3         | 0.35%   |
| Nesebar             | 3         | 0.35%   |
| Kyustendil          | 3         | 0.35%   |
| Vratsa              | 2         | 0.23%   |
| Teteven             | 2         | 0.23%   |
| Svoge               | 2         | 0.23%   |
| Sliven              | 2         | 0.23%   |
| Sevlievo            | 2         | 0.23%   |
| Nova Zagora         | 2         | 0.23%   |
| Karlovo             | 2         | 0.23%   |
| Kardzhali           | 2         | 0.23%   |
| Zlatia              | 1         | 0.12%   |
| Vresovo             | 1         | 0.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 161       | 240    | 16.16%  |
| Seagate                     | 106       | 140    | 10.64%  |
| WDC                         | 96        | 130    | 9.64%   |
| Toshiba                     | 81        | 111    | 8.13%   |
| SanDisk                     | 55        | 69     | 5.52%   |
| Kingston                    | 49        | 70     | 4.92%   |
| Unknown                     | 48        | 59     | 4.82%   |
| SK hynix                    | 46        | 63     | 4.62%   |
| Micron Technology           | 37        | 44     | 3.71%   |
| HGST                        | 36        | 52     | 3.61%   |
| Intel                       | 35        | 53     | 3.51%   |
| Hitachi                     | 32        | 34     | 3.21%   |
| A-DATA Technology           | 28        | 37     | 2.81%   |
| KIOXIA                      | 15        | 16     | 1.51%   |
| Crucial                     | 15        | 20     | 1.51%   |
| Transcend                   | 13        | 13     | 1.31%   |
| Kingston Technology Company | 12        | 12     | 1.2%    |
| SPCC                        | 10        | 15     | 1%      |
| Fujitsu                     | 10        | 13     | 1%      |
| Phison Electronics          | 9         | 12     | 0.9%    |
| KingSpec                    | 9         | 10     | 0.9%    |
| China                       | 8         | 10     | 0.8%    |
| Apple                       | 7         | 9      | 0.7%    |
| PNY                         | 6         | 7      | 0.6%    |
| Team                        | 5         | 5      | 0.5%    |
| LITEON                      | 5         | 8      | 0.5%    |
| LITEONIT                    | 4         | 4      | 0.4%    |
| Silicon Motion              | 3         | 3      | 0.3%    |
| Patriot                     | 3         | 3      | 0.3%    |
| Lexar                       | 3         | 3      | 0.3%    |
| Unknown                     | 3         | 3      | 0.3%    |
| Verbatim                    | 2         | 2      | 0.2%    |
| Union Memory (Shenzhen)     | 2         | 2      | 0.2%    |
| TO Exter                    | 2         | 2      | 0.2%    |
| Teclast                     | 2         | 2      | 0.2%    |
| Realtek Semiconductor       | 2         | 3      | 0.2%    |
| Realtek                     | 2         | 2      | 0.2%    |
| Phison                      | 2         | 3      | 0.2%    |
| Lenovo                      | 2         | 2      | 0.2%    |
| Intenso                     | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 19        | 1.83%   |
| HGST HTS721010A9E630 1TB                             | 15        | 1.45%   |
| Toshiba MQ01ABF050 500GB                             | 14        | 1.35%   |
| Toshiba MQ01ABD100 1TB                               | 14        | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 14        | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 12        | 1.16%   |
| Kingston SA400S37240G 240GB SSD                      | 12        | 1.16%   |
| Samsung NVMe SSD Drive 512GB                         | 11        | 1.06%   |
| Unknown MMC Card  32GB                               | 10        | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 10        | 0.96%   |
| Samsung SSD 860 EVO 250GB                            | 9         | 0.87%   |
| Unknown MMC Card  64GB                               | 8         | 0.77%   |
| SanDisk NVMe SSD Drive 512GB                         | 8         | 0.77%   |
| Samsung SSD 860 EVO 500GB                            | 8         | 0.77%   |
| HGST HTS541010A9E680 1TB                             | 8         | 0.77%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 7         | 0.68%   |
| Seagate ST9500325AS 500GB                            | 7         | 0.68%   |
| Kingston SA400S37120G 120GB SSD                      | 7         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB                      | 6         | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB                       | 6         | 0.58%   |
| Samsung SSD 850 EVO 250GB                            | 6         | 0.58%   |
| Toshiba NVMe SSD Drive 256GB                         | 5         | 0.48%   |
| Toshiba MQ04ABF100 1TB                               | 5         | 0.48%   |
| SPCC Solid State Disk 512GB                          | 5         | 0.48%   |
| SanDisk NVMe SSD Drive 256GB                         | 5         | 0.48%   |
| Samsung SSD 870 EVO 500GB                            | 5         | 0.48%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 0.48%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 5         | 0.48%   |
| Kingston Company SNV2S2000G 2TB                      | 5         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 4         | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 4         | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB                          | 4         | 0.39%   |
| Toshiba MQ01ABD075 752GB                             | 4         | 0.39%   |
| SK hynix NVMe SSD Drive 256GB                        | 4         | 0.39%   |
| Seagate ST9750420AS 752GB                            | 4         | 0.39%   |
| Seagate Expansion 1TB                                | 4         | 0.39%   |
| Samsung MZVL4512HBLU-00BTW 512GB                     | 4         | 0.39%   |
| Kingston NVMe SSD Drive 512GB                        | 4         | 0.39%   |
| Intel NVMe SSD Drive 512GB                           | 4         | 0.39%   |
| Hitachi HTS547575A9E384 752GB                        | 4         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 104       | 138    | 32%     |
| WDC                 | 73        | 96     | 22.46%  |
| Toshiba             | 59        | 78     | 18.15%  |
| HGST                | 36        | 52     | 11.08%  |
| Hitachi             | 32        | 34     | 9.85%   |
| Fujitsu             | 10        | 13     | 3.08%   |
| Unknown             | 4         | 6      | 1.23%   |
| Samsung Electronics | 3         | 5      | 0.92%   |
| TO Exter            | 2         | 2      | 0.62%   |
| JMicron Technology  | 1         | 1      | 0.31%   |
| IBM/Hitachi         | 1         | 2      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 68        | 85     | 23.45%  |
| Kingston            | 31        | 36     | 10.69%  |
| SanDisk             | 24        | 29     | 8.28%   |
| A-DATA Technology   | 22        | 31     | 7.59%   |
| WDC                 | 15        | 22     | 5.17%   |
| Crucial             | 12        | 16     | 4.14%   |
| Transcend           | 11        | 11     | 3.79%   |
| SPCC                | 9         | 14     | 3.1%    |
| KingSpec            | 9         | 10     | 3.1%    |
| Micron Technology   | 8         | 10     | 2.76%   |
| Intel               | 8         | 11     | 2.76%   |
| China               | 8         | 10     | 2.76%   |
| Toshiba             | 6         | 7      | 2.07%   |
| PNY                 | 6         | 7      | 2.07%   |
| Team                | 5         | 5      | 1.72%   |
| LITEON              | 5         | 8      | 1.72%   |
| Apple               | 5         | 7      | 1.72%   |
| LITEONIT            | 4         | 4      | 1.38%   |
| SK hynix            | 3         | 3      | 1.03%   |
| Patriot             | 3         | 3      | 1.03%   |
| Lexar               | 3         | 3      | 1.03%   |
| Verbatim            | 2         | 2      | 0.69%   |
| Teclast             | 2         | 2      | 0.69%   |
| Intenso             | 2         | 2      | 0.69%   |
| GOODRAM             | 2         | 2      | 0.69%   |
| AMD                 | 2         | 3      | 0.69%   |
| Unknown             | 2         | 2      | 0.69%   |
| Wibtek              | 1         | 2      | 0.34%   |
| VT                  | 1         | 1      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |
| Seagate             | 1         | 1      | 0.34%   |
| NT-256              | 1         | 1      | 0.34%   |
| Netac               | 1         | 4      | 0.34%   |
| KingDian            | 1         | 1      | 0.34%   |
| Indilinx            | 1         | 2      | 0.34%   |
| FORESEE             | 1         | 2      | 0.34%   |
| EDGE                | 1         | 1      | 0.34%   |
| ASMT                | 1         | 1      | 0.34%   |
| Apacer              | 1         | 1      | 0.34%   |
| ADATA SU            | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 317       | 479    | 33.37%  |
| HDD     | 315       | 427    | 33.16%  |
| SSD     | 273       | 364    | 28.74%  |
| MMC     | 41        | 50     | 4.32%   |
| Unknown | 4         | 3      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 512       | 764    | 57.02%  |
| NVMe | 316       | 477    | 35.19%  |
| MMC  | 41        | 50     | 4.57%   |
| SAS  | 29        | 32     | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 379       | 514    | 66.03%  |
| 0.51-1.0   | 186       | 267    | 32.4%   |
| 1.01-2.0   | 6         | 7      | 1.05%   |
| 3.01-4.0   | 2         | 2      | 0.35%   |
| 10.01-20.0 | 1         | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 227       | 26.71%  |
| 101-250        | 216       | 25.41%  |
| 501-1000       | 149       | 17.53%  |
| 1-20           | 65        | 7.65%   |
| 1001-2000      | 64        | 7.53%   |
| 51-100         | 54        | 6.35%   |
| 21-50          | 38        | 4.47%   |
| Unknown        | 16        | 1.88%   |
| More than 3000 | 13        | 1.53%   |
| 2001-3000      | 8         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 325       | 35.25%  |
| 21-50          | 169       | 18.33%  |
| 101-250        | 137       | 14.86%  |
| 51-100         | 122       | 13.23%  |
| 251-500        | 83        | 9%      |
| 501-1000       | 51        | 5.53%   |
| Unknown        | 16        | 1.74%   |
| 1001-2000      | 12        | 1.3%    |
| 2001-3000      | 4         | 0.43%   |
| More than 3000 | 3         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                            | Notebooks | Drives | Percent |
|------------------------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                                        | 4         | 4      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                               | 3         | 3      | 5.36%   |
| Toshiba MQ01ABF050 500GB                                         | 2         | 2      | 3.57%   |
| Intel SSDSC2CW120A3 120GB                                        | 2         | 2      | 3.57%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                   | 1         | 1      | 1.79%   |
| WDC WD5000LPVX-55V0TT0 500GB                                     | 1         | 1      | 1.79%   |
| WDC WD5000BEVT-75A0RT0 500GB                                     | 1         | 1      | 1.79%   |
| WDC WD3200BEVT-80A0RT0 320GB                                     | 1         | 1      | 1.79%   |
| WDC WD1600BEVT-80A23T0 160GB                                     | 1         | 1      | 1.79%   |
| WDC WD Blue SA510 2.5 500GB                                      | 1         | 1      | 1.79%   |
| Toshiba MQ01ABD100 1TB                                           | 1         | 1      | 1.79%   |
| Toshiba MQ01ABD050 500GB                                         | 1         | 1      | 1.79%   |
| Toshiba MK8052GSX 80GB                                           | 1         | 1      | 1.79%   |
| Toshiba MK2552GSX 250GB                                          | 1         | 3      | 1.79%   |
| Toshiba MK2035GSS 200GB                                          | 1         | 1      | 1.79%   |
| Toshiba MK1637GSX 160GB                                          | 1         | 1      | 1.79%   |
| T-FORCE TM8FPL1000G 1TB                                          | 1         | 1      | 1.79%   |
| SPCC M.2 PCIe SSD 256GB                                          | 1         | 1      | 1.79%   |
| SK hynix HFS256G32TNH-73A0A 256GB SSD                            | 1         | 1      | 1.79%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                             | 1         | 1      | 1.79%   |
| Seagate ST9750423AS 752GB                                        | 1         | 1      | 1.79%   |
| Seagate ST9500420AS 500GB                                        | 1         | 2      | 1.79%   |
| Seagate ST94019A 40GB                                            | 1         | 1      | 1.79%   |
| Seagate ST500LT012-9WS142 500GB                                  | 1         | 1      | 1.79%   |
| Seagate ST500LT012-1DG142 500GB                                  | 1         | 1      | 1.79%   |
| Seagate ST500LM021-1KJ152 500GB                                  | 1         | 1      | 1.79%   |
| Seagate ST500LM000-1EJ162 500GB                                  | 1         | 1      | 1.79%   |
| Seagate ST2000LX001-1RG174 2TB                                   | 1         | 1      | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB                                   | 1         | 1      | 1.79%   |
| Seagate ST1000LM014-1EJ164 1TB                                   | 1         | 1      | 1.79%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 1         | 1      | 1.79%   |
| Phison PSEJN512GA87EC0 512GB                                     | 1         | 1      | 1.79%   |
| KingSpec P3-256 256GB                                            | 1         | 1      | 1.79%   |
| KingSpec P3-128 128GB SSD                                        | 1         | 1      | 1.79%   |
| Hitachi HTS723216L9A360 160GB                                    | 1         | 1      | 1.79%   |
| Hitachi HTS547550A9E384 500GB                                    | 1         | 1      | 1.79%   |
| Hitachi HTS545050A7E380 500GB                                    | 1         | 1      | 1.79%   |
| Hitachi HTS543225L9SA00 250GB                                    | 1         | 2      | 1.79%   |
| Hitachi HTS543225L9A300 250GB                                    | 1         | 1      | 1.79%   |
| Hitachi HTS543216L9SA00 160GB                                    | 1         | 1      | 1.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 30.36%  |
| Toshiba             | 8         | 10     | 14.29%  |
| Hitachi             | 8         | 9      | 14.29%  |
| WDC                 | 6         | 6      | 10.71%  |
| A-DATA Technology   | 3         | 3      | 5.36%   |
| SK hynix            | 2         | 2      | 3.57%   |
| KingSpec            | 2         | 2      | 3.57%   |
| Intel               | 2         | 2      | 3.57%   |
| China               | 2         | 2      | 3.57%   |
| T-FORCE             | 1         | 1      | 1.79%   |
| SPCC                | 1         | 1      | 1.79%   |
| Samsung Electronics | 1         | 1      | 1.79%   |
| Phison              | 1         | 1      | 1.79%   |
| HGST                | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 2      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 18     | 43.59%  |
| Toshiba | 8         | 10     | 20.51%  |
| Hitachi | 8         | 9      | 20.51%  |
| WDC     | 4         | 4      | 10.26%  |
| HGST    | 1         | 1      | 2.56%   |
| Fujitsu | 1         | 2      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 44     | 69.09%  |
| SSD  | 12        | 12     | 21.82%  |
| NVMe | 5         | 5      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 33.33%  |
| Seagate ST9320325AS 320GB    | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 474       | 785    | 55.63%  |
| Works    | 322       | 474    | 37.79%  |
| Malfunc  | 53        | 61     | 6.22%   |
| Failed   | 3         | 3      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 565       | 58.43%  |
| Samsung Electronics              | 100       | 10.34%  |
| AMD                              | 78        | 8.07%   |
| SK hynix                         | 43        | 4.45%   |
| SanDisk                          | 42        | 4.34%   |
| Kingston Technology Company      | 30        | 3.1%    |
| Micron Technology                | 29        | 3%      |
| KIOXIA                           | 17        | 1.76%   |
| Toshiba America Info Systems     | 14        | 1.45%   |
| Phison Electronics               | 13        | 1.34%   |
| Realtek Semiconductor            | 7         | 0.72%   |
| Silicon Motion                   | 4         | 0.41%   |
| Micron/Crucial Technology        | 4         | 0.41%   |
| Union Memory (Shenzhen)          | 3         | 0.31%   |
| ADATA Technology                 | 3         | 0.31%   |
| Transcend                        | 2         | 0.21%   |
| Solid State Storage Technology   | 2         | 0.21%   |
| Marvell Technology Group         | 2         | 0.21%   |
| Lenovo                           | 2         | 0.21%   |
| Apple                            | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.1%    |
| Solidigm                         | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| O2 Micro                         | 1         | 0.1%    |
| Nvidia                           | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 72        | 6.92%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 65        | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 46        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 43        | 4.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 40        | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 36        | 3.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 36        | 3.46%   |
| Intel Volume Management Device NVMe RAID Controller                              | 34        | 3.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 28        | 2.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 26        | 2.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 23        | 2.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 23        | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 23        | 2.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 17        | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 16        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 14        | 1.35%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 14        | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.15%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 11        | 1.06%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 11        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 1.06%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 10        | 0.96%   |
| Intel SSD 660P Series                                                            | 10        | 0.96%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 10        | 0.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 9         | 0.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 8         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 0.77%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 7         | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.58%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 6         | 0.58%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                             | 6         | 0.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 6         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 542       | 54.36%  |
| NVMe | 320       | 32.1%   |
| RAID | 74        | 7.42%   |
| IDE  | 61        | 6.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 651       | 81.07%  |
| AMD          | 151       | 18.8%   |
| CentaurHauls | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 13        | 1.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 12        | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 12        | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 10        | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 10        | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 10        | 1.25%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 10        | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 9         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 9         | 1.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 9         | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 9         | 1.12%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 8         | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz        | 8         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz        | 7         | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 7         | 0.87%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 7         | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 7         | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 7         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 7         | 0.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 7         | 0.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 6         | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 6         | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 6         | 0.75%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 6         | 0.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.75%   |
| Intel 12th Gen Core i5-1235U             | 6         | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 6         | 0.75%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 6         | 0.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.62%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.62%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 5         | 0.62%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 5         | 0.62%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 5         | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 5         | 0.62%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 5         | 0.62%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 5         | 0.62%   |
| Intel Core i3-3110M CPU @ 2.40GHz        | 5         | 0.62%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 5         | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 181       | 22.54%  |
| Intel Core i5           | 164       | 20.42%  |
| Other                   | 84        | 10.46%  |
| Intel Core i3           | 55        | 6.85%   |
| AMD Ryzen 7             | 49        | 6.1%    |
| Intel Core 2 Duo        | 42        | 5.23%   |
| Intel Celeron           | 38        | 4.73%   |
| AMD Ryzen 5             | 35        | 4.36%   |
| Intel Pentium           | 34        | 4.23%   |
| Intel Atom              | 14        | 1.74%   |
| AMD Ryzen 3             | 14        | 1.74%   |
| AMD Ryzen 7 PRO         | 11        | 1.37%   |
| Intel Pentium Silver    | 8         | 1%      |
| Intel Pentium Dual-Core | 7         | 0.87%   |
| Intel Pentium Dual      | 7         | 0.87%   |
| AMD Ryzen 5 PRO         | 6         | 0.75%   |
| Intel Core 2            | 5         | 0.62%   |
| AMD A6                  | 5         | 0.62%   |
| AMD E1                  | 4         | 0.5%    |
| Intel Genuine           | 3         | 0.37%   |
| Intel Core i9           | 3         | 0.37%   |
| AMD E                   | 3         | 0.37%   |
| Intel Pentium M         | 2         | 0.25%   |
| Intel Core              | 2         | 0.25%   |
| Intel Celeron Dual-Core | 2         | 0.25%   |
| AMD Turion 64 X2 Mobile | 2         | 0.25%   |
| AMD Ryzen 9             | 2         | 0.25%   |
| AMD A8                  | 2         | 0.25%   |
| AMD A10                 | 2         | 0.25%   |
| Intel Xeon              | 1         | 0.12%   |
| Intel Mobile Pentium 4  | 1         | 0.12%   |
| Intel Core m3           | 1         | 0.12%   |
| Intel Core M            | 1         | 0.12%   |
| Intel Core Duo          | 1         | 0.12%   |
| Intel Core 2 Solo       | 1         | 0.12%   |
| Intel Celeron M         | 1         | 0.12%   |
| CentaurHauls VIA Nano   | 1         | 0.12%   |
| AMD V120                | 1         | 0.12%   |
| AMD Turion 64 Mobile    | 1         | 0.12%   |
| AMD Sempron             | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 364       | 45.27%  |
| 4       | 249       | 30.97%  |
| 8       | 71        | 8.83%   |
| 6       | 65        | 8.08%   |
| 1       | 19        | 2.36%   |
| 10      | 14        | 1.74%   |
| 14      | 11        | 1.37%   |
| 12      | 6         | 0.75%   |
| 16      | 2         | 0.25%   |
| 24      | 1         | 0.12%   |
| 3       | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 803       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 600       | 74.63%  |
| 1       | 202       | 25.12%  |
| 4       | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 778       | 96.41%  |
| Unknown        | 17        | 2.11%   |
| 32-bit         | 12        | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 331       | 38.85%  |
| 0x306a9    | 48        | 5.63%   |
| 0x206a7    | 45        | 5.28%   |
| 0x1067a    | 25        | 2.93%   |
| 0x806ec    | 23        | 2.7%    |
| 0x306d4    | 23        | 2.7%    |
| 0x306c3    | 20        | 2.35%   |
| 0x40651    | 18        | 2.11%   |
| 0x406e3    | 17        | 2%      |
| 0x20655    | 17        | 2%      |
| 0x906ea    | 16        | 1.88%   |
| 0x806c1    | 16        | 1.88%   |
| 0x806ea    | 15        | 1.76%   |
| 0x6fd      | 13        | 1.53%   |
| 0x906e9    | 12        | 1.41%   |
| 0x0a50000c | 11        | 1.29%   |
| 0x706a1    | 10        | 1.17%   |
| 0x506e3    | 10        | 1.17%   |
| 0x506c9    | 10        | 1.17%   |
| 0x10676    | 10        | 1.17%   |
| 0x08608103 | 10        | 1.17%   |
| 0x0a50000d | 9         | 1.06%   |
| 0x08108109 | 9         | 1.06%   |
| 0x806e9    | 8         | 0.94%   |
| 0xa0652    | 7         | 0.82%   |
| 0x08108102 | 7         | 0.82%   |
| 0x806eb    | 6         | 0.7%    |
| 0x406c3    | 6         | 0.7%    |
| 0x08600106 | 6         | 0.7%    |
| 0x906a4    | 5         | 0.59%   |
| 0x706e5    | 5         | 0.59%   |
| 0x106c2    | 5         | 0.59%   |
| 0x0a404102 | 5         | 0.59%   |
| 0x08600104 | 5         | 0.59%   |
| 0x906a3    | 4         | 0.47%   |
| 0x6f6      | 4         | 0.47%   |
| 0x906ed    | 3         | 0.35%   |
| 0x806d1    | 3         | 0.35%   |
| 0x106e5    | 3         | 0.35%   |
| 0x0a704103 | 3         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 127       | 15.78%  |
| IvyBridge         | 74        | 9.19%   |
| Unknown           | 70        | 8.7%    |
| SandyBridge       | 58        | 7.2%    |
| Haswell           | 58        | 7.2%    |
| Penryn            | 40        | 4.97%   |
| Skylake           | 38        | 4.72%   |
| TigerLake         | 33        | 4.1%    |
| Broadwell         | 30        | 3.73%   |
| Westmere          | 29        | 3.6%    |
| Zen 3             | 28        | 3.48%   |
| Core              | 27        | 3.35%   |
| Alderlake Hybrid  | 26        | 3.23%   |
| Zen+              | 21        | 2.61%   |
| Zen 2             | 21        | 2.61%   |
| Silvermont        | 20        | 2.48%   |
| Goldmont plus     | 16        | 1.99%   |
| Goldmont          | 14        | 1.74%   |
| CometLake         | 13        | 1.61%   |
| Icelake           | 11        | 1.37%   |
| Bonnell           | 7         | 0.87%   |
| Excavator         | 6         | 0.75%   |
| P6                | 5         | 0.62%   |
| Bobcat            | 5         | 0.62%   |
| Nehalem           | 4         | 0.5%    |
| Jaguar            | 4         | 0.5%    |
| Zen               | 3         | 0.37%   |
| K8 Hammer         | 3         | 0.37%   |
| K10               | 3         | 0.37%   |
| Tremont           | 2         | 0.25%   |
| Puma              | 2         | 0.25%   |
| Piledriver        | 2         | 0.25%   |
| Steamroller       | 1         | 0.12%   |
| NetBurst          | 1         | 0.12%   |
| Meteorlake Hybrid | 1         | 0.12%   |
| K8 & K10 hybrid   | 1         | 0.12%   |
| K10 Llano         | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 590       | 55.04%  |
| Nvidia                           | 259       | 24.16%  |
| AMD                              | 221       | 20.62%  |
| VIA Technologies                 | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 6.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 4.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 2.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 2.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 2.54%   |
| Intel HD Graphics 5500                                                                   | 27        | 2.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 2.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 2%      |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 1.91%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 21        | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.91%   |
| Intel UHD Graphics 620                                                                   | 19        | 1.72%   |
| AMD Lucienne                                                                             | 19        | 1.72%   |
| Intel HD Graphics 630                                                                    | 18        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.45%   |
| Intel HD Graphics 620                                                                    | 15        | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.27%   |
| Intel HD Graphics 530                                                                    | 12        | 1.09%   |
| AMD Rembrandt [Radeon 680M]                                                              | 12        | 1.09%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 11        | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1%      |
| AMD Barcelo                                                                              | 11        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.82%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 9         | 0.82%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.73%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.73%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.73%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.73%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 8         | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 345       | 42.65%  |
| Intel + Nvidia | 202       | 24.97%  |
| 1 x AMD        | 144       | 17.8%   |
| Intel + AMD    | 41        | 5.07%   |
| 1 x Nvidia     | 35        | 4.33%   |
| AMD + Nvidia   | 25        | 3.09%   |
| 2 x AMD        | 11        | 1.36%   |
| 2 x Intel      | 3         | 0.37%   |
| Other          | 1         | 0.12%   |
| 1 x VIA        | 1         | 0.12%   |
| 1 x SiS        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 658       | 80.24%  |
| Proprietary | 126       | 15.37%  |
| Unknown     | 36        | 4.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 517       | 61.99%  |
| 1.01-2.0   | 110       | 13.19%  |
| 0.01-0.5   | 89        | 10.67%  |
| 3.01-4.0   | 46        | 5.52%   |
| 0.51-1.0   | 44        | 5.28%   |
| 5.01-6.0   | 16        | 1.92%   |
| 7.01-8.0   | 7         | 0.84%   |
| 8.01-16.0  | 3         | 0.36%   |
| 2.01-3.0   | 2         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 193       | 21.33%  |
| AU Optronics            | 154       | 17.02%  |
| BOE                     | 110       | 12.15%  |
| Chimei Innolux          | 108       | 11.93%  |
| Samsung Electronics     | 72        | 7.96%   |
| Dell                    | 35        | 3.87%   |
| Lenovo                  | 26        | 2.87%   |
| Chi Mei Optoelectronics | 25        | 2.76%   |
| Philips                 | 18        | 1.99%   |
| PANDA                   | 15        | 1.66%   |
| Hewlett-Packard         | 13        | 1.44%   |
| Goldstar                | 13        | 1.44%   |
| LG Philips              | 12        | 1.33%   |
| Sharp                   | 11        | 1.22%   |
| Apple                   | 10        | 1.1%    |
| BenQ                    | 9         | 0.99%   |
| CSO                     | 8         | 0.88%   |
| Acer                    | 8         | 0.88%   |
| AOC                     | 7         | 0.77%   |
| Vestel Elektronik       | 5         | 0.55%   |
| Valve                   | 4         | 0.44%   |
| CPT                     | 4         | 0.44%   |
| Ancor Communications    | 4         | 0.44%   |
| Toshiba                 | 3         | 0.33%   |
| Sony                    | 3         | 0.33%   |
| InfoVision              | 3         | 0.33%   |
| TMX                     | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| MSI                     | 2         | 0.22%   |
| InnoLux Display         | 2         | 0.22%   |
| Iiyama                  | 2         | 0.22%   |
| HannStar                | 2         | 0.22%   |
| BOE Technology Group    | 2         | 0.22%   |
| ASUSTek Computer        | 2         | 0.22%   |
| ViewSonic               | 1         | 0.11%   |
| Seiko/Epson             | 1         | 0.11%   |
| NEC Computers           | 1         | 0.11%   |
| MPI                     | 1         | 0.11%   |
| LGD                     | 1         | 0.11%   |
| KDC                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 13        | 1.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 1.1%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 1.1%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.88%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.88%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.88%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.66%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 5         | 0.55%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 5         | 0.55%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.55%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.55%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 0.44%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 4         | 0.44%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 4         | 0.44%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.44%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 3         | 0.33%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.33%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.33%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.33%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 3         | 0.33%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 3         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 396       | 46.92%  |
| 1366x768 (WXGA)    | 210       | 24.88%  |
| 1600x900 (HD+)     | 38        | 4.5%    |
| 1280x800 (WXGA)    | 38        | 4.5%    |
| 3840x2160 (4K)     | 27        | 3.2%    |
| 1920x1200 (WUXGA)  | 26        | 3.08%   |
| 2560x1600          | 19        | 2.25%   |
| 2560x1440 (QHD)    | 18        | 2.13%   |
| 1680x1050 (WSXGA+) | 13        | 1.54%   |
| 1440x900 (WXGA+)   | 8         | 0.95%   |
| 1280x1024 (SXGA)   | 8         | 0.95%   |
| 1024x600           | 6         | 0.71%   |
| 800x1280           | 5         | 0.59%   |
| 3840x2400          | 4         | 0.47%   |
| 3440x1440          | 4         | 0.47%   |
| 2880x1800          | 4         | 0.47%   |
| 2560x1080          | 4         | 0.47%   |
| 3072x1920          | 2         | 0.24%   |
| 800x480            | 1         | 0.12%   |
| 3840x1080          | 1         | 0.12%   |
| 3456x2160          | 1         | 0.12%   |
| 3200x2000          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2256x1504          | 1         | 0.12%   |
| 2160x1440          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |
| 1600x1200          | 1         | 0.12%   |
| 1280x960           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |
| Unknown            | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 444       | 49.12%  |
| 14      | 86        | 9.51%   |
| 13      | 75        | 8.3%    |
| 17      | 55        | 6.08%   |
| 24      | 39        | 4.31%   |
| 12      | 33        | 3.65%   |
| 16      | 27        | 2.99%   |
| 23      | 23        | 2.54%   |
| 27      | 21        | 2.32%   |
| 21      | 19        | 2.1%    |
| 11      | 8         | 0.88%   |
| 34      | 7         | 0.77%   |
| 19      | 7         | 0.77%   |
| 84      | 6         | 0.66%   |
| 18      | 6         | 0.66%   |
| 10      | 6         | 0.66%   |
| 31      | 5         | 0.55%   |
| 22      | 5         | 0.55%   |
| 54      | 4         | 0.44%   |
| 7       | 4         | 0.44%   |
| Unknown | 4         | 0.44%   |
| 32      | 3         | 0.33%   |
| 20      | 3         | 0.33%   |
| 72      | 2         | 0.22%   |
| 65      | 2         | 0.22%   |
| 40      | 2         | 0.22%   |
| 33      | 2         | 0.22%   |
| 28      | 2         | 0.22%   |
| 35      | 1         | 0.11%   |
| 25      | 1         | 0.11%   |
| 8       | 1         | 0.11%   |
| 3       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 587       | 65.29%  |
| 201-300     | 85        | 9.45%   |
| 501-600     | 75        | 8.34%   |
| 351-400     | 68        | 7.56%   |
| 401-500     | 35        | 3.89%   |
| 701-800     | 12        | 1.33%   |
| 601-700     | 10        | 1.11%   |
| 1501-2000   | 8         | 0.89%   |
| 1001-1500   | 6         | 0.67%   |
| 1-100       | 5         | 0.56%   |
| Unknown     | 4         | 0.44%   |
| 801-900     | 3         | 0.33%   |
| 101-200     | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 649       | 81.13%  |
| 16/10   | 117       | 14.63%  |
| 5/4     | 9         | 1.13%   |
| 21/9    | 8         | 1%      |
| 3/2     | 5         | 0.63%   |
| 0.67    | 4         | 0.5%    |
| Unknown | 4         | 0.5%    |
| 4/3     | 2         | 0.25%   |
| 6/5     | 1         | 0.13%   |
| 1.00    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 442       | 49.28%  |
| 81-90          | 129       | 14.38%  |
| 201-250        | 63        | 7.02%   |
| 121-130        | 46        | 5.13%   |
| 61-70          | 33        | 3.68%   |
| 71-80          | 30        | 3.34%   |
| 111-120        | 26        | 2.9%    |
| 301-350        | 21        | 2.34%   |
| 351-500        | 19        | 2.12%   |
| 151-200        | 18        | 2.01%   |
| More than 1000 | 13        | 1.45%   |
| 251-300        | 13        | 1.45%   |
| 51-60          | 8         | 0.89%   |
| 141-150        | 8         | 0.89%   |
| 131-140        | 8         | 0.89%   |
| 41-50          | 6         | 0.67%   |
| 1-40           | 6         | 0.67%   |
| Unknown        | 4         | 0.45%   |
| 501-1000       | 2         | 0.22%   |
| 91-100         | 2         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 401       | 45.41%  |
| 101-120       | 227       | 25.71%  |
| 51-100        | 159       | 18.01%  |
| 161-240       | 63        | 7.13%   |
| More than 240 | 22        | 2.49%   |
| 1-50          | 7         | 0.79%   |
| Unknown       | 4         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 662       | 79.66%  |
| 2     | 124       | 14.92%  |
| 0     | 28        | 3.37%   |
| 3     | 17        | 2.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 437       | 32.81%  |
| Realtek Semiconductor                  | 428       | 32.13%  |
| Qualcomm Atheros                       | 159       | 11.94%  |
| Broadcom                               | 72        | 5.41%   |
| MediaTek                               | 47        | 3.53%   |
| Broadcom Limited                       | 29        | 2.18%   |
| Ralink                                 | 24        | 1.8%    |
| TP-Link                                | 21        | 1.58%   |
| Ericsson Business Mobile Networks      | 15        | 1.13%   |
| Sierra Wireless                        | 13        | 0.98%   |
| Marvell Technology Group               | 12        | 0.9%    |
| Dell                                   | 9         | 0.68%   |
| Ralink Technology                      | 6         | 0.45%   |
| Qualcomm Atheros Communications        | 5         | 0.38%   |
| Lenovo                                 | 5         | 0.38%   |
| Hewlett-Packard                        | 5         | 0.38%   |
| Motorola PCS                           | 4         | 0.3%    |
| DisplayLink                            | 4         | 0.3%    |
| Xiaomi                                 | 3         | 0.23%   |
| Qualcomm                               | 3         | 0.23%   |
| Huawei Technologies                    | 3         | 0.23%   |
| D-Link                                 | 3         | 0.23%   |
| ASIX Electronics                       | 3         | 0.23%   |
| AMD                                    | 3         | 0.23%   |
| Toshiba                                | 2         | 0.15%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.15%   |
| Samsung Electronics                    | 2         | 0.15%   |
| Google                                 | 2         | 0.15%   |
| Davicom Semiconductor                  | 2         | 0.15%   |
| Quectel Wireless Solutions             | 1         | 0.08%   |
| Nvidia                                 | 1         | 0.08%   |
| NetGear                                | 1         | 0.08%   |
| Micro Star International               | 1         | 0.08%   |
| JMicron Technology                     | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Fibocom                                | 1         | 0.08%   |
| Attansic Technology                    | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 263       | 16.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 77        | 4.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 35        | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 33        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 33        | 2.06%   |
| Intel Wireless 8265 / 8275                                             | 33        | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 27        | 1.69%   |
| Intel Wi-Fi 6 AX201                                                    | 27        | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 25        | 1.56%   |
| Intel Wireless 7260                                                    | 25        | 1.56%   |
| Intel Wireless 7265                                                    | 24        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 23        | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 22        | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 22        | 1.38%   |
| Intel Wi-Fi 6 AX200                                                    | 21        | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 20        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.13%   |
| Intel Wireless 8260                                                    | 17        | 1.06%   |
| Intel Wireless 3160                                                    | 16        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 15        | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                          | 15        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 14        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 13        | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.81%   |
| Intel WiFi Link 5100                                                   | 13        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 12        | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 0.75%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 11        | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 11        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.69%   |
| Intel Centrino Ultimate-N 6300                                         | 11        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 11        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 10        | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 416       | 49.23%  |
| Qualcomm Atheros                | 133       | 15.74%  |
| Realtek Semiconductor           | 112       | 13.25%  |
| Broadcom                        | 55        | 6.51%   |
| MediaTek                        | 40        | 4.73%   |
| Ralink                          | 24        | 2.84%   |
| TP-Link                         | 16        | 1.89%   |
| Sierra Wireless                 | 13        | 1.54%   |
| Broadcom Limited                | 11        | 1.3%    |
| Ralink Technology               | 6         | 0.71%   |
| Dell                            | 6         | 0.71%   |
| Qualcomm Atheros Communications | 5         | 0.59%   |
| Qualcomm                        | 3         | 0.36%   |
| NetGear                         | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Fibocom                         | 1         | 0.12%   |
| D-Link                          | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 4.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 33        | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 33        | 3.88%   |
| Intel Wireless 8265 / 8275                                     | 33        | 3.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 3.18%   |
| Intel Wi-Fi 6 AX201                                            | 27        | 3.18%   |
| Intel Wireless 7260                                            | 25        | 2.94%   |
| Intel Wireless 7265                                            | 24        | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 23        | 2.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 22        | 2.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 2.59%   |
| Intel Wi-Fi 6 AX200                                            | 21        | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 2.12%   |
| Intel Wireless 8260                                            | 17        | 2%      |
| Intel Wireless 3160                                            | 16        | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 1.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 1.53%   |
| Intel WiFi Link 5100                                           | 13        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 1.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 12        | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.29%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 11        | 1.29%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.29%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 10        | 1.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 9         | 1.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 9         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 0.82%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 7         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 0.82%   |
| Intel Centrino Wireless-N 2230                                 | 7         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 378       | 53.54%  |
| Intel                                  | 183       | 25.92%  |
| Qualcomm Atheros                       | 44        | 6.23%   |
| Broadcom                               | 25        | 3.54%   |
| Broadcom Limited                       | 18        | 2.55%   |
| Marvell Technology Group               | 12        | 1.7%    |
| MediaTek                               | 8         | 1.13%   |
| TP-Link                                | 5         | 0.71%   |
| Motorola PCS                           | 4         | 0.57%   |
| Lenovo                                 | 4         | 0.57%   |
| DisplayLink                            | 4         | 0.57%   |
| Xiaomi                                 | 3         | 0.42%   |
| ASIX Electronics                       | 3         | 0.42%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.28%   |
| Huawei Technologies                    | 2         | 0.28%   |
| Davicom Semiconductor                  | 2         | 0.28%   |
| D-Link                                 | 2         | 0.28%   |
| Samsung Electronics                    | 1         | 0.14%   |
| Nvidia                                 | 1         | 0.14%   |
| JMicron Technology                     | 1         | 0.14%   |
| ICS Advent                             | 1         | 0.14%   |
| Google                                 | 1         | 0.14%   |
| Attansic Technology                    | 1         | 0.14%   |
| Apple                                  | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 263       | 36.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 77        | 10.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 5.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 25        | 3.49%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 1.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 1.54%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 1.54%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 1.4%    |
| Intel Ethernet Connection I218-LM                                      | 10        | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.26%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 1.12%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 8         | 1.12%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.84%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 5         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.7%    |
| Intel Ethernet Connection (16) I219-V                                  | 5         | 0.7%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 5         | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 5         | 0.7%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 4         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.42%   |
| Motorola PCS moto g84 5G                                               | 3         | 0.42%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 3         | 0.42%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 3         | 0.42%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.42%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 785       | 52.65%  |
| Ethernet | 672       | 45.07%  |
| Modem    | 34        | 2.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 665       | 76.97%  |
| Ethernet | 199       | 23.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 629       | 78.23%  |
| 1     | 161       | 20.02%  |
| 3     | 7         | 0.87%   |
| 0     | 7         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 771       | 94.14%  |
| Yes  | 48        | 5.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 289       | 44.33%  |
| Realtek Semiconductor           | 60        | 9.2%    |
| Qualcomm Atheros Communications | 48        | 7.36%   |
| IMC Networks                    | 46        | 7.06%   |
| Broadcom                        | 40        | 6.13%   |
| Foxconn / Hon Hai               | 35        | 5.37%   |
| Lite-On Technology              | 31        | 4.75%   |
| Hewlett-Packard                 | 18        | 2.76%   |
| Toshiba                         | 17        | 2.61%   |
| Dell                            | 15        | 2.3%    |
| Ralink                          | 12        | 1.84%   |
| Cambridge Silicon Radio         | 11        | 1.69%   |
| Apple                           | 8         | 1.23%   |
| Foxconn International           | 6         | 0.92%   |
| MediaTek                        | 4         | 0.61%   |
| USI                             | 2         | 0.31%   |
| TP-Link                         | 2         | 0.31%   |
| Realtek                         | 2         | 0.31%   |
| Ralink Technology               | 2         | 0.31%   |
| ASUSTek Computer                | 2         | 0.31%   |
| Belkin Components               | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 111       | 17.02%  |
| Intel AX201 Bluetooth                               | 67        | 10.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 49        | 7.52%   |
| Realtek Bluetooth Radio                             | 38        | 5.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 4.29%   |
| IMC Networks Bluetooth Radio                        | 19        | 2.91%   |
| Intel AX200 Bluetooth                               | 18        | 2.76%   |
| IMC Networks Wireless_Device                        | 17        | 2.61%   |
| Ralink RT3290 Bluetooth                             | 12        | 1.84%   |
| Intel AX211 Bluetooth                               | 12        | 1.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 1.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 11        | 1.69%   |
| Realtek 802.11ac WLAN Adapter                       | 10        | 1.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 1.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 1.53%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1.38%   |
| Lite-On Bluetooth Device                            | 9         | 1.38%   |
| IMC Networks Bluetooth Device                       | 9         | 1.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.23%   |
| Toshiba Integrated Bluetooth HCI                    | 7         | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 1.07%   |
| Lite-On Wireless_Device                             | 6         | 0.92%   |
| Intel AX210 Bluetooth                               | 6         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 0.92%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.61%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.61%   |
| Apple Bluetooth Host Controller                     | 4         | 0.61%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.46%   |
| Toshiba Bluetooth Device                            | 3         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 638       | 63.67%  |
| AMD                              | 177       | 17.66%  |
| Nvidia                           | 133       | 13.27%  |
| Lenovo                           | 7         | 0.7%    |
| Razer USA                        | 6         | 0.6%    |
| C-Media Electronics              | 6         | 0.6%    |
| Logitech                         | 4         | 0.4%    |
| JMTek                            | 4         | 0.4%    |
| GN Netcom                        | 4         | 0.4%    |
| Realtek Semiconductor            | 3         | 0.3%    |
| Plantronics                      | 3         | 0.3%    |
| Creative Technology              | 3         | 0.3%    |
| Apple                            | 2         | 0.2%    |
| ZOOM                             | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| Trust                            | 1         | 0.1%    |
| Sony                             | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| No brand                         | 1         | 0.1%    |
| Native Instruments               | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| GYROCOM C&C                      | 1         | 0.1%    |
| Generalplus Technology           | 1         | 0.1%    |
| ASUSTek Computer                 | 1         | 0.1%    |
| A4Tech                           | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 117       | 9.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 82        | 6.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 61        | 5%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 58        | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 50        | 4.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 45        | 3.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 33        | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 32        | 2.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 2.46%   |
| Intel Broadwell-U Audio Controller                                         | 30        | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 29        | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29        | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 29        | 2.38%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 2.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 26        | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 23        | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 1.89%   |
| Intel CM238 HD Audio Controller                                            | 18        | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 17        | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 1.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 16        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 14        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 0.9%    |
| AMD FCH Azalia Controller                                                  | 11        | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.66%   |
| Nvidia GA107 High Definition Audio Controller                              | 8         | 0.66%   |
| Nvidia AD107 High Definition Audio Controller                              | 8         | 0.66%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.66%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 8         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 143       | 25.72%  |
| SK hynix                                | 120       | 21.58%  |
| Micron Technology                       | 75        | 13.49%  |
| Kingston                                | 64        | 11.51%  |
| Unknown                                 | 30        | 5.4%    |
| A-DATA Technology                       | 22        | 3.96%   |
| Ramaxel Technology                      | 21        | 3.78%   |
| Crucial                                 | 12        | 2.16%   |
| Transcend                               | 11        | 1.98%   |
| Nanya Technology                        | 11        | 1.98%   |
| Elpida                                  | 9         | 1.62%   |
| Corsair                                 | 9         | 1.62%   |
| Apacer                                  | 8         | 1.44%   |
| Team                                    | 6         | 1.08%   |
| Silicon Power Computer & Communications | 3         | 0.54%   |
| ASint Technology                        | 2         | 0.36%   |
| Unknown                                 | 2         | 0.36%   |
| Unknown (ABCD)                          | 1         | 0.18%   |
| Unifosa                                 | 1         | 0.18%   |
| Silicon Power                           | 1         | 0.18%   |
| Qimonda                                 | 1         | 0.18%   |
| Neo Forza                               | 1         | 0.18%   |
| GOODRAM                                 | 1         | 0.18%   |
| fef5                                    | 1         | 0.18%   |
| A Force                                 | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 11        | 1.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 9         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s        | 9         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 7         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 6         | 1.02%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 6         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 6         | 1.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 1.02%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                  | 6         | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 5         | 0.85%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 5         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 5         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 5         | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 5         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 4         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s       | 4         | 0.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 0.68%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 4         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 4         | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.68%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s     | 4         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 3         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 3         | 0.51%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 3         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 3         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 0.51%   |
| Silicon Power & RAM Module 16GB SODIMM DDR4 3200MT/s        | 3         | 0.51%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 3         | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 3         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 3         | 0.51%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 3         | 0.51%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s        | 3         | 0.51%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 3         | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 3         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 205       | 46.28%  |
| DDR3    | 156       | 35.21%  |
| DDR5    | 19        | 4.29%   |
| DDR2    | 14        | 3.16%   |
| SDRAM   | 11        | 2.48%   |
| LPDDR5  | 11        | 2.48%   |
| LPDDR4  | 10        | 2.26%   |
| Unknown | 5         | 1.13%   |
| LPDDR3  | 4         | 0.9%    |
| DRAM    | 4         | 0.9%    |
| DDR     | 4         | 0.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 408       | 93.36%  |
| Row Of Chips | 21        | 4.81%   |
| Chip         | 4         | 0.92%   |
| DIMM         | 3         | 0.69%   |
| Unknown      | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 187       | 38.09%  |
| 4096    | 124       | 25.25%  |
| 16384   | 85        | 17.31%  |
| 2048    | 49        | 9.98%   |
| 32768   | 27        | 5.5%    |
| 1024    | 17        | 3.46%   |
| 512     | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 109       | 22.57%  |
| 1600    | 102       | 21.12%  |
| 2667    | 85        | 17.6%   |
| 1334    | 33        | 6.83%   |
| 2400    | 28        | 5.8%    |
| 1333    | 17        | 3.52%   |
| 667     | 12        | 2.48%   |
| Unknown | 12        | 2.48%   |
| 5600    | 10        | 2.07%   |
| 4800    | 9         | 1.86%   |
| 2133    | 9         | 1.86%   |
| 1067    | 8         | 1.66%   |
| 6400    | 7         | 1.45%   |
| 3266    | 6         | 1.24%   |
| 1066    | 6         | 1.24%   |
| 4199    | 5         | 1.04%   |
| 2048    | 5         | 1.04%   |
| 7500    | 3         | 0.62%   |
| 4266    | 3         | 0.62%   |
| 1867    | 3         | 0.62%   |
| 800     | 3         | 0.62%   |
| 4267    | 2         | 0.41%   |
| 975     | 2         | 0.41%   |
| 7467    | 1         | 0.21%   |
| 2933    | 1         | 0.21%   |
| 1866    | 1         | 0.21%   |
| 533     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 2         | 25%     |
| Samsung Electronics | 2         | 25%     |
| Canon               | 2         | 25%     |
| STMicroelectronics  | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 12.5%   |
| Seiko Epson L3150 Series                                  | 1         | 12.5%   |
| Seiko Epson ET-2820 Series                                | 1         | 12.5%   |
| Samsung M332x 382x 402x Series                            | 1         | 12.5%   |
| Samsung M267x 287x Series                                 | 1         | 12.5%   |
| Canon PIXMA MP240                                         | 1         | 12.5%   |
| Canon MF3200 series                                       | 1         | 12.5%   |
| Brother DCP-7055 scanner/printer                          | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Mustek Systems  | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22 | 1         | 50%     |
| HP ScanJet 3400cse          | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 181       | 25.39%  |
| IMC Networks                           | 87        | 12.2%   |
| Bison Electronics                      | 59        | 8.27%   |
| Microdia                               | 57        | 7.99%   |
| Realtek Semiconductor                  | 55        | 7.71%   |
| Quanta                                 | 50        | 7.01%   |
| Sunplus Innovation Technology          | 41        | 5.75%   |
| Syntek                                 | 22        | 3.09%   |
| Suyin                                  | 20        | 2.81%   |
| Luxvisions Innotech Limited            | 20        | 2.81%   |
| Lite-On Technology                     | 20        | 2.81%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 2.52%   |
| Logitech                               | 12        | 1.68%   |
| Acer                                   | 11        | 1.54%   |
| Alcor Micro                            | 8         | 1.12%   |
| Apple                                  | 7         | 0.98%   |
| Sonix Technology                       | 6         | 0.84%   |
| Lenovo                                 | 5         | 0.7%    |
| Silicon Motion                         | 4         | 0.56%   |
| Samsung Electronics                    | 3         | 0.42%   |
| Ricoh                                  | 3         | 0.42%   |
| Z-Star Microelectronics                | 2         | 0.28%   |
| ShineTech                              | 2         | 0.28%   |
| Primax Electronics                     | 2         | 0.28%   |
| kingcome                               | 2         | 0.28%   |
| Importek                               | 2         | 0.28%   |
| Alpha Imaging Technology               | 2         | 0.28%   |
| ALi                                    | 2         | 0.28%   |
| Xiongmai                               | 1         | 0.14%   |
| Tobii Technology AB                    | 1         | 0.14%   |
| Sunplus Technology                     | 1         | 0.14%   |
| OmniVision Technologies                | 1         | 0.14%   |
| Microsoft                              | 1         | 0.14%   |
| Hewlett-Packard                        | 1         | 0.14%   |
| Creative Technology                    | 1         | 0.14%   |
| Aveo Technology                        | 1         | 0.14%   |
| Arkmicro Technologies                  | 1         | 0.14%   |
| Unknown                                | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 41        | 5.75%   |
| IMC Networks Integrated Camera                       | 29        | 4.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 24        | 3.37%   |
| Microdia Integrated_Webcam_HD                        | 20        | 2.81%   |
| Bison Integrated Camera                              | 18        | 2.52%   |
| Syntek Integrated Camera                             | 15        | 2.1%    |
| Sunplus Integrated_Webcam_HD                         | 15        | 2.1%    |
| Realtek Integrated_Webcam_HD                         | 15        | 2.1%    |
| Chicony HD Webcam                                    | 15        | 2.1%    |
| Quanta HP HD Camera                                  | 13        | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 13        | 1.82%   |
| Chicony TOSHIBA Web Camera - HD                      | 10        | 1.4%    |
| Bison SunplusIT Integrated Camera                    | 9         | 1.26%   |
| Bison HD Webcam                                      | 9         | 1.26%   |
| Realtek Lenovo EasyCamera                            | 8         | 1.12%   |
| Lite-On Integrated Camera                            | 8         | 1.12%   |
| Quanta HD User Facing                                | 7         | 0.98%   |
| Quanta ACER HD User Facing                           | 7         | 0.98%   |
| Microdia Integrated Webcam                           | 7         | 0.98%   |
| Chicony USB 2.0 Camera                               | 7         | 0.98%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 6         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 6         | 0.84%   |
| Bison Lenovo EasyCamera                              | 6         | 0.84%   |
| Quanta HD Webcam                                     | 5         | 0.7%    |
| Lite-On HP HD Webcam                                 | 5         | 0.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)             | 5         | 0.7%    |
| Chicony Lenovo EasyCamera                            | 5         | 0.7%    |
| Chicony Integrated Camera [ThinkPad]                 | 5         | 0.7%    |
| Chicony HP HD Webcam                                 | 5         | 0.7%    |
| Chicony HP HD Camera                                 | 5         | 0.7%    |
| Chicony HD WebCam (Asus N-series)                    | 5         | 0.7%    |
| Chicony HD User Facing                               | 5         | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 4         | 0.56%   |
| Sunplus Laptop Integrated Webcam HD                  | 4         | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.56%   |
| Realtek HD WebCam                                    | 4         | 0.56%   |
| Quanta VGA WebCam                                    | 4         | 0.56%   |
| Quanta HP TrueVision HD Camera                       | 4         | 0.56%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 4         | 0.56%   |
| Logitech Webcam C270                                 | 4         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 46        | 35.94%  |
| Synaptics                          | 41        | 32.03%  |
| AuthenTec                          | 15        | 11.72%  |
| Shenzhen Goodix Technology         | 8         | 6.25%   |
| Upek                               | 6         | 4.69%   |
| Elan Microelectronics              | 6         | 4.69%   |
| LighTuning Technology              | 4         | 3.13%   |
| STMicroelectronics                 | 1         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 14.06%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 9.38%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 6.25%   |
| AuthenTec AES2810                                                          | 8         | 6.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 5.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 3.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.13%   |
| Elan ELAN:ARM-M4                                                           | 4         | 3.13%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.56%   |
| Validity Sensors VFS491                                                    | 2         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.56%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.56%   |
| Synaptics WBDI                                                             | 2         | 1.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.56%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 1.56%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.78%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.78%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.78%   |
| Synaptics TouchPad                                                         | 1         | 0.78%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.78%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.78%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 0.78%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.78%   |
| AuthenTec AES1600                                                          | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 34        | 36.17%  |
| Alcor Micro           | 34        | 36.17%  |
| Upek                  | 9         | 9.57%   |
| O2 Micro              | 6         | 6.38%   |
| Lenovo                | 5         | 5.32%   |
| Advanced Card Systems | 3         | 3.19%   |
| SCM Microsystems      | 2         | 2.13%   |
| Clay Logic            | 1         | 1.06%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 35.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 13.68%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 9.47%   |
| Broadcom 5880                                                                | 8         | 8.42%   |
| Broadcom 58200                                                               | 8         | 8.42%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 6.32%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 5.26%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.11%   |
| Advanced Card Systems ACR39U                                                 | 2         | 2.11%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.05%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.05%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.05%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 490       | 57.85%  |
| 1     | 273       | 32.23%  |
| 2     | 78        | 9.21%   |
| 3     | 5         | 0.59%   |
| 7     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 128       | 30.4%   |
| Graphics card            | 95        | 22.57%  |
| Chipcard                 | 78        | 18.53%  |
| Net/wireless             | 36        | 8.55%   |
| Multimedia controller    | 20        | 4.75%   |
| Bluetooth                | 20        | 4.75%   |
| Camera                   | 12        | 2.85%   |
| Storage                  | 9         | 2.14%   |
| Communication controller | 6         | 1.43%   |
| Card reader              | 4         | 0.95%   |
| Sound                    | 3         | 0.71%   |
| Net/ethernet             | 3         | 0.71%   |
| Network                  | 2         | 0.48%   |
| Modem                    | 2         | 0.48%   |
| Firewire controller      | 2         | 0.48%   |
| Flash memory             | 1         | 0.24%   |


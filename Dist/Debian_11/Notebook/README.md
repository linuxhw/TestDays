Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 4605

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| Dell          | Inspiron 15 3511            | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| HP            | Lantis                      | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Packard Be... | H17HV                       | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Apple         | MacBookPro5,5               | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Apple         | MacBookPro5,5               | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Dell          | Inspiron 15 3511            | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Dell          | Latitude E7250              | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| ASUSTek       | K72Jr                       | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| HP            | EliteBook 8570p             | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| Dell          | Latitude E6440              | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| Dell          | Inspiron 15 3511            | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Positivo      | Mobile                      | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK E780               | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| HP            | EliteBook 1040 G4           | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Dell          | Inspiron 15-3565            | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| NEC Comput... | PC-VK27MBZCG                | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| HP            | EliteBook 840 G3            | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| Fujitsu       | LIFEBOOK E780               | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| HUAWEI        | BOM-WXX9                    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| Apple         | MacBookAir7,2               | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Dell          | Latitude 7370               | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| ASUSTek       | K53SJ                       | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| HP            | Laptop 14-dq0xxx            | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Lenovo        | Edge 15 80H1                | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Dell          | Inspiron 1525               | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Dell          | Precision M2800             | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Dell          | Latitude D620               | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Medion        | E6214                       | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Dell          | Latitude 5480               | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Fujitsu       | LIFEBOOK E780               | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Dell          | Inspiron 1521               | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| HP            | Pavilion 17                 | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Dell          | Latitude E6430              | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Dell          | Latitude 5411               | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Lenovo        | Edge 15 80H1                | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | Inspiron 3451               | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| Dell          | Latitude E7450              | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Acer          | Aspire 7745G                | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Dell          | Latitude 7410               | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| AMI           | Intel                       | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Apple         | MacBook10,1                 | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Acer          | TravelMate P215-53          | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| Dell          | Latitude 5414               | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Google        | Terra                       | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| Dell          | Precision 3550              | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Notebook                    | [7614984f1d](https://linux-hardware.org/?probe=7614984f1d) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| Acer          | Extensa 5635Z               | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Acer          | AO756                       | [58efd2f87f](https://linux-hardware.org/?probe=58efd2f87f) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| Dell          | Inspiron 15 5510            | [5d84a5a711](https://linux-hardware.org/?probe=5d84a5a711) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [ea4fdd80e6](https://linux-hardware.org/?probe=ea4fdd80e6) | Apr 09, 2023 |
| ASUSTek       | X756UQ                      | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ENVY dv6                    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [3063414a8c](https://linux-hardware.org/?probe=3063414a8c) | Apr 08, 2023 |
| Lenovo        | ThinkPad T450 20BUA05900    | [e771177cca](https://linux-hardware.org/?probe=e771177cca) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [6d50e55675](https://linux-hardware.org/?probe=6d50e55675) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| Google        | Reks                        | [25341f2040](https://linux-hardware.org/?probe=25341f2040) | Apr 07, 2023 |
| Google        | Reks                        | [21c7e0c282](https://linux-hardware.org/?probe=21c7e0c282) | Apr 07, 2023 |
| Google        | Terra                       | [09a6a1ca8f](https://linux-hardware.org/?probe=09a6a1ca8f) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [a74c66fc15](https://linux-hardware.org/?probe=a74c66fc15) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [46990342e8](https://linux-hardware.org/?probe=46990342e8) | Apr 06, 2023 |
| Acer          | TravelMate 5735Z            | [6d0065dea2](https://linux-hardware.org/?probe=6d0065dea2) | Apr 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| Dell          | Latitude E7250              | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| Toshiba       | Satellite C855D-12J         | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| Acer          | Aspire E1-532               | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Dell          | Precision M4700             | [1e2be52d80](https://linux-hardware.org/?probe=1e2be52d80) | Apr 05, 2023 |
| Acer          | TravelMate P215-53          | [0808bd0d17](https://linux-hardware.org/?probe=0808bd0d17) | Apr 04, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| HP            | EliteBook 840 G3            | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| Lenovo        | ThinkPad T530 242962G       | [58d0ea734d](https://linux-hardware.org/?probe=58d0ea734d) | Apr 03, 2023 |
| Toshiba       | Satellite Pro C850-1K0      | [893534249a](https://linux-hardware.org/?probe=893534249a) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0f4881cccf](https://linux-hardware.org/?probe=0f4881cccf) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Clevo         | P170HMx                     | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| Apple         | MacBookAir6,1               | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Acer          | Aspire A515-45              | [8fa60907d5](https://linux-hardware.org/?probe=8fa60907d5) | Apr 02, 2023 |
| Dell          | Precision M4700             | [aea1cc51a5](https://linux-hardware.org/?probe=aea1cc51a5) | Apr 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [e42bc1dd05](https://linux-hardware.org/?probe=e42bc1dd05) | Apr 02, 2023 |
| Acer          | TravelMate P215-53          | [bd1d2b4102](https://linux-hardware.org/?probe=bd1d2b4102) | Apr 02, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Dell          | Precision 5540              | [f25b25b590](https://linux-hardware.org/?probe=f25b25b590) | Apr 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Pavilion dv7                | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| ASUSTek       | X202E                       | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [ae7a7254b8](https://linux-hardware.org/?probe=ae7a7254b8) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [2239e12384](https://linux-hardware.org/?probe=2239e12384) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Dell          | Precision M4700             | [7c93bc178e](https://linux-hardware.org/?probe=7c93bc178e) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [990f324256](https://linux-hardware.org/?probe=990f324256) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [b6226ae481](https://linux-hardware.org/?probe=b6226ae481) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [bf3d484605](https://linux-hardware.org/?probe=bf3d484605) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [3e4d9fac89](https://linux-hardware.org/?probe=3e4d9fac89) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e85544a3d7](https://linux-hardware.org/?probe=e85544a3d7) | Mar 30, 2023 |
| Dell          | Precision M4800             | [ebd0442adc](https://linux-hardware.org/?probe=ebd0442adc) | Mar 30, 2023 |
| Lenovo        | ThinkPad T60 195143U        | [4de196550b](https://linux-hardware.org/?probe=4de196550b) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| Unknown       | Unknown                     | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| Dell          | Inspiron 15 3511            | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| Apple         | MacBookPro5,5               | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Dell          | Latitude E6420              | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Dell          | Latitude 7480               | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| TUXEDO        | N13xWU                      | [e9614af654](https://linux-hardware.org/?probe=e9614af654) | Mar 19, 2023 |
| Dell          | Latitude 7480               | [bbdb75bdce](https://linux-hardware.org/?probe=bbdb75bdce) | Mar 19, 2023 |
| HP            | Pavilion g7                 | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| Acer          | Aspire V5-552PG             | [d895f0f391](https://linux-hardware.org/?probe=d895f0f391) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [229dcc2cb0](https://linux-hardware.org/?probe=229dcc2cb0) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [5037090da8](https://linux-hardware.org/?probe=5037090da8) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| HP            | Notebook                    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Dell          | Precision M6800             | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| Dell          | Latitude 7480               | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Acer          | AO756                       | [21ba8b2996](https://linux-hardware.org/?probe=21ba8b2996) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [c8c6ab5fce](https://linux-hardware.org/?probe=c8c6ab5fce) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [634ae1ae2b](https://linux-hardware.org/?probe=634ae1ae2b) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX534FAC_UX533FA... | [83351958e6](https://linux-hardware.org/?probe=83351958e6) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [a897cf713a](https://linux-hardware.org/?probe=a897cf713a) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [63cbbd1f57](https://linux-hardware.org/?probe=63cbbd1f57) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [f5cbc232d7](https://linux-hardware.org/?probe=f5cbc232d7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [aeb56fbebc](https://linux-hardware.org/?probe=aeb56fbebc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [ee034131c0](https://linux-hardware.org/?probe=ee034131c0) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [438caf3588](https://linux-hardware.org/?probe=438caf3588) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [57d173995a](https://linux-hardware.org/?probe=57d173995a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [812104dae3](https://linux-hardware.org/?probe=812104dae3) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [27c3c24dfc](https://linux-hardware.org/?probe=27c3c24dfc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [714f8e1321](https://linux-hardware.org/?probe=714f8e1321) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [500bee4bb7](https://linux-hardware.org/?probe=500bee4bb7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [189b1a8ec7](https://linux-hardware.org/?probe=189b1a8ec7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [9be2c9ee2b](https://linux-hardware.org/?probe=9be2c9ee2b) | Mar 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [054bb62a67](https://linux-hardware.org/?probe=054bb62a67) | Mar 14, 2023 |
| Lenovo        | Z710 20250                  | [3a99fb6400](https://linux-hardware.org/?probe=3a99fb6400) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [07ceb1e102](https://linux-hardware.org/?probe=07ceb1e102) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [79fdcb1951](https://linux-hardware.org/?probe=79fdcb1951) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [73e4261a63](https://linux-hardware.org/?probe=73e4261a63) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [44784531d4](https://linux-hardware.org/?probe=44784531d4) | Mar 13, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [e58e88f5fd](https://linux-hardware.org/?probe=e58e88f5fd) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [267c6693a0](https://linux-hardware.org/?probe=267c6693a0) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [bdb4c28449](https://linux-hardware.org/?probe=bdb4c28449) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [d9226f0ad6](https://linux-hardware.org/?probe=d9226f0ad6) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [906f70a5e9](https://linux-hardware.org/?probe=906f70a5e9) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| HP            | ProBook 4415s               | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| Dell          | Latitude E6430              | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| Apple         | MacBook5,2                  | [ffb66872c2](https://linux-hardware.org/?probe=ffb66872c2) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [9736a383d7](https://linux-hardware.org/?probe=9736a383d7) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [f9bd57cf06](https://linux-hardware.org/?probe=f9bd57cf06) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [a71d5d0d96](https://linux-hardware.org/?probe=a71d5d0d96) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Latitude 7285               | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [91985ffa00](https://linux-hardware.org/?probe=91985ffa00) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [40499e56d1](https://linux-hardware.org/?probe=40499e56d1) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [3abbf961d5](https://linux-hardware.org/?probe=3abbf961d5) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [734afe2673](https://linux-hardware.org/?probe=734afe2673) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [364b9159c4](https://linux-hardware.org/?probe=364b9159c4) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Apple         | MacBook5,2                  | [e6cbad4861](https://linux-hardware.org/?probe=e6cbad4861) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [6fa1bc8547](https://linux-hardware.org/?probe=6fa1bc8547) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [ce9ba5580b](https://linux-hardware.org/?probe=ce9ba5580b) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [9a8f396913](https://linux-hardware.org/?probe=9a8f396913) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [07709f5f79](https://linux-hardware.org/?probe=07709f5f79) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [8bbc04cb55](https://linux-hardware.org/?probe=8bbc04cb55) | Mar 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a3682a5cb6](https://linux-hardware.org/?probe=a3682a5cb6) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [7b1918ab47](https://linux-hardware.org/?probe=7b1918ab47) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [0d996d4041](https://linux-hardware.org/?probe=0d996d4041) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [eb4c28b498](https://linux-hardware.org/?probe=eb4c28b498) | Mar 07, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [124045e654](https://linux-hardware.org/?probe=124045e654) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [cdaf43afa8](https://linux-hardware.org/?probe=cdaf43afa8) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Unknown       | Unknown                     | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [54a92cd736](https://linux-hardware.org/?probe=54a92cd736) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [916405bd1c](https://linux-hardware.org/?probe=916405bd1c) | Mar 03, 2023 |
| HP            | 635                         | [108b9443ea](https://linux-hardware.org/?probe=108b9443ea) | Mar 03, 2023 |
| Dell          | Latitude E7440              | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [180f5c9379](https://linux-hardware.org/?probe=180f5c9379) | Mar 03, 2023 |
| Dell          | Vostro1710                  | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Dell          | Latitude 3510               | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | [2894a5929b](https://linux-hardware.org/?probe=2894a5929b) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| GMKtec        | NucBox5                     | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | ProBook 4415s               | [4e909ec0ad](https://linux-hardware.org/?probe=4e909ec0ad) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| HP            | Pavilion g6                 | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Acer          | AO756                       | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| HP            | Presario CQ57               | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| LincPlus      | P2                          | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Acer          | Nitro AN515-55              | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | Latitude E5450              | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| Dell          | Latitude D630               | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Lenovo        | Z50-70 20354                | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| Dell          | Latitude E6330              | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Google        | Terra                       | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| Google        | Ampton                      | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| ASUSTek       | F5SL                        | [1e5bb7661e](https://linux-hardware.org/?probe=1e5bb7661e) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion 15                 | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Lenovo        | ThinkPad 13 20J10046US      | [85b9d54087](https://linux-hardware.org/?probe=85b9d54087) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [b8c8ed32e5](https://linux-hardware.org/?probe=b8c8ed32e5) | Feb 01, 2023 |
| Samsung       | 600B4B/600B5B               | [d3cf4446d5](https://linux-hardware.org/?probe=d3cf4446d5) | Feb 01, 2023 |
| Apple         | MacBookAir7,2               | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Apple         | MacBookPro10,1              | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| HP            | Compaq 6735b                | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Acer          | Swift SF314-56              | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Acer          | Aspire 7745G                | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| Dell          | Latitude 2110               | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Google        | Stout                       | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| Samsung       | 940XFG                      | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 580       | 15.77%  |
| 5.10.0-10-amd64        | 490       | 13.32%  |
| 5.10.0-20-amd64        | 240       | 6.53%   |
| 5.10.0-21-amd64        | 236       | 6.42%   |
| 5.10.0-18-amd64        | 176       | 4.79%   |
| 5.10.0-9-amd64         | 172       | 4.68%   |
| 5.10.0-7-amd64         | 171       | 4.65%   |
| 5.10.0-16-amd64        | 167       | 4.54%   |
| 5.10.0-19-amd64        | 162       | 4.4%    |
| 5.10.0-13-amd64        | 151       | 4.11%   |
| 5.10.0-11-amd64        | 104       | 2.83%   |
| 5.10.0-23-amd64        | 100       | 2.72%   |
| 5.10.0-14-amd64        | 79        | 2.15%   |
| 5.10.0-17-amd64        | 73        | 1.98%   |
| 5.10.0-15-amd64        | 52        | 1.41%   |
| 5.10.0-2-amd64         | 42        | 1.14%   |
| 5.10.0-22-amd64        | 41        | 1.11%   |
| 5.10.0-12-amd64        | 41        | 1.11%   |
| 5.10.0-6-amd64         | 28        | 0.76%   |
| 5.10.0-13-686-pae      | 26        | 0.71%   |
| 6.0.0-0.deb11.6-amd64  | 22        | 0.6%    |
| 5.18.0-0.deb11.4-amd64 | 22        | 0.6%    |
| 6.0.0-0.deb11.2-amd64  | 19        | 0.52%   |
| 5.14.0-0.bpo.2-amd64   | 17        | 0.46%   |
| 6.1.0-0.deb11.5-amd64  | 15        | 0.41%   |
| 5.16.0-0.bpo.4-amd64   | 15        | 0.41%   |
| 5.15.0-2-amd64         | 14        | 0.38%   |
| 5.19.0-0.deb11.2-amd64 | 13        | 0.35%   |
| 5.10.0-3-amd64         | 13        | 0.35%   |
| 6.0.0-6mx-amd64        | 9         | 0.24%   |
| 5.10.0-9-686-pae       | 9         | 0.24%   |
| 5.10.0-8-686-pae       | 9         | 0.24%   |
| 5.10.0-21-686-pae      | 9         | 0.24%   |
| 5.10.0-13-686          | 9         | 0.24%   |
| 5.18.0-0.bpo.1-amd64   | 8         | 0.22%   |
| 5.15.0-0.bpo.2-amd64   | 8         | 0.22%   |
| 5.10.0-9-686           | 8         | 0.22%   |
| 5.19.0-2-amd64         | 7         | 0.19%   |
| 5.10.0-21-686          | 7         | 0.19%   |
| 6.1.0-0.deb11.7-amd64  | 6         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 3022      | 88.65%  |
| 6.0.0    | 54        | 1.58%   |
| 5.18.0   | 41        | 1.2%    |
| 5.15.0   | 37        | 1.09%   |
| 5.16.0   | 35        | 1.03%   |
| 5.19.0   | 31        | 0.91%   |
| 6.1.0    | 29        | 0.85%   |
| 5.14.0   | 24        | 0.7%    |
| 5.17.0   | 13        | 0.38%   |
| 4.19.0   | 8         | 0.23%   |
| 6.3.4    | 3         | 0.09%   |
| 5.15.107 | 3         | 0.09%   |
| 5.13.19  | 3         | 0.09%   |
| 5.12.0   | 3         | 0.09%   |
| 5.10.60  | 3         | 0.09%   |
| 6.2.8    | 2         | 0.06%   |
| 6.1.15   | 2         | 0.06%   |
| 6.0.2    | 2         | 0.06%   |
| 5.17.5   | 2         | 0.06%   |
| 5.17.11  | 2         | 0.06%   |
| 5.15.35  | 2         | 0.06%   |
| 5.13.8   | 2         | 0.06%   |
| 5.11.0   | 2         | 0.06%   |
| 5.10.92  | 2         | 0.06%   |
| 5.10.109 | 2         | 0.06%   |
| 4.9.0    | 2         | 0.06%   |
| 6.4.3    | 1         | 0.03%   |
| 6.4.2    | 1         | 0.03%   |
| 6.3.5    | 1         | 0.03%   |
| 6.3.0    | 1         | 0.03%   |
| 6.2.6    | 1         | 0.03%   |
| 6.2.16   | 1         | 0.03%   |
| 6.2.14   | 1         | 0.03%   |
| 6.2.11   | 1         | 0.03%   |
| 6.1.9    | 1         | 0.03%   |
| 6.1.5    | 1         | 0.03%   |
| 6.1.31   | 1         | 0.03%   |
| 6.1.12   | 1         | 0.03%   |
| 6.0.9    | 1         | 0.03%   |
| 6.0.12   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3038      | 89.25%  |
| 6.0     | 59        | 1.73%   |
| 5.15    | 59        | 1.73%   |
| 5.18    | 43        | 1.26%   |
| 5.16    | 37        | 1.09%   |
| 5.19    | 35        | 1.03%   |
| 6.1     | 33        | 0.97%   |
| 5.14    | 29        | 0.85%   |
| 5.17    | 19        | 0.56%   |
| 4.19    | 10        | 0.29%   |
| 5.13    | 9         | 0.26%   |
| 6.2     | 6         | 0.18%   |
| 5.12    | 6         | 0.18%   |
| 5.11    | 6         | 0.18%   |
| 6.3     | 4         | 0.12%   |
| 6.4     | 2         | 0.06%   |
| 5.1     | 2         | 0.06%   |
| 4.9     | 2         | 0.06%   |
| 5.4     | 1         | 0.03%   |
| 5.15.6  | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 3.8     | 1         | 0.03%   |
| 3.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3200      | 95.84%  |
| i686    | 135       | 4.04%   |
| armv7l  | 3         | 0.09%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 1039      | 30.57%  |
| GNOME             | 864       | 25.42%  |
| KDE5              | 426       | 12.53%  |
| XFCE              | 419       | 12.33%  |
| MATE              | 127       | 3.74%   |
| X-Cinnamon        | 107       | 3.15%   |
| LXDE              | 102       | 3%      |
| Cinnamon          | 87        | 2.56%   |
| LXQt              | 47        | 1.38%   |
| i3                | 42        | 1.24%   |
| KDE               | 35        | 1.03%   |
| GNOME Flashback   | 27        | 0.79%   |
| lightdm-xsession  | 15        | 0.44%   |
| openbox           | 13        | 0.38%   |
| trinity           | 8         | 0.24%   |
| GNOME Classic     | 8         | 0.24%   |
| Budgie            | 5         | 0.15%   |
| Dwm               | 3         | 0.09%   |
| Cutefish          | 3         | 0.09%   |
| BunsenLabs        | 3         | 0.09%   |
| x-session-manager | 2         | 0.06%   |
| sway              | 2         | 0.06%   |
| ICEWM             | 2         | 0.06%   |
| Enlightenment     | 2         | 0.06%   |
| awesome           | 2         | 0.06%   |
| xmonad            | 1         | 0.03%   |
| wmaker-common     | 1         | 0.03%   |
| mwm               | 1         | 0.03%   |
| matchbox          | 1         | 0.03%   |
| jwm               | 1         | 0.03%   |
| GNUstep           | 1         | 0.03%   |
| fluxbox           | 1         | 0.03%   |
| default           | 1         | 0.03%   |
| Deepin            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 1668      | 49.29%  |
| Unknown     | 952       | 28.13%  |
| Wayland     | 638       | 18.85%  |
| Tty         | 121       | 3.58%   |
| Unspecified | 4         | 0.12%   |
| Web         | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1424      | 42.08%  |
| GDM     | 736       | 21.75%  |
| LightDM | 682       | 20.15%  |
| SDDM    | 381       | 11.26%  |
| TDM     | 70        | 2.07%   |
| GDM3    | 70        | 2.07%   |
| XDM     | 7         | 0.21%   |
| LXDM    | 6         | 0.18%   |
| SLiM    | 3         | 0.09%   |
| Ly      | 2         | 0.06%   |
| SU      | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |
| KDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 998       | 29.6%   |
| Unknown | 757       | 22.45%  |
| ru_RU   | 261       | 7.74%   |
| de_DE   | 208       | 6.17%   |
| fr_FR   | 180       | 5.34%   |
| en_GB   | 144       | 4.27%   |
| es_ES   | 106       | 3.14%   |
| it_IT   | 90        | 2.67%   |
| pt_BR   | 83        | 2.46%   |
| pl_PL   | 75        | 2.22%   |
| en_CA   | 35        | 1.04%   |
| es_MX   | 32        | 0.95%   |
| en_AU   | 30        | 0.89%   |
| es_AR   | 24        | 0.71%   |
| zh_CN   | 21        | 0.62%   |
| en_IN   | 20        | 0.59%   |
| C       | 20        | 0.59%   |
| hu_HU   | 15        | 0.44%   |
| en_IE   | 14        | 0.42%   |
| fi_FI   | 13        | 0.39%   |
| es_VE   | 12        | 0.36%   |
| es_CL   | 12        | 0.36%   |
| sv_SE   | 11        | 0.33%   |
| de_CH   | 11        | 0.33%   |
| de_AT   | 11        | 0.33%   |
| nl_NL   | 10        | 0.3%    |
| ja_JP   | 10        | 0.3%    |
| pt_PT   | 9         | 0.27%   |
| es_CO   | 9         | 0.27%   |
| tr_TR   | 8         | 0.24%   |
| nb_NO   | 8         | 0.24%   |
| fr_BE   | 8         | 0.24%   |
| cs_CZ   | 8         | 0.24%   |
| ko_KR   | 7         | 0.21%   |
| en_SG   | 7         | 0.21%   |
| zh_TW   | 6         | 0.18%   |
| sk_SK   | 5         | 0.15%   |
| en_ZA   | 5         | 0.15%   |
| en_NZ   | 5         | 0.15%   |
| uk_UA   | 4         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2260      | 67.14%  |
| BIOS | 1106      | 32.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2144      | 64.02%  |
| Overlay | 1054      | 31.47%  |
| Btrfs   | 90        | 2.69%   |
| Xfs     | 28        | 0.84%   |
| Zfs     | 12        | 0.36%   |
| Tmpfs   | 10        | 0.3%    |
| Ext2    | 4         | 0.12%   |
| Unknown | 3         | 0.09%   |
| Ext3    | 2         | 0.06%   |
| Rootfs  | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2279      | 67.61%  |
| MBR     | 637       | 18.9%   |
| Unknown | 455       | 13.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2691      | 79.9%   |
| Yes       | 677       | 20.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2517      | 74.75%  |
| Yes       | 850       | 25.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 673       | 20.16%  |
| Apple                          | 629       | 18.84%  |
| Hewlett-Packard                | 480       | 14.38%  |
| Dell                           | 423       | 12.67%  |
| ASUSTek Computer               | 280       | 8.39%   |
| Acer                           | 208       | 6.23%   |
| Google                         | 135       | 4.04%   |
| Toshiba                        | 52        | 1.56%   |
| MSI                            | 51        | 1.53%   |
| Aquarius                       | 44        | 1.32%   |
| Samsung Electronics            | 41        | 1.23%   |
| Unknown                        | 29        | 0.87%   |
| HUAWEI                         | 27        | 0.81%   |
| Fujitsu                        | 20        | 0.6%    |
| Sony                           | 19        | 0.57%   |
| Notebook                       | 19        | 0.57%   |
| Packard Bell                   | 13        | 0.39%   |
| Panasonic                      | 9         | 0.27%   |
| Clevo                          | 9         | 0.27%   |
| Medion                         | 8         | 0.24%   |
| TUXEDO                         | 7         | 0.21%   |
| Positivo                       | 7         | 0.21%   |
| Intel                          | 7         | 0.21%   |
| Timi                           | 6         | 0.18%   |
| IBM                            | 6         | 0.18%   |
| GPU Company                    | 6         | 0.18%   |
| SLIMBOOK                       | 5         | 0.15%   |
| LG Electronics                 | 5         | 0.15%   |
| Gigabyte Technology            | 5         | 0.15%   |
| HONOR                          | 4         | 0.12%   |
| Fujitsu Siemens                | 4         | 0.12%   |
| Alienware                      | 4         | 0.12%   |
| System76                       | 3         | 0.09%   |
| SmbiosType1_SystemManufacturer | 3         | 0.09%   |
| Pegatron                       | 3         | 0.09%   |
| PC Specialist                  | 3         | 0.09%   |
| Avell High Performance         | 3         | 0.09%   |
| AMI                            | 3         | 0.09%   |
| VIT                            | 2         | 0.06%   |
| Shanghai Zhaoxin Semiconductor | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 353       | 10.58%  |
| Apple MacBookAir7,2                   | 77        | 2.31%   |
| Apple MacBookAir7,1                   | 77        | 2.31%   |
| Google Enguarde                       | 74        | 2.22%   |
| Apple MacBook2,1                      | 55        | 1.65%   |
| Aquarius NS585                        | 44        | 1.32%   |
| Unknown                               | 34        | 1.02%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.72%   |
| Google Terra                          | 23        | 0.69%   |
| Apple MacBook4,1                      | 21        | 0.63%   |
| HP Notebook                           | 18        | 0.54%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.48%   |
| Acer Aspire A315-23                   | 15        | 0.45%   |
| ASUS 1005HA                           | 14        | 0.42%   |
| Google Reks                           | 13        | 0.39%   |
| HP Pavilion g6                        | 12        | 0.36%   |
| HP Laptop 15-db0xxx                   | 10        | 0.3%    |
| HP EliteBook 8460p                    | 9         | 0.27%   |
| Dell Latitude E7440                   | 9         | 0.27%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.24%   |
| HP EliteBook 840 G3                   | 8         | 0.24%   |
| Dell Latitude 7480                    | 8         | 0.24%   |
| Samsung 300E4C/300E5C/300E7C          | 7         | 0.21%   |
| HP Laptop 15-db1xxx                   | 7         | 0.21%   |
| HP Laptop 15-bw0xx                    | 7         | 0.21%   |
| HP 255 G8 Notebook PC                 | 7         | 0.21%   |
| Dell Latitude E6330                   | 7         | 0.21%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.18%   |
| HP 250 G7 Notebook PC                 | 6         | 0.18%   |
| Dell XPS 13 9310                      | 6         | 0.18%   |
| Dell Latitude E6420                   | 6         | 0.18%   |
| Dell Latitude E5430 non-vPro          | 6         | 0.18%   |
| Dell Latitude 5420                    | 6         | 0.18%   |
| Dell Inspiron 5100                    | 6         | 0.18%   |
| Apple MacBook7,1                      | 6         | 0.18%   |
| HUAWEI NBLK-WAX9X                     | 5         | 0.15%   |
| HP Laptop 15s-eq2xxx                  | 5         | 0.15%   |
| HP EliteBook 840 G8 Notebook PC       | 5         | 0.15%   |
| Dell Latitude E7450                   | 5         | 0.15%   |
| Dell Latitude E6520                   | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 451       | 13.51%  |
| Apple MacBook5    | 353       | 10.58%  |
| Dell Latitude     | 181       | 5.42%   |
| Apple MacBookAir7 | 154       | 4.61%   |
| Acer Aspire       | 139       | 4.16%   |
| Dell Inspiron     | 121       | 3.62%   |
| Lenovo IdeaPad    | 108       | 3.24%   |
| HP EliteBook      | 99        | 2.97%   |
| Google Enguarde   | 74        | 2.22%   |
| HP Pavilion       | 73        | 2.19%   |
| HP Laptop         | 71        | 2.13%   |
| HP ProBook        | 57        | 1.71%   |
| Apple MacBook2    | 55        | 1.65%   |
| Aquarius NS585    | 44        | 1.32%   |
| ASUS VivoBook     | 43        | 1.29%   |
| Toshiba Satellite | 42        | 1.26%   |
| Dell XPS          | 40        | 1.2%    |
| Unknown           | 34        | 1.02%   |
| Dell Precision    | 32        | 0.96%   |
| HP Compaq         | 30        | 0.9%    |
| Dell Vostro       | 30        | 0.9%    |
| HP ZBook          | 23        | 0.69%   |
| Google Terra      | 23        | 0.69%   |
| ASUS ASUS         | 23        | 0.69%   |
| ASUS ZenBook      | 22        | 0.66%   |
| Apple MacBook4    | 21        | 0.63%   |
| HP 250            | 20        | 0.6%    |
| Acer TravelMate   | 19        | 0.57%   |
| HP Notebook       | 18        | 0.54%   |
| Fujitsu LIFEBOOK  | 18        | 0.54%   |
| Lenovo ThinkBook  | 15        | 0.45%   |
| Lenovo Legion     | 15        | 0.45%   |
| Acer Swift        | 15        | 0.45%   |
| Acer Nitro        | 15        | 0.45%   |
| HP ENVY           | 14        | 0.42%   |
| HP 255            | 14        | 0.42%   |
| ASUS ROG          | 14        | 0.42%   |
| ASUS 1005HA       | 14        | 0.42%   |
| Google Reks       | 13        | 0.39%   |
| HP Stream         | 11        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 432       | 12.94%  |
| 2021    | 334       | 10.01%  |
| 2019    | 314       | 9.41%   |
| 2020    | 310       | 9.29%   |
| 2016    | 210       | 6.29%   |
| 2015    | 203       | 6.08%   |
| 2012    | 198       | 5.93%   |
| 2018    | 182       | 5.45%   |
| 2017    | 175       | 5.24%   |
| 2011    | 170       | 5.09%   |
| 2013    | 157       | 4.7%    |
| 2014    | 143       | 4.28%   |
| 2022    | 140       | 4.19%   |
| 2010    | 105       | 3.15%   |
| 2007    | 100       | 3%      |
| 2008    | 92        | 2.76%   |
| 2006    | 28        | 0.84%   |
| 2005    | 18        | 0.54%   |
| 2003    | 9         | 0.27%   |
| 2023    | 8         | 0.24%   |
| 2004    | 6         | 0.18%   |
| Unknown | 3         | 0.09%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3338      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3073      | 91.73%  |
| Enabled  | 277       | 8.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3198      | 95.78%  |
| Yes  | 141       | 4.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 913       | 27.2%   |
| 3.01-4.0    | 680       | 20.26%  |
| 16.01-24.0  | 492       | 14.66%  |
| 1.01-2.0    | 482       | 14.36%  |
| 8.01-16.0   | 419       | 12.48%  |
| 32.01-64.0  | 165       | 4.92%   |
| 2.01-3.0    | 69        | 2.06%   |
| 0.51-1.0    | 58        | 1.73%   |
| 64.01-256.0 | 36        | 1.07%   |
| 24.01-32.0  | 31        | 0.92%   |
| 0.01-0.5    | 11        | 0.33%   |
| Unknown     | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1546      | 43.98%  |
| 2.01-3.0   | 682       | 19.4%   |
| 4.01-8.0   | 379       | 10.78%  |
| 0.51-1.0   | 374       | 10.64%  |
| 3.01-4.0   | 321       | 9.13%   |
| 8.01-16.0  | 105       | 2.99%   |
| 0.01-0.5   | 94        | 2.67%   |
| 16.01-24.0 | 8         | 0.23%   |
| 32.01-64.0 | 2         | 0.06%   |
| 24.01-32.0 | 2         | 0.06%   |
| Unknown    | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2729      | 80.86%  |
| 2      | 548       | 16.24%  |
| 3      | 56        | 1.66%   |
| 0      | 25        | 0.74%   |
| 4      | 13        | 0.39%   |
| 5      | 3         | 0.09%   |
| 7      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2132      | 63.72%  |
| Yes       | 1214      | 36.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2696      | 80.6%   |
| No        | 649       | 19.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3277      | 98.11%  |
| No        | 63        | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2739      | 81.69%  |
| No        | 614       | 18.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1097      | 32.76%  |
| Germany     | 285       | 8.51%   |
| Russia      | 278       | 8.3%    |
| France      | 216       | 6.45%   |
| Spain       | 136       | 4.06%   |
| Brazil      | 112       | 3.34%   |
| Italy       | 109       | 3.25%   |
| Poland      | 98        | 2.93%   |
| UK          | 74        | 2.21%   |
| Netherlands | 55        | 1.64%   |
| Canada      | 51        | 1.52%   |
| Mexico      | 44        | 1.31%   |
| Switzerland | 37        | 1.1%    |
| Australia   | 36        | 1.07%   |
| Argentina   | 36        | 1.07%   |
| China       | 34        | 1.02%   |
| Sweden      | 32        | 0.96%   |
| India       | 29        | 0.87%   |
| Turkey      | 27        | 0.81%   |
| Ukraine     | 25        | 0.75%   |
| Hungary     | 25        | 0.75%   |
| Belgium     | 25        | 0.75%   |
| Finland     | 24        | 0.72%   |
| Austria     | 23        | 0.69%   |
| Norway      | 22        | 0.66%   |
| Portugal    | 21        | 0.63%   |
| Czechia     | 19        | 0.57%   |
| Romania     | 17        | 0.51%   |
| Greece      | 17        | 0.51%   |
| Venezuela   | 15        | 0.45%   |
| Japan       | 15        | 0.45%   |
| Colombia    | 15        | 0.45%   |
| Chile       | 14        | 0.42%   |
| Bulgaria    | 14        | 0.42%   |
| Ireland     | 13        | 0.39%   |
| Indonesia   | 13        | 0.39%   |
| Croatia     | 12        | 0.36%   |
| Thailand    | 10        | 0.3%    |
| Denmark     | 10        | 0.3%    |
| Taiwan      | 9         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 621       | 17.72%  |
| Dover-Foxcroft    | 229       | 6.54%   |
| Voronezh          | 143       | 4.08%   |
| Seville           | 36        | 1.03%   |
| Paris             | 36        | 1.03%   |
| St Petersburg     | 30        | 0.86%   |
| Madrid            | 27        | 0.77%   |
| Berlin            | 27        | 0.77%   |
| Warsaw            | 25        | 0.71%   |
| Moscow            | 24        | 0.68%   |
| Munich            | 19        | 0.54%   |
| Barcelona         | 17        | 0.49%   |
| Amsterdam         | 17        | 0.49%   |
| Vienna            | 16        | 0.46%   |
| Milan             | 16        | 0.46%   |
| Sao Paulo         | 13        | 0.37%   |
| London            | 13        | 0.37%   |
| Istanbul          | 12        | 0.34%   |
| Hamburg           | 12        | 0.34%   |
| Blizniew          | 11        | 0.31%   |
| Prague            | 10        | 0.29%   |
| Perm              | 10        | 0.29%   |
| Helsinki          | 10        | 0.29%   |
| Frankfurt am Main | 10        | 0.29%   |
| Dublin            | 10        | 0.29%   |
| Zagreb            | 9         | 0.26%   |
| Toronto           | 9         | 0.26%   |
| Sydney            | 9         | 0.26%   |
| Chorzele          | 9         | 0.26%   |
| Brisbane          | 9         | 0.26%   |
| Athens            | 9         | 0.26%   |
| San Jose          | 8         | 0.23%   |
| Rome              | 8         | 0.23%   |
| Oslo              | 8         | 0.23%   |
| Natal             | 8         | 0.23%   |
| Mexico City       | 8         | 0.23%   |
| Mesa              | 8         | 0.23%   |
| Lyon              | 8         | 0.23%   |
| Iasi              | 8         | 0.23%   |
| Cologne           | 8         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 533       | 651    | 13.6%   |
| WDC                 | 398       | 482    | 10.16%  |
| Seagate             | 315       | 371    | 8.04%   |
| Toshiba             | 303       | 323    | 7.73%   |
| Fujitsu             | 278       | 282    | 7.09%   |
| Unknown             | 269       | 336    | 6.86%   |
| Kingston            | 211       | 259    | 5.38%   |
| Apple               | 177       | 210    | 4.52%   |
| Sandisk             | 175       | 212    | 4.47%   |
| Crucial             | 153       | 177    | 3.9%    |
| SK hynix            | 141       | 157    | 3.6%    |
| Hitachi             | 109       | 124    | 2.78%   |
| A-DATA Technology   | 95        | 180    | 2.42%   |
| Intel               | 91        | 110    | 2.32%   |
| Micron Technology   | 88        | 93     | 2.25%   |
| HGST                | 66        | 81     | 1.68%   |
| KIOXIA              | 48        | 52     | 1.22%   |
| China               | 30        | 31     | 0.77%   |
| Unknown             | 28        | 30     | 0.71%   |
| LITEON              | 25        | 29     | 0.64%   |
| Transcend           | 18        | 24     | 0.46%   |
| SABRENT             | 17        | 18     | 0.43%   |
| PNY                 | 17        | 21     | 0.43%   |
| SPCC                | 16        | 17     | 0.41%   |
| Phison              | 16        | 20     | 0.41%   |
| Intenso             | 16        | 20     | 0.41%   |
| LITEONIT            | 15        | 18     | 0.38%   |
| Silicon Motion      | 14        | 17     | 0.36%   |
| JMicron Technology  | 12        | 12     | 0.31%   |
| Team                | 11        | 11     | 0.28%   |
| Patriot             | 11        | 11     | 0.28%   |
| GOODRAM             | 11        | 12     | 0.28%   |
| SSSTC               | 8         | 8      | 0.2%    |
| Netac               | 8         | 9      | 0.2%    |
| Lenovo              | 8         | 9      | 0.2%    |
| Apacer              | 8         | 8      | 0.2%    |
| UMIS                | 6         | 10     | 0.15%   |
| ASMT                | 6         | 9      | 0.15%   |
| ADATA Technology    | 6         | 6      | 0.15%   |
| Phison Electronics  | 5         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 5.93%   |
| Apple SSD AP0128H 121GB            | 77        | 1.93%   |
| Apple SSD SM0128G 121GB            | 71        | 1.78%   |
| Toshiba MK1655GSXF 160GB           | 52        | 1.3%    |
| A-DATA SU800 512GB SSD             | 44        | 1.1%    |
| Toshiba MK1653GSX 160GB            | 43        | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB     | 43        | 1.08%   |
| Kingston SA400S37240G 240GB SSD    | 42        | 1.05%   |
| Unknown AGND3R  16GB               | 39        | 0.98%   |
| Kingston SA400S37120G 120GB SSD    | 38        | 0.95%   |
| Unknown HAG2e  16GB                | 30        | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 28        | 0.7%    |
| Unknown                            | 28        | 0.7%    |
| Toshiba MQ04ABF100 1TB             | 26        | 0.65%   |
| Unknown SDW16G  16GB               | 25        | 0.63%   |
| Toshiba MQ01ABF050 500GB           | 25        | 0.63%   |
| Crucial CT500MX500SSD1 500GB       | 24        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB        | 24        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 23        | 0.58%   |
| HGST HTS721010A9E630 1TB           | 22        | 0.55%   |
| Toshiba MQ01ABD100 1TB             | 21        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB       | 21        | 0.53%   |
| Unknown MMC Card  32GB             | 20        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB    | 18        | 0.45%   |
| SABRENT Disk 1TB                   | 17        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD   | 17        | 0.43%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 16        | 0.4%    |
| Samsung SSD 850 EVO 500GB          | 15        | 0.38%   |
| Samsung SSD 850 EVO 250GB          | 15        | 0.38%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 14        | 0.35%   |
| HGST HTS541010A9E680 1TB           | 14        | 0.35%   |
| Kingston SA400S37480G 480GB SSD    | 13        | 0.33%   |
| HGST HTS725050A7E630 500GB         | 13        | 0.33%   |
| Samsung SSD 980 1TB                | 12        | 0.3%    |
| Samsung SSD 860 EVO 250GB          | 12        | 0.3%    |
| Intel SSDPEKNW512G8 512GB          | 12        | 0.3%    |
| Hitachi HTS543216L9SA02 160GB      | 12        | 0.3%    |
| WDC WD10SPZX-24Z10 1TB             | 11        | 0.28%   |
| Unknown SD/MMC/MS PRO 128GB        | 11        | 0.28%   |
| Seagate ST980811AS 80GB            | 11        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 303       | 357    | 23.8%   |
| Fujitsu             | 278       | 282    | 21.84%  |
| Toshiba             | 246       | 260    | 19.32%  |
| WDC                 | 220       | 250    | 17.28%  |
| Hitachi             | 109       | 124    | 8.56%   |
| HGST                | 66        | 81     | 5.18%   |
| Samsung Electronics | 16        | 17     | 1.26%   |
| Unknown             | 12        | 15     | 0.94%   |
| JMicron Technology  | 9         | 9      | 0.71%   |
| ASMT                | 5         | 8      | 0.39%   |
| Intenso             | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Unknown (CF)        | 1         | 1      | 0.08%   |
| SILICONMOTION       | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| Apple               | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 237       | 282    | 19.19%  |
| Kingston            | 166       | 212    | 13.44%  |
| Crucial             | 131       | 152    | 10.61%  |
| SanDisk             | 120       | 149    | 9.72%   |
| Apple               | 93        | 102    | 7.53%   |
| A-DATA Technology   | 70        | 142    | 5.67%   |
| WDC                 | 44        | 61     | 3.56%   |
| Micron Technology   | 30        | 33     | 2.43%   |
| China               | 30        | 31     | 2.43%   |
| SK hynix            | 25        | 30     | 2.02%   |
| Intel               | 25        | 27     | 2.02%   |
| LITEON              | 21        | 23     | 1.7%    |
| Transcend           | 16        | 22     | 1.3%    |
| PNY                 | 16        | 20     | 1.3%    |
| Toshiba             | 15        | 16     | 1.21%   |
| LITEONIT            | 15        | 18     | 1.21%   |
| Intenso             | 13        | 17     | 1.05%   |
| SPCC                | 12        | 13     | 0.97%   |
| Patriot             | 11        | 11     | 0.89%   |
| Team                | 10        | 10     | 0.81%   |
| Netac               | 8         | 9      | 0.65%   |
| GOODRAM             | 8         | 9      | 0.65%   |
| Apacer              | 7         | 7      | 0.57%   |
| Unknown             | 6         | 6      | 0.49%   |
| Lexar               | 5         | 6      | 0.4%    |
| Seagate             | 4         | 4      | 0.32%   |
| Plextor             | 4         | 4      | 0.32%   |
| KingDian            | 4         | 4      | 0.32%   |
| ZTC                 | 3         | 4      | 0.24%   |
| OCZ                 | 3         | 3      | 0.24%   |
| Lenovo              | 3         | 3      | 0.24%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.24%   |
| FORESEE             | 3         | 3      | 0.24%   |
| Dogfish             | 3         | 5      | 0.24%   |
| Corsair             | 3         | 3      | 0.24%   |
| XrayDisk            | 2         | 2      | 0.16%   |
| Verbatim            | 2         | 2      | 0.16%   |
| Unknown             | 2         | 2      | 0.16%   |
| TO Exter            | 2         | 2      | 0.16%   |
| Teclast             | 2         | 3      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1246      | 1413   | 32.96%  |
| SSD     | 1167      | 1526   | 30.87%  |
| NVMe    | 1045      | 1302   | 27.65%  |
| MMC     | 289       | 355    | 7.65%   |
| Unknown | 33        | 36     | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2203      | 2836   | 60.44%  |
| NVMe | 1032      | 1283   | 28.31%  |
| MMC  | 289       | 355    | 7.93%   |
| SAS  | 121       | 158    | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1772      | 2142   | 74.49%  |
| 0.51-1.0   | 549       | 724    | 23.08%  |
| 1.01-2.0   | 43        | 54     | 1.81%   |
| 4.01-10.0  | 11        | 14     | 0.46%   |
| 3.01-4.0   | 3         | 4      | 0.13%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 959       | 27.9%   |
| Unknown        | 742       | 21.59%  |
| 251-500        | 614       | 17.86%  |
| 501-1000       | 375       | 10.91%  |
| 1-20           | 205       | 5.96%   |
| 51-100         | 200       | 5.82%   |
| 1001-2000      | 152       | 4.42%   |
| 21-50          | 117       | 3.4%    |
| 2001-3000      | 38        | 1.11%   |
| More than 3000 | 35        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1323      | 37.62%  |
| Unknown        | 742       | 21.1%   |
| 21-50          | 389       | 11.06%  |
| 101-250        | 343       | 9.75%   |
| 51-100         | 320       | 9.1%    |
| 251-500        | 206       | 5.86%   |
| 501-1000       | 123       | 3.5%    |
| 1001-2000      | 40        | 1.14%   |
| More than 3000 | 13        | 0.37%   |
| 0              | 10        | 0.28%   |
| 2001-3000      | 8         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 25        | 25     | 7.23%   |
| Hitachi HTS543216L9SA02 160GB         | 11        | 11     | 3.18%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.6%    |
| Toshiba MK1655GSXF 160GB              | 8         | 8      | 2.31%   |
| Seagate ST9500325AS 500GB             | 8         | 8      | 2.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 8      | 2.02%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 6         | 7      | 1.73%   |
| Seagate ST9500420AS 500GB             | 6         | 6      | 1.73%   |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 1.73%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.45%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.45%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 1.16%   |
| Toshiba MQ01ABD100 1TB                | 4         | 4      | 1.16%   |
| Hitachi HTS545050B9A300 500GB         | 4         | 4      | 1.16%   |
| HGST HTS725050A7E630 500GB            | 4         | 5      | 1.16%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.87%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.87%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.87%   |
| Seagate ST500LM000-SSHD-8GB           | 3         | 3      | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 0.87%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.87%   |
| Hitachi HTS547575A9E384 752GB         | 3         | 3      | 0.87%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.87%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.58%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 4      | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.58%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 0.58%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.58%   |
| SK hynix SH920 mSATA 128GB SSD        | 2         | 2      | 0.58%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.58%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 2         | 2      | 0.58%   |
| Seagate ST980811AS 80GB               | 2         | 2      | 0.58%   |
| Seagate ST94811A 40GB                 | 2         | 2      | 0.58%   |
| Seagate ST9320423AS 320GB             | 2         | 2      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.58%   |
| Seagate ST2000LX001-1RG174 2TB        | 2         | 2      | 0.58%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.58%   |
| SanDisk SD9TN8W-256G-1006 256GB SSD   | 2         | 2      | 0.58%   |
| SanDisk SD6SP1M256G1012 256GB SSD     | 2         | 2      | 0.58%   |
| Samsung Electronics HM100JC 100GB     | 2         | 2      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 77     | 20.87%  |
| Hitachi             | 54        | 60     | 15.65%  |
| Toshiba             | 42        | 43     | 12.17%  |
| Fujitsu             | 34        | 34     | 9.86%   |
| WDC                 | 27        | 31     | 7.83%   |
| HGST                | 19        | 21     | 5.51%   |
| SK hynix            | 17        | 18     | 4.93%   |
| Samsung Electronics | 16        | 17     | 4.64%   |
| Kingston            | 13        | 13     | 3.77%   |
| Micron Technology   | 10        | 10     | 2.9%    |
| Intel               | 8         | 9      | 2.32%   |
| SanDisk             | 7         | 8      | 2.03%   |
| Crucial             | 6         | 6      | 1.74%   |
| A-DATA Technology   | 4         | 4      | 1.16%   |
| LITEONIT            | 3         | 4      | 0.87%   |
| LITEON              | 3         | 3      | 0.87%   |
| Unknown             | 2         | 2      | 0.58%   |
| ShiJi               | 1         | 1      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| Lenovo              | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| GOODRAM             | 1         | 1      | 0.29%   |
| DGM                 | 1         | 1      | 0.29%   |
| Apple               | 1         | 2      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 77     | 28.02%  |
| Hitachi             | 54        | 60     | 21.01%  |
| Toshiba             | 42        | 43     | 16.34%  |
| Fujitsu             | 34        | 34     | 13.23%  |
| WDC                 | 27        | 31     | 10.51%  |
| HGST                | 19        | 21     | 7.39%   |
| Samsung Electronics | 7         | 7      | 2.72%   |
| IBM/Hitachi         | 1         | 1      | 0.39%   |
| Apple               | 1         | 2      | 0.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 257       | 276    | 74.49%  |
| SSD  | 72        | 76     | 20.87%  |
| NVMe | 16        | 17     | 4.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 12.5%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 12.5%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 12.5%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 12.5%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 12.5%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 12.5%   |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 2      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2405      | 3093   | 67.82%  |
| Detected | 789       | 1160   | 22.25%  |
| Malfunc  | 343       | 369    | 9.67%   |
| Failed   | 8         | 9      | 0.23%   |
| Limited  | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1882      | 51.1%   |
| Samsung Electronics              | 369       | 10.02%  |
| Nvidia                           | 369       | 10.02%  |
| AMD                              | 316       | 8.58%   |
| SanDisk                          | 183       | 4.97%   |
| SK hynix                         | 111       | 3.01%   |
| Apple                            | 83        | 2.25%   |
| Micron Technology                | 58        | 1.57%   |
| Toshiba America Info Systems     | 47        | 1.28%   |
| KIOXIA                           | 47        | 1.28%   |
| Kingston Technology Company      | 47        | 1.28%   |
| ADATA Technology                 | 29        | 0.79%   |
| Phison Electronics               | 26        | 0.71%   |
| Micron/Crucial Technology        | 25        | 0.68%   |
| Silicon Motion                   | 23        | 0.62%   |
| Solid State Storage Technology   | 13        | 0.35%   |
| Union Memory (Shenzhen)          | 9         | 0.24%   |
| Realtek Semiconductor            | 7         | 0.19%   |
| Silicon Integrated Systems [SiS] | 4         | 0.11%   |
| Shenzhen Longsys Electronics     | 4         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.11%   |
| Lite-On Technology               | 4         | 0.11%   |
| Lenovo                           | 4         | 0.11%   |
| ULi Electronics                  | 3         | 0.08%   |
| Marvell Technology Group         | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.05%   |
| Jiangsu Huacun Elec.             | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Transcend                        | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 360       | 9.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 283       | 7.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 226       | 5.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 210       | 5.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 141       | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 139       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 118       | 2.99%   |
| Intel Volume Management Device NVMe RAID Controller                            | 110       | 2.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 90        | 2.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 89        | 2.25%   |
| Samsung NVMe SSD Controller 980                                                | 87        | 2.2%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 80        | 2.03%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 75        | 1.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 72        | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 65        | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 63        | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 58        | 1.47%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 57        | 1.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 54        | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                            | 54        | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 52        | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 51        | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                          | 47        | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 46        | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 45        | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.11%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 40        | 1.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 37        | 0.94%   |
| Intel SSD 660P Series                                                          | 35        | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 34        | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 31        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 30        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 29        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 27        | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 25        | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 25        | 0.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 22        | 0.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 22        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2291      | 59.51%  |
| NVMe | 1032      | 26.81%  |
| IDE  | 271       | 7.04%   |
| RAID | 256       | 6.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2873      | 86.04%  |
| AMD          | 459       | 13.75%  |
| ARM          | 4         | 0.12%   |
| CentaurHauls | 3         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 10.63%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 147       | 4.4%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 91        | 2.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 2.01%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 59        | 1.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 58        | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 56        | 1.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 45        | 1.35%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 42        | 1.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 36        | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 29        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 26        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.75%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.72%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 24        | 0.72%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 20        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 20        | 0.6%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 0.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 18        | 0.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.54%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.48%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 16        | 0.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 16        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 802       | 24.02%  |
| Intel Core i7           | 515       | 15.42%  |
| Intel Core 2 Duo        | 475       | 14.23%  |
| Intel Celeron           | 289       | 8.66%   |
| Other                   | 284       | 8.51%   |
| Intel Core i3           | 218       | 6.53%   |
| AMD Ryzen 5             | 143       | 4.28%   |
| Intel Atom              | 84        | 2.52%   |
| AMD Ryzen 7             | 71        | 2.13%   |
| Intel Core 2            | 64        | 1.92%   |
| Intel Pentium           | 58        | 1.74%   |
| AMD A6                  | 31        | 0.93%   |
| AMD Ryzen 7 PRO         | 29        | 0.87%   |
| Intel Pentium M         | 22        | 0.66%   |
| Intel Genuine           | 19        | 0.57%   |
| AMD A4                  | 17        | 0.51%   |
| Intel Pentium Dual-Core | 16        | 0.48%   |
| AMD Ryzen 9             | 15        | 0.45%   |
| AMD Ryzen 3             | 13        | 0.39%   |
| AMD Ryzen 5 PRO         | 12        | 0.36%   |
| AMD A8                  | 12        | 0.36%   |
| Intel Pentium Dual      | 11        | 0.33%   |
| AMD A10                 | 11        | 0.33%   |
| Intel Celeron M         | 10        | 0.3%    |
| AMD E1                  | 9         | 0.27%   |
| Intel Pentium 4         | 7         | 0.21%   |
| Intel Core i9           | 7         | 0.21%   |
| AMD E2                  | 7         | 0.21%   |
| Intel Pentium Silver    | 6         | 0.18%   |
| AMD A12                 | 6         | 0.18%   |
| AMD E                   | 5         | 0.15%   |
| Intel Xeon              | 4         | 0.12%   |
| Intel Core m7           | 4         | 0.12%   |
| Intel Core m3           | 4         | 0.12%   |
| AMD PRO A10             | 4         | 0.12%   |
| AMD C-50                | 4         | 0.12%   |
| Intel Pentium Gold      | 3         | 0.09%   |
| Intel Mobile Pentium 4  | 3         | 0.09%   |
| Intel Core Duo          | 3         | 0.09%   |
| AMD Turion 64 X2 Mobile | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1941      | 58.13%  |
| 4      | 906       | 27.13%  |
| 6      | 169       | 5.06%   |
| 8      | 142       | 4.25%   |
| 1      | 138       | 4.13%   |
| 10     | 22        | 0.66%   |
| 14     | 13        | 0.39%   |
| 12     | 7         | 0.21%   |
| 16     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3338      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2072      | 62.05%  |
| 1      | 1266      | 37.92%  |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3245      | 97.21%  |
| 32-bit         | 88        | 2.64%   |
| Unknown        | 5         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 551       | 16.28%  |
| 0x1067a    | 414       | 12.23%  |
| 0x306d4    | 220       | 6.5%    |
| 0x306a9    | 159       | 4.7%    |
| 0x806c1    | 138       | 4.08%   |
| 0x206a7    | 134       | 3.96%   |
| 0x806ec    | 112       | 3.31%   |
| 0x30678    | 103       | 3.04%   |
| 0x806e9    | 95        | 2.81%   |
| 0x406e3    | 83        | 2.45%   |
| 0x40651    | 80        | 2.36%   |
| 0x806ea    | 76        | 2.25%   |
| 0x6f6      | 64        | 1.89%   |
| 0x406c4    | 61        | 1.8%    |
| 0xa0652    | 56        | 1.65%   |
| 0x306c3    | 55        | 1.62%   |
| 0x08108109 | 45        | 1.33%   |
| 0x906eb    | 44        | 1.3%    |
| 0x20655    | 44        | 1.3%    |
| 0x906ea    | 41        | 1.21%   |
| 0x0a50000c | 41        | 1.21%   |
| 0x08600106 | 41        | 1.21%   |
| 0x08608103 | 38        | 1.12%   |
| 0x10676    | 36        | 1.06%   |
| 0x706e5    | 35        | 1.03%   |
| 0x0600611a | 31        | 0.92%   |
| 0x706a8    | 29        | 0.86%   |
| 0x06006705 | 29        | 0.86%   |
| 0x6fd      | 26        | 0.77%   |
| 0x106c2    | 26        | 0.77%   |
| 0x506e3    | 25        | 0.74%   |
| 0x506c9    | 24        | 0.71%   |
| 0x806eb    | 23        | 0.68%   |
| 0x106ca    | 23        | 0.68%   |
| 0x08108102 | 21        | 0.62%   |
| 0x6d8      | 20        | 0.59%   |
| 0x906e9    | 19        | 0.56%   |
| 0x906a4    | 19        | 0.56%   |
| 0x806d1    | 19        | 0.56%   |
| 0x906a3    | 16        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 522       | 15.62%  |
| Penryn           | 463       | 13.85%  |
| Broadwell        | 240       | 7.18%   |
| IvyBridge        | 204       | 6.1%    |
| Silvermont       | 197       | 5.89%   |
| Haswell          | 177       | 5.3%    |
| TigerLake        | 176       | 5.27%   |
| SandyBridge      | 174       | 5.21%   |
| Skylake          | 140       | 4.19%   |
| Core             | 116       | 3.47%   |
| Unknown          | 94        | 2.81%   |
| Zen+             | 88        | 2.63%   |
| Westmere         | 78        | 2.33%   |
| Excavator        | 77        | 2.3%    |
| Zen 2            | 75        | 2.24%   |
| CometLake        | 71        | 2.12%   |
| Zen 3            | 59        | 1.77%   |
| IceLake          | 58        | 1.74%   |
| Bonnell          | 55        | 1.65%   |
| P6               | 50        | 1.5%    |
| Goldmont plus    | 47        | 1.41%   |
| Goldmont         | 29        | 0.87%   |
| Bobcat           | 21        | 0.63%   |
| Puma             | 19        | 0.57%   |
| Zen              | 18        | 0.54%   |
| Alderlake Hybrid | 16        | 0.48%   |
| Tremont          | 13        | 0.39%   |
| Jaguar           | 13        | 0.39%   |
| NetBurst         | 10        | 0.3%    |
| Piledriver       | 9         | 0.27%   |
| K10 Llano        | 9         | 0.27%   |
| K8 Hammer        | 8         | 0.24%   |
| K10              | 6         | 0.18%   |
| Nehalem          | 4         | 0.12%   |
| K8 & K10 hybrid  | 4         | 0.12%   |
| Steamroller      | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2358      | 59.67%  |
| Nvidia                           | 979       | 24.77%  |
| AMD                              | 607       | 15.36%  |
| Zhaoxin                          | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| VIA Technologies                 | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 8.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 187       | 4.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 158       | 3.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 155       | 3.73%   |
| Intel HD Graphics 6000                                                                   | 154       | 3.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 119       | 2.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 103       | 2.48%   |
| Intel UHD Graphics 620                                                                   | 100       | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 99        | 2.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 97        | 2.34%   |
| Intel HD Graphics 620                                                                    | 95        | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 90        | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 1.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 80        | 1.93%   |
| Intel HD Graphics 5500                                                                   | 77        | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 77        | 1.86%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 75        | 1.81%   |
| AMD Renoir                                                                               | 75        | 1.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 65        | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 61        | 1.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 58        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 56        | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 56        | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 56        | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 55        | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 1.16%   |
| AMD Lucienne                                                                             | 47        | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 43        | 1.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 42        | 1.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 35        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 0.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 28        | 0.67%   |
| Intel HD Graphics 530                                                                    | 27        | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 26        | 0.63%   |
| Intel HD Graphics 630                                                                    | 25        | 0.6%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 24        | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 0.55%   |
| Nvidia TU117M                                                                            | 23        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1794      | 53.68%  |
| Intel + Nvidia  | 472       | 14.12%  |
| 1 x Nvidia      | 446       | 13.35%  |
| 1 x AMD         | 427       | 12.78%  |
| Intel + AMD     | 83        | 2.48%   |
| AMD + Nvidia    | 62        | 1.86%   |
| 2 x AMD         | 35        | 1.05%   |
| Other           | 14        | 0.42%   |
| 1 x Zhaoxin     | 3         | 0.09%   |
| 1 x SiS         | 3         | 0.09%   |
| 2 x Intel       | 1         | 0.03%   |
| 1 x VIA         | 1         | 0.03%   |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2897      | 86.25%  |
| Unknown     | 270       | 8.04%   |
| Proprietary | 192       | 5.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 2400      | 71.3%   |
| 0.01-0.5       | 603       | 17.91%  |
| 1.01-2.0       | 139       | 4.13%   |
| 3.01-4.0       | 93        | 2.76%   |
| 0.51-1.0       | 91        | 2.7%    |
| 5.01-6.0       | 21        | 0.62%   |
| 7.01-8.0       | 11        | 0.33%   |
| 2.01-3.0       | 6         | 0.18%   |
| More than 64.0 | 1         | 0.03%   |
| 8.01-16.0      | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 629       | 18.06%  |
| AU Optronics            | 556       | 15.96%  |
| BOE                     | 455       | 13.06%  |
| LG Display              | 394       | 11.31%  |
| Chimei Innolux          | 378       | 10.85%  |
| Samsung Electronics     | 245       | 7.03%   |
| Lenovo                  | 80        | 2.3%    |
| Dell                    | 68        | 1.95%   |
| Sharp                   | 66        | 1.89%   |
| Chi Mei Optoelectronics | 60        | 1.72%   |
| Goldstar                | 53        | 1.52%   |
| InfoVision              | 48        | 1.38%   |
| PANDA                   | 36        | 1.03%   |
| Hewlett-Packard         | 36        | 1.03%   |
| BenQ                    | 35        | 1%      |
| Philips                 | 27        | 0.78%   |
| HannStar                | 27        | 0.78%   |
| Unknown                 | 24        | 0.69%   |
| AOC                     | 23        | 0.66%   |
| LG Philips              | 22        | 0.63%   |
| Ancor Communications    | 20        | 0.57%   |
| Iiyama                  | 18        | 0.52%   |
| Acer                    | 18        | 0.52%   |
| ViewSonic               | 17        | 0.49%   |
| CSO                     | 16        | 0.46%   |
| CPT                     | 8         | 0.23%   |
| Sony                    | 7         | 0.2%    |
| Eizo                    | 7         | 0.2%    |
| Quanta Display          | 6         | 0.17%   |
| Panasonic               | 6         | 0.17%   |
| NEC Computers           | 6         | 0.17%   |
| MSI                     | 6         | 0.17%   |
| Pixio                   | 5         | 0.14%   |
| TMX                     | 4         | 0.11%   |
| Vestel Elektronik       | 3         | 0.09%   |
| Toshiba                 | 3         | 0.09%   |
| SLD                     | 3         | 0.09%   |
| LGD                     | 3         | 0.09%   |
| AGO                     | 3         | 0.09%   |
| ___                     | 2         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 209       | 5.95%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 187       | 5.32%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 54        | 1.54%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 42        | 1.2%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 41        | 1.17%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 41        | 1.17%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 38        | 1.08%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 28        | 0.8%    |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 25        | 0.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 25        | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 24        | 0.68%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 22        | 0.63%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 22        | 0.63%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 21        | 0.6%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 21        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 19        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 18        | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 18        | 0.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 16        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 14        | 0.4%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 12        | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 12        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 11        | 0.31%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 10        | 0.28%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 10        | 0.28%   |
| BenQ GW2470 BNQ78E4 1920x1080 530x300mm 24.0-inch                         | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 10        | 0.28%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch     | 9         | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 9         | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 9         | 0.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 9         | 0.26%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 9         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.26%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 9         | 0.26%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch            | 9         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1172      | 35.47%  |
| 1366x768 (WXGA)    | 896       | 27.12%  |
| 1280x800 (WXGA)    | 524       | 15.86%  |
| 1600x900 (HD+)     | 127       | 3.84%   |
| 1440x900 (WXGA+)   | 123       | 3.72%   |
| 3840x2160 (4K)     | 85        | 2.57%   |
| 2560x1440 (QHD)    | 60        | 1.82%   |
| 1920x1200 (WUXGA)  | 59        | 1.79%   |
| 1024x600           | 48        | 1.45%   |
| 1280x1024 (SXGA)   | 26        | 0.79%   |
| 2560x1600          | 21        | 0.64%   |
| 2288x1287          | 21        | 0.64%   |
| 1680x1050 (WSXGA+) | 17        | 0.51%   |
| 1024x768 (XGA)     | 15        | 0.45%   |
| 3840x2400          | 13        | 0.39%   |
| 2560x1080          | 12        | 0.36%   |
| 1360x768           | 12        | 0.36%   |
| 3440x1440          | 10        | 0.3%    |
| 2880x1800          | 10        | 0.3%    |
| 2160x1440          | 7         | 0.21%   |
| Unknown            | 5         | 0.15%   |
| 3840x1080          | 4         | 0.12%   |
| 1400x1050          | 4         | 0.12%   |
| 3200x1800 (QHD+)   | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 1024x576           | 3         | 0.09%   |
| 3840x1200          | 2         | 0.06%   |
| 3840x1100          | 2         | 0.06%   |
| 3072x1920          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1920x540           | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 3840x1600          | 1         | 0.03%   |
| 3520x1080          | 1         | 0.03%   |
| 2520x1680          | 1         | 0.03%   |
| 2048x1152          | 1         | 0.03%   |
| 1920x515           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 990       | 28.42%  |
| 13      | 932       | 26.75%  |
| 14      | 400       | 11.48%  |
| 11      | 257       | 7.38%   |
| 17      | 177       | 5.08%   |
| 12      | 116       | 3.33%   |
| 24      | 115       | 3.3%    |
| 27      | 76        | 2.18%   |
| 23      | 71        | 2.04%   |
| 21      | 61        | 1.75%   |
| 10      | 49        | 1.41%   |
| 18      | 29        | 0.83%   |
| 19      | 24        | 0.69%   |
| 31      | 22        | 0.63%   |
| 16      | 22        | 0.63%   |
| Unknown | 22        | 0.63%   |
| 142     | 21        | 0.6%    |
| 34      | 16        | 0.46%   |
| 25      | 10        | 0.29%   |
| 32      | 9         | 0.26%   |
| 22      | 8         | 0.23%   |
| 20      | 7         | 0.2%    |
| 84      | 6         | 0.17%   |
| 40      | 6         | 0.17%   |
| 72      | 5         | 0.14%   |
| 54      | 5         | 0.14%   |
| 29      | 5         | 0.14%   |
| 46      | 3         | 0.09%   |
| 28      | 3         | 0.09%   |
| 8       | 3         | 0.09%   |
| 52      | 2         | 0.06%   |
| 49      | 2         | 0.06%   |
| 43      | 2         | 0.06%   |
| 26      | 2         | 0.06%   |
| 55      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |
| 37      | 1         | 0.03%   |
| 33      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1641      | 47.48%  |
| 201-300        | 1101      | 31.86%  |
| 501-600        | 244       | 7.06%   |
| 351-400        | 202       | 5.84%   |
| 401-500        | 118       | 3.41%   |
| 601-700        | 43        | 1.24%   |
| 701-800        | 25        | 0.72%   |
| Unknown        | 22        | 0.64%   |
| More than 2000 | 21        | 0.61%   |
| 1001-1500      | 17        | 0.49%   |
| 1501-2000      | 11        | 0.32%   |
| 801-900        | 7         | 0.2%    |
| 101-200        | 3         | 0.09%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2242      | 71.11%  |
| 16/10   | 776       | 24.61%  |
| 5/4     | 26        | 0.82%   |
| 4/3     | 24        | 0.76%   |
| 3/2     | 21        | 0.67%   |
| 1.00    | 21        | 0.67%   |
| 21/9    | 19        | 0.6%    |
| Unknown | 13        | 0.41%   |
| 2.65    | 4         | 0.13%   |
| 3.40    | 2         | 0.06%   |
| 3.20    | 2         | 0.06%   |
| 32/9    | 1         | 0.03%   |
| 3.73    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 1127      | 32.43%  |
| 101-110        | 991       | 28.52%  |
| 51-60          | 259       | 7.45%   |
| 71-80          | 199       | 5.73%   |
| 201-250        | 195       | 5.61%   |
| 121-130        | 137       | 3.94%   |
| 61-70          | 112       | 3.22%   |
| 301-350        | 77        | 2.22%   |
| 251-300        | 53        | 1.53%   |
| 351-500        | 51        | 1.47%   |
| 41-50          | 49        | 1.41%   |
| 151-200        | 49        | 1.41%   |
| More than 1000 | 41        | 1.18%   |
| 141-150        | 41        | 1.18%   |
| 131-140        | 25        | 0.72%   |
| Unknown        | 22        | 0.63%   |
| 111-120        | 18        | 0.52%   |
| 501-1000       | 15        | 0.43%   |
| 91-100         | 11        | 0.32%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1449      | 42.43%  |
| 101-120       | 1220      | 35.72%  |
| 51-100        | 445       | 13.03%  |
| 161-240       | 180       | 5.27%   |
| More than 240 | 54        | 1.58%   |
| 1-50          | 45        | 1.32%   |
| Unknown       | 22        | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2645      | 78.07%  |
| 2     | 423       | 12.49%  |
| 0     | 271       | 8%      |
| 3     | 48        | 1.42%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1582      | 29.27%  |
| Realtek Semiconductor             | 1408      | 26.05%  |
| Qualcomm Atheros                  | 624       | 11.55%  |
| Broadcom                          | 616       | 11.4%   |
| Nvidia                            | 366       | 6.77%   |
| Broadcom Limited                  | 226       | 4.18%   |
| Marvell Technology Group          | 109       | 2.02%   |
| MediaTek                          | 61        | 1.13%   |
| ASIX Electronics                  | 38        | 0.7%    |
| Ralink                            | 35        | 0.65%   |
| TP-Link                           | 27        | 0.5%    |
| Dell                              | 27        | 0.5%    |
| Sierra Wireless                   | 26        | 0.48%   |
| Samsung Electronics               | 26        | 0.48%   |
| Ralink Technology                 | 21        | 0.39%   |
| Xiaomi                            | 19        | 0.35%   |
| Qualcomm                          | 16        | 0.3%    |
| DisplayLink                       | 15        | 0.28%   |
| JMicron Technology                | 13        | 0.24%   |
| Ericsson Business Mobile Networks | 13        | 0.24%   |
| Lenovo                            | 12        | 0.22%   |
| Hewlett-Packard                   | 11        | 0.2%    |
| Huawei Technologies               | 8         | 0.15%   |
| OPPO Electronics                  | 7         | 0.13%   |
| NetGear                           | 6         | 0.11%   |
| Fibocom                           | 6         | 0.11%   |
| Cypress Semiconductor             | 6         | 0.11%   |
| Qualcomm Atheros Communications   | 5         | 0.09%   |
| ICS Advent                        | 5         | 0.09%   |
| ASUSTek Computer                  | 5         | 0.09%   |
| AMD                               | 5         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.07%   |
| Microchip Technology              | 4         | 0.07%   |
| Attansic Technology               | 4         | 0.07%   |
| ULi Electronics                   | 3         | 0.06%   |
| Motorola PCS                      | 3         | 0.06%   |
| D-Link                            | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| Winbond Electronics               | 2         | 0.04%   |
| VIA Technologies                  | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 863       | 13.53%  |
| Nvidia MCP79 Ethernet                                                                 | 360       | 5.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 359       | 5.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 219       | 3.43%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 2.51%   |
| Intel Wireless 7260                                                                   | 152       | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 147       | 2.31%   |
| Intel Wireless 8265 / 8275                                                            | 135       | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 125       | 1.96%   |
| Intel Wireless 7265                                                                   | 124       | 1.94%   |
| Intel Wi-Fi 6 AX201                                                                   | 124       | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 123       | 1.93%   |
| Intel Wi-Fi 6 AX200                                                                   | 104       | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 85        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 82        | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 80        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 76        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 75        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 74        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 71        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 71        | 1.11%   |
| Intel Wireless 8260                                                                   | 71        | 1.11%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 0.88%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 56        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                                  | 49        | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 46        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 46        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 44        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 44        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 44        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 39        | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 38        | 0.6%    |
| Intel Ethernet Connection I219-LM                                                     | 37        | 0.58%   |
| Intel Ethernet Connection I218-LM                                                     | 37        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 37        | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 37        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 36        | 0.56%   |
| Intel Wireless 3165                                                                   | 36        | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 34        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1501      | 43.88%  |
| Qualcomm Atheros                      | 563       | 16.46%  |
| Broadcom                              | 533       | 15.58%  |
| Realtek Semiconductor                 | 415       | 12.13%  |
| Broadcom Limited                      | 197       | 5.76%   |
| MediaTek                              | 56        | 1.64%   |
| Ralink                                | 35        | 1.02%   |
| Sierra Wireless                       | 26        | 0.76%   |
| Ralink Technology                     | 21        | 0.61%   |
| Dell                                  | 18        | 0.53%   |
| TP-Link                               | 13        | 0.38%   |
| Qualcomm                              | 7         | 0.2%    |
| NetGear                               | 6         | 0.18%   |
| Fibocom                               | 6         | 0.18%   |
| Qualcomm Atheros Communications       | 5         | 0.15%   |
| ASUSTek Computer                      | 5         | 0.15%   |
| Ericsson Business Mobile Networks     | 3         | 0.09%   |
| Edimax Technology                     | 2         | 0.06%   |
| Z-Com                                 | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| D-Link                                | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |
| 3Com                                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 359       | 10.45%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 4.66%   |
| Intel Wireless 7260                                                                   | 152       | 4.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 147       | 4.28%   |
| Intel Wireless 8265 / 8275                                                            | 135       | 3.93%   |
| Intel Wireless 7265                                                                   | 124       | 3.61%   |
| Intel Wi-Fi 6 AX201                                                                   | 124       | 3.61%   |
| Intel Wi-Fi 6 AX200                                                                   | 104       | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 85        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 82        | 2.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 80        | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 76        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 75        | 2.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 74        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 71        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 71        | 2.07%   |
| Intel Wireless 8260                                                                   | 71        | 2.07%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 56        | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 46        | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 46        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 44        | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 44        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 39        | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 38        | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 37        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 36        | 1.05%   |
| Intel Wireless 3165                                                                   | 36        | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 34        | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 34        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 28        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                                        | 27        | 0.79%   |
| Intel Wireless 3160                                                                   | 25        | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 25        | 0.73%   |
| Intel Centrino Advanced-N 6200                                                        | 23        | 0.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 22        | 0.64%   |
| Intel Wireless-AC 9260                                                                | 22        | 0.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 20        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 20        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1248      | 44.15%  |
| Intel                            | 632       | 22.36%  |
| Nvidia                           | 366       | 12.95%  |
| Qualcomm Atheros                 | 130       | 4.6%    |
| Marvell Technology Group         | 109       | 3.86%   |
| Broadcom                         | 106       | 3.75%   |
| ASIX Electronics                 | 38        | 1.34%   |
| Broadcom Limited                 | 32        | 1.13%   |
| Xiaomi                           | 19        | 0.67%   |
| Samsung Electronics              | 15        | 0.53%   |
| DisplayLink                      | 15        | 0.53%   |
| TP-Link                          | 14        | 0.5%    |
| JMicron Technology               | 13        | 0.46%   |
| Lenovo                           | 12        | 0.42%   |
| Qualcomm                         | 9         | 0.32%   |
| OPPO Electronics                 | 7         | 0.25%   |
| Cypress Semiconductor            | 6         | 0.21%   |
| MediaTek                         | 5         | 0.18%   |
| ICS Advent                       | 5         | 0.18%   |
| Huawei Technologies              | 5         | 0.18%   |
| Silicon Integrated Systems [SiS] | 4         | 0.14%   |
| Microchip Technology             | 4         | 0.14%   |
| Attansic Technology              | 4         | 0.14%   |
| Motorola PCS                     | 3         | 0.11%   |
| Hewlett-Packard                  | 3         | 0.11%   |
| Apple                            | 3         | 0.11%   |
| VIA Technologies                 | 2         | 0.07%   |
| Spreadtrum Communications        | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| National Semiconductor           | 2         | 0.07%   |
| D-Link                           | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| ULi Electronics                  | 1         | 0.04%   |
| MosChip Semiconductor            | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| LeEco                            | 1         | 0.04%   |
| Google                           | 1         | 0.04%   |
| Digitech Systems                 | 1         | 0.04%   |
| Davicom Semiconductor            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 863       | 30.22%  |
| Nvidia MCP79 Ethernet                                             | 360       | 12.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 219       | 7.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 125       | 4.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 123       | 4.31%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 1.96%   |
| Intel Ethernet Connection (4) I219-V                              | 49        | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 1.54%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 1.3%    |
| Intel Ethernet Connection I218-LM                                 | 37        | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 37        | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 1.09%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 27        | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.91%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 22        | 0.77%   |
| Intel Ethernet Connection (13) I219-V                             | 22        | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 21        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.7%    |
| Intel Ethernet Connection I219-V                                  | 20        | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 17        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.42%   |
| Intel Ethernet Connection (13) I219-LM                            | 12        | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 11        | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 11        | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.35%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3280      | 54.13%  |
| Ethernet | 2693      | 44.45%  |
| Modem    | 82        | 1.35%   |
| Unknown  | 4         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2480      | 70.86%  |
| Ethernet | 1020      | 29.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2435      | 72.88%  |
| 1     | 826       | 24.72%  |
| 0     | 44        | 1.32%   |
| 3     | 35        | 1.05%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2730      | 81.2%   |
| Yes  | 632       | 18.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1139      | 41.3%   |
| Apple                           | 618       | 22.41%  |
| Realtek Semiconductor           | 235       | 8.52%   |
| Qualcomm Atheros Communications | 206       | 7.47%   |
| Broadcom                        | 113       | 4.1%    |
| Lite-On Technology              | 102       | 3.7%    |
| IMC Networks                    | 100       | 3.63%   |
| Foxconn / Hon Hai               | 62        | 2.25%   |
| Dell                            | 39        | 1.41%   |
| Cambridge Silicon Radio         | 33        | 1.2%    |
| Hewlett-Packard                 | 27        | 0.98%   |
| Toshiba                         | 16        | 0.58%   |
| Realtek                         | 15        | 0.54%   |
| ASUSTek Computer                | 13        | 0.47%   |
| Ralink                          | 11        | 0.4%    |
| Ralink Technology               | 6         | 0.22%   |
| Foxconn International           | 4         | 0.15%   |
| Taiyo Yuden                     | 3         | 0.11%   |
| MediaTek                        | 3         | 0.11%   |
| Fujitsu                         | 3         | 0.11%   |
| Alps Electric                   | 3         | 0.11%   |
| Qcom                            | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 509       | 18.45%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 349       | 12.65%  |
| Intel AX201 Bluetooth                               | 233       | 8.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 175       | 6.34%   |
| Apple Bluetooth USB Host Controller                 | 160       | 5.8%    |
| Realtek Bluetooth Radio                             | 151       | 5.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 130       | 4.71%   |
| Intel AX200 Bluetooth                               | 101       | 3.66%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 55        | 1.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33        | 1.2%    |
| Apple Bluetooth Host Controller                     | 30        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 1.05%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 0.91%   |
| Intel Bluetooth Device                              | 25        | 0.91%   |
| Lite-On Bluetooth Device                            | 24        | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.87%   |
| IMC Networks Bluetooth Device                       | 22        | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 0.8%    |
| IMC Networks Wireless_Device                        | 21        | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 0.65%   |
| Intel AX210 Bluetooth                               | 18        | 0.65%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.58%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 15        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.51%   |
| Realtek 802.11ac WLAN Adapter                       | 13        | 0.47%   |
| Lite-On Wireless_Device                             | 12        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.43%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.4%    |
| Broadcom HP Portable SoftSailing                    | 10        | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2463      | 64.56%  |
| Nvidia                                       | 674       | 17.67%  |
| AMD                                          | 494       | 12.95%  |
| C-Media Electronics                          | 23        | 0.6%    |
| Realtek Semiconductor                        | 16        | 0.42%   |
| Logitech                                     | 14        | 0.37%   |
| Lenovo                                       | 11        | 0.29%   |
| Texas Instruments                            | 10        | 0.26%   |
| Plantronics                                  | 10        | 0.26%   |
| Generalplus Technology                       | 10        | 0.26%   |
| Hewlett-Packard                              | 8         | 0.21%   |
| GN Netcom                                    | 8         | 0.21%   |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.16%   |
| Creative Technology                          | 5         | 0.13%   |
| ASUSTek Computer                             | 5         | 0.13%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.1%    |
| JMTek                                        | 4         | 0.1%    |
| Zhaoxin                                      | 3         | 0.08%   |
| ULi Electronics                              | 3         | 0.08%   |
| VIA Technologies                             | 2         | 0.05%   |
| Sennheiser Communications                    | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| RODE Microphones                             | 2         | 0.05%   |
| Razer USA                                    | 2         | 0.05%   |
| Microsoft                                    | 2         | 0.05%   |
| Kingston Technology                          | 2         | 0.05%   |
| CMX Systems                                  | 2         | 0.05%   |
| XMOS                                         | 1         | 0.03%   |
| Toshiba                                      | 1         | 0.03%   |
| Thomann                                      | 1         | 0.03%   |
| Tenx Technology                              | 1         | 0.03%   |
| Syntek                                       | 1         | 0.03%   |
| SteelSeries ApS                              | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| Samsung Electronics                          | 1         | 0.03%   |
| Pixart Imaging                               | 1         | 0.03%   |
| Phoenix Audio Technologies                   | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.03%   |
| Microdia                                     | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 362       | 7.8%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 329       | 7.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 286       | 6.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 244       | 5.26%   |
| Intel Broadwell-U Audio Controller                                                                | 240       | 5.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 237       | 5.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 175       | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 146       | 3.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 138       | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 134       | 2.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 108       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 106       | 2.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 104       | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 103       | 2.22%   |
| Intel 8 Series HD Audio Controller                                                                | 103       | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 89        | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 83        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 81        | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 74        | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 74        | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 74        | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 71        | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 69        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 67        | 1.44%   |
| Intel Comet Lake PCH cAVS                                                                         | 66        | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 62        | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 61        | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 55        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 47        | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 39        | 0.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 39        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 37        | 0.8%    |
| AMD High Definition Audio Controller                                                              | 35        | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 30        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 29        | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 27        | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 27        | 0.58%   |
| Intel CM238 HD Audio Controller                                                                   | 27        | 0.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 24        | 0.52%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 21        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 989       | 29.58%  |
| Samsung Electronics | 869       | 25.99%  |
| Micron Technology   | 369       | 11.03%  |
| Kingston            | 223       | 6.67%   |
| Unknown             | 213       | 6.37%   |
| Crucial             | 176       | 5.26%   |
| Elpida              | 100       | 2.99%   |
| A-DATA Technology   | 63        | 1.88%   |
| Ramaxel Technology  | 59        | 1.76%   |
| Nanya Technology    | 36        | 1.08%   |
| Corsair             | 35        | 1.05%   |
| Unknown (ABCD)      | 24        | 0.72%   |
| GOODRAM             | 24        | 0.72%   |
| Smart               | 20        | 0.6%    |
| Unknown             | 15        | 0.45%   |
| Transcend           | 13        | 0.39%   |
| Team                | 13        | 0.39%   |
| G.Skill             | 10        | 0.3%    |
| Silicon Power       | 6         | 0.18%   |
| Patriot             | 6         | 0.18%   |
| Apacer              | 6         | 0.18%   |
| ASint Technology    | 5         | 0.15%   |
| Timetec             | 4         | 0.12%   |
| AMD                 | 4         | 0.12%   |
| Wilk                | 3         | 0.09%   |
| Smart Brazil        | 3         | 0.09%   |
| Qimonda             | 3         | 0.09%   |
| PNY                 | 3         | 0.09%   |
| Infineon            | 3         | 0.09%   |
| fef5                | 3         | 0.09%   |
| 48spaces            | 3         | 0.09%   |
| Unknown (89F7)      | 2         | 0.06%   |
| Unifosa             | 2         | 0.06%   |
| Teikon              | 2         | 0.06%   |
| Shenzhen WODPOSIT   | 2         | 0.06%   |
| SHARETRONIC         | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| Kllisre             | 2         | 0.06%   |
| Goldkey             | 2         | 0.06%   |
| ff                  | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 7.56%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.95%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.81%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 60        | 1.72%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.26%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 40        | 1.15%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 0.89%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 30        | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 30        | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 30        | 0.86%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.77%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.77%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 26        | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 25        | 0.72%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 25        | 0.72%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.66%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 23        | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.66%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.54%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 18        | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 18        | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.49%   |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                        | 17        | 0.49%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.46%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 16        | 0.46%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 15        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.43%   |
| Unknown                                                          | 15        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.4%    |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 14        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1086      | 37.03%  |
| DDR3    | 979       | 33.38%  |
| DDR2    | 541       | 18.45%  |
| LPDDR4  | 97        | 3.31%   |
| LPDDR3  | 95        | 3.24%   |
| SDRAM   | 62        | 2.11%   |
| DDR     | 34        | 1.16%   |
| Unknown | 19        | 0.65%   |
| DDR5    | 8         | 0.27%   |
| DRAM    | 7         | 0.24%   |
| LPDDR5  | 5         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2696      | 91.73%  |
| Row Of Chips | 155       | 5.27%   |
| Unknown      | 52        | 1.77%   |
| Chip         | 23        | 0.78%   |
| DIMM         | 13        | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 933       | 29.55%  |
| 4096  | 778       | 24.64%  |
| 2048  | 523       | 16.57%  |
| 1024  | 501       | 15.87%  |
| 16384 | 312       | 9.88%   |
| 32768 | 62        | 1.96%   |
| 512   | 35        | 1.11%   |
| 256   | 11        | 0.35%   |
| 8072  | 1         | 0.03%   |
| 384   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 760       | 24.42%  |
| 2667    | 481       | 15.46%  |
| 3200    | 474       | 15.23%  |
| 800     | 373       | 11.99%  |
| 2400    | 175       | 5.62%   |
| 667     | 147       | 4.72%   |
| 1334    | 118       | 3.79%   |
| 2133    | 113       | 3.63%   |
| 1333    | 92        | 2.96%   |
| Unknown | 68        | 2.19%   |
| 1067    | 42        | 1.35%   |
| 1867    | 39        | 1.25%   |
| 4267    | 34        | 1.09%   |
| 3266    | 30        | 0.96%   |
| 4199    | 22        | 0.71%   |
| 1066    | 20        | 0.64%   |
| 533     | 16        | 0.51%   |
| 2048    | 13        | 0.42%   |
| 4800    | 12        | 0.39%   |
| 8400    | 10        | 0.32%   |
| 975     | 10        | 0.32%   |
| 4266    | 8         | 0.26%   |
| 333     | 8         | 0.26%   |
| 3733    | 7         | 0.22%   |
| 266     | 7         | 0.22%   |
| 6400    | 6         | 0.19%   |
| 1866    | 5         | 0.16%   |
| 400     | 5         | 0.16%   |
| 2933    | 3         | 0.1%    |
| 2666    | 3         | 0.1%    |
| 933     | 3         | 0.1%    |
| 1639    | 2         | 0.06%   |
| 3000    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 166     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |
| 100     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 33.33%  |
| Canon               | 5         | 23.81%  |
| Xerox               | 4         | 19.05%  |
| Brother Industries  | 3         | 14.29%  |
| Seiko Epson         | 1         | 4.76%   |
| Samsung Electronics | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 19.05%  |
| Seiko Epson L120 Series             | 1         | 4.76%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 4.76%   |
| HP LaserJet P1005                   | 1         | 4.76%   |
| HP LaserJet 1160 series             | 1         | 4.76%   |
| HP LaserJet 1150                    | 1         | 4.76%   |
| HP LaserJet 1022                    | 1         | 4.76%   |
| HP Ink Tank 110 series              | 1         | 4.76%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 4.76%   |
| HP DeskJet 2130 series              | 1         | 4.76%   |
| Canon PIXMA MX920 Series            | 1         | 4.76%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 4.76%   |
| Canon LBP2900                       | 1         | 4.76%   |
| Canon G3010 series                  | 1         | 4.76%   |
| Canon CanoScan LiDE 300             | 1         | 4.76%   |
| Brother PT-9500PC                   | 1         | 4.76%   |
| Brother MFC-L2707DW                 | 1         | 4.76%   |
| Brother HL-L2340D series            | 1         | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 57.14%  |
| Seiko Epson    | 2         | 28.57%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                       | 2         | 28.57%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 14.29%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 14.29%  |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 14.29%  |
| Canon CanoScan LIDE 25                        | 1         | 14.29%  |
| Canon CanoScan LiDE 220                       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 586       | 24.18%  |
| IMC Networks                           | 269       | 11.1%   |
| Quanta                                 | 226       | 9.33%   |
| Microdia                               | 184       | 7.59%   |
| Realtek Semiconductor                  | 176       | 7.26%   |
| Bison Electronics                      | 167       | 6.89%   |
| Sunplus Innovation Technology          | 115       | 4.75%   |
| Acer                                   | 88        | 3.63%   |
| Cheng Uei Precision Industry (Foxlink) | 84        | 3.47%   |
| Suyin                                  | 73        | 3.01%   |
| Lite-On Technology                     | 65        | 2.68%   |
| Syntek                                 | 54        | 2.23%   |
| Luxvisions Innotech Limited            | 54        | 2.23%   |
| Apple                                  | 47        | 1.94%   |
| Silicon Motion                         | 28        | 1.16%   |
| Logitech                               | 28        | 1.16%   |
| Alcor Micro                            | 23        | 0.95%   |
| Lenovo                                 | 22        | 0.91%   |
| Sonix Technology                       | 13        | 0.54%   |
| Ricoh                                  | 12        | 0.5%    |
| Z-Star Microelectronics                | 10        | 0.41%   |
| Primax Electronics                     | 10        | 0.41%   |
| Importek                               | 8         | 0.33%   |
| ALi                                    | 6         | 0.25%   |
| SunplusIT                              | 5         | 0.21%   |
| Intel                                  | 5         | 0.21%   |
| icSpring                               | 5         | 0.21%   |
| Genesys Logic                          | 5         | 0.21%   |
| Y Media                                | 4         | 0.17%   |
| Samsung Electronics                    | 4         | 0.17%   |
| OmniVision Technologies                | 4         | 0.17%   |
| MacroSilicon                           | 3         | 0.12%   |
| Sunplus Technology                     | 2         | 0.08%   |
| Pixart Imaging                         | 2         | 0.08%   |
| Mimaki Engineering                     | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |
| Generalplus Technology                 | 2         | 0.08%   |
| ARC International                      | 2         | 0.08%   |
| Alpha Imaging Technology               | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 169       | 6.94%   |
| Microdia Integrated_Webcam_HD                       | 97        | 3.98%   |
| IMC Networks Integrated Camera                      | 81        | 3.33%   |
| Quanta Chromebook HD Camera                         | 69        | 2.83%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 64        | 2.63%   |
| Realtek Integrated_Webcam_HD                        | 62        | 2.55%   |
| Chicony HD WebCam                                   | 52        | 2.13%   |
| Bison BisonCam, NB Pro                              | 51        | 2.09%   |
| Sunplus Integrated_Webcam_HD                        | 38        | 1.56%   |
| Acer Integrated Camera                              | 36        | 1.48%   |
| Chicony USB2.0 HD UVC WebCam                        | 35        | 1.44%   |
| Chicony HP HD Camera                                | 34        | 1.4%    |
| Bison Integrated Camera                             | 33        | 1.35%   |
| Quanta HP TrueVision HD Camera                      | 29        | 1.19%   |
| Syntek Integrated Camera                            | 28        | 1.15%   |
| Quanta HD User Facing                               | 28        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 27        | 1.11%   |
| Quanta VGA WebCam                                   | 24        | 0.99%   |
| Lite-On Integrated Camera                           | 22        | 0.9%    |
| Microdia Integrated Webcam                          | 21        | 0.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.86%   |
| Lite-On HP HD Camera                                | 21        | 0.86%   |
| Bison SunplusIT Integrated Camera                   | 21        | 0.86%   |
| Realtek USB Camera                                  | 20        | 0.82%   |
| Quanta HP HD Camera                                 | 18        | 0.74%   |
| Chicony HP Truevision HD camera                     | 17        | 0.7%    |
| Chicony HD User Facing                              | 17        | 0.7%    |
| Sunplus HD WebCam                                   | 16        | 0.66%   |
| Luxvisions Innotech Limited HP HD Camera            | 15        | 0.62%   |
| Chicony Lenovo EasyCamera                           | 15        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)             | 15        | 0.62%   |
| Chicony Chromebook HD Camera                        | 15        | 0.62%   |
| Apple Built-in iSight                               | 15        | 0.62%   |
| Realtek Integrated Webcam                           | 14        | 0.57%   |
| Chicony HP Webcam                                   | 14        | 0.57%   |
| Chicony HP Truevision HD                            | 14        | 0.57%   |
| Bison Lenovo Integrated Webcam                      | 14        | 0.57%   |
| Bison Lenovo EasyCamera                             | 14        | 0.57%   |
| Suyin HP TrueVision HD                              | 13        | 0.53%   |
| Quanta HD WebCam                                    | 13        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 177       | 35.47%  |
| Synaptics                          | 148       | 29.66%  |
| Shenzhen Goodix Technology         | 68        | 13.63%  |
| Upek                               | 29        | 5.81%   |
| AuthenTec                          | 28        | 5.61%   |
| Elan Microelectronics              | 21        | 4.21%   |
| LighTuning Technology              | 17        | 3.41%   |
| STMicroelectronics                 | 9         | 1.8%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.2%    |
| Focal-systems.Corp                 | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 12.63%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 8.42%   |
| Shenzhen Goodix  Fingerprint Device                                        | 40        | 8.02%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 6.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 32        | 6.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 5.21%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 4.81%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 3.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 3.41%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.01%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.61%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.4%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 2%      |
| Validity Sensors VFS491                                                    | 9         | 1.8%    |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.8%    |
| Elan ELAN:ARM-M4                                                           | 9         | 1.8%    |
| AuthenTec AES2810                                                          | 8         | 1.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.4%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.2%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.2%    |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.2%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.8%    |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 4         | 0.8%    |
| Synaptics UWP WBDI                                                         | 4         | 0.8%    |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.6%    |
| Synaptics WBDI                                                             | 3         | 0.6%    |
| Synaptics  WBDI                                                            | 3         | 0.6%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.6%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.6%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.4%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.4%    |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 107       | 38.63%  |
| Alcor Micro               | 93        | 33.57%  |
| Upek                      | 24        | 8.66%   |
| O2 Micro                  | 22        | 7.94%   |
| Lenovo                    | 16        | 5.78%   |
| Gemalto (was Gemplus)     | 4         | 1.44%   |
| Yubico.com                | 2         | 0.72%   |
| SCM Microsystems          | 2         | 0.72%   |
| Aladdin Knowledge Systems | 2         | 0.72%   |
| OmniKey                   | 1         | 0.36%   |
| Clay Logic                | 1         | 0.36%   |
| Cherry                    | 1         | 0.36%   |
| C3PO                      | 1         | 0.36%   |
| Advanced Card Systems     | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 92        | 33.21%  |
| Broadcom 58200                                                               | 34        | 12.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 10.47%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 8.66%   |
| Broadcom 5880                                                                | 23        | 8.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 6.86%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.5%    |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.44%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.72%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.72%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.72%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.72%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.36%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.36%   |
| OmniKey CardMan 4321                                                         | 1         | 0.36%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.36%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.36%   |
| C3PO LTC31v2                                                                 | 1         | 0.36%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.36%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1960      | 58.09%  |
| 1     | 1082      | 32.07%  |
| 2     | 260       | 7.71%   |
| 3     | 63        | 1.87%   |
| 4     | 5         | 0.15%   |
| 5     | 3         | 0.09%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 497       | 28.19%  |
| Graphics card            | 475       | 26.94%  |
| Chipcard                 | 259       | 14.69%  |
| Multimedia controller    | 203       | 11.51%  |
| Net/wireless             | 173       | 9.81%   |
| Bluetooth                | 33        | 1.87%   |
| Communication controller | 26        | 1.47%   |
| Storage                  | 22        | 1.25%   |
| Card reader              | 20        | 1.13%   |
| Camera                   | 19        | 1.08%   |
| Sound                    | 10        | 0.57%   |
| Net/ethernet             | 9         | 0.51%   |
| Network                  | 5         | 0.28%   |
| Modem                    | 4         | 0.23%   |
| Flash memory             | 4         | 0.23%   |
| Unassigned class         | 2         | 0.11%   |
| Tv card                  | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |


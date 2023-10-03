Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

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

Total: 116

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| COM1          | NBINF-X5-9G5                | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| Dell          | Latitude 7280               | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| ASUSTek       | UX303UA                     | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | G50-45 80E3                 | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| ASUSTek       | UX303UA                     | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Dell          | XPS 13 9310                 | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| Dell          | Latitude 5521               | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Acer          | Aspire A317-53              | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASUSTek       | UX303UA                     | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Dell          | Inspiron 3543               | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Latitude 7480               | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 7         | 7.45%   |
| 5.15.0-50-generic     | 5         | 5.32%   |
| 5.15.0-48-generic     | 5         | 5.32%   |
| 5.19.0-46-generic     | 4         | 4.26%   |
| 5.15.0-52-generic     | 4         | 4.26%   |
| 5.19.0-41-generic     | 3         | 3.19%   |
| 5.19.0-35-generic     | 3         | 3.19%   |
| 5.15.0-53-generic     | 3         | 3.19%   |
| 5.15.0-40-generic     | 3         | 3.19%   |
| 5.15.0-39-generic     | 3         | 3.19%   |
| 5.15.0-30-generic     | 3         | 3.19%   |
| 6.2.0-32-generic      | 2         | 2.13%   |
| 6.2.0-26-generic      | 2         | 2.13%   |
| 6.2.0-10007-tuxedo    | 2         | 2.13%   |
| 5.19.0-42-generic     | 2         | 2.13%   |
| 5.19.0-38-generic     | 2         | 2.13%   |
| 5.15.0-67-generic     | 2         | 2.13%   |
| 5.15.0-58-generic     | 2         | 2.13%   |
| 5.15.0-56-generic     | 2         | 2.13%   |
| 5.15.0-47-generic     | 2         | 2.13%   |
| 5.15.0-46-generic     | 2         | 2.13%   |
| 5.15.0-33-generic     | 2         | 2.13%   |
| 5.15.0-25-generic     | 2         | 2.13%   |
| 6.3.1-060301-generic  | 1         | 1.06%   |
| 6.2.0-33-generic      | 1         | 1.06%   |
| 6.2.0-10018-tuxedo    | 1         | 1.06%   |
| 6.1.0-060100-generic  | 1         | 1.06%   |
| 5.19.0-45-generic     | 1         | 1.06%   |
| 5.19.0-40-generic     | 1         | 1.06%   |
| 5.19.0-32-generic     | 1         | 1.06%   |
| 5.19.0-051900-generic | 1         | 1.06%   |
| 5.15.0-79-lowlatency  | 1         | 1.06%   |
| 5.15.0-76-lowlatency  | 1         | 1.06%   |
| 5.15.0-76-generic     | 1         | 1.06%   |
| 5.15.0-69-generic     | 1         | 1.06%   |
| 5.15.0-60-generic     | 1         | 1.06%   |
| 5.15.0-57-generic     | 1         | 1.06%   |
| 5.15.0-52-lowlatency  | 1         | 1.06%   |
| 5.15.0-43-generic     | 1         | 1.06%   |
| 5.15.0-41-generic     | 1         | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 60        | 67.42%  |
| 5.19.0  | 17        | 19.1%   |
| 6.2.0   | 8         | 8.99%   |
| 5.13.0  | 2         | 2.25%   |
| 6.3.1   | 1         | 1.12%   |
| 6.1.0   | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 60        | 67.42%  |
| 5.19    | 17        | 19.1%   |
| 6.2     | 8         | 8.99%   |
| 5.13    | 2         | 2.25%   |
| 6.3     | 1         | 1.12%   |
| 6.1     | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 80        | 94.12%  |
| GNOME  | 5         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 82        | 96.47%  |
| Wayland | 3         | 3.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 62        | 72.94%  |
| Unknown | 14        | 16.47%  |
| GDM3    | 9         | 10.59%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 28        | 32.94%  |
| de_DE | 12        | 14.12%  |
| fr_FR | 10        | 11.76%  |
| pt_BR | 5         | 5.88%   |
| en_GB | 4         | 4.71%   |
| it_IT | 3         | 3.53%   |
| en_CA | 3         | 3.53%   |
| ru_RU | 2         | 2.35%   |
| hu_HU | 2         | 2.35%   |
| fr_BE | 2         | 2.35%   |
| en_IE | 2         | 2.35%   |
| pl_PL | 1         | 1.18%   |
| mt_MT | 1         | 1.18%   |
| ja_JP | 1         | 1.18%   |
| es_PE | 1         | 1.18%   |
| es_MX | 1         | 1.18%   |
| es_ES | 1         | 1.18%   |
| es_EC | 1         | 1.18%   |
| es_CL | 1         | 1.18%   |
| en_SG | 1         | 1.18%   |
| en_AU | 1         | 1.18%   |
| cs_CZ | 1         | 1.18%   |
| C     | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 48        | 56.47%  |
| EFI  | 37        | 43.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 77        | 88.51%  |
| Tmpfs   | 3         | 3.45%   |
| Overlay | 3         | 3.45%   |
| Zfs     | 2         | 2.3%    |
| Xfs     | 1         | 1.15%   |
| Btrfs   | 1         | 1.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 56        | 65.88%  |
| Unknown | 24        | 28.24%  |
| MBR     | 5         | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 85.88%  |
| Yes       | 12        | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 69.77%  |
| Yes       | 26        | 30.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 20        | 23.53%  |
| Dell                   | 13        | 15.29%  |
| Hewlett-Packard        | 12        | 14.12%  |
| ASUSTek Computer       | 11        | 12.94%  |
| TUXEDO                 | 9         | 10.59%  |
| Apple                  | 4         | 4.71%   |
| MSI                    | 3         | 3.53%   |
| Google                 | 2         | 2.35%   |
| Toshiba                | 1         | 1.18%   |
| Timi                   | 1         | 1.18%   |
| Razer                  | 1         | 1.18%   |
| HUAWEI                 | 1         | 1.18%   |
| Digibras               | 1         | 1.18%   |
| COM1                   | 1         | 1.18%   |
| Chuwi                  | 1         | 1.18%   |
| BANGHO                 | 1         | 1.18%   |
| AXIOO                  | 1         | 1.18%   |
| Avell High Performance | 1         | 1.18%   |
| Acer                   | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 2.35%   |
| Lenovo G50-45 80E3                                   | 2         | 2.35%   |
| HP EliteBook 840 G3                                  | 2         | 2.35%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.18%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.18%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 1.18%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.18%   |
| TUXEDO Book XP1511                                   | 1         | 1.18%   |
| TUXEDO Book BA1510                                   | 1         | 1.18%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.18%   |
| Toshiba Satellite A505                               | 1         | 1.18%   |
| Timi TM1604                                          | 1         | 1.18%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.18%   |
| MSI Modern 15 A10M                                   | 1         | 1.18%   |
| MSI GL62 6QF                                         | 1         | 1.18%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.18%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.18%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 1.18%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.18%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.18%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.18%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.18%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 1.18%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.18%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.18%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.18%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.18%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.18%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.18%   |
| Lenovo IdeaPad 520-15IKB 81BF                        | 1         | 1.18%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.18%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.18%   |
| Lenovo IdeaPad 110-15ISK 80UD                        | 1         | 1.18%   |
| Lenovo G500 20236                                    | 1         | 1.18%   |
| HUAWEI HKD-WXX                                       | 1         | 1.18%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.18%   |
| HP ProBook 450 G7                                    | 1         | 1.18%   |
| HP ProBook 445 G7                                    | 1         | 1.18%   |
| HP Pavilion Gaming Notebook                          | 1         | 1.18%   |
| HP Pavilion g6                                       | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 8         | 9.41%   |
| Lenovo IdeaPad              | 7         | 8.24%   |
| Dell Latitude               | 5         | 5.88%   |
| HP EliteBook                | 4         | 4.71%   |
| Dell Inspiron               | 4         | 4.71%   |
| TUXEDO Book                 | 3         | 3.53%   |
| HP ProBook                  | 3         | 3.53%   |
| ASUS VivoBook               | 3         | 3.53%   |
| TUXEDO Pulse                | 2         | 2.35%   |
| TUXEDO InfinityBook         | 2         | 2.35%   |
| Lenovo G50-45               | 2         | 2.35%   |
| HP Pavilion                 | 2         | 2.35%   |
| Dell XPS                    | 2         | 2.35%   |
| TUXEDO Polaris              | 1         | 1.18%   |
| TUXEDO Aura                 | 1         | 1.18%   |
| Toshiba Satellite           | 1         | 1.18%   |
| Timi TM1604                 | 1         | 1.18%   |
| Razer Blade                 | 1         | 1.18%   |
| MSI Modern                  | 1         | 1.18%   |
| MSI GL62                    | 1         | 1.18%   |
| MSI Alpha                   | 1         | 1.18%   |
| Lenovo V15                  | 1         | 1.18%   |
| Lenovo Legion               | 1         | 1.18%   |
| Lenovo G500                 | 1         | 1.18%   |
| HUAWEI HKD-WXX              | 1         | 1.18%   |
| HP ENVY                     | 1         | 1.18%   |
| HP ElitePad                 | 1         | 1.18%   |
| HP Bloog                    | 1         | 1.18%   |
| Google Rabbid               | 1         | 1.18%   |
| Google Boten                | 1         | 1.18%   |
| Digibras NH4CU03            | 1         | 1.18%   |
| Dell Vostro                 | 1         | 1.18%   |
| Dell Precision              | 1         | 1.18%   |
| COM1 NBINF-X5-9G5           | 1         | 1.18%   |
| Chuwi HeroBook              | 1         | 1.18%   |
| BANGHO BES                  | 1         | 1.18%   |
| AXIOO Slimbook              | 1         | 1.18%   |
| Avell High Performance B.ON | 1         | 1.18%   |
| ASUS ZenBook                | 1         | 1.18%   |
| ASUS X555LAB                | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 16        | 18.82%  |
| 2020 | 14        | 16.47%  |
| 2016 | 9         | 10.59%  |
| 2014 | 8         | 9.41%   |
| 2019 | 7         | 8.24%   |
| 2018 | 6         | 7.06%   |
| 2017 | 4         | 4.71%   |
| 2013 | 4         | 4.71%   |
| 2022 | 3         | 3.53%   |
| 2015 | 3         | 3.53%   |
| 2011 | 3         | 3.53%   |
| 2009 | 3         | 3.53%   |
| 2012 | 2         | 2.35%   |
| 2010 | 2         | 2.35%   |
| 2008 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 85        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 78        | 91.76%  |
| Enabled  | 7         | 8.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 96.47%  |
| Yes  | 3         | 3.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 33.72%  |
| 16.01-24.0  | 21        | 24.42%  |
| 3.01-4.0    | 11        | 12.79%  |
| 8.01-16.0   | 11        | 12.79%  |
| 32.01-64.0  | 9         | 10.47%  |
| 64.01-256.0 | 4         | 4.65%   |
| 1.01-2.0    | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 29        | 32.22%  |
| 1.01-2.0   | 22        | 24.44%  |
| 4.01-8.0   | 16        | 17.78%  |
| 3.01-4.0   | 12        | 13.33%  |
| 8.01-16.0  | 7         | 7.78%   |
| 24.01-32.0 | 2         | 2.22%   |
| 16.01-24.0 | 2         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 75.86%  |
| 2      | 19        | 21.84%  |
| 3      | 2         | 2.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 81.18%  |
| Yes       | 16        | 18.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 76.74%  |
| No        | 20        | 23.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 97.65%  |
| No        | 2         | 2.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 87.06%  |
| No        | 11        | 12.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 14        | 16.47%  |
| USA                | 12        | 14.12%  |
| France             | 11        | 12.94%  |
| Brazil             | 5         | 5.88%   |
| Poland             | 3         | 3.53%   |
| Italy              | 3         | 3.53%   |
| Canada             | 3         | 3.53%   |
| UK                 | 2         | 2.35%   |
| Ireland            | 2         | 2.35%   |
| Hungary            | 2         | 2.35%   |
| Belgium            | 2         | 2.35%   |
| Austria            | 2         | 2.35%   |
| Sweden             | 1         | 1.18%   |
| Spain              | 1         | 1.18%   |
| Slovenia           | 1         | 1.18%   |
| Singapore          | 1         | 1.18%   |
| Russia             | 1         | 1.18%   |
| Romania            | 1         | 1.18%   |
| Peru               | 1         | 1.18%   |
| Mexico             | 1         | 1.18%   |
| Malta              | 1         | 1.18%   |
| Japan              | 1         | 1.18%   |
| Indonesia          | 1         | 1.18%   |
| Greece             | 1         | 1.18%   |
| Ghana              | 1         | 1.18%   |
| Ecuador            | 1         | 1.18%   |
| Dominican Republic | 1         | 1.18%   |
| Czechia            | 1         | 1.18%   |
| Cuba               | 1         | 1.18%   |
| Chile              | 1         | 1.18%   |
| Cabo Verde         | 1         | 1.18%   |
| Bulgaria           | 1         | 1.18%   |
| Belarus            | 1         | 1.18%   |
| Australia          | 1         | 1.18%   |
| Argentina          | 1         | 1.18%   |
| Algeria            | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 2.3%    |
| Vienna                | 2         | 2.3%    |
| Victoria              | 2         | 2.3%    |
| Frankfurt am Main     | 2         | 2.3%    |
| Dublin                | 2         | 2.3%    |
| Budapest              | 2         | 2.3%    |
| Berlin                | 2         | 2.3%    |
| Wertheim am Main      | 1         | 1.15%   |
| Weisswasser           | 1         | 1.15%   |
| Weilheim              | 1         | 1.15%   |
| Washington            | 1         | 1.15%   |
| Torun                 | 1         | 1.15%   |
| Targu Frumos          | 1         | 1.15%   |
| Tarakan               | 1         | 1.15%   |
| Sunnyvale             | 1         | 1.15%   |
| St Petersburg         | 1         | 1.15%   |
| Sofia                 | 1         | 1.15%   |
| Singapore             | 1         | 1.15%   |
| Siegen                | 1         | 1.15%   |
| Shirakuni             | 1         | 1.15%   |
| Sétif                | 1         | 1.15%   |
| Seelze                | 1         | 1.15%   |
| Sao Paulo             | 1         | 1.15%   |
| Sao Bernardo do Campo | 1         | 1.15%   |
| Santo Domingo Este    | 1         | 1.15%   |
| Santiago              | 1         | 1.15%   |
| Saint-Gilles          | 1         | 1.15%   |
| Renton                | 1         | 1.15%   |
| Recife                | 1         | 1.15%   |
| Queens                | 1         | 1.15%   |
| Quedlinburg           | 1         | 1.15%   |
| Puteaux               | 1         | 1.15%   |
| Puebla City           | 1         | 1.15%   |
| Praia                 | 1         | 1.15%   |
| Postojna              | 1         | 1.15%   |
| Pau                   | 1         | 1.15%   |
| Ostrava               | 1         | 1.15%   |
| Orvault               | 1         | 1.15%   |
| Nuremberg             | 1         | 1.15%   |
| Monza                 | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 25        | 29     | 24.04%  |
| Unknown                        | 9         | 9      | 8.65%   |
| Toshiba                        | 8         | 11     | 7.69%   |
| Crucial                        | 7         | 10     | 6.73%   |
| SK hynix                       | 6         | 6      | 5.77%   |
| Seagate                        | 6         | 6      | 5.77%   |
| WDC                            | 5         | 6      | 4.81%   |
| Micron Technology              | 5         | 5      | 4.81%   |
| Kingston                       | 4         | 4      | 3.85%   |
| Intel                          | 3         | 3      | 2.88%   |
| SPCC                           | 2         | 2      | 1.92%   |
| SanDisk                        | 2         | 2      | 1.92%   |
| JMicron Technology             | 2         | 2      | 1.92%   |
| China                          | 2         | 3      | 1.92%   |
| Apple                          | 2         | 2      | 1.92%   |
| A-DATA Technology              | 2         | 3      | 1.92%   |
| YMTC                           | 1         | 1      | 0.96%   |
| VISIPRO                        | 1         | 1      | 0.96%   |
| Union Memory                   | 1         | 1      | 0.96%   |
| TO Exter                       | 1         | 1      | 0.96%   |
| Solid State Storage Technology | 1         | 1      | 0.96%   |
| Realtek Semiconductor          | 1         | 1      | 0.96%   |
| Phison Electronics             | 1         | 1      | 0.96%   |
| OWC                            | 1         | 1      | 0.96%   |
| Netac                          | 1         | 1      | 0.96%   |
| KIOXIA                         | 1         | 1      | 0.96%   |
| HGST                           | 1         | 1      | 0.96%   |
| Hewlett-Packard                | 1         | 1      | 0.96%   |
| Corsair                        | 1         | 2      | 0.96%   |
| Unknown                        | 1         | 1      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4         | 3.77%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.89%   |
| Unknown SD64G  64GB                                 | 2         | 1.89%   |
| Unknown MMC Card  64GB                              | 2         | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.89%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 1.89%   |
| Samsung SSD 980 500GB                               | 2         | 1.89%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 1.89%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 1.89%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.89%   |
| YMTC PC005 1TB                                      | 1         | 0.94%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.94%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 0.94%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.94%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 0.94%   |
| VISIPRO SSD 256GB                                   | 1         | 0.94%   |
| Unknown SL128  128GB                                | 1         | 0.94%   |
| Unknown SA16G  16GB                                 | 1         | 0.94%   |
| Unknown NCard  4GB                                  | 1         | 0.94%   |
| Unknown MMC128  128GB                               | 1         | 0.94%   |
| Unknown MMC Card  128GB                             | 1         | 0.94%   |
| Union Memory RTOTJ128VGD2EYX 128GB                  | 1         | 0.94%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 0.94%   |
| Toshiba TR150 480GB SSD                             | 1         | 0.94%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 0.94%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.94%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 0.94%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.94%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 0.94%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 0.94%   |
| TO Exter nal USB 3.0 120GB                          | 1         | 0.94%   |
| SPCC Solid State Disk 120GB                         | 1         | 0.94%   |
| SPCC Solid State Disk 1024GB                        | 1         | 0.94%   |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 0.94%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 0.94%   |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB             | 1         | 0.94%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.94%   |
| SK hynix HCG8e  64GB                                | 1         | 0.94%   |
| SK hynix HBG4e  32GB                                | 1         | 0.94%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 0.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 42.86%  |
| WDC                 | 3         | 3      | 21.43%  |
| Toshiba             | 3         | 3      | 21.43%  |
| Samsung Electronics | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 20.51%  |
| Crucial             | 7         | 10     | 17.95%  |
| Micron Technology   | 3         | 3      | 7.69%   |
| SPCC                | 2         | 2      | 5.13%   |
| SanDisk             | 2         | 2      | 5.13%   |
| Kingston            | 2         | 2      | 5.13%   |
| China               | 2         | 3      | 5.13%   |
| Apple               | 2         | 2      | 5.13%   |
| VISIPRO             | 1         | 1      | 2.56%   |
| Union Memory        | 1         | 1      | 2.56%   |
| Toshiba             | 1         | 1      | 2.56%   |
| TO Exter            | 1         | 1      | 2.56%   |
| SK hynix            | 1         | 1      | 2.56%   |
| OWC                 | 1         | 1      | 2.56%   |
| Netac               | 1         | 1      | 2.56%   |
| JMicron Technology  | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |
| Corsair             | 1         | 2      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 38        | 45     | 38.78%  |
| SSD     | 35        | 46     | 35.71%  |
| HDD     | 14        | 14     | 14.29%  |
| MMC     | 10        | 12     | 10.2%   |
| Unknown | 1         | 1      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 58     | 47.37%  |
| NVMe | 38        | 45     | 40%     |
| MMC  | 10        | 12     | 10.53%  |
| SAS  | 2         | 3      | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 40     | 64.71%  |
| 0.51-1.0   | 14        | 16     | 27.45%  |
| 1.01-2.0   | 4         | 4      | 7.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 31.76%  |
| 101-250        | 27        | 31.76%  |
| 501-1000       | 12        | 14.12%  |
| 51-100         | 7         | 8.24%   |
| 21-50          | 4         | 4.71%   |
| 1001-2000      | 4         | 4.71%   |
| 1-20           | 2         | 2.35%   |
| More than 3000 | 1         | 1.18%   |
| 2001-3000      | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 27.59%  |
| 21-50     | 21        | 24.14%  |
| 101-250   | 18        | 20.69%  |
| 51-100    | 11        | 12.64%  |
| 251-500   | 7         | 8.05%   |
| 1001-2000 | 3         | 3.45%   |
| 501-1000  | 3         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB | 1         | 1      | 50%     |
| HGST HTS541010A9E680 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 48        | 63     | 53.93%  |
| Works    | 39        | 53     | 43.82%  |
| Malfunc  | 2         | 2      | 2.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 54        | 52.94%  |
| Samsung Electronics            | 16        | 15.69%  |
| AMD                            | 9         | 8.82%   |
| Toshiba America Info Systems   | 3         | 2.94%   |
| SK hynix                       | 3         | 2.94%   |
| SanDisk                        | 3         | 2.94%   |
| Micron Technology              | 2         | 1.96%   |
| KIOXIA                         | 2         | 1.96%   |
| Kingston Technology Company    | 2         | 1.96%   |
| ADATA Technology               | 2         | 1.96%   |
| Yangtze Memory Technologies    | 1         | 0.98%   |
| Solid State Storage Technology | 1         | 0.98%   |
| Realtek Semiconductor          | 1         | 0.98%   |
| Phison Electronics             | 1         | 0.98%   |
| Nvidia                         | 1         | 0.98%   |
| Marvell Technology Group       | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 10.38%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 9         | 8.49%   |
| Samsung NVMe SSD Controller 980                                              | 6         | 5.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 5         | 4.72%   |
| Intel Volume Management Device NVMe RAID Controller                          | 5         | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 3.77%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 3.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 3.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.83%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 2.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 2         | 1.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 1.89%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 1.89%   |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.94%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.94%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.94%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 0.94%   |
| SK hynix PC601 NVMe Solid State Drive                                        | 1         | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 0.94%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.94%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.94%   |
| Phison E8 PCIe3 NVMe Controller                                              | 1         | 0.94%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.94%   |
| Micron 2400 NVMe SSD (DRAM-less)                                             | 1         | 0.94%   |
| Micron 2300 NVMe SSD [Santana]                                               | 1         | 0.94%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 0.94%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.94%   |
| Kingston Company NVMe Controller                                             | 1         | 0.94%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 1         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 58        | 56.31%  |
| NVMe | 37        | 35.92%  |
| RAID | 7         | 6.8%    |
| IDE  | 1         | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 84.71%  |
| AMD    | 13        | 15.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 4.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 3.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 3.53%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 2.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.35%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.35%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.35%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.35%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.35%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.35%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.35%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 2.35%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.18%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.18%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.18%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.18%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.18%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.18%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.18%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.18%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.18%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.18%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.18%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 1         | 1.18%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 22        | 25.88%  |
| Intel Core i7        | 16        | 18.82%  |
| Other                | 14        | 16.47%  |
| Intel Core i3        | 6         | 7.06%   |
| AMD Ryzen 7          | 6         | 7.06%   |
| Intel Celeron        | 4         | 4.71%   |
| AMD Ryzen 5          | 4         | 4.71%   |
| Intel Atom           | 3         | 3.53%   |
| Intel Pentium Silver | 2         | 2.35%   |
| Intel Pentium        | 2         | 2.35%   |
| Intel Core 2 Duo     | 2         | 2.35%   |
| AMD A8               | 2         | 2.35%   |
| Intel Core i9        | 1         | 1.18%   |
| AMD Ryzen 3          | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 37        | 43.53%  |
| 2      | 31        | 36.47%  |
| 8      | 10        | 11.76%  |
| 6      | 5         | 5.88%   |
| 10     | 2         | 2.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 77.65%  |
| 1      | 19        | 22.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 55.68%  |
| 0x806c1    | 4         | 4.55%   |
| 0x08600106 | 4         | 4.55%   |
| 0x806ec    | 3         | 3.41%   |
| 0x706a8    | 3         | 3.41%   |
| 0x206a7    | 3         | 3.41%   |
| 0x806ea    | 2         | 2.27%   |
| 0x806d1    | 2         | 2.27%   |
| 0x406e3    | 2         | 2.27%   |
| 0x20655    | 2         | 2.27%   |
| 0x08108102 | 2         | 2.27%   |
| 0x906ea    | 1         | 1.14%   |
| 0x806eb    | 1         | 1.14%   |
| 0x506e3    | 1         | 1.14%   |
| 0x506c9    | 1         | 1.14%   |
| 0x40651    | 1         | 1.14%   |
| 0x306d4    | 1         | 1.14%   |
| 0x306c3    | 1         | 1.14%   |
| 0x30678    | 1         | 1.14%   |
| 0x106e5    | 1         | 1.14%   |
| 0x0a50000c | 1         | 1.14%   |
| 0x07030105 | 1         | 1.14%   |
| 0x07030104 | 1         | 1.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 20%     |
| Skylake       | 10        | 11.76%  |
| TigerLake     | 9         | 10.59%  |
| Zen 2         | 6         | 7.06%   |
| Unknown       | 5         | 5.88%   |
| IvyBridge     | 4         | 4.71%   |
| Haswell       | 4         | 4.71%   |
| Goldmont plus | 4         | 4.71%   |
| Silvermont    | 3         | 3.53%   |
| SandyBridge   | 3         | 3.53%   |
| IceLake       | 3         | 3.53%   |
| Broadwell     | 3         | 3.53%   |
| Zen+          | 2         | 2.35%   |
| Zen 3         | 2         | 2.35%   |
| Westmere      | 2         | 2.35%   |
| Puma          | 2         | 2.35%   |
| Penryn        | 2         | 2.35%   |
| CometLake     | 2         | 2.35%   |
| Nehalem       | 1         | 1.18%   |
| Goldmont      | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 65.71%  |
| Nvidia | 21        | 20%     |
| AMD    | 15        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 8.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 7.41%   |
| Intel UHD Graphics 620                                                    | 6         | 5.56%   |
| AMD Renoir                                                                | 6         | 5.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 3.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.7%    |
| Intel HD Graphics 5500                                                    | 3         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.78%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.85%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.85%   |
| Intel HD Graphics 620                                                     | 2         | 1.85%   |
| Intel HD Graphics 530                                                     | 2         | 1.85%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.85%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.93%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.93%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.93%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.93%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.93%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.93%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.93%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 58.82%  |
| Intel + Nvidia | 16        | 18.82%  |
| 1 x AMD        | 8         | 9.41%   |
| 2 x AMD        | 3         | 3.53%   |
| 1 x Nvidia     | 3         | 3.53%   |
| Intel + AMD    | 2         | 2.35%   |
| AMD + Nvidia   | 2         | 2.35%   |
| Other          | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 72        | 84.71%  |
| Proprietary | 12        | 14.12%  |
| Unknown     | 1         | 1.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 84.71%  |
| 1.01-2.0   | 4         | 4.71%   |
| 0.01-0.5   | 4         | 4.71%   |
| 7.01-8.0   | 2         | 2.35%   |
| 0.51-1.0   | 2         | 2.35%   |
| 3.01-4.0   | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 22        | 21.78%  |
| Chimei Innolux          | 21        | 20.79%  |
| Samsung Electronics     | 11        | 10.89%  |
| AU Optronics            | 11        | 10.89%  |
| LG Display              | 8         | 7.92%   |
| Sharp                   | 4         | 3.96%   |
| Goldstar                | 4         | 3.96%   |
| Apple                   | 4         | 3.96%   |
| Philips                 | 2         | 1.98%   |
| Lenovo                  | 2         | 1.98%   |
| Unknown (AAA)           | 1         | 0.99%   |
| TMX                     | 1         | 0.99%   |
| PANDA                   | 1         | 0.99%   |
| MStar                   | 1         | 0.99%   |
| KDC                     | 1         | 0.99%   |
| IBM                     | 1         | 0.99%   |
| HKC                     | 1         | 0.99%   |
| Daewoo                  | 1         | 0.99%   |
| Chi Mei Optoelectronics | 1         | 0.99%   |
| BenQ                    | 1         | 0.99%   |
| AOC                     | 1         | 0.99%   |
| Acer                    | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.98%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1         | 0.99%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch               | 1         | 0.99%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.99%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.99%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.99%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 0.99%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 700x390mm 31.5-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.99%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch               | 1         | 0.99%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.99%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.99%   |
| MStar LCD TV MST9000 1360x768                                         | 1         | 0.99%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 0.99%   |
| Lenovo T22v-20 LEN61FB 1920x1080 476x268mm 21.5-inch                  | 1         | 0.99%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch              | 1         | 0.99%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                 | 1         | 0.99%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 1         | 0.99%   |
| HKC LCD Monitor HKC36BB 1366x768 309x174mm 14.0-inch                  | 1         | 0.99%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 0.99%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 0.99%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 0.99%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                | 1         | 0.99%   |
| Daewoo 23.6W Monitor DWE0236 1920x1080 521x293mm 23.5-inch            | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 42        | 46.67%  |
| 1366x768 (WXGA)    | 23        | 25.56%  |
| 3840x2160 (4K)     | 3         | 3.33%   |
| 2560x1440 (QHD)    | 3         | 3.33%   |
| 1920x1200 (WUXGA)  | 3         | 3.33%   |
| 1600x900 (HD+)     | 3         | 3.33%   |
| 1280x800 (WXGA)    | 3         | 3.33%   |
| 1680x1050 (WSXGA+) | 2         | 2.22%   |
| 1440x900 (WXGA+)   | 2         | 2.22%   |
| 3456x2160          | 1         | 1.11%   |
| 2880x1800          | 1         | 1.11%   |
| 2560x1600          | 1         | 1.11%   |
| 2560x1080          | 1         | 1.11%   |
| 2520x1680          | 1         | 1.11%   |
| 1360x768           | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 42        | 41.58%  |
| 13      | 20        | 19.8%   |
| 14      | 10        | 9.9%    |
| 23      | 4         | 3.96%   |
| 17      | 4         | 3.96%   |
| 27      | 3         | 2.97%   |
| 11      | 3         | 2.97%   |
| 40      | 2         | 1.98%   |
| 24      | 2         | 1.98%   |
| 21      | 2         | 1.98%   |
| 12      | 2         | 1.98%   |
| 84      | 1         | 0.99%   |
| 60      | 1         | 0.99%   |
| 34      | 1         | 0.99%   |
| 31      | 1         | 0.99%   |
| 19      | 1         | 0.99%   |
| 10      | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 61        | 60.4%   |
| 201-300     | 16        | 15.84%  |
| 501-600     | 7         | 6.93%   |
| 351-400     | 5         | 4.95%   |
| 401-500     | 4         | 3.96%   |
| 801-900     | 2         | 1.98%   |
| 601-700     | 2         | 1.98%   |
| 701-800     | 1         | 0.99%   |
| 1501-2000   | 1         | 0.99%   |
| 1001-1500   | 1         | 0.99%   |
| Unknown     | 1         | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 72        | 81.82%  |
| 16/10 | 13        | 14.77%  |
| 3/2   | 2         | 2.27%   |
| 21/9  | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 41.58%  |
| 81-90          | 24        | 23.76%  |
| 201-250        | 7         | 6.93%   |
| 71-80          | 5         | 4.95%   |
| 121-130        | 4         | 3.96%   |
| 51-60          | 3         | 2.97%   |
| 301-350        | 3         | 2.97%   |
| More than 1000 | 2         | 1.98%   |
| 61-70          | 2         | 1.98%   |
| 351-500        | 2         | 1.98%   |
| 151-200        | 2         | 1.98%   |
| 501-1000       | 2         | 1.98%   |
| 41-50          | 1         | 0.99%   |
| 91-100         | 1         | 0.99%   |
| Unknown        | 1         | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 43.56%  |
| 101-120       | 26        | 25.74%  |
| 161-240       | 12        | 11.88%  |
| 51-100        | 11        | 10.89%  |
| More than 240 | 4         | 3.96%   |
| 1-50          | 3         | 2.97%   |
| Unknown       | 1         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 77.91%  |
| 2     | 18        | 20.93%  |
| 0     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 36.09%  |
| Realtek Semiconductor | 46        | 34.59%  |
| Qualcomm Atheros      | 13        | 9.77%   |
| Broadcom              | 8         | 6.02%   |
| MediaTek              | 4         | 3.01%   |
| ASIX Electronics      | 3         | 2.26%   |
| Hewlett-Packard       | 2         | 1.5%    |
| Broadcom Limited      | 2         | 1.5%    |
| Xiaomi                | 1         | 0.75%   |
| TP-Link               | 1         | 0.75%   |
| Nvidia                | 1         | 0.75%   |
| Lenovo                | 1         | 0.75%   |
| JMicron Technology    | 1         | 0.75%   |
| Huawei Technologies   | 1         | 0.75%   |
| Fibocom               | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 26        | 16.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 5.63%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 5%      |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 3.75%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.13%   |
| Intel Wireless 8260                                                     | 4         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.88%   |
| Intel Ethernet Connection I219-V                                        | 3         | 1.88%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.25%   |
| Intel Wireless 7265                                                     | 2         | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.63%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 54.02%  |
| Realtek Semiconductor | 13        | 14.94%  |
| Qualcomm Atheros      | 11        | 12.64%  |
| Broadcom              | 8         | 9.2%    |
| MediaTek              | 4         | 4.6%    |
| TP-Link               | 1         | 1.15%   |
| Hewlett-Packard       | 1         | 1.15%   |
| Fibocom               | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 8         | 9.2%    |
| Intel Wi-Fi 6 AX200                                                     | 7         | 8.05%   |
| Intel Wireless 8265 / 8275                                              | 6         | 6.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 5.75%   |
| Intel Wireless 8260                                                     | 4         | 4.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 4.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 4.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 2.3%    |
| Intel Wireless 7265                                                     | 2         | 2.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.3%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.15%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.15%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.15%   |
| Intel Wireless 7260                                                     | 1         | 1.15%   |
| Intel Wireless 3165                                                     | 1         | 1.15%   |
| Intel Wireless 3160                                                     | 1         | 1.15%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.15%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.15%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.15%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 60%     |
| Intel                 | 15        | 21.43%  |
| ASIX Electronics      | 3         | 4.29%   |
| Qualcomm Atheros      | 2         | 2.86%   |
| Broadcom              | 2         | 2.86%   |
| Xiaomi                | 1         | 1.43%   |
| Nvidia                | 1         | 1.43%   |
| Lenovo                | 1         | 1.43%   |
| JMicron Technology    | 1         | 1.43%   |
| Hewlett-Packard       | 1         | 1.43%   |
| Broadcom Limited      | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 36.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 8.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 5.56%   |
| Intel Ethernet Connection I219-V                                  | 3         | 4.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.39%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.39%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.39%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.39%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.39%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.39%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 55.33%  |
| Ethernet | 66        | 44%     |
| Modem    | 1         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 80.46%  |
| Ethernet | 17        | 19.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 69.41%  |
| 1     | 22        | 25.88%  |
| 0     | 4         | 4.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 64.77%  |
| Yes  | 31        | 35.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 56.76%  |
| Realtek Semiconductor           | 7         | 9.46%   |
| Qualcomm Atheros Communications | 7         | 9.46%   |
| Broadcom                        | 5         | 6.76%   |
| Apple                           | 4         | 5.41%   |
| IMC Networks                    | 3         | 4.05%   |
| Dell                            | 2         | 2.7%    |
| Smart Modular Technologies      | 1         | 1.35%   |
| Realtek                         | 1         | 1.35%   |
| MediaTek                        | 1         | 1.35%   |
| Foxconn International           | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 15        | 20.27%  |
| Intel AX201 Bluetooth                              | 13        | 17.57%  |
| Intel AX200 Bluetooth                              | 7         | 9.46%   |
| Realtek Bluetooth Radio                            | 5         | 6.76%   |
| Qualcomm Atheros  Bluetooth Device                 | 5         | 6.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 2.7%    |
| Intel AX210 Bluetooth                              | 2         | 2.7%    |
| IMC Networks Wireless_Device                       | 2         | 2.7%    |
| Dell DW375 Bluetooth Module                        | 2         | 2.7%    |
| Apple Bluetooth USB Host Controller                | 2         | 2.7%    |
| Apple Bluetooth Host Controller                    | 2         | 2.7%    |
| Smart Modular Bluetooth Device                     | 1         | 1.35%   |
| Realtek RTL8821A Bluetooth                         | 1         | 1.35%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.35%   |
| Realtek Bluetooth Radio                            | 1         | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.35%   |
| MediaTek Wireless_Device                           | 1         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.35%   |
| Intel Bluetooth Device                             | 1         | 1.35%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 1         | 1.35%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 68        | 70.83%  |
| AMD                    | 13        | 13.54%  |
| Nvidia                 | 10        | 10.42%  |
| Plantronics            | 1         | 1.04%   |
| Logitech               | 1         | 1.04%   |
| LINE TECH INDUSTRIAL   | 1         | 1.04%   |
| DSEA A/S               | 1         | 1.04%   |
| AKAI Professional M.I. | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 16        | 13.68%  |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 9.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 7.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 7.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 3.42%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 3.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 3.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.56%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.56%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.56%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.71%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.71%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.71%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.85%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.85%   |
| Nvidia Audio device                                                        | 1         | 0.85%   |
| Logitech PRO X                                                             | 1         | 0.85%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.85%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 34.92%  |
| SK hynix            | 15        | 23.81%  |
| Kingston            | 7         | 11.11%  |
| Micron Technology   | 5         | 7.94%   |
| Elpida              | 3         | 4.76%   |
| Unknown (ABCD)      | 2         | 3.17%   |
| Ramaxel Technology  | 2         | 3.17%   |
| Unknown             | 1         | 1.59%   |
| Teikon              | 1         | 1.59%   |
| Magnum Tech         | 1         | 1.59%   |
| fef5                | 1         | 1.59%   |
| ChangXin Memory     | 1         | 1.59%   |
| A-DATA Technology   | 1         | 1.59%   |
| 8945000080AD        | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 5.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 4.48%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 2.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.99%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 2.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.49%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.49%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.49%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.49%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.49%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.49%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.49%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.49%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.49%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.49%   |
| Samsung RAM M471A2G44BM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 1.49%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.49%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.49%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.49%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 61.54%  |
| DDR3    | 12        | 23.08%  |
| LPDDR4  | 6         | 11.54%  |
| SDRAM   | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 88.46%  |
| Row Of Chips | 3         | 5.77%   |
| Unknown      | 2         | 3.85%   |
| Chip         | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 41.51%  |
| 4096  | 10        | 18.87%  |
| 16384 | 9         | 16.98%  |
| 32768 | 5         | 9.43%   |
| 2048  | 5         | 9.43%   |
| 1024  | 2         | 3.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 16        | 28.07%  |
| 2667  | 11        | 19.3%   |
| 2400  | 9         | 15.79%  |
| 1600  | 9         | 15.79%  |
| 2133  | 3         | 5.26%   |
| 1334  | 2         | 3.51%   |
| 4267  | 1         | 1.75%   |
| 4199  | 1         | 1.75%   |
| 3733  | 1         | 1.75%   |
| 3266  | 1         | 1.75%   |
| 1333  | 1         | 1.75%   |
| 1067  | 1         | 1.75%   |
| 1066  | 1         | 1.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1320 | 1         | 50%     |
| Canon LiDE 400   | 1         | 50%     |

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
| Chicony Electronics                    | 25        | 34.25%  |
| IMC Networks                           | 8         | 10.96%  |
| Realtek Semiconductor                  | 6         | 8.22%   |
| Microdia                               | 5         | 6.85%   |
| Sunplus Innovation Technology          | 4         | 5.48%   |
| Bison Electronics                      | 4         | 5.48%   |
| Syntek                                 | 3         | 4.11%   |
| Luxvisions Innotech Limited            | 3         | 4.11%   |
| Apple                                  | 3         | 4.11%   |
| Acer                                   | 3         | 4.11%   |
| Quanta                                 | 2         | 2.74%   |
| Unknown (3730304231385031345945)       | 1         | 1.37%   |
| Samsung Electronics                    | 1         | 1.37%   |
| Polycom                                | 1         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.37%   |
| Alcor Micro                            | 1         | 1.37%   |
| 8SSC21D67422V1SR28902JL                | 1         | 1.37%   |
| Unknown                                | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HP HD Camera                          | 4         | 5.48%   |
| Microdia Integrated_Webcam_HD                 | 3         | 4.11%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 4.11%   |
| IMC Networks Integrated Camera                | 3         | 4.11%   |
| Chicony USB2.0 Camera                         | 3         | 4.11%   |
| Chicony Integrated Camera                     | 3         | 4.11%   |
| Chicony HD Webcam                             | 3         | 4.11%   |
| Bison SunplusIT Integrated Camera             | 3         | 4.11%   |
| Syntek Integrated Camera                      | 2         | 2.74%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.74%   |
| Realtek Integrated_Webcam_HD                  | 2         | 2.74%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 2.74%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 2.74%   |
| Chicony Integrated IR Camera                  | 2         | 2.74%   |
| Apple FaceTime HD Camera                      | 2         | 2.74%   |
| Unknown (3730304231385031345945) USB Camera   | 1         | 1.37%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.37%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.37%   |
| Sunplus HD WebCam                             | 1         | 1.37%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 1.37%   |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 1.37%   |
| Realtek Lenovo EasyCamera                     | 1         | 1.37%   |
| Realtek Integrated Webcam HD                  | 1         | 1.37%   |
| Realtek Integrated Webcam                     | 1         | 1.37%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 1.37%   |
| Quanta HP Wide Vision HD Camera               | 1         | 1.37%   |
| Polycom Poly Studio P5 webcam                 | 1         | 1.37%   |
| Microdia Lenovo EasyCamera                    | 1         | 1.37%   |
| Microdia Integrated Webcam HD                 | 1         | 1.37%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 1.37%   |
| IMC Networks Integrated RGB Camera            | 1         | 1.37%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 1         | 1.37%   |
| Chicony USB2.0 UVC WebCam                     | 1         | 1.37%   |
| Chicony USB2.0 0.3M UVC WebCam                | 1         | 1.37%   |
| Chicony Lenovo EasyCamera                     | 1         | 1.37%   |
| Chicony HP Truevision HD camera               | 1         | 1.37%   |
| Chicony HP Truevision HD                      | 1         | 1.37%   |
| Chicony HP Integrated Webcam                  | 1         | 1.37%   |
| Chicony EasyCamera                            | 1         | 1.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 42.86%  |
| Validity Sensors           | 5         | 23.81%  |
| Shenzhen Goodix Technology | 5         | 23.81%  |
| LighTuning Technology      | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 4.76%   |
| Synaptics UWP WBDI Device                                 | 1         | 4.76%   |
| Synaptics UWP WBDI                                        | 1         | 4.76%   |
| Synaptics  WBDI                                           | 1         | 4.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 4.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 4.76%   |
| Shenzhen Goodix FingerPrint                               | 1         | 4.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                     | 1         | 4.76%   |
| Unknown                                                   | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 60%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 49        | 56.98%  |
| 1     | 25        | 29.07%  |
| 2     | 9         | 10.47%  |
| 3     | 2         | 2.33%   |
| 7     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 40%     |
| Net/wireless             | 5         | 10%     |
| Graphics card            | 5         | 10%     |
| Chipcard                 | 5         | 10%     |
| Communication controller | 4         | 8%      |
| Multimedia controller    | 3         | 6%      |
| Camera                   | 3         | 6%      |
| Sound                    | 2         | 4%      |
| Card reader              | 2         | 4%      |
| Bluetooth                | 1         | 2%      |


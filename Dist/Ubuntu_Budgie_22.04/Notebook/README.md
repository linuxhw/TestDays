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

Total: 109

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-27-generic     | 7         | 8.05%   |
| 5.15.0-50-generic     | 5         | 5.75%   |
| 5.15.0-48-generic     | 5         | 5.75%   |
| 5.19.0-46-generic     | 4         | 4.6%    |
| 5.15.0-52-generic     | 4         | 4.6%    |
| 5.19.0-41-generic     | 3         | 3.45%   |
| 5.19.0-35-generic     | 3         | 3.45%   |
| 5.15.0-53-generic     | 3         | 3.45%   |
| 5.15.0-40-generic     | 3         | 3.45%   |
| 5.15.0-39-generic     | 3         | 3.45%   |
| 5.15.0-30-generic     | 3         | 3.45%   |
| 6.2.0-10007-tuxedo    | 2         | 2.3%    |
| 5.19.0-42-generic     | 2         | 2.3%    |
| 5.19.0-38-generic     | 2         | 2.3%    |
| 5.15.0-67-generic     | 2         | 2.3%    |
| 5.15.0-58-generic     | 2         | 2.3%    |
| 5.15.0-56-generic     | 2         | 2.3%    |
| 5.15.0-47-generic     | 2         | 2.3%    |
| 5.15.0-46-generic     | 2         | 2.3%    |
| 5.15.0-33-generic     | 2         | 2.3%    |
| 5.15.0-25-generic     | 2         | 2.3%    |
| 6.3.1-060301-generic  | 1         | 1.15%   |
| 6.1.0-060100-generic  | 1         | 1.15%   |
| 5.19.0-45-generic     | 1         | 1.15%   |
| 5.19.0-40-generic     | 1         | 1.15%   |
| 5.19.0-32-generic     | 1         | 1.15%   |
| 5.19.0-051900-generic | 1         | 1.15%   |
| 5.15.0-76-lowlatency  | 1         | 1.15%   |
| 5.15.0-76-generic     | 1         | 1.15%   |
| 5.15.0-69-generic     | 1         | 1.15%   |
| 5.15.0-60-generic     | 1         | 1.15%   |
| 5.15.0-57-generic     | 1         | 1.15%   |
| 5.15.0-52-lowlatency  | 1         | 1.15%   |
| 5.15.0-43-generic     | 1         | 1.15%   |
| 5.15.0-41-generic     | 1         | 1.15%   |
| 5.15.0-35-generic     | 1         | 1.15%   |
| 5.15.0-18-generic     | 1         | 1.15%   |
| 5.15.0-10075-tuxedo   | 1         | 1.15%   |
| 5.15.0-10058-tuxedo   | 1         | 1.15%   |
| 5.15.0-10056-tuxedo   | 1         | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 60        | 72.29%  |
| 5.19.0  | 17        | 20.48%  |
| 6.2.0   | 2         | 2.41%   |
| 5.13.0  | 2         | 2.41%   |
| 6.3.1   | 1         | 1.2%    |
| 6.1.0   | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 60        | 72.29%  |
| 5.19    | 17        | 20.48%  |
| 6.2     | 2         | 2.41%   |
| 5.13    | 2         | 2.41%   |
| 6.3     | 1         | 1.2%    |
| 6.1     | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 75        | 93.75%  |
| GNOME  | 5         | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 77        | 96.25%  |
| Wayland | 3         | 3.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 58        | 72.5%   |
| Unknown | 13        | 16.25%  |
| GDM3    | 9         | 11.25%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 27        | 33.75%  |
| de_DE | 11        | 13.75%  |
| fr_FR | 10        | 12.5%   |
| pt_BR | 5         | 6.25%   |
| en_GB | 4         | 5%      |
| it_IT | 3         | 3.75%   |
| ru_RU | 2         | 2.5%    |
| hu_HU | 2         | 2.5%    |
| fr_BE | 2         | 2.5%    |
| en_IE | 2         | 2.5%    |
| en_CA | 2         | 2.5%    |
| pl_PL | 1         | 1.25%   |
| mt_MT | 1         | 1.25%   |
| ja_JP | 1         | 1.25%   |
| es_PE | 1         | 1.25%   |
| es_MX | 1         | 1.25%   |
| es_ES | 1         | 1.25%   |
| es_EC | 1         | 1.25%   |
| es_CL | 1         | 1.25%   |
| cs_CZ | 1         | 1.25%   |
| C     | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 46        | 57.5%   |
| EFI  | 34        | 42.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 89.02%  |
| Tmpfs   | 3         | 3.66%   |
| Overlay | 3         | 3.66%   |
| Zfs     | 1         | 1.22%   |
| Xfs     | 1         | 1.22%   |
| Btrfs   | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 52        | 65%     |
| Unknown | 23        | 28.75%  |
| MBR     | 5         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 86.25%  |
| Yes       | 11        | 13.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 70.37%  |
| Yes       | 24        | 29.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 20        | 25%     |
| Dell                   | 12        | 15%     |
| Hewlett-Packard        | 11        | 13.75%  |
| ASUSTek Computer       | 10        | 12.5%   |
| TUXEDO                 | 8         | 10%     |
| Apple                  | 4         | 5%      |
| MSI                    | 3         | 3.75%   |
| Google                 | 2         | 2.5%    |
| Toshiba                | 1         | 1.25%   |
| Timi                   | 1         | 1.25%   |
| Razer                  | 1         | 1.25%   |
| HUAWEI                 | 1         | 1.25%   |
| Digibras               | 1         | 1.25%   |
| Chuwi                  | 1         | 1.25%   |
| BANGHO                 | 1         | 1.25%   |
| AXIOO                  | 1         | 1.25%   |
| Avell High Performance | 1         | 1.25%   |
| Acer                   | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                                   | 2         | 2.5%    |
| HP EliteBook 840 G3                                  | 2         | 2.5%    |
| TUXEDO Pulse 15 Gen1                                 | 1         | 1.25%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.25%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.25%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 1.25%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.25%   |
| TUXEDO Book XP1511                                   | 1         | 1.25%   |
| TUXEDO Book BA1510                                   | 1         | 1.25%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.25%   |
| Toshiba Satellite A505                               | 1         | 1.25%   |
| Timi TM1604                                          | 1         | 1.25%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.25%   |
| MSI Modern 15 A10M                                   | 1         | 1.25%   |
| MSI GL62 6QF                                         | 1         | 1.25%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.25%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.25%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 1.25%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.25%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.25%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.25%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.25%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 1.25%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.25%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.25%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.25%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.25%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.25%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.25%   |
| Lenovo IdeaPad 520-15IKB 81BF                        | 1         | 1.25%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.25%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.25%   |
| Lenovo IdeaPad 110-15ISK 80UD                        | 1         | 1.25%   |
| Lenovo G500 20236                                    | 1         | 1.25%   |
| HUAWEI HKD-WXX                                       | 1         | 1.25%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.25%   |
| HP ProBook 450 G7                                    | 1         | 1.25%   |
| HP ProBook 445 G7                                    | 1         | 1.25%   |
| HP Pavilion Gaming Notebook                          | 1         | 1.25%   |
| HP Pavilion g6                                       | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 8         | 10%     |
| Lenovo IdeaPad              | 7         | 8.75%   |
| Dell Latitude               | 4         | 5%      |
| Dell Inspiron               | 4         | 5%      |
| TUXEDO Book                 | 3         | 3.75%   |
| HP ProBook                  | 3         | 3.75%   |
| HP EliteBook                | 3         | 3.75%   |
| ASUS VivoBook               | 3         | 3.75%   |
| TUXEDO InfinityBook         | 2         | 2.5%    |
| Lenovo G50-45               | 2         | 2.5%    |
| HP Pavilion                 | 2         | 2.5%    |
| Dell XPS                    | 2         | 2.5%    |
| TUXEDO Pulse                | 1         | 1.25%   |
| TUXEDO Polaris              | 1         | 1.25%   |
| TUXEDO Aura                 | 1         | 1.25%   |
| Toshiba Satellite           | 1         | 1.25%   |
| Timi TM1604                 | 1         | 1.25%   |
| Razer Blade                 | 1         | 1.25%   |
| MSI Modern                  | 1         | 1.25%   |
| MSI GL62                    | 1         | 1.25%   |
| MSI Alpha                   | 1         | 1.25%   |
| Lenovo V15                  | 1         | 1.25%   |
| Lenovo Legion               | 1         | 1.25%   |
| Lenovo G500                 | 1         | 1.25%   |
| HUAWEI HKD-WXX              | 1         | 1.25%   |
| HP ENVY                     | 1         | 1.25%   |
| HP ElitePad                 | 1         | 1.25%   |
| HP Bloog                    | 1         | 1.25%   |
| Google Rabbid               | 1         | 1.25%   |
| Google Boten                | 1         | 1.25%   |
| Digibras NH4CU03            | 1         | 1.25%   |
| Dell Vostro                 | 1         | 1.25%   |
| Dell Precision              | 1         | 1.25%   |
| Chuwi HeroBook              | 1         | 1.25%   |
| BANGHO BES                  | 1         | 1.25%   |
| AXIOO Slimbook              | 1         | 1.25%   |
| Avell High Performance B.ON | 1         | 1.25%   |
| ASUS ZenBook                | 1         | 1.25%   |
| ASUS X555LAB                | 1         | 1.25%   |
| ASUS X205TA                 | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 14        | 17.5%   |
| 2020 | 13        | 16.25%  |
| 2016 | 8         | 10%     |
| 2014 | 8         | 10%     |
| 2019 | 6         | 7.5%    |
| 2018 | 6         | 7.5%    |
| 2017 | 4         | 5%      |
| 2013 | 4         | 5%      |
| 2022 | 3         | 3.75%   |
| 2015 | 3         | 3.75%   |
| 2011 | 3         | 3.75%   |
| 2009 | 3         | 3.75%   |
| 2012 | 2         | 2.5%    |
| 2010 | 2         | 2.5%    |
| 2008 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 73        | 91.25%  |
| Enabled  | 7         | 8.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 96.25%  |
| Yes  | 3         | 3.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 34.57%  |
| 16.01-24.0  | 21        | 25.93%  |
| 3.01-4.0    | 11        | 13.58%  |
| 32.01-64.0  | 8         | 9.88%   |
| 8.01-16.0   | 8         | 9.88%   |
| 64.01-256.0 | 4         | 4.94%   |
| 1.01-2.0    | 1         | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 28        | 33.33%  |
| 1.01-2.0   | 20        | 23.81%  |
| 4.01-8.0   | 16        | 19.05%  |
| 3.01-4.0   | 10        | 11.9%   |
| 8.01-16.0  | 7         | 8.33%   |
| 24.01-32.0 | 2         | 2.38%   |
| 16.01-24.0 | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 76.83%  |
| 2      | 17        | 20.73%  |
| 3      | 2         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 80%     |
| Yes       | 16        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 76.54%  |
| No        | 19        | 23.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 97.5%   |
| No        | 2         | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 88.75%  |
| No        | 9         | 11.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 13        | 16.25%  |
| USA                | 12        | 15%     |
| France             | 10        | 12.5%   |
| Brazil             | 5         | 6.25%   |
| Poland             | 3         | 3.75%   |
| Italy              | 3         | 3.75%   |
| UK                 | 2         | 2.5%    |
| Ireland            | 2         | 2.5%    |
| Hungary            | 2         | 2.5%    |
| Canada             | 2         | 2.5%    |
| Belgium            | 2         | 2.5%    |
| Austria            | 2         | 2.5%    |
| Sweden             | 1         | 1.25%   |
| Spain              | 1         | 1.25%   |
| Slovenia           | 1         | 1.25%   |
| Russia             | 1         | 1.25%   |
| Romania            | 1         | 1.25%   |
| Peru               | 1         | 1.25%   |
| Mexico             | 1         | 1.25%   |
| Malta              | 1         | 1.25%   |
| Japan              | 1         | 1.25%   |
| Indonesia          | 1         | 1.25%   |
| Greece             | 1         | 1.25%   |
| Ghana              | 1         | 1.25%   |
| Ecuador            | 1         | 1.25%   |
| Dominican Republic | 1         | 1.25%   |
| Czechia            | 1         | 1.25%   |
| Cuba               | 1         | 1.25%   |
| Chile              | 1         | 1.25%   |
| Cabo Verde         | 1         | 1.25%   |
| Bulgaria           | 1         | 1.25%   |
| Belarus            | 1         | 1.25%   |
| Argentina          | 1         | 1.25%   |
| Algeria            | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 2.44%   |
| Vienna                | 2         | 2.44%   |
| Frankfurt am Main     | 2         | 2.44%   |
| Dublin                | 2         | 2.44%   |
| Budapest              | 2         | 2.44%   |
| Berlin                | 2         | 2.44%   |
| Wertheim am Main      | 1         | 1.22%   |
| Weisswasser           | 1         | 1.22%   |
| Weilheim              | 1         | 1.22%   |
| Washington            | 1         | 1.22%   |
| Victoria              | 1         | 1.22%   |
| Torun                 | 1         | 1.22%   |
| Targu Frumos          | 1         | 1.22%   |
| Tarakan               | 1         | 1.22%   |
| Sunnyvale             | 1         | 1.22%   |
| St Petersburg         | 1         | 1.22%   |
| Sofia                 | 1         | 1.22%   |
| Siegen                | 1         | 1.22%   |
| Shirakuni             | 1         | 1.22%   |
| Sétif                | 1         | 1.22%   |
| Seelze                | 1         | 1.22%   |
| Sao Paulo             | 1         | 1.22%   |
| Sao Bernardo do Campo | 1         | 1.22%   |
| Santo Domingo Este    | 1         | 1.22%   |
| Santiago              | 1         | 1.22%   |
| Saint-Gilles          | 1         | 1.22%   |
| Renton                | 1         | 1.22%   |
| Recife                | 1         | 1.22%   |
| Queens                | 1         | 1.22%   |
| Quedlinburg           | 1         | 1.22%   |
| Puebla City           | 1         | 1.22%   |
| Praia                 | 1         | 1.22%   |
| Postojna              | 1         | 1.22%   |
| Pau                   | 1         | 1.22%   |
| Ostrava               | 1         | 1.22%   |
| Orvault               | 1         | 1.22%   |
| Nuremberg             | 1         | 1.22%   |
| Monza                 | 1         | 1.22%   |
| Montesilvano Marina   | 1         | 1.22%   |
| Mishawaka             | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 23        | 26     | 23.47%  |
| Unknown                        | 8         | 8      | 8.16%   |
| Toshiba                        | 8         | 11     | 8.16%   |
| Crucial                        | 7         | 9      | 7.14%   |
| Seagate                        | 6         | 6      | 6.12%   |
| WDC                            | 5         | 6      | 5.1%    |
| Micron Technology              | 5         | 5      | 5.1%    |
| SK hynix                       | 4         | 4      | 4.08%   |
| Kingston                       | 4         | 4      | 4.08%   |
| Intel                          | 3         | 3      | 3.06%   |
| SPCC                           | 2         | 2      | 2.04%   |
| SanDisk                        | 2         | 2      | 2.04%   |
| JMicron Technology             | 2         | 2      | 2.04%   |
| China                          | 2         | 3      | 2.04%   |
| Apple                          | 2         | 2      | 2.04%   |
| YMTC                           | 1         | 1      | 1.02%   |
| VISIPRO                        | 1         | 1      | 1.02%   |
| Union Memory                   | 1         | 1      | 1.02%   |
| TO Exter                       | 1         | 1      | 1.02%   |
| Solid State Storage Technology | 1         | 1      | 1.02%   |
| Realtek Semiconductor          | 1         | 1      | 1.02%   |
| Phison Electronics             | 1         | 1      | 1.02%   |
| OWC                            | 1         | 1      | 1.02%   |
| Netac                          | 1         | 1      | 1.02%   |
| KIOXIA                         | 1         | 1      | 1.02%   |
| HGST                           | 1         | 1      | 1.02%   |
| Hewlett-Packard                | 1         | 1      | 1.02%   |
| Corsair                        | 1         | 2      | 1.02%   |
| A-DATA Technology              | 1         | 1      | 1.02%   |
| Unknown                        | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 3.03%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2.02%   |
| Unknown SD64G  64GB                                 | 2         | 2.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2.02%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 2.02%   |
| Samsung SSD 980 500GB                               | 2         | 2.02%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 2.02%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 2.02%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 2.02%   |
| YMTC PC005 1TB                                      | 1         | 1.01%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 1.01%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 1.01%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 1.01%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.01%   |
| VISIPRO SSD 256GB                                   | 1         | 1.01%   |
| Unknown SL128  128GB                                | 1         | 1.01%   |
| Unknown SA16G  16GB                                 | 1         | 1.01%   |
| Unknown NCard  4GB                                  | 1         | 1.01%   |
| Unknown MMC128  128GB                               | 1         | 1.01%   |
| Unknown MMC Card  64GB                              | 1         | 1.01%   |
| Unknown MMC Card  128GB                             | 1         | 1.01%   |
| Union Memory RTOTJ128VGD2EYX 128GB                  | 1         | 1.01%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 1.01%   |
| Toshiba TR150 480GB SSD                             | 1         | 1.01%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.01%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.01%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1.01%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.01%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 1.01%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 1.01%   |
| TO Exter nal USB 3.0 1TB                            | 1         | 1.01%   |
| SPCC Solid State Disk 120GB                         | 1         | 1.01%   |
| SPCC Solid State Disk 1024GB                        | 1         | 1.01%   |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 1.01%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 1.01%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB                | 1         | 1.01%   |
| SK hynix HCG8e  64GB                                | 1         | 1.01%   |
| SK hynix HBG4e  32GB                                | 1         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.01%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| WDC                 | 3         | 3      | 20%     |
| Toshiba             | 3         | 3      | 20%     |
| Samsung Electronics | 1         | 1      | 6.67%   |
| JMicron Technology  | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 21.62%  |
| Crucial             | 7         | 9      | 18.92%  |
| Micron Technology   | 3         | 3      | 8.11%   |
| SPCC                | 2         | 2      | 5.41%   |
| SanDisk             | 2         | 2      | 5.41%   |
| Kingston            | 2         | 2      | 5.41%   |
| China               | 2         | 3      | 5.41%   |
| Apple               | 2         | 2      | 5.41%   |
| VISIPRO             | 1         | 1      | 2.7%    |
| Union Memory        | 1         | 1      | 2.7%    |
| Toshiba             | 1         | 1      | 2.7%    |
| TO Exter            | 1         | 1      | 2.7%    |
| OWC                 | 1         | 1      | 2.7%    |
| Netac               | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| Hewlett-Packard     | 1         | 1      | 2.7%    |
| Corsair             | 1         | 2      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 34        | 40     | 36.56%  |
| SSD     | 34        | 42     | 36.56%  |
| HDD     | 15        | 15     | 16.13%  |
| MMC     | 9         | 11     | 9.68%   |
| Unknown | 1         | 1      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 55     | 49.44%  |
| NVMe | 34        | 40     | 38.2%   |
| MMC  | 9         | 11     | 10.11%  |
| SAS  | 2         | 3      | 2.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 36     | 62%     |
| 0.51-1.0   | 15        | 17     | 30%     |
| 1.01-2.0   | 4         | 4      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 33.75%  |
| 101-250        | 25        | 31.25%  |
| 501-1000       | 11        | 13.75%  |
| 51-100         | 6         | 7.5%    |
| 21-50          | 4         | 5%      |
| 1001-2000      | 4         | 5%      |
| 1-20           | 2         | 2.5%    |
| More than 3000 | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 22        | 26.83%  |
| 21-50     | 21        | 25.61%  |
| 101-250   | 17        | 20.73%  |
| 51-100    | 10        | 12.2%   |
| 251-500   | 7         | 8.54%   |
| 501-1000  | 3         | 3.66%   |
| 1001-2000 | 2         | 2.44%   |

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
| Detected | 46        | 58     | 54.76%  |
| Works    | 36        | 49     | 42.86%  |
| Malfunc  | 2         | 2      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 51        | 54.26%  |
| Samsung Electronics            | 14        | 14.89%  |
| AMD                            | 8         | 8.51%   |
| Toshiba America Info Systems   | 3         | 3.19%   |
| SanDisk                        | 3         | 3.19%   |
| SK hynix                       | 2         | 2.13%   |
| Micron Technology              | 2         | 2.13%   |
| KIOXIA                         | 2         | 2.13%   |
| Kingston Technology Company    | 2         | 2.13%   |
| Yangtze Memory Technologies    | 1         | 1.06%   |
| Solid State Storage Technology | 1         | 1.06%   |
| Realtek Semiconductor          | 1         | 1.06%   |
| Phison Electronics             | 1         | 1.06%   |
| Nvidia                         | 1         | 1.06%   |
| Marvell Technology Group       | 1         | 1.06%   |
| ADATA Technology               | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 10        | 10.2%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 8         | 8.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 5         | 5.1%    |
| Samsung NVMe SSD Controller 980                                              | 5         | 5.1%    |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 4.08%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 4.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 4.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 3.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 3.06%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 3.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 3.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 2.04%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 2.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.04%   |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 1.02%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.02%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 1.02%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 1.02%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 1.02%   |
| SK hynix PC601 NVMe Solid State Drive                                        | 1         | 1.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 1.02%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 1.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 1.02%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.02%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 1.02%   |
| Phison E8 PCIe3 NVMe Controller                                              | 1         | 1.02%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.02%   |
| Micron 2400 NVMe SSD (DRAM-less)                                             | 1         | 1.02%   |
| Micron 2300 NVMe SSD [Santana]                                               | 1         | 1.02%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 1.02%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.02%   |
| Kingston Company NVMe Controller                                             | 1         | 1.02%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 1         | 1.02%   |
| Intel SSD 660P Series                                                        | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 55        | 57.29%  |
| NVMe | 34        | 35.42%  |
| RAID | 6         | 6.25%   |
| IDE  | 1         | 1.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 86.25%  |
| AMD    | 11        | 13.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 5%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 3.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 2.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.5%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.5%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.5%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.5%    |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.5%    |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.5%    |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 2.5%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.25%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.25%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.25%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.25%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.25%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.25%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.25%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.25%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.25%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.25%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 1         | 1.25%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.25%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 21        | 26.25%  |
| Intel Core i7        | 15        | 18.75%  |
| Other                | 13        | 16.25%  |
| Intel Core i3        | 6         | 7.5%    |
| Intel Celeron        | 4         | 5%      |
| AMD Ryzen 7          | 4         | 5%      |
| AMD Ryzen 5          | 4         | 5%      |
| Intel Atom           | 3         | 3.75%   |
| Intel Pentium Silver | 2         | 2.5%    |
| Intel Pentium        | 2         | 2.5%    |
| Intel Core 2 Duo     | 2         | 2.5%    |
| AMD A8               | 2         | 2.5%    |
| Intel Core i9        | 1         | 1.25%   |
| AMD Ryzen 3          | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 36        | 45%     |
| 2      | 30        | 37.5%   |
| 8      | 8         | 10%     |
| 6      | 4         | 5%      |
| 10     | 2         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 76.25%  |
| 1      | 19        | 23.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 53.66%  |
| 0x806c1    | 4         | 4.88%   |
| 0x806ec    | 3         | 3.66%   |
| 0x706a8    | 3         | 3.66%   |
| 0x206a7    | 3         | 3.66%   |
| 0x08600106 | 3         | 3.66%   |
| 0x806ea    | 2         | 2.44%   |
| 0x806d1    | 2         | 2.44%   |
| 0x406e3    | 2         | 2.44%   |
| 0x20655    | 2         | 2.44%   |
| 0x08108102 | 2         | 2.44%   |
| 0x906ea    | 1         | 1.22%   |
| 0x806eb    | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x506c9    | 1         | 1.22%   |
| 0x40651    | 1         | 1.22%   |
| 0x306d4    | 1         | 1.22%   |
| 0x306c3    | 1         | 1.22%   |
| 0x30678    | 1         | 1.22%   |
| 0x106e5    | 1         | 1.22%   |
| 0x0a50000c | 1         | 1.22%   |
| 0x07030105 | 1         | 1.22%   |
| 0x07030104 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 20%     |
| Skylake       | 9         | 11.25%  |
| TigerLake     | 8         | 10%     |
| Unknown       | 5         | 6.25%   |
| Zen 2         | 4         | 5%      |
| IvyBridge     | 4         | 5%      |
| Haswell       | 4         | 5%      |
| Goldmont plus | 4         | 5%      |
| Silvermont    | 3         | 3.75%   |
| SandyBridge   | 3         | 3.75%   |
| IceLake       | 3         | 3.75%   |
| Broadwell     | 3         | 3.75%   |
| Zen+          | 2         | 2.5%    |
| Zen 3         | 2         | 2.5%    |
| Westmere      | 2         | 2.5%    |
| Puma          | 2         | 2.5%    |
| Penryn        | 2         | 2.5%    |
| CometLake     | 2         | 2.5%    |
| Nehalem       | 1         | 1.25%   |
| Goldmont      | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 67.35%  |
| Nvidia | 19        | 19.39%  |
| AMD    | 13        | 13.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 7.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 7         | 6.93%   |
| Intel UHD Graphics 620                                                    | 6         | 5.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 3.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 3.96%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.96%   |
| AMD Renoir                                                                | 4         | 3.96%   |
| Intel HD Graphics 5500                                                    | 3         | 2.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.97%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.98%   |
| Intel HD Graphics 620                                                     | 2         | 1.98%   |
| Intel HD Graphics 530                                                     | 2         | 1.98%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.98%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.98%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.98%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.99%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.99%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.99%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.99%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.99%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.99%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.99%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.99%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.99%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.99%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 0.99%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 60%     |
| Intel + Nvidia | 15        | 18.75%  |
| 1 x AMD        | 7         | 8.75%   |
| 2 x AMD        | 3         | 3.75%   |
| 1 x Nvidia     | 3         | 3.75%   |
| Intel + AMD    | 2         | 2.5%    |
| Other          | 1         | 1.25%   |
| AMD + Nvidia   | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 68        | 85%     |
| Proprietary | 11        | 13.75%  |
| Unknown     | 1         | 1.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 86.25%  |
| 1.01-2.0   | 4         | 5%      |
| 0.01-0.5   | 3         | 3.75%   |
| 7.01-8.0   | 2         | 2.5%    |
| 0.51-1.0   | 2         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 21        | 22.34%  |
| Chimei Innolux          | 20        | 21.28%  |
| Samsung Electronics     | 11        | 11.7%   |
| AU Optronics            | 11        | 11.7%   |
| LG Display              | 7         | 7.45%   |
| Goldstar                | 4         | 4.26%   |
| Apple                   | 4         | 4.26%   |
| Sharp                   | 3         | 3.19%   |
| Lenovo                  | 2         | 2.13%   |
| Unknown (AAA)           | 1         | 1.06%   |
| TMX                     | 1         | 1.06%   |
| Philips                 | 1         | 1.06%   |
| MStar                   | 1         | 1.06%   |
| KDC                     | 1         | 1.06%   |
| IBM                     | 1         | 1.06%   |
| HKC                     | 1         | 1.06%   |
| Daewoo                  | 1         | 1.06%   |
| Chi Mei Optoelectronics | 1         | 1.06%   |
| BenQ                    | 1         | 1.06%   |
| AOC                     | 1         | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 2.13%   |
| Unknown (AAA) LCDTV AAA3393 1920x1080 520x290mm 23.4-inch              | 1         | 1.06%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                | 1         | 1.06%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 1.06%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 1.06%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 1.06%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 1.06%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch    | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 1.06%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 1.06%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 1.06%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch            | 1         | 1.06%   |
| Lenovo T22v-20 LEN61FB 1920x1080 476x268mm 21.5-inch                   | 1         | 1.06%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch               | 1         | 1.06%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                  | 1         | 1.06%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                  | 1         | 1.06%   |
| HKC LCD Monitor HKC36BB 1366x768 309x174mm 14.0-inch                   | 1         | 1.06%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 1         | 1.06%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 1         | 1.06%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 1         | 1.06%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                 | 1         | 1.06%   |
| Daewoo 23.6 monitor DWE0236 1920x1080 521x293mm 23.5-inch              | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch       | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 1         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 43.53%  |
| 1366x768 (WXGA)    | 23        | 27.06%  |
| 3840x2160 (4K)     | 3         | 3.53%   |
| 2560x1440 (QHD)    | 3         | 3.53%   |
| 1920x1200 (WUXGA)  | 3         | 3.53%   |
| 1600x900 (HD+)     | 3         | 3.53%   |
| 1280x800 (WXGA)    | 3         | 3.53%   |
| 1680x1050 (WSXGA+) | 2         | 2.35%   |
| 1440x900 (WXGA+)   | 2         | 2.35%   |
| 3456x2160          | 1         | 1.18%   |
| 2880x1800          | 1         | 1.18%   |
| 2560x1600          | 1         | 1.18%   |
| 2560x1080          | 1         | 1.18%   |
| 2520x1680          | 1         | 1.18%   |
| 1360x768           | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 39        | 41.49%  |
| 13      | 19        | 20.21%  |
| 14      | 10        | 10.64%  |
| 17      | 4         | 4.26%   |
| 27      | 3         | 3.19%   |
| 23      | 3         | 3.19%   |
| 11      | 3         | 3.19%   |
| 40      | 2         | 2.13%   |
| 24      | 2         | 2.13%   |
| 21      | 2         | 2.13%   |
| 84      | 1         | 1.06%   |
| 60      | 1         | 1.06%   |
| 34      | 1         | 1.06%   |
| 31      | 1         | 1.06%   |
| 12      | 1         | 1.06%   |
| 10      | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 60.64%  |
| 201-300     | 15        | 15.96%  |
| 501-600     | 6         | 6.38%   |
| 351-400     | 5         | 5.32%   |
| 401-500     | 3         | 3.19%   |
| 801-900     | 2         | 2.13%   |
| 601-700     | 2         | 2.13%   |
| 701-800     | 1         | 1.06%   |
| 1501-2000   | 1         | 1.06%   |
| 1001-1500   | 1         | 1.06%   |
| Unknown     | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 67        | 81.71%  |
| 16/10 | 12        | 14.63%  |
| 3/2   | 2         | 2.44%   |
| 21/9  | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 41.49%  |
| 81-90          | 23        | 24.47%  |
| 201-250        | 6         | 6.38%   |
| 71-80          | 5         | 5.32%   |
| 121-130        | 4         | 4.26%   |
| 51-60          | 3         | 3.19%   |
| 301-350        | 3         | 3.19%   |
| More than 1000 | 2         | 2.13%   |
| 351-500        | 2         | 2.13%   |
| 501-1000       | 2         | 2.13%   |
| 61-70          | 1         | 1.06%   |
| 41-50          | 1         | 1.06%   |
| 151-200        | 1         | 1.06%   |
| 91-100         | 1         | 1.06%   |
| Unknown        | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 42.55%  |
| 101-120       | 25        | 26.6%   |
| 161-240       | 11        | 11.7%   |
| 51-100        | 10        | 10.64%  |
| More than 240 | 4         | 4.26%   |
| 1-50          | 3         | 3.19%   |
| Unknown       | 1         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 79.01%  |
| 2     | 16        | 19.75%  |
| 0     | 1         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 35.2%   |
| Realtek Semiconductor | 43        | 34.4%   |
| Qualcomm Atheros      | 13        | 10.4%   |
| Broadcom              | 8         | 6.4%    |
| MediaTek              | 3         | 2.4%    |
| ASIX Electronics      | 3         | 2.4%    |
| Hewlett-Packard       | 2         | 1.6%    |
| Broadcom Limited      | 2         | 1.6%    |
| Xiaomi                | 1         | 0.8%    |
| TP-Link               | 1         | 0.8%    |
| Nvidia                | 1         | 0.8%    |
| Lenovo                | 1         | 0.8%    |
| JMicron Technology    | 1         | 0.8%    |
| Huawei Technologies   | 1         | 0.8%    |
| Fibocom               | 1         | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 23        | 15.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 5.96%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 4.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 3.97%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.31%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.31%   |
| Intel Wireless 8260                                                     | 4         | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.99%   |
| Intel Ethernet Connection I219-V                                        | 3         | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.99%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.32%   |
| Intel Wireless 7265                                                     | 2         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.32%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.66%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.66%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.66%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 52.44%  |
| Realtek Semiconductor | 13        | 15.85%  |
| Qualcomm Atheros      | 11        | 13.41%  |
| Broadcom              | 8         | 9.76%   |
| MediaTek              | 3         | 3.66%   |
| TP-Link               | 1         | 1.22%   |
| Hewlett-Packard       | 1         | 1.22%   |
| Fibocom               | 1         | 1.22%   |
| Broadcom Limited      | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 7         | 8.54%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 7.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 6.1%    |
| Intel Wireless 8265 / 8275                                              | 5         | 6.1%    |
| Intel Wireless 8260                                                     | 4         | 4.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 4.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 4.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.44%   |
| Intel Wireless 7265                                                     | 2         | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.22%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.22%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.22%   |
| Intel Wireless 7260                                                     | 1         | 1.22%   |
| Intel Wireless 3165                                                     | 1         | 1.22%   |
| Intel Wireless 3160                                                     | 1         | 1.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.22%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.22%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.22%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.22%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 39        | 59.09%  |
| Intel                 | 14        | 21.21%  |
| ASIX Electronics      | 3         | 4.55%   |
| Qualcomm Atheros      | 2         | 3.03%   |
| Broadcom              | 2         | 3.03%   |
| Xiaomi                | 1         | 1.52%   |
| Nvidia                | 1         | 1.52%   |
| Lenovo                | 1         | 1.52%   |
| JMicron Technology    | 1         | 1.52%   |
| Hewlett-Packard       | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 33.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 13.24%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 8.82%   |
| Intel Ethernet Connection I219-V                                  | 3         | 4.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 4.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.47%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.47%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.47%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.47%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.47%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.47%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.47%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.47%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 55.32%  |
| Ethernet | 62        | 43.97%  |
| Modem    | 1         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 80.49%  |
| Ethernet | 16        | 19.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 68.75%  |
| 1     | 21        | 26.25%  |
| 0     | 4         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 63.86%  |
| Yes  | 30        | 36.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 56.34%  |
| Realtek Semiconductor           | 7         | 9.86%   |
| Qualcomm Atheros Communications | 7         | 9.86%   |
| Broadcom                        | 5         | 7.04%   |
| Apple                           | 4         | 5.63%   |
| IMC Networks                    | 2         | 2.82%   |
| Dell                            | 2         | 2.82%   |
| Smart Modular Technologies      | 1         | 1.41%   |
| Realtek                         | 1         | 1.41%   |
| MediaTek                        | 1         | 1.41%   |
| Foxconn International           | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 15        | 21.13%  |
| Intel AX201 Bluetooth                              | 12        | 16.9%   |
| Intel AX200 Bluetooth                              | 6         | 8.45%   |
| Realtek Bluetooth Radio                            | 5         | 7.04%   |
| Qualcomm Atheros  Bluetooth Device                 | 5         | 7.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 2.82%   |
| Intel AX210 Bluetooth                              | 2         | 2.82%   |
| Dell DW375 Bluetooth Module                        | 2         | 2.82%   |
| Apple Bluetooth USB Host Controller                | 2         | 2.82%   |
| Apple Bluetooth Host Controller                    | 2         | 2.82%   |
| Smart Modular Bluetooth Device                     | 1         | 1.41%   |
| Realtek RTL8821A Bluetooth                         | 1         | 1.41%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.41%   |
| Realtek Bluetooth Radio                            | 1         | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.41%   |
| MediaTek Wireless_Device                           | 1         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.41%   |
| Intel Bluetooth Device                             | 1         | 1.41%   |
| IMC Networks Wireless_Device                       | 1         | 1.41%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.41%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.41%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 1         | 1.41%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.41%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 65        | 73.86%  |
| AMD                  | 11        | 12.5%   |
| Nvidia               | 8         | 9.09%   |
| Plantronics          | 1         | 1.14%   |
| Logitech             | 1         | 1.14%   |
| LINE TECH INDUSTRIAL | 1         | 1.14%   |
| DSEA A/S             | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 14.02%  |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 8.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 7.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 6.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 3.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 3.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 3.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.8%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.8%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.87%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.87%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.87%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.93%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.93%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.93%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 0.93%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.93%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.93%   |
| DSEA A/S EPOS ADAPT 1x5                                                    | 1         | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 35.59%  |
| SK hynix            | 14        | 23.73%  |
| Kingston            | 6         | 10.17%  |
| Micron Technology   | 5         | 8.47%   |
| Elpida              | 3         | 5.08%   |
| Unknown (ABCD)      | 2         | 3.39%   |
| Ramaxel Technology  | 2         | 3.39%   |
| Unknown             | 1         | 1.69%   |
| Teikon              | 1         | 1.69%   |
| Magnum Tech         | 1         | 1.69%   |
| fef5                | 1         | 1.69%   |
| ChangXin Memory     | 1         | 1.69%   |
| 8945000080AD        | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 6.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.17%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 3.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.59%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.59%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.59%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.59%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.59%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.59%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.59%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.59%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.59%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.59%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.59%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.59%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.59%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.59%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s         | 1         | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.59%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.59%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.59%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 29        | 59.18%  |
| DDR3    | 12        | 24.49%  |
| LPDDR4  | 6         | 12.24%  |
| SDRAM   | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 87.76%  |
| Row Of Chips | 3         | 6.12%   |
| Unknown      | 2         | 4.08%   |
| Chip         | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 20        | 40%     |
| 4096  | 10        | 20%     |
| 16384 | 8         | 16%     |
| 32768 | 5         | 10%     |
| 2048  | 5         | 10%     |
| 1024  | 2         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 15        | 28.3%   |
| 2667  | 9         | 16.98%  |
| 1600  | 9         | 16.98%  |
| 2400  | 8         | 15.09%  |
| 2133  | 3         | 5.66%   |
| 1334  | 2         | 3.77%   |
| 4267  | 1         | 1.89%   |
| 4199  | 1         | 1.89%   |
| 3733  | 1         | 1.89%   |
| 3266  | 1         | 1.89%   |
| 1333  | 1         | 1.89%   |
| 1067  | 1         | 1.89%   |
| 1066  | 1         | 1.89%   |

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
| Chicony Electronics                    | 22        | 31.88%  |
| IMC Networks                           | 8         | 11.59%  |
| Realtek Semiconductor                  | 6         | 8.7%    |
| Bison Electronics                      | 5         | 7.25%   |
| Sunplus Innovation Technology          | 4         | 5.8%    |
| Microdia                               | 4         | 5.8%    |
| Luxvisions Innotech Limited            | 4         | 5.8%    |
| Syntek                                 | 3         | 4.35%   |
| Apple                                  | 3         | 4.35%   |
| Quanta                                 | 2         | 2.9%    |
| Acer                                   | 2         | 2.9%    |
| Unknown (3730304231385031345945)       | 1         | 1.45%   |
| Samsung Electronics                    | 1         | 1.45%   |
| Polycom                                | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.45%   |
| Alcor Micro                            | 1         | 1.45%   |
| Unknown                                | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 4.35%   |
| IMC Networks Integrated Camera                    | 3         | 4.35%   |
| Chicony USB2.0 Camera                             | 3         | 4.35%   |
| Chicony Integrated Camera                         | 3         | 4.35%   |
| Chicony HP HD Camera                              | 3         | 4.35%   |
| Bison SunplusIT Integrated Camera                 | 3         | 4.35%   |
| Syntek Integrated Camera                          | 2         | 2.9%    |
| Realtek Integrated_Webcam_HD                      | 2         | 2.9%    |
| Microdia Integrated_Webcam_HD                     | 2         | 2.9%    |
| Luxvisions Innotech Limited HP HD Camera          | 2         | 2.9%    |
| Chicony USB2.0 VGA UVC WebCam                     | 2         | 2.9%    |
| Chicony Integrated IR Camera                      | 2         | 2.9%    |
| Apple FaceTime HD Camera                          | 2         | 2.9%    |
| Unknown (3730304231385031345945) USB Camera       | 1         | 1.45%   |
| Syntek Lenovo EasyCamera                          | 1         | 1.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 1.45%   |
| Sunplus Integrated_Webcam_HD                      | 1         | 1.45%   |
| Sunplus HD WebCam                                 | 1         | 1.45%   |
| Sunplus 1080P Webcam                              | 1         | 1.45%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 1.45%   |
| Realtek USB2.0 HD UVC WebCam                      | 1         | 1.45%   |
| Realtek Lenovo EasyCamera                         | 1         | 1.45%   |
| Realtek Integrated Webcam HD                      | 1         | 1.45%   |
| Realtek Integrated Webcam                         | 1         | 1.45%   |
| Quanta USB2.0 HD UVC WebCam                       | 1         | 1.45%   |
| Quanta HP Wide Vision HD Camera                   | 1         | 1.45%   |
| Polycom Poly Studio P5 webcam                     | 1         | 1.45%   |
| Microdia Lenovo EasyCamera                        | 1         | 1.45%   |
| Microdia Integrated Webcam HD                     | 1         | 1.45%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.45%   |
| Luxvisions Innotech Limited Integrated Camera     | 1         | 1.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 1         | 1.45%   |
| IMC Networks Integrated RGB Camera                | 1         | 1.45%   |
| Chicony XiaoMi USB 2.0 Webcam                     | 1         | 1.45%   |
| Chicony USB2.0 UVC WebCam                         | 1         | 1.45%   |
| Chicony USB2.0 0.3M UVC WebCam                    | 1         | 1.45%   |
| Chicony Lenovo EasyCamera                         | 1         | 1.45%   |
| Chicony HP Truevision HD camera                   | 1         | 1.45%   |
| Chicony HP Truevision HD                          | 1         | 1.45%   |
| Chicony HP Integrated Webcam                      | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 40%     |
| Validity Sensors           | 5         | 25%     |
| Shenzhen Goodix Technology | 5         | 25%     |
| LighTuning Technology      | 1         | 5%      |
| Elan Microelectronics      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 15%     |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 15%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 5%      |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 5%      |
| Synaptics UWP WBDI Device                                 | 1         | 5%      |
| Synaptics UWP WBDI                                        | 1         | 5%      |
| Synaptics  WBDI                                           | 1         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 5%      |
| Shenzhen Goodix FingerPrint                               | 1         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 5%      |
| Elan ELAN:Fingerprint                                     | 1         | 5%      |
| Unknown                                                   | 1         | 5%      |

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
| 0     | 47        | 58.02%  |
| 1     | 23        | 28.4%   |
| 2     | 8         | 9.88%   |
| 3     | 2         | 2.47%   |
| 7     | 1         | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 41.3%   |
| Chipcard                 | 5         | 10.87%  |
| Net/wireless             | 4         | 8.7%    |
| Graphics card            | 4         | 8.7%    |
| Communication controller | 4         | 8.7%    |
| Camera                   | 3         | 6.52%   |
| Sound                    | 2         | 4.35%   |
| Multimedia controller    | 2         | 4.35%   |
| Card reader              | 2         | 4.35%   |
| Bluetooth                | 1         | 2.17%   |


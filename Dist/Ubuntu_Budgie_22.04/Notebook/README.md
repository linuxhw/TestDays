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

Total: 133

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X220 4291G75       | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Toshiba       | Satellite A300              | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASUSTek       | E403SA                      | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [a293b54992](https://linux-hardware.org/?probe=a293b54992) | Nov 24, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [5efa262121](https://linux-hardware.org/?probe=5efa262121) | Nov 14, 2023 |
| Lenovo        | G50-45 80E3                 | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [143fa66e87](https://linux-hardware.org/?probe=143fa66e87) | Nov 08, 2023 |
| HONOR         | GLO-GXXX                    | [c6d6619fd9](https://linux-hardware.org/?probe=c6d6619fd9) | Nov 06, 2023 |
| Lenovo        | G50-45 80E3                 | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| Lenovo        | G50-45 80E3                 | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| ASUSTek       | UX303UA                     | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
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
| 5.15.0-27-generic     | 7         | 6.73%   |
| 5.15.0-50-generic     | 5         | 4.81%   |
| 5.15.0-48-generic     | 5         | 4.81%   |
| 5.19.0-46-generic     | 4         | 3.85%   |
| 5.15.0-52-generic     | 4         | 3.85%   |
| 5.19.0-41-generic     | 3         | 2.88%   |
| 5.19.0-35-generic     | 3         | 2.88%   |
| 5.15.0-53-generic     | 3         | 2.88%   |
| 5.15.0-40-generic     | 3         | 2.88%   |
| 5.15.0-39-generic     | 3         | 2.88%   |
| 5.15.0-30-generic     | 3         | 2.88%   |
| 6.2.0-39-generic      | 2         | 1.92%   |
| 6.2.0-33-generic      | 2         | 1.92%   |
| 6.2.0-32-generic      | 2         | 1.92%   |
| 6.2.0-26-generic      | 2         | 1.92%   |
| 6.2.0-10007-tuxedo    | 2         | 1.92%   |
| 5.19.0-42-generic     | 2         | 1.92%   |
| 5.19.0-38-generic     | 2         | 1.92%   |
| 5.15.0-67-generic     | 2         | 1.92%   |
| 5.15.0-58-generic     | 2         | 1.92%   |
| 5.15.0-56-generic     | 2         | 1.92%   |
| 5.15.0-47-generic     | 2         | 1.92%   |
| 5.15.0-46-generic     | 2         | 1.92%   |
| 5.15.0-33-generic     | 2         | 1.92%   |
| 5.15.0-25-generic     | 2         | 1.92%   |
| 6.5.0-10008-tuxedo    | 1         | 0.96%   |
| 6.3.1-060301-generic  | 1         | 0.96%   |
| 6.2.0-37-generic      | 1         | 0.96%   |
| 6.2.0-34-generic      | 1         | 0.96%   |
| 6.2.0-10018-tuxedo    | 1         | 0.96%   |
| 6.1.0-060100-generic  | 1         | 0.96%   |
| 5.19.0-45-generic     | 1         | 0.96%   |
| 5.19.0-40-generic     | 1         | 0.96%   |
| 5.19.0-32-generic     | 1         | 0.96%   |
| 5.19.0-051900-generic | 1         | 0.96%   |
| 5.15.0-89-generic     | 1         | 0.96%   |
| 5.15.0-88-lowlatency  | 1         | 0.96%   |
| 5.15.0-88-generic     | 1         | 0.96%   |
| 5.15.0-87-lowlatency  | 1         | 0.96%   |
| 5.15.0-79-lowlatency  | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 62        | 64.58%  |
| 5.19.0  | 17        | 17.71%  |
| 6.2.0   | 12        | 12.5%   |
| 5.13.0  | 2         | 2.08%   |
| 6.5.0   | 1         | 1.04%   |
| 6.3.1   | 1         | 1.04%   |
| 6.1.0   | 1         | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 62        | 64.58%  |
| 5.19    | 17        | 17.71%  |
| 6.2     | 12        | 12.5%   |
| 5.13    | 2         | 2.08%   |
| 6.5     | 1         | 1.04%   |
| 6.3     | 1         | 1.04%   |
| 6.1     | 1         | 1.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 90        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 84        | 93.33%  |
| GNOME  | 5         | 5.56%   |
| KDE5   | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 87        | 96.67%  |
| Wayland | 3         | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 64        | 71.11%  |
| Unknown | 15        | 16.67%  |
| GDM3    | 10        | 11.11%  |
| SDDM    | 1         | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 30        | 33.33%  |
| de_DE | 12        | 13.33%  |
| fr_FR | 11        | 12.22%  |
| pt_BR | 5         | 5.56%   |
| en_GB | 4         | 4.44%   |
| it_IT | 3         | 3.33%   |
| en_CA | 3         | 3.33%   |
| ru_RU | 2         | 2.22%   |
| hu_HU | 2         | 2.22%   |
| fr_BE | 2         | 2.22%   |
| en_IE | 2         | 2.22%   |
| pl_PL | 1         | 1.11%   |
| mt_MT | 1         | 1.11%   |
| ja_JP | 1         | 1.11%   |
| es_PE | 1         | 1.11%   |
| es_MX | 1         | 1.11%   |
| es_ES | 1         | 1.11%   |
| es_EC | 1         | 1.11%   |
| es_CL | 1         | 1.11%   |
| es_AR | 1         | 1.11%   |
| en_SG | 1         | 1.11%   |
| en_IL | 1         | 1.11%   |
| en_AU | 1         | 1.11%   |
| cs_CZ | 1         | 1.11%   |
| C     | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 51        | 56.67%  |
| EFI  | 39        | 43.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 80        | 86.02%  |
| Tmpfs   | 6         | 6.45%   |
| Overlay | 3         | 3.23%   |
| Zfs     | 2         | 2.15%   |
| Xfs     | 1         | 1.08%   |
| Btrfs   | 1         | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 60        | 66.67%  |
| Unknown | 25        | 27.78%  |
| MBR     | 5         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 86.67%  |
| Yes       | 12        | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 68.13%  |
| Yes       | 29        | 31.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 24.44%  |
| Dell                   | 13        | 14.44%  |
| Hewlett-Packard        | 12        | 13.33%  |
| ASUSTek Computer       | 12        | 13.33%  |
| TUXEDO                 | 9         | 10%     |
| Apple                  | 4         | 4.44%   |
| MSI                    | 3         | 3.33%   |
| Toshiba                | 2         | 2.22%   |
| Google                 | 2         | 2.22%   |
| Acer                   | 2         | 2.22%   |
| Timi                   | 1         | 1.11%   |
| Razer                  | 1         | 1.11%   |
| HUAWEI                 | 1         | 1.11%   |
| Digibras               | 1         | 1.11%   |
| COM1                   | 1         | 1.11%   |
| Chuwi                  | 1         | 1.11%   |
| BANGHO                 | 1         | 1.11%   |
| AXIOO                  | 1         | 1.11%   |
| Avell High Performance | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 2.22%   |
| Lenovo G50-45 80E3                                   | 2         | 2.22%   |
| HP EliteBook 840 G3                                  | 2         | 2.22%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.11%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.11%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 1.11%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.11%   |
| TUXEDO Book XP1511                                   | 1         | 1.11%   |
| TUXEDO Book BA1510                                   | 1         | 1.11%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.11%   |
| Toshiba Satellite A505                               | 1         | 1.11%   |
| Toshiba Satellite A300                               | 1         | 1.11%   |
| Timi TM1604                                          | 1         | 1.11%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.11%   |
| MSI Modern 15 A10M                                   | 1         | 1.11%   |
| MSI GL62 6QF                                         | 1         | 1.11%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.11%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.11%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 1.11%   |
| Lenovo ThinkPad X220 4291G75                         | 1         | 1.11%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002SIV             | 1         | 1.11%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.11%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.11%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.11%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.11%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 1.11%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.11%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.11%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.11%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.11%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.11%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.11%   |
| Lenovo IdeaPad 520-15IKB 81BF                        | 1         | 1.11%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.11%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.11%   |
| Lenovo IdeaPad 110-15ISK 80UD                        | 1         | 1.11%   |
| Lenovo G500 20236                                    | 1         | 1.11%   |
| HUAWEI HKD-WXX                                       | 1         | 1.11%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.11%   |
| HP ProBook 450 G7                                    | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 10        | 11.11%  |
| Lenovo IdeaPad              | 7         | 7.78%   |
| Dell Latitude               | 5         | 5.56%   |
| HP EliteBook                | 4         | 4.44%   |
| Dell Inspiron               | 4         | 4.44%   |
| TUXEDO Book                 | 3         | 3.33%   |
| HP ProBook                  | 3         | 3.33%   |
| ASUS VivoBook               | 3         | 3.33%   |
| TUXEDO Pulse                | 2         | 2.22%   |
| TUXEDO InfinityBook         | 2         | 2.22%   |
| Toshiba Satellite           | 2         | 2.22%   |
| Lenovo G50-45               | 2         | 2.22%   |
| HP Pavilion                 | 2         | 2.22%   |
| Dell XPS                    | 2         | 2.22%   |
| Acer Aspire                 | 2         | 2.22%   |
| TUXEDO Polaris              | 1         | 1.11%   |
| TUXEDO Aura                 | 1         | 1.11%   |
| Timi TM1604                 | 1         | 1.11%   |
| Razer Blade                 | 1         | 1.11%   |
| MSI Modern                  | 1         | 1.11%   |
| MSI GL62                    | 1         | 1.11%   |
| MSI Alpha                   | 1         | 1.11%   |
| Lenovo V15                  | 1         | 1.11%   |
| Lenovo Legion               | 1         | 1.11%   |
| Lenovo G500                 | 1         | 1.11%   |
| HUAWEI HKD-WXX              | 1         | 1.11%   |
| HP ENVY                     | 1         | 1.11%   |
| HP ElitePad                 | 1         | 1.11%   |
| HP Bloog                    | 1         | 1.11%   |
| Google Rabbid               | 1         | 1.11%   |
| Google Boten                | 1         | 1.11%   |
| Digibras NH4CU03            | 1         | 1.11%   |
| Dell Vostro                 | 1         | 1.11%   |
| Dell Precision              | 1         | 1.11%   |
| COM1 NBINF-X5-9G5           | 1         | 1.11%   |
| Chuwi HeroBook              | 1         | 1.11%   |
| BANGHO BES                  | 1         | 1.11%   |
| AXIOO Slimbook              | 1         | 1.11%   |
| Avell High Performance B.ON | 1         | 1.11%   |
| ASUS ZenBook                | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 16        | 17.78%  |
| 2020 | 14        | 15.56%  |
| 2016 | 9         | 10%     |
| 2014 | 8         | 8.89%   |
| 2019 | 6         | 6.67%   |
| 2018 | 6         | 6.67%   |
| 2017 | 5         | 5.56%   |
| 2022 | 4         | 4.44%   |
| 2015 | 4         | 4.44%   |
| 2013 | 4         | 4.44%   |
| 2011 | 4         | 4.44%   |
| 2012 | 3         | 3.33%   |
| 2009 | 3         | 3.33%   |
| 2010 | 2         | 2.22%   |
| 2008 | 2         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 90        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 83        | 92.22%  |
| Enabled  | 7         | 7.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 87        | 96.67%  |
| Yes  | 3         | 3.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 32.97%  |
| 16.01-24.0  | 23        | 25.27%  |
| 3.01-4.0    | 13        | 14.29%  |
| 8.01-16.0   | 11        | 12.09%  |
| 32.01-64.0  | 9         | 9.89%   |
| 64.01-256.0 | 4         | 4.4%    |
| 1.01-2.0    | 1         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 32.99%  |
| 1.01-2.0   | 23        | 23.71%  |
| 4.01-8.0   | 17        | 17.53%  |
| 3.01-4.0   | 14        | 14.43%  |
| 8.01-16.0  | 7         | 7.22%   |
| 24.01-32.0 | 2         | 2.06%   |
| 16.01-24.0 | 2         | 2.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 76.34%  |
| 2      | 20        | 21.51%  |
| 3      | 2         | 2.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 81.11%  |
| Yes       | 17        | 18.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 76.92%  |
| No        | 21        | 23.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 97.78%  |
| No        | 2         | 2.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 85.56%  |
| No        | 13        | 14.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 15        | 16.67%  |
| USA                | 12        | 13.33%  |
| France             | 12        | 13.33%  |
| Brazil             | 5         | 5.56%   |
| Poland             | 3         | 3.33%   |
| Italy              | 3         | 3.33%   |
| Canada             | 3         | 3.33%   |
| UK                 | 2         | 2.22%   |
| Peru               | 2         | 2.22%   |
| Ireland            | 2         | 2.22%   |
| Indonesia          | 2         | 2.22%   |
| Hungary            | 2         | 2.22%   |
| Belgium            | 2         | 2.22%   |
| Austria            | 2         | 2.22%   |
| Sweden             | 1         | 1.11%   |
| Spain              | 1         | 1.11%   |
| Slovenia           | 1         | 1.11%   |
| Singapore          | 1         | 1.11%   |
| Russia             | 1         | 1.11%   |
| Romania            | 1         | 1.11%   |
| Mexico             | 1         | 1.11%   |
| Malta              | 1         | 1.11%   |
| Japan              | 1         | 1.11%   |
| Israel             | 1         | 1.11%   |
| Greece             | 1         | 1.11%   |
| Ghana              | 1         | 1.11%   |
| Ecuador            | 1         | 1.11%   |
| Dominican Republic | 1         | 1.11%   |
| Czechia            | 1         | 1.11%   |
| Cuba               | 1         | 1.11%   |
| Chile              | 1         | 1.11%   |
| Cabo Verde         | 1         | 1.11%   |
| Bulgaria           | 1         | 1.11%   |
| Belarus            | 1         | 1.11%   |
| Australia          | 1         | 1.11%   |
| Argentina          | 1         | 1.11%   |
| Algeria            | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Berlin                | 3         | 3.23%   |
| Warsaw                | 2         | 2.15%   |
| Vienna                | 2         | 2.15%   |
| Victoria              | 2         | 2.15%   |
| Nuremberg             | 2         | 2.15%   |
| Frankfurt am Main     | 2         | 2.15%   |
| Dublin                | 2         | 2.15%   |
| Budapest              | 2         | 2.15%   |
| Yogyakarta            | 1         | 1.08%   |
| Wertheim am Main      | 1         | 1.08%   |
| Weisswasser           | 1         | 1.08%   |
| Weilheim              | 1         | 1.08%   |
| Washington            | 1         | 1.08%   |
| Torun                 | 1         | 1.08%   |
| Targu Frumos          | 1         | 1.08%   |
| Tarakan               | 1         | 1.08%   |
| Sunnyvale             | 1         | 1.08%   |
| St Petersburg         | 1         | 1.08%   |
| Sofia                 | 1         | 1.08%   |
| Singapore             | 1         | 1.08%   |
| Siegen                | 1         | 1.08%   |
| Shirakuni             | 1         | 1.08%   |
| Sétif                | 1         | 1.08%   |
| Seelze                | 1         | 1.08%   |
| Sao Paulo             | 1         | 1.08%   |
| Sao Bernardo do Campo | 1         | 1.08%   |
| Santo Domingo Este    | 1         | 1.08%   |
| Santiago              | 1         | 1.08%   |
| Saint-Gilles          | 1         | 1.08%   |
| Rishon LeTsiyyon      | 1         | 1.08%   |
| Renton                | 1         | 1.08%   |
| Recife                | 1         | 1.08%   |
| Queens                | 1         | 1.08%   |
| Quedlinburg           | 1         | 1.08%   |
| Puteaux               | 1         | 1.08%   |
| Puebla City           | 1         | 1.08%   |
| Praia                 | 1         | 1.08%   |
| Postojna              | 1         | 1.08%   |
| Pau                   | 1         | 1.08%   |
| Paris                 | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 27        | 33     | 24.55%  |
| Unknown                        | 11        | 11     | 10%     |
| Toshiba                        | 8         | 11     | 7.27%   |
| Crucial                        | 7         | 12     | 6.36%   |
| SK hynix                       | 6         | 6      | 5.45%   |
| Seagate                        | 6         | 6      | 5.45%   |
| Micron Technology              | 6         | 6      | 5.45%   |
| WDC                            | 5         | 6      | 4.55%   |
| Kingston                       | 4         | 4      | 3.64%   |
| Intel                          | 3         | 3      | 2.73%   |
| SPCC                           | 2         | 3      | 1.82%   |
| SanDisk                        | 2         | 2      | 1.82%   |
| JMicron Technology             | 2         | 2      | 1.82%   |
| China                          | 2         | 3      | 1.82%   |
| Apple                          | 2         | 2      | 1.82%   |
| A-DATA Technology              | 2         | 3      | 1.82%   |
| YMTC                           | 1         | 1      | 0.91%   |
| VISIPRO                        | 1         | 1      | 0.91%   |
| Union Memory                   | 1         | 1      | 0.91%   |
| TO Exter                       | 1         | 1      | 0.91%   |
| Solid State Storage Technology | 1         | 1      | 0.91%   |
| Realtek Semiconductor          | 1         | 1      | 0.91%   |
| Phison Electronics             | 1         | 1      | 0.91%   |
| OWC                            | 1         | 1      | 0.91%   |
| Netac                          | 1         | 1      | 0.91%   |
| KIOXIA                         | 1         | 1      | 0.91%   |
| HGST                           | 1         | 1      | 0.91%   |
| Hewlett-Packard                | 1         | 1      | 0.91%   |
| Gigabyte Technology            | 1         | 1      | 0.91%   |
| Corsair                        | 1         | 2      | 0.91%   |
| Unknown                        | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4         | 3.57%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.79%   |
| Unknown SD64G  64GB                                 | 2         | 1.79%   |
| Unknown MMC Card  64GB                              | 2         | 1.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.79%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 1.79%   |
| Samsung SSD 980 500GB                               | 2         | 1.79%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 1.79%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 1.79%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 1.79%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.79%   |
| YMTC PC005 1TB                                      | 1         | 0.89%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.89%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 0.89%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.89%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 0.89%   |
| VISIPRO SSD 256GB                                   | 1         | 0.89%   |
| Unknown SL128  128GB                                | 1         | 0.89%   |
| Unknown SA16G  16GB                                 | 1         | 0.89%   |
| Unknown NCard  4GB                                  | 1         | 0.89%   |
| Unknown MMC128  128GB                               | 1         | 0.89%   |
| Unknown MMC Card  968MB                             | 1         | 0.89%   |
| Unknown MMC Card  32GB                              | 1         | 0.89%   |
| Unknown MMC Card  128GB                             | 1         | 0.89%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD              | 1         | 0.89%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 0.89%   |
| Toshiba TR150 480GB SSD                             | 1         | 0.89%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 0.89%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.89%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 0.89%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.89%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                   | 1         | 0.89%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 0.89%   |
| TO Exter nal USB 3.0 480GB                          | 1         | 0.89%   |
| SPCC Solid State Disk 120GB                         | 1         | 0.89%   |
| SPCC Solid State Disk 1024GB                        | 1         | 0.89%   |
| Solid State Storage NVMe CA6-8D1024 1024GB          | 1         | 0.89%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB           | 1         | 0.89%   |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB             | 1         | 0.89%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| WDC                 | 3         | 3      | 20%     |
| Toshiba             | 3         | 3      | 20%     |
| TO Exter            | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 13     | 22.5%   |
| Crucial             | 7         | 12     | 17.5%   |
| Micron Technology   | 3         | 3      | 7.5%    |
| SPCC                | 2         | 3      | 5%      |
| SanDisk             | 2         | 2      | 5%      |
| Kingston            | 2         | 2      | 5%      |
| China               | 2         | 3      | 5%      |
| Apple               | 2         | 2      | 5%      |
| VISIPRO             | 1         | 1      | 2.5%    |
| Union Memory        | 1         | 1      | 2.5%    |
| Toshiba             | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 1      | 2.5%    |
| OWC                 | 1         | 1      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| JMicron Technology  | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| Hewlett-Packard     | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| Corsair             | 1         | 2      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 40        | 47     | 38.1%   |
| SSD     | 37        | 52     | 35.24%  |
| HDD     | 15        | 15     | 14.29%  |
| MMC     | 12        | 14     | 11.43%  |
| Unknown | 1         | 1      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 65     | 46.53%  |
| NVMe | 40        | 47     | 39.6%   |
| MMC  | 12        | 14     | 11.88%  |
| SAS  | 2         | 3      | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 44     | 64.81%  |
| 0.51-1.0   | 14        | 17     | 25.93%  |
| 1.01-2.0   | 5         | 6      | 9.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 32.22%  |
| 251-500        | 28        | 31.11%  |
| 501-1000       | 13        | 14.44%  |
| 51-100         | 7         | 7.78%   |
| 21-50          | 5         | 5.56%   |
| 1001-2000      | 4         | 4.44%   |
| 1-20           | 2         | 2.22%   |
| More than 3000 | 1         | 1.11%   |
| 2001-3000      | 1         | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 25        | 26.88%  |
| 21-50     | 22        | 23.66%  |
| 101-250   | 19        | 20.43%  |
| 51-100    | 12        | 12.9%   |
| 251-500   | 8         | 8.6%    |
| 501-1000  | 4         | 4.3%    |
| 1001-2000 | 3         | 3.23%   |

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
| Detected | 51        | 72     | 54.26%  |
| Works    | 41        | 55     | 43.62%  |
| Malfunc  | 2         | 2      | 2.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 57        | 53.27%  |
| Samsung Electronics            | 17        | 15.89%  |
| AMD                            | 9         | 8.41%   |
| Toshiba America Info Systems   | 3         | 2.8%    |
| SK hynix                       | 3         | 2.8%    |
| SanDisk                        | 3         | 2.8%    |
| Micron Technology              | 3         | 2.8%    |
| KIOXIA                         | 2         | 1.87%   |
| Kingston Technology Company    | 2         | 1.87%   |
| ADATA Technology               | 2         | 1.87%   |
| Yangtze Memory Technologies    | 1         | 0.93%   |
| Solid State Storage Technology | 1         | 0.93%   |
| Realtek Semiconductor          | 1         | 0.93%   |
| Phison Electronics             | 1         | 0.93%   |
| Nvidia                         | 1         | 0.93%   |
| Marvell Technology Group       | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 9.82%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 9         | 8.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 6         | 5.36%   |
| Intel Volume Management Device NVMe RAID Controller                          | 6         | 5.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 5         | 4.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 3.57%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 4         | 3.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.68%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 2.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 2.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 2         | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 2         | 1.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 1.79%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 1.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 1.79%   |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.89%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.89%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)          | 1         | 0.89%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 0.89%   |
| SK hynix PC601 NVMe Solid State Drive                                        | 1         | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 1         | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 0.89%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                  | 1         | 0.89%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.89%   |
| Phison E8 PCIe3 NVMe Controller                                              | 1         | 0.89%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.89%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 0.89%   |
| Micron 2400 NVMe SSD (DRAM-less)                                             | 1         | 0.89%   |
| Micron 2300 NVMe SSD [Santana]                                               | 1         | 0.89%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 0.89%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 61        | 55.45%  |
| NVMe | 40        | 36.36%  |
| RAID | 8         | 7.27%   |
| IDE  | 1         | 0.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 85.56%  |
| AMD    | 13        | 14.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 4.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 3.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 3.33%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 2.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.22%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.22%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.22%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.22%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.22%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.22%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.22%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.22%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.22%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 2.22%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.11%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.11%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.11%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.11%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.11%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.11%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.11%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.11%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.11%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.11%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.11%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 25.56%  |
| Intel Core i7           | 17        | 18.89%  |
| Other                   | 15        | 16.67%  |
| Intel Core i3           | 6         | 6.67%   |
| AMD Ryzen 7             | 6         | 6.67%   |
| Intel Celeron           | 5         | 5.56%   |
| AMD Ryzen 5             | 4         | 4.44%   |
| Intel Atom              | 3         | 3.33%   |
| Intel Pentium Silver    | 2         | 2.22%   |
| Intel Pentium           | 2         | 2.22%   |
| Intel Core 2 Duo        | 2         | 2.22%   |
| AMD A8                  | 2         | 2.22%   |
| Intel Pentium Dual-Core | 1         | 1.11%   |
| Intel Core i9           | 1         | 1.11%   |
| AMD Ryzen 3             | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 37        | 41.11%  |
| 2      | 35        | 38.89%  |
| 8      | 11        | 12.22%  |
| 6      | 5         | 5.56%   |
| 10     | 2         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 76.67%  |
| 1      | 21        | 23.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 90        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 56.99%  |
| 0x806c1    | 4         | 4.3%    |
| 0x08600106 | 4         | 4.3%    |
| 0x806ec    | 3         | 3.23%   |
| 0x706a8    | 3         | 3.23%   |
| 0x206a7    | 3         | 3.23%   |
| 0x806ea    | 2         | 2.15%   |
| 0x806d1    | 2         | 2.15%   |
| 0x406e3    | 2         | 2.15%   |
| 0x20655    | 2         | 2.15%   |
| 0x08108102 | 2         | 2.15%   |
| 0x906ea    | 1         | 1.08%   |
| 0x806eb    | 1         | 1.08%   |
| 0x806e9    | 1         | 1.08%   |
| 0x506e3    | 1         | 1.08%   |
| 0x506c9    | 1         | 1.08%   |
| 0x40651    | 1         | 1.08%   |
| 0x306d4    | 1         | 1.08%   |
| 0x306c3    | 1         | 1.08%   |
| 0x30678    | 1         | 1.08%   |
| 0x106e5    | 1         | 1.08%   |
| 0x0a50000c | 1         | 1.08%   |
| 0x07030105 | 1         | 1.08%   |
| 0x07030104 | 1         | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 18        | 20%     |
| Skylake       | 10        | 11.11%  |
| TigerLake     | 9         | 10%     |
| Zen 2         | 6         | 6.67%   |
| Unknown       | 6         | 6.67%   |
| Silvermont    | 4         | 4.44%   |
| SandyBridge   | 4         | 4.44%   |
| IvyBridge     | 4         | 4.44%   |
| Haswell       | 4         | 4.44%   |
| Goldmont plus | 4         | 4.44%   |
| Penryn        | 3         | 3.33%   |
| IceLake       | 3         | 3.33%   |
| Broadwell     | 3         | 3.33%   |
| Zen+          | 2         | 2.22%   |
| Zen 3         | 2         | 2.22%   |
| Westmere      | 2         | 2.22%   |
| Puma          | 2         | 2.22%   |
| CometLake     | 2         | 2.22%   |
| Nehalem       | 1         | 1.11%   |
| Goldmont      | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 74        | 67.27%  |
| Nvidia | 21        | 19.09%  |
| AMD    | 15        | 13.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 7.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 7.08%   |
| Intel UHD Graphics 620                                                    | 6         | 5.31%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 5.31%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 3.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 3.54%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.54%   |
| Intel HD Graphics 620                                                     | 3         | 2.65%   |
| Intel HD Graphics 5500                                                    | 3         | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.65%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.77%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.77%   |
| Intel HD Graphics 530                                                     | 2         | 1.77%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.77%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.77%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.77%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.88%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.88%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.88%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.88%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.88%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.88%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.88%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 61.11%  |
| Intel + Nvidia | 16        | 17.78%  |
| 1 x AMD        | 8         | 8.89%   |
| 2 x AMD        | 3         | 3.33%   |
| 1 x Nvidia     | 3         | 3.33%   |
| Intel + AMD    | 2         | 2.22%   |
| AMD + Nvidia   | 2         | 2.22%   |
| Other          | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 76        | 84.44%  |
| Proprietary | 12        | 13.33%  |
| Unknown     | 2         | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 85.56%  |
| 1.01-2.0   | 4         | 4.44%   |
| 0.01-0.5   | 4         | 4.44%   |
| 7.01-8.0   | 2         | 2.22%   |
| 0.51-1.0   | 2         | 2.22%   |
| 3.01-4.0   | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 23        | 21.9%   |
| Chimei Innolux          | 21        | 20%     |
| AU Optronics            | 13        | 12.38%  |
| Samsung Electronics     | 11        | 10.48%  |
| LG Display              | 8         | 7.62%   |
| Sharp                   | 4         | 3.81%   |
| Goldstar                | 4         | 3.81%   |
| Apple                   | 4         | 3.81%   |
| Philips                 | 2         | 1.9%    |
| Lenovo                  | 2         | 1.9%    |
| Unknown (AAA)           | 1         | 0.95%   |
| TMX                     | 1         | 0.95%   |
| PANDA                   | 1         | 0.95%   |
| MStar                   | 1         | 0.95%   |
| LG Philips              | 1         | 0.95%   |
| KDC                     | 1         | 0.95%   |
| IBM                     | 1         | 0.95%   |
| HKC                     | 1         | 0.95%   |
| Daewoo                  | 1         | 0.95%   |
| Chi Mei Optoelectronics | 1         | 0.95%   |
| BenQ                    | 1         | 0.95%   |
| AOC                     | 1         | 0.95%   |
| Acer                    | 1         | 0.95%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.9%    |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1         | 0.95%   |
| TMX TL142GDXP10-0 TMX1420 2520x1680 300x200mm 14.2-inch               | 1         | 0.95%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.95%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.95%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.95%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 0.95%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch   | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.95%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch               | 1         | 0.95%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.95%   |
| MStar LCD TV MST9000 1360x768                                         | 1         | 0.95%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 0.95%   |
| Lenovo T22v-20 LEN61FB 1920x1080 476x268mm 21.5-inch                  | 1         | 0.95%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch              | 1         | 0.95%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                 | 1         | 0.95%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 1         | 0.95%   |
| HKC LCD Monitor HKC36BB 1366x768 309x174mm 14.0-inch                  | 1         | 0.95%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 0.95%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 1         | 0.95%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 0.95%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 46.81%  |
| 1366x768 (WXGA)    | 24        | 25.53%  |
| 1280x800 (WXGA)    | 4         | 4.26%   |
| 3840x2160 (4K)     | 3         | 3.19%   |
| 2560x1440 (QHD)    | 3         | 3.19%   |
| 1920x1200 (WUXGA)  | 3         | 3.19%   |
| 1600x900 (HD+)     | 3         | 3.19%   |
| 1680x1050 (WSXGA+) | 2         | 2.13%   |
| 1440x900 (WXGA+)   | 2         | 2.13%   |
| 3456x2160          | 1         | 1.06%   |
| 2880x1800          | 1         | 1.06%   |
| 2560x1600          | 1         | 1.06%   |
| 2560x1080          | 1         | 1.06%   |
| 2520x1680          | 1         | 1.06%   |
| 1360x768           | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 44        | 41.9%   |
| 13      | 20        | 19.05%  |
| 14      | 11        | 10.48%  |
| 23      | 4         | 3.81%   |
| 17      | 4         | 3.81%   |
| 27      | 3         | 2.86%   |
| 12      | 3         | 2.86%   |
| 11      | 3         | 2.86%   |
| 40      | 2         | 1.9%    |
| 24      | 2         | 1.9%    |
| 21      | 2         | 1.9%    |
| 84      | 1         | 0.95%   |
| 60      | 1         | 0.95%   |
| 34      | 1         | 0.95%   |
| 31      | 1         | 0.95%   |
| 19      | 1         | 0.95%   |
| 10      | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 60.95%  |
| 201-300     | 17        | 16.19%  |
| 501-600     | 7         | 6.67%   |
| 351-400     | 5         | 4.76%   |
| 401-500     | 4         | 3.81%   |
| 801-900     | 2         | 1.9%    |
| 601-700     | 2         | 1.9%    |
| 701-800     | 1         | 0.95%   |
| 1501-2000   | 1         | 0.95%   |
| 1001-1500   | 1         | 0.95%   |
| Unknown     | 1         | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 75        | 81.52%  |
| 16/10 | 14        | 15.22%  |
| 3/2   | 2         | 2.17%   |
| 21/9  | 1         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 41.9%   |
| 81-90          | 25        | 23.81%  |
| 201-250        | 7         | 6.67%   |
| 71-80          | 5         | 4.76%   |
| 121-130        | 4         | 3.81%   |
| 61-70          | 3         | 2.86%   |
| 51-60          | 3         | 2.86%   |
| 301-350        | 3         | 2.86%   |
| More than 1000 | 2         | 1.9%    |
| 351-500        | 2         | 1.9%    |
| 151-200        | 2         | 1.9%    |
| 501-1000       | 2         | 1.9%    |
| 41-50          | 1         | 0.95%   |
| 91-100         | 1         | 0.95%   |
| Unknown        | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 47        | 44.76%  |
| 101-120       | 26        | 24.76%  |
| 161-240       | 12        | 11.43%  |
| 51-100        | 12        | 11.43%  |
| More than 240 | 4         | 3.81%   |
| 1-50          | 3         | 2.86%   |
| Unknown       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 78.02%  |
| 2     | 18        | 19.78%  |
| 0     | 2         | 2.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 36.17%  |
| Realtek Semiconductor | 48        | 34.04%  |
| Qualcomm Atheros      | 15        | 10.64%  |
| Broadcom              | 8         | 5.67%   |
| MediaTek              | 4         | 2.84%   |
| ASIX Electronics      | 3         | 2.13%   |
| Hewlett-Packard       | 2         | 1.42%   |
| Broadcom Limited      | 2         | 1.42%   |
| Xiaomi                | 1         | 0.71%   |
| TP-Link               | 1         | 0.71%   |
| Sierra Wireless       | 1         | 0.71%   |
| Nvidia                | 1         | 0.71%   |
| Lenovo                | 1         | 0.71%   |
| JMicron Technology    | 1         | 0.71%   |
| Huawei Technologies   | 1         | 0.71%   |
| Fibocom               | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 27        | 15.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 5.88%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.71%   |
| Intel Wireless 8265 / 8275                                              | 7         | 4.12%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 3.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.94%   |
| Intel Wireless 8260                                                     | 4         | 2.35%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.76%   |
| Intel Ethernet Connection I219-V                                        | 3         | 1.76%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.18%   |
| Intel Wireless 7265                                                     | 2         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.18%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.18%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.59%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.59%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.59%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.59%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 53.76%  |
| Realtek Semiconductor | 13        | 13.98%  |
| Qualcomm Atheros      | 13        | 13.98%  |
| Broadcom              | 8         | 8.6%    |
| MediaTek              | 4         | 4.3%    |
| TP-Link               | 1         | 1.08%   |
| Sierra Wireless       | 1         | 1.08%   |
| Hewlett-Packard       | 1         | 1.08%   |
| Fibocom               | 1         | 1.08%   |
| Broadcom Limited      | 1         | 1.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 8         | 8.6%    |
| Intel Wireless 8265 / 8275                                              | 7         | 7.53%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 7.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 5.38%   |
| Intel Wireless 8260                                                     | 4         | 4.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 4.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 4.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 2.15%   |
| Intel Wireless 7265                                                     | 2         | 2.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 2.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.15%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.08%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.08%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.08%   |
| Intel Wireless 7260                                                     | 1         | 1.08%   |
| Intel Wireless 3165                                                     | 1         | 1.08%   |
| Intel Wireless 3160                                                     | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.08%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 59.46%  |
| Intel                 | 17        | 22.97%  |
| ASIX Electronics      | 3         | 4.05%   |
| Qualcomm Atheros      | 2         | 2.7%    |
| Broadcom              | 2         | 2.7%    |
| Xiaomi                | 1         | 1.35%   |
| Nvidia                | 1         | 1.35%   |
| Lenovo                | 1         | 1.35%   |
| JMicron Technology    | 1         | 1.35%   |
| Hewlett-Packard       | 1         | 1.35%   |
| Broadcom Limited      | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 35.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 13.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 5.26%   |
| Intel Ethernet Connection I219-V                                  | 3         | 3.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.32%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.32%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.32%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.32%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.32%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.32%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.32%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.32%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 55.35%  |
| Ethernet | 70        | 44.03%  |
| Modem    | 1         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 81.52%  |
| Ethernet | 17        | 18.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 63        | 70%     |
| 1     | 23        | 25.56%  |
| 0     | 4         | 4.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 63.44%  |
| Yes  | 34        | 36.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 55.84%  |
| Realtek Semiconductor           | 7         | 9.09%   |
| Qualcomm Atheros Communications | 7         | 9.09%   |
| Broadcom                        | 6         | 7.79%   |
| IMC Networks                    | 4         | 5.19%   |
| Apple                           | 4         | 5.19%   |
| Dell                            | 2         | 2.6%    |
| Smart Modular Technologies      | 1         | 1.3%    |
| Realtek                         | 1         | 1.3%    |
| MediaTek                        | 1         | 1.3%    |
| Foxconn International           | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 15        | 19.48%  |
| Intel Bluetooth Device                             | 15        | 19.48%  |
| Intel AX200 Bluetooth                              | 7         | 9.09%   |
| Realtek Bluetooth Radio                            | 5         | 6.49%   |
| Qualcomm Atheros  Bluetooth Device                 | 5         | 6.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 2.6%    |
| Intel AX210 Bluetooth                              | 2         | 2.6%    |
| IMC Networks Wireless_Device                       | 2         | 2.6%    |
| Dell DW375 Bluetooth Module                        | 2         | 2.6%    |
| Apple Bluetooth USB Host Controller                | 2         | 2.6%    |
| Apple Bluetooth Host Controller                    | 2         | 2.6%    |
| Smart Modular Bluetooth Device                     | 1         | 1.3%    |
| Realtek RTL8821A Bluetooth                         | 1         | 1.3%    |
| Realtek RTL8723B Bluetooth                         | 1         | 1.3%    |
| Realtek Bluetooth Radio                            | 1         | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.3%    |
| MediaTek Wireless_Device                           | 1         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.3%    |
| IMC Networks Bluetooth Radio                       | 1         | 1.3%    |
| IMC Networks Atheros AR3012 Bluetooth              | 1         | 1.3%    |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 1         | 1.3%    |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.3%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                        | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 73        | 71.57%  |
| AMD                    | 13        | 12.75%  |
| Nvidia                 | 10        | 9.8%    |
| Plantronics            | 1         | 0.98%   |
| Logitech               | 1         | 0.98%   |
| LINE TECH INDUSTRIAL   | 1         | 0.98%   |
| DSEA A/S               | 1         | 0.98%   |
| Arturia                | 1         | 0.98%   |
| AKAI Professional M.I. | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 13.82%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 8.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 7.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 7.32%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 3.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 3.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.44%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.44%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.44%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.63%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.63%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.81%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.81%   |
| Nvidia Audio device                                                                               | 1         | 0.81%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 0.81%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                                                  | 1         | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.81%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 34.85%  |
| SK hynix            | 16        | 24.24%  |
| Kingston            | 7         | 10.61%  |
| Micron Technology   | 6         | 9.09%   |
| Elpida              | 3         | 4.55%   |
| Unknown (ABCD)      | 2         | 3.03%   |
| Ramaxel Technology  | 2         | 3.03%   |
| Unknown             | 1         | 1.52%   |
| Teikon              | 1         | 1.52%   |
| Magnum Tech         | 1         | 1.52%   |
| fef5                | 1         | 1.52%   |
| ChangXin Memory     | 1         | 1.52%   |
| A-DATA Technology   | 1         | 1.52%   |
| 8945000080AD        | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 5.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 4.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.86%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.43%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.43%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.43%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.43%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.43%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.43%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.43%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.43%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.43%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.43%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.43%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.43%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.43%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.43%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.43%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.43%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.43%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 59.26%  |
| DDR3    | 13        | 24.07%  |
| LPDDR4  | 6         | 11.11%  |
| SDRAM   | 1         | 1.85%   |
| LPDDR3  | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 87.04%  |
| Row Of Chips | 4         | 7.41%   |
| Unknown      | 2         | 3.7%    |
| Chip         | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 41.82%  |
| 4096  | 11        | 20%     |
| 16384 | 9         | 16.36%  |
| 32768 | 5         | 9.09%   |
| 2048  | 5         | 9.09%   |
| 1024  | 2         | 3.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 16        | 27.12%  |
| 2667  | 11        | 18.64%  |
| 1600  | 10        | 16.95%  |
| 2400  | 8         | 13.56%  |
| 2133  | 3         | 5.08%   |
| 1334  | 2         | 3.39%   |
| 1333  | 2         | 3.39%   |
| 4267  | 1         | 1.69%   |
| 4199  | 1         | 1.69%   |
| 3733  | 1         | 1.69%   |
| 3266  | 1         | 1.69%   |
| 1867  | 1         | 1.69%   |
| 1067  | 1         | 1.69%   |
| 1066  | 1         | 1.69%   |

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
| Chicony Electronics                    | 28        | 35.9%   |
| IMC Networks                           | 8         | 10.26%  |
| Realtek Semiconductor                  | 7         | 8.97%   |
| Bison Electronics                      | 6         | 7.69%   |
| Microdia                               | 5         | 6.41%   |
| Sunplus Innovation Technology          | 4         | 5.13%   |
| Syntek                                 | 3         | 3.85%   |
| Luxvisions Innotech Limited            | 3         | 3.85%   |
| Apple                                  | 3         | 3.85%   |
| Quanta                                 | 2         | 2.56%   |
| Unknown (3730304233333731323245)       | 1         | 1.28%   |
| Samsung Electronics                    | 1         | 1.28%   |
| Polycom                                | 1         | 1.28%   |
| Pixart Imaging                         | 1         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.28%   |
| Alcor Micro                            | 1         | 1.28%   |
| Acer                                   | 1         | 1.28%   |
| 8SSC21D67422V1SR28902JL                | 1         | 1.28%   |
| Unknown                                | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 4         | 5.13%   |
| Chicony HP HD Camera                          | 4         | 5.13%   |
| Microdia Integrated_Webcam_HD                 | 3         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 3.85%   |
| IMC Networks Integrated Camera                | 3         | 3.85%   |
| Chicony USB2.0 Camera                         | 3         | 3.85%   |
| Chicony HD Webcam                             | 3         | 3.85%   |
| Bison SunplusIT Integrated Camera             | 3         | 3.85%   |
| Syntek Integrated Camera                      | 2         | 2.56%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.56%   |
| Realtek Integrated_Webcam_HD                  | 2         | 2.56%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 2.56%   |
| Chicony Integrated IR Camera                  | 2         | 2.56%   |
| Bison EasyCamera                              | 2         | 2.56%   |
| Apple FaceTime HD Camera                      | 2         | 2.56%   |
| Unknown (3730304233333731323245) USB Camera   | 1         | 1.28%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.28%   |
| Sunplus HD WebCam                             | 1         | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 1.28%   |
| Realtek USB Camera                            | 1         | 1.28%   |
| Realtek Lenovo EasyCamera                     | 1         | 1.28%   |
| Realtek Integrated Webcam HD                  | 1         | 1.28%   |
| Realtek Integrated Webcam                     | 1         | 1.28%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 1.28%   |
| Quanta HP Wide Vision HD Camera               | 1         | 1.28%   |
| Polycom Poly Studio P5 webcam                 | 1         | 1.28%   |
| Pixart Imaging USB_2.0_Webcam                 | 1         | 1.28%   |
| Microdia Lenovo EasyCamera                    | 1         | 1.28%   |
| Microdia Integrated Webcam HD                 | 1         | 1.28%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 1.28%   |
| IMC Networks Integrated RGB Camera            | 1         | 1.28%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 1         | 1.28%   |
| Chicony USB2.0 UVC WebCam                     | 1         | 1.28%   |
| Chicony USB2.0 0.3M UVC WebCam                | 1         | 1.28%   |
| Chicony USB 2.0 Camera                        | 1         | 1.28%   |
| Chicony Lenovo EasyCamera                     | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 40.91%  |
| Validity Sensors           | 6         | 27.27%  |
| Shenzhen Goodix Technology | 5         | 22.73%  |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 13.64%  |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 13.64%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 4.55%   |
| Validity Sensors Synaptics WBDI                           | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 4.55%   |
| Synaptics UWP WBDI Device                                 | 1         | 4.55%   |
| Synaptics TouchPad                                        | 1         | 4.55%   |
| Synaptics  WBDI                                           | 1         | 4.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 4.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 4.55%   |
| Shenzhen Goodix FingerPrint                               | 1         | 4.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                     | 1         | 4.55%   |
| Unknown                                                   | 1         | 4.55%   |

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
| 0     | 52        | 57.14%  |
| 1     | 27        | 29.67%  |
| 2     | 9         | 9.89%   |
| 3     | 2         | 2.2%    |
| 6     | 1         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 40.38%  |
| Graphics card            | 6         | 11.54%  |
| Net/wireless             | 5         | 9.62%   |
| Chipcard                 | 5         | 9.62%   |
| Communication controller | 4         | 7.69%   |
| Multimedia controller    | 3         | 5.77%   |
| Camera                   | 3         | 5.77%   |
| Sound                    | 2         | 3.85%   |
| Card reader              | 2         | 3.85%   |
| Bluetooth                | 1         | 1.92%   |

